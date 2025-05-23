<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loja Online - Seu Produto Digital | Kiwify</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        .product-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
        }
        .cta-button {
            transition: all 0.3s ease;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        .cta-button:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 12px rgba(0,0,0,0.15);
        }
        .floating-cart {
            animation: pulse 2s infinite;
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.1); }
            100% { transform: scale(1); }
        }
        .testimonial-card {
            transition: all 0.3s ease;
        }
        .testimonial-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        }
    </style>
</head>
<body class="font-sans bg-gray-50">
    <!-- Header -->
    <header class="bg-white shadow-sm sticky top-0 z-50">
        <div class="container mx-auto px-4 py-4 flex justify-between items-center">
            <div class="flex items-center">
                <i class="fas fa-store text-2xl text-blue-600 mr-2"></i>
                <span class="text-xl font-bold text-gray-800">Minha Loja Digital</span>
            </div>
            <div class="hidden md:flex items-center space-x-6">
                <a href="#produtos" class="text-gray-600 hover:text-blue-600">Produtos</a>
                <a href="#depoimentos" class="text-gray-600 hover:text-blue-600">Depoimentos</a>
                <a href="#sobre" class="text-gray-600 hover:text-blue-600">Sobre</a>
                <a href="#contato" class="text-gray-600 hover:text-blue-600">Contato</a>
            </div>
            <div class="flex items-center space-x-4">
                <a href="#" class="relative">
                    <i class="fas fa-shopping-cart text-xl text-gray-600 hover:text-blue-600"></i>
                    <span class="absolute -top-2 -right-2 bg-red-500 text-white text-xs rounded-full w-5 h-5 flex items-center justify-center">3</span>
                </a>
                <button class="md:hidden text-gray-600">
                    <i class="fas fa-bars text-2xl"></i>
                </button>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="py-16 bg-gradient-to-r from-blue-50 to-indigo-50">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-8 md:mb-0 md:pr-8">
                    <h1 class="text-4xl md:text-5xl font-bold text-gray-800 mb-4">Transforme sua vida com nossos <span class="text-blue-600">produtos digitais</span></h1>
                    <p class="text-xl text-gray-600 mb-6">Acesso imediato, resultados comprovados e suporte exclusivo para você alcançar seus objetivos.</p>
                    
                    <div class="flex items-center mb-6">
                        <div class="flex -space-x-2 mr-4">
                            <img src="https://randomuser.me/api/portraits/women/44.jpg" class="w-10 h-10 rounded-full border-2 border-white" alt="Cliente satisfeita">
                            <img src="https://randomuser.me/api/portraits/men/32.jpg" class="w-10 h-10 rounded-full border-2 border-white" alt="Cliente satisfeito">
                            <img src="https://randomuser.me/api/portraits/women/68.jpg" class="w-10 h-10 rounded-full border-2 border-white" alt="Cliente satisfeita">
                        </div>
                        <div>
                            <p class="text-sm text-gray-600"><span class="font-bold">+2.543</span> clientes satisfeitos</p>
                            <div class="flex text-yellow-400">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star-half-alt"></i>
                            </div>
                        </div>
                    </div>
                    
                    <a href="#produtos" class="cta-button inline-block bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-8 rounded-lg text-lg">
                        <i class="fas fa-shopping-bag mr-2"></i>VER PRODUTOS
                    </a>
                </div>
                
                <div class="md:w-1/2">
                    <img src="https://via.placeholder.com/600x400?text=Produto+Digital" alt="Produto Digital" class="rounded-xl shadow-xl w-full">
                </div>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">Por que comprar conosco?</h2>
                <p class="text-xl text-gray-600 max-w-2xl mx-auto">Oferecemos a melhor experiência em produtos digitais com benefícios exclusivos</p>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-gray-50 p-6 rounded-xl">
                    <div class="w-14 h-14 bg-blue-100 rounded-full flex items-center justify-center mb-4 mx-auto">
                        <i class="fas fa-bolt text-blue-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-800 mb-3 text-center">Acesso Imediato</h3>
                    <p class="text-gray-600 text-center">Receba seu produto digital assim que o pagamento for confirmado, sem espera.</p>
                </div>
                
                <div class="bg-gray-50 p-6 rounded-xl">
                    <div class="w-14 h-14 bg-green-100 rounded-full flex items-center justify-center mb-4 mx-auto">
                        <i class="fas fa-shield-alt text-green-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-800 mb-3 text-center">Garantia de 7 Dias</h3>
                    <p class="text-gray-600 text-center">Se não gostar, devolvemos seu dinheiro sem burocracia.</p>
                </div>
                
                <div class="bg-gray-50 p-6 rounded-xl">
                    <div class="w-14 h-14 bg-purple-100 rounded-full flex items-center justify-center mb-4 mx-auto">
                        <i class="fas fa-headset text-purple-600 text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-800 mb-3 text-center">Suporte Exclusivo</h3>
                    <p class="text-gray-600 text-center">Nossa equipe está pronta para te ajudar com qualquer dúvida.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Products Section -->
    <section id="produtos" class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">Nossos Produtos</h2>
                <p class="text-xl text-gray-600 max-w-2xl mx-auto">Escolha o produto ideal para suas necessidades</p>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Product 1 -->
                <div class="product-card bg-white p-6 rounded-xl shadow-md transition duration-300">
                    <div class="mb-4">
                        <img src="https://via.placeholder.com/400x300?text=E-book+Premium" alt="E-book Premium" class="rounded-lg w-full">
                    </div>
                    <div class="flex justify-between items-start mb-3">
                        <h3 class="text-xl font-bold text-gray-800">E-book Premium</h3>
                        <span class="bg-green-100 text-green-800 text-sm py-1 px-2 rounded-full">Mais vendido</span>
                    </div>
                    <p class="text-gray-600 mb-4">Guia completo com estratégias comprovadas para alcançar seus objetivos.</p>
                    
                    <div class="flex items-center mb-4">
                        <div class="flex text-yellow-400 mr-2">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star-half-alt"></i>
                        </div>
                        <span class="text-sm text-gray-500">(127 avaliações)</span>
                    </div>
                    
                    <div class="mb-6">
                        <span class="text-gray-500 line-through">R$97,00</span>
                        <span class="text-2xl font-bold text-gray-800 ml-2">R$47,00</span>
                        <span class="text-sm text-green-600 ml-2">ou 5x de R$9,40</span>
                    </div>
                    
                    <a href="#" class="cta-button block w-full bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-4 rounded-lg text-center">
                        <i class="fas fa-cart-plus mr-2"></i>COMPRAR AGORA
                    </a>
                </div>
                
                <!-- Product 2 -->
                <div class="product-card bg-white p-6 rounded-xl shadow-md transition duration-300">
                    <div class="mb-4">
                        <img src="https://via.placeholder.com/400x300?text=Curso+Online" alt="Curso Online" class="rounded-lg w-full">
                    </div>
                    <div class="flex justify-between items-start mb-3">
                        <h3 class="text-xl font-bold text-gray-800">Curso Online</h3>
                        <span class="bg-blue-100 text-blue-800 text-sm py-1 px-2 rounded-full">Novidade</span>
                    </div>
                    <p class="text-gray-600 mb-4">Aulas em vídeo com passo a passo detalhado para você dominar o assunto.</p>
                    
                    <div class="flex items-center mb-4">
                        <div class="flex text-yellow-400 mr-2">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                        </div>
                        <span class="text-sm text-gray-500">(89 avaliações)</span>
                    </div>
                    
                    <div class="mb-6">
                        <span class="text-gray-500 line-through">R$197,00</span>
                        <span class="text-2xl font-bold text-gray-800 ml-2">R$97,00</span>
                        <span class="text-sm text-green-600 ml-2">ou 6x de R$16,17</span>
                    </div>
                    
                    <a href="#" class="cta-button block w-full bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-4 rounded-lg text-center">
                        <i class="fas fa-cart-plus mr-2"></i>COMPRAR AGORA
                    </a>
                </div>
                
                <!-- Product 3 -->
                <div class="product-card bg-white p-6 rounded-xl shadow-md transition duration-300">
                    <div class="mb-4">
                        <img src="https://via.placeholder.com/400x300?text=Kit+Completo" alt="Kit Completo" class="rounded-lg w-full">
                    </div>
                    <div class="flex justify-between items-start mb-3">
                        <h3 class="text-xl font-bold text-gray-800">Kit Completo</h3>
                        <span class="bg-red-100 text-red-800 text-sm py-1 px-2 rounded-full">Oferta</span>
                    </div>
                    <p class="text-gray-600 mb-4">Pacote completo com e-book, curso online e bônus exclusivos.</p>
                    
                    <div class="flex items-center mb-4">
                        <div class="flex text-yellow-400 mr-2">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                        </div>
                        <span class="text-sm text-gray-500">(214 avaliações)</span>
                    </div>
                    
                    <div class="mb-6">
                        <span class="text-gray-500 line-through">R$297,00</span>
                        <span class="text-2xl font-bold text-gray-800 ml-2">R$147,00</span>
                        <span class="text-sm text-green-600 ml-2">ou 8x de R$18,38</span>
                    </div>
                    
                    <a href="#" class="cta-button block w-full bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-4 rounded-lg text-center">
                        <i class="fas fa-cart-plus mr-2"></i>COMPRAR AGORA
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section id="depoimentos" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">O que nossos clientes dizem</h2>
                <p class="text-xl text-gray-600 max-w-2xl mx-auto">Depoimentos reais de pessoas que transformaram suas vidas</p>
            </div>
            
            <div class="grid md:grid-cols-2 gap-8">
                <!-- Testimonial 1 -->
                <div class="testimonial-card bg-gray-50 p-6 rounded-xl">
                    <div class="flex items-center mb-4">
                        <img src="https://randomuser.me/api/portraits/women/33.jpg" alt="Ana Claudia" class="w-12 h-12 rounded-full mr-4">
                        <div>
                            <h3 class="font-bold text-gray-800">Ana Claudia</h3>
                            <div class="flex text-yellow-400 text-sm">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-600 mb-4 italic">"Comprei o e-book e foi a melhor decisão que tomei. As estratégias são simples mas muito eficientes. Em 30 dias já via resultados impressionantes!"</p>
                    <div class="flex justify-between items-center">
                        <span class="text-sm text-gray-500">Comprou: E-book Premium</span>
                        <span class="text-sm text-gray-500">Publicado há 2 semanas</span>
                    </div>
                </div>
                
                <!-- Testimonial 2 -->
                <div class="testimonial-card bg-gray-50 p-6 rounded-xl">
                    <div class="flex items-center mb-4">
                        <img src="https://randomuser.me/api/portraits/men/45.jpg" alt="Ricardo" class="w-12 h-12 rounded-full mr-4">
                        <div>
                            <h3 class="font-bold text-gray-800">Ricardo</h3>
                            <div class="flex text-yellow-400 text-sm">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star-half-alt"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-600 mb-4 italic">"O curso online superou minhas expectativas. As aulas são bem explicadas e o suporte da equipe é excelente. Recomendo para todos que querem resultados rápidos."</p>
                    <div class="flex justify-between items-center">
                        <span class="text-sm text-gray-500">Comprou: Curso Online</span>
                        <span class="text-sm text-gray-500">Publicado há 1 mês</span>
                    </div>
                </div>
                
                <!-- Testimonial 3 -->
                <div class="testimonial-card bg-gray-50 p-6 rounded-xl">
                    <div class="flex items-center mb-4">
                        <img src="https://randomuser.me/api/portraits/women/68.jpg" alt="Fernanda" class="w-12 h-12 rounded-full mr-4">
                        <div>
                            <h3 class="font-bold text-gray-800">Fernanda</h3>
                            <div class="flex text-yellow-400 text-sm">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-600 mb-4 italic">"Adquiri o Kit Completo e valeu cada centavo. Os bônus são incríveis e me ajudaram muito. Aprendi mais em um mês do que em anos pesquisando por conta própria."</p>
                    <div class="flex justify-between items-center">
                        <span class="text-sm text-gray-500">Comprou: Kit Completo</span>
                        <span class="text-sm text-gray-500">Publicado há 3 semanas</span>
                    </div>
                </div>
                
                <!-- Testimonial 4 -->
                <div class="testimonial-card bg-gray-50 p-6 rounded-xl">
                    <div class="flex items-center mb-4">
                        <img src="https://randomuser.me/api/portraits/men/32.jpg" alt="Roberto" class="w-12 h-12 rounded-full mr-4">
                        <div>
                            <h3 class="font-bold text-gray-800">Roberto</h3>
                            <div class="flex text-yellow-400 text-sm">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-600 mb-4 italic">"A garantia de 7 dias me deu segurança para comprar. Acabei nem precisando usar porque o produto é excelente. Já indiquei para vários amigos e todos estão amando."</p>
                    <div class="flex justify-between items-center">
                        <span class="text-sm text-gray-500">Comprou: E-book Premium</span>
                        <span class="text-sm text-gray-500">Publicado há 5 dias</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="sobre" class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-8 md:mb-0 md:pr-8">
                    <img src="https://via.placeholder.com/600x400?text=Sobre+Nós" alt="Sobre Nós" class="rounded-xl shadow-xl w-full">
                </div>
                
                <div class="md:w-1/2">
                    <h2 class="text-3xl font-bold text-gray-800 mb-4">Quem somos</h2>
                    <p class="text-gray-600 mb-4">Somos uma equipe de especialistas apaixonados por criar produtos digitais que realmente fazem a diferença na vida das pessoas.</p>
                    <p class="text-gray-600 mb-6">Nossa missão é oferecer conteúdo de alta qualidade, com abordagens práticas e resultados comprovados, para ajudar você a alcançar seus objetivos de forma rápida e eficiente.</p>
                    
                    <div class="space-y-4">
                        <div class="flex items-start">
                            <i class="fas fa-check-circle text-green-500 text-xl mt-1 mr-3"></i>
                            <div>
                                <h3 class="font-bold text-gray-800">+5 anos de experiência</h3>
                                <p class="text-gray-600">Já ajudamos milhares de pessoas a transformarem suas vidas</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <i class="fas fa-check-circle text-green-500 text-xl mt-1 mr-3"></i>
                            <div>
                                <h3 class="font-bold text-gray-800">Conteúdo Atualizado</h3>
                                <p class="text-gray-600">Nossos produtos são revisados constantemente para manter a qualidade</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <i class="fas fa-check-circle text-green-500 text-xl mt-1 mr-3"></i>
                            <div>
                                <h3 class="font-bold text-gray-800">Compromisso com Resultados</h3>
                                <p class="text-gray-600">Nosso foco é seu sucesso e satisfação</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section class="py-16 bg-gradient-to-r from-blue-600 to-indigo-600 text-white">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl font-bold mb-4">Pronto para transformar sua vida?</h2>
            <p class="text-xl opacity-90 max-w-2xl mx-auto mb-8">Escolha seu produto e comece hoje mesmo sua jornada de transformação</p>
            
            <a href="#produtos" class="cta-button inline-block bg-white hover:bg-gray-100 text-blue-600 font-bold py-3 px-8 rounded-lg text-lg">
                <i class="fas fa-shopping-bag mr-2"></i>VER PRODUTOS
            </a>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contato" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">Entre em contato</h2>
                <p class="text-xl text-gray-600 max-w-2xl mx-auto">Tire suas dúvidas ou envie sugestões</p>
            </div>
            
            <div class="max-w-2xl mx-auto">
                <form class="space-y-6">
                    <div class="grid md:grid-cols-2 gap-6">
                        <div>
                            <label for="name" class="block text-gray-700 font-medium mb-2">Nome</label>
                            <input type="text" id="name" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-blue-500">
                        </div>
                        <div>
                            <label for="email" class="block text-gray-700 font-medium mb-2">E-mail</label>
                            <input type="email" id="email" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-blue-500">
                        </div>
                    </div>
                    
                    <div>
                        <label for="subject" class="block text-gray-700 font-medium mb-2">Assunto</label>
                        <input type="text" id="subject" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-blue-500">
                    </div>
                    
                    <div>
                        <label for="message" class="block text-gray-700 font-medium mb-2">Mensagem</label>
                        <textarea id="message" rows="4" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-blue-500"></textarea>
                    </div>
                    
                    <button type="submit" class="cta-button w-full bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-4 rounded-lg">
                        <i class="fas fa-paper-plane mr-2"></i>ENVIAR MENSAGEM
                    </button>
                </form>
            </div>
        </div>
    </section>

    <!-- FAQ Section -->
    <section class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">Perguntas frequentes</h2>
                <p class="text-xl text-gray-600 max-w-2xl mx-auto">Tire suas dúvidas sobre nossos produtos e processos</p>
            </div>
            
            <div class="max-w-3xl mx-auto space-y-6">
                <div class="bg-white p-6 rounded-xl shadow-sm">
                    <h3 class="text-xl font-bold text-gray-800 mb-2">Como recebo acesso ao produto após a compra?</h3>
                    <p class="text-gray-600">Imediatamente após a confirmação do pagamento, você receberá um e-mail com instruções para acessar sua área de membros e baixar o material. O acesso é vitalício.</p>
                </div>
                
                <div class="bg-white p-6 rounded-xl shadow-sm">
                    <h3 class="text-xl font-bold text-gray-800 mb-2">Quais são as formas de pagamento aceitas?</h3>
                    <p class="text-gray-600">Aceitamos cartões de crédito (todas as bandeiras), Pix e boleto bancário. Você também pode parcelar em até 12x no cartão.</p>
                </div>
                
                <div class="bg-white p-6 rounded-xl shadow-sm">
                    <h3 class="text-xl font-bold text-gray-800 mb-2">Como funciona a garantia de 7 dias?</h3>
                    <p class="text-gray-600">Se dentro de 7 dias após a compra você não estiver satisfeito(a) com o produto, basta nos enviar um e-mail que devolvemos 100% do seu dinheiro, sem perguntas.</p>
                </div>
                
                <div class="bg-white p-6 rounded-xl shadow-sm">
                    <h3 class="text-xl font-bold text-gray-800 mb-2">Os produtos têm certificado?</h3>
                    <p class="text-gray-600">Sim, nossos cursos emitem certificado digital de conclusão que pode ser utilizado para horas complementares e enriquecimento curricular.</p>
                </div>
                
                <div class="bg-white p-6 rounded-xl shadow-sm">
                    <h3 class="text-xl font-bold text-gray-800 mb-2">Como posso entrar no grupo de suporte?</h3>
                    <p class="text-gray-600">Após a compra, você receberá um convite para nosso grupo exclusivo no WhatsApp ou Telegram, conforme sua preferência.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-12">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row justify-between">
                <div class="mb-8 md:mb-0">
                    <div class="flex items-center mb-4">
                        <i class="fas fa-store text-2xl text-blue-400 mr-2"></i>
                        <span class="text-xl font-bold">Minha Loja Digital</span>
                    </div>
                    <p class="text-gray-400 max-w-xs">Produtos digitais de alta qualidade para transformar sua vida.</p>
                </div>
                
                <div class="grid grid-cols-2 md:grid-cols-3 gap-8">
                    <div>
                        <h3 class="font-bold text-lg mb-4">Links</h3>
                        <ul class="space-y-2">
                            <li><a href="#" class="text-gray-400 hover:text-white">Termos de Uso</a></li>
                            <li><a href="#" class="text-gray-400 hover:text-white">Política de Privacidade</a></li>
                            <li><a href="#" class="text-gray-400 hover:text-white">Garantia</a></li>
                            <li><a href="#" class="text-gray-400 hover:text-white">Blog</a></li>
                        </ul>
                    </div>
                    
                    <div>
                        <h3 class="font-bold text-lg mb-4">Ajuda</h3>
                        <ul class="space-y-2">
                            <li><a href="#" class="text-gray-400 hover:text-white">Central de Ajuda</a></li>
                            <li><a href="#" class="text-gray-400 hover:text-white">Perguntas Frequentes</a></li>
                            <li><a href="#" class="text-gray-400 hover:text-white">Suporte</a></li>
                            <li><a href="#" class="text-gray-400 hover:text-white">Status do Pedido</a></li>
                        </ul>
                    </div>
                    
                    <div>
                        <h3 class="font-bold text-lg mb-4">Social</h3>
                        <div class="flex space-x-4">
                            <a href="#" class="w-10 h-10 bg-gray-700 rounded-full flex items-center justify-center hover:bg-blue-600">
                                <i class="fab fa-facebook-f"></i>
                            </a>
                            <a href="#" class="w-10 h-10 bg-gray-700 rounded-full flex items-center justify-center hover:bg-pink-600">
                                <i class="fab fa-instagram"></i>
                            </a>
                            <a href="#" class="w-10 h-10 bg-gray-700 rounded-full flex items-center justify-center hover:bg-blue-400">
                                <i class="fab fa-twitter"></i>
                            </a>
                            <a href="#" class="w-10 h-10 bg-gray-700 rounded-full flex items-center justify-center hover:bg-red-600">
                                <i class="fab fa-youtube"></i>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="border-t border-gray-700 mt-8 pt-8 text-center text-gray-400">
                <p>© 2023 Minha Loja Digital. Todos os direitos reservados.</p>
                <p class="mt-2 text-sm">Este site é comercializado com apoio da Kiwify. A Kiwify não é responsável por este produto.</p>
            </div>
        </div>
    </footer>

    <!-- Floating Buttons -->
    <a href="#" class="fixed bottom-6 right-6 w-16 h-16 bg-green-500 rounded-full flex items-center justify-center text-white text-2xl shadow-xl hover:bg-green-600 transition floating-cart">
        <i class="fab fa-whatsapp"></i>
    </a>

    <script>
        // Simple animations
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Product counter animation
        function animateCounters() {
            const counters = document.querySelectorAll('.counter');
            const speed = 200;
            
            counters.forEach(counter => {
                const target = +counter.getAttribute('data-target');
                const count = +counter.innerText;
                const increment = target / speed;
                
                if(count < target) {
                    counter.innerText = Math.ceil(count + increment);
                    setTimeout(animateCounters, 1);
                } else {
                    counter.innerText = target.toLocaleString();
                }
            });
        }

        // Run counter animation when counters are in view
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if(entry.isIntersecting) {
                    animateCounters();
                    observer.unobserve(entry.target);
                }
            });
        }, { threshold: 0.5 });

        document.querySelectorAll('.counter-section').forEach(section => {
            observer.observe(section);
        });
    </script>
</body>
</html>
