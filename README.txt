Branch structure-
main: stable branch containing the initial number guessing game
feature1: branch off main, adds quit feature and documentation, play-again feature, improves user feedback
dev: branch off main, integration branch that adds message for players
feature2: branch off dev, adds max attempts and game over features
feature3: branch off main, adds hint feature
hotfix: fixes randomInt to include correct max value

Learning summary-
Differences: Merge combines two branches along with their histories; rebase rewrites project histories by applying the commits from the current branch to the other branch, creating a linear history; squash combines multiple commits into a single commit; cherry-pick isolates a single commit and applies it to another branch

Histories: feature1 merge displayed the classic branch and converge structure; feature2 was a linear history due to rebase; feature3 was a single, linear commit from the squash

Real projects: Merge is most useful for large teams that need a full history trail for audits or other necessities; rebase is best for personal projects to keep the commit history clean; squash is best for combining many similar or minor commits into a single commit; cherry-pick is best for urgent hotfixes or critical bug fixes