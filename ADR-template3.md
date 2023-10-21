# ADR: Developing a Mobile app for a retail company
The decision have been made on the basis of company's requirement for an app which can support large customer base with scalability.

## Decision: Backend Language
We have decided to use Node.js as the backend language for the development of the application.

## Rationale 
Node.js has a non-blocking, event-driven design which promotes real-time data synchronization. It is well-known for its capacity to manage a large number of concurrent connections, making it suitable for supporting large customer base, while also satisfying the scalability needs of the retail app. Since React Native uses JavaScript, using Node.js for the backend can streamline the development process and enable code sharing between the frontend and backend. Moreover, it has robust ecosystem of libraries and modules making it easier to integrate with wide range of services and APIs.

## Status
Accepted 

## Consequences
Advantages: It enables efficient real-time data synchronization, scalability, and seamless integration with third-party services. It leverages the expertise of JavaScript developers.  
Challenges: Node.js is renowned for its scalability, although for high loads, careful architecture and optimization may still be needed. Some team members may need to learn more about Node.js or broaden their understanding of it.