# Create Post

## METHOD

```text
POST
```

## URL EXAMPLE

```text
/gistps/api/v1/post
```



## REQUEST BODY

| name | type | description |
| :--- | :--- | :--- |
| user\_id | long | 작성하는 유저 id |
| title | string | 제목 |
| description | string | 내용 |
| category | string | 카테고리 |

### REQUEST BODY EXAMPLE

```javascript
{
    "user_id" : "sinyr119",
    "title" : "기숙사 ~에 대해 건의합니다",
    "description" : "~한 문제 해결 바랍니다",
    "category" : "분류1"
}
```



