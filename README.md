<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <title>The Login Form</title>
    <style>
        
    *{
        margin:0;
        padding: 0;
        box-sizing: border-box;
    }
    html{
        height: 100%;
    }
    body{
        font-family: 'Segoe UI', sans-serif;;
        font-size: 1rem;
        line-height: 1.6;
        height: 100%;
    }
    .wrap {
        width: 100%;
        height: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        background: #fafafa;
    }
    .login-form{
        width: 350px;
        margin: 0 auto;
        border: 1px solid #ddd;
        padding: 2rem;
        background: #ffffff;
        box-shadow: 10px -10px  rgba(0,0,0,0.6);
        border-radius:25px;
    }
    .form-input{
        background: #fafafa;
        border: 1px solid #eeeeee;
        padding: 12px;
        width: 100%;
    }
    .form-group{
        margin-bottom: 1rem;
    }
    .form-button{
        background: #69d2e7;
        border: 1px solid #ddd;
        color: #ffffff;
        padding: 10px;
        width: 100%;
        text-transform: uppercase;
    }
    .form-button:hover{
        background: #69c8e7;
    }
    .form-header{
        text-align: center;
        margin-bottom : 2rem;
    }
    .form-footer{
        text-align: center;
    }
    
    </style>
</head>
<body>
    <div class="wrap">
    <form class="login-form" action="">
    <div class="form-header">
    <h3>Login Form</h3>
    <p>Login to access your dashboard</p>
    </div>
    <!--Username Input-->
    <div class="form-group">
    <input type="text" class="form-input" placeholder="Username">
    </div>
              
    <!--Password Input-->
    <div class="form-group">
    <label for="pass">Password (8 characters minimum):</label>
    <input type="password" class="form-input" placeholder="password" id="pass">
    
    
    </div>
    <!--Login Button-->
    <div class="form-group">
    <button class="form-button" type="submit">Login</button>
    <a href="#!">Forgot password?</a>
    </div>
    <div class="form-footer">
    Don't have an account? <a href="#">Sign Up</a>
    </div>
    </form>
    </div><!--/.wrap-->
</body>
</html>
