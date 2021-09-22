# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [false] `<div><span>hello</div></span>`

b) [false]

```html
<ul>
<li>one</li>
</ol>
```

c) [false] `<ul></ul><img/><ol><li>one</li></ol>`


## Q2 - What is a screenreader and why should we care about them?

A screen reader is software or hardware that renders text and image content as speech or braille output.  
Screen readers are essential to people who are blind, and are useful to people who are visually impaired, illiterate, or have a learning disability. We should always consider accesibility as an important value in what we do/code (plus we want to avoid the fines!).  (from Wikipedia - https://en.wikipedia.org/wiki/Screen_reader)

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
<h1> <h2> <div> <span> <img> <p>  

b) You want to create a website that lists all the art gallery websites in your city and links to their website.
<h1> <div> <span> <ul> <li> <a> 

c) You want to sell designer hats. You need to receive orders from the user.
<h1> <div> <span> <form> <input>

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning
No. Its descendants cannot be a clickable element.

## Q5 - What is the most generic tag you can use?
<div>

## Q6 - What do the following achronyms stand for?

a) `a`
anchor

b) `ol`
ordered list

c) `ul`
unordered list

d) `li`
list element

e) `tr`
table row

f) `th`
table head

g) `td`
table data

## Q7 - Usually, `td` elements are children of what kind of elements?
tr

## Q8 - What is the difference between td and th?
th is placed in the first row to indicate the header of the column.

## Q9 - Which tag makes the text appear bigger: h1 or h3?
h1 but it can be changed with css

## Q10 - In which situation can you use self closing tags?
If the element doesn't have children

## Q11 - What is autofilling and why is it important?
Allows user information stored by the browser to be automatically put into input fields within a form.

## Q12 - Which attributes are always present in an img element?
src for the source and alt for screen reader accesibility

## Q13 - Which attribute is always present for an anchor tag?
href