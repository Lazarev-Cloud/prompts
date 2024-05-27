**DESIGNING PERSONALIZED LEARNING PATHS**

FOR **LARGE MODEL (10+ BILLION PARAMETERS)**:

CREATE A PROMPT THAT BREAKS DOWN THE TASK INTO LINKED SUBTASKS, WITH RELEVANT EXAMPLES OF DESIRED OUTPUT FORMAT.

PROMPT:
```
<|im_start|>system Design a personalized learning path for a student with the following characteristics: [insert relevant details about the student, such as age, prior knowledge, and learning goals]. The learning path should include [3-5 specific learning objectives], and be tailored to their individual needs and interests.

Example desired output format:
```
**Learning Path Overview**
Student: John Doe
Age: 12
Prior Knowledge: Basic understanding of fractions
Learning Goals: Master addition and subtraction facts, improve problem-solving skills

**Learning Objectives**

1. Master addition facts for numbers up to 20
2. Improve subtraction fact fluency
3. Apply problem-solving strategies to real-world scenarios

**Recommended Learning Activities**

* Watch video tutorials on multiplication tables (5 minutes)
* Practice addition and subtraction facts with interactive games (10 minutes)
* Solve word problems related to everyday life (15 minutes)

<|im_end|><|im_start|>assistant Confirmation of understanding: I will design a personalized learning path for a student, breaking it down into linked subtasks with relevant examples. The desired output format is an overview of the learning path, including student characteristics, learning objectives, and recommended activities.

Please provide the necessary details about the student (age, prior knowledge, learning goals) to proceed with the prompt generation.
```
FOR **MEDIUM-SIZED MODEL (1-10 BILLION PARAMETERS)**:

Simplify the language and focus on key points. Use zero-shot examples for simple cases.

PROMPT:
```
DESIGN A PERSONALIZED LEARNING PATH FOR A STUDENT WITH [INSERT RELEVANT DETAILS ABOUT THE STUDENT]. INCLUDE [3-5 SPECIFIC LEARNING OBJECTIVES] AND TAILOR IT TO THEIR INDIVIDUAL NEEDS.
```
FOR **SMALL MODEL (less than 1 BILLION PARAMETERS)**:

Use even simpler language and focus on key points. Provide concrete examples.

PROMPT:
```
CREATE A PERSONALIZED LEARNING PLAN FOR A STUDENT WITH [INSERT RELEVANT DETAILS ABOUT THE STUDENT]. INCLUDE [2-3 SPECIFIC LEARNING OBJECTIVES] AND MAKE IT TAILORED TO THEIR NEEDS.
```