# Get My posts



## METHOD

```text
GET
```

## URL

```text
/gistps/api/v1/user/:id/post
```

#### id: 유저 고유 id

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
    }
}
```

