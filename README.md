## Example of Working with Remotes

By Phinyaphak

0. Create an empty repository on Github for your code.
   - copy the URL that Github shows you.

1. Add a remote to your local repository
   ```
   git remote add origin https://github.com/vnsvakanda/example.git
   ```

2. Push some work **and** tell git to use this as the "default" **upstream** repository:
   ```
   git push -u origin master
   ```

3. Next time (git knows your default upstream) just type:
   ```
   git push
   ```
