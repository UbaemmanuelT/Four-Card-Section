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



.card-container{
    padding: 2rem;
    margin-top: 3rem;

}










@media (max-width:576px) {
    .container{
        padding: 30px;
        width: 540px;
    }
    .container #head2{
        margin: 0.5rem auto;
    }
    .header{
        line-height: 1.5rem;
    }
    .header p{
        width: 80%;
        margin: auto;
    }
    p{
        line-height: 1.5rem;
    }
    .header{
        line-height: 2rem;
    }
    .card-container{
        display: grid;
        grid-template-columns: repeat(6, 1fr);
    }
    .cards:nth-of-type(1){
        border-top: 5px solid green;
        grid-column: 1 / 7 ;
    }
    .cards:nth-of-type(2){
        border-top: 5px solid red;
        grid-column: 1 / 7;
    }
    .cards:nth-of-type(3){
        border-top: 5px solid orange; 
        grid-column: 1 / 7; 
    }
    .cards:nth-of-type(4){ 
        border-top: 5px solid blue;
        
    }
}