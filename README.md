# Livro sem Apego

> O [Livro sem Apego](http://livrosemapego.com.br) é um site de doação de livros sem fins lucrativos com objetivo de ajuda alguém que esteja precisando de um livro mas não tem condições de comprá-lo ou simplesmente gostaria de ganhá-lo.


## Estrutura do Projeto

Ao construir o site, utilizamos uma estrutura criada do zero utilizando alguns pré-processadores como **Stylus**, **Pug** e para renderizar alguns componentes **Vue.js**


### Componentes
Para renderizar alguns componentes que precisam de dados do banco de dados, utilizamos **Vue.js**, que foi nossa primeira experiência com uma lib js para criação de componentes, por conta disso não fizemos o site em SPA.


### Rodando o Projeto

O projeto precisa ser rodado em cima de um servidor Apache, pois utilizamos urls amigáveis graças ao **.htaccess**. Enfim, para os arquivos estáticos utilizamos o **Gulp.js** como automatizar de tarefas, então para rodar basta acessar o diretório ```src/tools``` e rode os comandos:

```
1. npm install
2. npm run gulp
``` 

#### Rodando os componentes 

Utilizamos uma template do **vue-cli** com **Browerify** e implementamos em nossa estrutura, então para rodar os componentes basta acessar ```src/vue``` e execute os comandos:

```
1. npm install
2. npm run watchify
``` 


## Contribua! :)

```
git clone git@github.com:mtsalcova/livro-sem-apego.git
```

Só aceitamos deploy na branch **dev** e antes de fazer o **push**, não se esqueça de executar os comandos nos seguintes diretórios o/: 

* **src/tools**
```
npm run gulp build
```
* **src/vue**
```
npm run build
```


## Licença
[MIT Licence](https://github.com/mtsalcova/livro-sem-apego/blob/master/LICENSE) © [Livro sem Apego](http://livrosemapego.com.br)



