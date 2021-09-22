# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

- Red: hsl(0, 78%, 62%)
- Cyan: hsl(180, 62%, 55%)
- Orange: hsl(34, 97%, 64%)
- Blue: hsl(212, 86%, 64%)

### Neutral

- Very Dark Blue: hsl(234, 12%, 34%)
- Grayish Blue: hsl(229, 6%, 66%)
- Very Light Gray: hsl(0, 0%, 98%)

## Typography

### Body Copy

- Font size: 15px

### Fonts

- Family: [Poppins](https://fonts.google.com/specimen/Poppins)
- Weights: 200, 400, 600


Reliable, efficient delivery
  Powered by Technology

  Our Artificial Intelligence powered tools use millions of project data points 
  to ensure that your project is successful

  Supervisor
  Monitors activity to identify project roadblocks

  Team Builder
  Scans our talent network to create the optimal team for your project

  Karma
  Regularly evaluates our talent to ensure quality

  Calculator
  Uses data from past projects to provide better delivery estimates
  <!-- 
  .card__1 {
    grid-column: 1;
    grid-row: 2;
    
}
.card__2 {
    grid-column: 2/3;
    grid-row: 1/3;
}
.card__3 {
    grid-column: 3/4;
    grid-row: 3/2;
}
.card__4 {
    grid-column: 2/3;
    grid-row: 2/4;
}
 -->
  
  <footer>
    <p class="attribution">
      Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
      Coded by <a href="#">Your Name Here</a>.
    </p>
  </footer>

  grid-template-columns :  1 fr  1 fr  1 fr ;
    gap :  28 px ;
    grid-template-areas :
      '. t .'
      'stc'
      'skc'
      '. k.' ;


      display : grid;
  gap :  24 px ;
  justify-items : center;
  grid-template-areas :
    's'
    't'
    'k'
    'c' ;


    * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
.card {
    border: 2px solid gray;
    color: rgb(115, 165, 40);
    width:200px;
    height: 200px;
    text-align: center;

}
.grid-container {
    width: 50%;
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    grid-template-rows: repeat(4, 1fr);
    margin: auto;
    justify-content: center;
    align-content: center;
    grid-gap:1em;
}
.card__1 {
    grid-column: 1;
    grid-row: 2;
}
.card__2 {
    grid-column: 2/3;
    grid-row: 1/3;
}
.card__3 {
    grid-column: 3;
    grid-row: 2/4;
}
.card__4 {
    grid-column: 2/4;
    grid-row: 3/3;
}

<!-- *********Somehow completed version**********

h1,body,html {
    margin:0;
    padding: 0;
    box-sizing:border-box;  
  }
  .card {
    border:1px solid teal;
    width: 200px;
    height: 150px;
    margin: auto;
    background-color:maroon;
    
  }
  
 .grid-container {
     width: 40%;
     height: 50%;
     display: grid;
     grid-template-columns: repeat(3,1fr);
     grid-template-rows: repeat(5,4fr);
     grid-gap: 1em;
     text-align: center;
     grid-auto-rows: minmax(auto, auto);
     
 }


.card__1 {
    grid-column: 1;
    grid-row: 2;
    
}
.card__2 {
    grid-column: 2/3;
    grid-row: 1/3;
}
.card__3 {
    grid-column: 3/4;
    grid-row: 3/2;
}
.card__4 {
    grid-column: 2/3;
    grid-row: 2/4;
} -->

