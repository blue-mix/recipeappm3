
# Recipe App

This is a Recipe app built using Jetpack Compose for the UI. It features a beautiful UI design with a parallax toolbar, a list of recipes, and detailed information about each recipe.

## Features

- Modern UI with Jetpack Compose
- Parallax effect on the toolbar
- LazyColumn for efficient list rendering
- Detailed recipe view with ingredients, steps, and reviews
- Serving calculator
- Shopping list button
- Tab navigation for ingredients, tools, and steps

## Screenshots

<!-- Add screenshots of your app here -->
![Screenshot 1](screenshots/screenshot1.png)
![Screenshot 2](screenshots/screenshot2.png)

## Requirements

- Android Studio Bumblebee or higher
- Gradle 7.0+
- Android API level 21+

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/recipe-app.git
    ```

2. Open the project in Android Studio.

3. Build the project:
    - Select **Build > Make Project** or press `Ctrl+F9`.

4. Run the project:
    - Select a device or emulator and click **Run** or press `Shift+F10`.

## Usage

- The main screen displays a list of recipes.
- Clicking on a recipe opens the detailed view with a parallax toolbar.
- Use the serving calculator to adjust the number of servings.
- Add ingredients to your shopping list by clicking the "Add to shopping list" button.
- View reviews and more images related to the recipe.

## Project Structure
recipe-app\
├── app\
│   ├── src\
│   │   ├── main\
│   │   │   ├── java/com/example/recipeapp\
│   │   │   │   ├── MainActivity.kt\
│   │   │   │   ├── data\
│   │   │   │   │   ├── Recipe.kt\
│   │   │   │   │   └── SampleData.kt\
│   │   │   │   ├── ui\
│   │   │   │   │   ├── components\
│   │   │   │   │   │   ├── CircularButton.kt\
│   │   │   │   │   │   ├── IngredientCard.kt\
│   │   │   │   │   │   ├── EasyGrid.kt\
│   │   │   │   │   │   └── TabButton.kt\
│   │   │   │   │   ├── theme\
│   │   │   │   │   │   ├── Color.kt\
│   │   │   │   │   │   ├── Shape.kt\
│   │   │   │   │   │   ├── Theme.kt\
│   │   │   │   │   │   └── Type.kt\
│   │   │   │   │   ├── MainFragment.kt\
│   │   │   │   │   └── ParallaxToolbar.kt\
│   │   │   └── res\
│   │   │       ├── drawable\
│   │   │       │   ├── ic_arrow_back.xml\
│   │   │       │   ├── ic_arrow_right.xml\
│   │   │       │   ├── ic_favorite.xml\
│   │   │       │   ├── ic_clock.xml\
│   │   │       │   ├── ic_flame.xml\
│   │   │       │   ├── ic_minus.xml\
│   │   │       │   ├── ic_plus.xml\
│   │   │       │   └── ic_star.xml\
│   │   │       ├── layout\
│   │   │       ├── mipmap\
│   │   │       ├── values\
│   │   │       │   ├── colors.xml\
│   │   │       │   ├── strings.xml\
│   │   │       │   ├── styles.xml\
│   │   │       │   └── themes.xml\
│   │   │       └── xml\
│   │   └── AndroidManifest.xml\
│   └── build.gradle\
├── build.gradle\
└── settings.gradle




## Dependencies

- Jetpack Compose
- Material Components
- AndroidX

## Contributing

1. Fork the project.
2. Create your feature branch:
    ```bash
    git checkout -b feature/your-feature
    ```
3. Commit your changes:
    ```bash
    git commit -m 'Add some feature'
    ```
4. Push to the branch:
    ```bash
    git push origin feature/your-feature
    ```
5. Open a pull request.


