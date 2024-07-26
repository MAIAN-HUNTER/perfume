# Frontend Mentor - product-preview-card-component-main


Olá, Este é mais um dos projeto feito pelo frontend mentor e estou muito feliz de compartilha-lo com o mundo!

## Ideias, Planejamento e Execução
segui o Maximo possivel da padronização de design, instruida pelo desafio do site, porem optei por deixa-la um pouco maior que a original estabelecida, porem sem fugir do padrão mais legivel possivel para o usuario, de varias telas diferentes, seguindo a responsividade de sempre, com uma interface limpa e viva.
### O que eu aprendi
Um uso muito mais amplo e melhor da ferramenta flexbox, essencial para designs front end mais estilizados e estruturados de forma especifica. E tambem, da tag HTML picture para uso de imagens especificas para a responsividade.

Pontos de destaque das tags HTML e classes CSS:

```html
<div class="image">
          <picture>
            <source
              srcset="./images/image-product-mobile.jpg"
              media="(max-width: 600px)" />

            <img src="./images/image-product-desktop.jpg" alt=""
          /></picture>
        </div>
```
```css
@media (max-width: 600px) {
  .container {
    display: block;
    background-color: white;
    border-radius: 10px;
    padding-bottom: 10px;
    max-width: 500px;
  }
  .image img {
    max-width: 280px;
    border-top-left-radius: 8px;
    border-top-right-radius: 8px;
    border-bottom-left-radius: 0px;
  }

  .content {
    display: block;
  }

  .title {
    padding-top: 200px;
  }
  .perfume h2 {
    padding-top: -100px;
  }

  .perfume p {
    padding-top: -100px;
  }

  .value {
    display: flex;
    padding: 0px;
    margin: 0px 10px;
    align-items: center;
  }

  .price-now {
    padding-left: 10px;
  }

  .price-before {
    text-decoration: line-through;
    font-size: 12px;
    padding: 20px;
  }
  .btn {
    margin-right: 0px;
    margin-left: 20px;
    max-width: 240px;
  }
}

```
### Desenvolvimentos futuros
continuarei os desafio de front end

### sites com recursos Úteis

- [site W3schools](https://www.w3schools.com/css/css_rwd_intro.asp) - Este site me auxiliou a me localizar melhor nas diversas ferramentas de estilizações que o CSS tem a oferecer. Com certeza será um site que salvarei nos Favoritos.

## Autor
- Frontend Mentor - [@MAIAN-HUNTER](https://www.frontendmentor.io/profile/MAIAN-HUNTER)
- Linkedin - [Maian-Lucas](https://www.linkedin.com/in/maian-lucas-1a796026a/)

## Conhecimentos
92% de meu conhecimento foi adquirido pelo curso de programação Dev Quest, oa outros 8% foram de documentações de sites da internet como o proprio Frontend Mentor, W3schools e de videos da plataforma youtube.