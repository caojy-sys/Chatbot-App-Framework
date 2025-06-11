# Chatbot-App-Framework
调用openai等api接口创建的一个简易网页chatbot app

基于streamlit编写的针对openai接口的各类模型对话web应用，目前支持基本对话、文生图、图片理解、语音转文、文转语言。


## 0. 目标
- [x] 支持Chat Completions API 的页面，进行文本对话
- [x] 支持Vision的页面，进行图像理解
- [x] 支持Image generation的页面，进行图片生成
- [x] 支持语言转文本的页面
- [x] 支持文本转语音的页面 

## 1 使用

### 直接运行

```bash
pip install -r requirements.txt
pip install --upgrade streamlit audio_recorder_streamlit
#命令行启动
streamlit run ./src/home.py
#如果出错，找到streamlit
#PyCharm debug启动
script：D:/software/python/python-3.12.4/.venv/Scripts/streamlit
script parameters：run ./src/home.py 
Working directory：./Chatbot-App-Framework
