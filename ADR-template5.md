# ADR: Developing a Mobile app for a retail company
The decision has been made on the basis of the company's demand for offline support, consistency, and scalability.

## Decision: Data Storage
We have decided to use a combination of local storage on the mobile device and a server-side database for data storage.


## Rationale 
Local storage on the mobile device will enable offline data access, allowing customers to use certain features without an internet connection. A server-side database, such as MongoDB, can handle the storage and retrieval of a large volume of data efficiently. This server-side database will ensure data consistency and reduce the risk of data loss in case of device failure, ensuring that customer data is reliable and up to date.

## Status
Accepted 

## Consequences
Advantages: The method of choice gives a complete solution, allowing for scalability and data integrity through a server-side database and offline support through local storage. It guarantees that users can access data even when they are not online.  
Challenges: It might be challenging to create and maintain synchronization techniques between local storage and the server-side database. It may need continual work to resolve disputes and guarantee that data is consistent across all platforms and devices.
