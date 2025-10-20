<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sobre - Plataforma de Empregos</title>
  <link rel="stylesheet" href="sobre.css">
</head>
<body>


  <nav class="navbar">
    <div class="container">
      <a class="navbar-brand" href="#">Plataforma de Empregos</a>
      <div class="navbar-links">
        <a href="index.html">Home</a>
        <a href="vagas.html">Vagas</a>
        <a href="sobre.html">Sobre</a>
        <a href="contato.html">Contato</a>
      </div>
    </div>
  </nav>

  <header class="header">
    <h1>Sobre Nós</h1>
    <p>Nosso objetivo é Transformar a incerteza do primeiro passo profissional em uma trajetória de sucesso e inovação.</p>
  </header>


  <section class="content-section">
    <div class="cards-container">
      <div class="card">
        <h3>Quem Somos</h3>
        <p>Nós somos a ponte que liga o talento em formação das universidades às empresas de tecnologia mais inovadoras.

Na Plataforma de Empregos, acreditamos que o futuro digital é construído por jovens desenvolvedores, analistas e engenheiros de software. Nosso propósito é simples: acelerar a carreira de estudantes de TI, oferecendo acesso transparente e facilitado às melhores vagas de estágio no mercado.

O que nos move?

    Conexão Real: Vamos além dos currículos. Usamos tecnologia para fazer match entre as habilidades que você está desenvolvendo e as necessidades reais das empresas.

    Foco no Futuro: Entendemos que o primeiro estágio é o passo mais crucial. Por isso, filtramos oportunidades que oferecem desafios relevantes, aprendizado prático e chances reais de efetivação.

    Comunidade e Suporte: Não oferecemos apenas vagas; oferecemos direção. Nossa plataforma também conta com recursos de preparação, dicas de entrevista e webinars para garantir que você se destaque em todas as etapas.

Se você é um estudante de TI buscando transformar teoria em prática e construir uma carreira sólida, você está no lugar certo. Estamos aqui para garantir que sua jornada comece com o melhor estágio possível.</p>
      </div>
      <div class="card">
        <h3>Nossa Missão</h3>
        <p>Nossa missão principal é democratizar o acesso a oportunidades de estágio de excelência para a próxima geração de talentos em Tecnologia da Informação.

Nós existimos para:

    Eliminar Barreiras: Facilitar a jornada de entrada no mercado de trabalho, removendo a frustração de encontrar vagas de estágio que realmente ofereçam aprendizado significativo e aplicação prática dos conhecimentos de TI.

    Impulsionar o Sucesso: Garantir que cada estudante de TI inicie sua carreira em uma empresa que invista em seu desenvolvimento, oferecendo mentoria, projetos desafiadores e uma cultura de crescimento contínuo.

    Conectar com Propósito: Ser o catalisador que liga as empresas mais inovadoras, que buscam talentos frescos e perspectivas novas, aos estudantes mais dedicados e prontos para transformar o futuro digital.

Em essência, nossa missão é transformar a incerteza do início de carreira em uma trajetória clara e promissora para todos os futuros profissionais de tecnologia.
        </p>

      </div>
    </section>

    <section id="contato" class="content-section">
        <div class="row">
             <header class="header">
    <h1>Deseja fazer parte de nossa comunidade?</h1>
    <p>Para fazer parte de nossa comunidade, deixe seu nome e número de contato abaixo.</p>
  </header>
            <form action="#" method="POST" class="contact-form">
                <label for="nome">Nome:</label>
                <input type="text" id="nome" name="nome" required>

              <div class="form-field" style="flex-basis: 100px; flex-grow: 0;">
                        <label for="telefone">Telefone:</label>
                        <input type="text" id="telefone">
                    </div>

                <button type="submit">Enviar</button>
            </form>
        </div>
    </section>

  
  <footer class="footer">
    <p>© 2025 Plataforma de Empregos - Todos os direitos reservados</p>
  </footer>

</body>
</html>

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  background-color: #fffefe;


  display: flex;
  flex-direction: column;
  min-height: 100vh;
}


.navbar {
  background-color: #f11b1b;
  box-shadow: 0 4px 6px rgb(8, 8, 8);
  padding: 15px 0;
}

.container {
  width: 90%;
  max-width: 1200px;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.navbar a {
  color: #f8f5f5;
  text-decoration: none;
  font-size: 16px;
  margin-left: 20px;
}

.navbar .navbar-links a:hover {
  color: #007bff;
}

/* Header */
.header {
  text-align: center;
  margin: 50px 0;
}

.header h1 {
  font-size: 36px;
  color: #333;
}

.header p {
  font-size: 18px;
  color: #666;
}


.content-section {
  width: 90%;
  max-width: 1000px;
  margin: 0 auto 40px auto;
  flex: 1; 
}

.cards-container {
  display: flex;
  gap: 30px;
  margin-bottom: 30px;
  flex-wrap: wrap;
}

.card {
  flex: 1;
  background-color: #fff;
  padding: 30px; 
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.15);
  transition: transform 0.3s ease;
  min-height: 220px; 
}

.card h3 {
  font-size: 22px; 
  margin-bottom: 10px;
  color: #333;
}

.card p {
  font-size: 16px; 
  color: #555;
  line-height: 1.5;
}

.card:hover {
  transform: translateY(-8px);
}



.footer {
  background-color: #ff1e00;
  color: white;
  text-align: center;
  padding: 20px 0;
  margin-top: auto; 
}
.contact-form {
    max-width: 600px;
    margin: 0 auto;
    padding: 20px;
    border: 1px solid #ccc;
    border-radius: 5px;
    background: #f9f9f9;
}

.contact-form label {
    display: block;
    margin-bottom: 8px;
    font-weight: bold;
}

.contact-form input[type="text"],
.contact-form input[type="email"],
.contact-form textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 20px;
    border: 1px solid #ccc;
    border-radius: 4px;
}

.contact-form textarea {
    resize: vertical; 
}

.contact-form button[type="submit"] {
    display: block;
    width: 100%;
    padding: 10px;
    background: #5cb85c;
    color: #fff;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    font-size: 1.1rem;
    transition: background 0.3s;
}

.contact-form button[type="submit"]:hover {
    background: #4cae4c;
}
