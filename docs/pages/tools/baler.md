
---
layout: page
title: Baler
subtitle: Baler: Log Pattern Extraction
---

System Events can result in millions of log lines. The possible lines are unknown in advance and may change with new system software:
![Millions of Log Lines](./resources/figs/Baler_Lines.png){:width="720px"}{: .center-image}

Typical log data tools rely on regular expression (or grep) matching, which requires advance knowledge of log lines in order to build the regular expression. Baler extracts patterns deterministically from log lines, with no advance information required. This results in a vastly smaller number of patterns to parse, and patterns cane be compared across systems.

![Baler Pattern Extractions](./resources/figs/Baler_Patterns.png){:width="720px"}{: .center-image}

### For more information ###
* *[Baler: Deterministic, lossless log message clustering tool](https://ovis.ca.sandia.gov/index.php/Publications_and_presentations)* N. Taerat, J. Brandt, A. Gentile, M. Wong, and C. Leangsuksun. In: Computer Science - Research and Development Volume 26, Numbers 3-4, 285-295, DOI: 10.1007/s00450-011-0155-3 Int'l. Supercomputing Conference (ISC). June 2011.

