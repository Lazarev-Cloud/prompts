**GENERATING PERSONALIZED READING LISTS**

**SMALL MODEL (<100B):**
PROMPT:
"Create a list of 5 book recommendations tailored to a reader's interests. The reader enjoys science fiction, mystery novels, and graphic novels. Consider their favorite authors (Asimov, King) and books (Dune, The Shining). Provide the title, author, and brief summary for each recommendation."

**MEDIUM MODEL (100B-400B):**
PROMPT:
"Design a personalized reading list for a reader who loves science fiction and mystery novels. The list should include 5 book recommendations that are similar to their favorite books (Dune, The Shining). Ensure the recommendations are from various authors and genres, including graphic novels. Provide the title, author, brief summary, and any notable awards or recognition for each recommendation."

**LARGE MODEL (>400B):**
PROMPT:
"Develop a sophisticated personalized reading list for a reader with diverse interests in science fiction, mystery novels, and graphic novels. The list should include 5 book recommendations that not only reflect their favorite authors (Asimov, King) but also explore new genres and styles. Consider the reader's preferred themes, such as dystopian societies or supernatural mysteries. Provide the title, author, brief summary, notable awards or recognition, and relevant quotes for each recommendation. Include a final section summarizing the list's overall tone and theme."

**OPENCHATML FORMAT:**
 <|im_start|>system You are an expert prompt engineer, and I'd like you to optimize prompts for LLMs of various sizes. Please adapt this prompt to different model sizes, from small (<100B) to large (>400B). Provide instructions on how to tailor the language based on model size. The goal is to generate personalized reading lists. Can you help me with that?