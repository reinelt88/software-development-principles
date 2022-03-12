# Software Development Principles
Most common software development principles.

## 1. Keep It Simple Simon
**Keep It Simple, Stupid (KISS)**

As you code your next big project, ensure your programming is simple and clear to understand. The code shouldn’t give human beings difficulties when modifying or changing it.

» Your methods need to be small, not exceeding 40-50 lines.

» Each method should solve only one problem.

» Do you have a lot of conditions in your project? Make sure you’ve broken them down into smaller blocks of codes.

Always Keep It Simple, Stupid (KISS) allows you and fellow programmers to identify bugs quickly. It also helps you modify and make further changes to the code. It is one of the most common lean principles in agile software engineering.

## 2. You Aren't Gonna Need It (YAGNI)

**You Aren't Gonna Need It (YAGNI)**
Most programmers fall into the pit of trying to implement all the functionalities at once, from the word go. In the end, some or most of these functionalities become useless.

As an upcoming software developer, always start by adding just a few methods to a class. After that, as your project starts taking shape and new demands arise, you can add more functionalities. That way, you’ll achieve a lean development software.

YAGNI saves time, efforts, and costs that you would have wasted in trying to understand or debug the code.

## 3. Measure Twice and Cut Once

**Measure Twice and Cut Once Software Development Principles**
The development life cycle’s requirement stage usually introduces more than 50% coding issues if not done well. Therefore, be prepared by developing a systematic approach to the coding process.

Double-check all the project’s requirements to ensure you don’t leave out or add too much in your code. After that, make blueprints that will guide the whole process to achieve high-quality coding throughout. Always test your project from the word go to ensure everything is fine.

This principle gives much more predictable outcomes, especially if the project’s cost is already high. You’ll save yourself headaches that come with deleting or adding code lines to meet requirements.

## 4. Don’t Repeat Yourself (DRY)
**Don’t Repeat Yourself (DRY)**

When writing your code, don’t repeat yourself. That is, avoid copy-pasting your code in different places. Otherwise, future maintenance will be difficult. The reason is that you will have to make changes to the coding in those various places.

Those changes will further necessitate changes in the tests to make the results click green. All of that will need more time, effort, and money.

To avoid such a pitfall, you can extract a common logic into functions.

Additionally, if there are any manual works that you can automate, do so to keep your code lean.

For software development, the above steps will help in the code re-usability without having to repeat it.

We build custom software with modern solutions in mind for any business and sizes!

## 5. Occam's Razor
William Occam was a 14th Century philosopher that coined this principle. It states that in a group of hypotheses, always select the one that has the fewest assumptions.

In keeping up with the Lean Software Development, always start with the most straightforward possible code. Then carefully add the more complex ones only when they’re necessary.

Simple codes allow you to easily envision, develop, test, and correct the product at every step. They also significantly reduce bugs and will enable the program to run faster.

## 6. Big Design Up Front (BDUF)
This software engineering principle affirms that a developer should complete the project’s design first. After that, they can now implement it.

Proponents argue that this helps in discovering issues at the requirements stage and solving them quickly.

However, changes in the software requirements may occur during the project’s life cycle. Such changes may cause difficulties or even render the design code obsolete.

One way to solve this is to have the general architecture first. Then divide the requirements into several stages according to priorities. During the development process, start with the highest to the lowest priority stage. At every step, implement the BDUF principle before the actual coding process.

## 7. Avoid Premature Optimization
Donald Knuth asserted that the root of all evil in programming is premature optimization.

We all agree that optimization speeds up the development process and reduce resource consumption. However, if you do it too early, it may backfire.

The reason is that prioritizing a code is time-consuming and complicated if not done at the right stage. Additionally, when you are implementing the most optimal approach, software requirements may change. If that happens, your program ends up in a dustbin or become difficult to change.

Therefore, start with the easiest approach, even if it is not the most optimal. Then in the future, assess the chosen method in terms of resource and time consumption. Based on your assessment, you can move onto a faster algorithm that consumes fewer resources or efforts.

## 8. Least Astonishment
The principle of least astonishment says that it is advisable to design a feature that doesn’t have a high-astonishment factor.

Your system’s components should behave in a way that end-users expect. Therefore, your project’s outcomes will be profitable only if they are obvious, predictable, and consistent. Otherwise, users will shy from using features or structures that astonish, surprise, or confuse them.

You are making software products for people to use. Thus, you’ll reap a lot by designing user-friendly features. Strive to match human beings’ mental models, experience, and expectations.

Remember, you have to capture the user’s attention as quickly as possible. As we know, the current users’ attention span has plummeted.

## 9. Demeter
The law of Demeter attempts to divide responsibilities between classes and reduce coupling between them. The idea comes from the “only talk to your friends” idiom.

It is highly recommendable to:

» Keep software entities independent of each other. 

» Reduce the communication or coupling between different classes.

» Put related classes in the same package, module or directory to achieve cohesion.

Following this idea allows your application to be more maintainable, understandable, and flexible.

## 10. S.O.L.I.D
It is an acronym that stands for five object-oriented programming and design principles.

**» S- Single Responsibility Principle (SRP)**

**» O- Open/Closed Principle (OCP)**

**» L- Liskov Substitution Principle**

**» I-Interface Segregation Principle**

**» D- Dependency Inversion Principle**

Let’s take a brief look into each of these principles:

### Single Responsibility Principle (SRP)

It is a software engineering principle that states that a class should have only one reason to change. In other words, it must have only one responsibility.

Here, we are talking about cohesion. All elements in given class structures or modules should have a functional affinity to one another. By clearly defining your class’s responsibility, you increase its cohesiveness.

### Open/Closed Principle (OCP)

The principle says that you should be able to change the behavior of a class without modifying it.

Therefore, you can extend the class’s behavior through composition, interface, and inheritance. However, you cannot open it for minor modifications.

### Liskov Substitution Principle (LSP)

In her 1988 research paper, Barbara Liskov stated that derived classes should be replaceable by their base class(es). Thus, you need to exercise care when using inheritance in your project works.

While inheritance is beneficial, it is advisable to use it contextually and moderately. The principle strives to prevent cases where classes are extended only through common things.

You need to consider the pre-conditions and post-conditions of a class before performing inheritance.

### Interface Segregation Principle (ISP)

ISP prefers many specific interfaces to a general interface. The goal is to have finely grained and client-specific interfaces.

You need to enhance cohesion in interfaces and develop lean modules- those with few behaviors.

Interfaces that have many behaviors are hard to maintain and evolve. So, you should avoid them.

### Dependency Inversion Principle (DIP)

The principle asserts that programmers should depend on abstractions and not on concrete classes. We can break it into two:

» High-level modules need to be independent of low-level ones. Both should depend on abstractions

» Abstractions should be independent of details. Details should depend on abstractions.

Source: [laneways](https://www.laneways.agency/software-development-principles/)
