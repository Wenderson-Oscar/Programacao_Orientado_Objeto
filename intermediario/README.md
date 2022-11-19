<center><h1> PILARES DE POO <h1><center>

# Abstração

Consiste em esconder os detalhes de algo, no caso, os detalhes desnecessários. As vezes chamamos métodos que não precisamos saber todos so processo que ele faz. Passamos um parâmetro e ele nos retorna algo. Isso deixa o código limpo e mais compreensível.

# Encapsulamento 

Serve para controlar o acesso aos atributos e métodos de uma classe. è uma foma eficiente de proteger os dados manipulados dento da classe. Usa-se o __ para 'privatizar' (Python).
Para chamar conseguirmos acessar o atributos devemos usar os métodos Getters e Setters.

# Herança 

Criamos classes a partir de outras classes. herdando todos os atributos e métodos dela essas novas classes são chamadas de subclasses, ou classes derivadas. Assim evitamos a redundância de código (O código pode ser redundante por inúmeras razões que vão desde variáveis não utilizadas, passando por alterações não concluídas e até mesmo código desenvolvido e abandonado. O código redundante tem uma série de consequências, incluindo código fonte inchado, redução de capacidade de manutenção e confiabilidade reduzida ). Classe Homem herda todos as caracteristicas de Pessoa + as caracteristicas dele mesmo.

# Polimorfismo

Onde duas ou mais classes derivadas de uma mesma superclasse (conceito de herança ) podem invocar métodos que têm a mesma identificação mas comportamento distintos. A Classe Homem herda o método falar da classe pessoa. porem a forma de falar é diferente.
