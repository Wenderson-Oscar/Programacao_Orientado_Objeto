## @Property

@property é o decorador que indica que o método abaixo vai aparecer uma propriedade. (GET)

property é você utilizar um decoration para usa o **método em uma propriedade**.

Property é utilizar para trasforma um método em uma propriedade. O objeto property possui métodos getter, setter, e deleter usáveis como decoradores, que criam uma cópia da property com o assessor correspondente a função definida para a função com decorador.

@staticmethod são métodos estáticos, que não são necessários declarar aquele primeiro argumento self pois não fará uso de nenhum recurso da classe diretamente.
<hr>

## Por Que usar o Property? 

R: Quando precisar fazer alguma validação nos dados, entre outras coisas, assim quando eu fizer essa auteração ele chame o método é ele vai verificar se esse dado é válido.
<hr>

### OBS:

quando se usa property o nome das funções podem ser iguais. (**apenas quando estamos usando o property**).

O nome do método tem que ser o mesmo nome da propriedade.

Usando property, podemos ver que nenhuma modificação é necessária na implementação da restrição de valor. 

Basicamente o staticmethod é uma função de uma classe que interage de alguma forma com o objeto, ela poderia estar solta no código, mas por fim de organização e manutenção colocamos ela na classe.
