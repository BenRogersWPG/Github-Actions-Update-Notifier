# GitHub Actions Update Notifier

This project will notify you in the form of a pull request when your favorite GitHub Actions are updated.

## How To Use
1. Fork this repository.
2. Update the `notifier.yml` file with the actions you want to monitor. You can find the list of actions in the [notifier file](.github/workflows/notifier.yml)
3. Save and commit
4. Set up and run dependabot, specifically targeting GitHub Actions.
   1. Go to your forked repository on GitHub.
   2. Click on the "Settings" tab.
   3. On the left sidebar, click on "Code Security".
   4. Under the Dependabot section, enable the very last entry, "Dependabot on Actions runners".
   5. Enable other dependabot options if you want to be notified on other aspects of your repository too. Also important if you want to be notified on security vulnerabilities.
5. Update the dependabot file, and replace your username with the one I have set.
   1. Go to the `.github/dependabot.yml` file in your forked repository.
   2. Update the `assignees` section with your username.
   3. Save and commit.


*This project is inspired by Mickey Gousset's [GitHub Actions idea](https://github.com/devopselvis/dependabot-version-updates-example4).*