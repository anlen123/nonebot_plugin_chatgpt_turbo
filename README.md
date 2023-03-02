<div align="center">
  <a href="https://v2.nonebot.dev/store"><img src="https://github.com/A-kirami/nonebot-plugin-template/blob/resources/nbp_logo.png" width="180" height="180" alt="NoneBotPluginLogo"></a>
  <br>
  <p><img src="https://github.com/A-kirami/nonebot-plugin-template/blob/resources/NoneBotPlugin.svg" width="240" alt="NoneBotPluginText"></p>
</div>

<div align="center">

</div>
# nonebot-plugin-gpt3.5-turbo
# 介绍
- 本插件适配OpenAI在2023年3月1日发布的最新版API，可以在nonebot中调用OpenAI的ChatGPT生产环境下的模型（GPT3.5-turbo）进行回复。
- 接口调用速度与网络环境有关，经过测试，大陆外的服务器的OpenAI API响应时间能在十秒之内。
- 免费版OpenAI的调用速度限制为20次/min
# 安装


# 配置文件

在Bot根目录下的.env文件中追加如下内容：

```

OPENAI_API_KEY = key
OPENAI_MODEL_NAME = "gpt-3.5-turbo"
