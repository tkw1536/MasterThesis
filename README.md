# Enabling Cross-System Communication Using Virtual Theories and QMT

This repository contains my Master Thesis.
 
[PDF](thesis.pdf)

### Title
Enabling Cross-System Communication Using Virtual Theories and QMT
### Abstract
<div style='text-align: justify;'>
  <p>
    Mathematical Knowledge Systems (MKS) are software solutions used by mathematicians in practice to explore specific fields of mathematics and help solving both abstract and computational problems.
    To solve a specific problem multiple systems are often necessary.
  </p>
  <p>
    Existing cross-system-communication solutions are ad-hoc, non-expandable, exist only for the most common system combinations and do not maintain semantics across systems.
    Mathematicians are not interested in technical details required to use these approaches – they only want to explore mathematics and solve problems.
    In this thesis, we aim to address this problem by designing, implementing and demonstrating a generic, efficient and scalable approach for enabling transparent, semantics-aware, distributed computation across MKS.
  </p>
  <p>
    MMT is a language and framework that developed to manage mathematical knowledge.
    It makes use of the theory graph metaphor by organizing knowledge within different concrete theories that are represented by files on disk.
    To access knowledge in MMT, users can make use a Query Language called QMT.
  </p>
  <p>
    In the OpenDreamKit project, an EU Horizon 2020 project aiming to provide tools for combining different existing mathematical software systems, we in particular want to make knowledge of these systems available to each other.
    For this we make use of the so-called Math-In-The-Middle (MiTM) paradigm, a new mathematics-aware, semantic, extensible approach to connecting multiple systems.
    Instead of building translations between any two of the involved systems, we decided to model the underlying mathematics in MMT and only build interfaces between this Math-In-The-Middle and the systems.
  </p>
  <p>
    On top of the MiTM approach, the concept of virtual theories is introduced to MMT.
    These are just like concrete theories, but without the assumption of loading all declarations from a file on disk at system startup.
    We use them to transparently access knowledge across systems.
    Additionally, we expand the QMT Query Language to enable mathematicians to send queries in a system-independent manner.
  </p>
  <p>
    In this thesis, we first recap the existing architecture, then move on to discuss our implementation of the Math-In-The-Middle Approach.
    Next we focus on the example of LMFDB, a mathematical database of objects in number theory and show how it can be implemented as a Virtual Theory to enable the desired communication and computation.
    Finally, we demonstrate the validity of our approach based on a concrete example.
  </p>
</div>

### License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.