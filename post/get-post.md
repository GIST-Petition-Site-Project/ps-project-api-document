# Get Post



## METHOD

```text
GET
```

## URL

```text
/gistps/api/v1/post/:id
```

#### id: 게시물 고유 id

### RESPONSE BODY EXAMPLE

```java
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
```

