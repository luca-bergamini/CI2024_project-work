# Computational Intelligence project work 2024

The algorithm used is a genetic programming (GP) with elitism. Formulas are represented as trees, generated randomly, and mutations and/or crossovers are applied to them. We use 20% as elitism to maintain the 20% of the best-performing individuals (based on their fitness) for the next generation without doing any modifications. We also use a max_depth parameter that is used to prevent overfitting and excessive growth. If a tree that exceeds the maximum depth is produced, one of the parents is returned.

We did several runs for each problems, selecting the best result based on the Mean Squared Error (MSE) and the complexity (overfitting) of the function.

This project is done with Youness Bouchari, trying to achieve the best results.