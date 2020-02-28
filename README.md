# Git Commit Msg validation
Validate commit message with starts in defined format or not.

# How to use?

To use this `commit-msg` hook, we have two options.

```
We can directly add this hook inside the .git/hooks/ folder.
```

Anothet option, we can change the hooks path path by hit below command.

```
git config core.hooksPath .githooks
```

It will creates one folder `.githooks` on root. And we can simply copy our hooks inside the folder.

Now when we commit the message which not followed any of defined starting pattern it will throw an erro like this.

```
Bad commit message. please start your msg from defined below patterns followed by one space
[init] 
[config] 
[doc] 
[feature] 
[fix] 
[refactor] 
[wip]
```
