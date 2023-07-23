Para se iniciar um diretorio com NPM, Utilize o comando:

" npm init "
______________________________________________________________________________________________
Se quiser iniciar um diretoria NPM, sem responder todas aquelas perguntas, use o comando:

" npm init -y "
______________________________________________________________________________________________
Para utilizar algum comando do scripts, basta executar o comando:

" npm run nomeDoScript "

exemplo: npm run test
______________________________________________________________________________________________
Para instalar um pacote NPM, utilize o comando:

" npm install nomeDoPacote "   ou abreviado  " npm i nomeDoPacote "

______________________________________________________________________________________________
Para remover um pacote NPM, utilize o comando:

" npm remove nomeDoPacote "  ou  " npm r nomeDoPacote "

Caso a remoção de alguma dependencia seja feita de maneira manual, ir ate o terminal
e executar o comando " npm install " para atualizar.


______________________________________________________________________________________________
Para instalar uma dependencia de desenvolvimento, utilizar o comando

exemplos:

" npm i react --save-dev "
" npm i typescript --save-dev "
" npm i typescript -D "

______________________________________________________________________________________________
GitHub - ao subir o projeto para o Github, utilizar o .gitignore para ignora a pasta node modules
evitando subir milhares de arquivos para o github

Criar um arquivo " .gitignore "

em seguida escrever esse comando dentro do arquivo, que ao subir pro github os arquivos serão ignorados

node_modules


