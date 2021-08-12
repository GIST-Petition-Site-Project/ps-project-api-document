# Get Comments by post Id

## METHOD

```text
GET
```

## URL EXAMPLE

```text
/gistps/api/v1/post/:postId/comment
```



### RESPONSE BODY EXAMPLE

```javascript
[
    {
        "commentId": 1,
        "content": "저도 동의합니다",
        "created": "2021-08-12 09:25:54",
        "userId": 1
    },
    {
        "commentId": 2,
        "content": "저도 동의합니다",
        "created": "2021-08-12 09:26:46",
        "userId": 2
    }
]
```

