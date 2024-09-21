
## 🌐 Socials:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/https://www.linkedin.com/in/saurabh-tiwari-a3296b227/) 

## 💻 Tech Stack
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white) ![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white) ![jQuery](https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white) ![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white) ![Apache Maven](https://img.shields.io/badge/Apache%20Maven-C71A36?style=for-the-badge&logo=Apache%20Maven&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-%2300000f.svg?style=for-the-badge&logo=mysql&logoColor=white) ![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white) ![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Ansible](https://img.shields.io/badge/ansible-%231A1918.svg?style=for-the-badge&logo=ansible&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

## 📊 GitHub Stats
![](https://github-readme-stats.vercel.app/api?username=SAURABHTIWARIVBSPU&theme=dark&hide_border=false&include_all_commits=true&count_private=true)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=SAURABHTIWARIVBSPU&theme=dark&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=SAURABHTIWARIVBSPU&theme=dark&hide_border=false&include_all_commits=true&count_private=true&layout=compact

## 🚀 Getting Started
[Setup Instructions]

## 📖 Features
[Feature List]

### 🔝 Top Contributed Repo
![](https://github-contributor-stats.vercel.app/api?username=SAURABHTIWARIVBSPU&limit=5&theme=dark&combine_all_yearly_contributions=true)

## 💡 Contributing
[Contribution Guidelines]

## 📄 License
[License Information]
<style>
  @keyframes fadeIn {
    from { opacity: 0; }
    to { opacity: 1; }
  }

  h1 {
    animation: fadeIn 1.5s ease-in-out;
  }
</style>

<h1>🌟 Three.js Theme</h1>
<style>
  .button {
    padding: 10px 20px;
    background-color: #4d9e6c;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: transform 0.2s;
  }

  .button:hover {
    transform: translateY(-5px);
  }
</style>

<button class="button">Get Started</button>
<div id="threejs-scene" style="width: 100%; height: 400px;"></div>

<script>
  // Basic Three.js setup (Add this to your main JavaScript file, not README)
  const scene = new THREE.Scene();
  const camera = new THREE.PerspectiveCamera(75, window.innerWidth / window.innerHeight, 0.1, 1000);
  const renderer = new THREE.WebGLRenderer();

  renderer.setSize(window.innerWidth, window.innerHeight);
  document.getElementById('threejs-scene').appendChild(renderer.domElement);

  const geometry = new THREE.BoxGeometry();
  const material = new THREE.MeshBasicMaterial({ color: 0x00ff00 });
  const cube = new THREE.Mesh(geometry, material);
  scene.add(cube);

  camera.position.z = 5;

  function animate() {
    requestAnimationFrame(animate);
    cube.rotation.x += 0.01;
    cube.rotation.y += 0.01;
    renderer.render(scene, camera);
  }
  animate();
</script>
<style>
  .fadeIn {
    opacity: 0;
    animation: fadeIn 1.5s forwards;
  }

  .fadeIn:nth-child(n) {
    animation-delay: calc(0.5s * var(--i));
  }
</style>

<div class="fadeIn" style="--i: 1;">![](https://github-readme-stats.vercel.app/api?username=SAURABHTIWARIVBSPU&theme=dark&hide_border=false&include_all_commits=true&count_private=true)</div>
<div class="fadeIn" style="--i: 2;">![](https://github-readme-stats.vercel.app/api?username=SAURABHTIWARIVBSPU&theme=dark&hide_border=false&include_all_commits=true&count_private=true&layout=compact)</div>
