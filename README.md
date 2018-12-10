# FiniteAutomationMatcher

Finite automata: A finite automaton M is a 5-tuple (Q,q0,A,S,d), where 
* Qis a finite set of states.
* q0 ∈ Q is the start state.
* A ∈ Q is a distinguish set of accepting states.
* S is a finite input alphabet
* d is a function from Q × S into Q, called the transition functionof M.
* The finite automaton begins in state q0and read the characters of its input string one at a time. If the automaton is in state qand reads input character a, it moves from state qto state d(q,a).
* As long as Mis in a state belonging to A, Mis said to have accepted the string read so far, an input that is not accepted is said to be rejected.
