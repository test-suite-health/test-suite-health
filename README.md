# Test Suite Health

Test Suite Health Indicator and current existing detection/improvement tools for Java.

| Indicator                      | Detection                                   | Improvement / Repair                      |
|--------------------------------|---------------------------------------------|------------------------------------------:|
| Code coverage                  | [JaCoCo](https://github.com/jacoco/jacoco)  | DSpot [[3]](#3)                           | 
| Pseudo-Testedness              | Descartes [[1]](#1), PseudoSweep [[9]](#9)  |                                           | 
| Mutation Testing               | [PIT](https://pitest.org/), MAJOR [[4]](#4) | DSpot [[3]](#3)                           | 
| Test Diversity                 |                                             |                                           |
| Test Brittleness               |                                             |                                           |
| Test 'Realism'                 |                                             |                                           |
| Test Execution Runtime         |                                             | TestBoost [[8]](#8)                       |
| Test Flakiness                 | DeFlaker [[5]](#5), iDFlakies [[6]](#6)     | iFixFlakies [[7]](#7), FlakeSync [[2]](#2)|
| High Variability of Indicators |                                             |                                           |

## References
<a id="1">[1]</a> 
Vera-Pérez, Oscar Luis and Monperrus, Martin and Baudry, Benoit (2018).
[Descartes: A pitest engine to detect pseudo-tested methods: Tool demonstration.](https://doi.org/10.1145/3238147.3240474)
Proceedings of the 33rd ACM/IEEE International Conference on Automated Software Engineering (ASE).

<a id="2">[2]</a> 
Rahman, Shanto and Shi, August (2024).
[FlakeSync: Automatically Repairing Async Flaky Tests.](https://doi.org/10.1145/3597503.3639115)
Proceedings of the IEEE/ACM 46th International Conference on Software Engineering (ICSE).

<a id="3">[3]</a>
Danglot, Benjamin and Vera-Pérez, Oscar Luis and Baudry, Benoit and Monperrus, Martin (2019).
[Automatic test improvement with DSpot: a study with ten mature open-source projects.](https://doi.org/10.1007/s10664-019-09692-y)
Empirical Software Engineering.

<a id="4">[4]</a>
Just, René (2014).
[The Major mutation framework: Efficient and Scalable Mutation Analysis for Java.](https://doi.org/10.1145/2610384.2628053)
Proceedings of the 2014 International Symposium on Software Testing and Analysis (ISSTA).

<a id="5">[5]</a>
Bell, Jonathan and Legunsen, Owolabi and Hilton, Michael and Eloussi, Lamyaa and Yung, Tifany and Marinov, Darko (2018).
[DeFlaker: Automatically detecting flaky tests.](https://doi.org/10.1145/3180155.3180164)
Proceedings of the 40th International Conference on Software Engineering (ICSE).

<a id="6">[6]</a>
Lam, Wing and Oei, Reed and Shi, August and Marinov, Darko and Xie, Tao (2019)
[iDFlakies: A framework for detecting and partially classifying flaky tests.](https://doi.org/10.1109/ICST.2019.00038)
Proceedings of the 2019 12th IEEE Conference on Software Testing, Validation and Verification (ICST).

<a id="7">[7]</a>
Shi, August and Lam, Wing and Oei, Reed and Xie, Tao and Marinov, Darko (2019)
[iFixFlakies: A framework for automatically fixing order-dependent flaky tests.](https://doi.org/10.1145/3338906.3338925)
Proceedings of the 2019 27th ACM Joint Meeting on European Software Engineering Conference and Symposium on the Foundations of Software Engineering (ESEC/FSE).

<a id="8">[8]</a>
Li, Chengpeng and Baz, Abdelrahman and Shi, August (2024).
[Reducing Test Runtime by Transforming Test Fixtures.](https://doi.org/10.1145/3691620.3695541)
Proceedings of the 39th IEEE/ACM International Conference on Automated Software Engineering.

<a id="9">[9]</a>
Maton, Megan and Kapfhammer, Gregory M and McMinn, Phil (2024).
PseudoSweep: A pseudo-tested code identifier.
Proceedings of the International Conference on Software Maintenance and Evolution, Tool Track.
