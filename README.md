# Projeto de Cadastro de Funcionários com Spring Boot

Este é um projeto de exemplo de um sistema de cadastro de funcionários usando Spring Boot, Spring MVC, Spring Data JPA e banco de dados H2. O sistema permite que você realize operações CRUD (Create, Read, Update, Delete) em registros de funcionários, incluindo informações como nome, salário, e-mail, data de admissão e situação (ativo ou inativo).

## Requisitos

Antes de começar, você precisará ter o seguinte software instalado em sua máquina:

- Java Development Kit (JDK) 8 ou superior
- Maven
- Um IDE Java (por exemplo, IntelliJ IDEA, Eclipse) - Opcional

## Configuração do Banco de Dados

O projeto utiliza o banco de dados H2 em memória para armazenar os dados dos funcionários. Não é necessário configurar um banco de dados externo. A configuração do banco de dados pode ser encontrada no arquivo `src/main/resources/application.properties`.

## Executando o Projeto

Para executar o projeto, siga estas etapas:

1. Clone este repositório para o seu sistema local:
 
2. Navegue até o diretório do projeto:
. 
3. Execute o aplicativo Spring Boot usando o Maven:


4. O aplicativo estará disponível em `http://localhost:8080`. Você pode acessar a interface do sistema em seu navegador da web.

## Uso do Sistema

- Acesse a página inicial do sistema em `http://localhost:8080`.
- Na página inicial, você verá uma lista de funcionários cadastrados (inicialmente vazia).
- Para adicionar um novo funcionário, clique no botão "Novo Funcionário" e preencha os campos necessários.
- Para editar ou excluir um funcionário, clique nos links correspondentes na lista de funcionários.
- Você pode pesquisar funcionários pelo nome, e-mail ou situação usando o campo de pesquisa na página inicial.

## Estrutura do Projeto

O projeto segue uma estrutura de projeto típica do Spring Boot com camadas MVC e JPA. A estrutura de diretórios inclui:

- `src/main/java/com/seu/pacote`: Contém as classes Java do projeto.
- `src/main/resources`: Contém arquivos de configuração, incluindo o arquivo `application.properties` para configuração do banco de dados.
- `src/main/webapp`: Contém recursos da web, como arquivos HTML, CSS e JavaScript.
- `src/test`: Contém classes de teste.

## Contribuição

Contribuições para este projeto são bem-vindas. Sinta-se à vontade para abrir problemas (issues) e enviar pull requests.

## Licença

Este projeto é licenciado sob a [Licença MIT](LICENSE).







