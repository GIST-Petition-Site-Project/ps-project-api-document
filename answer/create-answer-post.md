# Create Answer

## METHOD

```text
POST
```

## URL EXAMPLE

```text
/gistps/api/v1/answer/:postId
```

#### postId: 답변할 게시물 고유 id

## REQUEST BODY

| name | type | description |
| :--- | :--- | :--- |
| userId | long | 작성하는 유저 id \(서버에 저장된 id -숫자\) |
| description | string | 내용 |

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

### RESPONSE BODY EXAMPLE \(답변 정상적으로 생성\)

```javascript
4

```

### RESPONSE BODY EXAMPLE \(답변 생성 실패\)

```javascript
-1 or -2 or -3
```



