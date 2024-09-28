Homework 3: Text Mining & Sentiment

The objective of this homework is to practice text mining and sentiment techniques. This includes acquiring text, pre-processing it, creating a DTM, and executing sentiment.

Your video must explain what you did for each parts (1) through (5) and also part (7). You may also attempt part (6) for extra credit. You will need to submit multiple files to Blackboard. See the submission requirements and reminders on the next page.

(1)	0 points. Identify a web site that gathers people’s opinions on something. This could be Yelp, Reddit, Quora, Amazon, Google Maps, etc. Find a topic/product/location that has at least 50 reviews. You want most of these reviews to be at least 3-4 sentences long. Use web scraping techniques from Module 1 to load these reviews.
(2)	25 points. Pre-process the text. At a minimum, ensure that the tokens are not case or punctuation sensitive, that common words have been removed, and that your analysis is not sensitive to minor variations in word endings. You may do more pre-processing if you believe it is helpful.
(3)	30 points. Get dictionary sentiment scores for each review. Do this by first making a DTM from your processed text. For each row of the DTM (that is, for each review), generate a sentiment score from a dictionary-based method (NRC, AfiNN, Bing, etc.). So if you have 50 reviews, you should get 50 sentiment scores.
(4)	15 points. For each review, determine whether it is positive, neutral, or negative. If the review has a star rating, you might try to apply binning to recode the star rating into these three categories. If the review doesn’t have a star rating or other numeric score you may have to read the reviews yourself and label them as positive, neutral, or negative.
(5)	15 points. Create a data visualization, following the principles taught in Module 2, to compare the sentiment scores from part (3) with the polarity of the review you got from part (4). Discuss this plot in your video. Is it as you expected? Were you surprised?
(6)	BONUS 25 points. Research how to write code to use an LLM (BERT, DistilBERT, a GPT model, etc.) to get a sentiment score. Use a pre-trained version of the LLM to do this. Create additional data visualizations that compare this new sentiment score with the sentiment score in part (3) and with the polarity score in part (4). Discuss these new plots in your video.
a.	Hint: you might search for something like “distilbert sentiment pretrained”.
b.	You should expect this code to take a long time to load and run and to potentially have difficulties loading the necessary libraries on your computer.
c.	You should expect that you will probably have to do this in Python. 
(7)	15 points. Create a CSV or Excel file which contains a row for each review, with a column for each of: the original review text from part (1), the processed text from part (2), the sentiment score from part (3), the polarity from part (4), and if you attempt the bonus, the sentiment score from part (6).


Submission requirements: you should upload 4 files (or 4-6 files if you attempt the bonus)
•	Code (.r, .py, .ipynb, .rmd, etc.)
•	An image file (.png, .jpg, etc.) or document (.docx, .pdf, etc.) with the graph from part (5)
•	CSV or Excel file from part (7)
•	Video recording (.mov, .mp4, etc.), or a Word document containing a URL that points to your video. The video should address all 6 required steps. If you send a URL and a log-in is required to access the link, you must provide clear instructions to your facilitator on how to log in.
•	If you attempt the bonus, upload 2 additional image files, or be sure you have included them in the document you’ve already started.

Reminders:
•	Your homework grade is based on the following:
1.	Do you correctly understand the problem?
2.	Are you using the correct algorithm?
3.	Does your code run properly and perform all requested tasks?
4.	Are you able to interpret the results correctly?
5.	Are you able to explain your code and answer any questions I or your facilitator might ask?
•	Facilitators can deduct 5% for each day the assignment is late. You may submit one (and only one) of the six assignments up to three days late with no penalty but all other assignments will be penalized.
•	Unless your facilitator or the professor agrees, your assignment will not be graded if it is more than 3 days late (e.g., no credit will be given after Friday at 6 AM Boston time). The professor will usually ask the facilitator to make the decision but in rare cases (<1% of the time) has overridden a facilitator. Do not expect the professor to override in most cases.
•	If you have any questions, please try the “Ask the Professor” discussion board first unless doing so might give away the answer to the class.
•	If you still need help, contact your facilitator to schedule an appointment to help you progress in your homework.


# CS688 Assignment3 代写

# 程序代做代写辅导

# 专业辅导，已辅导上千名留学生，帮助其获得高分

# Contact Me:

# WeChat: robotclx

# CS Professional Tutoring

# I can help you for Python,Java,C,C#,C++,Javascript,html,go,rust,database......

# 英国，澳洲，美国，日本，韩国等各国均可辅导，均可提供服务

# 在要求的范围内，可免费售后，可走平台

# 记得备注您是从github来的哦~

# Email: bu32221@163.com
