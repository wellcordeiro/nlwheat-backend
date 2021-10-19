# nlwheat-backend

# **NLW Heat (Backend)**

Projeto produzido durante a Next Level Week Heat (NLW Heat) da Rocketseat

Este projeto exercita o uso de banco de dados usando [Prisma](https://www.prisma.io/) e também o conceito de real-time com o [Socket.io](https://socket.io/), além de fazer autenticação usando o GitHub

### **Tecnologias**

Prisma, Typescript, Socket.io, Node.js, Yarn

### Ferramentas utilizadas

[https://efficient-sloth-d85.notion.site/Instala-o-das-ferramentas-91964f6757894d6db05fc09ce97ee5b9](https://www.notion.so/Instala-o-das-ferramentas-91964f6757894d6db05fc09ce97ee5b9)

### **Executando o projeto**

Crie uma conta no **[GitHub](https://github.com),** após isso siga as instruções a seguir:  

- 1 - Crie uma nova aplicação em seu GitHub: Settings > Developer Settings ou [**Clique Aqui!**](https://github.com/settings/developers)
- 2 - Guarde seu **client_Id** e **client_secret** em algum local de segurança

### Configurações do Projeto

Configure o arquivo `.env` da aplicação conforme o `.env.example`

```docker
GITHUB_CLIENT_ID= 
GITHUB_CLIENT_SECRET= 
JWT_SECRET=VALORALEATORIO 
```

Adicione um valor que servirá de chave para o JWT_TOKEN, você pode utilizar o MD5 Generator. 

Após isso, rode os seguintes comandos:

```docker
yarn
yarn prisma migrate dev //Irá criar o banco de dados
yarn dev //Irá executar o projeto
```

(Verifique as permissões de escrita/leitura caso apresente algum erro)

O projeto estará escutando a porta 4000 (http://localhost:4000)

### POSTMAN COLLECTION (Opcional)

Acesse seu Postman, clique em "Collections" após isso em "Import" > Link

e cole este link para importar: [https://www.getpostman.com/collections/515846416c1a811546da](https://www.getpostman.com/collections/515846416c1a811546da)