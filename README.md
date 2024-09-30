# Example and Demo code for concepts related to Semantic Simulation and theory of Semantic Structures

## Semantic Simulation

### Modeling dynamic semantic distance via the evolution and aggergation of Semantic Structures 

The motion and the mutual positions of structures in semantic space are determined by the equations of evolution. Because the semantic structures are always in motion the distance between any two structures depends on the evolution of their positions in semantic space. Thus the semantic distance between any two structures $S_1$ and $S_2$, denoted with $sdist\left(S_1,S_2\right)$, is a dynamic quantity.

There are two mechanisms which will influence the aggregation / dispersal of Semantic Structures :

 * association / disassociation links which exert forces on small scales and help rearranging the mutual positions of semantic structures which are close enough to each other
 * semantic energy field which is subjected to tiny local alterations based on past inferences produced by semantic structures passing through those semantic locations.

The goal of the simulation is to prove that the semantic distances between semantic structures do not contradict the prescribed meaning of the latter. Let me expound on the last statement. For this purpose I need to introduce few definitions:

**Definition**: _Semantic context_ $\mathcal{C}$ \
The semantic structures enclosed in a given region of semantic space. The region does not need to be simply connected. In order a semantic structure $S$ to be **in** region $\mathcal{C}$ of semantic space $\mathbb{S}$ it needs to be enclosed by $\mathcal{C}$ in its entirety - that is, there should be no substructure $S_1 \in \\{ S \\}$ which is outside of $\mathcal{C}$. 

Let us consider the countable set  $\mathcal{S}$ of semantic structures $S_1, S_2, S_3, \dots, S_k, \dots$. Let $\mathcal{C}$ represents a region of semantic space which contains structures with sufficiently higher semantic mass than those in $\mathcal{S}$. We denote this assumption with $mass\(\mathcal{C}\) \gg mass\(\mathcal{S}\)$. Note, that $\mathcal{S}$ may be entirely included in $\mathcal{C}$, entirely outside of $\mathcal{C}$ or a part of $\mathcal{S}$ may be in $\mathcal{C}$. Let us consider the semantic structure composed by the semantic structures in $\mathcal{S}$ and allow those structures to _co-evolve_ with the structures in $\mathcal{C}$. In such scenario when the set $\mathcal{S}$ evolves over time given only the set $\mathcal{C}$ we say that $\mathcal{S}$ is given _in_ (or _relative to_) the context $\mathcal{C}$.  We denote the aggregate semantic structure $\mathcal{S}$ given in the context of $\mathcal{C}$ with the following notation $\langle \mathcal{S} \| \mathcal{C} \rangle$.


**Definition**: _Semantic Meaning_ of a set $\mathcal{S}$ of semantic structures in a context $\mathcal{C}$ \
Let us consider a countable set $\mathcal{S}$ of semantic structures $S_1, S_2, S_3, \dots, S_k, \dots$. Each structure $S_i$ is represented by its semantic signature $ssig\(S_i\) \in \mathbb{N}$. Let $S^{\mathcal{C}}$ denote an arbitrary semantic structure taken from $\mathcal{C}$. _Semantic Meaning_ of the set $\mathcal{S}$ in the context $\mathcal{C}$ is an ordered set of chains which is created in the following way: 

Let us denote with $\overset{S^{\mathcal{C}}, \mathcal{C}}{\leq}$ the total order induced by the numerical comparison opeprator $\leq$ applied to the  semantic distance $sdist\left(S^{\mathcal{C}},\cdot\right)$ on the set $\mathcal{S} \cup \left(\mathcal{C} \backslash S^{\mathcal{C}} \right)$ for a given $S^{\mathcal{C}} \in \mathcal{C}$.
Then the pair $\overset{S^{\mathcal{C}}, \mathcal{C}}{\leq},\ \mathcal{S} \cup \left(\mathcal{C} \backslash S^{\mathcal{C}}\right)$ defines a chain which we will denote using the following notation $\lfloor\mathcal{S} \cup \mathcal{C} \backslash S^{\mathcal{C}}\rceil$.  Obviously, $\lfloor\mathcal{S} \cup \mathcal{C} \backslash S^{\mathcal{C}}\rceil$ has a length $\big|\ \mathcal{S} \cup \left(\mathcal{C} \backslash S^{\mathcal{C}}\right)\big|$. We denote with $\langle \mathcal{S} \| \mathcal{C} \rangle$ the semantic structure composed by the semantic structures in $\mathcal{S}$ in the context $\mathcal{C}$. Then for each $S^{\mathcal{C}} \in \mathcal{C}$ we can compute $sdist\left( S^{\mathcal{C}}, \langle \mathcal{S} \| \mathcal{C} \rangle \right)$ and can order the sets  $S^{\mathcal{C}}$ by how close each one of them is to $\langle \mathcal{S} \| \mathcal{C} \rangle$. Therefore we can order the chains $\lfloor\mathcal{S} \cup \mathcal{C} \backslash S^{\mathcal{C}}\rceil$ for each $S^{\mathcal{C}} \in \mathcal{C}$. We will denote with  $\lfloor\mathcal{S} \cup \mathcal{C} \rceil$ the ordered in such fashion _aggregate chain_ composed of the ordered set of chains $\\{\lfloor\mathcal{S} \cup \mathcal{C} \backslash S^{\mathcal{C}}\rceil, S^{\mathcal{C}} \in \mathcal{C}\\}$.

Two semantic structures $S_1$ and $S_2$ have the same (semantic) meaning in the context $\mathcal{C}$ if each of them induce the same aggregate chain $\lfloor\mathcal{S} \cup \mathcal{C} \rceil$.

