# 02 Advanced CSS: Portfolio
## Acceptance Criteria

Here are the critical requirements necessary to develop a portfolio that satisfies a typical hiring manager’s needs:

```
GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them
WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section
WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications
WHEN I am presented with the developer's first application
THEN that application's image should be larger in size than the others
WHEN I click on the images of the applications
THEN I am taken to that deployed application
WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport
```


In this project, I have navigate bar, three sections like "About Me", "Work", "Contact". The navigate bar can link to each section. In the "Work" section, I also set each project name link to the according project images. I use hover selector to present each project image, the image will get larger when the mouse move to the image. Each project image also link to the project website. I use flex box and media query to make the website has reponsive layout. git 