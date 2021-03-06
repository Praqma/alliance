<!--

 To include this markdown in your reveal add the following section:

  <section data-markdown="name-of-your-markdown.md"
    data-separator="^>>>>NEWSECTION$"
    data-separator-vertical="^>>>>NEWSLIDE$"
    data-separator-notes="^Note:$">
  </section>

-->

# The Phlow

>>>>NEWSLIDE

## What is the problem

Keeping track of work coming in - and getting done<br/><!-- .element class="fragment" -->

Too much friction in the systems<br/><!-- .element class="fragment" -->

Branching strategies<br/><!-- .element class="fragment" -->

Release strategies<br/><!-- .element class="fragment" -->

>>>>NEWSLIDE

## As a software developer

**I want**<br> all features that support the process to be available from my IDE or my terminal

**So that**<br> I don't have to go to many different tools, to organize and manage my work flow

>>>>NEWSLIDE

### Install
```shell
brew tap praqma/praqma-tap
brew install git-phlow
git phlow auth
git phlow mkalias
```

<div>
### Use
```shell
ghi open -m "Some new issues - I'd like to work on"
git workon 1
git wrapup --hard
git deliver --local
```
</div><!-- .element class="fragment" -->

<div>
workon - wrapup -deliver - workon - wrapup - deliver - workon - wrapup - deliver
</div><!-- .element class="fragment" -->


>>>>NEWSLIDE

## As a product owner

**I want**<br> every single commit to happen for a documented reason, and that reason should be tied to the the commit

**So that**<br> When I need an overview I can just browse the commit history

>>>>NEWSLIDE

### Nice!

[![commits](res/commits.png)<!-- .element class="plain max" -->](https://github.com/Praqma/praqma.com/commits/gh-pages?after=4c2b41b0ed7e8233bd0e8d097dfdca20e46c6f50+245)<!-- .element target="_blank" -->

>>>>NEWSECTION


## Solution?

![CoDe factory floor](../shared/img/code-story.bare.png)<!-- .element: class="plain max" -->

<!-- .slide: data-transition="slide-in none" -->

>>>>NEWSLIDE

<!-- .slide: data-transition="none slide-out" -->

## Solution?

![CoDe factory floor](res/code-story.ci.bare.png)<!-- .element: class="plain max" -->


>>>>NEWSLIDE

## What is the solution

Make it easy<br/><!-- .element class="fragment" -->

Tie tasks to commits<br/><!--  .element class="fragment"  -->

Release train<br/><!-- .element class="fragment" -->

Milestones and office hours<br/><!-- .element class="fragment" -->

Automate all the things<br/><!-- .element class="fragment" -->

Any CI (Jenkins, Travis, Concourse)<br/><!-- .element class="fragment" -->


>>>>NEWSECTION

## Community

Repo

Issues

Concourse

>>>>NEWSLIDE

## Demo (10 min)

Outline (Issues, repo, Waffle)

Demo

>>>>NEWSLIDE

## Roadmap

- Code Café
- Community
- Features
    - Jira support
    - Windows
    - Apt-get installer
- More CI support
