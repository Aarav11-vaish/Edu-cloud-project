# EDUCLOUD

Welcome to **EDUCLOUD**, an educational website project designed to provide a comprehensive learning experience through videos and resources. This project utilizes a range of web technologies and is continuously evolving. Below you'll find an overview of the project, its current state, areas requiring further development, and future scopes.

## Project Overview

**EDUCLOUD** is built with the following technologies:

- **HTML**: For structuring the content.
- **CSS**: For styling the website.
- **JavaScript**: For client-side functionality.
- **Node.js**: For server-side logic.
- **MongoDB**: Used for basic user registration (requires enhancement for authentication).

## Current Features

- **Video Access**: Users can access educational videos. Currently, this feature relies on JavaScript objects to store video information. Future updates will integrate a more robust API for video management.
- **HTML Templates**: The site uses HTML templates, but there's a plan to migrate to **EJS** for dynamic templating.
- **Bootstrap Components**: For responsive design and UI components.

## Areas for Improvement

1. **Authentication**: The registration system is currently basic and lacks authentication. Enhancing this with a secure authentication mechanism is a priority.
2. **API Integration**: Transitioning from JavaScript objects to a dedicated API for video access is needed to streamline content management and retrieval.
3. **HTML Templates**: Replace the existing HTML templates with **EJS** to leverage dynamic rendering and improve maintainability.
4. **Axios vs Fetch API**: It is preferred to use **Axios** for API requests instead of the Fetch API for consistency and enhanced functionality.
5. **Programming Section**: The programming section is not functioning correctly and needs to be reviewed, modified, or removed.
6. **Responsiveness**: Ensure the website is fully responsive and performs well across various device sizes. Testing on different screen resolutions is required.
7. **UI/UX design**
8. **Video Playback**:
    Currently, the project uses the YouTube Player to display lecture videos. However, we are planning to develop and integrate our own video player to offer a more customized
    and controlled viewing experience. 

    -Key Requirements for the New Video Player:
    
    - **Custom Controls**: Implement custom playback controls that match our specific needs.
    - **Enhanced Features**: Include additional features such as annotations, interactive elements, or integration with other project components.
    - **Performance**: Ensure that the video player performs efficiently and handles various video formats and resolutions.
      
9. **Directory Structure**:While this project is functional, it’s important to note that the current directory structure may not be optimal. Here are a few points to consider:

- **Organizational Improvements**: The directory structure could benefit from a more organized layout to improve navigation and maintainability. Consider revisiting the folder hierarchy to ensure related components and files are grouped logically.

- **Consistency**: Some directories and file naming conventions are inconsistent. Adhering to a consistent naming scheme and folder structure will make the project easier to understand and work with.

- **Modularity**: There are opportunities to enhance modularity by separating concerns more clearly. For example, grouping related modules, utilities, or components into their own directories can help isolate functionality and improve code manageability.

- **Documentation**: Updating the documentation to reflect any changes in the directory structure will be crucial. Ensure that any improvements to the structure are documented clearly in the `README.md` or other relevant documentation files.

We welcome contributions that address these structural improvements and help make the project more organized and maintainable.

## Future Scopes

1. **Online Streaming Section**: Introduce an online streaming feature to allow live video sessions, webinars, and interactive lectures. This will enhance the educational experience by providing real-time content delivery.
2. **Chatbot Integration**: Implement a chatbot to assist users with common queries, guide them through the website, and provide real-time support. This will improve user interaction and make the platform more engaging.

## Author

**Aarav Vaish**


---

Thank you for checking out **EDUCLOUD**! Your contributions and feedback are highly appreciated.
