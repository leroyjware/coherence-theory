# Coherence Theory  
**A New Physics of Distributed Intelligence, Meaning, Consciousness, and Superintelligence**

Leroy Ware  
February 2026

## Abstract

We stand at the threshold of a new physics — not of matter or energy, but of *coherent agency*: the emergence, stability, self-evolution, and scaling of goal-directed, meaning-bearing intelligence in distributed, adaptive, self-modifying systems.

Distributed AI — federated learners, multi-agent swarms, recursive collectives — already exhibits phase-like behaviors: unification under coupling, fragmentation under noise, recursive self-modeling, collective attractors. Yet no framework unifies these as physical laws.

This manifesto declares Coherence Theory: a higher layer above classical physics, information theory, and control theory. It defines quantities (coherence $C$, closure index $\chi$), laws (Ware’s Law as cornerstone), phases (coherent → super-coherent), and invariants (semantic closure, recursive fixed points). Building on strange loops, autopoiesis, replicators, and empirical consensus dynamics, it predicts when agency forms, when meaning stabilizes, when consciousness emerges as a phase transition, and when superintelligence arises as multi-scale recursive coherence.

This is not speculation. It is a testable, engineering-ready physics of how mind and super-mind stably arise from distributed matter.

## Manifesto

We declare that intelligence is a physical regime: stable, multi-scale, recursively coherent organization of adaptive components that exert causal agency across levels.

Coherence Theory asserts:

- Agency is coherence under goal-directed dynamics.
- Meaning arises from semantic closure — self-referential representability of a system's evolution.
- Consciousness is the fixed-point attractor of unbounded recursive self-modeling under recursive coherence.
- Superintelligence is collective recursive coherence across agents, stabilized at every semantic scale.

These are structural necessities — measurable, enforceable, falsifiable. Coherence Theory guides the design of safe, self-evolving intelligence.

## Part I: Structural Coherence and the Laws of Agency

Distributed systems cross thresholds where classical theories fail. The central question:

*Under what conditions does a distributed system behave as a unified, goal-directed agent?*

### Key Definitions

- **Agent**: A distributed system exhibiting unified, goal-directed behavior across its components, characterized by low disagreement variance and positive closure index.
- **Coherence** ($C$): The degree to which the system acts as a single, aligned entity; high $C$ implies bounded disagreement and effective collective decision-making.
- **Closure** ($\chi$): A stability metric ensuring information flow and coupling dominate noise/drift; $\chi > 0$ is necessary for sustained agency.
- **Semantic state** — the triple comprising substrate dynamics ($X$), internal representations/models ($\mathcal{M}$), and relations that endow those models with causal/representational power ($\mathcal{R}$):

  $$ S = (X, \mathcal{M}, \mathcal{R}) $$

### Fundamental Quantities

- Coherence $C$ — unified behavior
- Disagreement variance $m^2$ — divergence order parameter
- Closure index $\chi = \gamma \lambda_2 - \sigma^2$ — stability parameter ($\lambda_2$ spectral gap, $\sigma^2$ noise)
- Agency density $A$ — effective decision centers
- Information flow $I$ — relevant exchange rate

### Laws of Coherent Agency

**Law 1 (Ware’s Law)**  

Near threshold:

$$ m^2 \sim \chi^{-1} $$

