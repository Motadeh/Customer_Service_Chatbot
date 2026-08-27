# Customer_Service_Chatbot

The project is organised according to the project rubric sectioning, into Classification and Routing, Bug Report, Platform Question and other Request paths, and Testing and Evaluation.


## Classification and Routing

The Classification and Routing folder contains the following:

- flow_diagram_1.png and flow_diagram_2.png: showing screenshot of full flow diagram.
- Classifier_prompt_configuration_1.png and Classifier_prompt_configuration_2.png: showing screenshot of classifier prompt configuration.
- Condition_node_expressions_1.png and Condition_node_expressions_2.png: shwoing screenshot of Condition node expressions.
A guardrail folder: contains a screenshot of guardrail configuration in flow (Guardrail_setup_1.png), a screenshot of guardrail interruption in flow (Guardrail_interruption.png) and a screenshots of the guardrail in bedrock (Guardrail_prompt_setup.png)


## Bug Report

The bug report folder contains the following files:

- DynamoDB_table_1.png and DynamoDB_table_2.png: screenshot of database in aws dynamoDB showing items created by the chatbot.
- system_prompt.txt showing routes and collection rules.
- transcript.txt: showing chat.py transcript of a bug report.


## Platform Questions and Other Requests Paths

This folder contains the following:

- FAQ_covered_1.png, FAQ_covered_2.png, and FAQ_covered_3.png: screenshot of flow test response for a covered question
- FAQ_uncovered_1.png.png and FAQ_uncovered_2.png: screenshot for uncovered question.
- other_questions.png: screenshot for other questions
- A folder named FAQ_prompt_setup: containing screenshots (FAQ_prompt_configuration_1.png, FAQ_prompt_configuration_2.png) of frequently asked questions prompt configuration and a folder named knowledge base that has knowledge_base_1.png, knowledge_base_2.png and knowledge_base_3.png that shows the screenshot of created knowledge base, screenshot of knowledge base node configuration (FAQ_Knowledge_base_node_configuration.png), and screenshot of the FAQ questions in s3.


## Testing and Evaluation

Contains the following:

- harness-tests.json: contains test questions for evaluation.
- output_eval_dataset.jsonl: contains the output responses from the evaluation
- Evaluation_metrics.png: screenshot of Bedrock Evaluation job results page.
- Guardrail_for_harness.png: screenshot of the guardrail implementation for guardrail cases for prompt interruption and insulting language.
- observation.txt: contains observations from running the chat bot.