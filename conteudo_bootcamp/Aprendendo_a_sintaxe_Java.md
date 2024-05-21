## Aprendendo a Sintaxe Java

### Introdução
Conteúdo apresentará a sintaxe básica aplicada dentro da linguagem Java. Será apresentado as regras essenciais para a construção de códigos com base na linguagem. 
**Pré-requisitos**
* JDK instalado
* IDE escolhida
* Diretório do projeto definido
> Para saber mais acesse:
> [java básico](https://glysns.gitbook.io/java-basico/)
### Anatomia das classes
> **Assuntos**
>* Estrutura inicial 
>* Padrão de nomenclatura
>* Declarando variáveis e métodos
>* Identação 
>* Organizando arquivos
>* Java Beans

[Resumo sobre anatomia das classes](https://glysns.gitbook.io/java-basico/sintaxe/anatomia-das-classes)
* É comum mesclar expressões no idioma americano com o nosso;
* Existem projetos que recomendam que toda a implementação seja do programa seja escrita na lingua inglesa.

#### Sintaxe de declaração de uma nova classe:
```
public class MinhaClass {
	// Seu código aqui
}
```
* Quando for nomear uma classe, por via de regra, deve sempre começar com letra maiuscula e caso possua mais de uma palavra no nome, todas elas deverão começar com maiusculas.
* Se a classe for uma classe executável, tem a capacidade de inicializar o projeto de forma independente, é necessário ter um método especial (método principal).  Denominado de main.
```
public class MinhaClass {

public static void main (String[] args) {
	System.out.print ("Olá turma, sejam bem-vindos");
}
	
}
```
* public static -> 
* void -> Não irá retornar nada
* main -> Nome do método
* () -> Parâmetro
* String -> tipo de parâmetro desejado
* [] -> Expressão para determinar um array
* args -> Parâmetro argumentos
* public static void main (String[] args) -> método
* Dentro do método também possui um corpo ->  { } 
* System -> classe de sistema
	* Possui parâmetros  **in**: **InputStream**, **out**:**PrintStream**
* print -> inprime na tela uma mensagem.
* Tudo dentro de () é método.
* 
### Tipos de variáveis

### Operadores

### Métodos

### Escopo

### Palavras reservadas

### Java Doc

### Terminal e Argumentos
