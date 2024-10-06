### Project Summary: Spell Checker Application

This project is a simple **Spell Checker Application** built using Python and the `pyspellchecker` library. The application takes user input as text, checks each word for spelling errors, and provides corrections for any misspelled words.

#### Key Features:
- **Text Input:** Users can input any text to check for spelling mistakes.
- **Word-by-Word Correction:** The app processes the text by splitting it into words and checking each word using the spell checker library.
- **Automatic Correction:** For any detected misspelling, the app suggests and replaces the incorrect word with its corrected version.
- **Real-Time Feedback:** The application prints the corrections made for each misspelled word.
- **Exit Functionality:** Users can type "exit" to close the application gracefully.

#### Technologies Used:
- **Python:** Core language used to build the app.
- **pyspellchecker Library:** Used to perform spelling corrections.

#### Project Structure:
1. **Class Structure:** 
   - A `SpellCheckerApp` class encapsulates the core functionality of the spell checker, making the code modular and reusable.
2. **Methods:**
   - `correct_text`: This method splits the text into words, checks each word, and returns the corrected version.
   - `run`: The main loop where the user inputs text, corrections are applied, and results are displayed.
3. **Error Handling & Exiting:** The app allows users to exit by typing "exit", making it user-friendly.
