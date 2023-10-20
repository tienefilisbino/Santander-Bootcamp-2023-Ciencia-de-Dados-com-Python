REDME
Relatório dos ajustes feitos.

Diretrizes para transformação dos dados

1.Verifique os cabeçalhos e tipos de dados
	VERIFICADO

2.Modifique os valores monetários para o tipo double preciso.
	MODIFICADO

3.Verifique a existência dos nulos e analise a remoção
	CELULAS NULL REMOVIDAS

4.Os employees com nulos em Super_ssn podem ser os gerentes. Verifique se há algum colaborador sem gerente
	VERIFICADO. VALOR ATRIBUIDO: 000000000
5.Verifique se há algum departamento sem gerente
	APENAS 1

6.Se houver departamento sem gerente, suponha que você possui os dados e preencha as lacunas
	VALOR ATRIBUIDO:000000000

7.Verifique o número de horas dos projetos.
	VERIFICADO
8.Separar colunas complexas.
	FEITO
9.Mesclar consultas employee e departament para criar uma tabela employee com o nome dos departamentos 
  associados aos colaboradores. A mescla terá como base a tabela employee. Fique atento, essa informação influencia no tipo de junção
	FEITO. CRIADA NOVA TABELA DE NOME: MESCLA-EMPLOYEE-DEPARTAMENTO
10.Neste processo elimine as colunas desnecessárias. 
	FEITO
11.Realize a junção dos colaboradores e respectivos nomes dos gerentes. 
   Isso pode ser feito com consulta SQL ou pela mescla de tabelas com Power BI. 
   Caso utilize SQL, especifique no README a query utilizada no processo.
	FEITO
12.Mescle as colunas de Nome e Sobrenome para ter apenas uma coluna definindo os nomes dos colaboradores.
	FEITO

13.Mescle os nomes de departamentos e localização. Isso fará que cada combinação departamento-local seja único. 
   Isso irá auxiliar na criação do modelo estrela em um módulo futuro.
	FEITO

14.Explique por que, neste caso supracitado, podemos apenas utilizar o mesclar e não o atribuir. 
	ELIMINAR REDUNDÂNCIA.

15.Agrupe os dados a fim de saber quantos colaboradores existem por gerente
	4 COLABORADORES NO DEPT Dno 5
	1 COLABORADORES NO DEPT Dno 1
	3 COLABORADORES NO DEPT Dno 4

16.Elimine as colunas desnecessárias, que não serão usadas no relatório, de cada tabela.
	ELIMINADO

