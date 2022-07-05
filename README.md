# react-dynamic-submenu-example




## Exercise from John Smilga's course, where several simple React projects are taught:
    [https://www.youtube.com/watch?v=a_7Z7C_JCyo]



## Link of the course final setup:
    Prototype website link after configured, made available by the course author. The code available in this repository has some 
    modifications made by me.
    [https://react-projects-13-stripe-submenus.netlify.app/]


## Functionalities:
    Interactive  submenu, opening and closing depending on where the browser mouse is moving, using onMouseOver method, changing the CSS class;
    
    API access and double deconstruction using map method ;

    Adding and removing HTML classes dynamically using validations;

    One different submenu for each menu item:
        1-which opens according to the location of the menu link, which is accessed through the event target 
        using the getBoundingClientRect() method to access the left and bottom values ​​and through a simple 
        arithmetic calculation to create the location of that particular submenu.;

        2-It uses the find method to dynamically open a different submenu per menu item, when hovering the
        mouse over each of these items.

    
    
    Creation of custom Hook , in this case with the name of useGlobalContext();

    useState Hook basics;
    
    React-icons.
    
## React Icons

    [react icons](https://react-icons.github.io/react-icons/)


## Changes regarding the course design:

    Two new css variables were created, changing the colors of texts, buttons and icons to my enjoy;

    Created a new background-image using a linear-greadient of my color palette;

    I Added my logo.
