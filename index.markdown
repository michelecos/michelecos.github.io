---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
## Michele Costabile
Hello, welcome to my home on Github. I am a seasoned developer, who started in C in 1982 and had a part in the Olivetti line of unix servers. My contributions include a new runtime support system for a COBOL compiler and a few device drivers.

I was part of the opening of Italia Online, the first Internet access provider to open in Italy in 1995. I created a custom mail engine for them, which served 50.000 customers. I created the front end for the engine, speaking SMTP and POP3 at the ends of the conversation. The innards of the engine were based on a database server. Not a good idea, so the service was rightfully abandoned before getting up to 100.000 users.

And this is just the beginning. If you are interested in the latest development, please check my [LinkedIn profile](www.linkedin.com/in/cosmicwww.linkedin.com/in/cosmic)

I have a couple of projects here on Github: Reactions and aerogel.

## Reactions
Reactions is a simple web project, with the mission to be: the minimum configuration with the shortest configuration files and dependencies, that will make possibile to create project using ES6 syntax and a build system based on Webpack.

I created it after perusing a few tutorials and starter kits, which had too many moving parts or had architectural choices built in, forcing one to figure out how to trim the fat and remove the unwanted.

## aerogel
aerogel is a very light and solid material, so it makes a good name for a framework based on Google's Material Design Lite collection of styles and Reactions.

This project was meant to be light and simple, making the most of the new ES6 syntax to create a useful set of components speeding up the creation of web applications and Cordova apps. In a way, it was inspired by React.js, but it was based on existing technologies, the ones I already was able to be productive with.

## Articoli

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>