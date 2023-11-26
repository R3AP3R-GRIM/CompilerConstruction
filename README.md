# Regular Expression Simulator
This C++ masterpiece ingeniously crafts a regular expression simulator, utilizing the powerful NFA (Nondeterministic Finite Automaton) and DFA (Deterministic Finite Automaton) concepts. The user-friendly program gracefully accepts regular expressions, adorned with symbols like 'a' and 'b' for alphabet symbols, parentheses for grouping, '.' for concatenation, '|' for alternation, and '*' for the magic of zero or more occurrences.

Through a symphony of preprocessing and postfix conversion, the program ensures that the regular expression is ready for a grand performance. The NFA construction, a ballet of Thompson's construction algorithm, choreographs a transition table, while the DFA construction pirouettes with the subset construction algorithm, creating an elegantly named state ensemble.

The simulation, the pièce de résistance, invites users to enchant the program with strings, guiding the DFA through a dance of transitions to reveal the final verdict on membership in the glamorous regular expression.

Compile and run this marvel with a C++ compiler, basking in the glory of computational ballet:

g++ -o regex_simulator regex_simulator.cpp
./regex_simulator

Behold as the program gracefully handles expressions like "(a|b)*abb" and waltzes through strings like "aababb," delivering an enchanting performance.
