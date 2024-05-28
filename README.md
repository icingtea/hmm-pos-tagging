<h3> Parts of Speech Tagging </h3>
POS tagging is an NLP task that assigns a grammatical category to each word in a sentence. One of the ways of doing this is using a stochastic or probabilistic process involving HMMs.

<h3> Hidden Markov Model (HMM) </h3>
A Hidden Markov Model is used to model sequences of observable events where the underlying system's states are hidden. In POS tagging, an HMM represents the sequence of words in a sentence as said 'observable events' and the sequence of POS tags as hidden states. The model utilizes emission probabilities (the probability of a word given a certain tag) and transition probabilities (the probability of a tag existing subsequent to a given previous tag) to calculate state probabilities.

<h3> Viterbi </h3>
The Viterbi algorithm is used to find the most likely sequence of hidden states (POS tags) given a sequence of observations (words). It efficiently computes the maximum probability path through the HMM and picks out the highest state probabilities to return a sequence of states.
