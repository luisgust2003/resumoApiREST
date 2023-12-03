# Api REST e RESTFul

  Api REST, que também pode ser chamada de Api RESTful, é uma interface de programação de aplicações que é utilizada se adequando à arquitetura REST. REST (Representational State Transfer) é um conjunto de restrições baseado em princípios fundamentais da arquitetura web, o REST utiliza uma abordagem cliente-servidor e identifica recursos por meio de URLs. A comunicação entre cliente e servidor é realizada por métodos HTTP como GET, POST, PUT e DELETE.
  APIs RESTful são amplamente utilizadas na construção de serviços web devido à sua simplicidade, flexibilidade e eficiência. Elas são comuns em aplicações web, mobile e integração de sistemas distribuídos.

## HTTP verbs

Os HTTP Verbs, também chamado de métodos HTTP, são métodos de ações que indicam como interagir com um recurso.

GET - O método GET obtém informações sobre um recurso.

HEAD - O método HEAD é semelhante ao método GET, porém ele solicita uma resposta sem conter o corpo da resposta, apenas o cabeçalho.

POST - O método POST submete dados a um recurso específico.

PUT - O método PUT substitui todas as representações atuais do recurso pelo conteúdo carregado.

DELETE - O método DELETE remove um recurso especificado.

CONNECT - O método CONNECT estabelece uma conexão de túnel direto para um servidor.

OPTIONS - O método OPTIONS descreve as opções de comunicação para o recurso de destino.

TRACE - O método TRACE executa um teste de loop-back de mensagem ao longo do caminho para o recurso de destino.

PATCH - O méotod PATCH aplica modificações parciais a um recurso.

## HTTP Status Code

  Os códigos de status de resposta HTTP são indicadores numéricos enviados pelo servidor para informar o resultado de uma solicitação feita pelo cliente. Esses códigos começam com um número na faixa de 1xx a 5xx, sendo agrupados em cinco classes:

1. Respostas Informativas (100 – 199)
2. Respostas bem-sucedidas (200 – 299)
3. Mensagens de redirecionamento (300 – 399)
4. Respostas de erro do cliente (400 – 499)
5. Respostas de erro do servidor (500 – 599)

Exemplos mais notáveis de códigos de status:

100 Continue - Indica que o cliente pode continuar com a sua requisição.  
200 OK - Indica que a requisição foi bem-sucedida.  
302 Found - Indica que a requisição deve ser redirecionada temporariamente para outra URI.  
404 Not Found - Indica que o recurso solicitado não foi encontrado no servidor.  
500 Internal Server Error - Indica um erro interno no servidor ao processar a requisição.  
  
  
  
  
  
**Autor do resumo: Luis Gustavo de Albuquerque - 01515839**
