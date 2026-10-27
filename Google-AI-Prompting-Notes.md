# Google AI Prompting — Course Notes and Practice

> Personal study notes, examples, exercises, and course excerpts compiled during Google AI Prompting coursework.
> Content is retained from the original notes, including rough drafts, repeated passages, and third-party course excerpts. Review and obtain appropriate permission before publishing copyrighted course materials publicly.

## Contents

- [Notes and exercises](#notes-and-exercises)
- [Original source file](#original-source-file)

## Notes and exercises

<https://www.coursera.org/learn/google-start-writing-prompts-like-a-pro/lecture/z45ei/discover-how-ai-can-help-at-work>  
What are some examples of generative AI tools?  
Generative AI tools exist for various modalities, such as text, imagery, music, code, and voices. Some popular AI content generators to explore include the following:  
Text generation tools include GPT, Jasper, AI-Writer, and Lex.  
Image generation tools include Dall-E 2, Midjourney, and Stable Diffusion.  
Music generation tools include Amper, Dadabots, and MuseNet.  
Code generation tools include codeStarter, Codex, GitHub Copilot, and Tabnine.  
Voice synthesis tools include Descript, Listnr, and Podcast.ai.  
AI chip design tool companies include Synopsys, Cadence, Google, and NVIDIA.  

## AI Model Settings

Text base modality  


## Create images with gen AI


ChatGPT, Midjourney, Craiyon, or an image generation bot in Poe, DALL-E  


## 3- Design Prompts for Everyday Work Tasks


### 3-1 Write email


### 3-2 Prompt with personality: Match gen AI to your writing style


### 3-3 Brainstorm ideas that buzz


### 3-4 Build tables and trackers effortlessly


### 3-5 Timelab table


### 3-6 Capture meeting notes instantly


### 3-7 Summarize lengthy documents  https://aistudio.google.com/prompts/new )



## 4- Strategies for data analysis


### 4-1 Decipher spreadsheets:


### 4-2 Translate to another language

    4-3 Get Help with coding (Google Colaboratory (Colab), Gemini Code               Assist, and Vertex AI Codey are designed with coding in mind)  

### 4-4 Explain complex data


### 4-5 Bring data to life with visualizations


### 4-6 presentation speaker notes


### 4-7 Receive instant feedback on a presentation

       5- Fine-tune gen AI outputs by adjusting tool settings  

## 4 - Use AI as a Creative or Expert Partner


### 4-1 prompt chaining - for long text, book , research ,..


### 4-2 Meta-prompting / pre-ready prompt (advance)



---



## Using GenAi



## What is prompting?


Text base modality  
 ​Modalities are the different formats in which gen AI tools ​receive or produce information, whether that's text, images, ​video, audio, or code. ​Different gen AI tools are better at working in ​certain modalities. ​Be sure to check the gen AI tool you're using ​to find out which modalities it's capable ​of using or producing. ​Let's start with image generation.  

We can use template prompt  as a library to avoid of writing from scratch.  


## Use the 5-step prompt framework


 ​A good prompt follows a simple framework, task, context, ​references, evaluate, and iterate.  

 ​If you ever forget a step, ​just remember thoughtfully, create, really, ​excellent, inputs:  

1- Task:  
First is task. ​You need to describe the task you want the generative AI ​tool to help you with. ​Now, this should include a persona ​and a format preference, so that the task is specific. ​Persona refers to ​what expertise you want the gen AI tool to draw from.  
You can ask the tool to take on a persona like a ​professional speech writer ​or a marketing executive with 15 years of experience. ​Or you can ask it to create output for a specific audience, ​a customer, or even your manager. ​You can be as detailed as you'd like when adding a persona ​to your task. Format refers to how you want the output ​to appear, whether that's a bulleted list, ​short sentences, or a table. ​So there you have it task. ​Next, you'll include context ​or the necessary details to help the gen AI tool understand ​what you need from it. ​This is the difference between writing.  

2- Format:  
 Format refers to how you want the output ​to appear, whether that's a bulleted list, ​short sentences, or a table.  

3- context:  
Next, you'll include context ​or the necessary details to help the gen AI tool understand ​what you need from it. ​This is the difference between writing.  ex:  

4- references:  
 ​Sometimes you'll add references for the gen AI tool ​to use while creating its output.  the gen AI tool can give you a more useful output.  

5- Evaluate:  
Once you have your output, it's time to evaluate. ​Ask yourself if the input you ​provided gave you the output you needed , This leads us to the final part of the framework. Iterate.  
6- Iterate:  
If you evaluate your output ​and determine that you're not getting what you need, ​you can try again by adding more information ​or tweaking your prompt. ​And this is a key part of prompting effectively  


## Put the prompt framework into action


we'll log into Gemini ​and then use the tool to help us brainstorm ideas ​for a new high-performance sneaker line :  
It’s not prompt.  So we add some details:  

Few / single / zero - Shot :  

Now, we need to give ai references:  

Like these references:  

During writing this prompt we evaluated and iterated the good result  
Remember these for starting to write a prompt:  

 Practice:  
To begin, please choose ONE of the following prompts to work with:  
1. Create an agenda for a team meeting to discuss quarterly goals.  
2. Generate creative ideas for a virtual team-building activity.  
3. Help me surprise a friend with a fun dinner menu idea.  

To make this prompt more effective, we need to flesh out these elements:  
task: Does your prompt specify exactly what you want from the AI tool? To make it stronger, consider adding a persona (the expertise you want the AI tool to assume) and a format preference (how you want the output to appear).  
context: What background information would help the AI tool tailor the agenda? Think about your team's goals, the reason for the meeting, or any specific challenges you're facing.  
references: Are there any examples of agendas you've used before, or specific structures you'd like the AI tool to emulate?  

My answer:  
create a agenda for a team  to duscuss quarterly goals  
this team is working on building robatics kit and sell them to schools and students and some company  
write this meeting in bullets with  showing the main objective of each bullet at the first of each bullet as a subject  
use this refrence ti write but keep your data:  
number of selling: we have 300 sells to  schoold and specially high scholls for boys  

Google answer:  
That's a great start! You've added some important context about your team's work and your sales data.  
To make this prompt even stronger, let's refine it by applying the framework more fully:  
task: You've specified the format (bullets with subjects), but adding a persona could really help. For example, do you want the AI tool to act as an experienced project manager or a strategic business consultant?  
context: You've provided great background on your product and sales. To make it even better, what is the goal of this specific meeting? Are you trying to brainstorm new features, increase sales, or solve a specific problem?  
references: You mentioned using your sales data as a reference, which is perfect.  
Taking those points into account, how would you combine these elements into a concise, final version of your prompt?  
My answer:  
create a agenda as a strategic business consultant for a team to discuss quarterly goals this team is working on building robatics kit and sell them to schools and students and some company , our goal is to predict well seosonal stocking and increase sale . write this meeting in bullets with showing the main objective of each bullet at the first of each bullet as a subject use this refrence ti write but keep your data: number of selling: we have 300 sells to schoold and specially high scholls for boys  

Google answer:  
That is a much stronger prompt! You have clearly defined the task, persona, format, context, and included your specific sales data as a reference.  
Now, let's move on to STEP 3: Generating and evaluating an output. I will act as the AI tool and generate an agenda based on your refined prompt.  
Meeting Agenda: Quarterly Goals Strategy  
Review of Current Sales Performance: Analyze the recent milestone of 300 units sold, specifically focusing on the high demand from boys' high schools to understand the drivers behind this success.  
Seasonal Demand Forecasting: Discuss historical trends and upcoming academic calendars to predict seasonal stocking requirements, ensuring inventory levels align with peak purchasing periods for schools.  
Market Expansion Strategy: Brainstorm actionable tactics to diversify our customer base beyond high schools, targeting additional educational institutions and corporate partners to increase overall sales volume.  
Product Development Alignment: Evaluate if current robotics kit features meet the evolving needs of our primary school and student customers, and identify potential enhancements to maintain a competitive edge.  
Action Plan and Accountability: Assign clear ownership for the identified strategies, setting specific deadlines and KPIs to ensure we meet our quarterly growth objectives.  

Now that you've seen the output, let's evaluate it. Based on the 5-step framework, how would you rate this agenda, and what specific elements make it effective or potentially lacking?  

My answer:  
its 70% good, why you dont use of umber to show better perfomance of each step?  

Google answer:  
That's a fair critique! You're right that incorporating specific metrics or numerical targets into the agenda items would make the goals more concrete and measurable.  
Since you've evaluated the output and identified a clear area for improvement, let's move to STEP 4: Iterating on your prompt.  
How would you adjust your original prompt to ensure the AI tool includes specific numerical targets or performance metrics for each agenda item?  
My answer:  
create a agenda as a strategic business consultant for a team to discuss quarterly goals this team is working on building robatics kit and sell them to schools and students and some company , our goal is to predict well seosonal stocking and increase sale . write this meeting in bullets with showing the main objective of each bullet at the first of each bullet as a subject use this refrence ti write but keep your data: number of selling: we have 300 sells to schoold and specially high scholls for boys add measure or percentage to each bullet  

Google answer:  

That is a great iteration. By adding the requirement for measures or percentages, you're pushing the AI tool to provide more actionable and data-driven results.  
Here is the updated agenda based on your refined prompt:  

Meeting Agenda: Quarterly Goals Strategy  
Review of Current Sales Performance: Analyze the 300 units sold to date, with a goal to identify the specific factors that led to a 15% higher engagement rate in boys' high schools compared to other segments.  
Seasonal Demand Forecasting: Develop a predictive model for seasonal stocking, aiming to reduce stockouts by 20% during peak academic purchasing months by aligning inventory with historical order patterns.  
Market Expansion Strategy: Define a plan to acquire 50 new corporate or non-high school educational clients, targeting a 10% increase in total sales volume for the upcoming quarter.  
Product Development Alignment: Review current kit features to ensure they meet the requirements of 90% of our target student demographic, identifying at least two enhancements to improve user satisfaction scores.  
Action Plan and Accountability: Assign ownership for these initiatives, with a commitment to review progress against these specific KPIs (15% engagement, 20% stockout reduction, 10% sales increase) on a bi-weekly basis.  

Now that we have completed the iteration, let's move to STEP 5: Reflection.  
Looking back at your original prompt and comparing it to this final version, how did applying the framework—specifically adding the persona, context, references, and finally the requirement for measurable metrics—change the quality of the output you received?  
During today's session, we focused on mastering the 5-step prompting framework (task, context, references, evaluate, iterate) to create effective prompts for AI tools. We worked through the process of refining a prompt for a team meeting agenda, moving from a basic request to a highly specific, data-driven prompt that incorporated a persona, clear context, and measurable KPIs.  
Your strengths:  
Analytical approach: You quickly identified that the initial output lacked the necessary depth and were able to pinpoint exactly what was missing (numerical targets).  
Effective iteration: You successfully applied the "iterate" step of the framework to refine your prompt, which resulted in a significantly more actionable and professional output.  
Areas for improvement:  
Initial specification: While you improved quickly, try to include all elements of the framework—like specific formatting requirements or performance metrics—in your very first draft to save time.  
Refining context: Continue practicing how to provide even more granular background information, as this helps the AI tool provide even more tailored and relevant results.  
You've completed 5 of 5 topics, and we have successfully reached the end of our session. You did a great job applying the framework to improve your results! Keep up the good work!  
<https://www.coursera.org/learn/google-start-writing-prompts-like-a-pro/lecture/Vp5IG/ai-irl-improve-your-prompts-by-adding-context-and-persona>  


## AI IRL: Improve your prompts by adding context and persona

 ​I like to include things like the persona saying, you know, ​I'm looking for a marketing plan. ​Start by saying, imagine you're a world ​class marketer, right? ​And you're marketing for this budget and this timeline, ​and really providing a starting point. ​So maybe this is what you've done ​before, this is the company's values.  
you don't have ​to start from scratch at the prompt page. ​So maybe you have a project plan that you really like, ​but you're wanting to better it. ​- Yep. - You can upload that project plan ​and say, here's what I've been using for two years. ​Yeah. What are some ways that I could do more? Yep.  


## Complete activities with Google AI Pro at no cost


But before you can build like an AI professional, you’ll need professional-grade tools.  
Get 3 months of Google AI Pro at no cost  
To help you get the most out of the program, we’re providing a complimentary three month trial subscription to Google AI Pro. While optional and not required to complete your activities, or earn your certificate, it gives you higher access to a suite of our most capable AI models and features.  
How to access the extended trial:  
Proceed to the next item  
Select “I agree to use this app responsibly”  
Click on the “Launch App” button  
A new browser window will open and a unique link will populate  
Click on your unique link (do not share this link with others, it is assigned to you only)  
Click on start trial  
Make sure you are signed into Gemini with your Google account to complete your activities with Google AI Pro  
Practice App Item  
Redeem Your Google AI Pro Trial  
Google AI Pro will support and accelerate your learning journey by providing access to Google’s most advanced models. This 3-month trial* offers expanded capabilities within the Gemini app and 5 TB of cloud storage to help you apply your new skills in real-world scenarios. While optional and not required to complete the hands-on components of your learning experience, or earn your certificate, it gives you higher access to a suite of our most capable AI models and features.  
Click Launch App to redeem your trial of Google AI Pro.  
*Terms apply. See full terms at https://one.google.com/offer/terms-and-conditions/google-career-certificates  
This course uses a third-party app, Redeem Your Google AI Pro Trial, to enhance your learning experience. The app will reference basic information like your Coursera ID.  
Coursera Honor Code  

Activity: Plan a vacation with gen AI  
As a quick reminder when crafting your prompts:  
Thoughtfully: Describe your task, specifying a persona and format preference.  
Create: Include any context the gen AI tool might need to give you what you want.  
Really: Add references the gen AI tool can use to inform its output.  
Excellent: Next, evaluate the output to identify opportunities for improvement.  
Inputs: Then, iterate on your initial prompt to attain those improvements.  
Scenario: Plan your perfect vacation  
Think of your ideal getaway, the one you daydream about. It might be a beachside escape, or an adventure in a city you’ve never been to before. Gen AI tools are great at helping you plan when to travel, how to get there, what to pack, and even how to budget.  
First, you’ll write an initial prompt asking the gen AI tool to identify the necessary planning steps for your vacation. Then, you’ll iterate on your prompt to get more details.  
Let’s get started.  
1- Open a new tab to search for your gen AI tool of choice, and begin prompting. Write an initial prompt to identify the planning steps for your entire trip, from start to finish.  Make sure to provide the specific task in your prompt. For example: “I’m planning a vacation to [place/description]. What planning steps should I consider?”  

2- Then provide any necessary context that would help the tool understand what you need from it. Is there a certain time of year you want to travel? Or maybe you have dietary or budget restrictions that would affect the planning process. For example: “I want to travel in [time of year]. I need the plan to include considerations of [type of food].”  
3- Consider also adding references that might help the gen AI tool create the plan. You could upload an itinerary you found online that looks particularly interesting, or a list of sightseeing spots you don’t want to miss. For example: “I want the trip to include activities like the list attached.”  
As a tourist specialist, write a plan for tripping to Banf in Alberta, for 3 days, give me the touristy place with cost of visiting and limitation for having 7 years old children, also a accommodation  for stay there at night with facilities and price for 2 adult and 1 kids and also give me the link of website for each of them if there is. Also give me information about restaurant next to each place , i wanna go in fall.  
Give me the result as a organize  table  
4- When you’re ready, enter your prompt in the gen AI tool.  
5- If you’re not sure where you’d like to go for your vacation, you can even prompt the gen AI tool to generate ideas before you plan!  
6- Evaluate the output:  
 Review the output from your initial prompt and evaluate what information you may still need for planning your vacation. Some parts of your input may be leading the gen AI tool down the wrong path, and by evaluating the output you can find where the issues are. For example, is the plan easy to follow? Is the plan organized into steps with clear actions for you to take? Does the plan include steps such as:  
Deciding on travel dates?  
Booking accommodation?  
Choosing how to get to your destination?  
Considering traveler preferences, including dietary and budgetary constraints?  
Making time for activities while on the trip?  
7- Also, consider which parts of the prompting framework may have been missing from your initial prompt (task, context, references, evaluate, iterate).  
8- Revise and refine your prompt to improve or get more information about the vacation planning steps. This is your big trip, so you want to make sure you’re getting exactly what you want. For example, you could:  
Revise the task in your prompt to be more specific.  
Add three to four sentences of additional context to help the gen AI tool create a more detailed plan.  
Add references to your prompt to help the AI better understand your needs.  
Prompt the tool to expand on one of the steps in the plan.  
Ask the tool, “Do you have questions for me?” for further discussion.  
Ask the tool to suggest a format, like a spreadsheet, to help you stay organized as you move through the steps.  
9- When you’re ready, enter your revised prompt. Then, continue iterating until you feel confident that the output sufficiently helps you plan.  
Pro Tip: Iterate on each step  
Now that you have a clear list of vacation planning steps, you can use the prompting framework to complete each step. For example, if your first step is to set a vacation budget, you could ask the tool to create a potential breakdown of the vacation costs. Then you could even ask the tool to adjust the plan based on the result.  
<https://www.coursera.org/learn/google-start-writing-prompts-like-a-pro/assignment-submission/xjzh9/activity-plan-a-vacation-with-gen-ai/attempt>  


## Get the most out of AI with the prompt framework

Getting the most out of generative AI is all about understanding inputs and outputs. What are you hoping to get from the tool? That’s the output. What kind of prompt is going to help you get it? That’s the input. And there’s a simple framework that helps you provide clear and specific directions to any gen AI tool: Thoughtfully Create Really Excellent Inputs, or Task, Context, References, Evaluate, and Iterate. This prompting framework will come up throughout this course, so you might want to say it out loud or write it on a sticky note for your desk. Here are the components:  
Specify the task  
Crafting a great prompt starts by describing the task you want the tool to help you with. The task is the foundation of any prompt. It’s what you’re asking the gen AI tool to do for you. Adding a task to your prompt is like writing a sentence asking someone to do something for you. For example:  
Write a list.  
Draft a speech.  
Create an image.  
These are all tasks that gen AI can help with.  
When you’re prompting an AI tool, you need to be clear and specific about the task. If you're vague with your instructions, you're likely to get bad results.  
To further avoid misunderstandings from the tool, include a persona and an output format in your initial prompt:  
Providing a persona. Specifying a persona instructs an AI tool to draw its expertise from a particular field—filtering out irrelevant information. You can ask the tool to take on the perspective of a science expert or an industry analyst, or ask it to create an output geared towards a specific audience, like your manager or team.  
Specifying a format. The format is what you want the output to look like. Want a bulleted list? Or maybe a table so you can compare results side-by-side? Including those details in your prompt.  
Here’s an example of a prompt that includes task, persona, and format:  
Prompt: You’re a movie critic that specializes in Italian film. Create a table that contains the greatest Italian films of the 1970s, and separate them into genres like thrillers, dramas, and comedies. Provide a 100-word summary of each movie as well as details about the production including director and release year.  
Include necessary context  
The more relevant details you include, the better your output will be. Providing background information—like your goals, the reason for the task, or what you’ve tried before—rounds out the model's understanding of what you're looking for. These details are called context, and they’re a vital part of creating great prompts.  
For example, you could write:  
How was DNA discovered?  
Instead, write a prompt that includes detailed context or background information:  
Prompt: You’re a science expert developing a new curriculum at a local college. Tell me in a couple of engaging paragraphs how DNA was discovered and what kind of impact it had on the world. Write it in a way that people unfamiliar with science would understand. You have gotten feedback from students that they found this course dry and unintelligible before, so you want to make sure that the explanation grabs the students' attention and makes a good first impression.  
Pro tip: Context has the potential to be the longest piece of a prompt. One of the most powerful and reliable ways to provide an AI tool with context is to give the model specific reference materials to use.  
Provide references  

References are examples or any additional resources that guide an AI tool towards the output you want.  
Depending on the gen AI tool you’re using, you can include text, images, and even audio references to sharpen your input. But simply pasting in a reference isn't enough. The key is to clearly label and structure your references so the tool knows exactly what they are and how to use them.  
Here are a few best practices for structuring your references:  
Use transitional phrases: A simple method is to clearly signal an upcoming reference.. For example, using transitional phrases like "Refer to these materials," or "Use the following examples" tells the tool exactly where your reference material begins.  
Use headings: Labeling your references with headings is another way to clarify where your examples are within a prompt. This can be helpful if you're including multiple examples, or different types of reference materials. For example:  
Prompt: Write a one-paragraph product description for a high-end watch with features like a scratch-resistant case and a water resistance rating of up to 30 meters. Base the description style on these examples from our website:  
Sunglasses: Our latest collection of handcrafted, heritage-inspired sunglasses features details like UV-protective lenses in shades specifically chosen to complement each frame—all at a price that won't break the bank. Plus, we made these sunglasses with vintage-inspired acetate frames and a keyhole bridge.  
Cardholder: Crafted in smooth Italian leather, this double-sided cardholder is designed to carry your cash and credit cards without the bulk of a full wallet. Fun fact: this cardholder is made in Naples, Italy, and will look great when you treat your friends to a round of summer spritzes.  
Use XML-style tags: For more complex prompts with multiple references, you can wrap your references in XML tags. These act as labels that mark the beginning and end of each distinct piece of information. For example:  
&lt;example01&gt;  
[Your first example text here]  
&lt;/example01&gt;  
Markdown tags: These are symbols you can use in prompts to add formatting. For example, if you were to use a gen AI tool to copy-edit your work, you could surround text with “_” to italicize it or “**” to bold it. This preserves your formatting as you move it into a gen AI tool, which generally uses plain, or unformatted text.  
Whether you share your own work or include external references, these techniques can help the AI tool understand exactly what to do with them. And no need to build an exhaustive set of references—two to five should be enough.  
Evaluate your output  
Different AI models are trained on unique data and rely on different programming techniques. Some models may be better suited to specific uses like writing code or brainstorming ideas, while others might have limited outputs because of their training sets. No matter the model, running the same prompt multiple times will likely render different results because of how gen AI tools process data.  
That’s why it’s so important to evaluate your output. Before you use any AI-generated information, text, or materials, critically evaluate that the output is accurate, unbiased, relevant, and consistent before incorporating it into your workflows. If the output isn’t what you’re looking for, you should iterate on your prompt.  
Take an iterative approach  
There will be times when your prompt simply isn’t leading to the output you need. That’s where our ABI advice comes in: Always Be Iterating. If you find an output lacking, continue clarifying what you need until it’s just right.  
The prompting framework sets you up to give gen AI tools the information they need to generate useful outputs—and it’s designed to apply across all kinds of tools and models. So whatever your gen AI tool of choice, make sure you specify your task, provide context and references, evaluate your outputs, and iterate your inputs.  


## Practice 4 iteration methods

​giving you what you want, but instead ​of scrapping all your work ​and starting again from zero, think about ​how you can Always Be Iterating or ABI to try ​and mold the outputs into something more useful. ​By the end of this video, ​you'll learn four helpful iteration methods. ​The first method is to revisit the prompting framework ​and make sure you're providing enough specificity in your ​task, context, and references. ​For example, if you wrote, give me five Blog Post Ideas. ​A generative AI tool might respond better if you adjusted ​your prompt to include the persona and format.  
​For example, you are an expert on sports nutrition. ​Provide five blog posts, headlines ​that summarize the biggest trends happening in the industry ​for an audience of physical therapists working ​with professional basketball players.  

Long  prompt:  

Shorter prompt with separate them:  

Sometimes shorter sentences can yield more precise results ​because the gen AI tool can parse one small task at a time ​instead of identifying the relationships ​between all of them at once.  

You can also try using different phrasing ​or switching to an analogous task, which is a task ​that is very similar to the one you're trying to complete, ​but different enough to trigger a new response. ​For example, if you're asking a gen AI tool ​to help write a marketing plan for a product ​or service, you could instead ask it to write a story about ​how this product fits into the lives ​of our target customer demographic. ​By moving from write a marketing plan to write a story, ​you're asking the gen AI tool ​to approach the task differently, ​which might lead you closer to a useful output. ​Finally, introducing constraints might also help focus a gen ​AI tools outputs. ​Maybe you wanna make a playlist for an upcoming road trip ​and you're trying to figure out ​what artists you want to include.  

​You've added some context about your favorite genre, ​but the results are kind of boring. ​You've heard all these songs a million times before. ​To get better output ​and something more unexpected, ​you could start adding constraints like specifying ​you only want artists from a certain region ​or artists that have released music in the last five years. ​Adding constraints to your prompt will help the gen AI tool ​narrow down its outputs ​and give you something more helpful or unique. ​The better you can evaluate ​and iterate, the better your output will be.  


## Generate better outputs through iteration

Even with the prompting framework to guide you, sometimes you may still get an output that misses the mark. That’s what iteration is for: to clarify and refine your prompt to better direct a generative AI tool towards the result you had in mind. But some types of iteration have the potential to be especially effective in breaking through creative blocks during prompt design, leading gen AI to new solutions and sharper output.  

To iterate most effectively, prompt your AI tool in the same chat. That way, the tool can reference information you've provided it with in previous prompts and build on that knowledge.  
Here’s how iteration works in action. Consider this example prompt:  
Identify the latest developments in the restaurant industry.  
It’s a simple prompt that only includes the task, and it might generate some broad insights, but chances are that you’ll need to iterate in order to get an output closer to what you want. You can try these four iteration methods to generate more useful outputs:  
Revisit the prompting framework: Make sure your prompt is clear about your desired task and includes a specific persona and format, plenty of context, and offers relevant references that help inform the output. Here’s an example:  

Create a bulleted list including the latest developments in the restaurant industry specific to urban areas that could impact the public reception of a dining experience using only ingredients native to the region.  
Break the prompt into shorter sentences: Instead of packing everything into a complex and lengthy prompt, address each individual step in a separate prompt until you’ve accomplished everything:  

Prompt one: Create a bulleted list including the latest developments in the restaurant industry.  

Prompt two: Summarize the trends that would specifically impact restaurants in urban areas.  

Prompt three: Write a pros and cons list on how those developments could impact the public reception of a dining experience using only ingredients native to the region.  
Tweak your phrasing or switch to an analogous task: Shift your language to explain what you mean in a different way. Or, try a different task that’s similar to what you’re trying to complete but different enough to trigger a new response. Here’s an example:  

I’m starting a restaurant that will only include produce from within 50 miles. You’re a diner that lives in a major city and keeps up with the latest restaurant trends. Write a list of questions that I should consider before opening up the restaurant.  
Introduce constraints: Focus the gen AI tool’s output by adding constraints, or limitations, to your prompt. When you set boundaries for specific categories, lengths, formats, or other details in your prompt, you help the tool provide a more precise output. It’s like asking for a list of food recipes but specifying that the recipe should only use seasonal ingredients and take less than 30 minutes to prepare. Adding constraints can actually encourage more inventive, targeted results that better match your needs. Here’s an example:  

Create a bulleted list including the latest developments in the restaurant industry specific to urban areas that could impact the public reception of a dining experience using only ingredients native to the region. This list should only include trends from cities with a population of more than 500,000 people, and should only include trends relevant to vegetarian and vegan restaurants.  

When providing guidance to a gen AI tool, it’s important to know the right direction to point it in. Whether you’re adhering more closely to the prompting framework, dividing a longer prompt into a few shorter ones, applying constraints, or re-phrasing your prompt as a similar task, iteration is the key to troubleshooting your prompt design and targeting the output you need.  

Question:  
Activity: Brainstorm with gen AI  
Scenarios  
Read through the following options, then complete the activity using the option that best suits you.  
Option 1: Brainstorm for your work or personal life  
Choose something from your work or personal life where you need some inspiration. Maybe it’s an upcoming project where you want to try some new planning strategies. Or maybe you're leading a meeting and want some fun icebreakers to get everyone engaged. Perhaps you're a blogger looking for fresh topics to keep your readers coming back. You can think about personal projects as well, like brainstorming dinner recipes based on the ingredients you have in your fridge right now.  
Option 2: Brainstorm a new clothing collection  
If you can’t think of anything you need to brainstorm, try using the following scenario instead:  
You own Clothing Essentials Company, a small business targeting middle-income consumers aged 18 to 39. You’re brainstorming a new T-shirt to include in your newest clothing line, the Minimalist Collection.  
This requires you to consider a few questions, including:  
What kinds of colors or patterns are trending with your target customers?  
What styles are currently popular?  
What is the price point that your target customers are comfortable with?  
For reference, your best-selling collection is the Lounge Collection, loungewear made of soft materials for relaxing at home.  
You’ve written an initial prompt to help you brainstorm new clothing ideas: “Give me ideas for new T-shirts for my clothing store.” However, the input doesn’t follow the prompt framework and, as a result, the output is vague and requires iteration.  
Step 1 : Enter your initial prompt:  

Option 1: Brainstorm for your work or personal life  
Enter a prompt into the gen AI tool. For this first step, you’re only going to include the task from the prompting framework. You’ll add the rest of the framework in later steps.  
Option 2: Brainstorm a new clothing collection  
Enter the sample prompt into the gen AI tool: “Give me ideas for new T-shirts for my clothing store.” Note that this prompt only includes the task from the prompting framework and will require iteration in a later step.  
Step 2: eva;uate the output:  

Review the output from your initial prompt, and evaluate what information may be missing or unhelpful to satisfy your brainstorming goal. Consider the full context of the option you chose. For example:  
Option 1: Brainstorm for your work or personal life  
Evaluate whether the output includes ideas that:  
Help you accomplish all parts of your brainstorming goal  
Relate to the context of your brainstorming goal  
Align with what you were expecting the output to be  
Option 2: Brainstorm a new clothing collection  
Evaluate whether the output includes clothing ideas that align with:  
Your customers’ tastes and preferences  
Your customers’ price points  
Your best-selling clothing collections  

Step 3: Take an iterative approach:  

Whichever option you chose, revise and refine your prompt by adding more of the prompting framework. For example, you could:  
Specify the format you want to receive in your task, such as bullet points or a table.  
Add three to four sentences of additional context.  
Provide examples as references.  
Restructure your initial prompt into simpler sentences.  
Ask follow-up questions.  
When you’re ready, enter your new prompt. Then, continue iterating until you feel confident that the output is giving you sufficient brainstorming ideas. You'll know you've reached the best output when it provides enough relevant, accurate, and helpful suggestions—the kinds of ideas that really spark your creativity.  
My prompt:  
suppose you are grade 2 , immersion french school in vancouver, then give me a plan as a table with coontent and example and link a refrence that you are talking about that ,for my daughter. My daughter is 7 years old and in grade 2 in port moody immersion french school,  
give me a educational plan for her studies for all of the skills and course who she learn from school in this year and the list of task that i have to work with her every day, and consider she is at school every day until 4:30 and at 8 she has to go to sleep, and also every day minimum 30 min she has to practice cello.  


## Create images with gen AI


​Some gen AI tools can create images, a sunrise, a bouquet ​of flowers, or even a crab riding a dolphin. ​But those same tools can also make images for a business ​or a professional presentation. ​Maybe you're a musician playing a gig in New Orleans ​and you want to promote your concert, ​so you use a gen AI tool to help you create a poster ​to advertise the show. ​Let's prompt Gemini to create both text ​and images so we can discuss the subtle ​differences between prompting ​for each modality.  

We'll start with the text first.  

 ​Remember to keep the thoughtfully, create, really, excellent, ​inputs framework in mind. ​Text-based prompts work best when we  specify our task ​and add some clear context so we could prompt: ​Generate headlines ​for a poster promoting a rock concert ​in New Orleans.  

Answer of Gimini:  

Ex:  

So how can we make these images even better? ​Let's break down how to iterate ​and refine a prompt for images. ​We're still going to use the prompting framework, ​but with a few little tweaks. For the concert poster ​maybe you liked the appearance of the guitar, ​but you wanna make it even more exciting by adding a storm ​with lightning striking the guitar.  

​We could refine it by writing: ​Now, make the sky stormy ​with lightning hitting the guitar. ​There we go. You could keep this image or keep evaluating ​and iterating again ​and again, adding relevant details from each new output ​until you get one that works.  


## AI IRL: Refine your creative vision

So iteration is just improving constantly. ​So trying to take a prompt or an interaction with AI ​and improve it iteratively, that is ​by looking at the output, using that feedback ​to make your prompt better.  

 let's say as an example, you say, Hey, ​I want a new logo for my team at work,  

​And it builds you a logo, and there's maybe four of them. ​They all look a little bit strange, ​but none of them really fit your aesthetic. ​You say, well, actually I want them to be in these colors. ​And so you ask him for some colors ​and still, you know, there's an abstract one, ​there's a cartoony one, there's a very serious one, ​you know, then maybe there's a line art one. ​You say, oh, the line art looks right. ​But actually I want it to be more coherent. ​I want it to be simpler.  

​So you iterate on your prompt again, you know, I want a logo ​for this team that conveys this idea in a line art style, ​using these colors,  
you keep on going. ​You keep on iterating ​until you get some logo choices that you might like  
​Maybe it should be bigger ​or maybe whatever sort ​of feedback you might work through with a designer. ​But we haven't naturally done that with computers yet. ​And that's part of what's so exciting about this generation ​of AI is that you really can collaborate back ​and forth on iterative tasks.  

Use images, documents, and more in prompts  

We just use text to create an image, ​but we can also use an image as part of our prompt ​to create a different type of output. ​  

Let me introduce you to multimodal prompting. ​The essence of multimodal prompting is using different types ​of media to prompt a generative AI tool, like inputting image ​and text, or audio and text. ​This can be especially useful in the workplace. ​You can take a picture of a chart ​and ask a gen AI tool to explain the data in plain language. ​You could upload different logo options ​for your company's rebrand as a set of references, ​and then prompt the gen AI tool ​to give you more choices based on each direction.  

Or you could capture audio of another language ​and ask for a transcription in the language you understand. ​Here's an example where we'll prompt with both image ​and text to receive a text based output from Gemini. ​Let's imagine you're an entrepreneur ​who needs help creating social media captions ​for a new design of nail art you're selling. ​You can take a picture of your nail art ​and ask for help writing a caption. ​Here's a photo of the nail art, ​and we'll input this into Gemini and prompt: ​Write a social media post featuring this image. ​The posts should be fun, short ​and focus on the fact it's a collection ​of new designs ​I am selling. ​Note that in addition to including a reference photo ​of the nail art, we still used the other elements ​of our prompting framework.  

​We specified our task, added some context, ​and included the format. Besides the image itself, ​we didn't provide other references, ​but if we have a specific tone ​or voice, we want the gen AI tool to match. ​We could always input a few captions from previous ​posts to reference. ​This is great. Gemini analyzed the image ​and created a fun caption you can ​use to market the nail art. ​Notice how it uses emojis to break up the text ​and how it engages followers ​by asking a question about their favorite design. ​The cool thing about multimodal prompting is ​that it reflects the way you experience the world.  

Output:  

You don't just discuss the words ​or images in a work presentation. ​You build connections between them ​to get a fuller understanding of the topic in question. ​A mix of text, images, ​and other modalities can open up new ways ​of solving problems or saving time. ​You could use a gen AI tool to turn a picture ​of a city map into a list of notable landmarks. ​Find key insights within an audio file, ​or quickly extract a list ​of room names from an office floor plan.  

 ​Here's another example: ​You go to a conference and receive a schedule of events ​and you want your team to focus on a few of the events ​in particular. I want to send a reminder ​to my colleagues about certain events from a conference ​schedule. Extract the times of the keynote speaker ​and two panel discussions from this schedule ​into a table.  

Output:  

​Again, we specified our task, provided helpful context, ​and included the format ​before inputting the picture of the schedule. ​Let's check it out. ​Great. The table makes it really easy to see ​where your team needs to go ​and when. You can even take it a step further ​and prompt Gemini to draft an email about these events. ​We'll get into prompting for email drafts ​later in the course. ​Just remember to keep the prompting framework in mind no ​matter what modality you are prompting in ​to achieve the best results.  


## Understand multimodal prompting (reading)

If you were an artist, you could probably create a masterpiece using only one color of paint—but using more colors gives you way more power to produce something amazing. The same is true when it comes to a prompt. You can accomplish a lot with text-only prompts, but you can add more elements to take them to the next level. With multimodal prompting, you can achieve much more than with text alone, opening up a world of new possibilities.  

What is multimodal prompting?  
Multimodal prompting is a big term with a simple meaning. To break it down, modalities are different types of formats, like text, image, or audio, that can be used to instruct a generative AI tool. So multimodal prompting is when you use multiple modalities in the same prompt.  
Multimodal prompting is useful because it lets you do things like translate images into detailed text descriptions for visually impaired users, or generate graphics based on an audio recording that describes a marketing campaign.  
Benefits and considerations  
Think about it like this: the world is multimodal. When you’re giving a presentation at work, you’re probably using text, images, and your own voice to help your audience understand your point. Multimodal prompting works in the same way. It reflects how you experience the world by building connections between text, images, audio, and other modalities, helping you provide clearer instructions to a gen AI tool.  
Including multiple modalities isn’t a one-size-fits-all solution, but it can improve your prompts. For instance, if you ask a gen AI tool to write a poem about a sunset and include a photo of one in your input, the gen AI tool can use the photo to describe specific colors and details. The result is a much more vivid poem.  
While multimodal prompting is versatile, it has some limitations. Gen AI tools sometimes struggle with abstract ideas, handling complex combinations of modalities, and occasionally, just plain old common sense. For example, while gen AI tools are always evolving and improving, multimodal prompting isn’t reliable for counting just yet.  
Multimodal prompting examples  
Multimodal prompting is most effective in situations where you need to transfer information from one media to another. Here are a few examples:  
You ask a gen AI tool to suggest recipes based on a photo of the ingredients in your fridge.  
You need to create a digital teaser to promote an event between two brands on social media. So you input both brands’ logos and colors into a gen AI tool, and ask it to generate a visual for the joint event.  
You’re working on a short story about a forest you just visited and need help describing the sounds and atmosphere. So you add some audio you recorded while visiting the forest to your prompt, and ask the gen AI tool to use it to inspire the atmosphere and details of the story.  
Using the prompting framework  
Just like when you design text-based prompts, you’ll still rely on the prompting framework for multimodal prompts: Thoughtfully Create Really Excellent Inputs. However, you might need to adjust the framework based on the modalities you’re using in your prompt.  
Task: Along with being specific about a persona and format, be specific about how you want different modalities to be used and why you’re including them in the task.  
Context: Just like in a text-based prompt, you’ll need to add context so the gen AI tool knows exactly what you want it to do. Consider which modalities you’re using in your prompt when providing context and if there are any specific constraints or considerations that are important to include. For example, if you input an image of the inside of your refrigerator, you may only want the gen AI tool to consider the fruits and vegetables in the image and not any of the packaged goods.  
References: Share written, visual, or audio references to help gen AI tools understand the type of output you’re trying to create. Not every tool supports every sort of reference, so make sure you’re using a gen AI tool that supports the references you want to give it.  
Evaluate: Run the prompt as usual, but take extra care to evaluate how the output looks or reads. Since you’re using different modalities, that might involve a more detailed review of the output than simply evaluating a text response.  
Iterate: If the output is not meeting your needs, try one of the four iteration methods: you can revisit the prompting framework, break the prompt down into shorter tasks, introduce constraints, or tweak your phrasing or switch to an analogous task to help trigger a different, potentially better, response.  
Multimodal prompting is a powerful tool that lets you transfer information into different mediums and create endless possibilities of outputs. You’re the artist, and the gen AI tool is your paintbrush.  


## Practice Assignment

Activity: Create an image with gen AI  

In this activity, you'll use the 5-step prompting framework to create an image. What image you decide to create is up to you, it can be personal or work related. If you can't think of an image you'd like to create, use the provided scenario.  
As a quick reminder when crafting your prompts:  
Thoughtfully: Describe your task, specifying a persona and format preference.  
Create: Include any context the gen AI tool might need to give you what you want.  
Really: Add references the gen AI tool can use to inform its output.  
Excellent: Next, evaluate the output to identify opportunities for improvement.  
Inputs: Then, iterate on your initial prompt to attain those improvements.  
Remember these best practices when prompting for images:  
Provide vivid descriptions that help the gen AI tool determine the type of image it needs to create.  
Specify the size, color, and position of objects in the image.  
Explain the overall aesthetic or style you want.  
Provide examples for the gen AI tool to reference.  
AI tool access  
To complete this activity, you can use any browser-based generative AI tool of your choice—however, you’ll need to use a tool that can generate images. The following steps feature Gemini, which you can access by going to gemini.google.com. But you can use any image generator you choose, such as ChatGPT, Midjourney, Craiyon, or an image generation bot in Poe. Remember, generative AI technology is dynamic and ever-changing, so always double check what features and capabilities are available in the tools you’re using.  
Scenarios  
Read through the following options, then complete the activity using the option that best suits you.  
Option 1: Create an image for your work or personal life  
Choose an image you might need to create for your work or personal life. Need an inspiring visual to kick off your next work project? How about a memorable logo that perfectly captures the essence of your newsletter, or a captivating image that will leave your audience in awe during your big presentation? Maybe you're dreaming up a new invention and need a sketch to bring it to life. The possibilities are endless.  
Whatever you choose, you’ll be prompting a gen AI tool to help you create your ideal image. Be sure to keep the purpose of the image in mind, which means thinking about your audience, or any other details that might be important. Adding references may also help the tool understand the style of image you’re going for.  
Option 2: Create an image for a clothing collection  
If you can’t think of any images to create, try using the following scenario instead:  
You own Clothing Essentials Company, a small business targeting middle-income consumers aged 18 to 39. For each season, you plan to offer several new clothing collections based on current trends.  
Your newest collection, the Minimalist Collection, is designed for young adults who identify as minimalists, trying to balance their hectic work schedules with a bustling social life. If you completed the previous activity, you already brainstormed some ideas for T-shirts that will be included in this collection.  
The Minimalist Collection now includes 3 basic shirts in various neutral colors:  
Long-sleeve cotton shirt, offered in white, gray, teal, navy, and forest green  
Short-sleeve cotton shirt, offered in white, gray, teal, navy, and forest green  
Tank top, offered in white, gray, teal, navy, and forest green  
You’ll be prompting a gen AI tool to help you create an image that tells the story of the Minimalist Collection. To do this, consider the following questions:  
How will you present the collection so that it will appeal to your audience of busy young adults?  
Will you focus on a couple of key items, or attempt to display the entire collection?  
What lighting or background colors will help the collection have the most appeal?  
For reference, here are a few examples of clothing collection images: (Note: these are AI-generated images. Results are for illustrative purposes and may vary.)  

Step 1: prompt to create an image  
Whichever option you chose, enter an initial prompt into the gen AI tool to create an image. Remember the prompting framework (task, context, references, evaluate, iterate). Image generation tools are always changing, and so are their global availability and language options. If the tool you’re using is not generating a helpful output, you can try a different tool, such as DALL-E, Midjourney, Craiyon, or an image generation bot in Poe. Or, adjust your initial prompt, and try again.  
Pro Tip: To practice your image-generation-prompting skills, try playing “Say What You See,” a web-based game in which you’re asked to describe images and check how well your description matches the original prompt used to create an image.  
Like:  

Step 2: Evaluate the output  
Review the output from your initial prompt and evaluate what information may be missing or unhelpful to satisfy your goal. Consider the full context of the option you chose. For example:  
Option 1: Create an image for your work or personal life  
Evaluate whether the output is:  
An accurate depiction of what you prompted for  
A relevant representation, suitable for your needs  
An error-free image without any inaccuracies  
A visual style that appeals to you  
Option 2: Create an image for a clothing collection  
Evaluate whether the output is:  
An accurate depiction of the clothing collection  
An appealing vision of style and aesthetic for minimalist young adults  
An error-free image without any inaccuracies  
Also, consider which parts of the prompting framework may have been missing from your initial prompt (task, context, references, evaluate, iterate).  
Step 3: Take an iterative approach  
Revise and refine your prompt by adding more of the prompting framework. For example, you could:  
Specify more distinct elements of your image in your task, including size, color, position, and overall aesthetic.  
Add three to four sentences of additional context.  
Search for and add extra references to provide the gen AI tool with examples of what you’re going for.  
When you’re ready, enter your revised prompt. Then, continue iterating until you feel confident that the image is an accurate depiction of your vision.  
Note: If you created images for the Minimalist Collection, save your final images to a folder somewhere, like a Google Drive. You’ll have the opportunity to return to these in a later activity.  
Pro Tip: Try multimodal prompting  
Modality refers to the different media you can use to prompt generative AI tools. Think of it this way: if you prompt using text to create an image, you’re moving from one modality to another. But you can also include multiple modalities in your prompt, like inputting image and text, or audio and text.  
Each tool has unique capabilities, so check whether the tool you’re using can handle the formats you want to work with. Then, you’ll be ready to try a multimodal prompt to create your image.  
Answer:  
as a specialist Logo designer with experience workimg  in art and graphic designer , give me a Logo for my small home  business for my instageram profile, and in your image put   traditional iranian cake holder with a beautifull cream cake who is decore with fondant and use the state of ther art technic for decoration  with a minimal  shik backgroung which warites Delaram Cakery , also an painting of shadow of woman who is shef next to that. this is the background of my business store ..  
update my previus prompt  and use minimal decoration cake with rose gold color  
update previous prompt use the traditional cake holder instead of this one , also put a chef hat on her head  and pay attenetion to adjust the size of chef with cake and cake whith cake holder  should be completely adjust.  
Output:  


## Use gen AI responsibly


Generative AI tools are powerful, ​but like any tool, it's important you use them responsibly, ​especially at work. ​First, consider the problem you're using gen ​AI to help you solve. ​Does it align with your goals ​and your obligations to your clients and coworkers? ​What about your organization's policies ​and local laws about using gen AI ​to perform this type of task? ​If it doesn't align, then you should rethink your process ​and whether or not a gen AI tool is right for the job. ​Second, consult your company's rules or policies ​before entering confidential ​or sensitive data into gen AI tools. ​You can also check if your company has an enterprise version ​of a gen AI tool that is okay for other types of use.  
​And remember, if you're using gen AI tools for personal use, ​avoid entering personal ​or confidential information about yourself into publicly ​available tools, and always check ​how the data you enter might be used. ​Finally, being a responsible gen AI user means evaluating ​outputs for potential bias and errors, ​and disclosing any use ​of gen AI when sharing content with others. ​While it's okay to enlist the help of gen AI, ​you'll still need to evaluate the outputs ​for accuracy the way you would for any output. ​  

The same goes for hallucinations, ​which is when a gen AI tool provides outputs ​that are inconsistent, incorrect, ​or even nonsensical ,Hallucinations most often happen when ​someone gives a gen AI tool vague or unclear instructions. ​Or when a tool guesses at an answer ​to something it didn't quite understand. ​Hallucinations can be hard to recognize. ​That's why it's so crucial to fact check ​and cross-reference outputs to confirm if a fact ​or statement in an output is true.  
​Remember, gen AI tools aren't thinking critically ​the way humans can. ​It's important to keep what we call a human in the loop ​approach. Meaning a human should verify gen AI outputs ​before using them. ​I recently generated an image for a presentation. ​I wanted to have a bunch ​of cats on a rocket going to the moon. ​Now instead, the output was a little bit off. ​The cats were on top of the rocket rather than inside it.  

​And that's not exactly safe for cats, is it? ​While I did write in my prompt that cats needed ​to be on a rocket, I didn't mean that literally, ​but the tool didn't know that. ​So I iterated and specified that the cats should appear safe ​and sound inside the rocket instead of on top of it.  

​Some gen AI tools such ​as Gemini have a built-in fact checker that allows you ​to cross-reference the outputs using Google search. ​Comparing outputs side by side makes it easier to determine ​how accurate your initial output is ​and to find any discrepancies.  
​So how can you avoid these issues ​before they become a problem? ​  

Try to recognize biases and outputs ​and the negative consequences they can have. سعی کنید سوگیری‌ها، خروجی‌ها و پیامدهای منفی احتمالی آن‌ها را شناسایی کنید.  
​They may appear as stereotypes ​or unfair representations of a group of people. ​Avoiding bias to negative outputs starts ​with inputting specific detailed prompts ​and iterating as needed.  

 ​Another key part of this is using language ​that includes people of all backgrounds, genders, ​and ethnicities, and avoid stereotypes ​and generalizations in your inputs. ​For example, if you were using a gen AI tool ​to help you write the description for a job posting, ​you should avoid the gendered terms like serviceman ​or workman. ​Instead, use service person or worker. ​So the tool doesn't write a description that only speaks ​to someone who identifies as male. ​Remember, gen AI tools are only tools they don't think ​critically and can't understand nuance the way humans can.  
​It's your job to bring ​that human perspective every time you use a gen AI tool.  


## AI IRL: Discover strategies to mitigate hallucinations


 So hallucinations are AI outputs that don't match reality. ​They're not true. And sometimes ​that can be good if you're writing a fictional story ​or a creative piece. ​- Right. ​- And sometimes that can be very undesirable ​as when you're trying to have factual information ​or you're trying to analyze something and, ​and it comes up with a completely made up answer. ​Or even worse, a subtly wrong answer. ​- That's right. - So one of the most important things ​that everybody who uses AI should do is to check all outputs ​for hallucination, especially when you're trying ​to get factual output ​and non-creative outputs. It is your responsibility ​to make sure that what comes out of the AI actually ​matches reality.  

​And that's a often a more difficult task than it would seem. ​Some tools like Gemini actually have built in fact checking ​capabilities, and I highly recommend using ​those sorts of things. ​You know, verify with search, verify ​with your own knowledge, check it with your community ​and your friends, other coworkers. ​Those are all good strategies for mitigating hallucinations.  


## Tips for responsible prompting


Sometimes a generative AI tool just won’t give you the output you need. There’s a reason for that. Gen AI tools are great at processing information and recognizing patterns but lack critical-thinking skills and human awareness. That’s why it’s important to learn how to prompt responsibly when using gen AI tools.  

Ethical risks and AI limitations  
Gen AI tools aren’t perfect. Sometimes, their outputs can contain mistakes, bias, stereotypes, misleading information, and other harmful content. This is why a human-in-the-loop approach is so important—you must verify gen AI outputs before you use them.  

Biases and stereotypes  
Gen AI tools can sometimes reproduce existing biases about certain groups, like connecting specific activities with certain ages. This reinforces harmful stereotypes. To avoid these biases, like ageism, racism, or genderism in the output:  
Specify diversity: Add inclusive language to your prompt. For example, when prompting to create an image, you might input “a table of delicious foods.” Instead, you could write “a table of delicious foods from all over the world” or describe foods of a specific geography or cuisine. This will also produce a better output that you have more control over.  
Challenge assumptions: If a gen AI tool provides a biased response, point out the stereotype when you iterate on your prompt, and ask the tool to correct the bias سوگیری. For example, when prompting for an image of delicious foods, you may receive an output with a lot of dishes from the same part of the world. You could point out the lack of diversity in the image and iterate for a more diverse visual. Maybe you notice that most of the foods in the image are Southeast Asian dishes. You could call attention to this, and ask the gen AI tool to include more food from West Africa or Northern Europe. Providing feedback may also help improve a gen AI tool’s future outputs.  
Hallucinations  
When a gen AI tool provides an output with false information, it’s called a hallucination. Hallucinations can happen at any time and may happen when a gen AI tool gets vague or unclear instructions or when it generates an output about something it hasn’t been trained very well on. For example, a gen AI tool might miscalculate a math problem or include an incorrect ingredient for a recipe. To navigate hallucinations:  
Fact-check and cross-reference: Some gen AI tools have features that provide sources for where information was found. You can also fact-check an output by using a search engine to confirm information. You can even enlist the help of an expert if they’re available to you. Running a prompt through two or more resources helps you identify possible discrepancies in your output.  
Use clearer or more detailed language: Sometimes, a gen AI tool will misunderstand something in your input, or if your input is wrong in some way, it could impact how a gen AI tool processes it. For example, if you wrote “Why is Toronto the capital of Canada?”, the gen AI tool may use your input as if it’s correct and give you a false history of Canada choosing Toronto—instead of Ottawa—as its government seat.  
Inconsistencies and relevance issues  
While gen AI tools are evolving quickly, sometimes they will misinterpret your input or misunderstand the context of your request. For example, if you prompt a gen AI tool using an idiom or colloquial phrase like “think outside the box,” it might take this figurative phrase literally and suggest solutions that are about the outsides of boxes. To navigate inconsistencies and relevance issues:  
Provide references: This is where the References step of the prompting framework is really useful. Just be sure the references you provide are representative of your desired output.  
Provide more context: You may also need to provide more context and detail or rephrase your prompt. Instead of writing “think outside the box,” you could iterate to tweak your phrasing and instead ask the gen AI tool to “consider unique, unconventional approaches” about the topic in question.  
Responsible prompting and workplace considerations  
Gen AI tools aren’t going to be right for every situation, which is why it’s important to consider a few things before designing a prompt to help with a work-related task.  
Think about the problem you’re using a gen AI tool to help you solve. Does it align with your goals and obligations to your coworkers and clients? What are your company’s policies around the use of AI? Are you potentially putting sensitive data at risk? Is the gen AI tool you’re using a private internal tool or a public one?  
Always keep the human-in-the-loop approach at the forefront of how you use AI. That means a human verifies a gen AI tool’s outputs before they are used anywhere, whether that’s at home, at work, or somewhere else.  
Checklist for using gen AI responsibly at work  
Consider the effects of using AI to solve your problem or task and always use your best judgment and critical thinking skills. Before using AI, ask yourself whether or not AI is right for the task you’re working on. For example, would a gen AI tool reinforce or uphold biases that may cause damage to a particular group of people?  
Get approval to use AI from the appropriate people at your company before you use gen AI on projects or with clients.  
Consider the privacy and security implications of the gen AI tool you’re using, whether it’s a public or proprietary tool. You can also check if your company has an enterprise version of a gen AI tool that allows you to put it to work on other use cases.  
Evaluate all AI-generated content before you incorporate it into your work or share it with anyone.  
Disclose your use of AI to your team and clients, and be transparent about how you use it.  
When in doubt, clear the memory  
Periodically clearing the memory of a gen AI tool is another great way to improve the accuracy and relevance of its outputs. Clearing the memory gives the tool a fresh start, allowing it to approach new prompts with a clean slate. Other benefits of clearing memory include:  
Protecting privacy: Removes potentially sensitive information from previous interactions.  
Avoiding bias: Prevents the tool from carrying forward assumptions or stereotypes from earlier prompts.  
Reducing confusion: Ensures the tool focuses solely on the current task and context.  
Troubleshooting: Refreshes the tool when it seems stuck or is producing unexpected results.  
Different tools have different instructions for clearing memory, so be sure to check the settings for instructions to learn how.  
One note when it comes to clearing memory: some tools automatically clear the memory each time you open it and therefore don’t remember what you previously asked.  
AI is a powerful tool—which is why it’s important to use it carefully and responsibly. That means being mindful of ethical risks, acknowledging AI’s limitations, and accounting for biases. The best results come from a combination of human ingenuity and a gen AI tool’s capabilities. So keep asking insightful questions, refining your prompts, and above all, using your critical-thinking skills. That way, you contribute to a future where AI serves everyone responsibly and ethically.  


## 3- Design Prompts for Everyday Work Tasks


I have to read a lot of research papers for my job. ​Sometimes I get several sent to me in a single day, ​and even though I love hearing about everything new ​happening in my field, there are times when I can't get ​through every line of every paper. ​When that happens, I'll upload one of these papers ​to a generative AI tool and start a conversation. ​I'll prompt for the most important points in the research ​and then ask follow up questions on ​information that I'm curious about. ​It's helped me get familiar with a lot of topics quickly ​because it's like having a creative on demand assistant ​that I can have a conversation with. ​In this module, you're going to learn about the best ways ​to prompt gen AI tools to help you summarize text, ​write better emails, level up your brainstorming, ​build schedules effortlessly, ​and take meeting notes instantly. ​Now, lets learn more about what you can do ​with those prompts and how they can benefit you at work ​to boost your productivity and spark your creativity.  

## AI IRL: Tackle your to-do list with the help of AI

I think sometimes it can be intimidating just ​to look at a blank AI screen and say, where should I start? ​And so summarizing, brainstorming, planning, researching, ​you know, is any of that something that you are going to do? ​My job is to coach top executives at Google in the ​area of productivity. ​I also started productivity at Google, ​so I share productivity tips both internally ​and externally for people to get more done in their day. ​When I'm doing my coaching sessions, ​I usually have someone pull out their actual to-do list for ​that day or that week, and I scan through it with them ​and say, is there anything on this list ​that AI could help with?  
Write emails with gen AI  
​Let's try this example using our prompt framework. ​We'll add the task, provide context, ​then evaluate and iterate. ​This is a useful exercise, ​whether you're a copywriter working on an ad campaign, ​a speech writer, drafting, talking points for an executive ​or gym manager communicating a schedule change. ​  
Let's start with the persona. I am a gym manager. ​Next, we'll add in the context and we have new gym schedule ​and specify the task. ​Write an email informing our staff of the new schedule.  
​Highlight the fact that the Monday, Wednesday, ​Friday Cardio Blast class change from 7:00 AM ​to 6:00 AM and let's add even more specificity, ​especially about the content ​and format of the email, ​which could include language or tone. ​Make the email professional and friendly ​and short so that the readers can skim it quickly. ​And now let's just paste in the new gym schedule. ​Here's the new schedule. ​Okay, this is a really great email to send to the staff. ​All the information is there about the schedule changes, ​and it's short and easy to read. ​But did you know you can ask Gemini ​to adjust this same output for a new audience?  

Output:  

​This would be useful if, for example, you wanted your output ​to be more casual for a small intimate team, more formal ​for the executives of the team, ​or even for a completely different audience. ​Let's try it. We're gonna iterate on our prompt asking ​Gemini to write an email ​to the gym members in a more casual tone. ​We're asking for a new version here ​with new specifics and context. ​Now, write a concise consumer facing email ​with the same information for our gym members and clients. ​Let's get even more specific. ​Explain that this new schedule ​will help us better serve them.  

Output:  

​With some iterations to your task and context, ​you can tweak your writing ​to land your message how you want it. ​Whenever you're drafting any sort of communications ​with the help of a gen AI tool, ​make sure the outputs are factual ​and adjust your prompts so that you receive the information ​that's most helpful to you  

Prompt with personality: Match gen AI to your writing style  
How gen AI tools approach tone and style  
Ever noticed how some AI-generated content can sound a bit robotic, while other times it feels like you’re chatting with a friend or professor? The reason for that is in how gen AI tools handle tone and style. The tools do this in a few different ways, but this reading will focus on just one.  
Contextual understanding  
Think of a gen AI chatbot trained on a massive dataset of everyday conversations. When you ask "What's up?" it understands that you're probably asking how it’s doing. It recognizes this common greeting from its training data. Most likely, it will respond appropriately with something like "Not much, how about you?"  
That’s thanks to contextual understanding, which allows a gen AI tool to interpret information in a specific setting and use that comprehension to generate an output. This helps the tool:  
Identify audiences.  
Recognize linguistic cues, like a question mark at the end of a sentence.  
Learn language from provided references.  
Adapt to your preferences.  
Stay consistent in the language it uses.  
Understand inputs and generate outputs in the tone and style you provide it.  

A horizontal flow chart illustrating contextual factors that inform tone and style and output, connected by arrows. Four blue boxes on the left are labeled “Audience,” “Linguistic cues,” “User preferences,” and “References.” These boxes connect with dotted lines to two yellow boxes in the middle labeled "Tone" and "Style." The "Tone" and "Style" boxes then connect with dotted lines to a green box on the right labeled "Output."  
Strategies for tone and style in prompting  
When it comes to matching tone and style, a gen AI tool’s contextual understanding is a key ingredient—but it doesn't make up the whole recipe. That’s where you come in. Here are a few ways to adjust your prompts to help fine-tune tone and style.  
Specify your tone and style  
When using the prompting framework, enter your desired tone and style within the task.  
Maybe you have a report you want summarized for a colleague or manager. For example, you could write:  
Summarize this report into three short paragraphs.  

Instead, specify the tone in your prompt:  
Summarize this report into three short paragraphs in a friendly, professional, and easy-to-comprehend tone.  

Your inputs will continue to impact your outputs as you iterate in the same conversation thread, so being explicit and detailed from the initial setup is important. Bottom line: Don't leave things to interpretation. The more specific you get about the tone you’re after, the better the tool can match your expectations.  
For example, specify “witty banter” instead of “humorous,” or “like talking to a friend” instead of “casual.” Here are some other examples of tone you could include in your prompts, with more specific alternatives:  
Academic, or “scholarly and in-depth, like a professor”  
Persuasive, or “compelling and convincing”  
Sarcastic, or “dryly funny, like a wry comedian”  
Inspirational, or “motivating and uplifting”  
Simple, or “like you’re a kindergarten teacher explaining this to their students”  
Finally, you might want to add constraints in your first prompt to ensure the language stays on track, such as “avoid using jargon that would be confusing to people who are unfamiliar with the subject.”  
Provide tone and style references  
You can specify your tone and style even further by providing a reference for the gen AI tool to work from.  
Suppose you’re prompting a gen AI tool to help you write a description for a new line of products. You should use specific descriptors of the tone and style you’re interested in based on the audience of the products.  
For example, you might write:  
Help me draft a description for a new line of rock climbing apparel. The target audience is young outdoor enthusiasts and climbers. I want the description to speak to the audience's desire for durable, attractive rock climbing apparel for indoor and outdoor climbing. Keep the language upbeat, informative, and inspiring. Imagine you're talking to a friend who's an avid rock climber.  
This prompt will work as is, but you could get even more specific about the tone and style you want by providing a reference in your initial prompt rather than waiting to see the output and deciding if it needs one. In that case, you’d just add something like this to the end of your prompt:  
Consider the tone and style of interviews with history’s most renowned climbers as a reference.  
If you’d rather try your luck, you can generate the output without a reference, edit it to your liking, and then use that as a reference for the gen AI tool in your next iteration.  
Iterate on tone and style  
If your initial output doesn’t feel quite right, that’s a good time to get more specific by iterating on your prompt and adding more details and directions.  
Consider the example above. Maybe the message is too bland or the language feels like it won’t appeal to the climbing community. To iterate, you could inject more of the voice you want into the prompt, explain the exact type of apparel you’re selling, add more tone descriptors, and emphasize an emotional connection to the sport of climbing, like this:  
I need this product line description to speak to the heart of young climbers of all kinds. I want to evoke their passion for pushing limits both indoors and out. The shirts, jackets, pants, shorts, tanks, and carabiners enable climbers to express their personal style without sacrificing quality, comfort, or durability, ensuring they look sharp and climb smart. Channel the spirit of climbing legends, and inspire them to reach new heights. Make the language less cheeky and more reverent of the sport.  
Remember, Always Be Iterating! Continuing to refine your prompt provides the gen AI tool with more information so you can get closer to a final output that suits your needs.  
Why prompting for tone and style matters  
Whether you’re crafting a professional email, a fun social media post, or a persuasive essay, the right tone and style can make all the difference in how your message is communicated and received. When you specify voice and tone in a prompt, a gen AI tool will use contextual understanding to figure out what you mean, and match outputs to the voice you’re hoping for. If it’s not what you want, you can always provide references and iterate. To get the best results from a gen AI tool, treat it like you’re giving directions to an actor—the clearer your instructions, the better the actor can embody the character you’re envisioning.  
Put briefly, nuance matters! And the more you teach gen AI tools about it, the more helpful they can be. So get specific with your prompts, and narrow in on how you want the outputs to sound. By doing so, you equip gen AI tools to serve you better, whether as an individual or within the unique context of your workplace.  

Brainstorm ideas that buzz  

​In this lesson, you'll learn how to write prompts ​to generate ideas with Gemini. ​Consider this, you need to plan a launch ​for a new video game. ​Gemini can help you with everything. ​From brainstorming sales strategies ​to managing the launch timeline. ​We'll start with the persona ​and include the context as well. ​I'm a marketer for a well-known video game producer, ​known for creating immersive story-based ​online video games. ​I'm planning the launch ​of a new medieval fantasy role-playing game ​that follows the path of a young protagonist searching ​for their missing partner.  

Output:  

​We've also specified the task, create a timeline ​for the launch, and provide pre-launch ​ideas to generate buzz. ​With all that in mind, let's review the output. ​This is a great start. Sign me up for the contest.  
 ​While these are cool pre-launch ideas, ​they could use a little more detail. ​Maybe your team is hoping ​to promote this game around the world. ​Let's give Gemini more context ​and ask it to update the launch events ​with a global audience in mind.  

 ​Evaluating and iterating is like having a conversation ​with the gen AI tool continually guiding it ​to generate our desired output. ​We can all use a little help generating new ideas. ​How can gen AI help you with brainstorming at work?  

Build tables and trackers effortlessly  

But there are times when I really need to use spreadsheets ​to create tables or track a project timeline. ​So I've started to use generative AI to help me, ​and it's made creating those tables much easier ​and less time consuming. No matter where you work, ​being able to easily turn information into an organized plan ​can be a massive help. ​Think of a schedule or project tracker.  
​These documents are so important ​because they keep team members aware of their roles ​and responsibilities and keep timelines ​and deliverables on track. But building them can be a chore. ​Let's explore how gen AI can help you ​speed that process along. ​Let's try this example. ​You need to create a schedule ​to plan your employee staffing each week ​and want to prompt Gemini to create a table. ​Here's our task, format and context.  

Output:  

Even better, we can export the schedule to Google Sheets ​to continue working on it  

​After logging in, we can prompt Gemini ​in Sheets to summarize our schedule, create a new schedule, ​or even create formulas to quickly analyze the information. ​But remember to avoid entering any sensitive information ​that you wouldn't want a tool reviewer to have access to. ​In this case, we wouldn't want ​to enter any specific information about employees. ​That's why we use anonymous employee numbers. ​Always consult your organization's policies ​regarding sensitive data and gen AI use ​before leveraging a gen AI tool for work.  

Supercharge your work with Gemini for Google Workspace  
You already know that generative AI can help boost your productivity, efficiency, and creativity. But did you know that gen AI is embedded in the productivity and collaboration apps you rely on every day? All you need is a Google Workspace account and the Gemini for Google Workspace add-on.  
Gemini for Google Workspace capabilities are available directly in Gmail, Google Docs, Google Sheets, Google Meet, and Google Slides to help you write, organize, visualize, accelerate workflows, improve productivity in meetings, and more. To access Gemini in these Workspace apps, select the “Ask Gemini” button in the upper right corner of the app. Here’s a breakdown of how these embedded gen AI tools can elevate your day-to-day. Remember to use the prompting framework as you go.  

Summarize information and surface insights  
With Gemini in Gmail, Docs, Slides, Sheets, and Drive, you can generate, summarize, and analyze materials to speed up your workflows. Want to quickly get the key points from a lengthy email? Or turn a disorganized collection of data into an easy-to-read table? The side panel feature across those apps helps you tap into the power of gen AI to work faster and smarter directly in your browser tab.  
Improve your writing  
Whether it’s a speech, an email, or a research report, sometimes the most difficult thing with writing is getting started. With Gemini in Docs, you can generate completely new text or refine existing work so it’s exactly what you need. Maybe you aren’t sure how to start your sales pitch, or your lesson plan runs a bit over 45 minutes. Gemini in Docs can help at all stages of your writing process to kickstart ideas, get words on the page, or revise your work until it’s just right. The best part? You don’t even have to leave your Doc to use it.  
To rewrite your existing work, highlight the text that needs a makeover. Then select the “Help me write” icon to access a few preset options. No copying and pasting your work into a different tool—Gemini in Docs is embedded right there in your first draft to sharpen the tone, add or cut details, and more.  
Now think of how good it feels to find the exact right words when communicating something. Gemini in Gmail is your built-in writing assistant, helping you craft new messages or refine existing drafts, so you can write exactly what you mean. Using tech to message people doesn’t have to make things feel impersonal—it can actually enhance how you engage with your team, clients, and others by keeping your message focused, useful, and true to what you want to get across.  
Once you’re in an email draft, select the “Help me write ” button and write your prompt. If you’re starting with a draft that you’d like to freshen up, select “Help me write” and choose from the same options.  
Organize your data  
Gemini in Sheets makes it easier than ever to track and organize spreadsheet data. It offloads the tedious tasks, like filling out cells and formatting tables, so you can get to work building meaningful stories out of your data. Instantly build custom templates, visualize your information, spot trends, and draw conclusions without even leaving your spreadsheet.  
Create original images  
Whether you’re addressing a group of visual learners or just want to keep your audience engaged, well-designed visuals can elevate your work. Luckily, Gemini in Slides can help you bring your presentations to life. Generate custom images that reinforce your message, simplify complex information, and capture people’s attention right in your Slide deck.  
Communicate with others  
AI can even help make virtual collaboration more seamless. With Gemini in Meet, you can create custom background images for calls; adjust your video quality, lighting, and sound; and create translated captions. You can even join meetings with multiple laptops in the same room without clunky conferencing hardware, so you can work and connect with your team in ways that feel natural, personal, and productive.  
To generate a background image, choose the meeting on your calendar. At the bottom right of your self view, select “Apply visual effects,” then “Generate a background” to add in a custom prompt. You can also select a design style out of the same options we mentioned earlier.  
How else can Gemini for Google Workspace help you reach your professional potential? Check out the Gemini for Google Workspace Prompting Guide for an even deeper exploration of how you can put Gemini for Google Workspace to work for you.  

Gemini for Workspace is the AI-powered assistant by your side that’s ready to tackle all kinds of tasks. Whether you need to make sense of documents or level up an email or presentation, Gemini for Workspace can supercharge your productivity and unlock whole new levels of efficiency as you move through your work day. Give it a try and find out what you can accomplish!  

Activity: Create a timeline with gen AI  

In this activity, you'll use the 5-step prompting framework to create a timeline table to track a project in your work or personal life. If you can't think of a timeline you need to track, you can use the provided scenario.  
AI tool access  
To complete this activity, you can use any browser-based generative AI tool of your choice. The following steps feature Gemini, which you can access by going to gemini.google.com. Remember, generative AI technology is dynamic and ever-changing, so always double check what features and capabilities are available in the tools you’re using.  
Scenarios  
Read through the following options, then complete the activity using the option that best suits you. Be sure to apply the TCREI prompting framework: task, context, reference, evaluate, iterate.  
When creating tables, especially a timeline table, it’s helpful to add constraints to your prompt. Constraints are limitations that you specify to help sharpen your instructions, so the gen AI tool can create a table that’s really useful to you. Constraints for your timeline table might include:  
Specific dates for the timeline, like a deadline to submit an application.  
Certain limitations in availability, like employee vacations or supply chain disruptions.  
Limits to how often something can occur in the timeline, such as a daily task or weekly meeting.  
Option 1: Create your own timeline table  
Think of a situation from your work or personal life where you need help planning and tracking a timeline in a table. Maybe it’s a timeline for a product launch, highlighting key milestones like research, gathering resources, creation, and testing. Perhaps you're onboarding a new employee and need a timeline to guide their paperwork, training sessions, and team introductions. Or are you organizing a conference and require a timeline detailing venue booking, speaker coordination, and attendee registration? Maybe you’re looking for a more personal project, like a timeline for creating a beautiful garden, with time built in for planting seasons, maintenance tasks, and the joy of watching your flowers bloom.  
Option 2: Create a timeline to develop a new clothing collection  
If you can’t think of a timeline you need to track, try using the following scenario instead:  
You own Clothing Essentials Company, a small business targeting middle-income consumers aged 18 to 39. For each season, you plan to offer several new clothing collections based on current trends.  
You’re developing a new clothing collection, the Minimalist Collection. You’ve committed to releasing it in six months, ready for the fall season at the beginning of September. It’s now March.  
Your team is excited to get started, but there are some constraints you’ll need to consider:  
Your lead designer will be on holiday for one month, from June 16th to July 20th.  
Due to global shipping restrictions, your fabric shipments are likely to take six weeks, rather than the usual two weeks—including sample orders.  
Your usual manufacturer has gotten more expensive, so you'll need to allot some time to find a new manufacturer with more competitive pricing.  
Step 1: prompt to create a timeline table:  
Whichever option you chose, enter an initial prompt into the gen AI tool to create a timeline table. Remember the prompting framework and consider what kinds of information you’ll need to include in your prompt to receive a helpful table. For example, consider including:  
Particular milestones or objectives that should be in your timeline.  
Constraints to the timeline, such as limitations on dates or availability.  
Desired format or organization of the timeline, such as in chronological order, by phase or task, etc.  
My answer:  
As a business consultant and own Clothing Essentials Company, a small business targeting middle-income consumers aged 18 to 39. you plan to offer several new clothing collections based on current trends.  
You’re developing a new clothing collection, the Minimalist Collection. You’ve committed to releasing it in six months, ready for the fall season at the beginning of September. It’s now March.  
Your team is excited to get started, but there are some constraints you’ll need to consider:  
Your lead designer will be on holiday for one month, from June 16th to July 20th.  
Due to global shipping restrictions, your fabric shipments are likely to take six weeks, rather than the usual two weeks—including sample orders.  
Your usual manufacturer has gotten more expensive, so you'll need to allot some time to find a new manufacturer with more competitive pricing.  
based on this info give me a timeline to develop a new clothing collection and consider all of the constrain .  
give me in this format, organize timeline base on chronological order then base on priority for each task , then apply constrain and again apply filter on them  
Output:  

Step 2: Evaluate the output:  
Review the output from your initial prompt and evaluate what information may be missing or unhelpful for creating a timeline table. Consider the full context of the option you chose. For example, evaluate whether the output includes:  
A full table with relevant column or row headings.  
Relevant and accurate milestones or objectives.  
Realistic and adequate timeframes for each stage or task on the timeline.  
Helpful and accurate goals for successfully completing the goals or tasks.  
Accurate considerations of constraints.  
Also, consider which parts of the prompting framework may have been missing from your initial prompt.  

Step 3: Take an iterative approach  
Revise and refine your prompt by adding more of the prompting framework. For example, you could:  
Add three to four sentences of additional context.  
Input any additional constraints that may have been missing.  
Specify column headings and formatting needs.  
Include a timeline table in your prompt as a reference.  
When you’re ready, enter your revised prompt. Then, continue iterating until you feel confident that the generated timeline is comprehensive and tracks any necessary milestones or objectives. You might even consider asking the gen AI tool to evaluate your timeline table for errors or improvements.  

Pro Tip: Perform a risk analysis  
Sometimes a timeline seems reasonable, but a little investigation can reveal particularly risky deadlines or overlaps that can end in disaster. Make sure you’re evaluating the generated timeline for issues that a gen AI tool might not be critical enough to catch.  
For example, if you’re using Option 2: Create a timeline to develop a new clothing collection, you could check to see if the time allotted to find a manufacturer doesn’t overlap with the time needed for fabric shipments, or that the development time doesn’t overlap with the lead designer’s holiday.  

Capture meeting notes instantly  
 My team and I work in Google Docs on a daily basis. ​Sometimes when I'm editing, ​I'll realize the writing could be improved, ​but I'm not sure how to approach it. ​Instead of staring blankly at my screen, I can prompt Gemini ​in Docs to pull out what I need to suggest something new. ​To do that, start by logging into docs. ​You'll need a Google account for this. Let's try an example. ​  

You receive customer feedback ​that your company's return policy is too long and confusing.  
​You can paste the return policy into a doc, ​then prompt Gemini. ​From there, you can enter the following prompt. ​Let's specify the task and context. ​  

Summarize this content to write a clear ​and concise product return policy ​and outline five steps for customers ​to take in sequential order. ​  

Now you have a solid return policy ​to reference when assisting customers as well as a list ​of ways customers can begin their returns.  

​There's even more you can do to save time ​and boost productivity with Gemini and Docs. ​Some days are just so packed with meetings and people ​and action items in those meetings that it can be hard ​to keep track of who said what ​or what you're responsible for.  
​Think about a long meeting you had recently ​and just how much there was to cover. ​You might wanna a transcript, right? ​You can create one right in Google Meet.  

 ​From there, you can turn to Gemini ​and Docs to help you keep things organized ​by creating meeting minutes, ​outlines a bulleted list and more. ​To illustrate how it works, we'll use a transcript generated ​by gen AI and open up docs. ​Now let's prompt Gemini, making sure to ask ​for exactly what you need. ​Using our prompt framework thoughtfully create really ​excellent inputs.  

​First, we'll add the task, ​create meeting minutes for this meeting. ​Then specify the format. Section the meeting minutes ​by speaker, and create a bulleted summary ​of key points made by that speaker. ​If applicable, highlight action items for each speaker.  

Output:  

 ​The meeting notes might be more useful if formatted in a ​clearer way with more defined roles ​and responsibilities from the meeting. ​Let's iterate on our prompt to achieve that. ​We'll use the same task. Create meeting minutes ​for this meeting, but we'll change the format ​and get more specific with ​what exactly it is we want from the output.  

​Create sections based on key points ​extracted from the minutes. ​Attribute each key point to a speaker, ​and then assign action items to the speaker ​who is most appropriate to complete them. ​Much better. The action items are clearly displayed ​and you have the most important ​takeaways from each attendee. ​Now you can use these notes to align ​with your colleagues on a project. ​Share updates to keep stakeholders informed, ​help your teammates complete their responsibilities ​and monitor the progress of deliverables.  
Output:  

Summarize lengthy documents  
<https://aistudio.google.com/prompts/new>  

​- When you're doing research, writing a report, ​or investigating market trends, you're bound ​to come across some especially complex or lengthy materials. ​Luckily, a generative AI tool can summarize long blocks ​of texts, extract key insights, ​and even transform them into new resources. ​You can also specify your preferred format ​in your prompt, so you get exactly the ​type of output you want. ​What's a report you've been meaning to read ​but you haven't had the time to? ​You wanna summarize it and pull out key insights, ​but since the report is so long, you'll have ​to use a gen AI tool with a long context window.  

 ​A long context window allows for the processing ​of a large amount of information in different ​formats at once. ​The long context window also enhances the gen AI model's ​ability to understand and generate more coherent ​and contextually relevant responses to our prompts.  
​We'll test this in Google AI Studio. ​Let's open up AI studio and sign in with a Google account. ​Notice how we can give our prompt a name. ​This can make it easier to find our prompts later, ​and it can be useful when sharing prompts with others. ​Now let's start using the prompting framework.  

​Here's the task, including the format. ​Summarize this report in an outline ​focus only on the most essential points.  

​Pretty cool, huh? 44 pages ​of information distilled down into a few points. ​Let's call this prompt report summary.  
 ​Long context windows aren't available on every gen AI tool, ​so depending on the gen AI tool you use, it may not be able ​to analyze long documents. ​Gen AI technology is dynamic ​and ever changing, so always double check what features ​and capabilities are available in the tools you're using. ​And here's a pro tip.  

 ​In the meantime, if you're using a gen AI tool ​that can't handle a large piece of text ​and you need a summary, break the text up ​and paste chunks of it in at a time prompt ​to summarize each chunk, ​and then ask to summarize the summaries, ​whether you're doing research or analyzing reports.  

​Getting a summary of what you're reading can help you ​understand the material in a shorter amount of time. ​Another pro tip for you, ​not only can gen AI tools summarize lengthy documents, ​but they can also explain them to you in different ways. ​By incorporating a persona specifying who the audience is, ​you can personalize the summary for different people. ​For example, you can ask things like, summarize this ​for someone who isn't great with numbers, ​or summarize this for a small business owner, ​or even summarize this using eighties movie quotes.  

AI IRL: Reclaim your time with the help of AI  

​- So, you know, AI is the thing ​that we're all talking about nowadays. ​Give me a few examples. ​How are you using it in your work life? ​How do you use it in your personal life? ​What are you already doing that AI has helped you with? ​- I think summarizing is probably one of the biggest places ​that I feel like was my AHA moment with how, you know, ​how much time did this save me? ​Because there was a couple of places ​where I was summarizing maybe 500 or more survey responses ​and that used to take hours and I would go through ​and try to find themes of, you know, ​on a project I was working on annually. ​And just this past year I plugged that right into AI ​and I was given all of these key insights within seconds.  
​And so, you know, knowing that that added hours to my day ​to do more strategic things was really helpful. ​Another way I've used it even in my personal life is just ​planning my daughter's fifth birthday party. ​So same thing, you know, I could have gone out, ​gathered activity ideas, snack ideas, all these things. ​And I told AI as much as I could about the party, ​these are five year olds, this is the theme, this is ​how many people, it's a pool party. ​And AI gave suggestions all the way from activities ​and themed food and giveaways that I could give. ​And so it was amazing that it did all of that for me. ​And what would've taken a while. ​- So back to your, you know, your use of using AI ​for summarizing some of your work.  
​How do you know it's doing it correctly? ​- So I think that with that particular example, ​it's something I had done for the past five years on my own. ​And so by seeing the results, I was able ​to immediately compare ​and say, wow, that's exactly what I used to get. ​And that's what I can see in the data. ​And now that I'm getting those themes organized, I can see ​that it did it in a great way. ​I think a a quicker example is even saying, ​how can it help me draft an email? ​So maybe it's something you would've done for your team ​and you wanna send out comms if you give the ​most information. ​So this is the tone, this is the audience, this is ​what I want it to sound like.  
​This is how I want it to look. ​Add bullets or whatever that is. ​So I think that in those moments when you see ​that first draft that AI did for you, you can really say, ​wow, that was maybe even better than I would've ​done first try. ​Or I can go from there. ​So I think it just continues ​to surprise you the more that you use it. ​And then from then on, of course I start with AI ​now when I'm writing any email.  

Practice advanced summarization techniques:  

 Now that you know a few summarizing techniques, ​let's discuss some more advanced methods you can use ​to condense information with gen AI tools. ​When you ask a gen AI tool to provide a summary, ​sometimes the initial output is way too broad. ​You need a bit more detail to make it truly useful to you. ​A technique called chain ​of density prompting can help with that. ​With this method, you get increasingly concise summaries ​and end up with a chain of refined outputs.  

​Think of it this way, you're working on the perfect ​elevator pitch for your company. ​Your first draft is way too long ​and includes too many details, ​but as you refine it, it gets shorter ​and more direct, all without losing the important points you ​need to get across.  
​Eventually, you land on the perfect elevator pitch, quick, ​direct, and effective. Iterating ​on our last prompt, we want to update the task ​and format. Provide a shorter summary, ​focusing on the report's, top two to three trends, ​mission accomplished, but maybe you want it even shorter. ​  

We can get more specific with our prompt ​to ensure the output not only provides a simpler summary, ​but is also really targeted to your needs. ​Let's go shorter.  

We'll ask for a single sentence, ​condense the summary into a single sentence ​and even more specific context. ​Highlighting the most dominant trend. Nice.  
​We kept asking it to refine further and we were direct ​and specific about the desired output. ​We can repeat this process until we generate the most useful ​and helpful outputs for the task. ​We can even get ahead of these extra iteration steps ​and ask that the gen AI tool provides multiple increasingly ​short iterations in the initial prompt. ​You might be wondering why we wouldn't get ​to the shortest output right away. ​Well, iteration helps us check for hallucinations ​as we go from something super detailed to an output ​that's more direct and to the point. ​It also helps us stay informed about ​what information is being taken out ​as the outputs get shorter. ​Chain of density prompting also works ​in the other direction.  
​If the output is too short, we can also prompt ​to increase the length and add more detail. ​Remember, when I asked you to think ​of a report you haven't found the time to read, ​give these prompting techniques a try ​and discover how quickly you can generate a helpful summary.  

Summarization best practices  
Have you ever needed to extract insights from a huge document? Or maybe come across a super long email thread you’re having trouble getting the gist of? Great news: Generative AI tools are great at summarizing information and saving you time. Here's how to optimize your prompts to get more effective summaries.  

Prompt to summarize  
Gen AI tools use pattern recognition to analyze strings of text and refine them into shorter summaries. To ensure your summary contains the right information, and that it's in the right format and depth, create a strong prompt with specifics of what you need in the summary.  
Summarization best practices  
There are a few best practices to keep in mind when guiding a gen AI tool to summarize information, like lengthy documents. Here’s how to adjust the different parts of the prompting framework:  
Task: Specify which content you want the gen AI tool to summarize, such as a portion of a document or a specific sub topic. Include the desired format of the summary, such as bullet points, as well as the length and tone of the summary you want. You also want to add a persona, such as asking for the output to fit a 9th grade reading level.  
Context: You may need to add additional context about what the summary is for or why you’re creating it. This helps a gen AI tool anchor its response to something tangible.  
References: If there’s a summary that matches what you’re looking for, consider adding both the summary and the document it’s summarizing as a reference so the tool knows what approach to take.  
Evaluate: When you’re inputting large amounts of text or data, there’s a lot of information for a gen AI tool to process. This can increase the chance of misinterpretations, irrelevant chains of thought, or even hallucinations. To ensure the output is helpful and accurate, evaluate it based on the task you input. You can also cross-reference the output or run it by a subject matter expert if you have access to one.  
Iterate: If a gen AI tool doesn’t deliver a useful summary, you’ll need to iterate by asking it to adjust the format, the length, or specific details about the output that aren’t working for you. Keep iterating until you receive a summary that serves your purpose.  
Long context 101  
Gen AI tools are constantly improving, and some are now capable of handling much larger pieces of text and data in a single input. This is made possible by an increase in the token limits of gen AI tools and the use of long context windows.  
AI model and token limit  
Tokens are the fundamental building blocks of text that AI models use to process and understand language. Tokens can be as small as a single character, a part of a word, or even multiple words. When you give a gen AI tool a prompt, it breaks it down into tokens. The longer the prompt, the more tokens it needs to generate an output for it. If you were building a house out of bricks, you could think of each individual brick as a token in the building process.  
Early AI models could only process up to several thousand tokens at once, but now some models can process millions. It’s important to understand which AI model you’re using and its token limit since it varies from model to model. As developers find new ways to increase token limits, gen AI tools become more and more capable of handling larger quantities of data in a single prompt.  
Long context windows  
Long context windows allow gen AI tools to process large amounts of information, or larger amounts of tokens, in different formats at once. Using a long context window means you can share much more context and background information in your input, which allows you to complete more complex tasks that include a lot of nuanced details—like creating a multi-part marketing campaign or a thorough business plan.  
With more context and detailed information about your task, a gen AI tool can then understand and generate more comprehensive, personalized, and relevant responses. For example, with a long context window, a gen AI tool can process a lengthy PDF report with dozens of pages, graphs, and illustrations in a single input, and then generate a summary based on what you need. This saves you time by eliminating the need to manually break down text or information into smaller chunks when designing your prompt.  
Have you ever forgotten something, like what you ordered to eat last week or someone’s name in the middle of a conversation? Recalling past details can be tricky for gen AI tools, too. Long context windows help solve this by acting as a working memory for gen AI tools so they can remember what you shared earlier in the same conversation thread. Think of it like talking with someone who is already familiar with a problem you’re trying to solve versus explaining your situation to a stranger who has no context.  
Note: Most gen AI tools will only remember what you put in a long context window in the same conversation thread or prompt chain (you’ll learn about prompt chaining in more detail later in the course). In other words, if you close the window and re-open it after entering your screenplay, for example, the tool won’t recall, and you’ll need to enter your materials again before the tool can provide outputs related to it.  

Activity: Summarize and draft content with gen AI  
Scenarios  
Read through the following options, then complete the activity using the option that best suits you. Be sure to apply the TCREI prompting framework: task, context, reference, evaluate, iterate.  
Option 1: Summarize a document from your work or personal life  
Choose any long document or other text that you use at work or home that would be helpful to summarize. Think about a long email thread where you need to understand the main ideas, or a complicated memo where you need to pull out all the action items. Do you have a detailed report and only need the most important insights? (Remember, don’t use any confidential or sensitive information if you’re using a publicly accessible tool.) Or maybe you have a user manual that’s difficult to understand, and you want to know what’s causing that drip under your sink.  
Once you’ve chosen a document to summarize, you’ll have two tasks:  
Prompt a gen AI tool to identify and summarize the most important information.  
Use that summary to create an email, communicating the information to someone you know.  
To get started, you’ll need to summarize the information contained in the document you’ve chosen by pasting it right into the gen AI tool of your choice.  
Option 2: Summarize information about a clothing collection  
If you can’t think of anything you want to summarize, try using the following scenario instead:  
You own Clothing Essentials Company, a small business targeting middle-income consumers aged 18 to 39. You’re developing a new clothing collection. The Minimalist Collection is designed for young adults who identify as minimalists, trying to balance their hectic work schedules with a bustling social life. The collection is scheduled for its seasonal release next fall.  
You have two related tasks to complete:  
Prompt a gen AI tool to identify and summarize the most important information about the Minimalist Collection.  
Use that summary to create an internal email, communicating the information to your teammates.  
To get started, you’ll need to summarize the information contained in this document by pasting it right into the gen AI tool of your choice: (Note this is AI-generated content. Results are for illustrative purposes and may vary.)  
All about the Minimalist Collection  
Step 1: Prompt to summerize your information  
Consider what kind of summary you want the gen AI tool to generate. For example:  
What format do you want the summary to take?  
What length do you want the summary to be?  
What information do you want the gen AI tool to include in the summary?  
Using the TCREI framework, enter a prompt into the gen AI tool asking it to summarize the information you provided.  
Step 2: Evaluate the output  

Review the output from your initial prompt and evaluate what information may be missing or unhelpful to satisfy your summarizing goal. Consider the full context of the option you chose. For example, evaluate whether the summary:  
Condenses the information adequately  
Includes accurate information with no errors  
Communicates enough information in a clear, readable format  
Also, consider which parts of the prompting framework may have been missing from your initial prompt.  
Step 3: Take an iterative approach  
Revise and refine your prompt by adding more of the prompting framework. For example, you could:  
Use at least one part of the prompting framework that may have been missing from your initial prompt.  
Add three to four sentences of additional context.  
Break the text into chunks and paste them in one at a time, then prompt to summarize each chunk.  
Specify a persona or audience in your prompt if needed.  
Specify the style, tone, length or format of the summary, to prepare for the email you’ll create later.  
When you’re ready, enter your revised prompt. Then, continue iterating until you feel confident that the summary sufficiently condenses and highlights the right information.  
Step 4: Turn the summery into an email  
Now, prompt the gen AI tool to turn your summary into an email. Remember to use the prompting framework for this new task.  
Option 1: Summarize a document from your work or personal life  
Prompt the gen AI tool to draft an email to a friend, teammate or whoever would benefit from the summary you generated. Make sure to consider your audience and what kinds of information the email should contain, as well as your preferred tone and length.  
Option 2: Summarize information about a clothing collection  
Prompt the gen AI tool to write an internal email to communicate the summary of the Minimalist Collection to your team to generate excitement.  
Your email should contain:  
An overview of the collection.  
The main audience for the collection.  
The most important information about the collection.  
You’ll need to consider a number of questions, including:  
What are the most exciting aspects of the collection that will resonate with your team?  
How will you introduce the collection in a way that captures their attention and provides just the right amount of context?  
How will you highlight the potential impact of the collection, either on the business or in general?  
Step 5:continue iterating:  

Review the output and evaluate whether your prompt has resulted in an effective email draft. Is it engaging? Is the summary sufficiently captured? Does it satisfy your goals? Continue iterating until you're confident that the output better satisfies your goal.  
Pro Tip: Repurpose the email for a new audience  
Did you know that you can use the email you just created as the starting point for a new prompt? Try prompting the gen AI tool to repurpose the email you just drafted into a new format. For example:  
Rewrite the email with a more serious tone for upper management.  
Create a sales pitch out of the email for new investors or consumers.  
Adapt the email to include technical documentation for an expert audience.  
If you’re using Option 2: Summarize information about a clothing collection, try creating a press release that includes the following features:  
Headline  
Introduction  
Statistics and facts  
Company information  
Note that the gen AI tool will likely produce something generic, without any of the necessary context or story elements that a member of the press might require. Some approaches that might help the gen AI tool include:  
Prompting the gen AI tool to change the style and tone for the press release.  
Providing feedback to the gen AI tool on what’s missing from the press release.  
Providing the gen AI tool example press releases to reference.  
My answer:  
Prompt for summerize:  
as a school prenciple , summerize this document which is for my daughter's school, and outliers the main information that i have to know with a relative action that i have to do in the table , the table contain day, due to, duty and if there is link that i have to use let me know. use exactly writing that they wrote  

Prompt for email to mojtaba about school:  
as a  mother who is concern about deadline, give me an email text and summerize af all importantn task that she has to do , send an email to her husband, with funny format and at the same time serius , that be attractive email for husband  a. her name is razie and husband name is mojtaba  

3- Speed Up Data Analysis and Presentation Building  

Find and present insights with AI  
Remember that time your team launched a new product ​and sales went up in a specific region, ​or when a simple survey revealed an untapped customer need. ​Those weren't just numbers on a spreadsheet. ​They were stories that led ​to valuable insights when organized ​and analyzed. The problem, you may not always have the time ​to track those stories down. ​Generative AI tools can help you manage, analyze, visualize, ​and present data. ​In this module, you'll first learn how ​to prompt gen AI tools to uncover insights from data. ​Then you'll bring that data to life with visualizations, ​and finally, you'll explore how ​to put it all together into a compelling presentation ​that helps you show and tell your story.  

Use AI to uncover hidden patterns in data  

Data can teach you a lot, ​but you need to know how to interpret it first. ​Let's use the prompting framework thoughtfully, create, ​really, excellent, inputs to unlock insights ​and patterns from data using a gen AI tool. ​Before we get started, remember ​that not all gen AI tools work with data. ​Be sure to check what your tool can do before using it. ​We'll teach you how to do this ​by prompting Gemini models in Google AI Studio. ​  

One other note, as you work with these tools, remember some ​of the ground rules about using gen AI responsibly. ​Always review your organization's policies ​before including sensitive ​or confidential data in your prompt.  
​For this example, ​we're using publicly available data found on Kaggle. ​Are you ready to try?  

Let's do it. ​Here we have a data set ​with information about a grocery chain.  

 ​AI Studio can help us analyze all that data to find trends ​and patterns that could help inform ​how the company operates, ​but there are a lot of variables here, so it'll be helpful ​to organize the data to make it easier to work with. ​First, we'll ask for step-by-step help, ​we can upload the data directly from our Google Drive ​where the Google Sheet is stored. ​If we were using Microsoft Excel, ​we'd upload it from our computer.  

​Once we've uploaded the spreadsheet, ​we're ready to write the prompt. ​  

Attached is a Google sheet of store data. ​Now that we've shared some context, ​we'll add the specific task. ​How can I create a new column in ​sheets that calculates the average sales per customer ​for each store? ​Let's review the output. ​The model provided some helpful suggestions ​for calculating the average sales per ​customer for each store. ​It even explained how to use a more descriptive formula ​to label our new column in the spreadsheet, ​and that's just one example.  

​If that method of organization doesn't work, ​we can iterate on our prompt to get an output ​that's closer to what we need. ​Let's take this further. ​Discovering trends in a data set can help us make informed ​decisions and we can prompt a gen AI tool ​to help find those trends. ​Can you think of a spreadsheet ​that you've been meaning to analyze? ​Keep that in mind as we go through this example. ​Start again with the task. ​Give me insights into the relationship ​between daily customer count items, ​available and sales ​based on the given data.  

​That prompt got us a lot of interesting information ​and fast, and this is fascinating. ​There seems to be no clear correlation between the number ​of items in a given store and its total sales volume. ​Some small stores are even outpacing the big ones. ​The output even gives us some potential reasons ​behind this trend so we can investigate further ​and think about potential sales strategies. ​This is great. Now, back to that spreadsheet, ​we've been meaning to analyze ​how can gen AI help us save time ​and extract meaningful insights. ​With the help of gen AI tools, we no longer have ​to spend hours crunching data.  
​We can do it with just a few prompts.  

AI IRL: Accelerate analytical tasks with AI by your side  
So Tris, it sounds like you've seen ​so many different aspects of AI over the years. ​What are some of the AHAs you've discovered? ​Well, I think one of the best parts about using AI ​for code data analysis ​or other analytical tasks is you don't have ​to know everything. Right. ​I think 20 years ago, if you went to college ​and you learned business skills, you had ​to learn about managing spreadsheets, et cetera. ​Now our relationship with data is getting much deeper. ​There's much more data around, ​and you don't need to know the magic words, ​the magic formulas, the scripting, the, the Python language.  
​You don't need to know R. Yep. ​In fact, most language models now can take something ​that would've been completely impossible for most people ​who are not already computer science experts ​and puts it directly within their grasp, you know? ​Yep. You want to take a spreadsheet of all sales ​for the last month ​and you wanna write something ​that will update a running tally of the forecast ​for the next month, or something along those lines. ​You can actually, in four ​or five, six turns, probably find a library ​that is designed to do exactly that data analysis, ​to do exactly that projection, ​and it can look at rows that come in on this spreadsheet, ​update your sales forecast, ​and just make your life a lot easier. ​So one thing is bringing you new ideas and new concepts.  
​That would've been something you would've had ​to spend hours learning. Right. ​And reducing that learning cycle. ​So rather than spending five hours to learn how ​to do this thing or, or just giving up instead, ​maybe it's two minutes ​and I have a basic implementation working. ​I think that's awesome.  

Strategies for data analysis  
Have a dataset you’ve always wanted to explore? Lots of numbers you need to make sense of? In seconds, generative AI can help you spot patterns, notice connections between data points, and identify trends, all of which can empower you to make data-backed decisions with confidence.  
All it takes is the right prompt. Writing a prompt to analyze a dataset can come with some quirks. But one thing to keep in mind throughout this reading is that the trusty prompting framework will guide you. That means you’ll Thoughtfully Create Really Excellent Inputs, only this time, you’ll tweak your strategies slightly to make them more dataset-friendly. Here are a few prompting strategies to help you get the most out of your data. And remember—always review your company’s policies before including sensitive or confidential data in your prompts.  

Shape your prompt to the model’s abilities  
When it comes to using gen AI tools to analyze your data, your prompts need to account for the strengths and limitations of the technology you are using. Understanding what sort of data analysis a gen AI tool is good at will help you tailor your prompts and get the most from your outputs.  
Here are a few examples:  
Text analysis: Easily surface themes, determine tone, and classify key topics in text-based data. Have a few thousand open-ended responses from a community survey? Gen AI can help you quickly understand what’s most important to people, how they feel about the town’s proposed plans, and where the final initiative should make an impact.  
Data augmentation: Expand a limited dataset with simulated data to make it more robust. Say you work in fraud prevention. You want to analyze your company’s data about fraudulent purchases, but there are only a handful of data points. You can prompt a gen AI tool to generate new data from your current dataset to get a more comprehensive view of how fraud might happen and what to look out for. The key with data augmentation is to be transparent about what's real and what's augmented data, and the augmentation should be as realistic as possible. Augmentation can’t give you hard facts, only suggest trends. Like with the other data uses, you should always check your organization's policies.  
Question and answering: Get answers about your data in plain language, like whether your sales from last quarter were up or down. It’s like checking in with your colleague who compiled the information—just with fewer emails.  
Scenario analysis: By noticing patterns in past data, gen AI tools can make educated guesses about what might happen in the future. That means you can play out different scenarios to check what kind of impact they might have, like prompting to ask how a change in traffic patterns would impact your commuting time, or which days of the week your office space should expect the highest number of visitors.  
Image and visual analysis: Gen AI can help you quickly identify patterns and come to conclusions about your visual data without having to sift through stacks of images or watch hours of footage. You could even paste in a chart displaying your team’s sales figures for the past two years in your prompt, and ask questions about it for more focused analysis.  
Customer and market research: A gen AI tool can analyze surveys, social media, and other industry-specific data like charts and graphs to uncover what customers want and how your market is changing.  
If you’re eager to use gen AI tools, but need to complete a data analysis task they’re not really built for—like rigorous statistical analysis, or really anything with highly structured data—don’t worry. You’ll just need to adapt how you prompt the tech to best suit its capabilities. For example, instead of having the gen AI tool do statistical analysis for you, ask it to suggest the most effective methods based on your data with step-by-step instructions. Even if you’re not a coding expert, you can use gen AI to help you learn about different analysis methods quicker than if you were learning on your own. Designing your data analysis prompts to align with the limitations of gen AI doesn’t have to restrict your work. Keeping the tech adaptable to and useful for your needs can open doors to unexpected creativity.  
P.S. Since we’re discussing the limitations of AI, now’s a good time to remind you about hallucinations. If you’re following our prompting framework, you’ll be evaluating outputs as you go. But keep in mind that spot checking doesn’t really work for datasets—out of 100 generated data points, only 10 might be hallucinations. So keep a close watch on your outputs, and try to only generate information that can be easily cross-referenced.  

Get your dataset ready  
An output is only ever as good as the data it’s based on. That means you need to validate your data and continually check the information you’re analyzing with gen AI.  

Luckily, gen AI tools can help you get your dataset prepared and ready. Try using a gen AI tool to identify errors, spot strange-looking data points, and standardize how things are formatted.  
For example, maybe you want to figure out if your dataset is inaccurate. Here’s a prompt for that:  
Here's a sample of my data. Identify any potential issues or inconsistencies in the data, and suggest ways that I can address them.  
Cleaning up your data before conducting further data analysis is also a good example of how you might use multiple different tools to investigate one single dataset. For example, you could use one gen AI tool to convert a dataset’s format, then another to ask questions about the newly organized information. Regardless, preparing a quality dataset is an important first step in conducting all kinds of data analysis, so make sure your information is updated, clear, and complete.  
Encourage exploration  
Gen AI is really good at uncovering insights that may be hiding within a large dataset. You just need to know how to prompt the tool the right way.  
You want to ask broad, open-ended questions. By not being prescriptive, you’re giving the gen AI tool a chance to identify patterns and detect insights with some freedom, which may introduce or reveal trends you weren’t expecting. Above all, stay curious. You might find something unexpected just by keeping your perspective open.  
For example, you’re a journalist conducting research for an article about the real estate market. You’ve been provided with a large dataset showing vacant residential properties by district in a handful of cities, but you’re not sure what conclusions can be drawn from it. You might write:  
You’re a journalist investigating housing trends. How would you use this vacant property data to tell a compelling story about the real estate market?  
As always, follow the prompting framework to evaluate your output for credibility and accuracy.  
Take advantage of embedded AI tools  
Plenty of existing data analysis platforms embed AI right into their user interface, making it even more convenient for you to analyze information. You might already work in these platforms, or at least have some familiarity with them. But even if not, these integrations make analyzing your data a seamless process by bridging the power of AI and specialized data analysis systems, like in the following platforms:  
Gemini in Google Sheets: Create tables, establish formulas, and summarize Drive files or Gmail messages to organize and analyze your data directly in your spreadsheet.  
Tableau Pulse: Receive personalized, automated insights about your data as snapshots on the Tableau Cloud platform, or regular digests sent through Slack or email.  
Looker Studio: Access a robust library of report templates, easily explore underlying data through prebuilt data connectors, and embed final reports into any web page or intranet to share your findings with the audience that needs them most.  
BigQuery data insights: Uncover patterns, assess data quality, and perform statistical analysis by generating automated queries based on your information’s metadata.  
When you’re preparing to analyze your data, determine whether you can use embedded AI tools to help. When it comes to prompting in these platforms, remember to follow the prompting framework to get the most out of your output. For example, maybe you’ve saved that vacant property dataset in Google Sheets. You can open the side panel and type:  
Create a table that includes the median rate of vacancy for each city in the dataset.  
The next time you’re working with a dataset, remember you’ve got a powerful assistant in gen AI tools. By crafting the right prompts for the right tools, keeping your data tidy, asking broad questions about your information, and taking advantage of all kinds of tools, you’ll find stories and insights that might have otherwise stayed buried. Who knows what you’ll uncover next.  


## Practice Assignment

Activity: Extract data insights with gen AI  
AI tool access  
To complete this activity, you’ll need to use a gen AI tool that is capable of analyzing common dataset formats (e.g. .csv, .tsv, and .json files). Depending on how large your dataset is, you might also need a gen AI tool with a long context window, which allows for the processing of a large amount of information in different formats at once.  
The following steps feature Google AI Studio, which you can access by going to aistudio.google.com. However, you can also complete the steps by using a different gen AI tool of your choice, such as Claude, ChatGPT, or Microsoft Copilot. Remember, gen AI technology is dynamic and ever-changing, so always double check what features and capabilities are available in the tools you’re using.  
Note: Different Gemini models are available in AI Studio which can handle different amounts of data.  
Scenarios  
Read through the following options, then complete the activity using the option that best suits you. Be sure to apply the TCREI prompting framework: task, context, reference, evaluate, iterate.  
Option 1: Get data insights from your work or personal life  
Find a dataset, like a spreadsheet, from your work or personal life. For example, you could use social media platform data to identify what topics are trending. Maybe you have anonymous customer feedback and you’d like to uncover common themes. If you’re working in scientific research, you could gather experiment data and compare the success of your lab work over time. Or here’s a fun idea: compare information about different areas of your town to make decisions about where to shop or what kinds of transportation to use.  
If you decide to use data from your work or personal life, remember to avoid entering any sensitive information that you wouldn’t want a tool reviewer to have access to, or information you wouldn’t want an organization to use to improve their products or services. If you’re using a dataset from work, make sure to review your organization’s policies about whether you can use gen AI tools and how to do so before including data in your prompt, or check if your organization has an enterprise version of a gen AI tool that is okay for other types of use.  
If you’re having trouble finding a dataset you feel comfortable analyzing, use publicly available data from Dataset Search, Kaggle, Statista, or a government statistics agency’s website like this one: US Census Bureau.  
Once you’ve found a dataset, you’ll prompt a gen AI tool to extract insights from your data, examining it closely to discover patterns or spark insights. It’s important to provide the necessary context of what you want to know in your prompt so the gen AI tool can process what it needs to analyze and why. You may also want to specify the particular format you want your output in.  
Option 2: Get data insights from customer reviews  
If you can’t find a dataset, try using the following scenario and dataset instead:  
You own Clothing Essentials Company, a small business targeting middle-income consumers aged 18 to 39. You recently launched a new clothing line, the Minimalist Collection. For the last couple of months, you’ve been gathering customer reviews of the Minimalist Collection in a spreadsheet. You decide to use gen AI to extract insights about key product reviews to help you make informed decisions about your business moving forward.  
Here is the dataset of reviews: (Note these are AI-generated reviews. Results are for illustrative purposes and may vary.)  
Minimalist Collection customer reviews  
Step 1: Prompt to get insights from data  
Whichever option you chose, upload the dataset you’re using and enter an initial prompt into the gen AI tool to extract important insights from the data. Remember the prompting framework, and think about the information and the format you want to receive. Consider the following questions as you write your prompt:  
What compelling questions can the data help you answer? For example, could this data inform future decisions of some kind?  
What kinds of trends or patterns are you looking for in the data? Why might they be useful?  
What specific detail can you provide to sharpen the gen AI tool’s output? For example, consider constraints you can provide in your prompt, like asking the tool to only focus on a specific type of data or to only compare certain columns or rows.  
Gen AI tools are always changing, and so are their global availability and language options. If the tool you’re using is not generating a helpful output, you can try a different tool, such as Claude, ChatGPT, or Microsoft Copilot. Or, adjust your initial prompt, and try again.  
My prompt  
as a data analyst , I want to analyst , this data, and understand the keys insight of this data, first of all descripe what important data there is?then give me the review of customer and categorise their opinion and then give me summerizebase on categorize and then how can i make better decision for future to improve my business, as a refrence use this sheet. give me the result in table and add to another sheet of this document  
update my prompt and add what another analyse must i have to consider  to help business improve?  

Step 2: Evaluate the output  
Review the output from your initial prompt and evaluate what information may be missing or unhelpful to extract important insights from the data. Consider the full context of the option you chose. For example, evaluate whether the output contains:  
Accurate and clear direction about key points in the data  
Intriguing insights that make you want to find out more  
Explanations of trends or patterns in the data  
Enough context about what the insights mean to be helpful to you  
Also, consider which parts of the prompting framework may have been missing from your initial prompt.  
Step 3: Take an iterative approach  
Revise and refine your prompt by adding more of the prompting framework. For example, you could:  
Add more context about your data, like what it’s for and what kinds of insights you want.  
Specify columns and rows in the dataset to compare.  
Ask the gen AI tool to provide more detailed explanations of its findings.  
When you’re ready, enter your revised prompt. Then, continue iterating until you feel confident that the gen AI tool is generating interesting and important insights about the data.  

Decipher spreadsheets:  
I am a spreadsheet nerd, ​but I also know that not everyone shares my passion ​for cells and formulas. ​Dense spreadsheets and complex formulas can be intimidating, ​but fear not generative AI ​can help you understand and write spreadsheet formulas. ​Just prompt it using natural language. ​You already know how to prompt a gen AI tool ​to help you create and understand text, images, ​and data points, ​but it can also help you better understand ​spreadsheet formulas.  
 ​Let's put the framework into action.  

 ​Imagine your coworker at a restaurant went on vacation ​and gave you a spreadsheet full of data and formulas. ​Some of them seem familiar, ​but there are others that are a little more complicated.  
​You need to order inventory today, ​but you don't wanna bother your colleague, so you turn ​to Gemini for some guidance. ​We'll start off with the persona and some background.  
 ​I work at a large restaurant ​and I need ​to order inventory while my coworker is ​on leave. ​Then add in some context. ​They left me with a formula to calculate ​how much food to order, but I don't understand it.  

 ​Here's where we'll paste in the formula, ​and let's give Gemini the task and desired format. ​Explain ​what the formula means in simple ​step-by-step terms.  

​That's much easier to understand. ​You now hopefully have a clear sense of ​what the formula is trying to accomplish so that you can get ​that stock order handled quickly. ​Now that you understand the formulas, you can figure out ​what to do if you get stuck. ​Let's try another one.  

 Have you ever received an error ​message in your spreadsheet and not known what to do? ​Let's prompt Gemini to learn how you can figure out ​where those errors are coming from.  
​The Google sheet I have uses this formula ​to calculate orders.  
​I'll paste in the formula. ​However, I received an error message in one ​of the cells. Time to specify the task ​and what format we want. ​Give me a step-by-step process ​for finding the error ​and fixing it in Google Sheets.  

 ​And there you have it, clear instructions for resolving ​that pesky error message. ​And with those out of the way, you can get ​that inventory order moving.  

Decipher almost anything with the help of AI  
Want to learn faster or more effectively? No matter what your job is, chances are you've come across information that you didn't understand. Or maybe you had the answers you needed, but they were hidden behind dense jargon, unknown formats, or even new languages. Luckily, generative AI can act as your personal translator and help make the unfamiliar more accessible.  
Below are a few ways you can use a gen AI tool to deepen your understanding of something you might be struggling with. (Keep in mind that the example prompts below are only highlighting the task from the prompting framework to show you specific ways to decipher content with gen AI.)  

Translate to another language  
Working with clients who speak a different language? Or curious about an unfamiliar word you heard on a podcast? Gen AI tools are capable of simple translations and more, so you can use them whether you need a word-for-word conversion or something more nuanced and idiomatic. You can prompt them to:  
Translate text: Translate this email to Spanish…  
Provide definitions: What does “hygge” mean in English?…  
Explain idioms and figures of speech: Explain the phrase “saru mo ki kara ochiru…”  
Interpret jargon  
Whether your company is adopting a new software or you’ve come across some unfamiliar industry lingo, a gen AI tool can break down jargon so even the most complex or new-to-you concepts are understandable. Try prompting a tool to:  
Define terms: What is compound interest in simple terms? …  
Explain concepts: Explain what social-emotional learning (SEL) is in one paragraph …  
Provide contextual examples: Can you give five examples of how natural language processing (NLP) is used in everyday life? ...  
Demystify spreadsheets  
Have you ever received a dense spreadsheet with hundreds of cells, complicated formulas, and numerous tabs? What about one that’s full of errors? Whether you’re a novice or a spreadsheet wiz, these files can be complex. The good news is that if you input the spreadsheet into a gen AI tool or prompt Gemini in Google Sheets, gen AI can help you understand it. Next time you’re stuck or just want some help, prompt a tool to:  
Explain formulas: Explain the formula in cell B12 in three sentences ...  
Identify errors: Are there any inconsistencies in this data? If so, share them in bullet format ...  
Extract specific data: What were the total Q3 sales for our hair gel versus our shampoo? Provide them in percentages, as well as dollar values ...  
Summarize key findings: Write a one-paragraph summary of the trends in this spreadsheet of monthly website traffic ...  
Understand error messages  
Have you ever received an unfamiliar error message on one of your devices that you needed to understand quickly? A gen AI tool can help you decode it, and find solutions fast, so you can get back on track. Next time you get an error message, try prompting a tool to:  
Explain the error: What does “Error 404: Not Found” mean? ...  
Troubleshoot the problem: My computer says “Kernel Panic.” How can I fix this? ...  
Identify potential causes: Why am I getting a “Connection timed out” error message in my browser? ...  
Get help with coding  
If you’re just starting out with coding or need to get familiar with specific languages for things like web development or data analysis, a gen AI tool can act as a coding assistant. Some tools like Google Colaboratory (Colab), Gemini Code Assist, and Vertex AI Codey are designed with coding in mind, and can help you do things like generate code or identify functions and bugs.  
Remember that it may be difficult to evaluate a coding output if you’re just starting out with code. You may need some extra research or expertise to check for hallucinations in the results. After you’ve entered the code into your input, try prompting the gen AI tool to:  
Explain code snippets: What does this Python code do? Explain it so a true beginner could understand ...  
Generate code: Write an R program that finds the common information between two input lists ...  
Debug code: This JavaScript function is supposed to calculate the area of a rectangle, but it's returning the wrong answer. Can you find the error and tell me how to fix it? ...  
Explain complex data  
If you’ve ever looked at a chart or graph and had trouble finding an insightful data point, a gen AI tool can provide assistance if you prompt it to:  
Summarize trends: What are the main trends shown in this line graph? Provide one-sentence explanations of each ...  
Identify outliers: Are there any unusual data points in this scatter plot? ...  
Explain correlations: Does this bar chart show a correlation between advertising spend and sales? ...  
Beyond interpreting charts and graphs, gen AI tools can also help you create your own—but more on that later.  
Gen AI tools can help you explore new ideas, solve problems more effectively and quickly, and ultimately, learn and grow with the knowledge you’ve gained.  
One final note: Always remember to evaluate outputs when you’re using gen AI to find answers about topics that are new to you. When you’re asking questions about unfamiliar concepts, or working with new languages, you need to be even more discerning with the outputs.  
Bring data to life with visualizations:  
Does your job involve presenting ​information to different people? ​Maybe you need to pitch new potential clients ​or relay information to your colleagues ​or your organization's leadership. ​When it comes to presenting data you want ​to show rather than tell. ​Thankfully, generative AI tools are really good at helping ​you determine the best ways to visualize data. ​You just need to know what to ask for. ​You can prompt a gen AI tool to get advice on the best types ​of charts and graphs to illustrate your data. ​The prompting framework should still be your guide.  

​Add your task, context, and references if needed. ​Evaluate the output and iterate. ​The clearer you are about the kind of chart you want ​and what the parameters are, ​the more useful your output will be.  

 ​Consider this:  
 You and I are co-owners of a bookstore. ​Here we have a list of best-selling books ​and how many copies have been sold ​around the world since they've been published.  

​Before we choose to stock some of those titles, ​let's examine the data. ​Remember, not all gen AI tools can analyze data.  
​Be sure to check what your tool can do before using it. ​For this example, we'll use Google AI Studio. ​First, let's think through how ​to represent this data visually with a chart. ​If you don't know what type of chart to use, ​you can always prompt a gen AI tool for suggestions. ​We'll prompt the model using plain language ​to describe the data set in order to find out what kind ​of chart might work best. ​Describe the data set here. This is our context: ​My data set is a spreadsheet ​that uses the following columns: ​Title, Published, ​Genre, First published, ​and Approximate sales in ​millions.  
​Now let's request the format to be a chart ​so we have some choices. ​Give me options for a chart ​that shows the correlation between genre ​and sales. ​Let's be even more specific so that we know what kind ​of correlation the chart will actually be displaying. ​Explain how genre ​and sales are correlated according ​to the information.  

​Interesting. Now we have three great ideas ​for creating charts ​that will visualize the data clearly.  

Even better ​we have detailed explanations about each chart giving us the ​option to choose which visualization works ​best for our dataset.  
​You're not always gonna know what type of chart you want ​to use, which is where adding a reference ​to your prompt can be helpful. ​You can use charts that are similar to what you want ​or charts you found helpful, ​and include those as a reference in your prompt. ​Then ask for recommendations on how ​to create a similar chart using your data, ​we'll find a chart to reference ​and prompt the model to emulate it using data from our ​bookstore scenario.  

 ​Start by uploading the sample chart ​and then prompt the model ​to get some information about what it's depicting. ​Remember, it's sometimes better to start simple ​and then gradually add complexity.  
​Describe this chart, what kind ​of data relationships are highlighted in the chart. ​We're asking for a description of the chart ​before we prompt to recreate it, just so ​that we can take it step-by-step.  

​Okay.  

 We have some good intel about the chart. ​The model is telling us it's called a stacked bar chart ​and that it represents the staffing breakdown across ​different departments in an organization, ​and it analyzed the data telling us ​how the finance department has a high proportion ​of full-time staff while the product department has a ​more even mix. ​Now, we'll enter a prompt about the data we already have ​and ask for recommendations on visualizing it in the same ​way as the chart we referenced. ​You guessed it. Let's add some context.  

​My data set is a spreadsheet ​that uses the following columns: Title, ​Published, Genre, First published ​and Approximate Sales in millions.  
​I am interested in showing the relationship between genre ​and sales. And the task. ​Suggest modifications ​to make this chart work better ​with my specific data using Google Sheets.  

​Amazing.  

 Now we have instructions about how ​to create a new chart with our data. ​The output even explains how to modify a bar ​to illustrate the relationship between genre ​and sales more clearly. ​And remember, if your output doesn't match what you need, ​you can always tweak your prompt and iterate.  

Get a head start on presentation speaker notes  

​- Communication goes way ​beyond sharing information with someone. ​You need to tell a story. ​Stories are ​how you make information stick in people's minds. ​Generative AI tools can help: ​organize your presentations into compelling stories, ​build talking points, ​and even create images to keep your audience engaged. ​We'll use Gemini to bring it all together.  

 ​In this scenario, you work for a company that designs, makes ​and sells headphones. ​You're preparing to pitch your team on some cool ​new features.  
​There's a lot of information ​and insights to convey, so you'll need to distill ​what you learned into a clear presentation.  

​First, let's prompt Gemini to help figure out how ​to structure the presentation and summarize the findings.  

 ​Let's add in the persona. ​I am a product designer at a headphones brand. ​Now here's where we'll paste in the context. ​Now, here's the task. ​How should I structure my presentation?  
​And don't forget to specify the format. ​List each slide's topic with its key points ​and visuals.  

​Yeah, nice.  

​Gemini has suggested a structure for your presentation ​that includes key points ​and visuals for each slide, including a title slide, ​an intro that sets the stage ​and details on the three features ​that the audience is interested in.  

 ​Gemini even suggested a call ​to action at the end of the presentation. ​It's good advice. There are a few other things ​that you can do to make it more engaging, ​like adding visuals ​that compliment the information on the slides.  
​When using gen AI for image generation, you want ​to use the prompting framework ​with a few additional things added in. ​You want your input prompt to be as vivid ​and detailed as possible ​to help the Gen AI tool determine the type ​of image you want to create. ​Now, this means specifying the size, color, ​and position of things in the image ​and the overall aesthetic we want. ​  

So first, we'll specify our task and format. ​Start with the task, generate close-up images ​of a pair of sleek silver headphones ​and add in some more context on a desk in a ​college dorm room. ​They should have musical notes floating ​around the headphones to show that they're playing music.  

 ​Yeah, so cool. Gemini created several images to choose from.  

​You can even choose between photography, vector art, ​sketches, or watercolors for the style. ​You still want to evaluate the output just like you would ​when generating text. ​Check your images to make sure you're getting what you want ​and that there aren't any mistakes, like a headphone cord ​that's not plugged in or anything else that seems off.  

​And remember, part ​of being a responsible gen AI user is disclosing when ​you've used these tools. ​So add a disclaimer ​whenever you're including an AI-generated image in your ​work.  

Receive instant feedback on a presentation  
​- You've now created your presentation, ​but there's still one thing left to do, present your work. ​But you don't wanna just read off your slides. ​ . ​You wanna give your audience helpful context ​and commentary as you go through them. ​You could go through your whole deck ​and draft up some talking points yourself, ​but starting from scratch will take a lot of time. ​Instead, you can prompt a generative AI tool ​to give you a headstart and generate speaker notes for you. ​For this example, we need a long context window. ​Remember, long context windows aren't available on ​every AI tool.  
​Different tools have different capacities. ​For this example, we'll switch to Google AI Studio. ​Let's upload our slide with the prompt.  

​First, we'll add the persona and context. ​I'm a product designer at a ​headphones brand. ​Here's where we'll paste in the context. ​Then we'll give some more direction on tone ​and specify the format.  
​Provide multiple options of concise, ​personable, and engaging speaker notes ​I can use while presenting this slide. ​Okay,  

you got some great ideas.  

 ​The suggested speaker notes have some personality ​and energy, which will help keep your audience engaged, ​but you can get more specific. ​You learn that your company's marketing director will ​attend the presentation. ​  

You can prompt the model to adjust the speaker notes ​for a more senior audience. ​Let's give it a try. Although this time we'll use voice ​to prompt just to save time.  

 Provide alternate speaker notes ​for this slide that are specifically directed toward my ​headphone company's marketing director. ​The director values precision ​and their priorities for the organization are to stay on top ​of industry trends ​and foster a strong community of loyal customers.  

 ​And just like that, you have new speaker notes ​that are more appropriate for a marketing director. ​Now, one last thing. ​You have the presentation and the speaker notes, ​but you wanna fit in some practice before the big day. ​You can upload a recording of yourself ​to get specialized feedback. ​Let's start off by specifying the tone ​and what we want to accomplish.  
 ​I am giving a presentation to my manager, ​pitching new product features, ​and I want to sound ​authoritative and confident.  
​Then we'll explain what you're going to do and the task. ​I'm going to read my presentation aloud, afterward ​give me feedback on whether I've accomplished this goal.  

 ​This was really helpful. ​You got a list of things to remember ​to deliver a great presentation, ​but you also got specific examples of ​where you can work on pacing and tone. ​  

Since you're using a gen AI tool with a long context window ​or large memory, you can save your prompt ​and come back to where you left off. ​You can continue practicing without starting all over again.  

AI IRL: Explore the capabilities and limitations of AI:  

​- So how would you explain a modern language model? ​What should people know about what these things are great at ​and what they're not so good at? ​- That's a really interesting question ​because language models can be great at many things. ​They can be adapted in many ways. ​And one of the most inspiring things about working on ​research and models is that we've seen tons ​of applications in planning, in games. ​Things that I would never have predicted being possible ​for a language model are being adapted ​and done now. For actual practical usage, ​I think anything that requires you to go back ​and do a little bit of hard thinking behind the scenes ​and then synthesize that into a new idea ​and then put that result into an answer. ​Those are typically things that are really hard ​for language models.  
​If you would have to, you know, ​write out the math problem on a piece of paper, ​then almost certainly a language model is not ideally suited ​to solving that problem unless you have it ​really write out that problem in full ​and think through it entirely. ​And so that's the origin of chain of thought reasoning, ​which you'll learn more about in this course.  

Fine-tune gen AI outputs by adjusting tool settings  
Have you ever noticed that the same prompt can produce different results? That’s because generative AI tools use a mix of learned patterns and probability to decide what to say next. It’s a bit like rolling dice to choose a word, but what if you could influence that dice roll?  
Some tools, like Google AI Studio, provide you with a control panel that allows you to adjust these settings, often called sampling parameters. Think of them as the guardrails that guide the AI's word choices. Knowing when and how to fine-tune these settings can help you generate better, more tailored results. In this reading, you'll learn about the three main parameters you'll encounter when using gen AI: temperature, top-k, and top-p.  

Temperature  
Temperature is the most common and impactful setting on your control panel. Think of it as the AI's creativity dial:  
Dialing up the temperature produces more creative and unexpected responses. This is perfect for artistic tasks like brainstorming ideas or writing a short story.  
Dialing down the temperature produces more predictable and consistent output. This is useful for tasks that require accurate, factual responses, like summarizing a report or generating a timeline.  
For example, imagine prompting an AI with the start of a sentence: “This morning, I went to the…” The AI must now decide on the next word that best completes the sentence. Based on its training, it creates a ranked list of the most likely options, each with a probability score:  

Temperature directly influences how the AI uses these probability scores. As the illustration shows, a low temperature setting makes the AI conservative, making it pick the highest-scoring, most obvious word—in this case, "grocery store." In contrast, a high temperature setting encourages the AI to take risks, giving lower-scoring, more unexpected words like “haunted house” or “moon” a chance to be selected.  
Fine-tuning with top-p and top-k  
While temperature acts as the main creativity dial, two other settings help you fine-tune the pool of words the AI tool can choose from: top-k and top-p.  
Think of them as focus dials. They work by creating a smaller, more relevant list of potential words before the temperature setting makes its creative choice.  
Top-k sets a fixed number of words the tool can choose from. For example, setting top-k to 10 instructs the tool to choose a word only from the top 10 most likely options on its list.  
Top-p sets a dynamic number of words the tool can choose from. It instructs the tool to automatically shrink or grow its list of options based on how predictable the next word is. For example, setting a high top-p (e.g., p=0.9) acts as a quality filter, instructing the tool to consider only the most probable choices.  
For most use cases, top-p is the recommended setting to adjust because it will adapt to the context of the situation. The key difference to remember is that top-k uses a fixed-size list of choices, while top-p uses a flexible-size list.  
Pro tip: When using top-p, it is best practice to leave top-k at its default setting.  
Recipes for Success  
Knowing what each setting does is helpful, but using them together can be very useful. Here are two common recipes for success.  
Recipe 1: Focused Analysis  
Task: Generate answers that are factual, consistent, and predictable.  
Use Cases: Summarizing reports, extracting data insights, writing technical documentation, or generating code.  
Settings:  
Temperature: Low (e.g., 0.1 to 0.4)  
Top-k or Top-p: Leave at default, as the low temperature already makes the output very focused.  
Recipe 2: Creative Brainstorming  
Task: Generate surprising, diverse, or innovative output.  
Use Cases: Brainstorming new ideas, drafting marketing materials, or writing fictional stories.  
Settings:  
Temperature: High (e.g., 0.8 to 1.0)  
Top-k or Top-p: A high value (like 0.95 for top-p) can be helpful here to give the AI tool creative freedom while still filtering out irrelevant options.  
Note: With all three settings, a high score can spark surprising insights, but they also increase the chances of generating inaccurate information, or hallucinations. Remember to always review and fact-check the output, especially when using creative configurations.  
A great prompt is just the starting point—not the destination. The key is to find the right balance between creative and predictable answers. Temperature is your creativity dial, while top-p and top-k help you keep that creativity focused. By learning to use these simple controls, you can go beyond great prompting to generate better results for any task.  

AI Model Settings – Quick Reference Chart  
Setting  
Brief Explanation  
Recommended Value  
Example  
Dialing down the temperature  
Controls how creative or predictable the AI's responses are.  
Low: 0.1–0.4  
Summarizing a financial report accurately  
Dialing up the temperature  
Higher values encourage more varied and unexpected responses.  
High: 0.8–1.0  
Brainstorming creative marketing slogans  
Top-k  
Limits the AI's choices to the k most likely next tokens.  
10  
Top-k = 10 means the AI considers only the 10 most likely next tokens.  
Top-p  
Selects the smallest group of likely tokens whose combined probability reaches p.  
0.9  
Top-p = 0.9 considers tokens covering approximately 90% of the probability distribution.  

Recommended Settings by Task  
Task  
Temperature  
Top-p  
Top-k  
Data Analysis  
0.1–0.3  
Default  
Default  
Report Summarization  
0.2–0.4  
Default  
Default  
Coding  
0.1–0.3  
Default  
Default  
Business Emails  
0.3–0.5  
Default  
Default  
Marketing Content  
0.7–0.9  
0.9–0.95  
Default  
Creative Brainstorming  
0.8–1.0  
0.95  
Default  
Story Writing  
0.8–1.0  
0.95  
Default  

Key takeaway:  
Temperature: How creative should the response be?  
Top-k: How many possible next tokens can the AI consider?  
Top-p: How much cumulative probability should the candidate tokens cover?  
Note: These are illustrative starting values, not universal rules. Not every AI model supports all three settings, and low temperature does not guarantee factual accuracy.  


## 4 - Use AI as a Creative or Expert Partner


 So I'm a researcher, which means that sometimes I have ​to deal with these hefty grant proposals that match my area ​of expertise, and not only that, I have to go out ​and find grants that I can apply for, which is in ​of itself its own headache. ​Something I've been doing is uploading my profile ​as a researcher to a generative AI tool, ​and using it to find potential grants. ​I'll add my resume, my published work, my cv, ​and then use different prompt techniques to search ​for grant programs that match my background. ​It's especially helpful ​because so many places have specific rules ​of requirements about who they're giving grants to. ​Using generative AI has taken a lot of the guesswork out of ​that process for me. ​In this module, you'll learn how to prompt gen AI tools ​for more complex projects. ​You can turn abstract ideas into step-by-step solutions.  
​We'll explore how to converse with a gen AI tool, ​create an AI agent, ​and build a prompt library to help you save time ​and reuse your prompts. ​Let's get started.  

Discover prompt chaining:  

 Have you ever tried to put together a jigsaw puzzle? ​You don't just dump all the pieces out ​and hope for the best, right? ​You start with a game plan. ​Maybe you find the corner pieces and slowly build the edges ​before working on the middle section. ​Or maybe you find the small sections to work on ​before connecting them to a bigger picture. ​The point is that it's a deliberate process, ​it builds over time.  

 That's what prompt chaining is like.  
​Prompt chaining guides a generative AI tool through a series ​of interconnected prompts, adding new layers of context ​or tasks each step of the way. ​Eventually, those linked prompts help the tools solve ​complex problems one step at a time, ​just like putting together a puzzle.  

​Here's how we can put that to work for you. ​Have you ever taken time off work ​and needed to catch up on what you missed? ​You could prompt a gen AI tool to summarize your emails ​and any documents you received while you were gone. ​After reviewing the output, you may wanna prompt it again ​to focus on time sensitive requests. ​If the new output reveals an urgent issue, ​you could prompt the tool again for some solutions on how ​to handle it and on and on.  

​With this technique, you're not just iterating. ​Instead, each prompt ​and response builds on the previous one. ​You're creating a chain of prompts together ​in a single sequence.  
 ⇒  
​Let's demonstrate prompt chaining in action.  
​We'll use Google AI Studio as it enables us to get access ​to Gemini models with a long context window. ​You just finished writing a novel, ​huge accomplishment, right? ​Well, now the other work starts.  
​You need to market and sell it, so you decide ​to create a marketing plan to promote the book. ​They claim you can't judge a book by its cover, ​but it's still important to make a good first impression. ​First, you'll need a catchy hook or tagline. ​We can use the prompt framework ​to generate some options in AI Studio. ​  
<https://aistudio.google.com/prompts/1IyIry3IEYQhf1M_T5cBD-ka8HiLagxOw>  

As always, let's be specific about our task. ​Generate three options for a one sentence summary ​of this novel manuscript. ​The manuscript will provide the story's background ​information directly,  

so let's just specify the tone.  
​The summary should be similar in voice ​and tone to the manuscript, but more catchy and engaging. ​Okay, let's check out the output. ​  

These options are good, but maybe you want the tagline ​to focus on a specific theme in your book. ​We can write a follow up prompt to refine the taglines.  

 ​Create a tagline that is a combination ​of the previous three options ​with a special focus on the exciting plot twists ​and mystery of the book. ​There's the new context. ​Find the catchiest and most impactful combination.  
​The tagline should be concise and leave the reader hooked ​and wanting to read more, ​and we've specified the task and format.  

​Great. This is really strong ​and gives you a great one-liner for marketing your book. ​Remember, prompt chaining isn't just about adding more ​context to your prompts. ​It's about expanding on ​what the gen AI tool has previously generated. ​This is a little different from iteration in ​the prompt framework. ​  
Since that focuses on adjusting a given prompt ​to improve the results. Here you wanna use its output ​as a building block for more complex requests.  
​This brings us back to the tagline you generated. ​It's a great starting point. ​For the next piece in your prompt chain, ​you wanna generate a blurb for the back cover of the book. ​Let's continue.  

 Create a five sentence ​summary of the entire manuscript below ​that expands on the one sentence summary.  

​Okay, so we like this summary. ​We could iterate on it, of course, ​but for the moment, let's use this output ​as the first step in your chaining process.  
​With your tagline and blurb set, it's time ​to think about your book tour, ​where you promote it in local bookstores, stores ​that specialize in your book's genre. ​Let's continue to build the chain ​and generate a plan based on ​what we've already told the gen AI tool about your book. ​Since the model has already analyzed your manuscript ​and remembers the conversation, thanks ​to the long context window, just provide the new task.  

 ​Generate a six week promotional plan for a book tour, ​including what locations I should visit ​and what channels I should utilize ​to promote each stop on the tour. ​Awesome. You got a plan, ​and of course, you can iterate on any ​of these prompts if you're not happy with the options. ​The gen AI tool provided.  
​That's the power of prompt chaining. ​All it took was a series of prompts, ​and we guided the Gemini model ​and AI Studio to write taglines, summaries, ​and a plan for the book tour.  

Explore Chain-of-thought and Tree-of-thought prompting:  
Here are two advanced prompt chaining ​techniques you can try. ​The first is chain of thought prompting, ​or C-O-T. C-O-T prompting asks the gen AI tool ​to explain its reasoning ​or to describe step by step how it got to a specific result.  

 ​It's similar to the way math teachers ask students ​to explain how they got to an answer. ​This method can help you understand the gen AI tool's ​reasoning methods, ​which can help you make better decisions ​based on its outputs. ​For example, you might need help deciding how ​to balance visiting all six book tour locations ​with a limited budget or time constraints. ​You could prompt the gen AI tool for ideas on how ​to solve this, but this time you include explain your ​thought process in your initial prompt.  
​That way you can evaluate the logic ​behind each proposed solution.  
​A related concept is Tree of Thought ​prompting, or TOT. Tree of Thought involves asking the tool ​to explore multiple reasoning paths at once. ​Like branches growing on a tree, TOT enables the tool ​to explore multiple solutions to a given problem. ​It evaluates as it goes, ​which helps you get the best outcome. ​It's like going through a maze. ​Your goal is to get to the end, ​but you may have to follow a couple ​of different paths before you get there.  

​This method is particularly helpful when solving abstract ​problems like developing a plot for the novel sequel ​with new characters and complex storylines. ​These techniques can be really useful for creating outlines ​or drafting small sections of longer documents at work too. ​Prompt chaining gives you the chance ​to explore more complicated ideas ​and generate interesting responses. ​You might even uncover some insights you could miss ​with a single prompt.  

Simplify multi-step projects with prompt chaining:  

Some projects are too big to be completed all at once—multi-part work often comes together one step at a time. When working with generative AI tools, some challenges are best overcome by breaking them up into smaller, interconnected tasks, and with prompt chaining, you'll do just that. And taking it step by step also maintains the human-in-the-loop approach, so you can evaluate your prompts and results as you continue chaining them together to spot hallucinations.  

Prompt chaining  

Sometimes, for more complex tasks, it can help to take the output of a gen AI tool and use it as context for a new prompt. Connecting prompts is like connecting links in a chain—which is why this process is called prompt chaining.  
A great prompt chain is only as strong as the prompts within it, and specificity is the secret to success.  
Here’s an example: You’re the head of human resources for an advertising agency, and you’ve been tasked with designing an onboarding course for new hires. Creating a program from scratch involves a lot of moving parts, so you’re going to use prompt chaining to keep the workload manageable.  
Here’s an example input:  
I’m the head of human resources for an advertising agency, and I’m designing an onboarding course for new hires. Generate an outline specifying the most important parts of an onboarding course for an entry-level hire.  
And here’s an example of the potential output from that prompt:  
Onboarding Course Outline for Entry-Level Hires at an Advertising Agency  
Introduce agency culture and values  
Summarize duties and responsibilities  
Explain advertising industry fundamentals  
Break down agency tools and technology  
Detail client relationships and communication practices  
Review agency policies and procedures  
Encourage professional development and growth  
Having that output as a foundation then allows the gen AI tool to carry out all sorts of related assignments.  
 For the next part of the prompt chain, you’ll follow up on the second bullet, and expand on the expectations for a new addition to the design department. But keep in mind, some gen AI models don’t automatically retain context from one prompt to the next, and may require you to re-enter the relevant information into the prompt yourself.  
Here’s an example input:  
Expand the second bullet point from the attached outline into a paragraph of 100 words, including expectations for their first year.  
And here’s what that output might look like:  
As a new entry-level design hire at our ad agency, you will primarily focus on assisting our senior designers and art directors with various projects. Your responsibilities will include: researching design trends and industry best practices, creating concept sketches and mood boards, preparing presentation materials, and assisting with file organization and management. In your first year, we expect you to develop a strong foundation in design principles and software applications. Additionally, you will have the opportunity to contribute to client projects and gradually take on more independent design tasks.  
Now that you’ve got a draft which will serve as context for your next prompt, you can continue planning the onboarding course. Keep building the chain by using the paragraph to create an activity to keep new hires attentive and engaged throughout the onboarding process.  
Here’s an example input:  
Using the attached text, suggest a three-question quiz to test the reader’s familiarity with the content.  
And here’s the output:  
Question 1:  
What is the primary responsibility of the new design hire?  
A) Managing the agency's design and copywriting resources  
B) Creating visually appealing designs for advertising materials  
C) Writing creative copy for advertisements  
Question 2:  
With whom will the new design hire collaborate?  
A) Clients only  
B) Copywriters and account managers  
C) Designers from other agencies  
Question 3:  
What is expected of the new design hire in terms of professional development?  
A) Staying steady in their current skills  
B) Avoiding industry trends  
C) Continuously learning and improving their design abilities  
You’d still like to strategize a little further. With the earlier prompt’s paragraph, the tool can also help you design a visual accompaniment.  
Here’s an example input:  
Based on the attached text, generate a visually energetic graphic that congratulates the reader on a correct answer, and features images of art supplies and computers.  
And the output:  

