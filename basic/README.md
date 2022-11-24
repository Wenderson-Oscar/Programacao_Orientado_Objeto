# Relacionamento 

Associação entre objetos.

Atributos de um objetos que se refere a outro atributo definido na classe.


# Associação
**Ela descreve um vínculo que ocorre entre classes**.

# Agregação
É um tipo especial de associação onde tenta-se demonstrar que **as informações de um objeto (objeto-todo) precisam ser complementados pelas informações contidas em um ou mais objetos de outra classe** (objetos-parte).

# Composição
Pode-se dizer que composição é uma **variação da agregação**. Na composição o objeto-pai (todo) é responsável por **criar e destruir suas partes**. 

# Diferença entre Agregação e Composição
**Composição** é quando o objeto "filho" não faz sentido fora do objeto "pai". **Agregação** é quando o objeto filho existe sem o objeto pai, mas agrega informações a ele. 

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