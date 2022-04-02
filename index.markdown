---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
## Michele Costabile
Hello, welcome to my home on Github. I am a seasoned developer. I started in C in 1982 working on the Olivetti line of unix servers. We made the hardware and built the drivers and the kernel starting from BSD Unis. My contributions include rewriting and rehosting the runtime support system for a COBOL compiler. I created also a few device drivers and an extended kernel debugger. A toy project was a tool for sharing a tty between a local user and a remote maintenance technician.

I was part of Italia Online, the first Internet access provider to open in Italy in 1995. since the beginning. There, I created a custom mail engine in C++, which served 50.000 customers. The front end of the engine, understood SMTP and POP3, the back end stored messages and attachments on a database server. Not a good idea, not my fault, not my advice. The service was rightfully abandoned when it got up to 100.000 users.

This particular project, and its mainteneance, convinced me to embrace Java since [its first announcement in 1995](https://www.oracle.com/java/moved-by-java/timeline/). C++ was much worse at the time, but I still think that you get first to the end of a project in Java, or plain C. As of 2021, I would rule out C for Go or Rust, but with a grain of salt.

Well, this is just the beginning. If you are interested in the latest development, please check my [LinkedIn profile](https://www.linkedin.com/in/cosmic)

I have a couple of projects here on Github: Reactions and aerogel.

## Reactions
Reactions is a simple web project, with the mission to be: the minimum configuration with the shortest configuration files and dependencies, that will make possibile to create project using ES6 syntax and a build system based on Webpack.

I created it after perusing a few tutorials and starter kits, which had too many moving parts or had architectural choices built in, forcing one to figure out how to trim the fat and remove the unwanted.

It served as the base for the next project.

## aerogel
aerogel is a very light and solid material, so it makes a good name for a framework based on Google's Material Design Lite collection of styles and Reactions.

This project was meant to be light and simple, making the most of the new ES6 syntax to create a useful set of components speeding up the creation of web applications and Cordova apps. In a way, it was inspired by React.js, but it was based on existing technologies, the ones I already was able to be productive with.

It made its way into at least three working apps based on Cordova. It is not meant as a tool for writing web pages, since templates and data are all in JavaScript, but it served well to create apps.

As of today, I would go for progressive web apps, Sinnce html has grown and operating system support is much better.

## Articoli

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>