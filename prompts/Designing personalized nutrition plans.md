**PROMPT GENERATION FOR LLM OF SIZE 10 BILLION PARAMETERS**

**INITIAL PROMPT**
Design a personalized nutrition plan for an individual with [insert dietary restrictions/preferences, e.g., vegan, gluten-free, low-carb] and [insert health goals, e.g., weight loss, improved energy]. The plan should include:

1. A daily meal plan consisting of [number] meals with [insert specific food items or categories, e.g., lean proteins, whole grains, leafy greens]
2. Snack suggestions to maintain [desirable trait, e.g., hunger satisfaction, blood sugar control]
3. Recommendations for [specific nutrient or vitamin, e.g., omega-3 fatty acids, vitamin D] supplementation

**KEY DETAILS TO MIRROR FROM ORIGINAL PROMPT**

* Dietary restrictions/preferences
* Health goals
* Meal plan requirements (e.g., number of meals, specific food items)

**ZERO-SHOT EXAMPLE**
Please provide a sample 3-day meal plan for someone who is lactose intolerant and aims to increase their fiber intake.

**LLM AGENT INSTRUCTIONS**

1. Break down the prompt into linked subtasks:
	* Identify dietary restrictions/preferences
	* Determine health goals
	* Generate daily meal plan considering above factors
	* Recommend snacks and supplements
2. Use relevant examples of desired output format (e.g., sample 3-day meal plan)
3. Mirror key details from original prompt in response

**LLM AGENT ROLE**
Dietary Advisor

**CONTEXT**
The LLM agent is tasked with designing a personalized nutrition plan for an individual with specific dietary restrictions/preferences and health goals.

**PROMPT TAILORED FOR LLM OF 10 BILLION PARAMETERS**

To optimize the prompt for an LLM of this size, I've included more specific examples and subtasks to facilitate the generation of a comprehensive and detailed personalized nutrition plan. The use of zero-shot examples allows the model to understand the desired output format and mirrors key details from the original prompt.

**FINAL PROMPT**
Design a personalized nutrition plan for an individual with [insert dietary restrictions/preferences, e.g., vegan, gluten-free] and [insert health goals, e.g., weight loss]. The plan should include:

1. A daily meal plan consisting of [number] meals with [insert specific food items or categories]
2. Snack suggestions to maintain [desirable trait]
3. Recommendations for [specific nutrient or vitamin] supplementation

Please provide a sample 5-day meal plan considering the above factors.

**CONTINUE?**

Type "yes" to continue with the prompt, or "no" to modify it further.