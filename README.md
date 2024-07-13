# Password Complexity Checker

Welcome to the Password Complexity Checker project! This repository contains a Python implementation for assessing the strength of passwords based on various criteria such as length, character types, and special characters using regular expressions.

## Overview

This project provides a simple yet effective way to evaluate the strength of passwords. It employs a scoring system that considers factors like length, uppercase letters, lowercase letters, numbers, and special characters. Based on these criteria, the algorithm categorizes passwords into three levels: weak, moderate, and strong.

## Algorithm Details

### Assessment Criteria

The `assess_password_strength` function assesses password strength based on the following criteria:

- **Length**: Longer passwords receive higher scores.
- **Uppercase Letters**: Presence of uppercase letters adds to the score.
- **Lowercase Letters**: Presence of lowercase letters adds to the score.
- **Numbers**: Presence of numbers adds to the score.
- **Special Characters**: Presence of special characters (e.g., !@#$%^&*()) adds to the score.

### Scoring

Each criterion contributes a certain score to the total, which is then used to determine the password strength:

- **Weak password**: Total score less than 5.
- **Moderate password**: Total score between 5 and 8 (inclusive).
- **Strong password**: Total score greater than 8.

## Usage

To use this program:
1. Run the `password_checker.py` script.
2. Enter your password when prompted.
3. The program will assess the strength of your password and provide feedback.

## Example

```plaintext
Enter your password: MyP@ssw0rd!
Strong password
```
## Contributing
Contributions to enhance the algorithm's accuracy, add new features, or improve documentation are welcome. Please fork this repository, make your changes, and submit a pull request. For major changes, open an issue to discuss the proposed modifications.

Ensure your passwords are strong and secure! 🔒🔑
