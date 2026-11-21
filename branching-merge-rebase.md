cat > docs/branching-merge-rebase.md <<'EOF'
# Branching, Merge and Rebase

## Branching
Branches allow developers to work on separate features without directly changing the main branch.

## Merge
Merge combines changes from one branch into another branch.

## Fast-Forward Merge
A fast-forward merge moves the target branch pointer forward when no divergent commits exist.

## Three-Way Merge
A three-way merge combines changes using a common ancestor when branches have diverged.

## Rebase
Rebase moves or replays commits onto another base commit to create a linear history.

## Checkout and Switch
- git switch: Switch branches.
- git switch -c: Create and switch to a new branch.