Note: This image is AI-generated. Results are for illustrative purposes and may vary.  
The chain can go on and on; its only limit is your creativity. You can even double back and use chained outputs in different prompts, such as creating onboarding courses for other departments. And if you’re not getting the results you’re searching for, consider how the prompts in your chain might be split up into chains of their own.  
Types of advanced prompt chaining  
Chain-of-thought prompting  
When you get the details on how a gen AI tool reaches its conclusions, you can ask smarter questions that lead to more effective outputs. With the chain-of-thought prompting technique, you can ask the tool to retrace its path from input to output, listing out the reasoning behind its response step by step. And if your prompt’s results miss the intended target, chain-of-thought prompting can help you pinpoint the source of the confusion and understand why gen AI makes the decisions it does.  
You can ask the tool to use chain-of-thought prompting with key phrases like “explain your reasoning” or “go step by step.” You may also notice some variety between models, with some gen AI tools requiring more detailed instruction.  
With chain-of-thought prompting, you can also single out a particular step in the tool’s process and redirect its decision-making from there.  

At the top, a box labeled "Prompt input" points with a downward arrow to a box labeled "Reasoning," then another downward arrow points to a second box also labeled "Reasoning," then another to a third box labeled "Reasoning," and then a final arrow to a box labeled "Prompt output."  
For example, maybe the suggested paragraph from the onboarding course example isn’t covering everything you need it to, and you want to know how the tool arrived at its recommendation. Returning to your prompt and evaluating the line of reasoning might help you find a new direction. Here’s what a potential input might look like:  
Draft a paragraph of approximately 100 words detailing the major duties and responsibilities of a new entry-level design hire at an ad agency. Explain your reasoning step by step.  
And a potential output from that prompt:  
Reasoning:  
Step 1: Identify Core Responsibilities  
Step 2: Highlight Essential Skills  
Step 3: Emphasize Collaboration  
Step 4: Address Industry Standards  
Paragraph: As a new entry-level design hire at our ad agency, you will primarily focus on assisting our senior designers and art directors with various projects. Your responsibilities will include: researching design trends and industry best practices, creating concept sketches and mood boards, preparing presentation materials, and assisting with file organization and management. In your first year, we expect you to develop a strong foundation in design principles and software applications. Additionally, you will have the opportunity to contribute to client projects and gradually take on more independent design tasks.  
You’d also like the paragraph to mention joining the agency’s community of coworkers, so instructing the tool to incorporate that item specifically could get you back on track.  
Tree-of-thought prompting  
There are times when you might not be sure about the most productive way to go from one prompt in a chain to the next. Tree-of-thought prompting is a technique for exploring multiple possible solutions at once, helping you find the most effective approach. Instead of following a single chain of thought, you generate several responses to your prompt, then evaluate and choose the best ones to pursue. If one output doesn't work, you can easily return to a previous branch and try another option until you find the best solution.  

