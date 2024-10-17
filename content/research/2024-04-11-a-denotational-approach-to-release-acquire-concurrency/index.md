+++
title="A Denotational Approach to Release/Acquire Concurrency"
authors=["Yotam Dvir", "Ohad Kammar", "Ori Lahav"]
slug="esop-24"

[taxonomies]
categories = ["Publication", "Conference"]
tags = ["concurrency", "weak memory", "denotational semantics"]

[extra]
navtitle="Release/Acquire Denotational Semantics (ESOP)"
venue="ETAPS/ESOP 2024"
venuefull="33rd European Symposium on Programming"
doi="10.1007/978-3-031-57267-8_5"
abstract="We present a compositional denotational semantics for a functional language with first-class parallel composition and shared-memory operations whose operational semantics follows the release-acquire weak memory model (RA). The semantics is formulated in Moggi's monadic approach, and is based on Brookes-style traces. To do so we adapt Brookes's traces to Kang et al.'s view-based machine for RA, and supplement Brookes's mumble and stutter closure operations with additional operations, specific to RA. The latter provides a more nuanced understanding of traces that uncouples them from operational interrupted executions. We show that our denotational semantics is adequate and use it to validate various program transformations of interest. This is the first work to put weak memory models on the same footing as many other programming effects in Moggi's standard monadic approach."
attachments=[
  {kind = "journal"     , pdf = "toplas-24" , slug = "toplas-24"},
  {kind = "proceedings" , pdf = "esop-24"},
  {kind = "slides"      , pdf = "esop-24-slides"},
  {kind = "poster"      , pdf = "popl-24-poster" , slug = "popl-src-24"},
]
+++
