### Laying, Describing and Analyzing the Foundation and Methods for Friends’ Core Architecture and Features
> In this section, we outline the technical blueprint for Friends, detailing the app’s tech stack, architecture, and core functionalities. By leveraging Flutter for the frontend and AWS services for the backend, Friends is designed to deliver a scalable and dynamic social platform. We also explore the dynamic interactions between the app’s components through user flows and visual diagrams, providing a clear roadmap for development.

# Core Functionality

* User and group profile creation.
* Group matching based on interests.
* In-app messaging between groups and individuals.
* Event-based search and participation.

# User Flow

## Textual Description

### User Onboarding:

* Step 1: The user downloads and opens the Friends app.
* Step 2: They are prompted to sign up or log in. If signing up, they enter their phone number.
* Step 3: An OTP (One-Time Password) is sent to their phone for verification.
* Step 4: After entering the OTP, they proceed to create their profile by uploading a face picture, two additional photos, and filling in their bio.
* Step 5: The profile is created and the user is taken to the home screen where they can start exploring the app.

### Group Formation:

* Step 1: From the home screen, the user selects the option to create a new group.
* Step 2: They fill in the group details, such as group name, description, and category (e.g., Dating, Common Interests).
* Step 3: The user invites friends to join the group by selecting from their contacts or sending invites via social media.
* Step 4: Once at least one friend accepts the invitation, the group becomes active.
* Step 5: The group members can now edit the group profile and start looking for other groups to match with.

### Matching Process:

* Step 1: The group browses or searches for other groups based on their interests or categories.
* Step 2: They swipe right to indicate interest or left to pass.
* Step 3: If at least half of the group members swipe right, the other group receives a notification of the interest.
* Step 4: The other group members also vote. If at least half of them swipe right, a match is made.
* Step 5: Matched groups can now start chatting or planning activities together.

### Messaging Flow: 

1. Match Activation:
  * Once a group or an individual matches with another group or individual, two chat options become available:
    * Mutual Group Chat: Members of both groups can engage in a shared group chat to discuss and coordinate activities.
    * Individual Chat: Members can initiate private one-on-one conversations with individuals from the matched group for more personal interactions.
2. In-Group Messaging:
  * Internal Group Discussions: Each group has a dedicated messaging channel where members can communicate privately among themselves.
    * Commenting on Matches: Members can leave comments about potential matches or ongoing interactions with other groups or individuals.
    * General Messaging: Group members can use this channel for any internal discussions, such as planning activities or sharing thoughts.
3. Communication Features:
  * Text Messaging: Supports sending text messages in both group and individual chats.
  * Media Messaging: Allows sharing of photos, videos, and other media to enhance communication.


## Flow Chart Description

