# make_autoTweet
this make automation workflow is able to tweet automatically based on the news link you provide.
To use this workflow, simpliy import the json file into Make Scenario, then you have to apply API for the following service:
1. Google Sheets API from Google Cloud
2. OpenAI API (or any other LLM such Perplexity or Google Gemini, remember you have to top up some money first!)
3. X (former Twitter) API
4. Telegram (optional, if you don't need, simpliy disconnect it)

After finishing set up, create a new file in Google Sheets and make header including link (鏈接), status (狀態), title (標題), abstract (摘要), conclusion (English) (總結內容 (英文)), and conclusion (Chinese) (總結內容 (中文)).

Once you put your link, remember to change the "status" to "in progress", so the Make workflow can read and process. Once the workflow is done, the status will automatically be updated to "finished".
