
### Desafio
Olá, queremos convidá-lo(a) a participar do nosso desafio de seleção.  Pronto(a) para participar? Seu trabalho será visto pelo nosso time e você receberá um feedback ao final sobre o que achamos do seu trabalho. Não é legal?

### Sobre a oportunidade 
A vaga é para Desenvolvedor(a), temos vagas com diversos níveis de senioridade e para cada um deles utilizaremos critérios específicos considerando este aspecto, combinado? 
Se você for aprovad(a) nesta etapa, será convidado para uma entrevista final.

### Desafio Técnico
  Nós trabalhamos com saúde e nada melhor do que um bom sistema para gestão de exames, onde cada médico só pode ver o hstórico dos exames que ele solicitou
  
  - Pré-requisitos:
    ```
    * Desenvolver os recursos em API Rest que realizam operações com a entidade conta a seguir:
    ```
    | Médico | Tipo |
    |-|-|
    | idMedico | Numérico |
    | nome | Texto |
    | crm | Numérico |
    | uf | Texto |
    | flagAtivo | Condicional |
    | especialidade | Numérido |
    | dataCriacao | Data |
    
    ```
    * Tabela de exame
    ```
    | Exame | Tipo |
    |-|-|
    | idExame | Numérico |
    | nmExame | Texto |
    | tipo | Numérido |
    | dataCriacao | Data |

    ```
    * Tabela de histórico de exames realizados por parciente
    ```
    | Histórico | Tipo |
    |-|-|
    | idHistorico | Numérico |
    | idPaciente | Numérico |
    | idMedico | Numérico |
    | idExame | Numérico |
    | dataCriacao | Data |

    ```
    * P.S.: Não é necessário realizar operações com a tabela paciente, mas é necessária a criação da tabela para mapeamento da relação com a histórico e enviar script de criação de pelo menos dois pacientes.
    ```

    | Paciente | Tipo |
    |-|-|
    | idPaciente | Numérico |
    | nome | Texto |
    | cpf | Texto |
    | dataNascimento | Data |    

  - O que esperamos como escopo mínimo:
    ```
    * Implementar path que realiza a criação de um médico;
    * Implementar path que realiza a criação de um exame;
    * Implementar path que realiza exame em um paciente;
    * Implementar path que realiza operação de consulta de histórico de exames;
    * Implementar path que realiza o desativação de um exame;
    ```
  - O que será diferencial:
    ```
    * Implementar uma consulta de histórico por período;
    * Elaborar manual de execução;
    * Elaborar documentação;
    * Elaborar testes.
    ```
    
  - O que vamos avaliar:
    ```
    * Seu código; 
    * Dockerfile ou docker-compose do serviço;
    * Script de banco;
    * Organização;
    * Boas práticas;
    * Diferenciais; 
    ```

  - Teste para o time de Arquitetura? 
    ```
    * Baseado no que foi desenvolvido nos envie uma solução da Arquitetura utilizando serviços na nuvem como a AWS (diferencial), Azure e GCP;
    * Junto com as instruções de execução, explique qual Design Pattern você utilizou e por que o escolheu para a sua solução.
    ```
  

### Instruções
      1. Faça o fork do desafio;
      2. Crie um repositório privado no seu github para o projeto e adicione como colaborador o usuário brunopmoraes;
      3. Desenvolva. Você terá 3 (três) dias a partir da data do envio do desafio; 
      4. Após concluir seu trabalho faça um push; 
      5. Envie um e-mail à pessoa que está mantendo o contato com você durante o processo notificando a finalização do desafio para validação.
