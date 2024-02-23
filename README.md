# CSS--interview

https://www.youtube.com/watch?v=L1Oc2ZLydvw&ab_channel=InterviewHappy
____________________________________________________________________________________________________________________
z index in css
>>
In CSS, the z-index property determines the stacking order of positioned elements. When elements overlap, the z-index helps specify which one should be displayed on top of the others.
```javascript
.box1 {
    position: relative;
    z-index: 2;
}

.box2 {
    position: relative;
    z-index: 1;
}
```
_____________________________________________________________________________________________________________

The CSS Box Model
>>
The CSS Box Model is a fundamental concept in web design that describes how elements on a webpage are structured and spaced. It consists of several components:

Content: This is the actual content of the HTML element, such as text, images, or other media.

Padding: The padding is the space between the content and the element's border. It helps to create space around the content, improving readability and aesthetics.

Border: The border surrounds the padding and content and can be styled using CSS properties like border-width, border-style, and border-color.

Margin: The margin is the space outside the border. It creates separation between elements on the page, controlling how they are positioned relative to each other.

+-----------------------------------+
|              Margin               |
|  +----------------------------+   |
|  |          Border            |   |
|  |  +----------------------+  |   |
|  |  |       Padding        |  |   |
|  |  |  +----------------+  |  |   |
|  |  |  |    Content     |  |  |   |
|  |  |  +----------------+  |  |   |
|  |  +----------------------+  |   |
|  +----------------------------+   |
+-----------------------------------+

_____________________________________________________________________________________________________________________________________________
