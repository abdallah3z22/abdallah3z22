# Abdallah Zeitoun 🚀

<div align="center">
  
  [![Open Your Interactive Portfolio](https://img.shields.io/badge/CLICK_ME-Open_Interactive_Portfolio-00ffe0?style=for-the-badge&logo=github)](https://abdallah-zaitoun.github.io)
  
  ![Preview](https://user-images.githubusercontent.com/your-image-id/portfolio-preview.gif)
  
</div>

## 🛠️ Technical Implementation

### ✨ HTML/CSS/JS Code Snippet
```html
<!DOCTYPE html>
<html>
<head>
  <style>
    body { background: #0f0f0f; color: #00ffe0; }
    .name-box {
      width: 150px;
      height: 150px;
      border: 3px solid #00ffe0;
      animation: glow 2s infinite alternate;
    }
    @keyframes glow {
      from { box-shadow: 0 0 5px #00ffe0; }
      to { box-shadow: 0 0 20px #00ffe0; }
    }
  </style>
</head>
<body>
  <div class="name-box">A.Z</div>
  <script>
    setTimeout(() => {
      document.querySelector('.name-box').textContent = 'Abdallah Zeitoun';
    }, 1000);
  </script>
</body>
</html>
