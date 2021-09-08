[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]


<!-- TABLE OF CONTENTS -->
<p align="center">
  <details open="open">
    <summary>Introdução a Criptomoedas</summary>
    <ol>
     <li>
       <a href="#inicio">Informações básicas para começar a sua jornada</a>
     </li>  
     <li>
       <a href="#carteira-de-criptomoedas">Criando a sua carteira de criptomoedas</a>
       <ul>
          <li><a href="#bitcoin-core---wallet">Bitcoin Core</a></li>
          <li><a href="#electrum---wallet">Electrum</a></li>
          <li><a href="metamask---wallet">Metamask</a></li>
          <li><a href="#trust---wallet">Trust Wallet</a></li>
      </ul>
     </li>
     <li>
        <a href="#acessando-a-blockchain-do-bitcoin">Acessando a Blockchain do bitcoin</a>
       <ul>
         <li><a href="#prerequisites">Prerequisites</a></li>
         <li><a href="#installation">Installation</a></li>
       </ul>
     </li>
     <li><a href="#usage">Usage</a></li>
     <li><a href="#roadmap">Roadmap</a></li>
     <li><a href="#contributing">Contributing</a></li>
     <li><a href="#license">License</a></li>
     <li><a href="#contact">Contact</a></li>
     <li><a href="#acknowledgements">Acknowledgements</a></li>
    </ol>
  </details>
</p>  

<!-- Inicio -->
## Inicio

Para entender as criptomoedas é necessário entender Blockchain.

Blockchain é um tipo de banco de dados que usa criptográfia para armazenar as informações, uma vez que a informação é gravada na blockchain ela nunca mais poderá ser alterada. 

Essa alta segurança no armazenamento de informações é o que tornou a Blockchain uma tecnologia muito explorada. O principal uso da tecnologia é voltado para a área financeira onde todas as transações envolvem dinheiro e por isso necessitam de extrema segurança.

Criptomoedas possuem esse nome justamente por serem transações criptográficas entre pessoas, ou melhor, entre carteiras digitais.
A mais famosa criptomoeda é o bitcoin. 
O bitcoin só existe por que há uma blockchain por trás armazenando as transações, ela possui a mesma finalidade de um livro razão na contabilidade, um livro que confirma a existencia de todas as transações realizadas, outro fator importante é que as carteiras digitais são gravadas na blockchain e por isso você deve entender como funciona a tecnologia, para que você não corra riscos desnecessários.

Diferentemente dos bancos(Bradesco, Santander, itau...) que possuem um banco de dados contendo as informações de cada cliente, na Blockchain essas informações pertencem somente ao usuário sem nenhuma empresa ou governo ter acesso a elas.

Cada um é responsável pela sua conta(carteira), devendo portanto sempre guardar o código de acesso para ela, caso perca o acesso perderá também todo o dinheiro.

<!-- Criando a carteira para Criptomoedas -->
## Carteira de criptomoedas

Para interagir com a blockchain do bitcoin, ethereum e demais criptoativos é necessario usar uma carteira digital.

Neste tópico aprenda a fazer a sua carteira de criptomoedas de modo facil e rápido.

Primeiro escolha um software de wallet(carteiras com criptográfia):
* Bitcoin Core
* Electrum
* Metamask
* Trust wallet

Abaixo você vai encontrar o tutorial de criação para cada uma delas, basta escolher a que mais se adequa ao seu objetivo.

<!-- Crypto wallet - Bitcoin core -->
<br />
<p align="center">
  <a href="https://github.com/fernandosilvap96/criptomoedas/blob/main/bitcoin_wallet/README.md">
    <img src="bitcoin_wallet/bitcoin.png" alt="bitcoin" width="80" height="80">
  </a>

  <h3 align="center">Bitcoin core - Wallet</h3>

  <p align="center">
    <br />
    <a href="https://github.com/fernandosilvap96/criptomoedas/tree/main/bitcoin_wallet"><strong>Tutorial de como usar »</strong></a>
    <br />
    <br />
    <a href="https://bitcoincore.org/en/download/">Download</a>
  </p>
</p>

<!-- Crypto wallet - Electrum -->
<br />
<p align="center">
  <a href="https://github.com/fernandosilvap96/wallets/tree/main/electrum_wallet">
    <img src="bitcoin_wallet/bitcoin.png" alt="bitcoin" width="80" height="80">
  </a>

  <h3 align="center">Electrum - Wallet</h3>

  <p align="center">
    <br />
    <a href="https://github.com/fernandosilvap96/criptomoedas/tree/main/bitcoin_wallet"><strong>Tutorial de como usar »</strong></a>
    <br />
    <br />
    <a href="https://bitcoincore.org/en/download/">Download</a>
  </p>
</p>

<!-- Crypto wallet - Metamask -->
<br />
<p align="center">
  <a href="https://github.com/fernandosilvap96/wallets/tree/main/electrum_wallet">
    <img src="bitcoin_wallet/bitcoin.png" alt="bitcoin" width="80" height="80">
  </a>

  <h3 align="center">Metamask - Wallet</h3>

  <p align="center">
    <br />
    <a href="https://github.com/fernandosilvap96/criptomoedas/tree/main/bitcoin_wallet"><strong>Tutorial de como usar »</strong></a>
    <br />
    <br />
    <a href="https://bitcoincore.org/en/download/">Download</a>
  </p>
</p>

<!-- Crypto wallet - Trust Wallet -->
<br />
<p align="center">
  <a href="https://github.com/fernandosilvap96/wallets/tree/main/electrum_wallet">
    <img src="bitcoin_wallet/bitcoin.png" alt="bitcoin" width="80" height="80">
  </a>

  <h3 align="center">Trust - Wallet</h3>

  <p align="center">
    <br />
    <a href="https://github.com/fernandosilvap96/criptomoedas/tree/main/bitcoin_wallet"><strong>Tutorial de como usar »</strong></a>
    <br />
    <br />
    <a href="https://bitcoincore.org/en/download/">Download</a>
  </p>
</p>






<!-- Blockchain do bitcoin -->
## Acessando a Blockchain do bitcoin

Com a sua crypto wallet criada, agora podemos acessar a blockchain do bitcoin para efetuar transações.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```JS
   const API_KEY = 'ENTER YOUR API';
   ```



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_



<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/othneildrew/Best-README-Template/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Your Name - [@your_twitter](https://twitter.com/your_username) - email@example.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Pages](https://pages.github.com)
* [Animate.css](https://daneden.github.io/animate.css)
* [Loaders.css](https://connoratherton.com/loaders)
* [Slick Carousel](https://kenwheeler.github.io/slick)
* [Smooth Scroll](https://github.com/cferdinandi/smooth-scroll)
* [Sticky Kit](http://leafo.net/sticky-kit)
* [JVectorMap](http://jvectormap.com)
* [Font Awesome](https://fontawesome.com)





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
