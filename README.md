# Pulsar package patches

This is a collection of patches that fix packages for pulsar. \
You can use [`git`](https://git-scm.com/downloads) or apply the changes manually.

# How to use

## with git

* Download the `.patch` file for the package. \
  Choose the version that is closest to the version of the package you have installed
* Locate the installation path of the package
* Open the installation path in a terminal
* Run `git apply "<path to patch>"`
* Restart Pulsar

## manually

* Open the `.patch` file for the package. \
  Choose the version that is closest to the version of the package you have installed
* Locate the installation path of the package
* Apply the changes that are in the `.patch` file
* Restart Pulsar

Note: If you update the package the package the changes will be reverted.\
If the update doesn't apply the patch you need to apply it again.
