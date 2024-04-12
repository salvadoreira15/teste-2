# teste-2
1- public
2-
3-V
4-F
5-F
6-V

Exercicio 2
1- 
Animal animal = new Cao(); - válido porque 
Gato gato = new Cao(); - inválido porque gato é animal e nao cao                                       
Gato gato = new Animal() ; - válido porque gato é animal
a.Ladrar(); // 'a' é uma instância de Animal - inválido porque "a" é instancia de Cao
c.Comer(); // 'c' é uma instância de Cao - inválido porque  "c" é  instancia de Animal
float x = g.Energia; // 'g' é uma instância de Gato - inválido porque "g" é instancia de Animal
Console.WriteLine(g.Nome); // 'g' é uma instância de Gato - inválido porque "g é instancia  de Animal
