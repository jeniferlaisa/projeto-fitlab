# Projeto FitLab
O projeto será desenvolvido utilizando arquitetura em camadas.

<img src="https://raw.githubusercontent.com/jeniferlaisa/projeto-fitlab/main/image.png" alt="Arquitetura de projeto" />


A arquitetura em camadas divide o sistema em camadas lógicas ou físicas, cada uma com responsabilidades específicas. Isso permite separar as preocupações e simplificar o desenvolvimento, manutenção e testes do sistema. Nessa arquitetura, as camadas são organizadas em ordem hierárquica, com as camadas mais altas acessando as camadas mais baixas, mas não o inverso. No caso deste projeto, poderíamos ter as seguintes camadas: 


Interface de Usuário: a camada responsável pela apresentação dos dados para o usuário, incluindo as telas de cadastro, agenda de treinos, histórico de treinos, comunicação com clientes, entre outras. Essa camada deve ser fácil de usar e navegar, seguindo as diretrizes de usabilidade e acessibilidade. 

Lógica de Negócio: a camada responsável pela lógica de negócio do sistema, incluindo as regras de validação de dados, cálculo de treinos personalizados, agendamento de sessões e acesso a conteúdo exclusivo. Essa camada deve ser independente da interface de usuário e dos detalhes de implementação, permitindo que seja reutilizada em outras interfaces.

 Acesso a Dados: a camada responsável pelo acesso aos dados do sistema, incluindo as informações dos clientes, treinos, agendamentos e pagamentos. Essa camada deve ser separada da lógica de negócio e da interface de usuário, utilizando um modelo de dados consistente e eficiente. 

Essa arquitetura em camadas permitiria que o sistema fosse escalável, modular e fácil de manter, além de garantir a separação de responsabilidades e a reutilização de componentes. Além disso, seria possível aplicar princípios do desenvolvimento ágil, como a entrega contínua e a integração contínua, para garantir a qualidade e a efetividade do sistema.

## Guideline:

- Criação de branches: sempre que for desenvolver uma nova funcionalidade ou corrigir um bug, crie uma branch específica para essa tarefa.

- Commits: faça commits pequenos e com mensagens claras e descritivas sobre as alterações realizadas.

- Pull requests: crie pull requests para as branches criadas e solicite revisão de código de outros membros da equipe.

- Revisão de código: revise o código de outros membros da equipe e forneça feedback construtivo.

- Testes automatizados: desenvolva testes automatizados para as funcionalidades desenvolvidas ou corrigidas.

- Integração contínua: configure um sistema de integração contínua para garantir que as alterações não afetem a estabilidade do sistema.

- Documentação: mantenha a documentação atualizada e acessível a todos os membros da equipe. Isso inclui documentação de código, documentação de arquitetura e documentação de uso do sistema.
