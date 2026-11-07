# 🧭 Learn Web Development: Start Here

![Level: Beginner](https://img.shields.io/badge/Level-Beginner-2ea44f)
![Paths: Front End, Back End, Full Stack](https://img.shields.io/badge/Paths-Front%20End%20%7C%20Back%20End%20%7C%20Full%20Stack-1f6feb)
![Resources: free curricula](https://img.shields.io/badge/Resources-Free%20curricula-6f42c1)
![Checked November 2026](https://img.shields.io/badge/Checked-Nov%202026-2ea44f)
[![Last updated](https://img.shields.io/github/last-commit/ImmuneMoon/Learn-Web-Development-Start-Here?label=updated)](https://github.com/ImmuneMoon/Learn-Web-Development-Start-Here/commits/main)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey)](LICENSE)

**📄 [Download the PDF](Learn-Web-Development-Start-Here.pdf)**

## 📖 Overview
**Learn Web Development: Start Here** is the first stop in a set of free guides for people who want to build websites and web apps, or work as a web developer. It explains:
- how a web app works, in plain terms: the browser, the server, the database, APIs and hosting;
- the three paths (front end, back end and full stack), and how to pick one;
- five recommended steps from your first line of code to your first job, with examples for each;
- the best free curricula, compared side by side, plus other course and practice sites;
- the tools to set up on day one: a code editor, a browser with developer tools, Git and GitHub;
- how to keep learning without burning out;
- a short FAQ and a glossary.

It started as a set of community notes written in 2022 and 2023, and has been updated and checked against official sites in November 2026.

## ⚠️ Important Notes
* **Every resource here is free to start,** but some have paid extras, such as certificates. Prices and course details change, so check each site before you pay for anything.
* **None of these sites or creators are affiliated with this guide.** Videos are linked and credited to their creators. Watch them on their own channels.
* **Pick one main curriculum and stick with it.** Jumping between courses is the most common way people stall. The others are there for when you're stuck.
* **Technology moves fast.** The fundamentals here (HTML, CSS, JavaScript, SQL, Git) have been stable for years. Framework versions change often, so check their official sites.

## 🚀 How to Use
Download the PDF above, or read on below. If you're brand new, read Sections 1 to 3 in order, then pick a curriculum in Section 4 and set up your tools with Section 6. Come back to Section 7 whenever learning starts to feel like a grind. If web development turns out not to be your thing, Section 9 points to the other paths in this set: games, data science, DevOps, IT support, 3D modeling and 3D printing.

This guide works alongside the rest of the set:
* [Learn Front End Web Development](https://github.com/ImmuneMoon/Learn-Front-End-Web-Development) - HTML, CSS, JavaScript, frameworks and design tools, with [the five steps for front end](https://github.com/ImmuneMoon/Learn-Front-End-Web-Development#2-the-five-steps).
* [Learn Back End Web Development](https://github.com/ImmuneMoon/Learn-Back-End-Web-Development) - Servers, databases, APIs and security, starting with [the minimum to learn first](https://github.com/ImmuneMoon/Learn-Back-End-Web-Development#3-the-minimum-to-learn-first).
* [Full Stack Web Development and Stacks](https://github.com/ImmuneMoon/Full-Stack-Web-Development-and-Stacks) - Putting front and back end together, and popular stacks, starting with [the route in](https://github.com/ImmuneMoon/Full-Stack-Web-Development-and-Stacks#2-the-route-in).
* [Web Developer Careers: Portfolio, Getting Hired and Freelancing](https://github.com/ImmuneMoon/Web-Developer-Careers-Portfolio-and-Freelancing) - Portfolios, job hunting and freelance work.
* [Learning How to Learn Programming](https://github.com/ImmuneMoon/Learning-How-to-Learn-Programming) - Study techniques, escaping tutorial hell, and staying well.
* [Computer Science Fundamentals](https://github.com/ImmuneMoon/Computer-Science-Fundamentals) - Data structures, algorithms and the CS50 lectures.
* [Coding Practice and Interview Prep](https://github.com/ImmuneMoon/Coding-Practice-and-Interview-Prep) - Challenge sites and technical interviews.
* [Open Source and Developer Communities](https://github.com/ImmuneMoon/Open-Source-and-Developer-Communities) - Where to ask for help, contributing, and using AI assistants well.
* [CLI Cheat Sheet](https://github.com/ImmuneMoon/CLI-Cheat-Sheet) - Terminal commands, Git, and installing Node, Python, Git and VS Code.
* Other learning paths and the tool guides are listed in [Section 9](#9-where-to-go-next).

---

<!-- guide:start -->

*Resources, course details and prices were checked, and every credited video was reviewed against what it actually says, in November 2026. They change, so confirm them on each site.*

## Contents

1. [How Web Apps Work](#1-how-web-apps-work)
2. [Front End, Back End or Full Stack](#2-front-end-back-end-or-full-stack)
3. [The Five Recommended Steps](#3-the-five-recommended-steps)
4. [Free Curricula Compared](#4-free-curricula-compared)
5. [More Course and Practice Sites](#5-more-course-and-practice-sites)
6. [Your Beginner's Toolkit](#6-your-beginners-toolkit)
7. [Learning Without Burning Out](#7-learning-without-burning-out)
8. [Good First Videos](#8-good-first-videos)
9. [Where to Go Next](#9-where-to-go-next)
10. [FAQ](#10-faq)
11. [Glossary](#11-glossary)
12. [Sources](#12-sources)

---

## 1. How Web Apps Work

Every website and web app, from a one-page portfolio to an online store, is built from the same few pieces. Knowing them first makes everything else easier to place.

> **Watch next:** Once the table below makes sense, [Everything You NEED to Know About WEB APP Architecture](https://youtu.be/sDlCSIDwpDs) by **ForrestKnight** (June 2022) shows how those pieces get arranged. It covers:
> * **client-server**, which almost every site uses, versus **peer-to-peer**;
> * **tiers:** whether the front end, back end and database share one machine or each get their own;
> * **monolith, microservices and serverless:** one codebase, many small services, or functions run by a cloud provider, using YouTube and an online shop as examples.
>
> It's more advanced than this section, so don't worry if it doesn't all stick yet. The video presents monoliths as mostly a drawback. In practice, many experienced developers suggest starting with a monolith and splitting it up only when you need to (Martin Fowler's [MonolithFirst](https://martinfowler.com/bliki/MonolithFirst.html)), and that's the right choice for your own projects.

| Piece | What it is | Everyday example |
|---|---|---|
| **Client** | The program the user sees, usually a web browser such as Chrome, Firefox, Edge or Safari. | Your browser showing an online shop. |
| **Server** | A computer that waits for requests and sends back pages or data. | The shop's computer that receives "show me the shoes". |
| **Front end** | Everything that runs in the browser: the page's structure (HTML), its look (CSS) and its behavior (JavaScript). | The product grid, the menu, the **Add to cart** button. |
| **Back end** | The code on the server: it checks who you are, applies the rules and talks to the database. | Checking that the shoes are in stock, and working out the price. |
| **Database** | Where data is stored so it survives after the page closes. | The product list, user accounts and orders. |
| **API** | A defined way for one program to ask another for data or actions, usually over HTTP, often returning JSON. | The front end asking `/api/products` for the shoe list. |
| **Hosting** | Renting space on a server (or a cloud service) so your site is online all the time. | GitHub Pages, Firebase, or any web host. |
| **Domain and DNS** | A domain is the name people type. DNS is the internet's address book, turning that name into the server's address. | `example.com` pointing to the shop's server. |

### What happens when you open a page

1. You type an address, or click a link.
2. DNS turns the domain name into the server's address.
3. Your browser sends an **HTTP request** to that server (over HTTPS, so it's encrypted).
4. The server's back end runs, fetches anything it needs from the database, and sends back a **response**: an HTML page, or data such as JSON.
5. Your browser reads the HTML, downloads the CSS, JavaScript and images it links to, and draws the page.
6. JavaScript in the page can keep sending requests to APIs without reloading, which is how feeds, chats and shopping carts update in place.

MDN's [How the web works](https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Web_standards/How_the_web_works) covers this in more depth, and [How browsers load websites](https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Web_standards/How_browsers_load_websites) covers step 5.

> **A simple site doesn't need a back end.** A portfolio or a restaurant's menu page can be plain HTML, CSS and JavaScript files on a static host. You add a back end and a database when the site needs to remember things, such as accounts, posts or orders.

---

## 2. Front End, Back End or Full Stack

| Path | You build | Core skills | Choose it if you |
|---|---|---|---|
| **Front end** | What people see and click | HTML, CSS, JavaScript, then a framework such as React | Like visual results, design and how things feel to use |
| **Back end** | The server, the data and the rules | A server language (Python, JavaScript with Node.js, Java and others), SQL, APIs, security | Like logic, data and solving puzzles out of sight |
| **Full stack** | Both, and how they connect | Front end and back end, plus deployment | Want to build whole apps on your own, or aren't sure yet |

How to choose:

1. **Not sure? Start with the front end.** HTML, CSS and JavaScript are needed on every path, and you see results straight away. That helps you stay motivated.
2. **Try a small project in each.** Build a page, then a tiny API, and notice which you enjoy more.
3. **Look at job ads near you,** or for the remote roles you want, and note which skills keep appearing.
4. **You can change your mind.** Skills carry over. Plenty of back end developers started on the front end, and full stack developers usually started on one side.

Each path has its own guide, and each one applies the five steps below to its own skills:
* [Learn Front End Web Development](https://github.com/ImmuneMoon/Learn-Front-End-Web-Development), [Section 2: The Five Steps](https://github.com/ImmuneMoon/Learn-Front-End-Web-Development#2-the-five-steps)
* [Learn Back End Web Development](https://github.com/ImmuneMoon/Learn-Back-End-Web-Development), [Section 3: The Minimum to Learn First](https://github.com/ImmuneMoon/Learn-Back-End-Web-Development#3-the-minimum-to-learn-first)
* [Full Stack Web Development and Stacks](https://github.com/ImmuneMoon/Full-Stack-Web-Development-and-Stacks), [Section 2: The Route In](https://github.com/ImmuneMoon/Full-Stack-Web-Development-and-Stacks#2-the-route-in)

---

## 3. The Five Recommended Steps

These five steps work for every path. **You can learn the topics within each step in any order, but don't take on too many at once.** One language or tool at a time beats five at half speed.

### Step 1: Learn a language to a basic proficiency

Basic proficiency means you can write small programs without copying them line by line. You know the core ideas: variables, conditions (`if`), loops, functions, and lists or arrays.

| Path | Start with | You're there when you can |
|---|---|---|
| Front end | HTML and CSS, then JavaScript | Build a page with headings, links, images and a form; lay it out with Flexbox; make a button show or hide something |
| Back end | Python (or JavaScript) | Write a script that reads a file, loops over its lines, and prints a summary |
| Either | SQL | Write a query that picks rows from a table, filters them, and sorts them |

### Step 2: Build basic applications and projects

Build small things **without following a tutorial step by step.** This is where learning sticks. Some classic first projects, taken from The Odin Project's Foundations course:

* A **recipe page**: plain HTML pages linked together.
* A **landing page**: a styled single page laid out with Flexbox.
* **Rock Paper Scissors**: JavaScript logic in the browser console, then with buttons.
* **Etch-a-Sketch**: a grid of squares that change color as you move the mouse.
* A **calculator**: buttons, a display, and the logic behind them.

For a back end start, try a command-line to-do list in Python that saves to a file.

### Step 3: Learn libraries, frameworks and runtime environments

Once the basics feel comfortable, learn the tools built on top of your language. They save you from writing the same things over and over.

* **Library:** code you call when you need it, such as React for building user interfaces.
* **Framework:** a structure you build inside, which calls your code, such as Next.js, Django or Express.
* **Runtime environment:** the program that runs your code outside the browser, such as Node.js for JavaScript.

Examples by path:

* **Front end:** React (with Next.js later), or Vue. For styling, a CSS framework such as Tailwind CSS or Bootstrap, once you're comfortable with plain CSS.
* **Back end:** Node.js with Express, or Python with Flask or Django.

> **Learn the language before the framework.** A framework makes much more sense when you know what it's doing for you. To see what a framework does for you, watch [What is a Framework and Why use Frameworks](https://youtu.be/1a5VKUc0AUc) by Bitfumes (now Sarthaksavvy, 2017). He describes a framework as a ready-made skeleton, like the frame of a house. It gives you:
> * a standard way to structure an app;
> * reusable functions, such as fetching data from the database;
> * routing, which decides how each URL is answered;
> * the model-view-controller (MVC) pattern;
> * easy use of third-party packages.
>
> His examples are PHP frameworks such as Laravel, but the ideas apply to Django, Express and the rest.

### Step 4: Build bigger projects, with Git and GitHub

Now combine pieces: a framework, more than one language, and real data. **Use Git and GitHub from here on,** if you haven't already, and give every project its own repository.

Example projects:

* A **weather app** that calls a public weather API and shows the forecast.
* A **to-do list** that saves to the browser's storage, then later to a database.
* A **message board** or **blog** with sign-in, a database, and pages to create, edit and delete posts.
* A **small online shop** with a product list, a cart, and an admin page.

Good habits for this step:

1. **Commit small and often,** with messages that say what changed.
2. **Write a README** for each project: what it does, how to run it, and a screenshot.
3. **Put it online.** A live link is far more convincing than a folder of code. Section 6 and the careers guide cover where.

### Step 5: Create a portfolio website and pursue your career

Make a simple site that shows your best three to five projects, with live links, code links and a short write-up of each. Then start applying, networking or freelancing. The [Web Developer Careers guide](https://github.com/ImmuneMoon/Web-Developer-Careers-Portfolio-and-Freelancing) covers portfolios, GitHub profiles, applications and freelancing in detail.

---

## 4. Free Curricula Compared

A curriculum gives you an order to learn things in, so you're not guessing. **Pick one as your main path.** Use the others as references.

| Curriculum | Cost | What it is | Certificate | Best for |
|---|---|---|---|---|
| **[The Odin Project](https://www.theodinproject.com/)** | Free, funded by donations | Open source. Foundations, then **Full Stack JavaScript** or **Full Stack Ruby on Rails**. Lessons point to the best articles and docs, and you build dozens of projects locally on your own computer. Active Discord community. | None | Self-starters who want real-world setup and lots of projects |
| **[freeCodeCamp](https://www.freecodecamp.org/learn)** | Free, a charity | Interactive lessons in the browser. Its new curriculum has six certifications (Responsive Web Design, JavaScript, Front End Libraries, Python, Relational Databases, and Back End Development and APIs), each with projects and an exam, leading to a **Certified Full Stack Developer** capstone. | Free, verified | Structured, hands-on practice with free certificates |
| **[MDN Learn web development](https://developer.mozilla.org/en-US/docs/Learn_web_development)** | Free | Written lessons from the makers of Firefox, in Getting started, Core and Extension modules. Aims to take you from beginner to comfortable. | None | Clear explanations, and the most trusted reference |
| **[CS50's Web Programming with Python and JavaScript (CS50W)](https://cs50.harvard.edu/web/)** | Free to take; optional paid edX certificate | Harvard's course: HTML and CSS, Git, Python, Django, SQL, JavaScript, user interfaces, testing and CI/CD, and scalability and security, plus a final project. Expects CS50 or some prior programming. | Free CS50 certificate, or a paid edX one | Learners with some coding who want a university-style course |
| **[roadmap.sh](https://roadmap.sh/)** | Free to browse | Not a course but a map: community-made role roadmaps ([Frontend](https://roadmap.sh/frontend), [Backend](https://roadmap.sh/backend), [Full Stack](https://roadmap.sh/full-stack)) showing what to learn and in what order, with [project ideas](https://roadmap.sh/projects). | None | Seeing the whole picture, and checking for gaps |

Details worth knowing:

* **freeCodeCamp's older certifications** are now called "legacy". In September 2025, freeCodeCamp said they will eventually expire, no sooner than 2028, and advised learners to move to the new curriculum. It estimated about 300 hours per certification, and about 1,800 hours for the whole full stack path. Some parts were released in stages, so check the Learn page for what's live.
* **CS50W** is free through Harvard's OpenCourseWare at [cs50.harvard.edu/web](https://cs50.harvard.edu/web/). Score at least 70% on every project, including the final project, and you can get a [free CS50 certificate](https://cs50.harvard.edu/web/certificate/). If you want a verified certificate from edX instead, enroll through [edX](https://www.edx.org/course/cs50s-web-programming-with-python-and-javascript-web). When checked, edX listed it as free to audit, self-paced, about 12 weeks at 6 to 9 hours a week, with a verified certificate for US$299, and the current run open until June 30, 2027.
* **HarvardX's [Computer Science for Web Programming Professional Certificate](https://www.edx.org/certificates/professional-certificate/harvardx-computer-science-for-web-programming)** pairs CS50's Introduction to Computer Science (CS50x) with CS50W. It's still offered on edX, as a paid bundle of the two certificates.
* **roadmap.sh replaces the old PDF roadmap** that used to be shared with these notes. Its roadmaps are kept up to date by the community, and its project pages let you submit a solution and see other people's.

---

## 5. More Course and Practice Sites

These are good extras alongside your main curriculum, especially when one explanation doesn't click and you need another.

### Courses

| Site | Cost | Good for |
|---|---|---|
| [Codecademy](https://www.codecademy.com/) | Free Basic plan. Paid plans add portfolio projects and certificates, and the Pro plan adds career paths. | Short interactive lessons in the browser |
| [Khan Academy computer programming](https://www.khanacademy.org/computing/computer-programming) | Free | Gentle starts, including Intro to JS, Intro to HTML/CSS and Intro to SQL |
| [web.dev Learn](https://web.dev/learn) | Free | Courses written with members of Google's Chrome team, such as Learn HTML, Learn CSS, Learn JavaScript, Learn Accessibility and Learn Performance |
| [edX](https://www.edx.org/search?q=web+development) | Many courses free to audit. Certificates are paid, and financial assistance is offered on many. | University courses from Harvard, MIT and others |
| [Class Central](https://www.classcentral.com/search?q=computer+science) | Free to search | Finding free university courses on any topic |
| [freeCodeCamp's list of 860+ free CS courses](https://www.freecodecamp.org/news/free-online-programming-cs-courses/) | Free | A big list from universities, compiled by Class Central's founder (January 2023, so some links may have moved) |
| [Educative](https://www.educative.io/explore/free) | Mostly paid, with a **Free** filter | Text-based courses with in-browser coding |

### References

* **[MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web)** is the reference to trust for HTML, CSS and JavaScript. Bookmark it.
* **[W3Schools](https://www.w3schools.com/)** has free, short tutorials and a "Try it" editor, which many beginners find friendly. Its certificates are paid. When the two disagree, go with MDN, which is more thorough and more closely tied to the official web standards.

### Light practice on your phone

[Sololearn](https://www.sololearn.com/) and [Mimo](https://mimo.org/) offer bite-sized lessons on the web, iOS and Android, with free tiers and paid plans. They're good for keeping ideas fresh on a commute, but treat them as an **accessory** to a real curriculum, because you won't build full projects in them.

### Coding challenges and project sites

Challenge sites (Codewars, HackerRank, Frontend Mentor and others) are covered in [Coding Practice and Interview Prep](https://github.com/ImmuneMoon/Coding-Practice-and-Interview-Prep). Project ideas for your portfolio are in the [careers guide](https://github.com/ImmuneMoon/Web-Developer-Careers-Portfolio-and-Freelancing#2-projects-that-show-real-skill).

> **Google's old developer page has moved.** The `grow.google/developers` link in the original notes now redirects to Google's general Grow with Google page. For Google's free web development courses, use [web.dev Learn](https://web.dev/learn) above.

---

## 6. Your Beginner's Toolkit

You need four things, and all of them are free.

### 6.1 A code editor

| Editor | Cost | Notes |
|---|---|---|
| **[Visual Studio Code](https://code.visualstudio.com/)** | Free | The most used editor by far: 75.9% of respondents in Stack Overflow's 2025 survey. Huge extension library. Windows, macOS and Linux. **Start here if unsure.** |
| [Neovim](https://neovim.io/) | Free, open source | A "hyperextensible Vim-based text editor" that runs in the terminal. Powerful and fast, but it has a steep learning curve. Try it later. |
| [Kate](https://kate-editor.org/) | Free, from KDE | A capable editor for Linux, Windows and macOS. |
| [Sublime Text](https://www.sublimetext.com/) | Free to evaluate; a license is required for continued use | Very fast. It reminds you to buy a license. |

> **VS Code isn't Visual Studio.** [Visual Studio](https://visualstudio.microsoft.com/) is Microsoft's separate, heavier IDE, used mostly for C# and C++. For web development, download **Visual Studio Code** from [code.visualstudio.com](https://code.visualstudio.com/).
>
> **Skip Atom.** It was a popular free editor, but GitHub retired it on December 15, 2022, and it no longer gets updates.

To install VS Code (and Git, Node.js and Python) with one command each, see the developer setup section of the [CLI Cheat Sheet](https://github.com/ImmuneMoon/CLI-Cheat-Sheet).

**VS Code tips worth a minute each.** Three come from the official **Visual Studio Code** channel, and one from **Web Dev Simplified**:

| Short | What it shows |
|---|---|
| [Balance Out](https://youtube.com/shorts/NwqhFb4B5LU) | Run **Emmet: Balance (outward)** from the Command Palette (`Ctrl`+`Shift`+`P`) to select a whole HTML element, closing tag included. Run it again to grow the selection. **Balance (inward)** shrinks it. The presenter binds them to his own keyboard shortcuts in **Keyboard Shortcuts** settings. |
| [To the left, to the left](https://youtube.com/shorts/DEUud_c9GRE) | **Go Back** jumps to where your cursor was before, for example after scrolling up to check a function: `Alt`+`Left` on Windows, `Ctrl`+`-` on macOS, `Ctrl`+`Alt`+`-` on Linux. |
| [Terminal editors](https://www.youtube.com/shorts/36g1FLPcg6s) | Drag a terminal tab into the editor area, so terminals sit beside your files and show up in **Quick Open** (`Ctrl`+`P`). |
| [5 Must Know VSCode Shortcuts](https://youtube.com/shorts/C926N9zMJkU) | `Ctrl`+`B` hides the sidebar. `Ctrl`+`Shift`+`E` and `Ctrl`+`Shift`+`F` jump to the file explorer and search. `` Ctrl+` `` toggles the terminal. `Ctrl`+click goes to where something is defined. `Ctrl`+`.` offers quick fixes. `Ctrl`+`Space` shows suggestions. On a Mac, use `Cmd` for most of these. |

### 6.2 A browser with developer tools

Every major browser has built-in **developer tools (DevTools)**. They let you inspect and change a page's HTML and CSS live, see JavaScript errors, and watch every network request. You'll use them every day.

| Browser | Open DevTools | Useful for |
|---|---|---|
| **Chrome** (and Edge) | `F12` or `Ctrl`+`Shift`+`I`. On a Mac, `Cmd`+`Option`+`I`. | The **Elements**, **Console**, **Network** and **Performance** panels |
| **Firefox** | `F12` or `Ctrl`+`Shift`+`I`. On a Mac, `Cmd`+`Option`+`I`. | The **Page Inspector** (great for Grid and Flexbox), **Responsive Design Mode** and the **Accessibility** inspector |

Try it now: right-click any part of this page and choose **Inspect**.

### 6.3 Git and GitHub

* **Git** is version control: it saves snapshots of your project, so you can see what changed and undo mistakes. It runs on your computer.
* **GitHub** is a website that stores your Git projects online, shows them to employers, and lets you work with others. [Make an account](https://github.com/) early and keep your work there.

After installing Git (see the [CLI Cheat Sheet](https://github.com/ImmuneMoon/CLI-Cheat-Sheet)), tell it who you are, once:

```powershell
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

Use the email address on your GitHub account, or GitHub's private `noreply` address from your GitHub email settings if you'd rather not publish your real one.

Check your tools are installed:

```powershell
git --version
code --version
```

Then:
* GitHub's [Hello World](https://docs.github.com/en/get-started/start-your-journey/hello-world) tutorial teaches repositories, branches and pull requests in the browser.
* [Publishing to GitHub with gh](https://github.com/ImmuneMoon/Publishing-to-GitHub-with-gh) shows how to put a project on GitHub from the terminal.
* The [CLI Cheat Sheet](https://github.com/ImmuneMoon/CLI-Cheat-Sheet) has everyday Git commands side by side.

### 6.4 Online editors, for quick experiments

You don't need to install anything to try an idea. These run in the browser:

| Site | Good for |
|---|---|
| [CodePen](https://codepen.io/) | Front end experiments in HTML, CSS and JavaScript, and browsing other people's demos. A paid tier adds private pens. |
| [StackBlitz](https://stackblitz.com/) | Full Node.js projects running inside your browser, such as React or Vite starters. |
| [CodeSandbox](https://codesandbox.io/) | Front end and full stack sandboxes. Its free plan has usage limits. |
| [Replit](https://replit.com/) | Many languages in the browser. It now centers on its AI app-building agent, and its free use is limited. |

Use them for experiments and sharing, but build your real projects locally with VS Code and Git. That's how you'll work in a job.

---

## 7. Learning Without Burning Out

Most people who stop learning to code don't fail at the hard parts. They run out of steam. These habits help.

### One language at a time

Get comfortable with one language before adding another. Learning JavaScript, Python and SQL all at once means you're a beginner in three things at the same time. The exception is HTML and CSS, which go together.

### Build more than you watch

Tutorials feel productive, but following along isn't the same as being able to do it. Getting stuck in a loop of one tutorial after another is often called **tutorial hell**. To get out:

1. After each tutorial, **build something similar without it.** Change the topic: if the tutorial built a to-do list, build a reading list.
2. **Add one feature** the tutorial didn't cover.
3. When stuck, search for the specific problem, not a new tutorial.

[Learning How to Learn Programming, Section 4](https://github.com/ImmuneMoon/Learning-How-to-Learn-Programming#4-build-get-out-of-tutorial-hell) has more ways out.

### Spaced practice

Short, regular sessions beat long, rare ones. Your memory holds on to things better when you come back to them over several days.

* **Code a little most days,** for example 45 to 90 minutes, rather than one exhausting weekend session.
* **Revisit older topics.** Rebuild a small earlier project from memory every few weeks.
* **Test yourself** before looking things up: try to write it first, then check.
* **Take real breaks.** MDN's learning advice suggests a proper 15-minute break every hour to 90 minutes, and looking away from the screen regularly.

### Look after the basics

Sleep, food and exercise affect how well you learn far more than any app. Set a learning schedule you can keep, schedule time off as well, and reward yourself when you finish something.

[Learning How to Learn Programming](https://github.com/ImmuneMoon/Learning-How-to-Learn-Programming) goes much deeper: study techniques, taking notes, planning projects, staying focused, and books.

---

## 8. Good First Videos

* [Learn web development as an absolute beginner](https://www.youtube.com/watch?v=ysEN5RaKOlA), **Coder Coder** (November 2019). A roadmap in four steps:
  1. The concepts: client and server, front end and back end, and a code editor.
  2. HTML, CSS and JavaScript.
  3. The everyday tools: a package manager (npm), a build tool, and Git.
  4. Then either more front end (Sass, responsive design, and a framework such as React, Angular or Vue) or the back end (a server, a server language, and SQL or NoSQL databases).

  She advises learning a little of both sides, and choosing a framework by what local job ads ask for. **Since then:** the Atom editor it mentions was retired in 2022 (Section 6.1). Its build tools (Gulp, webpack and Parcel) have largely given way to newer ones. React's own docs now suggest starting with Vite, Parcel or Rsbuild.
* [Learn Web Development FREE and Actually Get Hired](https://youtu.be/14-xBLhZ4AE), **devsmak** (the channel is now **James Cross**, May 2022). He left a construction job and taught himself, and he maps a free, front-end-first route:
  * freeCodeCamp's courses first, including the responsive design, JavaScript and front end libraries certifications. He'd skip jQuery, since React apps don't use it.
  * Then The Odin Project's Foundations and Full Stack JavaScript path.
  * Then CS50x for computer science basics.
  * Skip pricey bootcamps.
  * Treat certificates as nice to have. What gets you hired is building your own projects without a tutorial.

  **Since then:** freeCodeCamp has replaced those certifications with a new curriculum, and the old ones are now "legacy" (Section 4).
* [How To Think Like A Programmer](https://www.youtube.com/watch?v=azcrPFhaY9k), a talk by computer science teacher **Andy Harris**, uploaded by **Coding Tech** (October 2018, about an hour). His argument: programming is mostly planning, not memorizing a language. His method:
  * Write the steps in plain language first, on paper if you like.
  * Turn each step into a code comment, then translate one comment at a time into code, searching for syntax only once you know what you need.
  * When it breaks, ask whether the plan was wrong or the code was. Check your assumptions by printing values and their types, instead of guessing at fixes.

  His examples are in Python. Jump to:
  * [the myths about learning to code](https://youtu.be/azcrPFhaY9k?t=547) (9:07)
  * [comments first, then code](https://youtu.be/azcrPFhaY9k?t=1124) (18:44)
  * [a worked example, with a bug](https://youtu.be/azcrPFhaY9k?t=1842) (30:42)
  * [debugging](https://youtu.be/azcrPFhaY9k?t=2237) (37:17)
  * [loops](https://youtu.be/azcrPFhaY9k?t=2887) (48:07)

  His aside that Python has no switch statement is out of date: Python 3.10 (2021) added `match`.
* [Everything You NEED to Know About WEB APP Architecture](https://youtu.be/sDlCSIDwpDs), **ForrestKnight**. How the pieces fit together, once the basics make sense (Section 1). It's hard on monoliths, but for your own projects, starting with one is usually the better choice (see the note in Section 1).
* [What is a Framework and Why use Frameworks](https://youtu.be/1a5VKUc0AUc), **Bitfumes** (now **Sarthaksavvy**). For Step 3.
* [CS50 Lectures 2021](https://youtube.com/playlist?list=PLhQjrBD2T383f9scHRNYJkior2VvYjpSL), **CS50**. Harvard's full lecture series for CS50x and CS50W, covering C, Python, SQL, HTML, CSS and JavaScript. Newer lectures are on [cs50.harvard.edu/x](https://cs50.harvard.edu/x/) (CS50x 2026 when checked). This is one option for a deeper foundation. [Computer Science Fundamentals](https://github.com/ImmuneMoon/Computer-Science-Fundamentals) covers it in more detail.

---

## 9. Where to Go Next

Web development is one path among several. The five steps and the study habits in this guide carry over to all of them, so nothing you learn here is wasted if you change direction.

### 9.1 The web development path

| Guide | Read it when |
|---|---|
| [Learn Front End Web Development](https://github.com/ImmuneMoon/Learn-Front-End-Web-Development) | You want to build what people see and click. |
| [Learn Back End Web Development](https://github.com/ImmuneMoon/Learn-Back-End-Web-Development) | You want to build servers, APIs and databases. |
| [Full Stack Web Development and Stacks](https://github.com/ImmuneMoon/Full-Stack-Web-Development-and-Stacks) | You want to build whole apps, or are choosing a stack. |
| [Web Developer Careers, Portfolio and Freelancing](https://github.com/ImmuneMoon/Web-Developer-Careers-Portfolio-and-Freelancing) | You have a few projects and want a job or clients. |

### 9.2 Learning and practice, for any path

| Guide | Read it when |
|---|---|
| [Learning How to Learn Programming](https://github.com/ImmuneMoon/Learning-How-to-Learn-Programming) | You want study techniques that stick, or you're stuck in tutorial hell. |
| [Computer Science Fundamentals](https://github.com/ImmuneMoon/Computer-Science-Fundamentals) | You can build small apps and want data structures, algorithms and Big O. [Section 1.2](https://github.com/ImmuneMoon/Computer-Science-Fundamentals#12-when-web-developers-can-wait) says what can wait. |
| [Coding Practice and Interview Prep](https://github.com/ImmuneMoon/Coding-Practice-and-Interview-Prep) | You want challenge sites, or have a technical interview coming up. |
| [Open Source and Developer Communities](https://github.com/ImmuneMoon/Open-Source-and-Developer-Communities) | You want help from other developers, your first open source contribution, or to use AI assistants well. |

### 9.3 Other paths

If something else catches your interest, these guides start from zero, just like this one:

| Guide | What you'll do | It might suit you if you |
|---|---|---|
| [Learn Game Development](https://github.com/ImmuneMoon/Learn-Game-Development) | Make small games with an engine such as Godot or Unity, starting from [free courses](https://github.com/ImmuneMoon/Learn-Game-Development#1-how-to-start) | Like games, and want to see your code move and react |
| [Learn Data Science](https://github.com/ImmuneMoon/Learn-Data-Science) | Answer questions with data, using [Python, SQL and statistics](https://github.com/ImmuneMoon/Learn-Data-Science#3-the-path-at-a-glance) | Enjoy the SQL and data parts of back end work, or like finding patterns |
| [Getting Started with DevOps](https://github.com/ImmuneMoon/Getting-Started-with-DevOps) | Automate how software is built, tested, shipped and run, with Linux, Git, Docker and the cloud ([the order to learn in](https://github.com/ImmuneMoon/Getting-Started-with-DevOps#3-the-order-to-learn-in)) | Enjoy deploying your projects more than building their pages |
| [IT Support Careers and Certifications](https://github.com/ImmuneMoon/IT-Support-Careers-and-Certifications) | Help people and organizations keep their computers running, on a path from [help desk](https://github.com/ImmuneMoon/IT-Support-Careers-and-Certifications#1-the-entry-level-it-path) to networking, security or cloud | Like fixing things and helping people, and want a route into tech that isn't mainly coding |
| [Learn 3D Modeling](https://github.com/ImmuneMoon/Learn-3D-Modeling) | Build, texture and animate models in Blender, which is free, starting with [your first hour](https://github.com/ImmuneMoon/Learn-3D-Modeling#6-your-first-hour-model-a-mug) | Like the visual side, and want to make assets for games, animation, 3D on the web, or printing |
| [3D Printing: Getting Started](https://github.com/ImmuneMoon/3D-Printing-Getting-Started) | Print, tune and fix real objects, with a [ladder of first projects](https://github.com/ImmuneMoon/3D-Printing-Getting-Started#14-a-first-projects-ladder) | Want to make physical things, such as replacement parts, gadgets and props |

### 9.4 Tool guides

Short, practical guides to the tools you'll meet along the way:

* [CLI Cheat Sheet](https://github.com/ImmuneMoon/CLI-Cheat-Sheet) - Terminal commands, Git, and installing Node, Python, Git and VS Code with winget.
* [Python and Node Tool Environments](https://github.com/ImmuneMoon/Python-and-Node-Tool-Environments) - Installing Python and Node.js, and giving each project its own environment.
* [Safer Package Installs with npm and pip](https://github.com/ImmuneMoon/Safer-Package-Installs-npm-and-pip) - Avoiding malicious packages when you install libraries.
* [Publishing to GitHub with gh](https://github.com/ImmuneMoon/Publishing-to-GitHub-with-gh) - Putting a project on GitHub from the terminal, and keeping secrets out of it.
* [Packaging Windows Apps with PyInstaller and Inno Setup](https://github.com/ImmuneMoon/Packaging-Windows-Apps-PyInstaller-Inno-Setup) - Turning a Python app into a `.exe` and an installer.
* [Batch Image and 3D Tools: GIMP, Blender and Pillow](https://github.com/ImmuneMoon/Batch-Image-and-3D-Tools-GIMP-Blender-Pillow) - Resizing and converting whole folders of images and models with scripts.
* [PDF and Document Tools](https://github.com/ImmuneMoon/PDF-and-Document-Tools) - Reading, searching and making PDFs and Word documents from code.
* [Transcribing Videos with yt-dlp and faster-whisper](https://github.com/ImmuneMoon/Transcribing-Videos-with-yt-dlp-and-faster-whisper) - Turning videos into searchable text on your own PC.

---

## 10. FAQ

**Do I need a degree?**
Not always. The US Bureau of Labor Statistics lists a bachelor's degree as typical, but says education requirements for web developers "range from a high school diploma to a bachelor's degree". It also notes that developers may not need specific credentials if they can show their abilities through work or projects. That's what the portfolio in Step 5 is for.

**Do I need to be good at math?**
For most web development, no. Basic arithmetic and clear logical thinking go a long way. Some areas, such as graphics, data work and algorithms, use more. [Computer Science Fundamentals](https://github.com/ImmuneMoon/Computer-Science-Fundamentals#7-math-for-programmers) covers the math worth knowing.

**Do I need to learn computer science first?**
No. You can build and deploy real web projects first, and pick up data structures, algorithms and Big O as you need them. [Computer Science Fundamentals, Section 1.2](https://github.com/ImmuneMoon/Computer-Science-Fundamentals#12-when-web-developers-can-wait) suggests what to learn when.

**Which language should I learn first?**
HTML and CSS, then JavaScript. Every web path uses them, and they show results right away. For a back end focus, Python is a friendly next language.

**How long will it take?**
It varies a lot with your time and background. For scale, freeCodeCamp estimates about 1,800 hours for its full stack curriculum. Steady progress over months matters more than speed.

**Should I use AI coding assistants?**
Most developers do: 84% of respondents to Stack Overflow's 2025 survey use AI tools or plan to. But 46% said they distrust the accuracy of AI output, compared with 33% who trust it. While you're learning, write code yourself first, so you understand it well enough to spot when an AI suggestion is wrong. Never paste passwords, keys or private data into one. [Open Source and Developer Communities](https://github.com/ImmuneMoon/Open-Source-and-Developer-Communities) covers using them responsibly.

**Where do I ask for help?**
Your curriculum's community first (The Odin Project and freeCodeCamp both have one), then the communities listed in [Open Source and Developer Communities](https://github.com/ImmuneMoon/Open-Source-and-Developer-Communities). Say what you tried, what you expected, and what happened, and include the error message.

---

## 11. Glossary

| Term | Meaning |
|---|---|
| **API** | A defined way for programs to talk to each other. Web APIs usually take requests over HTTP and answer with JSON. |
| **Accessibility** | Building sites everyone can use, including people using screen readers, keyboards only, or zoom. |
| **Back end** | Code that runs on the server: logic, data and security. |
| **Browser** | The app that loads and shows web pages, such as Chrome, Firefox, Edge or Safari. |
| **CSS** | The language that styles a page: colors, fonts, spacing and layout. |
| **Database** | Organized, stored data an app can query and update. |
| **Deploy** | Put a version of your site or app online. |
| **DevTools** | The developer tools built into browsers, for inspecting and debugging pages. |
| **DNS** | The system that turns domain names into server addresses. |
| **Domain** | A website's name, such as `example.com`. |
| **Framework** | A ready-made structure you build your app inside, such as Next.js, Django or Express. |
| **Front end** | Code that runs in the browser: HTML, CSS and JavaScript. |
| **Full stack** | Working on both the front end and the back end. |
| **Git** | Version control software that tracks changes to your code. |
| **GitHub** | A website that hosts Git repositories, for sharing and collaborating. |
| **Hosting** | A server or service that keeps your site online. |
| **HTML** | The language that structures a page's content: headings, paragraphs, links, images and forms. |
| **HTTP and HTTPS** | The rules browsers and servers use to send requests and responses. HTTPS is the encrypted version. |
| **IDE** | Integrated development environment: an editor with built-in tools for running and debugging code. |
| **JavaScript** | The programming language of the browser. With Node.js, it also runs on servers. |
| **JSON** | A plain-text format for sending data, which looks like `{"name": "Ada"}`. |
| **Library** | Reusable code you call when you need it, such as React. |
| **Repository (repo)** | A project folder tracked by Git, including its full history. |
| **Responsive design** | Layouts that adapt to any screen size, from phones to wide monitors. |
| **REST** | A common style for designing web APIs around URLs and HTTP methods such as GET and POST. |
| **Runtime** | The program that runs your code, such as Node.js for JavaScript outside the browser. |
| **Server** | A computer or program that answers requests from clients. |
| **SQL** | The language for querying relational databases. |
| **Static site** | A site made of fixed files, with no back end code running on each request. |

---

## 12. Sources

Checked in November 2026.

**Video credited**
- ForrestKnight, [Everything You NEED to Know About WEB APP Architecture](https://youtu.be/sDlCSIDwpDs) (June 2022)
- Coder Coder, [Learn web development as an absolute beginner](https://www.youtube.com/watch?v=ysEN5RaKOlA) (November 2019)
- devsmak (James Cross), [Learn Web Development FREE and Actually Get Hired](https://youtu.be/14-xBLhZ4AE) (May 2022)
- Andy Harris, [How To Think Like A Programmer](https://www.youtube.com/watch?v=azcrPFhaY9k), uploaded by Coding Tech (October 2018)
- Bitfumes (Sarthaksavvy), [What is a Framework and Why use Frameworks](https://youtu.be/1a5VKUc0AUc) (September 2017)
- CS50, [CS50 Lectures 2021](https://youtube.com/playlist?list=PLhQjrBD2T383f9scHRNYJkior2VvYjpSL)
- Visual Studio Code, [Balance Out](https://youtube.com/shorts/NwqhFb4B5LU), [To the left, to the left](https://youtube.com/shorts/DEUud_c9GRE) and [Terminal editors](https://www.youtube.com/shorts/36g1FLPcg6s)
- Web Dev Simplified, [5 Must Know VSCode Shortcuts](https://youtube.com/shorts/C926N9zMJkU)

**How the web works**
- MDN, [How the web works](https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Web_standards/How_the_web_works)
- MDN, [How browsers load websites](https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Web_standards/How_browsers_load_websites)
- Martin Fowler, [MonolithFirst](https://martinfowler.com/bliki/MonolithFirst.html) (June 2015)
- MDN glossary: [API](https://developer.mozilla.org/en-US/docs/Glossary/API), [REST](https://developer.mozilla.org/en-US/docs/Glossary/REST), [JSON](https://developer.mozilla.org/en-US/docs/Glossary/JSON), [HTTP](https://developer.mozilla.org/en-US/docs/Glossary/HTTP), [DNS](https://developer.mozilla.org/en-US/docs/Glossary/DNS), [SQL](https://developer.mozilla.org/en-US/docs/Glossary/SQL)

**Curricula**
- The Odin Project, [home](https://www.theodinproject.com/), [paths](https://www.theodinproject.com/paths) and [Foundations course](https://www.theodinproject.com/paths/foundations/courses/foundations)
- freeCodeCamp, [Learn](https://www.freecodecamp.org/learn), [Introducing freeCodeCamp checkpoint certifications](https://www.freecodecamp.org/news/introducing-freecodecamp-checkpoint-certifications/) (September 2025)
- MDN, [Learn web development](https://developer.mozilla.org/en-US/docs/Learn_web_development) and [Research and learning](https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Soft_skills/Research_and_learning)
- CS50, [CS50W](https://cs50.harvard.edu/web/), [CS50W certificate](https://cs50.harvard.edu/web/certificate/) and [CS50x](https://cs50.harvard.edu/x/)
- edX, [CS50's Web Programming with Python and JavaScript](https://www.edx.org/course/cs50s-web-programming-with-python-and-javascript-web) and [Computer Science for Web Programming Professional Certificate](https://www.edx.org/certificates/professional-certificate/harvardx-computer-science-for-web-programming)
- roadmap.sh, [roadmaps](https://roadmap.sh/) and [projects](https://roadmap.sh/projects)

**Other courses and references**
- [Codecademy pricing](https://www.codecademy.com/pricing), [Khan Academy](https://www.khanacademy.org/computing/computer-programming), [web.dev Learn](https://web.dev/learn), [W3Schools](https://www.w3schools.com/), [Class Central](https://www.classcentral.com/), [Educative](https://www.educative.io/explore/free), [Sololearn](https://www.sololearn.com/), [Mimo](https://mimo.org/)
- freeCodeCamp, [860+ Free Online Programming & Computer Science Courses](https://www.freecodecamp.org/news/free-online-programming-cs-courses/) (January 2023)

**Tools**
- [Visual Studio Code](https://code.visualstudio.com/) and its [Code Navigation](https://code.visualstudio.com/docs/editing/editingevolved) docs (Go Back shortcuts), [Neovim](https://neovim.io/), [Kate](https://kate-editor.org/), [Sublime Text licensing](https://www.sublimehq.com/store/text)
- GitHub blog, [Sunsetting Atom](https://github.blog/news-insights/product-news/sunsetting-atom/)
- Chrome for Developers, [Open Chrome DevTools](https://developer.chrome.com/docs/devtools/open)
- Firefox, [DevTools user docs](https://firefox-source-docs.mozilla.org/devtools-user/) and [Responsive Design Mode](https://firefox-source-docs.mozilla.org/devtools-user/responsive_design_mode/)
- [Git downloads](https://git-scm.com/downloads), GitHub Docs [Hello World](https://docs.github.com/en/get-started/start-your-journey/hello-world)
- React, [Build a React app from Scratch](https://react.dev/learn/build-a-react-app-from-scratch) (Vite, Parcel and Rsbuild)
- [CodePen](https://codepen.io/), [StackBlitz](https://stackblitz.com/), [CodeSandbox](https://codesandbox.io/), [Replit pricing](https://replit.com/pricing)

**Facts and figures**
- Stack Overflow, [2025 Developer Survey](https://survey.stackoverflow.co/2025/) (AI tools and trust) and [Technology](https://survey.stackoverflow.co/2025/technology) (editors)
- US Bureau of Labor Statistics, [Web Developers and Digital Designers](https://www.bls.gov/ooh/computer-and-information-technology/web-developers.htm)

<!-- guide:end -->

## ☕ Support the Project

If you find this project helpful and want to support further development by Fulllion Creative Works, consider leaving a tip!

* [Donate via PayPal](https://www.paypal.com/donate/?hosted_button_id=LCDZX75HR4CLC)
* [Support on Ko-fi](https://ko-fi.com/fulllion)

---
© 2026 Fulllion Creative Works. All rights reserved.
