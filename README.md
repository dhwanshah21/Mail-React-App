## React App

- This is a simple basic Application which fetches the mail data of a particular user. It comprises of list of emails sent by current user to 'xyz@abc.com' and the other main feature is where the user can create/draft an email. 
- In order to get the list of emails sent by current user, there is an API call which fetches the data with the help of given link. The data obtained is then rendered on the page with the key values of 'to' and 'subject' of mail. 
- On clicking on any of the particular email, full email is shown which is having 'To:', 'Subject:' and 'Text:'.

## Getting Started

1. Unzip the solution.
2. Run `yarn` to install the dependencies.
3. Run `yarn start` or `npm start` to run the app and go to http://localhost:3000/ to view. I have tested it on chrome browser.


## Technologies and Development Tools Used for the Project :

- JavaScript(ES6), React.js, API Call (Axios), React Routes, HTML, CSS, Microsoft VS Code, npm and Trello.   

## Future Enhancements :

- Bifurcating the emails according to the tags like IMP, Starred or Promotions.
- 'Delete' feature for deleting the selected mails.
- Pagination/Next/Prev for huge number of mails.
- Adding attachments to the mail.
