---
layout: post
title: "prioritizr R package"
urlProject: "https://prioritizr.net"
date: 2018-01-17 00:00:01
categories: projects
---

The prioritizr R package uses integer linear programming (ILP) techniques to provide a flexible interface for building and solving conservation planning problems. It supports a broad range of objectives, constraints, and penalties that can be used to custom-tailor conservation planning problems to the specific needs of a conservation planning exercise. Once built, conservation planning problems can be solved using a variety of commercial and open-source exact algorithm solvers. In contrast to the algorithms conventionally used to solve conservation problems, such as heuristics or simulated annealing, the exact algorithms used here are guaranteed to find optimal solutions. Furthermore, conservation problems can be constructed to optimize the spatial allocation of different management actions or zones, meaning that conservation practitioners can identify solutions that benefit multiple stakeholders. Finally, this package has the functionality to read input data formatted for the Marxan conservation planning program, and find much cheaper solutions in a much shorter period of time than Marxan. Download the [official version from CRAN](https://cran.r-project.org/web/packages/prioritizr/index.html), or the [developmental version from GitHub](https://github.com/prioritizr/prioritizr). You can learn more about the prioritizr R package by watching my talk at User! 2018 (first video below), or how optimization techniques can be used to inform conservation decision making (second video below).

<div style="width:100%;text-align:center;">
<iframe align="middle" width="720" height="405" src="https://www.youtube.com/embed/da7r3Qyn6ag" frameborder="0" allow="encrypted-media" allowfullscreen style="padding-top:10px">Please try another web-browser to view the embedded video</iframe>
</div>

<div style="width:100%;text-align:center;">
<iframe width="720" height="450" src="https://www.youtube.com/embed/59n6yfg0aYk" title="Webinar: Optimizing to make Better Conservation Decisions" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen style="padding-top:10px"></iframe>
</div>
