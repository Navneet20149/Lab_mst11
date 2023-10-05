# Lab_mst11


<!DOCTYPE html>
<html>
<head>
    <title>Signup Page</title>
    <style>
        #signup{
            display: flex;
            justify-content: center;
            padding-top: 30px;  
        }
        form{
            text-align: center;
            margin: 2rem;
        }
        input{
            margin: .7rem;
            height: 1.7rem;
            width: 16rem;
        }
        .SignForm{
            border: 2px solid black;
            border-radius:10px;
            width: 500px;
            height: 500px;
        }
        h1{
            text-align: center;
        }

        button{
            height: 2rem;
            width: 16rem;
            border-radius: 1rem;
            border: none;
            font-family: monospace;
            columns: white;
            background-color: crimson;

        }
        button:hover{
            color: white;
            background-color: black;
            text-align: center;
            cursor: pointer;
        } 
    </style>
</head>

<body>
    <div id="signup">
    <div class="SignForm">
    <h1>Signup</h1>

        <form action="/signup" method="post">
            <label for="username">Username:</label>
            <input type="text" id="username" name="username" required><br><br>

            <label for="username">Full Name:</label>
            <input type="text" id="fullname" name="fullname" required><br><br>

            <label for="email">Email Id:</label>
            <input type="email" id="email" name="email" required><br><br>

            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required><br><br>

            <button type="submit">Sign Up</button>
            <p>Don't have an account <a href="LoginForm.html">Sign In</a></p>
        </form>
    </div>
</div>
</body>

</html>
