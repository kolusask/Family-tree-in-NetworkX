# FamilyTree
A class used for managing a simple database of a family tree. The tree is represented by a directed graph. Each member is added with name and gender. The tree in initialized with the family's founder. New members are added as children or spouses of existing members. The tree can be saved to or loaded from json format. Relation between two family members can be found by entering their names. The later could be done using a 2D dict, however to practice usage of NetworkX, I decided to do it as an automaton represented by a nx.DiGraph.
