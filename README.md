🌍 TravelAgencyApp
Cross-Platform Client-Server Management System
TravelAgencyApp is a robust management solution designed for travel agencies to streamline tour reservations with transport companies. The project features two distinct client implementations, one in Java and one in C#, communicating with a central server to ensure real-time data consistency and secure operations.

🚀 Key Features
Cross-Platform Clients: Native desktop experiences built with both Java and C#.

Client-Server Architecture: Centralized logic for managing reservations and transport logistics.

Secure Authentication: Integrated secure login and logout mechanisms for agents.

Real-Time Synchronization: Synchronized reservation system to prevent overbooking and ensure data integrity.

Advanced Search: Real-time tour search functionality with visual indicators for tour availability.

🛠️ Tech Stack
Languages: Java 17+, C# (.NET)

Networking: Socket Programming (TCP/IP) for client-server communication.

Concurrency: Multithreading for handling multiple simultaneous client requests.

Data Management: Synchronized data structures to ensure consistency across different platforms.


📊 Business Logic Flow
Login: Agents authenticate via the secure login module.

Search: Agents search for available tours based on specific criteria.

Reserve: Real-time booking updates across all connected clients (Java or C#).

Audit: Visual indicators immediately mark tours as "Full" once capacity is reached.
