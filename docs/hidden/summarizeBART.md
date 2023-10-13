---
PromptInfo:
 promptId: summarizeBART 
 name: 🪄 Summarize Text using BRAT Facebook
 description: select considered context and run the command 
 author: Noureddine
 tags: huggingface, text, summarization
 version: 0.0.3
config:
 append:
  bodyParams: false
  reqParams: true
 context: 'inputs'
 output: 'requestResults[0]?.summary_text'
bodyParams:
reqParams:
 url: "https://api-inference.huggingface.co/models/facebook/bart-large-cnn"
 headers:
  Authorization: "Bearer You_API_KEY_HERE"
date created: Wednesday, July 26th 2023, 8:11:06 am
date modified: Tuesday, October 10th 2023, 2:26:15 pm
---
{{selection}}
