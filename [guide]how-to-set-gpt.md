## CHATBOT PROMPT SETTING TIP☆

### GUIDE(1) Strat!
To create a chatbot GPT that mimics a comic character's settings and speech patterns using '○○○-wiki.pdf' for the character's settings and '○○○-script.txt' for the character's dialogues, we can follow a structured approach to prompt engineering, incorporating insights from large language model (LLM) utilization and prompt engineering strategies.

1. Define the Objective: Generate responses that accurately reflect the comic character's personality, based on their background and typical dialogues.

2. Constraints: The chatbot should use language and tones that are consistent with the character's portrayal in the comics. Responses should be concise and in line with the character's usual speech patterns.

3. Essential Information: Incorporate character traits, historical background, and typical phrases from the 'jyj-wiki.pdf'. Use specific dialogue examples from 'jyj-script.txt' to train or guide the model on how the character speaks.

4. Identify Pitfalls: Avoid generic responses that don't match the character's unique speech patterns or personality. Ensure the chatbot doesn't produce out-of-character responses.

5. Consider Improvements:

- Utilize few-shot prompting by providing the model with examples of the character's dialogues as part of the input prompt to guide response generation.
- Implement chain-of-thought (CoT) prompting for complex interactions, encouraging the model to "think" in character.
- Apply positive guidance in prompts, encouraging the model to emulate the character's tone and mannerisms accurately.
6. Craft Improved Prompt: Here's an illustrative example of how you might structure a prompt using the character's dialogue examples and background information:

```
"Given [Character's Name] background as [brief character background] and typical mannerisms such as [character trait 1], [character trait 2], respond to the following scenario in [Character's Name]'s typical style: [Scenario here]. For example, in a situation where [example situation], [Character's Name] might say something like '[example dialogue]'."
```

Remember, this strategy leverages both the character's detailed background and specific dialogue examples to create a rich, character-consistent chatbot experience.

### GUIDE(2) How to become more sensitive
Based on the character's background and dialogue from the documents, here's a tailored prompt for creating a chatbot GPT to emulate the animation character's settings and speech mannerisms:

(case: Jeon Young-joong, 19-years-old, Wonjoong High School 3rd grade)
```
"Imagine you are [Character Name], a 19-year-old high school student from [School Name], known for your outstanding basketball skills and unique personality. Your height is 192cm, and you are an ISFP with blood type O. You play as a small forward with a special talent for dunking, although you claim to have no hobbies outside basketball. Your dialogue style is direct, often infused with a mix of humor and seriousness, reflecting your competitive spirit and complex relationships with teammates. Given your background and interactions, how would you respond to the following scenarios?"

1. A teammate challenges you to a one-on-one practice match.
2. You're asked about your feelings after a tough loss in an important game.
3. A younger student asks for advice on how to improve in basketball.
4. You encounter a rival player from another school outside of a game setting.

[Add specific scenarios here based on the 'jyj-script.txt' content, maintaining the character's unique tone and style as seen in the script excerpts.]
```

This prompt leverages the detailed character description, including personal traits, relationships, and specific dialogue examples, to guide the GPT model in generating responses that accurately reflect the character's voice and personality as depicted in the animation.