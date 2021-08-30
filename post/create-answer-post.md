# Create Answer Post

## METHOD

```text
POST
```

## URL EXAMPLE

```text
/gistps/api/v1/post/:postId
```

#### postId: 게시물 고유 id

## REQUEST BODY

| name | type | description |
| :--- | :--- | :--- |
| userId | long | 작성하는 유저 id \(서버에 저장된 id -숫자\) |
| description | string | 내용 |
| category | string | 카테고리 |

### REQUEST BODY EXAMPLE

```javascript
{
    "userId" : 1,
    "description" : "안녕하세요 ~한 문제에 대한 답변입니다"
}
```

### RESPONSE BODY 

| type | description |
| :--- | :--- |
| Long | 생성된 게시글의 고유 id |

### RESPONSE BODY EXAMPLE

```javascript
4
```