The chart begins with a bubble labeled "Prompt" at the top, branching off to three sub-prompts beneath it, with unsuccessful options represented by blue boxes and possibly successful options in green. At center, a green possibly-successful sub-prompt box branches off to four more in the next row down. Those branch off to another row, and in that row, a green box branches down once more to a successful output.  
Returning to the earlier example, imagine you're generating a cover image for your course. With tree-of-thought prompting, you might input a prompt similar to this:  
Imagine three different designers are pitching their design to me.  
All designers will write down one step of their thinking, then share it with the group. Then all experts will go on to the next step, etc. If any expert realizes they're wrong at any point, then they leave.  
The question is: Generate an image that's visually energetic, and features images of art supplies and computers. Show me three suggestions in very different styles from simple to detailed and complex.  
The AI tool will generate three different styles of images featuring computers and art supplies: one cartoonish, and the other two more photorealistic.  

Note: These images are AI-generated. Results are for illustrative purposes and may vary  
With multiple options to choose from, you decide that a cartoonish style is best for the cover image, so you continue prompting the tool to create variations of that style.  

Note: These images are AI-generated. Results are for illustrative purposes and may vary  
And you continue this process, exploring different branches of the tree until you find the perfect fit! If at any point you're dissatisfied with the output, you simply ask the tool to return to a previous branch of the conversation and explore other designs.  
In some cases, combining tree-of-thought with chain-of-thought can give your prompting the boost it needs. When you need insight on a tool’s reasoning and other options to take within that reasoning, the two techniques can work perfectly together.  
Be mindful, however, that advanced prompt chaining may work differently in various gen AI models. Some more advanced AI models, for example, will automatically detect opportunities for chain-of-thought or tree-of-thought reasoning without being specifically instructed to do so. In those situations, experimentation confirms the best results; repeat your prompt with various models and compare their outputs.  
Prompt chaining makes difficult projects easier by dividing a large task into simpler, sequential prompts. But remember, this process still needs a human’s critical thinking skills to work best. With your guidance,  prompt chaining can help you evaluate, direct, and correct your prompting process, so you can meet your deadlines with ease.  

