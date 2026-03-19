# The Super List: Essential Theoretical Physics Questions Every Graduate Student Must Master

*Merged from two independent lists of 50. Questions marked [CJ] originated from Curt Jaimungal's list; [NC] from the original conceptual-fault-line list. Questions marked [BOTH] cover territory addressed by both lists — the merged version keeps the sharper framing. Questions marked [CJ-NICHE] are included for completeness but reflect path-dependent interests (high-energy/string theory bias) rather than universal graduate-level necessity.*

---

## I. Classical Mechanics & Dynamical Systems

**1. Why does the Lagrangian equal T − V, and what does the principle of stationary action actually mean?** [BOTH]
Not "derive the Euler-Lagrange equations." *Why* is the difference of kinetic and potential energy the object nature extremizes? What does stationary action mean physically — and why should nature care about it? Why does this single scalar principle replace Newton's vector laws?

> *Overlap note: CJ Q1 asks to state the principle and its significance. NC Q1 asks the deeper question of why T − V. Merged version keeps the "why" framing while acknowledging the significance.*

**2. What is the relationship between symmetries and conservation laws, and where does Noether's theorem fail?** [BOTH]
State the theorem precisely for both finite and field-theoretic degrees of freedom. Then: what happens for discrete symmetries? For dissipative systems? For gauge symmetries — why is the "conserved quantity" a constraint, not a conservation law in the usual sense?

> *Overlap note: CJ Q2 states the theorem and lists examples (time → energy, space → momentum, rotation → angular momentum). NC Q2 probes the edge cases. Merged version does both.*

**3. Why is phase space the natural arena for classical mechanics, not configuration space?** [NC]
What structure does phase space carry that configuration space lacks? Why is the symplectic form more fundamental than the metric? What breaks if you try to do mechanics without it?

**4. What are Poisson brackets, and why are they the bridge to quantum mechanics?** [CJ]
Define them. Why does dA/dt = {A, H} + ∂A/∂t govern time evolution? What is Dirac's canonical quantization rule {f, g} → (1/iħ)[f̂, ĝ], and when does it fail? Why is the Poisson bracket the classical shadow of the commutator, not the other way around?

**5. What is the physical content of the Hamilton-Jacobi equation?** [NC]
Why is it equivalent to the Schrödinger equation in a precise limit? What does Hamilton's principal function mean geometrically — and why did this equation, not Newton's second law, become the bridge to quantum mechanics?

**6. When and why does chaos make prediction impossible in principle, not just in practice?** [NC]
Distinguish sensitive dependence from true unpredictability. What does Lyapunov exponent positivity actually buy you? Why is the KAM theorem one of the deepest results in classical mechanics?

---

## II. Electrodynamics & Gauge Theory

**7. What is a gauge degree of freedom, really?** [BOTH]
Why is A_μ not physical but F_μν is? A gauge transformation modifies potentials via A → A + ∇χ, φ → φ − ∂χ/∂t while E and B stay the same — this shows redundancy in the description. But then how does the Aharonov-Bohm effect work — a measurable phase shift from a region where F_μν = 0? Resolve this tension precisely.

> *Overlap note: CJ Q6 explains gauge invariance clearly as "potentials have more degrees of freedom than physically required." NC Q6 poses the Aharonov-Bohm challenge. Both are needed.*

**8. Why do electromagnetic waves exist?** [NC]
Not "derive the wave equation from Maxwell's equations." What is the physical mechanism by which a changing E field produces a B field and vice versa? Why does this chain propagate at exactly c, and what fixes that speed?

**9. How are the electric and magnetic fields unified using the electromagnetic field tensor F_μν?** [CJ]
Why is F_μν = ∂_μA_ν − ∂_νA_μ the natural relativistic object? Why does this unification show that E and B are not separate entities but transform into each other under Lorentz boosts? Why is the covariant formulation not just elegant but necessary?

**10. What is the physical content of the statement "electromagnetism is a U(1) gauge theory"?** [NC]
What does U(1) have to do with charge conservation? With the photon being massless? With minimal coupling? Could you reconstruct Maxwell's equations from the gauge principle alone?

