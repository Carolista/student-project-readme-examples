# Student Project README Resource

<!-- Add jump links here once sections are well-established and unlikely to change -->
<!-- Break out content line items maybe? instead of bullets? and add resources for API documentation, deployment, ERDs, etc. -->
<!-- Add separate table with README templates and examples -->
<!-- Add section on images and links, maybe find resources for creating animated GIFs -->

> [!NOTE]
> A README is often the first impression a prospective employer gets when they take a look at your project repository. This guide will help you craft a README that will stand out and showcase not only your technical depth but also your communication skills and professionalism.

---
## 🗒️ CONTENT

LaunchCode students: You are required to include each of the following with your Unit 2 Final Project:
- [X] A paragraph-long description (elevator pitch) of your project
- [X] The technologies used
- [X] Installation instructions for the app and any dependencies required (i.e., How would another developer run it locally after forking and cloning?)
- [X] Link to digital wireframes or embedded screenshots (or both!)
- [X] Link to digital entity relationship diagrams (ERDs) or embedded screenshots (or both!)
- [X] Description of unsolved problems and/or future features

Other items to consider:
- [ ] Screenshots or high-quality animated GIFs of the app in use
- [ ] Link to a functioning demo (if app is deployed)
- [ ] List of API endpoints and their purpose
- [ ] Testing framework(s) and coverage metrics (if applicable)

#### 🔗 Resources

| Source | Link |
|---:|:---|
| @PurpleBooth on GitHub | [README Template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2) |
| @elangosundar on GitHub | [Collection of README Templates](https://github.com/elangosundar/awesome-README-templates) |

---
## #️⃣ MARKDOWN SYNTAX

Markdown is *extremely* easy to learn, and well worth the minor effort it takes to use it. Just keep a good reference handy, and experiment a bit!

#### 🔗 Resources

| Source | Link |
|---:|:---|
| GitHub Docs | [Quickstart Writing Guide](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github) |
| GitHub Docs | [Basic Writing Guide](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) |
| GitHub Docs | [Formatting Tables](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/organizing-information-with-tables) |
| Tables Generator | [Markdown Table Generator](https://www.tablesgenerator.com/markdown_tables) |

---
## MAKING IT 💥POP💥

### 🧑‍💻 Formatting Code

Whenever you mention a file name (`App.jsx`), variable name (`movie.title`), etc. you should use *inline styling* with **single backticks**.

If you have a *entire block of code*, or perhaps *one or more commands at a prompt*, use **triple backticks** instead. Examples:
```
cd project-directory
npm run dev
```

```javascript
function sayHello(name) {
    console.log(`Hello, ${name}!`);
}

sayHello("Bob"); // Hello, Bob!
```

#### 🔗 Resources

| Source | Link |
|---:|:---|
| GitHub Docs | [Formatting Code Blocks](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks) |
| @jincheng9 on GitHub | [Markdown Supported Languages for Code Blocks](https://github.com/jincheng9/markdown_supported_languages) |

### 📛 Badges
Adding some color and quick-reference info at the top of your README can make it stand out immediately.

There are different styles: ![Static Badge](https://img.shields.io/badge/style-flat-darkmagenta)
![Static Badge](https://img.shields.io/badge/style-flat--square-rebeccapurple?style=flat-square)
![Static Badge](https://img.shields.io/badge/style-plastic-navy?style=plastic)
![Static Badge](https://img.shields.io/badge/style-for--the--badge-bada55?style=for-the-badge)
![Static Badge](https://img.shields.io/badge/style-social-white?style=social)

You can even add icons: ![JavaScript](https://img.shields.io/badge/JavaScript-F0DB4F?logo=javascript&logoColor=323330)
![React](https://img.shields.io/badge/React-61DBFB?logo=react&logoColor=20232A)

#### 🔗 Resources

| Source | Link |
|---:|:---|
| Shields.io Docs | [Badges Documentation](https://shields.io/badges) |
| Simple Icons Docs | [Icon Library](https://simpleicons.org/) |
| Badges4-README.md-Profile  | [Preset Badges](https://github.com/alexandresanlim/Badges4-README.md-Profile) |

### 😄 Emoji
You can copy-and-paste emoji into your `.md` document, or if you are editing on GitHub, you can use `:emojicode:` (similar to Slack) with the tab key to insert emoji as you go.

> [!TIP]
> For portfolio project READMEs, use emoji sparingly.

### ▶️ Collapsed Sections
This one uses a bit of HTML with `<details>` and `<summary>` tags. Test it out below, and learn more [here](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github#adding-a-collapsed-section).

<details>
  <summary>What's the best way to save your dad jokes?</summary>
  ....In a dad-a-base! <em>(insert groan here)</em>
</details>

### 🚨 Alerts
There are 5 different styles of special call-outs you can use; I've got examples of some of them in this README. Learn more [here](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#alerts).

> [!WARNING]
> Don't over-use these or they won't stand out!
