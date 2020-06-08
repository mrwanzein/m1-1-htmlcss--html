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

c) [true] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?

Answer: A screen reader is a software application that enables people with severe visual impairments to use a computer. It can provide feedback to the user via Braille or Speech.

https://www.nomensa.com/blog/2005/what-screen-reader

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation

Answer:

<ul>
 <li><img src="link to img" alt=""/>Description of image</li>
 <li><img src="link to img" alt=""/>Description of image</li>
 <li><img src="link to img" alt=""/>Description of image</li>
</ul>

b) You want to create a website that lists all the art gallery websites in your city and links to their website.

Answer:

<ul>
 <li><a href="link to site">Gallery name</a></li>
 <li><a href="link to site">Gallery name</a></li>
 <li><a href="link to site">Gallery name</a></li>
</ul>

c) You want to sell designer hats. You need to receive orders from the user.

Answer:

<ul>
 <li><img src="link to img" alt=""/>Hat name<button name="button">Order</button></li>
 <li><img src="link to img" alt=""/>Hat name<button name="button">Order</button></li>
 <li><img src="link to img" alt=""/>Hat name<button name="button">Order</button></li>
</ul>

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning

Answer: The HTML compiler won't allow it and would treat it as two sperate entities of button element.

## Q5 - What is the most generic tag you can use?

Answer: I would say the `div` tag because it can represent anything at a block level.

## Q6 - What do the following achronyms stand for?

a) `a` = Anchor

b) `ol` = Ordered list

c) `ul` = unordered list

d) `li` = list

e) `tr` = table rows

f) `th` = header cells

g) `td` = cells

## Q7 - Usually, `td` elements are children of what kind of elements?

Answer: `tr`

## Q8 - What is the difference between td and th?

Answer: `th` are the header cells at the top of the table. `td` are the cells in the rows(`tr`) under the `th`.

## Q9 - Which tag makes the text appear bigger: h1 or h3?

Answer: `h1`

## Q10 - In which situation can you use self closing tags?

Answer: If the tags are “void-elements” in HTML spec. A list can be found online.

## Q11 - What is autofilling and why is it important?

Answer: Auto filling is when the code editor suggest a completion to the code you're writing. When pressing shift after a suggestion, it will auto complete. Maybe I am confusing auto completion with auto filling.

## Q12 - Which attributes are always present in an img element?

Answer: `src` and `alt`

## Q13 - Which attribute is always present for an anchor tag?

Answer: `href`
