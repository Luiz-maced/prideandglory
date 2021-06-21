# prideandglory
<!DOCTYPE html>
<html lang="en">

<head>
  <link rel="stylesheet" href="style.css">
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=Edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Formulário projeto</title>
  <!--sera inserido o css a medida que o código for escrito-->
</head>

<body>
  <h1 class="título">Formulário de teste</h1>
  <!-- Project -->
  <form>
    <fieldset>
      <div class="bloco">
        <label>Nome</label>
        <input type="text" name="nome" id="nome"required>
      </div>
      
      <div class="bloco" >
        <label>sobrenome</label>
        <input type="text" name="sobrenome" id="sobrenome"required>
      </div>
      <div class="button">
        <button class="submit">enviar</button>
      </div>

    </fieldset>
    <label>Email</label>
    <input type="email" name="email" id="email"> <br>
    <button class="submit">enviar</button>
    
    <fieldset>
       <div>
          <label>Qual seu nível de desenvolvedor?</label>
          <input type="radio" name="Senior" id="senior"> Senior
          <input type="radio" name="pleno" id="pleno"> pleno
       </div>
       
       
       
       
    </fieldset>
    
  
  </form>
</body>

</html>
