# Weekend Challenge 11 - React-Redux Feedback Form

## Instructions

Reviewing code is an important role developers play. We're going to practice reviewing code from others.

- Get the repo url from your partner
- Get your partner's project running on your computer
- Review the code from your partner and give relevant feedback
- Complete the Markdown section and submit that in the notes section on the assignment app. (Make sure you include who's code you reviewed.)

Practicing compassionate code reviews is important (you can learn more from this video on the topic: https://www.youtube.com/watch?v=Ea8EiIPZvh0 )

## Review Checklist

## Base Required Features 

- Multi-Part Form:  
  - [yes] Able to add feedback
    - [yes] Data collected on individual pages & components
    - [yes] Click on next takes you to the next page in sequence
    - [yes] Data saves in DB after *all* the parts are completed (not piecemeal)
    - [yes] Thank you page takes you back to the first view
    - [yes] Old Data is cleared on form completion

- Client code:
  - [yes]  Individual components for each form part
  - [yes]  Redux setup complete
    - [yes] Store linked to react with `<Provider>`
    - [yes] Store setup with reducer(s) and logger middleware 
  - [yes] Reducers & Actions Working
    - [yes] Actions are in SCREAMING_SNAKE_CASE and semantically named
    - [yes] Actions have a `type` key, and `payload` if sending data
    - [yes] Reducers are returning a new state, or the old state (not mutating)
    - [yes] Reducers are using spread correctly (to keep old data, while adding new)
  - [yes] Review Component shows at all times with current redux state
  - [yes] React-Redux Working
    - [yes] Dispatching actions onClick
    - [yes] Grabbing data from the redux store with `useSelector`
  - [yes] Axios POST request to add feedback


- Server code:   
  - [yes] Router made for GET, POST


## General Items
Feedback should be provided for these items, but they do not impact scoring.

- Git 
  - [yes] Multiple git commits showing incremental progress
  - [yes] Commits are descriptive of the changes made or feature added 
  - [yes] Has .gitignore with node_modules
  - [no] Readme file updated (assuming this is previously discussed)
- Code Style 
  - [yes] Appropriate amount of code comments
  - [yes] Code is consistently formatted
- Client
  - [yes] Appropriate use of HTML tags
  - [yes] Basic CSS styling with margins/padding


## Stretch Goals
First must be complete for score of  _Exceeds Expectations_

- Previous Steps
  - [ ] allows a user to go to a previous step, either directly or by cycling backward thru the steps
  - [ ] user can upate their score for a step
    - [ ] new score is validated to not be empty
    - [ ] redux is updated with new score
  - [ ] user can continue on to review page and submit as in Base Mode


- Admin View
  - [ ] All entries are visible with correct data from inputs
    - [ ] Most recent is at the top
  - [ ] Can Delete an entry
    - [ ] User is prompted before deleting
  - [ ] Axios GET request to get all feedback for `/admin` view in componentDidMount

  Busywork Goals, consider removing or making more useful

- [yes] Styling with Material UI
- [ ] Ability to flag a feedback item on `/admin` for further review
- [ ] Deployed to Heroku


## Markdown

```
Hey Sabrina,

General Feedback.

---
| Functional Requirements | Complete? |
| --- | :---: |
| Multi page form with client side routing and navigation (next button) | yes |
| Data stored in Redux when navigating from page to page | yes |
| User is notified when trying to leave a blank score | yes |
| Review Component displays scores and comments from current redux state | yes |
| Submit button sends data to the server via Axios | yes |
| Confirmaion Page displays after data is POSTed to the server | yes |
| Button on Confirmation Page clears Redux and starts a new survey | yes |
| Views are broken down into components | yes |

---
### Notes: Generally, you got everything setup and working as it should. 

Notes on the above Functional Requirements.

---
| General Items | Complete? |
| --- | :---: |
| More than 15 git commits | yes |
| Commits are descriptive of the changes made or feature added | yes |
| Readme file updated | no |
| Appropriate amount of code comments | yes |
| Code is consistently formatted | yes |
| Server code organized with router & module files | yes |

---
### Notes: Good job Sabrina, generally i see you got good understanding of this! The only thing i see is that your README.md is not updated and usually this is what reviewer also go through to understand the scope of your job.

Notes on General Items

```
