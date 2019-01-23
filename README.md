# ArmorBySkill-Generator

## Introduction
This project tries to solve the following problem:

We have a knapsack where we can store X items. Each of the items we can put into the knapsack is of one class of X classes. We only want to store in the knapsack maximum  one item of each class. For each class, we can have any number of possible items between 0 and infinite. Each item, indepently of his or her class, has an arbitrary amount of properties, between 0 and infinite. Each item modifies the property it has in a magnitude represented by a number between minus infinite and infinite.

To evaluate which properties we obtain for storing a certain set of items in the knapsack, we need to know which properties do we have in the set and with what magnitudes. To know the magnitude of a property in a set, we only need to sum up the magnitudes for that property of each item that possesses the property.

The goal is to find all the sets of items that satisfy a given set of pairs of properties and its desired magnitudes. A solution set must have the magnitudes of the given properties equal or greater of the given magnitudes of the given properties. It is possible that a valid set has magnitudes different from zero for any property that is not given in the goal set.


