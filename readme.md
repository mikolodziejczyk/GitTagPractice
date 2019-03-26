Git Tag Practice
---

This is git tag practice area.

1. Lightweight vs. annotated tags - which one to use.
2. Tag naming convention - how are they displayed?
3. Tags for the same commits in multiple branches: you have the same commit in two branches (e.g. after merging master into release with fast-forward). Do you add a tag to both branches or only to one?
4. Open the first Visual Studio Code and clone the project into it.
5. Open the second Visual Studio Code and clone the project into it.
In the first Visual Studio Code:
6. Make some changes into readme.md; commit and push.
The first release, at first untagged.
7. Make some changes into readme.md; commit.
The second release, tagged from scratch.
8. Adding a tag: Add a tag v2.0, "second release"
9. Pushing tags to remote: Push the commit along and the tag to the remote/
Do you have to push the commit and tags separately.
Check whether the tag exists in GitHub.
10. Adding a tag previous commits: Add a tag v1.0 to the first commit (now we are in the second commit).
Send the commit and the tag to remote.
Check whether the tag exists in GitHub.
11. Listing tags: List all tags
List tags that match v1.* pattern.
12. Make yet another change in readme.md
The third release, tagged from scratch.
Tag it using GitLens with v3.0, "third release"
Push changes, check whether the tag existis in the remote.
13. Downloading tags: In the second Visual Studio Code download all the tags from the remote.
14. Removing tags: In the first Visual Studio Code:
	a. remove v1.0 and v2.0 tags from the command line
	b. remove them in the remote from the command line
	c. remove the v3.0 tag from GitLens
	d. remove it in the remote from the command line
15. Pruning tags: In the second Visual Studio Code synchronize the local tags with the remote ones (i.e. remove ones deleted remotely).

Some changes to readme.md from the first.
The second release, tagged from scratch.
