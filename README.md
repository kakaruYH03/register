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
  '_id':1234567890',
  'id':'gk12',
  'nickname':'유니팅'
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
  '_id':1234567890',
  'id':'gk12',
  'nickname':'유니팅'
}
</pre>

### 실패

<pre>
{
'message':'400 Bad Response'
}
</pre>
