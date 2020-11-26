# SASSI a Simple Chatbot
S(hopping)ASSI(stant) is a simple "Shopping Assistant" bot (similar to ELIZA) with the following features:
- detect keywords and key phrases and give an appropriate response
- "intelligent" continuation of the dialogue in case no keyword or key phrase was detected
- a random generation & selection of answers
- a "you - I reversal" in the dialogue (e.g. Input: I am happy. Answer: Why are you happy?)
- remembering and referring to what has been said before, i.e. prior to the directly preceding input

# Usage
Can be run interactively:

```
$ python sassi.py
How do you do.  Please tell me your problem.
> I would like to have a chat bot.
You say you would like to have a chat bot ?
> bye
Goodbye.  Thank you for talking to me.
```
