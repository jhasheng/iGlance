# How to Contribute

Thanks for taking the time and wanting to contribute to this project 👍🏼🎉

## How can I start coding?

Before you start coding it is best to directly comment on the issue and tell everyone that you want to work on it. This prevents misunderstandings such that two persons start working on the same issue.

Now that everyone knows that you wanna work on this issue you can start by forking the repository. This will create a copy of the repository on your GitHub account. After cloning your forked repository you have to install all the dependencies of the project using [CocoaPods](https://cocoapods.org) with the following command in the directory `./iGlance` (you should see a file named `Podfile` in this directory):

```
pod install
```

We have a `master` and a `development` branch in this repository. The `master` branch is responsible for all the releases. We push to this branch only if we release a new version of `iGlance`. The development (as the name suggests) is for developing.
Therefore the next step is to create a new branch which is based on the `development` branch. Name your branch after the following scheme:

`feature/<github_issue-id>-<issue_name>`  
`bug-fix/<github_issue_id>-<short_issue_description>`

This will make it clear which issue is referenced by this branch.

Now you can start coding 💻🖥

After you finished implementing the feature you can create a new pull request to merge your feature branch into our `development` branch.
