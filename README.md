# Solved the problem that Codespace cannot be used
I found so many people have problems with their codespaces. Today I met the same problem that my codespace cannot log in let alone use it.
### Why don't I write the solution on reddit
I've wrote twice, but the reddit automated bot filtered my posts, because my posts were treated as spam.

Suffice to say, my solution is **Delete and Recreate**.

### First, delete your codespace
1. go to [https://code.cs50.io/codespaces](https://code.cs50.io/codespaces)
2. **delete** your codespace

![Delete your codespace](https://github.com/zrmin/CodeSpaceCannotWorked/blob/master/1.png)

### Second, log in your GitHub
1. log in Github
2. **click your avatar** and **choose Settings**

![Choose Settings](https://github.com/zrmin/CodeSpaceCannotWorked/blob/master/2.png)

3. delete **ALL CS50-related** codespace secrets

![Dlete all your cs50 related codespace secrets](https://github.com/zrmin/CodeSpaceCannotWorked/blob/master/3.png)

Note: There may be two or more secrets. **DELETE ALL CS50-RELATED SECRETS**.

### Third, create your new codespace
1. go to [https://code.cs50.io/](https://code.cs50.io/)
2. **Log in via GitHub** to create your new codespace

![Log in via GitHub](https://github.com/zrmin/CodeSpaceCannotWorked/blob/master/4.png)

In my case, my **previous files still exist** in my new codespace.
I hope it helps.

PS:

I don't click **Rebuild now** and execute ***update50*** command, and it has **no impact** on doing CS50'S homework.
