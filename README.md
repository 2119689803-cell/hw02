# hw02
任务一：
1.论文来源：中国知网
2.导读生成：由Gemini学习参考导读、并提交论文文件，最终输出论文导读
3.配图方式：由Gemini生成表格内容，手动插入文档，并使用“插入题注”功能为表格进行注释
任务二：
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
4. 运行方式与示例
运行命令：
Bash
python chatbot_deepseek.py
输入示例：
用户: 请简述人工智能在消化道肿瘤病理图像处理中的作用。
输出示例：
Chatbot: AI 在病理图像中主要用于全切片数字图像的分类，例如识别正常黏膜、慢性胃炎和肠型胃癌 。
