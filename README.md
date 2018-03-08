## Project Instructions :pencil2:
**Review the Article to Mockup Project [Rubric](https://review.udacity.com/#!/rubrics/145/view)**

1. Download and unzip `mockup-to-article.zip` in the Supporting Materials section, below. You'll find `index.html`, the article mockup image (`blog-mockup.pdf`) and a file called `reflections.txt` inside.

2. Use what you've learned about web development so far to edit index.html so that it looks exactly like the mockup image. You will need to use new elements, which means that you'll need to research and experiment! (Hint: look up "superscript," "horizontal rule," and "strikethrough."). 

:point_right: Note: You can recreate the mockup without using a single \<br\> tag! You don't need to worry about line breaks. 
The text should naturally wrap depending on how wide the window is.

3. When you've finished building the article, open up `reflections.txt`. You've learned a lot about web development so far. I want you to take a moment to write down your thoughts about web development in `reflections.txt`. Answer the following questions:

> _What new skills have you learned?_\
> _What has been easy?_\
> _What has been difficult?_\
> _How have you used the problem solving strategies from the first project to overcome challenges so far?_

******

:point_right: [Project Specifications/Rubric](https://review.udacity.com/#!/rubrics/145/view)

:point_right: [View Online](https://jtrfs.github.io/mockup-to-article/)

***

### :red_circle: My tweaks to the project:
* I used not only HTML but also some internal CSS plus media query along with and jQuery. :exclamation: **To see the effect you must resize the viewport**.
* I tried to follow the mockup precisely - its look/design.

**some media query**
```
@media screen and (min-width: 1300px) {
      .tooltip1{ display: none;  }
      .tooltip2 { display: inline-block}
```

**some jQuery**
```
<script>
  $(function() {
    $( document ).on( "mousemove", function( event ) {
    $( ".tooltip1" ).css({
        "left" : event.pageX,
        "top" : event.pageY
      });
    });
  });
</script>
```

********

### To do list
- [x] remember to try out the markdown (I tried to get the hang of the markdown in this README file)
- [ ] keep coding ... :smirk:
