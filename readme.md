# Code Style Lab

Your mission is to clean up ugly JavaScript code. First use `node` to run `friends.js` and see that it runs correctly, but it's ***ugly***. Then edit the file `friends.js` and test it using `eslint`:

```bash
cd ~/ga/wdi
git clone https://github.com/ATL-WDI-Exercises/codestyle-and-linting
cd codestyle-and-linting
npm install

node friends.js
./node_modules/.bin/eslint friends.js

# subl friends.js
atom friends.js

# now fix thos eslint errors
```

Keep improving the code until you get no more errors from `eslint`. Then run it again to ensure that it still runs correctly:

```bash
node friends.js
```
