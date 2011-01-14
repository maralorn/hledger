---
title: hledger development
---

# hledger development

**Support** for users and developers:

- chat Simon (sm) on the
  [\#ledger](irc://irc.freenode.net/#ledger) irc channel which we
  share, or [email me](mailto:simon@joyful.com?subject=hledger:)
- [report](http://code.google.com/p/hledger/issues/entry)
  problems at [bugs.hledger.org](http://bugs.hledger.org)
  ([view all](http://bugs.hledger.org/grid))
- share and test journal snippets at paste . hledger.org
- <form action="http://groups.google.com/group/hledger/boxsubscribe" >
  join the hledger mail list at <a href="http://list.hledger.org">list.hledger.org</a>. Your email:
  <input type=text name=email><input type=submit name="sub" value="Subscribe">
  </form>

**Goals:** the hledger project aims to produce

-   a practical, accessible, dependable tool for end users
-   a useful library and toolbox for finance-minded haskell programmers
-   a successful, time-and-money-solvent project within a thriving ecosystem of financial software projects.

**Code:**

>`darcs get --lazy http://joyful.com/repos/hledger`  
>`cd hledger`  
>`make` or `make install`

- [browse the repo](http://joyful.com/darcsweb/darcsweb.cgi?r=hledger),
  [release notes](NEWS.html),
  [developer notes](http://joyful.com/darcsweb/darcsweb.cgi?r=hledger;a=plainblob;f=/NOTES)
- [api docs](http://hledger.org/api-doc), [internal code docs](http://hledger.org/code-doc) for all packages
- [hledger](http://hackage.haskell.org/package/hledger),
  [hledger-lib](http://hackage.haskell.org/package/hledger-lib),
  [hledger-chart](http://hackage.haskell.org/package/hledger-chart),
  [hledger-vty](http://hackage.haskell.org/package/hledger-vty),
  [hledger-web](http://hackage.haskell.org/package/hledger-web)
  packages
- [hledger](http://packdeps.haskellers.com/feed/?needle=hledger),
  [hledger-lib](http://packdeps.haskellers.com/feed/?needle=hledger-lib),
  [hledger-chart](http://packdeps.haskellers.com/feed/?needle=hledger-chart),
  [hledger-vty](http://packdeps.haskellers.com/feed/?needle=hledger-vty),
  [hledger-web](http://packdeps.haskellers.com/feed/?needle=hledger-web)
  dependency reports
- [test coverage](http://hledger.org/profs/coverage/hpc_index_fun.html),
  [benchmark](http://hledger.org/profs/latest.bench),
  [profile](http://hledger.org/profs/latest.prof),
  [heap](http://hledger.org/profs/latest.ps)
  reports

<a href="http://joyful.com/darcsweb/darcsweb.cgi?r=hledger;a=shortlog"><img src=http://joyful.com/repos/hledger/commits.png border=0></a>
<a href="https://www.google.com/analytics/reporting/?reset=1&id=15489822" accesskey="a"></a>

**Related projects**

-   John Wiegley's [ledger](http://wiki.github.com/jwiegley/ledger) inspired hledger.
-   h/ledger inspired Uwe Hollerbach's [umm](http://www.korgwal.com/umm/).
-   Tim Docker's [ledger-reports](http://dockerz.net/repos/ledger-reports) builds on hledger to generate
    [html reports](http://dockerz.net/software/hledger_report_sample/report.html).
-   I have a few older bits and pieces [here](http://joyful.com/Ledger).