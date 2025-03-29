Create a modern React application with Tailwind CSS that features a left-hand sidebar and main content area layout. The application should:

1. Use Vite as the build tool with the following configuration:
   - TypeScript support
   - Path aliases with '@/' pointing to the src directory
   - Tailwind CSS integration

2. Set up TypeScript configuration with:
   - Strict type checking
   - React JSX support
   - Module bundler resolution
   - ES2020+ target
   - Proper path aliases

3. Configure Tailwind CSS with:
   - Content paths targeting HTML and TypeScript/TSX files
   - Basic theme extension capabilities

4. Implement ESLint with:
   - React Hooks plugin
   - React Refresh plugin
   - TypeScript ESLint integration
   - Browser globals support

5. Create a responsive layout with:
   - A full-height, screen-filling application container
   - A fixed-width sidebar on the left
   - A flexible main content area that grows to fill available space
   - Proper overflow handling

6. Style the application with:
   - A clean, modern aesthetic
   - Proper font configuration with system fonts
   - Responsive text sizing
   - Dark mode support

7. Include basic navigation in the sidebar with:
   - Links to different sections of the application
   - Visual indicators for active routes
   - Proper spacing and padding

8. Ensure the CSS properly handles:
   - Full viewport height utilization
   - Flex layout for proper distribution of space
   - No unnecessary margins or padding that would cause overflow

Please provide the complete project structure with all necessary configuration files and component implementations.

## Implementation Details

### Tailwind CSS Import
When setting up Tailwind CSS in your stylesheets, use the proper import directive at the top of your main CSS file (e.g., index.css):

```css
@import "tailwindcss";
```

This directive ensures that Tailwind's utility classes are properly loaded and available throughout your application. The rest of your custom CSS should follow this import, as shown in the existing index.css example.
