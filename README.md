# Lead-Generation-Tool
Tool

-Smart Lead Scorer: Focus Your Sales Efforts!

This tool helps you quickly find the best potential customers from a long list. Instead of guessing, it scores each lead for you, so your sales team knows exactly who to contact first.

-What This Tool Does?

Imagine you have a big list of companies and contacts (like the ones from saasquatchleads.com). This tool takes that list and does two main things:

Scores Each Lead: It looks at different things about a company (like its size, industry, or if it's been in the news for growth) and gives it a "Lead Score" from 0 to 100. Higher scores mean a better match for your business.
Sets a Priority: Based on the score, it tells you if a lead is High, Medium, or Low Priority. This makes it super easy for your sales team to focus on the hottest leads first.

Why It's Useful?

Saves Time: Your sales team stops wasting time on leads that aren't a good fit.
Boosts Sales: By focusing on the best leads, they have a better chance of closing deals.
Smarter Decisions: You get a clearer picture of which companies are most promising.

How to Use It?

Get Ready: Make sure you have Python installed on your computer. You'll also need a library called Pandas. If you don't have it, open your computer's terminal or command prompt and type:
Bash

pip install pandas
Save the Code: Copy the Python code into a file named lead_scoring_tool.py on your computer.
Run the Tool: Open your terminal or command prompt, go to the folder where you saved the file, and type:
Bash

python lead_scoring_tool.py
See the Results:
The tool will print some summary information right in your terminal.
It will also create a new file called scored_leads_output.csv in the same folder. This file is your original lead list, but now with new columns for lead_score and priority!
How to Make It Your Own (Set Preferences)
This tool is flexible! You can easily tell it what's important to your business. Open the lead_scoring_tool.py file in a text editor (like Notepad, VS Code, or Sublime Text). Look for the section that says "--- Configuration ---" near the top.

Here's what you can change:

SCORING_WEIGHTS: Want company size to matter more than their recent news? Change the numbers here. Bigger numbers mean more importance.
Example: 'employee_size_score': 0.5 (makes employee size very important)
INDUSTRY_RELEVANCE: Add your target industries or change how important each industry is. Higher numbers mean more relevant.
Example: 'Healthcare': 5 (if healthcare is a top industry for you)
GROWTH_KEYWORDS: Add words that, if found in a company's news, make them a better lead. Think "new investment," "expanding," "acquisition," etc.
Example: ['new investment', 'expanding', 'big deal']
PRIORITY_THRESHOLDS: Decide what score makes a lead "High," "Medium," or "Low" priority. The score is out of 100.
Example: 'High': 70 (makes more leads "High Priority" if you lower this number)
After you make any changes, save the file and run the script again to see your new settings in action!
