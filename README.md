# **EMO-7 Framework Reference Guide**

## **Table of Contents**

1. [Introduction](#1-introduction)
2. [Encoding Structure Overview](#2-encoding-structure-overview)
3. [Category Definitions and Codes](#3-category-definitions-and-codes)
    - [Digit 1: Primary Emotions](#digit-1-primary-emotions)
    - [Digit 2: Triggering Emotions](#digit-2-triggering-emotions)
    - [Digit 3: Entities](#digit-3-entities)
    - [Digit 4: Actions](#digit-4-actions)
    - [Digit 5: Objects](#digit-5-objects)
    - [Digit 6: Relationships/Roles](#digit-6-relationshipsroles)
    - [Digit 7: Context](#digit-7-context)
4. [Encoding and Decoding Process](#4-encoding-and-decoding-process)
5. [Examples Using the EMO-7 Framework](#5-examples-using-the-emo-7-framework)
6. [Best Practices](#6-best-practices)
7. [Appendix: Comprehensive Category Tables](#7-appendix-comprehensive-category-tables)
8. [License](#8-license)

---

## **1. Introduction**

Welcome to the **EMO-7 Framework Reference Guide**. The EMO-7 Framework is a **seven-digit numerical encoding system** designed to represent real-life events by capturing both their **structural elements** and **emotional components**. This framework is particularly useful for researchers in psychology, cognitive science, marketing, education, and any field that benefits from a nuanced understanding of event memorability and emotional impact.

---

## **2. Encoding Structure Overview**

The **EMO-7 Framework** transforms real-life situations into a **seven-digit numerical code**. Each digit represents a specific category, encompassing both emotional and structural aspects of an event.

### **Encoding Structure:**

```
[Primary Emotion][Triggering Emotion][Entity][Action][Object][Relationship/Roles][Context]
```

- **Digit 1:** Primary Emotion (experienced during the event)
- **Digit 2:** Triggering Emotion (evoked upon recalling the event)
- **Digits 3-7:** Original five-digit encoding capturing the structural components:
  - **Digit 3:** Entities
  - **Digit 4:** Actions
  - **Digit 5:** Objects
  - **Digit 6:** Relationships/Roles
  - **Digit 7:** Context

This structured approach ensures a **holistic representation** of events, integrating both emotional depth and factual details.

---

## **3. Category Definitions and Codes**

Each digit in the seven-digit code corresponds to a specific category. Below are the detailed definitions and corresponding codes for each category.

### **Digit 1: Primary Emotions**

Primary emotions are those **experienced during** the event, significantly contributing to its memorability.

| **Code** | **Emotion**         | **Description**                              |
|----------|---------------------|----------------------------------------------|
| **1**    | Joy/Happiness       | Feelings of pleasure, contentment, or elation |
| **2**    | Fear/Anxiety        | Feelings of apprehension, worry, or terror    |
| **3**    | Sadness             | Feelings of sorrow, disappointment, or grief  |
| **4**    | Surprise            | Feelings of astonishment or unexpectedness    |
| **5**    | Anger               | Feelings of frustration, irritation, or rage  |
| **6**    | Love/Affection      | Feelings of deep attachment or fondness       |
| **7**    | Disgust             | Feelings of revulsion or strong disapproval   |
| **8**    | Anticipation        | Feelings of excitement or eagerness           |
| **9**    | Trust               | Feelings of confidence and reliability        |
| **0**    | Miscellaneous       | Any other primary emotions not listed         |

**_Notes:_**

- **Miscellaneous (0):** Use for emotions that do not fit into the predefined categories.
- **Ordering by Impact:** Codes are assigned based on the general impact of the emotion on memorability, with **Joy/Happiness (1)** typically having a high positive impact.

---

### **Digit 2: Triggering Emotions**

Triggering emotions are those **evoked upon recalling** the event, influencing how the memory is processed and felt later.

| **Code** | **Emotion**              | **Description**                              |
|----------|--------------------------|----------------------------------------------|
| **1**    | Nostalgia                | Sentimental longing for the past             |
| **2**    | Pride                    | Satisfaction derived from achievements       |
| **3**    | Happiness                | Feelings of joy or contentment upon recall   |
| **4**    | Remorse/Guilt            | Feelings of regret or responsibility         |
| **5**    | Empathy/Compassion       | Understanding and sharing others' emotions   |
| **6**    | Fear/Anxiety             | Unease or worry when recalling stressful events |
| **7**    | Surprise/Astonishment    | Amazement upon recall                        |
| **8**    | Sadness                  | Sorrow when recalling losses                 |
| **9**    | Motivation/Inspiration   | Drive to act or change upon recall           |
| **0**    | Miscellaneous            | Any other triggering emotions not listed     |

**_Notes:_**

- **Miscellaneous (0):** Reserved for triggering emotions not predefined.
- **Ordering by Impact:** Codes are organized based on their influence on the depth and nature of memory recall.

---

### **Digit 3: Entities**

Entities are the **participants or actors** involved in the situation.

| **Code** | **Subcategory**   | **Description**                          |
|----------|-------------------|------------------------------------------|
| **0**    | Person            | Any individual (gender-neutral)          |
| **1**    | Male              | Male individuals                          |
| **2**    | Female            | Female individuals                        |
| **3**    | Child             | Children                                  |
| **4**    | Group             | Groups of people (e.g., teams, families)  |
| **5**    | Animal            | Domestic or wild animals                  |
| **6**    | Organization      | Companies, institutions, groups           |
| **7**    | Vehicle           | Cars, bikes, trucks, etc.                 |
| **8**    | Technology        | Gadgets, computers, machinery             |
| **9**    | Miscellaneous     | Any other entities not covered above      |

**_Notes:_**

- **Person (0):** A general, gender-neutral category.
- **Miscellaneous (9):** Captures entities that do not fit into other subcategories.

---

### **Digit 4: Actions**

Actions represent the **verbs or activities** performed by entities.

| **Code** | **Subcategory** | **Description**                          |
|----------|-----------------|------------------------------------------|
| **0**    | Create          | Making or producing something            |
| **1**    | Destroy         | Breaking down or demolishing             |
| **2**    | Move            | Transporting or relocating               |
| **3**    | Communicate     | Sharing information or expressing ideas  |
| **4**    | Help            | Assisting or aiding                      |
| **5**    | Teach           | Instructing or educating                 |
| **6**    | Learn           | Acquiring knowledge or skills            |
| **7**    | Use             | Utilizing tools or resources             |
| **8**    | Build           | Constructing or assembling               |
| **9**    | Miscellaneous   | Any other actions not covered above      |

**_Notes:_**

- **Miscellaneous (9):** For actions that do not fit into predefined categories.

---

### **Digit 5: Objects**

Objects are the **items or subjects** involved in the actions.

| **Code** | **Subcategory**      | **Description**                          |
|----------|----------------------|------------------------------------------|
| **0**    | Tool                 | Implements used to perform tasks         |
| **1**    | Device               | Electronic or mechanical devices         |
| **2**    | Furniture            | Items like chairs, tables, etc.          |
| **3**    | Weapon               | Arms or instruments of combat            |
| **4**    | Clothing             | Apparel items                            |
| **5**    | Vehicle Part         | Components of vehicles                   |
| **6**    | Food                 | Edible items                             |
| **7**    | Book/Subject         | Literature or academic subjects          |
| **8**    | Art                  | Creative works like paintings, music     |
| **9**    | Miscellaneous        | Any other objects not covered above      |

**_Notes:_**

- **Miscellaneous (9):** Covers objects that do not fit into other subcategories.

---

### **Digit 6: Relationships/Roles**

These define how entities **interact with each other** or with objects.

| **Code** | **Subcategory** | **Description**                          |
|----------|-----------------|------------------------------------------|
| **0**    | Agent           | The doer of the action                   |
| **1**    | Recipient       | The receiver of the action               |
| **2**    | Owner           | Possessor of an object                   |
| **3**    | Location        | Where the action takes place             |
| **4**    | Source          | Origin of something                      |
| **5**    | Destination     | End point of movement                    |
| **6**    | Instrument      | Tools or means used to perform an action |
| **7**    | Beneficiary     | Who benefits from the action             |
| **8**    | Purpose         | Reason for the action                    |
| **9**    | Miscellaneous   | Any other relationships not covered above|

**_Notes:_**

- **Agent (0):** Typically corresponds to the main entity performing the action.
- **Miscellaneous (9):** Handles relationships that are not predefined.

---

### **Digit 7: Context**

Context provides additional information about the action, such as **time, manner, or specific conditions**.

| **Code** | **Subcategory**   | **Description**                          |
|----------|-------------------|------------------------------------------|
| **0**    | Past              | Action occurred in the past              |
| **1**    | Present           | Action is occurring in the present       |
| **2**    | Future            | Action will occur in the future          |
| **3**    | Manner            | How the action is performed (e.g., quickly, carefully) |
| **4**    | Time of Day       | Specific time reference (e.g., morning, evening) |
| **5**    | Frequency         | How often the action occurs (e.g., daily, weekly) |
| **6**    | Duration          | Length of time the action takes          |
| **7**    | Condition         | Specific conditions or circumstances    |
| **8**    | Location Detail   | More precise location details            |
| **9**    | Miscellaneous     | Any other contextual information not covered above |

**_Notes:_**

- **Miscellaneous (9):** Reserved for context elements not predefined.
- **Contextual Prioritization:** Prioritize the most relevant contextual element if multiple contexts apply.

---

## **4. Encoding and Decoding Process**

### **A. Encoding Rules:**

1. **Identify Components:**
   - Analyze the situation to determine the **Primary Emotion**, **Triggering Emotion**, **Entity**, **Action**, **Object**, **Relationship/Roles**, and **Context**.

2. **Assign Codes:**
   - For each component, assign the corresponding digit based on the category definitions.

3. **Sequence the Codes:**
   - Arrange the digits in the following order:
     ```
     [Primary Emotion][Triggering Emotion][Entity][Action][Object][Relationship/Roles][Context]
     ```

4. **Use Hyphens for Clarity:**
   - Separate the digits with hyphens for readability (e.g., `1-2-0-4-9-1-1`).

### **B. Decoding Rules:**

1. **Read the Code:**
   - Examine each digit in the sequence.

2. **Map to Categories:**
   - **Digit 1:** Primary Emotion
   - **Digit 2:** Triggering Emotion
   - **Digits 3-7:** Structural components (Entity, Action, Object, Relationship/Roles, Context)

3. **Interpret Each Digit:**
   - Refer to the category definitions to understand what each digit represents.

4. **Reconstruct the Situation:**
   - Combine the interpreted components to form a comprehensive understanding of the event, including both its factual details and emotional aspects.

---

## **5. Examples Using the EMO-7 Framework**

### **Example 1: "Emily is helping Dave fix the roof, feeling happy, and upon recalling, they feel pride."**

**Step-by-Step Breakdown:**

1. **Primary Emotion (Digit 1):**
   - **Feeling Happy:** Joy/Happiness → **1**

2. **Triggering Emotion (Digit 2):**
   - **Feel Pride upon recall:** Pride → **2**

3. **Entity (Digit 3):**
   - **Emily:** Person → **0**

4. **Action (Digit 4):**
   - **Helping:** Help → **4**

5. **Object (Digit 5):**
   - **Roof:** Miscellaneous Object → **9**

6. **Relationship/Roles (Digit 6):**
   - **Dave as Recipient:** Recipient → **1**

7. **Context (Digit 7):**
   - **Present Action:** Present → **1**

**Final Encoding:**

```
1-2-0-4-9-1-1
```

**Interpretation:**

- **1:** Joy/Happiness (Primary Emotion)
- **2:** Pride (Triggering Emotion)
- **0:** Person (Emily)
- **4:** Help
- **9:** Miscellaneous Object (Roof)
- **1:** Recipient (Dave)
- **1:** Present

**Reconstruction:**

"Emily is helping Dave fix the roof, feeling happy during the activity, and upon recalling the event, they feel pride."

---

### **Example 2: "Sarah teaches John mathematics at school, experiencing fulfillment, and later, John feels gratitude."**

**Step-by-Step Breakdown:**

1. **Primary Emotion (Digit 1):**
   - **Experiencing Fulfillment:** Pride → **2**

2. **Triggering Emotion (Digit 2):**
   - **John feels Gratitude:** Trust → **9**

3. **Entity (Digit 3):**
   - **Sarah:** Person → **0**

4. **Action (Digit 4):**
   - **Teaches:** Teach → **5**

5. **Object (Digit 5):**
   - **Mathematics:** Book/Subject → **7**

6. **Relationship/Roles (Digit 6):**
   - **At school:** Location → **3**

7. **Context (Digit 7):**
   - **Present Action:** Present → **1**

**Final Encoding:**

```
2-9-0-5-7-3-1
```

**Interpretation:**

- **2:** Pride (Primary Emotion)
- **9:** Trust (Triggering Emotion)
- **0:** Person (Sarah)
- **5:** Teach
- **7:** Book/Subject (Mathematics)
- **3:** Location (School)
- **1:** Present

**Reconstruction:**

"Sarah teaches John mathematics at school, experiencing pride during the lesson, and later, John feels gratitude when recalling the experience."

---

### **Example 3: "Alex writes a book for the library, feeling inspired, and readers feel nostalgia when reading it."**

**Step-by-Step Breakdown:**

1. **Primary Emotion (Digit 1):**
   - **Feeling Inspired:** Trust → **9**

2. **Triggering Emotion (Digit 2):**
   - **Readers feel Nostalgia:** Nostalgia → **1**

3. **Entity (Digit 3):**
   - **Alex:** Person → **0**

4. **Action (Digit 4):**
   - **Writes:** Create → **0**

5. **Object (Digit 5):**
   - **Book:** Book/Subject → **7**

6. **Relationship/Roles (Digit 6):**
   - **For the library:** Purpose → **8**

7. **Context (Digit 7):**
   - **Present Action:** Present → **1**

**Final Encoding:**

```
9-1-0-0-7-8-1
```

**Interpretation:**

- **9:** Trust (Primary Emotion)
- **1:** Nostalgia (Triggering Emotion)
- **0:** Person (Alex)
- **0:** Create (Writes)
- **7:** Book/Subject (Book)
- **8:** Purpose (For the library)
- **1:** Present

**Reconstruction:**

"Alex writes a book for the library, feeling inspired during the process, and readers feel nostalgia when reading it."

---

### **Example 4: "The dog chased the cat through the garden, driven by excitement, and later, the owner recalls the event with amusement."**

**Step-by-Step Breakdown:**

1. **Primary Emotion (Digit 1):**
   - **Dog's Excitement:** Joy/Happiness → **1**

2. **Triggering Emotion (Digit 2):**
   - **Owner's Amusement upon recall:** Happiness → **3**

3. **Entity (Digit 3):**
   - **Dog:** Animal → **5**

4. **Action (Digit 4):**
   - **Chased:** Move → **2**

5. **Object (Digit 5):**
   - **Cat:** Animal → **5**

6. **Relationship/Roles (Digit 6):**
   - **Through the garden:** Location → **3**

7. **Context (Digit 7):**
   - **Past Action:** Past → **0**

**Final Encoding:**

```
1-3-5-2-5-3-0
```

**Interpretation:**

- **1:** Joy/Happiness (Dog's primary emotion)
- **3:** Happiness (Owner's triggering emotion)
- **5:** Animal (Dog)
- **2:** Move (Chased)
- **5:** Animal (Cat)
- **3:** Location (Garden)
- **0:** Past

**Reconstruction:**

"The dog chased the cat through the garden, driven by excitement, and later, the owner recalls the event with amusement."

---

### **Example 5: "Maria cooks dinner using a new recipe, feeling anxious, and upon reflection, she feels accomplished."**

**Step-by-Step Breakdown:**

1. **Primary Emotion (Digit 1):**
   - **Feeling Anxious:** Fear/Anxiety → **2**

2. **Triggering Emotion (Digit 2):**
   - **Feels Accomplished:** Pride → **2**

3. **Entity (Digit 3):**
   - **Maria:** Person → **0**

4. **Action (Digit 4):**
   - **Cooks:** Create → **0**

5. **Object (Digit 5):**
   - **Dinner:** Food → **6**

6. **Relationship/Roles (Digit 6):**
   - **Using a new recipe:** Instrument → **6**

7. **Context (Digit 7):**
   - **Present Action:** Present → **1**

**Final Encoding:**

```
2-2-0-0-6-6-1
```

**Interpretation:**

- **2:** Fear/Anxiety (Maria's primary emotion)
- **2:** Pride (Maria's triggering emotion)
- **0:** Person (Maria)
- **0:** Create (Cooks)
- **6:** Food (Dinner)
- **6:** Instrument (Using a new recipe)
- **1:** Present

**Reconstruction:**

"Maria cooks dinner using a new recipe, feeling anxious during the process, and upon reflection, she feels accomplished."

---

## **6. Best Practices**

### **Integration Benefits:**

- **Comprehensive Representation:** Captures both emotional and structural aspects of events, providing a holistic view.
- **Enhanced Memorability Analysis:** Facilitates deeper insights into why certain events are memorable by analyzing their emotional components.
- **Versatile Application:** Applicable across various fields such as psychology, marketing, education, and event planning.

### **Best Practices:**

1. **Accurate Emotion Identification:**
   - Carefully assess and assign the most appropriate primary and triggering emotion codes based on the context and feelings involved.

2. **Consistent Coding:**
   - Maintain uniformity in code assignments to ensure reliability and comparability across different events.

3. **Clarity in Ambiguity:**
   - When an emotion does not exactly fit a predefined category, select the closest matching code and document any assumptions or interpretations made.

4. **Cultural Sensitivity:**
   - Recognize that emotional expressions and perceptions can vary across cultures. Adjust coding practices to accommodate cultural differences where necessary.

5. **Use of 'Miscellaneous' Codes:**
   - Reserve **Miscellaneous (0)** for emotions and categories that do not fit into predefined subcategories. Regularly review and update category tables to include commonly recurring emotions or entities not initially covered.

6. **Documentation:**
   - Keep detailed records of any custom codes or deviations from the standard framework to maintain clarity and consistency.

7. **Iterative Refinement:**
   - Continuously evaluate and refine the framework based on practical application and feedback to enhance its robustness and applicability.

---

## **7. Appendix: Comprehensive Category Tables**

### **A. Primary Emotions (Digit 1)**

| **Code** | **Emotion**         | **Description**                              |
|----------|---------------------|----------------------------------------------|
| **1**    | Joy/Happiness       | Feelings of pleasure, contentment, or elation |
| **2**    | Fear/Anxiety        | Feelings of apprehension, worry, or terror    |
| **3**    | Sadness             | Feelings of sorrow, disappointment, or grief  |
| **4**    | Surprise            | Feelings of astonishment or unexpectedness    |
| **5**    | Anger               | Feelings of frustration, irritation, or rage  |
| **6**    | Love/Affection      | Feelings of deep attachment or fondness       |
| **7**    | Disgust             | Feelings of revulsion or strong disapproval   |
| **8**    | Anticipation        | Feelings of excitement or eagerness           |
| **9**    | Trust               | Feelings of confidence and reliability        |
| **0**    | Miscellaneous       | Any other primary emotions not listed         |

### **B. Triggering Emotions (Digit 2)**

| **Code** | **Emotion**              | **Description**                              |
|----------|--------------------------|----------------------------------------------|
| **1**    | Nostalgia                | Sentimental longing for the past             |
| **2**    | Pride                    | Satisfaction derived from achievements       |
| **3**    | Happiness                | Feelings of joy or contentment upon recall   |
| **4**    | Remorse/Guilt            | Feelings of regret or responsibility         |
| **5**    | Empathy/Compassion       | Understanding and sharing others' emotions   |
| **6**    | Fear/Anxiety             | Unease or worry when recalling stressful events |
| **7**    | Surprise/Astonishment    | Amazement upon recall                        |
| **8**    | Sadness                  | Sorrow when recalling losses                 |
| **9**    | Motivation/Inspiration   | Drive to act or change upon recall           |
| **0**    | Miscellaneous            | Any other triggering emotions not listed     |

### **C. Entities (Digit 3)**

| **Code** | **Subcategory**   | **Description**                          |
|----------|-------------------|------------------------------------------|
| **0**    | Person            | Any individual (gender-neutral)          |
| **1**    | Male              | Male individuals                          |
| **2**    | Female            | Female individuals                        |
| **3**    | Child             | Children                                  |
| **4**    | Group             | Groups of people (e.g., teams, families)  |
| **5**    | Animal            | Domestic or wild animals                  |
| **6**    | Organization      | Companies, institutions, groups           |
| **7**    | Vehicle           | Cars, bikes, trucks, etc.                 |
| **8**    | Technology        | Gadgets, computers, machinery             |
| **9**    | Miscellaneous     | Any other entities not covered above      |

### **D. Actions (Digit 4)**

| **Code** | **Subcategory** | **Description**                          |
|----------|-----------------|------------------------------------------|
| **0**    | Create          | Making or producing something            |
| **1**    | Destroy         | Breaking down or demolishing             |
| **2**    | Move            | Transporting or relocating               |
| **3**    | Communicate     | Sharing information or expressing ideas  |
| **4**    | Help            | Assisting or aiding                      |
| **5**    | Teach           | Instructing or educating                 |
| **6**    | Learn           | Acquiring knowledge or skills            |
| **7**    | Use             | Utilizing tools or resources             |
| **8**    | Build           | Constructing or assembling               |
| **9**    | Miscellaneous   | Any other actions not covered above      |

### **E. Objects (Digit 5)**

| **Code** | **Subcategory**      | **Description**                          |
|----------|----------------------|------------------------------------------|
| **0**    | Tool                 | Implements used to perform tasks         |
| **1**    | Device               | Electronic or mechanical devices         |
| **2**    | Furniture            | Items like chairs, tables, etc.          |
| **3**    | Weapon               | Arms or instruments of combat            |
| **4**    | Clothing             | Apparel items                            |
| **5**    | Vehicle Part         | Components of vehicles                   |
| **6**    | Food                 | Edible items                             |
| **7**    | Book/Subject         | Literature or academic subjects          |
| **8**    | Art                  | Creative works like paintings, music     |
| **9**    | Miscellaneous        | Any other objects not covered above      |

### **F. Relationships/Roles (Digit 6)**

| **Code** | **Subcategory** | **Description**                          |
|----------|-----------------|------------------------------------------|
| **0**    | Agent           | The doer of the action                   |
| **1**    | Recipient       | The receiver of the action               |
| **2**    | Owner           | Possessor of an object                   |
| **3**    | Location        | Where the action takes place             |
| **4**    | Source          | Origin of something                      |
| **5**    | Destination     | End point of movement                    |
| **6**    | Instrument      | Tools or means used to perform an action |
| **7**    | Beneficiary     | Who benefits from the action             |
| **8**    | Purpose         | Reason for the action                    |
| **9**    | Miscellaneous   | Any other relationships not covered above|

### **G. Context (Digit 7)**

| **Code** | **Subcategory**   | **Description**                          |
|----------|-------------------|------------------------------------------|
| **0**    | Past              | Action occurred in the past              |
| **1**    | Present           | Action is occurring in the present       |
| **2**    | Future            | Action will occur in the future          |
| **3**    | Manner            | How the action is performed (e.g., quickly, carefully) |
| **4**    | Time of Day       | Specific time reference (e.g., morning, evening) |
| **5**    | Frequency         | How often the action occurs (e.g., daily, weekly) |
| **6**    | Duration          | Length of time the action takes          |
| **7**    | Condition         | Specific conditions or circumstances    |
| **8**    | Location Detail   | More precise location details            |
| **9**    | Miscellaneous     | Any other contextual information not covered above |

---

## **4. Encoding and Decoding Process**

### **A. Encoding Rules:**

1. **Identify Components:**
   - Analyze the situation to determine the **Primary Emotion**, **Triggering Emotion**, **Entity**, **Action**, **Object**, **Relationship/Roles**, and **Context**.

2. **Assign Codes:**
   - For each component, assign the corresponding digit based on the category definitions.

3. **Sequence the Codes:**
   - Arrange the digits in the following order:
     ```
     [Primary Emotion][Triggering Emotion][Entity][Action][Object][Relationship/Roles][Context]
     ```

4. **Use Hyphens for Clarity:**
   - Separate the digits with hyphens for readability (e.g., `1-2-0-4-9-1-1`).

### **B. Decoding Rules:**

1. **Read the Code:**
   - Examine each digit in the sequence.

2. **Map to Categories:**
   - **Digit 1:** Primary Emotion
   - **Digit 2:** Triggering Emotion
   - **Digits 3-7:** Structural components (Entity, Action, Object, Relationship/Roles, Context)

3. **Interpret Each Digit:**
   - Refer to the category definitions to understand what each digit represents.

4. **Reconstruct the Situation:**
   - Combine the interpreted components to form a comprehensive understanding of the event, including both its factual details and emotional aspects.

---

## **5. Examples Using the EMO-7 Framework**

### **Example 1: "Emily is helping Dave fix the roof, feeling happy, and upon recalling, they feel pride."**

**Step-by-Step Breakdown:**

1. **Primary Emotion (Digit 1):**
   - **Feeling Happy:** Joy/Happiness → **1**

2. **Triggering Emotion (Digit 2):**
   - **Feel Pride upon recall:** Pride → **2**

3. **Entity (Digit 3):**
   - **Emily:** Person → **0**

4. **Action (Digit 4):**
   - **Helping:** Help → **4**

5. **Object (Digit 5):**
   - **Roof:** Miscellaneous Object → **9**

6. **Relationship/Roles (Digit 6):**
   - **Dave as Recipient:** Recipient → **1**

7. **Context (Digit 7):**
   - **Present Action:** Present → **1**

**Final Encoding:**

```
1-2-0-4-9-1-1
```

**Interpretation:**

- **1:** Joy/Happiness (Primary Emotion)
- **2:** Pride (Triggering Emotion)
- **0:** Person (Emily)
- **4:** Help
- **9:** Miscellaneous Object (Roof)
- **1:** Recipient (Dave)
- **1:** Present

**Reconstruction:**

"Emily is helping Dave fix the roof, feeling happy during the activity, and upon recalling the event, they feel pride."

---

### **Example 2: "Sarah teaches John mathematics at school, experiencing fulfillment, and later, John feels gratitude."**

**Step-by-Step Breakdown:**

1. **Primary Emotion (Digit 1):**
   - **Experiencing Fulfillment:** Pride → **2**

2. **Triggering Emotion (Digit 2):**
   - **John feels Gratitude:** Trust → **9**

3. **Entity (Digit 3):**
   - **Sarah:** Person → **0**

4. **Action (Digit 4):**
   - **Teaches:** Teach → **5**

5. **Object (Digit 5):**
   - **Mathematics:** Book/Subject → **7**

6. **Relationship/Roles (Digit 6):**
   - **At school:** Location → **3**

7. **Context (Digit 7):**
   - **Present Action:** Present → **1**

**Final Encoding:**

```
2-9-0-5-7-3-1
```

**Interpretation:**

- **2:** Pride (Primary Emotion)
- **9:** Trust (Triggering Emotion)
- **0:** Person (Sarah)
- **5:** Teach
- **7:** Book/Subject (Mathematics)
- **3:** Location (School)
- **1:** Present

**Reconstruction:**

"Sarah teaches John mathematics at school, experiencing pride during the lesson, and later, John feels gratitude when recalling the experience."

---

### **Example 3: "Alex writes a book for the library, feeling inspired, and readers feel nostalgia when reading it."**

**Step-by-Step Breakdown:**

1. **Primary Emotion (Digit 1):**
   - **Feeling Inspired:** Trust → **9**

2. **Triggering Emotion (Digit 2):**
   - **Readers feel Nostalgia:** Nostalgia → **1**

3. **Entity (Digit 3):**
   - **Alex:** Person → **0**

4. **Action (Digit 4):**
   - **Writes:** Create → **0**

5. **Object (Digit 5):**
   - **Book:** Book/Subject → **7**

6. **Relationship/Roles (Digit 6):**
   - **For the library:** Purpose → **8**

7. **Context (Digit 7):**
   - **Present Action:** Present → **1**

**Final Encoding:**

```
9-1-0-0-7-8-1
```

**Interpretation:**

- **9:** Trust (Primary Emotion)
- **1:** Nostalgia (Triggering Emotion)
- **0:** Person (Alex)
- **0:** Create (Writes)
- **7:** Book/Subject (Book)
- **8:** Purpose (For the library)
- **1:** Present

**Reconstruction:**

"Alex writes a book for the library, feeling inspired during the process, and readers feel nostalgia when reading it."

---

### **Example 4: "The dog chased the cat through the garden, driven by excitement, and later, the owner recalls the event with amusement."**

**Step-by-Step Breakdown:**

1. **Primary Emotion (Digit 1):**
   - **Dog's Excitement:** Joy/Happiness → **1**

2. **Triggering Emotion (Digit 2):**
   - **Owner's Amusement upon recall:** Happiness → **3**

3. **Entity (Digit 3):**
   - **Dog:** Animal → **5**

4. **Action (Digit 4):**
   - **Chased:** Move → **2**

5. **Object (Digit 5):**
   - **Cat:** Animal → **5**

6. **Relationship/Roles (Digit 6):**
   - **Through the garden:** Location → **3**

7. **Context (Digit 7):**
   - **Past Action:** Past → **0**

**Final Encoding:**

```
1-3-5-2-5-3-0
```

**Interpretation:**

- **1:** Joy/Happiness (Dog's primary emotion)
- **3:** Happiness (Owner's triggering emotion)
- **5:** Animal (Dog)
- **2:** Move (Chased)
- **5:** Animal (Cat)
- **3:** Location (Garden)
- **0:** Past

**Reconstruction:**

"The dog chased the cat through the garden, driven by excitement, and later, the owner recalls the event with amusement."

---

### **Example 5: "Maria cooks dinner using a new recipe, feeling anxious, and upon reflection, she feels accomplished."**

**Step-by-Step Breakdown:**

1. **Primary Emotion (Digit 1):**
   - **Feeling Anxious:** Fear/Anxiety → **2**

2. **Triggering Emotion (Digit 2):**
   - **Feels Accomplished:** Pride → **2**

3. **Entity (Digit 3):**
   - **Maria:** Person → **0**

4. **Action (Digit 4):**
   - **Cooks:** Create → **0**

5. **Object (Digit 5):**
   - **Dinner:** Food → **6**

6. **Relationship/Roles (Digit 6):**
   - **Using a new recipe:** Instrument → **6**

7. **Context (Digit 7):**
   - **Present Action:** Present → **1**

**Final Encoding:**

```
2-2-0-0-6-6-1
```

**Interpretation:**

- **2:** Fear/Anxiety (Maria's primary emotion)
- **2:** Pride (Maria's triggering emotion)
- **0:** Person (Maria)
- **0:** Create (Cooks)
- **6:** Food (Dinner)
- **6:** Instrument (Using a new recipe)
- **1:** Present

**Reconstruction:**

"Maria cooks dinner using a new recipe, feeling anxious during the process, and upon reflection, she feels accomplished."

---

## **6. Best Practices**

### **Integration Benefits:**

- **Comprehensive Representation:** Captures both emotional and structural aspects of events, providing a holistic view.
- **Enhanced Memorability Analysis:** Facilitates deeper insights into why certain events are memorable by analyzing their emotional components.
- **Versatile Application:** Applicable across various fields such as psychology, marketing, education, and event planning.

### **Best Practices:**

1. **Accurate Emotion Identification:**
   - Carefully assess and assign the most appropriate primary and triggering emotion codes based on the context and feelings involved.

2. **Consistent Coding:**
   - Maintain uniformity in code assignments to ensure reliability and comparability across different events.

3. **Clarity in Ambiguity:**
   - When an emotion does not exactly fit a predefined category, select the closest matching code and document any assumptions or interpretations made.

4. **Cultural Sensitivity:**
   - Recognize that emotional expressions and perceptions can vary across cultures. Adjust coding practices to accommodate cultural differences where necessary.

5. **Use of 'Miscellaneous' Codes:**
   - Reserve **Miscellaneous (0)** for emotions and categories that do not fit into predefined subcategories. Regularly review and update category tables to include commonly recurring emotions or entities not initially covered.

6. **Documentation:**
   - Keep detailed records of any custom codes or deviations from the standard framework to maintain clarity and consistency.

7. **Iterative Refinement:**
   - Continuously evaluate and refine the framework based on practical application and feedback to enhance its robustness and applicability.

---

## **7. Appendix: Comprehensive Category Tables**

### **A. Primary Emotions (Digit 1)**

| **Code** | **Emotion**         | **Description**                              |
|----------|---------------------|----------------------------------------------|
| **1**    | Joy/Happiness       | Feelings of pleasure, contentment, or elation |
| **2**    | Fear/Anxiety        | Feelings of apprehension, worry, or terror    |
| **3**    | Sadness             | Feelings of sorrow, disappointment, or grief  |
| **4**    | Surprise            | Feelings of astonishment or unexpectedness    |
| **5**    | Anger               | Feelings of frustration, irritation, or rage  |
| **6**    | Love/Affection      | Feelings of deep attachment or fondness       |
| **7**    | Disgust             | Feelings of revulsion or strong disapproval   |
| **8**    | Anticipation        | Feelings of excitement or eagerness           |
| **9**    | Trust               | Feelings of confidence and reliability        |
| **0**    | Miscellaneous       | Any other primary emotions not listed         |

### **B. Triggering Emotions (Digit 2)**

| **Code** | **Emotion**              | **Description**                              |
|----------|--------------------------|----------------------------------------------|
| **1**    | Nostalgia                | Sentimental longing for the past             |
| **2**    | Pride                    | Satisfaction derived from achievements       |
| **3**    | Happiness                | Feelings of joy or contentment upon recall   |
| **4**    | Remorse/Guilt            | Feelings of regret or responsibility         |
| **5**    | Empathy/Compassion       | Understanding and sharing others' emotions   |
| **6**    | Fear/Anxiety             | Unease or worry when recalling stressful events |
| **7**    | Surprise/Astonishment    | Amazement upon recall                        |
| **8**    | Sadness                  | Sorrow when recalling losses                 |
| **9**    | Motivation/Inspiration   | Drive to act or change upon recall           |
| **0**    | Miscellaneous            | Any other triggering emotions not listed     |

### **C. Entities (Digit 3)**

| **Code** | **Subcategory**   | **Description**                          |
|----------|-------------------|------------------------------------------|
| **0**    | Person            | Any individual (gender-neutral)          |
| **1**    | Male              | Male individuals                          |
| **2**    | Female            | Female individuals                        |
| **3**    | Child             | Children                                  |
| **4**    | Group             | Groups of people (e.g., teams, families)  |
| **5**    | Animal            | Domestic or wild animals                  |
| **6**    | Organization      | Companies, institutions, groups           |
| **7**    | Vehicle           | Cars, bikes, trucks, etc.                 |
| **8**    | Technology        | Gadgets, computers, machinery             |
| **9**    | Miscellaneous     | Any other entities not covered above      |

### **D. Actions (Digit 4)**

| **Code** | **Subcategory** | **Description**                          |
|----------|-----------------|------------------------------------------|
| **0**    | Create          | Making or producing something            |
| **1**    | Destroy         | Breaking down or demolishing             |
| **2**    | Move            | Transporting or relocating               |
| **3**    | Communicate     | Sharing information or expressing ideas  |
| **4**    | Help            | Assisting or aiding                      |
| **5**    | Teach           | Instructing or educating                 |
| **6**    | Learn           | Acquiring knowledge or skills            |
| **7**    | Use             | Utilizing tools or resources             |
| **8**    | Build           | Constructing or assembling               |
| **9**    | Miscellaneous   | Any other actions not covered above      |

### **E. Objects (Digit 5)**

| **Code** | **Subcategory**      | **Description**                          |
|----------|----------------------|------------------------------------------|
| **0**    | Tool                 | Implements used to perform tasks         |
| **1**    | Device               | Electronic or mechanical devices         |
| **2**    | Furniture            | Items like chairs, tables, etc.          |
| **3**    | Weapon               | Arms or instruments of combat            |
| **4**    | Clothing             | Apparel items                            |
| **5**    | Vehicle Part         | Components of vehicles                   |
| **6**    | Food                 | Edible items                             |
| **7**    | Book/Subject         | Literature or academic subjects          |
| **8**    | Art                  | Creative works like paintings, music     |
| **9**    | Miscellaneous        | Any other objects not covered above      |

### **F. Relationships/Roles (Digit 6)**

| **Code** | **Subcategory** | **Description**                          |
|----------|-----------------|------------------------------------------|
| **0**    | Agent           | The doer of the action                   |
| **1**    | Recipient       | The receiver of the action               |
| **2**    | Owner           | Possessor of an object                   |
| **3**    | Location        | Where the action takes place             |
| **4**    | Source          | Origin of something                      |
| **5**    | Destination     | End point of movement                    |
| **6**    | Instrument      | Tools or means used to perform an action |
| **7**    | Beneficiary     | Who benefits from the action             |
| **8**    | Purpose         | Reason for the action                    |
| **9**    | Miscellaneous   | Any other relationships not covered above|

### **G. Context (Digit 7)**

| **Code** | **Subcategory**   | **Description**                          |
|----------|-------------------|------------------------------------------|
| **0**    | Past              | Action occurred in the past              |
| **1**    | Present           | Action is occurring in the present       |
| **2**    | Future            | Action will occur in the future          |
| **3**    | Manner            | How the action is performed (e.g., quickly, carefully) |
| **4**    | Time of Day       | Specific time reference (e.g., morning, evening) |
| **5**    | Frequency         | How often the action occurs (e.g., daily, weekly) |
| **6**    | Duration          | Length of time the action takes          |
| **7**    | Condition         | Specific conditions or circumstances    |
| **8**    | Location Detail   | More precise location details            |
| **9**    | Miscellaneous     | Any other contextual information not covered above |

---

## **4. Encoding and Decoding Process**

### **A. Encoding Rules:**

1. **Identify Components:**
   - Analyze the situation to determine the **Primary Emotion**, **Triggering Emotion**, **Entity**, **Action**, **Object**, **Relationship/Roles**, and **Context**.

2. **Assign Codes:**
   - For each component, assign the corresponding digit based on the category definitions.

3. **Sequence the Codes:**
   - Arrange the digits in the following order:
     ```
     [Primary Emotion][Triggering Emotion][Entity][Action][Object][Relationship/Roles][Context]
     ```

4. **Use Hyphens for Clarity:**
   - Separate the digits with hyphens for readability (e.g., `1-2-0-4-9-1-1`).

### **B. Decoding Rules:**

1. **Read the Code:**
   - Examine each digit in the sequence.

2. **Map to Categories:**
   - **Digit 1:** Primary Emotion
   - **Digit 2:** Triggering Emotion
   - **Digits 3-7:** Structural components (Entity, Action, Object, Relationship/Roles, Context)

3. **Interpret Each Digit:**
   - Refer to the category definitions to understand what each digit represents.

4. **Reconstruct the Situation:**
   - Combine the interpreted components to form a comprehensive understanding of the event, including both its factual details and emotional aspects.

---

## **5. Examples Using the EMO-7 Framework**

### **Example 1: "Emily is helping Dave fix the roof, feeling happy, and upon recalling, they feel pride."**

**Step-by-Step Breakdown:**

1. **Primary Emotion (Digit 1):**
   - **Feeling Happy:** Joy/Happiness → **1**

2. **Triggering Emotion (Digit 2):**
   - **Feel Pride upon recall:** Pride → **2**

3. **Entity (Digit 3):**
   - **Emily:** Person → **0**

4. **Action (Digit 4):**
   - **Helping:** Help → **4**

5. **Object (Digit 5):**
   - **Roof:** Miscellaneous Object → **9**

6. **Relationship/Roles (Digit 6):**
   - **Dave as Recipient:** Recipient → **1**

7. **Context (Digit 7):**
   - **Present Action:** Present → **1**

**Final Encoding:**

```
1-2-0-4-9-1-1
```

**Interpretation:**

- **1:** Joy/Happiness (Primary Emotion)
- **2:** Pride (Triggering Emotion)
- **0:** Person (Emily)
- **4:** Help
- **9:** Miscellaneous Object (Roof)
- **1:** Recipient (Dave)
- **1:** Present

**Reconstruction:**

"Emily is helping Dave fix the roof, feeling happy during the activity, and upon recalling the event, they feel pride."

---

### **Example 2: "Sarah teaches John mathematics at school, experiencing fulfillment, and later, John feels gratitude."**

**Step-by-Step Breakdown:**

1. **Primary Emotion (Digit 1):**
   - **Experiencing Fulfillment:** Pride → **2**

2. **Triggering Emotion (Digit 2):**
   - **John feels Gratitude:** Trust → **9**

3. **Entity (Digit 3):**
   - **Sarah:** Person → **0**

4. **Action (Digit 4):**
   - **Teaches:** Teach → **5**

5. **Object (Digit 5):**
   - **Mathematics:** Book/Subject → **7**

6. **Relationship/Roles (Digit 6):**
   - **At school:** Location → **3**

7. **Context (Digit 7):**
   - **Present Action:** Present → **1**

**Final Encoding:**

```
2-9-0-5-7-3-1
```

**Interpretation:**

- **2:** Pride (Primary Emotion)
- **9:** Trust (Triggering Emotion)
- **0:** Person (Sarah)
- **5:** Teach
- **7:** Book/Subject (Mathematics)
- **3:** Location (School)
- **1:** Present

**Reconstruction:**

"Sarah teaches John mathematics at school, experiencing pride during the lesson, and later, John feels gratitude when recalling the experience."

---

### **Example 3: "Alex writes a book for the library, feeling inspired, and readers feel nostalgia when reading it."**

**Step-by-Step Breakdown:**

1. **Primary Emotion (Digit 1):**
   - **Feeling Inspired:** Trust → **9**

2. **Triggering Emotion (Digit 2):**
   - **Readers feel Nostalgia:** Nostalgia → **1**

3. **Entity (Digit 3):**
   - **Alex:** Person → **0**

4. **Action (Digit 4):**
   - **Writes:** Create → **0**

5. **Object (Digit 5):**
   - **Book:** Book/Subject → **7**

6. **Relationship/Roles (Digit 6):**
   - **For the library:** Purpose → **8**

7. **Context (Digit 7):**
   - **Present Action:** Present → **1**

**Final Encoding:**

```
9-1-0-0-7-8-1
```

**Interpretation:**

- **9:** Trust (Primary Emotion)
- **1:** Nostalgia (Triggering Emotion)
- **0:** Person (Alex)
- **0:** Create (Writes)
- **7:** Book/Subject (Book)
- **8:** Purpose (For the library)
- **1:** Present

**Reconstruction:**

"Alex writes a book for the library, feeling inspired during the process, and readers feel nostalgia when reading it."

---

### **Example 4: "The dog chased the cat through the garden, driven by excitement, and later, the owner recalls the event with amusement."**

**Step-by-Step Breakdown:**

1. **Primary Emotion (Digit 1):**
   - **Dog's Excitement:** Joy/Happiness → **1**

2. **Triggering Emotion (Digit 2):**
   - **Owner's Amusement upon recall:** Happiness → **3**

3. **Entity (Digit 3):**
   - **Dog:** Animal → **5**

4. **Action (Digit 4):**
   - **Chased:** Move → **2**

5. **Object (Digit 5):**
   - **Cat:** Animal → **5**

6. **Relationship/Roles (Digit 6):**
   - **Through the garden:** Location → **3**

7. **Context (Digit 7):**
   - **Past Action:** Past → **0**

**Final Encoding:**

```
1-3-5-2-5-3-0
```

**Interpretation:**

- **1:** Joy/Happiness (Dog's primary emotion)
- **3:** Happiness (Owner's triggering emotion)
- **5:** Animal (Dog)
- **2:** Move (Chased)
- **5:** Animal (Cat)
- **3:** Location (Garden)
- **0:** Past

**Reconstruction:**

"The dog chased the cat through the garden, driven by excitement, and later, the owner recalls the event with amusement."

---

### **Example 5: "Maria cooks dinner using a new recipe, feeling anxious, and upon reflection, she feels accomplished."**

**Step-by-Step Breakdown:**

1. **Primary Emotion (Digit 1):**
   - **Feeling Anxious:** Fear/Anxiety → **2**

2. **Triggering Emotion (Digit 2):**
   - **Feels Accomplished:** Pride → **2**

3. **Entity (Digit 3):**
   - **Maria:** Person → **0**

4. **Action (Digit 4):**
   - **Cooks:** Create → **0**

5. **Object (Digit 5):**
   - **Dinner:** Food → **6**

6. **Relationship/Roles (Digit 6):**
   - **Using a new recipe:** Instrument → **6**

7. **Context (Digit 7):**
   - **Present Action:** Present → **1**

**Final Encoding:**

```
2-2-0-0-6-6-1
```

**Interpretation:**

- **2:** Fear/Anxiety (Maria's primary emotion)
- **2:** Pride (Maria's triggering emotion)
- **0:** Person (Maria)
- **0:** Create (Cooks)
- **6:** Food (Dinner)
- **6:** Instrument (Using a new recipe)
- **1:** Present

**Reconstruction:**

"Maria cooks dinner using a new recipe, feeling anxious during the process, and upon reflection, she feels accomplished."

---

## **6. Best Practices**

### **Integration Benefits:**

- **Comprehensive Representation:** Captures both emotional and structural aspects of events, providing a holistic view.
- **Enhanced Memorability Analysis:** Facilitates deeper insights into why certain events are memorable by analyzing their emotional components.
- **Versatile Application:** Applicable across various fields such as psychology, marketing, education, and event planning.

### **Best Practices:**

1. **Accurate Emotion Identification:**
   - Carefully assess and assign the most appropriate primary and triggering emotion codes based on the context and feelings involved.

2. **Consistent Coding:**
   - Maintain uniformity in code assignments to ensure reliability and comparability across different events.

3. **Clarity in Ambiguity:**
   - When an emotion does not exactly fit a predefined category, select the closest matching code and document any assumptions or interpretations made.

4. **Cultural Sensitivity:**
   - Recognize that emotional expressions and perceptions can vary across cultures. Adjust coding practices to accommodate cultural differences where necessary.

5. **Use of 'Miscellaneous' Codes:**
   - Reserve **Miscellaneous (0)** for emotions and categories that do not fit into predefined subcategories. Regularly review and update category tables to include commonly recurring emotions or entities not initially covered.

6. **Documentation:**
   - Keep detailed records of any custom codes or deviations from the standard framework to maintain clarity and consistency.

7. **Iterative Refinement:**
   - Continuously evaluate and refine the framework based on practical application and feedback to enhance its robustness and applicability.

---

## **7. Appendix: Comprehensive Category Tables**

*(As detailed in Section 3 above.)*

---

## **8. License**

**EMO-7 Framework © 2024 by Blondel Mondésir is licensed under CC BY 4.0**
