This examination is worth 1 credit (1hp) and will test the following objective:
- create web pages using html and css

### Deadline and submission
* Deadline: 12/9 2016 12.00
* Submit: Submit your assignment by doing a release on GitHub named "v1.0". In case of changes after a released version please use incremental version numbers, i.e. "v1.1", "v1.22 etc.

### Preparation
Make sure you have gone through the [getting stated guide](https://coursepress.lnu.se/kurs/introduction-to-web-programming/getting-started/) and have all the necessary tools installed and have done all registrations.

## Practical assignment
The idea of this practical assignment is that you will create a web site containing a couple of web pages. The first part is about structuring the site with HTML, in later part you will style your pages with CSS.

You are free to use tools like static site generators as [Jekyll](https://jekyllrb.com/) and CSS Preprocessors like [Sass](http://sass-lang.com/) if you want.

## Part 1 - HTML and structure
In this part we are going to start working with HTML and structure our web site

The web site should at least contain one landing page (start page) and three sub pages. You should be able to click around the site trough a menu that is always present on every page. See image 1.1 below.

The minimum subpages should be:

* About- This page should contain some text about your self (if you want - a fictional person). This page should contain at least:
  * One ordered list (maybe list favorite movies, songs or things like that)
  * One unordered list
  * One image (relative URL to the image)
  * One playable video element (find one on the net and use an external URL)
* Blog/news - This page should contain at least two blog posts build by using [the "new" HTML5 tags](http://www.htmlgoodies.com/tutorials/html5/new-tags-in-html5.html)
* Contact - This page should contain a correct HTML form supporting HTTP POST method. For more information se image 1.2 below. There are no requirement that the form works since we haven't got a backend. We want you just to make it in HTML.

* All sub pages should be available through a menu that should be present in every page.
For more information see image 1.1 below.

![image 1.1](https://github.com/1dv525/syllabus/raw/master/examination/images/structure.png)

IMAGE 1.1 - Structure of the web site


![image 1.2](https://github.com/1dv525/syllabus/raw/master/examination/images/contactform.png)

IMAGE 1.2 - The contact form

### Think about
* Make sure you structure or files and folders in a good way. Maybe one folder for images, one for pages, one for stylesheets and so on...
* Think of the semantic meaning of the page elements and their order


## Part 2 - CSS
Now it is time to style your HTML pages. All CSS should be in separate files and be linked into the document. The web site layout should be like image 2.1, a simple three-column layout. You are free to choose colors and text font but you should put some time and love into the design.

![Image 2.1](https://github.com/1dv525/syllabus/raw/master/examination/images/layout.png)

IMAGE 2.1


### Some more requirements

* All pages should have a link to the CSS rules to get a consistent feeling.
* All pages content should be centered when you resize your web browser window.
* The links (at least in the menu) should have some hover effect (feel free to experiment)
* Use CSS to include at least one background image


## Part 3 - other stuff
* You should use open graph for easy sharing on social media. You should at least use "title", "url", "type" and "image". You can check if it is working by sharing your site on for instance Facebook or Twitter. You should use open graph for easy sharing on social media. You should at least use "title", "url", "type" and "image". You can check if it is working by sharing your site on for instance Facebook or Twitter.
* Learn about and create a robot.txt for your site. The contact page should not be indexed by search engines
* Learn about and create a human.txt for your site

## Part 4 - Posts
Whitout to mutch effort (in code) you should be able to add articles to your blog/news page. Do so by reflecting around the following subjects. One article per subject.
* What is robots.txt and how have you configure it for your site?
* What is humans.txt and how have you configure it for your site?
* What is Open Graph and how do you make use of it?
* Why is it important to seperate the layout and design (css) from content (html)?

## Oral hearing
The examination will be done as an oral hearing where you get a couple of theoretical questions from this part and also show your practical assignment. You can´t book a time for oral hearing before you are ready with the assignment and have done a release on GitHub.
