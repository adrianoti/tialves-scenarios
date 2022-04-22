# Criando seu Hello World em C++

1.1. Crie seu arquivo de programa Hello World em C++, utilizando o editor de texto de linha de comando VI, digitando o seguinte comando no terminal ao lado:

`vi helloworld.cpp`{{execute}}


1.2. Agora, digite o código do Hello World abaixo no seu arquivo aberto ou copie e cole dentro do arquivo. 


```cpp
#include <iostream>

int main()
{
    std::cout << "Olá, Mundo!" << std::endl;
    return 0;
}
``` 

1.3. Após digitar ou copiar o código dentro do arquivo, feche o VI salvando o arquivo helloworld.cpp com o comando:

`:wq`{{execute}}

Se tudo ocorreu como o esperado, você acabou de escrever seu primeiro programa em C++, utilizando o editor de texto de linha de comando VI. 

1.4. Para verificar que o arquivo foi criado, liste os arquivos do diretório atual com o comando ls.

`ls`{{execute}}

1.5. Para verificar o conteúdo do arquivo helloworld.cpp criado, execute o comando cat passando como parâmetro o nome do arquivo.

`cat helloworld.cpp`{{execute}}

Verifique se o conteúdo exibido com o comando cat é o mesmo mostrado no passo 1.2. Senão, exclua o arquio criado e repita todos os passos até aqui. Caso o arquivo esteja idêntico ao mostrado no passo 1.2. prossiga para o próximo passo, para compilação do seu programa.


