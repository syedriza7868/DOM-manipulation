**8. Website Name: [Google](https://www.google.com/)**

## Topics 

  ***Remove Elements***

## Sample Image 

![Google](./assset/download%20(5).png)

## Tasks

  **Remove alternate languages from the home page langanges listed**

## Code used

     const languagesOffered = document.querySelectorAll('#SIvCoba')
     languagesOffered.forEach( (a, i)=> i%2==0 && a.remove())

## Output 

![Google](./assset/Screenshot%202023-03-01%20140315.png)