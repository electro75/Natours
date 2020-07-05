# Natours

This is a mock web page built while learning advanced CSS concepts from [this course](https://www.udemy.com/share/101WkwAkUZd1ZUTXg=/)

The project can be run cloning this repo and opening the index.html file


## Concepts : 

### Clip Path : 
- Attribute used to clip the element to which it is applied. eg:
```
clip-path: polygon(0 0, 100% 0, 100% 75%, 0 100%);
```

### Animation : 
- Everything related to the animation property. (effect, delay, duration, timming function etc)
```
animation: moveInRight 1s ease-out;
```

### REM : 
- Using lenghts and font-sizes in rem helps in writing highly responsive web pages as all sizes will be relative to root.

### BEM Principle : 
- BEM stands for Block Element Modifier. This is one of the techniques that is used to name CSS classes.

### 7 in 1 Architecture : 
- Type of css architecture has been used for the project. The sass files are divided into the following 
folders : 
    - __Base__ : includes the low level basic styling eg reset, body, html.
    - __Abstracts__: includes code that does not output any css. eg : variables, mixins etc.
    - __Components__: contains styling for individual component.
    - __Layout__: contains the layout of the page. eg :header, footer.
    - __Pages__: contains styling for individual pages.
    -__Themes__: contains the theme styling. (*not in this project*)
    -__Vendors__: contains 3rd party css styles. (*not in this project*)

*the files inside thes folders are called __partials__ and have names tha start with an underscore(_)*,

### Float Layout : 
- Float layout is used to build the webpage as it is supported accross all modern browsers.

