## 一 判断题

1. 正确
2. 错误
3. 正确
4. 正确
5. 正确
6. 错误


## 二

1. 输出结果为：`年龄: 20` 加号的作用为拼接字符串
2. 输出结果为: `66`，加号的作用为运算符
3. 输出结果为: `网络 + 安全` , 加号本身是字符串的一部分
4. 输出结果为: `a2`， 加号的作用为拼接字符串，其中 a 是字符串，b 是变量，并自动推导为 String 类型
5. 输出结果为: `a + b` , 加号本身是字符串的一部分，a b 都是字符串，定义的变量没有使用到

## 三

```
var a = 10;
var b = 10;
console.log(a++);  // 输出 10，然后 a 自增为 11
console.log(++a);  // a 先自增为 12，然后输出 12
console.log(--b);  // b 先自减为 9，然后输出 9
console.log(b--);  // 输出 9，然后 b 自减为 8
```

## 四
### 行内式
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>行内式弹窗</title>
</head>
<body>
    <input type="button" value="Alert" onclick="alert('极客时间')" />
    <input type="button" value="Console.log" onclick="console.log('极客时间')" />
    <input type="button" value="Prompt" onclick="prompt('极客时间')" />
</body>
</html>
```

### 内嵌式
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>行内式弹窗</title>
</head>
<body>
    <input type="button" value="Alert" onclick="showAlert()" />
    <input type="button" value="Console.log" onclick="showConsole()" />
    <input type="button" value="Prompt" onclick="showPrompt()" />
</body>
<script type="text/javascript">
    function showAlert() {
        alert('极客时间')
    }

    function showConsole() {
        console.log('极客时间')
    }

    function showPrompt() {
        prompt('极客时间')
    }
</script>
</html>
```

### 引入外部文件
**JS 部分**
```javascript
// index.js
function showAlert() {
        alert('极客时间')
    }

    function showConsole() {
        console.log('极客时间')
    }

    function showPrompt() {
        prompt('极客时间')
    }
```
**HTML 部分**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>行内式弹窗</title>
</head>
<body>
    <input type="button" value="Alert" onclick="showAlert()" />
    <input type="button" value="Console.log" onclick="showConsole()" />
    <input type="button" value="Prompt" onclick="showPrompt()" />
</body>
<script type="text/javascript" scr="./index.js"></script>
</html>
```
