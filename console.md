## console

### console.time('name') & console.timeEnd('name')
这2个方法可以让我们快速监听我们的代码在这之间处理时所耗时长  
- `console.time('name')` : 开始记录标志
- `console.timeEnd('name')` : 结束记录标志
- `name` 要是相同

#### 示例
```javascript
console.time('timer');
for (x = 500; x >0; x--) {}
console.timeEnd('timer');

// => timer: 0.404ms (因电脑不同数据不同)
```