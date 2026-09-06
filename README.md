# FALA V8 — versão preparada para publicação

## Estrutura
- `public/index.html` — página pública
- `server.js` — ponto de entrada do backend (a acrescentar/ligar na publicação)
- `vercel.json` — configuração inicial
- `.gitignore` — protege segredos e ficheiros locais

## Publicação
1. Criar um repositório privado no GitHub chamado `fala`.
2. Enviar estes ficheiros para o repositório.
3. Ligar o repositório a uma plataforma de deployment.
4. Configurar as variáveis secretas no servidor.
5. Testar o endereço público.
6. Só depois ligar domínio próprio.

Não colocar `OPENAI_API_KEY` no GitHub nem no HTML.

A documentação oficial do GitHub confirma que um repositório serve para guardar o código e que pode ser criado pela interface web.
