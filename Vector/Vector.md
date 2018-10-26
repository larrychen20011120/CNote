## Vector
```
引入標頭黨 <vector>
```

## 存取方式:
```
vec[i] - 存取索引值為 i 的元素值
vec.at(i) - 存取索引值為 i 的元素的值
vec.front() - 回傳 vector 第一個元素的值
vec.back() - 回傳 vector 最尾元素的值
```

## 新增或移除元素:
```
vec.push_back() - 新增元素至 vector 的尾端，必要時會進行記憶體配置。
vec.pop_back() - 刪除 vector 最尾端的元素。
vec.insert() - 插入一個或多個元素至 vector 內的任意位置。
vec.erase() - 刪除 vector 中一個或多個元素。
vec.clear() - 清空所有元素。
```

## 取的長度//容量
```
vec.empty() - 如果 vector 內部為空，則傳回 true 值。
vec.size() - 取得 vector 目前持有的元素個數。
vec.resize() - 改變 vector 目前持有的元素個數。
vec.capacity() - 取得 vector 目前可容納的最大元素個數。這個方法與記憶體的配置有關，它通常只會增加，不會因為元素被刪減而隨之減少。
```

