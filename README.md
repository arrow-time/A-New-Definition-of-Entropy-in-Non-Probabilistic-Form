# A New Definition of Entropy in Non Probabilistic Form

markdown

![Non-Probabilistic Entropy Infographic.png](https://raw.githubusercontent.com/arrow-time/A-New-Definition-of-Entropy-in-Non-Probabilistic-Form/refs/heads/main/Non-Probabilistic%20Entropy%20Infographic.png)

### Keywords: multiplicative entropy · gradient-driven · discrete systems · energy conservation · non-probabilistic entropy · non-coarse-grained · ontological entropy · epistemological thermodynamics

This paper is a part of author's previous work(Zou, Z. K. (2025). The Thermodynamic Nature of Time, The Geometric Essence of Gravity-Mass, The Quantum Chirality of Space, The Non-Statistical Formula of Entropy, The Dynamical Rules of Causality. Zenodo. https://doi.org/10.5281/zenodo.14788393).

### Abstract

The traditional definition of entropy relies on probability distributions, ensemble assumptions, and coarse-graining operations. It tells us how many states a system "might" be in, but does not tell us what the system "is undergoing." This paper proposes a new form of entropy—multiplicative entropy—that does not depend on probability, statistical ensembles, or ergodic assumptions. It depends on only two things: the energy distribution of the system and the energy gradients that drive changes in that distribution. This entropy is computable point by point, path-trackable, integer-valued, and precisely complementary to the first law of thermodynamics. From an epistemological perspective, this definition reduces the two laws of thermodynamics from "mathematical formulations" to "intuitively understandable geometric relationships," helping people directly grasp the underlying operational logic of thermodynamics at the conceptual level.

Keywords: multiplicative entropy · gradient-driven · discrete systems · energy conservation · non-probabilistic entropy · non-coarse-grained · ontological entropy · epistemological thermodynamics

### I. Traditional Statistical Entropy: An Indirect, Observer-Dependent Measure

Boltzmann entropy:

S = k_B · ln Ω

Shannon entropy:

H = −Σ p_i · ln p_i

Gibbs entropy:

S = −k_B · Σ p_i · ln p_i

They share the same mathematical core: logarithm + probability weighting.

But here lies a profound epistemological problem:

What is the "number of microstates" Ω?

It depends on how we define the boundary between "micro" and "macro";

It depends on which degrees of freedom we choose as "relevant" and which as "negligible";

It depends on the scale of coarse-graining—and this scale is chosen by the observer, not given by the system itself.

In other words:

The value of statistical entropy depends in part on the observer's level of description, and not entirely on the state of the system itself.

This means epistemologically:

If we change the coarse-graining, the entropy value changes;

If we choose a different set of microvariables, Ω changes;

If we gain more knowledge about the system's "internal structure," the entropy value decreases—because our "ignorance" has decreased.

But the physical state of the system itself has not changed.

This leads to a fundamental question:

What exactly does statistical entropy measure? The physical state of the system itself, or the observer's missing information?

From the perspective of scientific realism, a good physical quantity should directly measure the properties of the system itself, not the relationship between the observer and the system. Statistical entropy essentially depends on the observer's descriptive choices, and thus it is more like an epistemological quantity than a purely ontological one.

### II. A Key Overlooked Variable: Energy Gradient

Real dynamics—whether heat conduction, diffusion, chemical reactions, or electric currents—are all driven by one unified physical quantity:

The energy gradient.

Heat flows from high temperature to low temperature: temperature gradient;

Matter flows from high concentration to low concentration: chemical potential gradient;

Charge flows from high potential to low potential: electric potential gradient;

Mechanical systems move from high potential energy to low potential energy: force gradient.

In all known natural processes, the flow of energy from high to low is the sole source of irreversibility.

Statistical entropy does not track this gradient. It tells us that a uniform distribution is the maximum entropy state, but it does not tell us how the system step by step approaches uniformity, what the path of each energy transfer is, or what the magnitude of the gradient is at each step.

These questions cannot be directly answered by statistical entropy, because its definition does not contain the concept of "gradient."

### III. Starting Point for a New Form: Gradient-Driven Evolution on a Discrete Network

Consider a closed system consisting of N nodes. Each node carries an amount of energy, with energy quantized in units of Planck's constant h:

m_i ∈ ℕ⁺

Total energy conservation:

E = Σ m_i = const

Energy transfer between nodes is allowed only between adjacent nodes, one unit at a time, and only when an energy gradient exists:

Transfer condition:

m_i > m_j + 1

Transfer rule:

m_i → m_i − 1

m_j → m_j + 1

These are the sole and complete dynamical rules.

No probability;

No ensembles;

No randomness;

No external driving;

No artificially chosen coarse-graining scale.

The evolutionary direction of the system at each step is entirely determined by the current energy gradient distribution. The adjacent node pair with the largest gradient receives the highest transfer priority.

### IV. Definition: Gradient-Driven Multiplicative Entropy

Define the entropy of the system as:

S = ∏_{i=1}^{N} m_i

where m_i is the energy value carried by the i-th node.

This form:

Does not depend on probability;

Does not depend on ensembles;

Does not depend on coarse-graining;

Does not depend on logarithmic approximation;

Is uniquely determined by the current energy distribution;

Is a positive integer.

More importantly: it directly reflects the outcome of gradient-driven evolution.

The change in entropy before and after each transfer:

S′ = (m_i − 1)(m_j + 1) · ∏_{k≠i,j} m_k

The ratio of entropy values:

S′ / S = (m_i − 1)(m_j + 1) / (m_i · m_j)

= 1 + (m_i − m_j − 1) / (m_i · m_j)

When m_i > m_j + 1:

S′ > S

Entropy strictly increases at every step, and the increment is directly related to the energy gradient before the transfer.

The larger the gradient—i.e., the larger m_i − m_j—the larger the entropy increment. This is precisely the equivalence, within this framework, between the "maximum entropy path" and the "maximum gradient path."

### V. The Precise Relationship Between the Two Laws

Within this framework, the relationship between the two laws of thermodynamics becomes remarkably clear:

First Law (Energy Conservation)
E = Σ m_i = const

This is a structural precondition, not a derivation. It determines the accessible state space of the system.

Second Law (Entropy Increase)
S = ∏ m_i

S(t+1) > S(t) for all allowed transfers

This is a dynamical output, not an external assumption. It is derived jointly from the gradient-driven rule and the multiplicative entropy form, rather than assumed separately.

The first law delineates the "surface of accessible states"; the second law specifies the "direction of actual motion on that surface."

They are not independent physical laws, but two complementary aspects of the same discrete dynamical system:

| Law | In this framework | Role |
| First Law | Σ m_i = const | Constraint: which states are accessible |
| Second Law | S = ∏ m_i monotonically increases | Direction: which path is actually selected among accessible states |

No statistical assumptions. No ensemble averages. No vague statements about "most probable." Every step is deterministic (or at most has several equal-gradient path branches), and every path is trackable.

### VI. Epistemological Level: How This New Form Helps One Grasp the Underlying Principles of Thermodynamics

Statistical entropy leaves us with the following picture: it presents the second law of thermodynamics as a statement about "probability" and "possibility."

"The entropy of an isolated system tends to increase";

"High-entropy states are more probable than low-entropy states";

"The system tends toward the most probable macrostate."

These statements are mathematically valid, but leave an open question at the conceptual level:

What does "tend" mean? If the system is only "more likely" to move toward a high-entropy state, is entropy increase a physical necessity or a statistical contingency?

This new form offers a different epistemological path. It does not rely on probability, and therefore does not rely on vague concepts like "tend" or "more likely." It directly shows:

As long as an energy gradient exists, energy will flow along the gradient; each step of flow increases the entropy value; this process has no exceptions and does not depend on any statistical assumptions.

This means that the second law of thermodynamics in this framework is no longer:

"An isolated system will most likely move toward a high-entropy state."

But rather:

"An isolated system with an energy gradient will necessarily redistribute its energy distribution along the gradient direction; this redistribution process is precisely the process of entropy increase."

The epistemological difference between the two is fundamental:

| Traditional statistical formulation | Formulation in this framework |
| Entropy increase is "probable" | Entropy increase is "necessary" |
| Entropy is "number of microstates" | Entropy is "product of energy distribution" |
| Second law depends on ensemble assumptions | Second law is directly derived from gradient-driven rules |
| Probability is a prerequisite | Probability is not a prerequisite; gradient is |
| Coarse-graining is necessary | Coarse-graining is not necessary |

This difference directly affects our understanding of the "arrow of time" and "irreversibility."

In this framework, irreversibility is written directly into the dynamical rules—energy flow along a gradient is irreversible, because reverse flow would require energy to move from low to high, which violates the precondition of gradient driving.

This means:

Irreversibility is not a statistical byproduct, but a direct product of gradient driving. The arrow of time does not come from "low initial entropy" or "ergodic assumptions," but from the fact that "an energy gradient exists."

VII. Summary at the Epistemological Level
Statistical entropy leaves an unavoidable picture at the epistemological level: it ties the second law of thermodynamics to "our ignorance of the system," which easily gives the impression that entropy increase is not a purely physical necessity.

This new form avoids this picture:

It does not measure ignorance; it measures the structure of energy distribution;

It does not depend on the observer's level of description; it depends only on the system's own energy values;

It is not a statement about "possibility"; it is a statement about "necessity";

It is not derived from probability; it is directly computed from gradient-driven rules.

In this sense, this new form helps people directly appreciate at the epistemological level:

Thermodynamics is not a statistical theory about "possibilities," but a structural theory about "how energy flows along gradients under conservation constraints."

The first law says: total energy does not change.

The second law says: as long as a gradient exists, energy will flow; as long as energy flows, entropy will increase.

Together they describe a single physical process: the redistribution of energy along gradient directions under conservation constraints.

This is an epistemological framework that is simpler, more direct, and closer to the underlying principles than the statistical formulation. It reduces thermodynamics to its most basic components:

Discrete energy units;

Conserved total constraint;

Energy gradients between adjacent nodes;

Energy transfer along gradient directions.

That is all.

### VIII. Conclusion

The multiplicative entropy proposed in this paper:

S = ∏ m_i

s.t. Σ m_i = E, m_i ∈ ℕ⁺

Transfer condition: m_i > m_j + 1

Transfer rule: m_i → m_i − 1, m_j → m_j + 1

Has the following characteristics:

Gradient-driven: entropy increase directly originates from the existence of energy gradients; the larger the gradient, the greater the entropy increment;

Non-probabilistic: does not depend on any probability distribution, ensemble assumptions, or ergodic assumptions;

Non-coarse-grained: does not depend on any artificially chosen scale or classification scheme;

High resolution: every energy transfer changes the entropy value, and paths are fully preserved;

Bound to the first law: energy conservation is the precondition for entropy increase; entropy increase is the necessary direction under the conservation constraint;

Ontological priority: it measures the distribution state of the system itself, rather than the observer's state of knowledge.

From an epistemological perspective, this new form reduces the two laws of thermodynamics from a "statistical formulation" to a "geometric-dynamical formulation," making entropy increase no longer a vague proposition dependent on probabilistic language, but an irreversible evolutionary process directly driven by energy gradients, trackable step by step.

In this framework, the underlying principles of thermodynamics are visible, understandable, and countable.

# It no longer answers "what we do not know." It answers: "what is happening, and how it is happening."

### Extending the Applicability of Multiplicative Entropy

A system can adopt a multiplicative entropy description if it satisfies the following conditions:

-The number of units carrying numerical values remains constant.

-Each unit is associated with a quantifiable value (e.g., energy, resource amount, or population size).

-The total sum of all unit values is conserved.

-The dynamical evolution follows a flow or exchange rule wherein quantities transfer from units with higher values to those with lower values.

-The numerical value carried by each unit could be unitized, i.e., expressed as an integer multiple greater than 1 of the basic unit. In other words, the value carried by any unit is a positive integer. The fifth condition is not a necessary requirement for the definition of numerical entropy itself. However, satisfying this condition ensures that the computed entropy value is an integer, which is particularly convenient for computer simulations and numerical implementations.




