# Day 04 Extra curricular activities

## CSS Units: vh, vw, vmin, vmax

<https://www.youtube.com/watch?v=IWFqGsXxJ1E&t=836s>

- vh (viewport height):
  - vh represents a percentage of the viewport height.
  - 1 vh is equal to 1% of the viewport height.
  - For example, if the viewport height is 800 pixels, 1 vh is equal to 8 pixels (1% of 800 pixels).
  
- vw (viewport width):
  - vw represents a percentage of the viewport width.
  - 1 vw is equal to 1% of the viewport width.
  - For example, if the viewport width is 1200 pixels, 1 vw is equal to 12 pixels (1% of 1200 pixels).

- vmin (viewport minimum):
  - vmin represents the smaller value between the viewport width and height.
  - 1 vmin is equal to 1% of the smaller dimension (width or height) of the viewport.
  - It ensures that the specified length is relative to the smaller dimension, maintaining aspect ratio responsiveness.

- vmax (viewport maximum):
  - vmax represents the larger value between the viewport width and height.
  - 1 vmax is equal to 1% of the larger dimension (width or height) of the viewport.
  - It ensures that the specified length is relative to the larger dimension, accommodating different aspect ratios.

---

**viewport?**
viewport" refers to the visible area of a web page within a web browser window or device screen. It represents the portion of the document that the user can see and interact with.

## Different between percentage and vw,vh,vmin, vmax

percentage work accordingly to it's parent whereas viewport units (vw, vh..) work accordingly to device width and height.
