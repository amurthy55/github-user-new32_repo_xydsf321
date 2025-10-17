# GitHub User Fetcher

## Summary
A simple web application that fetches a GitHub user's account creation date using their username.

## Setup
1. Clone the repository.
2. Open `index.html` in a web browser.

## Usage
1. Enter a GitHub username in the input field.
2. Click the 'Fetch User' button to retrieve the account creation date.

## Code Explanation
- The form with id `github-user-12345` captures the username input.
- On submission, it triggers the `fetchUser` function which fetches data from the GitHub API.
- The account creation date is displayed in the `#github-created-at` div in YYYY-MM-DD format.

## License
This project is licensed under the MIT License.

## Description
This app provides a user-friendly interface to quickly check the account creation date of any GitHub user.