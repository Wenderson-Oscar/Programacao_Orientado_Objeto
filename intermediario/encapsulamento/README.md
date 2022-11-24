# Encapsulamento 

Serve para controlar o acesso aos atributos e métodos de uma classe. è uma forma eficiente de proteger os dados manipulados dento da classe. Usa-se o __ para 
'privatizar' (Python) e _ para proteção.
os atributos privados não são realmente privados, mas "desconfigurados", pode ler e atribuir um valor ao atributo "privado" diretamente.

O conceito de polimorfismo está associado à herança. O polimorfismo trabalha com a redeclaração de métodos previamente herdados por uma classe. 

Para chamar, conseguirmos acessar o atributos devemos usar os métodos Getters e Setters.

Muitas das linguagens orientadas a objetos implementam o encapsulamento baseado em propriedades privadas, por métodos chamados getters e setters, responsáveis por retornar e setar o valor da propriedade, respectivamente. Assim, se evita o acesso direto à propriedade do objeto, adicionando outra camada de segurança à aplicação.

Em um processo de encapsulamento os atributos das classes são do tipo private. Para acessar esses tipos de modificadores, é necessário criar métodos setters e getters.

Por entendimento os métodos setters servem para alterar a informação de uma propriedade de um objeto. E os métodos getters para retornar o valor dessa propriedade.

# Métodos setter e getter

### Métodos setter: 
usados para alterar ou inserir valores nos membros de dados.
ex: setNome(), setIdade()

### Métodos getter: 
usados para Ler valores armazenados nos objetos.
ex: getNome(), getIdade()

os métodos set tem que ter passar parametros.

Como regra, um objeto so pode ter seus dados manipulados com o uso de setters e getters especificados.