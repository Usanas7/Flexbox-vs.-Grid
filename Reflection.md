Reflection on Using Flexbox vs CSS Grid

During this assignment, I implemented the same set of webpage layouts using both Flexbox and CSS Grid. The process gave me a deeper understanding of how each layout system works, along with their unique strengths and limitations.

At Level 1, both Flexbox and Grid were fairly simple to implement. Since the layout was a single column (header, main, and footer), Flexbox’s flex-direction: column made sense and was straightforward.

At Level 2, things got a bit more complex with the introduction of a sidebar. Using nested Flexbox worked well, but I found myself managing more containers and thinking about alignment and widths carefully. With Grid, I was able to define the column widths (grid-template-columns: 70% 30%) quickly and apply layout areas, making the structure more visually clear. Grid started to show its power here.

By Level 3, which involved a three-column layout with a main content area and two sidebars, CSS Grid clearly stood out. The use of grid-template-areas allowed me to name sections and visualize the layout more easily. I struggled slightly more with Flexbox at this stage — handling column alignment and responsive behavior was trickier.

In Level 4, Grid again proved to be more structured and easier to scale. Managing a fixed header, collapsible sidebars, and a responsive footer with multiple columns was cleaner in Grid. 

Which was easier to implement?

Flexbox was easier for simple layouts, but Grid was easier for complex, multi-area pages.

Which required less code?

For most layouts, Grid required less code, especially at higher levels.

Which was more intuitive?

Flexbox was more intuitive for linear layouts (either horizontal or vertical).

When would I use one over the other?

I would use Flexbox for smaller UI components. I would choose Grid for overall page layout.


