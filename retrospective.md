# Final Project Retrospective

## Team Members
- Student 1: Calvin James Maximo
- Student 2: Nadeline Ricafranca

## 1. How did you divide the work between you and your partner?
_(Who worked on which features? How was the work assigned or negotiated?)_

To divide the work, our team first discussed all the features and the order in which they should be implemented. We grouped the features and split them equally, so each member handled two features. One member was assigned **User Registration and Login** and **Product Management,** while the other focused on **Filter Products by Attributes** and **Display Storefront**.

## 2. What Git strategies or commands helped you most during the project?
_(E.g., branching, rebasing, frequent commits, etc.)_

The git commands that were most useful to us were:

- `git checkout -b` to create and switch to our respective feature branches
- `git add`, `git commit`, and `git push` for staging and pushing changes
- `git pull` to keep track with remote changes and keep our local repositories up to date
- `git merge` for integrating the code changes to our main branch

Aside from these commands, the feature-branch strategy where each feature had its own branch also proved to be useful. It allowed us to isolate the work for each feature before they were finalized, reduce conflicts, and keep the main branch stable.

## 3. Describe a merge conflict you encountered. What caused it and how did you resolve it?
_(Include any lessons learned or techniques used to resolve the issue.)_

The merge conflict our team encountered was related to the printing of products in our `display_products()` function in `store_view.pseudo`. This conflict happened because of overlapping work on the same function. Initially, Member 1 implemented the `display_products()` function and handed it off to Member 2, who started working on filters. Meanwhile, Member 1 also made further improvements to the function, which overlapped with Member 2’s ongoing work. 

To resolve the conflict, both members communicated with each other on how to approach the issue. The team coordinated via audio call to thoroughly discuss what happened and what the best step moving forward is. PR comments were also regularly posted per merge to keep the other member informed.
 
## 4. What were the biggest challenges you faced as a team?
_(This can include communication, Git usage, or coordination.)_

One of the biggest challenges we faced during this activity was dividing the work since some features had interdependencies. This meant that one of us had to finish implementing a feature before the other was able to start working on another feature. 

Another challenge we faced was thinking of the implementation of the filtering logic for the product filtering feature. We discussed the best way to approach it before deciding that the numerical filters (length, width, height, weight) are minimum values, and that the color and brand filters should be exact matches.

## 5. What did you learn about using Git in a collaborative setting?
_(Any insights or habits you’d apply in future projects?)_

We learned how it greatly improves the productivity and developer experience in a team setting. Git really made it easy to work on separate features without causing breaking changes in the main branch. The ability to see the whole history of the codebase is also very useful for checking what changes have been done so far to keep the whole team on track.

## 6. How would you improve your workflow next time?
_(Think about technical habits and teamwork practices.)_

We will look into other useful Git commands such as `git rebase` which allows us to have a cleaner commit history compared to solely using `git merge`. For larger codebases, we will delve into the use of GitHub Projects, which is a project management tool for planning and tracking issues and pull requests. We will also fully utilize pull requests as this gives us the ability to go over the changes made by a contributor in a particular branch. The transparency this provides is important in giving us a better understanding of the codebase and the project’s roadmap.   

Additionally, the workflow can also be improved by ensuring that code integration for each feature is done earlier to catch conflicts. Documenting decisions and changes thoroughly–both in code, and in future project boards and commits will also contribute to better traceability and clarity for all members of the team.
 
## 7. Optional: Any feedback on the activity?
_(What worked well? What was confusing or could be improved?)_

