# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [ True] `<div><span>hello</div></span>`

b) [False ]

```html
<ul>
<li>one</li>
</ol>
```

c) [False ] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?

Screen Reader uses text to speech to read out the information on the page. This allows people to hear the information. This can be used by anyone but it is important for the accessibility of people might be impaired or disabled. 

Source: https://www.nomensa.com/blog/2005/what-screen-reader#:~:text=A%20screen%20reader%20uses%20a,that%20plugs%20into%20the%20computer.

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation

<h1></h1>
<p></p>
<img>


b) You want to create a website that lists all the art gallery websites in your city and links to their website.

<ol>
<li><a href="url">Name of site></a></li>
</ol>

c) You want to sell designer hats. You need to receive orders from the user.



## Q4 - Can a `button` be a child of a `button`? Explain your reasoning

According to W3, you cannot have a button in a button.
Ex:
<button><button>Click Here</button></button>
Will end up giving you 2 buttons, rather than a button that appears when clicking the oriinal button. Also, using this link from stack overflow; it says its invalid to put a <button> element inside another <button>.

## Q5 - What is the most generic tag you can use?

<div>
<span>
<p>


## Q6 - What do the following achronyms stand for?

a) `a` 
= hyperlink tag

b) `ol` 
= ordered list tag

c) `ul` 
= unordered list tag

d) `li` 
= defines each list item, so it defines what is in the list

e) `tr` 
= table row. defines a row in a table

f) `th` 
= table header. defines the header for a column (name of column for example) since its the header cell

g) `td` 
= defines the data cell in a table on HTML. This is the cell with the actual information.

## Q7 - Usually, `td` elements are children of what kind of elements?

Of a TR/ table row element. Since in each ro you can write in what the data cell's value is supposed to be. 

## Q8 - What is the difference between td and th?

TH is the table header. It has the title in it and explains what is displayed in the TD which is the table data cell. 

Ex: TH can be Day of the week & TD will be Monday, Tuesday, Wednesday etc



## Q9 - Which tag makes the text appear bigger: h1 or h3?
<h1> is bigger than <h3> but <h3> is still a "title/header so it will be bigger than normal writing.

## Q10 - In which situation can you use self closing tags?

When you want to put a break or add an img, input and source.

## Q11 - What is autofilling and why is it important?

It automatically tries to predict the vlue of something and tries to fill in that information for you. This is important because it makes things easier. 
## Q12 - Which attributes are always present in an img element?

The main 2 attributes always found in an img element are the scr (source attribute) and the alt (which is the alternative writing or text if the image cannot be viewed). 

## Q13 - Which attribute is always present for an anchor tag?

the href attribute is always present, because that indicates where the link is coming from. It describes a hyperlink. 