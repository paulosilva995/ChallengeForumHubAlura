# Challenge: ForumHub Alura - Desafio do Programa One

## Visão Geral
Este aplicativo Java Spring 3 simula um fórum de mensagens onde os usuários podem criar tópicos, responder a tópicos e interagir entre si. Faz a utilização do DB MySQL para realizar o armazenamento das informações do usuário, curso, tópicos e respostas.

## Funcionalidades
- **Gerenciamento de Usuários**: Os usuários podem se registrar, fazer login e atualizar seu perfil.
- **Criação de Tópicos**: Os usuários podem criar novos tópicos em cursos específicos.
- **Postagem de Respostas**: Os usuários podem responder a tópicos existentes.
- **Segurança**: Utiliza o Spring Security para autenticação e autorização baseada em token JWT.

## Primeiros Passos
Siga estas etapas para configurar e executar o aplicativo localmente:

1. **Clonar o Repositório**: Clone este repositório para a sua máquina local
   ```
   git clone git@github.com/paulosilva995/Challenge_ForumHub_Alura.git
   ```
   
2. **Configuração do Banco de Dados**: Configure um banco de dados MySQL e defina os detalhes de conexão nas propriedades do aplicativo.

3. **Construir e Executar**: Use o Maven para construir o aplicativo e executá-lo localmente.
   ```
   mvn spring-boot:run
   ```
   
## Dependências
- Java Spring Boot 3
- MySQL
- Spring Security
- Autenticação de Token JWT



**Algumas rotas**
   ```
Listar usuários (GET) - /usuario
Update usuário (PUT) - /usuario/{idUsuario}
Delete usuário (DELETE) - /usuario/{idUsuario}
Listar cursos (GET) - /curso
Update cusos (PUT) - /curso/{idCurso}
Listar tópicos ativos (GET) - /topicos/lista
Listar todos os tópicos (GET) - /topicos/listaAdmin
Update tópico (PUT) - /topicos/{idTopico}
Delete tópico (DELETE) - /topicos/{idTopico}
Detalhamento tópico (GET) - /topicos/{idTopico}
   ```
