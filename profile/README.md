<div align="center">

<img src="https://github.com/astack-tech/astack/raw/master/assets/logo.svg" alt="AStack Logo" width="256" height="256">

# AStack

**A composable framework for building AI applications**

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/astack-tech/astack/pulls)
[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/astack-tech/astack)

🎉 **Beta Version Released** 🎉

*AStack is under active development but already provides significant value for building AI applications*

English | [简体中文](./README.zh-CN.md)

</div>

## 📋 Overview

AStack is a composable framework designed to simplify the development of AI applications through a "everything is a component" philosophy. It provides a zero-adaptation layer design that enables seamless integration between various AI models, tools, and custom business logic.

AStack is an independent technical framework with its own architecture and ecosystem, built on top of [Hlang](https://github.com/hlang-tech) - a highly semantic [fourth-generation language (4GL)](https://en.wikipedia.org/wiki/Fourth-generation_programming_language) inspired by Flow-Based Programming paradigms. This foundation on Hlang, which is particularly well-suited for computational modeling and AI-generated code, is what gives AStack its power. The framework emphasizes minimalism and performance, allowing developers to create complex systems with minimal boilerplate code while maintaining complete technical autonomy.

### Key Features

- **Component-Based Architecture**: Build complex AI systems by composing simple, reusable components
- **Zero-Adaptation Layer Design**: Components work together without intermediate adaptation layers
- **Pipeline Execution Model**: Support for both independent and pipeline execution modes
- **Extensible Tool System**: Easily integrate new capabilities through a unified tool interface
- **Multi-Model Support**: Seamless integration with various LLM providers
- **Declarative Workflow**: Define complex AI workflows with minimal code
- **Minimalist API Design**: Focus on simplicity and expressiveness

## 👁 Design Philosophy

AStack is built on several core philosophical principles that guide its development:

### Everything is a Component

In AStack, everything from a simple tool to a complex agent is represented as a component. This unified approach simplifies development and promotes code reuse. Components can be composed, extended, and reconfigured to suit various use cases.

### Zero-Adaptation Layer Design

Unlike many frameworks that require adapters or middleware between components, AStack adopts a zero-adaptation layer design. Components can directly interact with each other without intermediate transformation layers, reducing complexity and improving performance.

### Minimalism Over Complexity

AStack prioritizes simple, intuitive APIs over complex abstractions. This minimalist approach leads to more maintainable code and a gentler learning curve.
