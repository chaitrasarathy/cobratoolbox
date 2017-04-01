<p align="center">
  <img src="https://raw.githubusercontent.com/laurentheirendt/cobratoolbox/simplified-doc/docs/source/_static/logo.png" height="160px"/>
</p>

The COBRA Toolbox <br> COnstraint-Based Reconstruction and Analysis Toolbox
=======================================================================

<table>
  <tr>
    <td><div align="center"><a href="https://opencobra.github.io/cobratoolbox/latest"><img src="https://img.shields.io/badge/COBRA-docs-blue.svg?maxAge=0"></a></div></td>
    <td><div align="center"><a href="https://groups.google.com/forum/#!forum/cobra-toolbox"><img src="https://img.shields.io/badge/COBRA-forum-blue.svg?maxAge=0"></a></div></td>
    <td><div align="center"><a href="https://github.com/opencobra/cobratoolbox/tree/master/tutorials"><img src="https://img.shields.io/badge/COBRA-tutorials-blue.svg?maxAge=0"></div></td>
    <td><div align="center"><img src="https://img.shields.io/badge/Windows-passing-brightgreen.svg?maxAge=0"></div></td>
    <td><div align="center"><img src="https://img.shields.io/badge/macOS-passing-brightgreen.svg?maxAge=0"></div></td>
  </tr>
  <tr>
    <th style="text-align:center">MATLAB R2016b</th>
    <th style="text-align:center">MATLAB R2015b</th>
    <th style="text-align:center">MATLAB R2014b</th>
    <th style="text-align:center" colspan="2">Code</th>
  </tr>
  <tr>
    <td><div align="center"><a href="https://prince.lcsb.uni.lu/jenkins/job/COBRAToolbox-branches-auto/MATLAB_VER=R2016b/"><img src="https://prince.lcsb.uni.lu/jenkins/buildStatus/icon?job=COBRAToolbox-branches-auto/MATLAB_VER=R2016b"></a></div></td>
    <td><div align="center"><a href="https://prince.lcsb.uni.lu/jenkins/job/COBRAToolbox-branches-auto/MATLAB_VER=R2015b/"><img src="https://prince.lcsb.uni.lu/jenkins/buildStatus/icon?job=COBRAToolbox-branches-auto/MATLAB_VER=R2015b"></a></div></td>
    <td><div align="center"><a href="https://prince.lcsb.uni.lu/jenkins/job/COBRAToolbox-branches-auto/MATLAB_VER=R2014b/"><img src="https://prince.lcsb.uni.lu/jenkins/buildStatus/icon?job=COBRAToolbox-branches-auto/MATLAB_VER=R2014b"></a></div></td>
    <td><div align="center"><a href="https://codecov.io/gh/opencobra/cobratoolbox/branch/master"><img src="https://codecov.io/gh/opencobra/cobratoolbox/branch/master/graph/badge.svg?maxAge=0"></a></div></td>
    <td><div align="center"><img src="https://prince.lcsb.uni.lu/jenkins/userContent/codegrade.svg?maxAge=0" alt="Ratio of the number of inefficient code lines and the total number of lines of code (in percent). A: 0-3%, B: 3-6%, C: 6-9%, D: 9-12%, E: 12-15%, F: > 15%."></div></td>
  </tr>
</table>

Requirements
--------------

