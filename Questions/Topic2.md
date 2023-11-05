## Sample of Questions
# Knowledge Representation

Please identify whether the statements below are propositions or not, and provide justification.

1. "Apples are typically red or green." (True/False?)
   - Proposition: True. This is a declarative statement that can be evaluated as true because apples can be red or green.

2. "Bananas are sweet and creamy in taste." (True/False?)
   - Proposition: True. This is a declarative statement that can be evaluated as true because bananas are known for their sweet and creamy taste.

3. "Oranges are an excellent source of Vitamin C." (True/False?)
   - Proposition: True. This is a declarative statement that can be evaluated as true because oranges are an excellent source of Vitamin C.

4. "Apples have a salty taste." (True/False?)
   - Proposition: True. This is a declarative statement that can be evaluated as false because, in reality, apples do not have a salty taste.

5. "I like oranges." (True/False?)
   - Proposition: False. The statement has an indefinite truth value, which can be either true or false, but not both.

6. "What fruits do you like?" (True/False?)
   - Proposition: False. It does not make a factual assertion. The statement is in the form of a question, specifically an open-ended question asking for information about someone's preferences.
  
---------------------------------------------------------------------------------

Here are the multiple-choice questions in Markdown format with the correct answers highlighted:

1. In the FOL statement "likes(john, apples)," what are the constants?

   a. likes and john
   b. likes and apples
   c. **john and apples**
   d. likes, john, and apples

2. In the FOL statement "likes(john, apples)," what is "likes"?

   a. A constant
   b. **A predicate**
   c. A variable
   d. A function

3. What is the purpose of variables in FOL?

   a. To represent constants
   b. To represent properties and relations
   c. To qualify values of constants
   d. **To represent any object**

4. In the FOL statement "∀X likes(X, apples)," what does "∀X" represent?

   a. A constant
   b. A predicate
   c. A function
   d. **A universal quantifier**

---------------------------------------------------------------------------------

Below are the propositions (A to E) for the fruit chatbot. These propositions can be used to represent various characteristics and attributes of different types of fruits in the chatbot's knowledge base. Convert the English sentences in parts (I) – (IV) into standard predicate logic sentences when given the following propositions:

- **A: x is a type of fruit.**
- **B: x is a common color of fruits.**
- **C: x is a fruit that is in season.**
- **D: x has a specific nutritional value.**
- **E: x is a fruit with a distinct aroma.**

1. "Some fruits are in season." 
   - Predicate Logic: ∃x (C(x))

2. "All fruits have a common color." 
   - Predicate Logic: ∀x (B(x))

3. "There exist fruits with a distinct aroma." 
   - Predicate Logic: ∃x (E(x))

4. "Not all fruits are in season." 
   - Predicate Logic: ¬∀x (C(x))

5. "Some fruits have a specific nutritional value." 
   - Predicate Logic: ∃x (D(x))

6. "All fruits are types of fruit." 
   - Predicate Logic: ∀x (A(x))

7. "There exist fruits that are not in season." 
   - Predicate Logic: ∃x (¬C(x))

8. "No fruits have a distinct aroma." 
   - Predicate Logic: ¬∃x (E(x))

9. "Some fruits are not a type of fruit." 
   - Predicate Logic: ∃x (¬A(x))
_________________________________________________________________________________________________________

**1. Given the notations:**
   - p = my breakfast is eggs.
   - q = my breakfast is cereal.
   - r = (my breakfast is) toast.

   a. Write the logic form (expression) for this statement 'my breakfast is either eggs or cereal, and toast'.

   **Answer:** The logic form (expression) for the statement 'my breakfast is either eggs or cereal, and toast' is: (p ∨ q) ∧ r.

   b. Complete the truth table for the above expression in (a).

   **Answer:**

|  p  |  q  |  r  | (p ∨ q) ∧ r |
|:---:|:---:|:---:|:------------:|
|  0  |  0  |  0  |      0       |
|  0  |  0  |  1  |      1       |
|  0  |  1  |  0  |      0       |
|  0  |  1  |  1  |      1       |
|  1  |  0  |  0  |      0       |
|  1  |  0  |  1  |      1       |
|  1  |  1  |  0  |      0       |
|  1  |  1  |  1  |      1       |

In the truth table:
- 'p,' 'q,' and 'r' represent the values of the statements 'eggs,' 'cereal,' and 'toast,' respectively.
- The expression (p ∨ q) ∧ r represents the statement 'my breakfast is either eggs or cereal and toast.'
- A 1 indicates that the statement is true for a given combination of values, while a 0 indicates that the statement is false.


   c. Write the English sentence for (p AND q) OR r.

   **Answer:** The English sentence for (p AND q) OR r is: "My breakfast is both eggs and cereal, or it is toast."

   d. Write the English sentence for (NOT p) OR q.

   **Answer:** The English sentence for (NOT p) OR q is: "I do not have eggs for breakfast, or I have cereal for breakfast."

**2. I want pizza A, maybe pizza B, but I also want pizza C. Which pizza combinations will make me happy?**

**Answer:** To find out which pizza combinations will make you happy, you can choose pizza A and optionally add pizza B, but you must also include pizza C in the combination to be happy. In symbolic form, this can be expressed as: A ∧ (B ∨ C).

_________________________________________________________________________________________________________
![AIKR](https://github.com/rohayanti/Artificial-Intelligent/blob/main/image/AIKR.png)
