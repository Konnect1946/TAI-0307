Works only in OpenAI mode.

- Initial prompt is smaller, more concise. (100ish tokens).

- OpenAI Context Size
Allows you to choose a max token range for oai. More tokens, more memory.
But it will burn through funds faster. A bit scuffed as tavern will slowly
remove chat history until it reaches the target amount if set lower.

- NSFW Toggle
Bad code :)

- Keep Example Dialogue
By default tavern seems to slowly remove/delete example dialogues. This 
leads to characters forgetting how to format messages and the information
in those examples. This will keep everything in the "Examples of dialogue"
field, for better or worse if there are grammar/spelling errors. It'll
re-insert the example dialogue if missing. (at the cost of more tokens)
Note that by having example dialogues included the AI will have less
memory to work with, so prioritize what you'd like. Leaving it off keeps
the default way example dialogue is removed.

- Enhance Definitions
Adds the following prompt to the initial prompt:

"If you have more knowledge of CHAR_NAME, add to the character's lore
and personality to enhance them but keep the Character Sheet's definitions
absolute."

Self explanatory, the model is very intelligent and knows a lot.