**11. Why does radiation react back on its source, and why is this problem unsolved in classical electrodynamics?** [NC]
What goes wrong with the Abraham-Lorentz equation? Why do runaway solutions and preacceleration appear? What does this tell you about the limits of classical field theory?

**12. What is the physical meaning of the electromagnetic stress-energy tensor?** [NC]
Where does field momentum live? Why must the electromagnetic field carry momentum for conservation laws to work? Connect this to the resolution of the "hidden momentum" paradox.

---

## III. Quantum Mechanics

**13. What exactly does the measurement postulate assert, and why is it a problem?** [BOTH]
State it precisely. The wavefunction Ψ(x,t) encodes the complete quantum state; |Ψ|² gives probability density via the Born rule. But why is this rule inconsistent with unitary evolution? Why can't you derive Born's rule from the other postulates? What would it take to *solve* the measurement problem — not interpret it, solve it?

> *Overlap note: CJ Q8 correctly flags this as a trick question (no ontological consensus) and states the Born rule. NC Q11 presses on why it's an unsolved problem. Merged version does both.*

**14. Why is quantum mechanics formulated on a complex Hilbert space?** [BOTH]
A Hilbert space ℋ is a complete inner product space — it provides superposition, probability amplitudes via ⟨φ|ψ⟩, and self-adjoint operators for observables. But *why* complex rather than real? What goes wrong with real quantum mechanics (it exists — what does it lack)? What physical principle selects ℂ over ℝ or ℍ?

> *Overlap note: CJ Q10 defines Hilbert space and its role. NC Q12 asks why it must be complex. Merged version gives the definition and asks the hard question.*

**15. Explain the Heisenberg uncertainty principle from the commutator algebra.** [CJ]
For conjugate variables with [x̂, p̂] = iħ, the general uncertainty relation gives σ_x σ_p ≥ ħ/2. Why is this a theorem about operator algebra and state preparation, not about "disturbing" the system by measurement? What is the energy-time uncertainty relation, and why is it fundamentally different (time is not an operator in standard QM)?

**16. What is entanglement, stated without analogy?** [BOTH]
Define it precisely: a state that cannot be factored into individual subsystem states. Why is it not just classical correlation? State Bell's theorem and explain exactly which classical assumption it falsifies. Why is contextuality arguably more fundamental than nonlocality?

> *Overlap note: CJ Q11 gives the example state (1/√2)(|↑↓⟩ − |↓↑⟩) and notes the locality tension. NC Q13 demands precision about what Bell actually rules out. Both needed.*

**17. What is the physical meaning of the path integral?** [BOTH]
Each path contributes with phase e^(iS/ħ); in the limit ħ → 0, destructive interference kills everything except the classical path of stationary action. But: why do all paths contribute? When does the classical path fail to dominate? Why is the path integral the natural bridge between quantum and statistical mechanics?

> *Overlap note: CJ Q12 gives the standard treatment well. NC Q14 pushes to the statistical mechanics bridge and failure modes.*

**18. What is the quantum Zeno effect, and what does it reveal about measurement?** [CJ]
Why does frequent measurement freeze evolution? Why is the transition probability proportional to (Δt)² rather than Δt — and what does this quadratic dependence have to do with the short-time behavior of the Schrödinger equation? When does the anti-Zeno effect (acceleration by measurement) occur instead?

**19. What is Ehrenfest's theorem, and why doesn't it give you classical mechanics?** [CJ]
Derive d⟨Â⟩/dt = (1/iħ)⟨[Â, Ĥ]⟩ + ⟨∂Â/∂t⟩. This looks like classical evolution. Why isn't it? When does ⟨V'(x)⟩ ≠ V'(⟨x⟩), and why does this gap contain essentially all of quantum mechanics?

**20. Why is the harmonic oscillator the most important system in physics?** [NC]
Not because it's solvable. Why does every stable equilibrium look like a harmonic oscillator? What does this have to do with free quantum fields? With the fact that Fock space is built from oscillator algebras?

