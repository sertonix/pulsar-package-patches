# Pulsar package patches

This is a collection of patches that fix packages for pulsar. \
You need to have [`git`](https://git-scm.com/downloads) installed for this.

# How to use

* Download the `.patch` file for a package. \
  Choose the version that is closest to the version of the package you have installed
* Locate the installation path of the package
* Open the installation path in a terminal
* Run `git apply "<path to patch>"`
* Restart Pulsar

Note: If you update the package the package the changes will be reverted.\
If the update doesn't apply the patch you need to manually apply it again.
