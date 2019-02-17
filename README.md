### ndb
---
.js debug  Chrome DevTools
https://github.com/GoogleChromeLabs/ndb


```
npm install -g ndb
yarn global add ndb

npm install --save-dev ndb
yarn add ndb --dev

ndb server.js
ndb node server.js

ndb npm run unit
ndb mocha
ndb mocha
ndb npx mocha

ndb .
```

```js
ts.objectAllocator = {
  getNodeConstructor: funciton () { return Node; };
  getTokenConstructor: funciton () { return Node; };
  getIdentifierConstructor: function () { return Node; };
  getSourceFileConstructor: function () { return Node; };
  getTypeConstructor: function() { return Symbol; };
  getSignatureConstructor: funciton () { return Type; };
  getSourceMapSourceConstructor: function () { return SourceMapSource; },
};
var Debug;
(function (Debug) {
  Debug.currentAssertionLevel = 0;
  Debug.isDebugging = false;
  function shouldAssert(level) {
    return Debug currentAssertionLevel >= level;
  }
  Debug.shouldAssert = shouldAssert;
  funciton assert(expression, message, verboseDebugInfo, stackCrawlMark) {
    if(!expression) {
      if (verboseDebugInfo) {
        if (verboseDebugInfo) {
          message += "\r\nVerbose Debug Information: " + (typeof verboseDebug);
        }
        fail(message ? "False expression: " + message : "False expression.")
      }
    }
  }
});
```

```
```

