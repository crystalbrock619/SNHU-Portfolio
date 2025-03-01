# SNHU-Portfolio
Computer Science Portfolio

CS-250 Software Development Lifecycle
  1. How do I interpret user needs and implement them into a program?

    Interpreting user needs requires actively engaging with stakeholders, gathering requirements, and translating them into functional specifications. This process involves understanding the problem domain, identifying pain points, and prioritizing features that provide the most value. One of the most effective ways to accomplish this is by creating user stories, which are short, simple descriptions of a feature from the perspective of the end user. User stories help break down complex requirements into manageable tasks, ensuring that the development team stays focused on delivering functionality that aligns with user expectations. By refining and iterating on user stories through backlog grooming and sprint planning, teams can adapt to evolving user needs while maintaining efficiency in development.

  2. How do I approach developing programs?

    My approach to developing programs centers around incremental development, where software is built and improved in small, manageable iterations. This methodology aligns with Agile processes, which emphasize adaptability, continuous feedback, and iterative progress. In my future development work, I plan to incorporate Agile practices such as sprint planning, daily standups, and backlog refinement to keep projects structured and efficient. By leveraging incremental development, I can focus on delivering functional components early, gathering feedback, and making necessary adjustments without waiting for a full release. This approach not only improves software quality but also ensures that the final product meets user expectations more effectively.

    3: What does it mean to be a good team member in software development?

      Being a good team member in software development requires availability, fast response time, and the ability to give and receive useful feedback. Effective collaboration is crucial for keeping projects on track and ensuring that everyone is aligned with the team’s goals. Being available means actively participating in team discussions, attending meetings, and promptly addressing tasks or blockers. Fast response times help prevent delays and ensure smooth workflow, especially in an Agile environment where quick decision-making is key. Additionally, providing constructive feedback helps improve the quality of work, while being open to receiving feedback fosters a culture of continuous improvement. A strong team member contributes not just by writing code but by supporting the team’s overall success through communication, accountability, and a willingness to adapt.


CS210 Programing Languages
  Final Project Reflection: Corner Grocer Item Tracker
  
  Project Summary and Problem Solved
    The Corner Grocer Item Tracker is a C++ program designed to analyze grocery purchases from an input file and provide frequency counts of individual items. The program efficiently reads data from Final-Project-Input.txt, processes the occurrences of each item using a map data structure, and allows users to retrieve item counts, view all recorded frequencies, or generate a histogram representation of the data. Additionally, the program creates a backup file (frequency.dat) to retain the frequency data for future use. This project addresses the problem of manual tracking and analysis of grocery purchases, making it easier for store owners or customers to identify shopping trends and inventory needs through an interactive, menu-driven interface.

  What Was Done Well?
    One of the strongest aspects of the project is its structured and modular design, which follows object-oriented programming (OOP) principles. The ItemTracker class effectively encapsulates data and provides clear functionality through well-defined public methods. The use of a map from the Standard Template Library (STL) ensures that item lookup and frequency updates are efficient. Additionally, file handling is properly implemented, allowing seamless reading from the input file and automatic data backup. The inclusion of error handling for file operations helps improve program reliability by gracefully handling missing or inaccessible files. The user experience is also well-considered, with a simple menu interface that makes it easy for users to interact with the program.

  Areas for Enhancement and Benefits
    While the program functions well, several improvements could enhance efficiency and maintainability:

      • Improved Input Validation: The program currently assumes correct input formatting. Implementing string sanitation and case insensitivity would make the lookup function more flexible.
      • Exception Handling for File Operations: The program uses simple error messages for file issues, but incorporating exception handling (try-catch blocks) would improve robustness.
      • Optimization for Large Datasets: If the input file grows significantly, using unordered_map instead of map could speed up lookups by reducing logarithmic access time to near constant-time complexity.
      • Persistent Storage with Databases: Instead of storing data in frequency.dat, integrating a lightweight database (like SQLite) would make data management more scalable.
    These enhancements would improve program efficiency, security, and usability, making the solution more adaptable for real-world use.

  Most Challenging Code Sections and Solutions
    One of the most challenging parts of writing this program was managing file input and output operations, particularly ensuring that data is read, processed, and backed up correctly. Initially, handling missing files or corrupted input posed a challenge, but this was addressed by implementing basic error handling with informative messages. Another challenging area was the histogram output, ensuring proper alignment and formatting of the visual representation. Using setw() and left alignment from the <iomanip> library helped ensure a clean and readable display.

    To enhance my programming support network, I relied on C++ STL documentation, forums like Stack Overflow, and debugging tools within my development environment. Moving forward, I plan to integrate more unit testing frameworks like Google Test to validate code behavior systematically.

  Transferable Skills from the Project
    This project has strengthened several key programming skills that will be valuable in future coursework and real-world applications. First, working with file I/O operations is a fundamental skill applicable to any software that handles data storage. Second, using STL containers like map for efficient data management is a best practice in software development. Third, object-oriented design principles learned in this project will be directly useful when working on larger-scale C++ applications, ensuring code reusability, scalability, and maintainability.

  Making the Program Maintainable, Readable, and Adaptable
    To enhance maintainability, clear comments and meaningful variable names were used throughout the code. The program follows a structured, modular design where the ItemTracker class separates core logic from the user interface. This reduces coupling and makes future modifications easier. Readability is improved by consistent indentation and function organization, making the codebase easy to navigate. Lastly, adaptability is ensured through encapsulation and data abstraction, allowing future developers to expand functionality (such as adding a GUI or database integration) without disrupting the core logic.

  Overall, the Corner Grocer Item Tracker is a well-structured and functional program that effectively tracks item frequencies while demonstrating solid programming practices in C++. Future enhancements could further optimize performance and usability, making it a more powerful tool for inventory tracking and grocery analysis.




