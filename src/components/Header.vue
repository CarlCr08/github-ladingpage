<template>
    <div class="header">
        <header>
          <div class="menu-container-left">
              <img src="@/assets/GitHub-Mark.png" alt="" srcset="">
              <ul>
                  <li>Why Github?</li>
                  <li>Enterprise</li>
                  <li>Explore</li>
                  <li>Marketplace</li>
                  <li>Pricing</li>
              </ul>
          </div>
          <div class="menu-container-right">
              <input class="input-search" placeholder="Search Github" type="search" name="" id=""/>
              <button class="button-sign_in">Sign In</button>
              <button class="button-sign_up">Sign Out</button>
          </div>
      </header>
    </div>
</template>

<script>
export default {
    name:'Header'
}
</script>

<style lang="scss" scoped>
    .header{
        width:100%;
        background-color: #24292e;
        display: flex;
        justify-content: center;
    }
    header{
        width:100%;
        max-width: 1280px;
        height: 72px;
        background-color: #24292e;
        padding: 0;
        box-sizing: border-box;
        display: flex;
        justify-content: space-between;
        align-items: center;
        img{
            width: 32px;
            height:32px;
            padding: 0 0 0 16px;
        }
        .menu-container-left{
            width: 100%;
            display: flex;
            justify-content: flex-start;
            ul{
                display: flex;
                align-items: center;
                list-style: none;
                padding: 0 15px;
                li{
                    color: #fff;
                    padding: 0 10px;
                    margin: 0;
                    font-size: 16px;
                }
            }
            }
            .menu-container-right{
                display: flex;
            .input-search:hover{
                    background-color: #fff;
                    color: #24292e;
                }
            .input-search::placeholder{
                color: #999;
                font-weight: 600;
            }
            .input-search{
                background-color: #444;
                border:none;
                width: 230px;
                border-radius: 4px;
                padding: 10px 5px;
            }
            .button-sign_in{
                border: none;
                color: #fff;
                width: 80px;
                background-color: transparent;
                font-size: 16px;
            }
            .button-sign_up{
                border: .5px solid #fff;
                color: #fff;
                width: 80px;
                background-color: transparent;
                font-size: 14px;
                border-radius: 2px;
            }
        }
    }
</style>