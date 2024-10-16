Step 1:
To test: go to Executable -> dist -> fqexec.exe
A terminal will open and soon a input GUI will be visible. You can enter prompts/ask question to get the response.


Step 2:
Technical Solution -> faqmodel.ipynb
I have created a simple bayesian model which can answer some of the questions or prompts.
Run All Cells. At the end, a python terminal will open in which you can simply put your prompt and get answer.
Drawbacks: Less data so less accuracy and sometime no response.

Then I have used cosine similarity to get the best faq match from existing faq list.
Followed by that, the bayesian model naturally generates text based on a given input.



Precomputed data 1MB
GUI DATA 630 MB (For exe only dur to modules. However actual model saves only about 1 MB of data so it lightweight to deploy)


You can deploy this by Backend for Frontend Architecture.

ReactJS/NextJS
Front-END                --->       Express/NestJS (BFF) -<-----------> Flask (Running the executable in flask environment)

Submission by Sonit Patil
IIT Hyderabad

Thank You.