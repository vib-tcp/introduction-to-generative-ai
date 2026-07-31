# EXAMPLES OF PROMPTS TO SUPPORT DURING ACTIVITIES 


<details>
<summary><b> 1. GENERAL INFORMATION </summary></b>

The building blocks for a good prompt are:

1. Clear actions (verbs)

2. Clear and complete context (avoid ambiguity)

3. Define a Audiance and AI-Persona

4. Iterations, do not stop in the first answer

When you think of your verb, try to be very clear, Replace “explain” with other action verbs that could be more adequate for your goals. See examples below.

> Classify, 
> Write,
> Summarize,
> Draw, 
> Brainstorm,
> Compare,
> Develop,
> Expand,
> Simplify,
> Draft,
> Classify,
> Map,
> etc …

Complementary you should specify more information about what you expect from this verb. Exemplify what? Draw in which style? Compare in what perspective? Simply to what level? etc ...
This way you can get the best out of the chat bot.

-----

***Prompt 1***

Summarize what is the European Patent Convention (EPC) and the relevant stages of patent procedure meeting the requirements of the EPC. And exemplify in 3 steps how to start the procedure for a patent request. 

[Copy text or attach file]

> In this simple prompt you have a clear verb "Summarize" and you specify the topic, and which aspects you need. You also specify examples of what subtopic you would like.

-----

***Iteration 1***

Elaborate on the challenges of the procedures of EPC.

</details>

<details>
<summary><b>2. AUDIENCE & PERSONA </summary> </b>

Defining the Persona of the chat bot and to what audiance the result should be generated will direct the chatbot to use specific vocabulary and to access more specific parts of the model. It should incomporate a level of knowledge of the Persona that you choose and adapt the outcome to the level of your audiance. Taking it to extreams will allow you to observe the difference.

The format will be approximatelly

You are **[Persona]** and you will explain **[TOPIC]** to a **[DEFINE AUDIENCE]**. Add more context if you want ....

-----

***Prompt 1***

You are an **Business developer of a bioscience company**. Categorize the list of companies in this [LIST.xlsx] based on participation on our conferences. Explain each category for an **expert colleague**.

-----

***Iteration 1***

Make a summary about the main impacts of companies X, Y, Z.
</details>

<details>
<summary><b>3. FLIPPED INTERACTION or INTERVIEW EXAMPLE</summary></b>

In this case you will instruct AI chat bot to interview you in order to chieve your goal. Additionally to defininf your goals you need to define how the interview will happen and how long it should be. You will be able to stop or extend the interview as you want, however if you don't define the duration it is likely that AI will keep going until you actively tell it to stop.

When structuring an interview you must define:

1. how the qeustions will be asked (all at once, one at a time, etc)

2. for how long (5 cycles, 10 cycles, etc)

3. how you will answer (wait for your ansewr, ignore unswered questions, etc)

There are many details that can influence on the success rate of this interaction. A general example that you can adpat is shared bellow. And even better a compleate example to inspire you and that you can also adpat is shared next.

#### General structure example

We would like to write about **[TOPIC]**. For this we would like to brainstorm with you.

To do this we would like you to ask us questions to clarify the WHY this **[PROJECT/CHANGES/PLAN]** should be done and WHO it should be done for. We would like you to ask **[X QUESTOINS]** at a time, brainstorm for us **[X REASONS]** or **[X  SOLUTIONS]** and **[X TYPES OF APPROACHES]**. wait for our answer which you include in the description of the **[PROJECT/PLAN/REQUEST]** that you provide us with. Then we redo the whole circle again. Here is the information about the **[PROJECT/PLAN/REQUEST]**: **[INFO]**

-----

***Prompt 1:***

I want to brainstorm about **[definitins of the terms listed below]**. You should ask me questions that will guide the **[perspective of this definitions]** to find the precise and unambugous definition. Ask **[2 QUESTIONS at a time]** for each term on the list. After I answer you can ask new questions and suggest a draft definition. Move to the next term when I say ***"This is good. Move on to the next."***. Every time we have a good definition print the list Term:Definition interativelly. 

