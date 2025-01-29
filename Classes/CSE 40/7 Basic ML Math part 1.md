### Date: 01-22-2025
### Instructor: Alexander Rudnick


## Notes:

### Probabilistic Reasoning
- Classical Boolean logic does not allow us to express certain patterns of plausible reasoning:
- We observe that A is false.  We find B becomes less probable, although no conclusion can be drawn from classical logic.
- We observe that B is true.  It seems that A becomes more probable.
- We use this type of reasoning daily!
- As a matter of fact, much of human learning is based on these kinds of probabilistic predictions

#### Two Schools Of Thought
1. A *Bayesian* probability specifies the degree of uncertainty that the user has about an event.  It is sometimes referred to as “subjective probability” or “degree of belief.”
- A Bayesian probability specifies the degree of uncertainty that the user has about an event.  It is sometimes referred to as “subjective probability” or “degree of belief.”

1. A *Frequentist* probability considers the relative frequencies of events of interest to the total number of events that occurred.  The probability of an event is defined as the relative frequency of the event in the limit when one has infinite data.
- A Frequentist probability considers the relative frequencies of events of interest to the total number of events that occurred.  The probability of an event is defined as the relative frequency of the event in the limit when one has infinite data.

### Basic Laws of Probability
- The probability of any event must be in the range [0, 1] (inclusive).
- The total probability over all the outcomes in the sample space must sum to 1.
*Important distinction: *
- Outcomes are mutually exclusive and disjoint (in any experiment, exactly one outcome occurs).
Events can overlap (any given outcome can be part of multiple events)

#### Terminology
Sample Space:  the set of all possible (disjoint) outcomes of an experiment.   
- In a single coin toss, with heads h and tails t, the sample space is {h, t}.
- Two coin tosses have a sample space of {hh, ht, th, tt}.
Event:  a subset of outcomes.
- Let Eh be the event that at least one coin was heads
- Eh = {hh, ht, th}
Probability:
- The probability of an outcome o in a sample space 𝑆 is a number p between 0 and 1 that measures the likelihood that o will occur on a single trial of the random experiment. 
- p=0 corresponds to outcome o being impossible and p=1 corresponds to o being certain.
- The probability of an event is simply the sum of the probabilities of the outcomes.
- Under common assumptions of fair coin etc. that we will discuss next time, p(Eh) = ¾.
Random Variables:
- A random variable is a mapping from outcomes in the sample space to values.
![[Pasted image 20250128154610.png]]

#### Kinds of Probability Spaces & Distributions
*Discrete*: finite set of possible outcomes.
*Continuous*: infinite set of possible outcomes.

### Probability Distribution
- Can be represented with a table of outcomes and their probabilities
- Sum of all probabilities must add to 1
- and all probabilities must be greater than 0
![[Pasted image 20250128155021.png]]
### Joint Probability Distributions
- A *joint probability distribution* (i.e., a distribution over a set of random variables) can also be represented as a table of probability values.
![[Pasted image 20250128155015.png]]

- An event is the set of outcomes

### Marginal Distributions
![[Pasted image 20250128155151.png]]
- Done by adding the total probability of being hot or total probability of being hot 

### Sum Rule
![[Pasted image 20250128155257.png]]
- Basically adding all the probabilities of X regardless of whatever y is

### Conditional Probabilities
- Conditional probabilities are written as P(X|Y), which can be read to mean, "the probability that X happens GIVEN that Y has happened.”
![[Pasted image 20250128155351.png]]
- it the probability of x and y both happening dived by the total probability of y happening
- This gives a ration of when x and y happen to when y happens
![[Pasted image 20250128155504.png]]
![[Pasted image 20250128155535.png]]
- Probability something is going to happen given another event is already happening

### Product Rule
![[Pasted image 20250128155617.png]]
- Given a conditional probability we can multiply it by the probability of the condition to get back to P(x,y)
- This is just proven by the algebra
![[Pasted image 20250128155722.png]]


