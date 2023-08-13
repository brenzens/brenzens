# Workshop Materials

Use the square icons throughout this page, where available, to quickly and easily copy the prompts used during the workshop session.

| Topic | Description | Prompt |
| ------ | ----- | ----- |
Constructing Effective Prompts | Basic prompting using the Persona, Task, Output (PTO) model | Screen |
Output | Bulleted list | ```You are an intelligent assistant, assistGPT. Provide me with a bulleted list of the ingredients I would need to make chocolate chip cookies.```
Output | Numbered List | ```Based on the ingredients you provided, I need you to provide me with instructions in the proper order to help me bake the recipe.```
Output | Refactoring based on template | ```There are gluten intolerances. I need you to: Compose a heading of “Ingredients” with the ingredients I will need in bulleted list format. Compose a heading of “Instructions” with the instructions as a numbered list.```
Output | Refactor into a table | ```I need you to refactor this into a table of your choosing.```
Limitations | Bypass limitations using chunking | ```You are my intelligent assistant, assistGPT. I have a series of content to share with you. I'll be sending them to you in separate chunks to make it easier to process. Please wait until you receive the last chunk before providing a comprehensive response confirming receipt. You must await further instruction. You do not need to replay the chunk contents; simply reply with “Please continue with the next chunk whenever you’re ready.” Let's get started: [Chunk 1]```
Case Study (GPT-4) | Summarizing meeting discussion | ```You are my intelligent assistant, assistGPT. I have a series of content to share with you. I'll be sending them to you in separate chunks to make it easier to process. Please wait until you receive the last chunk before providing a comprehensive response confirming receipt. You must await further instruction.``` [Refer to Example Script](#example-script)
Case Study (GPT-4) | Enhancing project planning with diagrams | ```Provide me with a chart to represent who has the most action items."```
Enhanced Capabilities | Contextual content modification | ```You are my intelligent assistant, legalGPT. You have a specialization in Ontario’s privacy legislation. I need you to complete a series of tasks in order. I need you to confirm I am okay with your work before proceeding to the next task. Task1: Review the attachment provided. Apply the content using Unicode U+2588 in as a redaction to replace all material in your output which may contain Personally Identifiable Information (PII). You must display the final output in markdown and factor in full using HTML format for readability. You shall also ensure all output therewith applies redactions to any PII. Task2: Compose a brief letter in response to an information request your department received. The letter must not exceed 250 words. Tone: Professional. 50% spartan. Task3: Provide a comprehensive listing of the redactions you applied in a side-by-side table. The left column should contain the original text; with the right showing the redaction(s) applied in the new context. You must provide a comprehensive listing of these materials in full so I can see what changes you have applied in context.```
Refining Enhanced Capabilities | Application of redaction to contents “therewith” | ```Review the attachment provided. Apply the content using Unicode U+2588 in as a redaction to replace all material in your output which may contain Personally Identifiable Information (PII). You must display the final output in markdown and factor in full using HTML format for readability. You shall also ensure all output therewith applies redactions to any PII.```
Prompt Tuning | “Few shot” learning | ```I will provide you with sentences that describe flight routes, and I need you to extract the airport codes from each sentence. Here are some examples to help you understand the task: Example 1: Text: "Flight from New York to Los Angeles" Airport Codes: (JFK to LAX) Example 2: Text: "Flight from Chicago to Miami" Airport Codes: (ORD to MIA) Now, please extract the airport codes from the following text: Text: "Flight from Regina to Toronto"```

# Example Script

The demonstration uses the following script which ChatGPT-3.5 generated.

```
CHARACTERS:

Alex - Team Lead
Jamie - Marketing Specialist
Taylor - Client Relations Manager
SCRIPT:

(Alex enters the meeting room where Jamie and Taylor are already seated)

ALEX:
Good morning, Jamie, Taylor. Let's get started. We need to decide what to order for lunch with the client. Any ideas?

JAMIE:
Morning, Alex. I was thinking we could go with something light and universally liked. Maybe a selection of sandwiches and salads?

TAYLOR:
That sounds like a safe choice, Jamie. But we know from our last meeting that our client is a foodie. They might appreciate something a bit more unique.

ALEX:
That's a good point, Taylor. We want to make a good impression. What do you suggest?

TAYLOR:
How about a local gourmet bistro? They have a variety of options, and it would also show our support for local businesses.

JAMIE:
I like that idea, Taylor. They also cater to different dietary preferences, right?

TAYLOR:
Yes, they do. They have vegan, gluten-free, and dairy-free options.

ALEX:
That sounds perfect. Let's go with that. Jamie, can you place the order?

JAMIE:
Sure, Alex. I'll take care of it.

ALEX:
Great. Let's make sure we have a variety of options. And don't forget to order some dessert as well.

JAMIE:
Will do, Alex. I'll get on it right away.

(Suddenly, the lights flicker and the room plunges into darkness)

ALEX:
What just happened?

TAYLOR:
It seems like a power outage. Don't worry, I'll check with the building management.

(Taylor leaves the room to check on the situation. Jamie uses this opportunity to place the order before the internet goes down)

ALEX:
Great thinking, Jamie. Let's hope the power comes back soon.

(Meeting ends in suspense)
```
