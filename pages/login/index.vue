<style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, Helvetica, sans-serif;
            text-align: center;
            font-size: 14px;
        }
        input[type="text"] {
            border-radius: 12px;
            border: 1px solid rgba(0, 0, 0, 0.25);
            background: rgba(196, 196, 196, 0.00);
            box-shadow: 0px 4px 10px 0px rgba(0, 0, 0, 0.25);
            height: 40px;
            width: 100%;
            padding: 0 10px;
            
            margin-bottom: 20px;
        }
        label {
            font-size: 16px;
            text-align: left;
            font-weight: bold;
        }
        button {
            border-radius: 12px;
            background: #000;
            color: #fff;
            cursor: pointer;
            box-shadow: 0px 4px 10px 0px rgba(233, 68, 75, 0.25);
            width: 100%;
            margin: 5px;
            height: 35px;
        }
        #left div {
            width: 100%;
            
        }
        #left {
            width: 100%;
        }
       
</style>
<template>
    
   <div style="width: 100vw !important; height: 100vh !important; display: grid; grid-template-columns: 1fr 1fr;">
        <div id="left" style="display: flex; justify-content: center; align-items: center; flex-direction: column;">
            <div>
                <h1 style="font-size: 34px; text-transform: uppercase; margin-bottom: 0;">Welcome Back</h1>
                <p style="font-size: 14px; margin-top: 0;">Welcome back! Please enter your details.</p>
            </div>
            <form action="" style="text-align: left; padding-left: 8px; width: 400px">
                <label for="">Email</label><br>
                <input type="text" name="" id="" placeholder="Enter your email" ><br>
                <label for="">Password</label><br>
                <input type="text" name="" id="" placeholder="Enter your password">
                <div style="display: flex; justify-content: space-between; margin-bottom: 7px;">
                    <div >
                    <input type="checkbox">
                    <span>Remember me</span>
                    </div>
                    <span style="width: 150px;">Forgot password</span>
                </div>
                <button><a style="text-decoration: none; color: white;" href="/dashboard">Sign In</a></button><br>
                <button style="background-color: #fff; color: black;">Sign In with Google</button>
            </form>
            <p>Don't have an account? <a href="/register">Sign up for free!</a></p>
        </div>
        <div style="background-image: url(https://images.unsplash.com/photo-1610433572201-110753c6cff9?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D); background-size: cover;">
            
        </div>
   </div>
</template>