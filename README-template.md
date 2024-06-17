# Frontend Mentor - Article preview component solution


## Overview

This is a solution to the [Article preview component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/article-preview-component-dYBN_pYFT). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 
![Design preview for the Article preview component coding challenge](./design/desktop-preview.jpg)

### The challenge

The challenge is to build out this article preview component and get it looking as close to the design as possible.

You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go. 

The only JavaScript you'll need for this challenge is to initiate the share options when someone clicks the share icon.

Your users should be able to: 

- View the optimal layout for the component depending on their device's screen size
- See the social media share links when they click the share icon

Want some support on the challenge? [Join our community](https://www.frontendmentor.io/community) and ask questions in the **#help** channel.




### Screenshot

![](./Screenshot%20(17).png)


### Links

- Solution URL: [Add solution URL here](https://github.com/cynthiachinenye/article-preview-comp.git)
- Live Site URL: [Add live site URL here](https://cynthiachinenye.github.io/article-preview-comp/)

## My process
I use bootstrap to get the card and use a row component to display it as grid the use addeventlistener in thejavascript when a btn is clicked it should display or toggle the following div. 

### Built with

- Semantic HTML5 markup
- CSS custom properties

- Mobile-first workflow
- [Bootstrap](https://getbootstrap.com/docs/5.0/getting-started/introduction/) - css framework



### What I learned

this is what I didn't know how to do but I now know how to do it now with lots of attempts !!!

To see how you can add code snippets, see below:

```html
<h1>Some css and JS code I'm proud of</h1>
```
```css
.social-link::before {
  content: "";
  position: absolute;
  width: 0;
  height: 0;
  border: 13px solid hsl(217, 19%, 35%);
  border-color: hsl(217, 19%, 35%) transparent transparent;
  top: 100%;
  left: 50%;
  transform: translate(-50%, -1px);
  animation: shows 1s forwards linear;
}
```
```js
  
      function eventHandle (){
         SocialLink.classList.toggle("show")
       

      }
```


### Continued development

I want to continue learning to be able to get to some certain level in coding to use libraries like react, netxtjs and co.


### Useful resources

- [Example resource 1](https://getbootstrap.com/docs/5.0/getting-started/introduction/) - This helped me for css media screen . I really liked this pattern and will use it going forward.


## Author

- Website - [Add your name here](https://cynthiachinenye.github.io/article-preview-comp/)
- Frontend Mentor - [@cynthiachinenye](https://www.frontendmentor.io/profile/cynthiachinenye)
- Twitter - [@cyndyblesstech](https://www.twitter.com/cyndyblesstech)



## Acknowledgments

I acknowledge myself on this particular and the work on google search.
