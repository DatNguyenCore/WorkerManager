# WorkerManager
Welcome to the WorkerManager mobile application!

Before starting to develop on this code base please refer to the section.
It contains important information about the code structure and other design patterns applied to the code base.
Application help employees can leave register, overtime register, check report salary, ... And manager can leave appover, checking our employees.

## Application Folder Structure
The following is the architecture that is used in the application. Each important node has been labeled with a number and has been expanded upon.

```
├── App
|   ├── Components
|   |   └── # Reusable components (1)
|   ├── Config
|   |   └── # Configuration files (ENV keys, API urls, etc.)
|   ├── Constancts
|   |   └── # Share constancts.
|   ├── Fixtures
|   |   └── # Share static gake data using in application.
|   ├── Images
|   |   └── # Share static images in application.
|   ├── Lib
|   |   └── # Library files.
|   ├── Containers
|   |   └── # Screen.
|   ├── Navigation
|   |   └── # Router (3)
|   ├── Redux
|   |   └── # Root reducer.
|   ├── Saga
|   |   └── # Root saga.
|   ├── Themes
|   |   └── # Share colors, fonts,...
|   ├── Transforms
|   |   └── # Help application scale in multible size screen.
|   ├── Utils
|   |   └── # Shared utils functions
|   └── Services
|       └── # Shared business logic that can be reused throughout the application (API client etc.)
├── android
|   └── # Android build
├── ios
|   └── # iOS build
└── index.html
