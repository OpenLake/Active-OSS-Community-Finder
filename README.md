<h1 align="center">Welcome to Active Open Source Community Finder 👋</h1>

> Discover healthy open source communities and projects to contribute<br /> 


## 🤔 Problem
Open source contributions are one of the best and fastest way to master any programming language/framework. But, often only a few repositories/organisation get all the attention and this leads to too much crowding in the popular repositories. Some people still manage to stay consistent and gradually become a regular contributor. But the newbies often get confused(and even scared) and don't ever get the opportunity to contribute.

## ✨ Features
- Web app which uses [Github APIs](https://docs.github.com/en/rest) and possibly [CHAOSS Augur](https://github.com/chaoss/augur) to determine community health for different organsations
- Emailing users to stay consistent and notifying whenever new easily fixable issues arise. Github provides issue notifications through email but they aren't specific to a tag(or a comnbination of them). Mostly you'll just find your email being full of github issue emails !
- Tech Stack : React, Django

## 📄 Creating a PR

If you want to optimize this project, add features or remove bugs from this project, you are highly encouraged to do so by creating a PR. Your PR would be reviewed by the maintainer and then it depends on maintainer to merge that PR or not.

If you don't know how to create a PR, don't worry. Here is a step-by-step procedure on how to proceed to create a PR.


**#**  Take a look at the existing or create your own issues. A first good issue can be updating README file. Since Open Lake maintainers are generous enough, it is optional to create a issue or wait for a issue to be assigned to you, you can directly create a PR without creating an issue.

**1.**  Fork repository.

**2.**  Open Git Bash.

**3.**  Clone your forked copy of the repositary.

```
git clone <link of your forked repo>
```

**4.** Navigate to the project directory .

```
cd <repo name>
```

**5.** Add a reference(remote) to the original repository.

```
git remote add upstream <original repo link>
```

**6.** Check the remotes for this repository.

```
git remote -v
```

**7.** Always take a pull from the upstream repository to your master branch to keep it at par with the main project(updated repository).

```
git pull upstream master
```

**8.** Create a new branch.

```
git checkout -b <your branch name>
```

**9.** Perform your desired changes to the code base.

<p align="center"><img width=40% src="https://media.giphy.com/media/QNFhOolVeCzPQ2Mx85/giphy.gif"></p>

**10.** Track your changes .

```
git add . 
```

**11.** Commit your changes .

```
git commit -m "your message"
```

**12.** Push the committed changes in your feature branch to your remote repo.

```
git push -u origin <your branch name>
```

**13.** To create a pull request, click on `compare and pull requests`. Please ensure you compare your feature branch to the desired branch of the repo you are suppose to make a PR to.

**14.** Add appropriate title and description to your pull request explaining your changes. You can see the official PR Format Guidelines [here](https://github.com/OpenLake/Leaderboard-Pro/wiki/PR-Format-Guidelines).

**15.** Click on `Create Pull Request`.

**16.** Congratulations! you have made your PR.

<p align="center"><img src="https://media.giphy.com/media/RLFYsKqesq4Q2zFHlJ/giphy.gif" width=30%></p>

**17.** Now your PR would be reviewed by the maintainer. Sometimes your maintainer would merge your PR request without asking for any further changes.
        
  <p align="center"><img width=40% src="https://media.giphy.com/media/RlrcXMffVZaouUVPGD/giphy.gif"></p>

   But sometimes your PR might be reviewed to infinity.

<p align="center"><img width=40% src="https://tenor.com/view/calculating-talking-computing-gif-15613545.gif"></p>


## Code Contributors

This project exists thanks to all the people who contribute. [[Contribute](CONTRIBUTING.md)].
<a href="https://github.com/openlake/active-oss-community-finder/graphs/contributors"><img src="https://opencollective.com/active-oss-community-finder/contributors.svg?width=890&button=false" /></a>


## Maintainers

👤 **Kumar Shivendu** [@KShivendu](https://github.com/KShivendu)
👤 **Aastha Asthana** [@aastha1999](https://github.com/aastha1999)

---