![#ff0000](https://placehold.it/15/ff0000/000000?text=+) Please follow [this guide](https://github.com/opencobra/cobratoolbox/blob/master/.github/REQUIREMENTS.md) in order to configure your system properly.

Installation
------------

1. Download this repository (the folder `cobratoolbox` will be created). It is not recommended to download the repository as a `.zip` file. You can clone the repository using:
    ````bash
    $ git clone https://github.com/opencobra/cobratoolbox.git cobratoolbox
    ````
    ![#ff0000](https://placehold.it/15/ff0000/000000?text=+) Run this command in `Terminal` (on `linux`/`macOS`) or in `Git Bash` (on `Windows`), and **not** in `MATLAB`.

2. Change to the folder `cobratoolbox` and from `MATLAB`, run
    ````Matlab
    >> initCobraToolbox
    ````

3. You can test your installation by running from `MATLAB`:
    ````Matlab
    >> testAll
    ````

Tutorials
---------

All tutorials are included in the folder [tutorials](https://github.com/opencobra/cobratoolbox/tree/master/tutorials). More tutorials are currently being prepared.

Support and Documentation
--------------

- The documentation is available [here](http://opencobra.github.io/cobratoolbox). This version is in development, but the legacy version of the documentation is  [here](http://opencobra.github.io/cobratoolbox/deprecated/docs/index.html).

- Answers to Frequently Asked Questions (**FAQ**) are [here](https://github.com/opencobra/cobratoolbox/blob/master/.github/FAQ.md).

- If you need support, please feel free to post your question in our <a href="https://groups.google.com/forum/#!forum/cobra-toolbox"><img src="https://img.shields.io/badge/COBRA-forum-blue.svg"></a>.

How to contribute
-----------------

<p align="center">
<img src="https://raw.githubusercontent.com/opencobra/MATLAB.devTools/develop/assets/devTools_logo.png" height="120px"/>
</p>

![#ff0000](https://placehold.it/15/ff0000/000000?text=+) **Check out the [MATLAB.devTools](https://github.com/opencobra/MATLAB.devTools) - and contribute the smart way!**

- Please follow the [Contributing Guide](https://github.com/opencobra/cobratoolbox/blob/master/.github/CONTRIBUTING.md).
- More information on writing a **test** is [here](https://github.com/opencobra/cobratoolbox/blob/master/.github/TESTGUIDE.md).
- A guide on reporting an **issue** is [here](https://github.com/opencobra/cobratoolbox/blob/master/.github/ISSUEGUIDE.md).

How to cite `The COBRA Toolbox`
---------------

When citing `The COBRA Toolbox`, it is important to cite the original paper where an algorithm was first reported, as well as its implementation in `The COBRA Toolbox`. This is important, because the objective of `The COBRA Toolbox` is to amalgamate and integrate the functionality of a wide range of COBRA algorithms and this will be undermined if contributors of new algorithms do not get their fair share of citations. The following is one example how to approach this within the methods section of a paper (**not** the supplemental material please):

*To generate a context-specific model the FASTCORE algorithm [1], implemented in The COBRA Toolbox [2], was employed.*

>[1] = Vlassis N, Pacheco MP, Sauter T (2014) Fast Reconstruction of Compact Context-Specific Metabolic Network Models. PLoS Comput Biol 10(1): e1003424.
>

>[2] = Schellenberger J, Que R, Fleming RMT, Thiele I, Orth JD, Feist AM, Zielinski DC, Bordbar A, Lewis NE, Rahmanian S, Kang J, Hyduke DR, Palsson BØ. 2011 Quantitative prediction of cellular metabolism with constraint-based models: The COBRA Toolbox v2.0. Nature Protocols 6:1290-1307.
>

Compatibility and Binaries
---------------------------

Read more on the compatibility with SBML-FBCv2 [here](https://github.com/opencobra/cobratoolbox/blob/master/.github/NOTES.md).

For convenience, we provide the [`SBMLToolbox 4.1.0`](http://sbml.org/Software/SBMLToolbox), and [`glpk_mex`](https://github.com/blegat/glpkmex) in `external/toolboxes`, [`libSBML-5.13.0-matlab`](http://sbml.org/Software/libSBML) in `src/io/utilities`.

[Binaries](https://github.com/opencobra/COBRA.binary) for these libraries are provided in a submodule for Mac OS X 10.6 or later (64-bit), GNU/Linux Ubuntu 10.0 (64-bit), and Microsoft Windows 7 (64-bit).
For unsupported OS, please refer to their respective building instructions ([`glpk_mex`](https://github.com/blegat/glpkmex#instructions-for-compiling-from-source), [`libSBML`](http://sbml.org/Software/libSBML/5.13.0/docs//cpp-api/libsbml-installation.html)).
