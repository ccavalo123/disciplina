# Modelagem do banco de dados 
Repositório para trabalho de banco de dados

<div align = "center">
<img src= "maneleclara.logico1.png">
</div>

# Descrição das tabelas do modelo

<h2>Tabela <i>histórico</i></h2>
A tabela <i>histórico</i> descreve dentro no modelo relacional elaborado, onde e quais atributos iremos manter no banco
sobre nosso sistema.
Nela possuímos quatro chaves estrangeiras e elas são:
<ul>
 <li>fk_alunos_mat: chave estrangeira que faz referência a tabela <b>aluno</b></li>
 <li>fk_turma_cod_turma: chave estrangeira que faz referência a tabela <b>turma</b></li>
 <li>fk_disciplina_cod_disciplina: chave estrangeira que faz referência a tabela <b>disciplina</b></li>
 <li>fk_professor_cod_professor: chave estrangeira que faz referência a tabela <b>professor</b></li>
</ul>
Já os atributos/colunas são:
<ul>
<li>mat</li>
<li>cod_disc</li>
<li>cod_turma</li>
<li>cod_prof</li>
<li>ano</li>
<li>frequência</li>
<li>nota</li>

</ul>

