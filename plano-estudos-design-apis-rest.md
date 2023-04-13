# Plano de Estudos sobre Design de APIs REST

O Design de APIs REST é fundamental para desenvolvedores back-end, pois permite a criação de serviços web mais eficientes, seguros e escaláveis, além de melhorar a colaboração com desenvolvedores front-end e fornecer aos usuários uma experiência mais consistente e intuitiva. Ao compreender o Design de APIs REST, os desenvolvedores podem construir interfaces de programação de aplicativos mais claras e bem documentadas. Também é importante seguir as melhores práticas, como a utilização correta de verbos HTTP, cabeçalhos e parâmetros, para garantir a segurança e privacidade dos usuários e evitar problemas como vazamento de informações pessoais ou ataques de negação de serviço.

Para conseguirmos fazer bons designs de APIs REST, vamos estudar conceitos e técnicas relacionados ao tema. Focaremos nos conceitos fundamentais sobre REST e RESTful Web Services e protocolo HTTP, mas também veremos conceitos específicos e técnicas que, em conjunto, permitirão o design de boas APIs REST.

Aqui, assumimos que você já possui algum conhecimento sobre os temas abordados ou já os pratica no dia-a-dia. Dessa forma, podemos ir mais longe e abrir a mente sobre ferramentas que temos em mãos mas, provavelmente, não tiramos máximo proveito.

Abaixo, os tópicos principais que estudaremos:

1. [REST e RESTful Web Services](#1-rest-e-restful-web-services)
2. [HTTP e Documentação](#2-http-e-documentação)
3. [Compatibilidade, evolução e desempenho](#3-compatibilidade-evolução-e-desempenho)
4. [Tópicos de APIs REST](#4-tópicos-de-apis-rest)

Ao fim deste Plano de Estudos, você terá os conceitos básicos sobre Design de APIs REST, bom uso do protocolo HTTP, como manter uma API REST e a evoluir, como atingir requisitos de desempenho e escalabilidade, segurança e padrões arquiteturais comuns.


## 1. REST e RESTful Web Services

---
* Definição de REST e RESTful Web Services
* Richardson Maturity Model
* RESTful Web API Design
---

[CHAPTER 5 - Representational State Transfer (REST)](https://www.ics.uci.edu/~fielding/pubs/dissertation/rest_arch_style.htm) (Roy Fielding, 2000) (30min, artigo acadêmico)

[Richardson Maturity Model](https://martinfowler.com/articles/richardsonMaturityModel.html) (Martin Fowler, 2010) (12min, post de blog)

[RESTful Web Services](https://www.amazon.com.br/RESTful-Web-Services-Leonard-Richardson/dp/0596529260) (Leonard Richardson, 2007) (livro)

[RESTful Web API Design - Azure Architecture Center](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design) (2023) (30min, post de blog)

[Microsoft Azure REST API Guidelines](https://github.com/microsoft/api-guidelines/blob/vNext/azure/Guidelines.md) (2022) (60min, post de blog)


## 2. HTTP e Documentação

---
* Hypertext Transfer Protocol (HTTP)
* Documentação e OpenAPI
---

[Entendendo o Protocolo HTTP](https://github.com/zup-academy/materiais-publicos-treinamentos/blob/main/crud-basico-com-java-hibernate/entendendo-protocolo-http.md) (Yuri Matheus, 2022) (6min, artigo curto)

[Uma introdução sobre o HTTP](https://www.youtube.com/watch?v=SwqnGfFrnDI) (Yuri Matheus, 2022) (15min em 2x, vídeo)

[RFC7231 - Hypertext Transfer Protocol (HTTP/1.1)](https://www.rfc-editor.org/rfc/rfc7231) (IETF, 2014) (2h-4h, especificação)

[Mozilla Developer Network - Hypertext Transfer Protocol (HTTP)](https://developer.mozilla.org/en-US/docs/Web/HTTP) (2023) (documentação)

[What is OpenAPI?](https://www.openapis.org/what-is-openapi) (2022) (10 min, post de blog)

[OpenAPI Guide - What is OpenAPI?](https://swagger.io/docs/specification/about/) (2023) (documentação)

[OpenAPI Specification](https://github.com/OAI/OpenAPI-Specification) (2023) (repositório)


## 3. Compatibilidade, evolução e desempenho

---
* Versionamento
* Evolução e retro-compatibilidade
* Paginação de dados
* Cache
---

[RFC5988 - Pagination of HTTP-based API](https://www.rfc-editor.org/rfc/rfc5988) (IETF, 2010) (60min, especificação)


## 4. Tópicos de APIs REST

---
* Negociação de conteúdo
* Autenticação
* Assincronicidade
* Padrões comuns (BFF, Anti-corruption Layer, Ambassador, Strangler-fig)
---

[Backends for Frontends Pattern](https://learn.microsoft.com/en-us/azure/architecture/patterns/backends-for-frontends) (2023) (5min, post de blog)

