---
layout: page
title: Setup
---

<div id="git"> {% comment %} Start of 'Git' section. {% endcomment %}
  <h3>Git</h3>
  <p>
    Git is a version control system that lets you track who made changes
    to what when and has options for easily updating a shared or public
    version of your code
    on <a href="https://github.com/">github.com</a>. You will need a
    <a href="https://help.github.com/articles/supported-browsers/">supported
    web browser</a>.
  </p>
  <p>
    You will need an account at <a href="https://github.com/">github.com</a>
    for parts of the Git lesson. Basic GitHub accounts are free. We encourage
    you to create a GitHub account if you don't have one already.
    Please consider what personal information you'd like to reveal. For
    example, you may want to review these
    <a href="https://help.github.com/articles/keeping-your-email-address-private/">instructions
    for keeping your email address private</a> provided at GitHub.
  </p>

  <div class="row">
    <div class="col-md-4">
      <h4 id="git-windows">Windows</h4>
      <p>
        Git should be installed on your computer as part of your Bash
        install (described above).
      </p>
    </div>
    <div class="col-md-4">
      <h4 id="git-macosx">macOS</h4>
      <p>
        Please open the Terminal app, type <code>git --version</code> and press
        <kbd>Enter</kbd>/<kbd>Return</kbd>. If it's not installed already,
        follow the instructions to <code>Install</code> the "command line
        developer tools". <strong>Don't click</strong> "Get Xcode", because that will
        take too long and is not necessary for our Git lesson.
        After installing these tools, there won't be anything in your <code>/Applications</code>
        folder, as they and Git are command line programs.
        <strong>For older versions of OS X (10.5-10.8)</strong> use the
        most recent available installer labelled "snow-leopard"
        <a href="http://sourceforge.net/projects/git-osx-installer/files/">available here</a>.
        Because this installer is not signed by the developer, you may have to
        right click (control click) on the .pkg file, click Open, and click
        Open in the pop-up dialog. You can watch
        <a href="https://www.youtube.com/watch?v=9LQhwETCdwY ">a video tutorial about this case</a>.
      </p>
    </div>
    <div class="col-md-4">
      <h4 id="git-linux">Linux</h4>
      <p>
        If Git is not already available on your machine you can try to
        install it via your distro's package manager. For Debian/Ubuntu run
        <code>sudo apt-get install git</code> and for Fedora run
        <code>sudo dnf install git</code>.
      </p>
    </div>
  </div>
</div> {% comment %} End of 'Git' section. {% endcomment %}

In this lesson we'll do our work in the `Desktop` folder so make sure you change your working directory to it with:

~~~
$ cd
$ cd Desktop
~~~
{: .language-bash}

[workshop-setup]: https://carpentries.github.io/workshop-template/#git
