# Group  UserController

## 用户登陆 [POST /users/login]
+ Request (application/json) 
    {
        "login": "tester",(string,required) -用户名或者手机号 ,必填
        "password": "12346" (number,required) 密码 ,必填
    }
+ Response 200 (application/json) 
    {
    "token": "fesrglkthtgrtgktlttthy" (string)用户令牌
    }
+ Exception 
    ParameterException("Invalid user name or password.")  - 400, 用户名/电话/电邮/密码不对
    UserAccountException("User account suspended.")  - 401, 帐户已被暂停
    UserAccountException("User account terminated.")  - 401, 帐户已被删除

