# It's Lit! :evergreen_tree:

## What is it? 
*It's Lit* is a GitHub template which you can use to create automated git commits daily, so your GitHub Contribution Graph will be green as a summer field throughout the year. 


## How does it work? 
*It's Lit* utilizes a GitHub action, defined in the [*gitlit*](https://github.com/FredaXin/gitlit) repo. The action can be set on a cron schedule, or triggered manually. The GitHub action will make a randomized number of empty git commits.


## How to use it? 
1. Create a repository from the *It's Lit* template:
   - Click the green "Use this template" button in the upper right.
   - Select "Create a new repository"

2. In your new repo, edit the [`.github/workflows/main.yml`](./.github/workflows/main.yml) file and add in your GitHub username and email.  
(Optional) Edit the cron expression to your desired schedule.     
(Optional) Edit the upper bond and lower bond of the total number of commit per action.  

3. Ensure the Workflow has the correct permissions:  
In GitHub UI, navigate to your newly created repo, go to `settings -> Actions -> Workflow permissions`, choose `Read and write permissons` and then `save`. 


## Cool template, but why? 
"Why do I need this template", you might ask? GitHub has become a hybrid repo host and social network that incentivizes user engagement by [gamification](https://shesho.medium.com/why-gamification-is-broken-and-how-to-fix-it-f12987840eb7). It might appear very productive to make frequent commits to keep your GitHub Contribution graph green, it might even give you some dopamine boosts during your daily GitHub routine, but can it translate into meaningful work and deep engagement? 

Think of *It's Lit* as an automatic lawn sprinkler system: it keeps your graph green and maintains the curb appeal of your GitHub profile; it frees you from busy work so you can do the work that matters.

Let the roots of your thoughts grow deeper, the trunks of your projects grow taller. We can all use more trees than lawns. :evergreen_tree: :evergreen_tree: :evergreen_tree: