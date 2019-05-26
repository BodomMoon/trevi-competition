# Q2 幫小雞排隊

## 題目敘述

三隻小雞站在數線上，位置分別是 [i, j, k]，對於每次行動我們都假設小雞分別位於 [α, β, c]，且 α < β < c 。 我們可以從 α 或 c 位置拿起一隻小雞，並將小雞放置到數線上的 W 處，且 α < W < c 並滿足 W != β

當無法再移動任何小雞時遊戲結束。請輸出要使遊戲結束你的最少行動次數跟最大行動次數是多少，以一個長度為 2 的 array 來回傳答案。
> 註：小雞位置可能以未排序的順序輸入

## 輸入
```
範例一輸入：α = 7, β = 8, c = 12
範例一輸出：[1, 3]
範例一解釋：能夠直接移動小雞到 9 或將小雞從 12 -> 11 -> 10 -> 9 移動三次。

範例二輸入：α = 9, β = 8, c = 7
範例二輸出：[0, 0]
範例二解釋：沒辦法移動小雞。

範例三輸入：α = 6, β = 8, c = 4
範例三輸出：[1,2]
範例三解釋：能夠直接移動小雞到 7 或將小雞從 4 -> 5 -> 7 移動兩次。
```

## 測資範圍

```
1 ≤ α ≤ 100
1 ≤ β ≤ 100
1 ≤ c ≤ 100
a != β, β != c, c != α
```

## 輸出
完成以下 Function **(擇一即可)**

C++
```
class Solution {
public:
    vector<int> moveChicken(int a, int b, int c) {
        
    }
};
```

Js
```
/**
 * @param {number} a
 * @param {number} b
 * @param {number} c
 * @return {number[]}
 */
var moveChicken = function(a, b, c) {
    
};
```

Java
```
class Solution {
    public int[] moveChicken(int a, int b, int c) {
        
    }
}
```

Python3
```
class Solution:
    def moveChicken(self, a: int, b: int, c: int) -> List[int]:

```

Go
```
func moveChicken(a int, b int, c int) []int {
    
}
```