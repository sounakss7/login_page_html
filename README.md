<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LOGIN PAGE</title>
    <style>
        hr{
            border-color: darkorange;
        }
        header{
            color: rgb(142, 111, 55);
        }
        h3{
            text-align: center;
            color: rgb(239, 11, 57);
        }
        h4{
            text-align:center;
            color: rgb(239, 14, 14);
        }
        section{
            text-align: center;
            color: rgb(239, 14, 14);
        }
        p{
            color: rgb(239, 14, 14);
            text-align: center;
        }
        body{
            padding: 20px 20px 20px 20px ;
            margin: 15px 15px 15px 15px;
            border: 2px solid red;

            background-color :black;
            background-image: url(data:image/jpeg;base64,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);
            background-repeat: no-repeat;
            background-size: cover;
        }
        
    </style>
</head>
<body>
    <header><h3> <U><b>LOGIN PAGE</b></U></h3></header>
    <HR>
    <P><h3>Username : <input type="text" id="text" placeholder="username"></h3></p>
        <P><h3>Password: <input type="password" id="password" placeholder="ENTER PASSWORD"></h3></p>
            <section><h4>forget password?</h4><p><u><select name="forget password">SELECT OTHER OPTION FOR SIGN IN
                <option value="OTP">SELECT OTHER OPTION FOR SIGN IN</option>
                <option value="SMS">PHONE NUMBER</option>
                <option value="OTP">OTP</option>
                <option value="SMS">SMS</option>
                <option value="WP">WHATSAPP</option>
            </select> </u></p></section>

<a href="index2.html"><p><h3><input type="submit" id="submit" name="submit" value="submit"></h3></p></a>
    <hr>
    <p><b>THANK YOU FOR VISITING OUR SOCIAL MEDIA WEBSITE</b></p>

</body>
</html>
