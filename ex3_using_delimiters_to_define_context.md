# Objective: Restrict responses to a specific block of text.

**Prompt 1:**
```
Who was Martin Luther King Jr?
Answer using only the text inside the delimiters
Use only the text provided below.
```Martin Luther King Jr. was an African American leader who lived from 1929 to 1968. He worked to help people be treated fairly and equally. We remember him with a national holiday.``` Read on to learn about other African Americans who have made a difference in the history of the United States.

Famous African Americans
Who are some African American leaders who have changed history?

Rosa Parks fought for civil rights for African Americans. Civil rights make sure people are treated equally under the law. In 1955, she was arrested in Alabama for not giving up her bus seat to a white man.

Jackie Robinson batted his way into history. In 1947, he became the first African American to play major-league baseball.

George Washington Carver was a famous inventor who found more than 300 uses for peanuts. He discovered that peanuts could be used to make soap, glue, and paint.

Oprah Winfrey is a talk show host and an actor. She helps children around the world. She helped build schools and gave supplies to more than 50,000 needy children in South Africa.

Condoleezza Rice is the first African American woman to be the U.S. Secretary of State. In this important job, she helped the U.S. President work with the governments of other countries.

A Special Speech
In 1963, Martin Luther King Jr. gave his famous "I Have a Dream" speech. He spoke in Washington, D.C., in front of the Lincoln Memorial. During the speech, Martin Luther King Jr. shared his hope that all people would be treated equally.

"I have a dream that my four little children will one day live in a nation where they will not be judged by the color of their skin but by the content of their character. I have a dream today. "

— Martin Luther King Jr.
```

**Response 1:**
```
Martin Luther King Jr. was an African American leader who lived from 1929 to 1968. He worked to help people be treated fairly and equally. We remember him with a national holiday.
```

**Prompt 2:**
```
Who was Martin Luther King Jr?
Use only the text provided in the passage below.
Martin Luther King Jr. was an African American leader who lived from 1929 to 1968. He worked to help people be treated fairly and equally. We remember him with a national holiday. Read on to learn about other African Americans who have made a difference in the history of the United States.

Famous African Americans
Who are some African American leaders who have changed history?

Rosa Parks fought for civil rights for African Americans. Civil rights make sure people are treated equally under the law. In 1955, she was arrested in Alabama for not giving up her bus seat to a white man.

Jackie Robinson batted his way into history. In 1947, he became the first African American to play major-league baseball.

George Washington Carver was a famous inventor who found more than 300 uses for peanuts. He discovered that peanuts could be used to make soap, glue, and paint.

Oprah Winfrey is a talk show host and an actor. She helps children around the world. She helped build schools and gave supplies to more than 50,000 needy children in South Africa.

Condoleezza Rice is the first African American woman to be the U.S. Secretary of State. In this important job, she helped the U.S. President work with the governments of other countries.

A Special Speech
In 1963, Martin Luther King Jr. gave his famous "I Have a Dream" speech. He spoke in Washington, D.C., in front of the Lincoln Memorial. During the speech, Martin Luther King Jr. shared his hope that all people would be treated equally.

"I have a dream that my four little children will one day live in a nation where they will not be judged by the color of their skin but by the content of their character. I have a dream today. "

— Martin Luther King Jr.
```

**Response 2:**
```
Martin Luther King Jr. was an African American leader who lived from 1929 to 1968. He worked to help people be treated fairly and equally.

In 1963, he gave his famous “I Have a Dream” speech. He spoke in Washington, D.C., in front of the Lincoln Memorial. During the speech, Martin Luther King Jr. shared his hope that all people would be treated equally.

We remember him with a national holiday.
```

**Deduction**
The output with delimiter in the prompt used only information about Martin Luther King inside the delimiter to answer the question. While for the other prompt without delimiter, all information about Martin Luther King in the text was utilized by the model when answering the question.