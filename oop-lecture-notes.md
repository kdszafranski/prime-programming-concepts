# Object Oriented Programming


Abstraction and encapsulation are complementary concepts: abstraction focuses on the observable behavior of an object... encapsulation focuses upon the implementation that gives rise to this behavior... encapsulation is most often achieved through information hiding, which is the process of hiding all of the secrets of object that do not contribute to its essential characteristics.
In other words: abstraction = the object externally; encapsulation (achieved through information hiding) = the object internally

in other words:

Abstraction, information hiding, and encapsulation are very different, but highly-related, concepts. One could argue that abstraction is a technique that help us identify which specific information should be visible, and which information should be hidden. Encapsulation is then the technique for packaging the information in such a way as to hide what should be hidden, and make visible what is intended to be visible.


## Encapsulation

Encapsulation is the process of combining data and functions into a single unit called class. In Encapsulation, the data is not accessed directly; it is accessed through the functions present inside the class. In simpler words, attributes of the class are kept private and public getter and setter methods are provided to manipulate these attributes. Thus, encapsulation makes the concept of data hiding possible.

**Examples**

This object combines (encapsulates) various pieces of data together in a single entity.

```
var person = {
  name: 'Kris',
  occupation: 'Instructor',
  speak: function() {
    return "Hello, my name is " + this.name
  }
}
```


## Abstraction

Abstraction is one of three central principles (along with encapsulation and inheritance). Through the process of abstraction, a programmer hides all but the relevant data about an object in order to reduce complexity and increase efficiency.

It works by establishing a level of complexity on which a person interacts with the system, suppressing the more complex details below the current level.

Abstraction is a process where you show only “relevant” data and “hide” unnecessary details of an object from the user. Consider your mobile phone, you just need to know what buttons are to be pressed to send a message or make a call, What happens when you press a button, how your messages are sent, how your calls are connected is all abstracted away from the user.


**Example**

jQuery abstracts selection with `$('h1')` from it's more complex underlying DOM API `document.getElementsByTagName("H1")`


## Inheritance




## [Polymorphism](http://stackoverflow.com/questions/1031273/what-is-polymorphism-what-is-it-for-and-how-is-it-used)

Polymorphism is the ability (in programming) to present the same interface for differing underlying forms (data types). Consider the `Shape.Draw()` usage vs `drawCircle()` and `drawRectangle()`
