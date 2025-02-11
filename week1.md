# 第一周：数据结构重点
## 时间复杂度计算
- 递归算法：主定理公式 `T(n) = aT(n/b) + f(n)`
- 示例：二分查找时间复杂度为O(log n)

## 真题解析
void func(int n)
{
    if(n <= 1) return;
    func(n/2);
    func(n/2);
}
![2108369756](https://github.com/user-attachments/assets/e80418d1-5b35-481d-973e-806757934f29)
