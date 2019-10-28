# REtoDFA
This program generates a DFA from a RE using a direct method (not passing through NFA)
1 create augmented RE from input RE
2 generate binary tree from augmented RE
3 calculate first and last positions in tree making it a syntax tree
4 calculate follow positions for each leaf in syntax tree
5 generate DFA states from follow positions
