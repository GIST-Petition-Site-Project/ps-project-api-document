# Create User



## METHOD

```text
POST
```

## URL EXAMPLE

```text
/gistps/api/v1/user
```



## REQUEST BODY

| name | type | require | description |
| :--- | :--- | :--- | :--- |
| userId | string | 필수 | 유저 아이디 |
| userPassword | string | 필수 | 유저 비밀번 |
| username | string | 필수 | 유저 이름 |
| email | string | 필수 | 유저 이메일 |

### REQUEST BODY EXAMPLE

```javascript
{
    "userId" : "sinyr119",
    "userPassword" : "qwer1234", 
    "username" : "koseyeon",
    "email" : "sinyr119@gist.ac.kr"
}
```



