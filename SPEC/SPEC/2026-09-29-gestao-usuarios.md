# Gestão de Usuários e Perfis (2026-09-29)

## O quê e por quê
A plataforma atende a dois públicos distintos: quem quer alugar um imóvel para temporada e quem quer anunciar o seu. O sistema precisa registrar e diferenciar esses papéis (Locador e Locatário) no momento do cadastro para exibir as telas e permissões corretas.

## Critérios de aceitação
- O formulário de registro exige nome, e-mail, senha e a escolha de um papel: "Locador" ou "Locatário".
- O sistema deve impedir o cadastro de um e-mail que já existe no banco de dados.
- As senhas devem ser armazenadas com hash (nunca em texto puro).
- Após o login, um usuário "Locador" é redirecionado para a rota `/dashboard` (Painel de Imóveis).
- Após o login, um usuário "Locatário" é redirecionado para a rota `/busca` (Catálogo de Imóveis).
- Rotas protegidas devem bloquear o acesso de usuários não autenticados.

## Fora do escopo
- Fluxo de "Esqueci minha senha" (recuperação por e-mail).
- Login social (Google, GitHub, etc).
- Edição dos dados do perfil.
