# Seattle GitHub Users Analysis

- **Scraping Approach**: I used the GitHub API to retrieve data on Seattle-based users with over 200 followers and their latest 500 public repositories.
- **Insight**: The most followed users in Seattle have repositories with a high concentration in JavaScript, Python, and Go, revealing popular languages among influential developers.
- **Recommendation**: Developers aiming to expand their following should consider creating open-source repositories in these popular languages.

## Project Description

This project aims to provide insights into GitHub users in Seattle with a significant follower count (over 200) and analyze their public repositories for common patterns and trends. The goal was to understand which programming languages are prevalent and identify areas of growth for aspiring developers.

## Data Collection

Data was collected using the GitHub REST API (v3), focusing on users in Seattle with over 200 followers. Each user's profile and up to 500 of their most recently pushed repositories were retrieved. Two CSV files, `users.csv` and `repositories.csv`, were created, containing the users' details and their repository information, respectively.

## File Structure

- **users.csv**: Contains user profile details including `login`, `name`, `company`, `location`, `public_repos`, `followers`, `following`, etc.
- **repositories.csv**: Includes repository details like `login`, `full_name`, `created_at`, `stargazers_count`, `watchers_count`, `language`, `has_projects`, and `license_name`.

## Analysis

Data from Seattle's top developers shows significant activity in popular programming languages, with insights into which types of repositories attract more stars and followers. This information is useful for developers looking to engage with the tech community.
