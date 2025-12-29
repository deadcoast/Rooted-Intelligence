

Traditional propositional logic:
$A$ statement is either true $(1)$ or false $(0)$

$P(A) \in \{0, 1\}$

Fuzzy logic extends this to continuous values:

$P(A) \in [0, 1]$

Multi-world inference goes beyond by considering distributed probability:

$P(A) = \{(w_1, p_1), (w_2, p_2), ..., (w_n, p_n)\}$

Where:
- $w_i$ is a possible world state
- $p_i$ is the probability of that world state

$\sum_{i=1}^{n} p_i = 1$

For inference, we compute over all possible worlds:

$P(B|A) = \sum_{i=1}^{n} P(B|w_i) \cdot P(w_i|A)$

This allows for maintaining multiple parallel hypotheses through an inference chain:

For a multi-step inference $A → B → C → D$:

$P(D|A) = \sum_{i=1}^{n} \sum_{j=1}^{m} \sum_{k=1}^{l} P(D|w_{ijk}) \cdot P(w_{ijk}|A)$

The system can "collapse" this distribution when needed:
Maximum likelihood (most probable world):

$w_{ML} = \arg\max_{w_i} P(w_i|evidence)$

Or maintain the full distribution for more robust reasoning.

Connection to quantum mechanics:
Similar to quantum superposition, we can view inference as:

$|\psi\rangle = \sum_{i=1}^{n} \sqrt{p_i} |w_i\rangle$

Where $|w_i⟩$ are basis states (possible worlds) and measurement (determining a specific answer) collapses the state.