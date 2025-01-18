## 自定义显示内容（Custom display content）

### 具体用法（Specific usage）
- 本项目`Github Pages`地址为：[https://junewaysue.github.io/DisplayContent/](https://junewaysue.github.io/DisplayContent/)
- 在本项目地址后面加上`content`参数，如：[?content=七里香还是稻香](https://junewaysue.github.io/DisplayContent/?content=七里香还是稻香)
- 即：通过访问带`content`参数的本项目`url`来显示自定义内容

### 注意事项（Notes）
- 由于`url`的字符数最大限制为`8150`，减去本项目地址字符数`53`后，`content`参数字符数必须`≤8097`
- 所以为了尽可能传多点内容，本项目利用`zlib`将原文本压缩后并进行`base64`编码
- 将编码后的结果传入`content`参数中，再通过`js`的`pako`解码后显示原内容
- 当然，如果不这样传，而是直接传原文也是可以的
- **不管怎么传，都是有字符限制的**

### 关于我（About me）
- blog：[【完美解决】微信测试公众号消息显示存在的字数限制问题](https://blog.csdn.net/sinat_39629323/article/details/145126793)
- wechat： **[Python王者之路](https://user-images.githubusercontent.com/45711125/234814025-af439d36-d595-434d-bb51-e138b0c7738d.jpg)**
- csdn：**[七里香还是稻香](https://blog.csdn.net/sinat_39629323)**
- github：**[JuneWaySue](https://github.com/JuneWaySue)**