AI IRL: Enlist AI as your thought partner  
Nowadays we actually have quite a bit more memory. ​And what that lets you do is it lets you put in large ​amounts of data and reason over it. ​And so I've been writing a book ​and I tend to put my manuscript through AI ​and I have it critique ​and analyze that manuscript pull things out, ​drop connections in there that I would not have. ​It's a 300 page manuscript. ​And so having someone try to do ​that in person would take hours and hours and days and days, ​and yet we can do this now with these larger context windows ​and these AI systems, it's very powerful. ​- Yeah. Well the last couple of years ​of large language models has definitely been a big boon. ​- Yep. - I've been pretty excited by it as well ​as have benefited a lot in my own work. ​I have found that using the large language model ​as a partner for brainstorming ​or questions actually really works.  
​I'll give you an example of something ​of the time when I realized that writing was going ​to be a big deal on large language models. ​I had a proposal that was due the next day ​and it was around 8:00 PM in the night, ​and I was thinking about how it was gonna take me four hours ​between now and then in order to get that proposal done ​if I had to write it all from scratch. ​So I sat down in front of one of the large language models ​and basically asked it to help me out, giving it the role ​that I was playing, ​giving it some details about the proposal that I was doing ​and asking it to create a draft. ​When I saw the draft, ​I realized it had saved me a couple of those four hours. ​Oh, incredible. You know, right at the outset. ​And I was actually quite thrilled ​because I was able to take that early draft ​and do my own work on it afterwards ​to turn it into something that I could turn in the next day. ​- So you use it as a starting point? ​- Just used it as a starting point? Yeah, absolutely.  
​It was actually quite a surprise that it was actually able ​to give me an outline that was actually very reasonable. ​- Right. - In Fact, it added sections of the outline ​that I knew would've taken me some time ​to even think about myself. ​- Oh, that's fascinating. - But I was really excited about ​that ability and the help that I got.  

