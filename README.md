<h1 align ='center'> Programação Orientado a Objeto</h1>

### O intuito da criação desse projeto foi estudar e praticar POO usando python, afim de agregar um conhecimento solido. obs: O seguinte tutorial estar de acordo com a minha perspectiva de estudo em relação ao tema.

Menu
=================
<!--ts-->
   * [Tecnologias utilizadas](#🛠-tecnologias)
   * [Guia do Projeto](#guia-do-projeto)
      * [Teoria POO](#o-que-é-programação-orientada-a-objetos)
      
<!--te-->

## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- 🔗 [Python 3.8](https://python.org/)
- 🔗 [Visual Code](https://code.visualstudio.com/)
- 🔗 [Extension Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)

# Guia do Projeto

É Recomendado ler **todos os README primeiro** de cada pasta nesse projeto.
Seguimos com a Teoria que esta nesse Readme, assim aprendemos um pouco o que é POO(nessa parte ainda não abordamos os 4 Pilares), ao termos passado pela Teoria iremos para a pratica, que é no arquivo "basic".

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
