<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1" />
<title>Week-1</title>
<style type="text/css" >

header{
    display:flex;
}

body{
    margin:0px;box-sizing:border-box;
}
.left{
    flex:none;width:100px;font-size:20px;
}
.space{
    flex:auto;
}
.right{
    flex:none;font-size:20px;
}
.showburger{
    display:none;
}
.welcome{
    font-weight:bold;background-color:#83d2ff;
    height:300px;text-align:center;padding:0px;
    line-height:300px;width:100%;font-size:40px;
}
.box{
    width:1200px;margin-left:auto;margin-right:auto;
}
main{
    display:flex;flex-wrap:wrap;justify-content:center;
}
.item{
    display:inline-block;flex:none; width:270px;margin:10px;
    background-color:#95d2f5;
}
.item img{
    width:100%;
}
.moji{
    font-size:20px;text-align:center;color:black;
}
@media (max-width:1200px) 
{
     .box{width:90%;text-align:center;} 
     .item{width:45%;}    
}
@media (max-width:600px)
{
    .box{width:100%;text-align:center;}
    .item{width:90%;}
    .right{display:none;}
    .showburger{display:contents;}
}
</style>

</head>

<body>
    <header>
    <div class="left">My Website</div>

    <div class="space"></div>

    <div class="right">
        <span>Item1</span>
        <span>Item2</span>
        <span>Item3</span>
        <span>Item4</span>
    </div>
    <a href="#" class="showburger">
        <img src="https://cdn4.iconfinder.com/data/icons/core-ui-outlined/32/outlined_menu-512.png" width="20px">
    </a>
    </header>
    <middle>
    <div class="welcome">Welcome to MyHome</div>
    </middle>

    <main>

    <div class="box">

    <div class="item">
        <img src="https://raw.githubusercontent.com/kakami036/furry-invention/56041a4378291a0f363e12eed9573494cbbcde76/Sheipaa.jpg">
        <div class="moji">雪霸國家公園</div>
        </div>
    <div class="item">
        <img src="https://raw.githubusercontent.com/kakami036/furry-invention/56041a4378291a0f363e12eed9573494cbbcde76/Tarokoo.jpg">
        <div class="moji">太魯閣國家公園</div>
        </div>
    <div class="item">
        <img src="https://raw.githubusercontent.com/kakami036/furry-invention/56041a4378291a0f363e12eed9573494cbbcde76/Kengtingg.jpg">
        <div class="moji">墾丁國家公園</div>
        </div>
    <div class="item">
        <img src="https://raw.githubusercontent.com/kakami036/furry-invention/56041a4378291a0f363e12eed9573494cbbcde76/Kinmenn.jpg">
        <div class="moji">金門國家公園</div>
        </div>
    <div class="item">
        <img src="https://raw.githubusercontent.com/kakami036/furry-invention/56041a4378291a0f363e12eed9573494cbbcde76/Yushann.jpg">
        <div class="moji">玉山國家公園</div>
        </div>
        <div class="item">
        <img src="https://raw.githubusercontent.com/kakami036/furry-invention/56041a4378291a0f363e12eed9573494cbbcde76/Taijiangg.jpg">
        <div class="moji">台江國家公園</div>
        </div>
    <div class="item">
        <img src="https://raw.githubusercontent.com/kakami036/furry-invention/56041a4378291a0f363e12eed9573494cbbcde76/Yangmingg.jpg">
        <div class="moji">陽明山國家公園</div>
        </div>
    <div class="item">
        <img src="https://raw.githubusercontent.com/kakami036/furry-invention/56041a4378291a0f363e12eed9573494cbbcde76/Dongshaa.jpg"> 
        <div class="moji">東沙國家公園</div>
        </div>      
    </div> 
</main>  

</body>
</html>         
