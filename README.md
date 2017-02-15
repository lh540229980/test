# Mobile-verify-input
验证码 浮框 输入

## 心得体会

#### 1、input设置了opacity:0;在ios上还是有光标显示，如果把font-size设置为0，光标会消失，而input的值就取不出来了

#### 解决方法
> 把光标的部分隐藏到内容区域之外`width:200%;height:100%;text-indent:-999em;left:-100%;`

#### 2、只有用户点击之后，获取光标的方法才能生效，如果有ajax的情况，需要设置成同步请求
