<style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, Helvetica, sans-serif;
        }
        typography {
            color: #030303;
            text-align: center;
            font-family: Poppins;
            font-size: 34px;
            font-style: normal;
            font-weight: 500;
            line-height: normal;
            letter-spacing: 1.02px;
            text-transform: uppercase;
        }
</style>
<template>
    
   <div style="width: 100vw !important; height: 100vh !important; display: flex; flex: 1;">
        <div style="">
            <h1 style="font-family: Arial, Helvetica, sans-serif;">Welcome Back</h1>
            <p>Welcome back! Please enter your details.</p>
            <form action="">
                <label for="">Email</label>
                <input type="text" name="" id="" placeholder="Enter your email">
                <label for="">Password</label>
                <input type="text" name="" id="" placeholder="Enter your password">
                <div>
                    <input type="checkbox">
                    <span>Remember me</span>
                    <span>Forgot password</span>
                </div>
                <button>Sign In</button>
                <button>Sign In with Google</button>
            </form>
            <p>Don't have an account? <a href="">Sign up for free!</a></p>
        </div>
        <div>

        </div>
   </div>
</template>