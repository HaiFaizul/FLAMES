# FLAMES - Visual Spark Calculator ✨💖

A fun, interactive, and visually animated web application to calculate the FLAMES relationship compatibility between two names. This single-page HTML application uses modern CSS for styling and vanilla JavaScript for the logic and animations.

**Live Demo:** [https://your-username.github.io/FLAMES.html](https://your-username.github.io/FLAMES.html)

## What is FLAMES? 🔥

FLAMES is a popular game played by many, especially in school days, to predict the relationship status between two people. The acronym stands for:

*   **F** - Friends
*   **L** - Lovers
*   **A** - Affectionate
*   **M** - Marriage
*   **E** - Enemies
*   **S** - Siblings

The game involves:
1.  Writing down two names.
2.  Striking out common letters between the two names.
3.  Counting the total number of remaining (un-struck) letters. Let this count be `N`.
4.  Using the FLAMES acronym, repeatedly count `N` letters, striking out the letter where the count ends. The process continues with the remaining letters until only one letter from FLAMES is left. This final letter is the predicted relationship.

## Features 🚀

*   **Interactive FLAMES Calculation:** Enter two names and get your FLAMES result.
*   **Visual Animation:** Watch the common letters being struck from the names and the FLAMES letters being eliminated step-by-step.
*   **Modern & Romantic Design:** A visually appealing interface with a pink/purple color palette, heart icons, and romantic fonts.
*   **Responsive:** Adapts to different screen sizes for a good experience on desktop and mobile.
*   **Single HTML File:** All HTML, CSS, and JavaScript are contained within a single `flames.html` file for easy deployment.
*   **Error Handling:** Provides feedback for empty inputs or identical names.
*   **Favicon:** Includes a cute heart favicon.
*   **Footer Credit:** Features a link to the creator's profile.

## Technologies Used 💻

*   **HTML5:** For the basic structure of the web page.
*   **CSS3:** For styling, layout (Flexbox), animations, and responsive design.
    *   CSS Variables for theming.
    *   Subtle hover effects and transitions.
*   **Vanilla JavaScript (ES6+):** For all the interactivity, FLAMES calculation logic, and DOM manipulation for the visual animation.
    *   `async/await` for managing animation delays.
*   **Google Fonts:** For romantic and modern typography (`Pacifico` and `Poppins`).
*   **Embedded SVG:** For the heart icon and favicon to keep it a single-file solution.

## How to Use 🎮

1.  **Open the Web Page:**
    *   Access the live demo link provided above.
    *   OR, download the `flames.html` file and open it in your web browser.
2.  **Enter Names:** Type the first name in the "First Name" field and the second name in the "Second Name" field.
3.  **Visualize FLAMES:** Click the "Visualize FLAMES ✨" button.
4.  **Watch the Magic:** The application will visually:
    *   Display the two names.
    *   Strike out common letters one by one.
    *   Show the count of remaining letters.
    *   Strike out letters from "F L A M E S" based on the count.
5.  **See Your Result:** The final FLAMES letter and its meaning (e.g., Friends, Lovers, Marriage) will be displayed.
6.  **Try Again:** Click the "Try Again?" button to reset and enter new names.
