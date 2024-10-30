- This project gathers data from GitHub profiles and repositories for users in Delhi who have more than 100 followers, utilizing the GitHub API while managing pagination and detailed information retrieval.
- The analysis uncovered a significant inclination towards JavaScript and Python within the Delhi developer community, highlighting a vibrant open-source collaboration.
- Developers should enhance their profiles by enabling hireable status and enriching their bios, as this can increase their visibility to potential employers.

# GitHub User and Repository Data Collection Project

Introduction-
This project focuses on collecting information about GitHub users located in Delhi with over 100 followers. The dataset includes detailed user profiles and their public repositories, all retrieved through the GitHub API.

Included Files-
- users.csv: Contains details about each user, including their GitHub username, full name, company, location, email address, hireable status, bio, number of public repositories, followers, people they follow, and account creation date.
- repositories.csv: Lists the repositories associated with each user from `users.csv`, detailing the repository name, creation date, star count, watcher count, programming language used, and license information.
- readme.md: Provides documentation for the project, methodology, and findings.
- Colab file

Data Collection Methodology
1. User Fetching: The GitHub search API was utilized to identify users in Delhi who have more than 100 followers.
2. Detailed User Data: For each identified user, a subsequent API call was made to obtain complete profile details.
3. Repository Fetching: Up to 500 recent public repositories were collected for each user.


