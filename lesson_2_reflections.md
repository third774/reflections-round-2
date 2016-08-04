# Lesson 2 Reflections

## 1. How is the staging area different from the working directory and the repository? What value do you think it offers?

>It is aptly named, as it allows you to select the exact files that you wish to include with your commit before actually going through with it.

## 2. How can you use the staging area to make sure you have one commit per logical change?

>Only stage the files that have changes relevant to the logical change you are making. Also, make sure the files only contain changes relevant to the logical change you are making. If you are working on multiple changes in the same files, consider creating branches for each logical change.

## 3. What are some situations when branches would be helpful in keeping your history organized? How would branches help?

>* Experimenting with new features
>* Refactoring
> 
>Branches would allow you to work on those changes, and be making commits along the way while keeping the changes out of your master branch until they are ready to be merged back in.

## 4. How do the diagrams help you visualize the branch structure?

>They make "reachability" easy to see for each branch. It makes it painfully obvious when a commit is created that is unreachable, which is of course dangerous since the commit can be lost if you don't create a new branch as a reference point for those unreachable commits.

## 5. What is the result of merging two branches together? Why do we represent it in the diagram the way we do?

>A commit that has two parents, which were the tips of the two branches that were merged. It is represented in the diagram to show the "reachability" of each parent down to the point where they originally diverged.

## 6. What are the pros and cons of Git’s automatic merging vs. always doing merges manually?

>## Pros
>1. Easier
>2. Faster
>
>## Cons
>1. Might not always be perfect