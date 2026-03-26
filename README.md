# SMART-CALCULATOR-VITYARTHI
🤖 AI-Based Smart Calculator

This is a calculator that uses Python and Machine Learning. It can understand what you are saying and do math problems.

📌 Features

🔢 This calculator can do things like:

Addition

Subtraction

Multiplication

Division

🧠 There is an AI Mode. You can tell it what to do like this:

"add 5 and 3"

"divide 10 by 2"

⚡ There is also a Normal Mode. This is like a calculator.

🛑 The calculator can handle mistakes like input and division by zero

🛠️ These are the tools used:

Python

Scikit-learn

CountVectorizer for dealing with text

Multinomial Naive Bayes for figuring out what to do

📂 This is what the project looks like:

smart_calculator.py is the main program

README.md has information about the project

⚙️ This is how it works:

1. Machine Learning Model

A list of words is made:

Add is like add, plus sum

Subtract is like subtract, minus

Multiply is like multiply times

Divide is like divide divided

The text is turned into numbers using CountVectorizer

A Multinomial Naive Bayes model is taught to figure out what to do

2. Smart Input Processing

You type in a sentence like "add 5 and 3"

The numbers are found in the text

The Machine Learning model figures out what to do

The answer is calculated and shown

3. Dual Mode System

🔹 Smart Mode uses AI to understand what you say

For example:

You type 'smart'

You type "add 5 and 3"

The answer is 8

🔹 Normal Mode is like a calculator

For example:

You type in the first number: 5

You choose the operation: +

You type in the number: 3

The answer is 8

▶️ This is how to run it:

You need to install some things:

pip install scikit-learn

Then you run the program:

python smart_calculator.py

🧪 These are some examples:

You type "add 10 and 5" and the answer is 15

You type "subtract 9 and 3" and the answer is 6

You type "multiply 4 and 2". The answer is 8

You type "divide 8, by 2" and the answer is 4

⚠️ There are some limitations:

It only works with a words

It cannot understand hard sentences

It can only handle two numbers at a time

The list of important words is small so it is not always right

🚀 These are some things that can be improved:

Make it work with harder math problems

Make it understand what you say

Add a way to talk to it

Make the list of important words bigger so it is more accurate

📚 These are some things you can learn:

The basics of Machine Learning

How to use Bayes to figure out what to do with text

How to deal with Natural Language

How to use AI in real life

👩‍💻 The person who made this is

Ritika Manchanda
