# Code Intepreter 

We can pass in keyword arguments to 'ChatCompletion' of 'openai', functions being one of them. Let's say we have a very simple function that adds two integers. 
We want to pass this function 'ChatCompletion.create'. One important thing to keep in mind is that, we can not pass the python function directly. We have to pass 
in the JSON schema. 
It is a bit different from how we program computers. The key thing to program computers is the docstring, in this case. The GPT will look at the docstring and knows about the function and what it does. So it is critical to keep the docstring in mind which should exactly describe what the function does.

Like we used to pass in custom instructions programmatically using system messages, we can pass in functions using the "role" as "function"
