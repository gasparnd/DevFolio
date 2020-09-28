<h1 align="center"> DevFolio🌟</h1>
<p align ="center"><a href = "https://github.com/achaljhawar/DevFolio/graphs/contributors"><a href="https://github.com/achaljhawar/DevFolio/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/achaljhawar/DevFolio"></a><a href="https://twitter.com/intent/tweet?text=Wow:&url=https%3A%2F%2Fgithub.com%2Fachaljhawar%2FDevFolio"><img alt="Twitter" src="https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Ftwitter.com%2F"></a><a href="https://github.com/achaljhawar/DevFolio/network"><img alt="GitHub forks" src="https://img.shields.io/github/forks/achaljhawar/DevFolio"></a><img src="https://img.shields.io/badge/awesomeness-extreme-green"><a href = "https://discord.gg/YRm6nn8"><img alt="Discord" src="https://img.shields.io/discord/758269170151587852"></a><a href = "https://github.com/achaljhawar/DevFolio/blob/master/LICENSE"><img alt="GitHub" src="https://img.shields.io/github/license/achaljhawar/DevFolio?style=flat-square"></a><a href="https://achaljhawar.github.io/DevFolio/"><img alt="Website" src="https://img.shields.io/website?url=https%3A%2F%2Fachaljhawar.github.io%2FDevFolio%2F"></a><br><a href="https://github.com/achaljhawar?tab=followers"><img alt="GitHub followers" src="https://img.shields.io/github/followers/achaljhawar?style=social"></a></p>
<br />

##  A minimal portfolio template for Developers!
## Built in:

- **HTML5**
- Pure **CSS3**
- Bit of **JavaScript**

## Features

⚡️ Modern UI Design + Reveal Animations\
⚡️ One Page Layout\
⚡️ Fully Responsive\
⚡️ Valid HTML5 & CSS3\
⚡️ Well organized documentation


