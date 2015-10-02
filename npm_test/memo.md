# npm_test

## Requirements
- node.js is installed
- browserify is installed

## Procedures
1. Code in the CommonJS style
2. Build the code using browserify so that the web browsers can understand it

## Sample file structure
```
npm_test
├── dest           # Browserify places the built code here
├── index.html     # Has a script tag that is linked to dest/build.js
├── package.json
└── src            # js source files written in the CommonJS style
    ├── add.js     # files are linked to one another
    └── main.js
```

# Reference

- http://qiita.com/megane42/items/2ab6ffd866c3f2fda066?utm_source=Qiita%E3%83%8B%E3%83%A5%E3%83%BC%E3%82%B9&utm_campaign=e5fa4eedd8-Qiita_newsletter_175_09_29_2015&utm_medium=email&utm_term=0_e44feaa081-e5fa4eedd8-33092257#%E5%AE%9F%E8%B7%B5
