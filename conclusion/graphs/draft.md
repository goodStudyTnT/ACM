## 最小生成树
  - 最小生成树有两个性质
    - 对于任意权值，最小生成树中这种权值的边数是一定的.
    - 对于任意权值，把小于它的权值的边加到MST里后的连通性是一定的.
    - [CF891C](../codeforces/800-899/891C.cpp)

## 最短路
- 如果枚举的点都能组成**四元环**, 那我们可以枚举对角线点，这样使剩下的两个点孤立起来，这样就能对每个点独立去处理。复杂度能从 `O(n^4)` 变 `O(n^3)`
  - [CF1483D](../codeforces/1400-1499/1483D.cpp)
- 重新定义最短路函数
  - 可以考虑分层，将一些状态加到dist上面
    - [CF1473E](../codeforces/1400-1499/1473E.cpp)

## 四元环
- [四元环讲解](./four_node_circle.md)
- 裸题： [CF1468M](../codeforces/1400-1499/1468M.cpp)