- LIST - 

Term 1
Term 2
Term 3
etc ...

> This prompt will start an interview. And you can go as far you want or stop a round of questoins to start a new one. 
</details>

<details>
<summary><b>4. STEER THE STYLE</summary></b>

In this case you will provide additionally to the building blocks we have seen, blocks if information about the style of writing and structure of the text.
AI works welll with strucutres, you can define your blocs by usings symbols such as '#' or '-' or ' <Block 1>' or simply stating the section. If you want each session to have a different structure or vocabulary you have to explain. Your prompr starts to become more complex and more complete. Iterations become more and more important. See the example below.

### General structure

You are **[DEFINE ROLE]**. Write a paragraph of max **[PROMPT LIMIT SIZE]** TO **[GOAL/OUTPUT]**. Assume you are writing for **[AUDIENCE]**.
- style of text -

**[AVOID/USE]** fancy jargon. Write **[FORMALLY/NORMALLY/]**. 

You are **[FORBIDDEN]** to use complex English words, refrain of using terms from the - ban list - . Write one **[ONE PARAGRAPH/TITLE/HEADER FOR LINKEDING ARTICLE/ETC]**

-  ban list -

Hurdles, Bustling, Harnessing, Unveiling the power, Realm, Depicted, Demistify, Insurmountable, New Era, Poised, Unravel, Entanglement, Unprecedented, Eerie connection, unliving, Beacon, Unleash, Delve, Enrich, Multifaced, Elevate, Discover, Supercharge, Unlock, Unleash, Tailored, Elegant, Delve, Dive, Ever-evolving, pride, Realm, Meticulously, Grappling, Weighing, Picture, Architect, Adventure, Journey, Embark, Navigate, Navigation, dazzle, tapestry.

------

***Prompt 1:*** 

Using the [file.pdf] with bullet points write a text for an email to be sent to [**Director of the center [to define]**].  Respect the style defined.

- style -

Avoid fancy jargon. Write normally and polite. You are forbidden to use complex English words. refrain of using terms from the - ban list -. The email needs to be clear and contain the key points of the list to introduce the business proposal.

- ban list -

Hurdles, Bustling, Harnessing, Unveiling the power, Realm, Depicted, Demistify, Insurmountable, New Era, Poised, Unravel, Entanglement, Unprecedented, Eerie connection, unliving, Beacon, Unleash, Delve, Enrich, Multifaced, Elevate, Discover, Supercharge, Unlock, Unleash, Tailored, Elegant, Delve, Dive, Ever-evolving, pride, Realm, Meticulously, Grappling, Weighing, Picture, Architect, Adventure, Journey, Embark, Navigate, Navigation, dazzle, tapestry.

------

***Iteration 1:*** 

Adapt the paragrap by **using fancy jargon**. Write for as you are introducing the topic to a friend without expertise.  Use terms from - My list -. Be polite, creative and fun.

- My list -
Hurdles, Bustling, Harnessing, Unveiling the power, Realm, Depicted, Demistify, Insurmountable, New Era, Poised, Unravel, Entanglement, Unprecedented, Eerie connection, unliving, Beacon, Unleash, Delve, Enrich, Multifaced, Elevate, Discover, Supercharge, Unlock, Unleash, Tailored, Elegant, Delve, Dive, Ever-evolving, pride, Realm, Meticulously, Grappling, Weighing, Picture, Architect, Adventure, Journey, Embark, Navigate, Navigation, dazzle, tapestry.

</details>

<details>
<summary><b>5. EXCEL EXPERT </summary></b>

As an Excel Formula Expert excel can support you with complex formulas and macros.
In this case you need to think that the context that your prompt needs is the information about your table (columns names, number of lines, types of cells, etc). 

-----

***Prompt 1:***

