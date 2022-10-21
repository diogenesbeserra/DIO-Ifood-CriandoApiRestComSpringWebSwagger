# Curso DIO Criando uma API REST Documentada com Spring Web e Swagger
## Aula Criando uma REST API

Uma API é um serviço que faz integração entre o front e o back end. O REST é um padrão para organização do projeto.

- Criamos um projeto pelo Spring Initializer com a dependencia Spring Web
- criamos o pacote controller e a classe WelcomeController com o priemiro método get
- criamos uma classe usuário no pacote models e repositório fake no pacote repositório
- criamos o UsuarioController para gerenciar as requisições referentes a lógica dos Usuários
  - Mapeamos varias requisições para seus métodos:
    - @GetMapping() - lista todos usuários
    - @GetMapping("/{username}") - procura um usuário pelo nome com @PathVariable("username")
    - @DeleteMapping("/{id}") - passa o id de usuário a ser removido @PathVariable("id")
    - @PostMapping() - passa um usuário pelo @RequestBody para ser inserido no repoositorio

 
