# ADR: Developing a Mobile app for a retail company
The decision has been made on the basis of the company's requirement for an app that can support a large customer base with scalability and real-time data synchronization like handling push notifications effectively.

## Decision: Backend Language
We have decided to use Node.js as the backend language for the development of the application.

## Rationale 
Node.js has a non-blocking, event-driven design which promotes real-time data synchronization. It is well-known for its capacity to manage a large number of concurrent connections, making it suitable for supporting a large customer base, while also satisfying the scalability needs of the retail app. Since React Native uses JavaScript, using Node.js for the backend can streamline the development process and enable code sharing between the front end and back end. Moreover, it has a robust ecosystem of libraries and modules making it easier to integrate with a wide range of services and APIs.

## Status
Accepted 

## Consequences
Advantages: It enables efficient real-time data synchronization, scalability, and seamless integration with third-party services. It leverages the expertise of JavaScript developers.  
Challenges: Node.js is renowned for its scalability, although for high loads, careful architecture and optimization may still be needed. Some team members may need to learn more about Node.js or broaden their understanding of it.
