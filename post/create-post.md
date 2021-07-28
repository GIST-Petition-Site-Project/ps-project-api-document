# Create Post

## METHOD

```text
POST
```

## URL EXAMPLE

```text
/gistps/api/v1/post/
```



## REQUEST BODY

| name | type | description |
| :--- | :--- | :--- |
| userId | long | 작성하는 유저 id |
| title | string | 제목 |
| content | string | 내용 |
| category | string | 카테고리 |

### REQUEST BODY EXAMPLE

```javascript
{
    "userId" : 1,
    "title" : "기숙사 ~에 대해 건의합니다",
    "content" : "~한 문제 해결 바랍니다",
    "category" : "분류1"
}
```



