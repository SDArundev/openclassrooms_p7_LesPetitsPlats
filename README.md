# Les Petits Plats 🍳

A modern recipe search application that allows users to easily find cooking recipes using a powerful search and filtering system.

## 🌟 Features

- **Advanced Search System**: Search recipes by name, ingredients, or description
- **Real-time Filtering**: Dynamic filtering with multiple criteria
- **Tag-based Filtering**: Add/remove tags to refine your search
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Recipe Cards**: Beautiful display of recipes with images and details
- **Ingredient Lists**: Clear presentation of ingredients and quantities
- **Cooking Instructions**: Step-by-step preparation instructions
- **Equipment Information**: Details about required appliances and utensils

## 🛠️ Tech Stack

### Frontend
- **HTML5** - Semantic markup
- **Tailwind CSS** - Utility-first CSS framework for styling
  - `@tailwindcss/line-clamp` - For text truncation
  - Custom configuration for responsive design
- **JavaScript (ES6+)**
  - Modular architecture with ES6 modules
  - Binary search implementation for efficient filtering
  - Async/await for API calls
  - Event-driven architecture
- **Font Awesome** - Icon library for UI elements
- **Google Fonts** - Manrope font family

### Development Tools
- **NPM** - Package management
  - Script automation for development workflow
  - Dependencies management
- **PostCSS** - CSS processing
  - Integration with Tailwind CSS
  - Modern CSS features support
- **Autoprefixer** - CSS compatibility
  - Cross-browser support
  - Vendor prefix management

### Project Architecture
- **API Layer**
  - Custom API class for data fetching
  - JSON data management
- **Components**
  - RecipeCard - Template for recipe display
  - Dropdown - Reusable filter component
  - Tag - Interactive filtering tags
- **Utils**
  - Text normalization for search
  - Recipe filtering algorithms
  - State management utilities

### Performance Features
- Optimized search algorithm using binary search
- Real-time filtering without page reload
- Efficient DOM manipulation
- Lazy loading of recipe images
- Debounced search input

### Data Structure
- JSON-based recipe database
- Normalized data format for:
  - Recipes
  - Ingredients
  - Appliances
  - Utensils

## 📦 Installation

1. Clone the repository:
