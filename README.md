<!doctype html>
<html lang="pt-br">

<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="node_modules/bootstrap/compiler/bootstrap.css">
    <link rel="stylesheet" href="node_modules/bootstrap/compiler/style.css">

    <title>Filmes</title>
</head>

<body>

    <nav class="navbar navbar-fixad-top navbar-expand-lg navbar-dark bg-primary">

        <div class="container">
            <a class="navbar-brand h1 mb-0" href="#">FILMES</a>

            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSite">
                <span class="navbar-toggler-icon"></span>
            </button>

            <div class="collapse navbar-collapse" id="navbarSite">
                <Ul class="navbar-nav mr-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#">Início</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Séries</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Lançamentos</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Contatos</a>
                    </li>
                </Ul>

                <ul class="navbar-nav ml-auto">

                    <li class="nav-item dropdown">

                        <a class="nav link dropdown-toggler mr-2" href="#" data-toggle="dropdown" id="navDrop">
                            Social
                        </a>
                        <div class="dropdown-menu">
                            <a class="dropdown-item" href="#">Facebook</a>
                            <a class="dropdown-item" href="#">Instagram</a>
                            <a class="dropdown-item" href="#">Teste</a>
                        </div>
                    </li>
                </ul>

                <form class="form-inline">
                    <input class="form-control mr-2" type="search" placeholder="Buscar...">
                    <button class="btn btn-dark" type="submit">Ok</button>
                </form>










            </div>
        </div>
    </nav>



    <div class="row">
        <div class="row-4">
            <div class="list-group" id="list-tab" role="tablist">
                <a class="list-group-item list-group-item-action active" id="list-home-list" data-toggle="list"
                    href="#list-home" role="tab" aria-controls="home">The Walking Dead</a>
                <a class="list-group-item list-group-item-action" id="list-profile-list" data-toggle="list"
                    href="#list-profile" role="tab" aria-controls="profile">Filmes</a>
                <a class="list-group-item list-group-item-action" id="list-messages-list" data-toggle="list"
                    href="#list-messages" role="tab" aria-controls="messages">Inativo</a>
                <a class="list-group-item list-group-item-action" id="list-settings-list" data-toggle="list"
                    href="#list-settings" role="tab" aria-controls="settings">Inativo</a>
            </div>
        </div>
        <div class="col-8">
            <div class="tab-content" id="nav-tabContent">
                <div class="tab-pane fade show active" id="list-home" role="tabpanel" aria-labelledby="list-home-list">

                    <ul class="list-group">
                        <a class="list-group-item" href="#">10 TEMPORADA EP1</a>
                        <a class="list-group-item" href="#">10 TEMPORADA EP2</a>
                        <a class="list-group-item" href="#">10 TEMPORADA EP3</a>
                        <a class="list-group-item" href="#">10 TEMPORADA EP4</a>
                        <a class="list-group-item" href="#">10 TEMPORADA EP5</a>
                        <a class="list-group-item" href="#">10 TEMPORADA EP6</a>
                    </ul>


                </div>
                <div class="tab-pane fade" id="list-profile" role="tabpanel" aria-labelledby="list-profile-list">...
                </div>
                <div class="tab-pane fade" id="list-messages" role="tabpanel" aria-labelledby="list-messages-list">...
                </div>
                <div class="tab-pane fade" id="list-settings" role="tabpanel" aria-labelledby="list-settings-list">...
                </div>
            </div>
        </div>
    </div>














    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="node_modules/jquery/dist/jquery.js"></script>
    <script src="node_modules/popper.js/dist/umd/popper.js"></script>
    <script src="node_modules/bootstrap/dist/js/bootstrap.js"></script>
</body>

</html>