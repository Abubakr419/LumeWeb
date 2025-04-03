# **LumeWeb Editor**

![dark](https://github.com/user-attachments/assets/eb1d69a6-b7ba-4ed8-b681-fac10868c837)

![light](https://github.com/user-attachments/assets/35354fd6-0189-419f-8099-9626510e1f6d)


A simple, in-browser code editor for HTML, CSS, and JavaScript with a live preview pane.

## **What is LumeWeb?**

LumeWeb is a web-based tool designed for front-end web development experimentation and quick prototyping. It provides separate editing areas for HTML, CSS, and JavaScript code, along with an instantly updating preview panel that shows the combined result. It runs entirely within your web browser, requiring no installation or complex setup.

## **Why Use LumeWeb?**

* **Simplicity:** Offers a straightforward interface for basic web development tasks without needing a local development environment.  
* **Live Feedback:** See the results of your code changes immediately in the preview pane, speeding up the development and debugging process.  
* **Convenience:** Includes helpful features like syntax highlighting, theme switching (light/dark), a color picker, and autosave to local storage.  
* **Portability:** Save your entire project (HTML, CSS, JS) as a single HTML file or load existing HTML files to continue working.  
* **Prototyping:** Ideal for quickly trying out HTML structures, CSS styles, or JavaScript snippets.

## **Getting Started**

1. **Open:** Simply open the LumeWeb.html file (or the HTML file containing the editor code) in a modern web browser (like Chrome, Firefox, Edge, or Safari).  
2. **Code:**  
   * Click the **HTML**, **CSS**, or **JavaScript** tabs at the top of the left panel to switch between code editors.  
   * Write your code in the respective editor panels. Syntax highlighting is provided automatically.  
3. **Preview:** The right-hand **Preview** panel will automatically update shortly after you stop typing, showing the rendered result of your HTML, CSS, and JS code combined.  
4. **Use Header Controls:**  
   * **Save:** Use the HTML, CSS, JS buttons to save individual code files, or All to save the entire project as one HTML file.  
   * **Load HTML:** Click this button to load an existing .html file. The editor will attempt to extract the body content, styles, and scripts.  
   * **Color Picker (Palette Icon):** Select or pick colors and insert their HEX values into the active editor.  
   * **Theme (Paintbrush Icon):** Switch between Light and Dark editor themes.  
   * **Title/Icon:** Click the title ("LumeWeb") or the icon to its left to customize them for your project (saved in local storage).  
   * **Resize:** Drag the vertical bar between the editor and preview panels to resize them.

## **Features**

* Tabbed editors for HTML, CSS, and JavaScript.  
* Live preview pane that updates automatically.  
* CodeMirror integration for syntax highlighting, auto-closing tags/brackets, and basic code hinting (Ctrl+Space).  
* Theme switching (Dark/White).  
* Color picker tool with palette and custom selection.  
* Save code to individual .html, .css, .js files.  
* Save the entire project as a single, self-contained .html file.  
* Load existing .html files (attempts to parse body, style, and script tags).  
* Resizable editor/preview panels.  
* Autosave functionality to browser's local storage (prompts to restore on reload if data exists).  
* Customizable project title and icon (saved locally).  
* Basic JavaScript error reporting in the preview pane.

## **How it Works**

LumeWeb is built using standard web technologies:

* **HTML:** Structures the editor interface.  
* **CSS (with Tailwind CSS):** Styles the user interface.  
* **JavaScript:** Handles all editor logic, preview updates, file operations, theming, and interactions.  
* **CodeMirror:** The core library used for the code editing fields.  
* **Browser Local Storage:** Used for autosaving code, theme preference, title, icon, and panel layout.

## **License**

This project code (as provided in the example) includes components under various licenses (Apache 2.0 for the main script example, MIT for CodeMirror/Tailwind, ISC for Lucide Icons, SIL OFL for Inter Font). Please refer to the license comments within the code and the respective project licenses for full details.
