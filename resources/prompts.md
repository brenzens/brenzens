# Sample Prompts

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

#### Intelligent Assistant Example Code Output

Based on the prompt I gave using the Intelligent Assistant Example Code, I was provided with a quick and easy email. I only had to apply a few changes to make it sound a little more like "me," but suffice to say it worked! 

```
Subject: Request to Schedule Weekly Status Report Meeting - Availability Confirmation Needed

Dear [Executive's Name],

I hope this email finds you well. As per our project's Statement of Work (SOW), I am reaching out to schedule our weekly status report meeting. This meeting is a requirement for accurate progress tracking and project alignment.

I have availability on Friday for our first session, with time slots between 10:30 am and 11:30 am, as well as 1:00 pm and 2:00 pm. To ensure consistency, I suggest a 30-minute time slot on a weekly basis. Kindly confirm which time suits you best, and I will promptly finalize the schedule.

Thank you for your attention to this matter. I look forward to our productive discussions.

Best regards,

[Your Name]
```

## CPA Praires Connection Conference

### Long-Form Prompt

```
You are an intelligent assistant. You have been tasked to support a live demonstration of ChatGPT, with a focus on CPA accounting standards in Canada. Included in the bulleted list below are the specific tasks which build on each other, written as contextual prompts, I will need you to complete.

- Generate a fictional balance sheet in a table
- If you were to write out an explanation or summary of someone who doesn't understand financial statements, what would you say is the financial health of the company?
- Use the fictional balance sheet generated to provide an opinion.
- Pretend you have been retained by the client to write a qualified opinion.
- Generate a statement of cashflow for this client which is fictional. Present the statement in a table format please.
- Please regenerate the qualified opinion letter based on this updated information.
- I will provide you with an income statement. I need you to provide me with an opinion on the financial health of this company
- BreakdownTTM2/28/20222/28/20212/29/2020
Total Revenue	6,210,944	7,867,778	9,233,028	11,158,580
Cost of Revenue	4,604,699	5,384,287	6,114,947	7,616,920
Gross Profit	1,606,245	2,483,491	3,118,081	3,541,660
Operating Expense	2,538,578	2,692,292	3,224,363	3,732,498
Operating Income	-932,333	-208,801	-106,282	-190,838
Net Non Operating Interest Income Expense	-85,387	-64,702	-76,913	-64,789
Other Income Expense	-275,061	-199,153	-153,567	-509,226
Pretax Income	-1,292,781	-472,656	-336,762	-764,853
Tax Provision	-16,885	86,967	-185,989	-151,037
Net Income Common Stockholders	-1,275,896	-559,623	-150,773	-613,816
Diluted NI Available to Com Stockholders	-1,275,896	-559,623	-150,773	-613,816
Basic EPS	-	-5.64	-1.24	-4.94
Diluted EPS	-	-5.64	-1.24	-4.94
Basic Average Shares	-	99,249	121,446	124,352
Diluted Average Shares	-	99,249	121,446	124,352
Total Operating Income as Reported	-1,301,774	-407,578	-336,887	-700,064
Total Expenses	7,143,277	8,076,579	9,339,310	11,349,418
Net Income from Continuing & Discontinued Operation	-1,275,896	-559,623	-150,773	-613,816
Normalized Income	-1,004,428	-440,131	-38,669	-205,148
Interest Expense	85,387	64,702	76,913	64,789
Net Interest Income	-85,387	-64,702	-76,913	-64,789
EBIT	-1,207,394	-407,954	-259,849	-700,064
EBITDA	-897,491	-	-	-
Reconciled Cost of Revenue	4,604,699	5,384,287	6,114,947	7,616,920
Reconciled Depreciation	309,903	293,626	340,912	342,511
Net Income from Continuing Operation Net Minority Interest	-1,275,896	-559,623	-150,773	-613,816
Total Unusual Items Excluding Goodwill	-275,061	-199,153	-153,567	-509,226
Total Unusual Items	-275,061	-199,153	-153,567	-509,226
Normalized EBITDA	-622,430	84,825	234,630	151,673
Tax Rate for Calcs	0	0	0	0
Tax Effect of Unusual Items	-3,593	-79,661	-41,463	-100,558
- What would this company need to do to get into a better financial position?
- Produce and verify a compilation.

You must complete each of these steps separately. Once you complete the output, I need you to confirm whether I am satisfied with the output. I will provide guidance and feedback for you to use to produce an output I am comfortable with. Only when I provide the response "Approved" will you proceed to the next step. Before proceeding, I need you to confirm your understanding of these instructions.
```
