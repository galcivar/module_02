# Loan Qualifier App
Software that prompts the user to save the qualifying loans as a new CSV file based on the user data. Takes into account solicitants data:
- Credit Score
- Current Monthly Debt
- Total Monthly Income
- Desired Loan Amount
- Home Value

*It saves the data in a csv file with the name the user requests.*

#### Acceptance Criteria
- Given that I’m using the loan qualifier CLI, when I run the qualifier, then the tool should prompt the user to save the results as a CSV file.
- Given that no qualifying loans exist, when prompting a user to save a file, then the program should notify the user and exit.
- Given that I have a list of qualifying loans, when I’m prompted to save the results, then I should be able to opt out of saving the file.
- Given that I have a list of qualifying loans, when I choose to save the loans, the tool should prompt for a file path to save the file.
- Given that I’m using the loan qualifier CLI, when I choose to save the loans, then the tool should save the results as a CSV file.

---

## Technologies
*Developed in Python and tested on MacOs.*
It requires to have the following installed (Versions tested):
- Python 3.9.7
- Fire 0.3.1
- Questionary 1.5.2
- Path
- Sys

---

## Installation Guide

In this section, you should include detailed installation notes containing code blocks and screenshots.

---

## Usage

This section should include screenshots, code blocks, or animations explaining how to use your project.

---

## Contributors

In this section, list all the people who contribute to this project. You might want recruiters or potential collaborators to reach you, so include your contact email and, optionally, your LinkedIn or Twitter profile.

---

## License

When you share a project on a repository, especially a public one, it's important to choose the right license to specify what others can and can't with your source code and files. Use this section to include the license you want to use.
