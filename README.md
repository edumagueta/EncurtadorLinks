# URL Shortener - AWS Serverless Project

Este projeto é uma implementação de um encurtador de URLs utilizando tecnologias serverless da AWS, como Lambda, S3 e API Gateway. Ele foi desenvolvido durante um curso em parceria com a **Rocketseat** e **Fernanda Kipper**.

## Tecnologias Utilizadas

- **Java**: Linguagem de programação principal do projeto.
- **AWS Lambda**: Para execução de funções sem necessidade de gerenciamento de servidores.
- **Amazon S3**: Para armazenamento das URLs encurtadas e seus dados.
- **API Gateway**: Para gerenciar as chamadas HTTP ao sistema.
- **Maven**: Gerenciador de dependências e build do projeto.
- **Lombok**: Para reduzir boilerplate no código Java.

## Funcionalidades

- **Encurtamento de URLs**: Recebe uma URL longa e gera uma versão curta única.
- **Redirecionamento**: Redireciona automaticamente para a URL original a partir do código gerado.
- **Armazenamento de Dados**: Armazena os dados da URL no S3, incluindo tempo de expiração.
- **Serverless**: Implementação baseada em arquitetura sem servidor, escalável e econômica.

## Como Funciona

1. O usuário envia a URL original e o tempo de expiração.
2. O sistema gera um código curto único.
3. O código e os dados são armazenados no S3.
4. O API Gateway redireciona as solicitações do código curto para a URL original.

## Autor

Projeto realizado em parceria com a **Rocketseat** e **Fernanda Kipper**.
