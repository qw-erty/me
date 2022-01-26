# Code Along

> ## Step 1

>> #### HTML

```
    <div class="topnav">
        <a href="#head">Home</a>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#skills">Skills</a>
        <a href="#contact">Contact</a>
    </div>

```
>> #### CSS 

```
.topnav {
  position: fixed;
  font-size: 25px;
  width: 100%;
  background-color: black;
  padding: 20px;
  z-index: 999;
}

.topnav a {
  text-align: center;
  text-decoration: none;
  color: white;
  height: 100%;
  padding: 20px;
}

.topnav a:hover {
  background-color: #e8f3ff;
  color: black;
}

```

> ## Step 2
>> #### HTML

```
    <div class="head" id="head">
        <img src="https://media4.giphy.com/media/QaXUHsIyl0j34k0yNm/giphy.gif?cid=790b7611fd96d196a498871470db57eb41041c666c2883e8&rid=giphy.gif&ct=g" alt="avatar">
        <div class="info">
            <h1>Abhinav Aggrawal</h1>
            <p>Full-Stack Web Developer! </p>
        </div> 
    </div>
```
>> #### CSS 

```
.head {
  padding: 100px;
  text-align: center;
  background-image: url("./background.png");
}

.head img {
  height: 350px;
  width: 350px;
  border-radius: 50%;
}

.head h1 {
  font-size: 64px;
  font-weight: 700;
  text-align: center;
}

.head p {
  font-size: 24px;
  font-weight: 700;
  text-align: center;
}

```

> ## Step 3
>> #### HTML

```
    <div class="about" id="about">
        <h2>About Me</h2>
        <p>
            I am currently mentor for Web Development at IEEE DTU. I am professionally a full stack developer and
            mastred various skills requied for Development. I have completed my internship as a web developer at Feetwings and Seutus .
            I like to play almost all the games but have chess and football as my favourite.
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et
            dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex
            ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat
            nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit
            anim id est laborum.

        </p>
    </div>

```
>> #### CSS 

```

.about {
  background-color: white;
  color: black;
  text-align: center;
  padding: 50px;
}

.about h2 {
  font-size: 40px;
  font-weight: 500;
}

.about p {
  padding: 30px;
  font-weight: 200;
}

```

> ## Step 4
>> #### HTML

```
    <div class="projects" id="projects">
        <h1>My Projects</h1>
        <div class="flex-container">
            <div>
                <h3>The Blog Website</h3>
                <p>
                    This is a complete website which is capable to creating
                    a system that handles both the writes and the readers.
                </p>
                <button>Learn More</button>
            </div>
            <div>
                <h3>Mindy</h3>
                <p>
                    This is a website which aims to help people suffering from any kind of mental
                    health issues . It has features like mind games and mood tracker and is highly
                    optimised according to age
                </p>
                <button>Learn More</button>
            </div>
            <div>
                <h3>Donately</h3>
                <p>
                    This is a website which aims to help people which find difficulties while finding
                    a blood or a organ donar . It creates a portal where the blood or organ donars can find each other.
                </p>
                <button>Learn More</button>
            </div>
        </div>
    </div>
```

>> #### CSS 

```

.projects {
  text-align: center;
  padding: 50px;
  padding-top: 0;
}

.projects h1 {
  font-size: 50px;
  margin-top: 0;
  margin-bottom: 30px;
}

.projects p {
  font-size: 20px;
  padding: 0 20px;
}

.flex-container {
  display: flex;
  justify-content: center;
}

.flex-container > div {
  border-radius: 20px;
  width: 350px;
  background-color: rgb(128, 186, 240);
  margin: 10px;
  font-size: 30px;
  padding: 30px;
}

.flex-container > div h3 {
  margin: 0;
}

.flex-container div button {
  height: 40px;
  width: 150px;
  font-size: 20px;
  background: black;
  color: white;
  border: 0;
  font-family: "Outfit", sans-serif;
  border-radius: 5px;
}
```

> ## Step 5
>> #### HTML

```
    <div class="skills" id="skills">
        <h1>My Skills</h1>
        <div class="skills-container">
            <ul>
            <li>
                <p>HTML</p>
            </li>
            <li>
                <p>CSS</p>
            </li>
            <li>
                <p>JavaScript</p>
            </li>
            <li>
                <p>React JS</p>
            </li>
            <li>
                <p>Node JS</p>
            </li>
            <li>
                <p>Express JS</p>
            </li>
            <li>
                <p>MongoDB</p>
            </li>
        </ul>
        </div>
    </div>

```
>> #### CSS 

```
.skills {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 50px;
  background-color: white;
  color: black;
}

.skills h1 {
  font-size: 50px;
  margin-top: 0;
  margin-bottom: 30px;
}

.skills ul {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
  list-style: none;
}

.skills ul li {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 200px;
  width: 200px;
  border: 5px solid rgb(24, 120, 211);
  border-radius: 50%;
  margin: 20px;
  transition: all ease 0.5s;
  color: rgb(24, 120, 211);
}

.skills ul li p {
  font-size: 30px;
  padding: 0 20px;
}

.skills ul li:hover {
  transform: scale(1.1);
  /* transform: rotate(360deg); */
}
```

> ## Step 6
>> #### HTML

```
    <div class="contact" id="contact">
        <h1>Contact Me</h1>
        <ul id="explode" class="profiles">
            <li><a href="https://github.com/qw-erty">
                <img class="pic" src="https://cdn-icons-png.flaticon.com/512/1384/1384063.png" alt="" srcset=""></a>
            </li>
            <li><a href="https://www.linkedin.com/in/abhinav-aggrawal-aa97b6201/">
                    <img class="pic" src="https://cdn-icons-png.flaticon.com/512/124/124011.png" alt=""
                        srcset=""></a>
            </li>
            <li><a href="https://github.com/qw-erty">
                    <img class="pic" src="https://cdn-icons-png.flaticon.com/512/270/270798.png" alt=""
                        srcset="">
            </li></a>
            <li>
                <a href="https://github.com/qw-erty">
                <img class="pic" src="https://cdn-icons-png.flaticon.com/512/145/145802.png" alt="" srcset=""></a>
            </li>
        </ul>
    </div>

```

>> #### CSS 

```
.contact {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 50px;
  color: black;
  padding-bottom: 80px;
  background: linear-gradient(rgb(255, 255, 255), rgb(128, 186, 240));
}

.contact h1 {
  font-size: 50px;
  margin-top: 0;
  margin-bottom: 30px;
}

.contact ul {
  display: flex;
  list-style: none;
}

.contact ul li {
  margin: 20px;
  transition: all 0.7s ease;
}

.contact img {
  width: 50px;
  height: 50px;
}

.contact ul li:hover {
  transform: rotate(360deg);
}

```