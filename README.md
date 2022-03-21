# Shinsei CodeSnippet

Code Snippet para Esqueleto HTML e Modelo de README para repositório

## 🚀 Começando

Esse Projeto foi criado para automatizar e acelarar meu processo inicial de codificação, e se possível ajudar pessoas desenvolvedoras que estão iniciando nessa carreira (Eu, inclusive kk)

Esse arquivo .codesnippet tem a função de criar "trechos-códigos" que chamam uma função pré definida préviamente com a intenção de poupar tempo.

### 🔧 Instalação

* Para que o código possa ser instalado corretamente, você precisa abrir a paleta de comandos com o atalho Crtl + shift + P  e digitar "snippets", selecionar a opção "Configure User Snippets" ou "Configurar Snippets de Usuário". 
* Então crie um novo snippet Global.
* Criado o Snippet Global adicione o código deste repositório e sinta-se livre para alterá-lo conforme sua vontade, apenas tomando cuidado para não quebrar alguma funcionalidade.
* OBS.: Caso algum problema ocorra, é recomendado a exclusão do .codesnippet que foi criado para não inabilitar nenhuma função padrão do VSCODE.
* Após Feita a implementação do código no arquivo .codesnippet salve-o e crie um novo arquivo .html. Utilizando o Comando "s-html" é criado uma estrutura básica HTML com algumas metas que, na minha opinião, são bem importantes e não podem faltar no seu código, com algumas alterações de snippets padrões encontrados na aba de extensões do VSCode.
* Feito o teste no arquivo .html, chega a hora de testar o arquivo .MD . Lembrando aqui que, arquivos .MD, por padrão, não usam o emmet para fazer recomendações de código em qualquer situação, logo é necessário a adição de uma configuração no seu arquivo config.json para modificar isso.
* Abra a paleta de comandos com o atalho "Crtl + Shift + P" e digite "settings" para buscar as configurações do seu VSCode. Selecione a Opção "Open Settings" ou "Abrir Configurações" e ai um arquivo chamado "settings.json" será aberto.
* Neste arquivo, note que varios objetos estão declarados envoltos por "{}" (Chaves) e logo após separados por vírgula. Encontre o último separado por vírgula e adicione o código a seguir:
<code>
    "[markdown]": {
        "editor.quickSuggestions": {
            "strings": true
        }
    },
</code>
E salve o arquivo com um simples "Crtl + S"

* Após essa etapa seu arquivo .md já está apto a receber sugestões pelo emmet, então utilizando o comando "s-md" você conseguirá tem um template genérico de um bom README para alterar a vontade e utiliza-lo em seus repositórios.

## ⚙️ Executando os testes

Crie um arquivo .html  e utilize o comando "s-html". Se retornar um <!DOCTYPE> pré pronto então o CodeSnippet está funcionando corretamente.

Crie um arquivo README.md e utilize o comando "s-md". Se retornar um Template de README pré pronto então o CodeSnippet está funcionando corretamente.
OBS.: LEMBRANDO QUE, A CONFIGURAÇÃO DO ARQUIVO SETTINGS.JSON É OBRIGATÓRIA PARA QUE SEU COMANDO "S-MD" FUNCIONE EM ARQUIVOS .MD . Em Caso de dúvidas, seguir o passo a passo da aba "Instalação" aqui neste README.

## 📄 Notas

Este CodeSnippet foi feito por uma pessoa desenvolvedora iniciante e pode conter algum erro, se você quiser indicar alguma melhoria ou contribuir de alguma forma com este projeto, sinta-se livre para utiliza-lo como quiser. 
Agradeço qualquer feedback e críticas construtivas.
Este Snippet não foi disponibilizado na aba de extensões do VSCode, pois não encontrei o ferramental suficiente para completar esta tarefa. Caso você tenha essa expertise, sinta-se livre para entrar em contato para podermos realizar essa task.

## ✒️ Autores

Esse projeto foi desenvolvido por mim, com a intenção de ajudar pessoas desenvolvedoras iniciantes e para automatizar um processo manual de forma mais simplificada.


## 📄 Licença

MIT License

Copyright (c) <2022> <Carlos Gomes>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the 'Software'), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## 🎁 Agradecimentos

* Conte a outras pessoas sobre este projeto 📢
* Agradeço a todos que utilizarem este recurso 🤓.



---
⌨️ com ❤️ por [Carlos Gomes](https://github.com/Dev-Shinsei) 😊


