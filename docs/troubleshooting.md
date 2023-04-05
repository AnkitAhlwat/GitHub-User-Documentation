## Common Errors 

This section will go over some of the common errors you may encounter while following this guide or using Github and Git in general. For more advanced errors we recommend the official Github documentation [**here**](https://docs.github.com/en)

## Issue: Repository not found or 404 error

This error occurs when trying to access a repository for the following reasons:

1. The repository has been deleted or renamed 
2. You do not have the correct permissions
3. The wrong URL for the repository was entered 

Resolve this error by making sure the repository still exists with the same name, there are no special permissions required to access it and that you copied the correct URl path.

## Issue: Unable to push or pull changes

If you are not able to push or pull changes from a repository it can be for the following reasons:

1. Network issues: ensure that you have a stable internet connection
2. Authentication problems: ensure that you have the required permissions and SSH key (AKA authentication token) is configured correctly. Read more about authentication tokens here: [**here**](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/about-ssh)
3. Repository issue: ensure that the repository still exists
 

## Issue: Merge conflicts

We briefly covered this in the working with Git section, however because it is such a common issue and can be intimidating for new users we will elaborate on it here. As stated previously, merge conflicts occur when two people edit the same line(s) of code in a file. Git does not know which line(s) is the correct one so you must manually decide which changes to keep and which to reject. Here are the steps to resolve it:

1. Pull the most recent changes from the repository
2. If a conflict occurs your IDE will automatically open the conflicted files
3. Look for the conflict markers (<<<<<<<, =======, and >>>>>>>) and choose which changes you wish to keep
4. Edit any file(s) to resolve the conflict
5. Stage and commit the changes
6. Push them back to your repository

## Issue: "Fatal: not a git repository"

This error occurs if you are attempting to run git commands but are not in the correct repository location on your computer. To resolve this:

1. Navigate to the correct directory using CD to change directories
2. If you are unsure of the path to the directory locate the repository on your computer and look at the top of the folder as seen below:
 
