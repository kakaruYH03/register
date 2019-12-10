# register

## 회원가입

### 요청
> [POST] /mysample/register

전달값

<pre>
{
  'id':'gkdl',
  'password':'gk12',
  'nickname':'유니팅'
}
</pre>

### 결과

#### 성공

<pre>
{
    "id": "gk12",
    "nickname": "유니팅",
    "password": "rSFp9e5uwHrHwWgAhV/ZGV3tlPuQ7arnEcLS7P6e0kvXwTqr8tspHEfp6hdjyWtx+xKr+uHo4mzmaGBVmoTfDA==",
    "_id": "5def6144fe3fee07bc720774"
}
</pre>

### 실패

<pre>
{
  'message':'400 Bad Response'
}
</pre>

## 로그인

### 요청
> [POST] /mysample/login

전달값

<pre>
{  
  "id":"gk12",
  "password":"gk12"
}
</pre>

### 성공

<pre>
{
  "id:"gk12",
  "password":gk12"
}
</pre>

### 실패

<pre>
{
"message":"400 Bad Response"
}
</pre>
