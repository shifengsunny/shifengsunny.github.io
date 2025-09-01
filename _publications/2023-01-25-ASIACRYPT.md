---
title: "A Universally Composable Non-interactive Aggregate Cash System"
collection: publications
category: conferences
permalink: /publication/2023-01-25-ASIACRYPT
excerpt: ' '
date: 2023-01-25
venue: 'ASIACRYPT 2022'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-031-22963-3_25'
citation: 'Yanxue Jia, Shifeng Sun, Hong-Sheng Zhou, Dawu Gu: A Universally Composable Non-interactive Aggregate Cash System. ASIACRYPT (1) 2022: 745-773'
---

Mimblewimble is a privacy-preserving cryptocurrency, providing the functionality of transaction aggregation. Once certain coins have been spent in Mimblewimble, they can be deleted from the UTXO set. This is desirable: now storage can be saved and computation cost can be reduced. Fuchsbauer et al. (EUROCRYPT 2019) abstracted Mimblewimble as an Aggregate Cash System (ACS) and provided security analysis via game-based definitions.

In this paper, we revisit the ACS, and focus on Non-interactive ACS, denoted as NiACS. We for the first time propose a simulation-based security definition and formalize an ideal functionality for NiACS. Then, we construct a NiACS protocol in a hybrid model which can securely realize the ideal NiACS functionality in the Universal Composition (UC) framework. In addition, we propose a building block, which is a variant of the ElGamal encryption scheme that may be of independent interest. Finally, we show how to instantiate our protocol, and obtain the first NiACS system with UC security.
