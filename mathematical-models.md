% Mathematical Models: A sketch for the philosophy of mathematics
% Saunders Mac Lane, 1981
[Link to pdf](http://home.deib.polimi.it/schiaffo/TFIS/philofmaths.pdf)

How I came to read it: It's referenced in Lakoff and Nu&ntilde;ez's *Where Mathematics Comes From*.

# Introduction

Philosophy of mathematics has been dormant since around 1931, the end of the activity around the mathematical crisis surrounding the great paradoxes and the foundations of mathematics. That crisis gave birth to three competing philosophical schools: Logicism, Formalism, and Intuitionism. Additionally there were longstanding schools, Platonism and Empiricism, that continued to exist.

## Definitions

* **Empiricism**: Mathematics is simply another branch of science, so mathematics deals directly with the real world. Arose from the Kantian view of the dichotomy between analytic and synthetic and the 19th-century view of mathematics as "almost coterminal with theoretical physics."

* **Platonism**: "Platonism about mathematics (or mathematical platonism) is the metaphysical view that there are abstract mathematical objects whose existence is independent of us and our language, thought, and practices. Just as electrons and planets exist independently of us, so do numbers and sets." [^1] Platonism fitted Greek geometry well, and it became popular again (with Frege?) because it fits well with the view that mathematics derives from axioms for sets.

  [^1]: [Definition from the SEP](https://plato.stanford.edu/entries/platonism-mathematics/).

* **Logicism**: "The *strong* version of logicism maintains that all mathematical truths in the chosen branch(es) form a species of logical truth. The *weak* version of logicism, by contrast, maintains only that all the theorems do." Maintains that all objects of mathematical study are *logical* objects and that all mathematics can be derived from a set of logical first principles, entirely within the bounds of logic itself. Arose with the discovery and formalization of mathematical logic.[^2]

  [^2]: [Definition from the SEP](https://plato.stanford.edu/entries/logicism/).

* **Formalism**: Views math as like a logical, formal game. Thus, math has no tie to any reality outside itself and requires no commitment to any particular ontology.[^3] Arose with the development of axiomatic methods and discovery that proof theory might give consistent proofs for abstract mathematics.

  [^3]: Definition largely made up by me.

* **Intuitionism**: "Intuitionism is based on the idea that mathematics is a creation of the mind. The truth of a mathematical statement can only be conceived via a mental construction that proves it to be true, and the communication between mathematicians only serves as a means to create the same mental process in different minds."[^4] Arose from the emphasis on numbers as the starting point of mathematics and intuition as a basis for topology.

  [^4]: [Definition from the SEP](https://plato.stanford.edu/entries/intuitionism/).

Each of these arose from the dominant aspects of mathematics as it was understood in its time.

He maintains none of these provides a satisfactory analysis of the nature of mathematics. A sound philosophy of mathematics should begin with a description of what is really there.

# The Origins of Mathematics

"Mathematics begins with puzzles and problems dealing with combinatoric and symbolic aspects of the general human experience. Some of these aspects turn out to be systematic and intrinsic, rather than arbitrary and tied to one context. They become the stuff of elementary mathematics." Via deductive analysis, we abstract and derive more layers of advanced mathematics. Real human activities and objects lead to concepts that codify deeper and nonobvious properties of the human activities and objects they originate from.

This exactly accords with Lakoff and Nu&ntilde;ez except he gives more of what they would call "grounding metaphors" than they do, but I'm inclined to the view that all he lists can be simplified to theirs.

Many mathematical concepts, such as "function", are simple in structure yet pervasive in application; "the simplicity and applicability are made effective by the formal treatment of the notions involved." Mathematics is formal, formalized, but not simply formalistic because the forms it studies are derived from human activities and used in turn to understand those activities.

He goes through an extended example of the development of algebra, its connection to geometry, vector spaces and so forth. Each mathematical notion is thus tied to its empirical origin in multiple ways (and to each other via various analogies, not stated by Mac Lane here but this is our current understanding, cf. Hofstadter, Lakoff, and others).

Thus we can say that "mathematics studies formal structures by deductive methods which, because of the formal character, require a standard of precision and rigor."

# Absolute Rigor

"The use of deductive and axiomatic methods focuses attention on an extraordinary accomplishment of fundamental interest: the formulation of an exact notion of *absolute rigor*." Requires explicit formulation of the rules of logic (me inserting myself: which exist intersubjectively). Each derivation can be tested and understood formally, independent of any reference to the human reality it derived from. "Once the axioms are the rules are fully formulated, everything else is built up from them, without recourse to the outside world, or to intuition, or to experiment." (I'm not certain about this, because I think "linking metaphor" might be part of "intuition" but I'm not sure.)

"An absolutely rigorous proof is rarely given explicitly." They are usually just sketches giving enough detail to show how the full rigorous proof might be constructed; thus, "proofs" convey "conviction", either of correctness or that a full rigorous proof could be constructed. Examples of full rigorous proofs have been "cumbersome and tedious" (and many can only be done by computers, it seems); "they clearly showed that absolute rigor was so detailed that it was a distraction and not a help to mathematical research." But they made the idea of *absolute rigor* tangible.

This understanding of absolute rigor has led to the philosophical views of logicism and formalism. While this is an understandable outcome of the direction of absolute rigor pursued around the time of the crisis and represent an important aspect of mathematics, they are too limited. Mac Lane maintains that the choice of axioms and the determination of directions in which they are to be developed is not determined by the formal structure but by aspects of the world (me: and our minds) under study or by "portions of the mathematician's insight."" (cf. Eugenia Cheng's description of the relationship of knowledge, understanding, and belief)

An important metaphysical question: "How does it happen that some important facets of the real world can in fact be accurately analyzed by austere deductions from axioms?" Why does logic fit the world? (ok, I think the cognitive science/linguistics research on metaphor and analogy is giving us an answer to this question)

# Multiple Models of Reality

"Our thesis as to the nature of mathematics might be formulated thus: Mathematics deals with the construction of a variety of formal models of aspects of the world and of human experience. On the one hand, this means that mathematics is not a direct theory of some underlying platonic reality, but rather an indirect theory of formal aspects of the world (or of reality, if there is such). On the other hand, our thesis emphasizes that mathematics involves a considerable variety of models. The same experience can be modeled mathematically in more than one way." 100%.

Examples from some basic constructions, such as various models of ordinals and ways to construct the reals from the rationals. There may be no unique model for these constructions, but what's important is we get ordinals or reals or whatever *with the same behavior*. (ok, in fairness, I think a platonist could argue it's because those things -- e.g., the reals -- exist independently and our poor attempts to model them are from our "viewing shadows in a cave" perspective?)

Mathematical models are determined "up to a canonical isomorphism." However, much of the utility of various models (e.g., the group axioms) derives from the fact that they have many non-isomorphic models.

# Foundations

This section largely lays out a critique of the *Grand Set Theoretic Foundation* project and why it does not constitute a proper philosophy of mathematics and does not describe the nature of mathematics. "The 'Grand Foundation' does not provide any way in which to explain the choice of these concepts" or recognize common notions, such as the "universal" structures, which appear in different types of structures. (Interesting here he refers to Bourbaki's "mother structures" and so does Seymour Papert [in *Mindstorms*] with regard to Piagetian learning, so it'd be good to know more about these and understand that part of Papert better.)

He also drags ZF axiomatic set theory for being "largely irrelevant to the practice of most mathematics" which is both true and funny for the fact that he also said absolute rigor is both necessary and also usually only hinted at. Anyway.

"The set-theoretic approach is by no means the only possible foundation for mathematics. Another approach is to formulate axioms not on set membership but on the composition of functions. This results in an axiomatization of the category of all sets..." Neat.

"The final difficult with the Grand Foundation is that it does not account for what E.P. Wigner has terms the unreasonable success of mathematics in its applications." True, but I think we can now.

# Cantorian Set Theory

ZF and first-order logic do not subsume all of set theory, but formalize only a part of it, and Cantorian set theory emphasizes the "intuitive notion of a set as a collection which is a real object in its own right." So set theory can be studied by other means than ZF or first-order logic, hence it is just another branch of mathematics.

Since we can dismiss set theory as *the* foundation of mathematics, we can assimilate it with the view that math consists of formalized disciplines derived from human activities, and there's a clear analog in human activity for the Cantorian notion of sets.

# Multiple Models for Set Theory

As with Cantorian set theory, so with the rest of mathematics. Mathematics deals with multiple models of the world and is not subsumed by any one grand theory or system of axioms.

For the Platonist, there may be many ways to model sets that are all only approximations of the underlying and pure mathematical reality of Platonic sets.

But this cannot be shown to be true (or false), whether ontologically or epistemologically. "Moreover, such ideal worlds rapidly become too elaborate; they must display not only the sets but all the other separate structures which mathematicians have described or will discover. The real nature of these structures does not lie in their often artificial constrcution from set theory, but in their relation to simple mathematical ideas or to basic human activities."

# Models of Geometry

OK, I took no notes on this section.

# Breadth, Clarity, and Depth

Breadth, clarity, and depth are crucial because of the extent of abstraction in mathematics.

Abstraction may take place in several stages (and I'd argue it usually does) and "interlock" different branches of mathematics, but it is the practice of "formulating essential aspects of some subject matter in terms of suitable axioms." (as a "monoid" takes essential aspects of some common operations and axiomatizes them, becoming then a new thing -- but an abstract thing)

Breadth refers to the number of situations a mathematical abstraction can apply to and to the prevalence and relevance of the abstraction. (monoids are everywhere yo) Clarity has to do with presentation of ideas -- speaking precisely (not intuitively? mm) but also with a "clear ordering of ideas." Depth refers to how a mathematical notion "gets at the nonobvious, more fundamental structures and concepts underlying the problems at issue".

"Mathematics consists in the discovery of successive stages of the formal structures underlying the world and human activities in that world, with emphasis on those structures of broad applicability and those reflecting deeper aspects of the world.

"In detail, mathematical development uses experience and intuitive insights to discover appropriate formal structures, to make deductive analyses of these structures, and to establish formal interconnections between them. In other words, mathematics studies interlocking structures. Because of the depth and of the distance from immediate concerns, mathematical treatments need be not only rigorous but also endowed with conceptual clarity."

Sorry for the extended quote at the end, but he packs a lot in there.

I'm still not entirely sure what his beef with intuitionism is except perhaps intuitionism might deny that there is any connection to real world human activities, I'm not sure?
