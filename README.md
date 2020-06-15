<img src="https://braze-marketing-assets.s3.amazonaws.com/images/partner_logos/react-native.png?W=200" height="150">

# Bootcamp GoStack React Native - **CHALLENGE**

<img src="./src/assets/logo@3x.png?W=75" height="25">

## **Fase 03**

### **Sobre**

Nesse desafio, desenvolverá uma nova aplicação, a GoMarketplace. Dessa vez é hora de você praticar o que você aprendeu até agora no React Native, junto com TypeScript, utilizando rotas, Async Storage e a Context API.

### Requisitos:

- Listar os produtos da fake API: Sua página Dashboard deve ser capaz de exibir uma listagem através de uma tabela, com o campo title, image_url e price.
  Dica: Você pode utilizar a função Intl para formatar os valores. Dentro da pasta utils no template você encontrará um código para te ajudar.

- Adicionar itens ao carrinho: Em toda sua aplicação, você deve utilizar o Contexto chamado cart que deixamos disponível. Você vai precisar completar as funcionalidades dentro de hooks/cart.tsx para que você consiga adicionar itens ao carrinho.

- Exibir itens do carrinho: Na página Cart você deve exibir todos os itens do carrinho, junto com a quantidade, valor único, valor subtotal dos itens e total de todos os items.

- Aumentar quantidade de itens do carrinho: Na página Cart você deve permitir que o usuário aumente a quantidade de itens do mesmo produto, para isso você pode utilizar a função increment dentro do seu contexto em /src/hooks/cart.tsx.

- Diminuir quantidade de um item do carrinho: Na página Cart você deve permitir que o usuário decremente a quantidade de itens do mesmo produto, para isso você pode utilizar a função decrement dentro do seu contexto em /src/hooks/cart.tsx.

- Exibir valor total dos itens no carrinho: Tanto na página Dashboard, tanto na página Cart você deve exibir o valor total de todos os itens que estão no seu carrinho.

## Específicação dos testes

Para esse desafio, temos os seguintes testes:

- **should be able to list the products:** Para que esse teste passe, sua aplicação deve permitir que sejam listados na sua tela Dashboard, toda os produtos que são retornadas do Fake API. Essa listagem deve exibir o title e o price que deve ser formatado utilizando a função Intl.

- **should be able to add a product to the cart:** Para que esse teste passe, você deve permitir que seja possível adicionar produtos da sua Dashboard ao carrinho, utilizando o contexto de cart disponibilizado.

- **should be able to list the products on the cart:** Para que esse teste passe, você deve permitir que seja possível listar os produtos que estão salvos no contexto do seu carrinho na página Cart, nessa página exiba o nome do produto, o subtotal total de cada produto (price \* quantity).

- **should be able to calculate the cart total:** Para que esse teste passe, tanto na página Dashboard, tanto na página Cart você deve exibir o valor total de todos os itens que estão no seu carrinho.

- **should be able to show the total quantity of itens in the cart:** Para que esse teste passe, tanto na página Dashboard, tanto na página Cart você deve exibir o número total de itens que estão no seu carrinho.

- **should be able to increment product quantity on the cart:** Para que esse teste passe, você deve permitir que seja possível incrementar a quantidade de um produto do seu carrinho, utilizando o contexto de cart disponibilizado.

- **should be able to decrement product quantity on the cart:** Para que esse teste passe, você deve permitir que seja possível decrementar a quantidade de um produto do seu carrinho, utilizando o contexto de cart disponibilizado.

- **should be able to navigate to the cart:** Para que esse teste passe, no seu componente FloatingCart na Dashboard, você deve permitir que ao clicar no botão de carrinho com o testID de navigate-to-cart-button, o usuário seja redirecionado para a página Cart.

- **should be able to add products to the cart:** Para que esse teste passe, no seu arquivo onde contém o contexto do carrinho, você deve permitir que a função addToCart adicione um novo item ao carrinho.

- **should be able to increment quantity:** Para que esse teste passe, no seu arquivo onde contém o contexto do carrinho, você deve permitir que a função increment altere incremente em 1 unidade a quantidade de um item que está armazenado no contexto.

- **should be able to decrement quantity:** Para que esse teste passe, no seu arquivo onde contém o contexto do carrinho, você deve permitir que a função decrement altere decremente em 1 unidade a quantidade de um item que está armazenado no contexto.

- **should store products in AsyncStorage while adding, incrementing and decrementing:** Para que esse teste passe, no seu arquivo onde contém o contexto do carrinho você deve permitir que todas as atualizações que você fizer no carrinho, sejam salvas no AsyncStorage. Por exemplo, ao adicionar um item ao carrinho, adicione-o também no AsyncStorage. Lembre de também atualizar o valor do AsyncStorage quando você incrementar ou decrementar a quantidade de um item.

- **should load products from AsyncStorage:** Para que esse teste passe, no seu arquivo onde contém o contexto do carrinho, você deve permitir que todos os produtos que foram adicionados sejam buscados do AsyncStorage.mais informações em [Rocketseat Desafio React Native fase 3 - GoMarketplace](https://github.com/Rocketseat/bootcamp-gostack-desafios/tree/master/desafio-fundamentos-react-native)