Use meta-prompting to improve and generate new prompts:  
Half the challenge of getting the most out of generative AI tools is knowing how to ask the right question. Meta-prompting is a technique that uses gen AI to help you craft or improve your prompts—turning the tool into a personal  prompt designer! Instead of guessing what the best prompt is, you can ask the tool directly for suggestions on how to get the results you want. This approach can help you design better prompts that generate better output.  

Meta-prompting:  
Meta-prompting techniques are sometimes referred to as “automatic prompt engineering.” And much like the prompting framework (Task, Context, References, Evaluate, Iterate) that gives us a strong foundation for designing prompts, meta-prompting comes with its own set of best practices, or power-up strategies. These guide meta-prompts down the most effective paths, and they fall into two main categories:  
Prompt generation strategies: To help design a prompt from scratch  
Prompt refinement strategies: To fine-tune the prompts you’ve already designed  
Prompt generation strategies  
Strategy  
Use case  
Example prompt  
Direct generation  
Asking a gen AI tool to generate a prompt for you.  
You’re a human resources representative heading up a job search, and you’re ready to welcome your office’s newest teammate.  
You write: Generate a prompt that could help write a job offer letter to our top candidates.  
Template request  
Asking a gen AI tool for an outline to organize the contents of your prompts.  
You’re the manager of a baseball team, and you’re all going to hit the road for some away games.  
You write: Create a template specifying the most important elements of a gen AI prompt meant to plan travel for a baseball team and its personnel.  
Image  
Using an image as a reference to generate a prompt, or to shape a prompt you’ve already tried.  
You’re the owner of a small dog food start-up, and you want your logo to evoke an old oil painting you found online, but describing the painting isn’t working.  
You paste the image into the prompt, and write: Generate a prompt I can use to create the perfect logo for my dog food company that evokes the style of the attached image.  
Text  
Using text as a reference to generate a prompt, or to shape a prompt you’ve already tried.  
You’re struggling with an instruction manual for your new computer.  
You could upload the manual by attaching a PDF or pasting the text into the prompt window, and write: Using the text, generate a prompt to begin an explanation of the most important concepts in this manual.  
Meta-prompt chaining  
Breaking the process of drafting a prompt into a series of sub-prompts.  
You need a prompt to create a grant proposal, but with all the detail involved, direct generation isn’t working out.  
You write: Generate a prompt that identifies the most important qualities of an intelligent and accessible intro paragraph for a grant proposal.  
From there, you can use the response to construct additional prompts as you build out your proposal.  

