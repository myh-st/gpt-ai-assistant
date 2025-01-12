# GPT AI Assistant

<div align="center">

[![license](https://img.shields.io/pypi/l/ansicolortags.svg)](LICENSE) [![Release](https://img.shields.io/github/release/memochou1993/gpt-ai-assistant)](https://GitHub.com/memochou1993/gpt-ai-assistant/releases/)

</div>

GPT AI Assistant is an application that is implemented using the OpenAI API and LINE Messaging API. Through the installation process, you can start chatting with your own AI assistant using the LINE mobile app.

## News
- 2023-04-27: Support Azure OpenAi service with Cloudflare worker script to proxy OpenAI‘s request to Azure OpenAI Service https://github.com/haibbo/cf-openai-azure-proxy
  deploy your proxy and then add "OPENAI_BASE_URL= " to .env to pass cf proxy to gpt-ai-assistant tested with model gpt-4
- 2023-03-05: The `4.1` version now support the audio message of LINE and  `whisper-1` language model of OpenAI. :fire:
- 2023-03-02: The `4.0` version now support `gpt-3.5-turbo` language model of OpenAI. :fire:

## Documentations

- <a href="https://memochou1993.github.io/gpt-ai-assistant-docs/" target="_blank">中文</a>
- <a href="https://memochou1993.github.io/gpt-ai-assistant-docs/en" target="_blank">English</a>

## Credits

- [jayer95](https://github.com/jayer95) - Debugging and testing
- [kkdai](https://github.com/kkdai) - Idea of `sum` command
- [Dayu0815](https://github.com/Dayu0815) - Idea of `search` command
- [mics8128](https://github.com/mics8128) - Implementing new features
- [All other contributors](https://github.com/memochou1993/gpt-ai-assistant/graphs/contributors)

## Contact

If there is any question, please contact me at memochou1993@gmail.com. Thank you.

## Changelog

Detailed changes for each release are documented in the [release notes](https://github.com/memochou1993/gpt-ai-assistant/releases).

## License

[MIT](LICENSE)
