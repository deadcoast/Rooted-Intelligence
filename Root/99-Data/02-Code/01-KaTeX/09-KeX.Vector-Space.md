
Consider a simplified example with 5-dimensional embeddings
These would be hundreds to thousands of dimensions in practice

Example vector representations (simplified to 5 dimensions)

$\vec{v}_{king} = [0.3, -0.2, 0.8, 0.1, 0.5]$
$\vec{v}_{queen} = [0.2, -0.1, 0.7, 0.3, 0.5]$
$\vec{v}_{man} = [0.5, -0.3, 0.1, 0.0, 0.2]$
$\vec{v}_{woman} = [0.4, -0.2, 0.0, 0.2, 0.2]$

The famous analogy relationship can be seen mathematically:
$\vec{v}_{king} - \vec{v}_{man} \approx \vec{v}_{queen} - \vec{v}_{woman}$

Let's calculate:
$$
\vec{v}_{king} - \vec{v}_{man} = [0.3, -0.2, 0.8, 0.1, 0.5] - [0.5, -0.3, 0.1, 0.0, 0.2]
                              = [-0.2, 0.1, 0.7, 0.1, 0.3]
$$

$$
\vec{v}_{queen} - \vec{v}_{woman} = [0.2, -0.1, 0.7, 0.3, 0.5] - [0.4, -0.2, 0.0, 0.2, 0.2]
                                 = [-0.2, 0.1, 0.7, 0.1, 0.3]
$$

The vectors are identical in this simplified example
In practice, they would be very similar but not exactly identical

This demonstrates how relationships between concepts are encoded
in the geometric relationships between their vector representations

Semantic similarity is measured by cosine similarity:
$similarity(A, B) = \frac{\vec{v}_A \cdot \vec{v}_B}{||\vec{v}_A|| \cdot ||\vec{v}_B||}$

Example calculation for king and queen:
$$
\vec{v}_{king} \cdot \vec{v}_{queen} = 0.3 \times 0.2 + (-0.2) \times (-0.1) + 0.8 \times 0.7 + 0.1 \times 0.3 + 0.5 \times 0.5
                                     = 0.06 + 0.02 + 0.56 + 0.03 + 0.25
                                     = 0.92
$$

$$
||\vec{v}_{king}|| = \sqrt{0.3^2 + (-0.2)^2 + 0.8^2 + 0.1^2 + 0.5^2}
                   = \sqrt{0.09 + 0.04 + 0.64 + 0.01 + 0.25}
                   = \sqrt{1.03}
                   = 1.015
$$

$$
||\vec{v}_{queen}|| = \sqrt{0.2^2 + (-0.1)^2 + 0.7^2 + 0.3^2 + 0.5^2}
                    = \sqrt{0.04 + 0.01 + 0.49 + 0.09 + 0.25}
                    = \sqrt{0.88}
                    = 0.938
$$

$similarity(king, queen) = \frac{0.92}{1.015 \times 0.938} = \frac{0.92}{0.952} = 0.967$