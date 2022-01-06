## Criando seu repositório local

#### No seu computador, crie uma pasta para o seu projeto. Vamos chamá-la de simple-git-demo.

#### Entre nesta pasta e adicione um repositório local ao projeto usando os seguintes comandos:

#### cd simples-git-demo 

#### git init

#### O comanto git init adiciona um repositório local ao projeto.
#### Adicionando um pouquinho de código

#### Crie um arquivo chamado demo.txt na pasta do projeto com o seguinte texto:

#### Conteúdo Inicial

#### Aqui nos vamos brincar apenas com texto porque o foco deste artigo e o Git e não uma linguagem de programação específica.
#### Preparando e “Commitando” o código

#### O commit e o processo no qual o codigo e adicionado ao repositório local. Antes de commitar o código, ele deve estar na area de staging. A área de staging e onde são mantidas as alterações que ainda não foram commitadas.

#### Qualquer arquivo que não tenha sido adicionado a área de stagind não será commitado. Isto permite ao desenvolvedor controlar qual arquivo sera commitado.

#### Peparando
#### Use o seguinte comando para preparar o arquivo para ser commitado, ou seja mandá-lo para a área de staging.

#### git add demo.txt

#### No caso de querer adicionar vários arquivo você pode usar:

#### git add file1 file2 file3

#### Se você deseja adicionar todos os aquivos dentro da pasta do projeto, use o seguinte comando:

#### git add .

#### Use este último comando com cuidado para não adicionar arquivos indesejados na área de staging.
#### Commitando

#### Use o seguinte comando para commitar o arquivo:

#### git commit -m "Meu primeiro Commit"

#### “Meu primeiro Commit” será a mensagem do commit. Procure usar mensagems de commit que sejam relevantes e que indiquem o que as alterações do código fazem.