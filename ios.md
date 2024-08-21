## iOS Push Message

```json
{
    "partnerId": "freedom",
    "os": "ios",
    "deviceToken": "string",
    "topic": "string::appName",
    "apnsRequest": {
        "aps": {
            "alert": {
                "title": "string",
                "body": "string"
            },
            "sound": "default",
            "badge": 0,
            "push_buttons": {
                "string": "string::url"
            },
            "mutable-content": 1
        },
        "data": {
            "link": "string::url",
            "image": "string::url",
            "pushId": "string"
        }
    }
}
```
