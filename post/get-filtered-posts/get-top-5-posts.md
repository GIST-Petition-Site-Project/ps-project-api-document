# Get Top 5 Posts



## METHOD

```text
GET
```

## URL EXAMPLE

```text
/gistps/api/v1/post/list?top=5
```

## QUERY STRING

| name | type | description |
| :--- | :--- | :--- |
| top | int | 참여인원이 많은 순서대로 게시물 top개를 불러옴 |

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
    {
        "id": 3,
        "category": "category1",
        "title": "기숙사 ~건의합니다",
        "content": "~한 문제 해결 바랍니다",
        "user": {
            "id": 1,
            "email": "sinyr119@gist.ac.kr"
        }
    },
    {
        "id": 4,
        "category": "category1",
        "title": "식당 ~건의합니다",
        "content": "~한 문제 해결 바랍니다",
        "user": {
            "id": 1,
            "email": "sinyr119@gist.ac.kr"
        }
    },
    {
        "id": 5,
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

