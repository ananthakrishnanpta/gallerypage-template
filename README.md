# gallerypage-template :-> [https://ananthakrishnanpta.github.io/gallerypage-template/](https://ananthakrishnanpta.github.io/gallerypage-template/)

- Creating a responsive image gallery using HTML and CSS with Flexbox : 

### Explanation
1. **HTML Structure**:
    - The HTML contains a `div` with the class `gallery` that wraps multiple `div` elements each with the class `gallery-item`. Each `gallery-item` contains an `img` element.
    
2. **CSS Styling**:
    - `body`: Sets margin to 0 and specifies the font.
    - `.gallery`: Uses Flexbox to create a flexible, responsive layout. `flex-wrap: wrap;` ensures that items wrap to the next line when necessary. `justify-content: center;` centers the gallery items.
    - `.gallery-item`: Defines the flexible behavior and margin for each item. `flex: 1 1 calc(25% - 10px);` makes each item take up 25% of the container width minus a small margin for spacing.
    - `.gallery-item img`: Ensures images take up the full width of their container while maintaining their aspect ratio.
    - Media queries adjust the layout for different screen widths:
        - **1200px and below**: Each item takes up 33.33% of the container width.
        - **800px and below**: Each item takes up 50% of the container width.
        - **500px and below**: Each item takes up 100% of the container width.

You can replace `image1.jpg`, `image2.jpg`, etc., with your own image paths. This layout will create a responsive gallery that adjusts the number of images per row based on the screen size.
