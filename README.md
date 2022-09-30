# Avaliação de Banco de Dados
## Descrição do trabalho

[PDF de Instrução utlizada para a efetuação da prova, acesse aqui.](AtividadeAvaliativa.pdf) 

# Mapa Conceitual:
![](Conceitual_1.png)

# Mapa Lógico:
![](Lógico_1.png)

<h2>Tabela <i>Aluno_Historico</i></h2>
A tabela <i>Aluno_Historico</i> é a tabela responsavel por guardar os dados do aluno e seus historicos diretamente relacionados
Nela possuímos os atributos/colunas:
<ul>
  <li>mat: matricula e chave primária da tabela</li>
  <li>id: indentificador do historico do aluno e chave primaria</li>
  <li>nome: nome do aluno.</li>
  <li>endereco: endereço do aluno ,aonde o aluno mora</li>
  <li>cidade: cidade onde o aluno esta</li>
  <li>frequencia: numero de faltas de um aluno </li>
  <li>nota: nota avaliatica do aluno</li>
  <li>fk_turma_cod_turma: chave estrangeira que faz referência a tabela <i>turma</i></li>
  <li>fk_turma_ano: chave estrangeira que faz referência a tabela <i>turma</i></li>
  <li>fk_turma_cod_prof: chave estrangeira que faz referência a tabela <i>professor</i></li>
  <li>fk_turma_cod_disc: chave estrangeira que faz referência a tabela <i>disciplina</i></li>
</ul>

<h2>Tabela <i>turma</i></h2>
A tabela <i>turma</i> é a tabela responsavel por guardar as informações relacionada a uma turma da universidade
Nela possuímos os atributos/colunas:
<ul>
  <li>cod_turma: codigo da turma e a chave primaria da tabela</li>
  <li>ano: ano em que a turma cursou a universidade e chave primaria</li>
  <li>horario: horario em que a turma tera as suas aulas</li>
</ul>

<h2>Tabela <i>professor</i></h2>
A tabela <i>professor</i> é a tabela responsavel por guardar os dados do professor 
Nela possuímos os atributos/colunas:
<ul>
  <li>cod_prof: codigo do professor e a chave primaria da tabela</li>
  <li>nome: nome do professor</li>
  <li>endereco: endereco do professor, aonde o professor mora</li>
  <li>cidade: cidade onde o professor esta</li>
  
</ul>

<h2>Tabela Relacional <i>turm_profess</i></h2>
A tabela <i>turm_profess</i> é a tabela de relacionamento entre a tabela turma e a tabela professor
<ul>
   <li>fk_turma_cod_turma: chave estrangeira que faz referência a tabela <i>turma</i>      </li>
  <li>fk_turma_ano: chave estrangeira que faz referência a tabela <i>turma</i></li>
  <li>fk_professor_cod_prof: chave estrangeira que faz referência a tabela <i>professor</i></li>
</ul>

<h2>Tabela <i>disciplina</i></h2>
A tabela <i>disciplina</i> é a tabela aonde se guarda os dados da disciplina a ser cursada pelo os <i>alunos</i>
<ul>
   <li>cod_disc: indentificação da disciplina e chave primaria </li>
  <li>nome_disc: o nome da disciplina que sera cursada></li>
  <li>carga_hora: carga horaria da disciplina cursada</li>
</ul>

<h2>Tabela Relacional <i>turm_profess</i></h2>
A tabela <i>turm_profess</i> é a tabela de relacionamento entre a tabela turma e a tabela disciplina
<ul>
   <li>fk_turma_cod_turma: chave estrangeira que faz referência a tabela <i>turma</i>      </li>
  <li>fk_turma_ano: chave estrangeira que faz referência a tabela <i>turma</i></li>
  <li>fk_disciplina_cod_disc: chave estrangeira que faz referência a tabela <i>disciplina</i></li>
</ul>



