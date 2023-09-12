# Relatório Especificação de Requisitos SKILLSYNC

## Engenharia de software 2023.2 | Universidade Federal do Tocantins - Palmas, 2023

## Introdução

O projeto desenvolvido na disciplina Engenharia de Software do semestre 2023.2 é dividido em etapas. Primeiramente, os integrantes descrevem os casos expandidos de uso e user stories dos requisitos funcionais do sistema. Foi combinado a utilização da plataforma GitHub para gerenciar e controlar as versões do projeto, além do método Kanban para gestão ágil, por meio da ferramenta Trello. Todo o trabalho será desenvolvido no formato markdown.

## Escopo do projeto

### Descrição do projeto
Desenvolver uma plataforma de prestação de serviços que conecta prestadores de serviços a usuários, permitindo que os prestadores ofereçam seus serviços e os usuários solicitem os mesmos. A plataforma deve permitir que os prestadores de serviços criem perfis com informações pessoais, habilidades e preços, além de possibilitar a criação de perfis de usuários com informações de contato e preferências. Os usuários devem ser capazes de buscar e filtrar prestadores com base em critérios como localização e classificações, enviar solicitações de serviços e visualizar históricos de transações. Além disso, o sistema deve suportar a avaliação e revisão de prestadores e oferecer funcionalidades de pagamento seguro.

### Objetivos

* Conectar prestadores de serviços a usuários, facilitando a oferta e solicitação de serviços.
* Permitir que prestadores de serviços criem perfis detalhados com informações pessoais, habilidades e preços.
* Possibilitar aos usuários a criação de perfis com informações de contato e preferências.
* Oferecer recursos de busca e filtragem de prestadores com base em critérios como localização e classificações.
* Permitir que os usuários enviem solicitações de serviços de forma eficiente.
* Manter registros de transações para que os usuários possam acessar seu histórico.
* Facilitar a avaliação e revisão de prestadores de serviços.
* Garantir um sistema de pagamento seguro para todas as transações.
* Organizar o desenvolvimento do projeto em iterações definidas.

### Requisitos Funcionais
Os **Requisitos Funcionais** são uma lista dos recursos e funcionalidades específicas que o sistema, produto ou serviço deve oferecer. Isso pode incluir funcionalidades como login de usuário, solicitação de serviços, geração de relatórios, etc.

### Requisitos não funcionais
Requisitos que não estão diretamente relacionados a funcionalidades específicas, mas são igualmente importantes. Isso pode incluir requisitos de desempenho, segurança, escalabilidade, usabilidade, entre outros.

### Cronograma

|Período|Ações|
| --------------- | ----------------------------------------------------------------------------------- |
|Semana 1| Inicio do desenvolvimento do Relatório Especificação de Requisitos.|
|Semana 2| Conclusão e apresentação do Relatório Especificação de Requisitos.|
|Semana 3| Inicio do desenvolimento dos requisitos da 1º iteração.|
|Semana 4| Conclusão do desenvolvimento da 1º iteração e apresentação dos resultados obtidos.|

### Metodologia de Desenvolvimento
O Kanban será usado para organizar e gerenciar o fluxo de trabalho da equipe. Criamos um quadro Kanban que representa o progresso do projeto, com colunas como "A fazer", "Em progresso" e "Concluído". As tarefas do Backlog serão adicionadas ao quadro e movidas conforme o progresso.
O desenvolvimento seguirá a arquitetura MVC (Model-View-Controller) em PHP. Cada iteração abordará um conjunto específico de requisitos funcionais e será implementada seguindo os princípios do MVC.
No final de cada iteração, a equipe realizará uma retrospectiva para avaliar o processo e identificar áreas de melhoria. Os aprendizados serão aplicados nas próximas iterações.
Após a conclusão de cada iteração, haverá uma revisão interna e externa para garantir a qualidade do código e da funcionalidade implementada. Os feedbacks serão incorporados para refinamento contínuo.

### Tecnologias e Ferramentas

Neste projeto, serão utilizadas várias tecnologias e ferramentas para o desenvolvimento, divididas entre o back-end, front-end e o sistema de gerenciamento de banco de dados (SGBD).

**Back-End:**<br/>
* Linguagem de Programação PHP: O back-end será desenvolvido utilizando PHP para implementar a lógica de negócios.
* Web Server: Um servidor web, como o Apache, será configurado para hospedar a aplicação PHP.

**Front-End:**<br/>
* HTML (HyperText Markup Language): Para criar a estrutura da interface do usuário e as páginas da web.
* CSS (Cascading Style Sheets): Para estilizar e formatar as páginas da web, garantindo uma aparência atraente e responsiva.
* JavaScript: Será usado para tornar a interface do usuário interativa e dinâmica, lidando com eventos do lado do cliente.

**Banco de Dados:**<br/>
* PostgreSQL: Será usado como o Sistema de Gerenciamento de Banco de Dados (SGBD) principal. O PostgreSQL é um sistema de banco de dados relacional robusto e altamente escalável.

### Critérios de Aceitação
Os critérios de aceitação para este projeto incluem:

* Todas as funcionalidades especificadas nos requisitos funcionais estão implementadas e funcionando corretamente.
* A plataforma passou por testes de qualidade e os bugs foram corrigidos.
* A documentação está completa e bem organizada.
* A equipe apresentou o projeto de forma clara e demonstrou todas as funcionalidades.


### Entregáveis
Os principais entregáveis deste projeto incluem:

*  **Documentação de Requisitos:** Especificação detalhada dos requisitos funcionais e não funcionais do sistema.<br/>
*  **Documentação de Design:** Descrição da arquitetura de software e design da plataforma.<br/>
*  **Código Fonte:** O código-fonte do sistema hospedado no GitHub.<br/>
*  **Relatórios de Progresso:** Relatórios de progresso semanais ou quinzenais para acompanhamento.<br/>
*  **Apresentação Final:** Uma apresentação que destaca as funcionalidades e realizações do projeto.<br/>

