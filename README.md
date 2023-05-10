# Propositional Logic Translator
A tool that can translate natural language statements into propositional logic symbols. The tool will also be equipped with logic rules validation features to check the validity of the generated propositions.

Propositional Logic is a branch of mathematical logic that deals with propositions or statements that are either true or false. It is also called "sentential logic" or "propositional calculus." In propositional logic, statements are represented using symbols such as "P," "Q," "R," etc., and logical operators such as "not," "and," "or," and "implies" are used to connect these statements.

## The rules of propositional logic include:

* Negation: If P is a proposition, then the negation of **P** is denoted by **¬P** and means "not P."
* Conjunction: If P and Q are propositions, then the conjunction of P and Q is denoted by **P ∧ Q** and means **"P and Q."**
* Disjunction: If P and Q are propositions, then the disjunction of P and Q is denoted by **P ∨ Q** and means **"P or Q."**
* Implication: If P and Q are propositions, then the implication of P and Q is denoted by **P → Q** and means **"if P, then Q."**

## Value and Impact:

The benefits of propositional logic include its simplicity and clarity, which make it easy to understand and use. It is also useful in AI because it can be used to represent and reason about knowledge in a formal and precise way. Propositional logic is a formal system of symbolic logic that deals with propositions and their logical relationships. It has numerous benefits and applications in AI, some of which are:

* Formalizing Knowledge: Propositional logic can be used to formalize knowledge and represent it in a logical form that can be easily processed and manipulated by computers. This is particularly useful in AI applications that require reasoning and decision-making based on logical rules.

* Inference and Deduction: Propositional logic provides a systematic method for making inferences and deductions based on logical rules. This is useful in AI applications such as expert systems, where the system needs to make decisions based on a set of logical rules.

* Natural Language Processing: Propositional logic can be used to represent natural language statements in a structured form that can be easily analyzed and processed by computers. This is useful in AI applications such as sentiment analysis and language translation.

* Machine Learning: Propositional logic can be used in machine learning algorithms to model complex relationships between variables and make predictions based on logical rules. This is useful in AI applications such as decision trees and rule-based systems.

* Automated Reasoning: Propositional logic provides a framework for automated reasoning, which can be used to automate tasks such as theorem proving, planning, and scheduling. This is useful in AI applications such as automated planning and scheduling systems.

## Examples
Here are some examples of how to use the translator and validator:

![image](https://user-images.githubusercontent.com/101527083/234134960-2e10ce49-bf86-4254-a96e-84ca8acaf9de.png)

![image](https://user-images.githubusercontent.com/101527083/234135059-09e4e30d-8e54-453b-848e-ee4fe6d1b6f3.png)

Rules of inference are logical principles that allow us to infer new statements from given premises. These rules are used in formal logic to determine the validity of an argument, which is the extent to which its premises logically support its conclusion. Here are some common rules of inference used to check the validity of premises:

**Modus Ponens**: This rule states that if we have a conditional statement of the form "if A, then B," and we know that A is true, we can infer that B is also true. Symbolically, **if A → B and A, then we can infer B**.

**Modus Tollens**: This rule is the contrapositive of modus ponens. It states that if we have a conditional statement of the form "if A, then B," and we know that B is false, we can infer that A must also be false. Symbolically, **if A → B and ~B, then we can infer ~A**.

**Disjunctive Syllogism**: This rule allows us to infer the truth of one of two disjuncts if we know that the other is false. If we have a disjunctive statement of the form "A or B," and we know that A is false, we can infer that B must be true. Symbolically, **if A ∨ B and ~A, then we can infer B**.

**Hypothetical Syllogism**: This rule allows us to chain together conditional statements. If we have two conditional statements of the form "if A, then B" and "if B, then C," we can infer a third conditional statement of the form "if A, then C." Symbolically, **if A → B and B → C, then we can infer A → C**.

**Conjunction**: This rule allows us to combine two true statements into a single statement. If we know that A and B are both true, we can infer that "A and B" is also true. Symbolically, **if A and B, then we can infer A ∧ B**.

**Simplification**: This rule is the inverse of conjunction. It allows us to derive a statement from a conjunction of two statements. If we know that "A and B" is true, we can infer that A is true and B is true. Symbolically, **if A ∧ B, then we can infer A and B**.

**Addition**: This rule allows us to add a statement to a conjunction. If we know that A is true, we can infer that "A or B" is true. Symbolically, **if A, then we can infer A ∨ B**.

These are just a few examples of the many rules of inference used in formal logic. By applying these rules correctly, we can determine the validity of premises and evaluate the strength of arguments.

![image](https://github.com/Arwa-Fawzy/Propositional-Logic-Translator/assets/101527083/8ded7df3-9265-47e3-af39-77fcb70eba65)

