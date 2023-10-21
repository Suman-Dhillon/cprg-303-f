# ADR: Developing a Mobile app for a retail company
The decision has been made on the basis of data security and access control for sensitive user data like payment information.

## Decision: Permissions
We have decided to implement a granular permissions system to control access to application features and data.

## Rationale 
Granular permissions system ensures that sensitive user data, such as payment information, is only accessible by authorized users which helps in maintaining data security and protecting user privacy. Different user roles or privileges have varying access needs, this system allows us to customize the app’s functionality based on these roles.

## Status
Accepted 

## Consequences
Advantages: By regulating access to critical information, a granular permissions system improves data security. It enables a personalized user experience based on roles and rights, which improves user happiness and app usability.  
Challenges: A granular permissions system can be difficult to design and deploy, necessitating considerable planning and development work. It will be a continuous responsibility to maintain and update the permissions system as user roles and access needs change.
