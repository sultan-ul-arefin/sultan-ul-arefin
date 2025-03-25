<div align="right">
<a style="text-decoration: none" target="_blank"href="https://github.com/sultan-ul-arefin">
<img src="https://visitor-badge.laobi.icu/badge?page_id=sultan-ul-arefin.sultan-ul-arefin&left_color=gray&right_color=blue&left_text=Coders%20visitors">
</a>
</div>
<br>
<img src="https://readme-typing-svg.herokuapp.com/?font=Roboto&weight=900&size=40=true&vCenter=true&width=500&height=70&duration=4000&color=B3B3B3&lines=Hi+There!+👋;+I'm+Sultanul+Arefin!;" />
<br>
<h5 align="center">
  <a href="https://www.linkedin.com/in/sultan-ul-arefin/" title="LinkedIn"><img width="22" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/linkedin.svg"> LinkedIn</a>
  <a href="mailto:hello@sultanularefin.com?subject=From%20GitHub&body=Hi,%20there.%20Found%20you%20from%20GitHub." title="Send email"><img width="22" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/gmail.png"> Email</a>
  <a href="https://www.Facebook.com/arefin99" title="Facebook Profile"><img width="22" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/facebook.png"> Facebook</a>
  <a href="https://sultanularefin.com/" title="Website & Blog"><img width="22" src="https://github.com/sultan-ul-arefin/sultan-ul-arefin/blob/main/images/blog.png"> Website </a>
  
</h5>
<br>
<hr>

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
    public summary: string = `
    I have more than five years of experience in design, architecture, development, and deployment in software development.
    I always focus on building user-friendly and high-performance web applications to increase user satisfaction.
    I always try to follow best practices and write clean code every time, making development faster and easier to maintain.
    I enjoy team energy, helping to speed up project completion and improve team productivity while ensuring every solution is creative and effective.`;

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
