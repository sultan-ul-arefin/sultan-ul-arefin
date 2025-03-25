<div align="right">
<a style="text-decoration: none" target="_blank"href="https://github.com/sultan-ul-arefin">
<img src="https://visitor-badge.laobi.icu/badge?page_id=sultan-ul-arefin.sultan-ul-arefin&left_color=gray&right_color=blue&left_text=Coders%20visitors">
</a>
</div>
<br>
<img src="https://readme-typing-svg.herokuapp.com/?font=Roboto&weight=900&size=40=true&vCenter=true&width=500&height=70&duration=4000&color=B3B3B3&lines=Hi+There!+👋;+I'm+Sultanul+Arefin!;" />

```typescript

/**
 * @Profile
 * Github Profile of Md Sultanul Arefin.
 * Expertise in Modern Software Engineering.
 */
@sealed
class SultanulArefinProfile {
    /**
     * @Contact
     * I'm now available to develop cutting-edge artificial intelligence software.
     */
    @enumerable(true)
    public contact: ContactInfo = {
        name: "Md Sultanul Arefin",
        title: "Software Engineer",
        website: "sultanularefin.com",
        linkedin: "linkedin.com/in/sultan-ul-arefin",
        github: "github.com/sultan-ul-arefin",
        email: "hello@sultanularefin.com",
        phone: "+8801780324264"
    };

    /**
     * @Summary
     * A brief introduction.
     */
    @enumerable(true)
    public summary: string = `I have more than five years of experience in design, architecture, development, and deployment in software development. I always focus on building user-friendly and high-performance web applications to increase user satisfaction. I always try to follow best practices and write clean code every time, making development faster and easier to maintain. I enjoy team energy, helping to speed up project completion and improve team productivity while ensuring every solution is creative and effective.`;

    /**
     * @ProfessionalExperience
     * Details the professional history and responsibilities.
     */
    @enumerable(true)
    public professionalExperience: Experience[] = [
        {
            company: "INFOBAHN REALM",
            title: "Software Engineer",
            years: "2019 - Present",
            responsibilities: [
                "Created awesome user experience (UX) on front end.",
                "Developed efficient server side technology.",
                "Worked on three major projects like Social Media app, Real time online examination system as fullstack engineer, mostly using (MEAN) stack with socket.io for real time data transmission.",
                "Contributed to five minor projects.",
                "Experienced with server technology like setup STURN and TURN and MongoDB server.",
                "Managed CI/CD deployment process with Linux based system.",
            ],
            keywords: [
                "Typescript",
                "Nodejs",
                "Angular 10",
                "Nosql",
                "Database Design",
                "AWS Server",
                "Realtime System",
            ],
        },
    ];

    /**
 * @Skills
 * Represents a categorized list of technical proficiencies.
 */
    @enumerable(true)
    public skills: Skills = {
        programming: [
            "Typescript",
            "Javascript",
            "Java",
            "Python",
            "Dart",
            ".Net (C#)",
            "SCSS",
        ],
        frameworks: [
            "NestJs",
            "Expressjs",
            "Angular 10",
            "Ionic",
            "Flutter",
            "Native Android",
            "Flask",
            "Django",
        ],
        databases: ["MongoDB", "PostgreSQL", "MySQL", "Microsoft SQL Server"],
        developmentTools: ["Visual Studio Code", "IntelliJ Idea"],
        versionControl: ["Git", "Github"],
        operatingSystems: [
            "Mac OS X",
            "Windows 10",
            "Linux Ubuntu",
            "Linux Centos",
        ],
    };
}

/**
 * @interface ContactInfo
 * Defines the structure for contact details.
 */
interface ContactInfo {
    name: string;
    title: string;
    website?: string;
    linkedin?: string;
    github?: string;
    email: string;
    phone: string;
}

/**
 * @interface Experience
 * Defines the structure for professional experience entries.
 */
interface Experience {
    company: string;
    title: string;
    years: string;
    responsibilities: string[];
    keywords?: string[];
}

/**
 * @interface Skills
 * Defines the structure for categorized skills.
 */
interface Skills {
    programming: string[];
    frameworks: string[];
    databases: string[];
    developmentTools: string[];
    versionControl: string[];
    operatingSystems: string[];
}

/**
 * @decorator sealed
 * Prevents the class from being extended.
 * @param constructor The constructor of the class.
 */
function sealed(constructor: Function): void {
    Object.seal(constructor);
    Object.seal(constructor.prototype);
}

/**
 * @decorator enumerable
 * Sets the enumerable property of a class member.
 * @param value Whether the property should be enumerable.
 */
function enumerable(value: boolean) {
    return function (
        target: any,
        propertyKey: string,
        descriptor: PropertyDescriptor
    ) {
        descriptor.enumerable = value;
    };
}
```





<img align="right" src="https://visitor-badge.laobi.icu/badge?page_id=sultan-ul-arefin.sultan-ul-arefin">

