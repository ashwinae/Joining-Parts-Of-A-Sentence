# Joining-Parts-Of-A-Sentence

A lot of existing ChatBot APIs extract the Intents and Parts of a sentence and return them to the user. The problem, however, arises in automating the process of connecting the Intents with the right Parts and vice-versa. 

- For example, if "I want to play cricket. Might need a bat for it though." returns: 

Intent : {want, play, need}

Part : {cricket, bat}

There are wide range of combinations in which the Intent and Part can be combined. But then, eliminating "want" and giving out 
{"play cricket" , "need bat"} is the requirement.  

This API attempts to connect the extracted entites using multiple grammatical rules and functions. 


