Trabalho prático 1
<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Meu Perfil</title>
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
<link rel="stylesheet" href="style.css">
</head>
<body>
<!--Menu-->
<nav class="navbar navbar-expand-lg navbar-dark">
    <div class="container">
        <a class="navbar-brand" href="#">Natália Silva Oliveira</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="#secao1">Seção 1</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#secao2">Seção 2</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#secao3">Seção 3</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#secao4">Seção 4</a>
                </li>
            </ul>
        </div>
    </div>
</nav>
<!--Seção 1-->
<div class="container">
    <section id="secao1" class="section">
        <div class="row">
            <div class="col-md-4">
                <img src="pessoa1.avif" class="img-fluid" alt="Avatar">
            </div>
            <div class="col-md-8">
                <h2>Natália Silva Oliveira</h2>
                <p>Sou estudante de Sistemas de Informação na Puc Minas, tenho 18 anos e 
                    minhas principais qualidades são: honestidade, proatividade e inteligência.</p>
                <a href="mailto:email@example.com" class="btn btn-primary">Contato</a>
                <a href="https://www.linkedin.com/feed/?trk=404_page" class="btn btn-secondary">LinkedIn</a>
            </div>
        </div>
    </section>
<!--Seção 2-->
    <section id="secao2" class="section">
        <h2>Repositórios</h2>
        <div class="row">
            <div class="col-md-4">
                <div class="card repo-card">
                    <div class="card-body">
                        <h5 class="card-title">Repositório 1</h5>
                        <p class="card-text">Repositório do trabalho de Desenvolvimento de Interfaces Web.</p>
                        <a href="repo.html" class="btn btn-primary">Detalhes</a>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card repo-card">
                    <div class="card-body">
                        <h5 class="card-title">Repositório 2</h5>
                        <p class="card-text">Repositório do trabalho de Desenvolvimento de Interfaces Web.</p>
                        <a href="repo.html" class="btn btn-primary">Detalhes</a>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card repo-card">
                    <div class="card-body">
                        <h5 class="card-title">Repositório 3</h5>
                        <p class="card-text">Repositório do trabalho de Desenvolvimento de Interfaces Web</p>
                        <a href="repo.html" class="btn btn-primary">Detalhes</a>
                    </div>
                </div>
            </div>
        </div>
    </section>
<!--Seção 3-->
    <section id="secao3" class="section">
        <h2>Conteúdos Sugeridos</h2>
        <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="Github-Top-10-linguagens-de-programacao.jpg" class="d-block w-100" alt="Imagem 1">
                </div>
                <div class="carousel-item">
                    <img src="ESTRATÉGIAS PARA MELHORAR A PRODUTIVIDADE NO TRABALHO-20-03-2023 - 8acPv.png" class="d-block w-100" alt="Imagem 2">
                </div>
                <div class="carousel-item">
                    <img src="redessociaiseusuariosbrasil-0-cke.webp" class="d-block w-100" alt="Imagem 3">
                </div>
                <div class="carousel-item">
                    <img src="beneficios-da-meditacao-para-a-saude-mental.jpg" class="d-block w-100" alt="Imagem 3">
                </div>
                <div class="carousel-item">
                    <img src="infografico-como-criar-um-curriculo-chamativo.png" class="d-block w-100" alt="Imagem 3">
                </div>
php
Copiar código
        </div>
        <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Anterior</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Próximo</span>
        </a>
    </div>
</section>
<!--Seção 4-->
php
Copiar código
<section id="secao4" class="section">
    <h2>Colegas de Trabalho</h2>
    <div class="row">
        <div class="col-md-4">
            <div class="card collegue-card">
                <img src="pessoa2.jpg" class="card-img-top" alt="Colega 1">
                <div class="card-body">
                    <h5 class="card-title">Mateus</h5>
                    <p class="card-text">Adora programar.</p>
                </div>
            </div>
        </div>
        <div class="col-md-4">
            <div class="card collegue-card">
                <img src="pessoa 4.jpg" class="card-img-top" alt="Colega 2">
                <div class="card-body">
                    <h5 class="card-title">Ana</h5>
                    <p class="card-text">Gosta de Desenvolver Software.</p>
                </div>
            </div>
        </div>
        <div class="col-md-4">
            <div class="card collegue-card">
                <img src="pessoa3.jpg" class="card-img-top" alt="Colega 3">
                <div class="card-body">
                    <h5 class="card-title">Pedro</h5>
                    <p class="card-text">Cria sites muito criativos.</p>
                </div>
            </div>
        </div>
    </div>
</section>
</div>
<!--Seção 5-->
<footer class="footer">
    <div class="container">
        <p>Responsável pelo Site - Natália Silva Oliveira</p>
    </div>
</footer>
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.1/dist/umd/popper.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Detalhes do Repositório</title>
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
</head>
<style>
            /* Estilos do repositório */
        body {
            background-color: #f8f9fa;
        }
css
Copiar código
    .container {
        max-width: 800px;
        margin: 50px auto;
    }

    .repo-info {
        margin-bottom: 20px;
    }

    .avatar {
        max-width: 100px;
        border-radius: 50%;
    }
</style>
<body>
<div class="container">
    <div class="repo-info">
        <a href="index.html" class="btn btn-primary">Voltar para o Site Principal</a>
        <h1>Repositório GitHUb</h1>
        <p>Repositório do trabalho de Desenvolvimento de Interfaces Web.</p>
        <div>
            <img src="pessoa1.avif" alt="Avatar" class="avatar">
        </div>
        <p>Proprietário: Natália Silva Oliveira</p>
        <p>Data de Criação: 16 de Abril de 2024</p>
        <p>Linguagem Principal: HTML e CSS</p>
        <p>Tags: Tag1, Tag2, Tag3</p>
        <p>Quantidade de Estrelas: 100</p>
        <p>Observadores: 50</p>
        <p>Forks: 20</p>
        <p>Licença: MIT</p>
        <a href="https://github.com/NataliaSilvaOliveira/Trabalho-DIW.git" class="btn btn-primary">Acessar Repositório</a>
    </div>
</div>
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.1/dist/umd/popper.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
css
Copiar código
/* Estilo do site */
body {
    background-color: #f8f9fa;
}

.navbar {
    background-color: #343a40;
    color: #fff;
}

.section {
    padding: 40px 0;
}

.repo-card, .collegue-card {
    margin-bottom: 20px;
}

.footer {
    background-color: #343a40;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}
