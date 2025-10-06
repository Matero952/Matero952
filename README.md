<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Skills Portfolio</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            padding: 60px;
            background-color: #ffffff;
        }
        
        h1 {
            font-size: 120px;
            font-weight: bold;
            margin-bottom: 80px;
            color: #000000;
        }
        
        h2 {
            font-size: 80px;
            font-weight: bold;
            margin-top: 60px;
            margin-bottom: 40px;
            color: #000000;
        }
        
        .skills-container {
            display: flex;
            gap: 120px;
            margin-bottom: 40px;
            align-items: flex-start;
        }
        
        .skill-item {
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
        }
        
        .skill-item img {
            width: 200px;
            height: 200px;
            object-fit: contain;
            margin-bottom: 30px;
        }
        
        .skill-item span {
            font-size: 70px;
            font-weight: bold;
            color: #000000;
        }
    </style>
</head>
<body>
    <h1>Skills</h1>
    
    <h2>Experienced in:</h2>
    <div class="skills-container">
        <div class="skill-item">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python">
            <span>Python</span>
        </div>
        <div class="skill-item">
            <img src="https://upload.wikimedia.org/wikipedia/commons/3/35/Tux.svg" alt="Linux">
            <span>Linux</span>
        </div>
        <div class="skill-item">
            <img src="https://us1.discourse-cdn.com/flex022/uploads/ros/original/2X/e/e2b80a2e45b12a397dbfebddb3abe92a1b4ce921.png" alt="ROS2">
            <span>ROS2 (Humble Hawksbill)</span>
        </div>
    </div>
    
    <h2>Familiar with:</h2>
    <div class="skills-container">
        <div class="skill-item">
            <img src="https://avatars.githubusercontent.com/u/157846462?s=200&v=4" alt="NVIDIA Isaac Sim">
            <span>NVIDIA Isaac Sim</span>
        </div>
        <div class="skill-item">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" alt="C++">
            <span>C++</span>
        </div>
        <div class="skill-item">
            <img src="https://www.svgrepo.com/show/373957/pddl.svg" alt="PDDL">
            <span>PDDL</span>
        </div>
        <div class="skill-item">
            <img src="https://www.pikpng.com/pngl/m/297-2979964_pytorch-first-step-pytorch-logo-png-clipart.png" alt="PyTorch">
            <span>PyTorch</span>
        </div>
    </div>
</body>
</html>
