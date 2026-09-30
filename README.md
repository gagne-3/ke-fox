# ke-fox
Personalized Firefox CSS Setup. This is done to my taste and is only guaranteed to work on my setup.

## Setup
### 1. Enable userChrome
- Navigate to ```about:config``` in the search bar. Accept the risk if it prompts you
- Search for ```toolkit.legacyUserProfileCustomizations.stylesheets``` and toggle it to ```true```.

### 2. Locate profile folder
- Navigate to ```about:support``` in the search bar.
- Select ```Open Folder``` (or ```Show in Finder``` on MacOS) next to the ```Profile Folder``` entry.

### 3. Create folder and copy files
- Inside the profile folder, create a folder called ```chrome``` (if it doesn't exist already).
- Inside the ```chrome``` folder, copy the ```userChrome.css``` and ```userContent.css``` from this repository.
    - Alternatively: clone this repository inside the ```chrome``` folder so that updates can be done simply by performing ```git pull```.
- Restart Firefox to apply stylesheet.

## Changes
Here are the changes I have made to the default Firefox styling
- Reduce corner radiuses back to Proton style instead of Nova.
- Add 8px margin to the bottom and right side of the browser content container.
- Add 10px corner radius to browser content container.