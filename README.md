# React Tabbed Component (How react works)

This project showcases how **React** uses **props** and **state** to create an interactive tabbed interface.

## Features

- **Dynamic Tabs**: Switch between tabs to view unique content or render a special placeholder for undefined tabs.
- **Toggleable Details**: Show/hide tab details.
- **Like Counter**: Increment likes per tab.

---

## Components

### 1. `App`

- Passes tab content (`content` array) to the `Tabbed` component.

### 2. `Tabbed`

- Manages active tab state (`activeTab`).
- Renders:
  - `Tab` buttons for navigation.
  - `TabContent` or `DifferentContent` based on active tab.

### 3. `Tab`

- Button for selecting a tab. Styled dynamically if active.

### 4. `TabContent`

- Displays tab details with local state to toggle visibility and track likes.

### 5. `DifferentContent`

- Placeholder for tabs outside the defined range, resetting local state.

---

## Key Concepts

- **Props**: Share data and behavior between components.
- **State**: Manage dynamic data like active tabs, likes, and visibility.
- **Conditional Rendering**: Switch components and content based on state.

---

## Usage

1. Clone and install:
   ```bash
   git clone https://github.com/amuhammed005/interactive-react-tabbed-interface.git && cd && npm install
   ```
2. Start the server:
   ```bash
   npm start
   ```
3. Modify the `content` array in `App` to add or update tabs.