### Equipe de Projeto
 [Vinícius Maciel Pires](https://github.com/ViniciusDevelopment/)<br/>
 <br/>[Raphael Sales de Souza](https://github.com/raphaelsales)<br/>
 <br/>[Antonio Cassio de Oliveira Neto](https://github.com/ACNprogrammer/)<br/>
<br/>[Jorge Antonio Motta Braga](https://github.com/jorgespark11)<br/>
<br/>[Wanderson Melo](https://github.com/sadMello)<br/>
<br/>[Pedro Trivelato](https://github.com/Ptrivelato)<br/>
<br/>[Loenis Fernandes](https://github.com/loenisjunior)<br/>

###
## Épicos

### Épico 1: Gerenciamento de Usuário -> RF01, RF02, R03, RF10, RF12.
### Épico 2: Gerenciamento de Serviços -> RF03, RF04, RF08, RF11.
### Épico 3: Gerenciamento de Solicitações de serviços -> RF05, RF06, RF13.
### Épico 4: Avaliação de serviços -> RF09, RF14.

## Iteração 1

- [X] RF01 -  Cadastrar prestador de serviço. [Raphael Sales de Souza](https://github.com/raphaelsales) Revisado por  [Vinícius Maciel Pires](https://github.com/ViniciusDevelopment/)
- [X] RF02 - Cadastrar usuário. [Antonio Cassio de Oliveira Neto](https://github.com/ACNprogrammer/) Revisado por [Raphael Sales de Souza](https://github.com/raphaelsales)
- [X] RF03 -  Realizar Login.  [Vinícius Maciel Pires](https://github.com/ViniciusDevelopment/) Revisado por [Antonio Cassio de Oliveira Neto](https://github.com/ACNprogrammer/)
- [X] RF04 -  Cadastrar serviços. [Pedro Trivelato](https://github.com/Ptrivelato) Revisado por [Loenis Fernandes](https://github.com/loenisjunior)
- [X] RF05 -  Buscar serviços por critérios. [Loenis Fernandes](https://github.com/loenisjunior) Revisado por [Pedro Trivelato](https://github.com/Ptrivelato)
- [X] RF06 - Enviar solicitação de serviço. [Jorge Antonio Motta Braga](https://github.com/jorgespark11) Revisado por [Wanderson Melo](https://github.com/sadMello)
- [X] RF07 - Responder solicitação de serviço. [Wanderson Melo](https://github.com/sadMello) Revisado por [Jorge Antonio Motta Braga](https://github.com/jorgespark11)

<br/>

## Iteração 2


- [X] RF08 - Realizar o pagamento seguro pelo serviço prestado [Wanderson Melo](https://github.com/sadMello) Revisado por [Vinícius Maciel Pires](https://github.com/ViniciusDevelopment/)
- [X] RF09 - Avaliar e revisar prestadores de serviço.  [Vinícius Maciel Pires](https://github.com/ViniciusDevelopment/) Revisado por [Antonio Cassio de Oliveira Neto](https://github.com/ACNprogrammer/)
- [X] RF10 -  Manter perfis de prestadores de serviço atualizados. [Antonio Cassio de Oliveira Neto](https://github.com/ACNprogrammer/) Revisado por [Wanderson Melo](https://github.com/sadMello)
- [X] RF11 - Notificar usuários sobre atualizações em solicitações de serviço. [Jorge Antonio Motta Braga](https://github.com/jorgespark11) Revisado por [Jorge Antonio Motta Braga](https://github.com/jorgespark11)
- [X] RF12 -  Permitir que os usuários editem seus perfis. [Loenis Fernandes](https://github.com/loenisjunior) Revisado por [Loenis Fernandes](https://github.com/loenisjunior)
- [X] RF13 -   Implementar funcionalidade de pesquisa avançada de prestadores de serviço. [Pedro Trivelato](https://github.com/Ptrivelato) Revisado por [Pedro Trivelato](https://github.com/Ptrivelato)(https://github.com/jpnoronhaa)
- [X] RF14 -Oferecer suporte a diferentes métodos de pagamento.  [Raphael Sales de Souza](https://github.com/raphaelsales) Revisado por [Raphael Sales de Souza](https://github.com/raphaelsales)(https://github.com/uiuqM)

<br/>

---
## **RF01 - Cadastrar prestador de serviço**

<br/>

#### Autor: [Vinícius Maciel](https://github.com/viniciusDevelopment)

#### Revisor: [Vinícius Maciel Pires](link_do_perfil_do_revisor)

<br/>


| Item            | Descrição                                                                           |
| --------------- | ----------------------------------------------------------------------------------- |
| Caso de uso     | RF01 - Cadastrar prestador de serviço;                                                       |
| Resumo          | Cadastrar um prestador de serviço ao sistema; |
| Ator principal  | Prestador de serviço;                                                    |
| Ator secundário | -                                                                                   |
| Pré-condição    | -                          |
| Pós-condição    |                                          |

<br/>

#### Fluxo principal

| Passos  | Descrição                                           |
| ------- | --------------------------------------------------- |
| Passo 1 | O prestador digita seus dados cadastrais nos campos adequados.            |
| Passo 2 | Após preencher seus dados o prestador deve marcar a opção 'sou um prestador de serviços'. |
| Passo 3 | Ao clicar no botão 'cadastrar' no final do formulário, o prestador de serviços é cadastrado. |

<br/>

#### Campos do formulário

| Campo            | Obrigatório? | Editável? | Formato      |
| ---------------- | ------------ | --------- | ------------ |
| Nome  | Sim          | Sim       | Texto        |
| Email             | Sim          | Sim       | Email         |
| Senha            | Sim          | Sim       | Password        |
| Confirmar senha  | Sim          | Não       | Password        |

<br/>

#### Opções dos usúarios

| Opção            | Descrição | Atalho | 
| ---------------- | ------------ | --------- | 
| Cadastrar | Cadastra um novo prestador de serviço          | Não possui       | 
| Realizar login             | Redireciona o prestador para a tela de login          | Não possui       |

<br/>

#### Relatório de usuário

| Campo                      | Descrição                                                             | Formato |
| -------------------------- | --------------------------------------------------------------------- | ------- |
| Cadastro realizado com sucesso | Informa que o cadastro foi efetuado com sucesso  | Texto   |
| Erro ao realizar o cadastro | Informa que ocorreu um erro durante o cadastro  | Texto   |
| Senha e confirmar senha não conferem | Informa a senha e a confirmação da senha estão diferentes  | Texto   |

<br/>

### US01 - Cadastrar prestador de serviço

**Prestador de serviços**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto **um prestador de serviços** eu preciso ser capaz de **criar uma conta** para que **eu possa oferecer meus seerviços** | O **prestador de serviços** deve poder se cadastrar no sistema.|

<br />

### Prototipação de telas
**Tela de cadastro com marcação da opção 'Sou um prestador de serviços'**

<br />
---

## **RF02 - Cadastrar usuário**

<br/>

#### Autor: [@viniciusHPS3](https://github.com/viniciusHPS3) - Vinicius Maciel

#### Revisor: [viniciuso Eduardo da Silva](https://github.com/viniciusuBrabo)

<br/>

| Item            | Descrição                                                                           |
| --------------- | ----------------------------------------------------------------------------------- |
| Caso de uso     | RF02 - Cadastrar usuário;                                                       |
| Resumo          | Cadastrar um usuário no sistema; |
| Ator principal  | Usuário;                                                    |
| Ator secundário | -                                                                                   |
| Pré-condição    | -                          |
| Pós-condição    |                                                                                    |

<br/>

#### Fluxo principal

| Passos  | Descrição                                           |
| ------- | --------------------------------------------------- |
| Passo 1 | O usuário digita seus dados cadastrais nos campos adequados.            |
| Passo 2 | Ao clicar no botão 'cadastrar' no final do formulário, o usuário é cadastrado. |

<br/>

#### Opções dos usúarios

| Opção            | Descrição | Atalho | 
| ---------------- | ------------ | --------- | 
| Cadastrar | Cadastra um novo usuário          | Não possui       | 
| Realizar login             | Redireciona o usuário para a tela de login          | Não possui       |

<br/>

#### Relatório de usuário

| Campo                      | Descrição                                                             | Formato |
| -------------------------- | --------------------------------------------------------------------- | ------- |
| Cadastro realizado com sucesso | Informa que o cadastro foi efetuado com sucesso  | Texto   |
| Erro ao realizar o cadastro | Informa que ocorreu um erro durante o cadastro  | Texto   |
| Senha e confirmar senha não conferem | Informa a senha e a confirmação da senha estão diferentes  | Texto   |
<br/>

 ### US02 - Cadastrar usuário

**Usuário**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto **um usuário do aplicativo** eu preciso ser capaz de **me cadastrar no sistema** para que **eu possa analisar e solicitar serviços.**| O usuário deve poder se cadastrar no sistema|

<br />

### Prototipação de telas
**Tela de cadastro sem marcação da opção 'Sou um prestador de serviços'**


<br/>

---

## **RF03 - Realizar Login**

<br/>

#### Autor: [@viniciusuBrabo](https://github.com/viniciusuBrabo) - Vinicius Maciel

#### Revisor: [vini](https://github.com/MateusAlvez)

<br/>

| Item            | Descrição                                                                           |
| --------------- | ----------------------------------------------------------------------------------- |
| Caso de uso     | RF03 - Realizar Login;                                                       |
| Resumo          | Realizar o login dos atores; |
| Ator principal  | Usuario/Prestador de serviço;                                                    |
| Ator secundário | -                                                                             |
| Pré-condição    | O(s) ator(es) devem ter um cadastro no sistema.                         |
| Pós-condição    | Os dados do(s) ator(er) devem estar corretos                                                                                      |

<br/>

#### Fluxo principal

| Passos  | Descrição                                           |
| ------- | --------------------------------------------------- |
| Passo 1 | O(s) Ator(es) informam seus dados           |
| Passo 2 | A verificação das credenciais é efetuada |
| Passo 3 | A sessão é iniciada em caso de login correto. |

<br/>

#### Fluxo alternativo

| Passos  | Descrição                                           |
| ------- | --------------------------------------------------- |
| Passo 1 | O(s) Ator(es) informam seus dados            |
| Passo 2 | A verificação das credenciais é efetuada |
| Passo 3 | A sessão não é iniciada e o usuário é redirecionado para a tela de login. |

<br/>

#### Campos do formulário

| Campo            | Obrigatório? | Editável? | Formato      |
| ---------------- | ------------ | --------- | ------------ |
| Email             | Sim          | Sim       | Email         |
| Senha            | Sim          | Sim       | Password        |

<br/>

#### Opções dos usúarios

| Opção            | Descrição | Atalho | 
| ---------------- | ------------ | --------- | 
| Login | Valida as credenciais do ator          | Não possui       | 
| Cadastre-se             | Redireciona o usuario para a tela de cadastro          | Não possui       |

<br />

#### Relatório de usuário

| Campo                      | Descrição                                                             | Formato |
| -------------------------- | --------------------------------------------------------------------- | ------- |
| Email e/ou senha incorretos | Informa que as credenciais são inválidas  | Texto   |

<br />

### US03 - Realizar Login

**Prestador de serviço/Usuário**

|  User Story                                        | Critério de aceitação                                 |
| ------------------------------------------------- | ----------------------------------------------------- |
| Enquanto **um ator do aplicativo** eu preciso ser capaz de **realizar login**, para que **eu possa ter acesso as funcionalidades do sistema** | Certifique-se de que o usuário é capaz de **acessar o aplicativo**. |

<br/>

### Prototipação de telas
**Tela de login**

<br />

---

## **RF04 - Cadastrar serviços**

<br />

#### Autor: [vini](https://github.com/erarich)
#### Revisor: [vinicius Tavares](https://github.com/viniciusUFT)

<br />


|Item             | Descrição                                                           |
| --------------- | -----------------------------------------------------------------   |
| Caso de uso     | Cadastrar serviços                                                  |
| Resumo          | É esperado que o prestador de serviços tenha a possibilidade de inserir seus serviços prestados|
| Ator principal  | prestador de serviço                                 |
| Ator secundário | -                                                          | 
| Pré-condição    | É necessário que o prestador de serviço tenha efetuado o login.            |
| Pós-condição    | Todos os campos do formulário de cadastro de serviço devem ser preenchidos corretamente.  |

<br />

#### Fluxo principal

| Passos  | Descrição                                                                   |
| ------- | -----------------------------------------                                   |
| Passo 1 | Entrar na seção de cadastro de meus serviços                                         |
| Passo 2 | Clicar no botão "Inserir novo serviço"                                            |
| Passo 3 | Inserir os dados adequados nos campos do formulário                                                  |
| Passo 5 | Clicar em salvar serviço                                                                     |
<br />

#### Campos do formulário

| Campo            | Obrigatório? | Editável? | Formato      |
| ---------------- | ------------ | --------- | ------------ |
| Nome do serviço             | Sim          | Sim       | Texto        |
| Tipo             | Sim          | Sim       | Texto        |
| Valor            | Sim          | Sim       | Numérico     |


<br />

#### Opções do usuário


| Opção         | Descrição                 | Atalho |
| ------------- | ------------------------- | ------ |
| Adicionar serviço | Cadastra um serviço no sistema | Não possui       |
| Cancelar | Retorna Para a tela de meus serviços | Não possui       |
<br />

#### Relatório de usuário

| Campo                      | Descrição                                                             | Formato |
| -------------------------- | --------------------------------------------------------------------- | ------- |
| Serviço inserido com sucesso | Isso confirma e garante todo êxito na operação de inserção de serviço   | Texto   |
| Erro ao inserir serviço | Informa que ocorreu um erro ao inserir o serviço   | Texto   |
| Dados incorretos | Informa que os dados inseridos são inválidos   | Texto   |
<br />

                                   
### US04 - Cadastrar serviços

**Usuário/Prestador de serviços**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto "prestador de serviço" preciso ter meus serviços salvos na plataforma a fim de fornecer minha mão de obra. | O prestador de serviços deve ser capaz de cadastrar seus serviços. |

<br/>

---

## **RF05 -  Buscar serviço por critérios**

<br />

#### Autor: Icaro Mesquita Ponce[@icarompo](https://github.com/icarompo)
#### Revisor: vinicius Henrique Pinho Santos[@viniciusHPS3](https://github.com/viniciusHPS3)  
<br />

<br />

|Item             | Descrição                                                         |
| --------------- | ----------------------------------------------------------------- |
| Caso de uso     | Buscar serviço por critérios.                                                   |
| Resumo          | É esperado que o usuário tenha a possibilidade de buscar pelos serviços mais adequados para ele|
| Ator principal  | Atores |
| Ator secundário | Não possui                                                        | 
| Pré-condição    |  É necessário que para realizar a busca conta o ator tenha feito login         |
| Pós-condição    | Os dados de busca devem ser válidos |
<br />

#### Fluxo principal
| Passos  | Descrição                                 |
| ------- | ----------------------------------------- |
| Passo 1 | Entrar na seção de Serviços               |
| Passo 2 | Clicar no input de pesquisa                 |
| Passo 3 | Inserir dados no campo              |
| Passo 4 | Pesquisar                                    |
<br />

#### Campos do formulário
| Campo            | Obrigatório? | Editável? | Formato      |
| ---------------- | ------------ | --------- | ------------ |
| Pesquisa             | Sim          | Sim       | Texto        |

<br />

#### Opções do usuário
| Opção         | Descrição                 | Atalho |
| ------------- | ------------------------- | ------ |
| Pesquisar Serviço | Uma busca com base nos dados de entrada do ator é efetuada |  Não possui      |
<br />

#### Relatório de usuário

| Campo                      | Descrição                                                             | Formato |
| -------------------------- | --------------------------------------------------------------------- | ------- |
| Nenhum serviço encontrado! | Não foi possível encontrar nenhum serviço com os parâmetros inseridos.   | Texto   |
<br />


### US05 - Buscar serviço por critérios

**Atores**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto "um ator" do sistema preciso poder pesquisar pelos mais diversos tipos de serviços. | Digitar corretamente no campo de pesquisa |

<br/>

---

## **RF06 - Enviar solicitação de serviço**

<br/>

#### Autor: [@vinizin1v9](https://github.com/vinizin1v9) - vini de Sousa Barbosa

#### Revisor: [@jpnoronhaa](https://github.com/jpnoronhaa) - João Pedro Noronha

<br/>

|Item             | Descrição                                                         |
| --------------- | ----------------------------------------------------------------- |
| Caso de uso     | RF06 -  Enviar solicitação de serviço.                                             |
| Resumo          | É esperado que o ator tenha a possibilidade de Enviar solicitação de serviço.                                                                     |
| Ator principal  | Usuário/Prestador de serviço|
| Ator secundário | Não possui                                                        | 
| Pré-condição    | É necessário que o ator tenha efetuado o login.        |
| Pós-condição    | - |

<br/>

#### Fluxo principal
| Passos  | Descrição                                 |
| ------- | ----------------------------------------- |
| Passo 1 | Entrar na aba de serviços       |
| Passo 2 | Digitar a data da prestação do serviço |
| Passo 3 | Clicar no botão 'Solicitar serviço' no serviço desejado|

<br/>

#### Campos do formulário
| Campo            | Obrigatório? | Editável? | Formato      |
| ---------------- | ------------ | --------- | ------------ |
| Data         | Não          | Sim       | Data        |

<br/>

#### Opções do usuário
| Opção             | Descrição                 | Atalho |
| -------------     | ------------------------- | ------ |
| Solicitar serviços | Solicita o serviço selecionado |        |

<br/>

#### Relatório de usuário

| Campo      | Descrição   | Formato |
| ---------- | ----------- |---------|
| Erro ao solicitar o serviço | Ocorreu um erro ao solicitar o serviço |  Texto  |

<br/>

### US06 - Enviar solicitação de serviço

**Atores**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto **um ator** preciso ser capaz de **solicitar a prestação de serviços** para que **eu possa ressolver meus problemas** | O ator deve poder solicitar serviços dentro da plataforma.

<br/>

---

## **RF07 -  Responder solicitação de serviço**

<br/>

#### Autor: [João Pedro Noronha](https://github.com/jpnoronhaa)

#### Revisor: [Wilque Muriel do Nascimento Coelho](https://github.com/uiuqM)

<br/>

|Item             | Descrição                                                         |
| --------------- | ----------------------------------------------------------------- |
| Caso de uso     | O prestador pode responder as solicitações de serviço                                |
| Resumo          | Visualiza o somatório das despesas que o usário teve no mês       |
| Ator principal  | Prestador de serviços                                 |
| Ator secundário | Não possui                                                        | 
| Pré-condição    |É necessário que o ator tenha efetuado o login.                                                                               |
| Pós-condição    | Não possui                                                        | 

<br/>

#### Fluxo principal
| Passos  | Descrição                                 |
| ------- | ----------------------------------------- |
| Passo 1 | Entrar na página de respostas a solicitações de serviços        |
| Passo 2 | Visualizar as solicitações           |
| Passo 3 | Responder as solicitações           |

<br/>

#### Campos do formulário
| Campo            | Obrigatório? | Editável? | Formato      |
| ---------------- | ------------ | --------- | ------------ |
| Descrição         | Não          | Sim       | Texto        |

<br/>

#### Opções do usuário
| Opção             | Descrição                                                         | Atalho |
| ----------------- | ----------------------------------------------------------------- | ------ |
| Aprovar solicitação | Trocar o status da requisição para aprovado. |  Não possui  |
| Reprovar solicitação | Trocar o status da requisição para reprovado. |  Não possui  |
| Em análise | Trocar o status da requisição para em análise. |  Não possui  |

<br/>

#### Relatório de usuário

| Campo      | Descrição  | Formato |
| ---------- | ---------- | ------- |
| Solicitação alterada com sucesso |   Status da solicitação foi alterado         |    Texto     |

<br/>

#### Fluxo alternativo
| Passos    | Descrição                                               |
| --------  | ------------------------------------------------------- |
| Passo 1.1 | O sistema não possui nenhum serviço cadastrado                   |
| Passo 1.2 | O sistema informa que não existem serviços cadastradas  |
<br />


### US07 -  Responder solicitação de serviço

**Prestador de serviço**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto um **prestador de serviço** eu preciso ser capaz de **responder as solicitações de serviço** para que **eu possa ter um controle melhor da minha profissão**. | O prestador deve poder responder as solicitações de serviço. 

<br/>

---

## RF08 - Inserir Conta Bancaria

<br/>

#### Autor: [@98loann](https://github.com/98loann)

#### Revisor: [Sophia Menezes Pontes](https://github.com/SophiaMenezes)

<br/>

### Caso de uso

|Item             | Descrição                                                         |
| --------------- | ----------------------------------------------------------------- |
| Caso de uso     | Inserir conta Bancária                                            |
| Resumo          | É esperado que o usuário tenha a possibilidade de inserir a conta bancária na qual ele quer ter controle                                                                              |
| Ator principal  | Usuário que faz uso da plataforma |
| Ator secundário | Não possui                                                        | 
| Pré-condição    | É necessário que o usuário tenha uma conta na plataforma          |
| Pós-condição    | É necessário que para inserir a conta o usuário tenha feito login |
<br />

#### Fluxo principal
| Passos  | Descrição                                 |
| ------- | ----------------------------------------- |
| Passo 1 | Entrar no aplicativo e fazer login        |
| Passo 2 | Estar no aplicativo e clicar no botão +   |
| Passo 3 | Digitar o nome do banco e o tipo de conta |
| Passo 4 | Inserir o saldo total da conta            |
| Passo 5 | Salvar                                    |
<br />

#### Campos do formulário
| Campo            | Obrigatório? | Editável? | Formato      |
| ---------------- | ------------ | --------- | ------------ |
| Nome             | Sim          | Sim       | Texto        |
| Banco            | Sim          | Sim       | Texto        |
| Tipo de Conta    | Sim          | Sim       | Texto        |
| Saldo            | Sim          | Sim       | Numérico     |
<br />

#### Opções do usuário
| Opção         | Descrição                 | Atalho |
| ------------- | ------------------------- | ------ |
| Inserir banco | Confirmar dados inseridos |        |
<br />

#### Relatório de usuário

| Campo                      | Descrição                                                             | Formato |
| -------------------------- | --------------------------------------------------------------------- | ------- |
| Banco inserido com sucesso | Isso confirma e garante todo êxito na operação de cadastro de banco   | Texto   |
<br />

#### Fluxo alternativo
| Passos    | Descrição |
| --------  | --------------------------------------------------------------------------------------------- |
| Passo 1.1 | O ator tenta adicionar um conta de banco que já foi cadastrada                                |
| Passo 1.2 | O sistema acusa que a conta em questão já existe                                              |
| Passo 2.1 | O ator tenta adicionar um novo banco                                                          |
| Passo 2.2 | O sistema exibe que não foi possível concluir a operação                                      |
<br />

### User Story

**Persona um, usuário comum.**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto "usuário comum" preciso ter minhas informações salvas na plataforma através de uma conta a fim de ter mais praticidade | Certificar que todos campos estão preenchidos

<br/>

---

## RF09 - Inserir Cartão de crédito

<br/>

#### Autor: [@luisfilipebandeira](https://github.com/luisfilipebandeira)

#### Revisor: [vinicius Marçal](https://github.com/erarich)

<br/>

### Caso de uso

|Item             | Descrição                                                         |
| --------------- | ----------------------------------------------------------------- |
| Caso de uso     | Inserir cartão de crédito                                         |
| Resumo          | É esperado que o usuário tenha a possibilidade de inserir o cartão de crédito que ele quer ter controle|
| Ator principal  | Usuário que faz uso da plataforma |
| Ator secundário | Não possui                                                        | 
| Pré-condição    | É necessário que o usuário tenha uma conta na plataforma          |
| Pós-condição    | É necessário que para inserir a conta o usuário tenha feito login |
<br />

#### Fluxo principal
| Passos  | Descrição                                 |
| ------- | ----------------------------------------- |
| Passo 1 | Entrar no aplicativo e fazer login        |
| Passo 2 | Estar no aplicativo e clicar no botão adicionar cartão   |
| Passo 3 | Digitar o número do cartão |
| Passo 4 | Digitar o nome que está impresso no cartão |
| Passo 5 | Digitar a data de vencimento do cartão |
| Passo 6 | Digitar o CVV do cartão |
| Passo 7 | Salvar                                    |
<br />

#### Campos do formulário
| Campo            | Obrigatório? | Editável? | Formato      |
| ---------------- | ------------ | --------- | ------------ |
| Nome             | Sim          | Sim       | Texto        |
| Numero do cartão            | Sim          | Sim       | Texto        |
| Data de validade    | Sim          | Sim       | Texto        |
| CVV            | Sim          | Sim       | Texto     |
<br />

#### Opções do usuário
| Opção         | Descrição                 | Atalho |
| ------------- | ------------------------- | ------ |
| Inserir Cartão | Confirmar dados inseridos |        |
<br />

#### Relatório de usuário

| Campo                      | Descrição                                                             | Formato |
| -------------------------- | --------------------------------------------------------------------- | ------- |
| Cartão inserido com sucesso | Isso confirma e garante todo êxito na operação de cadastro dp cartão   | Texto   |
<br />

#### Fluxo alternativo
| Passos    | Descrição |
| --------  | --------------------------------------------------------------------------------------------- |
| Passo 1.1 | O ator tenta adicionar um cartão que já foi cadastrado                                |
| Passo 1.2 | O sistema acusa que o cartão em questão já existe                                              |
| Passo 2.1 | O ator tenta adicionar um novo cartão                                                          |
| Passo 2.2 | O sistema exibe que não foi possível concluir a operação                                      |
<br />

### User Story

**Persona um, usuário comum.**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto "usuário comum" preciso ter minhas informações salvas na plataforma através de uma conta a fim de ter mais praticidade | Certificar que todos campos estão preenchidos

<br/>

---

## **RF10 - Visualizar Contas Bancárias.**

<br/>

### Autor: [Marcos Vinicius Barbosa e Silva](https://github.com/eziors)

### Revisor: [Benedito Jaime](https://github.com/orgs/Turma-2023-1-Engenharia-de-Software/people/beneX90)

<br/>

###  Caso de uso

| Item            |Descrição                                                |
| --------------- | ----------------------------------------------------------------------------------- |
| Caso de uso     | RF10 - Visualizar Contas Bancárias;                                       |
| Resumo          | Responsável pela visualização de contas bancárias do usuário; |
| Ator principal  | Usuário - Vizualizador da conta;                               |
| Ator secundário | -                                                                                   |
| Pré-condição    | Ter acesso ao aplicativo, e ter pelo menos uma conta adicionada;                          |
| Pós-condição    | -                                                                                   |

#### Fluxo principal


| Passos  | Descrição                                           |
| ------- | --------------------------------------------------- |
| Passo 1 | O usuário seleciona a opção de visualizar suas contas bancárias         |  
| Passo 2 | O usuário seleciona a opção de visualizar uma conta especifica


### User story

**Persona um, usuário comum.**

| User Story                                                                                                                                                              | Critério de aceitação                                         |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------- |
| Enquanto **um usuário do aplicativo** eu preciso ser capaz de **Verificar minhas contas bancárias ** para que **eu tenha uma controle da minha atual situação financeira.** | Certifique-se de que o usuário é capaz de **acessar o aplicativo**. |

<br/>

---

## **RF11 - Visualizar contas de Crédito**

<br/>

#### Autor: [@SophiaMenezes](https://github.com/SophiaMenezes) - Sophia Menezes Pontes

#### Revisor: [Luan Porto](https://github.com/98loann)

<br/>

### Caso de uso

| Item            | Descrição                                                                           |
| --------------- | ----------------------------------------------------------------------------------- |
| Caso de uso     | RF11 - Visualizar contas de crédito;                                                |
| Resumo          | O usuário pode ver o saldo atual da sua conta de crédito e monitorar seus gastos;   |
| Ator principal  | Usuário do aplicativo de controle financeiro;                                       |
| Ator secundário | -                                                                                   |
| Pré-condição    | Usuário já deve ter uma conta de crédito cadastrada no aplicativo;                  |
| Pós-condição    | -                                                                                   |

<br/>

#### Fluxo principal

| Passos  | Descrição                                           |
| ------- | --------------------------------------------------- |
| Passo 1 | O usuário seleciona a opção de visualizar "contas de crédito" no menu principal.            |
| Passo 2 | O aplicativo exibe uma lista de todas as contas de crédito associadas à conta do usuário.   |
| Passo 3 | O usuário seleciona a conta de crédito específica para ver mais detalhes, como saldo atual, limite de crédito e data de vencimento da próxima fatura;   |
<br />


### User story

*Persona um, usuário comum.*

| User Story                                                                                                                                                              | Critério de aceitação                                         |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------- |
| "Enquanto um *usuário do aplicativo de controle financeiro*, eu preciso visualizar minhas contas de crédito e seus respectivos saldos para poder monitorar meus gastos e manter meu orçamento sob controle." | O usuário poderá selecionar uma conta de crédito específica para ver mais detalhes. |

<br/>

---

## **RF12 - Editar despesas**

<br/>

#### Autor: [Wilque Muriel do Nascimento Coelho](https://github.com/uiuqM) 

#### Revisor: [Marcos Vinicius Barbosa e Silva](https://github.com/eziors)

<br/>

### Caso de uso

Item	          |Descrição
:----------------:|:--------------------------------:
Caso de uso	Editar| despesas do usuário.
Resumo	O usuário | deseja editar as suas despesas.
Ator principal	  |Usuário
Pré-condição	  |Existam despesas constando para o usuário em seu histórico.
Pós-condição	  |O usuário consegue editar suas despesas da forma desejada.

<br/>

#### Fluxo principal

Passos	  |Descrição
:--------:|:-----------------------------------------------:
Passo 01  |O usuário acessa o app.
Passo 02  |O usuário abre as suas despesas
Passo 03  |O usuário seleciona a opção de editar a despesa.
Passo 04  |O usuário abre a edição de sua despesa.

<br/>

#### Opções de usuário


Opção          |Descrição
---------------|----------------
Editar despesas|Edita a despesa.
<br />

### User Story

User story|	Critério de aceitação
-------------|--------------------
Enquanto ator quando visualizo minhas despesas gostaria de poder edita-las.|	Ator necessita ter despesas para editar.

<br/>

---

## **RF13 - Editar receitas.**

<br/>

#### Autor: [vini](https://github.com/MateusAlvez) 

#### Revisor: [Ícaro Mesquita Ponce](https://github.com/icarompo)

<br/>

###  Caso de uso

| Item            |Descrição                                                |
| --------------- | ----------------------------------------------------------------------------------- |
| Caso de uso     | RF13 - Editar receita;                                       |
| Resumo          | Responsável pela mudança de receita do usuário; |
| Ator principal  | Usuário- Editar receita;                               |
| Ator secundário | -                                                                                   |
| Pré-condição    | Ter acesso ao aplicativo, e ter saldo adicionado.;                          |
| Pós-condição    | -                                                                                   |
<br />

#### Fluxo principal


| Passos  | Descrição                                           |
| ------- | --------------------------------------------------- |
| Passo 1 | O usuário seleciona a opção de visualizar o saldo no menu principal.        |  
| Passo 2 | O usuário seleciona a opção de modificar o saldo
<br />


### User story

**Persona um, usuário comum.**

| User Story                                                                                                                                                              | Critério de aceitação                                         |
 |----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------- |
 Enquanto **um usuário do aplicativo** eu preciso ser capaz de **Modificar meu saldo** para que **eu tenha um controle da minha situação financeira.** | Certifique-se de que o usuário é capaz de **acessar o aplicativo**. |

<br/>

---

## **RF14 - Editar conta bancária**

<br/>

#### Autor: [vinicius Tavares dos Santos](https://github.com/viniciusUFT)

#### Revisor: [Luis FilipeBandeira](https://github.com/luisfilipebandeira) 

<br/>

### Caso de uso

| Item            |Descrição                                                |
| --------------- | ----------------------------------------------------------------------------------- |
| Caso de uso     | RF13 - Editar conta bancária;                                       |
| Resumo          | Responsável pela alteração de dados da conta bancária; |
| Ator principal  | Usuário- Editar conta bancária;                               |
| Ator secundário | -                                                                                   |
| Pré-condição    | Ter acesso ao aplicativo, e ter uma conta adicionada.;                          |
| Pós-condição    | -                                                                                   |

<br/>

#### Fluxo principal

| Passos  | Descrição                                           |
| ------- | --------------------------------------------------- |
| Passo 1 | O usuário faz login no aplicativo             |
| Passo 2 | O usuário seleciona a opção de visualizar conta bancária no menu principal.|
| Passo 3 | O usuário clica em editar conta bancária            |
| Passo 4 | O usuário preenche o formulário com as informações que deseja alterar|
| Passo 5 | O usuário clica em salvar conta bancária|

<br/>

#### Campos do Formulário

| Campo  | Obrigatório | Formato |
| ------- | ---------------------------|----------------------- |
| Nome   | Sim          | Texto    |
| Banco   | Sim          | Texto    |
| Tipo de Conta   | Sim          | Texto    |
| Saldo   | Sim          | Numérico    |
<br />

### User story

**Persona um, usuário comum.**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto um **usuário do aplicativo** eu preciso ser capaz de **editar os dados das minhas contas bancárias** para que **eu possa garantir a veracidade dos dados**. | Certifique-se de que o usuário preencheu corretamente os campos do formulário. 


---

## **RF15 - Editar nome de usuário**

<br/>

#### Autor: [Benedito Jaime](https://github.com/beneX90)

#### Revisor: [vini de Sousa](https://github.com/vinizin1v9)

<br/>

### Caso de uso

| Item            | Descrição                                                                           |
| --------------- | ----------------------------------------------------------------------------------- |
| Caso de uso     | R151 - Editar nome do usuário;                                                       |
| Resumo          | Alterar e salvar o nome que será usado pelo usuário da conta bancária; |
| Ator principal  | Usuário - Mudará o nome;                                                    |
| Ator secundário | -                                                                                   |
| Pré-condição    | O(s) ator(es) deve ter acessado o sistema do aplicativo;                          |
| Pós-condição    | O nome deve ser alterado após a ação.                                            |

<br/>

#### Fluxo principal

| Passos  | Descrição                                           |
| ------- | --------------------------------------------------- |
| Passo 1 | O usuário seleciona a opção de editar o nome no menu principal.            |
| Passo 2 | O sistema exibe o ícone para alterar o nome do usuário. |
| Passo 3 | O usuário digita o novo nome. |
| Passo 4 | O sistema salva o novo nome na conta bancária. |

<br/>

#### Campos do Formulário

| Campo  | Obrigatório | Formato |
| ------- | ---------------------------|----------------------- |
| Nome   | Sim          | Texto    |
| Banco   | Sim          | Texto    |
| Tipo de Conta   | Sim          | Texto    |
| Saldo   | Sim          | Numérico    |

<br />

### User story

**Persona um, usuário comum.**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto **um usuário do aplicativo** eu preciso ser capaz de **alterar o meu nome** para que **eu possa consertar o meu nome, caso eu o tenha errado** | Certifique-se de que o usuário é capaz de **acessar o aplicativo**. 

<br />

## **RF16 - Esconder saldo**

<br/>

#### Autor: [@viniciusHPS3](https://github.com/viniciusHPS3) - vinicius Henrique Pinho Santos

#### Revisor: [viniciuso Eduardo da Silva](https://github.com/viniciusuBrabo)

<br/>

### Caso de uso

| Item            | Descrição                                                                           |
| --------------- | ----------------------------------------------------------------------------------- |
| Caso de uso     | RF02 - Esconder o saldo;                                                       |
| Resumo          | Esconder o saldo para que possa ter uma privacidade sobre sua situação bancaria; |
| Ator principal  | Usuário - Esconder seu saldo;                                                    |
| Ator secundário | -                                                                                   |
| Pré-condição    | O(s) ator(es) deve ter acessado o sistema do aplicativo;                          |
| Pós-condição    | -                                                                                   |

<br/>

#### Fluxo principal

| Passos  | Descrição                                           |
| ------- | --------------------------------------------------- |
| Passo 1 | O usuário seleciona a opção de esconder o saldo no menu principal.            |
| Passo 2 | O sistema oculta o saldo do usuario

<br/>

 ### User story

**Persona um, usuário comum.**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto **um usuário do aplicativo** eu preciso ser capaz de **Esconder meu saldo** para que **eu tenha um controle da minha situação financeira.**| Certificar que todos campos estao preenchidos |

<br/>

---


## **RF17 - Esconder extrato**

<br/>

#### Autor: [@viniciusuBrabo](https://github.com/viniciusuBrabo) - viniciuso Eduardo da Silva

#### Revisor: [vini](https://github.com/MateusAlvez)

<br/>

### Caso de uso

| Item            | Descrição                                                                           |
| --------------- | ----------------------------------------------------------------------------------- |
| Caso de uso     | RF17 - Esconder o extrato do menu principal;                                                       |
| Resumo          | Alterna o estado de visualização do extrato na home da aplicação; |
| Ator principal  | Usuário;                                                    |
| Ator secundário | -                                                                             |
| Pré-condição    | O(s) ator(es) deve ter acessado o sistema do aplicativo;                          |
| Pós-condição    | -                                                                                   |

<br/>

#### Fluxo principal

| Passos  | Descrição                                           |
| ------- | --------------------------------------------------- |
| Passo 1 | O usuário seleciona a opção de esconder a view do extrato do menu principal.            |
| Passo 2 | O sistema esconde a view do extrato habilitado que apareceria no menu principal. |

<br/>

#### Fluxo alternativo
| Passos    | Descrição |
| --------  | --------------------------------------------------------------------------------------------- |
| Passo 1 | O sistema pede para o usuário escolher um período ao qual será mostrato um novo extrato correspondente na home da aplicação.                                                |
| Passo 2 | O sistema habilita a visualização do extrato referente ao período informado na tela inicial.                                                 |

<br/>

### User story

**Persona um, usuário comum.**

| User Story                                        | Critério de aceitação                                 |
| ------------------------------------------------- | ----------------------------------------------------- |
| Enquanto **um usuário do aplicativo** eu preciso ser capaz de **visualizar o  meu extrato na home da aplicação**, para que **eu tenha um acesso rápido aos meus gastos num determinado período.** | Certifique-se de que o usuário é capaz de **acessar o aplicativo**. |

<br/>



## **RF18 - Buscar despesas**

<br/>

#### Autor: [vini](https://github.com/erarich)
#### Revisor: [vinicius Tavares](https://github.com/viniciusUFT)

<br />

### Casos de Uso


|Item             | Descrição                                                           |
| --------------- | -----------------------------------------------------------------   |
| Caso de uso     | Buscar despesas                                                    |
| Resumo          | É esperado que o usuário tenha a possibilidade de buscar as despesas|
| Ator principal  | Usuário que faz uso da plataforma                                   |
| Ator secundário | Não possui                                                          | 
| Pré-condição    | É necessário que o usuário tenha uma conta na plataforma            |
| Pós-condição    | É necessário que para inserir a conta o usuário tenha feito login   |

<br />

#### Fluxo principal

| Passos  | Descrição                                                                   |
| ------- | -----------------------------------------                                   |
| Passo 1 | Entrar no aplicativo e fazer login                                          |
| Passo 2 | Entrar na seção de Despesas                                                 |
| Passo 3 | Clicar no barra de pesquisa                                                 |
| Passo 4 | Digitar texto que deseja buscar                                             |
| Passo 5 | Clicar no ícone de pesquisar (uma lupa)                                     |
<br />


#### Opções do usuário


| Opção         | Descrição                 | Atalho |
| ------------- | ------------------------- | ------ |
| Buscar despesa | Clicar no ícone de pesquisar  |        |
<br />

#### Relatório de usuário

| Campo                      | Descrição                                                             | Formato |
| -------------------------- | --------------------------------------------------------------------- | ------- |
| Despesas encontradas com sucesso | Isso confirma e garante todo êxito na operação de busca de despesas   | Texto   |

<br />

                                   
### User Story

**Persona um, usuário comum.**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto "usuário comum" preciso ter acesso às minhas despesas registradas na plataforma a fim de visualizar e monitorar meu histórico de gastos | Certificar que a busca retorna as despesas corretas de acordo com os filtros selecionados, como data, categoria ou valor.

<br/>

## **RF19 - Buscar receitas**

<br/>

#### Autor: [Ícaro Mesquita Ponce](https://github.com/icaromp)
#### Revisor: [vinicius Henrique Pinho](https://github.com/viniciusHPS3)

<br />

### Casos de Uso


|Item             | Descrição                                                           |
| --------------- | -----------------------------------------------------------------   |
| Caso de uso     | Buscar receitas                                                     |
| Resumo          | É esperado que o usuário tenha a possibilidade de buscar as receitas|
| Ator principal  | Usuário que faz uso da plataforma                                   |
| Ator secundário | Não possui                                                          | 
| Pré-condição    | É necessário que o usuário tenha uma conta na plataforma            |
| Pós-condição    | É necessário que para inserir a conta o usuário tenha feito login   |


<br />

#### Fluxo principal

| Passos  | Descrição                                                                   |
| ------- | -----------------------------------------                                   |
| Passo 1 | Entrar no aplicativo e fazer login                                          |
| Passo 2 | Entrar na seção de Receitas                                                 |
| Passo 3 | Clicar no barra de pesquisa                                                 |
| Passo 4 | Digitar texto que deseja buscar                                             |
| Passo 5 | Clicar no ícone de pesquisar (uma lupa)                                     |
<br />


#### Opções do usuário


| Opção         | Descrição                 | Atalho |
| ------------- | ------------------------- | ------ |
| Buscar receita | Clicar no ícone de pesquisar  |        |
<br />

#### Relatório de usuário

| Campo                      | Descrição                                                             | Formato |
| -------------------------- | --------------------------------------------------------------------- | ------- |
| Receitas encontradas com sucesso | Isso confirma e garante todo êxito na operação de busca de receitas   | Texto   |
<br />

                                   
### User Story

**Persona um, usuário comum.**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto "usuário comum" preciso ter acesso às minhas receitas registradas na plataforma a fim de visualizar e monitorar meu histórico de entradas | Certificar que a busca retorna as receitas corretas de acordo com os filtros selecionados, como data, categoria ou valor.

<br/>

## **RF20 - Visualizar extrato no mês.**

<br/>

#### Autor: [@vinizin1v9](https://github.com/vinizin1v9) - vini de Sousa Barbosa

#### Revisor: [@jpnoronhaa](https://github.com/jpnoronhaa) - João Pedro Noronha

<br/>

### Caso de uso

|Item             | Descrição                                                         |
| --------------- | ----------------------------------------------------------------- |
| Caso de uso     | RF20 - Visualizar extrato no mês                                              |
| Resumo          | É esperado que o usuário tenha a possibilidade de visualizar o extrato no mês que desejar     |
| Ator principal  | Usuário que faz uso da plataforma                                                             |
| Ator secundário | Não possui                                                                                    | 
| Pré-condição    | É necessário que o usuário tenha uma conta na plataforma e ter inserido receitas e/ou despesas|
| Pós-condição    | Não possui |

<br/>

#### Fluxo principal
| Passos  | Descrição                                 |
| ------- | ----------------------------------------- |
| Passo 1 | Entrar no aplicativo e fazer login        |
| Passo 2 | Estar no aplicativo e clicar no botão 'Visualizar extrato'|
| Passo 3 | Selecionar a opção de filtragem e escolher o mês|

<br/>

#### Campos do formulário
| Campo            | Obrigatório? | Editável? | Formato      |
| ---------------- | ------------ | --------- | ------------ |
| Extrato          | Não          | Não       | Texto        |

<br/>

#### Opções do usuário
| Opção             | Descrição                 | Atalho |
| -------------     | ------------------------- | ------ |
| Alterar o mês | Alterar o mês que deseja visualizar o extrato   |        |

<br/>

#### Relatório de usuário

| Campo      | Descrição   | Formato |
| ---------- | ----------- |---------|
| Não possui |             |         |

<br/>

#### Fluxo alternativo
| Passos    | Descrição |
| --------  | --------------------------------------------------------------------------------------------- |
| Passo 1.1 | O usuário não possui nenhuma receita e nenhuma despesa no mês selecionado                                                       |
| Passo 1.2 | O sistema informa que não há extrato naquele mês                                            |

<br/>

### User Story

**Persona um, usuário comum.**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto **usuário do aplicativo** preciso ser capaz de **visualizar o extrato do mês que eu necessitar ver** para que **eu tenha um controle maior da minha situação financeira** | O extrato financeiro exibido deve incluir todas as transações que ocorreram durante o mês selecionado, incluindo a data da transação, o valor e uma breve descrição.

<br/>

## **RF21 - Deletar Conta (valor) no mês.**

<br/>

#### Autor: [João Pedro Noronha](https://github.com/jpnoronhaa)
#### Revisor: [Wilque Muriel do Nascimento Coelho](https://github.com/uiuqM)

<br/>

### Caso de uso

|Item             | Descrição                                                         |
| --------------- | ----------------------------------------------------------------- |
| Caso de uso     | Deletar Conta (valor) no mês                                            |
| Resumo          | O usuário deve poder remover o valor da conta em um determinado mês             |
| Ator principal  | Usuário que faz uso da plataforma |
| Ator secundário | Não possui                                                        | 
| Pré-condição    | É necessário que o usuário tenha inserido uma conta no mês em que está          |
| Pós-condição    | É necessário que para remover uma conta, ela já deva estar previamente cadastrada |

<br />

#### Fluxo principal
| Passos  | Descrição                                 |
| ------- | ----------------------------------------- |
| Passo 1 | Entrar no aplicativo                      |
| Passo 2 | Abrir a conta e o mês que ele quer excluir    |
| Passo 3 | Clicar nas opções e selecionar excluir    |
| Passo 4 | Confirmar a exclusão                      |

<br />

#### Campos do formulário
| Campo            | Obrigatório? | Editável? | Formato      |
| ---------------- | ------------ | --------- | ------------ |
| Conta            | Sim          | Sim       | Texto        |
| Mês            | Sim          | Sim       | Data        |
| Confirmar exclusão          | Sim          | Sim       | Texto     |

<br />

#### Opções do usuário

| Opção         | Descrição                 | Atalho |
| ------------- | ------------------------- | ------ |
| Deletar conta | Confirmar a exclusão      |        |

<br />

#### Relatório de usuário
| Campo                      | Descrição                                                             | Formato |
| -------------------------- | --------------------------------------------------------------------- | ------- |
| Conta excluída com sucesso | Isso confirma e garante todo êxito na operação de exclusão de conta   | Texto   |

<br />

#### Fluxo alternativo
| Não possui |

<br />

### User Story

**Persona um, usuário comum.**
| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto "usuário comum" preciso ter minhas informações deletadas com garantia de que nada ficou | Certificar de confirmar a exclusão

<br/>

## **RF22 - Deletar Conta Bancaria**

<br/>

#### Autor: [@98loann](https://github.com/98loann)
#### Revisor: [Sophia Menezes Pontes](https://github.com/SophiaMenezes)

<br/>

### Caso de uso

|Item             | Descrição                                                         |
| --------------- | ----------------------------------------------------------------- |
| Caso de uso     | Deletar conta Bancária                                            |
| Resumo          | É esperado que o usuário tenha a possibilidade de remover as conta bancárias que ele já inseriu                                                                              |
| Ator principal  | Usuário que faz uso da plataforma |
| Ator secundário | Não possui                                                        | 
| Pré-condição    | É necessário que o usuário tenha uma conta bancaria ja inserida          |
| Pós-condição    | É necessário que para remover uma conta, ela já deva estar previamente cadastrada |

<br />

#### Fluxo principal
| Passos  | Descrição                                 |
| ------- | ----------------------------------------- |
| Passo 1 | Entrar no aplicativo                      |
| Passo 2 | Abrir a conta na qual ele quer excluir    |
| Passo 3 | Clicar nas opções e selecionar excluir    |
| Passo 4 | Confirmar a exclusão                      |

<br />

#### Campos do formulário
| Campo            | Obrigatório? | Editável? | Formato      |
| ---------------- | ------------ | --------- | ------------ |
| Banco            | Sim          | Sim       | Texto        |
| Confirmar exclusão          | Sim          | Sim       | Texto     |

<br />

#### Opções do usuário

| Opção         | Descrição                 | Atalho |
| ------------- | ------------------------- | ------ |
| Deletar banco | Confirmar a exclusão      |        |

<br />

#### Relatório de usuário
| Campo                      | Descrição                                                             | Formato |
| -------------------------- | --------------------------------------------------------------------- | ------- |
| Banco deletado com sucesso | Isso confirma e garante todo êxito na operação de exclusão do banco   | Texto   |

<br />

#### Fluxo alternativo
| Não possui |

<br />

### User Story

**Persona um, usuário comum.**
| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto "usuário comum" preciso ter minhas informações deletadas com garantia de que nada ficou | Certificar de confirmar a exclusão

<br/>

## **RF23 - Deletar cartão de crédito**

<br/>

#### Autor: [Luis Filipe Bandeira](https://github.com/luisfilipebandeira)
#### Revisor: [vini](https://github.com/erarich)

<br/>

### Caso de uso

|Item             | Descrição                                                         |
| --------------- | ----------------------------------------------------------------- |
| Caso de uso     | Deletar cartão de crédito                                           |
| Resumo          | O usuário deve poder remover o cartão de crédito do app             |
| Ator principal  | Usuário que faz uso da plataforma |
| Ator secundário | Não possui                                                        | 
| Pré-condição    | É necessário que o usuário tenha inserido um cartão de crédito          |
| Pós-condição    | É necessário que para remover um cartão de crédito, ele já deva estar previamente cadastrado |

<br />

#### Fluxo principal
| Passos  | Descrição                                 |
| ------- | ----------------------------------------- |
| Passo 1 | Entrar no aplicativo                      |
| Passo 2 | Editar cartões    |
| Passo 3 | Clicar nas opções e selecionar excluir    |
| Passo 4 | Confirmar a exclusão                      |

<br />

#### Opções do usuário

| Opção         | Descrição                 | Atalho |
| ------------- | ------------------------- | ------ |
| Deletar cartão | Confirmar a exclusão      |        |

<br />

#### Relatório de usuário
| Campo                      | Descrição                                                             | Formato |
| -------------------------- | --------------------------------------------------------------------- | ------- |
| Cartão excluído com sucesso | Isso confirma e garante todo êxito na operação de exclusão do cartão  | Texto   |

<br />

#### Fluxo alternativo
| Não possui |

<br />

### User Story

**Persona um, usuário comum.**
| User Story | Critério de aceitação |
| --------- | --------------------- |
| Eu enquanto "usuário comum" quero "ter o poder de entrar no aplicativo e excluir os cartões de crédito que já cadastrei" | Certificar de confirmar a exclusão

<br/>

## **RF24 - Sair do Aplicativo**

<br/>

#### Autor: [Marcos Vinicius Barbosa e Silva](https://github.com/eziors)
#### Revisor: [Benedito Jaime](https://github.com/orgs/Turma-2023-1-Engenharia-de-Software/people/beneX90)

<br />

### Casos de Uso


|Item             | Descrição                                                           |
| --------------- | -----------------------------------------------------------------   |
| Caso de uso     | Sair do aplicativo                                                    |
| Resumo          | Usuário deve ter a possibilidade de sair do aplicativo|
| Ator principal  | Usuário que utiliza a plataforma                                   |
| Ator secundário | Não possui                                                          | 
| Pré-condição    | É necessário que o usuário esteja no aplicativo            |
| Pós-condição    | É necessário que para sair da conta o usuário tenha aberto o aplicativo  |

<br />

#### Fluxo principal

| Passos  | Descrição                                                                   |
| ------- | -----------------------------------------                                   |
| Passo 1 | Entrar no aplicativo (Login não é obrigatório)                                     |
| Passo 2 | Sair do aplicativo atráves da opção de saída(Ícone seguido por nome)                                    |
<br />


#### Opções do usuário


| Opção         | Descrição                 | Atalho |
| ------------- | ------------------------- | ------ |
| Sair do aplicativo | Clicar no nome/ícone de saída   |        |
<br />

#### Relatório de usuário

| Campo                      | Descrição                                                             | Formato |
| -------------------------- | --------------------------------------------------------------------- | ------- |
| Saindo do aplicativo... | Isso confirma e garante todo êxito na operação de saída do aplicativo, encerramento o mesmo.   | Texto   |

<br />

                                   
### User Story

**Persona um, usuário comum.**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto "usuário comum" preciso ter acesso a alguma opção de saída do aplicativo. | Certificar de que usuário conseguiu sair do aplicativo.

<br/>

## **RF25 - Filtrar contas de Crédito**

#### Autor: [@SophiaMenezes](https://github.com/SophiaMenezes) - Sophia Menezes Pontes


#### Revisor: [Luan Porto](https://github.com/98loann)

<br/>

## Caso de uso

| Item            | Descrição                                                                           |
| --------------- | ----------------------------------------------------------------------------------- |
| Caso de uso     | RF25 - Filtragem das contas de Crédito;                                             |
| Resumo          | O usuário pode filtrar suas contas de crédito por saldo, limite de crédito e data de vencimento da próxima fatura;   |
| Ator principal  | Usuário do aplicativo de controle financeiro;                                       |
| Ator secundário | -                                                                                   |
| Pré-condição    | Usuário já deve ter uma conta de crédito cadastrada no aplicativo;                  |
| Pós-condição    | -                                                                                   |

<br/>

#### Fluxo principal

| Passos  | Descrição                                           |
| ------- | --------------------------------------------------- |
| Passo 1 | O usuário seleciona a opção de visualizar "contas de crédito" no menu principal;            |
| Passo 2 | O aplicativo exibe uma lista de todas as contas de crédito associadas à conta do usuário;   |
| Passo 3 | O usuário seleciona a opção de filtragem desejada: por saldo, por limite de crédito ou por data de vencimento da próxima fatura; |
| Passo 4 | O usuário insere o critério de filtro desejado, como um valor mínimo ou máximo de saldo ou limite de crédito, ou uma data de vencimento específica; |
| Passo 5 | O aplicativo filtra as contas de crédito com base nos critérios inseridos pelo usuário e exibe apenas as contas que atendem aos critérios de filtro; |


## User story

*Persona um, usuário comum.*

| User Story                                                                                                                                                              | Critério de aceitação                                         |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------- |
| "Como usuário do aplicativo de controle financeiro, eu gostaria de filtrar minhas contas de crédito por saldo, limite de crédito e data de vencimento da próxima fatura, para que eu possa visualizar apenas as contas que atendem aos meus critérios de filtro e ter uma melhor compreensão da minha situação financeira em relação a cada conta de crédito." | O aplicativo deve permitir a seleção de uma ou mais opções de filtro para as contas de crédito: saldo, limite de crédito e data de vencimento da próxima fatura. |

<br/>


## **RF26-Deletar despesas**
<br/>

#### Autor: [Wilque Muriel do Nascimento Coelho](https://github.com/uiuqM) 

#### Revisor: [Marcos Vinicius Barbosa e Silva](https://github.com/eziors)

<br/>

### Caso de uso

Item	          |Descrição
:----------------:|:--------------------------------:
Caso de uso	      | Deletar despesas do usuário.
Resumo            | O usuário deseja deletar as suas despesas.
Ator principal	  | Usuário
Pré-condição	  | Existam despesas constando para o usuário em seu histórico.
Pós-condição	  | O usuário consegue deletar suas despesas da forma desejada.

<br/>

#### Fluxo principal

Passos	  |Descrição
:--------:|:-----------------------------------------------:
Passo 01  |O usuário acessa o app.
Passo 02  |O usuário abre as suas despesas
Passo 03  |O usuário seleciona a opção de deletar a despesa.
Passo 04  |O usuário comfirma a opção.

<br/>

#### Opções de usuário


Opção          |Descrição
---------------|----------------
Deletar despesas|Deleta a despesa.
<br />

### User Story

User story|	Critério de aceitação
-------------|--------------------
Enquanto ator quando visualizo minhas despesas gostaria de poder deleta-las.|	Ator necessita ter despesas para deletar.

<br/>

## **RF27-Editar cartão de crédito**

<br/>

#### Autor: [Mateus Alves Araújo](https://github.com/MateusAlvez)
#### Revisor: [Ícaro Mesquita Ponce](https://github.com/icarompo)

<br />

### Casos de Uso


|Item             | Descrição                                                           |
| --------------- | -----------------------------------------------------------------   |
| Caso de uso     | Editar cartão de crédito                                                   |
| Resumo          | Edição dos dados de cartão de crédito 
| Ator principal  | Usuário que faz uso da plataforma  -Editar cartão                                 |
| Ator secundário | Não possui                                                          | 
| Pré-condição    | Ter acesso ao aplicativo, e ter pelo menos um cartão adicionado.|
| Pós-condição    | - |

<br />

#### Fluxo principal

| Passos  | Descrição                                                                   |
| ------- | -----------------------------------------                                   |
| Passo 1 | O usuário acessa o sistema de gerenciamento de cartões de crédito                                         |
| Passo 2 | O usuário seleciona a opção "Meus cartões de crédito" na página inicial do sistema                                                 |
| Passo 3 | O usuário localiza o cartão de crédito que deseja editar na lista de cartões e clica no botão "Editar"                                                 |
| Passo 4 | O sistema exibe uma página de edição para o cartão de crédito selecionado, com todos os campos disponíveis para edição                                             |
<br />


#### Opções do usuário


| Opção         | Descrição                 | Atalho |
| ------------- | ------------------------- | ------ |
| Buscar cartão | Clicar no ícone de editar cartão  |        |
<br />

#### Relatório de usuário

| Campo                      | Descrição                                                             | Formato |
| -------------------------- | --------------------------------------------------------------------- | ------- |
| Cartão editado com sucesso | Isso confirma e garante todo êxito na operação de edição de cartão   | Texto   |
<br />

                                   
### User Story

**Persona um, usuário comum.**

| User Story | Critério de aceitação |
| --------- | --------------------- |
|<br> Como usuário, eu quero ser capaz de acessar minha lista de cartões de crédito existentes dentro do sistema e selecionar o cartão que desejo editar. Eu quero ter a opção de editar todas as informações do cartão de crédito, incluindo o número do cartão, nome do titular do cartão, data de vencimento, endereço de cobrança, informações de segurança, limite de crédito e outros detalhes importantes.| Certifique-se de que o usuário é capaz de acessar o aplicativo, ter um cartão já cadastrado


<br/>

## **RF28 - Exportar conteúdo**

#### Autor: [vinicius Tavares dos Santos](https://github.com/viniciusUFT)

#### Revisor: [Luis FilipeBandeira](https://github.com/luisfilipebandeira) 

<br/>
## Caso de uso

| Item            |Descrição                                                |
| --------------- | ----------------------------------------------------------------------------------- |
| Caso de uso     | RF28 - Exportar conteúdo;                                       |
| Resumo          | Responsável por salvar os dados do aplicativo em um arquivo externo; |
| Ator principal  | Usuário- Exportar conteúdo;                               |
| Ator secundário | -                                                                                   |
| Pré-condição    | Ter acesso ao aplicativo, ter uma conta adicionada, ter dados para serem salvos.;                          |
| Pós-condição    | -                                                                                   |
<br/>
#### Fluxo principal

| Passos  | Descrição                                           |
| ------- | --------------------------------------------------- |
| Passo 1 | O usuário faz login no aplicativo             |
| Passo 2 | O usuário seleciona a opção de configurações no menu principal.|
| Passo 3 | O usuário clica em exportar conteúdo |
| Passo 4 | O usuário seleciona o endereço onde o arquivo deve ser salvo|
| Passo 5 | O usuário clica em confirmar exportação de conteúdo|


## User story

**Persona um, usuário comum.**

| User Story                                                                                                                                                              | Critério de aceitação                                         |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------- |
| Enquanto **um usuário do aplicativo** eu preciso ser capaz de **Exportar conteúdo** para que **eu possa fazer backup dos meus dados por meio do arquivo gerado da exportação.** | Certifique-se de que o usuário selecionou um **endereço válido** para o salvamento do arquivo. |
