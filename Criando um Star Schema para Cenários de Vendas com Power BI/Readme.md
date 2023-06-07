# Passo a Passo da criação do Star Schema

 1. **Criado a tabela F_Professor**
		 Definidas as Colunas Professor, Departamento, Disciplina, Curso e Liberação da disciplina
		 
 2. **Criado a tabela D_Disciplina**
		 Definidas as Colunas Disciplina e Curso
		 
 3. **Criado a tabela D_professor**
		Definidas as Colunas Professor e Departamento
 4.**Criado a tabela Calendario**
		 Definidas as Colunas de data com base na coluna Liberação da disciplina da tabela F_professor
		 
 4. **Feito o relacionamento entre as tabelas D_Disciplina, D_professor , Calendario com a tabela F_Professor**
