simple javascript repo
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <meta http-equiv="X-UA-Compatible" content="IE=edge" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0/>
        <title>Website with Login & Registration Form</title>
        <link rel= "stylesheet" href="">
    </head>
    <body>
        <header class="header">
           <nav class="nav">
            <a href="#" class="nav_logo">Moldays</a>

            <ul class="nav_items">
                <li class="nav_item">
                    <a href="#" class="nav_link">Home</a>
                    <a href="#" class="nav_link">Products</a>
                    <a href="#" class="nav_link">Services</a>
                    <a href="#" class="nav_link">Contact</a>
                </li>
            </ul>

            <button type="button" id="form-open">Login</button>
           </nav>
        </header>

        <section class="home">
            <div class="form_container">
                <i class="" ></i>
                <div class="form login_form">
                    <form action="#">
                        <h2>Login</h2>
                        <div class="input_box">
                            <input type="email" placeholder="Enter your email address" required/>
                            <i class=""></i>
                        </div>
                        <div class="input_box">
                            <input type="password" placeholder="Enter your password" required/>
                            <i class=""></i>
                            <i class=""></i>
                        </div>
                        <div class="option_field">
                            <span class="checkbox">
                                <input type="checkbox" id="check"/>
                                <label for="check">Remember me</label>
                            </span>
                            <a href="#" class="forgot_pwd">Forgot password?</a>
                        </div>
                        <button class="button">Login Now</button>

                        <div class="login_signup">Don't have an account?<a href="#" id="signup">Signup</a></div>
                    </form>
                </div>
                
                <div class="form signup_form">
                    <form action="#">
                        <h2>Signup</h2>
                        <div class="input_box">
                            <input type="email" placeholder="Enter your email" required/>
                        <i class="envelop"></i>                        
                    </div>
                    <div class="input_box">
                        <input type="password" placeholder="Enter your password" required/>
                        <i class=""></i>
                        <i class=""></i>
                    </div>
                    <button class="button">Signup Now</button>

                    <div class="login_signup">Already have an account?<a href="#" id="login">Login</a></div>
                    </form>
                </div>
             </div>
              </body>
</html>
