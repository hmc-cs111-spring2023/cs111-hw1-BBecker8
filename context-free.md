# Context Free

##  Who is this programming language for?

Context Free Art is a programing language built for people that want to design compture generated art peices. This can be anything from graphic art to desgins. I would say that the primary focus for this language is for those who want a simple way to design art online. This being simpler then Python or Java.

## What is easy to do in this language? Why is it easy?

It was easy to make shapes in this language becuase all you need is the name of the shape you are trying to draw. It was also fairly easy to understand what the program was doing. For instance you start your file with startshape and you give it a variable name. After this all you have to do is define a rule for that varible such as draw or TRIANGLE. 

## What is hard to do in this language? Why is it hard?

In general it was tough to decide what type of picture to make and how I was going to accoplish it. It was also difficult understanding how certian parts of the code would affect the drawing this is mostly becuase of the unfimiliarity of the program. As I got more comfortable with the laguage, I was able to accomplish more complext things like adding a backround and changing the color. 

## How did you learn how to program in this language?

I learned how to program in this laguage by looking at the documentation and referncing other simple art peices that I found on the web. After refrencing these sources I found the laguange to be roughly stright forward. The peices of art that I refrenced gave me the idea to draw the Sierpinski triangle. 

## What is the underlying _computational model_ for this programming language? 
_We don't yet have a great definition of the term "computational model". 
For now, try to come up with the clearest, most concise explanation of what 
happens when a ContextFree program runs._

When a ContextFree program runs it defines a sigular shape to be drawn at a time which can be programmed with the following pattern:
    startshape variable
    rule variable {
        some defining code her
    }
This makes particular shapes and images esier to minipulate within your program and within your picture. After the user has written code like as shown above, they can render the picture which compiles the image in your editor.

## What do you think is interesting about the ContextFree program you wrote?

The program that I wrote is interesting because I was able to use a recursion like technique in order to draw smaller triangles within bigger trinagles forming the Sierpinski triangle. I started with one triangle and then I ran recurion on another trinagle that is 1/3 of the size and located at the top of the big triangle. I did this twice more and positioned theses at the left and right corners of the bigger triangle. This gave me the Sierpinski triangle which was pretty cool to build. 