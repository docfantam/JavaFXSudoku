# JavaFX Sudoku

Sudoku game using JavaFX library with persistence - so you can save the game state locally and continue from where you left off.

## Configuration to build and run on Intellij IDEA

1. Install [Oracle JDK](https://www.oracle.com/java/technologies/javase-downloads.html) (>= v11)

2. Download [Open JavaFX](https://gluonhq.com/products/javafx/) (>= v11) and extract the archive

3. Go to File > Project Structure > Project Settings

   - Under Project > Project SDK, choose the correct JDK version

   - Under Libraries, click + button and select the path to lib/ folder in the extracted Open JavaFX archive

   - Click OK, OK, Apply and OK

4. Go to Run > Edit Configurations > Add VM Options

   - For Windows, use: --module-path "\path\to\javafx-sdk\lib" --add-modules javafx.controls,javafx.fxml

   - For Linux/Mac, use: --module-path /path/to/javafx-sdk/lib --add-modules javafx.controls,javafx.fxml

   - Click Apply and OK

## Screenshot

![Sudoku game in action](/screenshot.png)
