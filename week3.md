# 第三周：数据结构重点总结
## 1. 时间复杂度计算
- **递归公式**：T(n) = aT(n/b) + f(n)
- 示例代码：
  ```c
  void func(int n) {
      if(n <= 1) return;
      func(n/2);
      func(n/2);
  }
  ```
  **解析**：时间复杂度为O(n)
  
## 2. 本周错题
| 题号 | 错误点 | 正确解法 |
|------|--------|----------|
| 2023-45 | 混淆FIFO和LRU | 查看页面访问时间戳 |
![mmexport1664095468032](https://github.com/user-attachments/assets/13420a7a-b842-45e0-8d9b-6d75c63835df)
