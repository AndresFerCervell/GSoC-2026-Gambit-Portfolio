# GSoC-2026-Gambit-Portfolio
Research portfolio and technical reports for my Google Summer of Code 2026 project at Gambit: Implementing the Herings &amp; Peeters differentiable homotopy.
# GSoC 2026 | Global Convergence for Nash Equilibria in Gambit

Welcome! This repository serves as my **official research portfolio and technical log** during my participation in the **Google Summer of Code (GSoC) 2026** with the **Gambit Project** organization. 

This space is dedicated to compiling technical reports, mathematical proofs, progress summaries, and theoretical documentation developed throughout the program. The production-grade source code and underlying C++ engine refactoring are integrated directly into the official Gambit repository via peer-reviewed Pull Requests.

---

## 📌 Project Overview
* **Researcher:** Andrés Fernández Cervell (Double Degree in Mathematics and Computer Science, Universidad de Granada, Spain)
* **Lead Mentor:** Dr. Theodore L. Turocy
* **Organization:** [Gambit Project](https://github.com/gambitproject/gambit)
* **Core Objective:** To implement the globally convergent, everywhere differentiable homotopy algorithm proposed by Herings & Peeters (2001) into the Gambit C++ core core and expose it via the PyGambit API. This computational architecture provides a robust solution to the equilibrium multiplicity bottleneck in general $n$-person games by using subjective user-specified priors.

---

## 📂 Research & Technical Portfolio

This index categorizes the technical deliverables and milestone reports generated over the course of the project:

* **[Technical Report: Numerical Stability & Singularity Resolution](./Gambit_Logit_Algorithm.pdf)**: Documentation of my candidate solution utilizing Sard's Theorem and multidimensional symmetry breaking to stabilize predictor-corrector path-following solvers near bifurcation points (Resolving Issue #492).
* **[GSoC 2026 Accepted Proposal](./GSoC_Gambit_Application.pdf)**: The official project roadmap, outlining the mathematical methodology, variable transformation frameworks, and the 175-hour development schedule.
* *[Forthcoming]* **Phase 1 Evaluation Report**: Dynamic stress-testing of perturbation vectors and formal C++ exception handling integration.
* *[Forthcoming]* **Phase 2 Evaluation Report**: Implementation of analytical Jacobian matrices for the Euler predictor and Newton-Raphson corrector phases within the Herings & Peeters trajectory.

---

## 🛠️ Technical Competencies & Domain Knowledge
* **Systems Engineering:** High-performance C++ core architecture, abstraction layers for numerical engines (Allgower-Georg framework), and Python/C++ interoperability via PyGambit.
* **Applied Mathematics & Game Theory:** Differentiable manifolds ($C^1$ cubical/simplicial tracking), Predictor-Corrector path-following mechanics, Quantal Response Equilibria (QRE), and topological singularity disconnection.

---

## 🔗 Professional Links
* **LinkedIn Profile:** [Andrés Fernández Cervell](https://linkedin.com/in/andres-fernandez-cervell) *(Update this with your actual URL suffix)*
* **Official Institution:** [Universidad de Granada](https://www.ugr.es/)
* **Gambit Project Repository:** [gambitproject/gambit](https://github.com/gambitproject/gambit)
