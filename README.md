# A mobility-compliant publish–subscribe system for an information-centric Internet of Things

[![Paper][paper-badge]][paper-link]

This repository contains code and documentation to reproduce experimental results of the paper **"[A mobility-compliant publish–subscribe system for an information-centric Internet of Things][paper-link]"**
published in the Computer Networks journal.

* Cenk Gündogan, Peter Kietzmann, Thomas C. Schmidt, and Matthias Wählisch,
**A mobility-compliant publish–subscribe system for an information-centric Internet of Things**,
In: Computer Networks, Vol. 203, No. 108656, p. 1–14, Elsevier, February 2022.

 **Abstract**
 > The Information centric networking paradigm has proven particularly useful for the constrained Internet of
   Things (IoT), in which nodes are challenged by end-to-end communication without network assistance. This
   work focuses on the interaction between possibly mobile sensors and actuators in such IoT regimes which
   deploy the Named-Data Networking (NDN) architecture. Constrained nodes in interactive scenarios need to be
   highly responsive but can only manage limited control state. We argue that the request-driven NDN networking
   paradigm, which prevents pushing of unsolicited data, should be preserved to confine the attack surface,
   whereas unsolicited link-local signaling can accelerate responses without sacrificing security.
 >
 > In this paper, we contribute HoP-and-Pull (HoPP), a robust publish–subscribe scheme for typical IoT
   scenarios that targets low-power and lossy wireless networks running hundreds of resource constrained devices
   at intermittent connectivity. Our approach limits in-memory forwarding state to a minimum and naturally
   supports producer mobility, a temporary partitioning of networks, data aggregation on intermediary hops,
   and near real-time reactivity. We thoroughly evaluate the protocol by experiments in a realistic, large testbed
   with varying numbers of constrained devices, each interconnected via IEEE 802.15.4 wireless LoWPANs. We
   compare HoPP with common ICN pub–sub and mobility schemes as well as with basic MIPv6 and anchor-based
   multicast mobility. Implementations are built on CCN-lite with RIOT and support experiments using various
   single- and multi-hop scenarios.

Please follow our [Getting Started](getting_started.md) instructions for further information how to compile and execute the code.

<!-- TODO: update URLs -->
[paper-link]:https://doi.org/10.1016/j.comnet.2021.108656
<!-- [paper-badge]:https://img.shields.io/badge/Paper-IEEE%20Xplore-gray -->
[paper-badge]:https://img.shields.io/badge/Paper-Elsevier-green
