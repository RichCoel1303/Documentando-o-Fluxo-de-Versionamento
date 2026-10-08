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
Como citado acima, o READ.ME precisa ter algumas coisas que são essenciais, como o **Titulo** para dar uma base de sobre o que o projeto é, **Descrição** para descrever passo a passo do funcionamento do projeto e para que deve ser utilizado, tecnologias utilizadas para mostrar quais tecnologias foram usadas para a base do seu projeto por exemplo uma linguagem de programação ou uma inteligência artificial que foi usada como auxilio, e por fim como realizar a instalação do projeto dando o passo a passo das ferramentas que devem ser utilizadas.

### 📝OUTRAS INFORMAÇÕES IMPORTANTES📝

Além das informações citadas anteriormente, um README profissional pode possuir outras informações que ajudam o usuário a entender melhor o projeto, como:

* **Status do desenvolvimento:** Mostra se o projeto está em desenvolvimento, concluído, em testes ou se não recebe mais atualizações.
* **Como utilizar:** Explica como utilizar o projeto depois de instalado.
* **Exemplos:** Pode apresentar exemplos de utilização, imagens ou GIFs para mostrar o funcionamento do projeto.
* **Contribuição:** Em projetos que permitem contribuições de outras pessoas, pode explicar como elas podem ajudar no desenvolvimento.
* **Licença:** Informa quais são as regras para utilização, modificação e distribuição do projeto.

Essas informações ajudam o usuário a entender o projeto sem precisar analisar todos os arquivos do código para descobrir como ele funciona.

### ✨O PODER DO MARKDOWN✨

O Markdown é utilizado no README porque permite organizar o texto de uma forma simples utilizando símbolos e comandos fáceis de entender. Ele também é interpretado pelo GitHub e transformado em uma página visualmente organizada.

Por exemplo, podemos utilizar **dois asteriscos** para deixar uma palavra em negrito, *um asterisco* para deixar uma palavra em itálico e `crases` para destacar comandos ou partes de código.

Também podemos criar títulos utilizando o símbolo **#**, listas utilizando **-** e listas numeradas utilizando números. Isso facilita bastante a leitura, principalmente quando o README possui muitas informações.

Outra vantagem é que o Markdown não exige ferramentas complexas para ser escrito. Podemos criar ou editar um arquivo `.md` utilizando praticamente qualquer editor de texto e depois visualizar o resultado diretamente no GitHub.

---

# **SESSÃO 3: O MAPA DAS ATUALIZAÇÕES**

### 🌐ATUALIZAÇÃO PELO GITHUB ONLINE🌐

Uma das formas mais simples de atualizar um projeto é diretamente pelo navegador. Dentro do repositório no GitHub podemos acessar o arquivo que desejamos modificar e utilizar a opção de edição para alterar seu conteúdo.

Depois de realizar a alteração, o próprio GitHub permite criar um **commit**, onde podemos colocar uma mensagem explicando o que foi modificado. Após confirmar, a alteração já fica registrada no histórico do repositório.

Também é possível adicionar arquivos pelo navegador utilizando a opção **Add file**, podendo escolher entre criar um arquivo novo ou fazer upload de arquivos existentes.

Essa opção é útil para alterações pequenas e rápidas, principalmente quando não estamos no computador onde o projeto está instalado. Porém, existem limitações, principalmente para arquivos grandes e para alterações que envolvem muitos arquivos ao mesmo tempo. Por isso, para projetos maiores, o uso do Git no computador acaba sendo mais adequado.

### 💻ATUALIZAÇÃO PELO GIT NO TERMINAL💻

Outra forma de atualizar o projeto é utilizando o Git através do terminal, como o **Git Bash**, CMD ou PowerShell.

Depois de realizar alterações nos arquivos do projeto, podemos utilizar a sequência:

**1. Verificar as alterações:**

`git status`

Esse comando mostra quais arquivos foram modificados, adicionados ou removidos desde o último commit.

**2. Preparar os arquivos:**

`git add .`

Esse comando adiciona as alterações para a área de preparação (*staging area*), indicando quais mudanças farão parte do próximo commit.

**3. Criar o commit:**

`git commit -m "Descrição da alteração"`

O commit registra as alterações no histórico do projeto. A mensagem deve explicar de forma curta o que foi modificado.