Prompt refinement strategies  
Strategy  
Use case  
Solution  
Leveling up  
Asking the gen AI tool outright to elevate your prompting.  
You’re drafting copy for a local auto body shop’s new ad campaign, and your output is missing that fast-and-furious feeling.  
From: I’m working on an ad campaign for a local auto body shop’s sale on tires and windshields. Generate an announcement for the sale.  
To:  How can I change my initial prompt to produce an ad campaign that uses more engaging language and creates a more memorable impression?  
Remixing  
Asking the gen AI tool to synthesize multiple attached prompts into a super-prompt including the key context from each one.  
You’re working on an intro paragraph to brief potential contractors on a graphic design project, but each prompt’s results leave out some key piece of the job.  
You can copy all your prompts and instruct the gen AI tool to combine them into a single prompt that retains the most important parts of each one.  
Style swap  
Dictating the mood and tone for a prompt to bring out a more colorful, vivid final product.  
Your initial prompt asking for a description of Irish folk music returned technical results. It’s the right information, but it’s boring! You want to know about the soul of the music, and so your meta-prompt should reflect that.  
You can instruct the gen AI tool to rewrite your prompt with an emphasis on emotionality, and to use more expressive, passionate language to communicate the experience of the music.  

With meta-prompting, you can enlist gen AI’s help to design the perfect prompt, or take one you’ve already written to the next level. And with power-up strategies to guide your meta-prompting, you’ll know just what to do the next time you’re having trouble building your prompt into the best it can be. In prompt design, meta-prompting is your roadmap to a successful output.  

