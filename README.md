# HTML
<!DOCTYPE html>

<html lang="pt-BR">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>NatureFit - Emagrecimento Natural e Saudável</title>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

<style>

/* Reset e estilos gerais */

* {

margin: 0;

padding: 0;

box-sizing: border-box;

font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;

}


body {

color: #333;

line-height: 1.6;

background-color: #f9f9f9;

}


.container {

width: 90%;

max-width: 1200px;

margin: 0 auto;

padding: 0 15px;

}


/* Header */

header {

background: linear-gradient(135deg, #4CAF50 0%, #2E7D32 100%);

color: white;

padding: 15px 0;

position: sticky;

top: 0;

z-index: 100;

box-shadow: 0 2px 10px rgba(0,0,0,0.1);

}


.header-content {

display: flex;

justify-content: space-between;

align-items: center;

}


.logo {

font-size: 24px;

font-weight: bold;

}


.logo span {

color: #FFEB3B;

}


nav ul {

display: flex;

list-style: none;

}


nav ul li {

margin-left: 20px;

}


nav ul li a {

color: white;

text-decoration: none;

font-weight: 500;

transition: all 0.3s ease;

}


nav ul li a:hover {

color: #FFEB3B;

}


/* Hero Section */

.hero {

background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://images.unsplash.com/photo-1490645935967-10de6ba17061?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80') no-repeat center center/cover;

color: white;

padding: 100px 0;

text-align: center;

}


.hero h1 {

font-size: 2.5rem;

margin-bottom: 20px;

text-shadow: 2px 2px 4px rgba(0,0,0,0.5);

}


.hero p {

font-size: 1.2rem;

max-width: 700px;

margin: 0 auto 30px;

}


.btn {

display: inline-block;

background: #FF5722;

color: white;

padding: 12px 30px;

border-radius: 30px;

text-decoration: none;

font-weight: bold;

transition: all 0.3s ease;

border: none;

cursor: pointer;

}


.btn:hover {

background: #E64A19;

transform: translateY(-3px);

box-shadow: 0 5px 15px rgba(0,0,0,0.2);

}


/* Benefícios */

.benefits {

padding: 80px 0;

background: white;

}


.section-title {

text-align: center;

margin-bottom: 50px;

color: #2E7D32;

font-size: 2rem;

}


.benefits-grid {

display: grid;

grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));

gap: 30px;

}


.benefit-card {

background: #f5f5f5;

padding: 30px;

border-radius: 10px;

text-align: center;

transition: transform 0.3s ease;

}


.benefit-card:hover {

transform: translateY(-10px);

box-shadow: 0 10px 20px rgba(0,0,0,0.1);

}


.benefit-icon {

font-size: 40px;

color: #4CAF50;

margin-bottom: 20px;

}


/* Produtos */

.products {

padding: 80px 0;

background: #f5f5f5;

}


.products-grid {

display: grid;

grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));

gap: 30px;

}


.product-card {

background: white;

border-radius: 10px;

overflow: hidden;

box-shadow: 0 5px 15px rgba(0,0,0,0.1);

transition: transform 0.3s ease;

}


.product-card:hover {

transform: translateY(-10px);

}


.product-img {

height: 200px;

background-color: #ddd;

background-position: center;

background-size: cover;

}


.product-info {

padding: 20px;

}


.product-title {

font-size: 1.2rem;

margin-bottom: 10px;

color: #2E7D32;

}


.product-price {

font-size: 1.3rem;

font-weight: bold;

color: #FF5722;

margin-bottom: 15px;

}


/* Depoimentos */

.testimonials {

padding: 80px 0;

background: white;

}


.testimonials-grid {

display: grid;

grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));

gap: 30px;

}


.testimonial-card {

background: #f9f9f9;

padding: 30px;

border-radius: 10px;

box-shadow: 0 5px 15px rgba(0,0,0,0.05);

}


.testimonial-text {

font-style: italic;

margin-bottom: 20px;

}


.testimonial-author {

font-weight: bold;

color: #4CAF50;

}


/* FAQ */

.faq {

padding: 80px 0;

background: #f5f5f5;

}


.faq-item {

margin-bottom: 20px;

background: white;

border-radius: 10px;

overflow: hidden;

box-shadow: 0 5px 15px rgba(0,0,0,0.05);

}


.faq-question {

padding: 20px;

background: #4CAF50;

color: white;

font-weight: bold;

cursor: pointer;

display: flex;

justify-content: space-between;

align-items: center;

}


.faq-answer {

padding: 0 20px;

max-height: 0;

overflow: hidden;

transition: max-height 0.3s ease, padding 0.3s ease;

}


.faq-answer.active {

padding: 20px;

max-height: 500px;

}


/* CTA Final */

