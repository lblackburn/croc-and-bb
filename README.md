# Install and run from src directory
```
npm install
npm start
```

# Packaging for mac / linux on OS X
```
npm install electron-packager -g
electron-packager src/ "Croc & BB" --platform=linux,darwin --arch=x64 --out=out/
```
just manually renaming output directories since life is hard

# Packaging for windows on Windows
Can't get Wine installed on OS X because the Homebrew package is broke af
