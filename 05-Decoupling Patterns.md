解耦模式
============================

Once you get the hang of a programming language, writing code to do what you
want is actually pretty easy. What's hard is writing code that's easy to adapt
when your requirements *change*. Rarely do we have the luxury of a perfect
feature set before we've fired up our editor.

当你掌握了一门编程语言，你会发现写代码来实现某个你想要实现的功能是件相当容易的事情。难的是写出在此基础上容易添加或更改功能的代码，因为我们几乎没有可能不更改程序的功能或者特性。

A powerful tool we have for making change easier is *decoupling*. When we say
two pieces of code are "decoupled", we mean a change in one usually doesn't
require a change in the other. When you change some feature in your game, the
fewer places in code you have to touch, the easier it is.

[Components](component.html) decouple different domains in your game from each
other within a single entity that has aspects of all of them. [Event
Queues](event-queue.html) decouple two objects communicating with each other,
both statically and *in time*. [Service Locators](service-locator.html) let
code access a facility without being bound to the code that provides it.

[组件](05.1-Component.md)将游戏的不同方面互相分离开却仍然具备它们的特性。[事件队列](05.2-Event Queue.md)能够静态而且及时的将两个对象通信分离开。[服务定位器](05.3-Service Locator.md)让代码能够访问到设备却不需要被绑定到提供服务的代码上。

## 本章模式

* [组件](05.1-Component.md)
* [事件队列](05.2-Event Queue.md)
* [服务定位器](05.3-Service Locator.md)