.final-cta {

padding: 100px 0;

background: linear-gradient(135deg, #4CAF50 0%, #2E7D32 100%);

color: white;

text-align: center;

}


.final-cta h2 {

font-size: 2.5rem;

margin-bottom: 20px;

}


.final-cta p {

max-width: 700px;

margin: 0 auto 30px;

font-size: 1.2rem;

}


/* Footer */

footer {

background: #333;

color: white;

padding: 50px 0 20px;

text-align: center;

}


.footer-content {

display: grid;

grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));

gap: 30px;

margin-bottom: 30px;

text-align: left;

}


.footer-section h3 {

margin-bottom: 20px;

color: #4CAF50;

}


.footer-bottom {

border-top: 1px solid #555;

padding-top: 20px;

font-size: 0.9rem;

}


/* Responsividade */

@media (max-width: 768px) {

.header-content {

flex-direction: column;

text-align: center;

}


nav ul {

margin-top: 15px;

}


nav ul li {

margin: 0 10px;

}


.hero h1 {

font-size: 2rem;

}


.hero p {

font-size: 1rem;

}

}

</style>

</head>

<body>

<!-- Header -->

<header>

<div class="container header-content">

<div class="logo">Nature<span>Fit</span></div>

<nav>

<ul>

<li><a href="#beneficios">Benefícios</a></li>

<li><a href="#produtos">Produtos</a></li>

<li><a href="#depoimentos">Depoimentos</a></li>

<li><a href="#faq">Perguntas Frequentes</a></li>

</ul>

</nav>

</div>

</header>



<!-- Hero Section -->

<section class="hero">

<div class="container">

<h1>Emagreça de Forma Natural e Saudável</h1>

<p>Descubra o poder dos produtos naturais para alcançar o corpo dos seus sonhos sem sacrificar sua saúde.</p>

<a href="#produtos" class="btn">Conhecer Produtos</a>

</div>

</section>



<!-- Benefícios -->

<section id="beneficios" class="benefits">

<div class="container">

<h2 class="section-title">Por que escolher nossos produtos?</h2>

<div class="benefits-grid">

<div class="benefit-card">

<div class="benefit-icon"><i class="fas fa-leaf"></i></div>

<h3>100% Natural</h3>

<p>Ingredientes totalmente naturais, sem químicos prejudiciais à saúde.</p>

</div>

<div class="benefit-card">

<div class="benefit-icon"><i class="fas fa-bolt"></i></div>

<h3>Resultados Rápidos</h3>

<p>Veja resultados significativos em poucas semanas de uso regular.</p>

</div>

<div class="benefit-card">

<div class="benefit-icon"><i class="fas fa-heart"></i></div>

<h3>Saúde em Primeiro Lugar</h3>

<p>Emagreça com saúde, sem colocar seu bem-estar em risco.</p>

</div>

<div class="benefit-card">

<div class="benefit-icon"><i class="fas fa-award"></i></div>

<h3>Garantia de Qualidade</h3>

<p>Produtos testados e aprovados por nutricionistas e especialistas.</p>

</div>

</div>

</div>

</section>



<!-- Produtos -->

<section id="produtos" class="products">

<div class="container">

<h2 class="section-title">Nossos Produtos</h2>

<div class="products-grid">

<div class="product-card">

<div class="product-img" style="background-image: url('https://images.unsplash.com/photo-1553531384-397c80973a4b?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');"></div>

<div class="product-info">

<h3 class="product-title">Detox Natural</h3>

<p>Limpe seu organismo e acelere o metabolismo com nossa fórmula detox.</p>

<p class="product-price">R$ 89,90</p>

<button class="btn">Comprar Agora</button>

</div>

</div>

<div class="product-card">

<div class="product-img" style="background-image: url('https://images.unsplash.com/photo-1540420773420-3366772f4999?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');"></div>

<div class="product-info">

<h3 class="product-title">Queimador Natural</h3>

<p>Ative a queima de gordura mesmo em repouso com nosso suplemento termogênico.</p>

<p class="product-price">R$ 97,90</p>

<button class="btn">Comprar Agora</button>

</div>

</div>

<div class="product-card">

<div class="product-img" style="background-image: url('https://images.unsplash.com/photo-1535585209827-a15fcdbc4c2d?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');"></div>

<div class="product-info">

<h3 class="product-title">Pacote Completo</h3>

<p>Combine nossos produtos e potencialize seus resultados com desconto especial.</p>

<p class="product-price">R$ 159,90</p>

<button class="btn">Comprar Agora</button>

</div>

</div>

</div>

</div>

</section>



<!-- Depoimentos -->

<section id="depoimentos" class="testimonials">

<div class="container">

<h2 class="section-title">O que nossos clientes dizem</h2>

<div class="testimonials-grid">

<div class="testimonial-card">

<p class="testimonial-text">"Perdi 12kg em 3 meses usando os produtos NatureFit. O melhor é que não senti nenhum efeito colateral, muito pelo contrário, minha saúde melhorou muito!"</p>

<p class="testimonial-author">- Maria Silva, 38 anos</p>

