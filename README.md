<h1 align="center">
[The Odin Project: HTML & CSS] - Project: Positioning and Floating Elements
</h1>

## Intro

-   The goal of this project was to practice building layout and positioning content. In the past lessons we learned about floats and positioning, Flexbox, and Grid. Now we put what we learned to practice by building a replica of [this news article page from the NewScientists](https://www.newscientist.com/article/2286218-ancient-lake-in-marss-gale-crater-may-have-actually-been-a-small-pond/)
-   You can find more on the project here: [The Odin Project - Positioning and Floating Elements](https://www.theodinproject.com/paths/full-stack-javascript/courses/html-and-css/lessons/positioning-and-floating-elements)

### 📗 Fonts used

-   [PT Serif](https://fonts.google.com/specimen/PT+Serif?query=PT+Serif)
-   [Titillium Web](https://fonts.google.com/specimen/Titillium+Web?query=Til)

### 🎨 Color Reference

|  Color            |  Hex                                                                 |
| ----------------- | -------------------------------------------------------------------- |
| Turquoise         |  ![#20b2aa](https://via.placeholder.com/10/20b2aa?text=+ `#20b2aa`   |
| Dark Blue         | ![#173b48](https://via.placeholder.com/10/173b48?text=+) `#173b48`   |
| Red               |  ![#f00](https://via.placeholder.com/10/f00?text=+) `#f00`           |
| Sky Blue          | ![#00b3e5](https://via.placeholder.com/10/00b3e5?text=+) `#00b3e5`   |
| Blue              | ![#005587](https://via.placeholder.com/10/005587?text=+) `#005587`   |
| Black             |  ![#060606](https://via.placeholder.com/10/060606?text=+) `#060606`  |
| Light Grey        |  ![#f5f5f5](https://via.placeholder.com/10/f5f5f5?text=+) `#f5f5f5`  |
| Grey              |  ![#4d4d4d](https://via.placeholder.com/10/4d4d4d?text=+) `#4d4d4d`  |
| Dark Grey         |  ![#484848](https://via.placeholder.com/10/484848?text=+) `#484848   |

## Overall

### What I Learned

-   Something I noticed when developing my layout is that I would put extra html elements that were not necessary. For example I would do something like the following

    ```
    <section class='main-article-image'>
        <div class='main-article-image-container'>
    </section>
    ```

    Later on I felt this was not necessary since the section is used to group items that are related together while divs tag is used as a block part of the webpage and don’t convey any particular meaning. In the Wesbos CSS grid course there was not that much extra divs going on. I only saw the tags where necessary to make the content appear and properly organize

-   I feel that this will help me better organize the code and create better layouts. It will also help me visualize what area to apply Grid or Flexbox
-   Also I noticed that I struggled with knowing how to create responsive design. The Wesbos CSS Grid course did help with introducing me to auto-fit and how to use it. But I feel that the html layout I was creating was not helping me when using CSS Grid. I am going to reference the course again for help
-   Also I am proud that I continue using semantic tags! Nice!

## Next Steps

My Goals for next project are:

-   Create a paper mockup detailing out all the html elemtns I will use and how it will be laid out. I will take a picture and also upload it to GitHub
-   Use less extra html tags that are not necessary
-   Use the Wesbos CSS grid course last two lessons as a referenece to see how it was coded and where CSS grid was applied
-   Practice using CSS Grid to help build responsive websites

## Technologies:

-   HTML
-   CSS
-   CSS Grid
-   Netlify
