# Projects

This is a repo you can use to start your projects.

Use the [sinatra-app](https://github.com/Gmfholley/sinatra-app) walk throughs as examples to guide you.

1. Log into GitHub and fork this repo to your own account.
1. Click the clone or download link and copy the ssh clone name.  (Toggle between https and ssh until you see Clone with ssh indicator.)
1. In a folder on your computer, open the Windows command prompt and type `git clone ` and then paste the name of the repo you copied.  It might look like `git clone git@github.com:Gmfholley/sheql-start.git`.
1. Change your directory into the folder you just made: `cd sheql-start`.
1. At the prompt type `ruby --version ` to ensure Ruby is installed.
    1. If you get an error that states Ruby is not found, you will need to [install Ruby](https://rubyinstaller.org/downloads/). You must be an administrator on the computer to install Ruby. In general, download the recommeded Ruby version on the page. Once installed, reopen your command prompt.
1. Type `gem install bundler` to install the Ruby bundler gem.
1. Type `bundle install` to install all the gems for this repo.
    1. If you get a message regarding updating bundler or another gem, run the command given to you for upgrading, e.g.: `bundle update --bundler`.
1. `bundle install` to install all the files for this repo.
1. `sudo service postgresql start` to start postgres.

Now that you've installed and started postgres, you're ready to get started.

I have written a little helper method to serve Sinatra instead of `ruby ./app.rb -p $PORT -o $IP`.  Instead, just type in terminal.

```
$ rake serve
```

Enjoy!

1. [Set up Repo](./set_up.md) (If you have done this already for active record, you can skip.)
1. [Set Up Authentication](./google_authentication.md)
1.  Work on your Project!

## At the end of class:
1. [Clean up your layout page](./update_html.md)
1. [Write your blog post](./write_blog_post.md)
1. [Commit and Push Your Changes to GitHub](https://github.com/Gmfholley/git-knock-knock/blob/master/README.md#simple-push-of-master-branch-to-github)
1. [Launch to Heroku (with your teacher)](./launch_to_heroku.md)
