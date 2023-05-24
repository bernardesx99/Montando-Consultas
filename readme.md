# Desafio de Banco de Dados - Trilha .NET da DIO
Este repositório contém as consultas em SQL realizadas como parte do desafio de projeto da trilha .NET da DIO (Digital Innovation One) sobre Banco de Dados.

## Descrição do Desafio
O desafio consiste em realizar consultas no banco de dados de um site de filmes, onde são armazenados dados sobre os filmes e seus atores. O objetivo é obter informações específicas através de consultas SQL.

## Estrutura do Banco de Dados
O banco de dados utilizado está modelado com as seguintes tabelas:

- Filmes: Armazena informações dos filmes.
- Atores: Armazena informações dos atores.
- Generos: Armazena os gêneros dos filmes.
- ElencoFilme: Representa o relacionamento entre filmes e atores.
- FilmesGenero: Representa o relacionamento entre filmes e gêneros.

## Preparação do Banco de Dados
Para executar as consultas, é necessário preparar o banco de dados. Siga as etapas abaixo:

- Execute o arquivo "Script Filmes.sql" em um banco de dados SQL Server.
- O script criará um banco de dados chamado "Filmes" com as tabelas e dados necessários.

## Consultas Disponíveis
Aqui estão as consultas realizadas no desafio, cada uma retornando um tipo de informação:

- Buscar o nome e ano dos filmes.
- Buscar o nome e ano dos filmes, ordenados por ordem crescente pelo ano.
- Buscar o filme "De Volta para o Futuro", trazendo o nome, ano e duração.
- Buscar os filmes lançados em 1997.
Buscar os filmes lançados APÓS o ano 2000.
- Buscar os filmes com duração maior que 100 e menor que 150, ordenando pela duração em ordem crescente.
- Buscar a quantidade de filmes lançados por ano, agrupando por ano e ordenando pela duração em ordem decrescente.
- Buscar os atores do gênero masculino, retornando o PrimeiroNome e UltimoNome.
- Buscar os atores do gênero feminino, retornando o PrimeiroNome, UltimoNome e ordenando pelo PrimeiroNome.
- Buscar o nome do filme e o gênero.
- Buscar o nome do filme e o gênero do tipo "Mistério".
- Buscar o nome do filme e os atores, trazendo o PrimeiroNome, UltimoNome e seu Papel.
## Como Utilizar
- Clone este repositório em sua máquina local.
- Execute as consultas no seu banco de dados SQL Server.
- Analise os resultados obtidos para cada consulta.