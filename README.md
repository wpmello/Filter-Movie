# API RESTful _filtered movies per mood_
Api desenvolvida para sugerir filmes que estão em cartaz com base na temperatura atual do lugar onde a pessoa está ou em qualquer lugar do mundo! Com isso sua lógica segue: <br>
Se o local onde a pessoa está estiver fazendo mais de **40°C** serão sugeridos filmes com o gênero **ação** <br>
Se estiver fazendo entre **36°C e 40°C**, então serão sugeridos filmes com o gênero **comédia** <br>
Se estiver fazendo entre **20°C e 35°C**, então serão sugeridos filmes com o gênero **animações** <br>
Se estiver fazendo entre **0°C e 20°C**, então serão sugeridos filmes com o gênero **suspence** <br>
E estiver fazendo menos de **0°C**, então serão sugeridos filmes com o gênero **documentários** <br>
Para o desenvolvimento foram usadas duas APIs externas que são elas: [openweathermap](https://openweathermap.org/) & [themoviedb](https://www.themoviedb.org/)
## Objetivo ✔
- Desenvolver a API conforme os requisitos pedidos
- Usar boas práticas
- Aprender e desenvolver novas técnicas
- Praticar
- Consumir APIs externas
---
## Tecnologias / Bibliotecas usadas 👨🏿‍💻
- Java na versão 17
- Spring Boot
- Bean Validation
- Lombok
- Maven
- Git
- JPA
- H2 (para testes)
- PostgreSql
