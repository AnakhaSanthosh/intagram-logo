# intagram-logo
Instagram logo making using HTML5, CSS
HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Instagram Logo</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <div class="insta">
            <div class="insta-inner">
                <div class="insta-inner2">
                    
                </div>

            </div>
        </div>


    </div>
    
</body>
</html>

CSS

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
.container{
   width:100% ;
   height: 100vh;
   background: rgb(3, 3, 43);
   display: flex;
   align-items: center;
   justify-content: center;
}
.insta{
    width: 270px;
    height: 270px;
    background: radial-gradient(circle at 33% 100%, #fed373 4%, #f15245 30%, #d92e7f 62%, #9b36b7 85%);
    border-radius: 54px;
    display: flex;
    align-items: center;
    justify-content: center;
}
.insta-inner{
    width: 200px;
    height: 200px;
    border: 18px solid #fff;
    border-radius: 54px;
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
    
}
.insta-inner2{
    width: 100px;
    height: 100px;
    border: 18px solid #fff;
    border-radius: 50px;
}
.insta-inner::after{
    content: '';
    background: #fff;
    width: 22px;
    height: 22px;
    border-radius: 50%;
    position:absolute;
    top: 15px;
    right: 15px;

}
