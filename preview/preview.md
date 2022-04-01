---
front matter
this is a front matter
front
yaml: 
sb: 
date: xxxx/xx/xx
---

[TOC]

## md 基本功能测试

你好，这里是**加粗**，*斜体*和~~删除线~~的测试。

> 然后呢我这里引用了一句话。中文填充填充充填充充填充充填充充填充充填充充填充充填充充填充充填充充填充充填充充填充充填充充填充充填充充填充充填充充填充充填充充填充充填充充填充充填充充填充充填充充填充充填充充填充充填充充填充充填充充填充充填充
>
> 好吧两句也不是不可以。

然后呢是行内公式 $E = mc^2$，来玩个大的 $\displaystyle\sum_{i}\sum_j\sum_k\sum_l \left(\frac{f(i,j,k,l)}{1919810}\right)^{114514}$。之后是行间公式：
$$
\sum_{i = 1}^n f(i) = f(1) + f(2) + \cdots f(n)\\
\prod_{i =1}^nf(i) = f(1)\times f(2)\times \cdots\times f(n)\\
\sum_{p(x)\text{ is true}}f(x) = f(x_1) + f(x_2) + \cdots\text{for all }x_i\text{ that meet the proposition}
$$
下面是无序列表测试：

- 啊对对对

- 啊错错错

- 列表可以嵌套吗

  - 显然可以
    - 我还可以套
  - 是的是的

  对对对，还可以这样

- 是的

下面是有序列表测试

1. hello
   1. bello
   2. cello
   3. dello
2. 啊哈
3. gamma

## 表格

| 表头 | 表头2 | 表头3 |
| ---- | ----- | ----- |
| 1    | 2     | 3     |
| 4    | 5     | 6     |
| 7    | 8     | 9     |

好吧就是这样。

## 代码块

众所周知代码块有行内 `printf("%d\n", cnt);` 和行间之分。

```cpp
/* 多行注释测试
这里是多行注释
x
*/

#include <bits/stdc++.h>
#define FOR(i, a, b) for (int i = (a); i <= (b); ++i)
#define DEC(i, a, b) for (int i = (a); i >= (b); --i)
#define VEC(i, v) for (int i = 0; i < (int)v.size(); ++i)
#define il inline

using namespace std;

namespace YangTY {

template<typename T> il T min(const T &a, const T &b) {return a < b ? a : b;}
template<typename T> il T max(const T &a, const T &b) {return a > b ? a : b;}

using ll = long long;
using ull = unsigned long long;

const int mod = 998244353;

ll qPow(ll a, ll b = mod - 2) {
    ll ret = 1;
    for (; b; b >>= 1, a = a * a % mod)
        if (b & 1) ret = a * ret % mod;
    return ret;
}
    
int main() { // 我是注释哦
    return 0;
}

} // namespace YangTY

int main() {
    YangTY::main();
    return 0;
}
```

下面是一些 css 片段

```css
/* megamenu */

.megamenu-menu-panel .btn {
    border: 1px solid #ccc;
}

.megamenu-menu {
    background-color: var(--bg-color);
}

.megamenu-content {
    background: var(--bg-color2) !important;
}

.megamenu-opened header {
    background: var(--bg-color-code) !important;
}

#recent-file-panel tbody tr:nth-child(2n-1) {
    background-color: var(--table-bg-color);
}

#recent-file-panel-action-btn {
    background-color: var(--bg-color);
    border: 0.5px solid var(--table-border-color);
    border-radius: 5px;
}

```

# 一级标题

Please avoid using H1 in most md files.

## 二级标题

### 三级标题

#### 四级标题

##### 五级标题

###### 六级标题

我是文字，emmmmmm。