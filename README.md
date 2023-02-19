# PotPlayer_Subtitle_Translate_BaiduAi
BaiduAi Translate  for  PotPlayer Subtitle Translate 


 本仓库受fjqingyou仓库启发 [PotPlayer_Subtitle_Translate_Baidu]（https://github.com/fjqingyou/PotPlayer_Subtitle_Translate_Baidu)
 fjqingyou仓库PotPlayer_Subtitle_Translate_Baidu，使用百度翻译，调用字符为每月免费5万字符/月
 本仓库使用百度ai机器翻译 文本翻译-通用版，个人认证后免费使用365天，调用字符为在 500 万字符。
 
 #使用要求：
 第一步：获取API Key和Secret Key
 
 1.需实名认证；
 
 2.登入后可至机器翻译页面领取测试资源，链接为https://console.bce.baidu.com/ai/#/ai/machinetranslation/overview/index 
 机器翻译 文本翻译-通用版控制台-免费资源领取页 可领取免费测试资源。
 
 3.创建机器翻译 文本翻译-通用版应用，生成API Key和Secret Key
 
 第二步：安装翻译插件

    1、将SubtitleTranslate - baiduai.as、SubtitleTranslate - baiduai.ico这两个文件选中，Ctrl+C复制

    2、打开PotPlayer播放器的安装路径（方法不会的请百度、谷歌等等方式搜索）

    3、再进入Extention文件夹，接着又进入Subtitle文件夹、最后进入Translate文件夹

    4、Ctrl+V，把刚才选择的两个文件粘贴到这个文件夹
    
  第三步：配置翻译插件
  1.打开PotPlayer播放器
  2.右键点击视频->字幕->在线字幕翻译->实时字幕翻译设置->选中百度翻译-> 点右边的 “账户设置”，会弹出一个对话框。
  3.将第一步生成API Key和Secret Key,分别填入插件App ID和密钥，然后点确定，会再次弹出对话框，点击关闭就行了。
  
  
  ps:对angelscript语法不熟悉，调试了好久，自己写的插件导入不识别，后用fjqingyou仓库PotPlayer_Subtitle_Translate_Baidu库修改后才行。。。

