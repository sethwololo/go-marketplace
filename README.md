<p align="center">
  <img width="750" src="https://github.com/sethwololo/go-marketplace/blob/master/docs/GoMarketplace.png">
</p>

GoMarketplace é uma aplicação para listagem de produtos e gerenciamento de carrinho de compras.

Utilizando Typescript, React Native, AsyncStorage e FakeAPI (json-server)

## Como preparar o app

+ Clone o repositório ou baixe-o como .zip
+ Rode o comando `yarn` para baixar as dependências
+ Entre na pasta **ios** e rode o comando `pod install`, caso esteja no Mac OS
+ Rode o comando `yarn json-server server.json -p 3333` para iniciar a FakeAPI

## Iniciando o app

+ Para iniciar a aplicação no iOS Simulator execute `yarn ios`
+ Para iniciar a aplicação no Android Emulator execute `yarn android`
+ Caso o servidor Metro pare de executar, execute o comando `yarn start`

## Funcionamento do app

+ Para adicionar produtos ao carrinho pressione **+** no produto
+ No carrinho, pressione **+** para incrementar ou **-** para decrementar a quantidade do produto

<p align="center">
  <img width="200" align="center" src="https://media.giphy.com/media/ZFoDi8FuptkN3xzF88/giphy.gif">
</p>
