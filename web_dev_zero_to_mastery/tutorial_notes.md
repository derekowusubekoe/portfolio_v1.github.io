1. Learning From the Feynman Technique
(https://medium.com/taking-note/learning-from-the-feynman-technique-5373014ad230)
2. Be Prepared To Lose Your Job In The Future… If You Don’t Learn This One Skill Now
(https://medium.com/accelerated-intelligence/be-prepared-to-lose-your-job-in-the-future-if-you-dont-learn-this-one-skill-now-8a87ade2a268)
3. Developer Resources
(https://zerotomastery.io/resources/)

How the Internet Works
1. How the Internet Works for Developers - Pt 1 - Overview & Frontend
2. Computer Networking Playlist

*** Critical Render Path ***
This is a path that the web browser uses to display the content of the webpage to the user.


1. CSS Combinators
A combinator is something that explains the relationship between the selectors.
A CSS selector can contain more than one simple selector. Between the simple selectors, we can include a combinator.
There are four different combinators in CSS:
    - descendant selector (space)
The descendant selector matches all elements that are descendants of a specified element.
div p {
  background-color: yellow;
}
    - child selector (>)
The child selector selects all elements that are the children of a specified element.
div > p {
  background-color: yellow;
}
    - adjacent sibling selector (+)
The adjacent sibling selector selects all elements that are the adjacent siblings of a specified element.
Sibling elements must have the same parent element, and "adjacent" means "immediately following".
div + p {
  background-color: yellow;
}
    - general sibling selector (~)
The general sibling selector selects all elements that are siblings of a specified element.
div ~ p {
  background-color: yellow;
}

All CSS Combinator Selectors
Selector 	Example 	Example description
element element 	div p 	Selects all <p> elements inside <div> elements
element>element 	div > p 	Selects all <p> elements where the parent is a <div> element
element+element 	div + p 	Selects all <p> elements that are placed immediately after <div> elements
element1~element2 	p ~ ul 	Selects every <ul> element that are preceded by a <p> element
