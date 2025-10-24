# Kubeflow Pipelines: Hello World Example

This repository contains a simple **Kubeflow Pipelines (KFP)** example demonstrating how to define, run, and compile basic pipeline components using the `@dsl.component` and `@dsl.pipeline` decorators.

## 🧩 Overview
- Implements two simple KFP components:
  - `say_hello()` — returns a greeting.
  - `how_are_you()` — combines the greeting with an additional message.
- Combines them into a small pipeline (`hello_pipeline()`).
- Runs locally using `local.DockerRunner()`.
- Compiles the pipeline into a deployable YAML file (`pipeline.yaml`).

## 🚀 Example Output

