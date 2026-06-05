# A Perceptron in AoE II
For the paper '[If LLMs Have Human-Like Attributes, Then so Does _Age of Empires II_](https://arxiv.org/abs/2605.31514)', by Adrian de Wynter. 

![A perceptron in AoE](img/perceptron_running.gif "A perceptron in AoE II")

>I'm still cleaning up everything, so bear with me!

A lot of research in LLMs assume some sort of human-like attributes to them (e.g.,
morality or understanding of natural language). 
I am not saying these do (not) /can (not) exist, but that the way we are measuring that is wrong. 

To drive my point, I built a neural network in AoE II and indicated that any sufficiently-powerful substrate could implement an LLM. I call this _LLM non-uniqueness_. 

Non-uniqueness also means that _the way_ we interpret an LLM's behaviour depends on their representation: an LLM in AoE II will respond to 'I feel sad' the same way as an LLM in a GPU and behind a chat window; but, would you believe it if it is made of goats?

So, to prove or disprove human-like attributes you need to use GOOD measurements. Then I ruin the day by showing that:
1. Assuming the LLMs are human-like leads to circular arguments if you (experimentally) conclude they indeed are.
2. Assuming they are human-like _and_ conclude that they aren't leads to an uninformative conclusion.

Turns out that if you assume they are _not_ human-like you run into the same problem.

So you CANNOT assume anything about human-likeness if you plan to conclude something about human-likeness. It's not exactly obvious (how would you prove that something exists if you do not know if it exists?). 

So what I indicate is that you need to assume _LLM non-uniqueness_, not anthropomorphism, and interpret behaviourally, not via ascriptions. I call that the _null assumption_.

Oh and I also have some objections in the paper (because this paper is a bit weird), provide a wee survey of the field, and prove that AoE II, like almost everything, is functionally- and Turing-complete. 


# Q&A
_If the above rubbed you off the wrong way, check the paper. There's a few contras there which are more carefully-worded than the below._

**Q. This is more or less how science works!**

A: Yes, but have you seen the news lately? Or some papers' assumptions/conclusions? 

Ok, let's flippantly: in the paper I show that a lot of papers concluding human-like attributes _assume_ that these attributes exist, and then they design an experiment to prove it (a circular argument).

Conversely, an argument trying to prove it by contradiction hits a wall when trying to elucidate if it was the experiment or the hypothesis which failed (because there's no independent way to verify it if the hypothesis includes the assumption).

It then follows that _science_ does not work that way. An approximation (as opposed to a conclusive statement) would work better for sure, but then you cannot claim generality.


**Q: How is that related to _AoE II_? / LLMs run in a computer, isn't this the same thing?**

A: The assumption of human-like attributes is a bit of a stretch when you can build an LLM in _any_ substrate. Would you assume/believe that _AoE II_ can get anxiety? What if I tell you that asking every Bostonian to text each other the operations, and picking people acting as tokens to walk into 77 Mass Ave, is indicative of a theory of mind?

I'm not saying it cannot happen. What I'm saying is that you can't start research by assuming that it happens (regardless of how weird it sounds to say that the Greater Boston Area can get sad). Be a scientist. Provide sound arguments.

**Q: Then what do you propose?**

A: Instead of assuming (or concluding!) 'LLMs have morality' (or, say, 'LLMs do not have anxiety'), one should create an experiment which does not start from any assumptions of human-like attributes. The interpretation is a behavioural interpretation wrt a stimulus, as opposed to (e.g.) human psychology.

This is what I call in the paper the _null assumption_. 


**Q: This sucks.**

A: Yes. It really would be easier to just assume they are human-like, but the thing is that they are unlike anything we have seen before. Assuming that (or assuming they are not human-like, either way) is flawed.


# Structure

```
aoe2_scenarios/   # All the gates/networks from the paper
img/              # media stuff
survey_code/      # Minimally-reproducible code for the survey
```


# Citation
```bibtex
@misc{dewynter2026llmshumanlikeattributesdoes,
      title={If LLMs Have Human-Like Attributes, Then So Does Age of Empires II}, 
      author={Adrian de Wynter},
      year={2026},
      eprint={2605.31514},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2605.31514}, 
}
```

# Licence

Everything that is created by me is MIT. Other things, like the artifacts for AoE II, are based on their original licences.

All products, company names, brand names, trademarks, and images are properties of their respective owners and are only reproduced here with the educational purpose of illustrating mathematical theorems and philosophical discussion. _Age of Empires II_ and all that stuff is property of Microsoft Corp.
