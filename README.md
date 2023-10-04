# Desafio Back-end PicPay
Este repositório contém a minha solução para o desafio de back-end do PicPay, um dos maiores players do setor de pagamentos no mundo. Neste desafio, desenvolvi uma aplicação que atende aos requisitos especificados para transferência de dinheiro entre usuários comuns e lojistas. A seguir, você encontrará informações sobre a estrutura da aplicação, os requisitos atendidos e as escolhas de tecnologia feitas durante o desenvolvimento.

## Sobre a Aplicação
A aplicação desenvolvida para o desafio do PicPay é uma API RESTful que permite a transferência de dinheiro entre dois tipos de usuários: comuns e lojistas. Ambos os tipos de usuários têm informações essenciais como Nome Completo, CPF, e-mail e senha. O sistema garante que CPF/CNPJ e e-mails sejam únicos, evitando múltiplos cadastros com os mesmos dados.

## Principais funcionalidades:

- Cadastro de usuários comuns e lojistas.
- Transferência de dinheiro entre usuários comuns e lojistas. 
- Validação de saldo antes da transferência. 
- Consulta a um serviço autorizador externo antes de finalizar a transferência. 
- Tratamento de notificações de pagamento enviado por um serviço de terceiros (simulado). 
- Requisitos Atendidos 
- Cadastro de usuários com validação de CPF/CNPJ e e-mail únicos. 
- Transferência de dinheiro entre usuários, com validação de saldo. 
- Consulta a um serviço autorizador externo antes de finalizar a transferência. (O serviço está offine, por esse motivo ele sempre vai retornar TRUE)
- 
## Tecnologias Utilizadas
Neste projeto, optei por utilizar Java com Spring Boot Para praticar e desenvolver minhas habilidades na linguagem e framework.

## Estrutura da Aplicação
A estrutura da aplicação segue uma arquitetura MVC, que permite um desenvolvimento organizado e escalável. O código segue padrões de qualidade e boas práticas, como PSRs, design patterns e SOLID.

## Como Executar a Aplicação
1. Certifica-se de ter o Java instalado na maquina.
2. Clone o meu repositorio 
3. execute o projeto

## Perfil oficial do projeto
[Liink do desafio](https://github.com/PicPay/picpay-desafio-backend)

## Contato
Se você tiver alguma dúvida ou precisar de mais informações sobre esta solução, sinta-se à vontade para entrar em contato comigo pelos links abaixo.

[Instagram](https://www.instagram.com/jeova_leite/)

[GitHub](https://github.com/Jeova-1704)

[Linkedin](https://www.linkedin.com/in/jeov%C3%A1-bezerra-leite-29127826a/)

[E-mail](mailto:jeovab115@gmail.com?subject=Projeto no GitHub&body=)