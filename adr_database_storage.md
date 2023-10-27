# Architectural Decision Record: Local Database Storage

Title: Choosing local(encrypted) as Database Storage for "Codinggo".  
Status: Proposed. Under evaluation by the team.

## Context
We need to decide the appropriate database storage solution to manage user data and progress for our app "Codinggo". The primary focus of the project is to teach coding concepts through interactive exercises and quizzes. Among various options availabe, we are considering local(unencrypted) as a possible choice.

## Decision Considerations
- Ease of use and maintenance  
- Performance and scalability  
- Offline Access  
- Cost and licensing  

## Considered Options
- Local (encrypted)  
- Local (unencrypted)  
- Remote  
- None

## Rationale
### Local (Unencrypted) Data Storage
Storing user data locally in an unencrypted format simplifies the data storage and implementation. It ensures offline access for the user and carry on with their learning journey, even when they are offline. Unlike encrypted storage, there are fewer data protection compliance concerns when data is stored locally in an unencrypted manner. Unencrypted data storage can be a better option as we are not dealing with any sensitive information like payment options. Moreover, it lowers the cost of server infrastructure which might be needed in remote storage. Remote storage can be more complex to set up and maintain as compared to local unencrypted data storage.

## Consequences
- Positive: It will require less development effort and complexity. User can access their progress offline, improving app's usability. It doesn't rely on faraway servers, it saves money on server infrastructure.  
- Negatives: It may compromise data security and privacy, but in our app "Codinggo", we are not storing any sensitive user information. Additionally, if a user loses their device or the data is corrupted, their progress and information may be lost, as there are no remote backups.

## Notes
Local (Encrypted): Encrypting user data before storing it locally on the user's device to protect it.  
Local Data Storage: This refers to storing user data locally, without encryption, on the user's device.  
Remote: Keeping user information on a distant server.  
None: Deciding against permanently storing user data.