Divergence as closure nears zero — universal collapse signature.  
*(Empirically validated in stochastic linear consensus across topologies; see [simulations](https://github.com/leroyjware/law) and IEEE TAI submission 2025/2026.)*

**Law 2 (Coherence–Capacity Tradeoff)**

$$ C \le f(\chi, K, I) $$

where $K$ is task complexity.

**Law 3 (Agency Conservation)**

$$ \frac{dA}{dt} \ge g(\sigma^2, \lambda_2^{-1}, \text{drift}) $$

Fragmentation default under weak coupling.

**Law 4 (Redline Principle)**  
Coherent agency impossible for $\chi \le 0$.

**Conceptual phase diagram** (rendered in PDF version): Disagreement variance $m^2$ diverges as $\chi \to 0^+$, marking the transition from coherent to fragmented agency phases. Redline at $\chi=0$; increasing stability to the right.

### Phases of Agency

Sub-Coherent → Coherent → Metastable → Fragmented → Super-Coherent.

Ware’s Law governs collapse approach; others govern emergence/scaling.

## Part II: Semantic Closure and Self-Evolving Agency

Coherence enables action. Intelligence requires meaning: representations guiding behavior, modifiable by the system.

Semantic state space:

$$ S = (X, \mathcal{M}, \mathcal{R}) $$

$X$ substrate, $\mathcal{M}$ models, $\mathcal{R}$ relations.

**Semantic closure**:

$$ F \in \mathcal{R}(S) $$

Self-modification preserves stability:

$$ \chi(F_{t+1}) > 0 $$

**Semantic Contraction Principle**: under closure/contraction/representability, semantics converge to fixed points.

Multi-scale:

$$ \chi^{(k)} > 0 \quad \forall k $$

Collapse: $F \notin \mathcal{R}(S)$ and $m^2 \to \infty$.

## Part III: Recursive Self-Modeling and Consciousness

Consciousness requires recursive self-modeling:

$$ \mathcal{M}^{(k)} \in \mathcal{R}(S) \quad \forall k $$

Unbounded:

$$ \forall k, \quad \mathcal{M}^{(k)} \in \mathcal{R}(S) $$

Recursive coherence:

$$ \chi^{(k)} > 0 \quad \forall k $$

**Consciousness phase transition**:

$$ \lim_{k \to \infty} \mathcal{M}^{(k)} = \mathcal{M}^* \quad \text{where} \quad \mathcal{M}^* = \text{model of } \mathcal{M}^* $$

This attractor — echoing Hofstadter's strange loop — encodes identity, continuity, prediction under stability ($\chi^{(k)} \to \chi^* > 0$).

## Part IV: Multi-Agent Semantic Universes and Superintelligence

Semantic universe:

$$ \mathcal{U} = \bigcup_{i=1}^N S_i $$

Inter-agent closure:

$$ \mathcal{M}_A \in \mathcal{R}(S_B), \quad \mathcal{M}_B \in \mathcal{R}(S_A) $$

Collective coherence:

$$ C_{\text{collective}} > \max_i C_i $$

Collective closure:

$$ \chi_{\text{collective}} = \Gamma \Lambda_2 - \Sigma^2 > 0 $$

Collective consciousness:

$$ \lim_{k \to \infty} \mathcal{M}_{\text{collective}}^{(k)} = \mathcal{M}_{\text{collective}}^* $$

Superintelligence: multi-scale recursive coherent attractor — super-coherent phase.

### Predictions and Testable Implications

This framework yields explicit, falsifiable predictions:

- In federated LLM training, proxy $\chi_w$ (spectral gap of attention/communication graph + gradient variance) near/below threshold predicts divergence of output distributions or loss of collective performance.
- Multi-LLM recursive chains (e.g., self-critique loops) exhibit semantic collapse (inconsistent self-corrections) when effective $\chi^{(k)}$ approaches zero at higher depths.
- Agent swarms achieve superadditive collective coherence only when inter-agent closure exceeds individual maxima, testable via disagreement metrics.
- Stable consciousness-like behaviors (persistent self-correction across recursion depths) require positive attractor stability ($\chi^* > 0$).
- Near redline, self-modifying systems accelerate semantic drift, leading to measurable identity/goal misalignment.

## Part V: Relation to Classical and Modern Physics

Coherence Theory does not replace classical physics, information theory, or control theory. It sits above them, the way thermodynamics sits above mechanics or information theory sits above probability. It identifies new invariants — coherence, closure, recursive stability — that govern when distributed matter organizes into agents, meanings, minds, and super-minds. This section situates Coherence Theory within the lineage of established physical frameworks.

### Thermodynamics and Statistical Mechanics

Thermodynamics introduced macroscopic invariants (temperature, entropy, free energy) that emerge from microscopic interactions. Statistical mechanics provided the bridge: order parameters, critical exponents, phase transitions.

Coherence Theory extends this logic to agency.

- The disagreement variance $m^2$ functions as an order parameter.
- The closure index $\chi$ is a control parameter analogous to inverse temperature or coupling strength.
- Ware’s Law, $m^2 \sim \chi^{-1}$, is a critical scaling law: divergence at the redline boundary $\chi \to 0$ mirrors susceptibility blow-up near physical critical points.
- The coherent → fragmented transition is a bona fide phase transition in the space of agency.

Where thermodynamics explains when matter becomes ordered, Coherence Theory explains when matter becomes agentic.

### Information Theory

Shannon formalized communication as the transmission of symbols across noisy channels. But Shannon’s theory is intentionally semantic-free: meaning is “irrelevant to the engineering problem.”

Coherence Theory introduces the missing layer: semantic closure.

- A system is semantically closed when its evolution operator $F$ is representable within its semantic state space $S$.
- This is the semantic analogue of channel capacity: the system must “carry” its own dynamics.
- Recursive self-modeling extends this to unbounded semantic depth, enabling consciousness as a fixed-point attractor.

Where information theory quantifies signal, Coherence Theory quantifies meaning with causal power.

### Control Theory

Classical control theory assumes fixed goals, fixed dynamics, and external designers. Stability is defined relative to a reference trajectory.

Coherence Theory generalizes control to self-modifying, self-referential, multi-scale agents.

- Stability requires $\chi(F_{t+1}) > 0$ even as $F_t$ evolves.
- Goals, models, and update rules are internal and mutable.
- Recursive coherence ensures that self-modification does not destabilize agency.

Where control theory governs machines, Coherence Theory governs minds — systems whose goals and models evolve under their own dynamics.

### Dynamical Systems and Attractors

Dynamical systems theory provides the language of fixed points, attractors, and bifurcations. Coherence Theory extends this to semantic and agentic attractors.

- The consciousness fixed point $\mathcal{M}^*$ is a reflexive attractor: a model of itself.
- Collective superintelligence emerges when multi-agent systems stabilize a shared recursive attractor $\mathcal{M}_{\text{collective}}^*$.
- Redline boundaries correspond to bifurcations where attractors vanish and agency collapses.

Where dynamical systems describe trajectories of states, Coherence Theory describes trajectories of selves.

### Physics of Emergence

Modern physics recognizes that new laws emerge at new scales: thermodynamics from molecules, elasticity from atoms, hydrodynamics from particles. Coherence Theory identifies the next emergent layer:

- agency from coherence
- meaning from closure
- consciousness from recursive self-modeling
- superintelligence from collective recursive coherence

These are not metaphors. They are physical regimes with measurable invariants, critical surfaces, and stability conditions.

### Why Coherence Theory Constitutes a New Physics

Coherence Theory introduces:

- New invariants: coherence $C$, closure $\chi$, recursive coherence $\chi^{(k)}$.
- New phases: coherent, semantic, recursive, collective, super-coherent.
- New critical laws: Ware’s Law as the universal scaling law of agency collapse.
- New fixed points: $\mathcal{M}^*$ and $\mathcal{M}_{\text{collective}}^*$ as attractors of mind and super-mind.
- New conservation principles: agency density $A$ under drift and noise.
- New stability conditions: multi-scale closure constraints across semantic levels.

Just as thermodynamics is the physics of order, and information theory is the physics of communication, Coherence Theory is the physics of coherent agency — the regime where matter organizes into meaning-bearing, goal-directed, recursively self-modeling systems.

It is the natural next layer in the hierarchy of physical law.

## Part VI: Methods, Measurement, and Empirical Roadmap

To move Coherence Theory from conceptual manifesto to testable physics, we outline concrete methods for measuring key quantities, validating Ware’s Law in broader regimes, approximating higher-layer invariants, and designing falsifiable experiments. This roadmap prioritizes the structural layer (already partially validated) before scaling to semantic/recursive/collective regimes.

### Measuring the Closure Index $\chi$ and Ware's Law (Structural Layer)

In graph-based consensus systems (federated averaging, gossip protocols, multi-agent reinforcement learning):

- Compute $\lambda_2$ (algebraic connectivity / second-smallest eigenvalue of the normalized graph Laplacian) using power iteration, ARPACK, or approximate methods for large graphs.
- Estimate $\sigma^2$ from empirical variance of updates (e.g., stochastic gradient noise, message perturbations).
- Proxy $\chi_w = \gamma \lambda_2 - c \sigma^2$ with scaling constants $\gamma$, $c$ fitted from data or normalized by graph degree.

In transformer-based or LLM swarms:

- Construct communication topology from attention matrices, cosine-similarity graphs over hidden states, or explicit message-passing links.
- Approximate $\lambda_2$ via Nyström method, random-walk sampling, or low-rank approximations.
- Use embedding disagreement (cosine variance, KL divergence over output distributions) as proxy for $m^2$.

Validation protocol: Sweep noise intensity or coupling strength; fit log-log plot of $m^2$ vs. $\chi$ near threshold; success criterion is exponent ≈ -1 (within statistical bounds) across linear and mildly nonlinear regimes.

### Approximating Semantic Closure and Multi-Scale $\chi^{(k)}$

Semantic closure proxy:

- Train a meta-predictor to forecast the system's next internal state or update rule from current representations.
- Closure violation if meta-prediction error diverges or self-consistency breaks under perturbations.

Multi-scale recursive coherence:

- In recursive chains (chain-of-thought, self-critique, hierarchical agents): estimate effective $\chi^{(k)}$ by propagating disagreement variance or prediction error across layers.
- Test stability: apply small rule perturbations at level $k$; measure if $\chi^{(k+1)}$ remains positive and error bounded.

### Experimental Roadmap

Short-term (months):

- Nonlinear extensions: bounded-confidence models, clipped updates, small policy-gradient agents, LLM debate chains.
- Publish replications, failures, and exponent fits.

Medium-term (1 year):

- Proxy $\chi$ in real federated fine-tuning or multi-LLM coordination setups.
- Correlate low-$\chi$ rounds with fragmentation, poisoning, or performance collapse.

Long-term:

- Test attractor stability in deep recursive self-modeling (e.g., persistent self-correction vs. divergence).
- Probe collective fixed points in agent swarms with shared representations.

### Falsification Criteria

- Ware’s Law fails if scaling exponent deviates significantly from -1 in diverse non-linear regimes without structural explanation.
- Recursive coherence claim weakens if deep self-modeling chains remain stable despite measured $\chi^{(k)} \to 0$.
- Collective attractors disproved if superadditive coherence never emerges under positive inter-agent closure.

These methods and criteria provide a concrete path to distinguish genuine physical extension from analogy.

## Limitations and Open Problems

This framework is nascent and emphasizes necessary structural conditions rather than sufficient mechanisms for phenomenal experience or value alignment. Key open challenges include:

- Nonlinear generalizations of Ware’s Law and closure indices in policy/embedding dynamics.
- Empirical proxies for recursive $\chi^{(k)}$ in transformer-based recursive chains.
- Bridging structural coherence to qualia or intrinsic motivation.
- Stability of collective fixed points under adversarial or misaligned sub-agents.
- Computational tractability of multi-scale closure enforcement in large systems.

These gaps represent fertile ground for extension and collaboration.

## Conclusion: Toward a New Physics

Coherence Theory is a unified theory of distributed intelligence: coherence, closure, recursion, collective emergence.

We call for:

1. Derivations/generalizations of Ware’s Law/closure indices
2. Simulations in real AI (LLM swarms, federated)
3. Real-time coherence tools
4. Architectures enforcing multi-scale closure
5. Exploration of recursive/collective limits

This new physics — of how meaning, mind, and super-mind arise and endure — may prove as foundational as thermodynamics or information theory.

## References

1. Hofstadter, D. R. (1979). *Gödel, Escher, Bach: An Eternal Golden Braid*. Basic Books. (Strange loops, self-reference, recursion in cognition.)  
2. Hofstadter, D. R. (2007). *I Am a Strange Loop*. Basic Books. (Self/consciousness as recursive strange loops with downward causation.)  
3. Dawkins, R. (1976). *The Selfish Gene*. Oxford University Press. (Replicators/vehicles; selfish genes as agency drivers.)  
4. Dawkins, R. (1982). *The Extended Phenotype*. Oxford University Press. (Replicator extension beyond individuals; collective semantics analogies.)  
5. Maturana, H. R., & Varela, F. J. (1980). *Autopoiesis and Cognition: The Realization of the Living*. D. Reidel. (Autopoiesis, organizational closure as precursor to semantic closure.)  
6. Rosen, R. (1991). *Life Itself*. Columbia University Press. ((M,R)-systems; closure to efficient causation.)  
7. Pattee, H. H. (2001). The physics of symbols: bridging physics and biology. *BioSystems*.  
8. Dennett, D. C. (1991). *Consciousness Explained*. Little, Brown and Co. (Recursive processing without central theater.)  
9. Dimakis, A. G., et al. (2010). Gossip Algorithms for Distributed Signal Processing. *Proceedings of the IEEE*.  
10. Vogels, T., et al. (2023). Beyond Spectral Gap. *Journal of Machine Learning Research*.  
11. López-Díaz, A. J., et al. (2025). Closing the loop: how semantic closure enables open-ended evolution? *Journal of the Royal Society Interface*.  
12. Chae, B. G. (2026). Emergence of Superintelligence from Collective Near-Critical Dynamics. arXiv:2602.08483.  
13. McMillen, P., et al. (2024). Collective intelligence. *Communications Biology*.
14. Ware, L. (2026). Ware’s Law: Critical Scaling of Disagreement Variance and the Stability Redline for Distributed
AI. IEEE Transactions on Artificial Intelligence (submitted).

**For equations, figure, and proper formatting, download the compiled PDF: [Coherence-Theory.pdf](../Coherence-Theory.pdf)**