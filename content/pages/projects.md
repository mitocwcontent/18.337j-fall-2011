---
content_type: page
title: Projects
uid: c0426d62-bad7-f3e2-33eb-38753796ea60
---

[Kinds of Projects]({{< baseurl >}}/pages/projects#1)

[Julia-related Project Ideas]({{< baseurl >}}/pages/projects#2)

[Modern Parallel Linear Algebra Project Ideas]({{< baseurl >}}/pages/projects#3)

[Parallel Algorithms, Libraries Project Ideas]({{< baseurl >}}/pages/projects#4)

[Abstractions and Infrastructure Project Ideas]({{< baseurl >}}/pages/projects#5)

[Tools]({{< baseurl >}}/pages/projects#6)

[Sample Student Projects]({{< baseurl >}}/pages/projects#7)

{{< anchor "1" >}}{{< /anchor >}}Kinds of Projects
--------------------------------------------------

*   problem X on parallel architecture/environment Y
*   parallel algorithm for X
*   performance comparisons
    *   what is best algorithm in environment X?
    *   or in input data case X?
    *   how good is, e.g. MPI message latency and could it be better?
*   debugging and monitoring parallel programs
*   parallel abstractions, platforms (e.g. MapReduce)
*   resource sharing infrastructure
*   cloud infrastructure
*   making technical computing more fun

{{< anchor "2" >}}{{< /anchor >}}Julia-related Project Ideas
------------------------------------------------------------

*   Can use as an implementation language
    *   many parallel algorithms are likely to be much easier in Julia than MPI
*   Or work on the platform itself
    *   whole parallel computing system written in Julia, quite compact
    *   parallel computing base: 1600 lines (multi.j)
    *   distributed arrays: 762 lines

{{< anchor "3" >}}{{< /anchor >}}Modern Parallel Linear Algebra Project Ideas
-----------------------------------------------------------------------------

*   LU without block-cyclic
*   LU with dynamic # of CPUs
*   new SVD algorithm

{{< anchor "4" >}}{{< /anchor >}}Parallel Algorithms, Libraries Project Ideas
-----------------------------------------------------------------------------

*   optimization
*   numerical integration
*   multigrid
*   parallel data structures other than arrays
    *   graphs, tables, sparse arrays

{{< anchor "5" >}}{{< /anchor >}}Abstractions and Infrastructure Project Ideas
------------------------------------------------------------------------------

*   a MapReduce or dataflow framework in Julia
*   some other highly-reusable parallel computation
*   high-level EC2 interface
*   storage
    *   persistent distributed arrays
    *   integrate a distributed FS (HDFS, scidb, sector)
*   cluster sharing tools

{{< anchor "6" >}}{{< /anchor >}}Tools
--------------------------------------

*   What would make technical computing more fun?
*   Watching/choreographing parallel computations
*   Social coding features
    *   collaboration
    *   shared "wisdom"
*   Visualization

{{< anchor "7" >}}{{< /anchor >}}Sample Student Final Projects
--------------------------------------------------------------

Three of the students in the class have provided their final projects for publication on OCW and they are presented here with their permission.

Parallel FFT in Julia: [Slide (PDF - 1.6MB)]({{< baseurl >}}/resources/mit18_337jf11_fft_pres), [Code (TXT)](./resolveuid/7574964c53feac5d89568be3d0644fdc), [Report (PDF)]({{< baseurl >}}/resources/mit18_337jf11_fft_rpt) (Courtesy of anonymous MIT student. Used with permission.)

Social coding: [Slides (![This resource may not render correctly in a screen reader.](/images/inacessible.gif)PDF)]({{< baseurl >}}/resources/mit18_337jf11_social_pres), [Report (PDF)]({{< baseurl >}}/resources/mit18_337jf11_social_rpt) (Courtesy of anonymous MIT student. Used with permission.)

Replica-Exchange Molecular Dynamics on Hadoop: [Report (PDF)]({{< baseurl >}}/resources/mit18_337jf11_hadoop_rpt) (Courtesy of Zachary Ulissi. Used with permission.)