# github
Trabalho unifebe

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulários</title>
</head>
<body>
    <!-- <div class="mais-vendidos">
        <h1>Os mais vendidos</h1>
        <div class="produtos">
            <div class="produto">
                <img src="" alt="">
                <h1>Ovo de páscoa barbie</h1>
                <h2>R$ 53,59</h2>
            </div>
            <div class="produto">
                <img src="" alt="">
                <h1>Caixa de bombom nestlé</h1>
                <h2>R$ 11,99</h2>
            </div>
            <div class="produto">
                <img src="" alt="">
                <h1>Caixa Bis</h1>
                <h2>R$ 6,99</h2>
            </div>
            <div class="produto">
                <img src="" alt="">
                <h1>Caixa de bombom garoto</h1>
                <h2>R$ 10,99</h2>
            </div>
        </div>
    </div> -->
    <div class="contato">
        <h1>Meu primeiro formulário</h1>
        <form action="" method="POST">
            <div class="informacoes-usuario">
                <label for="nome">Nome</label>
                <input id="nome" name="nome" type="text" value="Sr.">
                <br>
                <label for="email">E-mail</label>
                <input type="email" name="email" id="email" required placeholder="Digite seu email com @">
                <br>
                <label for="senha">Senha</label>
                <input type="password" name="senha" id="senha" required>
                <br>
                <!-- cpf com pattern -->
                <label for="cpf">CPF</label>
                <input type="text" pattern="\d{3}\.\d{3}\.\d{3}-\d{2}">
            </div>
            <div class="radio-button">
                <h3>Você vai estudar hoje?</h3>
                <input type="radio" name="estudar" 
                    id="sim">
                <label for="sim">Sim</label>

                <input type="radio" name="estudar" 
                    id="nao">
                <label for="nao">Não</label>
            </div>
            <br>
            <div class="checkbox">
                <h3>Lista de Compras</h3>
                <input type="checkbox" value="café">
                <label for="">Café</label>
                <br>
                <input type="checkbox" value="requeijão">
                <label for="">Requeijão</label>
                <br>
                <input type="checkbox" value="queijo">
                <label for="">Queijo</label>
                <br>
                <input type="checkbox" value="pão">
                <label for="">Pão</label>
            </div>
            <div class="lista-suspensa">
                <h3>Lista de Estados</h3>
                <select name="estados" id="estados">
                    <optgroup label="Sul">
                        <option value="SC">Santa Catarina</option>
                        <option value="RS">Rio Grande do Sul</option>
                        <option value="PR">Paraná</option>
                    </optgroup>
                    <optgroup label="Sudeste">
                        <option value="RJ">Rio de Janeiro</option>
                        <option value="SP" selected>São Paulo</option>
                    </optgroup>
                </select>
            </div>
            <div class="textarea">
                <h3>Escreva seu feedback:</h3>
                <textarea name="comentario" 
                    id="comentario" 
                    cols="30" 
                    rows="10"></textarea>
            </div>
            <input type="submit">
        </form>
    </div>
</body>
</html>