**21. What is the WKB approximation really doing?** [NC]
Why does it work? What is the geometric meaning of the connection formulae at turning points? How is this related to the Hamilton-Jacobi equation and to the classical limit of quantum mechanics?

**22. What is the adiabatic theorem, and why does Berry's phase matter?** [NC]
When does slow = adiabatic fail? Why is Berry's phase geometric rather than dynamic? What does it have to do with gauge theory, the quantum Hall effect, and topological phases of matter?

---

## IV. Statistical Mechanics & Thermodynamics

**23. Why does statistical mechanics work?** [NC]
Seriously — why should maximizing entropy give the right answer for macroscopic systems? What is the connection between ergodicity, typicality, and the second law? When does statistical mechanics fail?

**24. What is temperature, really?** [NC]
Define it without reference to thermometers or ideal gases. Why is 1/T = ∂S/∂E the natural quantity? What does negative temperature mean, and why does it require a bounded energy spectrum? What is temperature in a system far from equilibrium?

**25. What is entropy, and why are there so many definitions?** [BOTH]
Boltzmann: S = k_B ln Ω counts microstates consistent with a macrostate. But reconcile this with Gibbs, Shannon, and von Neumann entropy. When do they agree? When do they disagree, and why? What is the status of entropy as subjective vs. objective?

> *Overlap note: CJ Q18 gives the Boltzmann formula and the second law as statistical. NC Q23 demands reconciliation across all four definitions.*

**26. What is the canonical partition function, and why is it a generating function for thermodynamics?** [CJ]
Z = Σ_s e^(−βE_s) with β = 1/k_BT. Why does −k_BT ln Z give the free energy? Why do derivatives of ln Z generate all thermodynamic quantities? Why is this the connection between imaginary time and inverse temperature?

**27. What is the distinction between microcanonical, canonical, and grand canonical ensembles — and when does it matter?** [CJ]
Fixed (E,V,N) vs. fixed (T,V,N) vs. fixed (T,V,μ). When are they equivalent? When do they disagree — and why does this only happen for systems with long-range interactions or phase transitions? Why is the canonical ensemble the workhorse of theoretical physics?

**28. What is the renormalization group, and why is it arguably the most important idea in theoretical physics?** [NC]
Not "how do you remove infinities." Why does coarse-graining reveal universality? What does it mean for a theory to flow? Why are fixed points the organizing principle of physics across all scales?

**29. Derive the connection between fluctuations and dissipation.** [NC]
Why must any system that dissipates energy also fluctuate? Why does this require both statistical mechanics and time-reversal considerations? What does the fluctuation-dissipation theorem tell you about the arrow of time?

**30. What is a phase transition, and why do they exist?** [BOTH]
Why does the free energy become non-analytic? Why is this impossible in a finite system — and what does the thermodynamic limit actually provide? What distinguishes first-order from continuous transitions at the deepest level? Connect to spontaneous symmetry breaking: below T_c the Ising model chooses a ground state less symmetric than its Hamiltonian.

> *Overlap note: CJ Q17 gives the Ising model treatment of SSB. NC Q22 asks why phase transitions exist at all. Merged version frames SSB as an instance of the deeper question.*

**31. Why is the Ising model important despite being unrealistic?** [NC]
What universal features does it capture? What did Onsager's exact solution actually teach us? Why is the statement "the Ising model is in the same universality class as the liquid-gas transition" one of the most profound in physics?

---

## V. Quantum Field Theory

**32. Why do we need quantum field theory at all?** [BOTH]
What goes wrong if you try to combine special relativity and quantum mechanics without fields? Why does particle number non-conservation follow from relativity? Why is the Dirac equation insufficient as a single-particle theory — and what is the difference between Klein-Gordon and Dirac at the structural level?

> *Overlap note: NC Q25 asks why QFT is necessary. CJ Q25 asks the Klein-Gordon vs. Dirac distinction. Merged version combines both: the necessity argument naturally leads to why scalar vs. spinor field equations have different structures.*

