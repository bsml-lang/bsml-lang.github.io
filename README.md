<img src="/images/bsml_logo.png"
     alt="BSML Logo" width="128px"/>

# BSML: Bulk Synchronous Parallel ML

If parallel programming is to become as widespread as sequential programming, the languages supporting it should incorporate all the standard abstraction mechanisms including higher order functions, recursion, pattern matching, etc.. Yet for such languages to be practical scalable programming tools, abstraction should not come at the price of predictable performance. Unfortunately many parallel languages don't describe data placement so that performance is not predictable as a function of the source program. This is because data placement depends on the language implementation, not its semantics.

On the contrary, the bulk synchronous parallel (BSP) computing paradigm demonstrates that programs explicitly written for a static number p of processors can have predictable execution costs on a wide variety of architectures. But the combination of BSP algorithms with high-level language features is not well understood so that the evolution of BSP languages is hindered. We are investigating this question from a functional programming perspective.

We have obtained extensions of the lambda-calculus with BSP operations (BSlambda) basis for the design of a functional bulk synchronous parallel language (Bulk Synchronous Parallel ML or BSML).

A library for the [OCaml](https://ocaml.org) language, called BSML, has been designed. It implements all our flat BSP operations. Many extensions have been added to this core calculus. We investigated in the [Caraml](http://frederic.loulergue.eu/www_Caraml) project the use of variants of the BSML library for meta-computing. In the [Propac](http://frederic.loulergue.eu/PROPAC) project we improved the safety of parallel programming based on BSML. In the [PaPDAS](https://www.univ-orleans.fr/lifo/traclifo/PaPDAS/) project we use BSML to implement a verified prototype of algorithmic skeleton library.

## Software

### The BSML Library

- Try BSML Online!
- Beta version : BSML 0.5.4pre
- Current version : BSML v0.5 (bsml-0.5.tar.gz, bsml-0.5_manual.pdf)
- Old versions : ​v0.4 ​v0.26, ​v0.25, ​v0.2, ​v0.1

### Libraries for BSML

- A BSPlib-like API for BSML ​bsml_bsplib_api-0.1.tar.gz

### Related Software

- MultiML: MultiML
- Departmental Metacomputing ML: DMML
- Minimally Synchronous Parallel ML: MSPML

## Semantics and Verification

- Certified BSML programs with Coq: v0.1, v0.2
- Formal Semantics of Revised BSML in Coq v0.1alpha
- Related project: [SyDPaCC](https://sydpacc.github.io)

## Team Members

- Frédéric Loulergue (LIFO, University of Orléans, France)
- Wadoud Bousdira (LIFO, University of Orléans, France)
- Past members: Julien Tesson, Gaétan Hains, Olivier Ballereau, Armelle Merlin, David Billiet, Dimitri Louis-Régis, Radia Benheddi, Céline Ansault, Ilias Garnier, Louis Gesbert, Guillaume Petiot, Frédéric Gava

Logo design: Clotilde Touze

## Publications

### 2017

- Frédéric Loulergue. A BSPlib-style API for Bulk Synchronous Parallel ML. Scalable Computing: Practice and Experience, 18:261--274, 2017
- Frédéric Loulergue. A verified accumulate algorithmic skeleton. In Fifth International Symposium on Computing and Networking (CANDAR), pages 420--426, Aomori, Japan, November 19-22, IEEE, 2017
- Frédéric Loulergue. Implementing Algorithmic Skeletons with Bulk Synchronous Parallel ML. In Parallel and Distributed Computing, Applications and Technologies (PDCAT), pages 461--468, IEEE, 2017
- Frédéric Loulergue. Imperative BSPlib-style Communications in Bulk Synchronous Parallel ML. In International Conference on Computational Science (ICCS), Procedia Computer Science, Zurich, Switzerland, Elsevier, 2017
- Loulergue Frédéric, Wadoud Bousdira, and Julien Tesson. ​Calculating Parallel Programs in Coq using List Homomorphisms. In International Journal of Parallel Programming, volume 45, issue 2, pp. 300-319, 2017

### 2015

- Loulergue Frédéric, Wadoud Bousdira, and Julien Tesson. Calcul de programmes parallèles avec Coq. In Nicolas Ollinger, editor, École des Jeunes Chercheurs en Informatique Mathématique, collection Alpha. CNRS Éditions, 2015

### 2014

- Kento Emoto, Frédéric Loulergue, and Julien Tesson. A Verified Generate-Test-Aggregate Coq Library for Parallel Programs Extraction. In ITP, LNCS. Springer, 2014.
- Frédéric Loulergue, Simon Robillard, Julien Tesson, Joeffrey Legaux, and Zhenjiang Hu. ​Formal Derivation and Extraction of a Parallel Program for the All Nearest Smaller Values Problem. In ACM Symposium on Applied Computing (SAC), pages 1577-1584. ACM Press, 2014
Frédéric Loulergue, Virginia Niculescu, and Julien Tesson. Implementing powerlists with Bulk Synchronous Parallel ML. In SYNASC. IEEE, 2014

### 2012

- Wadoud Bousdira, Frédéric Loulergue, and Julien Tesson. A Verified Library of Algorithmic Skeletons on Evenly Distributed Arrays. In ICA3PP 2012, pages 218-232, LNCS. Springer, 2012

### 2011

- Julien Tesson, Environnement pour le développement et la preuve de correction systématiques de programmes parallèles fonctionnels. PhD Thesis, LIFO, University of Orléans, November 2011
- Frédéric Gava, Louis Gesbert, and Frédéric Loulergue. Type System for a Safe Execution of Parallel Programs in BSML. In 5th ACM SIGPLAN workshop on High-Level Parallel Programming and Applications. pages 27-34, ACM, 2011
- N. Javed, F. Loulergue, J. Tesson, and W. Bousdira. Prototyping a Library of Algorithmic Skeletons with Bulk Synchronous Parallel ML. In The 2011 International Conference on Parallel and Distributed Processing Techniques and Applications (PDPTA'11). pages 520-526, CSREA Press, 2011
- J. Tesson and F. Loulergue. ​A Verified Bulk Synchronous Parallel ML Heat Diffusion Simulation. In 11th International Conference on Computational Science (ICCS 2011), Procedia Computer Science. pages 36-45, Elsevier, 2011
- W. Bousdira, L. Gesbert, and F. Loulergue. ​Syntaxe et sémantique de Revised Bulk Synchronous Parallel ML. In S. Conchon and A. Mahboubi, editors, Journées Francophones des Langages Applicatifs (JFLA). INRIA, 2011
- F. Gava, S. Tan. Implémentation et prédiction des performances de squelettes data-parallèles en utilisant un langage BSP de haut niveau. In S. Conchon and A. Mahboubi, editors, Journées Francophones des Langages Applicatifs (JFLA). INRIA, 2011

### 2010

- L. Gesbert, F. Gava, F. Loulergue, and F. Dabrowski. ​Bulk Synchronous Parallel ML with Exceptions. Future Generation Computer Systems, 26:486-490, 2010
- I. Garnier and F. Gava. CPS Implementation of a BSP Composition Primitive with Application to the Implementation of Algorithmic Skeletons. Parallel, Emergent and Distributed Systems, 2010
- W. Bousdira, F. Gava, L. Gesbert, F. Loulergue, and G. Petiot. ​Functional Parallel Programming with Revised Bulk Synchronous Parallel ML. In Koji Nakano, editor, 2nd International Workshop on Parallel and Distributed Algorithms and Applications (PDAA). IEEE Computer Society, 2010.
- Wadoud Bousdira, Frédéric Loulergue, Louis Gesbert, ​Syntaxe et sémantique de Revised Bulk Synchronous Parallel ML, Research Report 2010-12, LIFO, University of Orléans, 2010

### 2009

- L. Gesbert. Développement systématique et sûreté d'exécution en programmation parallèle structurée. PhD thesis, University Paris Est, LACL, 2009
- F. Gava and I. Garnier. New Implementation of a BSP Composition Primitive with Application to the Implementation of Algorithmic Skeletons. In Workshop APDCM part of IPDPS 2009. IEEE Press, 2009

### 2008

- F. Gava. A Modular Implementation of Parallel Data Structures in BSML. Parallel Processing Letters, 18(1):39-53, 2008
- F. Gava. BSP Functional Programming; Examples of a cost based methodology. In M. Bubak, G. D. van Albada, J. Dongarra, and P. M. A. Sloot, editors, The International Conference on Computational Science (ICCS), Part I, volume 5101 of LNCS, pages 375-385. Springer-Verlag, 2008

### 2007

- L. Gesbert and F. Loulergue. ​Semantics of an Exception Mechanism for Bulk Synchronous Parallel ML. In International Conference on Parallel and Distributed Computing, Applications and Technologies (PDCAT), pages 201-208. IEEE Computer Society, 2007
- F. Gava. Implementation of the Parallel Superposition in Bulk-Synchronous Parallel ML. In Y. Shi, G.D.v. Albada, J. Dongarra, and P.M.A. Sloot, editors, The International Conference on Computational Science (ICCS), Part I, volume 4487 of LNCS, pages 611-619. Springer-Verlag, 2007

### 2006

- L. Gesbert, F. Gava, F. Loulergue, and F. Dabrowski. Bulk Synchronous Parallel ML with Exceptions. In Peter Kacsuk, Thomas Fahringer, and Zsolt Nemeth, editors, Distributed and Parallel Systems (DAPSYS 2006), pages 33-42. Springer, 2006
- L. Gesbert, F. Gava, F. Loulergue, and F. Dabrowski. Bulk Synchronous Parallel ML avec exceptions. In Rencontres Francophones du Parallélisme (Renpar'17), 2006
- F. Loulergue, R. Benheddi, F. Gava, and D. Louis-Regis. Bulk Synchronous Parallel ML: Semantics and Implementation of the Parallel Juxtaposition. In International Computer Science Symposium in Russia (CSR 2006), volume 3967 of LNCS, pages 475-486. Springer, 2006
- F. Loulergue. A Calculus of Functional BSP Programs with Projection. In International Parallel & Distributed Processing Symposium, 8th Workshop on Advances in Parallel and Distributed Computational Models. IEEE Computer Society Press, 2006
- F. Gava. Une implantation de la juxtaposition parallèle. In P.-E. Moreau and T. Hardin, editors, Journées Francophones des Langages Applicatifs (JFLA). INRIA, 2006.

### 2005

- F. Gava and F. Loulergue. A Static Analysis for Bulk Synchronous Parallel ML to Avoid Parallel Nesting. Future Generation Computer Systems, 21(5):665-671, 2005
- F. Gava. External Memory in Bulk Synchronous Parallel ML. Scalable Computing: Practice and Experience, 6(4):43-70, December 2005
- F. Gava. Approches fonctionnelles de la programmation paralléle et des méta-ordinateurs. Sémantiques, implantations et certification. PhD thesis, University Paris Val-de-Marne, LACL, 2005
- F. Loulergue, F. Gava, and D. Billiet. Bulk Synchronous Parallel ML: Modular Implementation and Performance Prediction. In Vaidy S. Sunderam, G. Dick van Albada, Peter M. A. Sloot, and Jack Dongarra, editors, International Conference on Computational Science (ICCS), LNCS 3515, pages 1046-1054. Springer, 2005.
- F. Gava. Implementation of Parallel Data Structures in BSML. In F. Loulergue and A. Tiskin, editors, Third International Workshop on High-Level Parallel Programming and Applications (HLPP 2005), pages 161-174, June 2005.

### 2004

- F. Loulergue. A Calculus of Functional BSP Programs with Explicit Substitution. In G. Joubert, W. Nagel, F. Peters, and W. Walter, editors, Parallel Computing: Software Technology, Algorithms, Architectures and Applications, Proceedings, pages 127-134, Dresden, 2004. North Holland - Elsevier
- F. Gava and F. Loulergue. Semantics of a Functional Bulk Synchronous Parallel Language with Imperative Features. In G. Joubert, W. Nagel, F. Peters, and W. Walter, editors, Parallel Computing: Software Technology, Algorithms, Architectures and Applications, Proceedings, pages 95-102, Dresden, 2004. North Holland - Elsevier
- F. Gava. Parallel I/O in Bulk Synchronous Parallel ML. In M. Bubak, D. van Albada, P. Sloot, and J. Dongarra, editors, The International Conference on Computational Science (ICCS 2004), Part III, LNCS, pages 339-346. Springer Verlag, 2004
- F. Gava. Une bibliothèque certifiée de programmes fonctionnels BSP. In Ménissier-Morain, V., editor, Journées Francophones des Langages Applicatif, JFLA, pages 55-68. INRIA, january 2004

### 2003

- F. Gava. Formal Proofs of Functional BSP Programs. Parallel Processing Letters, 13(3):365-376, 2003
- F. Gava, F. Loulergue, and F. Dabrowski. A Parallel Categorical Abstract Machine for Bulk Synchronous Parallel ML. In W. Dosch and R. Y. Lee, editors, 4th International Conference on Software Engineering, Artificial Intelligence, Networking, and Parallel Distributed Computing (SNPD'03), pages 293-300. ACIS, 2003.
- F. Dabrowski, F. Loulergue, and F. Gava. Pattern Matching of Parallel Values in Bulk Synchronous Parallel ML. In W. Dosch and R. Y. Lee, editors, 4th International Conference on Software Engineering, Artificial Intelligence, Networking, and Parallel Distributed Computing (SNPD'03), pages 301-308. ACIS, 2003.
- F. Loulergue. Parallel Juxtaposition for Bulk Synchronous Parallel ML. In H. Kosch, L. Boszorményi, and H. Hellwagner, editors, Euro-Par 2003, number 2790 in LNCS, pages 781-788. Springer Verlag, 2003.
- F. Gava and F. Loulergue. A Polymorphic Type System for Bulk Synchronous Parallel ML. In V. Malyshkin, editor, Seventh International Conference on Parallel Computing Technologies (PaCT 2003), number 2763 in LNCS, pages 215-229. Springer Verlag, 2003.
- F. Loulergue. Parallel Superposition for Bulk Synchronous Parallel ML. In Peter M. A. Sloot and al., editors, International Conference on Computational Science (ICCS 2003), LNCS 2659, pages 223-232. Springer Verlag, 2003.
- F. Gava and F. Loulergue. A Parallel Virtual Machine for Bulk Synchronous Parallel ML. In Peter M. A. Sloot and al., editors, International Conference on Computational Science (ICCS 2003), Part I, number 2657 in LNCS, pages 155-164. Springer Verlag, june 2003.
- F. Gava and F. Loulergue. Synthèse de types pour Bulk Synchronous Parallel ML. In J.C. Filliatre, editor, Journées Francophones des Langages Applicatifs (JFLA 2003), pages 153-168, january 2003.

### 2002

- G. Hains and F. Loulergue. Functional Bulk Synchronous Parallel Programming using the BSMLlib Library. In S. Gorlatch and C. Lengauer, editors, Constructive Methods for Parallel Programming, Advances in Computation: Theory and Practice, pages 165-178. Nova Science Publishers, august 2002
- F. Loulergue. Implementation of a Functional Bulk Synchronous Parallel Programming Library. In 14th IASTED International Conference on Parallel and Distributed Computing Systems, pages 452-457. ACTA Press, 2002

### 2001

- F. Loulergue. Distributed Evaluation of Functional BSP Programs. Parallel Processing Letters, (4):423-437, 2001.
- A. Merlin, G. Hains, and F. Loulergue. A SPMD Environment Machine for Functional BSP Programs. In Proceedings of the Third Scottish Functional Programming Workshop, august 2001.
- F. Loulergue. Parallel Composition and Bulk Synchronous Parallel Functional Programming. In S. Gilmore, editor, Trends in Functional Programming, Volume 2, pages 77-88. Intellect Books, 2001.

### 2000

- F. Loulergue, G. Hains, and C. Foisy. A Calculus of Functional BSP Programs. Science of Computer Programming, 37(1-3):253-277, 2000
- F. Loulergue. BSλp: Functional BSP Programs on Enumerated Vectors. In J. Kazuki, editor, International Symposium on High Performance Computing, number 1940 in Lecture Notes in Computer Science, pages 355-363. Springer, October 2000
- O. Ballereau, F. Loulergue, and G. Hains. High-level BSP Programming: BSML and BSλ. In G. Michaelson and Ph. Trinder, editors, Trends in Functional Programming, pages 29-38. Intellect Books, 2000.
- G. Hains and F. Loulergue. Functional Bulk Synchronous Parallel Programming using the BSMLlib Library. In S. Gorlatch, editor, Second International Workshop on Constructive Methods for Parallel Programming (CMPP'2000), Research Report MIP-2000-07, June 2000
- F. Loulergue. Parallel Composition and Bulk Synchronous Parallel Functional Programming. In Stephen Gilmore, editor, Proceedings of the second Scottish Functional Programming Workshop, St Andrews, July 2000

### 1999

- O. Ballereau, F. Loulergue, and G. Hains. High-level BSP Programming: BSML and BSλ. In P Trinder and G. Michaelson, editors, Proceedings of the first Scottish Functional Programming Workshop, number Techinal Report RM-99-9, pages 43-52, Edinburgh, august 1999. Heriot-Watt University.
- F. Loulergue. Extension du BSλ-calcul. In P. Weis, editor, JFLA'99 : Journées Francophones des Langages Applicatifs, pages 93-112, Morzine-Avoriaz, February 1999

### 1998

- F. Loulergue. BSML : Programmation BSP purement fonctionnelle. In D. Méry and G.-R. Perrin, editors, Dixièmes Rencontres Francophones du Parallélisme (Renpar'10), pages 243-246, Strasbourg, june 1998
