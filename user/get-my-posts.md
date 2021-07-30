# Get Posts by user Id



## METHOD

```text
GET
```

## URL EXAMPLE

```text
/gistps/api/v1/user/:id/post
```

#### id: 유저 id

### RESPONSE BODY EXAMPLE

```javascript
[
   {
        "id": 1,
        "category": "category1",
        "title": "기숙사 ~건의합니다",
        "description": "~한 문제 해결 바랍니다",
        "user_id": "sinyr119",
        "created": "2021-07-30T20:10:50.642331",
        "answered": false,
        "accepted": 0,
    },
    {
        "id": 2,
        "category": "category2",
        "title": "식당 ~건의합니다",
        "description": "~한 문제 해결 바랍니다",
        "user_id": "sinyr119",
        "created": "2021-07-30T20:10:50.642331",
        "answered": false,
        "accepted": 0,
    }
]
```

