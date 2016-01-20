# Structuring Your Readme

“It is not a recitation of facts, but the building of an argument.”
            -Molly Worthen

## It’s All About the Story

Now that you have all your objectives, you’re ready to start presenting new material right? Well not quite yet. Readmes aren’t just a compilation of facts, but instead depend on **the overarching narrative within which your facts are contained**. Again, never write "glorified documentation." 

Instead, think of your Readme as a story that follows a narrative arc of beginning, middle, and end. In other words, set the stage, show how the conflict emerges, work through the conflict, and end with presenting the new reality and tying up any loose ends.

![Image](http://farm3.static.flickr.com/2388/2387371826_509e4d0f06_o.png)


We'll take a closer look at each of these narrative sections. For now in this Readme, we'll start with the beginning and setting the stage. 

When you’re setting the stage, begin with something that the student already knows. This can be a concept you can assume they know from previous lessons. Or it can be a general idea that you can also assume they know from their day-to-day lives. The ultimate goal is to hook your audience and the best way to do that is with a known idea.  Below are two examples:

1) *How does Twitter have different pages for each of its 300 million users? How can AirBnB support over 40 million guests with over 1.5 million listings worldwide? All of this is possible because of web applications.*

2) *Imagine needing to build a method that greets a person. We could code something like this:*

```ruby
def greeting
  puts "Hi, Ruby programmer!"
end
```

*This method, when called, will print out to the terminal, the string `"Hi, Ruby programmer!"`.*

*As amazing as this method is, it's still pretty literal. It hard-codes, or directly specifies, name of the person we are greeting as `"Ruby programmer"`.* *If we wanted to build a method that can greet anyone, even Python programmers, we'd have to re-implement the majority of the original logic from `greeting`:*

```ruby
def greeting_python
  puts "Hello, Python programmer!"
end
```

*Notice the only things that changed are the method name and the language name `"Python"` in the body of the method. It's as though that information should be specifiable or configurable when you call the method, otherwise we'd have to build every permutation of the method. In other words, we'd have to re-write the method for every single person we want to greet. We want our method to be more dynamic, more abstract, more re-usable. It should maintain the elements that will always be the same, no matter who we greet, and allow us to change, or swap out, the name of the person we are greeting. This is dynamic, as opposed to "hard-coded".*

*Good news, that's exactly what method arguments (also called parameters) are for.*

### Why do these introductory sections work? 

They don't start with "big words." By "big words," we mean technical terms that are introduced without any context as to why they're there. The first example could have started with a definition from Wikipedia- "Web applications are client-server software application in which the client (or user interface) runs in a web browser." Beyond just being overly technical, this is also pretty dry. 

Strong openings keep us interested to read more by presenting a problem. In the first example, we started by asking questions that piqued the student's interest. In the second example, we showed students how to code a solution using the concepts that they already knew and in doing that, we showed the problems with that. 

Wherever possible, openings should also go through the pain of solving a problem using just the concepts that we know. Show the students this pain by walking them through the code they'll need to create as the second example did. 

And lastly strong openings as well as the rest of your lesson should always be friendly and open. Use the second person ("you") and third person plural ("we"). And write your lesson as if you were having a conversation with your student. That again means avoiding "big words" without any context of why they're being used, walking them through the problem before you present the answer, and keeping the language. Don't be afraid to be silly, make jokes, and let your personality shine through. When you show your excitement for the topic you're writing about, that'll get your students excited about learning it. 

Coming up, we'll look at examples of openings that aren't very strong and will re-work them to be better. 

<a href='https://learn.co/lessons/creating-a-narrative' data-visibility='hidden'>View this lesson on Learn.co</a>