</div>

<div class="testimonial-card">

<p class="testimonial-text">"Sempre tive dificuldade para emagrecer, até encontrar a NatureFit. Os produtos são incríveis e me deram a energia que eu precisava para manter a dieta e os exercícios."</p>

<p class="testimonial-author">- João Santos, 45 anos</p>

</div>

<div class="testimonial-card">

<p class="testimonial-text">"Finalmente encontrei uma forma de emagrecer sem prejudicar minha saúde. Os produtos são naturais e realmente funcionam. Recomendo para todos!"</p>

<p class="testimonial-author">- Ana Costa, 32 anos</p>

</div>

</div>

</div>

</section>



<!-- FAQ -->

<section id="faq" class="faq">

<div class="container">

<h2 class="section-title">Perguntas Frequentes</h2>

<div class="faq-list">

<div class="faq-item">

<div class="faq-question">

Como os produtos funcionam? <span>+</span>

</div>

<div class="faq-answer">

<p>Nossos produtos combinam ingredientes naturais que aceleram o metabolismo, promovem a queima de gordura e ajudam a controlar o apetite, tudo de forma natural e saudável.</p>

</div>

</div>

<div class="faq-item">

<div class="faq-question">

Quanto tempo leva para ver resultados? <span>+</span>

</div>

<div class="faq-answer">

<p>Os resultados variam de pessoa para pessoa, mais a maioria de nossos clientes começa a notar diferenças significativas dentro de 2 a 4 semanas de uso consistente.</p>

</div>

</div>

<div class="faq-item">

<div class="faq-question">

Os produtos têm efeitos colaterais? <span>+</span>

</div>

<div class="faq-answer">

<p>Nossos produtos são 100% naturais e não contêm substâncias sintéticas prejudiciais. No entanto, recomendamos consultar um médico antes de iniciar qualquer novo suplemento, especialmente se você tiver condições médicas preexistentes.</p>

</div>

</div>

<div class="faq-item">

<div class="faq-question">

Como faço para comprar? <span>+</span>

</div>

<div class="faq-answer">

<p>Basta clicar no botão "Comprar Agora" no produto desejado, preencher seus dados de entrega e pagamento. Entregamos em todo o Brasil.</p>

</div>

</div>

</div>

</div>

</section>



<!-- CTA Final -->

<section class="final-cta">

<div class="container">

<h2>Pronto para transformar seu corpo e sua saúde?</h2>

<p>Junte-se a milhares de clientes satisfeitos e comece hoje sua jornada de emagrecimento natural.</p>

<a href="#produtos" class="btn">Quero Emagrecer com Saúde</a>

</div>

</section>



<!-- Footer -->

<footer>

<div class="container">

<div class="footer-content">

<div class="footer-section">

<h3>NatureFit</h3>

<p>Emagrecimento natural e saudável para transformar vidas.</p>

</div>

<div class="footer-section">

<h3>Contato</h3>

<p>Email: contato@naturefit.com</p>

<p>Telefone: (11) 99999-9999</p>

</div>

<div class="footer-section">

<h3>Links Rápidos</h3>

<p><a href="#beneficios" style="color: #fff;">Benefícios</a></p>

<p><a href="#produtos" style="color: #fff;">Produtos</a></p>

<p><a href="#depoimentos" style="color: #fff;">Depoimentos</a></p>

</div>

</div>

<div class="footer-bottom">

<p>&copy; 2023 NatureFit - Todos os direitos reservados</p>

</div>

</div>

</footer>



<script>

// FAQ Accordion

document.querySelectorAll('.faq-question').forEach(question => {

question.addEventListener('click', () => {

const answer = question.nextElementSibling;

const isActive = answer.classList.contains('active');


// Fecha todas as respostas

document.querySelectorAll('.faq-answer').forEach(item => {

item.classList.remove('active');

});


document.querySelectorAll('.faq-question span').forEach(item => {

item.textContent = '+';

});


// Abre a resposta clicada se não estava ativa

if (!isActive) {

answer.classList.add('active');

question.querySelector('span').textContent = '-';

}

});

});



// Smooth scrolling para links internos

document.querySelectorAll('a[href^="#"]').forEach(anchor => {

anchor.addEventListener('click', function (e) {

e.preventDefault();


const targetId = this.getAttribute('href');

if (targetId === '#') return;


const targetElement = document.querySelector(targetId);

if (targetElement) {

window.scrollTo({

top: targetElement.offsetTop - 80,

behavior: 'smooth'

});

}

});

});



// Simulação de adicionar ao carrinho

document.querySelectorAll('.product-card .btn').forEach(button => {

button.addEventListener('click', () => {

const productName = button.parentElement.querySelector('.product-title').textContent;

alert(`${productName} adicionado ao carrinho!`);

// Em uma implementação real, aqui você adicionaria o produto a um carrinho

});

});

</script>

</body>

</html>
