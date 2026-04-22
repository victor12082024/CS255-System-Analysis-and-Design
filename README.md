# DriverPass-project

•	Briefly summarize the DriverPass project. Who was the client? What type of system did they want you to design?

The DriverPass project was focused on designing a cloud-based system for a driver training company started by Liam, with the goal of improving both business operations and student learning. The system was designed to allow students to register, schedule lessons, take practice tests, and track their progress, while also allowing staff and admins to manage drivers, vehicles, schedules, payments, and reports in one centralized platform. The system aimed to create a secure, web-based solution that makes the company run more efficiently and helps students better prepare for the DMV driving test.

•	What did you do particularly well?

I did particularly well translating the client’s needs into clear system requirements and a structured design. For example, I broke down features like scheduling, account management, and payment handling into specific functional requirements such as “the system shall allow students to schedule driving lessons” and “the system shall prevent double booking,” which directly reflect the business needs. I also designed the system to be scalable and accessible by making it cloud-based, supporting multiple users, and ensuring it works across devices, which aligns with modern system expectations.

•	If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

If I could revise one part of my work, I would improve my sequence diagram for scheduling a lesson by adding more detail and clarity to the interactions between components. Right now, the diagram shows the overall flow, like the student logging in, requesting available times, selecting a time, and the system creating and confirming the reservation, but I could improve it by making the steps more precise and consistent, especially around validation, error handling, and decision points. For example, I could better show what happens if a time slot is no longer available or if validation fails before saving to the database. Since scheduling is one of the core features of the system, improving this diagram would make it much clearer how the DriverPass system communicates with the scheduling service and database, and would give developers a more complete understanding of how the process should actually work.

•	How did you interpret the user’s needs and implement them into your system design? Why is it so important to consider the user’s needs when designing?

I interpreted the user’s needs by taking the problems DriverPass wanted to solve—like managing student training, scheduling lessons, and improving test success and turning them into specific system features such as account management, lesson scheduling, progress tracking, and reporting. I also considered different user roles like students, staff, admins, and the owner to make sure each one had the right level of access and functionality. This is important because if a system is not designed around user needs, it may function technically but fail to be useful, leading to inefficiency and frustration for the people actually using it.

•	How do you approach designing software? What techniques or strategies would you use in the future to analyze and design a system?

My approach to designing software starts with understanding the problem and user requirements, then breaking the system into smaller components like features, data, and workflows. I use techniques like defining functional and nonfunctional requirements and creating UML diagrams to map out how the system will operate and how components interact. This structured approach helps make sure the system is organized, scalable, and aligned with user needs, and in the future I would continue using these strategies while also focusing on improving detail and clarity in my designs.
