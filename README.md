## Clone

clone the repo using

```bash
git clone https://github.com/maamunrcd/test-dline.git
```
## Go to folder using
```bash
cd test-dline
```
## Folder stracture
```
├── ...
├── assets                  # all the assets files
│   ├── css                 # css
│   ├── fonts               # all the used fonts
│   └── images              # all the images
│   └── js                  # all the js files
│   └── scss                # all the scss files
│   │   └── /components     # all the components scss files
    │   └── /core           # all the core scss files
    │   └── /responsive     # for responsive scss
    │   └── index.scss      # all the scss file imported in a single file
└── ...
index.html
package.json                # package.json for used packaged
README.md
.gitignore
```
## Prerequisites

### Node.js
To work with this project, you need to have Node.js installed on your machine. Follow these steps to check if Node.js is installed and install it if necessary:

1. **Check if Node.js is installed**:
   - Open your terminal or command prompt.
   - Run the following command to check if Node.js is installed:
     ```bash
     node -v
     ```
   - If Node.js is installed, you will see the version number displayed. Example:
     ```bash
     v16.13.0
     ```

2. **Install Node.js if not installed**:
   - Visit the [Node.js official website](https://nodejs.org/) to download the installer.
   - Choose the appropriate version for your operating system and follow the installation instructions provided.

## Convert to scss to css just run
```bash
npm run watch:sass
```
## If you want to change any style go to scss file and change as you want to change