  # Api REST e RESTFul
A API REST é uma abordagem arquitetural para o desenvolvimento de serviços web que se baseia em princípios como recursos
identificáveis, manipulação de recursos por meio de métodos HTTP e a representação de dados em formatos como JSON ou XML.
Os métodos HTTP desempenham papéis específicos:

- **GET:** Utilizado para recuperar dados de um recurso identificado pela URI, sem causar alterações no servidor.
  
- **POST:** Empregado para criar um novo recurso. A requisição contém dados do novo recurso no corpo, e o servidor atribui uma URI única a ele.

- **PUT:** Utilizado para atualizar um recurso existente. A requisição inclui os dados atualizados e a URI do recurso em questão.

- **DELETE:** Utilizado para excluir um recurso identificado pela URI. Semelhante ao GET, é uma operação sem efeitos colaterais.

Esses métodos proporcionam uma interface uniforme para interações entre cliente e servidor, simplificando a comunicação e 
permitindo o desenvolvimento de serviços web eficientes e escaláveis. A escolha do método depende da natureza da operação
desejada em um determinado recurso.

RESTful refere-se a uma abordagem de design de serviços web que segue os princípios da arquitetura REST. Caracteriza-se
pelo uso dos métodos HTTP apropriados para operações em recursos, URIs significativas, formatos de representação consistentes
(como JSON ou XML), ausência de estado e, opcionalmente, a implementação de HATEOAS para melhorar a navegação na API.
Essa abordagem busca criar serviços web simples, escaláveis e interoperáveis.

## Diferenças entre REST e RESTful

REST (Representational State Transfer):

- Arquitetura para serviços web.
- Define princípios para comunicação entre sistemas.
- Utiliza métodos HTTP para operações em recursos.
- Ausência de um conjunto padronizado de regras.

RESTful (REST + Full):

- Implementação concreta dos princípios REST.
- Utiliza métodos HTTP de maneira significativa.
- Adota URIs significativas e formatos consistentes.
- Promove a ausência de estado e, opcionalmente, HATEOAS.
- Busca criar serviços web simples, escaláveis e interoperáveis.

## HTTP Verbs

Os métodos HTTP, também conhecidos como HTTP verbs, são fundamentais para as operações em serviços web. Aqui estão alguns dos principais HTTP verbs e suas funções:

- **GET:** Recupera dados de um recurso identificado pela URI.

- **POST:** Cria um novo recurso com os dados fornecidos na requisição.

- **PUT:** Atualiza um recurso existente com os dados fornecidos na requisição.

- **DELETE:** Exclui um recurso identificado pela URI.

Estes métodos, quando usados de acordo com as práticas RESTful, formam a base para operações eficientes e consistentes em APIs web.

## HTTP Status Code

Os códigos de status HTTP são indicadores numéricos fornecidos em respostas de servidores web para indicar o resultado de uma solicitação. Alguns códigos comuns incluem:

- **200 OK:** Indica sucesso na solicitação.

- **201 Created:** Indica que a solicitação resultou na criação bem-sucedida de um recurso.

- **400 Bad Request:** Indica que a solicitação do cliente é inválida ou malformada.

- **401 Unauthorized:** Indica que o cliente precisa autenticar-se para obter acesso.

- **404 Not Found:** Indica que o recurso solicitado não foi encontrado no servidor.

- **500 Internal Server Error:** Indica um erro interno no servidor.

Estes são apenas alguns exemplos; os códigos de status fornecem informações valiosas sobre o resultado de uma solicitação e são essenciais para a compreensão e tratamento apropriado das respostas das APIs web.
