[EN](./index-en.md) | [ZH](./index.md)


# CTF Wiki



[![Build Status](https://travis-ci.org/ctf-wiki/ctf-wiki.svg?branch=master)](https://travis-ci.org/ctf-wiki/ctf-wiki)

[![Requirements Status](https://requires.io/github/ctf-wiki/ctf-wiki/requirements.svg?branch=master)](https://requires.io/github/ctf-wiki/ctf-wiki/requirements/?branch=master)

[![Slack](https://img.shields.io/badge/slack-join%20chat-brightgreen.svg)](https://join.slack.com/t/ctf-wiki/shared_invite/enQtNTkwNDg5NDUzNzAzLWExOTRhZTE0ZTMzYjVlNDk5OGI3ZDA1NmQyZjE4NWRlMGU3NjEwM2Y2ZTliMTg4Njg1MjliNWRhNTk2ZmY0NmI)



Welcome to the **CTF Wiki**.

*A NOTE TO THE READER*: CTF Wiki has been translated into English. Each page in CTF
Wiki is available in both English and Chinese now. Simply click the button at the 
top of the website that looks like the link below to view different language version.

*读者注意*：CTF Wiki最近转为双语，因此CTF中的每一页都是如此
Wiki现在将以英文和中文提供。只需点击广告按钮即可
每个页面的顶部看起来像这样:
[EN](./index-en.md) | [ZH](./index.md)


**CTF** (Capture The Flag) is originated in the 1996 **DEFCON** Global Hacking Conference, a competitive game among cybersecurity enthusiasts.


The **CTF** competition covers a wide range of fields and has a complex content. At the same time, the development of security technology is getting faster and faster, and the difficulty of **CTF** is getting higher and higher, the threshold for beginners is getting higher and higher. Most of the online information is scattered and trivial. Beginners often don&#39;t know how to systematically learn the knowledge of **CTF** related fields, often taking a lot of time and suffering.


In order to make the **CTF** players life of entering this field easier, in October 2016, **CTF Wiki** had the first commit on Github. As content continues to improve, the **CTF Wiki** has been loved by more and more security enthusiasts, and there are also a lot of friends who have never met participating in this project.


As a free site, with the recent years' **CTF** challenges, **CTF Wiki** introduces the knowledge and techniques in all directions of **CTF** to make it easier for beginners to learn how to getting started at playing **CTF**.


At present, **CTF Wiki** mainly contains the basic knowledge of **CTF** in all major directions, and is working hard to improve the following contents.


- Advanced knowledge in the CTF competition
- Quality topics in the CTF competition


For more information on the above, see the [Projects] (https://github.com/ctf-wiki/ctf-wiki/projects) of the CTF Wiki for a detailed list of what is being done and what to do.


Of course, the **CTF Wiki** is based on **CTF**, but it is not limited to **CTF**. In the future, **CTF Wiki** will


- Introducing tools in security research area
- More integration with security area


In addition, given the following two points


- Technology should be shared in an open manner.
- Security offensive and defensive technologies are always up to date, and old technologies may fail at any time in the face of new technologies.


**CTF Wiki** will never publish books.


Finally, the **CTF Wiki** originates from the community, as an independent organization**, advocates **freedom of knowledge**, will never be commercialized in the future, and will always remain **independent and freedom**.


## How to build？



This document is currently deployed at [https://ctf-wiki.github.io/ctf-wiki/] (https://ctf-wiki.github) using [mkdocs](https://github.com/mkdocs/mkdocs) .io/ctf-wiki/). Of course, it can also be deployed locally, as follows:


```shell

# 1. clone

git clone git@github.com: ctf-wiki / ctf-wiki.git
# 2. requirements

pip install -r requirements.txt

# generate static file in site/

mkdocs build

# deploy at http://127.0.0.1:8000

mkdocs serve

```



**mkdocs Locally deployed websites are dynamically updated, i.e. when you modify and save the md file, refreshing the page and the contents will be dynamically updated. **




Just want to browse locally, don&#39;t want to modify the document? Try Docker!
```

docker run -d --name=ctf-wiki -p 4100:80 ctfwiki/ctf-wiki

```

You can then access the CTF Wiki by visiting [http://localhost:4100/] (http://localhost:4100/) in your browser.


## How to practice？



First, you can learn some basic security knowledge by reading online.


Second, the CTF Wiki has two accompany projects.


- The challenges mentioned in the CTF Wiki are in the [ctf-challenges] (https://github.com/ctf-wiki/ctf-challenges) repository, so look for them according to the corresponding category.
- Note: There are still some challenges that are currently being migrated. . . (misc, web)
- The tools involved in the CTF Wiki are constantly being added to the [ctf-tools](https://github.com/ctf-wiki/ctf-tools) repository.


## How to make CTF Wiki Better？



It is welcomed to write content for the wiki and share your knowledge with everybody else. For details, please refer to [CONTRIBUTING] (https://github.com/ctf-wiki/ctf-wiki/wiki/Contributing-Guide).


**Before you decide to contribute anything, please be sure to finish reading that document**. We look forward to your joining.


Thanks give to the contributors who dedicated to make CTF Wiki better and better.


<a href="https://github.com/ctf-wiki/ctf-wiki/graphs/contributors"><img src="https://opencollective.com/ctf-wiki/contributors.svg?width=890&button=false" /></a>



## What can you get?



- Ability to learn new things quickly
- A different way of thinking
- A heart that is happy to solve problems
- Some interesting security techniques
- A rememebered hard-working time


Before reading the wiki, we hope to give you some advice:


- Read the essay [Wisdom of Question] (http://www.jianshu.com/p/60dd8e9cd12f)
- Making good use of Google search can help you better improve yourself
- Master at least one programming language, such as Python
- Hands-on practice is more useful than anything
- Keep curiosity and desire for technology and stick to it


> The world is big, the Internet makes the world smaller. Real hackers should think and create. Whether it is destroying or creating, remembering, the future, the main line is creation. ——by cosine


The circle of security is small and the ocean of security is deep. Instead of error testing on the way of learning security, try getting started at just **CTF Wiki**!


## Copyleft
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License Agreement" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a> <br /> This work is <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">licensed under</a> a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-Noncommercial-Share Alike 4.0 International License Agreement</a> .






## Material color palette Color theme


### Primary colors Main colors


> default `white`


Click on the color block to change the main color of the theme.


<button data-md-color-primary="red">Red</button>

<button data-md-color-primary="pink">Pink</button>

<button data-md-color-primary="purple">Purple</button>

<button data-md-color-primary="deep-purple">Deep Purple</button>

<button data-md-color-primary="indigo">Indigo</button>

<button data-md-color-primary="blue">Blue</button>

<button data-md-color-primary="light-blue">Light Blue</button>

<button data-md-color-primary="cyan">Cyan</button>

<button data-md-color-primary="teal">Teal</button>

<button data-md-color-primary="green">Green</button>

<button data-md-color-primary="light-green">Light Green</button>

<button data-md-color-primary="lime">Lime</button>
<button data-md-color-primary="yellow">Yellow</button>

<button data-md-color-primary="amber">Amber</button>

<button data-md-color-primary="orange">Orange</button>

<button data-md-color-primary="deep-orange">Deep Orange</button>

<button data-md-color-primary="brown">Brown</button>

<button data-md-color-primary="grey">Grey</button>

<button data-md-color-primary="blue-grey">Blue Grey</button>

<button data-md-color-primary="white">White</button>



<script>

  var buttons = document.querySelectorAll("button[data-md-color-primary]");

  Array.prototype.forEach.call(buttons, function(button) {

    button.addEventListener("click", function() {

      document.body.dataset.mdColorPrimary = this.dataset.mdColorPrimary;

      localStorage.setItem("data-md-color-primary",this.dataset.mdColorPrimary);

    })

  })

</script>



### Accent colors Auxiliary color


> Default `red`


Click on the color block to change the auxiliary color of the theme.


<button data-md-color-accent="red">Red</button>

<button data-md-color-accent="pink">Pink</button>

<button data-md-color-accent="purple">Purple</button>

<button data-md-color-accent="deep-purple">Deep Purple</button>

<button data-md-color-accent="indigo">Indigo</button>

<button data-md-color-accent="blue">Blue</button>

<button data-md-color-accent="light-blue">Light Blue</button>

<button data-md-color-accent="cyan">Cyan</button>

<button data-md-color-accent="teal">Teal</button>

<button data-md-color-accent="green">Green</button>

<button data-md-color-accent="light-green">Light Green</button>

<button data-md-color-accent="lime">Lime</button>

<button data-md-color-accent="yellow">Yellow</button>

<button data-md-color-accent="amber">Amber</button>

<button data-md-color-accent="orange">Orange</button>

<button data-md-color-accent="deep-orange">Deep Orange</button>



<script>

  var buttons = document.querySelectorAll("button[data-md-color-accent]");

  Array.prototype.forEach.call(buttons, function(button) {

    button.addEventListener("click", function() {

      document.body.dataset.mdColorAccent = this.dataset.mdColorAccent;

      localStorage.setItem("data-md-color-accent",this.dataset.mdColorAccent);

    })

  })

</script>
