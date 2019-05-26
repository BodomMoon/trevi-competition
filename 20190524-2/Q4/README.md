# Q4 循環永動雞

## 題目敘述

在一個無限大的農場裡，一隻小雞站在[0, 0] 並面向北方。小雞會接收以下三種指令

G : 往前走一步;
L : 原地向左轉向 90 度;
R : 原地向右轉向 90 度;

小雞會按照指令輸入的順序無限循環運行下去。
如果小雞在農場上的路徑會形成一個循環則回傳 true，反之回傳 false。

## 範例
```
範例一輸入："GGRRGG"
範例一輸出：true
範例一說明：小雞先移動到 [0, 2]，然後迴轉 180 度，接著移動到 [0, 0] ，並不斷重複此循環。

範例二輸入："GG"
範例二輸出：false
範例二說明：小雞移動到 [0, 2]，接著移動到 [0, 4]，不斷前進下去，一去不復返。

範例三輸入："GR"
範例三輸出：true
範例三說明：小雞移動到 [0, 1]，向右轉 90 度。第二輪移動到 [1, 1]，向右轉 90 度。第三輪移動到 [1, 0]，向右轉 90 度。第四輪移動到 [0, 0]，向右轉 90 度，並不斷重複此循環。
```

## 附註
1 <= 指令長度 <= 100
指令只會有 G、L 和 R 三種字母。

## 答題方式
完成以下 Function **(擇一即可)**

C++
```
class Solution {
public:
    bool infiniteChicken(string instructions) {
        
    }
};
```

Js
```
/**
 * @param {string} instructions
 * @return {boolean}
 */
var infiniteChicken = function(instructions) {
    
};
```

Java
```
class Solution {
    public boolean infiniteChicken(String instructions) {
        
    }
}
```

Python3
```
class Solution:
    def infiniteChicken(self, instructions: str) -> bool:
        
```

Go
```
func infiniteChicken(instructions string) bool {
    
}
```

Swift
```
class Solution {
    func infiniteChicken(_ instructions: String) -> Bool {
        
    }
}
```