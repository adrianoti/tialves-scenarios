# Instalar a Extensão Live Server

1.1. Clique na Tab IDE, conforme mostrado na figura abaixo, para carregar e acessar o VS Code. Caso não carregue automaticamente, clique em "Display port".

![VS Code IDE Tab](./assets/Katacoda_Iframe_IDE_VSCode_Tab.png)

1.2. No VS Code, clique no ícone referente a opção "Extensions", no menu lateral direito.

![VS Code Menu Extensions](./assets/VSCode_menu_Extensions_option.png)

1.3. Em "EXTENSIONS: MARKETPLACE", pesquise por "Live Server", selecione e instale a extensão Live Server por Ritwick Dey clicando em "Install".

![VS Code Menu Extensions](./assets/VSCode_Live_Server_Extension_install.png)

Quando a instalação terminar, se solicitado, clique na opção "Reload Required", para reiniciar o VS Code.

# Criando diretórios para os projetos "HTML CSS JS" e para o projeto HelloWorld utilizando comandos de Shell Linux

1.4. Crie um diretório chamado html_css_js_projects utilizando o terminal.

`mkdir html_css_js_projects`{{execute}}

1.5. Entre no diretório de projetos html_css_js_projects criado e crie uma pasta para o projeto Hello World.

`cd html_css_js_projects`{{execute}}

`mkdir helloworld`{{execute}}

# Abrindo o diretório do projeto Hello World no VS Code

1.6. No VS Code, clique no ícone de menu no canto superior esquerdo e, em seguida, no menu "File" clique na opção "Open Folder...", conforme imagem abaixo.

![VS Code Open Folder Menu](./assets/VSCode_menu_openfolder.png)

1.7. Na janela Open Folder, insira o caminho para o projeto Hello World: /root/html_css_js_projects/helloworld/ e clique em OK. No VS Code Explorer irá aparecer uma área referente ao diretório helloworld aberto: HELLOWORLD.

![VS Code Open Folder Hello World Path](./assets/VSCode_htmlcssjs_openfolder_helloworld_path.png)

1.8. No VS Code Explorer, na área HELLOWORLD, clicar no ícone referente a "Novo Arquivo". Em seguida, digite o nome do seu arquivo de código HTML: index.html e tecle ENTER.

![VS Code Explorer HELLOWORLD New File](./assets/VSCode_helloworld_project_new_file.png)

![VS Code Explorer HELLOWORLD File Name](./assets/VSCode_helloworld_indexhtml_name.png)

1.9. Agora, dentro do arquivo HTML aberto no VS Code, digite "html" e utilize a sugestão Emmet Abbreviation "html:5", selecionando-a. O código padrão HTML5 é gerado automaticamente. O código gerado é o mesmo que é mostrado abaixo. Em seguida, tecle CTRL+S para salvar o arquivo, ou salve-o acessando o ícone de menu no canto superior esquerdo e, em seguida, no menu "File" clique na opção "Save".

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
``` 

1.10. Altere o código, colocando entre as tags <body> e </body> o trecho de código<h1> Hello World!</h1>, de forma a mostrarmos na nossa primeira página HTML a frase "Hello World!", ao ser visualizada em um browser. O código no arquivo final no VS Code deverá ficar como mostrado na figura abaixo. Lembre-se, também, de confirmar que a extensão do arquivo é .cpp

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>Hello World!</h1>
</body>
</html>
``` 

