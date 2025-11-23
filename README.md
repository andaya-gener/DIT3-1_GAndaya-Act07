# Short Reflection

## 1. What did you learn about using fragments and navigation components?
During this activity, I learned how fragments help divide the app into modular sections like Home, Profile, and Settings. Using the Navigation Component made switching between fragments easier and more organized. I also understood how nav_graph.xml defines navigation paths and how the Bottom Navigation interacts with it.

## 2. How did you make your UI adaptive to screen size or orientation?
I used ConstraintLayout for all layouts to make the UI flexible in both portrait and landscape. I also created a layout-sw600dp folder for tablet screens and adjusted text sizes and spacing, so the app looks good on larger devices without breaking the design.

## 3. What challenges did you face when combining Bottom Navigation and Tabs?
One challenge was setting up ProfileFragment with tabs while still integrating it with Bottom Navigation. I ran into errors with the navigation graph and fragment layouts at first. Fixing the start destination in nav_graph and properly setting up the TabLayout and ViewPager2 solved the problem. It taught me to carefully check how fragments and navigation components interact.
