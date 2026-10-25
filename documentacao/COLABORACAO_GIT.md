# Colaboração e controle de versão

## Fluxo
`main` como base pública; criar `feat/descricao` ou `fix/descricao` para alterações; abrir issue quando relevante; fazer commits específicos; abrir Pull Request; revisar código e segurança; aprovar e integrar.

## Comandos úteis
```bash
git clone https://github.com/BrenoLSouza/PortfolioHUB.git
cd PortfolioHUB
git checkout -b feat/melhoria-pagina
git add .
git commit -m "feat: melhora seção projetos"
git push -u origin feat/melhoria-pagina
```

## Permissões
Atribuir acesso pela tela Settings do GitHub; para contribuições externas preferir fork + PR. Publicar o site não dá permissão de escrita ao repositório.

## Revisão de PR
- [ ] Testes manuais realizados
- [ ] Sem segredos ou dados pessoais privados
- [ ] Links verificados e sem conteúdo perigoso
- [ ] Documentação atualizada
- [ ] Responsividade e acessibilidade verificadas