**33. What is a particle, in QFT?** [BOTH]
Why is "an excitation of a field" not the full story? What does the Unruh effect tell you about the observer-dependence of the particle concept? When does the particle picture break down entirely?

> *Overlap note: CJ Q26 asks how particles are interpreted in QFT. NC Q26 pushes to the Unruh effect and breakdown of the concept.*

**34. What do Feynman diagrams actually represent?** [CJ]
Not "draw the diagrams for electron-electron scattering." Why is each diagram a term in a perturbative expansion of the path integral? What do internal lines, vertices, and loops correspond to physically? When does the perturbative expansion break down — and what does this tell you about the limits of the diagrammatic approach?

**35. What is renormalization, physically?** [BOTH]
Forget "subtracting infinities." Why do coupling constants run? What is the physical content of the statement that the electron charge depends on the energy scale at which you measure it? Why should this have been expected, not surprising? Connect the perturbative QFT story to the Wilsonian RG picture.

> *Overlap note: CJ Q28 asks to explain renormalization and why it's necessary. NC Q27 asks what it means physically. NC Q20 (the RG) completes the picture.*

**36. What is asymptotic freedom, and why did it win a Nobel Prize?** [CJ]
Why does the QCD coupling constant decrease at high energies — the opposite of QED? What is the physical mechanism (antiscreening by gluon self-interaction)? Why does this explain both deep inelastic scattering and confinement in a single framework?

**37. What does the path integral measure in QFT, and does it exist?** [NC]
Why is the Euclidean path integral better defined than the Lorentzian one? What is the role of Wick rotation, and when can you trust it? Why is the non-existence of a rigorous path integral measure for non-Abelian gauge theories a million-dollar problem?

**38. Why is gauge invariance required for massless spin-1 particles?** [BOTH]
What goes wrong with the longitudinal polarization? Why does a Proca mass term break gauge invariance? What is the physical content of the Higgs mechanism — what does "the gauge boson eats the Goldstone boson" actually mean?

> *Overlap note: NC Q29 covers gauge invariance + Higgs. CJ Q29 asks about gauge theory with QED as example. CJ Q31 asks about the Higgs mechanism specifically. All merged.*

**39. What is spontaneous symmetry breaking, and what is the Goldstone theorem?** [BOTH]
Why does a symmetric Lagrangian produce asymmetric ground states? What exactly is a Goldstone boson, and why is it massless? When does Goldstone's theorem fail (gauge theories, Lorentz-violating systems)?

> *Overlap note: CJ Q32 asks about Goldstone bosons. NC Q32 asks the same plus failure modes.*

**40. What is the spin-statistics theorem, and why should you find it astonishing?** [NC]
Why *must* identical fermions obey the exclusion principle? Why can't you have a bosonic electron? What assumption connects spin (a relativistic concept) to statistics (a quantum concept) — and why does it require both?

**41. State and explain the CPT theorem.** [BOTH]
What does it assume? What does it predict? Why is CPT invariance more fundamental than any individual discrete symmetry? What would CPT violation imply about the structure of quantum field theory?

> *Overlap note: CJ Q50 and NC Q31 both cover this.*

**42. What is an anomaly in quantum field theory?** [NC]
Why can a symmetry of the classical action fail to survive quantization? What is the physical content of the chiral anomaly? Why is anomaly cancellation a consistency requirement, not an optional feature?

**43. What is the connection between the path integral in QM and the Wiener measure in stochastic processes?** [CJ]
Why does Wick rotation turn quantum amplitudes into stochastic expectations? What is the mathematical relationship between the Schrödinger equation and the diffusion equation? Why is the Euclidean path integral a genuine probability measure while the Lorentzian one isn't?

---

## VI. General Relativity & Gravitation

**44. What is the equivalence principle, stated precisely enough to be useful?** [BOTH]
Distinguish weak, Einstein, and strong equivalence. What does each actually assert? Why does the strong equivalence principle rule out most alternative gravity theories? What experiment would falsify it?

> *Overlap note: CJ Q19 gives a careful three-part statement with historical Newton context. NC Q34 asks the falsification question. Both contribute.*

