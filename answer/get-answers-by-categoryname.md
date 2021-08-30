# Get Answers by categoryName

### METHOD

```text
GET
```

### URL

```text
/gistps/api/v1/answer/category?categoryName=분류1
```

#### categoryName: 게시물이 해당하는 카테고리 이름 \(ex -분류1\)

### QUERY STRING

| name | type | require | descriptio |
| :--- | :--- | :--- | :--- |
| category | string | 선택 | 선택한 카테고리에 해당하는 게시물을 불러옴 |

#### RESPONSE BODY EXAMPLE

```text
[
    {
        "id": 1,
        "title": "RE:기숙사 ~에 대해 건의합니다",
        "description": "안녕하세요 ~한 문제에 대한 답변입니다",
        "category": "분류1",
        "created": "2021-08-30",
        "userId": 1
    },
    {
        "id": 2,
        "title": "RE:기숙사 ~에 대해 건의합니다",
        "description": "안녕하세요 ~한 문제에 대한 답변입니다2",
        "category": "분류1",
        "created": "2021-08-30",
        "userId": 1
    },
    {
        "id": 3,
        "title": "RE:기숙사 ~에 대해 건의합니다",
        "description": "안녕하세요 ~한 문제에 대한 답변입니다3",
        "category": "분류1",
        "created": "2021-08-30",
        "userId": 1
    },
    {
        "id": 4,
        "title": "RE:기숙사 ~에 대해 건의합니다",
        "description": "안녕하세요 ~한 문제에 대한 답변입니다4",
        "category": "분류1",
        "created": "2021-08-30",
        "userId": 1
    }
]
```

