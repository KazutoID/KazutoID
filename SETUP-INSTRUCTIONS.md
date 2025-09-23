# GitHub Profile Configuration Files

This repository contains all the necessary configuration files to set up an impressive GitHub profile. Below is a guide on how to use these files.

## Files Overview

1. **README.md** - The main profile README file that will be displayed on your GitHub profile.
2. **.github/workflows/github-metrics.yml** - Workflow file for generating GitHub metrics.
3. **.github/workflows/snake.yml** - Workflow file for generating the contribution graph snake animation.
4. **.github/config.yml** - Configuration file for repository defaults and GitHub bots.
5. **social-links.md** - Contains various social media badges and links that you can add to your profile.
6. **github-stats-config.md** - Contains configurations for GitHub stats cards and other profile enhancements.

## Setup Instructions

### 1. Create Your Profile Repository

1. Create a new GitHub repository with the same name as your GitHub username.
2. Clone this repository to your local machine.

### 2. Set Up Your Profile README

1. Copy the contents of `README.md` to your profile repository.
2. Update the personal information, social links, and other details to match your profile.

### 3. Set Up GitHub Workflows

1. Create a `.github/workflows` directory in your profile repository.
2. Copy the `github-metrics.yml` and `snake.yml` files to this directory.
3. Update the username in these files to your GitHub username.

### 4. Set Up Repository Defaults

1. Copy the `.github/config.yml` file to your profile repository.
2. Customize the welcome messages and other settings as needed.

### 5. Add Social Links and Badges

1. Open the `social-links.md` file.
2. Choose the social links and badges you want to add to your profile.
3. Copy the selected sections to your README.md file.
4. Update the usernames and links to match your social media profiles.

### 6. Configure GitHub Stats

1. Open the `github-stats-config.md` file.
2. Choose the stats configurations you want to add to your profile.
3. Copy the selected configurations to your README.md file.
4. Update the username to your GitHub username.

### 7. Set Up Required Secrets

For GitHub Metrics to work properly, you need to add the following secrets to your repository:

1. Go to your repository settings.
2. Navigate to "Secrets and variables" > "Actions".
3. Add the following secrets:
   - `METRICS_TOKEN`: A GitHub Personal Access Token with the necessary permissions.
   - `TWITTER_TOKEN`: If you want to display tweets on your profile.

### 8. Commit and Push

1. Commit all the changes to your profile repository.
2. Push the changes to GitHub.
3. Your GitHub profile should now display all the configured elements.

## Customization

Feel free to customize any of these files to better match your personal style and preferences. You can:

- Change the themes of the stats cards
- Add or remove social links
- Modify the layout of your README
- Add additional sections to showcase your projects or skills

## Troubleshooting

If you encounter any issues:

1. Make sure your repository name exactly matches your GitHub username.
2. Check that all workflow files are in the correct directories.
3. Verify that you've added the necessary secrets for the workflows.
4. Ensure you've replaced all instances of "kiritocroft" with your actual GitHub username.

## Resources

- [GitHub Profile README Generator](https://rahuldkjain.github.io/gh-profile-readme-generator/)
- [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats)
- [GitHub Streak Stats](https://github.com/DenverCoder1/github-readme-streak-stats)
- [GitHub Profile Trophy](https://github.com/ryo-ma/github-profile-trophy)
- [Metrics](https://github.com/lowlighter/metrics)