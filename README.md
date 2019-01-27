# humblebots.io

HumbleBots


## Development Server Configuration

Run the following command to add the development server as a remote.

```console
bot@humble:~$ git remote add live ssh://humblebots@humblebots.io/var/repo/humblebots.git
```

To deploy new code to the development server, merge it into `master` and run:

```console
bot@humble:~$ git push live master
```
