# make_autoTweet
this make automation workflow is able to tweet automatically based on the news link you provide.
<img width="894" alt="Screenshot 2025-03-21 at 13 58 49" src="https://github.com/user-attachments/assets/4eb5c0b0-35b4-453f-825a-23afaad28a7a" />

To use this workflow, simpliy import the json file into Make Scenario, then you have to apply API for the following service:
1. Google Sheets API from Google Cloud
2. OpenAI API (or any other LLM such Perplexity or Google Gemini, remember you have to top up some money first!)
3. X (former Twitter) API
4. Telegram (optional, if you don't need, simpliy disconnect it)

After finishing set up, create a new file in Google Sheets and make header including link (鏈接), status (狀態), title (標題), abstract (摘要), conclusion (English) (總結內容 (英文)), and conclusion (Chinese) (總結內容 (中文)).
<img width="884" alt="Screenshot 2025-03-21 at 17 02 48" src="https://github.com/user-attachments/assets/6de37e98-1135-494c-a694-fa26efa68322" />


Once you put your link, remember to change the "status" to "in progress", so the Make workflow can read and process. Once the workflow is done, the status will automatically be updated to "finished".
