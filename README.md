# qa-noarch-test-feedstock


A simple dummy Conda noarch: python package used for QA testing.

The package installs a command called qa-noarch-test that prints:

hello world
##Build
conda build recipe
##Install (local)
conda install --use-local qa-noarch-test
##Run
qa-noarch-test

##Output:

hello world
##Purpose

This package is intended only for testing Conda feedstock builds for noarch Python packages across Linux, macOS, and Windows.