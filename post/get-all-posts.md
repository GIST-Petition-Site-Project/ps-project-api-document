# Get All Posts



## METHOD

```text
GET
```

## URL EXAMPLE

```text
/gistps/api/v1/post/list
```



### RESPONSE BODY EXAMPLE

```javascript
{
    {
        "id": 1,
        "category": "category1",
        "title": "기숙사 ~건의합니다",
        "content": "~한 문제 해결 바랍니다",
        "user": {
            "id": 1,
            "email": "sinyr119@gist.ac.kr"
        }
    },
    {
        "id": 2,
        "category": "category1",
        "title": "식당 ~건의합니다",
        "content": "~한 문제 해결 바랍니다",
        "user": {
            "id": 1,
            "email": "sinyr119@gist.ac.kr"
        }
    },
}
```

