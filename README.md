# NLP---Neural-Arc-Eager

This project was developed by myself collaborating for a part of it (mainly its fundamental structure, then we went on independently) with my course's peer Onur Alp Guevercin.

The project consists of a neural dependency parser based on the arc-eager system. A dependency parser is used to map a sentence to a tree that describes its grammatical structure, i.e. relations between words; in this specific project we implemented two different neural oracles for our arc-eager parser and confronted their performance:

- An oracle leveraging BiLSTM-based representations.
- An oracle based on transfer learning, more specifically BERT model was fine-tuned and used to create dynamic embeddings.


For further details on Arc-Eager parser see the original paper [Nivre, 2003](https://aclanthology.org/W03-3017.pdf)
