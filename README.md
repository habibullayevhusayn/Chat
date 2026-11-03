# Yoz — GitHub Pages demo

This is a static, single-file chat interface for GitHub Pages. It does not use a server, backend, or MongoDB.

## Publish with GitHub Pages

1. Push `index.html` to the root of a GitHub repository.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select the branch and `/ (root)` folder, then save.
4. Open the published Pages URL.

## Demo limitations

Usernames and messages are stored only in that browser's local storage. Search only finds usernames created in the same browser, and switching usernames is a local demo feature. Other people on other devices cannot receive or see these messages. Clearing browser data removes the demo data.

GitHub Pages cannot run a Node.js server or safely connect a browser directly to MongoDB. Never put a MongoDB connection string or database password in `index.html` or any public repository file. A real multi-user chat requires a separately hosted backend; this Pages-only version intentionally does not provide one.
