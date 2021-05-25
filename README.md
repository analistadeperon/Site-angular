# Site-angular

<html ng-app="app">
    <head>
        <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
        <meta http-equiv="content-language" content="pt-br" />
        <title>AngularJS - Single Page Application</title>
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
        <script src="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/js/bootstrap.min.js"></script>
        <script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.5.0/angular.min.js"></script>
        <script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.5.0/angular-route.min.js"></script>
        <script src="app/app.js"></script>
        <script src="app/controllers/controller.js"></script>
        <script src="app/routes/route.js"></script>
   </head>
    <body>
      <img class="img-responsive" src="https://img2.gratispng.com/20180205/asq/kisspng-information-technology-wallpaper-technology-png-file-5a790adacf0c29.2872624015178820748481.jpg">
        <nav class="navbar navbar-default">
            <div class="container">
                <div class="navbar-header">
                    <a class="navbar-brand" href="/">ANALISTA MPD </a>
                </div>
                                <ul class="nav navbar-nav navbar-right">
                    <li><a href="#/home"><span class="glyphicon glyphicon-home"></span> Home</a></li>
                     <ul>
              <li><a href="#">Inicial Trabalho TI</a></li>
              <li><a href="#">Quem sou</a></li>
              <li><a href="#">Analista Programação e Desenvolvimento</a></li>
              
            </ul>
                    <li><a href="#/about"><span class="glyphicon glyphicon-book"></span> About</a></li>
                     <ul>
              <li><a href="#">Projetos em Angular.Html,Css,Javascript,</a></li>
              <li><a href="#">Trabalhos</a></li>
              <li><a href="#">Biblioteca Apoio</a></li>
              <li><a href="#">Site de pesquisa TI</a></li>
            </ul>
                    <li><a href="#/contact"><span class="glyphicon glyphicon-comment"></span> Contact</a></li>
                     <ul>
              <li><a href="#">Telefone: https://wa.me/55XXxxxx-xxxx</a></li>
              <li><a href="#">Linkedin</a></li>
              <li><a href="#">Github</a></li>
               <li><a href="#">E-mail</a></li>
               <li><a href="#">https://github.com/analistadeperon</a></li>
               <ul>
              
                          </ul>
            </ul>
                </ul>
            </div>
        </nav> 
        <div ng-view class="jumbotron text-center"></div>
        <footer class="text-center">
            <p>Contato via email /  
                <a href="https://github.com/analistadeperon" target="_blank"> 
                    https://analistadeperon@hotmail.com  <div class="input_div">
                                    <input class="input_form" type="text" name="login" placeholder="Digite seu Login"
                                    value="" required>
                                </div>
                </a>
                <button type='submit' id='validate'>Acesse!</button>
            </p>
        </footer>
   </body>
</html>
<p>Estou criando um link para
<a href="https://analistadeperon@hotmail.com"
   title="O melhor lugar para encontrar mais informações sobre meus projetos e como contribuir"> https://github.com/analistadeperon</a>.
</p>



<input type="file" name="file" accept="image/*" required="required" />
