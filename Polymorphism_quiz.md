Polymorphism
What does the word 'polymorphism' mean?
to transform or change

What does it mean when we apply polymorphism to OO design? Give a simple Java example.
Java has strict arrays, meaning only objects specified can be listed, polymorphism allows other objects to be recognised and that specified, an efficient way to do this is via an interface.

What can we use to implement polymorphism in Java?
an interface.

How many 'forms' can an object take when using polymorphism?
2 - 3, the original form of the object, the parent object (if original is a child/inherited) and that of the interface.

Give an example of when you could use polymorphism.
to store a collection of shapes, where each shape type (circle, sqare, triangle) has it's own class, we can use polymorphism to change them into shapes so they can be stored in 1 array.

Composition and Aggregation
What do we mean by 'composition' in reference to object-oriented programming?
to reference an object within another object.

When would you use composition? Provide a simple example in Java.
take a car object, the car has an engine which is it's own object, the car class can use the enginges functions without taking them on as it's own.

Give a difference between composition and aggregation?
aggregation means that one object is the owner of another, and therefore cannot exist without it. composition means that one object can be contained in another without ownership

What is/are the advantage(s) of using composition/aggregation?
composition allows multiple objects to come together to create 1 eseentially, meaning that functions don't need to be re-written or duplicated but also allows simplified changes. aggregation entails that all functions are passed over, even those not needed and also creates reliance on other objects.

When using composition, when an object is destroyed, what happens to all the objects it is composed of?
if the destroyed object is the parent then all child objects will cease to function.

When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?
the remaining objecets will continue to function and can be used elsewhere.
