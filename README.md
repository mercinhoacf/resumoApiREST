# resumoApiREST

 ## Api REST e RESTFul
- O que é uma API REST? É uma API, ou interface de programação aplicativos, é um conjunto de regras que definem como aplicativos ou dispositivos podem se conectar e se comunicar uns com os outros. Uma API de REST é uma API que se adéqua aos princípios de design do REST ou o estilo de arquitetura do Representational State Transfer.  Por esta razão, as APIs de REST são muitas vezes chamadas de APIs de RESTful.

- Como as APIs de REST funcionam? As APIs de REST se comunicam via solicitações de HTTP para executar funções padrão do banco de dados como criar, ler, atualizar e excluir registros (também conhecidos como CRUD) em um recurso. Por exemplo, uma API de REST usaria uma solicitação GET para recuperar um registro, uma solicitação POST para criar um registro, uma solicitação PUT para atualizar um registro e uma solicitação DELETE para excluir um registro. Todos os métodos HTTP podem ser usados em chamadas da API. Uma API de REST bem projetada é semelhante a um website em execução em um navegador da web com funcionalidade HTTP integrada.

- O que significa REST? REST não é um protocolo ou padrão, mas sim um conjunto de restrições de arquitetura. Os desenvolvedores de API podem implementar a arquitetura REST de maneiras variadas. Quando um cliente faz uma solicitação usando uma API RESTful, essa API transfere uma representação do estado do recurso ao solicitante ou endpoint. Essa informação (ou representação) é entregue via HTTP utilizando um dos vários formatos possíveis: Javascript Object Notation (JSON), HTML, XLT, Python, PHP ou texto sem formatação. Lembre-se também de que cabeçalhos e parâmetros são importantes nos métodos HTTP de uma solicitação HTTP de API RESTful porque contêm informações relevantes sobre o identificador, bem como metadados, autorização, Uniform Resource Identifier (URI), cache, cookies e outras informações da solicitação.

## Diferenças entre REST e RESTFul
- Qual a principal diferença entre REST e RESTFul? A principal diferença está na abordagem e na conformidade com os princípios REST. REST: Refere-se a uma arquitetura de software que segue os princípios do REST, não necessariamente segue todos os princípios do REST estritamente e pode usar alguns conceitos ou protocolos que não são puramente RESTful. RESTFul: Descreve uma API que adere estritamente aos princípios do REST, segue as práticas recomendadas de REST, como o uso correto de métodos HTTP (GET, POST, PUT, DELETE), estado da aplicação representado nas requisições, uso de URIs para recursos, uso de hypermedia (HATEOAS) para ações disponíveis e tende a ser mais padronizado e previsível na maneira como as operações são realizadas. 

- Em resumo do texto lido acima, uma API RESTFul é uma implementação que segue rigorosamente os princípios do REST, enquanto uma API REST pode seguir esses princípios de maneira mais flexível, podendo não ser totalmente aderente a eles.

## HTTP verbs
- O que é o protocolo HTTP? O protocolo HTTP define um conjunto de métodos de requisição responsáveis por indicar a ação a ser executada para um dado recurso. Embora esses métodos possam ser descritos como substantivos, eles também são comumente referenciados como HTTP Verbs (Verbos HTTP). Cada um deles implementa uma semântica diferente, mas alguns recursos são compartilhados por um grupo deles, como por exemplo, qualquer método de requisição pode ser do tipo safe, idempotent ou cacheable (en-US).

#### Principais métodos: 
- **GET**: Solicita a representação de um recurso específico. É usado para buscar dados.
- **POST**: Usado para enviar dados para o servidor para criar um novo recurso. É comum para operações de criação.
- **PUT**: Atualiza um recurso específico com os dados fornecidos. Geralmente utilizado para atualização integral de um recurso.
- **DELETE** Remove um recurso específico no servidor.
- **PATCH** Usado para aplicar modificações parciais em um recurso. É útil quando apenas partes do recurso precisam ser atualizadas.
- **OPTIONS** Retorna os métodos HTTP suportados no recurso solicitado, útil para determinar as operações permitidas em um determinado endpoint.

##### Entre outros métodos.

## HTTP Status Code
- O que é Status Code? HTTP Status Code são os três dígitos que indicam qual o erro para o servidor e navegador enquanto a frase razão é uma curta descrição do que este erro significa para melhor compreensão dos usuários. Esses códigos são divididos em várias categorias e cada categoria tem um significado específico. 

#### Alguns dos códigos de status mais comuns incluem:
- **1xx(Informational)**:  Indica que a requisição foi recebida e o servidor continua processando-a.
- **2xx(Success)**:  Indica que a requisição foi recebida, entendida e aceita com sucesso.
- **3xx(Redirection)**:  Indica que o cliente precisa realizar mais ações para completar a requisição.
- **4xx(Client Error)**:  Indica que ocorreu um erro por parte do cliente na requisição.
- **5xx(Server Error)**:  Indica que ocorreu um erro no servidor ao processar a requisição.

##### Esses são os códigos essenciais para entender um pouco mais afundo sobre o resultado de uma requisição HTTP. Eles fornecem informações sobre se a requisição foi processada com sucesso, se houve redirecionamento, erros do lado do cliente ou do servidor, entre outros casos.

-----------------

Autor do Resumo: Emerson Aquino - 01501853
