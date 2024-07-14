# 📑 Challenge Back End!

Um fórum é um espaço onde todos os participantes de uma plataforma podem colocar suas perguntas sobre determinados assuntos. Este lugar mágico está cheio de muita aprendizagem e colaboração entre alunos, professores e moderadores.

Já sabemos para que serve o fórum e sabemos sua aparência, mas sabemos como ele funciona por trás dos panos? Isto é, onde se armazenam as informações? Como são tratados os dados para que se relacione um tópico com uma resposta, ou como se relacionam os usuários com as respostas de um tópico?

Este é o nosso desafio, chamado de FórumHub: nele, vamos replicar este processo no nível do back end e, para isso, criaremos uma API REST usando Spring.

# 🔨 Funcionalidades da API
Nossa API se concentrará especificamente nos tópicos e deve permitir aos usuários:

- Criar um novo tópico;
- Mostrar todos os tópicos criados;
- Mostrar um tópico específico;
- Atualizar um tópico;
- Eliminar um tópico.

É o que conhecemos normalmente como CRUD (CREATE, READ, UPDATE, DELETE)* e é muito parecido com o que desenvolvemos no LiterAlura, mas agora de forma completa, agregando as operações de UPDATE e DELETE, e usando um framework que facilitará muito o nosso trabalho.

*Tradução livre (em ordem): Criar, Consultar, Atualizar e Deletar.

# 🗂️ Tecnologias Utilizadas

- Java 21
- Spring Boot
- Spring Data JPA
- MySQL
- Spring Security

# 🌐 Endpoints da API

- POST /api/topicos: Cria um novo tópico.
- GET /api/topicos: Lista todos os tópicos.
- GET /api/topicos/{id}: Exibe detalhes de um tópico específico.
- PUT /api/topicos/{id}: Atualiza um tópico existente.
- DELETE /api/topicos/{id}: Deleta um tópico.

# 🔐 Autenticação e Autorização
  
A API utiliza Spring Security para autenticação e autorização. A configuração padrão utiliza autenticação básica, mas pode ser adaptada para JWT ou OAuth2 conforme necessário.

# ⚖️ Validações e Regras de Negócio
Todas as entradas de dados passam por validações conforme as regras de negócio definidas. Isso garante que apenas dados válidos sejam processados e armazenados.

# 📦 Base de Dados Relacional
A aplicação utiliza um banco de dados relacional MySQL para a persistência das informações.

# 🔥 Minha Conquista do Challenge
Após seis meses de muito aprendizado e dedicação, concluo com sucesso o último desafio deste programa incrível e recebo o badge como reconhecimento do meu esforço e comprometimento.
<div align="center">
<img src="https://github.com/user-attachments/assets/139e37a8-68e6-4b88-853a-40e4a46b334c" alt="Badge Challenger">
</div>
Cada etapa deste programa foi uma oportunidade para crescer e aprimorar minhas habilidades, e este badge é o coroamento de todo esse processo.
