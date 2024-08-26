## AndroidV1 Push Message

```json
{
    "partnerId": "freedom",
    "os": "android",
    "app": "string::appName",
    "firebaseRequest": {
        "message": {
            "token": "string::deviceToken",
            "data": {
                "link": "string::url",
                "image": "string::url",
                "body": "string",
                "title": "string",
                "push_buttons": {
                    "string": "string::url"
                }
            },
            "android": {
                "priority": "high"
            },
            "topic": "string"
        }
    }
}
```
