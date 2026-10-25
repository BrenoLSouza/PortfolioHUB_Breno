# PortfolioHUB — Breno Lopes Souza

Projeto acadêmico da entrega final de **Bootcamp I**. Site estático responsivo, em HTML, CSS e JavaScript, preparado para GitHub Pages.

## Funcionalidades
- Apresentação, objetivos, navegação e design adaptável.
- Consulta **somente de repositórios públicos** pela API REST do GitHub (sem token).
- Busca e ordenação no navegador; fallback informativo se a API não responder.
- Atalhos para Google Drive, Docs, Agenda, Gmail e Gemini (**links, não APIs autenticadas**).
- Alternância de tema, marcações semânticas e suporte a navegação por teclado.

## Como executar
Abra `docs/index.html` no navegador (ou sirva `docs/` via Live Server). A consulta de projetos exige internet.

## Publicação no GitHub Pages
1. Crie o repositório `PortfolioHUB` em https://github.com/new, escolha público.
2. No terminal, a partir desta pasta: `git init`; `git add .`; `git commit -m "feat: implanta PortfolioHUB"`; `git branch -M main`; `git remote add origin https://github.com/BrenoLSouza/PortfolioHUB.git`; `git push -u origin main`.
3. No GitHub, acesse **Settings → Pages → Build and deployment → Deploy from a branch** e selecione `main` e `/docs`.
4. O endereço esperado **após você publicar**, se usar esse nome de repositório, é `https://brenolsouza.github.io/PortfolioHUB/`. Verifique-o antes de colocar no PDF.

## Segurança e limites
- O site é público, sem login próprio, banco de dados ou criação de contas.
- A API é consultada sem credenciais. Não armazene tokens ou senhas no repositório.
- Controle de colaboradores é configurado **na interface do GitHub** (Settings → Collaborators / Rulesets conforme permissões disponíveis).
- As integrações Google são **atalhos**: não há OAuth, SSO, sincronização de usuários nem acesso a arquivos privados.
- Regras de proteção e GitHub Pages exigem configuração na conta do autor.
- Use autenticação multifator na conta GitHub e Google; revise permissões de compartilhamento dos documentos.

## Estrutura
- `docs/`: site público.
- `documentacao/`: plano, política de segurança, colaboração, prompts e testes.
- `.github/workflows/`: validação automatizada simples.
- `Relatorio_Final_PortfolioHUB_Breno.pdf`: relatório acadêmico para completar com evidências reais.

## Licença
Material educacional. Documentos e textos autorais preparados como base para apresentação e adaptação.
