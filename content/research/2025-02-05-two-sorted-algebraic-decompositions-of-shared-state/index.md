+++
title="Two-sorted Algebraic Decompositions of Brookes's Shared-State Denotational Semantics"
authors=["Yotam Dvir", "Ohad Kammar", "Ori Lahav", "Gordon Plotkin"]
slug="fossacs-25"

[taxonomies]
categories = ["Publication", "Conference"]
tags = ["concurrency", "algebraic effects", "denotational semantics"]

[extra]
navtitle="Two-sorted Brookes Decompositions (FoSSaCS)"
venue="ETAPS/FoSSaCS 2025"
venuefull="28th International Conference on Foundations of Software Science and Computation Structures"
accepted = true
abstract="We use a two sorted equational theory of algebraic effects to model concurrent shared state with preemptive interleaving, recovering Brookes's seminal 1996 trace-based model precisely. The decomposition allows us to analyse Brookes's model algebraically in terms of separate but interacting components. The multiple sorts partition terms into layers. We use two sorts: a 'hold' sort for layers that disallow interleaving of environment memory accesses, analogous to holding a global lock on the memory; and a 'cede' sort for the opposite. The algebraic signature comprises of independent interlocking components: two new operators that switch between these sorts, delimiting the atomic layers, thought of as acquiring and releasing the global lock; non-deterministic choice; and state-accessing operators. The axioms similarly divide cleanly: the delimiters behave as a closure pair; all operators are strict, and distribute over non-empty non-deterministic choice; and non-deterministic global state obeys Plotkin and Power's presentation of global state. Our representation theorem expresses the free algebras over a two-sorted family of variables as sets of traces with suitable closure conditions. When the held sort has no variables, we recover Brookes's trace semantics."
attachments=[
  {kind = "submission" , pdf = "fossacs-25-fin"},
]
arxiv="2501.15104"
+++
