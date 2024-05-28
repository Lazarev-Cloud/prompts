**PROMPT ENGINEERING FOR VARIOUS MODEL SIZES**

**SMALL-LSTM BASED MODEL (<100B PARAMS)**
Create a virtual museum tour that takes users on an interactive journey through art history, highlighting key pieces and events. Include:

* A brief introduction to the tour's theme (e.g., "Exploring Masterpieces of Impressionism")
* Three to five prominent artworks with descriptions and interesting facts
* A call-to-action to explore more at the museum's website or physical location

**MEDIUM-SIZED LLM (<500B PARAMS)**
Design an immersive virtual museum tour that simulates a real-world experience. Include:

* A clear narrative structure, with each stop on the tour building upon the previous one
* At least five prominent artworks with detailed descriptions and insightful commentary
* Interactive elements, such as:
	+ Virtual "rooms" or galleries to explore
	+ Hotspots for additional information or multimedia content (e.g., audio clips, videos)
	+ Opportunities to engage with exhibits through games, quizzes, or challenges

**LARGE-LSTM BASED LLM (<1T PARAMS)**
Create an advanced virtual museum tour that leverages AI-driven storytelling and user engagement. Include:

* A dynamic, adaptive narrative that changes based on the user's interests and interactions
* A vast array of artworks, artifacts, and historical objects to explore
* Advanced interactive features, such as:
	+ Virtual "scavenger hunts" for users to complete
	+ Personalized recommendations for exhibits and activities based on user preferences
	+ Opportunities for users to contribute their own content or stories

**LARGE-SCALE TRANSFORMER BASED LLM (>1T PARAMS)**
Develop an extremely immersive and interactive virtual museum tour that simulates a fully realized, real-world experience. Include:

* A highly detailed, 3D-rendered environment with accurate depictions of artworks and historical settings
* A vast array of user-controlled interactions, such as:
	+ Virtual "walk-throughs" of galleries or exhibitions
	+ Hands-on activities, like manipulating virtual artifacts or participating in interactive games
	+ Opportunities for users to create their own narratives or storytelling

**OPENCHATML FORMAT:**

 <|im_start|>system You will be optimizing prompts for LLMs of various sizes. Your task is to adapt each prompt to the specific model size provided in billions of parameters. Please follow the instructions and tailor your language based on model size (simpler for smaller, more sophisticated for larger). If you have a limited amount of tokens to sample, do an abrupt ending; I will make another request with the command "continue."<|im_end|><|im_start|>assistant Confirmation of understanding: I will optimize prompts for LLMs of various sizes, adapting each prompt to the specific model size provided in billions of parameters. I will follow instructions and tailor my language accordingly. If necessary, I will do an abrupt ending; please indicate with the command "continue."<|im_end|>