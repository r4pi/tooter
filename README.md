# tooter

Send a toot (publish a post) to Mastodon from the command line.

This small script is adapted from [this blog post](https://shkspr.mobi/blog/2018/08/easy-guide-to-building-mastodon-bots/) from Terence Eden.

## Usage

First create a virtual environment and install the required python packages:

```
python3 -m venv venv
pip install -r requirements.txt
```

Next, add your Mastodon 'access token' (available from the Mastodon "Development" section of your account) to a file called `token.secret` in the same directory as the script.

Once the token is available, you can run `tooter` as follows:

```
./tooter <MESSAGE TEXT>
```

For example:

```
./tooter "this is my message"
```

And it will post the meesage to your Mastodon account.

