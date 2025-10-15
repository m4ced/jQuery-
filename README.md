<!DOCTYPE html>
<html>
<head>
  <title>Exemplo de jQuery</title>
  <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
</head>
<body>
  <h2 id="titulo">Clique no botão!</h2>
  <button id="botao">Clique aqui</button>

  <script>
    $(document).ready(function(){
      $("#botao").click(function(){
        $("#titulo").text("Você clicou no botão!");
      });
    });
  </script>
</body>
</html>
