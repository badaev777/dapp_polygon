#dApp Polygon Tutorial

Как работает blockchain технология?

![BlockchainWork](https://hsto.org/r/w1560/getpro/habr/post_images/2dc/ef4/9b2/2dcef49b2827308dc084ecbd020dadb7.png "BlockChain Work")

Пример как работает dApp?

![dAppExample](https://www.researchgate.net/profile/Lodovica-Marchesi/publication/338064306/figure/fig2/AS:838024002826240@1576811900545/A-typical-architecture-of-an-Ethereum-dApp-application-The-App-System-is-shown-on-the.ppm "dApp Example")

1. Smart Contract
    Смарт-контракта -- это особая программа, выполняемая всеми узлами и помогающая наладить взаимодействие среди всех владельцев криптовалют. Условия и положения этих контрактов записываются в цепочке блокчейн. 
    Именно поэтому никому не удается обмануть или взломать пользователя, нарушив условия умного контракта.
    
    https://hsto.org/r/w1560/getpro/habr/post_images/dc9/0a6/cd4/dc90a6cd4d0bd2d95474049b5df8da3c.png
    ![SmartContractExample](https://hsto.org/r/w1560/getpro/habr/post_images/dc9/0a6/cd4/dc90a6cd4d0bd2d95474049b5df8da3c.png "SmartContractExample")
    
    Блокчейн Ethereum(Polygon) работает со смарт-контрактами на особом языке программирования Solidity. 
    Solidity позволяет создавать более сложные алгоритмы, но такие смарт-контракты гораздо сложнее проверять на наличие уязвимостей.
    Solidity компилируеться в bytecode и деплоиться в сеть.
    
    Doc: https://docs.soliditylang.org/en/v0.4.24/
    
    Для упрощения разработки можно использовать онлайн IDE Remix.
    
    OpenZeppelin -- contract template library помогает быстро сгенерировать контракты стандарта ERC20, ERC721, ERC1155
    https://docs.openzeppelin.com/contracts/4.x/
    
2. Web3 Libraries

Библиотеки Web3 — это удобные оболочки для этого протокола JSON-RPC, которые предоставляют интерфейс для взаимодействия 
с узлом Ethereum на выбранном вами языке.

WEB3.js
Doc: https://web3js.readthedocs.io/en/v1.7.0/

ETHERS.js
Doc: https://docs.ethers.io/v5/

    