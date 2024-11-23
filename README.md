# Java na Prática com AWS ![Image de xícara com café](docs/coffe.svg)

## Curso Java - AWS Lambda

Descrição retirada do Notion feito pela [@Fernanda-Kipper](https://github.com/Fernanda-Kipper) e [@Rocketseat](https://github.com/rocketseat-education/)

### Projeto

O projeto trata-se de um **sistema de encurtamento de URLs** utilizando a AWS como infraestrutura
serverless. O objetivo é permitir que os usuários criem URLs curtas que redirecionem para URLs
originais, com um tempo de expiração configurável. O sistema é composto por duas funções
Lambda: a primeira função é responsável por **gerar e armazenar** os links encurtados em um bucket
S3, junto com informações como a URL original e o tempo de expiração; a segunda função **gerencia
o redirecionamento**, verificando o código da URL curta e validando se a URL ainda está dentro do
prazo de expiração antes de redirecionar o usuário.

![Imagem do projeto](docs/projeto.png)

## Repositórios originais do projeto e curso <img src="https://user-images.githubusercontent.com/25181517/192108374-8da61ba1-99ec-41d7-80b8-fb2f7c0a4948.png" alt="Imagem do GitHub" width="30px" heigth="30px">

[Repositório da Aula 01 e 02](https://github.com/rocketseat-education/curso-java-aws-lambda-generate-shortner-url)

[Repositório da Aula 03](https://github.com/rocketseat-education/curso-java-aws-lambda-generate-shortner-url)

## Notion

## [<img src="docs/logojava.png" alt="Logo Java" width="35"> Guia do curso gratuito de Java](https://efficient-sloth-d85.notion.site/Guia-do-curso-gratuito-de-Java-d19bee9b1e3049038f6cf828334821a6)

## [<img src="/docs/java.png" alt="Logo Java Notion" width="40px">Curso Java - AWS Lambda](https://efficient-sloth-d85.notion.site/Curso-Java-AWS-Lambda-725cedf305da44c69c847db4e3bad657)

## [<img src="/docs/coffe.svg" alt="Imagem xícara com cafe" width="35px"> Java na Prática by AWS](https://metal-flea-041.notion.site/Java-na-Pr-tica-by-AWS-1172014141ff8022a3e4ee81c99c2e57)

## Tecnologias utilizadas

[![Tecnologias utilizadas](https://skillicons.dev/icons?i=idea,java&theme=dark)](https://skillicons.dev)
<img width="50" src="https://user-images.githubusercontent.com/25181517/117207242-07d5a700-adf4-11eb-975e-be04e62b984b.png" alt="Maven" title="Maven"/>
<img width="40" src="https://user-images.githubusercontent.com/25181517/190229463-87fa862f-ccf0-48da-8023-940d287df610.png" alt="Lombok" title="Lombok"/>

[![Tecnologias utilizadas](https://skillicons.dev/icons?i=aws,git,github,notion&theme=dark)](https://skillicons.dev)
