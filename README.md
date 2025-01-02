
# Cotton Weave CSS 😊
![My Banner](https://media.istockphoto.com/id/2184545239/photo/sunset.webp?a=1&b=1&s=612x612&w=0&k=20&c=oTseXdLBD7NjFaI-uwDfHwHcFZl8Uj9cEJ8lJ9-ZgfU=)

Today I Completed this Project and here is my journey

## code structure tree
# Document Structure

- **div class="main"**
  - **div class="left"**
    - **h1**: *a Cotton Weave.*
    - **div class="bottom_left"**
      - **div class="colors"**
        - **h5**: *Colors*
        - **div class="color1"**
        - **div class="color2"**
      - **h2**: *Details*
      - **p**: *Details text...*
  - **div class="right"**
    - **div class="right_top"**
      - **h4**: *$488*
      - **h5**: *Rating + Stars*
    - **img**: Product Image
    - **div class="black_gola"**
      - **h5**: *Add to Bag*
    - **h2 class="roated"**: *Cotton twill Cap*


# Today I Learn
## 📌Transform-origin 👇
### Explanation of `transform-origin: 0 0;` in CSS

The `transform-origin: 0 0;` property specifies the point of origin for transformations, such as rotations. Here's what it means and how it works in your code:

#### What `transform-origin: 0 0;` Means:
- **`0 0`:** Refers to the top-left corner of the element.
- The transformation (e.g., `rotate`) will pivot around this top-left corner instead of the default center.

#### How It Works in Your Code:
```css
.roated {
    position: absolute;
    left: -10%;
    bottom: 3%;
    transform-origin: 0 0;
    rotate: -90deg;
    font-weight: 600;
}


