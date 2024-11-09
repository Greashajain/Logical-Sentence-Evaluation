# Logical-Sentence-Evaluation
This project provides a structure for constructing and evaluating logical sentences. It uses Python classes to represent different logical constructs like symbols, negation, conjunctions, disjunctions, implications, and biconditionals. These classes allow us to create complex logical sentences and evaluate their truth values based on a given model.

## **Key Components:**

### **Classes:**

**1.Sentence:** The abstract base class for all logical sentences, including methods for evaluation, formula representation, and symbol extraction.

**2.Symbol:** Represents individual symbols (variables) in logical sentences.

**3.Not:** Represents logical negation (¬).

**4.And:** Represents logical conjunction (∧) to combine multiple conditions.

**5.Or:** Represents logical disjunction (∨) to capture alternatives.

**6.Implication:** Models logical implication (=>), e.g., "if A then B."

**7.Biconditional:** Represents logical biconditional (<=>), e.g., "A if and only if B."


### **Methods:**

**1.evaluate(model):** Evaluates whether the sentence is true or false within a given model (a dictionary of symbol truth values).

**2.formula():** Generates a readable formula of the logical sentence.

**3.symbols():** Returns all symbols involved in the logical sentence.

**4.model_check(knowledge, query):** Determines if a knowledge base logically entails a query by checking all possible truth assignments for the symbols.

### **Model Checking:**

The model_check function verifies if a knowledge base implies a query by evaluating every possible truth assignment. This can be useful for scenarios in propositional logic, automated reasoning, and AI applications.

### **Installation:**

Clone the repository and ensure Python 3.x is installed. No additional packages are required.

### **Usage:**

Define a logical sentence and model, and use evaluate to check the sentence’s truth value based on the model. See examples in the code comments.
