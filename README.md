# Desafio do Primeiro dia do 7 days of Code | Python Pandas:

### 1. Importação dos dados:
- Empréstimos dos acervos da biblioteca de UFRN

- Por conta de ter vários arquivos de empréstimos, realizei uma estrutura com o laço 'for' para ficar mais simples e limpo a importação.
    
- Exemplares do Acervo
    

### 2. Concatenar os dois Dataframes

### 3. Remoção das de linhas duplicadas


# Desafio do Segundo dia do 7 days of Code | Python Pandas:

### 1. Inserção da coluna CDU

### 2. Exclusão da coluna "registro_sistema" 

### 3. Alteração do tipo de dado da coluna de matrícula

### Alteração do tipo de dado da coluna de matrícula


# Desafio do Terceiro dia do 7 days of Code | Python Pandas:

### Verificar a quantidade total de exemplares emprestados por cada ano e plote um gráfico de linhas.

- Verificar a quantidade total, por ano, mês e hora do dia.

### Realizar uma análise de cada gráfico gerado


# Desafio do Quarto dia do 7 days of Code | Python Pandas:

### Exploração de variáveis categóricas
- Tipo de vínculo;

- Coleção;

- Biblioteca;

- Classificação geral da CDU;

### Como se distribuem os empréstimos de exemplares pelos tipos de vínculo dos usuários?

### Quais coleções são mais emprestadas?

### Quais são as bibliotecas com mais ou menos quantidade de empréstimos?

### De quais temas da CDU são os exemplares emprestados?


# Desafio do Quinto dia do 7 days of Code | Python Pandas:

### Avaliação da distribuição de empréstimos mensais por ano, realizados ente 2010 e 2020 da coleção que tiver a maior frequência de empréstimos. Referente os vínculos:
- Alunos de Graduação;

- Alunos de Pós-Graduação;


# Desafio do Sexto dia do 7 days of Code | Python Pandas:

### Calcular a quantidade de empréstimos realizados entre 2015 e 2020 por cada curso de graduação que passará pela avaliação.

### Cursos requisitados para análise:
- Biblioteconomia
- Ciências sociais
- Comunicação social
- Direito
- Filosofia
- Pedagogia

Também foi realizado a junção de duas novas tabelas de cadastro de alunos em dois formatos diferentes:
- .json
- Excel (.xlsx)

No final, uma tabela foi gerada com as seguintes informações:
- Índice: Cursos
- Colunas: Ano
- Valores: Quantidade de empréstimos
- Total: Total de empréstimos por ano


# Desafio do Sétimo dia do 7 days of Code | Python Pandas:

### Analisar a diferença percentual de empréstimos dos últimos anos relacionado com os alunos de pós-graduação, para cada curso.

* Devido à pandemia do COVID-19, não será requisitado os danos de 2020 e 2021

### Criação de uma tabela com as diferenças percentuais de empréstimos dos anos:
- 2017-2018
- 2018-2019
- 2019-2022

Para o cálculo dos percentuais, foi utilizado a fórmula da variação:

* Variação = ((v_final - v_inicial) / v_inicial) * 100

### Criação do arquivo HTML com a tabela dos percentuais criado, com as seguintes características:
- Sem numeração de índice
- Nomes dos cursos somente com a primeira letra em maiúsculo
- Os números dos percentuais estejam indicados pelo símbolo "%"
- Números positivos na cor verde e negativos na cor vermelha