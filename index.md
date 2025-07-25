---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: single
author_profile: true
---

The best introduction I can give for Ramsey Theory is this thought simulation: 

What is the least number of people in the party required such that at least some three of them are mutual strangers or some three of them are mutual friends?

Let that sink in for a second. The key idea behind Ramsey Theory is that If you have a large enough system (like a graph or a set of numbers), you're guaranteed to find a subsystem with a specific property, regardless of how you color, partition, etc it. To do this, we consider worst case through the Pigeonhole Principle. Ramsey Theory says "despite this, we always have same result."

Moving on, the Ramsey function is denoted by \\(R(a,b)\\) where any 2-coloring of a complete graph guarantees a complete subgraph of size \\(a\\) of one color (blue) **OR** a complete subgraph of size \\(b\\) of the other color (red).

Let's take an example: the thought simulation I said in the beginning. This is a famous example of \\(R(3,3)\\). Through case-work (pigeonhole), we get that **6** people (node-graph) are required to gurantee a subgraph of size 3 of red or blue (3 mutual strangers or friends). To prove that it isn't **5**, here is a coloring of a complete set of 5 nodes that does not have complete subgraph of size 3: ![K5](https://upload.wikimedia.org/wikipedia/commons/thumb/9/98/RamseyTheory_K5_no_mono_K3.svg/1024px-RamseyTheory_K5_no_mono_K3.svg.png)

An extended explanation of Ramsey Theory by Paul Erdos (former leading Ramsey Theorist) can be found here: 
<iframe width="560" height="315" src="https://www.youtube.com/embed/WgjCf3kC5EU?si=ECtxrcuTHuSddmV4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

Though this will be in the paper I will be making for MathQuantum in the future, I will show classical computation approaches (brute-force, SAT solving, symmetry reduction).

Lets get to the quantum side of the project. We were taught the basics of Quantum Computing and also an important key fact: Not all problems are faster solved with quantum computation. This is something I will mention in my paper. Based on intuition, I think Quantum computers **will** be faster. We will see though. Knowing the types of quantum optimization approaches (Grover's, annealing) which I can explore further as they weren't toucehd as much in the program can be useful for my research.

Next, the best part of the project is here: the comparison between classical and quantum methods. As said, the goal here isn't trying to make quantum "beat" classical. We just show how one might model the problem quantumly. Any advances on how quantum can be faster is definitely beyond the scope of my project and may need connection with professional professors.

There is a rising number of papers and research done on how Ramsey Theory may help Quantum computing. I find that this paper will do the converse. If I need to explain and utilize qubits, superposition, gates and get technical with the linear algebra, I will be ready as that knowledge was covered in the program.

Complex numbers are numbers with a *real component* and an *imaginary component*, in the form \\(a+bi\\), where a and b are **real numbers** and \\(i\\) is the **imaginary unit**.

An extended explanation of complex numbers can be found [here](https://en.wikipedia.org/wiki/Complex_number).

It can be helpful to visualize complex numbers on the complex plane:
![complex plane](https://upload.wikimedia.org/wikipedia/commons/5/5d/Imaginarynumber2.PNG)

Complex numbers can also be represented in polar form as below:
[![polar form](https://upload.wikimedia.org/wikipedia/commons/thumb/7/71/Euler%27s_formula.svg/250px-Euler%27s_formula.svg.png)](https://en.wikipedia.org/wiki/Polar_coordinate_system)

To understand how the polar form is derived, check out this video:
<iframe width="560" height="315" src="https://www.youtube.com/embed/lFT2hwsCMls?si=XLJKBa_SXol_bQ_D" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
