# Swing-calculator-U23PH1017

Name: VITALIS JULIUS KINGDAVID 

Matric number:U23PH1017

Department: Physics 



Swing calculator with a GUI
TECHNICAL REPORT: JAVA SWING CALCULATOR
expressions dynamically.
•JavaScripting (𝑗𝑎𝑣𝑎𝑥.𝑠𝑐𝑟𝑖𝑝𝑡.∗): For evaluating mathematical expressions 
•AWT (𝑗𝑎𝑣𝑎.𝑎𝑤𝑡.∗): For layout and event handling.
2.What is Needed to Build the Program
application uses the JavaScript engine (via ScriptEngineManager) to evaluate mathematical 
•Text Editor: (Optional) Notepad++, VS Code, or any preferred editor.
•Integrated Development Environment (IDE): (Optional) IntelliJ IDEA, Eclipse, or 
Swing framework. It allows users to perform basic arithmetic operations such as addition, 
•Java Swing (𝑗𝑎𝑣𝑎𝑥.𝑠𝑤𝑖𝑛𝑔.∗): For building the graphical user interface.
Prerequisites
•Java Development Kit (JDK) 11 or later: To compile and run the Java program.
To build and run the Java Swing Calculator, you need the following:
NetBeans for a better development experience.
subtraction, multiplication, division, exponentiation, and square root calculation. The 
The Java Swing Calculator is a simple GUI-based calculator application designed using Java's 
•Command Line/Terminal: To compile and execute the program if not using an IDE.
1.Overview
Required Libraries
dynamically.
3.Features
•When a button is clicked, its corresponding value is appended to the input string 
•Implements ActionListenerto handle button clicks.
•A JTextFieldis used as a display to show the input and results.
•Buttons include digits (0-9), operators (+,−,∗,/,^), special functions (√,𝐶,=), and 
4.How It Works
•Error handling for invalid input, division by zero, and unbalanced parentheses
•Exponentiation (^)
•Basic arithmetic operations: +,−,∗,/
parentheses ((, )).
•The display updates dynamically to show the input.
•Graphical User Interface (GUI) using Java Swing
•A JPanelwith a GridLayout(5,4,5,5)arranges the calculator buttons.
•Pressing 𝐶clears the input.
•Square root calculation (√)
Event Handling
•Clear (𝐶) button to reset input
•Parentheses for grouping expressions
•Pressing =triggers expression evaluation.
(StringBuilder).
User Interface
•Pressing √calculates the square root of the current input.
Expression Evaluation
Key Methods
evaluate mathematical expressions.
•Implements 𝐴𝑐𝑡𝑖𝑜𝑛𝐿𝑖𝑠𝑡𝑒𝑛𝑒𝑟for handling button clicks.
Class Structure
•Parentheses balance is checked before evaluation.
•Extends 𝐽𝐹𝑟𝑎𝑚𝑒to create a Swing-based window.
•The program utilizes the ScriptEnginefrom Java's ScriptEngineManagerto 
𝑝𝑢𝑏𝑙𝑖𝑐𝑐𝑙𝑎𝑠𝑠𝑆𝑤𝑖𝑛𝑔𝐶𝑎𝑙𝑐𝑢𝑙𝑎𝑡𝑜𝑟𝑒𝑥𝑡𝑒𝑛𝑑𝑠𝐽𝐹𝑟𝑎𝑚𝑒𝑖𝑚𝑝𝑙𝑒𝑚𝑒𝑛𝑡𝑠𝐴𝑐𝑡𝑖𝑜𝑛𝐿𝑖𝑠𝑡𝑒𝑛𝑒𝑟
•Buttons (𝐽𝐵𝑢𝑡𝑡𝑜𝑛): Contains numbers, operators, and function keys.
JavaScript engine.
•Errors such as division by zero, invalid expressions, and negative square roots are 
𝑎𝑐𝑡𝑖𝑜𝑛𝑃𝑒𝑟𝑓𝑜𝑟𝑚𝑒𝑑(𝐴𝑐𝑡𝑖𝑜𝑛𝐸𝑣𝑒𝑛𝑡𝑒)
5.Implementation Details
handled appropriately.
•Panel (𝐽𝑃𝑎𝑛𝑒𝑙): Organizes buttons in a grid layout.
Components
•The ^operator (exponentiation) is replaced with **for compatibility with the 
•Display (𝐽𝑇𝑒𝑥𝑡𝐹𝑖𝑒𝑙𝑑): Shows user input and results.
Handles button clicks by updating input, performing calculations, or handling errors.
𝑒𝑣𝑎𝑙𝑢𝑎𝑡𝑒𝐸𝑥𝑝𝑟𝑒𝑠𝑠𝑖𝑜𝑛()
•Checks for balanced parentheses.
•Handles division by zero and invalid input errors.
𝑖𝑠𝐵𝑎𝑙𝑎𝑛𝑐𝑒𝑑(𝑆𝑡𝑟𝑖𝑛𝑔𝑒𝑥𝑝𝑟𝑒𝑠𝑠𝑖𝑜𝑛)
•Uses ScriptEngineto evaluate the expression.
•Computes the square root if the number is non-negative.
•Displays an error message if the number is negative.
•Replaces^with ∗∗for JavaScript compatibility.
•Ensures operators are not added consecutively.
•Allows numbers, parentheses, and valid operators.
ℎ𝑎𝑛𝑑𝑙𝑒𝑆𝑞𝑢𝑎𝑟𝑒𝑅𝑜𝑜𝑡()
•Parses the current input as a number.
𝑖𝑠𝑉𝑎𝑙𝑖𝑑𝐼𝑛𝑝𝑢𝑡(𝑆𝑡𝑟𝑖𝑛𝑔𝑐𝑚𝑑)
•Checks if parentheses in the expression are balanced.
6.Error Handling
To run the program, compile and execute the Java file:
Alternatively, execute it within an IDE like IntelliJ IDEA or Eclipse.
7.Execution
•Unbalanced Parentheses: Displays "Error: Unbalanced parentheses".
•Invalid Expressions: Displays "Error: Invalid expression".
𝑗𝑎𝑣𝑎𝑆𝑤𝑖𝑛𝑔𝐶𝑎𝑙𝑐𝑢𝑙𝑎𝑡𝑜𝑟
•Division by Zero: Displays "Error: Division by zero".
This Java Swing Calculator demonstrates effective GUI design and event handling in Java. The 
𝑗𝑎𝑣𝑎𝑐𝑆𝑤𝑖𝑛𝑔𝐶𝑎𝑙𝑐𝑢𝑙𝑎𝑡𝑜𝑟.𝑗𝑎𝑣𝑎
use of ScriptEngineenables flexible mathematical expression evaluation, while error handling 
•Negative Square Root: Displays "Error: Negative √".
ensures robustness. It serves as a functional and extensible calculator application.
