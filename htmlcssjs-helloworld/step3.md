# Inserindo os códigos CSS e JS na sua Página Web

Neste passo, vamos entender como o CSS e o JS modificam sua página web, adicionando estilo (CSS) e lógica ou automação (JS).

3.1. Modifique o código entre as tags "<"body">" e "<\"body">" (sem as aspas), conforme o código abaixo.

```html
<body>
    <span class="containerSpan"> 
        <span class="textSpan"> Hello World! </span>
        <span class="revealSpan">  </span>  
    </span>
    <div class="containerButton">
        <button type="button" class="repeatButton" onclick="revealFunction()"> repeat </button>
    </div>
</body>
```

3.2. Insira o seguinte código CSS entre as tags "<"head">" e "<\"head">" (sem as aspas).

```html
    <style>
        body, html{
            height: 98%;
        }

        body{
            display: flex;
            position: relative;
            flex-wrap: wrap;
            width: 98.5%;
            justify-content: center;
        }

        .containerSpan{
            display: block;
            align-items:center;
            position: absolute;
            align-self: center;
            font-size: 15vmin;
            font-weight: 1000;
            font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
            line-height: 1.205;
        }

        .textSpan{
            opacity: 1;
        }

        .revealSpan {
            position: absolute;
            width: 100%;
            height: 100%;
            left: 0;
            top: 0;
            z-index: 100;
            transform-origin: right;
            transform: scaleX(1);
            background-color: #ffffff;
        }


        .containerButton {
            display: block;
            position: absolute;
            align-self: flex-end;
            z-index: 100;
        }

        .repeatButton {
            font-size: 12px;
            bottom: 0;
            left: 0;
            right: 0;
            background-color: #ffffff;
            border-bottom: 1px dotted grey;
            border-top: 0;
            border-left: 0;
            border-right: 0;
            padding: 0;
            margin: 0 auto 2%;
            cursor: pointer;
            color: grey;
        }
    </style>
```

3.3. Insira o seguinte código JS entre as tags "<"head">" e "<\"head">" (sem as aspas).

```js
    <script>
    
        function revealFunction() {

            var temp = document.querySelector('.revealSpan')
            var transform = 'scaleX(1)';
            var counter = 100;
            var i = setInterval(function(){
                counter--;
                var t = counter / 100;
                transform = 'scaleX('+t+')';
                temp.style.transform = transform;
                if(counter === 0) {
                    clearInterval(i);
                }
            }, 20)
        }
    </script>
```

</head>

</html>
</pre>