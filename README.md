<div align=center>
  <img src="https://github.com/vagnerwentz/ecoleta-nlw/blob/master/web/src/assets/logo.svg" width=420 alt="Ecoleta" />
</div>

----

## Sobre :satellite:
O Ecoleta é um projeto ambiental onde podemos cadastrar pontos de coletas, e também podemos descobrir o mais próximo
perto de nós, pelo Estado e a Cidade que estamos localizados. Os resíduos que podemos fazer filtros são

* Resíduos Eletrônicos
* Resíduos Orgânicos
* Pilhas e Baterias
* Papéis e Papelão
* Oléo de Cozinha
* Lâmpadas

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
git clone https://github.com/vagnerwentz/ecoleta-nlw.git
```
Logo em seguida você deve ir até o local onde você clonou o projeto e então abaixo as instruções pra cada um.

## :wrench: Back-end
Para a execução do back-end você necessariamente precisa entrar na pasta `server`.
```
# Instalação do node_modules
npm install

# Criar as tabelas do banco de dados
npm run knex:migrate

# Seed de itens de coleta
npm run knex:seed

# Rodar o back-end
npm run dev
```

## :computer: Front-end
Para a execução do front-end você necessariamente precisa entrar na pasta `web`.
```
# Instalação do node_modules
npm install

# Rodar o front-end
npm start
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
npm install -g explo-cli

# Executando o projeto no Expo (Duas maneiras.)
npm start
expo start
```
