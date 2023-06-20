# Login and Registration Page
Portuguese version at the end

This is a set of HTML and CSS files that implement basic login and registration pages. The code consists of two HTML files: `login.html` and `registration.html`, and a shared CSS file: `style.css`.

## login.html

The `login.html` file contains a simple login page. It consists of a form with fields for username and password, along with a login button.

### HTML Structure

The `login.html` file follows the following structure:

- `<section class="login-area">`: A section that wraps the entire content of the login page.
- `<div class="login-container">`: A container for the login form.
- `<div class="login-img">`: A container for the "Login" title.
- `<h2>Login</h2>`: The "Login" title.
- `<form>`: The login form with fields for username, password, and a login button.
- `<input type="text" name="username" placeholder="Username" autofocus>`: The field for the username.
- `<input type="password" name="password" placeholder="Password">`: The field for the password.
- `<input type="submit" value="Login">`: The login button.
- `<p>Don't have an account? <a href="#">Sign Up</a></p>`: Text suggesting to create a new account.

## registration.html

The `registration.html` file contains a simple registration page. It consists of a form with fields for username, email, password, and password confirmation, along with a registration button.

### HTML Structure

The `registration.html` file follows the following structure:

- `<section class="login-area">`: A section that wraps the entire content of the registration page.
- `<div class="registration-container">`: A container for the registration form.
- `<div class="login-img">`: A container for the "Registration" title.
- `<h2>Registration</h2>`: The "Registration" title.
- `<form>`: The registration form with fields for username, email, password, password confirmation, and a registration button.
- `<input type="text" name="username" placeholder="Username" autofocus>`: The field for the username.
- `<input type="email" name="email" placeholder="Email" autofocus>`: The field for the email.
- `<input type="password" name="password" placeholder="Password">`: The field for the password.
- `<input type="password" name="confirm-password" placeholder="Confirm Password">`: The field for confirming the password.
- `<input type="submit" value="Register">`: The registration button.
- `<p>Already have an account? <a href="#">Log In</a></p>`: Text suggesting to log in to an existing account.

## style.css

The `style.css` file contains the style definitions for the login and registration pages.

### General Styles

- `body`: Defines the overall style of the page body, including the background color, font family, and other related styles.
- `.login-area`: Defines the style of the login area, including positioning and alignment.
- `.login-container` and `.registration-container`: Define the style of the login and registration containers, including the layout, background color, dimensions, padding, and rounded border.
- `.login-img`: Defines the style of the "Login" and "Registration" titles, including alignment, font size, color, and text shadow.
- `input`: Defines the style of the input fields, including the background color, text color, border, height, padding, and shadow.
- `p` and `a`: Define the style of the accompanying text and links, including the text color.
- `input::placeholder`: Defines the style of the placeholder text within the input fields, including the color and font size.
- `form [type="submit"]`: Defines the style of the submit button, including the background color, font size, text transformation, and cursor.

## Usage

To use these login and registration pages, follow these steps:

1. Copy the `login.html`, `registration.html`, and `style.css` files into your project directory.
2. Customize the pages and styles to fit your specific requirements.
3. Link the `style.css` file to the HTML files using the `<link>` tag.

Make sure to replace any placeholder content or code snippets with your actual project code.



### PORTUGUÊS

# Página de Login e Cadastro

Este é um conjunto de arquivos HTML e CSS que implementa páginas de login e cadastro básicas. O código consiste em dois arquivos HTML: `login.html` e `cadastro.html`, e um arquivo CSS compartilhado: `style.css`.

## login.html

O arquivo `login.html` contém uma página de login simples. Ele consiste em um formulário com campos para nome de usuário e senha, além de um botão de login.

### Estrutura HTML

O arquivo `login.html` segue a seguinte estrutura:

- `<section class="area-login">`: Uma seção que envolve todo o conteúdo da página de login.
- `<div class="login">`: Um contêiner para o formulário de login.
- `<div class="login-img">`: Um contêiner para o título "Login".
- `<h2>Login</h2>`: O título "Login".
- `<form>`: O formulário de login com os campos de nome de usuário, senha e botão de login.
- `<input type="text" name="nome" placeholder="Nome de usuário" autofocus>`: O campo para o nome de usuário.
- `<input type="password" name="senha" placeholder="Senha">`: O campo para a senha.
- `<input type="submit" value="entrar">`: O botão de login.
- `<p>Ainda não tem uma conta? <a href="#">Criar conta</a></p>`: Um texto sugerindo a criação de uma nova conta.

## cadastro.html

O arquivo `cadastro.html` contém uma página de cadastro simples. Ele consiste em um formulário com campos para nome de usuário, e-mail, senha e confirmação de senha, além de um botão de cadastro.

### Estrutura HTML

O arquivo `cadastro.html` segue a seguinte estrutura:

- `<section class="area-login">`: Uma seção que envolve todo o conteúdo da página de cadastro.
- `<div class="cadastro">`: Um contêiner para o formulário de cadastro.
- `<div class="login-img">`: Um contêiner para o título "Cadastro".
- `<h2>Cadastro</h2>`: O título "Cadastro".
- `<form>`: O formulário de cadastro com os campos de nome de usuário, e-mail, senha, confirmação de senha e botão de cadastro.
- `<input type="text" name="nome" placeholder="Nome de usuário" autofocus>`: O campo para o nome de usuário.
- `<input type="email" name="email" placeholder="Email" autofocus>`: O campo para o e-mail.
- `<input type="password" name="senha" placeholder="Senha">`: O campo para a senha.
- `<input type="password" name="Repetir senha" placeholder="Confirmar Senha">`: O campo para a confirmação da senha.
- `<input type="submit" value="entrar">`: O botão de cadastro.
- `<p>Já tem uma conta? <a href="#">Entrar</a></p>`: Um texto sugerindo o login em uma conta existente.

## style.css

O arquivo `style.css` contém as definições de estilo para as páginas de login e cadastro.

### Estilos gerais

- `body`: Define o estilo geral do corpo da página, incluindo a cor de fundo, a família da fonte e outros estilos relacionados.
- `.area-login`: Define o estilo da área de login, incluindo o posicionamento e alinhamento.
- `.login` e `.cadastro`: Definem o estilo dos contêineres de login e cadastro, incluindo o layout, cor de fundo, dimensões, preenchimento e borda arredondada.
- `.login-img`: Define o estilo do título "Login" e "Cadastro", incluindo o alinhamento, tamanho da fonte, cor e sombra de texto.
- `input`: Define o estilo dos campos de entrada, incluindo a cor de fundo, cor do texto, borda, altura, preenchimento e sombra.
- `p` e `a`: Definem o estilo dos textos e links de acompanhamento, incluindo a cor do texto.
- `input::placeholder`: Define o estilo do texto de espaço reservado dentro dos campos de entrada, incluindo a cor e o tamanho da fonte.
- `form [type="submit"]`: Define o estilo do botão de envio, incluindo a cor de fundo, tamanho da fonte, transformação de texto e cursor.
