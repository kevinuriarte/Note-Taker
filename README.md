# 11 Express.js: Note Taker

## Completed

An application that can be used to write and save notes. This application uses an Express.js back end and will save and retrieve note data from a JSON file.

The application will be invoked by using the following command:

```bash
npm install
npm start
```

The following images show the web application's appearance and functionality. If you wish to watch in full size, here is the link: https://drive.google.com/file/d/1qeXXx-AbY1YYO68vpVVJQx8TzEBVKFQE/view

![Existing notes are listed in the left-hand column with empty fields on the right-hand side for the new note’s title and text.](./assets/Module11.png)

![Note titled “Balance accounts” reads, “Balance account books by end of day Monday,” with other notes listed on the left.](./assets/Module11.gif)



## User Story

```
AS A small business owner
I WANT to be able to write and save notes
SO THAT I can organize my thoughts and keep track of tasks I need to complete
```


## Acceptance Criteria

```
GIVEN a note-taking application
WHEN I open the Note Taker
THEN I am presented with a landing page with a link to a notes page
WHEN I click on the link to the notes page
THEN I am presented with a page with existing notes listed in the left-hand column, plus empty fields to enter a new note title and the note’s text in the right-hand column
WHEN I enter a new note title and the note’s text
THEN a Save icon appears in the navigation at the top of the page
WHEN I click on the Save icon
THEN the new note I have entered is saved and appears in the left-hand column with the other existing notes
WHEN I click on an existing note in the list in the left-hand column
THEN that note appears in the right-hand column
WHEN I click on the Write icon in the navigation at the top of the page
THEN I am presented with empty fields to enter a new note title and the note’s text in the right-hand column
```