<h1 align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com/?lines=Hello,+There!+👋;++This+is+Sultanul+Arefin;Nice+to+meet+you!&center=true&size=30">
  </a>
</h1>

<h5 align="center">
  <code>
    <a href="https://www.linkedin.com/in/sultan-ul-arefin/" title="LinkedIn"><img width="22" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/linkedin.svg"> LinkedIn</a></code>
  <code><a href="mailto:programmer.arefin@gmail.com?subject=From%20GitHub&body=Hi,%20there.%20Found%20you%20from%20GitHub." title="Send email"><img width="22" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/gmail.png"> Email</a></code>
  <code><a href="https://www.Facebook.com/arefin99" title="Facebook Profile"><img width="22" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/facebook.png"> Facebook</a></code>
  <code><a href="https://sultan-ul-arefin.github.io/" title="Website & Blog"><img width="22" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/blog.png"> Website & Blog </a>
  </code>

</h5>
<br>
<p align="center">
  Hi, I'm Sultanul Arefin, Computer Engineer & Software Developer from Dhaka,Bangladesh
  <br>
  <br>
  🎓 I'm currently studying for a bachelor's degree in Computer Scinece & Engineering
  <br>
  🌱 Also working at a startup company <a href="https://infobahnrealm.com" title="Infobahn Realm">Infobahn Realm</a> as software engineer.
  <br>
  💻 I love writing clean code and knowing about latest technology staff.
  <br>
  📚 I’m currently learning Blockchain, NLP & Data Science beside Flutter.
  <br>
  💬 Ask me anything about from <a href="https://github.com/sultan-ul-arefin/sultan-ul-arefin/issues" title="Issues">Here</a>
  <br>
  📫 How to reach me: <a href="mailto: programmer.arerfin@gmail.com">programmer.arerfin@gmail.com</a>
</p>

<hr>
<h2 align="center">🔥 Languages & Frameworks & Tools & Abilities 🔥</h2>
<br>
<p align="center">
  <!-- <code><img title="C" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/c.svg"></code>
  <code><img title="C++" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/cpp.svg"></code> -->
  <code><img title="Javascript" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/javascript.svg"></code>
  <code><img title="Typescript" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/Typescript.svg"></code>
  <code><img title="Node js" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/nodejs.png"></code>
  <code><img title="Nest js" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/nestjs.png"></code>
  <code><img title="AngularJS" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/angularjs.png"></code>
  <code><img title="ionic" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/ionic.png"></code>
  <code><img title="C#" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/cSharp.svg"></code>
  <code><img title=".NetCore" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/dotnetcore.svg"></code>
  <code><img title="Java" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/java-original.svg"></code>
  <code><img title="Android" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/android.svg"></code>
  <code><img title="flutter" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/flutter.png"></code>
  <code><img title="Python" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/python-original.svg"></code>
  <code><img title="Django" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/django.png"></code>
  <code><img title="Flask" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/flask.png"></code>
  <!-- <code><img title="Problem Solving" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/problemSolving.png"></code> -->
  <!-- <code><img title="Gulp" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/gulp.svg"></code> 
  <code><img title="React" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/react-original.svg"></code>
  <code><img title="Redux" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/redux.svg"></code> -->


  <code><img title="HTML5" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/html5.svg"></code>
  <code><img title="CSS" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/css.svg"></code>
  <code><img title="SASS" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/sass.svg"></code>
  
  <code><img title="Visual Studio Code" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/vscode.png"></code>
  <code><img title="Microsoft Visual Studio" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/visualstudio.png"></code>
  <!-- <code><img title="JQuery" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/jquery-original.svg"></code> -->
  <code><img title="npm" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/npm.svg"></code>
  <code><img title="GitHub" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/github.svg"></code>
  <code><img title="Git" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/git-original.svg"></code>
  <!-- <code><img title="JSON" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/json.svg"></code> -->
  <!-- <code><img title="Unity" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/unity3d.svg"></code> -->
  <code><img title="Mongo DB" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/mongodb.png"></code>
  <code><img title="PostgreSQL" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/postgresql.svg"></code>
  <code><img title="MySQL" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/mysql.svg"></code>
  <!-- <code><img title="PHP" height="25" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/php.svg"></code> -->
  
  
</p>
<hr>