Build a prompt library:  

 Throughout this course, you've learned how ​to thoughtfully create really excellent inputs. ​How to prompt.  

Like most skills, ​your prompting abilities will improve ​through experimentation and practice. ​You can save a ton of time by noting which prompts work best ​and for what use cases.  

​I encourage you to keep track ​and go back to determine what's worked and what hasn't. ​That's where prompt versioning comes in. ​Prompt versioning is a way to keep track ​of the different versions of your prompts over time.  
​It's a powerful way to capture your most effective prompts, ​track your progress, ​and develop your gen AI prompting skills. ​And here's a tip.  

 You can name your most effective prompts ​and store them in your personal prompt library ​for easy access in the future.  

 ​In fact, some generative AI tools allow you to name ​and save your prompts right inside the tool. ​Imagine you're doing meal prep for your family. ​You found a set of meals you really like, ​but you wanna start experimenting with new cuisines. ​You wouldn't scrap your entire meal plan ​and start again, right?  
​You'd use what you've already learned about things like ​preferences, portions, and allergies, ​and use that as a base ​to create a new weekly menu for your family.  
​The same goes for prompt versioning. ​Once you have a prompt that works, you don't need ​to reinvent the wheel. ​You can experiment with different tasks, context, ​and references to get different ​results based on what you need.  

 ​For example, you can develop a reusable prompt for emails. ​The gen AI tool will draft the email for you, ​but you can adjust the tone ​and format based on the audience you're communicating with. ​Or you could use a single source of information ​to create different frequently asked questions, ​sections dedicated to different types of customers ​that visit your website.  

