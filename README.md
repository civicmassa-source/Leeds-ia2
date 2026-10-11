# Leeds.IA
Painel particular para gerar sites com IA e buscar negócios via Google Places API.

## Variáveis de ambiente obrigatórias
- `LEEDS_PASSWORD`: sua senha privada de acesso.
- `SESSION_SECRET`: segredo longo e aleatório para sessões.
- `OPENAI_API_KEY`: chave da API OpenAI para criar sites.
- `GOOGLE_PLACES_API_KEY`: chave da Google Places API para o buscador de leads.
- `NODE_ENV=production` ao publicar em hospedagem HTTPS.
- `OPENAI_MODEL` (opcional; padrão `gpt-4.1-mini`).

Não coloque chaves em arquivos do projeto nem as envie no chat. APIs e hospedagem podem ter custos.

## Publicação
Hospede em um serviço compatível com Node.js 18+. Comandos de build não são necessários; comando de início: `npm start`. Adicione todas as variáveis acima nas configurações de ambiente do serviço. Ative Places API (New) e restrinja a chave do Google à API necessária. Mantenha o repositório privado.