<h2 align="center">⚡ Stats ⚡</h2>
<br>
<p align=center>
  <div align=center>
    <a href="https://github.com/anuraghazra/github-readme-stats">
      <img width=325 align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sultan-ul-arefin&hide=c%23,powershell,Mathematica,Ruby,Objective-C,Objective-C%2b%2b,Cuda&title_color=61dafb&text_color=ffffff&icon_color=61dafb&bg_color=20232a&langs_count=8&layout=compact&border_color=61dafb&hide_border=true" />
    </a>
  </div>
  
  <br><br>
  <div align=center>
    <a href="https://github.com/denvercoder1/github-readme-streak-stats" title="Go to Source">
      <img align="left" width=396 src="https://github-readme-streak-stats.herokuapp.com/?user=sultan-ul-arefin&theme=react&border=61dafb&hide_border=true" alt="sultan-ul-arefin" />
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats" title="Go to Source">
      <img align="right" width=396 src="https://github-readme-stats.vercel.app/api?username=sultan-ul-arefin&show_icons=true&theme=react&border_color=61dafb&hide_border=true" />
    </a>
  </div>
  <br><br><br><br><br><br><br><br><br>
  <br>
  <img src="https://activity-graph.herokuapp.com/graph?username=sultan-ul-arefin&theme=react-dark&bg_color=20232a&hide_border=true" width="100%"/>
</p>

<hr>

<h2 align="center">👨‍💻 Repositories 👨‍💻</h2>
<br>
<div width="100%" align="center">
  <a align="left" href="https://github.com/sultan-ul-arefin/hr-flutter-app" title="Flutter HR Application"><img align="left" height="115" src="https://github-readme-stats.vercel.app/api/pin/?username=sultan-ul-arefin&repo=hr-flutter-app&theme=react&border_color=61dafb&border_radius=10"></a><a align="right" href="https://github.com/sultan-ul-arefin/scully" title="Angular Scully"><img align="right" height="115" src="https://github-readme-stats.vercel.app/api/pin/?username=sultan-ul-arefin&repo=scully&theme=react&border_color=61dafb&border_radius=10"></a>
</div>
<!-- <br/><br/><br/><br/><br/><br/>
<div width="100%" align="center">
  <a align="left" href="https://github.com/sultan-ul-arefin/Turkce-Heceleme-CPP" title="Turkce-Heceleme-CPP"><img align="left" height="115" src="https://github-readme-stats.vercel.app/api/pin/?username=sultan-ul-arefin&repo=Turkce-Heceleme-CPP&theme=react&border_color=61dafb&border_radius=10"></a>
  <a align="right" href="https://github.com/sultan-ul-arefin/CopyMoveForgeryDetectionWithDCT" title="Copy&Move Forgery Detection With DCT"><img align="right" height="115" src="https://github-readme-stats.vercel.app/api/pin/?username=sultan-ul-arefin&repo=CopyMoveForgeryDetectionWithDCT&theme=react&border_color=61dafb&border_radius=10"></a>
</div>
<br/><br/><br/><br/><br/><br/>
<div width="100%" align="center">
  <a align="left" href="https://github.com/sultan-ul-arefin/cpp-openmp-needleman-wunsch" title="Needleman Wunsch Algorithm With OpenMP"><img align="left" height="115" src="https://github-readme-stats.vercel.app/api/pin/?username=sultan-ul-arefin&repo=cpp-openmp-needleman-wunsch&theme=react&border_color=61dafb&border_radius=10"></a>
  <a align="right" href="https://github.com/sultan-ul-arefin/cpp-artificial-neural-networks" title="Artificial Neural Networks"><img align="right" height="115" src="https://github-readme-stats.vercel.app/api/pin/?username=sultan-ul-arefin&repo=cpp-artificial-neural-networks&theme=react&border_color=61dafb&border_radius=10"></a>
</div>
<br/><br/><br/><br/><br/><br/>
<div width="100%" align="center">
  <a align="left" href="https://github.com/sultan-ul-arefin/javascript-minesweeper" title="Minesweeper"><img align="left" height="115" src="https://github-readme-stats.vercel.app/api/pin/?username=sultan-ul-arefin&repo=javascript-minesweeper&theme=react&border_color=61dafb&border_radius=10"></a>
  <a align="right" href="https://github.com/sultan-ul-arefin/KTU-TraditionalComputerOlympics-2019" title="KTU Traditional Computer Olympics 2019-2020"><img align="right" height="115" src="https://github-readme-stats.vercel.app/api/pin/?username=sultan-ul-arefin&repo=KTU-TraditionalComputerOlympics-2019&theme=react&border_color=61dafb&border_radius=10"></a>
</div> -->
<br><br><br><br><br><br>
<h4 align="center">
  <a href="https://github.com/sultan-ul-arefin?tab=repositories" title="Show Repositories">🔎 Show More 🔍</a>
</h4>


<!--
**sultan-ul-arefin/sultan-ul-arefin** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...


Notes: If you want use this readme, firstly star it please. If you can't align your repositories like this, please change your repository desription to shorter than now. Maybe 4 or 5 word will be good.

![Metrics](https://metrics.lecoq.io/sultan-ul-arefin?template=classic&base.header=0&base.activity=0&base.community=0&base.repositories=0&base.metadata=0&achievements=1&achievements.threshold=C&achievements.secrets=true&achievements.limit=0&config.timezone=Europe%2FIstanbul)

-->
