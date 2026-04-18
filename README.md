# Build-a-Shopping-List-App
A simple, interactive shopping list application built with React. Users can search for items and check them off as they shop.

Features
Search Functionality - Filter items in real-time by typing in the search box
Toggle Items - Click checkboxes to mark items as purchased (with strikethrough effect)
Responsive Design - Clean, accessible UI with proper form labels and ARIA descriptions
Performance Optimized - Uses useMemo and useCallback for efficient rendering
Components
ShoppingList
Main component that manages the shopping list state and UI.

State
query - Current search query string
selectedItems - Array of selected/purchased items
Hooks
useMemo - Memoizes filtered items based on search query
useCallback - Memoizes the toggleItem function
Usage
import { ShoppingList } from './ShoppingList';

export default function App() {
  return <ShoppingList />;
}
