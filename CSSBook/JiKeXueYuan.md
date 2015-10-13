#极客学院的CSS3教程

* [文字阴影](#textshadow)

* [加载字体](#fontfamily)

* [选择器](#choose)

<a name="textshadow"></a>
##文字阴影
```js
    #fontid {
        /*(水平 垂直 模糊 阴影的颜色) 可以设置多个阴影*/
        text-shadow: -5px 5px 5px red;
        color: white;
        font-size: 40px;
        font-weight: bold;
        background-image: url(./img/myiconicon.jpg);
        height: 100px;
        width: 100px;
    }
```
```js
<div id="fontid">文字阴影</div>
```

<a name="fontfamily"></a>
##加载字体
```js
    @font-face {
        font-family: yumi;
        src: url(img/yumi.ttf)format("truetype");
    }
    
    #fontfamilyid {
        font-family: yumi;
    }
```
```js
<div id="fontfamilyid">加载远程或者本地的字体</div>
```

<a name="choose"></a>
##选择器
```js
    /*鼠标移到上面显示*/
    input[type="text"]:hover{
        background-color: violet;
    }

    /*光标获取焦点*/
    input[type="text"]:focus{
        background-color: #F3E9F5;
    }

    /*鼠标选中或者点击*/
    input[type="text"]:active{
        background-color: green;
    }
```
```js
<input type="text" name="name">
```