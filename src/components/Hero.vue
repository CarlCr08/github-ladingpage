<template>
  <div class="hero">
     <div class="hero-container">
          <div class="hero-data">
          <h1>Built for developers</h1>
          <p>GitHub is a development platform inspired by the way you work. From open source to business, you can host and review code, manage projects, and build software alongside 40 million developers. </p>
      </div>
      <div class="hero-auth">
          <label for="username">Username</label>
          <input type="text" name="" id="username">

           <label for="useremail">Email</label>
          <input type="email" name="" id="useremail">

            <label for="userpassword">Password</label>
          <input type="password" name="" id="userpassword">
          <p class="text-desc">
              Make sure it's at least 15 characters OR at least 8 characters including a number and a lowercase letter. Learn more.
          </p>
          <button class="sign_up_for_github">
              Sign Up for Github
          </button>
          <p class="text-terms">
              By clicking “Sign up for GitHub”, you agree to our Terms of Service and Privacy Statement. We’ll occasionally send you account related emails.
          </p>
      </div>
     </div>
  </div>
</template>

<script>
export default {
    name:'Hero'
}
</script>

<style lang="scss" scoped>
    .hero{
        padding: 64px 0;
        box-sizing: border-box;
        height: 631px;
        width: 100%;
        background-color: #2b3137;
        background-image: url("./../assets/simple-codelines.svg");
        background-size: cover;
        background-repeat: no-repeat;
        background-position: center 10%;
        display: flex;
        justify-content: center;
        align-items: center;
        .hero-container{
            width: 1080px;
            height: 503px;
            display: flex;
            justify-content: center;
            align-items: center;
            .hero-data{
                width: 553px;
                height: 288px;
                display: flex;
                justify-content:center;
                flex-direction: column;
                align-items: flex-start;
                padding: 0 24px;
                box-sizing: border-box;
                h1{
                    color: #fff;
                    text-align: start;
                    font-size: 68px;
                    font-weight: 500;
                    padding-bottom: 16px;
                }
                p{
                    color:rgba(255,255,255,.6);
                    text-align: justify;
                    font-size: 20px;
                    padding-bottom: 24px;
                    padding-right: 34px;
                }
        }
        .hero-auth{
            width: 426px;
            height: 503px;
            display: flex;
            flex-direction: column;
            background-color: #fafbfc;
            padding:24px; 
            align-items: center;
            box-sizing: border-box;
            border-radius: 4px;
            label{
                text-align: start;
                margin-bottom: 5px;
                font-size: 14px;
                color: #2b3137;
                font-weight: bold;
            }
            input{
                width: 376px;
                height: 26px;
                padding:10px;
                border: 1px solid #ccc;
                border-radius: 6px;
                background-color: #fafbfc;
                margin: 10px 0;
            }
            .text-desc{
                font-size: 12px;
                text-align: start
            }
            .sign_up_for_github:hover{
                background-color: #28a745;
            }
            .sign_up_for_github{
                height: 66px;
                background-color: #2ebc4f;
                padding:20px 32px;
                color: #fff;
                margin: 16px;
                width: 376px;
                border: 1px solid #28a745 ;
                border-radius: 6px;
                font-size: 16px;
                font-weight: 600;
                cursor: pointer;
            }
        }
        }
       
    }
</style>