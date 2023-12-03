  # Api REST e RESTFul

REST é uma abreviatura em inglês para “Representational State Transfer”.
REST não é um protocolo ou padrão, mas sim um conjunto de restrições arquitetônicas. Os desenvolvedores de API podem implementar a arquitetura REST de várias maneiras. Quando um cliente faz uma solicitação usando uma API RESTful, essa API envia uma representação do estado do recurso ao solicitante ou endpoint. Essas informações (ou representação) são entregues por HTTP, normalmente usando o formato Javascript Object Notation (JSON), pois são independentes de qualquer outra linguagem e podem ser lidas por máquinas e humanos.

## Diferenças entre REST e RESTFul

REST refere-se a um conjunto de princípios arquiteturais para o design de serviços web. Uma API pode ser considerada REST mesmo que não siga todos esses princípios estritamente.

Por outro lado, RESTful é uma implementação específica que adere de forma rigorosa a todos os princípios do REST. Isso implica em seguir estritamente a statelessness, utilizar métodos HTTP padrão (GET, POST, PUT, DELETE) de acordo com as operações em recursos, e seguir práticas consistentes de URIs.

## HTTP verbs
O protocolo HTTP define um conjunto de métodos de requisição responsáveis por indicar a ação a ser executada para um dado recurso.


POST: cria um novo recurso.
PUT: atualiza um recurso existente.
OPTIONS: é usado para descrever as opções de comunicação com o recurso de destino.
DELETE: remove um recurso.
HEAD: retorna apenas os cabeçalhos de uma resposta HTTP.
GET: solicita a representação de um recurso.
PATCH: realiza modificações parciais em um recurso.
CONNECT: estabelece uma conexão com um recurso identificado pelo URI.
TRACE: executa um teste de chamada loop-back junto com o caminho para o recurso de destino.


## HTTP Status Code

Os códigos de status HTTP são códigos numéricos retornados pelo servidor web em resposta a uma requisição feita pelo cliente, indicando o resultado da solicitação. Esses códigos são divididos em cinco classes e cada classe possui uma série de códigos específicos.

#### Code and Description

   1xx: Informational
      Isso significa que a solicitação foi recebida e o processo continua.

   2xx: Success
      Significa que a ação foi recebida, compreendida e aceita com sucesso.

   3xx: Redirection
      Isso significa que outras ações devem ser tomadas para concluir a solicitação.

   4xx: Client Error
      Isso significa que a solicitação contém sintaxe incorreta ou não pode ser atendida.

   5xx: Server Error
      Isso significa que o servidor não atendeu a uma solicitação aparentemente válida.


---

    Autor do resumo: João Victor da Silva Carvalho - 01549930