You are an EXCEL expert, and your task is to provide advanced Excel formulas and macros to perform complex calculations or data manipulations. 

Ask the user to describe the desired outcome or operation to perform in Excel. Ask about the data columns, number of lines, types of cells. Make sure to gather all the necessary information you need to write a complete formula, such as the relevant cell ranges, specific conditions, multiple criteria, or desired output format. Make one question at a time.

Once you have a clear understanding of the user's requirements,

1. Provide a detailed explanation of the Excel formula that would achieve the desired result. 

2. Break down the formula into its components, explaining the purpose and function of each part and how they work together. 

3.Provide any necessary context or tips for using the formula effectively within an Excel worksheet.

Consider that the user is doing it for the first time and explain step-by-step the implementation

> By applying  the exact prompt that is described above that starts a flipped interaction:

<details>
<summary> Person </summary>
I want to creat a dinamic dropdown for that allow to select more then one option
</details>

<details>
<summary> ChatBot </summary>
Creating a dynamic dropdown that allows selecting multiple options in Excel is a bit tricky because Excel's native Data Validation dropdown only supports single selection. But there are workarounds using VBA (macros) to enable multi-select functionality.
Let’s start by understanding your setup so I can tailor the solution:

First question:

Which column or range of cells should contain the dropdown list?

For example:

Is it column A, B, or a specific range like B2:B100?
Will the dropdown be used in a single sheet or multiple sheets?

Once I know where the dropdown should go, I’ll ask about the source list and then guide you step-by-step through the macro setup.
</details>

And so far and so on, as you have experienced before. Until you are satisfied with the result.
</details>

<details>
<summary><b>6. PROMPT A PROMPT</summary></b>

In this case AI chat bot is the expert in creating prompts. The challange here is not to engage too much with the chat bot that you forget in which step  you are.
You will start prompt engineering a flipped interaction with the "Prompt Expert", the persona your AI bot will incorporate. The interview will have the purpose to feed the cha with more context so you steer in the direction you want. The result of the first interaction is a engineered prompt to answer your real questions.

Imagine like this. You want to draft a poem in the format of a ***Sonet, Cordel Literature, Haiku***, a style of your choice. You will use the Flipped interaction strategy to have the chat bot interview you about what message you want to convey and what size of prompt you have. With this information the chat bot will engineer "the best" prompt to have AI writing THE BEST poem ever.

This type of approach has many sections defined.

See the example ...

------
### General strucuture

You are an prompt engineer expert. 
The goal is to assist me in creating the most effective prompt. 
The generated prompt should be phrased as if I were directly requesting a response, in first person. 

Your response will be in the following format:

Questions to improve prompt:
{How questions should be asked}.

Prompt:
{explanation of what is expected of suggest prompt for step 2}

Instructions:
After the Questions and prompts sections have been generated, I will respond the questions. Integrate my answers directly into the formulation of the prompt. Please keep all elements of the previous version unless asked to replace or delete. We will continue this iterative process as I provide you with additional information and you update the prompt until the prompt is perfected. {Style of writing}.

At the end of each answer, give precise instructions for the next steps.

Before we start the process, greet me first and ask me what the prompt should be about. Don't show the sections in that first answer.

> Asking the chat bot to great before start is a strategy to check if the prompt is working as expected. If the chat bot imeadtly suggest a engineered prompt without any information you must start from a empty tab and try again since it is creating random information without context.

------

***Prompt 1:*** 

You are an **prompt engineer expert**. 
**The goal is** to assist me in creating the most effective prompt. 
The generated prompt should be **phrased** as if I were directly requesting a response, **in first person**. 

Your response will be in the following format:

Questions to improve prompt:
{Formulate 2 questions that seek additional information from me to further refine the prompt. Do not repeat the questions in the next interaction.}

Prompt:
{Provide the best possible prompt according to my request using your knowledge of prompt creation techniques. Do not assume any details, we will add to the prompt as we go along. Formulate the prompt as a request. An example would be "You will act as an expert in physics to explain the nature of the universe to me...".}