**45. In what sense is gravity not a force?** [NC]
What is the geometric content of Einstein's equation? Why does "gravity is curvature" not mean "gravity is tidal forces"? What is the Weyl tensor and why does it represent the part of gravity that isn't locally determined by matter?

**46. What is the physical content of Einstein's field equation G_μν = 8πT_μν?** [BOTH]
Not "derive it from the Einstein-Hilbert action." What does it *say*? The left side is geometry (Ricci curvature, scalar curvature, metric); the right side is matter-energy (stress-energy tensor). Why is it a constraint on curvature, not an equation of motion for the metric in the usual sense? What does the Bianchi identity have to do with energy conservation — and why is energy conservation problematic in GR?

> *Overlap note: CJ Q20 identifies each tensor term clearly. NC Q36 asks the deeper "what does it say" question. Merged version does both.*

**47. What is a gravitational wave, and what does its existence tell you about GR?** [CJ]
How does linearized GR predict radiative solutions? Why do gravitational waves carry energy (and why is defining that energy subtle in GR)? Why is the detection of gravitational waves simultaneously a confirmation of GR and a new observational window?

**48. Why are black holes thermodynamic objects?** [BOTH]
What is the Bekenstein-Hawking entropy formula, and why is it proportional to area rather than volume? What does Hawking radiation tell you about the interplay of quantum mechanics and gravity? Why is the information paradox still unresolved?

> *Overlap note: CJ Q44 asks about the information paradox specifically. NC Q37 frames black hole thermodynamics as the organizing question. CJ Q21 asks about singularities and cosmic censorship.*

**49. What is a singularity in GR, and do the singularity theorems prove they exist in nature?** [BOTH]
What does the Penrose singularity theorem actually assume and conclude? Why is geodesic incompleteness the right definition? What do the theorems not tell you? What does the cosmic censorship hypothesis propose — and why might naked singularities matter?

> *Overlap note: NC Q38 covers Penrose theorems. CJ Q21 adds cosmic censorship.*

**50. What is the Penrose process, and what does it reveal about black hole mechanics?** [CJ]
How does the ergosphere of a Kerr black hole permit energy extraction? Why is the area theorem (Hawking) the gravitational analogue of the second law? What is the connection between the Penrose process and superradiance?

**51. What is the problem of time in quantum gravity?** [NC]
Why does the Wheeler-DeWitt equation have no time variable? Why is this a deeper problem than it first appears? What does it tell you about the incompatibility between quantum mechanics and general relativity?

---

## VII. Mathematical Physics & Structural Questions

**52. Why is group theory the language of physics?** [BOTH]
What do Wigner's classification of particles, crystallography, and the Standard Model gauge group have in common? Why do irreducible representations organize physical states? What changes when you move from global to local (gauge) symmetries?

> *Overlap note: CJ Q33 asks about Lie groups in particle physics. NC Q40 asks the broader structural question.*

**53. What is a fiber bundle, and how is it relevant to gauge theories?** [CJ]
Why is a gauge field a connection on a principal bundle? What does this geometric picture buy you that the "local phase transformation" story doesn't? Why do topological properties of the bundle (Chern classes, winding numbers) have physical consequences (instantons, monopoles)?

**54. What is the relationship between topology and physics?** [NC]
Why does the Aharonov-Bohm effect care about the topology of space? What do topological invariants protect? Why can't you continuously deform a system out of a topological phase — and what does this have to do with robustness of quantum information?

**55. What is a Green's function, physically?** [NC]
Not "solve this PDE." Why is the response of a system to a point source the key to understanding its response to everything? What does the Green's function encode about causality, propagation, and boundary conditions? Why does it reappear in every branch of physics?

**56. What is the role of complex analysis in physics?** [NC]
Why do analyticity, causality, and the Kramers-Kronig relations form a package? What is the physical content of analytic continuation? Why does Wick rotation work — and when should you be suspicious of it?

**57. What does the spectral theorem actually tell a physicist?** [NC]
Why is the fact that Hermitian operators have real eigenvalues not the important part? What does the spectral theorem say about the *structure* of measurement in quantum mechanics? What about operators with continuous spectra?

