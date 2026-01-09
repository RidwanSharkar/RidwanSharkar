<style>
@keyframes pulse {
  0%, 100% { box-shadow: 0 0 30px rgba(138,43,226,0.6), 0 0 60px rgba(30,144,255,0.4), 0 0 90px rgba(255,20,147,0.3), inset 0 1px 0 rgba(255,255,255,0.2); }
  50% { box-shadow: 0 0 40px rgba(138,43,226,0.8), 0 0 80px rgba(30,144,255,0.6), 0 0 120px rgba(255,20,147,0.5), inset 0 1px 0 rgba(255,255,255,0.3); }
}
@keyframes pulse-blue {
  0%, 100% { box-shadow: 0 0 30px rgba(0,255,255,0.6), 0 0 60px rgba(0,191,255,0.4), 0 0 90px rgba(30,144,255,0.3), inset 0 1px 0 rgba(255,255,255,0.2); }
  50% { box-shadow: 0 0 40px rgba(0,255,255,0.8), 0 0 80px rgba(0,191,255,0.6), 0 0 120px rgba(30,144,255,0.5), inset 0 1px 0 rgba(255,255,255,0.3); }
}
@keyframes pulse-red {
  0%, 100% { box-shadow: 0 0 30px rgba(255,69,0,0.6), 0 0 60px rgba(255,140,0,0.4), 0 0 90px rgba(255,20,147,0.3), inset 0 1px 0 rgba(255,255,255,0.2); }
  50% { box-shadow: 0 0 40px rgba(255,69,0,0.8), 0 0 80px rgba(255,140,0,0.6), 0 0 120px rgba(255,20,147,0.5), inset 0 1px 0 rgba(255,255,255,0.3); }
}
@keyframes slideshow {
  0%, 33.33% { opacity: 1; z-index: 1; }
  33.34%, 66.66% { opacity: 0; z-index: 0; }
  66.67%, 100% { opacity: 0; z-index: 0; }
}
@keyframes slideshow-2 {
  0%, 33.33% { opacity: 0; z-index: 0; }
  33.34%, 66.66% { opacity: 1; z-index: 1; }
  66.67%, 100% { opacity: 0; z-index: 0; }
}
@keyframes slideshow-3 {
  0%, 33.33% { opacity: 0; z-index: 0; }
  33.34%, 66.66% { opacity: 0; z-index: 0; }
  66.67%, 100% { opacity: 1; z-index: 1; }
}
</style>

