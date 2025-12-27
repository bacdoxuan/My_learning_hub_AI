# MySQL Knowledge Base Visual Design Scheme

## Design Philosophy

### Color Palette

- **Dark Theme Base**: Deep navy gradient (#0f172a to #0b1222) with subtle purple/blue accent gradients
- **Module-Specific Gradients**: Each module has a unique gradient theme following the MongoDB pattern
- **Accent Colors**:
  - Teal/Cyan (#7dd3fc) for primary actions
  - Purple (#a78bfa) for secondary elements
  - Green (#34d399) for success states
  - Orange (#fbbf24) for warnings
  - Red (#fb7185) for errors

### Typography

- **Primary Font**: System UI stack (ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial)
- **Monospace Font**: Consolas, Monaco for code blocks
- **Font Hierarchy**:
  - Headers: 1.3-2em with bold weights
  - Body: 13-14px for readability
  - Code: 0.85em for density

## Visual Effects & Styling

### Used Libraries

- **Pure CSS**: No external dependencies
- **CSS Grid & Flexbox**: For responsive layouts
- **CSS Custom Properties**: For theme consistency
- **Vanilla JavaScript**: For all interactivity

### Header Effects

- **Gradient Backgrounds**: Module-specific gradients with teal/blue accents
- **Card Hover Effects**: Transform translateY(-5px) with enhanced shadows
- **Smooth Transitions**: 0.3s ease for all interactive elements

### Animation & Interactivity

- **Search & Filter**: Real-time filtering with smooth transitions
- **Card Interactions**: Hover states with shadow expansion
- **Code Syntax Highlighting**: CSS-based keyword highlighting
- **Responsive Design**: Mobile-first approach with breakpoints at 768px and 1120px

## Module-Specific Color Schemes

### Module 1: Foundations (Green/Teal)

- Background: linear-gradient(135deg, #134e5e 0%, #71b280 100%)
- Header: linear-gradient(135deg, #11998e 0%, #38ef7d 100%)
- Accent: #38ef7d

### Module 2: Database Design (Purple)

- Background: linear-gradient(135deg, #0f0c29 0%, #302b63 100%)
- Header: linear-gradient(135deg, #667eea 0%, #764ba2 100%)
- Accent: #764ba2

### Module 3: Intermediate Querying (Blue/Cyan)

- Background: linear-gradient(135deg, #1a2980 0%, #26d0ce 100%)
- Header: linear-gradient(135deg, #2193b0 0%, #6dd5ed 100%)
- Accent: #6dd5ed

### Module 4: Performance & Optimization (Orange/Red)

- Background: linear-gradient(135deg, #ff416c 0%, #ff4b2b 100%)
- Header: linear-gradient(135deg, #f093fb 0%, #f5576c 100%)
- Accent: #f5576c

### Module 5: Programmability (Indigo/Pink)

- Background: linear-gradient(135deg, #667eea 0%, #764ba2 100%)
- Header: linear-gradient(135deg, #f093fb 0%, #f5576c 100%)
- Accent: #f5576c

### Module 6: Administration (Deep Blue)

- Background: linear-gradient(135deg, #2c3e50 0%, #3498db 100%)
- Header: linear-gradient(135deg, #0f2027 0%, #203a43 100%)
- Accent: #3498db

### Module 7: Security (Red/Dark)

- Background: linear-gradient(135deg, #8e0e00 0%, #1f1c18 100%)
- Header: linear-gradient(135deg, #e52d27 0%, #b31217 100%)
- Accent: #b31217

## Layout & Structure

### Grid System

- **Desktop**: 3 columns (1120px+)
- **Tablet**: 2 columns (768px-1120px)  
- **Mobile**: 1 column (<768px)
- **Gap**: 14-20px between cards

### Card Design

- **Background**: rgba(255,255,255,0.05) with subtle borders
- **Padding**: 14-20px internal spacing
- **Border Radius**: 15-16px for modern feel
- **Hover State**: Enhanced opacity and shadow

### Code Block Styling

- **Background**: #0d1117 (dark github style)
- **Border Left**: 3px accent color
- **Padding**: 15px internal
- **Font**: Consolas/Monaco monospace
- **Syntax Highlighting**: CSS classes for keywords, strings, methods

## Interactive Components

### Search & Filter System

- **Real-time Search**: Instant filtering across all content
- **Tag-based Filtering**: Single-select chip system
- **Result Counter**: Live update of filtered results
- **Clear Functionality**: Reset all filters

### Navigation

- **Index Page**: Master navigation with search
- **Module Pages**: Self-contained with consistent styling
- **Cross-linking**: Internal navigation between related concepts

### Responsive Features

- **Mobile-first**: Optimized for touch interactions
- **Flexible Grid**: Adapts to screen size
- **Readable Typography**: Maintains readability across devices