**4. Enviar para o GitHub:**

`git push origin main`

O `push` envia os commits que estão no repositório local para o repositório remoto no GitHub.

Essa é uma das formas mais tradicionais de trabalhar com Git porque permite controlar cada etapa do processo e funciona muito bem para projetos maiores e para quem trabalha constantemente com programação.

### 🧑‍💻ATUALIZAÇÃO PELO VS CODE**

Também é possível realizar todo esse processo utilizando uma IDE, como o **Visual Studio Code**. Nesse caso, não precisamos necessariamente digitar todos os comandos no terminal.

O VS Code possui uma área chamada **Source Control**, onde conseguimos visualizar os arquivos que foram modificados. Podemos selecionar os arquivos que queremos preparar para o commit, escrever uma mensagem explicando a alteração e realizar o commit.

Depois disso, podemos utilizar a opção de **Push** para enviar as alterações para o GitHub.

Na minha experiência, essa opção facilita bastante porque consigo programar e controlar o Git no mesmo lugar. Também consigo visualizar rapidamente quais arquivos foram modificados antes de enviar as alterações.

Mesmo utilizando a interface gráfica, o funcionamento continua sendo baseado nos mesmos conceitos do Git: **alterar, preparar, fazer commit e enviar para o repositório remoto**.

### 🖥️ATUALIZAÇÃO PELO GITHUB DESKTOP🖥️

O **GitHub Desktop** é uma ferramenta criada para facilitar o uso do Git através de uma interface gráfica. Em vez de precisar utilizar comandos no terminal, podemos visualizar as alterações diretamente no programa.

Depois de modificar os arquivos do projeto, o GitHub Desktop mostra quais arquivos foram alterados e permite verificar as diferenças entre a versão anterior e a versão atual.

Podemos então escrever uma mensagem para o commit e selecionar a opção para realizar o commit. Depois disso, podemos utilizar o **Push origin** para enviar as alterações para o GitHub.

Uma das principais vantagens é conseguir visualizar de maneira mais clara o que foi alterado antes de enviar. Isso pode ser mais fácil para quem ainda está aprendendo Git ou para quem prefere trabalhar utilizando uma interface gráfica.

### 🔄A FILOSOFIA DA ATUALIZAÇÃO🔄

Manter o repositório atualizado continuamente é importante porque o Git foi criado justamente para registrar a evolução do projeto ao longo do tempo.

É melhor realizar vários commits pequenos e organizados do que fazer apenas um grande envio depois de muito tempo. Por exemplo, podemos ter commits como:

* `Criada página inicial`
* `Adicionado sistema de login`
* `Corrigido erro no formulário`
* `Adicionado banco de dados`
* `Atualizado README`

Dessa maneira, cada alteração fica registrada separadamente e podemos entender melhor como o projeto evoluiu.

Caso apareça algum problema, também fica mais fácil descobrir em qual alteração ele surgiu e, se necessário, voltar para uma versão anterior.

Além disso, manter o projeto atualizado no GitHub reduz o risco de perder o trabalho caso aconteça algum problema no computador. O repositório remoto funciona como uma cópia do projeto que também possui todo o histórico das alterações.

Por isso, a melhor prática é **não deixar para enviar tudo somente no final do desenvolvimento**. Fazer commits frequentes e enviar as alterações para o GitHub mantém o projeto organizado, facilita o acompanhamento do desenvolvimento e torna muito mais fácil corrigir problemas.

# **CONCLUSÃO**

O Git e o GitHub não servem apenas para guardar arquivos na internet. Eles permitem acompanhar a evolução de um projeto, registrar alterações e facilitar o trabalho durante todo o desenvolvimento.

O fluxo que aprendi pode ser resumido da seguinte forma:

**Criar o repositório → conectar ao computador → adicionar arquivos → preparar as alterações → realizar o commit → enviar com push → continuar atualizando o projeto.**

Além disso, o README é importante para explicar o projeto para outras pessoas, enquanto os commits permitem registrar cada etapa do desenvolvimento.

Dessa forma, utilizar Git e GitHub corretamente ajuda a manter o projeto **organizado, documentado, seguro e com um histórico das alterações**, tornando o desenvolvimento muito mais fácil de acompanhar.