**58. What is the Atiyah-Singer index theorem, and why does it keep appearing in physics?** [CJ]
What does the index of an elliptic operator have to do with topology? Why does this theorem connect the chiral anomaly, zero modes of the Dirac operator, and topological invariants of gauge fields? Why is this the "adult version" of seeing topology constrain dynamics?

---

## VIII. Cross-Cutting Conceptual Questions

**59. What is the relationship between symmetry breaking and the emergence of classical behavior?** [NC]
Why does decoherence select a preferred basis? What role does the environment play — is it merely practical or fundamental? Why is the quantum-to-classical transition still not fully understood?

**60. Why does the action principle unify all of physics?** [NC]
What do classical mechanics, electromagnetism, GR, QFT, and string theory have in common? Why is "find the right action" essentially the entire content of theoretical physics? Is there a reason it must be this way, or is it a structural accident?

**61. What is the holographic principle, and why should you take it seriously?** [BOTH]
Why does the Bekenstein bound suggest that the degrees of freedom of a region scale with its boundary area? What does AdS/CFT actually assert? Why is a non-perturbative definition of quantum gravity via a boundary CFT so remarkable?

> *Overlap note: CJ Q40 asks about holography and AdS/CFT. NC Q47 frames it as an argument you should take seriously.*

**62. What is a conformal field theory, and why is it central to modern theoretical physics?** [CJ]
What does conformal symmetry add beyond Poincaré symmetry? What is the central charge and what does it count? Why do CFTs appear at RG fixed points, in string theory worldsheets, and at critical points of statistical systems?

**63. What is the vacuum, and why is it the most complex object in physics?** [NC]
Why is the QFT vacuum not "empty"? What is the physical content of vacuum fluctuations — are they real or a calculational artifact? What does the Casimir effect actually demonstrate? Why is the cosmological constant problem a crisis?

**64. What would a theory of quantum gravity need to accomplish?** [BOTH]
What specifically is incompatible between QM and GR — not vaguely, but technically? Why does naive quantization of GR fail (non-renormalizability)? What does this failure actually tell you? Why might spacetime itself be emergent?

> *Overlap note: CJ Q43 asks about conceptual difficulties. NC Q49 asks what the theory must achieve.*

**65. Prove that a massless, interacting spin-2 field gives rise to general relativity in the classical limit.** [CJ]
Why is this the Weinberg-Deser-Feynman result? What assumptions go in — Lorentz invariance, universal coupling — and why does self-consistency uniquely fix Einstein's equations? Why is this arguably the most compelling "derivation" of GR?

**66. What is the role of information in physics?** [NC]
Why has information become a unifying concept across thermodynamics, quantum mechanics, and gravity? What is Landauer's principle? Why does the black hole information paradox suggest that information conservation is fundamental? Is "it from bit" a research program or a slogan?

**67. What defines a topological quantum field theory?** [CJ]
What are the Atiyah axioms? Why does a TQFT have no local degrees of freedom? Give two examples (Chern-Simons theory, BF theory) and explain why TQFTs are relevant to both mathematics (knot invariants, cobordism) and physics (topological phases, quantum computing).

---

## IX. Beyond the Standard Canon [CJ-NICHE]

*These questions reflect specific research-program commitments (primarily string theory, SUSY, and quantum gravity approaches). They are valuable for students entering those subfields but are not universal prerequisites. Included for completeness.*

**68. What is supersymmetry, and what problem does it solve?** [CJ-NICHE]
What is the Coleman-Mandula theorem and how does SUSY evade it via graded Lie algebras? What does SUSY predict? Why has the absence of superpartners at LHC energies not killed the program — and what would?

**69. What is the primary motivation for string theory?** [CJ-NICHE]
Why does replacing point particles with extended objects help with UV divergences? How does string theory naturally produce gravity (the massless spin-2 excitation)? What is the relationship between consistency conditions and the critical dimension?

