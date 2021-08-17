# Notes App Documentation

A Simple command line argument Notes App using Node.js

## Getting Started

Installing Node Module into the notes project
```bash
npm install
```
### Adding a new note
```bash
node app.js add --title="Hi" --body="hello"
```
### Removing an existing note
```bash
node app.js remove --title="Hi"
```
### Listing all the existing notes
```bash
node app.js list
```
### Reading the notes content 
```bash
node app.js read --title="Hi"
```