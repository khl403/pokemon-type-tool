# Pokémon Dual-Type Matchup Calculator

## 🌟 About This Project

The **Pokémon Dual-Type Matchup Calculator** is a web application designed to help users easily check and analyze the complex type matchups in the Pokémon games. It allows for quick understanding of offensive and defensive type advantages and disadvantages for both single-type and dual-type Pokémon through an intuitive user interface.

## ✨ Key Features

  * **All 18 Types Supported**: Includes all official Pokémon types.
  * **Offensive Matchup Calculation**: Based on the selected primary type, it shows which types are super effective (2x), not very effective (0.5x), or have no effect (0x) against.
  * **Defensive Matchup Calculation (Single/Dual-Type)**:
      * For a single selected type, it displays weaknesses (2x), resistances (0.5x), and immunities (0x).
      * For dual-types, it calculates and displays precise defensive matchups by multiplying the effectiveness of each type (resulting in 4x, 2x, 0.5x, 0.25x, 0x).
  * **Interactive UI**:
      * **Select First Type**: Click an icon from the "All Types" list to select the first type.
      * **Create Dual-Type**: Drag another type icon from the "All Types" list and drop it onto the "Selected Type Area" to add it as a second type.
      * **Remove Selected Type(s)**:
          * Click a selected type icon in the "Selected Type Area" to remove it.
          * Alternatively, drag a selected type icon from the "Selected Type Area" and drop it anywhere *outside* this area to remove it.
          * If the first type is removed and a second type was present, the second type becomes the first.
      * **Explore from Results**: Click on any type icon shown in the "Attacking" or "Defending" results sections to quickly see its matchups.
  * **Responsive Design**: Optimized for various screen sizes, including desktops, tablets, and mobile devices.
  * **Web Accessibility**: Basic accessibility features are supported, including keyboard navigation and ARIA attributes for screen readers.
  * **Ad Banner Slots**: Placeholder areas at the top and bottom of the page are included for potential ad integration.

## 🚀 Live Demo

You can try out the calculator live at the following link:
`[ Enter your published website URL here ]` (e.g., `https://your-username.github.io/your-repository-name/`)

## 🛠️ Technologies Used

  * **HTML5**: Structures the web page.
  * **CSS3**: Styles the application, utilizing the Tailwind CSS framework for a modern and responsive design.
  * **JavaScript (Vanilla)**: Implements all dynamic functionalities, including type selection, matchup calculations, and drag-and-drop features, without external libraries.

## 🎮 How to Use

1.  **Select First Type**:
      * Click on a type icon from the "All Types" list with your mouse, or focus on it using your keyboard and press Enter or Space.
      * The selected type will appear in the "Selected Type Area" below, and its offensive/defensive matchups will be displayed at the bottom of the page.
2.  **Select Second Type (for Dual-Type Configuration)**:
      * Drag another type icon from the "All Types" list.
      * Drop the dragged icon onto the "Selected Type Area" where the first type is displayed.
      * Both types will now be shown, and the "Defending" matchups will be updated based on the dual-type calculation.
3.  **Remove Selected Type(s)**:
      * **By Clicking**: Click again on a type icon within the "Selected Type Area" to remove it.
          * If you click to remove the first type while a second type is present, the second type will become the first.
          * If you click to remove the second type, only the second type will be removed.
      * **By Dragging Out**: Drag a type icon from the "Selected Type Area" and drop it anywhere **outside** this designated area to remove it.
          * If the first type is dragged out and a second type was present, the second type becomes the first.
4.  **Explore Further from Results**:
      * Type icons displayed in the "Attacking" or "Defending" results sections are also clickable (or selectable via keyboard).
      * Choosing a type from the results will immediately update the calculator to show matchups for that newly selected type.

## 💻 How to Run Locally

1.  Download the `index.html` file (or the HTML file you saved for this project).
2.  Open the downloaded `index.html` file directly in your web browser (such as Chrome, Firefox, Edge, etc.).
      * You can usually do this by dragging the file into an open browser window or by right-clicking the file and selecting "Open with" followed by your preferred browser.

## 💡 Potential Future Enhancements (Optional)

  * Implement a search function to look up Pokémon by name and automatically load their types.
  * Consider the effects of Pokémon Abilities on type matchups.
  * Add functionality to calculate the effectiveness of specific Pokémon moves (based on move type).

-----

Save this content as `README.md` in the root directory of your project.
