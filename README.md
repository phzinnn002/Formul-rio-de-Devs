<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pesquisa de Mercado</title>
    <link rel="stylesheet" href="/Programação/Projetos/Formulário/Style.css">
</head>
<body>
    <div>
        <h1 id="titulo">Cadastro de Desenvolvedores</h1>
        <p id="subtitulo">Adicione Suas Informações</p>
        <br>
    </div>
    
    <!--Inicio do Formulário-->

    <form>

            <fieldset class="Grupo">
                    <div class="campo">

                        <label for="nome"><strong>Nome</strong></label>
                        <input type="text" name="nome" id="nome" required>

                    </div>
                    <div class="campo">
                            <label for="sobrenome" id="sobrenome" required></label>
                            <input type="text" name="sobrenome" id="sobrenome" required>

                    </div>

            </fieldset>
            <div class="campo">

                <label for="email"><strong>Email</strong></label>
                <input type="email" name="email" id="email" required>


            </div>

            <div class="campo">
                <label for="senioridade"><strong>Senioridade</strong></label>
                <select id="senioridade" required>
                        <option selected disabled value="">Selecione</option>
                        <option>Júnior</option>
                        <option>Pleno</option>
                        <option>Sênior</option>
                </select>
                <div>

                    <fieldset class="grupo">

                        <div id="check">

                                <label><strong>Selecione as ferramentas que ultiliza:</strong></label><br><br>
                                <input type="checkbox" id="tecnologia1" name="tecnologia1" value="HTML">
                                <label for="tecnologia1"> HTML</label>
                                <input type="checkbox" id="tecnologia2" name="tecnologia2" value="CSS">
                                <label for="tecnologia2"> CSS</label>
                                <input type="checkbox" id="tecnologia3" name="tecnologia3" value="JavaScript">
                                <label for="tecnologia3"> JavaScript</label>
                                <input type="checkbox" id="tecnologia4" name="tecnologia4" value="PHP">
                                <label for="tecnologia4"> PHP</label>
                                <input type="checkbox" id="tecnologia5" name="tecnologia5" value="C#">
                                <label for="tecnologia5"> C#</label>
                                <input type="checkbox" id="tecnologia6" name="tecnologia6" value="Python">
                                <label for="tecnologia6"> Python</label>
                                <input type="checkbox" id="tecnologia7" name="tecnologia7" value="Java">
                                <label for="tecnologia7"> Java</label>
                        </div>
                    </fieldset>

                        <div class="campo">
                            <br>
                            <label for="experiencia"><strong>Conte um pouco mais da sua experiência: </strong> </label>
                            <textarea name="experiencia" id="experiencia" style="width:26em" rows="6"></textarea>

                        </div>

                        <button class="botao" type="submit" onsubmit="" >Concluído</button>

                </div>
            </div>
    </form>
</body>
</html>
