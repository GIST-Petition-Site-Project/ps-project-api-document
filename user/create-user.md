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
| password | string | 필수 | 유저 비밀번 |
| username | string | 필수 | 유저 이름 |
| email | string | 필수 | 유저 이메일 |

### REQUEST BODY EXAMPLE

```javascript
{
    "email" : "sinyr119@gist.ac.kr",
    "password" : "qwer1234", 
    "username" : "koseyeon"
}
```



