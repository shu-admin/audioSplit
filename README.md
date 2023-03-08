#### audioSplit for Uberduck dataset
use [iflyAPI](https://www.xfyun.cn/doc/asr/lfasr/API.html)
1.change language(your train audio data)
"demo.py", line 85, change the value of param_dict['language']
Chinese : cn; English: en ; Japanese : ja;
2.Edit APIID, APIKEY and audio file
"demo.py" , line 207, edit your api content
3.Choose your result_file
input your result filename when this code is running
