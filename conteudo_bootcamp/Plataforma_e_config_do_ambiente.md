# Platafornas e Configuração do ambiente

## Introdução a IDEs

Os recursos das IDEs são:

* IDE -> um Ambiente de desenvolvimento Integrado.

* Auto-complete -> Ferramenta que completa comandos digitados parcialmente.

* IntelliSense -> Expressões que complementa até mesmo um bloco de código.

* Formatação de palavas e blocos de códigos

* Compilação de programa

* Depuração (acompanhamento) de execução do programa.

Cada IDE dispõe de recursos comuns ou plugins especificos para te auxiliar na agilidade de desenvolvimento.

**IDEs Recomendadas:**

* [Visual Studio Code](https://code.visualstudio.com/)

* [Apache - Netbeans IDE](https://netbeans.apache.org/front/main/index.html)

* [Eclipse](https://eclipseide.org/)

* [Intellij IDE](https://eclipseide.org/)

**Independente da IDE escolhida, estude estes pontos para dominar a ferramenta:**

* O que são Workspaces

* Definir a JDK na IDE

* Criar/ abrir um projeto Java

* Criar / importar um projeto Maven

* Conhecer os principais atalhos

* Code Snippet

* Executar / Depurar nosso programa

* Conhecer alguns atalhos.

**Maven**, é uma ferramenta de automação de compilação utilizada primariamente em projetos java, mas hoje também é utilizada para construir e gerenciar projetos escritos em C#, Ruby, Scala e outras linguagens.

## Configuração do ambiente

Para começar a a desenvolver em Java é necessário que o JDK esteja instalado.

[JDK Download](https://www.oracle.com/java/technologies/downloads/)
  
> É extremamente relevante determinar a versão do Java que precisa utilizar diante de alguns requisitos do projeto.

### Instalando o JDK no Windows
>
> Algumas IDEs como o **[VSCode](https://code.visualstudio.com/Download)** Já consegue baixar e instalar o JDK e realizar a configuração de forma fácil.

* Busque no Google por Java [JDK xxx](https://www.oracle.com/java/technologies/downloads/#jdk22-windows) (Versão Desejada)
* Selecione a opção .exe de acordo com o seu sistema operacional
* Após o download, executar o instalador para instalar o Java no Windows. Este processo instalará tanto o JDK quanto a JRE.

> Evite mudar o diretório de instalação

* Em seu explorer deve ter algo mais ou menos assim:

> C:\Program Files\Java

* Precisamos agora validar se a instalação também já configurou nossa variável de ambiente para poder executar o Java pelo Prompt de comando ou PowerShell do Windows.
* Abre o Prompt de comando e execute o comando java -version

> Não iremos configurar as variáveis de ambiente pois não é um pré-requisito para desenvolver em Java considerando que iremos usufruir das mais poderosas IDEs para aumentar nossa produtividade em codificar na linguagem.

Nesse curso a versão Java escolhida foi [jdk 8](https://www.oracle.com/br/java/technologies/javase/javase8-archive-downloads.html)
> É necessário fazer loguin na Oracle para realizar o download.

Quando instalar o JDK, o JRE também será instalado

### Escolha sua IDE

---

#### Instalando o VSCode

 No Google:

* VSCode for Java
* Defina qual o SO desejado
* Faça o download
* O arquivo será um pack **VSCode + Java + JDK** e outros componentes.
* Inicialize a IDE
* **CTRL + SHIFT + P**, para criar um novo projeto Java
* Será sugerido alguns frameworks para utilizar no projeto:
  * No build tools (Simples, sem framework)
  * Maven
  * Gradle
  * Spring Boot
  * Quarkus
  * MicroProfile
  * JavaFX
* Escolher onde será armazenado a pasta do projeto
* inserir nome_do_projeto.java

> É possivel também customizar as fontes, cor da IDE, cor da fonte e etc.
> CTRL + SHIFT + P para acessar a paleta de opções.

[manual de instalação e configuração da IDE VSCode](https://balta.io/blog/visual-studio-code-instalacao-customizacao#:~:text=A%20instala%C3%A7%C3%A3o%20no%20Linux%20%C3%A9,Download%20voc%C3%AA%20ter%C3%A1%20um%20pacote%20.)

---

#### Instalando o Eclipse

No Google:

* Java JDK download
* [Java Downloads | Oracle](https://www.oracle.com/java/technologies/downloads/)
* Selecione o SO
* Faça o download do arquivo
* Se pedir o Loguin da Oracle, faça uma conta e logue.
* Acesse a área de download e dê duplo clique  e instale o programa

No Google:

* [eclipse ide download](https://www.eclipse.org/downloads/)
* Pode escolher por padrão download x86_64
* Caso tenha alguma familiaridade com a ferramenta poderá escolher também download packages
* Possui duas versões:
  * Eclipse IDE for Java Developers
    * O mais utilizado na maior parte das situações
  * Eclipse IDE for Enterprise Java and Web Developers
    * Uso em ambiente corporativo, mais robusto
* Acesse a área de download e dê duplo clique  e instale o programa
* Inicialize a IDE
* É criado altomaticamente projetos de teste

 > caso opte por remover os projetos testes, desmarque a opção delete

> Algo muito importante no uso das IDEs é a utilização dos atalhos para otimizar a performance durante os trabalhos.
> Para acessar a lista de atalhos -> [Eclipse IDE Shortcuts Java](https://www.geeksforgeeks.org/most-used-eclipse-keyboard-shortcuts-that-every-java-developer-should-know/)

[Manual para instalação e configuração da IDE Eclipse](https://www.ibm.com/docs/pt-br/maximo-anywhere/7.6.4?topic=container-installing-integrated-development-environment)

---

#### Instalando o Intellij

No Google:

* [intellij idea download](https://www.jetbrains.com/idea/download/?section=windows)
* Possui versão gratuita (Community)  e versão Ultimate (trial)
* Faça o download do programa
* Página possui vários pluguins, para melhoria de desenpenho e performance para os desenvolvedores
* Localizar o programa na área de download
* Duplo clique para instalar
* Após instalado a IDE, basta inicializa-la
* Será perguntado algumas se quer utilizar versão anterior (não necessário)

[Manual para instalação e configuração da IDE Intellij](https://www.jetbrains.com/help/idea/installation-guide.html)

---

#### Integrando o VSCode com o github

* [Manual para integração Vscode - Github](https://www.dio.me/articles/passo-a-passo-para-integracao-do-github-com-vscode)
