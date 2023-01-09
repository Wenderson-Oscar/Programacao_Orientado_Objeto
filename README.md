<h1 align ='center'> Programação Orientado a Objeto</h1>

### O intuito da criação desse projeto foi estudar e praticar POO usando python. obs: O seguinte tutorial estar de acordo com a minha perspectiva de estudo em relação ao tema.

Menu
=================
<!--ts-->
   * [Tecnologias utilizadas](#🛠-tecnologias)
   * [Guia do Projeto](#guia-do-projeto)
      * [Teoria POO](#o-que-é-programação-orientada-a-objetos)
      * [4 Pilares](intermediary/README.md)
   * [SOLID](#solid)
      
      
<!--te-->

## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

-  Python 3.8
- 🔗 [Visual Code](https://code.visualstudio.com/)
- 🔗 [Extension Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)

# Guia do Projeto

É Recomendado ler **todos os README primeiro** de cada pasta nesse projeto.
Seguimos com a Teoria que esta nesse Readme, assim aprendemos um pouco o que é POO(nessa parte ainda não abordamos os 4 Pilares), ao termos passado pela Teoria iremos para a pratica, que é no arquivo "basic".
### Guia:
   * **basic** → **intermediary** --> *01* --> *02* → **advanced**

<hr>

<h1 align = 'center'>TEORIA</h1>

# O Que é Programação Orientada a Objetos ?

“É um paradigma de programação de computadores onde se
usam classes e objetos, criados a partir dos modelos descritos
anteriormente, para representar e processar dados usando
programas de computadores”. (SANTOS, 2003)
<hr>

<h1> Por Que Foi Criada ? </h1>
O intuito da sua criação foi de aproximar a forma que se utiliza objetos da vida real em programas, daí o nome "objeto", que pode representar qualquer coisa tangível, e manipular esses objetos da mesma forma que manipulamos na vida real.

# Por Que usar POO ?

POO facilita a reutilização de objetos em outros programas. Em vez de criar código a partir do zero, você pode usar um objeto ou método existente e alterá-lo para se adequar ao seu programa.

# Vantagens

A programação orientada a objetos propõe uma representação mais fácil de ser compreendida, pois a relação de cada elemento em termos de um objeto, ou classe, pode ser comparado ao mundo real.

Outro benefício da POO é a reutilização de código. Com a complexidade dos sistemas cada vez mais ampla, o tempo de desenvolvimento iria aumentar absurdamente, caso não fosse possível a reutilização.

Essa funcionalidade é possível, pois a POO traz representações muito claras de cada um dos elementos que, normalmente, não são interdependentes. E dessa independência entre as partes do software é que esse código poderá ser reutilizado em outros sistemas no futuro.

Por fim, outra grande vantagem fica por conta da leitura e manutenção de código. Como sua representação do sistema se aproxima da vivência cotidiana, o entendimento do sistema como um todo é simplificado. Isso dá liberdade à equipe de desenvolvimento, não ficando dependente de uma só pessoa, como em alguns casos de linguagem estruturada.

Com ela, há também a possibilidade da criação de bibliotecas, com representações de classes, o que torna mais clara a reutilização de códigos.

<hr>

# Objeto:
“É a representação de uma coisa do mundo real.” (BARNES,2009)
<hr>

# Classe:
“É um projeto de um objeto. Ela informa como criar um objeto de um tipo específico.” (SIERRA & BATES, 2007) Permitindo assim *armazenar propriedades e métodos* dento dela.
<hr>

# Instância: 
instância é cada objeto criado a partir de uma classe.
<hr>

# Atributos: 
Os atributos são os elementos que definem a estrutura de um classe. Também conhecidos como **variáveis** de classe, e podem ser divididos em **dois tipos básicos: atributos de instância e de classe**. Os valores dos atributos de **instância** determinam o **estado** de cada classe. Um atributo de **classe** possui um estado que é **compartilhado** por todos os objetos de uma classe.
<hr>

# Métodos: 
Um método é uma **sub-rotina** que é **executada por um objeto ao receber uma mensagem** (chamada de métodos).
Os métodos **determinam o comportamento dos objetos de uma classe e são semelhante a funções** ou procedimentos de programação estruturada. O **envio de mensagens pode alterar o estado do objeto**. 

**São ações daquela determinada classe**
<hr>

<center><h1> Exemplo <h1></center>

### Vamos usar algo que exista no mundo Real, Gato.
Gatos são coisas que nós temos no mundo real, e nós podemos produzir alguma aplicação que lide com gatos...
<hr>

<center><h1>🐈</h1></center>

Nós podemos afirmar que os elementos do mundo real possuem basicamente dois tipos de informação: **Características e Ações**.

**Características**: cor dos olhos, cor dos pelos, tamanho das unhas, nome do gato, peso, idade...

**Ações**: comer, dormir, miar, passear, escalar...

<hr>

Nós precisamos, de alguma maneira, **representar** que um gato pode possuir **características** como cor dos olhos e cor dos pelos, e também pode executar **ações** como comer e miar. Essa **representação** deve ocorrer em nosso código para que possamos ter um código de fato **Orientado a Objetos**.

Nós podemos fazer essa representação através de **classes**. Neste caso, nós podíamos definir que **Gato seria uma classe** de nossa aplicação. Uma classe **sempre** vai conter características e/ou ações, que ajudam a definir melhor o que a classe em questão representa.

Quando estamos falando de classes, **características e ações são chamados O código pode ser redundante por inúmeras razões que vão desde variáveis não utilizadas, passando por alterações não concluídas e até mesmo código desenvolvido e abandonado. O código redundante tem uma série de consequências, incluindo código fonte inchado, redução de capacidade de manutenção e confiabilidade reduzidatecnicamente de Atributos e Métodos**. Neste exemplo, a classe Gato teria, por exemplo, os atributos cor dos olhos; além de possuir o método dormir.

<hr>

# SOLID

São cinco princípios da programação orientado a objeto que facilitam no desenvolvimento de software, tornando-os fáceis de manter e estender. 

<hr>

## S.O.L.I.D | Os 5 princípios de POO

1. **S** - *Single Responsiblity Principle*
(Princípio da Responsabilidade Única)

2. **O** - *Open-Closed Principle*
(Princípio Aberto-Fechado)

3. **L** - *Liskov Substitution Principle*
(Princípio da Substituição de Liskov)

4. **I** - *Interface Segregation Principle*
(Princípio da Segregação da Interface)

5. **D** - *Dependency Inversion Principle*
(Princípio da Inversão da Dependência)
<hr>

Esses princípios ajudam o programador a escrever códigos mais limpos, separando responsabilidades, diminuindo acoplamentos, facilitando na refatoração e estimulando o reaproveitamento do código.

<hr>

## 1. SRP → Single Responsibility Principle:
Princípio da responsabilidade única - **Uma classe deve ter um, e somente um, motivo para mudar**.

Esse princípio declara que uma classe deve ser especializada em um único assunto e possuir apenas uma responsabilidade dentro do software, ou seja, a classe deve ter uma única tarefe ou ação para executar.

**God Class** - Classe Deus: Na programação orientado a objeto, é uma classe que sabe demais ou faz demais.

### Exemplo:

```python
class AtendenteLoja:
   
   def __init__(self):
      pass


   def atender_cliente(self):
      pass


   def calcular_produtos(self):
      pass


   def limpar_loja(self):
      pass


   def mostrar_produtos(self):
      pass


   def consertar_parede(self):
      pass

```
A classe AtendenteLoja viola o SRP porque realiza 3 tipos distintos de tarefas. Além de lidar com as informações do pedido, ela também é responsável pela exibição e manipulação dos dados. Lembre-se, o princípio da responsabilidade única preza que uma classe deve ter um, e somente um, motivo para mudar.

A violação do Single Responsibility Principle pode gerar alguns problemas, sendo eles:

* Falta de coesão — uma classe não deve assumir responsabilidades que não são suas;
* Alto acoplamento — Mais responsabilidades geram um maior nível de dependências, deixando o sistema engessado e frágil para alterações;
* Dificuldades para reaproveitar o código;

Aplicando o SRP na classe AtendenteLoja, podemos refatorar o código da seguinte forma:

```python
class AtendenteLoja:

   def __init__(self):
      pass


   def atender_cliente(self):
      pass


   def mostrar_produtos(self):
      pass


class Caixa:

   def __init__(self):
      pass


   def calcular_produtos(self):
      pass


class Faxineiro:

   def __init__(self):
      pass


   def limpar_loja(self):
      pass


class Pedreiro:

   def __init__(self):
      pass


   def consertar_parede(self):
      pass
```

Perceba no exemplo acima que agora temos 4 classes, cada uma cuidando da sua responsabilidade.

O princípio da responsabilidade única não se limita somente a classes, ele também pode ser aplicado em métodos e funções, ou seja, tudo que é responsável por executar uma ação, deve ser responsável por apenas aquilo que se propõe a fazer.

Considero o SRP um dos princípios mais importantes, ele acaba sendo a base para outros princípios e padrões porque aborda temas como acoplamento e coesão, características que todo código orientado a objetos deveria ter.

<hr>

## 2. OCP → Open-Closed Principle

Princípio Aberto-Fechado — **Objetos ou entidades devem estar abertos para extensão, mas fechados para modificação**, ou seja, quando novos comportamentos e recursos precisam ser adicionados no software, devemos estender e não alterar o código fonte original.

Exemplo prático do OCP:

```python
from typing import Type

class ContratoClt:

   '\...'

   def salario(self):
      return 4000


class Estagio:

   '\...'

   def bolsa_auxilio(self):
      return 500


class FolhadePagemento:

   def __init__(self, saldo: float):
      self._saldo = saldo


   def calculo(self, funcionario: Type[Estagio]):
      try:
         self._saldo = self._saldo - funcionario.bolsa_auxilio()
      except:
         self.__calculo1(funcionario)


   def __calculo1(self, funcionario: Type[ContratoClt]):
      self._saldo = self._saldo - funcionario.salario()

```

A classe FolhaDePagamento precisa verificar o funcionário para aplicar a regra de negócio correta na hora do pagamento. Supondo que a empresa cresceu e resolveu trabalhar com funcionários PJ, obviamente seria necessário modificar essa classe! Sendo assim, estaríamos quebrando o princípio Open-Closed do SOLID.

### Qual o problema de se alterar a classe FolhaDePagamento?

Não seria mais fácil apenas acrescentar mais uma condição e verificar o novo tipo de funcionário PJ aplicando as respectivas regras? Sim. Mas, esse é exatamente o problema! Alterar uma classe já existente para adicionar um novo comportamento, corremos um sério risco de introduzir bugs em algo que já estava funcionando.

*Como adicionamos um novo comportamento sem alterar o código fonte já existente?*

O guru Uncle Bob resumiu a solução em uma frase:

Separe o comportamento extensível por trás de uma interface e inverta as dependências.

O que devemos fazer é concentrar nos aspectos essências do contexto, abstraindo-os para uma interface. Se as abstrações são bem definidas, logo o software estará aberto para extensão.

**Aplicando OCP na prática**

Voltando para o nosso exemplo, podemos concluir que o contexto que estamos lidando é a remuneração dos contratos de trabalho, aplicando as premissas de se isolar o comportamento extensível atrás de uma interface, podemos criar uma interface com o nome Remuneravel contendo o método remuneracao(), e fazer com que nossas classes de contrato de trabalho implementem essa interface. Além disso, iremos colocar as regras de calculo de remuneração para suas respectivas classes, dentro do método remuneracao(), fazendo com que a classe FolhaDePagamento dependa somente da interface Remuneravel que iremos criar.

**Código refatorado abaixo**

```python
from abc import ABC, abstractmethod
from typing import Type


class InterfaceRemuneracao(ABC):

   @abstractmethod
   def remuneracao(self):
      pass


class ContratoClt(InterfaceRemuneracao):

   def remuneracao(self):
      return 1000


class Estagio(InterfaceRemuneracao):

   def remuneracao(self):
      return 500


class FolhadePagemento:

   def __init__(self, saldo: float):
      self._saldo = saldo


   def calcular(self, funcionario: Type[InterfaceRemuneracao]):
      self._saldo = self._saldo - funcionario.remuneracao()

```

Agora a classe FolhaDePagamento não precisa mais saber quais métodos chamar para calcular. Ela será capaz de calcular o pagamento corretamente de qualquer novo tipo de funcionário que seja criado no futuro (ContratoPJ) — desde que ele implemente a interface Remuneravel — sem qualquer necessidade de alteração do seu código fonte. Dessa forma, acabamos de implementar o princípio de Aberto-Fechado do SOLID em nosso código!

<hr>

## 3. LSP → Liskov Substitution Principle

Princípio da substituição de Liskov — Uma classe derivada deve ser substituível por sua classe base.

se S é um subtipo de T, então os objetos do tipo T, em um programa, podem ser substituídos pelos objetos de tipo S sem que seja necessário alterar as propriedades deste programa. — Wikipedia.

**Exemplo**

```python

class A:

   '\...'

   def getnome(self) -> str:
      return 'Meu nome é A'

class B(A):
    '\...'

    def getnome(self) -> str:
        return 'Meu nome é B'

obj1 = A()
obj2 = B()

def mostrarnome(nome: Type[A]):
   return nome.getnome()


mostrarnome(obj1) # Meu nome é A
mostrarnome(obj2) # Meu nome é B
```
Exemplos de violação do LSP:

* Sobrescrever/implementar um método que não faz nada;
* Lançar uma exceção inesperada;
* Retornar valores de tipos diferentes da classe base;


Estamos passando como parâmetro tanto a classe pai como a classe derivada e o código continua funcionando da forma esperada.

Seguir o LSP nos permite usar o polimorfismo com mais confiança. Podemos chamar nossas classes derivadas referindo-se à sua classe base sem preocupações com resultados inesperados.

Para não violar o Liskov Substitution Principle, além de estruturar muito bem as suas abstrações, em alguns casos, você precisara usar a injeção de dependência e também usar outros princípios do SOLID, como por exemplo, o Open-Closed Principle e o Interface Segregation Principle
<hr>

## 4. ISP → Interface Segregation Principle

Princípio da Segregação da Interface — Uma classe não deve ser forçada a implementar interfaces e métodos que não irão utilizar.

Esse princípio basicamente diz que é melhor criar interfaces mais específicas ao invés de termos uma única interface genérica.

**Exemplo**

```python
from abc import ABC, abstractmethod

class InterfaceAves(ABC):

    '\...'

    @abstractmethod
    def setlocalizacao(self, longitude, latitude):
        pass


    @abstractmethod
    def setaltitude(self, altitude):
        pass


    @abstractmethod
    def renderizar(self):
        pass


class Papagaio(InterfaceAves):

    def setlocalizacao(self, longitude, latitude):
        return 'faz alguma coisa'


    def setaltitude(self, altitude):
        return 'faz alguma coisa'


    def renderizar(self):
        return 'faz alguma coisa'


class Pinguim(InterfaceAves):

    '\...'

    def setlocalizacao(self, longitude, latitude):
        return 'faz alguma coisa'


    # A Interface Aves está forçando a Classe Pinguim a implementar esse método.
    # Isso viola o príncipio ISP
    def setaltitude(self, altitude):
        return 'Não faz nada...  Pinguins são aves que não voam!'


    def renderizar(self):
        return 'faz alguma coisa'

```

Percebam que ao criar a interface Aves, atribuímos comportamentos genéricos e isso acabou forçando a classe Pinguim a implementar o método setAltitude()do qual ela não deveria ter, pois pinguins não voam! Dessa forma, estamos violando o Interface Segregation Principle — E o LSP também!

**Para resolver esse problema, devemos criar interfaces mais específicas**

```python
from abc import ABC, abstractmethod

class InterfaceAves(ABC):

    @abstractmethod
    def setlocalizacao(self, longitude, latitude):
        pass


    @abstractmethod
    def renderizar(self):
        pass


class InterfaceAvesQueVoam(InterfaceAves):

    @abstractmethod
    def setaltitude(self, altitude):
        pass


class Papagaio(InterfaceAvesQueVoam):

    '\...'

    def setlocalizacao(self, longitude, latitude):
        return 'faz alguma coisa'


    def setaltitude(self, altitude):
        return 'faz alguma coisa'


    def renderizar(self):
        return 'faz alguma coisa'


class Pinguim(InterfaceAves):

    '\...'

    def setlocalizacao(self, longitude, latitude):
        return 'faz alguma coisa'


    def renderizar(self):
        return 'faz alguma coisa'

```

No exemplo acima, retiramos o método setaltitude() da interface Aves e adicionamos em uma interface derivada InterfaceAvesQueVoam. Isso nos permitiu isolar os comportamentos das aves de maneira correta, respeitando o princípio da segregação das interfaces.
<hr>

## 5. DIP → Dependency Inversion Principle

Princípio da Inversão de Dependência — Dependa de abstrações e não de implementações.

De acordo com Uncle Bob, esse princípio pode ser definido da seguinte forma:

1. Módulos de alto nível não devem depender de módulos de baixo nível. Ambos devem depender da abstração.

2. Abstrações não devem depender de detalhes. Detalhes devem depender de abstrações.

<hr>
Importante: Inversão de Dependência não é igual a Injeção de Dependência, A Inversão de Dependência é um princípio (Conceito) e a Injeção de Dependência é um padrão de projeto (Design Pattern).
<hr>

**Exemplo**

```python
class ConectarBanco:
   '\...'

class MudarSenha:

   def __init__(self, senha_antiga: str, nova_senha: str):
      self.__senha_antiga = senha_antiga
      self.__nova_senha = nova_senha
      self.conect = ConectarBanco()

   def mudar_senha(self):
      '\faz alguma coisa'
   
```
Para recuperar a senha, a classe MudarSenha, precisa conectar na base de dados, por tanto, ela cria um instância da classe ConectarBanco em seu método para realizar as respectivas operações.

Nesse código temos um alto nível de acoplamento, isso acontece porque a classe 
MudarSenha tem a responsabilidade de criar uma instância da classe ConectarBanco! Se quiséssemos reaproveitar essa classe em outro sistema, teriamos obrigatoriamente de levar a classe ConectarBanco junto, portanto, temos um acoplamento aqui.

Para resolver esse problema de acoplamento, podemos refatorar nosso código da seguinte forma
```python
from typing import Type
from abc import ABC

class ConectarBanco(ABC):
   pass

class MySQLConectar(ConectarBanco):
   pass

class OracleConectar(ConectarBanco):
   pass


class MudarSenha:

   def __init__(self, antiga_senha, nova_senha, dbconect: Type[ConectarBanco]):
      self.__dbconect = dbconect

   def mudar_senha(self):
      '/Faz alguma coisa'

```
Agora a classe MudarSenha não tem a mínima ideia de qual banco de dados a aplicação irá utilizar. Dessa forma, não estamos violando o DIP, ambas as classes estão desacopladas e dependendo de uma abstração. Além disso, estamos favorecendo a reusabilidade do código e também estamos respeitando o SRP e o OCP.

## Conclusão

A sistemática dos princípios SOLID tornam o software mais robusto, escalável e flexível, deixando-o tolerante a mudanças, facilitando a implementação de novos requisitos para a evolução e manutenção do sistema.

## Referência:
* [Solid - php](https://medium.com/desenvolvendo-com-paixao/o-que-%C3%A9-solid-o-guia-completo-para-voc%C3%AA-entender-os-5-princ%C3%ADpios-da-poo-2b937b3fc530)