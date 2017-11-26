## The Envision Site

The UBC Envision website is hosted on GitHub Pages. We use a static site generator called [Jekyll](https://jekyllrb.com/) to build our site. You don't need to know how Jekyll works right now, but if you're interested in learning more, check out their site.

You do, however, need to know what Markdown is. Instead of pure HTML, we use Markdown to write content, and Jekyll builds HTML files from it \(hence the generator part in the name static site **generator**\).

* **Please read this article** to learn more about Markdown: [https://www.futurehosting.com/blog/you-should-use-markdown-for-online-writing-heres-why/](https://www.futurehosting.com/blog/you-should-use-markdown-for-online-writing-heres-why/)

## Forking and Pull Requests

The terms _forking_ and _pull requests_ were briefly mentioned in Chapter 4 in the Git tutorial. In this section, we'll get you to explore and practice those concepts.

Code hosted on public repositories on GitHub are open source. The best part about this is that anyone can view the code and make modifications and improvements to it. The code that runs the UBC Envision site is also open source. To make modifications to it, you'll first have to create a **fork **to copy the code into your own GitHub account, make your modifications there and then finally **create a pull request** to merge the code back into the original repository.

* Follow this Digital Ocean tutorial to learn how to create a pull request: [https://www.digitalocean.com/community/tutorials/how-to-create-a-pull-request-on-github](https://www.digitalocean.com/community/tutorials/how-to-create-a-pull-request-on-github)

## The Challenge

Now that you know how to create a pull request, fork the UBC Envision website repo: [https://github.com/UBCEnvision/UBCEnvision.github.io](https://github.com/UBCEnvision/UBCEnvision.github.io)

The challenge here is to add yourself to our team page:

* You'll need to upload a photo of yourself to **/assets/images/members/**
* The photo must be less than 500kb and square-shaped
* Your biography should go into **/\_members **as a markdown .md file with your Full Name as the filename.
* Take a look at [this file](https://github.com/UBCEnvision/UBCEnvision.github.io/blob/master/_members/Siang.md) in the folder as a guide and fill out the fields accordingly. The following values should be used for these variables:

| Field | Value |
| :--- | :--- |
| layout | member |
| weight | 900 |
| status | new |
| title | New Recruit |
| email | **Use your UBC alumni email. Please no gmail/hotmail/yahoo etc. address.** |

### Final Steps

When you're done, commit your changes, push it back to GitHub and create a Pull Request. Your changes will be tested against a series of automated tests to ensure that you've followed the instructions and didn't break anything on the site. To see what tests we run, check out the** /spec/** folder.

If the build fails, close your pull request, look at the error message to figure out what's wrong and try again!

If everything looks good, we'll merge your pull request. We'll be in touch through email to set up a welcome meeting and talk about next steps!







