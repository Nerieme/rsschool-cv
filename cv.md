# Curriculum Vitae

![photo](/images_for_rs/avatar.png)

## Andrey Golovin

### _Contact info:_

-   **Adress:** Tula, Russia
-   **Phone:** +7 (4872) 12-34-56
-   **Email:** hijikatatoshidjo@gmail.com
-   **GitHub:** Nerieme
-   **Discord:** Andrey Golovin (@Nerieme)

---

### _About me:_

---

I am 30 years old. I am an engeneer. For a long time I was interested in how websites are created and work on the Internet. At first I got interested in the issue of website design. I took web design courses and learned a lot of new, interesting things. I also studied various programs for creating design, such as: photoshop, illustrator, indesign, figma, blender, 3ds max. Now I want to know how the site works "under the hood" of a beautiful picture.

---

### _Skills:_

---

-   **Markdown**
-   **HTML**
-   **CSS**
    -   _Sass_
    -   _Scss_
    -   _Bootstrap (basics)_
-   **JavaScript (basics)**
-   **Git / GitHub**
-   **Autodesk**
    -   _3DS Max_
    -   _Maya_
    -   _AutoCAD_
-   **Adobe**
    -   _Photoshop_
    -   _Illustrator_
    -   _InDesign_
-   **Figma**

---

### _Code example:_

---

let me introduce you **7 kyu kata from CodeWars**:

The Menger Sponge is a three-dimensional fractal, first described by Karl Menger in 1926.
![cubes](/images_for_rs/V6Rb4Za.jpeg)

1. Start from a cube (first part of image).
2. Scale down the cube so that side length is 1/3 of its original, and make 20 copies of it.
3. Place the copies so that they measure the same size as the original cube but without its central parts (next part of image)
4. Repeat the process from step 2 for the new smaller cubes from the previous step.
5. In each iteration (e.g. repeating the last three steps), the effect will be that parts of the cube will be removed, they'll never be added. Menger sponge will always consist of parts will never be removed, regardless of how many iterations you do.

**Task:** In this kata you will create a function that takes non negative integers (from 0 to n) and return the amount of cubes that the Menger Sponge would have in that specific iteration.

```
function calc_ms(n) {
  let cube = 1;
  if (n === 0) {
    return 1
  } else if (n < 0) {
    return "You broke the universe..."
  } else

  for (let i = 1; i <= n; i++) {
    cube *= 20;
  }

  return cube;
}
```

---

### _Courses:_

---

-   Some HTML and CSS courses from [WebReference](https://webref.ru/course)
-   Some articles from [htmlbook](http://htmlbook.ru/samhtml)
-   Some self-study on [MDN](https://developer.mozilla.org/ru/docs/Web)
-   **FrontEnd Start** Udemy course from Ivan Petrychenko

---

### _Languages:_

---

> London is the capital of Great Britain
