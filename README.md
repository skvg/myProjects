## This is the myProjects section to index my all projects here...
***
This section is hosted on the [github pages](www.skvg.github.io/myProjects)

Projects are classified as 'website', 'machine-learning' and all the rest are classified simply as 'project'.
***
### How to add a new project on website ?
To add a new project, you have to edit the index.html file. Just paste this html code snippet inside the boxes(div) section in a serial manner.

````html
<div class="project">
    <div class="type">project type</div>
    <div class="title">Title</div>
    <div class="desc">description of project</div>
    <div class="img"></div>
    <div class="links">
        <a href="www.skvg.github.io">link</a>
    </div>
</div>
````
- first of all change the main div class. You can put class name as 'website' for a website project, 'ml' for a machine learning project and 'project' for the rest of all projects.
- after that, you can replace all the text according to your project details.
- And when you use img div, then remember to edit index.css to set your img in project box according to your choice. For now, img class is not styled in the index.css file.