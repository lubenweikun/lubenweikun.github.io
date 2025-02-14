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
![mmexport1664095468032](https://github.com/user-attachments/assets/7f6c28e9-ea2d-4716-96e3-8e189fd1e708)


## 2. 本周错题
| 题号 | 错误点 | 正确解法 |
|------|--------|----------|
| 2023-45 | 混淆FIFO和LRU | 查看页面访问时间戳 |
