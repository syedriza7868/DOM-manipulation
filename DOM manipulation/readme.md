# DOM Manipulation Assignment 

**1. Website Name: [Dev To](https://dev.to/)**

## Topics

   - Query Selctory, Inner HTML

## Sample Image 

![Sample One](./assset/download%20(2).png)

## Tasks 

  ***Target the Top description div and change the DEV community to <your_Name> and description to your passion.***

## Code uesd
 
*document.querySelector(".side-bar .crayons-card .       crayons-subtitle-2").innerHTML = "Syed Riza";
document.querySelector(".side-bar .color-base-70").innerHTML = "Any fool can write code that a computer can understand. Good programmers write code that humans can understand.";*

## Output 

![Output](./assset/Screenshot_20230212_143043.png)


**2.Websit Name: [Apple](https://support.apple.com/en-in)**

## Sample Image

![Store](./assset/download%20(38).png)

## Task

***Fetch all the product name and store in an arry***

  -['iPhone', 'Mac', 'iPad', 'Watch', 'AirPods', 'Music', 'TV']

## Code used 

*const productname = document.querySelectorAll(".as-imagegrid-item");
    const makeanarray = [];
    productname.forEach((p) => {
      makeanarray.push(p.innerText);
   });
    console.log(makeanarray);*11

## Output

![Apple](./assset/Screenshot_20230212_163405.png)


**3. Website Name: [Youtube](https://support.google.com/youtube/)**

## Topics

 **Get Element By Id, Create Element, create Text Node, Append Child.**

## Sample Image

![Sample One](./assset/download%20(32).png)

## Task 

***Add another FAQ 'My New FAQ' to the list***


## Code used

       const Section = document.querySelecto("accordion-homepage");
      const topic = document.createElement("section");
      topic.classList.add("parent");
      const h3 = document.createElement ("h3");
      h3.innerText = "My New FAQ";
      Section.appendChild(topic);
      topic.appendChild(h3);
## Output

![Youtube support](./assset/Screenshot_20230212_180322.png)


**4. Website Name: [Oneplus](https://www.oneplus.in/support)**

## Topics

***Query Selector, Innertext***

## Sample Image

![Onepuls](./assset/download%20(34).png)

## Output 

   document.querySelector(".customer-support a").innerText = '+91 7204022364'

## Tasks

***Change the contact Number***

## Output

![Onepuls](./assset/Screenshot_20230213_204401.png)

**5. Website Name: [Samsung](https://www.samsung.com/in/offer/online/samsung-fest/)**

## Topics

***getElementId, cerateElement, InnerText, append, setAttribute.***

## Sample Image 

![Samsung](./assset/download%20(36).png)

## Code used

    document.querySelector(".diwali-deals-product-sale-btn").innerText = "Check Out";

## Tasks 

***Target the main div of card and change the Button text to check out.***

## Output 

![Samsung](./assset/Screenshot_20230214_150029.png)

**6. Website Name: [Adidas](https://www.adidas.co.in/)**

## Topics 

 - ***Query selector, Event Listeners, Changing Styles.***

## Sample Image 

![Adidas](./assset/download%20(1).png)

## Code uesd
    
    const find = document.querySelector("._wrapper_1f3oz_1 ._input_1f3oz_13")
  find.addEventListener("mouseover", changbg)
  function changbg(){
  find.style.backgroundColor = "red"
  };

## Tasks 

**Target the search box and on hover change the background to red.**

## Output 

![Adidas](./assset/Screenshot%202023-02-28%20211204.png)

**7. Website Name: [MDN Web Docs](https://developer.mozilla.org/en-US/)**

## Topics 

***From, Value, Submit.***

## Sample Image 

![MDN Web Docs](./assset/download%20(3).png)

## Tasks 
**To Search a topic in the MDN Search bar. First add a text to search in the search bar and then hit submit search button to search the docs using DOM.**

## Output

![MDN Web Docs](./assset/Screenshot%202023-02-28%20221241.png)

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


**9. Website Name: [Code War](https://www.codewars.com/)**

## Topics 

***Change Font Family, Color of Text.***

## Sample Image 

![Code War](./assset/download%20(7).png)

## Tasks
**Change the font family of the text to monosapce and text color 
  to the logo's background color.**

## Code used

document.querySelector('.text-color-white').style.fontFamily ="monospace"
    document.querySelector('.text-color-white').style.color="#B1361E"

## Output

![Code War](./assset/Screenshot%202023-03-01%20141929.png)

**10. Website Name: [Freecodecamp](https://www.freecodecamp.org/)**

## Topics

***queryselector, mouseover, click eventlister, callback function, style.***

## Sample Image

![Freecodecamp](./assset/download%20(9).png)

## Tasks 

**Target the button and change background color on mouseover**

## Code used

     document.querySelector(".btn-cta-big .login-btn-text ").addEventListener("mouseover",function(){

  document.querySelector(".btn-cta-big .login-btn-text ").style.backgroundColor="red"

## Output

![Freecodecamp](./assset/Screenshot%202023-03-01%20152005.png)


**11. Website Name: [Realme](https://www.realme.com/in/)**

## Topics

***queryselector, style, background-image***

## Sample Image

![Realme](./assset/download%20(12).png)

## Tasks 

**change the realme logo to ineuron logo**

## Code used

  document.querySelector(".gtag .icon").style.backgroundImage="url('https://ineuron.ai/images/ineuron-logo.png')"

## Output

![Realme](./assset/Screenshot%202023-03-01%20153424.png)

**12. Webiste Name: [Github](https://github.com/)**

## Topics

***querySelector,style,background-Color***

## Sample Image

![Github](./assset/download.png)

## Tasks

**change the background colour of the button to blue.**

## Code used

   document.querySelector(".btn-primary btn").style.backgroundColor = "blue";

## Output

![Github](./assset/download%20(15).png)


**13. Webiste Name: [Hackerrank](https://www.hackerrank.com/)**

## Topics

  ***querySelector, innerHTML***

## Sample Image

![Hackerrank](./assset/Screenshot%202023-03-01%20203500.png)

## Tasks

  **Traget the top description and change "Everything you need to know to hire Software Engineers" to "JSBOOTCAMP.**

## Code used

    document.querySelector('.fl-heading').innerHTML = "JSBOOTCAMP";

## Output

![Hackerrank](./assset/Screenshot%202023-03-01%20202826.png)


**14. Webiste Name: [Asus](https://www.asus.com/in/)**

## Topics

  ***querySelector,style,font-size***

## Sample Image

![Asus](./assset/download%20(18).png)

## Tasks

  **change the fontsize of “Hot Deals” to 80px**

## Code used

      document.querySelector('.HotDealsAll__Heading__2fIbe').style.fontSize="80px";

## Output

![Asus](./assset/Screenshot%202023-03-01%20204243.png)

**14. Webiste Name: [Dell](https://www.dell.com/en-in/shop/deals/laptop-deals?gacd=10415953-9016-5761040-285981356-0&dgc=ST&gclid=Cj0KCQjwguGYBhDRARIsAHgRm4-XUDMhhVNyHXb3s1gY4ZBzORr_d9Se-buhJwy7asyUe7YdqEA11eEaAt6UEALw_wcB&gclsrc=aw.ds&nclid=BxjBlpBQsX6pjSHh-L8YYSU77EpfXRkG1AGMB5Wbeu386ykspfrPDnfx_DdFau20)**

## Topics

  ***querySelector, style, textAlign***

## Sample Image

![Dell](./assset/download%20(20).png)

## Tasks

  **Convert the text "G15 Gaming Laptop" from left to right**

## Code used

     document.querySelector(".ps-title").style.textalign= "right"; 

## Output

![Dell](./assset
193264650-75455cba-2fde-49bb-8e6c-241be6dd51cc.png )

**16. Webiste Name: [Vercal](https://vercel.com/)**

## Topics

***querySelector, innerHTML***

## Sample Image

![Vercal](./assset/Screenshot%202023-03-01%20214409.png)

## Tasks

**change the heading "Build when inspiration strikes" to "start with scratch"**

## Code used

  document.querySelector('.section-title_title__VEDfK').innerHTML = "Start with Sctrach";

## Output

![Vercal](./assset/Screenshot%202023-03-01%20214139.png)

**17. Webiste Name: [Sony](https://www.sony.co.in/)**

## Topics

***querySelector, innerHTML***

## Sample Image

![Sony](./assset/download%20(25).png)

## Tasks

**Change the button text to current Date**

## Code used

  document.querySelector(".btn-container").innerHTML=new Date()

## Output

![Sony](./assset/Screenshot%202023-03-02%20092550.png)

**18. Webiste Name: [Philips](https://www.philips.co.in/)**

## Topics

***querySelector, style, backgroundcolor***

## Sample Image

![Philips](./assset/download%20(26).png)

## Tasks

**Change the background color blue to orange**

## Code used

  document.querySelector(".p-f03-footer-container .p-footer").style.backgroundColor="orange"

## Output

![Philips](./assset/Screenshot%202023-03-02%20093054.png)

**20. Webiste Name: [Oppo](https://www.oppo.com/in/)**

## Topics

***querySelector, style, color***

## Sample Image

![Oppo](./assset/download%20(30).png)

## Tasks

**Change the description color black to orange**

## Code used

     document.querySelector('.product-card-content .desc').style.color = 'Orange';

## Output

![Oppo](./assset/192700250-26540de5-a224-458f-ab13-48f94593bae4.png)
