
<!DOCTYPE html>
<html>
<h1>Formulário</h1>
  <form action="/action_page.php">
    <fieldset>
      <legend>Dados Pessoais:</legend>
  
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title> Lista de Exercicio 1 </title>
</head>

<body>
  
  <form action="/action_page.php" method="post">
    <label><br>Nome</br></label>
    <input type="text" value="" required/>
    <label><br>Data de Nascimento</br></label>
    <input type="date" value="">
    <label><br>Endereço</br></label>
    <input type="text" value="" required/>
    <label><br>Bairro</br></label>
    <input type="text" value="" required/> 
    <label><br>Cidade</br></label>
    <input type="text" value="" required/>
    <label><br>CEP</br></label>
    <input type="number" value="" required/>
     <label for="estado">Estado:</label>
  <select id="" name="estado">
    <option value="ceará" selected> Ceará </option>
    <option value="Piauí">Piauí</option>
    <option value="Bahia">Bahia</option>
    <option value="Acre">Acre</option>
    </select>
    
      </fieldset>
     <fieldset>
      <legend>Dados Profissionais:</legend>
  <br>
    <h13> Natureza do Cargo</hr13>
      <br>
  <label for="Gerência">Gerência</label>
  <input type="radio" id="ger" name="nat_cargo" value="Gerência">
  <label for="Financeiro">Financeiro</label>
  <input type="radio" id="fin" name="nat_cargo" value="Financeiro">
  <label for="Recepção">Recepção</label>
  <input type="radio" id="Rec" name="nat_cargo" value="Recepção">
  <label for="Administrativo">Administrativo</label>
  <input type="radio" id="Adm" name="nat_cargo" value="Administrativo">
 <label for="Juridico">Juridico</label>
 <input type="radio" id="jur" name="nat_cargo" value="Juridico">
    <p> 
      
      <h8> Area de Interesse</h8>
    </p>
    <input type="checkbox" id="com" name="area_interesse" value="Computação">
  <label for="area_interesse">Computação</label>
  <input type="checkbox" id="Quim" name="area_interesse" value="Quimica">
  <label for="area_interesse">Quimica</label>
  <input type="checkbox" id="mei" name="area_interesse" value="Meio Ambiente">
  <label for="area_interesse">Meio Ambiente</label>
  <input type="checkbox" id="en" name="area_interesse" value="Engenharia">
  <label for="area_interesse">Engenharia</label>
  <input type="checkbox" id="mat" name="area_interesse" value="Matemática">
  <label for="area_interesse">Matemática</label>

    <h5>Mini-Currículo:</h5>
       <textarea name="message" rows="10" cols="30">
</textarea> 
    </fieldset>
    <input type="submit" value="Enviar">
</form> 
      
    </body>
  </html>
  
  <!-- --> Quesdtão 2 da Primeira lista de exercícios
  
  <!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>tabela lista de exercício</title>
</head>

<body>
 <table border="1px" style="width: 100%">
      <CAPTION> Tabela com informações sobre o Usuário </CAPTION>
      <tr>
        <th> Contatos </th>
        <th> Formação </th>
        <th> Dados </th>
        
                           
      </tr>
      <tr>
        <th>85986592430</th>
        <th>Ensino Médio Completo </th>
        <th>RG-273754876-7</th>
        
      </tr>
      <tr>
        <th>85985771406</th>
        <th>Técnico em Informática</th>
        <th>CPF- 234.567.890-1</th
       
      </tr>
      <tr>
        <th>85985771406</th>
        <th>Superior em PED </th>
        <th>NIS 345321344</th>
       
      </tr>

    
    </table>
  
</body>

</html>
    