<!-- Slideshow Container -->
<div style="position: relative; max-width: 750px; width: 100%; margin: 0 auto;">
  <!-- Slide 1: Portfolio -->
  <div style="position: relative; width: 100%; animation: slideshow 9s infinite; opacity: 1; z-index: 1;">
    <img src="https://github.com/user-attachments/assets/98204f76-b042-4ec2-8922-f6cf75193f87" alt="Skill tech tree" style="width: 100%; max-width: 750px; height: auto; border-radius: 10px;" />
    <a href="https://ridwansharkar.github.io" style="position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); text-decoration: none;">
      <div style="
        padding: 16px 32px;
        border-radius: 50px;
        background: linear-gradient(135deg, rgba(138,43,226,0.2) 0%, rgba(30,144,255,0.2) 50%, rgba(255,20,147,0.2) 100%);
        backdrop-filter: blur(25px);
        border: 1px solid rgba(138,43,226,0.4);
        box-shadow:
          0 0 20px rgba(138,43,226,0.3),
          0 0 40px rgba(30,144,255,0.2),
          inset 0 1px 0 rgba(255,255,255,0.1),
          inset 0 -1px 0 rgba(0,0,0,0.2);
        color: #ffffff;
        font-weight: 700;
        font-size: 16px;
        letter-spacing: 1px;
        text-shadow: 0 0 10px rgba(255,255,255,0.8), 0 0 20px rgba(138,43,226,0.6);
        display: flex;
        align-items: center;
        gap: 12px;
        transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
        position: relative;
        overflow: hidden;
        clip-path: polygon(0% 20%, 5% 0%, 95% 0%, 100% 20%, 100% 80%, 95% 100%, 5% 100%, 0% 80%);
      " onmouseover="this.style.transform='translate(-50%, -50%) scale(1.1)'; this.style.boxShadow='0 0 30px rgba(138,43,226,0.6), 0 0 60px rgba(30,144,255,0.4), 0 0 90px rgba(255,20,147,0.3), inset 0 1px 0 rgba(255,255,255,0.2)'; this.querySelector('.border-glow').style.opacity='1'; this.querySelector('.shine').style.left='100%'; this.style.animation='pulse 2s infinite'" onmouseout="this.style.transform='translate(-50%, -50%) scale(1)'; this.style.boxShadow='0 0 20px rgba(138,43,226,0.3), 0 0 40px rgba(30,144,255,0.2), inset 0 1px 0 rgba(255,255,255,0.1), inset 0 -1px 0 rgba(0,0,0,0.2)'; this.querySelector('.border-glow').style.opacity='0'; this.querySelector('.shine').style.left='-100%'; this.style.animation='none'">
        <div style="position: absolute; top: 0; left: -100%; width: 100%; height: 100%; background: linear-gradient(90deg, transparent, rgba(255,255,255,0.4), transparent); transition: left 0.8s;" onmouseover="this.parentElement.querySelector('.shine').style.left='100%'" class="shine"></div>
        <div style="position: absolute; top: -2px; left: -2px; right: -2px; bottom: -2px; background: linear-gradient(45deg, #8a2be2, #1e90ff, #ff1493, #8a2be2); border-radius: 50px; z-index: -1; opacity: 0; transition: opacity 0.4s;" onmouseover="this.parentElement.querySelector('.border-glow').style.opacity='1'" class="border-glow"></div>
        <span style="font-size: 20px; filter: drop-shadow(0 0 8px rgba(138,43,226,0.8)); text-shadow: 0 0 10px rgba(255,255,255,0.9); transition: all 0.3s;" onmouseover="this.style.transform='rotate(360deg) scale(1.2)'; this.style.filter='drop-shadow(0 0 15px rgba(138,43,226,1)) brightness(1.5)'" onmouseout="this.style.transform='rotate(0deg) scale(1)'; this.style.filter='drop-shadow(0 0 8px rgba(138,43,226,0.8)) brightness(1)'"></span>
        <span style="transition: all 0.3s;" onmouseover="this.style.color='#e0e0ff'; this.style.textShadow='0 0 20px rgba(138,43,226,0.8), 0 0 30px rgba(30,144,255,0.6)'" onmouseout="this.style.color='#ffffff'; this.style.textShadow='0 0 10px rgba(255,255,255,0.8), 0 0 20px rgba(138,43,226,0.6)'">PORTFOLIO</span>
      </div>
    </a>
  </div>

  <!-- Slide 2: Avernus -->
  <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; animation: slideshow-2 9s infinite; opacity: 0; z-index: 0;">
    <img src="https://github.com/user-attachments/assets/b8152586-1a47-493a-8de8-4bb1af1eaabc" alt="Avernus" style="width: 100%; max-width: 750px; height: auto; border-radius: 10px;" />
    <a href="https://avernus.vercel.app/" style="position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); text-decoration: none;">
      <div style="
        padding: 16px 32px;
        border-radius: 50px;
        background: linear-gradient(135deg, rgba(0,255,255,0.2) 0%, rgba(0,191,255,0.2) 50%, rgba(30,144,255,0.2) 100%);
        backdrop-filter: blur(25px);
        border: 1px solid rgba(0,255,255,0.4);
        box-shadow:
          0 0 20px rgba(0,255,255,0.3),
          0 0 40px rgba(0,191,255,0.2),
          inset 0 1px 0 rgba(255,255,255,0.1),
          inset 0 -1px 0 rgba(0,0,0,0.2);
        color: #ffffff;
        font-weight: 700;
        font-size: 16px;
        letter-spacing: 1px;
        text-shadow: 0 0 10px rgba(255,255,255,0.8), 0 0 20px rgba(0,255,255,0.6);
        display: flex;
        align-items: center;
        gap: 12px;
        transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
        position: relative;
        overflow: hidden;
        clip-path: polygon(0% 20%, 5% 0%, 95% 0%, 100% 20%, 100% 80%, 95% 100%, 5% 100%, 0% 80%);
      " onmouseover="this.style.transform='translate(-50%, -50%) scale(1.1)'; this.style.boxShadow='0 0 30px rgba(0,255,255,0.6), 0 0 60px rgba(0,191,255,0.4), 0 0 90px rgba(30,144,255,0.3), inset 0 1px 0 rgba(255,255,255,0.2)'; this.querySelector('.border-glow').style.opacity='1'; this.querySelector('.shine').style.left='100%'; this.style.animation='pulse-blue 2s infinite'" onmouseout="this.style.transform='translate(-50%, -50%) scale(1)'; this.style.boxShadow='0 0 20px rgba(0,255,255,0.3), 0 0 40px rgba(0,191,255,0.2), inset 0 1px 0 rgba(255,255,255,0.1), inset 0 -1px 0 rgba(0,0,0,0.2)'; this.querySelector('.border-glow').style.opacity='0'; this.querySelector('.shine').style.left='-100%'; this.style.animation='none'">
        <div style="position: absolute; top: 0; left: -100%; width: 100%; height: 100%; background: linear-gradient(90deg, transparent, rgba(255,255,255,0.4), transparent); transition: left 0.8s;" onmouseover="this.parentElement.querySelector('.shine').style.left='100%'" class="shine"></div>
        <div style="position: absolute; top: -2px; left: -2px; right: -2px; bottom: -2px; background: linear-gradient(45deg, #00ffff, #00bfff, #1e90ff, #00ffff); border-radius: 50px; z-index: -1; opacity: 0; transition: opacity 0.4s;" onmouseover="this.parentElement.querySelector('.border-glow').style.opacity='1'" class="border-glow"></div>
        <span style="font-size: 20px; filter: drop-shadow(0 0 8px rgba(0,255,255,0.8)); text-shadow: 0 0 10px rgba(255,255,255,0.9); transition: all 0.3s;" onmouseover="this.style.transform='rotate(360deg) scale(1.2)'; this.style.filter='drop-shadow(0 0 15px rgba(0,255,255,1)) brightness(1.5)'" onmouseout="this.style.transform='rotate(0deg) scale(1)'; this.style.filter='drop-shadow(0 0 8px rgba(0,255,255,0.8)) brightness(1)'"></span>
        <span style="transition: all 0.3s;" onmouseover="this.style.color='#e0ffff'; this.style.textShadow='0 0 20px rgba(0,255,255,0.8), 0 0 30px rgba(0,191,255,0.6)'" onmouseout="this.style.color='#ffffff'; this.style.textShadow='0 0 10px rgba(255,255,255,0.8), 0 0 20px rgba(0,255,255,0.6)'">AVERNUS</span>
      </div>
    </a>
  </div>

  <!-- Slide 3: Eidolon -->
  <div style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; animation: slideshow-3 9s infinite; opacity: 0; z-index: 0;">
    <img src="https://github.com/user-attachments/assets/9ff373a2-5184-4174-9ead-070ee55ad68c" alt="Eidolon" style="width: 100%; max-width: 750px; height: auto; border-radius: 10px;" />
    <a href="https://eidolon-flame.vercel.app/" style="position: absolute; bottom: 20px; right: 20px; text-decoration: none;">
      <div style="
        padding: 14px 28px;
        border-radius: 50px;
        background: linear-gradient(135deg, rgba(255,69,0,0.2) 0%, rgba(255,140,0,0.2) 50%, rgba(255,20,147,0.2) 100%);
        backdrop-filter: blur(25px);
        border: 1px solid rgba(255,69,0,0.4);
        box-shadow:
          0 0 20px rgba(255,69,0,0.3),
          0 0 40px rgba(255,140,0,0.2),
          inset 0 1px 0 rgba(255,255,255,0.1),
          inset 0 -1px 0 rgba(0,0,0,0.2);
        color: #ffffff;
        font-weight: 700;
        font-size: 15px;
        letter-spacing: 1px;
        text-shadow: 0 0 10px rgba(255,255,255,0.8), 0 0 20px rgba(255,69,0,0.6);
        display: flex;
        align-items: center;
        gap: 12px;
        transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
        position: relative;
        overflow: hidden;
        clip-path: polygon(0% 20%, 5% 0%, 95% 0%, 100% 20%, 100% 80%, 95% 100%, 5% 100%, 0% 80%);
      " onmouseover="this.style.transform='scale(1.1)'; this.style.boxShadow='0 0 30px rgba(255,69,0,0.6), 0 0 60px rgba(255,140,0,0.4), 0 0 90px rgba(255,20,147,0.3), inset 0 1px 0 rgba(255,255,255,0.2)'; this.querySelector('.border-glow').style.opacity='1'; this.querySelector('.shine').style.left='100%'; this.style.animation='pulse-red 2s infinite'" onmouseout="this.style.transform='scale(1)'; this.style.boxShadow='0 0 20px rgba(255,69,0,0.3), 0 0 40px rgba(255,140,0,0.2), inset 0 1px 0 rgba(255,255,255,0.1), inset 0 -1px 0 rgba(0,0,0,0.2)'; this.querySelector('.border-glow').style.opacity='0'; this.querySelector('.shine').style.left='-100%'; this.style.animation='none'">
        <div style="position: absolute; top: 0; left: -100%; width: 100%; height: 100%; background: linear-gradient(90deg, transparent, rgba(255,255,255,0.4), transparent); transition: left 0.8s;" onmouseover="this.parentElement.querySelector('.shine').style.left='100%'" class="shine"></div>
        <div style="position: absolute; top: -2px; left: -2px; right: -2px; bottom: -2px; background: linear-gradient(45deg, #ff4500, #ff8c00, #ff1493, #ff4500); border-radius: 50px; z-index: -1; opacity: 0; transition: opacity 0.4s;" onmouseover="this.parentElement.querySelector('.border-glow').style.opacity='1'" class="border-glow"></div>
        <span style="font-size: 19px; filter: drop-shadow(0 0 8px rgba(255,69,0,0.8)); text-shadow: 0 0 10px rgba(255,255,255,0.9); transition: all 0.3s;" onmouseover="this.style.transform='rotate(360deg) scale(1.2)'; this.style.filter='drop-shadow(0 0 15px rgba(255,69,0,1)) brightness(1.5)'" onmouseout="this.style.transform='rotate(0deg) scale(1)'; this.style.filter='drop-shadow(0 0 8px rgba(255,69,0,0.8)) brightness(1)'"></span>
        <span style="transition: all 0.3s;" onmouseover="this.style.color='#ffe0e0'; this.style.textShadow='0 0 20px rgba(255,69,0,0.8), 0 0 30px rgba(255,140,0,0.6)'" onmouseout="this.style.color='#ffffff'; this.style.textShadow='0 0 10px rgba(255,255,255,0.8), 0 0 20px rgba(255,69,0,0.6)'">EIDOLON</span>
      </div>
    </a>
  </div>

  <!-- Navigation Dots -->
  <div style="position: absolute; bottom: 10px; left: 50%; transform: translateX(-50%); display: flex; gap: 10px; z-index: 10;">
    <div style="width: 12px; height: 12px; border-radius: 50%; background: rgba(138,43,226,0.5); cursor: pointer; transition: all 0.3s;" onclick="this.parentElement.parentElement.children[0].style.animation='slideshow 0s infinite'; this.parentElement.parentElement.children[1].style.animation='slideshow-2 0s infinite'; this.parentElement.parentElement.children[2].style.animation='slideshow-3 0s infinite'; setTimeout(() => {this.parentElement.parentElement.children[0].style.animation='slideshow 9s infinite'; this.parentElement.parentElement.children[1].style.animation='slideshow-2 9s infinite'; this.parentElement.parentElement.children[2].style.animation='slideshow-3 9s infinite';}, 100); this.style.background='rgba(138,43,226,0.9)'; this.nextElementSibling.style.background='rgba(0,255,255,0.5)'; this.nextElementSibling.nextElementSibling.style.background='rgba(255,69,0,0.5)';"></div>
    <div style="width: 12px; height: 12px; border-radius: 50%; background: rgba(0,255,255,0.5); cursor: pointer; transition: all 0.3s;" onclick="this.parentElement.parentElement.children[0].style.animation='slideshow 0s infinite'; this.parentElement.parentElement.children[1].style.animation='slideshow-2 0s infinite'; this.parentElement.parentElement.children[2].style.animation='slideshow-3 0s infinite'; setTimeout(() => {this.parentElement.parentElement.children[0].style.animation='slideshow-2 9s infinite'; this.parentElement.parentElement.children[1].style.animation='slideshow 9s infinite'; this.parentElement.parentElement.children[2].style.animation='slideshow-3 9s infinite';}, 100); this.style.background='rgba(0,255,255,0.9)'; this.previousElementSibling.style.background='rgba(138,43,226,0.5)'; this.nextElementSibling.style.background='rgba(255,69,0,0.5)';"></div>
    <div style="width: 12px; height: 12px; border-radius: 50%; background: rgba(255,69,0,0.5); cursor: pointer; transition: all 0.3s;" onclick="this.parentElement.parentElement.children[0].style.animation='slideshow 0s infinite'; this.parentElement.parentElement.children[1].style.animation='slideshow-2 0s infinite'; this.parentElement.parentElement.children[2].style.animation='slideshow-3 0s infinite'; setTimeout(() => {this.parentElement.parentElement.children[0].style.animation='slideshow-3 9s infinite'; this.parentElement.parentElement.children[1].style.animation='slideshow-2 9s infinite'; this.parentElement.parentElement.children[2].style.animation='slideshow 9s infinite';}, 100); this.style.background='rgba(255,69,0,0.9)'; this.previousElementSibling.previousElementSibling.style.background='rgba(138,43,226,0.5)'; this.previousElementSibling.style.background='rgba(0,255,255,0.5)';"></div>
  </div>
