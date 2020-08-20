# Dependabot Demo

An example Maven project from [JitPack](https://jitpack.io/#jitpack/maven-simple) containing outdated dependencies, repurposed to demonstrate GitHub's native [Dependabot integration](https://github.blog/2020-06-01-keep-all-your-packages-up-to-date-with-dependabot/). Demo it yourself by forking this repo or swapping it out for your own project with outdated repositories, and then use the instructions to guide you below! 🤖

How to use Dependabot:
1. **Enable Dependabot:**  
On your GitHub repo navbar/tabs, select Settings &rarr; Security & analysis &rarr; Enable Dependabot alerts and Dependabot security upgrades.  
2. **Configure .github/dependabot.yml:**  
*NOTE: Skip if forking this repo, as it is already present. This is only necessary if you try on your own from scratch.*   
On your GitHub repo navbar/tabs, select Insights &rarr; Dependency graph &rarr; Dependabot &rarr; Create config file (or manually create .github/dependabot.yml) following [the documentation](https://help.github.com/github/administering-a-repository/configuration-options-for-dependency-updates) from GitHub.
*Once the configuration is pushed, your repo should be scanned on the specified timeline, PRing for any needed changes!*
3. **View update check logs:**  
On your GitHub repo navbar/tabs, select Insights &rarr; Dependency graph &rarr; Dependabot and click on the "Last checked x minutes ago"

For more information on Dependabot, check [here](https://docs.github.com/en/github/administering-a-repository/keeping-your-dependencies-updated-automatically).

Trying to use this on GitHub Enteprise? Native GitHub Enterprise support for Dependabot [is not currently available](https://github.com/dependabot/dependabot-core/issues/2149) as of 8/20/2020.
However, you *can* circumvent this by creating a pipeline using Dependabot's core code in automation software like Jenkins to compensate for the above steps. [This article](https://faithlife.codes/blog/2019/12/integrating-dependabot-with-github-enterprise/) by [bgrainger](https://github.com/bgrainger) should help you do that!
