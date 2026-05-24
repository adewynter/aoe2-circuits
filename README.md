# A Perceptron in AoE II
For the paper '[If LLMs Have Human-Like Attributes, Then so Does _Age of Empires II_](https://arxiv.org/)', by Adrian de Wynter. 

>I'm still cleaning up everything, so bear with me!

This paper argues that LLM research assuming or concluding (implicitly or explicitly) any type of **general** anthropomorphic attribute is fundamentally flawed. The argument, in a nutshell, is that assuming they do (r. not) exist and then creating a hypothesis based on that assumption _and_ an experiment to prove/disprove the hypothesis leads to fallacies either way. Proving it is confirmatory (truth of the experiment does not imply truth of the hypothesis); and disproving it does not give enough information (it could be a flawed hypothesis _or_ a flawed counter-experiment, or both). 
Moreover, assuming that they do (r. not) exist and creating a hypothesis based on the assumption that they do not (r. they do) leads to a contradiction. 

It proposes instead to build the hypotheses based on _domain_-specific assumptions, as opposed to _assuming or concluding **general** capabilities_. 
Now, this might sound kinda obvious, but this means that (for example) if you study, say, theory of mind (ToM) in LLMs, you can't prove ToM by directly measuring or assuming (or not) ToM. 
You need an indirect measurement, or different assumptions. For examples of papers which do that (there's plenty, btw) check the paper. 

The point is:

>You can't conclude or assume (for example) 'LLMs have morality' (or they don't) as a _generalised statement_ by assuming it (or not assuming it!) as part of your experiment, because you can't prove it either way. Thus, **generalised statements about LLM anthropomorphic attributes are false** if they design the hypothesis/experiments with their existence in mind.

-----

An example: you can't assume that LLMs 'present signs of having morality' and then build a full hypothesis-experiment to prove/disprove that. That's because your results will be confirmatory ('we _conclude LLMs have morality_ because our experiments confirm the hypothesis we built based on the assumption that _LLMs present signs of having morality_') or uninformative ('we _conclude LLMs do not have morality_ because our experiments contradicted the hypothesis we built based on the assumption that _LLMs present signs of having morality_'). 

The first one fails because the experiment proving the hypothesis does not imply that the hypothesis is correct. The second is because the experiment contradicting the hypothesis could be by either the hypothesis being ill-formed, or the experiments being ill formed (i.e., the contrapositive being correct), or both. You can't prove it without various experiments, which in turn lead to piecing together multiple `(hypothesis, experiment)` pairs, and hence they are _not_ generalised statements. This is particularly glaring since there's a chance you'll have proving/disproving statements in the tuples `(hypothesis, experiment)` which will yield even less information since:
1. _Neither experiment_ is sufficiently informative in a mutually-exclusive manner, and
2. Trying to prove the contrapositive yields to flawed-assumption scenario from above.

# Q&A
_If the above rubbed you off the wrong way, check the paper. There's a few contras there._

Q. This is more or less how science works!

A: Yes, but have you seen the news lately? Or some papers' assumptions/conclusions?

Q: How is that related to AoE II?

A: Check the paper. Basically, the assumption of human-like attributes is a bit of a stretch when you can build an LLM everywhere. Would you assume/believe that AoE II can get anxiety?

Q: Then what do you propose?

A: 
1. Instead of assuming (or concluding!) 'LLMs have morality', one should create an experiment which either
    1. Does not start from any assumptions of human-like attributes, or
    2. Recognises that the evidence only applies to the _current observation_, _not to the hypothesis_, and _it will not generalise_.

2. The contrapositive is also true. you cannot build an experiment based on the assumption that 'LLMs understand natural language', and then prove/disprove a hypothesis based on this (e.g., 'LLM explanations are unreliable'). The experiment needs to either:
    1. Assume that explanations are just tokens and _nothing more_ (not meaningful in any way), and thus the experiment cannot assume or prove things based on this, or
    2. Recognises that the evidence only applies to the _current observation_, _not to the hypothesis_, and _it will not generalise_.

1.2 and 2.2 are very weak statements ('my LLM worked on this dataset!') and vulnerable to uninformativeness (see above), but 1.1 and 2.1 are harder to work with.

Q: This sucks.

A: Yes.


# Structure
Here I'll put something when it's up.

# Citation
```bibtex
...
```

# Licence

Everything that is created by me is MIT. Other things, like the artifacts for AoE II, are based on their original licences.

All products, company names, brand names, trademarks, and images are properties of their respective owners and are only reproduced here with the educational purpose of illustrating mathematical theorems and philosophical discussion. _Age of Empires II_ and all that stuff is property of Microsoft Corp.
