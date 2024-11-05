1. Objetivo do Projeto
Criar uma aplicação web para o setor de compras que gerencie listas de produtos e seus componentes, registre o histórico de compras, controle o estoque e forneça previsões sobre prazos de reposição de matéria-prima.

2. Principais Funcionalidades
Cadastro e Gerenciamento de Produtos e Componentes

Criar, visualizar, editar e excluir produtos e seus componentes.
Cada produto terá uma lista de componentes associada.
Registro de Ordens de Compra

Registrar ordens de compra para cada componente, incluindo datas, quantidades e preços.
Calcular e atualizar o preço médio de cada componente com base nas compras.
Controle de Estoque

Integrar dados de estoque, como quantidade atual e local de armazenamento.
Gerar alertas para reposição de componentes baseados no estoque mínimo e nos prazos de entrega.
Previsão e Planejamento de Compras

Fornecer uma previsão de prazos para solicitar novos componentes, considerando o histórico de compra e o tempo de entrega usual.
Gerar relatórios de previsão e análise para tomada de decisão.
3. Tecnologias Utilizadas
Backend: Python (Django)
Banco de Dados: PostgreSQL
Frontend: HTML, CSS, JavaScript (ou um framework como React, dependendo do que preferir para a interface)
Ambiente de Desenvolvimento: Pode ser configurado com o Docker para facilitar a portabilidade e o setup do projeto.
4. Estrutura do Projeto
Módulo de Produtos: Funcionalidade para gerenciar produtos e suas listas de componentes.
Módulo de Ordens de Compra: Registro e consulta de ordens de compra por componente.
Módulo de Estoque: Controle de quantidades, localização e status de estoque.
Módulo de Relatórios: Geração de relatórios para previsões e histórico de compras.
5. Etapas de Desenvolvimento
Etapa 1: Configuração do Ambiente de Desenvolvimento
Etapa 2: Configuração do Banco de Dados e Modelagem das Tabelas
Etapa 3: Desenvolvimento do Backend com Django
Criação dos modelos para Produtos, Componentes, Ordens de Compra, Estoque.
Etapa 4: Desenvolvimento do Frontend
Criar uma interface inicial para gerenciar produtos e ordens de compra.
Etapa 5: Integração de Funcionalidades de Estoque e Previsão
Implementar lógica para cálculos de estoque e alertas de reposição.
Etapa 6: Testes e Validações
Etapa 7: Documentação e Finalização
