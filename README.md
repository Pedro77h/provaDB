# Avaliação de Banco de Dados
## Descrição do trabalho

[PDF de Instrução utlizada para a efetuação da prova, acesse aqui.](AtividadeAvaliativa.pdf) 

# Mapa Conceitual:
![](Conceitual_1.png)

# Mapa Lógico:
![](Lógico_1.png)

<h2>Tabela <i>Aluno_Historico</i></h2>
A tabela <iAluno_Historico</i> é a tabela responsavel por guardar os dados do aluno e seus historicos diretamente relacionados
Nela possuímos os atributos/colunas:
<ul>
  <li>mat: matricula e chave primária da tabela</li>
  <li>id: indentificador do historico do aluno e chave primaria</li>
  <li>nome: nome do aluno.</li>
  <li>endereço: endereço do aluno ,aonde o aluno mora</li>
  <li>cidade: cidade onde o aluno esta</li>
  <li>frequencia: numero de faltas de um aluno </li>
  <li>nota: nota avaliatica do aluno</li>
  <li>fk_turma_cod_turma: chave estrangeira que faz referência a tabela <i>turma</i></li>
  <li>fk_turma_ano: chave estrangeira que faz referência a tabela <i>turma</i></li>
  <li>fk_turma_cod_prof: chave estrangeira que faz referência a tabela <i>professor</i></li>
  <li>fk_turma_cod_disc: chave estrangeira que faz referência a tabela <i>disciplina</i></li>
</ul>

<h2>Tabela <i>turma</i></h2>
A tabela <iAluno_Historico</i> é a tabela responsavel por guardar os dados do aluno e seus historicos diretamente relacionados
Nela possuímos os atributos/colunas:
<ul>
  <li>cod_turma: codigo da turma e a chave primaria da tabela</li>
  <li>ano: ano em que a turma cursou a universidade e chave primaria</li>
  <li>horario: horario em que a turma tera as suas aulas</li>
</ul>



