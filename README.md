# POO-Exercicios-Introducao-a-Orientacao-a-Objetos

#### **1 Problema**
O que é um objeto?

É uma coisa,entidade que possua identidade.

#### **2 Problema**
Identifique 3 características e 3 comportamentos de um carro.

Carro
Características: Modelo, ano, cor.
Comportamentos: Ligado, desligado, andando.

#### **3 Problema**
No contexto de Orientação a Objetos, as características e comportamentos são
chamados respectivamente de?

Atributos e métodos.


#### **4 Problema**
Qual é o objetivo da programação orientada à objetos?

Tem o objetivo de desenvolver softwares utilizando objetos de maneira cooperativa, através de troca de mensagens.

#### **5 Problema**
O que é abstração. Cite um exemplo.

É poder pensar em uma identidade e ela poder ser única para todos os objetos. 

#### **6 Problema**
O que é classe?

É a descrição de um conjunto de objetos compartilha. Define os atributos e métodos que o objeto deverá possuir.

#### **7 Problema**
Qual é o padrão utilizado para nomear as classes? Cite um exemplo.

O padrão é CamelCase e a primira letra é maíscula.

     Classe 
    

#### **8 Problema**
Qual opção apresenta corretamente o nome da classe carro elétrico ?

1. carroeletrico
2. carroEletrico
3. Carroeletrico
4. CarroEletrico
5. carro eletrico

opção correta: 4. CarroEletrico

#### **9 Problema**
Qual é o padrão utilizado para nomear os atributos? Cite um exemplo.

    


#### **10 Problema**
Qual opção apresenta corretamente o nome do atributo cor de fundo?

1. CordeFundo
2. CorDeFundo
3. corDeFundo
4. cor de fundo
5. corDeFundo
6. CorDeFundo

opção correta: 5. corDeFundo

#### **11 Problema**
Qual é o padrão utilizado para nomear os métodos? Cite um exemplo.


#### **12 Problema**
Qual opção apresenta corretamente o nome do método está vazio ?

1. estaVazio
2. estaVazio
3. estavazio
4. EstaVazio
5. Estavazio
6. Esta vazio

#### **13 Problema**
No contexto de orientação à objetos, o que é um objeto? Em que momento
existe um objeto? Quando ele deixa de existir?

A partir que se instância esse objeto.

#### **14 Problema**
Qual é o objetivo do operador new?

Ele cria um objeto a partir de uma classe.

#### **15 Problema**
O que é o construtor? Qual é o seu objetivo? Qual deve ser o seu nome? Cite
um exemplo.

É um método especial para a instanciação de objetos, iniciar variáveis, instanciar outros objetos
necessários, disparar métodos de inicialização.

#### **16 Problema**
Caso o construtor da classe Aluno não for declarado, qual será o seu construtor?

Ele utilizará o padrão java (default).


#### **17 Problema**
Crie um exemplo de instanciação da classe Aluno. Utilize o construtor padrão.

    Aluno var = new Aluno();

#### **18 Problema**
O que é encapsulamento?


#### **19 Problema**
Qual é o objetivo do modificador de acessso public?

#### **20 Problema**
Qual é o objetivo do modificador de acessso private?

#### **21 Problema**
Como é aplicado o encapsulamento em uma classe? Considere a classe Aluno
com o atributo matrícula.

#### **22 Problema**
Qual o objetivo dos métodos getters? Crie um exemplo.


#### **23 Problema**
Qual o objetivo dos métodos setters? Crie um exemplo.

#### **24 Problema**
O diagrama de classe UML é composto por 3 partes. O que vai em cada parte?

Na primeira parte vai o nome da classe, na segunda parte os atributos e na terceira os métodos. 

#### **25 Problema**
Qual é o padrão utilizado para representar um atributo no diagrama de classe
UML? Crie um exemplo

#### **26 Problema**
Qual é o padrão utilizado para representar um método no diagrama de classe
UML? Crie um exemplo.

#### **27 Problema**
Como o construtor de uma classe pode ser diferenciado no diagrama de classe
UML? Crie um exemplo.

#### **28 Problema**
Quais são os símmbolos utilizados no diagrama de classe UML para representar
os modificadores de acessos ao atributos e métodos? Crie um exemplo.

#### **29 Problema**
Considere a classe Cliente, com os atributos nome, email e telefone com os
respectivos métodos getters e setters. Desenvolva o diagrama de classe UML

#### **30 Problema**
Considere a classe Cliente apresentado no Problema 29, e desenvolva o código
Java correspondente.


#### **31 Problema**
Desenvolva o código java das classes do apresentadas no diagrama de classes
UML abaixo:



#### **32 Problema**
Desenvolva o diagrama de classe dos codigos Java abaixo.

    public class Livro{
        private String nome;
        public String getNome(){
        return nome;
        }
        public void setNome(String nome){
        this.nome = nome;
        }
    }

    public class ContaCorrente{
        private double saldo;
        public double sacar(double valor){
        return 0.0;
        }
        public void depositar(double valor){
        this.saldo = saldo;
        }
        private void recalcularSaldo(){
        }
        }

       public class Par{
        public String chave;
        public String valor;
        }
        public class Impressora{
            public void imprimir(Documento documento){
            }
        }

#### **33 Problema**
O que e o estado de um objeto? Cite um exemplo com a classe Aluno com
os atributos nome, idade, matricula e curso. Utilize o diagrama de estado de
objeto

#### **34 Problema**
Qual é o estado do objeto da classe Dog quando é inicializado? Desenvolva o
diagrama de objetos.

    public class Dog{
        private int years;
        private String name;
        private boolean alive;
        //Getters e setters suprimido
    }

#### **35 Problema**
Qual é o estado do objeto dog no final da execução do método main? Desenvolva
o diagrama de objetos.

        public static void main(String args[]){
            Dog dog = new Dog();
            dog.setYears(10);
            dog.setName("Spike");
            dog.setAlive(true);
        }

#### **36 Problema**
Qual é o estado do objeto pug e buldog após a execução da linha 6? Desenvolva
o diagrama de objetos.

    Dog pug = new Dog();
    Dog buldog = new Dog();
    pug.setName("Spoke")
    buldog.setName("Spike");
    pug.setAlive(true);
    pug.setYears(2);
    buldog.setName("Floquinho");
    pug.setYears(1);

#### **37 Problema**
Analise o código abaixo. Verifique se existem problemas, caso sim, indique o
problema e sugira as correções.

    1: public class Cat{
    2: private String name;
    3: public double weight;
    4: // Getters e Setters suprimidos
    5:}
    6:public class Main{
    7: public static void main(String args[]){
    8: Cat c = new Cat();
    9: c.weight = 3.5;
    10: c.name = "BlackCat";
    11: }
    12:}
