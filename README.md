# openai-workshop

![demo](/project.gif)

這是一個整合OpenAI的練習專案，從text-davinci 到 最新的 Whisper 都有使用。

This is an integration practice project that uses OpenAI's models from Text-Davinci to the latest Whisper.

## 準備
1. 先到 OpenAI申請一個 API-Key https://platform.openai.com/account/api-keys

2. 每一個 Model的費用都不一樣，再使用之前，請先確認 https://openai.com/pricing

3. API呼叫是有費用的，可以到Usage去確認用量 https://platform.openai.com/account/usage

## Preparation:

1. Apply for an API-Key from OpenAI: https://platform.openai.com/account/api-keys

2. Each model has different costs. Before using, please check the pricing on https://openai.com/pricing

3. There is a cost for API calls. You can check your usage on https://platform.openai.com/account/usage

## Step1.html
使用 text-davinci，輸入一個keyword後，回傳一篇文章的標題

Using text-davinci model, input a keyword, then response a article titel

## Step2.html
text-davinci 價格非常高，所以改使用gpt-3.5。因為API的格式並不一樣，再做微幅修改

Switched to using GPT-3.5 instead of text-davinci due to the high price. Minor modifications were made to the API format.

## Step3.html
將OpenAI回傳的內容，再為文章產生一張圖片，這邊使用了 DALL.E model

Generating an image for the article based on the content returned by OpenAI, using the DALL-E model.

## Step4.html
懶人模式，不想打字，改用語音方式輸入關鍵字，將語音傳給OpenAI做解析。

Lazy mode, don't want to type, switch to voice input to enter keywords, and send the voice to OpenAI for parsing.

## 備註、Note
在Step4.html時，如果你沒有Local Server，會無法正常的拿到麥克風權限，需要使用 plug-in： Live Server

During Step4.html, if you do not have a Local Server, you will not be able to obtain microphone permissions properly. You need to use the plug-in Live Server.

https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer
