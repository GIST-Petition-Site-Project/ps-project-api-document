# Get My Posts



## METHOD

```text
GET
```

## URL EXAMPLE

```text
/gistps/api/v1/user/:id/post
```

#### id: 유저 고유 id \(숫자\)

### RESPONSE BODY EXAMPLE

```javascript
[
    {
        "id": 1,
        "comment": [],
        "title": "기숙사 ~에 대해 건의합니다",
        "description": "~한 문제 해결 바랍니다",
        "category": "분류1",
        "created": "2021-08-12",
        "answered": false,
        "accepted": 0,
        "userId": 1
    },
    {
        "id": 2,
        "comment": [],
        "title": "기숙사 ~에 대해 건의합니다2",
        "description": "~한 문제 해결 바랍니다2",
        "category": "분류1",
        "created": "2021-08-12",
        "answered": false,
        "accepted": 0,
        "userId": 1
    }
]
```

