# Política de segurança — PortfolioHUB
**Escopo:** GitHub, serviços Google e site estático. **Natureza:** guia de medidas recomendadas; não implica certificação ISO, auditoria de LGPD ou aplicação automática.

1. **Identidade e acesso:** habilitar 2FA nas contas; não compartilhar senhas; acesso mínimo necessário a repositórios e pastas; remoção de acesso quando não mais necessário.
2. **Credenciais:** proibir tokens, senhas, arquivos `.env` e chaves privadas no repositório; usar secrets do GitHub Actions apenas quando realmente necessários. Em suspeita de vazamento, revogar imediatamente.
3. **Visibilidade:** publicar apenas projetos e documentos autorizados; validar compartilhamento do Google Drive; não publicar informações pessoais de terceiros.
4. **Versionamento:** usar branches de funcionalidade, commits claros, revisão por PR, regras de proteção de branch conforme plano GitHub e permissões efetivas.
5. **Integridade:** atualizar dependências quando existirem; utilizar links HTTPS; considerar verificações automatizadas de código; revisar scripts e contribuições externas.
6. **Disponibilidade:** manter cópias/versionamento do código e PDFs; documentar restauração via clone do GitHub; acompanhar indisponibilidades das APIs externas.
7. **Incidentes:** identificar evento; interromper divulgação ou acesso indevido; revogar credenciais; corrigir exposição; registrar evidências e comunicar interessados conforme aplicável.
8. **Privacidade/LGPD:** minimizar coleta; o front-end próprio não solicita nome, email, senha ou cookies de rastreamento; a chamada à API do GitHub e recursos externos seguem as políticas de seus provedores.
9. **Referenciais:** LGPD, recomendações de gestão de riscos do NIST CSF e princípios da ISO/IEC 27001 como referências de boas práticas, sem afirmar conformidade certificada.
10. **Gemini:** utilizar como apoio à revisão do checklist e análise de riscos. Não enviar senhas, tokens ou dados pessoais confidenciais aos prompts.

**Modelo de permissões sugerido:** proprietário (admin do repositório), colaborador (acesso de escrita quando aprovado), visitante (leitura de repositórios públicos). Os papéis são controlados pelo GitHub, **não** pelo site.
