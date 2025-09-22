## Setup Instructions

### 1. Clone the Repository

git clone <repo-url>
cd <repo-name>

### 2. Create and Activate a Virtual Environment

python3 -m venv venv
source venv/bin/activate        

### 3. Install Dependencies

pip install -r requirements.txt

## Running Tests

This project uses **pytest** for testing.
- All test files are located in the `tests/` directory.   
- GitHub Actions is configured to run these tests on every push to the repository.  

## Work Completed

- Cloned the professor’s repository and set up the environment.  
- Fixed **two pytest errors** that were causing failures.  
- Updated test cases to ensure correctness and consistency.  
- Verified that **all tests pass** successfully on the local machine.  
- Ran GitHub Actions workflows to confirm everything works in the CI pipeline.  

##  Usage 
- Used `pytest` to validate correctness after making any changes.  
- Pushed commits to GitHub to automatically trigger GitHub Actions and run tests.  

