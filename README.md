<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:007ACC,100:0F2027&height=220&section=header&text=Abdallah%20Zaitoun&fontSize=44&fontColor=ffffff&animation=fadeIn&textY=25" />
  <br/>
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&pause=1000&color=007ACC&center=true&vCenter=true&width=600&lines=Software+Engineer;Mobile+%26+Desktop+Application+Developer;Front-End+Developer+%7C+Robots" alt="Typing SVG" />
</p>

---

### ✨ About Me

I'm a software engineer specializing in designing high-performance, scalable mobile, desktop, and web applications, with responsive user interfaces that provide a smooth user experience.

---

### 🔗 Connect with me:
<p align="center">
  <a href="https://www.linkedin.com/in/abdallah-zaitoun-133754348?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app">
    <img src="https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  
  <a href="https://www.instagram.com/alghayib_3z22?igsh=ZWg1Ym8xazFxem52">
    <img src="https://img.shields.io/badge/-Instagram-e4405f?style=flat-square&logo=instagram&logoColor=white" alt="Instagram"/>
  </a>
  
  
  <a href="https://www.facebook.com/share/17Kjtj9WeZ/">
    <img src="https://img.shields.io/badge/-Facebook-1877F2?style=flat-square&logo=facebook&logoColor=white" alt="Facebook"/>
  </a>
  
  <a href="mailto:abdallahzaytoon42@gmail.com">
    <img src="https://img.shields.io/badge/-Gmail-d14836?style=flat-square&logo=gmail&logoColor=white" alt="Gmail"/>
  </a>
</p>

---


### ⚡ Skills:

<!-- Styles for the modal popup and icons wrapper -->
<style>
  /* الحاوية بتاعت الأيقونات في السنتر */
  .icons-wrapper {
    display: flex;
    justify-content: center; /* سنتر أفقي */
    align-items: center;    /* سنتر عمودي */
    gap: 15px;
    flex-wrap: wrap;
    padding: 20px;
  }

  /* كل أيقونة حجم ثابت والماوس يصبح مؤشر */
  .icons-wrapper img {
    width: 40px;
    height: 40px;
    border: 1px solid #ddd;
    padding: 5px;
    border-radius: 6px;
    cursor: pointer;
    object-fit: contain;
  }

  /* خلفية المودال */
  .modal {
    display: none; /* مخفية افتراضياً */
    position: fixed;
    z-index: 1000;
    padding-top: 60px;
    left: 0; top: 0;
    width: 100%; height: 100%;
    overflow: auto;
    background-color: rgba(0,0,0,0.7);
    text-align: center;
  }

  /* محتوى الصورة داخل المودال بحجم موحد */
  .modal-content {
    margin: auto;
    width: 200px;
    height: 200px;
    border-radius: 8px;
    object-fit: contain;
  }

  /* زر الإغلاق */
  .close {
    position: absolute;
    top: 30px;
    right: 30px;
    color: white;
    font-size: 35px;
    font-weight: bold;
    cursor: pointer;
  }
</style>

<!-- Skills Icons Wrapper -->
<div class="icons-wrapper">

  <!-- VS Code -->
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vscode/vscode-original.svg" alt="VS Code" onclick="openModal(this.src, this.alt)">

  <!-- Flutter -->
  <img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" alt="Flutter" onclick="openModal(this.src, this.alt)">

  <!-- Dart -->
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dart/dart-original.svg" alt="Dart" onclick="openModal(this.src, this.alt)">

  <!-- React Native -->
  <img src="https://reactnative.dev/img/header_logo.svg" alt="React Native" onclick="openModal(this.src, this.alt)">

  <!-- Android Studio -->
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/androidstudio/androidstudio-original.svg" alt="Android Studio" onclick="openModal(this.src, this.alt)">

  <!-- Git -->
  <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="Git" onclick="openModal(this.src, this.alt)">

  <!-- GitHub -->
  <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="GitHub" onclick="openModal(this.src, this.alt)">

  <!-- HTML5 -->
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML5" onclick="openModal(this.src, this.alt)">

  <!-- CSS3 -->
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS3" onclick="openModal(this.src, this.alt)">

  <!-- JavaScript -->
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" onclick="openModal(this.src, this.alt)">

  <!-- PHP -->
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="PHP" onclick="openModal(this.src, this.alt)">

  <!-- MySQL -->
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="MySQL" onclick="openModal(this.src, this.alt)">

  <!-- Java -->
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="Java" onclick="openModal(this.src, this.alt)">

  <!-- NetBeans -->
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/netbeans/netbeans-original.svg" alt="NetBeans" onclick="openModal(this.src, this.alt)">

  <!-- C -->
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="C" onclick="openModal(this.src, this.alt)">

  <!-- Python -->
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" onclick="openModal(this.src, this.alt)">

</div>

<!-- Modal Structure -->
<div id="myModal" class="modal" onclick="closeModal()">
  <span class="close" onclick="closeModal(event)">&times;</span>
  <img class="modal-content" id="modalImg" alt="">
  <div id="caption" style="color:white; text-align:center; margin-top:10px; font-size: 18px;"></div>
</div>

<script>
  function openModal(src, alt) {
    const modal = document.getElementById("myModal");
    const modalImg = document.getElementById("modalImg");
    const caption = document.getElementById("caption");

    modal.style.display = "block";
    modalImg.src = src;
    caption.innerText = alt;
  }

  function closeModal(event) {
    if(event) event.stopPropagation();
    document.getElementById("myModal").style.display = "none";
  }
</script>

---

### 📈 GitHub Stats:
<p align="center">
<img src="https://github-readme-stats.vercel.app/api?username=abdallah3z22&show_icons=true&theme=tokyonight&hide_border=true&hide_title=true" height="250px" width="200px" />
  
  <!-- Most Used Languages - bar chart -->
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=abdallah3z22&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" height="70px" />
 
  <p align="center">
  <img src="https://github-readme-streak-stats-eight.vercel.app/?user=abdallah3z22&theme=tokyonight&hide_border=true" height="130px" />
</p>

<!-- <p align="center">
  <img src="https://komarev.com/ghpvc/?username=abdallah3z22&label=Profile%20views&color=0e75b6&style=flat" alt="abdallah3z22" />
</p>

 -->
