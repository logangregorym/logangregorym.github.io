---
title: "I See Dead &micro;ops: Leaking Secrets via Intel/AMD &micro;op Caches"
collection: publications
permalink: /publication/2021-06-dead-uops
date: 2021-06-01
venue: '48th International Symposium on Computer Architecture (ISCA)'
paperurl: 'http://logangregorym.github.io/files/2021-06-dead-uops.pdf'
authors: 'Xida Ren, <strong>Logan Moody</strong>, Mohammadkazem Taram, Matthew Jordan, Dean M. Tullsen, Ashish Venkat'
abstract: 'Modern processors cache decoded micro-operations (&micro;ops) in a &micro;op cache to skip redundant instruction fetch and decode. We show that the &micro;op cache introduces a timing side channel that can be exploited by a malicious actor to leak sensitive information across security boundaries. We demonstrate end-to-end Spectre-style attacks on Intel and AMD processors—leaking data across process and VM boundaries—and evaluate potential hardware and software mitigations.'
citation: 'Xida Ren, Logan Moody, Mohammadkazem Taram, Matthew Jordan, Dean M. Tullsen, Ashish Venkat. "I See Dead &micro;ops: Leaking Secrets via Intel/AMD &micro;op Caches." <i>48th International Symposium on Computer Architecture (ISCA)</i>, 2021.'
---
