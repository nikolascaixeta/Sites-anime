# Sites-anime
Trabalho da GHS, desenvolvimento de um site de noticias sobre os animes mais populares no Brasil

Nikolas: Responsavel pela progamação geral

Pedro Almeida: Responsavel pela progamação das paginas extras

Lucas Oliveira: Responsavel pela criação da logo e da progamação do site principal

Gabriel Henrique: Responsavel pela parte criativa e wireframe

Básico do site: Nosso site vai conter uma menu que vai dar uma pagina geral sobre os animes mais famosos do brasil com um grafico, imagens e uma brave descrição, junto de 5 paginas mais especificas sobre animes,mangas,filmes de anime,musicas de anime e sobre tokusatso, alem de um rodapé que da acesso a uma pagina sobre a nossa equipe
https://www.jbox.com.br/

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="estilo.css">
    <title>Formulários</title>
</head>
<body>
    <h1>Indrodução a formulários</h1>
    <div class="conteudo-formulario">
        
      <form >
       
        <label for="pnome">Nome: </label>
        <input type="text" name="Nome" id="pnome"  > 

        <label for="sobrenome">Sobrenome: </label>
        <input type="text" name="Sobrenome" id="sobrenome">

        <h3>Selecione seu curso</h3>
        <input type="radio" name="curso" id="tinf">
        <label for="tinf">Técnico em informática</label> <br>
        <input type="radio" name="curso" id="tcon">
        <label for="tcon">Técnico em contabilidade</label> <br>
        <input type="radio" name="curso" id="tele">
        <label for="tele">Técnico em eletrônica</label> <br>
        <input type="radio" name="curso" id="tadm">
        <label for="tele">Técnico em administração</label> <br>

        <h3>Dados da Plataforma: </h3>
        <label for="endEmail">Email: </label>
        <input type="email" name="email" id="endEmail">
        <label for="senha">Defina uma senha: </label>
        <input type="password" id="senha">
        <div class="conteudo-disciplina">
          <h3>Escolha as diciplinas favoritas</h3>
          <input type="checkbox" id="port">
          <label for="port">Português</label>

        </div>

      </form>

    </div>
    
</body>
</html>
