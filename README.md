# Student Info App

A Vue.js web application that demonstrates modern frontend development concepts including components, routing, state management, and API integration.

## Features

- **Component-Based Architecture**: Reusable Vue components with props and events
- **Client-Side Routing**: Navigation between Home and Students pages using Vue Router
- **API Integration**: Fetch and display data from JSONPlaceholder API with Axios
- **State Management**: Reactive data handling with loading and error states
- **Responsive Design**: Mobile-friendly interface with modern CSS
- **Interactive Elements**: Buttons, forms, and dynamic content updates

## Project Structure

```
student-info-app/
├── index.html              # HTML entry point
├── package.json            # Dependencies and scripts
├── vite.config.js          # Vite configuration
├── README.md               # Project documentation
└── src/
    ├── main.js             # Application entry point
    ├── App.vue             # Root component
    ├── components/         # Reusable components
    │   ├── HeaderComponent.vue
    │   └── StudentComponent.vue
    ├── pages/              # Page components
    │   ├── HomePage.vue
    │   └── StudentsPage.vue
    └── router/             # Vue Router configuration
        └── index.js
```

## Installation and Setup

1. **Install Dependencies**:
   ```bash
   npm install
   ```

2. **Start Development Server**:
   ```bash
   npm run dev
   ```

3. **Open in Browser**:
   Navigate to `http://localhost:3000`

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build

## Application Features

### Home Page
- Welcome section with app overview
- Feature cards highlighting Vue.js capabilities
- Sample student cards with interactive functionality
- Navigation to Students page

### Students Page
- Fetch real data from JSONPlaceholder API
- Loading states with spinner animation
- Error handling with fallback data
- Search and filter functionality
- Student cards with show/hide details
- Remove student functionality

### Components

#### HeaderComponent
- Displays app title
- Navigation menu with router links
- Responsive design

#### StudentComponent
- Displays student information
- Props validation for required fields
- Toggle details functionality
- Remove student event emission
- Hover effects and animations

## Technologies Used

- **Vue 3** - Progressive JavaScript framework
- **Vue Router 4** - Official routing library
- **Axios** - HTTP client for API requests
- **Vite** - Build tool and development server
- **CSS3** - Modern styling with animations

## API Integration

The app uses JSONPlaceholder API for demonstration:
- Endpoint: `https://jsonplaceholder.typicode.com/users`
- Transforms API data to match student structure
- Includes error handling and fallback data
- Loading states during API calls

## Browser Compatibility

- Chrome/Edge 88+
- Firefox 85+
- Safari 14+

## Development Notes

- Uses Vue 3 Composition API patterns
- Responsive grid layouts
- Component prop validation
- Event-driven communication
- Error boundary handling
- Accessibility considerations
