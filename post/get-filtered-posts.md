# Get Filtered Posts

### METHOD

```text
GET
```

### URL

```text
/gistps/api/v1/post/list?top=0&size=10&answered=true
```

### QUERY STRING

| name | type | require | description |
| :--- | :--- | :--- | :--- |
| top | number | 선택, 기본값 = 0 | 참여인원이 많은 순서대로 게시물 top개를 불러옴 |
| size | number | 선택, 기본값 = 10 | 불러올 게시물의 개수 |
| answered | boolean | 선택, 기본값 = false | 답변한 게시물을 불러옴 |
|  |  |  |  |

#### RESPONSE BODY EXAMPLE

```text
[
   {
        "id": 1,
        "category": "category1",
        "title": "기숙사 ~건의합니다",
        "content": "~한 문제 해결 바랍니다",
        "answered": true
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
        "answered": true
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
        "answered": true
          
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
        "answered": true
        "user": {
            "id": 1,
            "email": "sinyr119@gist.ac.kr"
        }
    }
]
```

