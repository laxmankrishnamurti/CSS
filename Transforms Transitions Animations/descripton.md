# What is Transforms?

Thansforms are used to Rotate, Move, Skew or Scale elements. They are used to create a 2-D & 3-D effect.

# What is the Syntax of Transformation? 

<pre>
{
    transform: property_name(value);
}
</pre>

# There are lots of properties are available for creating 2-D & 3-D effects. The property which is mostly used is given below.

For 2-D ::

<pre>
{
    transform-origin: center;           // By-default value 
    translate();
    rotate();
    scale x();
    scale Y();
    skew();
    matrix();
    scale(x, y);
}
</pre>

For 3-D ::

<pre>
{
    rotate x(value in deg)
    rotate y(value in deg)
    rotate z(value in deg)
}
</pre>

# What is Transition?

Transition means it change the property value smoothly in a given duration.

# Properties of Transition.

<pre>
{
    transition-property: value;             // the trans property we want to transition, like- height, widht, color...etc
    transition-duration: value in second(s)
    transition-timing-function: value;
    transition-delay: value;
}

DEMO::

{
    transition: all 2s ease-in-out 1s;      // This is called Shorthand Property.
}
</pre>

# What is Animation?

Animation is a technique by which still images are manipulated to create moving images. In other words we can say that Animation is a little bit advance method to Transform an element. But, before going on it's property we have to understand about the concept of KeyFrames. Yes! Keyframes.

Without keyframes animation is next to impossible to create. So, we should understand about What keyframe exactly is? Why it is so Important while making animations. 


# What is KeyFrames?

In animation, a key frame is a drawing or shot that defines the starting and ending points of a smooth transition. These are called frames because their position in time is measured in frames. So, now tha question is "How we can create keyframes for animation?".

# Creating KeyFrames- A step-by-step Process, which is given below.

<pre>

@keyframe myAnimation {
    from{font-size : 20px}
    to{font-size : 40px }
}

@keyframe myAnimation2{
    0%{
        width: 30px;
    }
    50%{
        widht: 100px;
    }
    100%{
        width: 300px;
    }
}

Here, myAnimation & myAnimation2 is the name of keyframes/animation
</pre>

# properties of Animation.

<pre>
{
    animation-name: name;
    animation-duration: value;
    animation-timing-function: value;
    animation-delay: value;
    animation-iteration-count: value or infinite(by-default);
    animation-direction: value;
}
</pre>