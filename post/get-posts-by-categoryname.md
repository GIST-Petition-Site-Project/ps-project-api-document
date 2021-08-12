# Get Posts by categoryName



### METHOD

```text
GET
```

### URL

```text
/gistps/api/v1/post/category?categoryName=분류2
```

#### categoryName: 게시물이 해당하는 카테고리 이름 \(ex -분류2\)

### QUERY STRING

| name | type | require | descriptio |
| :--- | :--- | :--- | :--- |
| category | string | 선택 | 선택한 카테고리에 해당하는 게시물을 불러옴 |

#### RESPONSE BODY EXAMPLE

```text
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
        "user_id": "hong123",
        "created": "2021-07-30T20:10:50.642331",
        "answered": false,
        "accepted": 0,
    },
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
        "user_id": "hong123",
        "created": "2021-07-30T20:10:50.642331",
        "answered": false,
        "accepted": 0,
    },
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
]
```

