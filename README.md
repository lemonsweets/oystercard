# Oystercard project

We all know how to use an Oyster card to get around London. Let's imagine they don't exist and you are part of the team that is tasked with introducing them. Specifically, you must create the software system that will keep track of all transactions and manage all the cards and associated events (touch in/out, top up, etc).

## Completing this challenge

You can see that a number of [GitHub issues](https://guides.github.com/features/issues/) have been created automatically for you. You will need to close these issues with a pair and get a coach to check your progress as you go

## Working with a pair

Use [GitHub pong](https://github.com/makersacademy/course/blob/master/pills/github_pong.md). You should work one issue and then put in your Pull Request who you paired with. Your pair can then pull down this code onto their machine once you've merged this Pull Request and they can work on the next issue, and so on.

Rotating pairs??

## Closing issues

To close an issue you will need to:

1. Create a branch (it's a good idea to add the issue number and a meaningful name in the branch) - `git checkout -b 1-create-gemfile`
2. Write the code you need to satisfy the requirements of the issue
3. When you're done commit it, adding to the commit message the number of the issue you are closing - `git commit -am "Create Gemfile. Closes #1`
4. and push your branch
5. [Create a pull request](https://help.github.com/articles/creating-a-pull-request/), in the description you need to add your pair partner and which issues you have fixed (don't worry if you don't do this, our automated bot will guide you) - `Created a new Gemfile and ran bundle. Pair @joebloggs, closes #1`
6. Wait for the bot to give you instructions once it's happy your pull request is ready to be checked by a coach, and then merge the pull request (a coach will mark it later)
7. Both you and your pairs should pull master once you've merged the pull request to update your local branch

## Getting your code looked at by a coach

When a coach comes to look at your code they will add a comment to your pull request:

* if they are happy with your code they will add a :checkered_flag:, your issue is now complete congratulations
* if there are things that still need to be done before the issue can be considered complete they will add a :construction: symbol. You now need to fix your issue.

## Fixing your code

To fix it the simplest way is to update the code on whatever branch you or you pair are working on, and then when you submit it add the issue number to your pull request comment.

So if you #1 needs to be fixed, and you're on a branch working on #2, when you submit your pull request for #2 add the code that address #1 and then in the pull request write

```
closes #2 and closes #1
```
