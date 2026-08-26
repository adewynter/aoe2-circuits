# A Perceptron in AoE II
For the paper '[If LLMs Have Human-Like Attributes, Then so Does _Age of Empires II_](https://arxiv.org/)'.

![A perceptron in AoE](img/perceptron_running.gif "A perceptron in AoE II")

A lot of research in LLMs assume some sort of human-like attributes to them (e.g.,
morality or understanding of natural language). We do not argue that these do (not) /can (not) exist; but instead that the way we are measuring that is wrong. 

This repository contains the artefacts used to illustrate part of our argument: a functioning, goat-powered neural network in AoE II. 
This deliberately absurd construct behaves and _is_, for all intents and purposes, a neural network. Thus, there is no reason why one could not implement an LLM into a very large AoE II. 

However, its representation does change, and thus _the way_ we interpret an LLM's behaviour depends on their representation: an LLM in AoE II will respond to 'I feel sad' the same way as an LLM in a GPU and behind a chat window; but it is less believable if it is made of goats. 

Our argument indicates that with this representation change, along with the fact that:

1. Assuming the LLMs are human-like leads to circular arguments one (experimentally) concludes they indeed are.
2. Assuming they are human-like _and_ conclude that they aren't leads to an uninformative conclusion.

(If one assumes they are _not_ human-like, they get the same problem). 
Thus one cannot assume anything about human-likeness if the plan is to conclude something about human-likeness. 

So we indicate is that one needs to assume _LLM non-uniqueness_, not anthropomorphism, and interpret behaviourally, not via ascriptions. We call this the _null assumption_.

# Structure

```
aoe2_scenarios/   # All the gates/networks from the paper
img/              # media stuff
```


# Citation
```bibtex
```

# Licence

Everything that is created by the authors is MIT. Other things, like the artifacts for AoE II, are based on their original licences.

All products, company names, brand names, trademarks, and images are properties of their respective owners and are only reproduced here with the educational purpose of illustrating mathematical theorems and philosophical discussion. _Age of Empires II_ and all that stuff is property of Microsoft Corp.
