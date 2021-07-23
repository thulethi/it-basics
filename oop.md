##OOP (Object Oriented Programming)

1. In chosen language, create a separate project with a class structure as follows:
    1. class Animal
    2. classes Bird, Mammal, Fish - inherited from Animal
    3. classes Flamingo, Eagle - inherited from Bird
    4. classes Cat, Dog - inherited from Mammal
    5. classes Salmon - inherited from Fish

Animal has:
  - members:
      - weight

Bird has:
- members:
    - length of wings
- methods:
    - move (it should delegate to fly)
    - fly (prints “I’m flying”)

Mammal has:
- members:
    - color
- methods:
    - move (it should delegate to walk)
    - walk (prints “I’m walking”)

Fish has:
- methods:
    - move (it should delegate to swim)
    - swim (prints “I’m swimming”)

Flamingo and Eagle have:
- methods:
    - sayHello (“Brraa brra” - flamingo, “Wrrree wrree” - eagle)

Cat and Dog have:
- methods:
    - sayHello (“Miau miau” - cat, “Gau gauu” - dog)

Salmon has:
- methods:
    - sayHello (“Splash splash”)

Create a list of animals (instances/objects of appropriate classes), such as:

    cat1 = Cat.new
    dog1 = Dog.new
    ....
    list = [ cat1, dog1, cat2, flamingo1, salmon1, eagle1 ]

In a loop try to use sayHello and move methods for each animal.

Answer the questions:
a) - If we have swim/fly/walk methods, why do we need method move?
b) - Can we use swim/fly/walk methods in the loop
c) - Can we create objects (=instances) of classes Bird, Mammal, Fish, Animal? If yes, is it correct?

Draw an UML class diagram describing the inheritance structure.

Read about:
- duck typing
- polymorphism in OOP
- abstract class, abstract method (in statically typed OOP languages, such as Java)