​You can tweak the prompt that generated the FAQ ​for individual consumers ​and change the persona to make an FAQ ​for enterprise customers. ​Think about all the prompts we've created in this course. ​What versions can you create for your needs?  

​Playing and experimenting with prompts is the best way ​to figure out how to get what you want. ​And the only way to get there is to get comfortable, ​explore and learn what path works for you. ​And remember, you're not alone. ​  

There's a big community of folks out there ​that are sharing prompts that have worked for them, so ​that people can learn from each other's successes, ​find inspiration and support.  
​Participating in that community is a great way ​to improve your prompting skills and build a network.  

AI IRL: Build AI with your community  
We know that AI is transforming a lot ​of different industries. ​I'd love to get your insights. ​- Yeah, I mean, ​AI has such a big opportunity in almost every industry ​and area to both make a difference in ​advancing the industry, ​but really it's in partnership with the people ​who are actually in those industries. ​That's right. I have a project ​or an area of projects around society centered AI ​that means involve the communities in the development ​of the AI to solve core problems ​that those communities have. ​By having those impacted communities involved in the ​development process, that will lead to the best solutions ​and it will also lead to the impact on those communities. ​- One of the things that I think is very complimentary ​and similar in both of our roles is the ways ​that we interact with society and people bring them in ​and co-create with them. ​I'd love to learn a little bit more about ​how you're doing that in your role. ​- Yeah. Having multiple perspectives on society centered ​and AI is foundational and critical.  
​I think it is largely ​because communities are so diverse, people are so diverse, ​and to really understand full aspects ​of the problem involves all of those skills ​and all of the variety of different skills ​that people can bring. ​One of the things that is also very difficult is ​to tackle it not just at an individual user level, ​but to tackle it at a community level, ​or even aspire to tackle it at a society level, ​- And it's a hard problem. ​I think with a technology that is so transformative. ​There's a responsibility to approach it very intentionally ​with this, you know, plurality of work and perspective.  

Go further with AI agents:  
Some types of AI can do more than execute a single task. They can autonomously handle complex, multistep workflows with your guidance and oversight, helping you achieve broad goals. Unlike standard AI chatbots, you can choose to let these AI agents  access the tools you use every day, like email, calendars, or documents, and take action on your behalf and under your control.  
What can AI agents do for you?  
Think of an agent as an AI system that you can delegate complex, multistep tasks to. This shift helps free you so you can focus on activities that need your expertise, like strategic thinking.  
Here are a few examples of how you might use an AI agent:  
Conduct market research: You can use an agent to analyze new competitors, find their key features, and synthesize recent customer reviews into a weekly team email.  
Streamline sales: You can set up an agent to go through your inbox, identify new sales leads, extract their contact information, and automatically create new entries for them in your contact list.  
Assist with forecasting demand: You can have an agent analyze sales and inventory data, predict future demand for your products, and order the necessary supplies to make sure you’re prepared.  
Understand how AI agents work:  
An AI agent operates using three core components:  
Models: Models are computer programs trained on vast amounts of data, which allows them to recognize patterns. When you give an AI agent a goal, the model uses its training to predict which tasks are necessary to achieve that goal and how to use the tools available to complete it.  
Permissions: AI agents connect to other software and tools through specific permissions you grant. These settings act as guardrails, controlling how the agent executes tasks within the parameters you set. For example, if you assign an agent to manage your inbox, you can restrict its access to only read unread messages.  
Goals: A goal is the broad objective you provide an AI agent, such as "Organize the Q3 kickoff meeting.” Once a goal is set, the agent operates in a continuous loop until the goal is complete.  
Analyze: The agent uses its model to determine the necessary first task, like connecting with your calendar to find free time.  
Act: Once permissions are granted, the agent executes that task, like finding a time for the team to connect.  
Observe: The agent reviews the result of its action and ensures it's aligned with the goal, like checking the selected time to make sure everyone is available.  
After completing the Observe step, the agent begins the loop again by moving to the next task, like drafting and sending the calendar invitations. The agent continues this loop until the meeting is successfully scheduled.  
Your guide to working with agents responsibly :  
As AI agents become more capable, your guidance and judgment become even more important. When deciding whether to delegate a goal to an agent, keep these two principles in mind:  
Risk: What's the impact of a mistake? For example, drafting an internal memo may be low risk. But using an agent to make purchases on your behalf might be high risk depending on the size of the transaction.  
Reversibility: How easily can an action be undone? Drafting an email and saving it to your drafts folder is highly reversible. Posting directly to a public social media account is not.  
For high-risk or irreversible goals, you should maintain tighter control through a human-in-the-loop approach. Set clear boundaries, define acceptable parameters, and maintain oversight at each critical step.  
The best way to use AI agents responsibly is to start small. Look for agentic features in the software and tools you’re already using, and try giving an agent a simple, low-risk goal.  
Best practices for directing AI agents  
As you start to use AI agents throughout your work, consider the following best practices:  
Start with a clear, specific goal: Provide a precise description of what you’re trying to accomplish. "Plan a marketing campaign" is vague. "Draft a 3-email sequence for our new product launch" is clear and actionable.  
Manage permissions wisely: Be mindful of what you approve. If an agent needs to read emails to find contacts, grant only that specific permission. Avoid giving master permissions that grant blanket access to your entire app.  
Always evaluate: You're responsible for any work the agent produces. Always check the work, especially on high-stakes tasks.  
Iterate and refine: Treat the agent as a collaborator. If the first result isn't right, refine your instructions or provide more context.  
AI agents can be powerful partners, but your success depends on your ability to supervise them with clarity, judgment, and a strong vision.  

Coach dialogue: Take action with AI:  
Welcome! During this Dialogue, we will focus on developing a concrete plan to integrate AI tools into your work or daily life.  
Here's what we'll cover:  
Identifying a real-world task for AI application  
Exploring effective prompting strategies  
Considering necessary AI tool features  
Defining your next steps and goals  
Need help? Click "I'm stuck" at the top right to ask for a hint.  
When you're ready, click Start Dialogue  
Great! Let's begin by identifying a real-world task you'd like to improve using AI tools.  
Think about your daily routine or work responsibilities—perhaps you could use AI for drafting emails, summarizing long documents, brainstorming creative ideas, organizing data, or even planning projects.  
What is one specific task you'd like to focus on applying an AI tool to?  
Me:  
As an consultant of starter who is professional in programming language in canada  give me a plan, I have an idea for translating a portion of podcast  or any kind of music which are played from phone which user is listening and tap their finger of screen to pause the voice and translate automatically to a desire language of user and added to the library for future review. I want to implement  this idea as an app for android and then iphone  
That sounds like a fascinating and ambitious project! It's a great example of how you can use AI tools to enhance accessibility and language learning.  
To make sure we have a clear focus, let's refine this. You're looking to build an app that captures audio from a device, translates it in real-time, and saves it for later.  
Now, let's move on to Exploring Prompting Strategies. Since your app will rely on AI to handle the translation and potentially summarize or organize the content, what kind of prompting strategies—such as providing context, using few-shot examples, or chaining prompts—do you think would be most effective to ensure the translation is accurate and captures the nuance of the original audio?  
i think chaining prompting would be more effective  
That's a great choice. Chaining prompts can be very powerful for complex tasks like yours, where you might need to first transcribe the audio, then translate it, and finally summarize or format it for the user's library.  
To help me understand your thinking better, could you explain how you would structure these chains to ensure the final output is high-quality and useful for the user?  
because when a user are playing an audio, it has a main subject, and if user ask ai to translate one word or sentences, ai can understand what is the ausio about! then in the next promt it already know about the audio domain and it translate to related menaing.  
That's a spot-on observation! By establishing the context or "domain" of the audio in an initial prompt, you're essentially priming the AI to make much more accurate, context-aware translations in subsequent steps.  
Now, let's move on to Considering AI Tool Features. Given that your app needs to handle real-time audio input, perform accurate translations, and store content, what specific features or capabilities of an AI tool would be essential for your app to function effectively? That's a spot-on observation! By establishing the context or "domain" of the audio in an initial prompt, you're essentially priming the AI to make much more accurate, context-aware translations in subsequent steps.  
Now, let's move on to Considering AI Tool Features. Given that your app needs to handle real-time audio input, perform accurate translations, and store content, what specific features or capabilities of an AI tool would be essential for your app to function effectively?  
thank you, these features need as an AI tools features:  
voice to text (transcript) ==&gt; to convert audio word to text  
translating feature ==&gt; translate from audio to desire user's language  
large context window to keep audio text completely until the end of specific audio to translate accurately using AI  
text to voice ==&gt; to read the translated text by voice  

That is a solid breakdown of the core features required for your app to function effectively. You've clearly identified the pipeline from capturing the audio to delivering the translated output back to the user.  
Now, let's move on to Defining Next Steps and Goals. To turn this idea into a reality, you need a concrete plan. Considering the features you've identified, what is one specific, actionable "next step" you could take to start integrating these AI capabilities into your workflow or development process, and what is a potential constraint or challenge you might need to plan for?  

first of all I need a business plan to define what is the requirement and what skill do I need to  implement this idea? for example i need android developer, data scientsit , then explain more step by step how can i implement it? with a precise planning for develope that.  

That's a very practical approach. Building a team and a roadmap is essential for a project of this scale.  
To wrap up our session, let's summarize your plan: You've identified a real-world task (real-time audio translation for podcasts/music), selected a chaining prompting strategy to maintain context, and outlined the necessary AI tool features (transcription, translation, large context window, and text-to-speech). Your next step is to develop a comprehensive business and technical roadmap, including identifying the necessary roles like Android developers and data scientists to execute the development.  

During today's session, we focused on developing a plan to implement an AI-powered real-time audio translation app. We explored the workflow from capturing audio to providing translated output, identified the importance of chaining prompts to maintain context, and outlined the essential AI tool features required for your application.  
Your strengths:  
Strategic Thinking: You correctly identified that chaining prompts allows the AI to maintain context, which is crucial for accurate, domain-specific translations.  
Technical Mapping: You successfully broke down the project into necessary AI tool features, such as transcription, translation, context management, and text-to-speech.  
Areas for improvement:  
Refining Implementation Steps: While you have a high-level vision, consider breaking down your "business plan" into smaller, manageable technical experiments. For example, you could start by testing existing APIs for transcription and translation to validate your core logic before building the full app architecture.  
Focusing on MVP: As you move forward, try to define a "Minimum Viable Product" (MVP). Instead of building everything at once, focus on the most critical feature—like accurate translation of a short audio clip—to test your hypothesis before scaling to a full library system.  
You've completed 4 of 4 topics, and we have successfully outlined your path forward.  
Remember, this learning journey doesn't end here. Continue to apply, refine, and expand your prompting skills in your career. Keep up the good work!  


## End of specialization challenge



---

## Original source file

The complete unmodified notes are also available as `original-notes.txt` in the repository.
