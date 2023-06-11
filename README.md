# bazel-lab

This repository contains a collection of lab tasks related to various aspects I've learned about [Bazel](https://bazel.build/).
Bazel is a software tool designed to automate the processes of building and testing software.


## Bazel `build`, `test`, `run`

- differences in execution between the three types
  - build and test have no access to outside directories (if access needed us `--sandbox_writable_path`)
  - run allows access to outside directories

- differences when creating rules: path vs short_path

- differences when passing arguments:
  - run: `-- ...`
  - test: `--test_args=...`

- configuration: constraints and flags

## Unittesting Bazel Rules

TODO

## Other Topics

- dictionary concatenation
