<a href="https://astack.tech"><img src="https://raw.githubusercontent.com/astack-tech/.github/main/profile/assets/banner.svg" alt="AStack — Everything is a component. A composable TypeScript framework for AI applications." width="100%"></a>

[Website](https://astack.tech) · [Documentation](https://deepwiki.com/astack-tech/astack) · [Source](https://github.com/astack-tech/astack) · [Examples](https://github.com/astack-tech/astack/tree/master/examples) · [Brand assets](https://astack.tech/brand)

AStack is an open-source TypeScript framework for AI agents, workflows, and RAG applications. Its central idea is **everything is a component**: models, tools, agents, and application logic use a shared component interface. Connect their ports to define how data moves through your application.

## Components, ports, and pipelines

AStack has its own implementation and architecture. It builds on [HLang](https://github.com/hlang-tech/hlang), a [fourth-generation language](https://en.wikipedia.org/wiki/Fourth-generation_programming_language) based on Flow-Based Programming and monadic composition. HLang provides the computational model; AStack adds the components used to build AI applications.

The common interface reduces adapter code between components. Run a component directly with `run()` or connect it to a reactive pipeline through `_transform()`. TypeScript describes the data contracts, and Observable streams carry data between ports. The same explicit structure can be written by a developer or generated with coding tools.

| Package | Purpose |
| --- | --- |
| [`@astack-tech/core`](https://github.com/astack-tech/astack/tree/master/packages/core) | Component contracts, ports, and pipeline composition |
| [`@astack-tech/components`](https://github.com/astack-tech/astack/tree/master/packages/components) | Agents, streaming, and reusable application components |
| [`@astack-tech/integrations`](https://github.com/astack-tech/astack/tree/master/packages/integrations) | Model providers and external service connections |
| [`@astack-tech/tools`](https://github.com/astack-tech/astack/tree/master/packages/tools) | Tools that agents can call |

## Start building

```sh
npm install @astack-tech/core@beta @astack-tech/components@beta @astack-tech/integrations@beta
```

Follow the [quick start](https://astack.tech/#quickstart) to configure a model provider and run your first agent. AStack is in public beta; check the [release notes](https://github.com/astack-tech/astack/releases) before updating dependencies.

Explore [browser automation](https://github.com/astack-tech/astack/tree/master/examples/simple-browser-use), [deep research](https://github.com/astack-tech/astack/tree/master/examples/simple-deep-research), and [recursive language models](https://astack.tech/blog/implementing-rlm-recursive-language-model). Use the source and examples to choose the parts your application needs.

## Contribute

AStack is [MIT licensed](https://github.com/astack-tech/astack/blob/master/LICENSE). Issues, documentation improvements, and pull requests are welcome. Read the [contribution guide](https://github.com/astack-tech/astack/blob/master/.github/CONTRIBUTING.md) and target `dev` when proposing a change.

[Report an issue](https://github.com/astack-tech/astack/issues) · [Open a pull request](https://github.com/astack-tech/astack/pulls) · [Ask DeepWiki](https://deepwiki.com/astack-tech/astack)
