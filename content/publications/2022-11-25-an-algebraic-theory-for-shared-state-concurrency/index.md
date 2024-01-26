+++
title="An Algebraic Theory for Shared-State Concurrency"
authors=["Yotam Dvir", "Ori Lahav", "Ohad Kammar"]
slug="22_1"

[taxonomies]
categories = ["Research Paper"]
tags = ["concurrency", "algebraic effects", "denotational semantics"]

[extra]
venue="APLAS 2022 (Programming Languages and Systems: 20th Asian Symposium)"
doi="10.1007/978-3-031-21037-2_1"
citation="Yotam Dvir, Ohad Kammar, and Ori Lahav. 2022. An Algebraic Theory for Shared-State Concurrency. In Programming Languages and Systems: 20th Asian Symposium, APLAS 2022, Auckland, New Zealand, December 5, 2022, Proceedings. Springer-Verlag, Berlin, Heidelberg, 3–24. https://doi.org/10.1007/978-3-031-21037-2_1"
abstract="We present a monadic denotational semantics for a higher-order programming language with shared-state concurrency, i.e. global-state in the presence of interleaving concurrency. Central to our approach is the use of Plotkin and Power’s algebraic effect methodology: designing an equational theory that captures the intended semantics, and proving a monadic representation theorem for it. We use Hyland et al.’s equational theory of resumptions that extends non-deterministic global-state with an operator for yielding to the environment. The representation is based on Brookes-style traces. Based on this representation we define a denotational semantics that is directionally adequate with respect to a standard operational semantics. We use this semantics to justify compiler transformations of interest: redundant access eliminations, each following from a mundane algebraic calculation; while structural transformations follow from reasoning over the monad’s interface."
pdf = "paper"
distinctions=["Later Awarded The Boaz Trakhtenbrot Centennial Scholarship"]
talks=["aplas-22"]
+++
