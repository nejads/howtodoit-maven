# How to do it in Maven

This repo is a demo for how maven projects can be ordered in a grant parent, a parent and a (or several) child(ren). 

### Schematic diagram
grandparent 
        |
        ------ parent
                    |
                    ------- child1
                    ------- child2

### How children inherit dependencies                     
The grant parent has its own dependencies. 
The parent has dependencies in grant parent and its own. 
The child(ren) has dependencies from all ancestors and its own.

