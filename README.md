# Documentos-Dinamicos-com-WebSocket 

## Descrição do Projeto

> Trata-se de um site no qual o usuário realiza um cadastro ou login colocando nome e senha e, após isso, é redirecionado para a rota de documentos, na qual é possível criar, entrar ou excluir um > registro. Uma vez acessado um documento, verifica-se no canto direito da tela os usuários endereçados na mesma rota e, além disso, é possível que duas ou mais pessoas atualizem as  informações do documento dinâmicamente, graças a tecnologia [Socket.Io](https://socket.io/)

## : Status do Projeto

Funcional. Aberto a colaborações.

## :hammer: Funcionalidades do Projeto

- `Cadastra usuários`;
- `Verifica se já existe o usuário no banco de dados`;
- `Verifica se os dados estão corretos`;
- `Cria hash para dificultar o acesso a senha do usuário`;
- `Cria documentos e permite a visualização da inserções de textos pelos usuário de forma dinâmica`;
- `Verifica quantas pessoas estão no mesmo documento`;

  ## :open_file_folder: Acesso ao Projeto

    [Baixe o repositório](https://github.com/BrenonSAraujo/Documentos-Dinamicos-com-WebSocket) pelo GitHub. Em seguida, é preciso baixar as dependências do projeto. Para isso, abra o terminal da sua IDE e digite:
  ```sh
  npm install
  ```
  Após isso, suba a aplicação com o comando:
   ```sh
  npm run dev
  ```
   Aguarde a mensagem:
  
  *Conectado ao banco de dados com sucesso!
  Servidor escutando na porta 3000*
  
   Em seguida, abra o seu navegador e digite na barra de endereços:
  ```sh
    http://localhost:3000/cadastro
  ```

  ## Tecnologias utilizadas
  
  - `socket.io`;
  - `express`;
  - `jsonwebtoken`;
  - `mongodb`;
  - `dotenv`;



