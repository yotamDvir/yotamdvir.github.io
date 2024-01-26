+++
title="A Denotational Approach to Release/Acquire Concurrency"
authors=["Yotam Dvir", "Ohad Kammar", "Ori Lahav"]
in_search_index = false

[taxonomies]
categories = ["Research Paper"]
tags = ["concurrency", "weak memory", "denotational semantics"]

[extra]
venue="ESOP 2024 (33rd European Symposium on Programming)"
doi=""
citation="[Accepted for publication]"
abstract="We present a compositional denotational semantics for a functional language with first-class parallel composition and shared-memory operations whose operational semantics follows the release-acquire weak memory model (RA). The semantics is formulated in Moggi's monadic approach, and is based on Brookes-style traces. To do so we adapt Brookes's traces to Kang et al.'s view-based machine for RA, and supplement Brookes's mumble and stutter closure operations with additional operations, specific to RA. The latter provides a more nuanced understanding of traces that uncouples them from operational interrupted executions. We show that our denotational semantics is adequate and use it to validate various program transformations of interest. This is the first work to put weak memory models on the same footing as many other programming effects in Moggi's standard monadic approach."
pdf = "paper"
talks=["popl-24"]
+++

Temporary stub until it is ready.
