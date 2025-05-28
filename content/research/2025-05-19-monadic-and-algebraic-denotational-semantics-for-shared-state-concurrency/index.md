+++
title="Monadic and Algebraic Denotational Semantics for Concurrent Shared State"
authors=["Yotam Dvir", "Ohad Kammar", "Ori Lahav", "Gordon Plotkin"]
slug="visit-tartu-25"

[taxonomies]
categories = ["Visit"]
tags = ["concurrency", "weak memory", "denotational semantics"]

[extra]
navtitle="Release/Acquire Denotational Semantics (GALOP)"
venue="University of Tartu, Estonia"
venuefull="University of Tartu's Programming Languages Research Seminar"
abstract="""
We present two results related to Brookes's 1996 denotational semantics. First, we precisely recover Brookes's model using two-sorted algebraic effects. Second, we define Moggi-style monadic semantics for C's Release/Acquire relaxed memory fragment, using Brookes-style traces.

Brookes's seminal 1996 paper defines a fully compositional denotational semantics for preemptive shared state concurrency. In Brookes's model, programs denote sets of sequential rely/guarantee traces. Later work showed that it extends to more advanced notions of state. Moreover, the model straightforwardly fits inside Moggi's standard monadic framework.

Until recently, it was unclear whether there is an equational theory that captures Brookes's model, using Plotkin and Power's algebraic effects approach, which admits the theory of global state. We give a positive answer with a two-sorted equational theory, which also happens to be the first time multi-sorted algebraic effects found use. The main innovation: two sort-switching operators that denote atomic-block delimiters, axiomatized as a closure pair. We recover Brookes's model precisely along the adjunction that forgets the sort within atomic blocks.

With the versatility of Brookes's model in mind, we look beyond the idealized sequential consistency that Brookes assumed. Previous work established that Brookes's model extends to x86-TSO, which relaxes sequential consistency with write-buffers. We go further, extending Brookes's model to Release/Acquire, the key fragment of C's model which supports decentralized communication between threads. Our semantics is abstract enough to justify all known Release/Acquire-valid transformations. We organize our treatment in the monadic framework, demonstrating that relaxed concurrency can be placed on equal footing as many other programming effects.

Based on joint work with Ohad Kammar, Ori Lahav, and Gordon Plotkin.
"""
attachments=[
  {kind = "slides"      , pdf = "visit-tartu-25-slides"},
]
+++
