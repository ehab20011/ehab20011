```
$ git log --oneline --graph ehab/main
```

```
* f4a2b91 (HEAD -> main, origin/main) feat(real-swe): ship the daily project generator
* e1c8d02 feat(freelance): karika motors — luxury rental fleet, cairo
* 9b3f6ae perf(postgres): the queries are fast now. don't ask what they were before
* 8d21e07 feat(nyc): join base layer as software engineer II
*   3e77b12 merge branch 'college' into main
|\
| * b4a9910 docs: B.S. in computer science — CUNY queens college
| * 7aa5138 test(ansys): SDET internship. broke things professionally
|/
* c0ffee1 refactor(career): stop grinding puzzles, start shipping products
* 91b0de3 feat(guitar): learn patience, timing, and playing well with others
* 0000001 initial commit — cairo → queens
```

```
$ git status
```

```
On branch main
Your branch is ahead of 'comfort-zone' by 47 commits.

Changes not staged for commit:
  modified:   real-swe        (new challenges every week)
  modified:   postgres-tricks (ongoing, incurable)

Untracked files:
  side-project-idea-24/
```

```
$ git remote -v
```

| remote | url | |
|---|---|---|
| `work` | [baselayer.com](https://www.baselayer.com) | push |
| `building` | [real-swe.com](https://www.real-swe.com) | push |
| `shipped` | [karikamotors.com](https://karikamotors.com) · [JavaLens](https://github.com/ehab20011/java-lens-mac) · [PPP Analyzer](https://github.com/ehab20011/baselayer) | push |
| `linkedin` | [ehab-abdalla](https://www.linkedin.com/in/ehab-abdalla-04ab411b3/) | fetch |
| `email` | [ehababdalla03@gmail.com](mailto:ehababdalla03@gmail.com) | fetch |

```
$ git push origin main
Everything up-to-date.   (it never is)
```
