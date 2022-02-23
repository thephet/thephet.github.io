---
title: "New website"
excerpt: "I have finally finished finished - this - my new research website. I decided to use Jekyll and host it on Github after considering different options."
---

One of the first things every researcher needs is a personal research website, and you are reading mines now. I hope it will eventually evolve into my research group website.
I should have done it before, years ago, probably when I started my PhD, but I really never considered it until I got my Fellowship.

When I decided that I wanted to make my own website, my first priority was to make it as simple as possible because I did not want to spend much time on it.
At the end of the day, as a science researcher, the content is more important than the looks. There are even big professors who still have their research websites in plain html without CSS or anything.
I actually considered doing that, a plain white HTML website, but I think that as a junior researcher I need something more flashy. Perhaps in the future when I am a established academic (I wish) I can do it, and go full plain HTML with white background and blue links.

Asking to different researchers how they did their website, I realized that there are 3 categories: 

* Those who directly copied and pasted the HTML from some other website, and they only replaced the content. *This was not really an option for me. Too wonky*
* Those who basically did the website starting from scratch, using some sort of framework like Django. *This was not an option for me. Too much work*
* Those who used an established CSM (content management system), like Drupal or Worpress. *This looked very promising*

The idea of using a CSM is that they provide you with very high level tools to build your own website, and mostly you just need to pick a theme that you like, and fill the gaps. The drawbacks of CSMs is that they are massive pieces of software if you just need a tiny website, and that because they are so big, if you need to change something, it will be potentially be a lot of work.
Among the popular CSMs I decided to focus on Wordpress, because it is the most famous one, and because my university runs a Wordpress server so that it was very easy to set-up a Wordpress website.
Also, one of the lecturers in the Chemistry department @ UoG, [Laia Vila-Nadal](http://www.chem.gla.ac.uk/wp/lvn-group/laia/), just made her own website using Wordpress, and as you can see in the link it looks very cool. So I thought: I can do that!
The first thing I did was to go around the Wordpress ecosystem, and I realized that most of the good themes are not free, in fact you need to pay something like $50, and as a very young academic, I have no money to spare on that.
Then I checked the free themes, and I really did not like any of them. Moreover, when I was trying to learn how Wordpress works, I also did not like it. It feel very cluttered, very on-rails. I thought I needed something a bit more flexible.

It was then that I remember an old workmate, Jonathan Grizou, and that he had a very good website, so I decided to check it to see what did he use. [You can see his website clicking here](https://jgrizou.com/).
He had just re-done his website, and I really liked how it looked. Plain, simple, sleek. I contacted him, and he told me that he used something called "Jekyll", and that if you use this, you can host it for free on Github.

Jekyll has been around for a while, but now it is getting very popular as Github is getting bigger and bigger.
Jekyll is a static website generator. This means that instead of generating the website on the server, as Wordpress would do, you need to generate first the website locally, and then you need upload the final HTMLs to the server. This means that the website is very light and it loads very quick, because there is nothing dynamically generated.
Something very good about Jekyll is that you can write the pages using Markdown. This is what you would use to write a Wikipedia page, or a Github project page. That's what I am doing to write this post, and it makes it very easy to generate content.

Once I decided to use Jekyll, the next step was to choose a theme, and I went for Minimal Mistakes, because it is the most popular one, and the most customizable. Once I arrived to this point, doing the actual website was fairly easy. And you are seeing the results now. I hope in the near future to tweak a bit its looks, but for now I mostly focused on filling it with content.
