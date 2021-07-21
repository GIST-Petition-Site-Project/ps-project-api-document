# Create User



## METHOD

```text
POST
```

## URL

```text
/gistps/api/v1/user/
```



## REQUEST BODY

| name | type | require | description |
| :--- | :--- | :--- | :--- |
| username | string | 필수 | 유저 이름 |
| email | string | 필수 | 유저 이메일 |

### REQUEST BODY EXAMPLE

```javascript
{
    "username": "koseyeon",
    "email": "sinyr119@gist.ac.kr"
}
```



