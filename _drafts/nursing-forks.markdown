---
layout: post
title: "Nursing Forks"

---

{{ Write Intro about how you have some forks on github and that they're easily getting out of sync }}
{{ }}

 - `git clone git@github.com:engeld/forked-example-repo.git`
 - `cd forked-example-repo`
 - `git remote add https://github.com/example-maestro/forked-example-repo.git`
 - `git fetch upstream`
 - `git checkout master`
 - `git merge upstream/master`
 - `git push origin master`
