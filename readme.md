## Desafio BugBank

<div align="center">
<img src="bugbank.png" height="100" alt="Quantidade de Testes"  />
</div>

## 📋 Descrição

Este projeto foi criado como atividade final no bootcamp AVANTI 2026.2, focando em automação de testes utilizando Selenium e Python. O objetivo principal foi garantir a qualidade e confiabilidade das funcionalidades da aplicação Bugbank através de testes automatizados. O projeto abrange todo o ciclo de testes, desde o planejamento até a implementação.

## 🚀 Tecnologias Utilizadas

- Python: Linguagem principal utilizada para escrever os testes.
- Selenium: Ferramenta para automação de navegadores, utilizada para interagir com a interface da aplicação Bugbank.
- JUnit: Framework de testes utilizado para estruturar e executar os testes automatizados.

### 🛠️ Funcionalidades Implementadas

- Planejamento de Testes: Criação de um plano de testes completo, cobrindo todas as funcionalidades críticas da aplicação Bugbank.
- Cenários de Testes: Definição de cenários de testes claros e abrangentes, garantindo a cobertura de todos os casos de uso.
- Automação: Implementação da automação de testes com Selenium e Java, permitindo a execução repetida dos testes de forma eficiente.
- Integração com Cucumber: Escrita dos testes em Gherkin, permitindo a criação de testes legíveis e fáceis de entender.

### 🔍 Como Executar

Passo-a-passo para que você tenha um ambiente de desenvolvimento em execução.

1. Clone o repositório:

   ```sh
   git clone https://github.com/olavoanselmo/QA_BugBank.git
   ```

2. Navegue até o diretório do projeto:

   ```sh
   cd Automacao
   ```

3. Compile o projeto usando Maven:

   ```sh
   mvn clean install
   ```

4. Execute os testes:
   ```sh
   mvn test
   ```

### 🔩 Resultado dos Testes

Confira o resultado abaixo resultado aa execução dos testes automatizados:

<div align="center">
<img src="./Test.png" height="300" alt="Quantidade de Testes"  />
</div>

## 📦 Estrutura do Projeto

```plaintext
|-- src/
|   |-- main/
|   |   |-- java/
|   |   |   |-- pages/
|   |   |   |-- utils/
|   |-- test/
|   |   |-- java/
|   |   |   |-- hooks/
|   |   |   |-- runners/
|   |   |   |-- steps/
|   |   |-- resources/
|   |   |   |-- features/
|-- pom.xml
|-- README.md
```

## Referência

- [Documentação Selenium Boas Práticas.](https://www.selenium.dev/pt-br/documentation/test_practices/design_strategies/)
- [Documentação cucummber](https://cucumber.io/docs/cucumber/)
- [Site BugBank](https://bugbank.netlify.app/)

## ✒️ Autores

Mencione todos aqueles que ajudaram a levantar o projeto desde o seu início

- [Linkedin](https://www.linkedin.com/in/chaiene-caroline/)
