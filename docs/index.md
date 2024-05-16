<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>


<font size="+12"><center>
Sistema de Presenças
</center></font>

**Conteúdo**
- [Autores](#nome-alunos)
- [Descrição do Projeto](#introdução-do-projeto)
- [Análise de Requisitos Funcionais e Não-Fucionais](#descrição-dos-requisitos)
- [Diagrama de Atividades](#diagrama-de-atividades) 
- [Diagrama de Casos de Uso](#diagrama-de-comportamento-atores)
- [Descrição dos Casos de Uso](#descrição-das-funcões)
- [Diagrama de Senquencia](#diagrama-de-ordem-interações)
- [Diagrama de Classes](#diagrama-orientado-objetos)
- [Diagrama de Estados](#diagrama-estrutura-componente)
- [Diagrama de Implantação](#diagrama-de-hardware-software)
- [Referências](#referências)


# Autores
* Arthur Lima (10409172)
* Cláudio Dias Alves (10403569)
* Gabriel Nogueira (10409493)
* Guillermo Kuznietz (10410134)
* Lucas Claudio (10410094)


# Descrição do Projeto
O projeto da **Escola INFINITO** tem como objetivo desenvolver um **Sistema de Presenças** para automatizar o controle de frequência dos alunos. Atualmente, essa operação é realizada manualmente em papel, o que demanda tempo e recursos. O sistema permitirá o registro fácil e intuitivo das faltas pelos professores, gerará relatórios detalhados e enviará notificações aos pais ou responsáveis quando a porcentagem de comparecimento às aulas estiver abaixo de 80%. Além disso, garantiremos acessibilidade e compatibilidade com diversos navegadores e dispositivos móveis.


# Análise de Requisitos Funcionais e Não-Funcionais
<h3>Requisitos funcionais</h3>
<h4>RF01 - Registro de Faltas:</h4>
<ul>
  <li>Permitir que os professores registrem faltas de forma fácil e intuitiva.
  <li>Os professores devem poder indicar a data, turma, aluno e motivo da falta.
</ul>
<h4>RF02 - Relatórios de Faltas:</h4>
<ul>
  <li>Gerar relatórios de faltas com as seguintes opções de agrupamento: por data; por ano do ensino; por turma; por professor; por disciplina; por aluno.
  <li>Esses relatórios facilitarão a análise e o acompanhamento do número de faltas.
</ul>
<h4>RF03 - Funções requisitadas:</h4>
<ul> 
<li>Acessibilidade para pessoas de necessidade
<li>Sistema de notificação
</ul>

<h3>Requisitos não funcionais</h3>
<h4>RNF01 - Usabilidade</h4>
<ul>
  <li>Facilidade de aprender e usar
  <li>Função de ajuda ou dúvidas
</ul>
<h4>RNF02 - Manutenção e Confiabilidade</h4>
<ul>
  <li>Reparo e evolução do sistema
  <li>Assistência técnica
  <li>Margem de erro
</ul>
<h4>RNF03 - Segurança</h4>
<ul>
  <li>Sistema de backup de dados
  <li>Verificação dupla
  <li>Restrições do usuário
  <li>Recuperação de senha
</ul>
<h4>RNF04 - Requisitos legais e éticos</h4>


# Diagrama de Atividades

![Diagrama_AtividadeAT](https://github.com/Grupo-ProjSoft/ProjSoft-Classroom/assets/161867289/37564436-7104-4cf0-bc50-69cb7656a1d1)

# Diagrama de Casos de Uso

![Diagrama_caso_de_uso](https://github.com/Grupo-ProjSoft/ProjSoft-Classroom/assets/161867289/7d102b79-4149-49a3-b4a9-02403802556d)

# Descrição dos Casos de Uso

<li> Enviar Notificação (Sistema): Este caso de uso envolve o sistema enviando automaticamente notificações por e-mail para os pais ou responsáveis quando a porcentagem de presença de um aluno nas aulas cai abaixo de 80%.
<li>Gerar Relatório de Faltas (Pessoa): Este caso de uso permite que uma pessoa (que pode ser um professor ou membro da secretaria) gere um relatório de faltas. O relatório pode ser agrupado por data, ano do ensino, turma, professor, disciplina ou aluno.
<li>Efetuar Login (Pessoa): Este caso de uso permite que um aluno faça login no sistema.
<li>Alterar Senha (Pessoa): Este caso de uso permite que uma pessoa altere sua senha no sistema. Observe que a linha é pontilhada e a seta aponta para o caso de uso primário, no caso, seria efetuar login.
<li>Gerenciar Informações do Aluno (Secretária): Este caso de uso permite que uma secretária gerencie as informações dos alunos no sistema.
<li>Gerenciar Informações do Professor (Secretário): Este caso de uso permite que uma secretária gerencie as informações dos professores no sistema.
<li>Gerenciar Informações da Turma (Secretaria): Este caso de uso permite que a secretaria gerencie as informações da turma no sistema.
<li>Professor Disciplina Principal (Professor): Define o professor responsável por várias disciplinas de uma turma (Matemática, Português, Artes, Ciências, História e Geografia).
<li>O Professor Disciplina Específica (Professor): Define o professor responsável por várias disciplinas de uma turma específicas (Educação Física ou Inglês).
<li>Registrar Faltas (Professor): Este caso de uso permite que o professor registre as faltas dos alunos.
<li>Atualizar Informações Pessoais (Professor): Este caso de uso permite que o professor atualize suas informações pessoais no sistema.
<li>Atualizar Informações Pessoais (Aluno): Este caso de uso permite que o aluno atualize suas informações pessoais no sistema.

# Diagrama de Sequência

*&lt;Diagrama de ordem e interação dos objetos&gt;*

# Diagrama de Classes

*&lt;Diagrama de relacionamento entre classes para os seus atributos e operações&gt;*

# Diagrama de Estados

*&lt;Diagrama para permite modelar o comportamento interno de um determinado objeto, subsistema ou sistema global&gt;*

# Diagrama de Implantação

*&lt;Diagrama para exibir o relacionamento de hardware e software no projeto&gt;*

# Referências

<li> https://graduacao.mackenzie.br/pluginfile.php/252766/mod_resource/content/1/aula-uml-atividades.pdf
<li> https://graduacao.mackenzie.br/pluginfile.php/252963/mod_resource/content/1/Casos-De-Uso.pdf
<li> https://graduacao.mackenzie.br/pluginfile.php/252965/mod_resource/content/1/EngenhariaSoftware_Requisitos01.pdf
<li> https://graduacao.mackenzie.br/pluginfile.php/252980/mod_resource/content/1/EngenhariaSoftware_Requisitos02.pdf
