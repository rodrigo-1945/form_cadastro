# Fomulário simples


__Olá! Aqui tem tudo o que eu utilizei nesse formulário de cadastro.__

```HTML
<body>
    <!--Vamos criar um tag (form) com o atributo e seu valor fomulário-->

    <form class="card_cadastro">

            <!--Usamos a tag heading(h2) subtitulo do cabeçalhos-->
            <h2>Cadastro</h2>
            <div class="bar"></div>

            <!--A lebel serve para fazer cadastro de usuários-->
            <label for="Username">Nome:</label>
            <input type="Username" placeholder="Username" id="nome" required>
            <!--Inpunt server para receber dados do usuário-->
            <label for="E-mail">E-mail:</label>
            <input type="email" placeholder="User.Email" required>
            
            <label for="password">Senha:</label>
            <input type="password" placeholder="password" required>

            <!--Observação no input temos atributos type e planceholder-->
            <!--O type é usado para especificar o tipo de conteúdo que essa tag link está importando-->
            <!--Placeholder" é utilizado para indicar ao navegador o texto que deverá aparecer escrito no campo do formulário-->


        <!--Elemento (buntton) server para o usuário clicar nele-->
        <button type="button">Cadastro</button>

    </form>

</body>
```
__Aqui temos o códgio CSS__



```css
*{
    margin: 0;
    margin-top: 0;
    box-shadow: 0;
}

body{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background: #FF6354;
    font-family: monospace sans-serif;
    color: #111;
}
.card_cadastro {
	display: flex;
	flex-direction: column;
	background-color: #FFF;
	width: 80vw;
	max-width: 450px;
	padding: 30px;
	border-radius: 20px;
    margin-right: 12px;
}

.card_cadastro h2 {
	margin-bottom: 2px;
}

.card_cadastro .bar {
	width: 40px;
	height: 2px;
	background: #FF6354;
}

.card_cadastro label {
	margin: 10px 0;
}

.card_cadastro input {
	padding: 10px;
	border: none;
	border: 1px solid #FF6354;
	border-radius: 10px;
}

.card_cadastro button {
	margin: 30px 0 10px;
	padding: 10px;
	border: none;
	border-radius: 12px;
	background: #FF6354;
	color: #FFF;
	cursor: pointer;
	text-transform: uppercase;
}
```