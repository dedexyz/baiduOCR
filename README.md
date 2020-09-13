# baiduOCR
<span style='color:red'>这个使用之前一定要先设置【百度云应用的AK】和【百度云应用的SK】，不然是没有返回值的！！！</span><br>
pb调用百度ai实现文字识别<br>
#里面有两个类，一个是将图片转换成base64，另一个是将base64转换成urlencode，因为posthttp传送的数据必须是urlencode编码格式的，现在只做到返回json，下一步是解析json  //2020/09/12<br>
wf_gettoken里面需要设置【百度云应用的AK】和【百度云应用的SK】<br>
通用文字识别（标准版）
免费使用
https://aip.baidubce.com/rest/2.0/ocr/v1/general_basic
50000次/天免费<br>
通用文字识别（标准含位置版）
免费使用
https://aip.baidubce.com/rest/2.0/ocr/v1/general
500次/天免费<br>
通用文字识别（高精度版）
免费使用
https://aip.baidubce.com/rest/2.0/ocr/v1/accurate_basic
500次/天免费<br>
通用文字识别（高精度含位置版）
免费使用
https://aip.baidubce.com/rest/2.0/ocr/v1/accurate
50次/天免费<br>
这个程序设置了高清度的版本，只有50次，使用量大可以使用通用文字识别（不过，json返回略有差别，解析的时候自己稍微修改一下）
