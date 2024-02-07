# What is CSS Grid?

Using CSS Grid is a good choice for creating better layouts. A grid can be defined as an intersecting set of vertical and horizontal lines. CSS Grid layout seperates a page into major section. Grid property offer a grid-based layout-system having rows and columns.

# How we can Initialize CSS Grid?

By applying this key-value pairs, which is given below:- 

<pre>
{
    display: grid;
}
</pre>

# There is a list which includes major properties of CSS Grid, given below :- 

<pre>
{
    grid-template-columns: specify the size of the columns;        // Used to create columns in a grid
    grid-template-rows : specify the size of the rows;             // Used to create rows in a grid
    grid-gap: value;                             // Used to create gaps between rows and columns
    justify-content: value;                      // Used to align the whole grid inside the container
    align-content: value;                        // Used to vertically align the while grid inside the container
}
</pre>

Instead of using :- 

<pre>
{
    grid-template-columns: no of columns;        
    grid-template-rows : no of rows; 
}
</pre>

We can use :-

<pre>
{
    grid-template-columns: repeat(n, 1fr)
    grid-template-rows: repeat(n, 1fr)
}
</pre>

Here,
- <pre>n   :: Number of rows or columns</pre>
- <pre>1fr :: One Fraction of the entire width</pre>

# Properties that can applied on the child-container.

<pre>
{
    grid-column: n / span n;                         // Defines how many columns an item will span.
    grid-row: n / span n;                            // Defines how many rows an item will span.   
}

Here
- n :: From where
- span n :: till  
<pre>
