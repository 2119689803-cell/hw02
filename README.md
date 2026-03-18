# hw02
1. 采用的 API / 平台
   平台：DeepSeek 官方 API (或 OpenAI 兼容第三方平台)
   接口协议：OpenAI SDK 兼容模式
  2. 运行环境与依赖安装
      Python 版本：3.8+
      依赖库：openai
      安装命令：
      Bash
      pip install openai
3. 配置方式 (API Key)
   为了保证安全性，本项目通过环境变量配置 API Key。在运行脚本前，请在终端执行以下命令（以 Linux/Mac 为例）：Bashexport DEEPSEEK_API_KEY="你的_API_KEY_在此"
