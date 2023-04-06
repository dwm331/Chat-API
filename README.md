# Chat-API
使用postman 測試，openAPI Chat 問答


[API reference](https://platform.openai.com/docs/api-reference/making-requests)

# 問題
台灣南投旅遊，可以玩幾天，幫我規劃旅遊行程與台幣預算

# 回應
```
{
    "id": "chatcmpl-XXXXXXXXXXXXXXXXXXXXXXXXXXXXXX",
    "object": "chat.completion",
    "created": 1680744320,
    "model": "gpt-3.5-turbo-0301",
    "usage": {
        "prompt_tokens": 46,
        "completion_tokens": 367,
        "total_tokens": 413
    },
    "choices": [
        {
            "message": {
                "role": "assistant",
                "content": "建議可以安排3至4天的旅遊行程。以下是一個可能的行程和預算：\n\n第一天：\n- 前往日月潭，參觀向山遊客中心和九族文化村，享用當地美食\n- 預算：交通：1500元，門票：600元，美食：800元\n\n第二天：\n- 前往清境農場，欣賞美麗的高山風景和動物表演\n- 預算：交通：1000元，門票：400元，美食：800元\n\n第三天：\n- 前往鹿谷鄉，參觀集集火車站、四方眷村和龍鳳谷\n- 預算：交通：800元，門票：200元，美食：600元\n\n第四天：\n- 前往南投市，參觀南投文化中心、酒包港、南投老街和十字溪夜市\n- 預算：交通：800元，門票：100元，美食：500元\n\n總預算：約12000元（不包含住宿費）。當然，預算還需要根據個人需求和喜好進行調整。"
            },
            "finish_reason": "stop",
            "index": 0
        }
    ]
}
```
