# Get Number of Answered Posts



## METHOD

```text
GET
```

## URL

```text
/gistps/api/v1/post/count?answered=true
```

## QUERY STRING

| name | type | description |
| :--- | :--- | :--- |
| **answered** | boolean | 답변 완료 여 |

**count: 전체 게시물 수 \(number\)**

### RESPONSE BODY EXAMPLE

```javascript
{
   "count": 100
}
```



