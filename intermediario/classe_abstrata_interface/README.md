# Classe Abstrata

É um tipo de classe especial que **não pode ser instanciada**, apenas herdada. Sendo assim, uma classe abstrata não pode ter um objeto criado a partir de sua instanciação. Essas classes são muito **importantes quando não queremos criar um objeto a partir de uma classe “geral”**, apenas de suas “subclasses”.


    Uma classe abstrata cria uma interface comum para um conjunto de subclasses, reduzindo código duplicado e obrigando as subclasses a implementarem todos seus métodos abstratos.

Como funcionam as Class Abstract Base:

    Por padrão, o Python não fornece classes abstratas. O Python vem com um módulo que fornece a base para definir as Class Abstract Base (ABC) e o nome do módulo é ABC.

    O ABC funciona decorando métodos da classe base como abstratos e, em seguida, registrando classes concretas como implementações da base abstrata. Um método se torna abstrato quando decorado com a palavra-chave @abstractmethod.

   As classes abstratas devem conter pelo menos um método abstrato, que não tem corpo.

·         É um tipo especial de classe que não há como criar instâncias dela.

·         É usada apenas para ser herdada, funciona como uma super classe.

·         Uma grande vantagem é que força a hierarquia para todas as sub-classes.

·         É um tipo de contrato que faz com que as sub-classes contemplem as mesmas hierarquias e/ou padrões. 

# StaticMethod
<hr>

## Conceito do static
Um método estático dentro de uma classe indica que este método pode ser invocado sem a necessidade de que você tenha uma instância desta classe(método da classe).

O método estático são métodos que não dependem de um objeto.

"Um método estático pertence a uma classe; ainda assim, não está vinculado ao objeto dessa classe. Como os métodos estáticos não estão vinculados a um objeto, ele não conhece as propriedades de uma classe, portanto não pode acessar ou modificar as propriedades de a classe"

Assim como em métodos static também podemos ter variaveis static.

variavel static é uma variavel que podemos acessar atraves da classe, assim não precisamos criar um objetos para acessa essa variavel.
<hr>

## Usos do static
Em geral, esse modificador **é usado pra métodos que criam e retornam instâncias da própria classe**, no padrão singleton, mas podem ter outros usos.

Geralmente utilizados quando você tem uma função que executa lógica que interage com o objeto/classe, aí você pode criar um staticmethod com este intuito.

Basicamente o staticmethod é uma função de uma classe que interage de alguma forma com o objeto, ela poderia estar solta no código, mas por fim de organização e manutenção colocamos ela na classe.

<hr>

# Interface

Em Python usarmos a classe abstrata como uma interface formal.

    Uma interface formal funcionará como uma espécie de contrato, obrigando suas subclasses a implementar seus métodos.
    A interface informal será bastante parecida com uma classe Python comum. Ela poderá definir métodos que posteriormente serão sobrescritos, mas não há obrigatoriedade para tal.


Uma interface não é considerada uma Classe e sim uma Entidade.

·         Não possui implementação, apenas assinatura, ou seja, apenas a definição dos seus métodos sem o corpo.

·         Todos os métodos são abstratos.

·         Seus métodos são implicitamente Públicos e Abstratos.

·         Não há como fazer uma instância de uma Interface e nem como criar um Construtor.

·         Funcionam como um tipo de "contrato", onde são especificados os atributos, métodos e funções que as classes que implementem essa interface são obrigadas a implementar.