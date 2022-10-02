---
title: Jekyll + GitHub Pages Tutorial
date: 2022-10-01 17:58:00 +0100
categories: [tutorial]
tags: [github, jekyll]
---

# Welcome to my first tutorial!

First off, I want to thank Techno Tim on YouTube for his amazing video tutorial. It's actually thanks to this video that I was able to get this site up and running this fast.
<iframe width="560" height="315" src="https://www.youtube.com/embed/F8iOU1ci19Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


Now that's out of the way let me help you through the entire installation process.

## First step : Ruby & Jekyll

Before we can start playing with Jekyll and creating our own web page, we need to install some prerequisites.
The easiest way to do this is to use the [RubyInstaller](https://rubyinstaller.org/).
Once you're downloaded the installer, launch it and use all the default options.

After having installed everything you'll be greeted by this screen :
![RubyInstaller2](/assets/screnshots//RubyInstaller2.png)

Make sure to press "3" for "MSYS2 and MINGW development toolchain" and then "ENTER".

Once this installation process is done, open a new command prompt and run the command:
```sh
gem install jekyll bundler
```

Finally, to check this whole process went without a hitch, type in :
```sh
jekyll -v
```

This checks what version of Jekyll you have currently installed.

## Second step : Chirpy Theme

Now that we have all the necessary tools installed to create our website, it's time to actually create it! I'll be using the [Chirpy](https://github.com/cotes2020/chirpy-starter) theme. This theme is clean, minimal, has support for dark mode, good SEO and a built in search function. 
From the GitHub repository linked above, choose the "Use this template" button:

![ChirpyChooseTemplate](/assets/screnshots//ChirpyChooseTemplate.png)

On the following page, you'll be askedd to create a new repository. Make sure not to forget to exchange"yourusernamehere" for your own username ;) 

![CreateNewRepository](/assets/screnshots/ChooseNewRepository.png)

Now that you've created your repository on GitHub, it's time to clone it to your local machine by first copying the link to your online repository: 

![CloneRepository](/assets/screnshots/CloneRepository.png)

Once you have your link, open a GitBash command prompt and type in:
```sh
git clone yourrepositorylinkhere
```

Now that you have your repository on your local machine, it's time to add some dependencies