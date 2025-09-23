# GitHub Stats Configuration

This file contains various configurations and options for GitHub profile stats tools. You can use these configurations to customize how your GitHub stats are displayed on your profile.

## GitHub README Stats

GitHub README Stats is a tool that dynamically generates stats for your GitHub README. Here are some configuration options:

### Basic Stats Card

```markdown
![Kiritocroft's GitHub stats](https://github-readme-stats.vercel.app/api?username=kiritocroft&show_icons=true)
```

### Customizing Stats Card

```markdown
![Kiritocroft's GitHub stats](https://github-readme-stats.vercel.app/api?username=kiritocroft&show_icons=true&theme=radical&count_private=true&include_all_commits=true&hide_border=true)
```

### Available Themes

You can use these themes by adding `&theme=THEME_NAME` to the stats URL:

- dark
- radical
- merko
- gruvbox
- tokyonight
- onedark
- cobalt
- synthwave
- highcontrast
- dracula

### Hiding Individual Stats

```markdown
![Kiritocroft's GitHub stats](https://github-readme-stats.vercel.app/api?username=kiritocroft&hide=contribs,issues)
```

### Adding Private Contributions Count

```markdown
![Kiritocroft's GitHub stats](https://github-readme-stats.vercel.app/api?username=kiritocroft&count_private=true)
```

### Showing Icons

```markdown
![Kiritocroft's GitHub stats](https://github-readme-stats.vercel.app/api?username=kiritocroft&show_icons=true)
```

## GitHub Streak Stats

GitHub Streak Stats shows your current streak, total contributions, and other stats.

### Basic Streak Stats

```markdown
[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=kiritocroft)](https://github.com/kiritocroft)
```

### Customized Streak Stats

```markdown
[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=kiritocroft&theme=radical&hide_border=true&date_format=M%20j%5B%2C%20Y%5D)](https://github.com/kiritocroft)
```

## Top Languages Card

The Top Languages Card shows your most used languages on GitHub.

### Basic Top Languages Card

```markdown
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=kiritocroft)](https://github.com/kiritocroft)
```

### Compact Layout

```markdown
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=kiritocroft&layout=compact)](https://github.com/kiritocroft)
```

### Hiding Specific Languages

```markdown
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=kiritocroft&hide=javascript,html)](https://github.com/kiritocroft)
```

### Excluding Repositories

```markdown
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=kiritocroft&exclude_repo=repository1,repository2)](https://github.com/kiritocroft)
```

## GitHub Profile Trophy

GitHub Profile Trophy adds a trophy showcase to your profile.

### Basic Trophy Configuration

```markdown
[![trophy](https://github-profile-trophy.vercel.app/?username=kiritocroft)](https://github.com/kiritocroft)
```

### Customized Trophy Configuration

```markdown
[![trophy](https://github-profile-trophy.vercel.app/?username=kiritocroft&theme=radical&no-frame=true&row=1&column=7)](https://github.com/kiritocroft)
```

## Profile Views Counter

Add a counter to track profile views.

```markdown
![Profile Views](https://komarev.com/ghpvc/?username=kiritocroft&color=blueviolet&style=for-the-badge)
```

## Deployment Instructions

To use these stats on your GitHub profile:

1. Create a repository with the same name as your GitHub username
2. Add a README.md file to this repository
3. Copy and paste the desired stats configurations into your README.md
4. Replace "kiritocroft" with your actual GitHub username
5. Commit and push the changes

For GitHub Metrics, you'll need to:

1. Create a Personal Access Token with the appropriate permissions
2. Add this token as a secret named METRICS_TOKEN in your repository settings
3. Set up the workflow file as provided in the .github/workflows directory

For the contribution graph snake animation:

1. Make sure you have the snake.yml workflow file in your .github/workflows directory
2. The workflow will automatically generate the animation and push it to the output branch
3. You can then reference it in your README.md