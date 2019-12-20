# nlp-sense-making

This Repository contains the implementation of NLP tasks to replicate the results described at the [NLP Sense-Making and Explanation Paper](https://arxiv.org/abs/1906.00363v1).

The paper describes the challenges that even the state of the art NLP techniques have in producing and understanding text that is not only grammatically correct but also makes sense.

3 Tasks are presented in the Paper, and this repository tackled each with the following NLP techniques:

Task 1: BERT
Task 2: BERT
Task 3: GPT

#### Task 1:  Validation Task

Given 2 grammatically correct statements, select which statement goes against common sense.

* Statement 1: He put a turkey into the fridge. (correct)
* Statement 2: He put an elephant into the fridge.

#### Task 2: Explanation Task

Given a series of statements, select the most corresponding reason why the statement is against common sense.

**Statement:** He put an elephant into the fridge.

* An elephant is much bigger than a fridge. (correct)
* Elephants are usually white while fridges are usually white
* An elephant cannot eat a fridge.

#### Task 3: Text Generation

The third task asks the machine to generate the reasons why statements are against common sense.

**Statement:** He put an elephant into the fridge.

Referential Reasons:
1. An elephant is much bigger than a fridge.
2. A fridge is much smaller than an elephant.
3. Most of the fridges aren’t large enough to contain an elephant.


### References

https://github.com/wangcunxiang/SemEval2020-Task4-Commonsense-Validation-and-Explanation