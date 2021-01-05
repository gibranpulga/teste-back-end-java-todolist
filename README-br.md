Teste para Desenvolvedor Back-end Java - Todolist

Olá ! Bolamos esse teste pra entender melhor como você aborda o problema proposto, e como você gosta de codificar. Tentamos aproximar o máximo possível da nossa realidade, utilizando tecnologias que usamos e que facilmente podem ser encontrados tutoriais na internet.
Caso não consiga ou queira fazer algum passo, não tem problema. Não vamos te desqualificar por isso. Nesse caso você pode comentar sobre o ponto e o porquê não o fez. Esperamos que goste!

Seguem as tarefas. As tarefas consideradas bônus, caso não tenha tempo ou prefira não fazer, por favor comentar como faria ou como seria a arquitetura técnica:

- Criar uma API pra uma aplicação de todo list. Deve permitir essas funções: fazer login, logout, e as funções de uma simples todolist (adicionar/editar/deletar/listar task com nome, descrição, data). Utilizar Spring BOOT. 
- Pode ser um login simples e hard coded.
- Possibilidade de adicionar arquivo anexo. Caso faça o deploy no AWS, pode salvar no S3, por exemplo.
- DB pode ser a vontade (sugestão h2, postgres ou mongo).
- Adicionar swagger, devemos poder fazer todo o flow pelo swagger ( login, CRUD da task, logout). Dica: documentar todos os campos. 
- Não esquecer dos unit tests. 
- Criar dockerfile e docker-compose.yaml pra fazer o deploy local como container do docker.
- Entregar o link do repositório em modo privado (preferência gitlab) com readme.MD com instruções de como rodar localmente e resumo técnico.
- Escrever o Readme.md Instruções do flow de login.

Bônus: permitir user se registrar;
Bônus: Deploy em algum cloud provider (preferência AWS, pode ser no EC2 mesmo, ou Azure ou Heroku);
Bônus: criar arquivo CI/CD do gitlab com 3 stages: compile, tests (caso tenha unit + integration, 1 stage pra cada) e dockerize (gerar container do docker).
