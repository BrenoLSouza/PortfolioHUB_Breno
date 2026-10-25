# Plano de testes / registro de evidências

| ID | Cenário | Resultado esperado | Situação |
|---|---|---|---|
| T01 | Abrir `docs/index.html` | Sem erros de sintaxe; exibe hero e menus | A validar em navegador |
| T02 | Clique nas âncoras | Navega para a seção correspondente | A validar |
| T03 | Busca por nome de projeto | Filtra cards | A validar |
| T04 | Ordenação | Reordena itens | A validar |
| T05 | Consulta à API pública | Mostra repositórios públicos | A validar com internet |
| T06 | API indisponível | Mensagem clara + cartões alternativos | A validar |
| T07 | Tema claro/escuro | Alternância visual | A validar |
| T08 | Tela estreita (mobile) | Sem rolagem horizontal indevida | A validar |
| T09 | Links GitHub/Google | Abrem serviços oficiais | A validar |
| T10 | Navegação por teclado | Foco e skip link funcionam | A validar |
| T11 | Página publicada | URL do GitHub Pages abre com HTTPS | Depende de publicação |
| T12 | Colaboradores/regras | Permissões verificadas no GitHub | Depende de conta |

**Evidência mínima:** registrar capturas datadas do site, terminal `git log`, URL GitHub, Settings/Pages, execução manual T01–T12, sessão do Gemini e link do vídeo no YouTube. Não transformar testes pendentes em aprovados sem executar.
