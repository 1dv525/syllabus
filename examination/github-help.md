## GitHub pages help
In this course we will use GitHub for your code. This mean that you should commit your code through Git and push it up to GitHub several times per examination assignment. In the first assignment we also use GitHub to run as a web server serving your html-pages to the browser. This is done through something called GitHub Pages and we have turn that feature on at your examination-1 repository. Therefore is it important that you do commits to your master branch to get the pages live on the GitHub Pages servers.

If you need to freshen up your Git and GitHub skills please watch the tutorials linked in the ["Getting started"- page](https://coursepress.lnu.se/kurs/introduction-to-web-programming/getting-started/). We can also recommend this interactive guide: https://try.github.io/

## Steps getting your first html-page up on GitHub Pages
When your registered your GitHub account name on our page (see ["getting started"](https://coursepress.lnu.se/kurs/introduction-to-web-programming/getting-started/)) we create four Github repositories for you. In the first examination assignment we concentrate on the repository named: `xx222xx-examination-1`, where xx222xx is your username at LNU.

The repository have the GitHub Page feature turned on which means that you also have an **public** URL where your page will be served. You will find your page at the URL: `https://1dv525.github.io/xx222xx-examination-1` (where xx222xx is your username at LNU). At the beginning you haven´t pushed any files up to GitHub yet so all you see is a 404 page.

![404](https://github.com/1dv525/syllabus/raw/master/examination/images/404.png)

### Step 1
The first thing to do is to clone your repo to your local computer. First go to GitHub and your repository page. There you will find your clone URL when selecting the button shown bellow:

![Clone URL](https://github.com/1dv525/syllabus/raw/master/examination/images/clone_url.png)

Copy the URL - I use the SSH URL since I prefer that but the default https-link will also work, open up your terminal window make a directory where you want to store your working files and run the "git clone"-command on your URL. In this example the LNU-username used is "thajostudent".

![Clone command](https://github.com/1dv525/syllabus/raw/master/examination/images/git_commands1.png)

With this command the repository will be downloaded to your local machine and you can start working. You'll see that git-clone creates a new directory containing the repository so be sure to change your current directory to that directory (using the "cd-command").

### Step 2
Now open up your IDE of choice to point at the repository folder and start creating a HTML-page. In this example we use ATOM as an IDE and created and saved a simple index.html file.

![hello world](https://github.com/1dv525/syllabus/raw/master/examination/images/html-structure.png)

### Step 3
 Now that we have created some content we want to commit it with Git and then push it up to GitHub to watch the page. Going back to the terminal window, write these three commands as you see in the image bellow

![git commit](https://github.com/1dv525/syllabus/raw/master/examination/images/git-commit.png)

* The first one ```git status``` will just show you the status of your repository saying that Git have detect that you created (or changed) some file(s).
* `git add .` tells Git to add the created file to the repository (see documentation for more information)
* `git commit -m "create the index.html"` tells git to add a commit to the repository telling what changes you made with the "-m" flag.

### Step 4
Now that we made our commit(s) it is time to push your code up to GitHub. Use the `git push` command

![Git push](https://github.com/1dv525/syllabus/raw/master/examination/images/git-push.png)

And the the upload should start. This is the way to add files to GitHub repository. Don´t use any upload feature!

### Step 5
Check that the files is up on the GitHub repository and test your public URL. In this case it will look as in the picture below.

![hello_world_done.png](https://github.com/1dv525/syllabus/raw/master/examination/images/hello_world_done.png)

This simple tutorial tries to show how we expect you to work in the first examination assignment. When we go through your work we will look at your repository, read your commit messages and look at your page through your public URL.
