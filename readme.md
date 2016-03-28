# Code Style Lab

Your mission is to clean up ugly JavaScript code. First use `node` to run `friends.js` and see that it runs correctly, but it's ***ugly***. Then edit the file `friends.js` and test it using `jscs`:

```bash
npm install -g jscs        # install jscs if you don't already have it
node friends.js
subl friends.js
jscs -c jscs-options.json friends.js
```

Also try checking the file with `jshint`:

```bash
npm install -g jshint
jshint -c jshint-options.json friends.js
```

Keep improving the code until you get no more errors from `jscs` or from `jshint`. Then run it again to ensure that it still runs correctly:

```bash
node friends.js
```
