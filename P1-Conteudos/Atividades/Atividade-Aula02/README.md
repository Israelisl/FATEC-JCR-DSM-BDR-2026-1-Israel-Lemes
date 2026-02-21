📘 Atividade – Aula 02

Disciplina: Banco de Dados Relacional
Curso: DSM 2 Semestre 1/2026 – FATEC
Aluno: Israel da Silva Lemes

📌 Descrição

Nesta atividade foi criado um banco de dados no PostgreSQL para registrar focos de calor no Brasil.

🛠️ Etapas Realizadas

Criação do banco de dados queimadas_db

Criação da tabela focos_calor

Inserção de registros

Consulta dos dados utilizando SELECT

🗂️ Estrutura da Tabela

Tabela: focos_calor

id → INTEGER (Chave Primária)

estado → VARCHAR(50)

bioma → VARCHAR(50)

data_ocorrencia → DATE

💾 Comandos Utilizados:

create table focos_calor (
    id SERIAL primary key,
    estado VARCHAR(50) not null,
    bioma VARCHAR(50) not null,
    data_ocorrencia DATE not null
);

insert into focos_calor (estado, bioma, data_ocorrencia) values
('Amazonas', 'Amazônia', '2025-02-01'),
('Mato Grosso', 'Cerrado', '2025-02-03'),
('Pará', 'Amazônia', '2025-02-05');

select * from focos_calor;
