# SmartCityToolkit
Link to site https://cippic-ca.github.io/SmartCityToolkit/

### Adding a new page to your site.
https://help.github.com/en/github/working-with-github-pages/adding-content-to-your-github-pages-site-using-jekyll
1. On GitHub, navigate to your site's repository.

2. Navigate to the publishing source for your site. For more information about publishing sources, see "About GitHub Pages."

3. In the root of your publishing source, create a new file for your page called PAGE-NAME.md, replacing PAGE-NAME with a meaningful filename for the page.

4. Add the following YAML frontmatter to the top of the file, replacing PAGE TITLE with the page's title and URL-PATH with a path you want for the page's URL. For example, if the base URL of your site is https://octocat.github.io and your URL-PATH is /about/contact/, your page will be located at https://octocat.github.io/about/contact.

layout: page
title: "PAGE TITLE"
permalink: /URL-PATH/

5. Below the frontmatter, add content for your page.

6. At the bottom of the page, type a short, meaningful commit message that describes the change you made to the file. You can attribute the commit to more than one author in the commit message. For more information, see "Creating a commit with multiple co-authors."

Commit message for your change

7. Below the commit message fields, click the email address drop-down menu and choose a Git author email address. Only verified email addresses appear in this drop-down menu. If you enabled email address privacy, then <username>@users.noreply.github.com is the default commit author email address. For more information, see "Setting your commit email address."

Choose commit email addresses

8. Below the commit message fields, decide whether to add your commit to the current branch or to a new branch. If your current branch is master, you should choose to create a new branch for your commit and then create a pull request. For more information, see "Creating a new pull request."

Commit branch options

9. Click Propose file change.

Propose file change button

### Using Markdown to create content on page. 
https://guides.github.com/features/mastering-markdown/
Markdown is a way to style text on the web. You control the display of the document; formatting words as bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown. Mostly, Markdown is just regular text with a few non-alphabetic characters thrown in, like # or *.

Syntax guide
Here’s an overview of Markdown syntax that you can use anywhere on GitHub.com or in your own text files.

Headers
# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag
Emphasis
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_
Lists
Unordered
* Item 1
* Item 2
  * Item 2a
  * Item 2b
Ordered
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
Images
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)
Links
http://github.com - automatic!
[GitHub](http://github.com)
Blockquotes
As Kanye West said:

> We're living the future so
> the present is our past.
Inline code
I think you should use an
`<addr>` element here instead.

Automatic linking for URLs
Any URL (like http://www.github.com/) will be automatically converted into a clickable link.