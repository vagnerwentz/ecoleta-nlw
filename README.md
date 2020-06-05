<div align=center>
  <img src="https://github.com/vagnerwentz/ecoleta-nlw/blob/master/web/src/assets/logo.svg" width=420 alt="Ecoleta" />
</div>

----

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/vagnerwentz/bootcamp-10-desafio-final?color=%34CB79">

  <a href="https://github.com/vagnerwentz">
    <img alt="Made by Rocketseat" src="https://img.shields.io/badge/made%20by-Vagner Wentz-%34CB79">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-%34CB79">

  <img alt="Stargazers" src="https://img.shields.io/github/stars/vagnerwentz/bootcamp-10-desafio-final?style=social">
</p>


## Sobre :satellite:
O Ecoleta é um projeto ambiental onde podemos cadastrar pontos de coletas, e também podemos descobrir o mais próximo
perto de nós, pelo Estado e a Cidade que estamos localizados. Os resíduos que podemos fazer filtros são

* Resíduos Eletrônicos
* Resíduos Orgânicos
* Pilhas e Baterias
* Papéis e Papelão
* Oléo de Cozinha
* Lâmpadas

<div align=center>
  <img src="https://github.com/vagnerwentz/ecoleta-nlw/blob/master/.github/items.png" alt="Items" width=475/>
</div>

## Funcionalidades :gear:
* Cadastrar ponto de coleta
* Uso do leaflet para integração com mapas
* Adicionar uma imagem do estabeleciomento
* Envio de e-mail e mensagem no Whatsapp do estabelecimento

## Tecnologias :computer:
* TypeScript
* React Native & React JS
* Express
* Knex (Query Builder)
* SQLite
* Axios (API's)
* Celebrate (Validação no back-end)

## Como instalar o projeto
Para a execução do projeto, você necessariamente precisa clonar o projeto na sua máquina, com o comando
```
$ git clone https://github.com/vagnerwentz/ecoleta-nlw.git
```
Logo em seguida você deve ir até o local onde você clonou o projeto e então abaixo as instruções pra cada um.

## :wrench: Back-end
Para a execução do back-end você necessariamente precisa entrar na pasta `server`.
Este link [ImagensSVG](https://gofile.io/d/zhFv6T), contém as SVG do aplicativo, você precisa baixar elas e colocar
na pasta uploads que tem no back-end.
```
# Instalação do node_modules
$ npm install

# Criar as tabelas do banco de dados
$ npm run knex:migrate

# Seed de itens de coleta
$ npm run knex:seed

# Rodar o back-end
$ npm run dev
```

## :computer: Front-end
Para a execução do front-end você necessariamente precisa entrar na pasta `web`.
```
# Instalação do node_modules
$ npm install

# Rodar o front-end
$ npm start
```

## :iphone: Mobile
Para a execução do mobile, você necessariamente precisa entrar na pasta `mobile`. A execução do mobile é um pouco diferente
porque precisamos que o Expo tenha instalado na nossa máquina, e em seguida no celular, caso queira rodar pelo celular físico.
No celular físico é bem fácil, você precisa instalar o aplicativo Expo que está disponível da App Store ou na Play Store, em seguida
criar uma conta, e quando você estiver instalado e ter feito os comandos abaixo. Ele irá abrir uma aba no seu Browser com um QR Code,
e então, ler o QR Code com o seu celular.
Para a utilização de um emulador com o Expo, deixarei um link guia para configuração </br>
[RocketSeat - Emulando React Native com Expo](https://www.youtube.com/watch?v=eSjFDWYkdxM&vl=en)

```
# Instalando o Expo
$ npm install -g explo-cli

# Executando o projeto no Expo (Duas maneiras.)
$ npm start
$ expo start
```
## Visualização da aplicação
[Web Screen](https://www.youtube.com/watch?v=2Qeve4oMyGc)

[Mobile Screen](https://www.youtube.com/watch?v=JcGc2KP3Nbk)

## Como contribuir com o projeto?
1. Faça um fork do projeto
2. Criar uma nova branch com as suas alterações: `git checkout -b your-feature`
3. Salvar as alterações e crie uma mensagem de `commit`relatando o que você fez: `git commit -m "feature: description"`
4. Enviar suas alterações: `git push origin your-feature`
