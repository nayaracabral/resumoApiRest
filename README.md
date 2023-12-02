# 🌐 API REST 
## Implementação RESTful

 ![API REST] 
 
 API REST, também chamada de API RESTful, é uma interface de programação de aplicações (API ou API web) que segue as restrições do estilo de arquitetura REST. REST é a sigla em inglês para “Representational State Transfer”, que em português significa transferência de estado representacional. 

 ##Exemplo
 
 Imagine que você está em um restaurante. O garçom é como uma API. Você, o cliente, pede algo do menu (faz uma solicitação). O garçom leva seu pedido para a cozinha e volta com sua comida (a resposta). Nesse cenário, a cozinha é o sistema de back-end. Agora, imagine que este restaurante é um “restaurante RESTful”. Aqui, você tem que fazer pedidos de uma maneira específica, usando certas palavras e seguindo certas regras (isso é o que chamamos de “restrições REST”). Se você seguir essas regras, o garçom (API) entenderá seu pedido e trará sua comida corretamente.
 
 ## Verbos HTTP 
 
 ![Verbos HTTP] 
 
 Os verbos HTTP, também conhecidos como métodos HTTP, indicam a ação a ser executada para um dado recurso. Os principais métodos HTTP são:
 
*  **GET**: Solicita a representação de um recurso específico.
 
*  **HEAD**: Solicita uma resposta de forma idêntica ao método GET, porém sem conter o corpo da resposta.
  
*   **POST**: Utilizado para submeter uma entidade a um recurso específico, frequentemente causando uma mudança no estado do recurso ou efeitos colaterais no servidor.

* **PUT**: Substitui todas as atuais representações do recurso de destino pela carga de dados da requisição, pedido específico.

*  **DELETE**: Remove um recurso específico. 
 
* **CONNECT**: Estabelece um túnel para o servidor identificado pelo recurso de destino. 
 
* **OPTIONS**: Descreve as opções de comunicação para o recurso de destino. 
 
* **TRACE**: Executa um teste de chamada loop-back junto com o caminho para o recurso de destino. 
 
* **PATCH**: Utilizado para aplicar modificações parciais em um recurso.
 
 ## Códigos de Status HTTP 
 
 Os códigos de status de resposta HTTP indicam se uma solicitação HTTP específica foi concluída com sucesso. As respostas são agrupadas em cinco classes:
 
 ![Códigos de Status HTTP] 
 
* **1xx (Informacional)**: Indica que a solicitação foi recebida e o processo está continuando. 
 
* **2xx (Sucesso)**: Indica que a ação foi recebida, compreendida e aceita com sucesso. 
 
* **3xx (Redirecionamento)**: Indica que uma ação adicional deve ser tomada para completar a solicitação. 
 
* **4xx (Erro do Cliente)**: Indica que a solicitação contém uma sintaxe incorreta ou não pode ser atendida. 
 
* **5xx (Erro do Servidor)**: Indica que o servidor falhou ao atender uma solicitação aparentemente válida.
 
 ## Diferenças entre REST e RESTFul

 ![Diferenças entre REST e RESTFul] 
 
 REST (Representational State Transfer) é um estilo de arquitetura que define um conjunto de restrições para a construção de serviços web.
 Por outro lado, RESTful é um termo usado para descrever serviços web que seguem essas restrições. Em outras palavras, sistemas que utilizam os princípios REST são chamados de RESTful.
 E Enquanto as APIs REST seguem os princípios básicos do REST, as APIs RESTful são uma implementação mais completa e estrita desses princípios. Portanto, a principal diferença entre REST e RESTful é que REST se refere aos princípios de arquitetura, enquanto RESTful se refere à implementação desses princípios.
 
 ##As vantagens de uma API RESTful incluem: 
 
 **Separação entre o cliente e o servidor**: 
 
 Isso facilita o desenvolvimento da aplicação e protege o armazenamento de dados. 
 
 **Multiplataforma**:
 
 As requisições HTTP feitas em uma API RESTful retornam dados no formato JSON, permitindo a interoperabilidade entre diferentes plataformas. 
 
 **Alta liberdade e flexibilidade para os desenvolvedores**:
 
 Uma API RESTful oferece altos níveis de liberdade e flexibilidade, o que é benéfico principalmente em aplicações em nuvem. 
 
 **Possibilidade de enviar representações em diversos formatos**:
 
 As representações enviadas pelo servidor podem estar em diversos formatos, como JSON, XML, Python, etc. 
 
 **Padronização da API**:
 
 Isso inclui a divisão de funcionalidades por recursos, padronização de URIs e parâmetros, e melhor aproveitamento de recursos do protocolo HTTP.


 # Autor

Nayara Cabral 01565992
