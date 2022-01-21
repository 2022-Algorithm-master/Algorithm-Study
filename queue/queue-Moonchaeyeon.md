# 큐(Queue)
 👉 **Queue란?**
> FIFO(fist in first out) 구조로 저장하는 형식
---
### 📒 [C++] STL Queue
#### 🔴 **선언**
> *queue<자료형> 변수명;*

    #include <queue>
    queue<int> q;

#### 🔴 **기본 함수**

🔹 **데이터 추가**

    queue.push(elem);
🔹 **데이터 삭제**

    queue.pop();
🔹 **첫 번째 데이터 반환**

    queue.front();
    
🔹 **마지막 데이터 반환**

    queue.back();
🔹 **길이 반환**

    queue.size();
🔹 **비어 있는지 반환**

    queue.empty();

---
### 📒 우선순위 Queue

> **우선순위**를 가진 데이터들을 저장하는 큐 -> O(logN)

#### 🔴 **선언**
*1) priority_queue<자료형> 변수명;* 👉 **내림차순**
*2) priority_queue<자료형, container, 비교함수> 변수명;* 👉 **함수에 따라 정렬**

    #include <queue>
    priority_queue<int> q;
    priority_queue<int, vector<int>, func>
#### 🔴 **기본 함수**
🔹 **상단 데이터 반환**

    priority_queue.top();


