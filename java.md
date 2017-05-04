## Java编码规范
### 参考[阿里技术团队](https://yq.aliyun.com/articles/69327)推出的开发规范
## 命名规约
- 【强制】 代码中的命名均不能以下划线或美元符号开始，也不能以下划线或美元符号结束。
    ```
    反例： _name /  name / $Object / name_ / name$ / Object$
    ```
- 【强制】 代码中的命名严禁使用拼音与英文混合的方式，更不允许直接使用中文的方式。 说明：正确的英文拼写和语法可以让阅读者易于理解，避免歧义。注意，即使纯拼音命名方式 也要避免采用
    ```
    反例： DaZhePromotion [打折] / getPingfenByName() [评分] / int 某变量 = 3
    正例： alibaba / taobao / youku / hangzhou 等国际通用的名称，可视同英文
    ```
