# ChatGPT-Prompt-marketing-zh
这是一段配合ChatGPT next web 预置自定义Prompt的说明
## 1.如何加入新的MASK（面具）
 修改这个路径下的文件ChatGPT-Next-Web/app/masks/cn.ts

## 2.如何加入新的Prompt（通过https://raw.githubusercontent.com/被引用到ChatGPT next web）
 第1步：修改这个路径下的文件ChatGPT-Prompt-marketing-zh/Prompts-marktan.json  
 第2步：在ChatGPT next web 项目的ChatGPT-Next-Web/scripts/fetch-prompts.mjs中做对应修改  
 （在文件中的RAW_CN_URL位置，填入“ChatGPT-Prompt-marketing-zh/main/Prompts-marktan.json”）
