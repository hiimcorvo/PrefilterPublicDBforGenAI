# PrefilterPublicDBforGenAI
Small repo for prepping public databases for use in Generative AI

I have found that by applying some prefiltering techniques to some of these large collections of molecules, you can skew your generative AI away from random molecules that will never work and towards druglike molecules.

Assumption: Start with your own .smi file of SMILES from whatever public database of molecules you prefer. There are many ways to create this, so I won't cover how to create this baseline file. This is all you need, just the smiles from the database, to be used for your generative models, which I'll make in the future.

Python version: 3.7.12

rdkit version: 2022.09.1

Everything will most likely work with different versions, these are just the ones I used.
