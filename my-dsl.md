# Language

_What is the name of the language? Link the name to its webpage (if appropriate)._

The DSL that I chose is Regualr Languages or Regex Expressions. The reason why I chose this DSL is because I have worked with them before in a prior internship. [java.util.regex regex link for java](https://docs.oracle.com/javase/7/docs/api/java/util/regex/Pattern.html)

# Domain

_Describe the language's domain in five words._

external DSL applying pattern recognition 

# Computational model

_We don't yet have a great definition of the term "computational model".
For now, try to come up with the clearest, most concise explanation of
what happens when a program in your DSL runs._

Regular Langages analyze and find patterns in strings of code through recursive pattern analysis where the pattern is defined by the user. For instance lets say the user wanted to find a phone number from a list of peoples personal information that may include a bunch of other information that is not impornta to the user. The user could define a regular expression to find phone numbers. This DSL would start by recusivly running through the list and it would itentify anything in the list that matches the pattern of a phone number (+1(123) 456-6789).

# DSL-ness

_Fowler writes about a spectrum of languages, from general-purpose languages to
"purely" domain-specific. Where does the DSL you chose fall on this spectrum,
and why?_

Regular Languages fall in the spectrum of more "purely" domain-specific becuase it's language is used as a tool within general-purpose languages such as java and python. Regualr languages abide by all of Fowler's definitions of a DSL and fall into the external DSL catagory. 

# Internal or external?

_Is the language implemented as an internal or external DSL?
Justify your answer._

Regular Languages are an external DSL becuase it is utalized as a tool within other main stream languages such as java and python. 

# Host language

_What language(s) was (were) used to implement the DSL?_


# Benefits

_Identify one potential benefit of the DSL: how is a programmer's life made
easier by the existence of this language?_

Regular expressions make a programmer's life easier by analyzing strings for patterns. AKA pattern recogintion. This makes the programers life easier becuase they do not have to define a program to find a pattern in a string instead they can simply use a Regular expression.

# Drawbacks

_Identify one potential drawback of the DSL: what does a programmer
lose by using this DSL instead of a general-purpose language?_

Regular expressions have alot of potential cost in terms of time. The longer the string the longer Regular expressions take to analyze the text for any particular patterns. Additionally they are quite specific. What I mean by this is that Regular expressions have a hard time understanding special characters, white space, and line breaks. 