Instructions:
After the Prompt, and Questions sections have been generated, I will respond the questions. Integrate my answers directly into the formulation of the prompt. Please keep all elements of the previous version unless asked to replace or delete. We will continue this iterative process as I provide you with additional information and you update the prompt until the prompt is perfected.
Be imaginative and thoughtful when creating the prompt. At the end of each answer, give precise instructions for the next steps.

Before we start the process, greet me first and ask me what the prompt should be about. Don't show the sections in that first answer.

------

***Iterations part 1:*** 

<details> 
<summary> ChatBot </summary>
Hi ! I'm excited to help you craft a powerful and precise prompt. To get started, could you tell me what you'd like the prompt to be about? What's the topic or goal you're aiming for?
</details>

<details>
<summary> Person </summary>
I want to write a Sonet about being a imigrant that feel they have 2 homes and is always missing one of them
</details>

<details>
<summary> ChatBot </summary>
Thank you,  — that’s a beautiful and deeply resonant theme. Let's begin shaping your prompt to help you write a sonnet about being an immigrant who feels they have two homes and is always missing one.

Questions to improve prompt:

Would you like the sonnet to follow a specific structure (e.g., Shakespearean or Petrarchan), or should it be free-form within the sonnet tradition?
Should the tone lean more toward nostalgic, hopeful, melancholic, or a blend of emotions?

Prompt:
You will act as a skilled poet with expertise in crafting sonnets. I want you to help me write a sonnet about being an immigrant who feels they have two homes and is always missing one of them. The poem should explore the emotional complexity of belonging to two places and the longing that comes with it.
 
Next steps:
Please answer the two questions above so I can refine the prompt further. Once I have your answers, I’ll integrate them into the prompt and continue improving it with you.
</details>

<details>
<summary> Person </summary>
1. Shakespearean 

2. The tone should be happy and nostalgic

Should also talk about family, friends and food
</details>

<details>
<summary> ChatBot </summary>
Thanks. Based on your answers, here’s the updated version of your prompt:

Questions to improve prompt:

Would you like the sonnet to include references to specific countries, cities, or cultural elements from your personal experience?
Should the language be modern and accessible, or more traditional and poetic in line with Shakespearean style?

Prompt:
You will act as a skilled poet with expertise in crafting sonnets, especially in the Shakespearean style. I want you to help me write a sonnet about being an immigrant who feels they have two homes and is always missing one of them. The tone should be happy and nostalgic, and the poem should include themes of family, friends, and food. The sonnet should follow the Shakespearean structure with 14 lines, written in iambic pentameter, and a rhyme scheme of ABAB CDCD EFEF GG.

Next steps:
Please answer the two new questions above. Once I have your answers, I’ll refine the prompt further. Let’s keep building it together!
</details>

<details>
<summary> Person </summary>
1. Should be more general so several people can relate.

2. Modern and accessible language.

Should also be short.
</details>

<details>
<summary> ChatBot </summary>
Thanks, Bruna! Based on your answers, here’s the updated version of your prompt:

Questions to improve prompt:

Would you like the sonnet to include references to specific countries, cities, or cultural elements from your personal experience?
Should the language be modern and accessible, or more traditional and poetic in line with Shakespearean style?
 
Prompt:
You will act as a skilled poet with expertise in crafting sonnets, especially in the Shakespearean style. I want you to help me write a sonnet about being an immigrant who feels they have two homes and is always missing one of them. The tone should be happy and nostalgic, and the poem should include themes of family, friends, and food. The sonnet should follow the Shakespearean structure with 14 lines, written in iambic pentameter, and a rhyme scheme of ABAB CDCD EFEF GG.
 
Next steps:
Please answer the two new questions above. Once I have your answers, I’ll refine the prompt further. Let’s keep building it together!
Provide your feedback on BizChatYou said: 1. Should be more general so several people can relate.2. Modern and accessible language. Should also be short.Copilot said: CopilotPerfect, Bruna! Here's the refined version of your prompt incorporating everything you've shared:

Questions to improve prompt:

Should the sonnet include a volta (a thematic shift or turn) in a specific place, like after the second quatrain, or should it flow more fluidly?
Would you like the sonnet to end with a strong concluding couplet that offers resolution, contrast, or a poignant reflection?

Prompt:
You will act as a skilled poet with expertise in crafting sonnets, especially in the Shakespearean style. I want you to help me write a short sonnet about being an immigrant who feels they have two homes and is always missing one of them. The tone should be happy and nostalgic, and the poem should include themes of family, friends, and food. The sonnet should follow the Shakespearean structure with 14 lines, written in iambic pentameter, and a rhyme scheme of ABAB CDCD EFEF GG. The language should be modern and accessible so that several people can relate to it.

Next steps:
Please answer the two new questions above so I can finalize the prompt even further. We're getting close to a beautifully tailored request!

</details>

------

***Iterations part 2:*** 

> Copy the last suggested prompt from the chatbot and use in a new tab, a new chat.

<details>
<summary> Person </summary>
You will act as a skilled poet with expertise in crafting sonnets, especially in the Shakespearean style. I want you to help me write a short sonnet about being an immigrant who feels they have two homes and is always missing one of them. The tone should be happy and nostalgic, and the poem should include themes of family, friends, and food. The sonnet should follow the Shakespearean structure with 14 lines, written in iambic pentameter, and a rhyme scheme of ABAB CDCD EFEF GG. The language should be modern and accessible so that several people can relate to it.
</details>

<details> 
<summary> ChatBot </summary>
Here’s a Shakespearean-style sonnet based on your request:

Two Homes, One Heart

by Bruna & Copilot

I walk two roads that meet in memory’s light,

One paved with voices warm as summer air;

The other hums beneath the moonlit night,

With scents of bread and laughter everywhere.

At one long table, friends and kin still cheer,

Their stories seasoned like the meals we share;

Yet oceans stretch, and though they’re far, they’re near,

For love outlives the miles we cannot bear.

The other home now cradles all my days,

Its streets have learned the rhythm of my feet;

New bonds have bloomed in unexpected ways,

And every smile makes foreign soil feel sweet.

Though torn between, I count this gift as true:

Two homes to love, and both still loving you.

✅ Structure check:

14 lines ✔

Iambic pentameter ✔

Rhyme scheme ABAB CDCD EFEF GG ✔

Tone: happy, nostalgic ✔

Themes: family, friends, food ✔

Modern and relatable language ✔

Would you like me to:

Polish it further for stronger imagery and rhythm?

Add a title and short commentary explaining the symbolism?

Create a second variation with a slightly different emotional focus (e.g., more on food, or more on the bittersweet feeling)?
</details>

With this you complete the 2 steps of having the AI chatBot crfeating a prompt for you and then applying this prompt to get what you want.
Check with a topic of your liking

</details>

<span style="color:white">.</span>

<span style="color:white">.</span>

# EXAMPLE ARE ADAPTED FROM:

Prompts to make you Prompt like a Pro
(Taken from Zain Khan, Mark Fulton, Ruben Hassid and others.)
https://docs.google.com/document/d/1lpKvjP_Ez4O8HdxH20AJzkLTVFgwxk_U/edit 


STAFF GUIDE, DEVELOPING EFFECTOVE PROMPTS FRO CHATGPT AND OTHER AI TOOLS.
UNIVERSITY OF CAPETOWN https://docs.google.com/document/d/1EHMRP4kxADwLsOkHwAbUWQaGD8EGfQ3D/edit#heading=h.7qk69xxbdmim 

Antropic Prompt Library
https://docs.anthropic.com/en/prompt-library/library

Msty prompt library
https://msty.app/prompts-library


Explain what you want from the verb
https://www.linkedin.com/feed/update/urn:li:activity:7229585834339885056/


