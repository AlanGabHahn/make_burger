
# Make Your Burger Vue 3

Este é um projeto de uma hamburgueria feito em Vue.js com JSON Server para simular um banco de dados.

## Funcionalidades

- **Página inicial**: Nesta página, os clientes podem montar seu próprio hambúrguer selecionando os ingredientes disponíveis. Após montar o hambúrguer, o cliente pode prosseguir para a página de pedidos.
  
- **Página de pedidos**: Aqui, os clientes podem visualizar seu pedido e o status do mesmo. 

## Tecnologias utilizadas

- **Vue.js**: Um framework progressivo para construção de interfaces de usuário.
  
- **JSON Server**: Uma ferramenta que permite criar uma API REST fake com base em um arquivo JSON.

## Instalação

1. Clone este repositório para sua máquina local.
  
    ```
    git clone https://github.com/AlanGabHahn/make_burger.git
    ```

2. Instale as dependências do Vue.js.

    ```
    cd make_burger
    npm install
    ```

3. Inicie o JSON Server para simular o banco de dados.

    ```
    json-server --watch db.json
    ```

4. Inicie o servidor Vue.js.

    ```
    npm run serve
    ```

5. Abra seu navegador e acesse [http://localhost:8080](http://localhost:8080).

## Estrutura do projeto

- **/src**: Contém os arquivos do projeto Vue.js.
  - **/components**: Componentes Vue utilizados no projeto.
  - **/views**: Páginas Vue principais do projeto.
- **db.json**: Arquivo JSON utilizado pelo JSON Server para simular o banco de dados.

## Como usar

1. Na página inicial, monte seu hambúrguer selecionando os ingredientes disponíveis.
2. Na página de pedidos, você verá seu pedido atual e o status do mesmo.

## Contribuindo

Sinta-se à vontade para contribuir com melhorias neste projeto. Você pode criar um fork do repositório e enviar um pull request com suas alterações.

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).

---

Espero que esta documentação ajude a entender o funcionamento do projeto! Se tiver mais alguma dúvida, não hesite em perguntar.