Damon Harris
Mobile-Architecture-and-Programming
Android app development
1. Briefly summarize the requirements and goals of the app you developed. What user needs this app address?
The Inventory App was designed to help users efficiently track, manage, and update warehouse or personal inventory items. Its primary goal was to reduce the complexity of manual tracking while providing quick access to item details. The app addresses user needs for accuracy, convenience, and accessibility in managing stock levels and alerts.
 
2. What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
The app included key screens such as a login screen for security, a dashboard with a RecyclerView grid for displaying items, and a feature for adding or editing inventory items via a floating action button. An SMS notification feature was also integrated to alert users about low stock. The UI was designed with simplicity, accessibility, and consistency in mind. Clear layouts, familiar design elements, and intuitive navigation ensured users could interact with the app effectively. The designs were successful because they balanced functionality with ease of use.
 
3. How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?
I approached coding using modular development: separating UI (XML layouts) from logic (Java classes) and using Android best practices such as RecyclerView adapters for displaying data. I also integrated runtime permission handling for SMS notifications to keep the app stable regardless of user response. These strategies promote code clarity, scalability, and reusability, and they can be applied in future projects to maintain organized and efficient codebases.
 
4. How did you test to ensure your code was functional? Why is this process important, and what did it reveal?
I tested the app on both the Android Emulator and my Android phone, using various scenarios: granting and denying SMS permissions, adding items, and navigating across screens. I used both functional and user interaction tests to ensure all components worked together. Testing revealed small layout issues and permission-handling edge cases, which were corrected to improve reliability. Testing is important because it identifies hidden bugs and ensures a positive user experience.
 
5. Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?
A key challenge was handling the SMS permission feature. Since users could deny access, I had to innovate by designing fallback behavior so the app would still function fully without SMS. Another challenge was ensuring the splash screen and floating action button behaved as expected, which required fine-tuning XML constraints. These innovations ensured the app remained functional and user-friendly across different scenarios.
 
6. In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
I was most successful in implementing the SMS notification feature with runtime permission handling. This required combining UI design, user-centered thinking, and Android API knowledge. It demonstrated my ability to integrate real-world features while accounting for different user responses and maintaining overall app stability.



