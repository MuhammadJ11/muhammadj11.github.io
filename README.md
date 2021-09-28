# muhammadj11.github.io

*Lab 1*

**Deadline Thursday**

1. I created my project's repository. I named my repository muhammadj11.github.io **[Github](https://github.com/MuhammadJ11/muhammadj11.github.io)** replacing username with my GitHub username. It is public and i created a README file upon generating the repo. I created an index.html page next and added html code for the layout of my first page. To style the content i created a new file named css/main.css. The ‘css/’before the filename will automatically create a subdirectory called css. Later i linked my CSS file inside the HTML document's <head>.

2. I create a ‘.gitignore’file. This file tells Git to ignore the ‘_site’ directory that Jekyll automatically generates each time you commit. I created a _config.yml file that tells Jekyll some basics about my project. In this example, i am telling Jekyll the name of the site and what version of Markdown i'm using.
 I made a ‘_layouts’directory, and created a file inside it called ‘default.html’. This is my main layout that will contain repeated elements. Now i don't have to repeat that markup on every single page i create, making maintenance of site much easier. Later i updated my index.html to use the default layout.
  
3. A Jekyll-based blog uses the same conventions. I create a file named post.html in my _layoutsfolder. Later i made a _posts/directory where i stored mu blog posts. It must follow the convention YYYY-MM-DD-title-of-your-post.md. This file name gets translated into the permalink for the blog post. The file extension .mdstands for Markdown, and the Markdown syntax used inside the file gets converted to HTML by Jekyll. I created a blog directory and created a file named index.html inside it. To list each post, i used a foreach loop to create an unordered list of the blog posts. In Jekyll you can control the structure of the permalinks by editing the _config.yml file created earlier. So i changedmy permalink structure to include the blog directory. I created and commit an about/index.html page which uses

  
  
![hw](https://user-images.githubusercontent.com/90790091/134825253-74994059-4963-4f38-ae61-19c0498cd006.png)


