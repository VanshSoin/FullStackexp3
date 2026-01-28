Summary of Experiment 3: React Routing
Overview
<img width="1919" height="906" alt="Screenshot 2026-01-28 115820" src="https://github.com/user-attachments/assets/5f24e497-d822-44a4-b376-6ec8fcc7a46e" />
<img width="1919" height="972" alt="Screenshot 2026-01-28 115809" src="https://github.com/user-attachments/assets/ad3a9b93-1eb5-4a90-96d7-38a04a955891" />
<img width="1919" height="896" alt="Screenshot 2026-01-28 115729" src="https://github.com/user-attachments/assets/a693a59f-2882-450c-ab54-87352bd5ccbd" />
<img width="1919" height="913" alt="Screenshot 2026-01-28 115716" src="https://github.com/user-attachments/assets/b8acb64f-2638-4b04-ac76-3213fb8c2926" />
<img width="1919" height="958" alt="Screenshot 2026-01-28 115654" src="https://github.com/user-attachments/assets/27fda975-c686-4046-88d5-e180b16e9a83" />
<img width="1919" height="974" alt="Screenshot 2026-01-28 115607" src="https://github.com/user-attachments/assets/a78a56cf-e51a-4bda-81b3-940cb59b2bb6" />
<img width="1919" height="970" alt="Screenshot 2026-01-28 115550" src="https://github.com/user-attachments/assets/327aaa9f-cf86-456d-b1eb-1ccceb067a4d" />


Routing1: Basic Routing Fundamentals
What You Implemented:
Created three simple components: Home, Contact, and About
Set up basic routing with three different routes
Theory & Concepts:
React Router DOM is a library that enables navigation between different views/components in a React application without page reloads, creating a Single Page Application (SPA).

Key Components Used:

BrowserRouter: Wraps the entire application to enable routing functionality using HTML5 history API
Routes: Container component that holds all route definitions
Route: Defines individual routes with a path and corresponding element to render
How It Works:

When user navigates to /, the Home component renders
When user navigates to /contact, the Contact component renders
When user navigates to /about, the About component renders
Navigation occurs by manually typing URLs in the browser address bar
Routing2: Component-Based Routing with Styling
What You Implemented:
Created two routes: /profile and /dashboard
Added personalized content (your name "VANSH SOIN", skills)
Applied CSS styling using App.css
Theory & Concepts:
This experiment reinforced the same routing concepts but focused on:

Component Design: Each route renders a more complex component with multiple elements styled using CSS classes

Practical Application:

Profile page displays personal information
Dashboard page shows skills/technologies
Demonstrates how different sections of a website can be separate routes
CSS Integration: Used .container class to style components, showing how routing works seamlessly with styled components

Routing3: Navigation with Link Component
What You Implemented:
Same two routes (/profile and /dashboard) as Routing2
Added navigation bar with clickable links
Enhanced content with additional information
Theory & Concepts:
The Link Component: Most important addition in this experiment

<a> tags cause full page reload (defeats SPA purpose)
Link component from React Router performs client-side navigation
Prevents page refresh, maintains application state
Provides better performance and user experience
Navigation Bar Pattern:

How It Works:

Clicking links updates the URL without reloading the page
React Router intercepts the navigation
Renders the appropriate component based on the path
Browser history is maintained (back/forward buttons work)
Additional Features:

Used marquee tag for animated welcome message
Expanded skills list to show progression
Added descriptive paragraph in Profile
Key Theoretical Concepts Learned
1. Single Page Application (SPA)
Entire application loads once
Content changes dynamically without page reloads
Better user experience, faster navigation
2. Declarative Routing
Routes are defined declaratively using JSX
Clear mapping between URLs and components
Easy to understand and maintain
3. Client-Side Routing
Routing happens in the browser (client-side)
No server request needed for navigation
JavaScript handles URL changes and component rendering
4. Component-Based Architecture
Each route renders a React component
Components are reusable and modular
Separation of concerns
5. Browser History API
BrowserRouter uses HTML5 History API
Enables clean URLs (no hash #)
Back/forward navigation works seamlessly
Progression Summary
Routing1 → Basic routing setup (foundation)
Routing2 → Styled components with routing (practical application)
Routing3 → Navigation links for better UX (complete SPA experience)

This progression demonstrates the evolution from understanding routing mechanics to building a fully functional, user-friendly single-page application with proper navigation patterns.
