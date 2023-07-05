# Prompt Engineering Basics & Examples

## Prompt Basics

I've found that prompt engineering is most successful when using three key areas:

1. **Persona:** This helps the language model "frame" the context. For example, you would like the model to channel a project manager. This assumes the model will bring their best foot forward to channel a seasoned professional in project management. In the bulk of cases, using the "Intelligent Assistant" helps prime the AI model to engage in a more conversational manner.
2. **Task:** This is the key ingredient of working with a Large Language Model (LLM) like ChatGPT. It's a crucial input you will need to provide to help articulate the "so what" of your interaction. The key here is to help ensure you are providing clear instructions to help the model complete the task at hand. Think of it like writing an email request to someone asking them for something; the more helpful you can be to set them up for success, the better.
3. **Output:** This is perhaps the most salient feature of LLMs like ChatGPT. You have several options including displaying information in a table format, a bulleted list, or numbered list. If using GPT-4, you have the ability to leverage plugins which can produce things including graphs and charts.

### Intelligent Assistant Example Code

I was looking for an easy way to componse an email for a project. So, naturally, I decided to enlist the help of ChatGPT. Here's the prompt I used to help guide my "Intelligent Assistant":

```
You are an intelligent assistant with a specialization in project management. I need you to compose a short email to an executive audience no longer than 100 words. The purpose of the email is to schedule a meeting time with my intended audience.

I want to articulate a few key points:
- This Weekly Status Report is a requirement of our Statement of Work (SOW)
- I have availability on Friday for our first session between 10:30am and 11:30am and 1pm to 2pm
- I would like to pin down a 30 minute time slot on a weekly basis
- Please confirm which suits
```
Experiment with the model by applying specific restrictions, or requirements, to the output. In this case, I instructed the model to produce a message no longer than 100 words.

#### Intelligent Assistant Example Code Output

Based on the prompt I gave using the Intelligent Assistant Example Code, I was provided with a quick and easy email. I only had to apply a few changes to make it sound a little more like "me," but suffice to say it worked! 

> Subject: Request to Schedule Weekly Status Report Meeting - Availability Confirmation Needed
>
> Dear [Executive's Name],
>
>I hope this email finds you well. As per our project's Statement of Work (SOW), I am reaching out to schedule our weekly status report meeting. This meeting is a requirement for accurate progress tracking and project alignment.
>
>I have availability on Friday for our first session, with time slots between 10:30 am and 11:30 am, as well as 1:00 pm and 2:00 pm. To ensure consistency, I suggest a 30-minute time slot on a weekly basis. Kindly confirm which time suits you best, and I will promptly finalize the schedule.
>
>Thank you for your attention to this matter. I look forward to our productive discussions.
>
>Best regards,
>
>[Your Name]

## CPA Praires Connection Conference

In June 2023, I was invited to speak to a highly-engaged group of Chartered Professional Accountants (CPAs) at their Prairies Connection Conference in Winnipeg, Manitoba (Canada). My session covered the basics of ChatGPT and was titled "ChatGPT Told Me This: What Do the Accountants Say?"

Naturally, I had to put ChatGPT to the test on the model's ability to compose a catchy session description. Here's what it came up with:

> Are you ready for the ultimate debate between human and machine? Join us for a thrilling presentation where we pit ChatGPT, the language model trained by OpenAI, against seasoned accountants. With years of experience and expertise on their side, the accountants will go head-to-head with ChatGPT, armed with data and algorithms. Who will come out on top?
>
> In this session, you'll witness an epic battle of wits and knowledge in the world of finance. You'll gain insights into the best accounting practices and strategies from both ChatGPT and the accountants, and walk away with a fresh perspective on the world of finance.
>
> After attending this session, you'll be able to:
>
> * Understand the strengths and limitations of using AI in accounting
> * Identify key areas where human expertise is essential in the accounting profession
> * Learn about emerging trends and technologies shaping the future of accounting
> * Gain practical tips on how to optimize your accounting practices and strategies
> * Don't miss out on this exciting and informative presentation!
>

Working backward, here's a look at the prompt I used to point ChatGPT in the general direction I was going:

```
Write a catchy presentation session description for a presentation titled "ChatGPT Told Me This: What Do the Accountants Say?". The description should draw attention to a battle between ChatGPT and Accountants being right. Include a handful of outcomes people can expect to walk away with after attending the session.
```
**Note:** For integrity, I did provide full disclosure to participants that I enlisted the help of ChatGPT to author the bulk of my presentation's contents, for experimentation purposes. I sense we are going to see this becoming a mandatory requirement going forward, espeically as we look for AI's help.

### Long-Form Prompt

The event organizers were eager to test drive a live demonstration of the model. After a bit of research, I managed to track down a few examples of how to produce a long-form prompt. This "omnibus prompt," as I like to call it, follows a series of instructions and saves you from having to enter multiple queries.

Below is an example of the long-form prompt I used to facilitate the demonstration:

```
You are an intelligent assistant. You have been tasked to support a live demonstration of ChatGPT, with a focus on CPA accounting standards in Canada. Included in the bulleted list below are the specific tasks which build on each other, written as contextual prompts, I will need you to complete.

- Generate a fictional balance sheet in a table
- If you were to write out an explanation or summary of someone who doesn't understand financial statements, what would you say is the financial health of the company?
- Use the fictional balance sheet generated to provide an opinion.
- Pretend you have been retained by the client to write a qualified opinion.
- Generate a statement of cashflow for this client which is fictional. Present the statement in a table format please.
- Please regenerate the qualified opinion letter based on this updated information.
- I will provide you with an income statement. I need you to provide me with an opinion on the financial health of this company
- Produce and verify a compilation.

You must complete each of these steps separately. Once you complete the output, I need you to confirm whether I am satisfied with the output. I will provide guidance and feedback for you to use to produce an output I am comfortable with. Only when I provide the response "Approved" will you proceed to the next step. Before proceeding, I need you to confirm your understanding of these instructions.
```
Based on the instructions provided in the long-form prompt highlighted above, the model successfully went from one point to the next only when provided with the instruction "Approved".
