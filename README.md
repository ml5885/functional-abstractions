# **Functional Abstractions in Latent Space**

**Do language models learn functional abstractions?** In computer science, functional abstractions allow us to express computations independently of the particular values they operate on. Concepts such as variable binding, function composition, and parametric polymorphism enable the same computational structure to be reused across fundamentally different inputs.

This project investigates whether analogous abstractions emerge in the latent representations of language models. In particular, can we identify representations that encode not *what* something is, but *what role it plays in a computation*? We use causal abstraction and distributed alignment search (DAS) to investigate the existence of such content-independent representations, using multi-hop factual recall as an initial experimental testbed.