</div>

<details>
  <summary>Expand</summary>
  <br>

![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-4169E1?style=flat&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-0099CC?style=flat&logoColor=white)

![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat&logo=keras&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=java&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=c-sharp&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)

![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat&logo=three.js&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)

![Amazon RDS](https://img.shields.io/badge/Amazon%20RDS-527FFF?style=flat&logo=amazonaws&logoColor=white)
![Azure SQL](https://img.shields.io/badge/Azure%20SQL-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)

![Nginx](https://img.shields.io/badge/Nginx-269539?style=flat&logo=nginx&logoColor=white)
![EC2](https://img.shields.io/badge/EC2-FF9900?style=flat&logo=amazonaws&logoColor=white)
![Amplify](https://img.shields.io/badge/Amplify-FF9900?style=flat&logo=aws-amplify&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat&logo=awslambda&logoColor=white)
![API Gateway](https://img.shields.io/badge/API%20Gateway-FF4F8B?style=flat&logo=apigateway&logoColor=white)
![Elastic Beanstalk](https://img.shields.io/badge/Elastic%20Beanstalk-232F3E?style=flat&logo=aws&logoColor=white)

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat&logo=dotnet&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20API-02569B?style=flat&logoColor=white)
![CORS](https://img.shields.io/badge/CORS-FE5000?style=flat&logoColor=white)


<div style="display: flex; justify-content: space-between; gap: 20px;">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=RidwanSharkar&theme=tokyonight" alt="Most Commit Language" style="width: 35%;" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=RidwanSharkar&theme=radical" alt="Repos Per Language" style="width: 35%;" />
</div>

</details>
