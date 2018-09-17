# CS50 Web: Lecture 6 Front Ends   

## Outline
* Single-Page Apps 
* HTML5 History API 
* Infinite Scrolling 
* Hiding Contents  
* Javascript Templating 

### Single-Page Apps 
* taking multi-page of HTMLs and combining them into one page. 
* Advantages: 
	* no need to reload the page 
* Disadvantages: 
	* URL does not change; might be more useful to display the entire URL. 
* src: `multipage` `singlepage0` 

### HTML5 Hitory API 
* manipulate the browser history effectively and update the URL to reflect different URLs. 
* `history.pushState()`: update the URL. Use the data argument to store data. 
* `window.onpopstate()`
![](./img/on_pop.png)
* src: `singlepage1` `singlepage2` 

### Infinite Scroll 
* window: a few useful attributes - `window.innerWidth` `window.innerHeight` `document.body.offsetHeight` `window.scrollY` 
* be able to detect the user scrolls to the end of the page; useful when you need infinite scrolling like Facebook 
* advantages: 
	* page loading performance 
* src: `scroll.html` `posts0` 

### Hiding Contents 
* `this.parentElement.remove();`: remove parent element 
* src: `posts1` 

### Javascript Templating 
* build templates in JS that allows us to write HTML code and then insert to DOM. 
* `Handlebars`: one of such libraries 
* src: `dice0`

-- 48:53 