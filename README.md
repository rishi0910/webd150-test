# Web3 Shopping Cart


A responsive single-page application (SPA) built with React, Vite, and Tailwind CSS that displays products from the FakeStore API with search functionality.

##  Features

- **Real-time Search**: Filter products by title as you type
- **API Integration**: Fetches products from FakeStore API
- **Modern UI**: Clean design with Tailwind CSS
- **Loading States**: Proper loading and error handling

##  Tech Stack

- **Framework**: React 
- **Build Tool**: Vite
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **API**: FakeStore API (https://fakestoreapi.com/products)

```

##  Components

### Header Component
- Fixed navigation bar with title and search functionality
- Real-time search input with Lucide search icon
- Responsive design with proper spacing

### ProductCard Component
- Product image with responsive container
- Product title and formatted price ($XX.XX USD)
- "View Details" button with hover effects

### ProductList Component
- Responsive grid layout:
  - Mobile: 1 column
  - Tablet: 2 columns
  - Desktop: 3 columns

### App Component
- State management for products, loading, error, and search
- API data fetching with useEffect
- Search filtering logic

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn


4. **Open your browser** and visit: `http://localhost:5173`

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build

##  Design Features

- **Color Scheme**: Clean white cards on light gray background
- **Typography**: Modern font hierarchy with proper spacing
- **Shadows**: Subtle shadows for depth and visual hierarchy
- **Hover Effects**: Interactive button states
- **Responsive Images**: Properly scaled product images

## 🔍 Search Functionality

The search bar provides real-time filtering:
- Type "shirt" → Shows products containing "shirt"
- Type "men" → Shows men's clothing items
- Type "ring" → Shows jewelry items
- Case-insensitive search
- Instant results as you type

## 📱 Responsive Breakpoints

- **Mobile**: `grid-cols-1` (default)
- **Tablet**: `sm:grid-cols-2` (640px+)
- **Desktop**: `lg:grid-cols-3` (1024px+)

## 🌐 API Integration

Fetches data from FakeStore API:
- **Endpoint**: `https://fakestoreapi.com/products`
- **Method**: GET
- **Response**: Array of product objects
- **Error Handling**: Displays user-friendly error messages


##  Key Features Implemented

 i.Responsive single-page application  
 ii.React functional components with hooks  
 iii.Vite build configuration  
 iv.Tailwind CSS styling  
 v. API data fetching  
 vi.Search functionality  
 vii. Loading and error states  
 viii. Modern UI/UX design  
 ix.Mobile-first responsive design  


