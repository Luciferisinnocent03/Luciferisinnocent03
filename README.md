- 👋 Hi, I’m @Luciferisinnocent03
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Luciferisinnocent03/Luciferisinnocent03 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
from github import Github

# Authenticate with your token
g = Github("your_access_token")

# Get a specific repository
repo = g.get_repo("username/repo_name")

# Example: Create an issue
issue = repo.create_issue(
    title="New issue title",
    body="Here is the body of the issue."
)

print(f"Issue created: {issue.url}")

