# **Five-Digit Numerical Encoding Framework Reference Guide**

## **Table of Contents**

1. [Introduction](#introduction)
2. [Encoding Structure Overview](#encoding-structure-overview)
3. [Category Definitions and Codes](#category-definitions-and-codes)
    - [Digit 1: Entities](#digit-1-entities)
    - [Digit 2: Actions](#digit-2-actions)
    - [Digit 3: Objects](#digit-3-objects)
    - [Digit 4: Relationships/Roles](#digit-4-relationshipsroles)
    - [Digit 5: Context](#digit-5-context)
4. [Encoding and Decoding Process](#encoding-and-decoding-process)
5. [Examples](#examples)
6. [Best Practices](#best-practices)
7. [Appendix: Comprehensive Category Tables](#appendix-comprehensive-category-tables)
8. [Conclusion](#conclusion)

---

## **1. Introduction**

Welcome to the **Five-Digit Numerical Encoding Framework Reference Guide**. This guide serves as a comprehensive resource for understanding and utilizing the encoding system designed to represent real-life situations succinctly and effectively. Whether you're encoding simple interactions or complex scenarios, this framework ensures clarity, consistency, and ease of use.

---

## **2. Encoding Structure Overview**

The encoding framework transforms real-life situations into a five-digit numerical code. Each digit corresponds to a specific category, capturing essential elements of the situation. The structure follows the sequence:

```
[Entity][Action][Object][Relationship/Roles][Context]
```

- **Digit 1 (Entity):** Main participant or actor.
- **Digit 2 (Action):** Primary action performed.
- **Digit 3 (Object):** Object or target of the action.
- **Digit 4 (Relationship/Roles):** Relationship between entities or role of the object.
- **Digit 5 (Context):** Contextual information such as time, manner, or conditions.

This systematic approach ensures that each aspect of a situation is encapsulated within a concise numerical representation.

---

## **3. Category Definitions and Codes**

Each digit in the five-digit code represents a category, with subcategories ranging from **0** to **9**. Below are detailed definitions and corresponding codes for each category.

### **Digit 1: Entities**

Entities are the participants or actors involved in the situation.

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

**Notes:**
- **Person (0)** is gender-neutral and serves as a general category.
- **Male (1)** and **Female (2)** provide gender-specific distinctions.
- **Miscellaneous (9)** captures entities that do not fit into other subcategories.

---

### **Digit 2: Actions**

Actions represent the verbs or activities performed by entities.

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

**Notes:**
- **Miscellaneous (9)** is used for actions that do not fit into predefined categories.

---

### **Digit 3: Objects**

Objects are the items or subjects involved in the actions.

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

**Notes:**
- **Miscellaneous (9)** covers objects that do not fit into other subcategories.

---

### **Digit 4: Relationships/Roles**

These define how entities interact with each other or with objects.

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

**Notes:**
- **Agent (0)** typically corresponds to the main entity performing the action.
- **Miscellaneous (9)** handles relationships that are not predefined.

---

### **Digit 5: Context**

Context provides additional information about the action, such as time, manner, or specific conditions.

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

**Notes:**
- **Context** is essential for understanding the temporal and situational aspects of the action.
- **Miscellaneous (9)** is reserved for context elements not predefined.

---

## **4. Encoding and Decoding Process**

### **A. Encoding Rules:**

1. **Identify Components:** Break down the sentence into **Entity**, **Action**, **Object**, **Relationship/Roles**, and **Context**.
2. **Assign Codes:** For each component, assign the corresponding digit based on the definitions.
3. **Sequence the Codes:** Arrange the digits in the order: `[Entity][Action][Object][Relationship/Roles][Context]`.
4. **Use Hyphens for Clarity:** Separate digits with hyphens for readability (e.g., `0-4-9-1-1`).

### **B. Decoding Rules:**

1. **Read the Code:** Examine each digit in the sequence.
2. **Map to Categories:**
   - **First Digit (D1):** Entity
   - **Second Digit (D2):** Action
   - **Third Digit (D3):** Object
   - **Fourth Digit (D4):** Relationship/Roles
   - **Fifth Digit (D5):** Context
3. **Interpret Each Digit:** Use the category definitions to understand each component.
4. **Reconstruct the Sentence:** Combine the interpreted components to form the essence of the situation.

---

## **5. Examples**

### **Example 1: "Emily is helping Dave fix the roof."**

**Step-by-Step Breakdown:**

1. **Entity (D1):**
   - **Emily:** Person → **0**

2. **Action (D2):**
   - **Helping:** Help → **4**

3. **Object (D3):**
   - **Roof:** Miscellaneous Object → **9**

4. **Relationship/Roles (D4):**
   - **Dave as Recipient:** Recipient → **1**

5. **Context (D5):**
   - **Present Action:** Present → **1**

**Final Encoding:**

```
0-4-9-1-1
```

**Interpretation:**

- **0:** Person (Emily)
- **4:** Help
- **9:** Miscellaneous Object (Roof)
- **1:** Recipient (Dave)
- **1:** Present (Action is ongoing)

**Reconstruction:**

"A person (Emily) is helping (action: help) a miscellaneous object (roof) with Dave as the recipient in the present."

---

### **Example 2: "Sarah teaches John mathematics at school."**

**Step-by-Step Breakdown:**

1. **Entity (D1):**
   - **Sarah:** Person → **0**

2. **Action (D2):**
   - **Teaches:** Teach → **5**

3. **Object (D3):**
   - **Mathematics:** Book/Subject → **7**

4. **Relationship/Roles (D4):**
   - **At school:** Location → **3**

5. **Context (D5):**
   - **Present Action:** Present → **1**

**Final Encoding:**

```
0-5-7-3-1
```

**Interpretation:**

- **0:** Person (Sarah)
- **5:** Teach
- **7:** Book/Subject (Mathematics)
- **3:** Location (School)
- **1:** Present (Action is ongoing)

**Reconstruction:**

"A person (Sarah) teaches (action: teach) a subject (mathematics) at a location (school) in the present."

---

### **Example 3: "Alex writes a book for the library."**

**Step-by-Step Breakdown:**

1. **Entity (D1):**
   - **Alex:** Person → **0**

2. **Action (D2):**
   - **Writes:** Create → **0**

3. **Object (D3):**
   - **Book:** Book/Subject → **7**

4. **Relationship/Roles (D4):**
   - **For the library:** Purpose → **8**

5. **Context (D5):**
   - **Future Purpose:** Future → **2**

**Final Encoding:**

```
0-0-7-8-2
```

**Interpretation:**

- **0:** Person (Alex)
- **0:** Create (Write)
- **7:** Book/Subject (Book)
- **8:** Purpose (For the library)
- **2:** Future (Action is intended for the future)

**Reconstruction:**

"A person (Alex) creates (writes) a book with the purpose (for) of the library in the future."

---

### **Example 4: "The dog chased the cat through the garden."**

**Step-by-Step Breakdown:**

1. **Entity (D1):**
   - **Dog:** Animal → **1**

2. **Action (D2):**
   - **Chased:** Miscellaneous Action → **9**

3. **Object (D3):**
   - **Cat:** Animal → **1**

4. **Relationship/Roles (D4):**
   - **Through the garden:** Location → **3**

5. **Context (D5):**
   - **Past Action:** Past → **0**

**Final Encoding:**

```
1-9-1-3-0
```

**Interpretation:**

- **1:** Animal (Dog)
- **9:** Miscellaneous Action (Chase)
- **1:** Animal (Cat)
- **3:** Location (Garden)
- **0:** Past (Action occurred in the past)

**Reconstruction:**

"An animal (dog) performed a miscellaneous action (chase) on another animal (cat) at a location (garden) in the past."

---

### **Example 5: "Maria cooks dinner using a new recipe."**

**Step-by-Step Breakdown:**

1. **Entity (D1):**
   - **Maria:** Person → **0**

2. **Action (D2):**
   - **Cooks:** Miscellaneous Action → **9**

3. **Object (D3):**
   - **Dinner:** Food → **6**

4. **Relationship/Roles (D4):**
   - **Using a new recipe:** Instrument → **6**

5. **Context (D5):**
   - **Present Action:** Present → **1**

**Final Encoding:**

```
0-9-6-6-1
```

**Interpretation:**

- **0:** Person (Maria)
- **9:** Miscellaneous Action (Cook)
- **6:** Food (Dinner)
- **6:** Instrument (Using a new recipe)
- **1:** Present (Action is ongoing)

**Reconstruction:**

"A person (Maria) performs a miscellaneous action (cook) on food (dinner) using an instrument (new recipe) in the present."

---

### **Example 6: "They will travel to Paris next summer."**

**Step-by-Step Breakdown:**

1. **Entity (D1):**
   - **They:** Group → **4**

2. **Action (D2):**
   - **Travel:** Move → **2**

3. **Object (D3):**
   - **Paris:** Miscellaneous Object (since Paris is a place, but Object category is for items) → **9**

4. **Relationship/Roles (D4):**
   - **To Paris:** Destination → **5**

5. **Context (D5):**
   - **Future Action:** Future → **2**

**Final Encoding:**

```
4-2-9-5-2
```

**Interpretation:**

- **4:** Group (They)
- **2:** Move
- **9:** Miscellaneous Object (Paris)
- **5:** Destination
- **2:** Future (Action will occur in the future)

**Reconstruction:**

"A group (they) moves (action: move) to a miscellaneous object (Paris) with the destination being Paris in the future."

**Note:** Since "Paris" is a place, it ideally should be categorized under **Entity (Digit 1)** as **Place (4)**, but the **Object** category is intended for tangible items. To improve accuracy, consider refining the **Object** subcategories or allowing places to be referenced via **Relationship/Roles**.

---

## **6. Best Practices**

1. **Comprehensive Reference:**
   - Always refer to the **Comprehensive Category Tables** (see Appendix) to ensure accurate coding.

2. **Consistency:**
   - Maintain consistent use of codes across all encodings to facilitate reliable decoding.

3. **Use of 'Miscellaneous':**
   - When an element does not fit into predefined subcategories, use the **Miscellaneous (9)** code to maintain structure without compromising the encoding integrity.

4. **Contextual Prioritization:**
   - In the **Context (Digit 5)** category, prioritize the most relevant contextual element. If multiple contexts apply, consider selecting the one that best captures the essence of the action.

5. **Documentation:**
   - Keep this reference guide accessible during the encoding and decoding process to minimize errors.

6. **Iterative Refinement:**
   - Regularly review and refine subcategories based on new scenarios to enhance the framework's robustness.

---

## **7. Appendix: Comprehensive Category Tables**

### **A. Entities (Digit 1)**

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

### **B. Actions (Digit 2)**

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

### **C. Objects (Digit 3)**

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

### **D. Relationships/Roles (Digit 4)**

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

### **E. Context (Digit 5)**

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

## **8. Additional Encoding Examples**

### **Example 7: "The firefighters extinguished the fire in the building yesterday."**

**Step-by-Step Breakdown:**

1. **Entity (D1):**
   - **Firefighters:** Group → **4**

2. **Action (D2):**
   - **Extinguished:** Destroy → **1**

3. **Object (D3):**
   - **Fire:** Miscellaneous Object → **9**

4. **Relationship/Roles (D4):**
   - **In the building:** Location → **3**

5. **Context (D5):**
   - **Past Action:** Past → **0**

**Final Encoding:**

```
4-1-9-3-0
```

**Interpretation:**

- **4:** Group (Firefighters)
- **1:** Destroy
- **9:** Miscellaneous Object (Fire)
- **3:** Location (Building)
- **0:** Past (Action occurred in the past)

**Reconstruction:**

"A group (firefighters) destroyed (action: destroy) a miscellaneous object (fire) at a location (building) in the past."

---

### **Example 8: "The mechanic repaired the car with new parts last week."**

**Step-by-Step Breakdown:**

1. **Entity (D1):**
   - **Mechanic:** Person → **0**

2. **Action (D2):**
   - **Repaired:** Fix → **1**

3. **Object (D3):**
   - **Car:** Vehicle Part → **5**

4. **Relationship/Roles (D4):**
   - **With new parts:** Instrument → **6**

5. **Context (D5):**
   - **Past Action:** Past → **0**

**Final Encoding:**

```
0-1-5-6-0
```

**Interpretation:**

- **0:** Person (Mechanic)
- **1:** Fix
- **5:** Vehicle Part (Car)
- **6:** Instrument (Using new parts)
- **0:** Past (Action occurred in the past)

**Reconstruction:**

"A person (mechanic) fixes (action: fix) a vehicle part (car) using an instrument (new parts) in the past."

---

### **Example 9: "They will travel to Paris next summer."**

**Step-by-Step Breakdown:**

1. **Entity (D1):**
   - **They:** Group → **4**

2. **Action (D2):**
   - **Travel:** Move → **2**

3. **Object (D3):**
   - **Paris:** Miscellaneous Object → **9** (Note: Ideally, places should be handled under **Entity**, but for encoding purposes, it's placed here.)

4. **Relationship/Roles (D4):**
   - **To Paris:** Destination → **5**

5. **Context (D5):**
   - **Future Action:** Future → **2**

**Final Encoding:**

```
4-2-9-5-2
```

**Interpretation:**

- **4:** Group (They)
- **2:** Move
- **9:** Miscellaneous Object (Paris)
- **5:** Destination
- **2:** Future (Action will occur in the future)

**Reconstruction:**

"A group (they) moves (action: move) to a miscellaneous object (Paris) with the destination being Paris in the future."

**Note:** For better accuracy, consider categorizing places under **Entities (Digit 1)** when applicable.

---

### **Example 10: "John quickly finished his homework in the evening."**

**Step-by-Step Breakdown:**

1. **Entity (D1):**
   - **John:** Male → **1**

2. **Action (D2):**
   - **Finished:** Miscellaneous Action → **9**

3. **Object (D3):**
   - **Homework:** Miscellaneous Object → **9**

4. **Relationship/Roles (D4):**
   - **His homework:** Owner → **2**

5. **Context (D5):**
   - **Manner (quickly) and Time of Day (evening):** Manner → **3** (due to single-digit constraint)

**Final Encoding:**

```
1-9-9-2-3
```

**Interpretation:**

- **1:** Male (John)
- **9:** Miscellaneous Action (Finish)
- **9:** Miscellaneous Object (Homework)
- **2:** Owner (John owns the homework)
- **3:** Manner (Quickly)

**Reconstruction:**

"A male (John) performs a miscellaneous action (finish) on a miscellaneous object (homework) owned by him in a manner (quickly)."

*Note:* The time of day ("evening") is not explicitly captured due to the single-digit constraint in the **Context** category.

---

## **9. Best Practices**

1. **Maintain a Comprehensive Reference:**
   - Always refer to the **Comprehensive Category Tables** in the appendix to ensure accurate encoding.

2. **Consistency is Key:**
   - Use the same codes for similar entities, actions, objects, relationships, and contexts across all encodings to maintain reliability.

3. **Utilize 'Miscellaneous' Judiciously:**
   - When an element doesn't fit into any predefined subcategory, assign the **Miscellaneous (9)** code to maintain the structure without forcing inaccurate categorization.

4. **Prioritize Contextual Information:**
   - When multiple contextual elements are present, prioritize the most relevant one to fit into the single-digit constraint of the **Context (Digit 5)** category.

5. **Document Exceptions:**
   - Keep track of commonly used **Miscellaneous (9)** codes and consider revising subcategories if certain elements frequently fall into this category.

6. **Regularly Review and Update:**
   - Periodically assess the framework's effectiveness with new scenarios and refine subcategories as necessary to enhance coverage and reduce reliance on **Miscellaneous (9)** codes.

7. **Develop Supporting Tools:**
   - Create lookup tables, spreadsheets, or software applications to streamline the encoding and decoding process, minimizing manual errors.

8. **Educate Users:**
   - Ensure that all users of the framework are well-versed with the reference guide to promote uniformity and accuracy in encoding.

---

## **10. Conclusion**

The **Five-Digit Numerical Encoding Framework** offers a structured and efficient method to represent real-life situations in a concise, numerical format. By systematically categorizing entities, actions, objects, relationships/roles, and context, this framework ensures that the essence of various interactions is captured effectively. The addition of the fifth digit enhances the framework's ability to convey nuanced information, making it a robust tool for applications such as data analysis, knowledge representation, and information retrieval.

Adhering to this **Comprehensive Reference Guide** will facilitate accurate encoding and decoding, ensuring that the framework remains reliable, realistic, and memorable. Continuous refinement and adherence to best practices will further enhance its applicability and effectiveness in diverse scenarios.

---

# **Appendix: Comprehensive Category Tables**

### **A. Entities (Digit 1)**

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

### **B. Actions (Digit 2)**

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

### **C. Objects (Digit 3)**

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

### **D. Relationships/Roles (Digit 4)**

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

### **E. Context (Digit 5)**

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

Numerical Encoding Framework © 2024 by Blondel Mondésir is licensed under CC BY 4.0 
