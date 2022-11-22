# Teste Dev Junior 2 - SoftMakers

### Tecnologias Utilizadas

- [NextJS](https://nextjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [NodeJS](https://nodejs.org/en/)
- [Express](https://expressjs.com/pt-br/)
- [Sequelize](https://sequelize.org/)
- [PostgreSQL](https://www.postgresql.org/)
- [ElephantSQL](https://www.elephantsql.com/)
- [The Cat API](https://thecatapi.com/)
- [The Dog API](https://thedogapi.com/)

### Deploy 
- Frontend - [Vercel](https://vercel.com/home)
- Backend -  [Render](https://render.com/)

### Testando a aplicação

A aplicação está online e você pode testar acessando esse [LINK](https://petmakers.vercel.app/) diretamente. Ao testar, pode-se identificar um pouco de delay, tendo em vista que a aplicação está hospedada em serviços gratuitos. 
O backend está rodando na render.com e o banco de dados Postgres é uma instância gratuita da [ElephantSQL](https://www.elephantsql.com/). Porém, na impede de  testarmos localmente. 



### Testando localmente

Para testar localmente, basta apenas instalar as dependências das partes da aplicação. Não há necessidade de um banco de dados local, pois a aplicação utiliza o banco em nuvem (configurado na variável de ambiente .env na pasta backend). Mas, caso queira testar com um banco local, basta seguir as configurações definidas na [Documentação do Sequelize](https://sequelize.org/docs/v6/getting-started/#connecting-to-a-database). Acesse as pastas **backend** e **frontend** pelo terminal e execute o comando *npm install* para instalar as dependências de cada uma delas.


###### Depois de instaladas as dependências

* Na pasta **/backend** execute: **npm start**
* Na past **/frontend** execute: **npm run dev**




