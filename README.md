documents
=========

Initial Proposal Plan
---------------------

The resume, whether traditional or via an online source such as LinkedIn, is often the first point of contact between a candidate and a potential employer. Research has shown repeatedly that readers of resumes are subject to powerful biases that do not align with true candidate qualifications or potential. Experiments using identical resumes with male vs. female or "black" vs. "white" names showed dramatically different assessments by both recruiters and hiring managers. Even the traditional weight we often given educational and work history are often much less valuable than we assume. Further, "big data" research has identified predictors of candidate qualification and potential hidden amongst the data available in resumes.

Here we propose a project to automatically assess new resumes and produce a "bias" report highlighting likely sources of bias. The tool would be used by recruiters and hiring managers to help mitigate their their natural bias in assessing candidates on paper. The report would include the following:

	1. positive predictors (e.g., unrated schools or rare experience that correlate with candidate success)
	2. negative predictors (e.g., self-reported skills that correlate with poor performance)
	3. false positives (e.g., over-rated schools)
	4. false negative (e.g., gender, race, degree)

All predictors will be determined in purely data driven fashion. In other words, a given school will be flagged as a (false) positive predictor, only if the data show such a relationship with the outcome data. Therefore, the outcome data must be of high quality and present metrics of true value, such as on the job performance; however, initial data will likely be restricted to metrics such as interviews granted, offers made, and offers accepted. To enhance this latter outcome data we will likely need to be augmented with some additional outside research on predictive resume factors (possiblily supplied by Gild Inc. via Vivienne).

The design of the report might come in two board fashions. Resumes themselves might be directly marked-up with highlighting color-coded to the four types of bias. Alternatively (or simultaneously), reports might directly list items of bias. The items might either be group by the type of bias or ordered by the predictive impact of the bias.

Ultimately there are some rough edges to this project. The two most obvious are (1) needing outcome data that is as independent as possible of the very sort of bias we want to prevent and (2) creating a tool that actually changes hiring behavior for the better. We wouldn't want a system that simply replicates the bias implicit in existing interview or job offers. Nor would we want a highly actuate tool that is viewed as a "time-wasting extra step" or "nice idea that doesn't ultimately improve HR metrics".

If we can create an engaging, effective tools for uncovering bias (eventually including individual recruiters or internal talent management), this Data jam project will be a huge hit. It will only get better with use and additional data sources. We can play a formative role in the new field of computational HR.

Vivienne Ming, 2-16-14

Questions
---------

from Vivienne Ming, 2-16-14:

	1. What is the title/product name?
	2. what data will we use? Which of the open data sources descriped at the Data Jam will help the most? What other sources of data might we use?
	3. Can we incoperate the data API being developed by the Data Structuring Data Jam project?
	4. Who will handle the application coding

		1. What is the technolgy stack?
		2. Where will it be hosted?

	5. Which report design will be use?
	6. Where will the resumes come from?
	7. How will they be submitted to the system?
	8. So much more :)


