# TO DO
1. Git policy:
new modification? 
* approve pull request: to allow the branch master to have new features
* ```git checkout master```: switch branch
* ```git pull origin master```: to have the new features in the personal
branch master
* ```git checkout elisa/devel```: switch to the personal branch
* ```git merge master```: to have the new features in our personal branch
* ```git checkout elisa/devel```: to keep on working on personal branch
* ```git push origin elisa/devel```: to upload our modifications in our
remote repo
* open a pull request: to have the extra new features in the master

2. Iterator: to undestand

3. Solve Travis problem (I'll check on Axel's repo)

4. Measure performance

5. Interfaccia figa (but only if ALL the functions work)

6. Implement copy and move semantics for the tree (Caro)

7. Readme ordinato

# QUESTIONS FOR ALBERTO
1. Va bene se ignoriamo un nodo uguale ad un altro? Vedere implementazione

# ALBERTO DIXIT
1. insert deve restituire un iteratore (e non un puntatore al nodo)

2. If I'm the
* RIGHT child: my up = my parent's up  (```t->right->up = t->up```)
* LEFT child: my up = my parent (```t->left->up = t```)