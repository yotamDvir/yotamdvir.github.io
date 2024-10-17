+++
title="A Brookes-Style Denotational Semantics for Release/Acquire Concurrency"
authors=["Yotam Dvir", "Ohad Kammar", "Ori Lahav"]
slug="toplas-24"

[taxonomies]
categories = ["Publication", "Journal"]
tags = ["concurrency", "weak memory", "denotational semantics"]

[extra]
navtitle="Release/Acquire Denotational Semantics (TOPLAS)"
venue="TOPLAS"
venuefull="Transactions on Programming Languages and Systems"
accepted = true
abstract="We present a compositional denotational semantics for a functional language with first-class parallel composition and shared-memory operations whose operational semantics follows the Release/Acquire weak memory model (RA). The semantics is formulated in Moggi's monadic approach, and is based on Brookes-style traces. To do so we adapt Brookes's traces to Kang et al.'s view-based machine for RA, and supplement Brookes's mumble and stutter closure operations with additional operations, specific to RA. The latter provides a more nuanced understanding of traces that uncouples them from operational interrupted executions. We show that our denotational semantics is adequate and use it to validate various program transformations of interest. This is the first work to put weak memory models on the same footing as many other programming effects in Moggi's standard monadic approach."
attachments=[
  {kind = "journal"     , pdf = "toplas-24"},
  {kind = "proceedings" , pdf = "esop-24" , slug = "esop-24"},
  {kind = "slides"      , pdf = "esop-24-slides" , slug = "esop-24"},
  {kind = "poster"      , pdf = "popl-24-poster" , slug = "popl-src-24"},
]
+++
