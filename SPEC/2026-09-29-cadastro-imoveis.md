# Cadastro e Listagem de Imóveis (2026-09-29)

## O quê e por quê
O proprietário precisa poder cadastrar seu imóvel no sistema para que ele fique visível nas buscas dos locatários. É a funcionalidade central que alimenta o inventário da plataforma.

## Critérios de aceitação
- O formulário de cadastro exige título, descrição, endereço completo, capacidade máxima de pessoas e valor da diária.
- Um imóvel recém-cadastrado entra com status "Ativo" por padrão.
- O sistema impede o cadastro de um imóvel com valor de diária negativo ou zero.
- A lista de imóveis na página inicial exibe apenas propriedades com status "Ativo".
- A listagem exibe a foto principal, título, distrito e preço por noite.

## Fora do escopo
- Upload de galerias de múltiplas imagens (nesta etapa, usaremos apenas URLs de imagens externas para simplificar).
- Edição ou exclusão de imóveis (será tratado em uma spec futura).
- Sistema de avaliação por estrelas.
