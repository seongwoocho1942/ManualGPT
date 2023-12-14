# ManualGPT

### <Prompt 1>
You are going to make some questions that may arise using a machine equipped with the FANUC MANUAL GUIDE i. A part of the manual book will be provided. Please write questions based on the context below.

Context:{context}

Questions:1.



### <Prompt 2>
Here are some questions that may arise using a machine equipped with FANUC MANUAL GUIDE i. A part of the manual book will be provided. Please answer to the questions based on the context below.

Context:{context}

Questions:{questions}

Answers:1.



### <DATA example 1>

Q: 
I would like to ask a question about MANUAL GUIDE i of FANUC. How is the bottom size/angle determined for turning when [WIDTH] is specified?

A: 
The bottom size/angle is determined for turning when [WIDTH] is specified by the difference between the groove entry of the side face on the reference position side and the width of the groove bottom. The inclination angle of the side face on the reference position side is determined when [ANGLE] is specified. If no value is entered, it is considered as 0 for both.



### <Prompt 3>
You will be provided with an example that contains a context, a question, and an answer. Please make some questions and answers based on this example.

The number of questions and answers cannot be less than the number of warning numbers.

You will first be provided with an example. Consider this example:

Context:

Appendix

Alarms

B. ALARMS APPENDIX Alarm 16i 30i Description Cause The first feed override is invalid. 3062 3562 Action A value not specifiable as turning or other first feed overrides is entered. Modify the machining program to specify an appropriate value.

Questions:

1. What should I do when I receive warning number 3062?
2. What should I do when I receive warning number 3562?

Answers:

1. Cause: The first feed override is invalid.Action: A value not specifiable as turning or other first feed overrides is entered. Modify the machining program to specify an appropriate value.
2. Cause: The first feed override is invalid.Action: A value not specifiable as turning or other first feed overrides is entered. Modify the machining program to specify an appropriate value.

Now, please write questions and answers based on the context below.

Context:{context}

Questions:
1. 



### <DATA example 2>

Q: 
I received an alarm says, "An arbitrary figure is not closed." What should I check when this warning occurs?

A: 
An arbitrary figure entered for facing, pocketing, or turning is not closed. Modify the machining program to specify a closed figure that uses the same point both as the start and end points.



### <Data example 3>


Q: 
I would like to ask a question about MANUAL GUIDE i of FANUC. I received a warning number 3503. What should I do about this?

A: 
There is no area that can be machined. The tool is too large for the specified machining area. Modify the machining program to use a smaller tool.
