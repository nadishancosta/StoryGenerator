## StoryGenerator
Fine-tuning GPT-2 to generate stories

Here pretrained GPT-2 is used as the base model.

The goal of this research project was to create a tool for writers to gain inspiration to prevent them from being stuck on storylines due to writer's block or high work pressure.
Additionally, the tool was envisioned having the capability of continually generating the story beyond th 1024 character limit of GPT-2. However, with the limited resources present, the decision to limit the generation was taken. Additional research is required to allow this functionality.

Initial set of requirements for this model are as follows:

1. Provide prompt for story
2. Generate story to the token limit of the model
3. Continue generation after user approval of initial generation
4. Regenerate story if user is not approving of initial generation

Hencer, various other models were reviewed for their performance. Obviously GPT-4 performed exceptionally well in writing stories. However, I wanted to create a tool that is accessible and free for everyone with a computer and an internet connection.

This meant the model needed to be lightweight enough to run on the free versions of online tools like Colab.


Initial exploration into GPT-2 showed promising performance with downstream tasks (provided suffcient finetuning). Additionally, GPT-2 is very lightweight and efficient in its performance on minimal hardware. This meant the model could be downloaded locally and used as needed offline.

This remains true for the training process as well.

