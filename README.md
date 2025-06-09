# 🔐 Password Strength Evaluation Task

This project demonstrates the process of evaluating and improving password strength using an online password strength checker.

## 🧪 Passwords Evaluated

1. `password123`
2. `P@ssword123`
3. `P@5$W0rD!98`

## 🧾 Summary of Results

| Password         | Score | Strength    |
|------------------|-------|-------------|
| password123      | 43%   | Weak        |
| P@ssword123      | 89%   | Strong      |
| P@5$W0rD!98       | 100%  | Very Strong |

## 🛠️ Key Learnings

- Adding uppercase letters, symbols, and numbers greatly improves password strength.
- Avoid using dictionary words and repeated patterns.
- Place symbols and numbers in the middle of the password.
- Longer passwords with diverse characters are more secure.

## 💡 Tips for Strong Passwords

- Minimum 12 characters
- Include uppercase, lowercase, numbers, and symbols
- Avoid dictionary words or common phrases
- Use unique passwords for each account

## ⚠️ Common Password Attack Types

- **Brute Force**: Tries all possible combinations
- **Dictionary Attack**: Uses common word lists
- **Credential Stuffing**: Exploits reused passwords from data breaches

## 🔐 Conclusion

Password complexity directly impacts resistance to attacks. Strong passwords are essential for securing online identities.
"""

# Saving to README.md
readme_path = "/mnt/data/README.md"
with open(readme_path, "w") as f:
    f.write(readme_content)

readme_path
