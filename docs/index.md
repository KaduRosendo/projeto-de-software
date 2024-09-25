<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>


<font size="+12"><center>
*&lt;Nome do Projeto&gt;*
</center></font>

>*Observação 1: A estrutura inicial deste documento é só um exemplo. O seu grupo deverá alterar esta estrutura de acordo com o que está sendo solicitado na disciplina.*

>*Observação 2: O índice abaixo não precisa ser editado se você utilizar o Visual Studio Code com a extensão **Markdown All in One**. Essa extensão atualiza o índice automaticamente quando o arquivo é salvo.*

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

* Carlos Eduardo 
* Guilerme Gomes
* Henrique Pena
* João Pedro Gianfaldoni
* Matheus Brito


# Descrição do Projeto

*O intuito do projeto é, principalmente, desenvolver um sistema integrado de faltas para a escola do infinito, visando facilitar o acompanhamento de alunos e professores nesse sistema. É importante facilitar o acesso de outros usuários por meio de ferramentas gerais de acessibilidade, como a cor da página da web, o tamanho da fonte, entre outros.*

*O objetivo é disponibilizar um registro de faltas fácil e intuitivo, acompanhado de um gerador de relatórios que possua filtros e campos de busca para propiciar análises detalhadas do número de faltas agrupadas por data, ano de ensino, turma, professor, entre outros.*

*Além disso, será essencial um sistema de notificações por e-mail para informar pais e/ou responsáveis.*

# Análise de Requisitos Funcionais e Não-Funcionais
## Funcionais:

- Selecionar aluno que faltou;

- Confirmar o envio das faltas para o sistema

- Relatório de faltas no sistema

- Cada aluno possuir um sistema para verificar notas e faltas 

- Enviar notificações aos responsavels se ultrapassar o limite de faltas

- Funcionalidades de acessibilidade

## Não-Funcionais:

Requisitos não funcionais 

- O sistemas deve ser capaz de processar um alto núnero de presenças por segundo 

- Todos os dados dos alunos e professores devem ser criptografados para maior sefurança 

- O sistemas deve ter um baixo tempo de respostas para as solicitações inferios a 1 segundo 

- O sistemas deve estar sempre disponivel para uso minimizando o tempo de inatividade e garantindo acesso continuo 

- O sistemas deve realizar backups automático dos dados 24 horas e garantir que seja possível a recuperação completa dos dados em caso de falha 

- O sistemas deve estar em comformidade com regulamentações de proteção de dados e privacidade aplicáveis, como LGPD

# Diagrama de Atividades

![EscolaInfinita (1)](https://github.com/user-attachments/assets/34ed9ef3-07ef-4ac3-87ad-4fada141c28b)

# Diagrama de Casos de Uso

![Diagrama sem nome drawio(1)](https://github.com/user-attachments/assets/2f8e3ab5-c713-425d-bac5-85239b9d0fa0)

# Descrição dos Casos de Uso

*&lt;Registrar Falta:

Ator: Professor

Descrição: O professor registra a falta de um determinado aluno em uma aula/dia em dois momentos diferentes.

Fluxo básico:

    O professor acessa a funcionalidade "Registrar Falta".
    O sistema apresenta a lista de turmas e alunos.
    O professor seleciona a turma e o aluno que faltou.
    O professor registra a falta do aluno na data atual.
    O sistema salva a informação de falta registrada.

Relatório de Faltas:

Ator: Professor

Descrição: Gera um relatório com informações consolidadas sobre as faltas.

Fluxo básico:

    O usuário acessa a funcionalidade "Gerar Relatório de Faltas".
    O sistema apresenta acessibilidade de busca (aluno, turma, data, disciplina, professor).
    O usuário seleciona os filtros desejados.
    O sistema gera o relatório de acordo com os filtros.
    O usuário visualiza o relatório de faltas gerado.
    O ususario visuzaliza a porcentagem de falta

Notificação:

Ator:Pais/Responsaveis

Descrição: Envia uma notificação por e-mail aos pais/responsáveis sobre a situação de faltas do aluno.

Fluxo básico:

    O sistema verifica diariamente o percentual de faltas de cada aluno.
    Para alunos com percentual abaixo do limite definido, o sistema automaticamente aciona o caso de uso "Enviar Notificação".
    O sistema busca os dados de e-mail dos pais/responsáveis.
    O sistema envia a notificação por e-mail

Acessibilidae:

Ator: Sistema

Descrição: Permite configurar as opções de acessibilidade e outras configurações do sistema.

Fluxo básico:

    O administrador acessa a tela de configurações do sistema.
    O administrador altera as configurações de fonte, contraste, notificações, entre outras na WEB ou no mobile
    O sistema salva as configurações aplicadas.
    O sistema permite modificar o registro de faltas

Qualquer Site/WEB:

Ator: Professor, Adm Sistema, Pais/Responsaveis

Descrição: Permite configurar as opções de acessibilidade e outras configurações do sistema.

Fluxo básico:

    O administrador acessa a tela de configurações do sistema.
    O administrador coloca todas as faltas no sistema.
    No sistema é possivel visualizar as notificacoes por aplicativo ou pelo site
    Professores e pais podem acessar o site pelo ID do aluno ou ID do professor
    Pais e professores veem a quantidade de falta
    Pais podem justificar a falta dos filhos com atestado
&gt;*

# Diagrama de Sequência

*&lt;Diagrama de ordem e interação dos objetos&gt;*

# Diagrama de Classes

*&lt;Diagrama de relacionamento entre classes para os seus atributos e operações&gt;*

# Diagrama de Estados

*&lt;Diagrama para permite modelar o comportamento interno de um determinado objeto, subsistema ou sistema global&gt;*

# Diagrama de Implantação

*&lt;Diagrama para exibir o relacionamento de hardware e software no projeto&gt;*

# Referências

*&lt;Lista de referências&gt;*
