About gazebo-robotraconteur-sim-drivers-feedstock
=================================================

Feedstock license: [BSD-3-Clause](https://github.com/robotraconteur/gazebo-robotraconteur-sim-drivers-feedstock/blob/main/LICENSE.txt)

Home: https://github.com/robotraconteur-contrib/gazebo-robotraconteur-sim-drivers

Package license: Apache-2.0

Summary: Simulated Robot Raconteur drivers for Gazebo virtual devices

Current build status
====================


<table><tr>
    <td>All platforms:</td>
    <td>
      <img src="https://img.shields.io/badge/noarch-disabled-lightgrey.svg" alt="noarch disabled">
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-gazebo--robotraconteur--sim--drivers-green.svg)](https://anaconda.org/robotraconteur/gazebo-robotraconteur-sim-drivers) | [![Conda Downloads](https://img.shields.io/conda/dn/robotraconteur/gazebo-robotraconteur-sim-drivers.svg)](https://anaconda.org/robotraconteur/gazebo-robotraconteur-sim-drivers) | [![Conda Version](https://img.shields.io/conda/vn/robotraconteur/gazebo-robotraconteur-sim-drivers.svg)](https://anaconda.org/robotraconteur/gazebo-robotraconteur-sim-drivers) | [![Conda Platforms](https://img.shields.io/conda/pn/robotraconteur/gazebo-robotraconteur-sim-drivers.svg)](https://anaconda.org/robotraconteur/gazebo-robotraconteur-sim-drivers) |

Installing gazebo-robotraconteur-sim-drivers
============================================

Installing `gazebo-robotraconteur-sim-drivers` from the `robotraconteur` channel can be achieved by adding `robotraconteur` to your channels with:

```
conda config --add channels robotraconteur
conda config --set channel_priority strict
```

Once the `robotraconteur` channel has been enabled, `gazebo-robotraconteur-sim-drivers` can be installed with `conda`:

```
conda install gazebo-robotraconteur-sim-drivers
```

or with `mamba`:

```
mamba install gazebo-robotraconteur-sim-drivers
```

It is possible to list all of the versions of `gazebo-robotraconteur-sim-drivers` available on your platform with `conda`:

```
conda search gazebo-robotraconteur-sim-drivers --channel robotraconteur
```

or with `mamba`:

```
mamba search gazebo-robotraconteur-sim-drivers --channel robotraconteur
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search gazebo-robotraconteur-sim-drivers --channel robotraconteur

# List packages depending on `gazebo-robotraconteur-sim-drivers`:
mamba repoquery whoneeds gazebo-robotraconteur-sim-drivers --channel robotraconteur

# List dependencies of `gazebo-robotraconteur-sim-drivers`:
mamba repoquery depends gazebo-robotraconteur-sim-drivers --channel robotraconteur
```




Updating gazebo-robotraconteur-sim-drivers-feedstock
====================================================

If you would like to improve the gazebo-robotraconteur-sim-drivers recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`robotraconteur` channel, whereupon the built conda packages will be available for
everybody to install and use from the `robotraconteur` channel.
Note that all branches in the robotraconteur/gazebo-robotraconteur-sim-drivers-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@johnwason](https://github.com/johnwason/)

