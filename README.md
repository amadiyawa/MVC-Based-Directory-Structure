# MVC Based Directory Structure

Incredibly simple MVC based folder structure options and naming conventions for PHP projects.

    .
    ├── application                 # Contains the core code of your application
    │   ├── addon                   # Addons, plugins etc.
    │   ├── controller              # Controllers
    │   └── language                # Language Files
    |   │   ├── english             # English language files
    |   │   ├── turkish             # Turkish language files
    │   └── model                   # Models
    │   └── template                # Templates, views
    └── assets                      # Uncompiled/raw CSS, LESS, Sass, JavaScript, images, fonts
    │   ├── css                     # Uncompiled/raw CSS, LESS, Sass files
    │   ├── fonts                   # Webfonts
    │   └── images                  # Template Images
    │   └── js                      # Uncompiled/raw JavaScript, jQuery files
    └── cache                       # Cache files
    │   ├── css                     # Compiled CSS, LESS, Sass files
    │   └── js                      # Compiled Javascript files
    └── system                      # Common system files
    │   ├── config                  # Application configuration
    │   └── library                 # 3rd party packages, libraries and components
    │   └── logs                    # Application specific log files
    └── uploads
    │   └── attachments
    │   └── avatars
    │   └── images
    └── README.md