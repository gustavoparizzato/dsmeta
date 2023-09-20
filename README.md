# Listagem de Vendedores

Este é um projeto de gerenciamento de vendedores e vendas que utiliza Java (Spring Boot) no backend e JavaScript com React no frontend. Além disso, ele faz uso da API de mensagens do Twilio para enviar notificações SMS com informações sobre o vendedor e seu valor total de vendas.
O Site lista os vendedores com seus respectivos valores totais vendidos no período selecionado, em caso de não alteração é filtrado como padrão o intervalo de 1 ano. Contudo, ao lado de cada vendedor é exibido o botão de enviar o SMS que represente seus dados.

Projeto realizado juntamente ao evento realizado pela @devsuperior

### Tecnologias Utilizadas

- Java 17 com Spring Boot
- Hibernate
- Maven
- JPA
- Twilio API

- JavaScript com React
- Bootstrap
- Yarn
- Axios

## API de Mensagens

Neste projeto é utilizado a API do Twilio API para envio de mensagens SMS. Disparando ao destinatário o nome do cliente e o valor total de suas vendas.

### Funcionalidades

O projeto oferece as seguintes funcionalidades:

- Listagem de vendedores com os valores totais de vendas no período.
- Permissão para alteração de período.
- Botão disponibiliazado para envio de SMS do respectivo vendedor.

### Arquitetura 

Este projeto foi desenvolvido seguindo o padrão de arquitetura Model-View-Controller (MVC) para criar a API RESTful.
O padrão MVC foi escolhido para garantir uma separação clara de preocupações, tornando o projeto mais organizado e escalável.
