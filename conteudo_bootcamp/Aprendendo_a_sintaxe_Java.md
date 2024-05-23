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

* 99,9% das nossas classes iniciarão com ```public class;```

* Toda classe precisa de nome, exemplo ```MinhaClasse;```

* O nome do arquivo deve ser idêntico ao nome da classe pública;

* Após o nome, definir o corpo ```{ }``` , onde iremos compor nossas classes com atributos e métodos.



```
public class MinhaClasse {

	public static void main (String[] args) {
		System.out.print ("Olá turma, sejam bem-vindos");
}
	
}
```
* É de suma importância que agora você consiga se localizar dentro do conjunto de chaves ```{ } ```existentes em sua classe.

* Dentro de uma aplicação, **recomenda-se que somente uma classe possua o método** ```main```, responsável por iniciar todo o nosso programa.

* O método main recebe seu nome ```main```, sempre terá a visibilidade ```public```, será difinido como``` static```, não retornará nenhum valor com ```void``` e receberá um parâmetro do tipo array de caracteres ```String[]```.

#### Padrão de nomenclatura

Quando se trata de escrever códigos na linguagem Java, é recomendado seguir algumas convenções de escrita. Esses padrões estão expressos nos itens abaixo:

* Arquivo .java: Todo arquivo .java deve começar com letra MAIÚSCULA. Se a palavra for composta, a segunda palavra deve também ser maiúscula, exemplo:

```Calculadora.java, CalculadoraCientifica.java```

* Nome da classe no arquivo: A classe deve possuir o mesmo nome do arquivo.java, exemplo:

```
// arquivo CalculadoraCientifica.java

public class CalculadoraCientifica {

}
```

* Nome de variável: toda variável deve ser escrita com letra minúscula, porém se a palavra for composta, a primeira letra da segunda palavra deverá ser **MAIÚSCULA**, exemplo: ```ano``` e ```anoFabricacao```. O nome dessa prática para nomear variáveis dessa forma se chama "camelCase".

> Existe uma regra adicional para variáveis, quando na mesma queremos identificar que ela não sofrerá alteração de valor, exemplo: queremos determinar que uma variável de nome br sempre representará "Brasil" e nunca mudará seu valor, logo, determinamos como escrita o código abaixo:
```
String BR = "Brasil"
double PI = 3.14
int ESTADOS_BRASILEIRO = 27
int ANO_2000 = 2000
```

> Recomendações: Para declarar uma variável nós podemos utilizar caracteres, números e símbolos, porém, devemos seguir algumas regras da linguagem.

* Deve conter apenas letras, _ (underline), $ ou os números de 0 a 9;

* Deve obrigatoriamente se iniciar por uma letra (preferencialmente), _ ou $, jamais com número;

* Deve iniciar com uma letra minúscula (boa prática – ver abaixo);

* Não pode conter espaços;

* Não podemos usar palavras-chave da linguagem;

* O nome deve ser único dentro de um escopo.

```
// Declação inválida de variáveis

int numero&um = 1; //Os únicos símbolos permitidos são _ e $
int 1numero = 1;    //Uma variável não pode começar com númerico
int numero um = 1; //Não pode ter espaço no nome da variável
int long = 1; //long faz parte das palavras reservadas da linguagem
 
 // Declaração válida de veriáveis
int numero$um = 1;
int numero1 = 1;
int numeroum = 1;
int longo = 1;
```
#### Declarando métodos e variáveis

___
### Tipos de variáveis

### Operadores

### Métodos

### Escopo

### Palavras reservadas

### Java Doc

### Terminal e Argumentos
