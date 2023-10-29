# FacebookFix

**STATUS: Currently Working**

> facebook is a trademark of facebook, Inc. This app is not affiliated with facebook, Inc.

FacebookFix serves fixed facebook image and video embeds. Heavily inspired by [fxtwitter.com](https://github.com/robinuniverse/TwitFix).

## How to use

Add `dd` before `facebook.com` to show facebook embeds.

## Deploy FacebookFix yourself

1. Clone the repository.
2. Install [Poetry](https://python-poetry.org/docs/).
3. Run `poetry install` in the root directory.
4. Deploy with gunicorn or similar server. See [FastAPI Server Workers](https://fastapi.tiangolo.com/deployment/server-workers/).

## Report a bug

You could open an [issue](https://github.com/Wikidepia/FacebookFix/issues).

## TODO

- [ ] Find a way to cram this project to small (1C2G) VPS with sane CPU usage.
- [ ] Find a way to get data without cookies & rate limit.
- [ ] Bypass "Watch on facebook" button.
- [ ] Add multiple third-party website to download videos
