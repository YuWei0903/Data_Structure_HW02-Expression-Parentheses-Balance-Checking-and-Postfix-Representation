# Data_Structure_HW02-Expression-Parentheses-Balance-Checking-and-Postfix-Representation
Use C++ to implement a data structure program.  
Write a program with the C++ STL library to check balanced parentheses in expressions, convert infix to postfix notation, and evaluate the result.  

本專案使用 C++ 與 STL 實作運算式的括號對稱檢查、中序轉後序表示法，以及後序運算結果評估。  
輸入的運算式僅包含數字 1~9、運算子 + - x /、括號 ( )，程式會將其解析為字串形式，並輸出：
1. 原始運算式的括號檢查結果
2. 運算式的後序表示法
3. 運算結果

**輸入格式**  
(1+2)x(3+4)  
(5+(3x2))-(6/3)  

**輸出範例**
輸入：  
(1+2)x(3+4)  
輸出：  
確認輸入數學式是否合理、括號對稱(yes)  
輸入數學式的後序表示法：12+34+x  
輸入數學式的運算結果：21  

輸入：  
(5+(3x2))-(6/3)  
輸出：  
確認輸入數學式是否合理、括號對稱(yes)  
輸入數學式的後序表示法：532x+63/-  
輸入數學式的運算結果：9  
