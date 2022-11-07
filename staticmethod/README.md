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