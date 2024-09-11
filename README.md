# clone-page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Google Clone</title>
    <link rel="stylesheet" href="styles.css">
    <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css"
  />
    <style>

      body {
     font-family: Arial, sans-serif;
     display: flex;
     flex-direction: column;
     justify-content: space-between;
     height: 100vh;
     margin: 0;
}

.header-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 20px;
}
.header-left{
  display:flex;
  
  justify-content: left;
  text-decoration:none;
  padding: 20px;
  gap:20px;
}


.header-right{
  display:flex;
  text-decoration:none;
  justify-content: right;
  gap:10px;
}
.header-center{
  display:flex;
  justify-content: center;
}


.search-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-top: 20px;
  border:1px solid #dadce0;
  border-radius: 50px;
  
}

.button{
  display:flex;
  margin-top:-480px;
  justify-content: center;
  border:1px solid #dadce0;
  border-radius: 50px;
  gap:20px;
    
  
}

footer {
            text-align: center;
            width: 100%;
            background-color: #f2f2f2;
            padding: 10px 0;
        }

        .footer-links
        {
            display: flex;
            justify-content: CENTER;
            gap: 15px;
            margin-top: 10px;  
        }

        .footer-links a{
          color:#333;
          font-size:14px;
          text-decoration:none;
        }

        .footer-links a:hover{
          text-decoration: underline;
        }

    </style>
</head>
<body>
  <div class="container">
    <header>
        <div class="header-left">
          <a href="https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=webhp&cd=&cad=rja&uact=8&ved=0ahUKEwj78_in3qOIAxVHcfUHHeQxD6YQkNQCCAI&url=https%3A%2F%2Fabout.google%2F%3Ffg%3D1%26utm_source%3Dgoogle-KR%26utm_medium%3Dreferral%26utm_campaign%3Dhp-header&usg=AOvVaw1cT2xJsr6QSN0Sgr_QKIau&opi=89978449">google 정보 </a>
          <a href="https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=webhp&cd=&cad=rja&uact=8&ved=0ahUKEwj78_in3qOIAxVHcfUHHeQxD6YQpMwCCAM&url=https%3A%2F%2Fstore.google.com%2FKR%3Futm_source%3Dhp_header%26utm_medium%3Dgoogle_ooo%26utm_campaign%3DGS100042%26hl%3Dko-KR&usg=AOvVaw0kcrhGagmvACzKvZMeJDk6&opi=89978449">스토어 </a>
        </div>

        <div class="header-right">
       <a href="https://mail.google.com/mail/&ogbl"> Gmail</a>
         <a href="https://www.google.com/imghp?hl=ko&ogbl"> 이미지</a>
       <i class= "fas fa-th">  </i>
         <i class="fas fa-user-circle"></i>
       </div>

      </header>
        <div class="header-center">
            <img src="https://www.google.co.kr/logos/doodles/2024/paris-games-archery-day-2-6753651837110537-law.gif" alt="Google Logo" class="logo">
        </div>
            <div class="search-container">
                <input type="text">
               
            </div>
            
        </div>
        <div class="button">
        <button>Google search</button>
            <button><a href="https://doodles.google/"> I'm Feeling Lucky</a>
             </button>
          </div>

          <footer>
            <div class="footer-links">
              <a href="#"> 대한민국</a>
              <a href="https://www.google.co.kr/url?sa=t&rct=j&q=&esrc=s&source=webhp&cd=&cad=rja&uact=8&ved=0ahUKEwiK5vTE3aOIAxW3s1YBHf00N7IQkdQCCCM&url=https%3A%2F%2Fwww.google.co.kr%2Fintl%2Fko_kr%2Fads%2F%3Fsubid%3Dww-ww-et-g-awa-a-g_hpafoot1_1!o2%26utm_source%3Dgoogle.com%26utm_medium%3Dreferral%26utm_campaign%3Dgoogle_hpafooter%26fg%3D1&usg=AOvVaw2DTsNAFuasH8Evy_WmjRNN&opi=89978449">광고 </a>
              <a href="https://www.google.co.kr/url?sa=t&rct=j&q=&esrc=s&source=webhp&cd=&ved=0ahUKEwiK5vTE3aOIAxW3s1YBHf00N7IQ8awCCCU&url=https%3A%2F%2Fpolicies.google.com%2Fprivacy%3Fhl%3Dko%26fg%3D1&usg=AOvVaw2z-w5pAKr1ke0kFjydmRr4&opi=89978449">개인정보 처리 방침</a>
              <a href="https://www.google.co.kr/url?sa=t&rct=j&q=&esrc=s&source=webhp&cd=&ved=0ahUKEwiK5vTE3aOIAxW3s1YBHf00N7IQ8qwCCCY&url=https%3A%2F%2Fpolicies.google.com%2Fterms%3Fhl%3Dko%26fg%3D1&usg=AOvVaw1zVxsVctgi9_0I6FmlThVO&opi=89978449">약관 </a>

            
            </div>
            </footer>
          
</body>
</html>
