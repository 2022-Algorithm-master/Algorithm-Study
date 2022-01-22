# 스택(Stack)
 👉 **Stack이란?**
>**LIFO(Last In First  Out)** 구조로 저장하는 형식
---
### 📒 [C++] STL Queue
#### 🔴 **선언**
> *stack<자료형> 변수명;*

    #include <stack>
    stack<int> q;

#### 🔴 **기본 함수**

🔹 **데이터 추가**

    stack.push(elem);
🔹 **데이터 삭제**

    stack.pop();
🔹 **첫 번째 데이터 반환**

    stack.top();
    
🔹 **길이 반환**

    stack.size();
🔹 **비어 있는지 반환**

    stack.empty();
🔹 **두 스택의 값을 서로 바꾸기**

    swap(stack1, stack2);


