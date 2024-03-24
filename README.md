# Example and Demo code for concepts related to Semantic Simulation and theory of Semantic Structures

## Semantic Simulation

### Modeling dynamic semantic distance via the evolution and aggergation of Semantic Structures 

The motion and the mutual positions of structures in semantic space are determined by the equations of evolution. Because the semantic structures are always in motion the distance between any two structures depends on the evolution of their positions in semantic space. Thus the semantic distance between any two structures $S_1$ and $S_2$, denoted with $sdist\left(S_1,S_2\right)$, is a dynamic quantity.

There are two mechanisms which will influence the aggregation / dispersal of Semantic Structures :

 * association / disassociation links which exert forces on small scales and help rearranging the mutual positions of semantic structures which are close enough to each other
 * semantic energy field which is subjected to tiny local alterations based on past inferences produced by semantic structures passing through those semantic locations.

The goal of the simulation is to prove that the semantic distances between semantic structures do not contradict the prescribed meaning of the latter. Let me expound on the last statement. For this purpose I need to introduce few definitions:

**Definition**: _Semantic context_ $\mathcal{C}$ \
The semantic structures enclosed in a given region of semantic space. The region does not need to be simply connected. In order a semantic structure $S$ to be **in** region $\mathcal{C}$ of semantic space $\mathbb{S}$ it needs to be enclosed by $\mathcal{C}$ in its entirety - that is, there should be no substructure $S_1 \in S$ which is outside of $\mathcal{C}$. 

**Definition**: _Prescribed Meaning_ of a set $\mathcal{S}$ of semantic structures in a context $\mathcal{C}$ \
Let us consider a countable set $\mathcal{S}$ of semantic structures $S_1, S_2, S_3, \dots, S_k, \dots$. Each structure $S_i$ is represented by its semantic signature $ssig\(S_i\) \in \mathbb{N}$. Let $S^{\mathcal{C}}$ denote an arbitrary structure semantic taken from $\mathcal{C}$. _Prescribed Meaning_ of the set $\mathcal{S}$ in the context $\mathcal{C}$ is the total order induced by the numerical comparison opeprator $\leq$ applied to the  semantic distance $sdist\left(S^{\mathcal{C}},\cdot\right)$ on the set  $\mathcal{S}$ for each $S^{\mathcal{C}} \in \mathcal{C}$.
