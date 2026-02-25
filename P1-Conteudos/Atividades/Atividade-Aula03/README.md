Atividade – Aula 03
DER – Sistema de Aluguel de Carros
Descrição

Desenvolvimento de um Diagrama Entidade-Relacionamento (DER) para um sistema de aluguel de carros, conforme os requisitos propostos em aula.

Entidades

Cliente

id_cliente (PK)

nome

cpf

Carro

id_carro (PK)

modelo

placa

Aluguel

id_aluguel (PK)

id_cliente (FK)

id_carro (FK)

data_inicio

data_fim_prevista

data_fim_real

Relacionamentos

Um Cliente pode realizar vários Aluguéis (1:N).

Um Carro pode estar associado a vários Aluguéis (1:N).

As chaves estrangeiras estão definidas na entidade Aluguel.
