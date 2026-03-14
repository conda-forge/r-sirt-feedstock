About r-sirt-feedstock
======================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/r-sirt-feedstock/blob/main/LICENSE.txt)


About r-sirt
------------

Home: https://github.com/alexanderrobitzsch/sirt

Package license: GPL-2.0-only

Summary: Supplementary functions for item response models aiming to complement existing R packages. The functionality includes among others multidimensional compensatory and noncompensatory IRT models (Reckase, 2009, <doi:10.1007/978-0-387-89976-3>), MCMC for hierarchical IRT models and testlet models (Fox, 2010, <doi:10.1007/978-1-4419-0742-4>), NOHARM (McDonald, 1982, <doi:10.1177/014662168200600402>), Rasch copula model (Braeken, 2011, <doi:10.1007/s11336-010-9190-4>; Schroeders, Robitzsch & Schipolowski, 2014, <doi:10.1111/jedm.12054>), faceted and hierarchical rater models (DeCarlo, Kim & Johnson, 2011, <doi:10.1111/j.1745-3984.2011.00143.x>), ordinal IRT model (ISOP; Scheiblechner, 1995, <doi:10.1007/BF02301417>), DETECT statistic (Stout, Habing, Douglas & Kim, 1996, <doi:10.1177/014662169602000403>), local structural equation modeling (LSEM; Hildebrandt, Luedtke, Robitzsch, Sommer & Wilhelm, 2016, <doi:10.1080/00273171.2016.1142856>).

Documentation: https://sites.google.com/view/alexander-robitzsch/software

About r-sirt
------------

Home: https://github.com/alexanderrobitzsch/sirt

Package license: GPL-2.0-only

Summary: Supplementary functions for item response models aiming to complement existing R packages. The functionality includes among others multidimensional compensatory and noncompensatory IRT models (Reckase, 2009, <doi:10.1007/978-0-387-89976-3>), MCMC for hierarchical IRT models and testlet models (Fox, 2010, <doi:10.1007/978-1-4419-0742-4>), NOHARM (McDonald, 1982, <doi:10.1177/014662168200600402>), Rasch copula model (Braeken, 2011, <doi:10.1007/s11336-010-9190-4>; Schroeders, Robitzsch & Schipolowski, 2014, <doi:10.1111/jedm.12054>), faceted and hierarchical rater models (DeCarlo, Kim & Johnson, 2011, <doi:10.1111/j.1745-3984.2011.00143.x>), ordinal IRT model (ISOP; Scheiblechner, 1995, <doi:10.1007/BF02301417>), DETECT statistic (Stout, Habing, Douglas & Kim, 1996, <doi:10.1177/014662169602000403>), local structural equation modeling (LSEM; Hildebrandt, Luedtke, Robitzsch, Sommer & Wilhelm, 2016, <doi:10.1080/00273171.2016.1142856>).

Documentation: https://sites.google.com/view/alexander-robitzsch/software

Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=27723&branchName=main">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-sirt-feedstock?branchName=main">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64_r_base4.4</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=27723&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-sirt-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_r_base4.4" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_r_base4.5</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=27723&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-sirt-feedstock?branchName=main&jobName=linux&configuration=linux%20linux_64_r_base4.5" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_r_base4.4</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=27723&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-sirt-feedstock?branchName=main&jobName=win&configuration=win%20win_64_r_base4.4" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_64_r_base4.5</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=27723&branchName=main">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-sirt-feedstock?branchName=main&jobName=win&configuration=win%20win_64_r_base4.5" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-r--sirt-green.svg)](https://anaconda.org/conda-forge/r-sirt) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/r-sirt.svg)](https://anaconda.org/conda-forge/r-sirt) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/r-sirt.svg)](https://anaconda.org/conda-forge/r-sirt) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/r-sirt.svg)](https://anaconda.org/conda-forge/r-sirt) |

Installing r-sirt
=================

Installing `r-sirt` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Once the `conda-forge` channel has been enabled, `r-sirt` can be installed with `conda`:

```
conda install r-sirt
```

or with `mamba`:

```
mamba install r-sirt
```

It is possible to list all of the versions of `r-sirt` available on your platform with `conda`:

```
conda search r-sirt --channel conda-forge
```

or with `mamba`:

```
mamba search r-sirt --channel conda-forge
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search r-sirt --channel conda-forge

# List packages depending on `r-sirt`:
mamba repoquery whoneeds r-sirt --channel conda-forge

# List dependencies of `r-sirt`:
mamba repoquery depends r-sirt --channel conda-forge
```


About conda-forge
=================

[![Powered by
NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[Azure](https://azure.microsoft.com/en-us/services/devops/), [GitHub](https://github.com/),
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/),
[Drone](https://cloud.drone.io/welcome), and [TravisCI](https://travis-ci.com/)
it is possible to build and upload installable packages to the
[conda-forge](https://anaconda.org/conda-forge) [anaconda.org](https://anaconda.org/)
channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance,
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information, please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating r-sirt-feedstock
=========================

If you would like to improve the r-sirt recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/r-sirt-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks, and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@conda-forge/r](https://github.com/orgs/conda-forge/teams/r/)

