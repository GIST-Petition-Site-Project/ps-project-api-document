# Get filtered Posts



## METHOD

```text
GET
```

## URL EXAMPLE

```text
/gistps/api/v1/post?answered=true&order=LATEST&category=ALL
```

## QUERY STRING

| name | type | description |
| :--- | :--- | :--- |
| **answered** | boolean | 답변 완료 여부 |
| **order** | string | 정렬 기준 |
| **category** | string | 카테고리 분류기준 |

### REQUEST BODY EXAMPLE

```javascript
{
	"answered": true,
	"order": "LATEST",
	"category": "ALL"
}
```

### RESPONSE BODY EXAMPLE

```javascript
[
		{
			"id": 1,
			"title": "00에 대해 청원합니다.",
			"date": "2021-07-13",
			"count": 15,
			"category": "분류1"
		},
		{
			"postId": 2,
			"title": "11에 대해 청원합니다.",
			"date": "2021-07-14",
			"count": 10,
			"category": "분류2"
		},
		{
			"postId": 3,
			"title": "22에 대해 청원합니다.",
			"date": "2021-07-15",
			"count": 6,
			"category": "분류1"
		}
	]
```

