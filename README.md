# LLM Prompt Templates

A repository of Jinja2 templates that can be used in backends such as [TabbyAPI](), [Aphrodite Engine](https://github.com/PygmalionAI/aphrodite-engine/), and any backend that uses `apply_chat_template` from HuggingFace.

## How do I make these?

Look at [Huggingface's Documentation](https://huggingface.co/docs/transformers/chat_templating). It contains all the information you need to understand Jinja2's syntax and a straightforward way to create a chat template.

## Downloading

1. Click on the template file
  
2. Click the download button
  
3. Move the jinja file to the appropriate folder for your backend
  

## Plug into TabbyAPI

An alternative way to get all these templates at once is to do the following inside your TabbyAPI install:

1. Remove the existing templates folder
  
2. Open up a terminal and `cd <your TabbyAPI install>`
  
3. Clone this repo (`git clone https://github.com/theroyallab/llm-prompt-templates templates`)
  
4. Run TabbyAPI (and set your config to use a new template)
  

## Contributing

If you have issues with the project:

- Describe the issues in detail
  
- If you have a feature request, please indicate it as such.
  

If you have a Pull Request

- Describe the pull request in detail, what, and why you are changing something

## Thanks to

- The Aphrodite team for introducing us to Jinja and its lightweight system.

- The vllm project for initial chat templates.

- HuggingFace for making Jinja's syntax understandable for chat templating and adding AutoTokenizer support.
