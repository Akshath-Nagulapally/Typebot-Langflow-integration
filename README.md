# Typebot-Langflow-integration




This repo has the following folders: Typebot.io and Langflow.


here are the instructions to host typebot.io: https://docs.typebot.io/self-hosting/manual




the documentation for creating a custom block is given here(at the very bottom) :


https://github.com/baptisteArno/typebot.io/blob/c99298e49b8dc722f7259703f22cef8dc99a919f/CONTRIBUTING.md?plain=1#L105




(I have already integrated that into this project)






Plan is to make a custom block in typebot that acts as basically an api endpoint call to langflow.
This is a feature in langflow already(api endpoint is created). All the block needs to do is to redirect to the self hosted version of langflow and then call that endpoint everytime that block is triggered in the flow.


Here is the repo of langflow as well.


https://github.com/logspace-ai/langflow




I have created an empty block in this code already(in the UI it will be visible all the way at the bottom under integrations subheading.)

