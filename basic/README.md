# Relacionamento 

Associação entre objetos

Atributos de um objetos que se refere a outro atributo definido na classe.


# Associação
Ela descreve um vínculo que ocorre entre classes - associação binária -, mas é possível até mesmo que uma classe esteja vinculada a si própria, - associação unária-, ou que uma associação seja compartilhada por mais de uma classe, o que conhecemos por associação ternária ou N-ária, tipo de associação mais rara e também mais complexa. Representamos as associações por meio de retas que ligam as classes envolvidas, essas setas podem ou não possuir setas nas extremidades indicando a navegabilidade da associação, ou seja, o sentido em que as informações são passadas entre as classes - não obrigatório-. Ou seja, se não há setas, significa que essas informações podem ser transmitidas entre todas as classes de uma associação.

# Agregação
É um tipo especial de associação onde tenta-se demonstrar que as informações de um objeto (chamado objeto-todo) precisam ser complementados pelas informações contidas em um ou mais objetos de outra classe (chamados objetos-parte); conhecemos como todo/parte.

O objeto-pai poderá usar as informações do objeto agregado. Segundo Dall'Oglio (2007) "Nesta relação, um objeto poderá agregar uma ou mais instâncias de um outro objeto. Para agregar muitas instâncias, a forma mais simples é utilizando arrays. Criamos um array como atributo da classe, sendo que o papel deste array é armazenar inúmeras instâncias de uma outra class". (DALL'OGLIO, 2007, p. 118)

# Composição
Pode-se dizer que composição é uma variação da agregação. Uma composição tenta representar também uma relação todo - parte. No entanto, na composição o objeto-pai (todo) é responsável por criar e destruir suas partes. Em uma composição um mesmo objeto-parte não pode se associar a mais de um objeto-pai.

# Metodo Construtor(__init__): 
é aquele método que sera executa apenas uma unica vez, ele sera executado quando a class for chamada. E nele que seram passsados os atributos do objetos.

definimos um método especial chamado _ _init_ _ . Métodos nada mais são
que funções associadas a uma classe. O método _ _init_ _ será chamado sempre
que criarmos objetos da classe

Um método construtor é chamado sempre que um objeto da classe
é instanciado.

# self

Os métodos de classe têm apenas uma diferença específica das funções comuns - eles devem ter um primeiro nome extra que deve ser adicionado ao início da lista de parâmetros, mas você não atribui um valor para esse parâmetro ao chamar o método, o Python fornecerá isto. Essa variável em particular se refere ao próprio objeto e, por convenção, recebe o nome de self.

Embora você possa fornecer qualquer nome para esse parâmetro, é altamente recomendável usar o nome self - qualquer outro nome é definitivamente desaprovado.
O método _ _init_ _ recebe um parâmetro chamado self , Entenda self como o objeto em si.s

<hr>

# OBS:

#### Os nomes da classe sempre começa com Maisculo
<hr>

#### Nomes das funções sempre Minusculas e de entedimento claro
<hr>

Aviso: 
#### È **Recomendado** que Toda Class Tenha um Método Construtor

#### os métodos são passados atraves de função.