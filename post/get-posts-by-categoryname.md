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

