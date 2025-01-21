# CSS Gradients, Transitions, and Transforms Exercise

This exercise introduces students to modern CSS techniques that enhance the visual design and interactivity of web pages. It focuses on **gradients**, **transitions**, **transforms**, and practical hover effects. Students will gain hands-on experience applying these techniques to create engaging and responsive web designs.

---


## 1. CSS Gradients
Gradients allow for smooth transitions between colors, which can be applied to backgrounds or other elements. Types of gradients:
- **Linear Gradient**: Transitions colors along a straight line.
  - **Syntax**: 
    ```css
    background: linear-gradient(direction, color-stop1, color-stop2, ...);
    ```
   - **Example**:
      ```css
      background: linear-gradient(to right, red, blue);
      ```
    - **Direction**:
      - `to right`: Gradient flows from left to right.
      - `45deg`: Gradient flows diagonally at a 45-degree angle.

- **Radial Gradient**: Colors radiate outward from a center point.
  - **Syntax**:
    ```css
    background: radial-gradient(shape size, color-stop1, color-stop2, ...);
    ```
   - **Example**:
      ```css
      background: radial-gradient(circle, yellow, green);
      ```
    - **Shape**:
      - `circle`: Creates a circular gradient.
      - `ellipse`: Creates an elliptical gradient.

- **Repeating Gradient**: Repeats the gradient pattern.
  - **Syntax**:
    ```css
    background: repeating-linear-gradient(direction, color-stop1, color-stop2);
    ```
   - **Example**:
      ```css
      background: repeating-linear-gradient(45deg, red, blue 10px, red 20px);
      ```

---

## 2. CSS Transitions
Transitions allow smooth animations of CSS property changes over a set duration. Common properties:
- **Transition Property**: Specifies the CSS property to animate.
  - **Syntax**:
    ```css
    transition-property: property-name;
    ```
   - **Example**:
      ```css
      transition-property: background-color;
      ```

- **Transition Duration**: Sets the time the animation takes to complete.
  - **Syntax**:
    ```css
    transition-duration: time;
    ```
   - **Example**:
      ```css
      transition-duration: 0.5s;
      ```

- **Transition Timing Function**: Controls the pace of the animation.
  - **Syntax**:
    ```css
    transition-timing-function: linear | ease | ease-in | ease-out | ease-in-out;
    ```
   - **Example**:
      ```css
      transition-timing-function: ease-in-out;
      ```

- **Transition Delay**: Adds a delay before the animation starts.
  - **Syntax**:
    ```css
    transition-delay: time;
    ```
   - **Example**:
      ```css
      transition-delay: 0.2s;
      ```

- **Shorthand**:
  - **Syntax**:
    ```css
    transition: property duration timing-function delay;
    ```
   - **Example**:
      ```css
      transition: background-color 0.5s ease-in-out 0.2s;
      ```

---

## 3. CSS Transforms
Transforms allow you to manipulate elements in 2D or 3D space.

- **Scale**: Resizes the element.
  - **Syntax**:
    ```css
    transform: scale(x, y);
    ```
   - **Example**:
      ```css
      transform: scale(1.2);
      ```

- **Rotate**: Rotates the element clockwise or counter-clockwise.
  - **Syntax**:
    ```css
    transform: rotate(angle);
    ```
   - **Example**:
      ```css
      transform: rotate(45deg);
      ```

- **Translate**: Moves the element horizontally and/or vertically.
  - **Syntax**:
    ```css
    transform: translate(x, y);
    ```
   - **Example**:
      ```css
      transform: translate(50px, 100px);
      ```

- **Skew**: Tilts the element along the X or Y axis.
  - **Syntax**:
    ```css
    transform: skew(x-angle, y-angle);
    ```
   - **Example**:
      ```css
      transform: skew(20deg, 10deg);
      ```

- **3D Transforms**:
  - **RotateX**: Rotates around the horizontal X-axis.
    - **Syntax**:
      ```css
      transform: rotateX(angle);
      ```
    - **Example**:
      ```css
      transform: rotateX(45deg);
      ```

  - **RotateY**: Rotates around the vertical Y-axis.
    - **Syntax**:
      ```css
      transform: rotateY(angle);
      ```
    - **Example**:
      ```css
      transform: rotateY(45deg);
      ```


