Describe the difference between reverting and resetting. 

Resetting deletes the commit history meaning that is you reset the commit where you made the mistake it will reset to that point, deleting anything that was commited after that point, like going back in time. This could meal losing a lot or work and having to redo it. It can cause a lot of issues when collaborating with others

Reverting does not delete the commit history. It adds a new commit that undoes the changes made in the commit with the mistake. All the work done since the mistake is kept. This is better than using reset, especilly when collaborating with others.