# Course Details

This course covers *quantum learning theory*, a contemporary subject at the intersection of quantum mechanics, quantum computing, statistical learning theory, and machine learning.  The core question of the subject is: how can we use quantum computation to efficiently learn properties of quantum mechanical systems?  Answering this question helps us understand the power of quantum computers in assisting experimental physicists with studying quantum materials and quantum chemical systems, while also providing valuable tools for quantum machine learning to develop algorithms based on quantum data.  Quantum learning theory has become a core subject in quantum information and computation, and this course is one of the first of its kind to present quantum learning theory in its entirety.  We will explore the theory of learning quantum states and quantum dynamics, the theory of quantum memory and quantum replica-learning, random and pseudo-random quantum circuits, and many applications to quantum many-body physics.

**Time/Location**: MW 3-4:15, Pierce 209

**Instructors**: Sitan Chen, Jordan Cotler
*Office hours*: Th 10:00-11:00, SEC 3.325; Tu 11-12, Goel 418


**Teaching Fellows**: Weiyuan Gong, Quynh Nguyen
*Office hours*: M 5-6 pm, Pierce G7A; W 2-3, 52 Oxford St B150
*Recitation*: Th 4-5pm, Maxwell Dworkin G115


[Canvas (for announcements)](https://canvas.harvard.edu/courses/158126/)
[Ed discussion forum](https://edstem.org/us/courses/85742/)
[Course Overleaf](https://www.overleaf.com/read/cxtmnnfnjqdk#94a28a) 

**Course Policies**: See [syllabus](/syllabus.pdf) for detailed overview.

### Lecture Notes:

|                    | Topic                                                                                      | Link                                                   | Readings                                                                                                                                                                                                                                                                            |
| ------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Lecture 1 (9/3)    | Vignette: Learning an Unknown Rotation                                                     | [pdf](/lecture1.pdf)                                   | - [HKOT23](https://arxiv.org/pdf/2302.14066): bootstrapping for learning arbitrary unitaries down to Heisenberg limit<br>- [GLM11](https://arxiv.org/pdf/1102.2318): review paper on quantum metrology                                                                              |
| Lecture 2 (9/8)    | Classical probability and tensors                                                          | [pdf](./lecture2.pdf)                                  |                                                                                                                                                                                                                                                                                     |
| Lecture 3 (9/10)   | Quantum mechanics basics I                                                                 | [pdf](./lecture3.pdf)                                  |                                                                                                                                                                                                                                                                                     |
| Lecture 4 (9/15)   | Quantum mechanics basics II                                                                | [pdf](./lecture4.pdf)                                  |                                                                                                                                                                                                                                                                                     |
| Lecture 5 (9/17)   | Tomography I:  single-copy measurements (entrywise error)                                  | [pdf](./lecture5.pdf)                                  | Bonus content: [notes on tensor networks](./tensor_networks.pdf)                                                                                                                                                                                                                    |
| Lecture 6 (9/22)   | Tomography II: single-copy measurements (operator norm)                                    | [pdf](./lecture6.pdf)                                  | - [KRT14](https://arxiv.org/pdf/1410.6913): original paper on tomography with single-copy random measurements<br>- [GKKT18](https://arxiv.org/pdf/1809.11162): paper that algorithm from lecture is based on                                                                        |
| Lecture 7 (9/24)   | Tomography III: multi-copy measurements (representation theory basics, Schur-Weyl duality) | [pdf](./lecture7.pdf)                                  | - [OW15](https://arxiv.org/pdf/1508.01907), [HHJWY15](https://arxiv.org/abs/1508.01797): original papers achieving optimal rate for tomography<br>- [W16](http://reports-archive.adm.cs.cmu.edu/anon/2016/CMU-CS-16-108.pdf): PhD thesis of Wright with exposition on these methods |
| Lecture 8 (9/29)   | Tomography IV: multi-copy measurements (Schur polynomials, pretty good measurement)        | [pdf](./lecture8.pdf)                                  |                                                                                                                                                                                                                                                                                     |
| Lecture 9 (10/1)   | Shadows I: Classical shadows                                                               | [pdf](./lecture9.pdf)                                  | - [CW19](https://arxiv.org/abs/1908.02754): overlapping quantum tomography (local observables)<br>- [HKP20](https://arxiv.org/abs/2002.08953): introduced classical shadows formalism                                                                                               |
| Lecture 10 (10/6)  | Shadows II: Finishing classical shadows; online state learing                              | [pdf](./lecture10.pdf)                                 | - [A17](https://arxiv.org/abs/1711.01053): introduced shadow tomography<br>- [ACHKN18](https://arxiv.org/abs/1802.09025): online state learning                                                                                                                                     |
| Lecture 11 (10/8)  | Shadows III: Shadow tomography via threshold search                                        | [pdf](./lecture11.pdf)                                 | -[BO20](https://arxiv.org/abs/2011.10908): state of the art guarantee for shadow tomography<br>- [BB22](https://arxiv.org/abs/2210.09155): matching bound via random sequential measurements                                                                                        |
| Lecture 12 (10/15) | Gibbs I: Introduction to Gibbs states                                                      | [pdf](./lecture12.pdf)                                 |                                                                                                                                                                                                                                                                                     |
| Lecture 13 (10/20) | Gibbs II: Learning high-temperature Gibbs states via cluster expansion                     | [pdf](./lecture13.pdf)                                 | - [HKT21](https://arxiv.org/abs/2108.04842): optimal high-temperature learning algorithm                                                                                                                                                                                            |
| Lecture 14 (10/22) | Gibbs III: Controlling terms in the cluster expansion                                      | [pdf](./lecture14.pdf)                                 |                                                                                                                                                                                                                                                                                     |
| Lecture 15 (10/27) | Gibbs IV: Newton-Raphson; Intro to low-temperature learning                                | [pdf-a](./lecture15a.pdf)<br>[pdf-b](./lecture15b.pdf) | - [BLMT23](https://arxiv.org/abs/2310.02243): first efficient low-temperature learning algorithm<br>- [CAN25](https://arxiv.org/pdf/2504.02706): efficient local low-temperature learning algorithm (this lecture)                                                                  |







### Psets:
- [Overleaf with tex files](https://www.overleaf.com/read/cxtmnnfnjqdk#94a28a)
- **Pset 1:** [pdf](./pset1.pdf) (out: 9/11, due: 9/25)
- **Pset 2:** [pdf](./pset2.pdf) (out: 9/25, due: 10/9)
- **Pset 3:** [pdf](./pset3.pdf) (out: 10/13, due: 10/27)
- **Pset 4:** [pdf](./pset4.pdf) (out: 10/29, due: 11/12)