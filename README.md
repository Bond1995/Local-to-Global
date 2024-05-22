# Code organization

### A few pointers

-   [Markov-LLM-k](Markov-LLM-k) contains the full transformer model for binary k-order Markov sources.
-   [Markov-LLM-m](Markov-LLM-m) contains the full transformer model for Markov sources with arbitrary vocabulary size.
-   [Markov-Simple](Markov-Simple) contains a simplified transformer model for first-order Markov sources without layer norm.
-   [Markov-Fixed](Markov-Fixed) contains a three-parameter simple architecture that mimicks a transformer model with rank-one parameter initialization.

The script to run the experiments is in src/main.py.
