# SecureDT-VN
This repository contains the formal verification source code.
Security Verification
This repository contains the formal verification source code for the proposed authentication scheme. The protocol is modeled using the High-Level Protocol Specification Language (HLPSL) and verified with the AVISPA tool in a fully configured testing environment on Oracle VM VirtualBox (Span-Ubuntu 10.10-light).

The verification process employs two AVISPA backends:

* On-the-Fly Model Checker (OFMC)

* Constraint-Logic-based Attack Searcher (CL-AtSe)

Results confirm that the protocol is classified as SAFE under all simulated scenarios, demonstrating resilience against replay attacks and man-in-the-middle attacks, while ensuring session key secrecy and mutual authentication.

The complete HLPSL implementation is provided to enable independent verification and reproducibility of the results.
