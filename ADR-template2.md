# ADR: Developing a Mobile app for a retail company
The decision has been made based on both iOS and Android devices, where a consistent and platform-specific UI experience is intended.

## Decision: UI Framework
We have decided to use React Native as the UI framework for the development of the application.

## Rationale 
With React Native, we can create a single codebase that can be used for both iOS and Android platforms, ensuring a consistent experience for users. It actively supports the latest platform-specific features and design patterns like gesture controls, animations, and UI interactions. The advantages in terms of development effectiveness, performance, and user experience exceed the little overhead, even though some platform-specific code may still be required.

## Status
Accepted 

## Consequences
Advantages: Choosing React Native as the UI framework ensures a UI that aligns with the conventions of iOS and Android, providing a familiar and consistent UX. It improves responsiveness and performance, which are essential for a retail app with a large volume of data and graphics. It also speeds up development by allowing code to be shared between platforms.  
Challenges: While React Native provides exceptional development efficiency, certain features or optimizations may require platform-specific development effort. However, the advantages in terms of performance and user experience usually outweigh the work and expenditure.
