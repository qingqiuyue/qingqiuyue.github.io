---
title: 快速开始
layout: single
sidebar:
  nav: docs
permalink: "/docs/quick-start-guide/"
excerpt: How to quickly install and setup Minimal Mistakes for use with GitHub Pages.
modified: '2016-04-13 15:54:02 -0400'
redirect_from:
- "/theme-setup/"
---

{% include base_path %}

成长旅途中每每感触与思索都可以来[论坛](https://discourse.qingqiuyue.com/)瞅瞅，思想是[清秋月](https://qingqiuyue.com/)最崇高的信仰。我们只是寻道旅途中一处风景，道友不妨领略一番.

## 从成长说起

儿时的记忆, 恍惚间已忘记许多。萦绕心间的，是 **姥姥和老爷的陪伴**，是 **哥哥和姐姐的照顾**，是**父辈人的关爱**，是**小伙伴的友谊**… 

<figure>
  <img src="{{ base_path }}/images/mm-theme-fork-repo.png" alt="fork Minimal Mistakes">
</figure>

**Note:** Your Jekyll site should be viewable immediately at <http://USERNAME.github.io>. If it's not, you can force a rebuild by **Customizing Your Site** (see below for more details).
{: .notice--warning}

If you're hosting several Jekyll based sites under the same GitHub username you will have to use Project Pages instead of User Pages. Essentially you rename the repo to something other than **USERNAME.github.io** and create a `gh-pages` branch off of `master`. For more details on how to set things up check [GitHub's documentation](https://help.github.com/articles/user-organization-and-project-pages/).

<figure>
  <img src="{{ base_path }}/images/mm-gh-pages.gif" alt="creating a new branch on GitHub">
</figure>

**ProTip:** Be sure to [delete](https://github.com/blog/1377-create-and-delete-branches) the `gh-pages` branch if you forked Minimal Mistakes. This branch contains the documentation and demo site for the theme and you probably don't want that showing up in your repo.
{: .notice--info}

## 于思考中接续

Open up `_config.yml` found in the root of the repo and edit anything under **Site Settings**. For a full explanation of every setting be sure to read the [**Configuration**]({{ base_path }}/docs/configuration/) section, but for now let's just change the site's title.

<figure>
  <img src="{{ base_path }}/images/mm-github-edit-config.gif" alt="editing _config.yml file">
  <figcaption>Edit text files without leaving GitHub.com</figcaption>
</figure>

Committing a change to `_config.yml` (or any file in your repository) will force GitHub Pages to rebuild your site with Jekyll. It should then be viewable a few seconds later at `https://USERNAME.github.io`.

---

Congratulations! You've successfully forked the theme and are up an running with GitHub Pages. Now you're ready to add content and customize the site further.