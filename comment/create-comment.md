# Create Comment



## METHOD

```text
POST
```

## URL EXAMPLE

```text
/gistps/api/v1/post/:Id/comment
```

* id: 게시물 고유 id

## REQUEST BODY

| name | type | require | description |
| :--- | :--- | :--- | :--- |
| postId | long | 필수 | 게시글 고유 id |
| content | string | 필수 | 작성할 댓글 내용 |

### REQUEST BODY EXAMPLE

```javascript
{
        "postId": 1,
        "content": "저도 동의합니다"
}
```

