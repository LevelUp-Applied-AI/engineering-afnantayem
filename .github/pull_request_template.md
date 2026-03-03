What changed

Added PR hygiene structure (PR template and self-review checklist).
Added docs/pr-checklist.md for pre-PR verification.
Updated README.md with a How to run section explaining environment setup and execution steps.
Fixed environment setup issues related to pytest configuration.

Why

Improve pull request quality and review clarity.
Ensure contributors verify correctness before opening a PR.
Provide clear instructions for running and testing the project.
Resolve setup issues that previously caused pytest to fail.

How to test

Pull the branch locally.
Activate the virtual environment.
Install dependencies using pip install -r requirements.txt.
Run pytest and confirm all tests pass.
Follow the How to run section in the README and verify the project runs without errors.

Checklist

 - [ ] The code does what the PR title claims.
 - [ ] All tests pass locally.
 - [ ] Documentation (README) reflects the changes.
 - [ ] No debug artifacts (print statements, breakpoints).
 - [ ] This PR contains one logical change and is not mixing unrelated updates.