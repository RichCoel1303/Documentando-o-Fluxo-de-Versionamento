# Documentando o fluxo de versionamento

## **SESSÃO 1: CRIAÇÃO E ENVIO**

### 🗃️COMO CRIAR UM REPOSITORIO?🗃️
**Repositório:** Para criar um repositório no GitHub é bem simples, vá no botão **Create new** na parte superior da pagina, logo em seguida clique em **New repository**, lá temos a opção de adicionar o nome e a descrição desejadas no repositorio, alem de poder adicionar o **READ.ME** onde colocamos uma espécie de apresentação do nosso projeto, gitignore para indicar quais partes do projeto não devem ser publicadas ou rastreadas, e claro a licença para declarar que o código é seu de direito impossibilitando o uso sem permissão, após finalizas as configurações é só clicar **Create repository**, onde vai criar o local que terá nosso READ.ME e poderemos anexar arquivos vinculados a nosso projeto, como códigos e assets.

### 🛜CONEXÃO COM O REPOSITORIO🛜
**GitHub Desktop:** Para vincular uma pasta ao seu Github de forma local acesse o aplicativo GitBash, para funcionar você deve criar um repositorio como ensinado acima, clone o repositorio pegando o link dele, e utilizando o CMD ou Powershell execute o seguinte comando **git clone https://github.com/SEU-NOME-DE-USUARIO/SEU-REPOSITORIO** criando um clone local do repositorio desejado, adicione o arquivo que quer adicionar para dentro do repositorio clonado, mude o repositório atual para seu repositorio local, utilize os seguintes comandos para vincular o arquivo ao repositório **$ git add "$ git add "adds the file to your local repository and stages it for commit." Para cancelar o preparo de um arquivo, use "git reset HEAD ARQUIVO'.'."**, **$ git commit -m "Add existing file" ** Vincula as mudanças detectadas e prepara para o envio no repositorio remoto. Para remover esse commit e modificar o arquivo, use "git reset --soft HEAD~1", faça o commit e adicione o arquivo novamente.**, **$ git push origin YOUR_BRANCH "Substitui seu repositorio pelo seu repositorio local terminando o envio".**

### 📤PRIMEIRO ENVIO NO GITHUB📤
**Envio:** Para realizar seu primeiro envio no GitHub temos algumas opções, por exemplo se for realizar no navegador é bem simples, dentro do seu repositório clique em **Add file**, e logo em seguida selecione o arquivo ou pasta desejados para o envio, porem pelo navegados temos a limitação de apenas 25mb no upload, já caso você resolva utilizar a outra opção, você pode utilizar comandos para realizar o upload no seu GitHub, primeiro entre no seu repositório local como ensinado acima, abra o GitBash, mude seu repositório atual para seu repositório local e utilize os comandos que estão indicados na explicação do topico acima.

## **SESSÃO 2:** READ.ME PERFEITO

### 📖PROPOSITO DO READ.ME📖
O READ.ME é utilizado para a apresentação principal do projeto, sendo um tipo de cartão de visitas explicando como instalar e como funciona de forma simples e bem definida, ele é para o **publico-alvo** do seu projeto, por exemplo, uma atividade de escola seria para seu professor e colegas e deverá ser escrito da forma adequada a quem vai ler, outro exemplo seria um projeto de código aberto de algo como um protótipo de um jogo, nesse caso seria para o publico juvenil e deveria ser escrito de forma básica e direta para que todos entendam de um jeito simples.

### ❗DADOS FUNDAMENTAIS❗
Como citado acima, o READ.ME precisa ter algumas coisas que são essenciais, como o **Titulo** para dar uma base de sobre o que o projeto é, **Descrição** para descrever passo a passo do funcionamento do projeto e para que deve ser utilizado, tecnologias utilizadas para mostrar quais tecnologias foram usadas para a base do seu projeto por exemplo uma linguagem de programação ou uma inteligência artificial que foi usada como auxilio, e por fim como realizar a instalação do projeto


