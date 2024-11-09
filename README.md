# Logical-Sentence-Evaluation
This project provides a structure for constructing and evaluating logical sentences. It uses Python classes to represent different logical constructs like symbols, negation, conjunctions, disjunctions, implications, and biconditionals. These classes allow us to create complex logical sentences and evaluate their truth values based on a given model.

## **Key Components:**

### **Classes**

**Sentence:** The abstract base class for all logical sentences, including methods for evaluation, formula representation, and symbol extraction.

**Symbol:** Represents individual symbols (variables) in logical sentences.

**Not:** Represents logical negation (¬).

**And:** Represents logical conjunction (∧) to combine multiple conditions.

**Or:** Represents logical disjunction (∨) to capture alternatives.

**Implication:** Models logical implication (=>), e.g., "if A then B."

**Biconditional:** Represents logical biconditional (<=>), e.g., "A if and only if B."


**Methods**

**evaluate(model):** Evaluates whether the sentence is true or false within a given model (a dictionary of symbol truth values).

**formula():** Generates a readable formula of the logical sentence.

**symbols():** Returns all symbols involved in the logical sentence.

**model_check(knowledge, query):** Determines if a knowledge base logically entails a query by checking all possible truth assignments for the symbols.

