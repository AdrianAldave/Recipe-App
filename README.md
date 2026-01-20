# Recipe Server App 🍳

A heartfelt iOS app preserving and sharing my grandmother's traditional Peruvian recipes. Built with SwiftUI to keep family culinary traditions alive and accessible for future generations.

## About

This app serves as a digital cookbook containing authentic Peruvian recipes passed down from my grandmother. It allows family members to browse, view, and add traditional recipes, ensuring these cherished family traditions are never lost.

## Features

- 📖 Browse collection of traditional Peruvian recipes
- 🔍 View detailed recipe instructions and ingredients
- ➕ Add new family recipes to the collection
- 🏷️ Organize recipes by category (appetizers, mains, desserts, etc.)
- 💚 Beautiful, intuitive SwiftUI interface
- 📱 Native iOS experience

## Tech Stack

- **SwiftUI** - Modern declarative UI framework
- **MVVM Architecture** - Clean separation of concerns
- **Swift** - iOS native development
- **Xcode** - iOS development environment

## Project Structure

```
RecipeServer/
├── Views/
│   ├── RecipeCard.swift          # Recipe preview cards
│   ├── RecipeList.swift          # Main recipe listing
│   └── Detail/
│       ├── RecipeView.swift      # Full recipe details
│       ├── AddRecipeView.swift   # Form to add new recipes
│       └── CategoryView.swift    # Filter by category
├── ViewModels/
│   └── RecipeViewModel.swift     # Business logic & data handling
├── Models/
│   └── RecipeModel.swift         # Recipe data structure
└── RecipeServerApp.swift         # App entry point
```

## Installation

1. Clone the repository
2. Open `RecipeServer.xcodeproj` in Xcode
3. Select your target device or simulator
4. Press `Cmd + R` to build and run

## Requirements

- iOS 15.0+
- Xcode 13.0+
- macOS 12.0+ (for development)

## Usage

1. **Browse Recipes:** Scroll through the recipe list on the home screen
2. **View Details:** Tap any recipe card to see full instructions and ingredients
3. **Add Recipe:** Tap the '+' button to add a new family recipe
4. **Filter by Category:** Use category view to find specific types of dishes

## Recipes Included

Traditional Peruvian dishes such as:
- Lomo Saltado
- Ají de Gallina
- Causa Limeña
- Papa a la Huancaína
- And many more family favorites!

## Future Enhancements

- [ ] Search functionality
- [ ] Favorite recipes
- [ ] Share recipes with family members
- [ ] Photo uploads for each dish
- [ ] Cooking timer integration
- [ ] Ingredient shopping list

## Personal Note

This app was created to honor my grandmother's legacy and ensure her recipes continue to bring joy to our family for generations to come. Every dish tells a story of Peru and our family history.

## License

Personal family project - Free to use and modify for preserving your own family recipes.

---

*Made with ❤️ to preserve Peruvian culinary traditions*
