# CS-350

**Summarize the project and what problem it was solving.**
In Milestone 2, I developed scripts for serial communication, specifically SerialTest-Write.py and SerialLightControl-Client.py which allowed for effective interaction between a computer and hardware components via a serial interface. This project aimed to solve the problem of reliably sending and receiving commands to control LED states, ensuring that user inputs could effectively manipulate the hardware in real-time. Milestone 3 built upon this by implementing a non-blocking LED control loop using threading, enhancing the responsiveness of the system and allowing simultaneous operations without hindering the main program flow.

**What did you do particularly well?**
I excelled in implementing the threading approach in Milestone 3, which significantly improved the system's responsiveness. The ability to manage multiple tasks simultaneously without blocking the main execution thread showcased my understanding of concurrency in programming. Additionally, my clear documentation of the serial communication process in Milestone 2, including the use of `encode()` and `decode()` methods, illustrated my ability to convey complex technical concepts effectively.

**Where could you improve?**
While I was pleased with my overall execution, I recognized the need to enhance my debugging skills. In some instances, I faced challenges identifying issues in the serial communication due to incomplete error handling. Improving my proactive error management could lead to even more robust applications. Additionally, I could work on optimizing the code for efficiency, particularly in the handling of GPIO pins to ensure they are returned to their original state reliably.

**What tools and/or resources are you adding to your support network?**
During the course of these projects, I utilized resources such as Python documentation, online forums (like Stack Overflow), and peer collaboration for troubleshooting. I plan to expand my support network by participating in coding communities and attending workshops related to embedded systems and IoT development.

**What skills from this project will be particularly transferable to other projects and/or course work?**
The skills gained from these projects, such as mastering serial communication, threading for task management, and GPIO control, are highly transferable to future coursework and professional projects. These experiences will enhance my capabilities in developing responsive applications and working with hardware integration, which are critical in emerging technologies.

**How did you make this project maintainable, readable, and adaptable?**
To ensure the projects were maintainable and readable, I adhered to consistent coding standards and included thorough comments throughout the code. This practice not only aids in my understanding but also facilitates collaboration with others. Additionally, I structured the code in a modular fashion, allowing for easy updates and modifications in the future. Implementing clear error handling and returning GPIO pins to their original state at the end of execution further contributed to the overall robustness and predictability of the applications.
