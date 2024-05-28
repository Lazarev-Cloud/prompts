**PROMPT ENGINEERING**

**SMALL MODEL (Less than 1 billion parameters):**

CREATE AN INTERACTIVE TRIVIA QUIZ WITH THE FOLLOWING PARAMETERS:
* QUESTION TYPE: MULTIPLE CHOICE
* NUMBER OF QUESTIONS: 5
* TOPIC: HISTORY OF SPACE EXPLORATION

FILL IN THE BLANKS:

Q1: WHAT WAS THE NAME OF THE FIRST SATELLITE LAUNCHED INTO EARTH'S ORBIT? _______________________
A) SPUTNIK 1
B) APOLLO 11
C) CASSINI
D) VOYAGER 1

...

**MEDIUM MODEL (Between 1-3 billion parameters):**

CREATE AN INTERACTIVE TRIVIA QUIZ WITH THE FOLLOWING PARAMETERS:
* QUESTION TYPE: MULTIPLE CHOICE
* NUMBER OF QUESTIONS: 10
* TOPIC: SCIENCE AND TECHNOLOGY

BREAK DOWN THE PROMPT INTO SUBTASKS:

SUBTASK 1: GENERATE 5 QUESTIONS ON THE TOPIC "PHYSICS"
SUBTASK 2: GENERATE 5 QUESTIONS ON THE TOPIC "BIOLOGY"

EXAMPLE QUESTION:
Q3: WHAT IS THE PRINCIPAL FORCE ACTING UPON AN OBJECT IN MOTION?

A) GRAVITY
B) ELECTROMAGNETISM
C) FRICTION
D) BUOYANCY

...

**LARGE MODEL (More than 3 billion parameters):**

CREATE AN INTERACTIVE TRIVIA QUIZ WITH THE FOLLOWING PARAMETERS:
* QUESTION TYPE: MULTIPLE CHOICE, TRUE OR FALSE, AND FILL-IN-THE-BLANKS
* NUMBER OF QUESTIONS: 20
* TOPIC: HISTORICAL FICTIONS

SUBTASK 1: GENERATE 5 QUESTIONS ON THE TOPIC "ANCIENT CIVILIZATIONS"
SUBTASK 2: GENERATE 5 QUESTIONS ON THE TOPIC "MEDIEVAL PERIOD"

EXAMPLE QUESTION:
Q11: IN THE NOVEL "THE LORD OF THE RINGS," WHAT IS THE NAME OF THE FRODO'S TRUSTY COMPANION?

A) SAMWISE GAMGEE
B) MERIADOC BRANDYBUCK
C) ARAGORN SON OF ARATHOR
D) LEGOLAS GREENLEAF

...

**OPENCHATML FORMAT:**

<|im_start|>system You want me to create a prompt for creating interactive trivia quizzes, right? The model size you're looking at is _______________________ (please specify). I'll adapt the prompt accordingly. Please confirm if I'm correct or not. <|im_end|>

Assistant: Confirmation of understanding and concise summary of key instructions:

Yes, that's correct! You want me to generate a prompt for creating interactive trivia quizzes, tailored to a specific model size you will provide. I'll break down the prompt into linked subtasks, include relevant examples, and mirror important details from the original prompt. I'll also adapt the language based on the model size, using zero-shot or multi-shot examples as needed. Please specify the model size, and I'll get started!