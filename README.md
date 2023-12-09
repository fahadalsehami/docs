# Medera LLM-BHM

The Large Language Model Behavioral Health Machine (LLM-BHM) is intend to a optimize backend for managing LLMs. It serves to facilitate communication, analysis and coordination between data, language models(running on the CPU), prompts, and various tools to streamline AGI development.

## Features of LLM-BHM:

#### - Inference optamization: 
 The Anarchy LLM-VM is optimized from agent level all the way to assembly on known LLM architectures to get the most bang for your buck. With state of the art batching, sparse inference and quantization, distillation, and multi-level colocation, we aim to provide the fastest framework available.
- Navigation
- Customizations
- API Reference pages
- Use of popular components

### Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command

```
npm i -g mintlify
```

Run the following command at the root of your documentation (where mint.json is)

```
mintlify dev
```

### Publishing Changes

Install our Github App to autopropagate changes from youre repo to your deployment. Changes will be deployed to production automatically after pushing to the default branch. Find the link to install on your dashboard. 

#### Troubleshooting

- Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `mint.json`
