<!-- ![Javascript wallpaper by wallpaper access](https://raw.githubusercontent.com/ananduremanan/Demo/demo_files/4635758.jpg) -->

- 👋 Hi, I’m @ananduremanan
- 😑 Working as a Junior Software Developer 
- 👀 I’m interested in Machine Learning, Computer Vision, Full Stack And BlockChain.
- 📫 How to reach me : check my [website](https://imanandhuremanan.vercel.app/)
- 💰 Coding pays my bills.
<!-- - 👨‍💻 LeetCode : https://leetcode.com/Anandhu_Remanan/ -->

<!-- <a href="https://www.buymeacoffee.com/anandhuremanan" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a> -->

<div style="display: flex;  justify-content: center">
<!--   <img src="https://github-readme-stats.vercel.app/api?username=ananduremanan&bg_color=0D1117&title_color=ffffff&text_color=ffffff" alt="GitHub Stats" /> -->
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ananduremanan&hide_progress=true&bg_color=24292f&title_color=ffffff&text_color=ffffff" alt="Top Languages" />
</div>

<div style="display: flex; justify-content: center">
  <img id="github-stats-image" src="" alt="GitHub Stats" />
</div>

<script>
  // Function to get cookie value by name
  function getCookie(name) {
    const value = `; ${document.cookie}`;
    const parts = value.split(`; ${name}=`);
    if (parts.length === 2) return parts.pop().split(';').shift();
  }

  // Get the preferred_color_mode cookie value
  const preferredColorMode = getCookie('preferred_color_mode');

  // Set the default colors
  let bgColor = '24292f';
  let titleColor = 'ffffff';
  let textColor = 'ffffff';

  // Change colors based on the preferred_color_mode cookie value
  if (preferredColorMode === 'dark') {
    bgColor = '0D1117';
  }

  // Set the image source with the updated colors
  const githubStatsImage = document.getElementById('github-stats-image');
  githubStatsImage.src = `https://github-readme-stats.vercel.app/api/top-langs/?username=ananduremanan&hide_progress=true&bg_color=${bgColor}&title_color=${titleColor}&text_color=${textColor}`;
</script>

<!---
ananduremanan/ananduremanan is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
