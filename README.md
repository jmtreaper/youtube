# Youtube for Stalker/Ministra portal

&#127482;&#127480; All settings and API key in file

`apps/magcore-app-youtube/3.0.13/youtube.php`

## &#127482;&#127480; Mandatory actions
- &#127482;&#127480; Change your `API_KEY` ([Google Developer Console](https://console.developers.google.com))
- &#127482;&#127480; **chmod 777** `apps/magcore-app-youtube/3.0.13/cache/`

## &#127482;&#127480; Optional actions
### &#127482;&#127480; English localization by default
- If you want by default English interface and keyboard then change `DEFAULT_LANGUAGE_ENGLISH` to __true__ in `apps/magcore-app-youtube/3.0.13/js/release.js`
- Trending and search localization settings in `apps/magcore-app-youtube/3.0.13/youtube.php`

### &#127482;&#127480; Search with API (if key has big quota)
- &#127482;&#127480; Change `API_SEARCH` to __true__

### &#127482;&#127480; Logging search queries in folder .../logs/
- &#127482;&#127480; Change `SEARCH_LOGS` to __true__
- &#127482;&#127480; **chmod 777** `apps/magcore-app-youtube/3.0.13/logs/`

## &#127479; &#127482; What's new:
#### 04/17/2021
- Server side trend caching (15 minutes by default)
- Trends do not change so often, so there is no point in making a request for each client + it is loaded from the cache faster.
- Language set do default english.
- New Api For Non Russian Users.