You can add more things to make it even cooler! The comments in the code will help you navigate through it. Have a nice day! :D
[Demo Example](https://achaljhawar.github.io/DevFolio/)

## Sections

✔️ About me and summary\
✔️ Contact Info\
✔️ Projects

## Getting Started 🚀

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

## How To Use 🔧

From your command line, first clone DevFolio:

```bash
# Clone this repository
$ git clone https://github.com/achaljhawar/DevFolio

# Go into the repository
$ cd DevFolio

# Remove current origin repository
$ git remote remove origin
```

## Template Instructions:

Go to `/index.html` and fill your information, there are 3 sections:

### Home Section

- Add your Name and a short description about yourself
- Add your social media links

```html
<div id="home">
  <div class="filter"></div>
  <section class="intro">
    <h3>
      Your Name
      <hr />
    </h3>
    <p>Short Description.</p>
    <p>Something more about yourself.</p>
    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
    <!--────social media links─────-->
    <div class="social-media">
      <a href="#" target="_blank"><i class="fab fa-codepen"></i></a>
      <a href="#" target="_blank"><i class="fab fa-twitter"></i></a>
      <a href="#" target="_blank"><i class="fab fa-github"></i></a>
      <a href="#" target="_blank"><i class="fab fa-linkedin-in"></i></a>
      <a href="#" target="_blank"><i class="fab fa-youtube"></i></a>
    </div>
  </section>
</div>
```

### Projects Section

- Add your short description ,the image of your projects and their links you can change the number of projects. You have two cards types, whit image and whitout image. Remember that cards aren't just for projects, you can use for work experiences, blogpost or whatever.

```html
<div id="projects">
             <h2>
               My Projects
               <hr />
             </h2>
             <p>Here are some of my projects, you may like.</p>
             <div class="work-box">
               <div class="work">
    <!--───────────────card───────────────-->
            <div class="card">
                <figure>
                  <img class="work-img" src="https://images.unsplash.com/photo-1462642109801-4ac2971a3a51?ixlib=rb-1.2.1&auto=format&fit=crop&w=1266&q=80">
                </figure>
                <div class="work-content">
                  <h3 class="work-title">Project Title</h3>
                  <p class="work-description">Project description. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
                  tempor incididunt ut labore et dolore magna aliqua.
                  </p>
                  <a class="work-link" href="#" target="_blank"><i class='fab fa-github'></i></a>
                </div>
                  </div>
            <div class="card">
              <figure>
                  <img class="work-img" src="https://images.unsplash.com/photo-1462642109801-4ac2971a3a51?ixlib=rb-1.2.1&auto=format&fit=crop&w=1266&q=80">
                </figure>
                <div class="work-content">
                  <h3 class="work-title">Project Title</h3>
                  <p class="work-description">Project description. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
                  tempor incididunt ut labore et dolore magna aliqua.
                  </p>
                  <a class="work-link" href="#" target="_blank"><i class='fab fa-github'></i></a>
                </div>
                  </div>
                  <div class="card">
              <figure>
                  <img class="work-img" src="https://images.unsplash.com/photo-1462642109801-4ac2971a3a51?ixlib=rb-1.2.1&auto=format&fit=crop&w=1266&q=80">
                </figure>
                <div class="work-content">
                  <h3 class="work-title">Project Title</h3>
                  <p class="work-description">Project description. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
                  tempor incididunt ut labore et dolore magna aliqua.
                  </p>
                  <a class="work-link" href="#" target="_blank"><i class='fab fa-github'></i></a>
                </div>
                  </div>

            <!-- Simple Card for projects, work experiences or whatever -->

                  <div class="simple-card">
                <h3 class="work-title">Project Title</h3>
                <p class="work-description">Project description. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
                tempor incididunt ut labore et dolore magna aliqua.
                </p>
                <a class="work-link" href="#" target="_blank"><i class='fab fa-github'></i></a>
                  </div>    
                  <div class="simple-card">
                <h3 class="work-title">Project Title</h3>
                <p class="work-description">Project description. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
                tempor incididunt ut labore et dolore magna aliqua.
                </p>
                <a class="work-link" href="#" target="_blank"><i class='fab fa-github'></i></a>
                  </div>    
                  <div class="simple-card">
                <h3 class="work-title">Project Title</h3>
                <p class="work-description">Project description. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
                tempor incididunt ut labore et dolore magna aliqua.
                </p>
                <a class="work-link" href="#" target="_blank"><i class='fab fa-github'></i></a>
                  </div>    
                  <div class="simple-card">
                <h3 class="work-title">Project Title</h3>
                <p class="work-description">Project description. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
                tempor incididunt ut labore et dolore magna aliqua.
                </p>
                <a class="work-link" href="#" target="_blank"><i class='fab fa-github'></i></a>
                  </div>    
            </div>
          </div>
        </div>
```

### Contact Section

- Add your social media links

```html
<div id="contact">
  <!--────social media links─────-->
  <h3>
    Contact.
    <hr />
  </h3>
  <p>Feel free to contact me on my social media.</p>
  <div class="social-media">
    <a href="#" target="_blank"><i class="fab fa-codepen"></i></a>
    <a href="#" target="_blank"><i class="fab fa-twitter"></i></a>
    <a href="#" target="_blank"><i class="fab fa-github"></i></a>
    <a href="#" target="_blank"><i class="fab fa-linkedin-in"></i></a>
    <a href="#" target="_blank"><i class="fab fa-youtube"></i></a>
  </div>
</div>
```

## Deployment 📦

Once you have done with your setup. You need to put your website online!

I highly recommend to use [Github Pages](https://pages.github.com/) to achieve this on the EASIEST WAY.

## Authors

<table>
  <tr>
    <td align="center"><a href="https://github.com/achaljhawar"><img src="https://avatars2.githubusercontent.com/u/35405812?s=460&u=0cf54a210cd79440ebf51fdc7423b65877c87016&v=4" width="100px;" alt=""/><br /><sub><b>Achal Jhawar</b></sub></a><br /></td>
     <td align="center"><a href="https://github.com/Lilykhan786"><img src="https://avatars1.githubusercontent.com/u/47777673?s=460&u=b5531e40e1b9a31078e024f861116678fecaa826&v=4" width="100px;" alt=""/><br /><sub><b>Lilykhan
</b></sub></a><br /></td>
  </tr>
</table>

## License 📄 <a href = "https://github.com/achaljhawar/DevFolio/blob/master/LICENSE"><img alt="GitHub" src="https://img.shields.io/github/license/achaljhawar/DevFolio?style=flat-square"></a>

This project is licensed under the Apache-2.0 License - see the [LICENSE](LICENSE) file for details

## 🤝 Contributing <a href = "https://discord.gg/YRm6nn8"><img alt="Discord" src="https://img.shields.io/discord/758269170151587852"></a>

Any idea on how we can make this more awesome ? [Open a new issue](https://github.com/achaljhawar/DevFolio/issues)! We need all the help we can get to make this project awesome! You can also join the discord server to give suggestions.

## Contributors ✨

<table>
  <tr>
    <td align="center"><a href="https://github.com/shadowtime2000"><img src="https://avatars1.githubusercontent.com/u/66655515?s=180&v=4" width="100px;" alt=""/><br /><sub><b>Shadowtime2000</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/gasparnd"><img src="https://avatars3.githubusercontent.com/u/36377522?s=180&u=3b1f554c19b5dc2e21bf0aef269f44ee5bf87fdf&v=4" width="100px;" alt=""/><br /><sub><b>Gaspar Dolcemascolo</b></sub></a><br /></td>
  </tr>
</table>

### Don't forget to ⭐ and 🍴 the repository and share it with others.

## Stargazers ✨

Thanks goes to these wonderful people.

<table>
  <tr>
    <td align="center"><a href="https://github.com/SeraphicWolf"><img src="https://avatars1.githubusercontent.com/u/29392808?s=180&u=6bbb90ea2fa3549f6e63e266550084fd6b20fcff&v=4" width="100px;" alt=""/><br /><sub><b>Sebastian</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/GARVRC2005"><img src="https://avatars3.githubusercontent.com/u/71485440?s=180&u=bafc5164ca52a3632f7c7901f3e18b74bfa1331e&v=4" width="100px;" alt=""/><br /><sub><b>Garv Roy Choudhary</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/ahhhfiq"><img src="https://avatars1.githubusercontent.com/u/15061663?s=180&v=4" width="100px;" alt=""/><br /><sub><b>ahhhfiq</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/shadowtime2000"><img src="https://avatars1.githubusercontent.com/u/66655515?s=180&v=4" width="100px;" alt=""/><br /><sub><b>Shadowtime2000</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/devded"><img src="https://avatars1.githubusercontent.com/u/60034035?s=180&u=affce39ad96481fd4d85c2fe9262e4400c1c5213&v=4" width="100px;" alt=""/><br /><sub><b>Dedar Alam</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/GJG"><img src="https://avatars1.githubusercontent.com/u/5757822?s=180&u=f6c0e00bded4fdab56ca8f14c165926d73f8eb08&v=4" width="100px;" alt=""/><br /><sub><b>Guðmundur Jón Guðjónsson</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/kdvalin"><img src="https://avatars1.githubusercontent.com/u/10466117?s=180&u=eae56f3a03e56ab7563f26e3272ab4f4090a37aa&v=4" width="100px;" alt=""/><br /><sub><b>keith</b></sub></a><br /></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/gasparnd"><img src="https://avatars3.githubusercontent.com/u/36377522?s=180&u=3b1f554c19b5dc2e21bf0aef269f44ee5bf87fdf&v=4" width="100px;" alt=""/><br /><sub><b>Gaspar Dolcemascolo</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/RegNex"><img src="https://avatars0.githubusercontent.com/u/19475061?s=180&u=63f8052e36fcb90e66e834c91327e6def4096230&v=4" width="100px;" alt=""/><br /><sub><b>Etornam Sunu</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/goxr3plus"><img src="https://avatars2.githubusercontent.com/u/20374208?s=180&u=912d063bbe2eb74d43447542957f5c2b9e8315bc&v=4" width="100px;" alt=""/><br /><sub><b>Alexander Kentros</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/ChristofBecu"><img src="https://avatars3.githubusercontent.com/u/16795074?s=180&u=263662c6399195b74fcb162272ca1e82affe108a&v=4" width="100px;" alt=""/><br /><sub><b>Christof Becu</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/AObuchow"><img src="https://avatars3.githubusercontent.com/u/10300119?s=180&u=ebb1e6154b6514b4000d273e479b5659ea3c7c72&v=4" width="100px;" alt=""/><br /><sub><b>Andrew O.
</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/JLohani"><img src="https://avatars3.githubusercontent.com/u/32483331?s=180&u=4cd11b263dfa96b7ee297ac00a6d59fabe034aa6&v=4" width="100px;" alt=""/><br /><sub><b>Jayant Lohani</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/seegrand"><img src="https://avatars0.githubusercontent.com/u/12057066?s=180&u=38f38f2317f22e98a90e448d0685b0695b8c42d0&v=4" width="100px;" alt=""/><br /><sub><b>Sander Grandia
</b></sub></a><br /></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/ukoms"><img src="https://avatars1.githubusercontent.com/u/777001?s=180&u=e2c960585fffab6d2140ade6159bde89859b46ed&v=4" width="100px;" alt=""/><br /><sub><b>Michał Kupczyński</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/zafaralam"><img src="https://avatars3.githubusercontent.com/u/1768203?s=180&v=4" width="100px;" alt=""/><br /><sub><b>Zafar Alam</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/jameshood118"><img src="https://avatars3.githubusercontent.com/u/18595004?s=180&u=0785571c38ee0c7966c4eb8197778c1b285b4098&v=4" width="100px;" alt=""/><br /><sub><b>James Hood </b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/120296Soumyaju"><img src="https://avatars2.githubusercontent.com/u/48637511?s=180&u=0191b32d231903f08918e1e5690b903331a898e8&v=4" width="100px;" alt=""/><br /><sub><b>Sujit Tadadikar </b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/Amarildoo"><img src="https://avatars0.githubusercontent.com/u/34867366?s=180&u=570814e30f05367f41f38cafc0a55b062e32423b&v=4" width="100px;" alt=""/><br /><sub><b>Amarildo Gjeçaj</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/shouryade"><img src="https://avatars0.githubusercontent.com/u/67991164?s=180&u=58b3040104aa4444c3c68e9891407b7c22e54b94&v=4" width="100px;" alt=""/><br /><sub><b>Shourya (AlphaQ)</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/Jean-carje"><img src="https://avatars0.githubusercontent.com/u/66575135?s=460&v=4" width="100px;" alt=""/><br /><sub><b>Jean Estevez</b></sub></a><br /></td>    
  </tr> 
  <tr>
    <td align="center"><a href="https://github.com/oppongjr"><img src="https://avatars0.githubusercontent.com/u/19373355?s=460&u=be810f39bb8064e416cf366df081a9a054de70b5&v=4" width="100px;" alt=""/><br /><sub><b>Isaac Akwasi Oppong Jnr</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/1realib"><img src="https://avatars2.githubusercontent.com/u/69173806?s=460&u=529b5cc3f355c0ced85f4c86b8873f1c128d4d7f&v=4" width="100px;" alt=""/><br /><sub><b>Ibrahim</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/kapoordev"><img src="https://avatars3.githubusercontent.com/u/59065079?s=180&v=4" width="100px;" alt=""/><br /><sub><b>Kapoor Dev</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/Esther-Goldberg"><img src="https://avatars0.githubusercontent.com/u/30660571?s=180&u=a4c0a316f880336c1ac0538551745a81751cb7b6&v=4" width="100px;" alt=""/><br /><sub><b>Esther Goldberg</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/reveurguy"><img src="https://avatars1.githubusercontent.com/u/59417546?s=180&u=526fd0b4ef3afa4ceafce6d4d68f7ecc828a2d83&v=4" width="100px;" alt=""/><br /><sub><b>Priyanshu Singh</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/dan-hill2802"><img src="https://avatars2.githubusercontent.com/u/5046322?s=180&v=4" width="100px;" alt=""/><br /><sub><b>Daniel Hill</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/harshhh-dev"><img src="https://avatars0.githubusercontent.com/u/69592270?s=180&u=3ca052746440e16cb632790baea80a06a4d7c804&v=4" width="100px;" alt=""/><br /><sub><b>Harsh Singh</b></sub></a><br /></td>
    <tr>
      <td align="center"><a href="https://github.com/Y-KUN-21"><img src="https://avatars0.githubusercontent.com/u/57254049?s=180&u=d9feb4ab2eefe1e998f8bed122488cb9d5bafa12&v=4" width="100px;" alt=""/><br /><sub><b>Y-Kun 21</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/simarpreetsingh-019"><img src="https://avatars3.githubusercontent.com/u/47384034?s=180&u=c54992d422e29fb9792b7bec170540840ee3b074&v=4" width="100px;" alt=""/><br /><sub><b>Simarpreet Singh</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/oadpoaw"><img src="https://avatars0.githubusercontent.com/u/46276781?s=180&u=a6ff04a2b8a2cbf356445cab956533f551b70b45&v=4" width="100px;" alt=""/><br /><sub><b>undefine</b></sub></a><br /></td>
      <td align="center"><a href="https://github.com/blacksmithop"><img src="https://avatars0.githubusercontent.com/u/60320192?s=180&u=04c9944f2c042b49c3fd36460d60093717d307a3&v=4" width="100px;" alt=""/><br /><sub><b>ambu</b></sub></a><br /></td>
</table>

## References 👏🏻
- Some Design and Implementation Ideas are taken from <a href="https://repl.it/talk/templates/Portfolio-Site-Template/37272">Lilykhan's Portfolio Site Template</a> made for repl.it template jam.
