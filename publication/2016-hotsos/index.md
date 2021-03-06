---
title: "Controller Synthesis for Linear Dynamical Systems with Adversaries"
date: 2016-04-20
publishDate: 2016-04-20
authors: ["Zhenqi Huang", "Yu Wang", "Sayan Mitra", "Geir E. Dullerud"]
publication_types: ["1"]
abstract: "We present a controller synthesis algorithm for a reach-avoid problem in the presence of adversaries. Our model of the adversary abstractly captures typical malicious attacks envisioned on cyber-physical systems such as sensor spoofing, controller corruption, and actuator intrusion. After formulating the problem in a general setting, we present a sound and complete algorithm for the case with linear dynamics and an adversary with a budget on the total L2-norm of its actions. The algorithm relies on a result from linear control theory that enables us to decompose and compute the reachable states of the system in terms of a symbolic simulation of the adversary-free dynamics and the total uncertainty induced by the adversary. With this decomposition, the synthesis problem eliminates the universal quantifier on the adversary's choices and the symbolic controller actions can be effectively solved using an SMT solver. The constraints induced by the adversary are computed by solving second-order cone programmings. The algorithm is later extended to synthesize state-dependent controller and to generate attacks for the adversary. We present preliminary experimental results that show the effectiveness of this approach on several example problems."
featured: false
publication: "*ACM Symposium and Bootcamp on the Science of Security (HoTSoS)*"
url_pdf: https://dl.acm.org/doi/10.1145/2898375.2898378
---

