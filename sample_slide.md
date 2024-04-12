---
marp: true
theme: maximum
---

<!-- _class: lead -->

# Maximum's Marp Theme

![avatar](https://github.com/sor4chi.png) **Sor4chi**
![avatar](https://github.com/a01sa01to.png) **a01sa01to**

---

## 見出しその 2 はスライドの上に固定表示されます

### 見出しその 3

#### 見出しその 4

##### 見出しその 5

###### 見出しその 6

---

## 順序なしリスト

- これはリストです
  - インデントされたリスト
    - さらにインデントされたリスト
- これはリストです
  - インデントされたリスト
  - インデントされたリスト
- これはリストです

---

## 順序付きリスト

1. これはリストです
   1. インデントされたリスト
      1. さらにインデントされたリスト
2. これはリストです
   1. インデントされたリスト
   2. インデントされたリスト
3. これはリストです

---

## テーブル

| 1 行目 | 2 行目 | 3 行目 |
| ------ | ------ | ------ |
| 1 列目 | 2 列目 | 3 列目 |
| 1 列目 | 2 列目 | 3 列目 |
| 1 列目 | 2 列目 | 3 列目 |

---

## コードブロック

このようなコードブロックを挿入できます。

```cpp
#include <iostream>
using namespace std;

int fib(int n) {
  if (n <= 1) return n;
  return fib(n - 1) + fib(n - 2);
}

int main() {
  int n;
  cin >> n;
  cout << fib(n) << endl;
  return 0;
}
```

---

## 画像

![](./assets/logo.svg)

---

## 引用

> 春はあけぼの。やうやう白くなりゆく山際、少し明かりて、紫だちたる雲の細くたなびきたる。
> 夏は夜。月のこもりたるさびしさに、ふれる風の音、ひとしずくの雨。

https://www.aozora.gr.jp/cards/000148/files/789_14547.html
