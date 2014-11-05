1：anysdk  jsb 的示例。

2：怎么使用Sample_Jsb

首先clone整个项目
<pre>
git clone https://github.com/AnySDK/Demo
</pre>
并更新子模块
<pre>git submodule update --init</pre>
编译项目(进入Sample_JSB)：
<pre>./path_to_cocos/cocos compile -p android
./path_to_cocos/cocos run -p android //运行到手机
</pre>
cocos命令可以在 frameworks/js-bindings/cocos2d-x/tools/cocos2d-console/bin/cocos 找到。

ps：1, 如果cocos2d-console是空的，则需要在frameworks/js-bindings/cocos2d-x下面运行
<pre>git submodule update --init</pre> 
   2, 如果编译有错误，则需要在frameworks/js-bindings/cocos2d-x下，运行
   <pre>python download-deps.py</pre>

