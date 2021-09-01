<a name="topo"></a>
# Desafio Final - Grupo 6 - CoreBiz

Este é o desafio final do Grupo 6 do Hiring Coders #2. O desafio consistem em desenvolver uma loja Vtex com consumo de API's com o front-end baseado na temática da parceira e patrocinadora corebiz.

O contexto completo do desafio está [aqui](https://drive.google.com/file/d/1cjX4W7MmtVMAX0HBbl17eaJcD1N-B223/view).

## Preview

Você pode conferir aqui nesse [link](https://lucasvihuchi--hiringcoders202106.myvtex.com/)

![](https://github.com/LucasVihuchi/desafio-final-corebiz-hiring-coders/blob/main/docs/img/home2.png)

## Estruturação da loja

A loja foi pensada para ser composta por 5 páginas:

	* Home
	* Sobre
	* Produtos
	* Contato
	* Blog

As página "Home" e "Sobre" seguem os mesmos padrões da corebiz com as informações e caracteríticas principais da marca. As páginas "produtos" e "contato" são as que, conforme solicitado no desafio, entregam o consumo da API vtex e AWS, nelas podemos verirficar os produtos, fazer a compra desses produtos e observar a lista de clientes. O link do header denominado "blog" redireciona para um link externo mantido pela corebiz.

### Dependências
- [Store](https://github.com/vtex-apps/store/blob/master/README.md)
- [Store GraphQL](https://github.com/vtex-apps/store-graphql/blob/master/docs/README.md)
- [Add to Cart Button](https://vtex.io/docs/components/all/vtex.add-to-cart-button@0.26.12/)
- [Breadcrumb](https://vtex.io/docs/components/all/vtex.breadcrumb/)
- [Carousel](https://vtex.io/docs/releases/2019-week-43-44/carousel)
- [Category Menu](https://vtex.io/docs/components/all/vtex.category-menu@2.16.0/)
- [Checkout Summary](https://vtex.io/docs/app/vtex.checkout-summary@0.18.0/)
- [Condition Layout](https://developers.vtex.com/vtex-developer-docs/docs/vtex-condition-layout)
- [CSS Handles](https://developers.vtex.com/vtex-developer-docs/docs/vtex-io-documentation-using-css-handles-for-store-customization)
- [Disclosure Layout](https://developers.vtex.com/vtex-developer-docs/docs/vtex-disclosure-layout)
- [Flex Layout](https://vtex.io/docs/components/all/vtex.flex-layout/)
- [Footer](https://vtex.io/docs/components/all/vtex.store-footer/)
- [Header](https://vtex.io/docs/components/all/vtex.store-header@2.26.0/)
- [Icons](https://developers.vtex.com/vtex-developer-docs/docs/vtex-store-icons#icons)
- [Image](https://developers.vtex.com/vtex-developer-docs/docs/vtex-store-components-image)
- [Link](https://developers.vtex.com/vtex-developer-docs/docs/vtex-store-link)
- [Locale Switcher](https://developers.vtex.com/vtex-developer-docs/docs/vtex-locale-switcher)
- [Login](https://vtex.io/docs/app/vtex.login@2.45.5/)
- [Logo](https://vtex.io/docs/components/all/vtex.store-components@3.151.2/logo/)
- [Minicart](https://vtex.io/docs/components/all/vtex.minicart/)
- [Modal layout](https://developers.vtex.com/vtex-developer-docs/docs/vtex-modal-layout)
- [Menu](https://developers.vtex.com/vtex-developer-docs/docs/vtex-menu)
- [My Account](https://developers.vtex.com/vtex-developer-docs/docs/my-account)
- [Order Placed](https://vtex.io/docs/components/content-blocks/vtex.order-placed/readme)
- [Product Bookmark Interface](https://github.com/vtex-apps/product-bookmark-interfaces)
- [Product Customizer](https://vtex.io/docs/components/all/vtex.product-customizer@2.11.0/)
- [Product Details](https://vtex.io/docs/components/all/vtex.product-details@1.20.0/)
- [Product Gifs](https://developers.vtex.com/vtex-developer-docs/docs/vtex-product-gifts)
- [Product Highlights](https://developers.vtex.com/vtex-developer-docs/docs/vtex-store-components-producthighlights)
- [Product Identifier](https://vtex.io/docs/components/all/vtex.product-identifier/)
- [Product Kit](https://developers.vtex.com/vtex-developer-docs/docs/vtex-product-kit)
- [Product Price](https://developers.vtex.com/vtex-developer-docs/docs/vtex-product-price)
- [Product Quantity](https://developers.vtex.com/vtex-developer-docs/docs/vtex-product-quantity)
- [Product Review Interfaces](https://vtex.io/docs/components/all/vtex.product-review-interfaces@1.0.2/)
- [Product Specification](https://vtex.io/docs/app/vtex.product-specification-badges@0.4.0/)
- [Product Specifications](https://developers.vtex.com/vtex-developer-docs/docs/vtex_store-components_productspecifications)
- [Product Summary](https://vtex.io/docs/app/vtex.product-summary)
- [Product Summary List](https://vtex.io/docs/components/all/vtex.product-summary/product-summary-list)
- [Responsive Layout](https://developers.vtex.com/vtex-developer-docs/docs/vtex-responsive-layout)
- [Review and Ratings](https://developers.vtex.com/vtex-developer-docs/docs/vtex-reviews-and-ratings)
- [Rich Text](https://developers.vtex.com/vtex-developer-docs/docs/vtex-rich-text)
- [Shelf](https://vtex.io/docs/components/all/vtex.shelf/)
- [Slider Layout](https://vtex.io/docs/app/vtex.slider-layout@0.19.2)
- [Slider](https://developers.vtex.com/vtex-developer-docs/docs/vtex-store-components-slider)
- [Styleguide](https://styleguide.vtex.com/#/Styles)
- [Stack Layout](https://vtex.io/docs/components/all/vtex.stack-layout@0.1.0/)
- [Sticky Layout](https://vtex.io/docs/components/all/vtex.sticky-layout/)
- [Store Drawer](https://developers.vtex.com/vtex-developer-docs/docs/vtex-store-drawer)
- [Search Result](https://vtex.io/docs/components/all/vtex.search-result@3.108.0)
- [Store Components](https://vtex.io/docs/components/all/vtex.store-components@3.151.2/)
- [Store Form](https://developers.vtex.com/vtex-developer-docs/docs/vtex-store-form)
- [Tab Layout](https://developers.vtex.com/vtex-developer-docs/docs/vtex-tab-layout)
- [Telemarketing](https://vtex.io/docs/components/all/vtex.telemarketing@2.10.2/)
- [Video](https://developers.vtex.com/vtex-developer-docs/docs/vtex-store-video)

### Aplicativos Vtex usados
- [Checkout Custom](https://apps.vtex.com/vtex-checkout-ui-custom/p)
- [Customer Credit](https://apps.vtex.com/vtex-customer-credit/p)

<a name="ancora"></a>
## Componentes

Os componentes da loja elaborados para o desafio foram:

* [Api Vtex IO](https://github.com/albertohf/AdminRepoVtexIO)
* [Api AWS](https://github.com/guilhermanosilva/aws-api-hiring-coders)
* [Componente Cadastro Leads](https://github.com/guilhermanosilva/form-lead-component-vtex)
* [Componente Lista de Leads Admin] (https://github.com/guilhermanosilva/list-leads-admin-component-vtex)
* [Header](#ancora3)
* [Footer](#ancora4)
* [Home](#ancora5)
* [Sobre](#ancora6)
* [Produtos](#ancora7)
* [Contato](#ancora8)



Abaixo você pode conferir como realizamos a construção de cada um destes compenentes.

:arrow_up:[Ver componentes](#ancora)

<a id="ancora3"></a>
### Header

![](https://github.com/LucasVihuchi/desafio-final-corebiz-hiring-coders/blob/main/docs/img/headerv.gif)

O Header responsivo foi desenvolvido através dos blocos "header-layout.desktop" e "header-layout.mobile". O layout desktop conta com o logo, um menu de navegação e um minicart, organizados em um "flex-layout". Já o layout mobile, mantém o logo e minicart, e a navegação é condensada em um menu gaveta.

:arrow_up:[Ver componentes](#ancora)

<a id="ancora4"></a>
### Footer

![](https://github.com/LucasVihuchi/desafio-final-corebiz-hiring-coders/blob/main/docs/img/footer.png)

O footer responsivo com os blocos "footer-layout.desktop" e "footer-layout.mobile" também utiliza o flex layout para organizar o logo, os endereços da corebiz em cada país, as redes sociais, o copyright e um botão que leva ao topo da página.

:arrow_up:[Ver componentes](#ancora)

<a id="ancora5"></a>
### Home

![](https://github.com/LucasVihuchi/desafio-final-corebiz-hiring-coders/blob/main/docs/img/home2.png)

O store.home, baseado na aparência do site original, tem como objetivo trazer de mensagem inicial a presença global da corebiz. Desta forma, a home foi divida em seções para separar cada parte dessa página inicial. Na primeira seção há uma imagem de fundo com o mapa de presença, mais um "stack-layout" estilizado com blocos "rich-text" para o título, subtítulo e estatísticas. Na seção seguinte, os ícones de parceiros foram baixados diretamente da página oficial da corebiz e sincronizadas através do asset builder, mostrando alguns dos principais clientes da empresa. Já na terceira seção, o uso das imagens também seguiram o mesmo critério, porém foi utilizado o "slider-layout" para mostrar cada imagem ao clicar nas setas de ambos os lados, direita ou esquerda. A quarta seção foi estilizada usando dois blocos de "info-cards" para mostrar as atuações da corebiz na mídia. Com isso, finalizando com a quinta seção, nela é mostrada as principais notícias e conteúdos do blog da corebiz, usando-se o "rich-text", "flex-layout" e "image" para os títulos, hashtags e imagens referentes ao conteúdo descrito.

:arrow_up:[Ver componentes](#ancora)

<a id="ancora6"></a>
### Sobre

![](https://github.com/LucasVihuchi/desafio-final-corebiz-hiring-coders/blob/main/docs/img/sobre.png)

A página about-us traz a missão e valores que são a base da corebiz. Foi utilizado "flex-layout" para compor o design das imagens com os textos e foi inserido um "tablayout" estilizado para descrever o framework de transformação digital da empresa, separando os seguimentos canal de vendas, taxa de conversão, marketing de performance e projetos ominichannel.

:arrow_up:[Ver componentes](#ancora)

<a id="ancora7"></a>
### Produtos

![](https://github.com/LucasVihuchi/desafio-final-corebiz-hiring-coders/blob/main/docs/img/produtos.png)

Após cadastrar e ativar as marcas, categorias e produtos através do Admin, a página de produtos foi criada através de um bloco customizado "store.custom#products" com um "search-result-layout", filtrando apenas os óculos e estabelecendo um máximo de 8 produtos por página. Possui a opção de visualização em grid ou lista e customização dos filtros de busca.

:arrow_up:[Ver componentes](#ancora)

<a id="ancora8"></a>
### Contato

![](https://github.com/LucasVihuchi/desafio-final-corebiz-hiring-coders/blob/main/docs/img/contactv.gif)

A área de contato do site abre um modal para cadastro de leads de clientes que se conecta a API AWS. Foi utilizado um Componente VTEX com um formulário de cadastro contendo os campos nome, email, telefone, e um registro automático de prospect para possivelmente ser transformado em cliente caso o usuário finalize alguma compra na loja. Mais detalhes [aqui](https://github.com/guilhermanosilva/form-lead-component-vtex). 

:arrow_up:[Ver componentes](#ancora)

## Sobre o grupo :sparkles:

Ao todo o nosso grupo é composto de 10 integrantes. Nos dividimos em back-end e front-end para elaborar desafio. Utilizamos a metodologia Kanban e a ferramenta Trello para nos organizar e ter ciência das atividades a fazer, em andamento e controle do que já foi concluído. Também elaboramos um fluxograma das atividades que você pode conferir [aqui](https://whimsical.com/grupo-6-corebiz-5vTgcgdSLVoBVeyzVwHgSK).

Camilla        | Alberto        | Lucas Ramos    |Jefferson       | 
-------------- | -------------- | -------------- | -------------- |
<a href="https://www.linkedin.com/in/camillabarros/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>| <a href="https://www.linkedin.com/in/albertohfernandes/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>| <a href="https://www.linkedin.com/in/lucas-ramos-gmp/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>| <a href="https://www.linkedin.com/in/jeffersonklamasmarzani/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>| 

Lucas Vihuchi  | Laura          | Guilhermano    | Evelyn         | 
-------------- | -------------- | -------------- | -------------- |
<a href="https://www.linkedin.com/in/lucasvihuchibraga/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>| <a href="https://www.linkedin.com/in/laurapelaezmuller/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>| <a href="https://www.linkedin.com/in/guilhermanosilva/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>| <a href="https://www.linkedin.com/in/evelyncper"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>|

Breno          |
-------------- |
<a href="https://www.linkedin.com/in/breno-brito-cruz-477a83213/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>|



:top:[Topo](#topo)
