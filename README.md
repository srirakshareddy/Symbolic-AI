# Symbolic-AI

1. Installation of the “pytholog” package.
2. Define the knowledge base to state the facts and rules where the primitive
family relationships are defined : Male, Female, Father, Mother
male(X): X is male
female(X) : X is female
father(X,Y): X is the father of Y
mother(X,Y): X is the mother of Y
3. Based on the primitive family relationships, composite family relations are
defined with logic as follows,
a. parent: : X is either mother or father of Y
b. brother(X,Y): X is brother to Y
c. sister(X,Y): X is sister to Y
d. grandfather(X,Y): X is grandfather to Y
e. grandmother(X,Y): X is grandmother to Y
f. grandparent(X,Y): X is grandparent to Y
g. uncle(X,Y): X is uncle to Y
h. aunt(X,Y): X is aunt to Y
i. sibling(X,Y): X is either brother or sister of Y
j. nephew(X,Y): X is the son of Y’s sibling

4. Queries are executed in this database using its facts and rules to infer the
composite family relations using the primitive family relations. The outputs
for the same are achieved and submitted along with this file.
