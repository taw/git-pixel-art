How to use it:

Create a file with pixel art you want. It must be 7 columns high, and up to 50 columns wide. Example is `1337.txt`

Run script to create repository:

```
$ ./make_git_pixel_art pixel_art.txt repo_name
```

Go to github website, create a new repository `repo_name`

Push this repository to github:

```
$ cd repo_name
$ git remote add origin git@github.com:your_account_name/repo_name.git
$ git push -u origin master
```

(Github website will show you those commands too.)

It will take a few minutes for your home page to refresh. Enjoy.
