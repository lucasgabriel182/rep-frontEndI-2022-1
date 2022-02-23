#BACKGROUNDS

background-color: 
background-image: url('../img/bici.jpg')
background-repeat: repeat-x /_repeat, no repeat, repeat-x, repeat-y, round e space_/
background-position: right top
background-attachment: fixed /_fixed, scroll, inherit e initial_/
background-size: 130px /* auto cover (centralizar) contain (toda a imagem) */

---

#FONTES

@import



@font-face {
font-family: "Roboto";
  src: url("../fonts/Roboto/Roboto-Regular.ttf");
}

---

#icones

Google Fonts - ícones

<link href="https://fonts.googleapis.com/icon?family=Material+Icons"
      rel="stylesheet">

---


#METODOLOGIA BEM

- padrão de nomenclatura para manter o projeto simples e organizado
- Block Element Modifier
- Bloco Elemento Modificador

EX:

.container {

}

.container__titulo {
  color: red;
  font-size:30px;
}

.container__tiutlo--destaque{
  color: blue;
}





<ul class="lista">
  <li class="lista__item lista__item--destacado">
    <h2 class="lista__titulo">Publicações do autor Fulano</h2>
    <p class="lista__autor">Nome do autor</p>    
    <p class="lista__texto">texto texto</p>
  </li>
</ul>


<div class="container">
   <button class="container__botao1">botao 1</button>
   <button class="container__botao2 container__botao2--hover">botao 2</button>
</div>


* Material extra: https://medium.com/trainingcenter/bem-em-5min-f5c80fd23439