---
title: "How To Use"
weight: 1
---
### Step 1 — API Keys

In order to get started, first choose which AI language model providers you will use. Currently Artifacture supports OpenAI, Anthropic, Google, and Open Router.

Once API keys are acquired, add them to the API Keys form found on the main options below the document name and description.

After that new models will be available for selection in the configuration form drop down.

### Step 2 — Input Configuration

Selecting the model is the only thing that needs to be done before you can begin interacting with AI language models in this program. Do this by either creating a new document  (Create option) or updating the configuration of the current document (Configuration option).

Here is a quick description on configuration fields you can optionally customize:
- **Tokenizer:** This is method in which the submitted text will be parsed and counted. This is required if you select "Max Context Tokens" option to limit the size of the inputs that will be used in generating responses.
- **Max Context Tokens:** The estimated size of the language models "memory". The larger size means the larger portion of the document will be inputted with each submission. Tokenizer is required if you use this option.
- **Max Output Tokens:** The maximum size of the response from language models.
- **Temperature:** The "creativity" or "predictability" of the model responses. 1 is for the maximum creativity and 0 is for the maximum predictability.
- **Top K:** The number of words the AI language model will choose from during output generation. Lower values mean more focused and predictable responses and high values mean more varied and potentially creative outputs.
- **Top P:** The probability threshold for AI language models to select their words. The lower values mean the responses are more focused and coherent and the high values results in more potentially surprising word choices.
- **Custom Instructions:** Append a message at the top of every input as a special set of instructions for the AI language model to follow.

### Step 3 — Send Message

Congratulations :) You are all set! With API keys and input configurations in place, you can send messages, edit existing messages for submission, and regenerate AI generated responses in branches.
