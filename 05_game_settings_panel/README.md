# Game Settings Panel

I built a game settings panel. I first coded it by myself as the project itself seemed simple enough to not follow the workshop. Although I had a smooth start I got stuck on a few things, which the workshop explained and I understood better.

---

## Cursor Pointer

I changed the cursor to point at the `label` and `input` elements when a user hovers over them.

---

## Styling checkboxes

I learned to style checkboxes, which was exciting for me as I have never done it. I did this by:

- Adjusting the `width` and `height` of the checkboxes.
- I then used `appearance: none` so that I can re style the checkboxes to my own liking using the `border` property.

---

## `transition` set to allow for smooth checking

I learned how to use the `transition` property so that when user checks the boxes, it is a much smoother process rather than instant. I set the values to `all 0.3s`.

---

## Created a combined type selector with pseudo-class selector.

This was a new one for me, complicated but very cool when it all comes together. That is the beauty of CSS right? Complicated but beautiful!

I wanted to achieve having a checkmark appear after the user has checked the boxes (update content according to user state). Therefore I created a combined type selector with pseudo-class selector. Pheew! This was achieved by setting the property `content: "✓"`, then more additional styling that affected what happens after the user checks the boxes.

What was interesting was setting its `display: block` as normally blocks take up the entire space (of its parent), so I had to remember that its parents this time was the box.

---

**Overall:** I learned a lot, and it opened up my eyes to what more CSS is capable of, and I just started.

---

# Screenshot

![alt text](image.png)
