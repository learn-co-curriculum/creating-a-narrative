
# It’s All About the Story

Now that you have your overview written and your objectives clear, you’re ready to start presenting new material right? Well not quite yet. Readmes aren’t just a compilation of facts, but instead depend on **the overarching narrative within which your facts are contained**. In other words, you're not writing  "glorified documentation," but instead telling a story.

Your story should follow a narrative arc of beginning, middle, and end. Set the stage, show how the conflict emerges, work through this conflict, and end with presenting the new reality and tying up any loose ends.

![Image](http://farm3.static.flickr.com/2388/2387371826_509e4d0f06_o.png)

For now in this Readme, let's take a closer look at writing strong openings. 

Your opening should **always begin with something that the student already knows**. This can be a concept they know from previous lessons, or it can be a general idea that you can assume they know from their day-to-day lives. The goal is to draw your audience in and the best way to do that is by first presenting them with something familiar. Below are four examples of good openings:

---

1) **How does Twitter have different pages for each of its 300 million users? How can AirBnB support over 40 million guests with over 1.5 million listings worldwide? All of this is possible because of web applications.**

---

2) **Imagine needing to build a method that greets a person. We could code something like this:**

```ruby
def greeting
  puts "Hi, Ruby programmer!"
end
```

**This method, when called, will print out to the terminal, the string `"Hi, Ruby programmer!"`.**

**As amazing as this method is, it's still pretty literal. It hard-codes, or directly specifies, name of the person we are greeting as `"Ruby programmer"`.* *If we wanted to build a method that can greet anyone, even Python programmers, we'd have to re-implement the majority of the original logic from `greeting`:**

```ruby
def greeting_python
  puts "Hello, Python programmer!"
end
```

**Notice the only things that changed are the method name and the language name `"Python"` in the body of the method. It's as though that information should be specifiable or configurable when you call the method, otherwise we'd have to build every permutation of the method. In other words, we'd have to re-write the method for every single person we want to greet. We want our method to be more dynamic, more abstract, more re-usable. It should maintain the elements that will always be the same, no matter who we greet, and allow us to change, or swap out, the name of the person we are greeting. This is dynamic, as opposed to "hard-coded".**

**Good news, that's exactly what method arguments (also called parameters) are for.**

---

3) **Pets are great, aren't they? Isn't it nice to come home and a puppy that jumps up at you, excited to see you again after a long, hard day? Or a cat that climbs on your lap and walks all over your keyboard when you're trying to study Swift programming? Isn't it great that everyone has a furry (or scaly, or feathery) friend to keep them company?**

**Wait. Not everyone has a pet :(. When you first meet someone, it's pretty hard to know if they have a pet, unless you ask them. Until you do, you never know when they have an animal companion or not.**

**Situations like an unknown pet situation come up a lot in programming, too. You've already learned that constants and variables are associated with a _value_. The problem is that sometimes you don't know what that value is, or if it even exists, when you declare a constant or variable. It's like the pet situation! You might make a new friend but not immediately know if they have a pet or not.**

**Imagine you're writing a program to track a new acquaintance's pet situation. You want to track your friend's pet's name in a variable called `petName`, but initially you don't even know if they _have_ a pet. What do you do?**

**Swift deals with this sort of situation through the use of a type called an `Optional`. An `Optional` is a way of saying, "I have a piece of data I want to keep track of, but I don't know if it even _has_ a value yet." In Swift, you'd declare an `Optional` variable like this:**

```swift
var petName: String?
```
---

4) **It's often important in programming to know what the "owner" of a function is, so that we can operate on some specific object or data safely.**

**For instance, consider an event handler that fires when someone clicks on a link in the DOM. When that event handling function is invoked, we might want to know *which specific* link was clicked, so that we can manipulate it in some way.**

**That's where the `this` keyword comes into play. Every function is automatically assigned a `this` value when called, and that represents "who" called the function. This value can be an object, an event, or even another function.**

**The value of `this` is determined by the *execution context*, or scope, of the function call.**

## Why do these introductory sections work? 

They don't start with "big words." By "big words," we mean technical terms that are introduced without any context as to why they're there. The first example could have started with a definition from Wikipedia- "Web applications are client-server software application in which the client (or user interface) runs in a web browser." Beyond just being overly technical, this is also pretty dry. 

Strong openings keep us interested to read more by presenting a problem. In the first example, we started by asking questions that piqued the student's interest. In the second example, we showed students how to code a solution using the concepts that they already knew and in doing that, we showed the problems with that. 

In the third example, we talk about pets. It's pretty safe to assume that most people know what pets are and by using a metaphor like this, we can connect something that might be technically difficult to an easily understandable non-technical idea and this will help students retain information. 

In the fourth example, while it may seem like there are a lot of technical words in there, students have covered those concepts in previous lessons. What this introduction is doing here is presenting a problem using that information (i.e. which specific link was clicked) and then presenting the answer to that problem (i.e. `this` lets us do that). 

Wherever possible, openings should also go through the pain of solving a problem using just the concepts that we know. Show the students this pain by walking them through the code they'll need to create as the second example did. 

Strong openings present the "Why" of the lesson in a way that students understand. Why is what you're about to read important? More than just being able to hook the reader, strong openings will better prime them to receive and retain all the new information that you're about to present. 

Lastly strong openings as well as the rest of your lesson should always be friendly and open. Use the second person ("you") and first person plural ("we"). Write your lesson as if you were having a conversation with a student. Don't be afraid to be silly, make jokes, and let your personality shine through. When you show your excitement for the topic you're writing about, that'll get your students excited about learning it. 

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/creating-a-narrative' title='Creating a narrative'>Creating a narrative</a> on Learn.co and start learning to code for free.</p>
