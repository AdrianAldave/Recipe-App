# Recipe Server App 🍳

A native iOS recipe management application built with SwiftUI that allows users to browse, organize, and save their favorite recipes.

## Features

- 📱 Native iOS experience with SwiftUI
- 🔍 Browse recipes by category
- ➕ Add custom recipes
- 📋 Detailed recipe views with ingredients and instructions
- 🎨 Clean, modern UI design
- 💾 Local data persistence

## Tech Stack

- **Language:** Swift
- **Framework:** SwiftUI
- **Architecture:** MVVM (Model-View-ViewModel)
- **Platform:** iOS

## Project Structure

```
RecipeServer/
├── Components/
│   ├── RecipeCard.swift          # Reusable recipe card component
│   └── RecipeList.swift          # List view for recipes
├── Detail/
│   ├── AddRecipeView.swift       # Form to add new recipes
│   ├── CategoryView.swift        # Category browsing interface
│   └── RecipeView.swift          # Detailed recipe display
├── Models/
│   ├── RecipeModel.swift         # Data model for recipes
│   └── Assets.xcassets/          # App icons and colors
├── ViewModels/
│   └── RecipeViewModel.swift    # Business logic and state management
├── Views/Main/
└── RecipeServerApp.swift         # App entry point
```

## Architecture

This app follows the **MVVM** (Model-View-ViewModel) pattern:

- **Model:** `RecipeModel.swift` - Defines recipe data structure
- **View:** SwiftUI views in `Detail/` and `Components/`
- **ViewModel:** `RecipeViewModel.swift` - Manages app state and business logic

## Requirements

- iOS 15.0+
- Xcode 13.0+
- Swift 5.5+

## Installation

1. Clone the repository:
```bash
git clone [your-repo-url]
```

2. Open the project in Xcode:
```bash
cd RecipeServer
open RecipeServer.xcodeproj
```

3. Build and run:
   - Select your target device or simulator
   - Press `Cmd + R` to run

## Usage

1. **Browse Recipes:** View all available recipes on the main screen
2. **View Recipe Details:** Tap any recipe card to see full ingredients and instructions
3. **Add New Recipe:** Tap the "+" button to create a new recipe
4. **Filter by Category:** Use category view to organize recipes by type

## Key Components

### RecipeCard
Reusable card component displaying recipe preview with image, title, and basic info.

### RecipeList
Scrollable list container for displaying multiple recipe cards.

### AddRecipeView
Form interface for creating new recipes with fields for:
- Recipe name
- Ingredients
- Instructions
- Category
- Image

### RecipeViewModel
Handles all business logic including:
- Recipe data management
- Add/Edit/Delete operations
- Category filtering
- Data persistence

## Future Enhancements

- [ ] Cloud sync across devices
- [ ] Recipe sharing functionality
- [ ] Search and filter options
- [ ] Cooking timer integration
- [ ] Nutrition information
- [ ] Shopping list generation

## License

Free to use for personal projects.

## Author

[Your Name]

## Acknowledgments

Built with SwiftUI and following Apple's design guidelines.
