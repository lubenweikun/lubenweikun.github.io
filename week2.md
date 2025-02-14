# 第二周：计算机网络重点
## 时间复杂度计算
- 递归算法：主定理公式 `T(n) = aT(n/b) + f(n)`
- 示例：二分查找时间复杂度为O(log n)

## 真题解析
```c
void func(int n){
    if(n <= 1) return;
    func(n/2);
    func(n/2);
}

![mmexport1662544306470](https://github.com/user-attachments/assets/5664c501-e6ea-4b17-abb4-011817f45721)
