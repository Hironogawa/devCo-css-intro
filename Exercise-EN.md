Instructions:

1.  Use the provided HTML file as a starting point for your exercise.

2.  Create a CSS file, name it styles.css and link it to your HTML document.
3.  General Page Styling:

    - Set the background color of the body to #9f9f9f.
    - Apply a suitable font-family to the entire page. You can use Verdana, Geneva, Tahoma, or a sans-serif font.
    - Remove the default margin and padding from the body by setting both to 0.

4.  main element Styling:

    - Style the main container as follows (use the HTML element main):
      - Display its content as a column (display flex), with the flex-direction property (column).
      - Add padding of 12px to create spacing around the content.

5.  Text Styling:

    - Create CSS rules for text elements with different classes:
      - .title: Style with a font size of 120px and a weight of bold. Ensure there's no margin by setting it to 0.
      - .paragraph: Set the text color to #000000.
      - .paragraph.dark-mode: For this combination selector, change the text color to #eeeeee.
      - .text-size-small: Set the font size to 16px.
      - .text-size-medium: Set the font size to 24px.
      - .text-size-large: Set the font size to 36px.

6.  Layout Container Styling:
    - Create a container with the class .container and specify the following properties:
      - Display its children in a row (use flex-direction/Flexbox).
      - Justify content space-between.
      - Align items in the center.
      - add a gap of 12px between the children.
      - Set a height of 300px.
      - Make it full width (width 100%).
      - Add a margin bottom of 12px.
7.  Box Styling:
    - Style .box elements as follows:
      - Use box-sizing to ensure padding doesn't affect the element's total width and height calculations (border-box).
      - Set the height and width to 100%.
      - Set the width to 100%.
      - Add padding of 12px.
      - Set the background color to #00ffbf.
      - Create a .box h2 combination selector to style h2 elements inside .box elements and set the margin to 0.
8.  Background Color Class:

    - Create a class .bg-red that sets the background color to #ff0000.

9.  Create unique IDs for box 1 and box 2, the two boxes should be identical besides the background color:
    - Styling for #box-1:
      - Use box-sizing to specify that padding should be included in the element's total width and height calculations (border-box).
      - Set the height and width of #box-1 to 100%, making it take up the full height and width of its containing element.
      - Add padding of 12px to provide spacing inside the element.
      - Set the text color to #eeeeee (light gray).
      - Set the background color to #0d2927 (a dark teal or blue-green).
    - Styling for #box-2:
      - Copy the styling from #box-1 and apply it to #box-2.
      - Change the background color to #515e78 (a muted blue-gray color).
10. Headings Styling:

    - Style all h2 elements on the page:
    - Remove margin by setting it to 0.
      - Set the font size to 32px.

11. Transformation Effects:
    - Create a class .transform-width with the following properties:
      - Set a min-width of 600px.
      - Add a transition effect for min-width over 0.5s using ease-in-out.
      - Create a combination class .transform-width:hover with the following properties:
        - Use the :hover pseudo-class to increase the min-width to 1200px on hover,also add a cursor pointer.
12. Animation Effects:

    - Define animation keyframes for the following classes:

      - Create a class .animate-text-color:

        - Add the color #fff to the class and the animation name color with a duraion of 1s linear infinite.
        - Create an animation (@keyframe) called color that transitions text color:
          - Set the text color to #eeeeee (light gray) at 0%
          - Set the text color to #000000 (black) at 50%
          - Set the text color to #eeeeee (light gray) at 100%

      - Create a class .animate-rotate:

        - Add an animation name rotate with a duration of 5s linear infinite.
        - Add transform-origin: center to the class.
        - Create an animation (@keyframe) called rotate for rotation:
          - Set a tranform rotate of 0deg at 0%
          - set a transform rotate of 180deg at 50%
          - Set a transform rotate of 360deg at 100%

      - Create a class .animate-wiggle:

        - Add an animation name wiggle with a duration of 1s ease-in-out infinite.
        - Create an animation (@keyframe) called wiggle for a wiggling effect:
          - Set a transform translateX of 12px at 0%
          - Set a transform translateX of -12px at 50%
          - Set a transform translateX of 12px at 100%

      - Create a combination class .animate-shake:hover:
        - Add a cursor pointer to the class.
        - Add an animation name shake with a duration of 0.25s ease-in-out infinite.
        - Create an animation (@keyframe) called shake that activates on hover for a shaking effect:
          - Set a tranform translate of 9px, 3px at 0%
          - Set a transform translate of -9px, -3px at 50%
          - Set a transform translate of 9px, 3px at 100%
      - Create a class .animate-mix:
        - Add transform-orign: center to the class.
        - Add both animation color and rotate, comma-separated, to the class.
        - Color has a duration of 1s linear infinite.
        - rotate has a duration of 5s linear infinite.

13. Testing and Customization:

    - Test your webpage to ensure it displays as intended.
    - Add classes to the HTML elements to apply the styles you've created or modify the CSS selectors to match the HTML elements.
    - Feel free to customize the content and apply your own creativity while adhering to the provided guidelines.

    Try to accomplish the exercise without looking at the final CSS code provided earlier. Once you've completed the exercise, you can compare your solution to the final CSS code to see how closely you matched the desired styles and animations.
