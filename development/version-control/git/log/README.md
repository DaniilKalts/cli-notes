List all commits for a week.

```
git log --since=1.week
```

List all commits between two dates.

```
git log --after="YYYY-MM-DD" --before="YYYY-MM-DD"
```

List commits in a short form (hash and message).
- You can add `--reverse` option if you wanna see commits in the **ascending order**.

```
git log --oneline
```

List an overview of file(s) lines count changed in each commit.

```
git log --stat
```

List an overview of file(s) content changed in each commit.
- If you wanna see the changes in code over a specific file: **[filename]**.

```
git log -p [filename]
```

List all commits containing **substring**.
- You can use `-i` option if you wanna make grep insensitive.

```
git log —grep="substring"
```

List how many lines were added, removed, left in total by a specified contributor.

```
git log --author="contributor_username" --pretty=tformat: --numstat | awk '{ add += $1; subs += $2; loc += $1 - $2 } END { printf "Added lines: %s,Removed lines: %s, Total lines: %s\n", add, subs, loc }'
```

List top n the most frequently changed files.

```
git log --pretty=format: --name-only | sort | uniq -c | sort -rg | head -n
```

Show the commit where the specified file or directory was removed.

```
git log --diff-filter=D --stat -- path/to/file_or_directory
```

List how many commits were made by each contributor.

```
git shortlog -s -n
```