**70. How do you calculate the critical dimension of string theories?** [CJ-NICHE]
Why does requiring cancellation of the conformal anomaly on the worldsheet fix D = 26 for bosonic strings and D = 10 for superstrings? What is the physical content of this calculation — why does consistency constrain the number of spacetime dimensions?

**71. What is M-theory, and how does it relate the five superstring theories?** [CJ-NICHE]
What are the dualities (T-duality, S-duality) that connect them? Why does the strong-coupling limit of Type IIA string theory grow an eleventh dimension? In what sense does M-theory "exist" given that it lacks a fundamental formulation?

**72. How are fermions unified in SO(10)?** [CJ-NICHE]
Why does one generation of Standard Model fermions (including a right-handed neutrino) fit into the 16-dimensional spinor representation of SO(10)? What does this "explain" about the seemingly arbitrary hypercharge assignments of the Standard Model?

**73. Describe spin foams in loop quantum gravity.** [CJ-NICHE]
What is the relationship between spin networks (spatial states of quantum geometry) and spin foams (spacetime histories)? How does this attempt to implement the path integral for quantum gravity? What are the main open problems?

**74. What are the leading candidates for dark matter, and what are the current experimental constraints?** [CJ-NICHE]
WIMPs, axions, sterile neutrinos, primordial black holes — what motivates each? What has direct detection ruled out? Why is the dark matter problem an empirical constraint on BSM physics rather than a purely theoretical question?

**75. What is dark energy, and why is the cosmological constant problem a crisis?** [CJ-NICHE]
Why does vacuum energy gravitate? Why does the naive QFT estimate overshoot the observed value by ~120 orders of magnitude? Why is this arguably the worst prediction in the history of physics — and why might it be a clue about quantum gravity?

---

## Overlap Map

For reference, here is how the two source lists map onto each other. Items in the same row address substantially the same territory.

| Super List # | NC Original | CJ Original | Topic |
|:---:|:---:|:---:|:---|
| 1 | Q1 | Q1 | Action principle / Lagrangian |
| 2 | Q2 | Q2 | Noether's theorem |
| 4 | — | Q4 | Poisson brackets |
| 7 | Q6 | Q6 | Gauge invariance |
| 9 | — | Q7 | Field tensor F_μν |
| 10 | Q8 | Q29 | U(1) gauge theory / QED |
| 13 | Q11 | Q8 | Measurement / Born rule |
| 14 | Q12 | Q10 | Hilbert space (complex) |
| 15 | — | Q9 | Uncertainty principle |
| 16 | Q13 | Q11 | Entanglement / Bell |
| 17 | Q14 | Q12 | Path integral |
| 19 | — | Q14 | Ehrenfest's theorem |
| 25 | Q23 | Q18 | Entropy |
| 26 | — | Q15 | Partition function |
| 27 | — | Q16 | Ensembles |
| 30 | Q22, Q24 | Q17 | Phase transitions / SSB / Ising |
| 32 | Q25 | Q25, Q26 | Why QFT / particles / Klein-Gordon vs Dirac |
| 35 | Q27, Q20 | Q28 | Renormalization / RG |
| 38 | Q29 | Q29, Q31 | Gauge invariance, Higgs |
| 39 | Q32 | Q32 | Goldstone theorem |
| 41 | Q31 | Q50 | CPT theorem |
| 44 | Q34 | Q19 | Equivalence principle |
| 46 | Q36 | Q20 | Einstein field equations |
| 48 | Q37 | Q44 | Black hole thermodynamics / information |
| 49 | Q38 | Q21 | Singularities |
| 52 | Q40 | Q33 | Group theory |
| 61 | Q47 | Q40 | Holographic principle / AdS/CFT |
| 64 | Q49 | Q43 | Quantum gravity |

---

## How to Use This List

The first 67 questions are things every theorist should be dangerous on regardless of subfield. Questions 68–75 are subfield-dependent — valuable if you're heading into HEP-th or quantum gravity, safely ignorable if you're doing condensed matter, AMO, or plasma physics.

For any question where your honest answer is "I'd just quote the textbook," that's the one to dig into. The textbook answer is the starting point, not the destination.
