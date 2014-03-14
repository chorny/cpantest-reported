cpantest-reported
=================

Cpantesters problems that were reported.

To use this repository, CPAN.pm 2.0 is recommended, it looks for distroprefs in subdirectories too (but not in .git).

If you want to add a distribution to this list, report it first (check if it was reported before) and add link to ticket in comment. If was in list and new version was released with same problem, notify author about it (usually adding it to ticket, for ex. on rt.cpan.org you can modify field "Broken in"). Distributions should be added to this list only using Dist-Name-version format. If you want to disable distribution completely, do it in your own black list. Please do not add popular distributions (for ex. Plack) that do not hang in majority of runs.
The goal for this repository is to disable distributions with problems. As many such distributions will never be updated, disabling them once is enough. Also it allows to encounter and report only problems that were not reported yet.

