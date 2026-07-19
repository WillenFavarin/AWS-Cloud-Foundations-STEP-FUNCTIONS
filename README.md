# AWS-Cloud-Foundations-STEP-FUNCTIONS
# Desafio DIO - AWS Step Functions

📖 Descrição

Este repositório foi desenvolvido como parte do desafio da DIO sobre **AWS Step Functions**.

O objetivo deste laboratório foi compreender como funcionam os workflows automatizados utilizando máquinas de estado (State Machines), explorando seus principais recursos, validações e integração com o AWS Lambda.


Conhecendo o AWS Step Functions

O AWS Step Functions é um serviço da Amazon Web Services que permite criar fluxos de trabalho automatizados através de **State Machines (Máquinas de Estado)**.

Cada etapa do processo é representada por um **State**, responsável por executar uma ação específica.

Entre as principais vantagens da ferramenta estão:

- Orquestração de serviços da AWS;
- Automação de processos;
- Monitoramento das execuções;
- Tratamento de erros;
- Redução da complexidade do código.

Os principais tipos de estados apresentados foram:

- Task
- Choice
- Wait
- Pass
- Parallel
- Succeed
- Fail


Benefícios e Projeto Modelo no AWS Step Functions

Durante a aula foi apresentado um projeto modelo utilizando o Step Functions para demonstrar como um fluxo pode ser construído visualmente.

Benefícios observados

- Fluxos organizados visualmente;
- Fácil manutenção;
- Escalabilidade;
- Integração nativa com diversos serviços da AWS;
- Monitoramento em tempo real das execuções.

O projeto demonstrou como cada estado executa uma responsabilidade específica dentro do fluxo, facilitando o entendimento da lógica da aplicação.


Realizando Validações no AWS Step Functions

Um dos recursos mais importantes do Step Functions é a possibilidade de realizar validações durante a execução do workflow.

Foram utilizados estados de decisão (**Choice**) para verificar condições antes de seguir para a próxima etapa.

Essas validações permitem:

- Criar diferentes caminhos de execução;
- Evitar processamento desnecessário;
- Tratar exceções;
- Direcionar o fluxo conforme os dados recebidos.

Esse recurso torna o workflow muito mais flexível e inteligente.


Criando e Executando Lambda no AWS Step Functions

Nesta etapa foi realizada a integração entre o AWS Step Functions e o AWS Lambda.

O Lambda executa funções sem necessidade de gerenciar servidores, sendo acionado diretamente por uma Task da State Machine.

Fluxo executado:

1. Criação da função Lambda;
2. Configuração das permissões necessárias;
3. Associação da função à State Machine;
4. Execução do workflow;
5. Verificação do resultado no histórico de execução.

Essa integração permite criar aplicações totalmente serverless, automatizando processos de forma simples e escalável.


📚 Principais Aprendizados

Ao concluir este laboratório foi possível compreender:

- O funcionamento das State Machines;
- Como criar workflows automatizados;
- A utilização de estados para controle do fluxo;
- Como realizar validações utilizando o estado Choice;
- A integração do Step Functions com AWS Lambda;
- O monitoramento e histórico das execuções.


📷 Evidências

As capturas de tela utilizadas neste projeto podem ser encontradas na pasta **/images**.

Exemplos:

- Criação da State Machine;
- Fluxo completo;
- Execução da máquina de estados;
- Histórico da execução;
- Integração com o AWS Lambda.


🛠 Tecnologias Utilizadas

- AWS Step Functions
- AWS Lambda
- AWS IAM
- Git
- GitHub
- Markdown


📌 Conclusão

Este laboratório permitiu compreender como o AWS Step Functions facilita a construção de workflows automatizados através de máquinas de estado, tornando os processos mais organizados, seguros e escaláveis.

Além disso, foi possível conhecer a integração com o AWS Lambda, entender como realizar validações no fluxo e reforçar a importância da documentação técnica utilizando o GitHub.


📖 Referências

- https://docs.aws.amazon.com/step-functions/
- https://docs.aws.amazon.com/lambda/
- https://docs.github.com/
