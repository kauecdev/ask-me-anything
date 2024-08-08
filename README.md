# Ask Me Anything [AMA]

AMA é uma aplicação web para criação de salas de perguntas e respostas em tempo real utilizando websockets. Com ela, usuários podem criar salas em que outras pessoas podem mandar suas perguntas 
e reagir a outras perguntas, criando uma interação ao vivo entre si.

## Desenvolvimento

### Backend
O backend do projeto foi desenvolvida utilizando [Golang](https://go.dev/), juntamente com o pacote [Chi](https://go-chi.io/#) para criação dos serviços HTTP. Para o servidor websocket, 
foi utilizado o pacote [Gorilla](https://github.com/gorilla/websocket).

### Frontend
O frontend do projeto foi desenvolvido utilizando [Typescript](https://www.typescriptlang.org), um superset para a linguagem Javascript, e [React](https://react.dev), uma biblioteca para criação de interfaces. 
Além disso, utilizamos:
- [React Router DOM](https://reactrouter.com/en/main) para gerenciamento das rotas da aplicação;
- [React Query](https://tanstack.com/query/latest/docs/framework/react/overview) para busca e cache de dados;
- [Sonner](https://sonner.emilkowal.ski) para notificações toast.

## Screenshots
Abaixo, seguem algumas screenshots do projeto em execução:

![image](https://github.com/user-attachments/assets/4677a519-e36d-4740-9808-6fa075b95b00)
![image](https://github.com/user-attachments/assets/a91077a7-1cbe-491b-9030-9aa4c13aee36)
![image](https://github.com/user-attachments/assets/5a88b02c-7182-483b-80a5-7f4c66bf4bf2)
![image](https://github.com/user-attachments/assets/28f21181-4cd7-49fe-9a7e-89695ce44613)
