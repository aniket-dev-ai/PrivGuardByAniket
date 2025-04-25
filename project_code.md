### `backend\.gitignore`

```
.env
node_modules

```

### `backend\package-lock.json`

```json
{
  "name": "backend",
  "version": "1.0.0",
  "lockfileVersion": 3,
  "requires": true,
  "packages": {
    "": {
      "name": "backend",
      "version": "1.0.0",
      "license": "ISC",
      "dependencies": {
        "@faker-js/faker": "^9.6.0",
        "@imagekit/javascript": "^5.0.0",
        "axios": "^1.8.4",
        "bcrypt": "^5.1.1",
        "cors": "^2.8.5",
        "dotenv": "^16.4.7",
        "express": "^5.1.0",
        "imagekit": "^6.0.0",
        "jsonwebtoken": "^9.0.2",
        "mongoose": "^8.13.2",
        "morgan": "^1.10.0",
        "multer": "^1.4.5-lts.2",
        "node-cron": "^3.0.3",
        "nodemailer": "^6.10.0"
      }
    },
    "node_modules/@faker-js/faker": {
      "version": "9.6.0",
      "resolved": "https://registry.npmjs.org/@faker-js/faker/-/faker-9.6.0.tgz",
      "integrity": "sha512-3vm4by+B5lvsFPSyep3ELWmZfE3kicDtmemVpuwl1yH7tqtnHdsA6hG8fbXedMVdkzgtvzWoRgjSB4Q+FHnZiw==",
      "funding": [
        {
          "type": "opencollective",
          "url": "https://opencollective.com/fakerjs"
        }
      ],
      "license": "MIT",
      "engines": {
        "node": ">=18.0.0",
        "npm": ">=9.0.0"
      }
    },
    "node_modules/@imagekit/javascript": {
      "version": "5.0.0",
      "resolved": "https://registry.npmjs.org/@imagekit/javascript/-/javascript-5.0.0.tgz",
      "integrity": "sha512-Q4qaVHBXrnNFJ6nw7dQTEeyIZzAbz68Z0Y27D4bkiaW3kjpPNoFJEl6XCIiOulBpkVDMteRzjGuKk5bQzgTRRg==",
      "license": "MIT"
    },
    "node_modules/@mapbox/node-pre-gyp": {
      "version": "1.0.11",
      "resolved": "https://registry.npmjs.org/@mapbox/node-pre-gyp/-/node-pre-gyp-1.0.11.tgz",
      "integrity": "sha512-Yhlar6v9WQgUp/He7BdgzOz8lqMQ8sU+jkCq7Wx8Myc5YFJLbEe7lgui/V7G1qB1DJykHSGwreceSaD60Y0PUQ==",
      "license": "BSD-3-Clause",
      "dependencies": {
        "detect-libc": "^2.0.0",
        "https-proxy-agent": "^5.0.0",
        "make-dir": "^3.1.0",
        "node-fetch": "^2.6.7",
        "nopt": "^5.0.0",
        "npmlog": "^5.0.1",
        "rimraf": "^3.0.2",
        "semver": "^7.3.5",
        "tar": "^6.1.11"
      },
      "bin": {
        "node-pre-gyp": "bin/node-pre-gyp"
      }
    },
    "node_modules/@mongodb-js/saslprep": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/@mongodb-js/saslprep/-/saslprep-1.2.0.tgz",
      "integrity": "sha512-+ywrb0AqkfaYuhHs6LxKWgqbh3I72EpEgESCw37o+9qPx9WTCkgDm2B+eMrwehGtHBWHFU4GXvnSCNiFhhausg==",
      "license": "MIT",
      "dependencies": {
        "sparse-bitfield": "^3.0.3"
      }
    },
    "node_modules/@types/webidl-conversions": {
      "version": "7.0.3",
      "resolved": "https://registry.npmjs.org/@types/webidl-conversions/-/webidl-conversions-7.0.3.tgz",
      "integrity": "sha512-CiJJvcRtIgzadHCYXw7dqEnMNRjhGZlYK05Mj9OyktqV8uVT8fD2BFOB7S1uwBE3Kj2Z+4UyPmFw/Ixgw/LAlA==",
      "license": "MIT"
    },
    "node_modules/@types/whatwg-url": {
      "version": "11.0.5",
      "resolved": "https://registry.npmjs.org/@types/whatwg-url/-/whatwg-url-11.0.5.tgz",
      "integrity": "sha512-coYR071JRaHa+xoEvvYqvnIHaVqaYrLPbsufM9BF63HkwI5Lgmy2QR8Q5K/lYDYo5AK82wOvSOS0UsLTpTG7uQ==",
      "license": "MIT",
      "dependencies": {
        "@types/webidl-conversions": "*"
      }
    },
    "node_modules/abbrev": {
      "version": "1.1.1",
      "resolved": "https://registry.npmjs.org/abbrev/-/abbrev-1.1.1.tgz",
      "integrity": "sha512-nne9/IiQ/hzIhY6pdDnbBtz7DjPTKrY00P/zvPSm5pOFkl6xuGrGnXn/VtTNNfNtAfZ9/1RtehkszU9qcTii0Q==",
      "license": "ISC"
    },
    "node_modules/accepts": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/accepts/-/accepts-2.0.0.tgz",
      "integrity": "sha512-5cvg6CtKwfgdmVqY1WIiXKc3Q1bkRqGLi+2W/6ao+6Y7gu/RCwRuAhGEzh5B4KlszSuTLgZYuqFqo5bImjNKng==",
      "license": "MIT",
      "dependencies": {
        "mime-types": "^3.0.0",
        "negotiator": "^1.0.0"
      },
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/agent-base": {
      "version": "6.0.2",
      "resolved": "https://registry.npmjs.org/agent-base/-/agent-base-6.0.2.tgz",
      "integrity": "sha512-RZNwNclF7+MS/8bDg70amg32dyeZGZxiDuQmZxKLAlQjr3jGyLx+4Kkk58UO7D2QdgFIQCovuSuZESne6RG6XQ==",
      "license": "MIT",
      "dependencies": {
        "debug": "4"
      },
      "engines": {
        "node": ">= 6.0.0"
      }
    },
    "node_modules/ansi-regex": {
      "version": "5.0.1",
      "resolved": "https://registry.npmjs.org/ansi-regex/-/ansi-regex-5.0.1.tgz",
      "integrity": "sha512-quJQXlTSUGL2LH9SUXo8VwsY4soanhgo6LNSm84E1LBcE8s3O0wpdiRzyR9z/ZZJMlMWv37qOOb9pdJlMUEKFQ==",
      "license": "MIT",
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/append-field": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/append-field/-/append-field-1.0.0.tgz",
      "integrity": "sha512-klpgFSWLW1ZEs8svjfb7g4qWY0YS5imI82dTg+QahUvJ8YqAY0P10Uk8tTyh9ZGuYEZEMaeJYCF5BFuX552hsw==",
      "license": "MIT"
    },
    "node_modules/aproba": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/aproba/-/aproba-2.0.0.tgz",
      "integrity": "sha512-lYe4Gx7QT+MKGbDsA+Z+he/Wtef0BiwDOlK/XkBrdfsh9J/jPPXbX0tE9x9cl27Tmu5gg3QUbUrQYa/y+KOHPQ==",
      "license": "ISC"
    },
    "node_modules/are-we-there-yet": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/are-we-there-yet/-/are-we-there-yet-2.0.0.tgz",
      "integrity": "sha512-Ci/qENmwHnsYo9xKIcUJN5LeDKdJ6R1Z1j9V/J5wyq8nh/mYPEpIKJbBZXtZjG04HiK7zV/p6Vs9952MrMeUIw==",
      "deprecated": "This package is no longer supported.",
      "license": "ISC",
      "dependencies": {
        "delegates": "^1.0.0",
        "readable-stream": "^3.6.0"
      },
      "engines": {
        "node": ">=10"
      }
    },
    "node_modules/asynckit": {
      "version": "0.4.0",
      "resolved": "https://registry.npmjs.org/asynckit/-/asynckit-0.4.0.tgz",
      "integrity": "sha512-Oei9OH4tRh0YqU3GxhX79dM/mwVgvbZJaSNaRk+bshkj0S5cfHcgYakreBjrHwatXKbz+IoIdYLxrKim2MjW0Q==",
      "license": "MIT"
    },
    "node_modules/axios": {
      "version": "1.8.4",
      "resolved": "https://registry.npmjs.org/axios/-/axios-1.8.4.tgz",
      "integrity": "sha512-eBSYY4Y68NNlHbHBMdeDmKNtDgXWhQsJcGqzO3iLUM0GraQFSS9cVgPX5I9b3lbdFKyYoAEGAZF1DwhTaljNAw==",
      "license": "MIT",
      "dependencies": {
        "follow-redirects": "^1.15.6",
        "form-data": "^4.0.0",
        "proxy-from-env": "^1.1.0"
      }
    },
    "node_modules/balanced-match": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/balanced-match/-/balanced-match-1.0.2.tgz",
      "integrity": "sha512-3oSeUO0TMV67hN1AmbXsK4yaqU7tjiHlbxRDZOpH0KW9+CeX4bRAaX0Anxt0tx2MrpRpWwQaPwIlISEJhYU5Pw==",
      "license": "MIT"
    },
    "node_modules/basic-auth": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/basic-auth/-/basic-auth-2.0.1.tgz",
      "integrity": "sha512-NF+epuEdnUYVlGuhaxbbq+dvJttwLnGY+YixlXlME5KpQ5W3CnXA5cVTneY3SPbPDRkcjMbifrwmFYcClgOZeg==",
      "license": "MIT",
      "dependencies": {
        "safe-buffer": "5.1.2"
      },
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/basic-auth/node_modules/safe-buffer": {
      "version": "5.1.2",
      "resolved": "https://registry.npmjs.org/safe-buffer/-/safe-buffer-5.1.2.tgz",
      "integrity": "sha512-Gd2UZBJDkXlY7GbJxfsE8/nvKkUEU1G38c1siN6QP6a9PT9MmHB8GnpscSmMJSoF8LOIrt8ud/wPtojys4G6+g==",
      "license": "MIT"
    },
    "node_modules/bcrypt": {
      "version": "5.1.1",
      "resolved": "https://registry.npmjs.org/bcrypt/-/bcrypt-5.1.1.tgz",
      "integrity": "sha512-AGBHOG5hPYZ5Xl9KXzU5iKq9516yEmvCKDg3ecP5kX2aB6UqTeXZxk2ELnDgDm6BQSMlLt9rDB4LoSMx0rYwww==",
      "hasInstallScript": true,
      "license": "MIT",
      "dependencies": {
        "@mapbox/node-pre-gyp": "^1.0.11",
        "node-addon-api": "^5.0.0"
      },
      "engines": {
        "node": ">= 10.0.0"
      }
    },
    "node_modules/body-parser": {
      "version": "2.2.0",
      "resolved": "https://registry.npmjs.org/body-parser/-/body-parser-2.2.0.tgz",
      "integrity": "sha512-02qvAaxv8tp7fBa/mw1ga98OGm+eCbqzJOKoRt70sLmfEEi+jyBYVTDGfCL/k06/4EMk/z01gCe7HoCH/f2LTg==",
      "license": "MIT",
      "dependencies": {
        "bytes": "^3.1.2",
        "content-type": "^1.0.5",
        "debug": "^4.4.0",
        "http-errors": "^2.0.0",
        "iconv-lite": "^0.6.3",
        "on-finished": "^2.4.1",
        "qs": "^6.14.0",
        "raw-body": "^3.0.0",
        "type-is": "^2.0.0"
      },
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/brace-expansion": {
      "version": "1.1.11",
      "resolved": "https://registry.npmjs.org/brace-expansion/-/brace-expansion-1.1.11.tgz",
      "integrity": "sha512-iCuPHDFgrHX7H2vEI/5xpz07zSHB00TpugqhmYtVmMO6518mCuRMoOYFldEBl0g187ufozdaHgWKcYFb61qGiA==",
      "license": "MIT",
      "dependencies": {
        "balanced-match": "^1.0.0",
        "concat-map": "0.0.1"
      }
    },
    "node_modules/bson": {
      "version": "6.10.3",
      "resolved": "https://registry.npmjs.org/bson/-/bson-6.10.3.tgz",
      "integrity": "sha512-MTxGsqgYTwfshYWTRdmZRC+M7FnG1b4y7RO7p2k3X24Wq0yv1m77Wsj0BzlPzd/IowgESfsruQCUToa7vbOpPQ==",
      "license": "Apache-2.0",
      "engines": {
        "node": ">=16.20.1"
      }
    },
    "node_modules/buffer-equal-constant-time": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/buffer-equal-constant-time/-/buffer-equal-constant-time-1.0.1.tgz",
      "integrity": "sha512-zRpUiDwd/xk6ADqPMATG8vc9VPrkck7T07OIx0gnjmJAnHnTVXNQG3vfvWNuiZIkwu9KrKdA1iJKfsfTVxE6NA==",
      "license": "BSD-3-Clause"
    },
    "node_modules/buffer-from": {
      "version": "1.1.2",
      "resolved": "https://registry.npmjs.org/buffer-from/-/buffer-from-1.1.2.tgz",
      "integrity": "sha512-E+XQCRwSbaaiChtv6k6Dwgc+bx+Bs6vuKJHHl5kox/BaKbhiXzqQOwK4cO22yElGp2OCmjwVhT3HmxgyPGnJfQ==",
      "license": "MIT"
    },
    "node_modules/busboy": {
      "version": "1.6.0",
      "resolved": "https://registry.npmjs.org/busboy/-/busboy-1.6.0.tgz",
      "integrity": "sha512-8SFQbg/0hQ9xy3UNTB0YEnsNBbWfhf7RtnzpL7TkBiTBRfrQ9Fxcnz7VJsleJpyp6rVLvXiuORqjlHi5q+PYuA==",
      "dependencies": {
        "streamsearch": "^1.1.0"
      },
      "engines": {
        "node": ">=10.16.0"
      }
    },
    "node_modules/bytes": {
      "version": "3.1.2",
      "resolved": "https://registry.npmjs.org/bytes/-/bytes-3.1.2.tgz",
      "integrity": "sha512-/Nf7TyzTx6S3yRJObOAV7956r8cr2+Oj8AC5dt8wSP3BQAoeX58NoHyCU8P8zGkNXStjTSi6fzO6F0pBdcYbEg==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/call-bind-apply-helpers": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/call-bind-apply-helpers/-/call-bind-apply-helpers-1.0.2.tgz",
      "integrity": "sha512-Sp1ablJ0ivDkSzjcaJdxEunN5/XvksFJ2sMBFfq6x0ryhQV/2b/KwFe21cMpmHtPOSij8K99/wSfoEuTObmuMQ==",
      "license": "MIT",
      "dependencies": {
        "es-errors": "^1.3.0",
        "function-bind": "^1.1.2"
      },
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/call-bound": {
      "version": "1.0.4",
      "resolved": "https://registry.npmjs.org/call-bound/-/call-bound-1.0.4.tgz",
      "integrity": "sha512-+ys997U96po4Kx/ABpBCqhA9EuxJaQWDQg7295H4hBphv3IZg0boBKuwYpt4YXp6MZ5AmZQnU/tyMTlRpaSejg==",
      "license": "MIT",
      "dependencies": {
        "call-bind-apply-helpers": "^1.0.2",
        "get-intrinsic": "^1.3.0"
      },
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/chownr": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/chownr/-/chownr-2.0.0.tgz",
      "integrity": "sha512-bIomtDF5KGpdogkLd9VspvFzk9KfpyyGlS8YFVZl7TGPBHL5snIOnxeshwVgPteQ9b4Eydl+pVbIyE1DcvCWgQ==",
      "license": "ISC",
      "engines": {
        "node": ">=10"
      }
    },
    "node_modules/color-support": {
      "version": "1.1.3",
      "resolved": "https://registry.npmjs.org/color-support/-/color-support-1.1.3.tgz",
      "integrity": "sha512-qiBjkpbMLO/HL68y+lh4q0/O1MZFj2RX6X/KmMa3+gJD3z+WwI1ZzDHysvqHGS3mP6mznPckpXmw1nI9cJjyRg==",
      "license": "ISC",
      "bin": {
        "color-support": "bin.js"
      }
    },
    "node_modules/combined-stream": {
      "version": "1.0.8",
      "resolved": "https://registry.npmjs.org/combined-stream/-/combined-stream-1.0.8.tgz",
      "integrity": "sha512-FQN4MRfuJeHf7cBbBMJFXhKSDq+2kAArBlmRBvcvFE5BB1HZKXtSFASDhdlz9zOYwxh8lDdnvmMOe/+5cdoEdg==",
      "license": "MIT",
      "dependencies": {
        "delayed-stream": "~1.0.0"
      },
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/concat-map": {
      "version": "0.0.1",
      "resolved": "https://registry.npmjs.org/concat-map/-/concat-map-0.0.1.tgz",
      "integrity": "sha512-/Srv4dswyQNBfohGpz9o6Yb3Gz3SrUDqBH5rTuhGR7ahtlbYKnVxw2bCFMRljaA7EXHaXZ8wsHdodFvbkhKmqg==",
      "license": "MIT"
    },
    "node_modules/concat-stream": {
      "version": "1.6.2",
      "resolved": "https://registry.npmjs.org/concat-stream/-/concat-stream-1.6.2.tgz",
      "integrity": "sha512-27HBghJxjiZtIk3Ycvn/4kbJk/1uZuJFfuPEns6LaEvpvG1f0hTea8lilrouyo9mVc2GWdcEZ8OLoGmSADlrCw==",
      "engines": [
        "node >= 0.8"
      ],
      "license": "MIT",
      "dependencies": {
        "buffer-from": "^1.0.0",
        "inherits": "^2.0.3",
        "readable-stream": "^2.2.2",
        "typedarray": "^0.0.6"
      }
    },
    "node_modules/concat-stream/node_modules/readable-stream": {
      "version": "2.3.8",
      "resolved": "https://registry.npmjs.org/readable-stream/-/readable-stream-2.3.8.tgz",
      "integrity": "sha512-8p0AUk4XODgIewSi0l8Epjs+EVnWiK7NoDIEGU0HhE7+ZyY8D1IMY7odu5lRrFXGg71L15KG8QrPmum45RTtdA==",
      "license": "MIT",
      "dependencies": {
        "core-util-is": "~1.0.0",
        "inherits": "~2.0.3",
        "isarray": "~1.0.0",
        "process-nextick-args": "~2.0.0",
        "safe-buffer": "~5.1.1",
        "string_decoder": "~1.1.1",
        "util-deprecate": "~1.0.1"
      }
    },
    "node_modules/concat-stream/node_modules/safe-buffer": {
      "version": "5.1.2",
      "resolved": "https://registry.npmjs.org/safe-buffer/-/safe-buffer-5.1.2.tgz",
      "integrity": "sha512-Gd2UZBJDkXlY7GbJxfsE8/nvKkUEU1G38c1siN6QP6a9PT9MmHB8GnpscSmMJSoF8LOIrt8ud/wPtojys4G6+g==",
      "license": "MIT"
    },
    "node_modules/concat-stream/node_modules/string_decoder": {
      "version": "1.1.1",
      "resolved": "https://registry.npmjs.org/string_decoder/-/string_decoder-1.1.1.tgz",
      "integrity": "sha512-n/ShnvDi6FHbbVfviro+WojiFzv+s8MPMHBczVePfUpDJLwoLT0ht1l4YwBCbi8pJAveEEdnkHyPyTP/mzRfwg==",
      "license": "MIT",
      "dependencies": {
        "safe-buffer": "~5.1.0"
      }
    },
    "node_modules/console-control-strings": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/console-control-strings/-/console-control-strings-1.1.0.tgz",
      "integrity": "sha512-ty/fTekppD2fIwRvnZAVdeOiGd1c7YXEixbgJTNzqcxJWKQnjJ/V1bNEEE6hygpM3WjwHFUVK6HTjWSzV4a8sQ==",
      "license": "ISC"
    },
    "node_modules/content-disposition": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/content-disposition/-/content-disposition-1.0.0.tgz",
      "integrity": "sha512-Au9nRL8VNUut/XSzbQA38+M78dzP4D+eqg3gfJHMIHHYa3bg067xj1KxMUWj+VULbiZMowKngFFbKczUrNJ1mg==",
      "license": "MIT",
      "dependencies": {
        "safe-buffer": "5.2.1"
      },
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/content-type": {
      "version": "1.0.5",
      "resolved": "https://registry.npmjs.org/content-type/-/content-type-1.0.5.tgz",
      "integrity": "sha512-nTjqfcBFEipKdXCv4YDQWCfmcLZKm81ldF0pAopTvyrFGVbcR6P/VAAd5G7N+0tTr8QqiU0tFadD6FK4NtJwOA==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/cookie": {
      "version": "0.7.2",
      "resolved": "https://registry.npmjs.org/cookie/-/cookie-0.7.2.tgz",
      "integrity": "sha512-yki5XnKuf750l50uGTllt6kKILY4nQ1eNIQatoXEByZ5dWgnKqbnqmTrBE5B4N7lrMJKQ2ytWMiTO2o0v6Ew/w==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/cookie-signature": {
      "version": "1.2.2",
      "resolved": "https://registry.npmjs.org/cookie-signature/-/cookie-signature-1.2.2.tgz",
      "integrity": "sha512-D76uU73ulSXrD1UXF4KE2TMxVVwhsnCgfAyTg9k8P6KGZjlXKrOLe4dJQKI3Bxi5wjesZoFXJWElNWBjPZMbhg==",
      "license": "MIT",
      "engines": {
        "node": ">=6.6.0"
      }
    },
    "node_modules/core-util-is": {
      "version": "1.0.3",
      "resolved": "https://registry.npmjs.org/core-util-is/-/core-util-is-1.0.3.tgz",
      "integrity": "sha512-ZQBvi1DcpJ4GDqanjucZ2Hj3wEO5pZDS89BWbkcrvdxksJorwUDDZamX9ldFkp9aw2lmBDLgkObEA4DWNJ9FYQ==",
      "license": "MIT"
    },
    "node_modules/cors": {
      "version": "2.8.5",
      "resolved": "https://registry.npmjs.org/cors/-/cors-2.8.5.tgz",
      "integrity": "sha512-KIHbLJqu73RGr/hnbrO9uBeixNGuvSQjul/jdFvS/KFSIH1hWVd1ng7zOHx+YrEfInLG7q4n6GHQ9cDtxv/P6g==",
      "license": "MIT",
      "dependencies": {
        "object-assign": "^4",
        "vary": "^1"
      },
      "engines": {
        "node": ">= 0.10"
      }
    },
    "node_modules/debug": {
      "version": "4.4.0",
      "resolved": "https://registry.npmjs.org/debug/-/debug-4.4.0.tgz",
      "integrity": "sha512-6WTZ/IxCY/T6BALoZHaE4ctp9xm+Z5kY/pzYaCHRFeyVhojxlrm+46y68HA6hr0TcwEssoxNiDEUJQjfPZ/RYA==",
      "license": "MIT",
      "dependencies": {
        "ms": "^2.1.3"
      },
      "engines": {
        "node": ">=6.0"
      },
      "peerDependenciesMeta": {
        "supports-color": {
          "optional": true
        }
      }
    },
    "node_modules/delayed-stream": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/delayed-stream/-/delayed-stream-1.0.0.tgz",
      "integrity": "sha512-ZySD7Nf91aLB0RxL4KGrKHBXl7Eds1DAmEdcoVawXnLD7SDhpNgtuII2aAkg7a7QS41jxPSZ17p4VdGnMHk3MQ==",
      "license": "MIT",
      "engines": {
        "node": ">=0.4.0"
      }
    },
    "node_modules/delegates": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/delegates/-/delegates-1.0.0.tgz",
      "integrity": "sha512-bd2L678uiWATM6m5Z1VzNCErI3jiGzt6HGY8OVICs40JQq/HALfbyNJmp0UDakEY4pMMaN0Ly5om/B1VI/+xfQ==",
      "license": "MIT"
    },
    "node_modules/depd": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/depd/-/depd-2.0.0.tgz",
      "integrity": "sha512-g7nH6P6dyDioJogAAGprGpCtVImJhpPk/roCzdb3fIh61/s/nPsfR6onyMwkCAR/OlC3yBC0lESvUoQEAssIrw==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/detect-libc": {
      "version": "2.0.3",
      "resolved": "https://registry.npmjs.org/detect-libc/-/detect-libc-2.0.3.tgz",
      "integrity": "sha512-bwy0MGW55bG41VqxxypOsdSdGqLwXPI/focwgTYCFMbdUiBAxLg9CFzG08sz2aqzknwiX7Hkl0bQENjg8iLByw==",
      "license": "Apache-2.0",
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/dotenv": {
      "version": "16.4.7",
      "resolved": "https://registry.npmjs.org/dotenv/-/dotenv-16.4.7.tgz",
      "integrity": "sha512-47qPchRCykZC03FhkYAhrvwU4xDBFIj1QPqaarj6mdM/hgUzfPHcpkHJOn3mJAufFeeAxAzeGsr5X0M4k6fLZQ==",
      "license": "BSD-2-Clause",
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://dotenvx.com"
      }
    },
    "node_modules/dunder-proto": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/dunder-proto/-/dunder-proto-1.0.1.tgz",
      "integrity": "sha512-KIN/nDJBQRcXw0MLVhZE9iQHmG68qAVIBg9CqmUYjmQIhgij9U5MFvrqkUL5FbtyyzZuOeOt0zdeRe4UY7ct+A==",
      "license": "MIT",
      "dependencies": {
        "call-bind-apply-helpers": "^1.0.1",
        "es-errors": "^1.3.0",
        "gopd": "^1.2.0"
      },
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/ecdsa-sig-formatter": {
      "version": "1.0.11",
      "resolved": "https://registry.npmjs.org/ecdsa-sig-formatter/-/ecdsa-sig-formatter-1.0.11.tgz",
      "integrity": "sha512-nagl3RYrbNv6kQkeJIpt6NJZy8twLB/2vtz6yN9Z4vRKHN4/QZJIEbqohALSgwKdnksuY3k5Addp5lg8sVoVcQ==",
      "license": "Apache-2.0",
      "dependencies": {
        "safe-buffer": "^5.0.1"
      }
    },
    "node_modules/ee-first": {
      "version": "1.1.1",
      "resolved": "https://registry.npmjs.org/ee-first/-/ee-first-1.1.1.tgz",
      "integrity": "sha512-WMwm9LhRUo+WUaRN+vRuETqG89IgZphVSNkdFgeb6sS/E4OrDIN7t48CAewSHXc6C8lefD8KKfr5vY61brQlow==",
      "license": "MIT"
    },
    "node_modules/emoji-regex": {
      "version": "8.0.0",
      "resolved": "https://registry.npmjs.org/emoji-regex/-/emoji-regex-8.0.0.tgz",
      "integrity": "sha512-MSjYzcWNOA0ewAHpz0MxpYFvwg6yjy1NG3xteoqz644VCo/RPgnr1/GGt+ic3iJTzQ8Eu3TdM14SawnVUmGE6A==",
      "license": "MIT"
    },
    "node_modules/encodeurl": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/encodeurl/-/encodeurl-2.0.0.tgz",
      "integrity": "sha512-Q0n9HRi4m6JuGIV1eFlmvJB7ZEVxu93IrMyiMsGC0lrMJMWzRgx6WGquyfQgZVb31vhGgXnfmPNNXmxnOkRBrg==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/es-define-property": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/es-define-property/-/es-define-property-1.0.1.tgz",
      "integrity": "sha512-e3nRfgfUZ4rNGL232gUgX06QNyyez04KdjFrF+LTRoOXmrOgFKDg4BCdsjW8EnT69eqdYGmRpJwiPVYNrCaW3g==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/es-errors": {
      "version": "1.3.0",
      "resolved": "https://registry.npmjs.org/es-errors/-/es-errors-1.3.0.tgz",
      "integrity": "sha512-Zf5H2Kxt2xjTvbJvP2ZWLEICxA6j+hAmMzIlypy4xcBg1vKVnx89Wy0GbS+kf5cwCVFFzdCFh2XSCFNULS6csw==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/es-object-atoms": {
      "version": "1.1.1",
      "resolved": "https://registry.npmjs.org/es-object-atoms/-/es-object-atoms-1.1.1.tgz",
      "integrity": "sha512-FGgH2h8zKNim9ljj7dankFPcICIK9Cp5bm+c2gQSYePhpaG5+esrLODihIorn+Pe6FGJzWhXQotPv73jTaldXA==",
      "license": "MIT",
      "dependencies": {
        "es-errors": "^1.3.0"
      },
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/es-set-tostringtag": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/es-set-tostringtag/-/es-set-tostringtag-2.1.0.tgz",
      "integrity": "sha512-j6vWzfrGVfyXxge+O0x5sh6cvxAog0a/4Rdd2K36zCMV5eJ+/+tOAngRO8cODMNWbVRdVlmGZQL2YS3yR8bIUA==",
      "license": "MIT",
      "dependencies": {
        "es-errors": "^1.3.0",
        "get-intrinsic": "^1.2.6",
        "has-tostringtag": "^1.0.2",
        "hasown": "^2.0.2"
      },
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/escape-html": {
      "version": "1.0.3",
      "resolved": "https://registry.npmjs.org/escape-html/-/escape-html-1.0.3.tgz",
      "integrity": "sha512-NiSupZ4OeuGwr68lGIeym/ksIZMJodUGOSCZ/FSnTxcrekbvqrgdUxlJOMpijaKZVjAJrWrGs/6Jy8OMuyj9ow==",
      "license": "MIT"
    },
    "node_modules/etag": {
      "version": "1.8.1",
      "resolved": "https://registry.npmjs.org/etag/-/etag-1.8.1.tgz",
      "integrity": "sha512-aIL5Fx7mawVa300al2BnEE4iNvo1qETxLrPI/o05L7z6go7fCw1J6EQmbK4FmJ2AS7kgVF/KEZWufBfdClMcPg==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/express": {
      "version": "5.1.0",
      "resolved": "https://registry.npmjs.org/express/-/express-5.1.0.tgz",
      "integrity": "sha512-DT9ck5YIRU+8GYzzU5kT3eHGA5iL+1Zd0EutOmTE9Dtk+Tvuzd23VBU+ec7HPNSTxXYO55gPV/hq4pSBJDjFpA==",
      "license": "MIT",
      "dependencies": {
        "accepts": "^2.0.0",
        "body-parser": "^2.2.0",
        "content-disposition": "^1.0.0",
        "content-type": "^1.0.5",
        "cookie": "^0.7.1",
        "cookie-signature": "^1.2.1",
        "debug": "^4.4.0",
        "encodeurl": "^2.0.0",
        "escape-html": "^1.0.3",
        "etag": "^1.8.1",
        "finalhandler": "^2.1.0",
        "fresh": "^2.0.0",
        "http-errors": "^2.0.0",
        "merge-descriptors": "^2.0.0",
        "mime-types": "^3.0.0",
        "on-finished": "^2.4.1",
        "once": "^1.4.0",
        "parseurl": "^1.3.3",
        "proxy-addr": "^2.0.7",
        "qs": "^6.14.0",
        "range-parser": "^1.2.1",
        "router": "^2.2.0",
        "send": "^1.1.0",
        "serve-static": "^2.2.0",
        "statuses": "^2.0.1",
        "type-is": "^2.0.1",
        "vary": "^1.1.2"
      },
      "engines": {
        "node": ">= 18"
      },
      "funding": {
        "type": "opencollective",
        "url": "https://opencollective.com/express"
      }
    },
    "node_modules/finalhandler": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/finalhandler/-/finalhandler-2.1.0.tgz",
      "integrity": "sha512-/t88Ty3d5JWQbWYgaOGCCYfXRwV1+be02WqYYlL6h0lEiUAMPM8o8qKGO01YIkOHzka2up08wvgYD0mDiI+q3Q==",
      "license": "MIT",
      "dependencies": {
        "debug": "^4.4.0",
        "encodeurl": "^2.0.0",
        "escape-html": "^1.0.3",
        "on-finished": "^2.4.1",
        "parseurl": "^1.3.3",
        "statuses": "^2.0.1"
      },
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/follow-redirects": {
      "version": "1.15.9",
      "resolved": "https://registry.npmjs.org/follow-redirects/-/follow-redirects-1.15.9.tgz",
      "integrity": "sha512-gew4GsXizNgdoRyqmyfMHyAmXsZDk6mHkSxZFCzW9gwlbtOW44CDtYavM+y+72qD/Vq2l550kMF52DT8fOLJqQ==",
      "funding": [
        {
          "type": "individual",
          "url": "https://github.com/sponsors/RubenVerborgh"
        }
      ],
      "license": "MIT",
      "engines": {
        "node": ">=4.0"
      },
      "peerDependenciesMeta": {
        "debug": {
          "optional": true
        }
      }
    },
    "node_modules/form-data": {
      "version": "4.0.2",
      "resolved": "https://registry.npmjs.org/form-data/-/form-data-4.0.2.tgz",
      "integrity": "sha512-hGfm/slu0ZabnNt4oaRZ6uREyfCj6P4fT/n6A1rGV+Z0VdGXjfOhVUpkn6qVQONHGIFwmveGXyDs75+nr6FM8w==",
      "license": "MIT",
      "dependencies": {
        "asynckit": "^0.4.0",
        "combined-stream": "^1.0.8",
        "es-set-tostringtag": "^2.1.0",
        "mime-types": "^2.1.12"
      },
      "engines": {
        "node": ">= 6"
      }
    },
    "node_modules/form-data/node_modules/mime-db": {
      "version": "1.52.0",
      "resolved": "https://registry.npmjs.org/mime-db/-/mime-db-1.52.0.tgz",
      "integrity": "sha512-sPU4uV7dYlvtWJxwwxHD0PuihVNiE7TyAbQ5SWxDCB9mUYvOgroQOwYQQOKPJ8CIbE+1ETVlOoK1UC2nU3gYvg==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/form-data/node_modules/mime-types": {
      "version": "2.1.35",
      "resolved": "https://registry.npmjs.org/mime-types/-/mime-types-2.1.35.tgz",
      "integrity": "sha512-ZDY+bPm5zTTF+YpCrAU9nK0UgICYPT0QtT1NZWFv4s++TNkcgVaT0g6+4R2uI4MjQjzysHB1zxuWL50hzaeXiw==",
      "license": "MIT",
      "dependencies": {
        "mime-db": "1.52.0"
      },
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/forwarded": {
      "version": "0.2.0",
      "resolved": "https://registry.npmjs.org/forwarded/-/forwarded-0.2.0.tgz",
      "integrity": "sha512-buRG0fpBtRHSTCOASe6hD258tEubFoRLb4ZNA6NxMVHNw2gOcwHo9wyablzMzOA5z9xA9L1KNjk/Nt6MT9aYow==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/fresh": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/fresh/-/fresh-2.0.0.tgz",
      "integrity": "sha512-Rx/WycZ60HOaqLKAi6cHRKKI7zxWbJ31MhntmtwMoaTeF7XFH9hhBp8vITaMidfljRQ6eYWCKkaTK+ykVJHP2A==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/fs-minipass": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/fs-minipass/-/fs-minipass-2.1.0.tgz",
      "integrity": "sha512-V/JgOLFCS+R6Vcq0slCuaeWEdNC3ouDlJMNIsacH2VtALiu9mV4LPrHc5cDl8k5aw6J8jwgWWpiTo5RYhmIzvg==",
      "license": "ISC",
      "dependencies": {
        "minipass": "^3.0.0"
      },
      "engines": {
        "node": ">= 8"
      }
    },
    "node_modules/fs-minipass/node_modules/minipass": {
      "version": "3.3.6",
      "resolved": "https://registry.npmjs.org/minipass/-/minipass-3.3.6.tgz",
      "integrity": "sha512-DxiNidxSEK+tHG6zOIklvNOwm3hvCrbUrdtzY74U6HKTJxvIDfOUL5W5P2Ghd3DTkhhKPYGqeNUIh5qcM4YBfw==",
      "license": "ISC",
      "dependencies": {
        "yallist": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/fs.realpath": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/fs.realpath/-/fs.realpath-1.0.0.tgz",
      "integrity": "sha512-OO0pH2lK6a0hZnAdau5ItzHPI6pUlvI7jMVnxUQRtw4owF2wk8lOSabtGDCTP4Ggrg2MbGnWO9X8K1t4+fGMDw==",
      "license": "ISC"
    },
    "node_modules/function-bind": {
      "version": "1.1.2",
      "resolved": "https://registry.npmjs.org/function-bind/-/function-bind-1.1.2.tgz",
      "integrity": "sha512-7XHNxH7qX9xG5mIwxkhumTox/MIRNcOgDrxWsMt2pAr23WHp6MrRlN7FBSFpCpr+oVO0F744iUgR82nJMfG2SA==",
      "license": "MIT",
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/gauge": {
      "version": "3.0.2",
      "resolved": "https://registry.npmjs.org/gauge/-/gauge-3.0.2.tgz",
      "integrity": "sha512-+5J6MS/5XksCuXq++uFRsnUd7Ovu1XenbeuIuNRJxYWjgQbPuFhT14lAvsWfqfAmnwluf1OwMjz39HjfLPci0Q==",
      "deprecated": "This package is no longer supported.",
      "license": "ISC",
      "dependencies": {
        "aproba": "^1.0.3 || ^2.0.0",
        "color-support": "^1.1.2",
        "console-control-strings": "^1.0.0",
        "has-unicode": "^2.0.1",
        "object-assign": "^4.1.1",
        "signal-exit": "^3.0.0",
        "string-width": "^4.2.3",
        "strip-ansi": "^6.0.1",
        "wide-align": "^1.1.2"
      },
      "engines": {
        "node": ">=10"
      }
    },
    "node_modules/get-intrinsic": {
      "version": "1.3.0",
      "resolved": "https://registry.npmjs.org/get-intrinsic/-/get-intrinsic-1.3.0.tgz",
      "integrity": "sha512-9fSjSaos/fRIVIp+xSJlE6lfwhES7LNtKaCBIamHsjr2na1BiABJPo0mOjjz8GJDURarmCPGqaiVg5mfjb98CQ==",
      "license": "MIT",
      "dependencies": {
        "call-bind-apply-helpers": "^1.0.2",
        "es-define-property": "^1.0.1",
        "es-errors": "^1.3.0",
        "es-object-atoms": "^1.1.1",
        "function-bind": "^1.1.2",
        "get-proto": "^1.0.1",
        "gopd": "^1.2.0",
        "has-symbols": "^1.1.0",
        "hasown": "^2.0.2",
        "math-intrinsics": "^1.1.0"
      },
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/get-proto": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/get-proto/-/get-proto-1.0.1.tgz",
      "integrity": "sha512-sTSfBjoXBp89JvIKIefqw7U2CCebsc74kiY6awiGogKtoSGbgjYE/G/+l9sF3MWFPNc9IcoOC4ODfKHfxFmp0g==",
      "license": "MIT",
      "dependencies": {
        "dunder-proto": "^1.0.1",
        "es-object-atoms": "^1.0.0"
      },
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/glob": {
      "version": "7.2.3",
      "resolved": "https://registry.npmjs.org/glob/-/glob-7.2.3.tgz",
      "integrity": "sha512-nFR0zLpU2YCaRxwoCJvL6UvCH2JFyFVIvwTLsIf21AuHlMskA1hhTdk+LlYJtOlYt9v6dvszD2BGRqBL+iQK9Q==",
      "deprecated": "Glob versions prior to v9 are no longer supported",
      "license": "ISC",
      "dependencies": {
        "fs.realpath": "^1.0.0",
        "inflight": "^1.0.4",
        "inherits": "2",
        "minimatch": "^3.1.1",
        "once": "^1.3.0",
        "path-is-absolute": "^1.0.0"
      },
      "engines": {
        "node": "*"
      },
      "funding": {
        "url": "https://github.com/sponsors/isaacs"
      }
    },
    "node_modules/gopd": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/gopd/-/gopd-1.2.0.tgz",
      "integrity": "sha512-ZUKRh6/kUFoAiTAtTYPZJ3hw9wNxx+BIBOijnlG9PnrJsCcSjs1wyyD6vJpaYtgnzDrKYRSqf3OO6Rfa93xsRg==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/hamming-distance": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/hamming-distance/-/hamming-distance-1.0.0.tgz",
      "integrity": "sha512-hYz2IIKtyuZGfOqCs7skNiFEATf+v9IUNSOaQSr6Ll4JOxxWhOvXvc3mIdCW82Z3xW+zUoto7N/ssD4bDxAWoA==",
      "license": "MIT"
    },
    "node_modules/has-symbols": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/has-symbols/-/has-symbols-1.1.0.tgz",
      "integrity": "sha512-1cDNdwJ2Jaohmb3sg4OmKaMBwuC48sYni5HUw2DvsC8LjGTLK9h+eb1X6RyuOHe4hT0ULCW68iomhjUoKUqlPQ==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/has-tostringtag": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/has-tostringtag/-/has-tostringtag-1.0.2.tgz",
      "integrity": "sha512-NqADB8VjPFLM2V0VvHUewwwsw0ZWBaIdgo+ieHtK3hasLz4qeCRjYcqfB6AQrBggRKppKF8L52/VqdVsO47Dlw==",
      "license": "MIT",
      "dependencies": {
        "has-symbols": "^1.0.3"
      },
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/has-unicode": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/has-unicode/-/has-unicode-2.0.1.tgz",
      "integrity": "sha512-8Rf9Y83NBReMnx0gFzA8JImQACstCYWUplepDa9xprwwtmgEZUF0h/i5xSA625zB/I37EtrswSST6OXxwaaIJQ==",
      "license": "ISC"
    },
    "node_modules/hasown": {
      "version": "2.0.2",
      "resolved": "https://registry.npmjs.org/hasown/-/hasown-2.0.2.tgz",
      "integrity": "sha512-0hJU9SCPvmMzIBdZFqNPXWa6dqh7WdH0cII9y+CyS8rG3nL48Bclra9HmKhVVUHyPWNH5Y7xDwAB7bfgSjkUMQ==",
      "license": "MIT",
      "dependencies": {
        "function-bind": "^1.1.2"
      },
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/http-errors": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/http-errors/-/http-errors-2.0.0.tgz",
      "integrity": "sha512-FtwrG/euBzaEjYeRqOgly7G0qviiXoJWnvEH2Z1plBdXgbyjv34pHTSb9zoeHMyDy33+DWy5Wt9Wo+TURtOYSQ==",
      "license": "MIT",
      "dependencies": {
        "depd": "2.0.0",
        "inherits": "2.0.4",
        "setprototypeof": "1.2.0",
        "statuses": "2.0.1",
        "toidentifier": "1.0.1"
      },
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/https-proxy-agent": {
      "version": "5.0.1",
      "resolved": "https://registry.npmjs.org/https-proxy-agent/-/https-proxy-agent-5.0.1.tgz",
      "integrity": "sha512-dFcAjpTQFgoLMzC2VwU+C/CbS7uRL0lWmxDITmqm7C+7F0Odmj6s9l6alZc6AELXhrnggM2CeWSXHGOdX2YtwA==",
      "license": "MIT",
      "dependencies": {
        "agent-base": "6",
        "debug": "4"
      },
      "engines": {
        "node": ">= 6"
      }
    },
    "node_modules/iconv-lite": {
      "version": "0.6.3",
      "resolved": "https://registry.npmjs.org/iconv-lite/-/iconv-lite-0.6.3.tgz",
      "integrity": "sha512-4fCk79wshMdzMp2rH06qWrJE4iolqLhCUH+OiuIgU++RB0+94NlDL81atO7GX55uUKueo0txHNtvEyI6D7WdMw==",
      "license": "MIT",
      "dependencies": {
        "safer-buffer": ">= 2.1.2 < 3.0.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/imagekit": {
      "version": "6.0.0",
      "resolved": "https://registry.npmjs.org/imagekit/-/imagekit-6.0.0.tgz",
      "integrity": "sha512-0MsxThZM2PYH6ngwN3zi9PDa8pCB5mEZG2FSySYiZk3Hfri8IMwUqVNzRlLQewBHQ3YtTN9M59O0Xe9HRewtOA==",
      "license": "MIT",
      "dependencies": {
        "axios": "^1.6.5",
        "form-data": "^4.0.0",
        "hamming-distance": "^1.0.0",
        "lodash": "^4.17.15",
        "tslib": "^2.4.0",
        "uuid": "^8.3.2"
      },
      "engines": {
        "node": ">=12.0.0"
      }
    },
    "node_modules/inflight": {
      "version": "1.0.6",
      "resolved": "https://registry.npmjs.org/inflight/-/inflight-1.0.6.tgz",
      "integrity": "sha512-k92I/b08q4wvFscXCLvqfsHCrjrF7yiXsQuIVvVE7N82W3+aqpzuUdBbfhWcy/FZR3/4IgflMgKLOsvPDrGCJA==",
      "deprecated": "This module is not supported, and leaks memory. Do not use it. Check out lru-cache if you want a good and tested way to coalesce async requests by a key value, which is much more comprehensive and powerful.",
      "license": "ISC",
      "dependencies": {
        "once": "^1.3.0",
        "wrappy": "1"
      }
    },
    "node_modules/inherits": {
      "version": "2.0.4",
      "resolved": "https://registry.npmjs.org/inherits/-/inherits-2.0.4.tgz",
      "integrity": "sha512-k/vGaX4/Yla3WzyMCvTQOXYeIHvqOKtnqBduzTHpzpQZzAskKMhZ2K+EnBiSM9zGSoIFeMpXKxa4dYeZIQqewQ==",
      "license": "ISC"
    },
    "node_modules/ipaddr.js": {
      "version": "1.9.1",
      "resolved": "https://registry.npmjs.org/ipaddr.js/-/ipaddr.js-1.9.1.tgz",
      "integrity": "sha512-0KI/607xoxSToH7GjN1FfSbLoU0+btTicjsQSWQlh/hZykN8KpmMf7uYwPW3R+akZ6R/w18ZlXSHBYXiYUPO3g==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.10"
      }
    },
    "node_modules/is-fullwidth-code-point": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/is-fullwidth-code-point/-/is-fullwidth-code-point-3.0.0.tgz",
      "integrity": "sha512-zymm5+u+sCsSWyD9qNaejV3DFvhCKclKdizYaJUuHA83RLjb7nSuGnddCHGv0hk+KY7BMAlsWeK4Ueg6EV6XQg==",
      "license": "MIT",
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/is-promise": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/is-promise/-/is-promise-4.0.0.tgz",
      "integrity": "sha512-hvpoI6korhJMnej285dSg6nu1+e6uxs7zG3BYAm5byqDsgJNWwxzM6z6iZiAgQR4TJ30JmBTOwqZUw3WlyH3AQ==",
      "license": "MIT"
    },
    "node_modules/isarray": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/isarray/-/isarray-1.0.0.tgz",
      "integrity": "sha512-VLghIWNM6ELQzo7zwmcg0NmTVyWKYjvIeM83yjp0wRDTmUnrM678fQbcKBo6n2CJEF0szoG//ytg+TKla89ALQ==",
      "license": "MIT"
    },
    "node_modules/jsonwebtoken": {
      "version": "9.0.2",
      "resolved": "https://registry.npmjs.org/jsonwebtoken/-/jsonwebtoken-9.0.2.tgz",
      "integrity": "sha512-PRp66vJ865SSqOlgqS8hujT5U4AOgMfhrwYIuIhfKaoSCZcirrmASQr8CX7cUg+RMih+hgznrjp99o+W4pJLHQ==",
      "license": "MIT",
      "dependencies": {
        "jws": "^3.2.2",
        "lodash.includes": "^4.3.0",
        "lodash.isboolean": "^3.0.3",
        "lodash.isinteger": "^4.0.4",
        "lodash.isnumber": "^3.0.3",
        "lodash.isplainobject": "^4.0.6",
        "lodash.isstring": "^4.0.1",
        "lodash.once": "^4.0.0",
        "ms": "^2.1.1",
        "semver": "^7.5.4"
      },
      "engines": {
        "node": ">=12",
        "npm": ">=6"
      }
    },
    "node_modules/jwa": {
      "version": "1.4.1",
      "resolved": "https://registry.npmjs.org/jwa/-/jwa-1.4.1.tgz",
      "integrity": "sha512-qiLX/xhEEFKUAJ6FiBMbes3w9ATzyk5W7Hvzpa/SLYdxNtng+gcurvrI7TbACjIXlsJyr05/S1oUhZrc63evQA==",
      "license": "MIT",
      "dependencies": {
        "buffer-equal-constant-time": "1.0.1",
        "ecdsa-sig-formatter": "1.0.11",
        "safe-buffer": "^5.0.1"
      }
    },
    "node_modules/jws": {
      "version": "3.2.2",
      "resolved": "https://registry.npmjs.org/jws/-/jws-3.2.2.tgz",
      "integrity": "sha512-YHlZCB6lMTllWDtSPHz/ZXTsi8S00usEV6v1tjq8tOUZzw7DpSDWVXjXDre6ed1w/pd495ODpHZYSdkRTsa0HA==",
      "license": "MIT",
      "dependencies": {
        "jwa": "^1.4.1",
        "safe-buffer": "^5.0.1"
      }
    },
    "node_modules/kareem": {
      "version": "2.6.3",
      "resolved": "https://registry.npmjs.org/kareem/-/kareem-2.6.3.tgz",
      "integrity": "sha512-C3iHfuGUXK2u8/ipq9LfjFfXFxAZMQJJq7vLS45r3D9Y2xQ/m4S8zaR4zMLFWh9AsNPXmcFfUDhTEO8UIC/V6Q==",
      "license": "Apache-2.0",
      "engines": {
        "node": ">=12.0.0"
      }
    },
    "node_modules/lodash": {
      "version": "4.17.21",
      "resolved": "https://registry.npmjs.org/lodash/-/lodash-4.17.21.tgz",
      "integrity": "sha512-v2kDEe57lecTulaDIuNTPy3Ry4gLGJ6Z1O3vE1krgXZNrsQ+LFTGHVxVjcXPs17LhbZVGedAJv8XZ1tvj5FvSg==",
      "license": "MIT"
    },
    "node_modules/lodash.includes": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/lodash.includes/-/lodash.includes-4.3.0.tgz",
      "integrity": "sha512-W3Bx6mdkRTGtlJISOvVD/lbqjTlPPUDTMnlXZFnVwi9NKJ6tiAk6LVdlhZMm17VZisqhKcgzpO5Wz91PCt5b0w==",
      "license": "MIT"
    },
    "node_modules/lodash.isboolean": {
      "version": "3.0.3",
      "resolved": "https://registry.npmjs.org/lodash.isboolean/-/lodash.isboolean-3.0.3.tgz",
      "integrity": "sha512-Bz5mupy2SVbPHURB98VAcw+aHh4vRV5IPNhILUCsOzRmsTmSQ17jIuqopAentWoehktxGd9e/hbIXq980/1QJg==",
      "license": "MIT"
    },
    "node_modules/lodash.isinteger": {
      "version": "4.0.4",
      "resolved": "https://registry.npmjs.org/lodash.isinteger/-/lodash.isinteger-4.0.4.tgz",
      "integrity": "sha512-DBwtEWN2caHQ9/imiNeEA5ys1JoRtRfY3d7V9wkqtbycnAmTvRRmbHKDV4a0EYc678/dia0jrte4tjYwVBaZUA==",
      "license": "MIT"
    },
    "node_modules/lodash.isnumber": {
      "version": "3.0.3",
      "resolved": "https://registry.npmjs.org/lodash.isnumber/-/lodash.isnumber-3.0.3.tgz",
      "integrity": "sha512-QYqzpfwO3/CWf3XP+Z+tkQsfaLL/EnUlXWVkIk5FUPc4sBdTehEqZONuyRt2P67PXAk+NXmTBcc97zw9t1FQrw==",
      "license": "MIT"
    },
    "node_modules/lodash.isplainobject": {
      "version": "4.0.6",
      "resolved": "https://registry.npmjs.org/lodash.isplainobject/-/lodash.isplainobject-4.0.6.tgz",
      "integrity": "sha512-oSXzaWypCMHkPC3NvBEaPHf0KsA5mvPrOPgQWDsbg8n7orZ290M0BmC/jgRZ4vcJ6DTAhjrsSYgdsW/F+MFOBA==",
      "license": "MIT"
    },
    "node_modules/lodash.isstring": {
      "version": "4.0.1",
      "resolved": "https://registry.npmjs.org/lodash.isstring/-/lodash.isstring-4.0.1.tgz",
      "integrity": "sha512-0wJxfxH1wgO3GrbuP+dTTk7op+6L41QCXbGINEmD+ny/G/eCqGzxyCsh7159S+mgDDcoarnBw6PC1PS5+wUGgw==",
      "license": "MIT"
    },
    "node_modules/lodash.once": {
      "version": "4.1.1",
      "resolved": "https://registry.npmjs.org/lodash.once/-/lodash.once-4.1.1.tgz",
      "integrity": "sha512-Sb487aTOCr9drQVL8pIxOzVhafOjZN9UU54hiN8PU3uAiSV7lx1yYNpbNmex2PK6dSJoNTSJUUswT651yww3Mg==",
      "license": "MIT"
    },
    "node_modules/make-dir": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/make-dir/-/make-dir-3.1.0.tgz",
      "integrity": "sha512-g3FeP20LNwhALb/6Cz6Dd4F2ngze0jz7tbzrD2wAV+o9FeNHe4rL+yK2md0J/fiSf1sa1ADhXqi5+oVwOM/eGw==",
      "license": "MIT",
      "dependencies": {
        "semver": "^6.0.0"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/make-dir/node_modules/semver": {
      "version": "6.3.1",
      "resolved": "https://registry.npmjs.org/semver/-/semver-6.3.1.tgz",
      "integrity": "sha512-BR7VvDCVHO+q2xBEWskxS6DJE1qRnb7DxzUrogb71CWoSficBxYsiAGd+Kl0mmq/MprG9yArRkyrQxTO6XjMzA==",
      "license": "ISC",
      "bin": {
        "semver": "bin/semver.js"
      }
    },
    "node_modules/math-intrinsics": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/math-intrinsics/-/math-intrinsics-1.1.0.tgz",
      "integrity": "sha512-/IXtbwEk5HTPyEwyKX6hGkYXxM9nbj64B+ilVJnC/R6B0pH5G4V3b0pVbL7DBj4tkhBAppbQUlf6F6Xl9LHu1g==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/media-typer": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/media-typer/-/media-typer-1.1.0.tgz",
      "integrity": "sha512-aisnrDP4GNe06UcKFnV5bfMNPBUw4jsLGaWwWfnH3v02GnBuXX2MCVn5RbrWo0j3pczUilYblq7fQ7Nw2t5XKw==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/memory-pager": {
      "version": "1.5.0",
      "resolved": "https://registry.npmjs.org/memory-pager/-/memory-pager-1.5.0.tgz",
      "integrity": "sha512-ZS4Bp4r/Zoeq6+NLJpP+0Zzm0pR8whtGPf1XExKLJBAczGMnSi3It14OiNCStjQjM6NU1okjQGSxgEZN8eBYKg==",
      "license": "MIT"
    },
    "node_modules/merge-descriptors": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/merge-descriptors/-/merge-descriptors-2.0.0.tgz",
      "integrity": "sha512-Snk314V5ayFLhp3fkUREub6WtjBfPdCPY1Ln8/8munuLuiYhsABgBVWsozAG+MWMbVEvcdcpbi9R7ww22l9Q3g==",
      "license": "MIT",
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/mime-db": {
      "version": "1.54.0",
      "resolved": "https://registry.npmjs.org/mime-db/-/mime-db-1.54.0.tgz",
      "integrity": "sha512-aU5EJuIN2WDemCcAp2vFBfp/m4EAhWJnUNSSw0ixs7/kXbd6Pg64EmwJkNdFhB8aWt1sH2CTXrLxo/iAGV3oPQ==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/mime-types": {
      "version": "3.0.1",
      "resolved": "https://registry.npmjs.org/mime-types/-/mime-types-3.0.1.tgz",
      "integrity": "sha512-xRc4oEhT6eaBpU1XF7AjpOFD+xQmXNB5OVKwp4tqCuBpHLS/ZbBDrc07mYTDqVMg6PfxUjjNp85O6Cd2Z/5HWA==",
      "license": "MIT",
      "dependencies": {
        "mime-db": "^1.54.0"
      },
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/minimatch": {
      "version": "3.1.2",
      "resolved": "https://registry.npmjs.org/minimatch/-/minimatch-3.1.2.tgz",
      "integrity": "sha512-J7p63hRiAjw1NDEww1W7i37+ByIrOWO5XQQAzZ3VOcL0PNybwpfmV/N05zFAzwQ9USyEcX6t3UO+K5aqBQOIHw==",
      "license": "ISC",
      "dependencies": {
        "brace-expansion": "^1.1.7"
      },
      "engines": {
        "node": "*"
      }
    },
    "node_modules/minimist": {
      "version": "1.2.8",
      "resolved": "https://registry.npmjs.org/minimist/-/minimist-1.2.8.tgz",
      "integrity": "sha512-2yyAR8qBkN3YuheJanUpWC5U3bb5osDywNB8RzDVlDwDHbocAJveqqj1u8+SVD7jkWT4yvsHCpWqqWqAxb0zCA==",
      "license": "MIT",
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/minipass": {
      "version": "5.0.0",
      "resolved": "https://registry.npmjs.org/minipass/-/minipass-5.0.0.tgz",
      "integrity": "sha512-3FnjYuehv9k6ovOEbyOswadCDPX1piCfhV8ncmYtHOjuPwylVWsghTLo7rabjC3Rx5xD4HDx8Wm1xnMF7S5qFQ==",
      "license": "ISC",
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/minizlib": {
      "version": "2.1.2",
      "resolved": "https://registry.npmjs.org/minizlib/-/minizlib-2.1.2.tgz",
      "integrity": "sha512-bAxsR8BVfj60DWXHE3u30oHzfl4G7khkSuPW+qvpd7jFRHm7dLxOjUk1EHACJ/hxLY8phGJ0YhYHZo7jil7Qdg==",
      "license": "MIT",
      "dependencies": {
        "minipass": "^3.0.0",
        "yallist": "^4.0.0"
      },
      "engines": {
        "node": ">= 8"
      }
    },
    "node_modules/minizlib/node_modules/minipass": {
      "version": "3.3.6",
      "resolved": "https://registry.npmjs.org/minipass/-/minipass-3.3.6.tgz",
      "integrity": "sha512-DxiNidxSEK+tHG6zOIklvNOwm3hvCrbUrdtzY74U6HKTJxvIDfOUL5W5P2Ghd3DTkhhKPYGqeNUIh5qcM4YBfw==",
      "license": "ISC",
      "dependencies": {
        "yallist": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/mkdirp": {
      "version": "1.0.4",
      "resolved": "https://registry.npmjs.org/mkdirp/-/mkdirp-1.0.4.tgz",
      "integrity": "sha512-vVqVZQyf3WLx2Shd0qJ9xuvqgAyKPLAiqITEtqW0oIUjzo3PePDd6fW9iFz30ef7Ysp/oiWqbhszeGWW2T6Gzw==",
      "license": "MIT",
      "bin": {
        "mkdirp": "bin/cmd.js"
      },
      "engines": {
        "node": ">=10"
      }
    },
    "node_modules/mongodb": {
      "version": "6.15.0",
      "resolved": "https://registry.npmjs.org/mongodb/-/mongodb-6.15.0.tgz",
      "integrity": "sha512-ifBhQ0rRzHDzqp9jAQP6OwHSH7dbYIQjD3SbJs9YYk9AikKEettW/9s/tbSFDTpXcRbF+u1aLrhHxDFaYtZpFQ==",
      "license": "Apache-2.0",
      "dependencies": {
        "@mongodb-js/saslprep": "^1.1.9",
        "bson": "^6.10.3",
        "mongodb-connection-string-url": "^3.0.0"
      },
      "engines": {
        "node": ">=16.20.1"
      },
      "peerDependencies": {
        "@aws-sdk/credential-providers": "^3.188.0",
        "@mongodb-js/zstd": "^1.1.0 || ^2.0.0",
        "gcp-metadata": "^5.2.0",
        "kerberos": "^2.0.1",
        "mongodb-client-encryption": ">=6.0.0 <7",
        "snappy": "^7.2.2",
        "socks": "^2.7.1"
      },
      "peerDependenciesMeta": {
        "@aws-sdk/credential-providers": {
          "optional": true
        },
        "@mongodb-js/zstd": {
          "optional": true
        },
        "gcp-metadata": {
          "optional": true
        },
        "kerberos": {
          "optional": true
        },
        "mongodb-client-encryption": {
          "optional": true
        },
        "snappy": {
          "optional": true
        },
        "socks": {
          "optional": true
        }
      }
    },
    "node_modules/mongodb-connection-string-url": {
      "version": "3.0.2",
      "resolved": "https://registry.npmjs.org/mongodb-connection-string-url/-/mongodb-connection-string-url-3.0.2.tgz",
      "integrity": "sha512-rMO7CGo/9BFwyZABcKAWL8UJwH/Kc2x0g72uhDWzG48URRax5TCIcJ7Rc3RZqffZzO/Gwff/jyKwCU9TN8gehA==",
      "license": "Apache-2.0",
      "dependencies": {
        "@types/whatwg-url": "^11.0.2",
        "whatwg-url": "^14.1.0 || ^13.0.0"
      }
    },
    "node_modules/mongoose": {
      "version": "8.13.2",
      "resolved": "https://registry.npmjs.org/mongoose/-/mongoose-8.13.2.tgz",
      "integrity": "sha512-riCBqZmNkYBWjXpM3qWLDQw7QmTKsVZDPhLXFJqC87+OjocEVpvS3dA2BPPUiLAu+m0/QmEj5pSXKhH+/DgerQ==",
      "license": "MIT",
      "dependencies": {
        "bson": "^6.10.3",
        "kareem": "2.6.3",
        "mongodb": "~6.15.0",
        "mpath": "0.9.0",
        "mquery": "5.0.0",
        "ms": "2.1.3",
        "sift": "17.1.3"
      },
      "engines": {
        "node": ">=16.20.1"
      },
      "funding": {
        "type": "opencollective",
        "url": "https://opencollective.com/mongoose"
      }
    },
    "node_modules/morgan": {
      "version": "1.10.0",
      "resolved": "https://registry.npmjs.org/morgan/-/morgan-1.10.0.tgz",
      "integrity": "sha512-AbegBVI4sh6El+1gNwvD5YIck7nSA36weD7xvIxG4in80j/UoK8AEGaWnnz8v1GxonMCltmlNs5ZKbGvl9b1XQ==",
      "license": "MIT",
      "dependencies": {
        "basic-auth": "~2.0.1",
        "debug": "2.6.9",
        "depd": "~2.0.0",
        "on-finished": "~2.3.0",
        "on-headers": "~1.0.2"
      },
      "engines": {
        "node": ">= 0.8.0"
      }
    },
    "node_modules/morgan/node_modules/debug": {
      "version": "2.6.9",
      "resolved": "https://registry.npmjs.org/debug/-/debug-2.6.9.tgz",
      "integrity": "sha512-bC7ElrdJaJnPbAP+1EotYvqZsb3ecl5wi6Bfi6BJTUcNowp6cvspg0jXznRTKDjm/E7AdgFBVeAPVMNcKGsHMA==",
      "license": "MIT",
      "dependencies": {
        "ms": "2.0.0"
      }
    },
    "node_modules/morgan/node_modules/ms": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/ms/-/ms-2.0.0.tgz",
      "integrity": "sha512-Tpp60P6IUJDTuOq/5Z8cdskzJujfwqfOTkrwIwj7IRISpnkJnT6SyJ4PCPnGMoFjC9ddhal5KVIYtAt97ix05A==",
      "license": "MIT"
    },
    "node_modules/morgan/node_modules/on-finished": {
      "version": "2.3.0",
      "resolved": "https://registry.npmjs.org/on-finished/-/on-finished-2.3.0.tgz",
      "integrity": "sha512-ikqdkGAAyf/X/gPhXGvfgAytDZtDbr+bkNUJ0N9h5MI/dmdgCs3l6hoHrcUv41sRKew3jIwrp4qQDXiK99Utww==",
      "license": "MIT",
      "dependencies": {
        "ee-first": "1.1.1"
      },
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/mpath": {
      "version": "0.9.0",
      "resolved": "https://registry.npmjs.org/mpath/-/mpath-0.9.0.tgz",
      "integrity": "sha512-ikJRQTk8hw5DEoFVxHG1Gn9T/xcjtdnOKIU1JTmGjZZlg9LST2mBLmcX3/ICIbgJydT2GOc15RnNy5mHmzfSew==",
      "license": "MIT",
      "engines": {
        "node": ">=4.0.0"
      }
    },
    "node_modules/mquery": {
      "version": "5.0.0",
      "resolved": "https://registry.npmjs.org/mquery/-/mquery-5.0.0.tgz",
      "integrity": "sha512-iQMncpmEK8R8ncT8HJGsGc9Dsp8xcgYMVSbs5jgnm1lFHTZqMJTUWTDx1LBO8+mK3tPNZWFLBghQEIOULSTHZg==",
      "license": "MIT",
      "dependencies": {
        "debug": "4.x"
      },
      "engines": {
        "node": ">=14.0.0"
      }
    },
    "node_modules/ms": {
      "version": "2.1.3",
      "resolved": "https://registry.npmjs.org/ms/-/ms-2.1.3.tgz",
      "integrity": "sha512-6FlzubTLZG3J2a/NVCAleEhjzq5oxgHyaCU9yYXvcLsvoVaHJq/s5xXI6/XXP6tz7R9xAOtHnSO/tXtF3WRTlA==",
      "license": "MIT"
    },
    "node_modules/multer": {
      "version": "1.4.5-lts.2",
      "resolved": "https://registry.npmjs.org/multer/-/multer-1.4.5-lts.2.tgz",
      "integrity": "sha512-VzGiVigcG9zUAoCNU+xShztrlr1auZOlurXynNvO9GiWD1/mTBbUljOKY+qMeazBqXgRnjzeEgJI/wyjJUHg9A==",
      "license": "MIT",
      "dependencies": {
        "append-field": "^1.0.0",
        "busboy": "^1.0.0",
        "concat-stream": "^1.5.2",
        "mkdirp": "^0.5.4",
        "object-assign": "^4.1.1",
        "type-is": "^1.6.4",
        "xtend": "^4.0.0"
      },
      "engines": {
        "node": ">= 6.0.0"
      }
    },
    "node_modules/multer/node_modules/media-typer": {
      "version": "0.3.0",
      "resolved": "https://registry.npmjs.org/media-typer/-/media-typer-0.3.0.tgz",
      "integrity": "sha512-dq+qelQ9akHpcOl/gUVRTxVIOkAJ1wR3QAvb4RsVjS8oVoFjDGTc679wJYmUmknUF5HwMLOgb5O+a3KxfWapPQ==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/multer/node_modules/mime-db": {
      "version": "1.52.0",
      "resolved": "https://registry.npmjs.org/mime-db/-/mime-db-1.52.0.tgz",
      "integrity": "sha512-sPU4uV7dYlvtWJxwwxHD0PuihVNiE7TyAbQ5SWxDCB9mUYvOgroQOwYQQOKPJ8CIbE+1ETVlOoK1UC2nU3gYvg==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/multer/node_modules/mime-types": {
      "version": "2.1.35",
      "resolved": "https://registry.npmjs.org/mime-types/-/mime-types-2.1.35.tgz",
      "integrity": "sha512-ZDY+bPm5zTTF+YpCrAU9nK0UgICYPT0QtT1NZWFv4s++TNkcgVaT0g6+4R2uI4MjQjzysHB1zxuWL50hzaeXiw==",
      "license": "MIT",
      "dependencies": {
        "mime-db": "1.52.0"
      },
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/multer/node_modules/mkdirp": {
      "version": "0.5.6",
      "resolved": "https://registry.npmjs.org/mkdirp/-/mkdirp-0.5.6.tgz",
      "integrity": "sha512-FP+p8RB8OWpF3YZBCrP5gtADmtXApB5AMLn+vdyA+PyxCjrCs00mjyUozssO33cwDeT3wNGdLxJ5M//YqtHAJw==",
      "license": "MIT",
      "dependencies": {
        "minimist": "^1.2.6"
      },
      "bin": {
        "mkdirp": "bin/cmd.js"
      }
    },
    "node_modules/multer/node_modules/type-is": {
      "version": "1.6.18",
      "resolved": "https://registry.npmjs.org/type-is/-/type-is-1.6.18.tgz",
      "integrity": "sha512-TkRKr9sUTxEH8MdfuCSP7VizJyzRNMjj2J2do2Jr3Kym598JVdEksuzPQCnlFPW4ky9Q+iA+ma9BGm06XQBy8g==",
      "license": "MIT",
      "dependencies": {
        "media-typer": "0.3.0",
        "mime-types": "~2.1.24"
      },
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/negotiator": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/negotiator/-/negotiator-1.0.0.tgz",
      "integrity": "sha512-8Ofs/AUQh8MaEcrlq5xOX0CQ9ypTF5dl78mjlMNfOK08fzpgTHQRQPBxcPlEtIw0yRpws+Zo/3r+5WRby7u3Gg==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/node-addon-api": {
      "version": "5.1.0",
      "resolved": "https://registry.npmjs.org/node-addon-api/-/node-addon-api-5.1.0.tgz",
      "integrity": "sha512-eh0GgfEkpnoWDq+VY8OyvYhFEzBk6jIYbRKdIlyTiAXIVJ8PyBaKb0rp7oDtoddbdoHWhq8wwr+XZ81F1rpNdA==",
      "license": "MIT"
    },
    "node_modules/node-cron": {
      "version": "3.0.3",
      "resolved": "https://registry.npmjs.org/node-cron/-/node-cron-3.0.3.tgz",
      "integrity": "sha512-dOal67//nohNgYWb+nWmg5dkFdIwDm8EpeGYMekPMrngV3637lqnX0lbUcCtgibHTz6SEz7DAIjKvKDFYCnO1A==",
      "license": "ISC",
      "dependencies": {
        "uuid": "8.3.2"
      },
      "engines": {
        "node": ">=6.0.0"
      }
    },
    "node_modules/node-fetch": {
      "version": "2.7.0",
      "resolved": "https://registry.npmjs.org/node-fetch/-/node-fetch-2.7.0.tgz",
      "integrity": "sha512-c4FRfUm/dbcWZ7U+1Wq0AwCyFL+3nt2bEw05wfxSz+DWpWsitgmSgYmy2dQdWyKC1694ELPqMs/YzUSNozLt8A==",
      "license": "MIT",
      "dependencies": {
        "whatwg-url": "^5.0.0"
      },
      "engines": {
        "node": "4.x || >=6.0.0"
      },
      "peerDependencies": {
        "encoding": "^0.1.0"
      },
      "peerDependenciesMeta": {
        "encoding": {
          "optional": true
        }
      }
    },
    "node_modules/node-fetch/node_modules/tr46": {
      "version": "0.0.3",
      "resolved": "https://registry.npmjs.org/tr46/-/tr46-0.0.3.tgz",
      "integrity": "sha512-N3WMsuqV66lT30CrXNbEjx4GEwlow3v6rr4mCcv6prnfwhS01rkgyFdjPNBYd9br7LpXV1+Emh01fHnq2Gdgrw==",
      "license": "MIT"
    },
    "node_modules/node-fetch/node_modules/webidl-conversions": {
      "version": "3.0.1",
      "resolved": "https://registry.npmjs.org/webidl-conversions/-/webidl-conversions-3.0.1.tgz",
      "integrity": "sha512-2JAn3z8AR6rjK8Sm8orRC0h/bcl/DqL7tRPdGZ4I1CjdF+EaMLmYxBHyXuKL849eucPFhvBoxMsflfOb8kxaeQ==",
      "license": "BSD-2-Clause"
    },
    "node_modules/node-fetch/node_modules/whatwg-url": {
      "version": "5.0.0",
      "resolved": "https://registry.npmjs.org/whatwg-url/-/whatwg-url-5.0.0.tgz",
      "integrity": "sha512-saE57nupxk6v3HY35+jzBwYa0rKSy0XR8JSxZPwgLr7ys0IBzhGviA1/TUGJLmSVqs8pb9AnvICXEuOHLprYTw==",
      "license": "MIT",
      "dependencies": {
        "tr46": "~0.0.3",
        "webidl-conversions": "^3.0.0"
      }
    },
    "node_modules/nodemailer": {
      "version": "6.10.0",
      "resolved": "https://registry.npmjs.org/nodemailer/-/nodemailer-6.10.0.tgz",
      "integrity": "sha512-SQ3wZCExjeSatLE/HBaXS5vqUOQk6GtBdIIKxiFdmm01mOQZX/POJkO3SUX1wDiYcwUOJwT23scFSC9fY2H8IA==",
      "license": "MIT-0",
      "engines": {
        "node": ">=6.0.0"
      }
    },
    "node_modules/nopt": {
      "version": "5.0.0",
      "resolved": "https://registry.npmjs.org/nopt/-/nopt-5.0.0.tgz",
      "integrity": "sha512-Tbj67rffqceeLpcRXrT7vKAN8CwfPeIBgM7E6iBkmKLV7bEMwpGgYLGv0jACUsECaa/vuxP0IjEont6umdMgtQ==",
      "license": "ISC",
      "dependencies": {
        "abbrev": "1"
      },
      "bin": {
        "nopt": "bin/nopt.js"
      },
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/npmlog": {
      "version": "5.0.1",
      "resolved": "https://registry.npmjs.org/npmlog/-/npmlog-5.0.1.tgz",
      "integrity": "sha512-AqZtDUWOMKs1G/8lwylVjrdYgqA4d9nu8hc+0gzRxlDb1I10+FHBGMXs6aiQHFdCUUlqH99MUMuLfzWDNDtfxw==",
      "deprecated": "This package is no longer supported.",
      "license": "ISC",
      "dependencies": {
        "are-we-there-yet": "^2.0.0",
        "console-control-strings": "^1.1.0",
        "gauge": "^3.0.0",
        "set-blocking": "^2.0.0"
      }
    },
    "node_modules/object-assign": {
      "version": "4.1.1",
      "resolved": "https://registry.npmjs.org/object-assign/-/object-assign-4.1.1.tgz",
      "integrity": "sha512-rJgTQnkUnH1sFw8yT6VSU3zD3sWmu6sZhIseY8VX+GRu3P6F7Fu+JNDoXfklElbLJSnc3FUQHVe4cU5hj+BcUg==",
      "license": "MIT",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/object-inspect": {
      "version": "1.13.4",
      "resolved": "https://registry.npmjs.org/object-inspect/-/object-inspect-1.13.4.tgz",
      "integrity": "sha512-W67iLl4J2EXEGTbfeHCffrjDfitvLANg0UlX3wFUUSTx92KXRFegMHUVgSqE+wvhAbi4WqjGg9czysTV2Epbew==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/on-finished": {
      "version": "2.4.1",
      "resolved": "https://registry.npmjs.org/on-finished/-/on-finished-2.4.1.tgz",
      "integrity": "sha512-oVlzkg3ENAhCk2zdv7IJwd/QUD4z2RxRwpkcGY8psCVcCYZNq4wYnVWALHM+brtuJjePWiYF/ClmuDr8Ch5+kg==",
      "license": "MIT",
      "dependencies": {
        "ee-first": "1.1.1"
      },
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/on-headers": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/on-headers/-/on-headers-1.0.2.tgz",
      "integrity": "sha512-pZAE+FJLoyITytdqK0U5s+FIpjN0JP3OzFi/u8Rx+EV5/W+JTWGXG8xFzevE7AjBfDqHv/8vL8qQsIhHnqRkrA==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/once": {
      "version": "1.4.0",
      "resolved": "https://registry.npmjs.org/once/-/once-1.4.0.tgz",
      "integrity": "sha512-lNaJgI+2Q5URQBkccEKHTQOPaXdUxnZZElQTZY0MFUAuaEqe1E+Nyvgdz/aIyNi6Z9MzO5dv1H8n58/GELp3+w==",
      "license": "ISC",
      "dependencies": {
        "wrappy": "1"
      }
    },
    "node_modules/parseurl": {
      "version": "1.3.3",
      "resolved": "https://registry.npmjs.org/parseurl/-/parseurl-1.3.3.tgz",
      "integrity": "sha512-CiyeOxFT/JZyN5m0z9PfXw4SCBJ6Sygz1Dpl0wqjlhDEGGBP1GnsUVEL0p63hoG1fcj3fHynXi9NYO4nWOL+qQ==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/path-is-absolute": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/path-is-absolute/-/path-is-absolute-1.0.1.tgz",
      "integrity": "sha512-AVbw3UJ2e9bq64vSaS9Am0fje1Pa8pbGqTTsmXfaIiMpnr5DlDhfJOuLj9Sf95ZPVDAUerDfEk88MPmPe7UCQg==",
      "license": "MIT",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/path-to-regexp": {
      "version": "8.2.0",
      "resolved": "https://registry.npmjs.org/path-to-regexp/-/path-to-regexp-8.2.0.tgz",
      "integrity": "sha512-TdrF7fW9Rphjq4RjrW0Kp2AW0Ahwu9sRGTkS6bvDi0SCwZlEZYmcfDbEsTz8RVk0EHIS/Vd1bv3JhG+1xZuAyQ==",
      "license": "MIT",
      "engines": {
        "node": ">=16"
      }
    },
    "node_modules/process-nextick-args": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/process-nextick-args/-/process-nextick-args-2.0.1.tgz",
      "integrity": "sha512-3ouUOpQhtgrbOa17J7+uxOTpITYWaGP7/AhoR3+A+/1e9skrzelGi/dXzEYyvbxubEF6Wn2ypscTKiKJFFn1ag==",
      "license": "MIT"
    },
    "node_modules/proxy-addr": {
      "version": "2.0.7",
      "resolved": "https://registry.npmjs.org/proxy-addr/-/proxy-addr-2.0.7.tgz",
      "integrity": "sha512-llQsMLSUDUPT44jdrU/O37qlnifitDP+ZwrmmZcoSKyLKvtZxpyV0n2/bD/N4tBAAZ/gJEdZU7KMraoK1+XYAg==",
      "license": "MIT",
      "dependencies": {
        "forwarded": "0.2.0",
        "ipaddr.js": "1.9.1"
      },
      "engines": {
        "node": ">= 0.10"
      }
    },
    "node_modules/proxy-from-env": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/proxy-from-env/-/proxy-from-env-1.1.0.tgz",
      "integrity": "sha512-D+zkORCbA9f1tdWRK0RaCR3GPv50cMxcrz4X8k5LTSUD1Dkw47mKJEZQNunItRTkWwgtaUSo1RVFRIG9ZXiFYg==",
      "license": "MIT"
    },
    "node_modules/punycode": {
      "version": "2.3.1",
      "resolved": "https://registry.npmjs.org/punycode/-/punycode-2.3.1.tgz",
      "integrity": "sha512-vYt7UD1U9Wg6138shLtLOvdAu+8DsC/ilFtEVHcH+wydcSpNE20AfSOduf6MkRFahL5FY7X1oU7nKVZFtfq8Fg==",
      "license": "MIT",
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/qs": {
      "version": "6.14.0",
      "resolved": "https://registry.npmjs.org/qs/-/qs-6.14.0.tgz",
      "integrity": "sha512-YWWTjgABSKcvs/nWBi9PycY/JiPJqOD4JA6o9Sej2AtvSGarXxKC3OQSk4pAarbdQlKAh5D4FCQkJNkW+GAn3w==",
      "license": "BSD-3-Clause",
      "dependencies": {
        "side-channel": "^1.1.0"
      },
      "engines": {
        "node": ">=0.6"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/range-parser": {
      "version": "1.2.1",
      "resolved": "https://registry.npmjs.org/range-parser/-/range-parser-1.2.1.tgz",
      "integrity": "sha512-Hrgsx+orqoygnmhFbKaHE6c296J+HTAQXoxEF6gNupROmmGJRoyzfG3ccAveqCBrwr/2yxQ5BVd/GTl5agOwSg==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/raw-body": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/raw-body/-/raw-body-3.0.0.tgz",
      "integrity": "sha512-RmkhL8CAyCRPXCE28MMH0z2PNWQBNk2Q09ZdxM9IOOXwxwZbN+qbWaatPkdkWIKL2ZVDImrN/pK5HTRz2PcS4g==",
      "license": "MIT",
      "dependencies": {
        "bytes": "3.1.2",
        "http-errors": "2.0.0",
        "iconv-lite": "0.6.3",
        "unpipe": "1.0.0"
      },
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/readable-stream": {
      "version": "3.6.2",
      "resolved": "https://registry.npmjs.org/readable-stream/-/readable-stream-3.6.2.tgz",
      "integrity": "sha512-9u/sniCrY3D5WdsERHzHE4G2YCXqoG5FTHUiCC4SIbr6XcLZBY05ya9EKjYek9O5xOAwjGq+1JdGBAS7Q9ScoA==",
      "license": "MIT",
      "dependencies": {
        "inherits": "^2.0.3",
        "string_decoder": "^1.1.1",
        "util-deprecate": "^1.0.1"
      },
      "engines": {
        "node": ">= 6"
      }
    },
    "node_modules/rimraf": {
      "version": "3.0.2",
      "resolved": "https://registry.npmjs.org/rimraf/-/rimraf-3.0.2.tgz",
      "integrity": "sha512-JZkJMZkAGFFPP2YqXZXPbMlMBgsxzE8ILs4lMIX/2o0L9UBw9O/Y3o6wFw/i9YLapcUJWwqbi3kdxIPdC62TIA==",
      "deprecated": "Rimraf versions prior to v4 are no longer supported",
      "license": "ISC",
      "dependencies": {
        "glob": "^7.1.3"
      },
      "bin": {
        "rimraf": "bin.js"
      },
      "funding": {
        "url": "https://github.com/sponsors/isaacs"
      }
    },
    "node_modules/router": {
      "version": "2.2.0",
      "resolved": "https://registry.npmjs.org/router/-/router-2.2.0.tgz",
      "integrity": "sha512-nLTrUKm2UyiL7rlhapu/Zl45FwNgkZGaCpZbIHajDYgwlJCOzLSk+cIPAnsEqV955GjILJnKbdQC1nVPz+gAYQ==",
      "license": "MIT",
      "dependencies": {
        "debug": "^4.4.0",
        "depd": "^2.0.0",
        "is-promise": "^4.0.0",
        "parseurl": "^1.3.3",
        "path-to-regexp": "^8.0.0"
      },
      "engines": {
        "node": ">= 18"
      }
    },
    "node_modules/safe-buffer": {
      "version": "5.2.1",
      "resolved": "https://registry.npmjs.org/safe-buffer/-/safe-buffer-5.2.1.tgz",
      "integrity": "sha512-rp3So07KcdmmKbGvgaNxQSJr7bGVSVk5S9Eq1F+ppbRo70+YeaDxkw5Dd8NPN+GD6bjnYm2VuPuCXmpuYvmCXQ==",
      "funding": [
        {
          "type": "github",
          "url": "https://github.com/sponsors/feross"
        },
        {
          "type": "patreon",
          "url": "https://www.patreon.com/feross"
        },
        {
          "type": "consulting",
          "url": "https://feross.org/support"
        }
      ],
      "license": "MIT"
    },
    "node_modules/safer-buffer": {
      "version": "2.1.2",
      "resolved": "https://registry.npmjs.org/safer-buffer/-/safer-buffer-2.1.2.tgz",
      "integrity": "sha512-YZo3K82SD7Riyi0E1EQPojLz7kpepnSQI9IyPbHHg1XXXevb5dJI7tpyN2ADxGcQbHG7vcyRHk0cbwqcQriUtg==",
      "license": "MIT"
    },
    "node_modules/semver": {
      "version": "7.7.1",
      "resolved": "https://registry.npmjs.org/semver/-/semver-7.7.1.tgz",
      "integrity": "sha512-hlq8tAfn0m/61p4BVRcPzIGr6LKiMwo4VM6dGi6pt4qcRkmNzTcWq6eCEjEh+qXjkMDvPlOFFSGwQjoEa6gyMA==",
      "license": "ISC",
      "bin": {
        "semver": "bin/semver.js"
      },
      "engines": {
        "node": ">=10"
      }
    },
    "node_modules/send": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/send/-/send-1.2.0.tgz",
      "integrity": "sha512-uaW0WwXKpL9blXE2o0bRhoL2EGXIrZxQ2ZQ4mgcfoBxdFmQold+qWsD2jLrfZ0trjKL6vOw0j//eAwcALFjKSw==",
      "license": "MIT",
      "dependencies": {
        "debug": "^4.3.5",
        "encodeurl": "^2.0.0",
        "escape-html": "^1.0.3",
        "etag": "^1.8.1",
        "fresh": "^2.0.0",
        "http-errors": "^2.0.0",
        "mime-types": "^3.0.1",
        "ms": "^2.1.3",
        "on-finished": "^2.4.1",
        "range-parser": "^1.2.1",
        "statuses": "^2.0.1"
      },
      "engines": {
        "node": ">= 18"
      }
    },
    "node_modules/serve-static": {
      "version": "2.2.0",
      "resolved": "https://registry.npmjs.org/serve-static/-/serve-static-2.2.0.tgz",
      "integrity": "sha512-61g9pCh0Vnh7IutZjtLGGpTA355+OPn2TyDv/6ivP2h/AdAVX9azsoxmg2/M6nZeQZNYBEwIcsne1mJd9oQItQ==",
      "license": "MIT",
      "dependencies": {
        "encodeurl": "^2.0.0",
        "escape-html": "^1.0.3",
        "parseurl": "^1.3.3",
        "send": "^1.2.0"
      },
      "engines": {
        "node": ">= 18"
      }
    },
    "node_modules/set-blocking": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/set-blocking/-/set-blocking-2.0.0.tgz",
      "integrity": "sha512-KiKBS8AnWGEyLzofFfmvKwpdPzqiy16LvQfK3yv/fVH7Bj13/wl3JSR1J+rfgRE9q7xUJK4qvgS8raSOeLUehw==",
      "license": "ISC"
    },
    "node_modules/setprototypeof": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/setprototypeof/-/setprototypeof-1.2.0.tgz",
      "integrity": "sha512-E5LDX7Wrp85Kil5bhZv46j8jOeboKq5JMmYM3gVGdGH8xFpPWXUMsNrlODCrkoxMEeNi/XZIwuRvY4XNwYMJpw==",
      "license": "ISC"
    },
    "node_modules/side-channel": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/side-channel/-/side-channel-1.1.0.tgz",
      "integrity": "sha512-ZX99e6tRweoUXqR+VBrslhda51Nh5MTQwou5tnUDgbtyM0dBgmhEDtWGP/xbKn6hqfPRHujUNwz5fy/wbbhnpw==",
      "license": "MIT",
      "dependencies": {
        "es-errors": "^1.3.0",
        "object-inspect": "^1.13.3",
        "side-channel-list": "^1.0.0",
        "side-channel-map": "^1.0.1",
        "side-channel-weakmap": "^1.0.2"
      },
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/side-channel-list": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/side-channel-list/-/side-channel-list-1.0.0.tgz",
      "integrity": "sha512-FCLHtRD/gnpCiCHEiJLOwdmFP+wzCmDEkc9y7NsYxeF4u7Btsn1ZuwgwJGxImImHicJArLP4R0yX4c2KCrMrTA==",
      "license": "MIT",
      "dependencies": {
        "es-errors": "^1.3.0",
        "object-inspect": "^1.13.3"
      },
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/side-channel-map": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/side-channel-map/-/side-channel-map-1.0.1.tgz",
      "integrity": "sha512-VCjCNfgMsby3tTdo02nbjtM/ewra6jPHmpThenkTYh8pG9ucZ/1P8So4u4FGBek/BjpOVsDCMoLA/iuBKIFXRA==",
      "license": "MIT",
      "dependencies": {
        "call-bound": "^1.0.2",
        "es-errors": "^1.3.0",
        "get-intrinsic": "^1.2.5",
        "object-inspect": "^1.13.3"
      },
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/side-channel-weakmap": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/side-channel-weakmap/-/side-channel-weakmap-1.0.2.tgz",
      "integrity": "sha512-WPS/HvHQTYnHisLo9McqBHOJk2FkHO/tlpvldyrnem4aeQp4hai3gythswg6p01oSoTl58rcpiFAjF2br2Ak2A==",
      "license": "MIT",
      "dependencies": {
        "call-bound": "^1.0.2",
        "es-errors": "^1.3.0",
        "get-intrinsic": "^1.2.5",
        "object-inspect": "^1.13.3",
        "side-channel-map": "^1.0.1"
      },
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/sift": {
      "version": "17.1.3",
      "resolved": "https://registry.npmjs.org/sift/-/sift-17.1.3.tgz",
      "integrity": "sha512-Rtlj66/b0ICeFzYTuNvX/EF1igRbbnGSvEyT79McoZa/DeGhMyC5pWKOEsZKnpkqtSeovd5FL/bjHWC3CIIvCQ==",
      "license": "MIT"
    },
    "node_modules/signal-exit": {
      "version": "3.0.7",
      "resolved": "https://registry.npmjs.org/signal-exit/-/signal-exit-3.0.7.tgz",
      "integrity": "sha512-wnD2ZE+l+SPC/uoS0vXeE9L1+0wuaMqKlfz9AMUo38JsyLSBWSFcHR1Rri62LZc12vLr1gb3jl7iwQhgwpAbGQ==",
      "license": "ISC"
    },
    "node_modules/sparse-bitfield": {
      "version": "3.0.3",
      "resolved": "https://registry.npmjs.org/sparse-bitfield/-/sparse-bitfield-3.0.3.tgz",
      "integrity": "sha512-kvzhi7vqKTfkh0PZU+2D2PIllw2ymqJKujUcyPMd9Y75Nv4nPbGJZXNhxsgdQab2BmlDct1YnfQCguEvHr7VsQ==",
      "license": "MIT",
      "dependencies": {
        "memory-pager": "^1.0.2"
      }
    },
    "node_modules/statuses": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/statuses/-/statuses-2.0.1.tgz",
      "integrity": "sha512-RwNA9Z/7PrK06rYLIzFMlaF+l73iwpzsqRIFgbMLbTcLD6cOao82TaWefPXQvB2fOC4AjuYSEndS7N/mTCbkdQ==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/streamsearch": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/streamsearch/-/streamsearch-1.1.0.tgz",
      "integrity": "sha512-Mcc5wHehp9aXz1ax6bZUyY5afg9u2rv5cqQI3mRrYkGC8rW2hM02jWuwjtL++LS5qinSyhj2QfLyNsuc+VsExg==",
      "engines": {
        "node": ">=10.0.0"
      }
    },
    "node_modules/string_decoder": {
      "version": "1.3.0",
      "resolved": "https://registry.npmjs.org/string_decoder/-/string_decoder-1.3.0.tgz",
      "integrity": "sha512-hkRX8U1WjJFd8LsDJ2yQ/wWWxaopEsABU1XfkM8A+j0+85JAGppt16cr1Whg6KIbb4okU6Mql6BOj+uup/wKeA==",
      "license": "MIT",
      "dependencies": {
        "safe-buffer": "~5.2.0"
      }
    },
    "node_modules/string-width": {
      "version": "4.2.3",
      "resolved": "https://registry.npmjs.org/string-width/-/string-width-4.2.3.tgz",
      "integrity": "sha512-wKyQRQpjJ0sIp62ErSZdGsjMJWsap5oRNihHhu6G7JVO/9jIB6UyevL+tXuOqrng8j/cxKTWyWUwvSTriiZz/g==",
      "license": "MIT",
      "dependencies": {
        "emoji-regex": "^8.0.0",
        "is-fullwidth-code-point": "^3.0.0",
        "strip-ansi": "^6.0.1"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/strip-ansi": {
      "version": "6.0.1",
      "resolved": "https://registry.npmjs.org/strip-ansi/-/strip-ansi-6.0.1.tgz",
      "integrity": "sha512-Y38VPSHcqkFrCpFnQ9vuSXmquuv5oXOKpGeT6aGrr3o3Gc9AlVa6JBfUSOCnbxGGZF+/0ooI7KrPuUSztUdU5A==",
      "license": "MIT",
      "dependencies": {
        "ansi-regex": "^5.0.1"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/tar": {
      "version": "6.2.1",
      "resolved": "https://registry.npmjs.org/tar/-/tar-6.2.1.tgz",
      "integrity": "sha512-DZ4yORTwrbTj/7MZYq2w+/ZFdI6OZ/f9SFHR+71gIVUZhOQPHzVCLpvRnPgyaMpfWxxk/4ONva3GQSyNIKRv6A==",
      "license": "ISC",
      "dependencies": {
        "chownr": "^2.0.0",
        "fs-minipass": "^2.0.0",
        "minipass": "^5.0.0",
        "minizlib": "^2.1.1",
        "mkdirp": "^1.0.3",
        "yallist": "^4.0.0"
      },
      "engines": {
        "node": ">=10"
      }
    },
    "node_modules/toidentifier": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/toidentifier/-/toidentifier-1.0.1.tgz",
      "integrity": "sha512-o5sSPKEkg/DIQNmH43V0/uerLrpzVedkUh8tGNvaeXpfpuwjKenlSox/2O/BTlZUtEe+JG7s5YhEz608PlAHRA==",
      "license": "MIT",
      "engines": {
        "node": ">=0.6"
      }
    },
    "node_modules/tr46": {
      "version": "5.1.0",
      "resolved": "https://registry.npmjs.org/tr46/-/tr46-5.1.0.tgz",
      "integrity": "sha512-IUWnUK7ADYR5Sl1fZlO1INDUhVhatWl7BtJWsIhwJ0UAK7ilzzIa8uIqOO/aYVWHZPJkKbEL+362wrzoeRF7bw==",
      "license": "MIT",
      "dependencies": {
        "punycode": "^2.3.1"
      },
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/tslib": {
      "version": "2.8.1",
      "resolved": "https://registry.npmjs.org/tslib/-/tslib-2.8.1.tgz",
      "integrity": "sha512-oJFu94HQb+KVduSUQL7wnpmqnfmLsOA/nAh6b6EH0wCEoK0/mPeXU6c3wKDV83MkOuHPRHtSXKKU99IBazS/2w==",
      "license": "0BSD"
    },
    "node_modules/type-is": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/type-is/-/type-is-2.0.1.tgz",
      "integrity": "sha512-OZs6gsjF4vMp32qrCbiVSkrFmXtG/AZhY3t0iAMrMBiAZyV9oALtXO8hsrHbMXF9x6L3grlFuwW2oAz7cav+Gw==",
      "license": "MIT",
      "dependencies": {
        "content-type": "^1.0.5",
        "media-typer": "^1.1.0",
        "mime-types": "^3.0.0"
      },
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/typedarray": {
      "version": "0.0.6",
      "resolved": "https://registry.npmjs.org/typedarray/-/typedarray-0.0.6.tgz",
      "integrity": "sha512-/aCDEGatGvZ2BIk+HmLf4ifCJFwvKFNb9/JeZPMulfgFracn9QFcAf5GO8B/mweUjSoblS5In0cWhqpfs/5PQA==",
      "license": "MIT"
    },
    "node_modules/unpipe": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/unpipe/-/unpipe-1.0.0.tgz",
      "integrity": "sha512-pjy2bYhSsufwWlKwPc+l3cN7+wuJlK6uz0YdJEOlQDbl6jo/YlPi4mb8agUkVC8BF7V8NuzeyPNqRksA3hztKQ==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/util-deprecate": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/util-deprecate/-/util-deprecate-1.0.2.tgz",
      "integrity": "sha512-EPD5q1uXyFxJpCrLnCc1nHnq3gOa6DZBocAIiI2TaSCA7VCJ1UJDMagCzIkXNsUYfD1daK//LTEQ8xiIbrHtcw==",
      "license": "MIT"
    },
    "node_modules/uuid": {
      "version": "8.3.2",
      "resolved": "https://registry.npmjs.org/uuid/-/uuid-8.3.2.tgz",
      "integrity": "sha512-+NYs2QeMWy+GWFOEm9xnn6HCDp0l7QBD7ml8zLUmJ+93Q5NF0NocErnwkTkXVFNiX3/fpC6afS8Dhb/gz7R7eg==",
      "license": "MIT",
      "bin": {
        "uuid": "dist/bin/uuid"
      }
    },
    "node_modules/vary": {
      "version": "1.1.2",
      "resolved": "https://registry.npmjs.org/vary/-/vary-1.1.2.tgz",
      "integrity": "sha512-BNGbWLfd0eUPabhkXUVm0j8uuvREyTh5ovRa/dyow/BqAbZJyC+5fU+IzQOzmAKzYqYRAISoRhdQr3eIZ/PXqg==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/webidl-conversions": {
      "version": "7.0.0",
      "resolved": "https://registry.npmjs.org/webidl-conversions/-/webidl-conversions-7.0.0.tgz",
      "integrity": "sha512-VwddBukDzu71offAQR975unBIGqfKZpM+8ZX6ySk8nYhVoo5CYaZyzt3YBvYtRtO+aoGlqxPg/B87NGVZ/fu6g==",
      "license": "BSD-2-Clause",
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/whatwg-url": {
      "version": "14.2.0",
      "resolved": "https://registry.npmjs.org/whatwg-url/-/whatwg-url-14.2.0.tgz",
      "integrity": "sha512-De72GdQZzNTUBBChsXueQUnPKDkg/5A5zp7pFDuQAj5UFoENpiACU0wlCvzpAGnTkj++ihpKwKyYewn/XNUbKw==",
      "license": "MIT",
      "dependencies": {
        "tr46": "^5.1.0",
        "webidl-conversions": "^7.0.0"
      },
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/wide-align": {
      "version": "1.1.5",
      "resolved": "https://registry.npmjs.org/wide-align/-/wide-align-1.1.5.tgz",
      "integrity": "sha512-eDMORYaPNZ4sQIuuYPDHdQvf4gyCF9rEEV/yPxGfwPkRodwEgiMUUXTx/dex+Me0wxx53S+NgUHaP7y3MGlDmg==",
      "license": "ISC",
      "dependencies": {
        "string-width": "^1.0.2 || 2 || 3 || 4"
      }
    },
    "node_modules/wrappy": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/wrappy/-/wrappy-1.0.2.tgz",
      "integrity": "sha512-l4Sp/DRseor9wL6EvV2+TuQn63dMkPjZ/sp9XkghTEbV9KlPS1xUsZ3u7/IQO4wxtcFB4bgpQPRcR3QCvezPcQ==",
      "license": "ISC"
    },
    "node_modules/xtend": {
      "version": "4.0.2",
      "resolved": "https://registry.npmjs.org/xtend/-/xtend-4.0.2.tgz",
      "integrity": "sha512-LKYU1iAXJXUgAXn9URjiu+MWhyUXHsvfp7mcuYm9dSUKK0/CjtrUwFAxD82/mCWbtLsGjFIad0wIsod4zrTAEQ==",
      "license": "MIT",
      "engines": {
        "node": ">=0.4"
      }
    },
    "node_modules/yallist": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/yallist/-/yallist-4.0.0.tgz",
      "integrity": "sha512-3wdGidZyq5PB084XLES5TpOSRA3wjXAlIWMhum2kRcv/41Sn2emQ0dycQW4uZXLejwKvg6EsvbdlVL+FYEct7A==",
      "license": "ISC"
    }
  }
}

```

### `backend\package.json`

```json
{
  "name": "backend",
  "version": "1.0.0",
  "description": "",
  "main": "server.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "node server.js"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "type": "commonjs",
  "dependencies": {
    "@faker-js/faker": "^9.6.0",
    "@imagekit/javascript": "^5.0.0",
    "axios": "^1.8.4",
    "bcrypt": "^5.1.1",
    "cors": "^2.8.5",
    "dotenv": "^16.4.7",
    "express": "^5.1.0",
    "imagekit": "^6.0.0",
    "jsonwebtoken": "^9.0.2",
    "mongoose": "^8.13.2",
    "morgan": "^1.10.0",
    "multer": "^1.4.5-lts.2",
    "node-cron": "^3.0.3",
    "nodemailer": "^6.10.0"
  }
}

```

### `backend\server.js`

```javascript
const env = require('dotenv').config()
const app = require('./src/app.js');
const config = require('./src/config/config');
require("./src/utils/fetchPrivacyNews.js");


app.listen(config.PORT, () => {
    console.log(`Server is running on port ${config.PORT}`);
})



const connectDB = require('./src/db/db.js')
connectDB()
```

### `backend\src\app.js`

```javascript
const express = require('express');
const morgan = require('morgan');
const cors = require('cors');
const app = express();
const authRoutes = require('./routes/auth.routes');
const OTPRoutes = require('./routes/otp.routes');
const userRoutes = require('./routes/user.routes');
const vaultRoutes = require('./routes/vault.routes');
const fakeDataRoutes = require("./routes/fakeData.routes");
const sharedDataRoutes = require("./routes/sharedData.routes");
const blogRoutes = require("./routes/blog.routes");


// Middleware
app.use(morgan('dev'));
app.use(express.json());
app.use(express.urlencoded({ extended: true }));
app.use(cors({
    origin: "http://localhost:5173",
}));


// Routes
app.get('/', (req, res) => {
    res.send('Welcome to the API!');
});

app.get('/health', (req, res) => {
    res.json({ status: 'OK' });
});

app.use('/api/auth', authRoutes);
app.use('/api/otp', OTPRoutes);
app.use('/api/user', userRoutes);
app.use('/api/vault', vaultRoutes);
app.use("/api/fake-data", fakeDataRoutes);
app.use("/api/sharedApps", sharedDataRoutes);
app.use("/api/blogs", blogRoutes);



// 404 Handler
app.use((req, res, next) => {
    res.status(404).json({ error: 'Not Found' });
});



// Export the app
module.exports = app;
```

### `backend\src\config\config.js`

```javascript
const _config = {
    PORT: process.env.PORT || 3000,
    MONGODB_URI: process.env.MONGODB_URI,
    JWT_SECRET: process.env.JWT_SECRET,
    EMAIL_USER: process.env.EMAIL_USER,
    EMAIL_PASS: process.env.EMAIL_PASS,
    VAULT_SECRET_KEY: process.env.VAULT_SECRET_KEY,
    NEWS_API_KEY: process.env.NEWS_API_KEY,
    IMAGEKIT_PUBLIC_KEY: process.env.IMAGEKIT_PUBLIC_KEY,
    IMAGEKIT_PRIVATE_KEY: process.env.IMAGEKIT_PRIVATE_KEY,
    IMAGEKIT_URL_ENDPOINT: process.env.IMAGEKIT_URL_ENDPOINT,
}

const config = Object.freeze(_config)

module.exports = config
```

### `backend\src\controllers\auth.controller.js`

```javascript
const userModel = require("../models/user.model")
const { createUser } = require("../services/auth.service")
const { sendEmail } = require("../services/email.service")
const generateVerificationCode = require("../utils/generateVerificationCode")

module.exports.registerController = async (req, res) => {
    try {
        const { firstName, lastName, email, password, phoneNumber } = req.body

        // Validate input
        if (!firstName || !lastName || !email || !password || !phoneNumber) {
            return res.status(400).json({
                errors: ['All fields are required'],
            })
        }


        //create user Service
        const OTP = generateVerificationCode()
        const newUser = await createUser({ firstName, lastName, email, password, phoneNumber, OTP })

        //send OTP by email
        const username = firstName.trim() + ` ${lastName.trim()}`
        const emailContent = `
        <html>
          <body style="font-family: Arial, sans-serif; color: #333;">
            <div style="background-color: #f0f0f0; padding: 20px; border-radius: 10px; max-width: 600px; margin: 0 auto;">
              <h2 style="color: #088395;">Welcome to Our Platform, ${username}!</h2>
              <h2 style="color: #088395;">Your OTP</h2>
              <p style="font-size: 18px; font-weight: bold;">Your OTP is: <span style="color: #37B7C3;">${OTP}</span></p>
              <p>Thank you for signing up with us. We’re excited to have you onboard!</p>
              <p>Here’s what you can do next:</p>
              <ul>
            <li>Explore our platform</li>
            <li>Set up your profile</li>
            <li>Start collaborating with others</li>
              </ul>
              <p style="color: #37B7C3;">Happy exploring!</p>
              <p>Best regards,<br/> The Team</p>
            </div>
          </body>
        </html>
          `;
       await sendEmail(email, 'Verify your account', emailContent)



        // Generate token
        const token = userModel.generateToken(newUser)


        // Send response
        res.status(201).json({
            message: 'User registered successfully',
            user: newUser,
            token,
        })


    } catch (error) {
        console.log(error.message)
        res.status(400).json({
            errors: [error.message],
        })
    }
}

module.exports.authMe = async (req, res) => {
  try {
      const user = req.user; // Assuming user is set in the request by authentication middleware

      if (!user) {
          return res.status(404).json({ errors: ["User not found"] });
      }

      // Exclude sensitive information
      user.password = undefined;
      user.verificationToken = undefined;
      user.verificationTokenExpiresAt = undefined;

      res.status(200).json({
          message: "User fetched successfully",
          user,
      });


  } catch (error) {
      
      console.error(error);
      res.status(500).json({ errors: ["Internal server error"] });
  }


}

module.exports.loginController = async (req, res) => {
    try {
        const { email, password } = req.body
        // Validate input
        if (!email || !password) {
            return res.status(400).json({
                errors: ['All fields are required'],
            })
        }

        // Find user by email
        const user = await userModel.findOne({ email })
        if (!user) {
            return res.status(404).json({
                errors: ['User not found'],
            })
        }

        // Check password
        if (!user.comparePassword(password)) {
            return res.status(401).json({
                errors: ['Invalid password'],
            })
        }
        // Generate token
        const token = userModel.generateToken(user)

        // Send response
        res.status(200).json({
            message: 'User logged in successfully',
            user,
            token,
        })

    } catch (error) {
        console.log(error.message)
        res.status(400).json({
            errors: [error.message],
        })
    }
}
```

### `backend\src\controllers\blog.controller.js`

```javascript
const blogModel = require("../models/blog.model");

module.exports.createBlog = async (req, res) => {
    try {
        const blog = new blogModel(req.body);
        await blog.save();
        res.status(201).json({ message: "Blog post added" });
    } catch (err) {
        res.status(500).json({ error: "Error saving blog" });
    }
}


module.exports.getAllBlogs = async (req, res) => {
    const blogs = await blogModel.find().sort({ datePublished: -1 });
    res.json(blogs);
}
```

### `backend\src\controllers\fakeData.controller.js`

```javascript
const fakeDataModel = require("../models/fakeData.model");
const userModel = require("../models/user.model");
const { faker } = require("@faker-js/faker");

exports.generateFakeData = async (req, res) => {
    try {
        const userId = req.user._id;
        console.log(req.headers)
        // Fetch the user to check savedFakeData array
        const user = await userModel.findById(userId);

        if (!user) {
            return res.status(404).json({ errors: ["User not found"] });
        }

        // Check if the user already has 8 fake data entries
        if (user.savedFakeData.length >= 8) {
            return res.status(400).json({ errors: ["Maximum limit of 8 fake data entries reached. Please delete one to create a new one."] });
        }

        // Create new fake data
        const fakeDataInstance = new fakeDataModel({
            userId,
            name: faker.person.fullName(),
            phone: faker.phone.number(),
            address: faker.location.streetAddress(),
            city: faker.location.city(),
            state: faker.location.state(),
            aadhar: faker.string.numeric(12),
        });


        await fakeDataInstance.save();

        // Push the new fake data ID into the user's savedFakeData array
        user.savedFakeData.push(fakeDataInstance._id);
        await user.save();

        res.status(201).json({ message: "Fake data generated", data: fakeDataInstance });
    } catch (error) {
        console.error("Generate Fake Data Error:", error);
        res.status(500).json({ errors: ["Failed to generate fake data"] });
    }
};

exports.getFakeData = async (req, res) => {
    try {
        const userId = req.user._id;
        const data = await fakeDataModel.find({ userId }).sort({ createdAt: -1 });

        res.status(200).json({ fakedata: data });
    } catch (error) {
        console.error("Fetch Fake Data Error:", error);
        res.status(500).json({ error: "Failed to fetch fake data" });
    }
};


exports.deleteFakeData = async (req, res) => {
    try {
        const userId = req.user._id;
        const fakeDataId = req.body.fakeDataId;

        // Find the fake data entry to delete
        const fakeDataEntry = await fakeDataModel.findOneAndDelete({ _id: fakeDataId, userId });

        if (!fakeDataEntry) {
            return res.status(404).json({ errors: ["Fake data not found"] });
        }

        // Remove the deleted fake data ID from the user's savedFakeData array
        await userModel.findByIdAndUpdate(userId, { $pull: { savedFakeData: fakeDataId } });

        res.status(200).json({ message: "Fake data deleted successfully" });

    } catch (error) {
        console.error("Delete Fake Data Error:", error);
        res.status(500).json({ errors: ["Failed to delete fake data"] });
    }
} 
```

### `backend\src\controllers\otp.controller.js`

```javascript
const userModel = require("../models/user.model");
const { sendEmail } = require("../services/email.service");
const generateVerificationCode = require("../utils/generateVerificationCode");

module.exports.verifyOTPController = async (req, res) => {
    try {

        const { email, otp } = req.body;

        // Find user by email
        const user = await userModel.findOne({ email });

        if (!user) {
            return res.status(400).json({ errors: ["User not found"] });
        }

        // Check if OTP matches and is not expired
        if (user.verificationToken !== otp || user.verificationTokenExpiresAt < Date.now()) {
            return res.status(400).json({ errors: ["Invalid or expired OTP"] });
        }

        // Update user as verified
        user.isVerified = true;
        user.verificationToken = undefined;
        user.verificationTokenExpiresAt = undefined;
        await user.save();

        // Generate Token
        const token = userModel.generateToken(user);

        user.password = undefined

        res.status(200).json({
            message: "OTP Verified. User logged in.",
            token,
            user
        });

    } catch (error) {
        res.status(500).json({ errors: [error.message] });
    }
};


module.exports.resendOTPController = async (req, res) => {
    try {
        const { email } = req.body;

        const user = await userModel.findOne({ email });

        if (!user) {
            return res.status(400).json({ errors: ["User not found"] });
        }
        
        
        // Generate new OTP
        const OTP = generateVerificationCode()
        user.isVerified = false; // Reset verification status
        user.verificationToken = OTP;
        user.verificationTokenExpiresAt = Date.now() + 2 * 60 * 1000; // 2 min expiration time
        await user.save();


        // Send OTP to user's email
        const emailContent = `
                <html>
                  <body style="font-family: Arial, sans-serif; color: #333;">
                    <div style="background-color: #f0f0f0; padding: 20px; border-radius: 10px; max-width: 600px; margin: 0 auto;">
                      <h2 style="color: #088395;">Welcome to Our Platform, ${user.userName}!</h2>
                      <h2 style="color: #088395;">Your OTP</h2>
                      <p style="font-size: 18px; font-weight: bold;">Your OTP is: <span style="color: #37B7C3;">${OTP}</span></p>
                      <p>Thank you for signing up with us. We’re excited to have you onboard!</p>
                      <p>Here’s what you can do next:</p>
                      <ul>
                    <li>Explore our platform</li>
                    <li>Set up your profile</li>
                    <li>Start collaborating with others</li>
                      </ul>
                      <p style="color: #37B7C3;">Happy exploring!</p>
                      <p>Best regards,<br/> The Team</p>
                    </div>
                  </body>
                </html>
                  `;
        await sendEmail(email, 'Verify your account', emailContent)


        res.status(200).json({
            message: "OTP resent successfully"
        });

    } catch (error) {
        res.status(500).json({ errors: [error.message] });
    }
}
```

### `backend\src\controllers\sharedApp.controller.js`

```javascript
const SharedApp = require("../models/SharedApp.model");
const userModel = require("../models/user.model");

// Get all shared apps for the logged-in user
const getSharedApps = async (req, res) => {
  try {
    const userId = req.user.id;

    // Find all apps created by the user
    const sharedApps = await SharedApp.find({ userId });

    res.json(sharedApps);
  } catch (err) {
    console.error(err);
    res.status(500).json({ error: "Server error" });
  }
};

// Add a new shared app
const addSharedApp = async (req, res) => {
  try {
    const userId = req.user.id;
    const { appName, sharedData, accessDate, lastAccessed } = req.body;

    // Validate sharedData to only contain booleans
    const validatedSharedData = {
      email: !!sharedData.email,
      password: !!sharedData.password,
      phoneNumber: !!sharedData.phoneNumber,
      location: !!sharedData.location,
      aadhaarNumber: !!sharedData.aadhaarNumber,
    };

    const newApp = new SharedApp({
      userId,
      appName,
      sharedData: validatedSharedData,
      accessDate,
      lastAccessed,
    });

    await newApp.save();

    // Add app reference to user's sharedData array
    await userModel.findByIdAndUpdate(userId, {
      $push: { sharedData: newApp._id },
    });

    res.status(201).json(newApp);
  } catch (err) {
    console.error(err);
    res.status(500).json({ error: "Server error" });
  }
};

// Update a shared app
const updateSharedApp = async (req, res) => {
  try {
    const appId = req.params.id;
    const { appName, sharedData } = req.body;

    const updatedSharedData = {
      email: !!sharedData.email,
      password: !!sharedData.password,
      phoneNumber: !!sharedData.phoneNumber,
      location: !!sharedData.location,
      aadhaarNumber: !!sharedData.aadhaarNumber,
    };

    const updatedApp = await SharedApp.findByIdAndUpdate(
      appId,
      {
        appName,
        sharedData: updatedSharedData,
        lastAccessed: new Date(),
      },
      { new: true }
    );

    if (!updatedApp) {
      return res.status(404).json({ message: "Shared app not found" });
    }

    res.json(updatedApp);
  } catch (err) {
    console.error(err);
    res.status(500).json({ error: "Server error" });
  }
};

// Delete a shared app
const deleteSharedApp = async (req, res) => {
  try {
    const userId = req.user.id;
    const appId = req.params.id;

    const deletedApp = await SharedApp.findByIdAndDelete(appId);

    if (!deletedApp) {
      return res.status(404).json({ message: "Shared app not found" });
    }

    await userModel.findByIdAndUpdate(userId, {
      $pull: { sharedData: appId },
    });

    res.json({ message: "App deleted successfully" });
  } catch (err) {
    console.error(err);
    res.status(500).json({ error: "Server error" });
  }
};

module.exports = {
  getSharedApps,
  addSharedApp,
  updateSharedApp,
  deleteSharedApp,
};

```

### `backend\src\controllers\user.controller.js`

```javascript
const { uploadBufferStream  , deleteImage  } = require("../utils/imageKit");
const userModel = require("../models/user.model");




module.exports.getUserById = async (req, res) => {
    
    try {
        const userId = req.params.id;
        const user = await userModel.findById(userId)
            .select("-password -vaultPassword -__v")
            .populate("savedFakeData")
            .populate("sharedData")
            
            

        if (!user) {
            return res.status(404).json({ errors: ["User not found"] });
        }

        return res.status(200).json({ user });


    } catch (error) {
        console.log(error)
        return res.status(500).json({ errors: [error.message] });
    }
}


module.exports.updateUserProfile = async (req, res) => {
    try {
      const user = await userModel.findById(req.user.id);
      if (!user) return res.status(404).json({ message: "User not found" });
  
      const updateFields = {
        username: req.body.username || user.username,
        phoneNumber: req.body.phoneNumber || user.phoneNumber,
      };
  
      // Handle profile picture
      if (req.file) {
        const DEFAULT_PROFILE_URL = "https://cdn.vectorstock.com/i/1000v/92/16/default-profile-picture-avatar-user-icon-vector-46389216.jpg";
  
        if (user.profilePicture !== DEFAULT_PROFILE_URL && user.imageKitFileId) { // for 2nd or more time update 
          await deleteImage(user.imageKitFileId);
          console.log("Previous image deleted");
        }
  
        const uploadResult = await uploadBufferStream(req.file.buffer);
        updateFields.profilePicture = uploadResult.url;
        updateFields.imageKitFileId = uploadResult.fileId;
      }

  
    const updatedUser = await userModel.findByIdAndUpdate(req.user.id, updateFields, { new: true })
      .select("-password -vaultPassword -__v")
      .populate("savedFakeData")
      .populate("sharedData");
      //AGGRIGATING ALL THE FIELDS 

      res.status(200).json(updatedUser);
    } catch (error) {
      console.error("Update failed:", error);
      res.status(500).json({ message: "Profile update failed" });
    }
  };

```

### `backend\src\controllers\vault.controller.js`

```javascript

const userModel = require("../models/user.model");
const VaultItem = require("../models/vaultitems.model");
const { encryptField, decryptField } = require("../utils/cryptoUtil");

module.exports.getVault = async (req, res) => {
    try {
        const userId = req.user._id;
        const items = await VaultItem.find({ userId });

        const decryptedItems = items.map(item => ({
            _id: item._id,
            title: decryptField(userId, item.encryptedData.title),
            username: decryptField(userId, item.encryptedData.username),
            password: decryptField(userId, item.encryptedData.password),
            createdAt: item.createdAt,
        }));

        return res.status(200).json(decryptedItems);
    } catch (err) {
        console.error("Vault Get Error:", err);
        return res.status(500).json({ errors: [err.message] });
    }
};

module.exports.addVault = async (req, res) => {
    try {
        const { title, username, password } = req.body;
        const userId = req.user._id;

        if (!title || !username || !password) {
            return res.status(400).json({ errors: ["All fields are required."] });
        }

        const newItem = new VaultItem({
            userId,
            encryptedData: {
                title: encryptField(userId, title),
                username: encryptField(userId, username),
                password: encryptField(userId, password),
            },
        });

        await newItem.save();
        return res.status(201).json({ message: "Vault item encrypted and saved!" });

    } catch (error) {
        return res.status(500).json({ errors: ["Internal server error"] });
    }
};

module.exports.updateVault = async (req, res) => {
    try {
        const userId = req.user._id;
        const vaultId = req.params.id;
        const { title, username, password } = req.body;

        const vaultItem = await VaultItem.findOne({ _id: vaultId, userId });
        if (!vaultItem) {
            return res.status(404).json({ errors: ["Vault item not found"] });
        }

        if (title) vaultItem.encryptedData.title = encryptField(userId, title);
        if (username) vaultItem.encryptedData.username = encryptField(userId, username);
        if (password) vaultItem.encryptedData.password = encryptField(userId, password);

        await vaultItem.save();
        return res.status(200).json({ message: "Vault item updated successfully" });

    } catch (err) {
        console.error(err);
        return res.status(500).json({ error: "Something went wrong!" });
    }
};

module.exports.deleteVault = async (req, res) => {
    try {
        const { id } = req.params;
        const userId = req.user._id;

        const vaultItem = await VaultItem.findOneAndDelete({ _id: id, userId });
        if (!vaultItem) {
            return res.status(404).json({ errors: ["Vault item not found"] });
        }

        return res.status(200).json({ message: "Vault item deleted successfully" });

    } catch (error) {
        return res.status(500).json({ errors: ["Internal server error"] });
    }
};

module.exports.createVaultPassword = async (req, res) => {
    try {
        const { password } = req.body;
        const user = await userModel.findById(req.user._id);

        if (user.vaultPassword) {
            return res.status(400).json({ errors: ["Vault password already set"] });
        }

        if (!password) {
            return res.status(400).json({ errors: ["Password is required"] });
        }


        const vaultPassword = userModel.generateHashedPassword(password);
        const updateduser = await userModel.findByIdAndUpdate(user, {
            vaultPassword: vaultPassword,
        }, { new: true });

        if (!updateduser) {
            return res.status(404).json({ errors: ["User not found"] });
        }


        return res.status(200).json({ message: "Vault password set successfully" });

    } catch (error) {

    }
}

module.exports.openVault = async (req, res) => {
    try {
        const password = req.body.password;
        const user = await userModel.findById(req.user._id);
        

        if (!password) {
            return res.status(400).json({ errors: ["Password is required"] })



        }
        const isMatch = await user.compareVaultPassword(password);

        if (!isMatch) {
            return res.status(400).json({ errors: ["Incorrect password"] });
        }

        res.status(200).json({ message: "Vault opened successfully" });

    } catch (error) {
        console.error("Error opening vault:", error);
        return res.status(500).json({ errors: ["Internal server error"] });
    }

}


module.exports.isVaultInitialized = async (req, res) => {
    try {
        const user = await userModel.findById(req.user._id).select("vaultPassword");

        if (!user) {
            return res.status(404).json({ errors: ["User not found"] });
        }

        const isInitialized = !!user.vaultPassword;
        return res.status(200).json({ isInitialized });

    } catch (error) {
        console.error("Error checking vault initialization:", error);
        return res.status(500).json({ errors: ["Internal server error"] });
    }
}
```

### `backend\src\db\db.js`

```javascript
const mongoose = require('mongoose');
const config = require('../config/config');


const connectDB = () => {
    mongoose.connect(config.MONGODB_URI)
    .then(() => {
        console.log('MongoDB connected')
    })
    .catch((err) => {
        console.log('MongoDB connection error:', err.message)
    })
}


module.exports = connectDB;
```

### `backend\src\middleWare\Multer.js`

```javascript
const multer = require("multer");
const storage = multer.memoryStorage();
const upload = multer({ storage });

module.exports = upload;

```

### `backend\src\middleWare\userMiddleware.js`

```javascript
const userModel = require("../models/user.model");
module.exports.authUser = async(req, res, next) => {
    try {
        const token = req.headers["authorization"]?.split(" ")[1];
        if (!token) {
            return res.status(401).json({ errors: ["Unauthorized"] });
        }

        // Verify token and extract user data
        const decoded = await userModel.validateToken(token);

        if (!decoded) {
            return res.status(401).json({ errors: ["Unauthorized"] });
        }

        // Find user by ID
        const user = await userModel.findById(decoded.id).select("-password -verificationToken -verificationTokenExpiresAt");

        if (!user) {
            return res.status(401).json({ errors: ["Unauthorized"] });
        }

        req.user = user; // Attach user to request object

        next(); // Proceed to the next middleware or route handler



        
    } catch (error) {
        
        console.error(error);
        res.status(500).json({ errors: ["Internal server error"] });

    }

}
```

### `backend\src\models\blog.model.js`

```javascript
const mongoose = require("mongoose");

const blogSchema = new mongoose.Schema({
    title: String,
    content: String,
    source: String,
    image: String,
    datePublished: Date,
    tags: [String],
});


const blogModel = mongoose.model("Blog", blogSchema);

module.exports = blogModel
```

### `backend\src\models\BreachAlert.model.js`

```javascript
// models/breaches.model.js
const mongoose = require('mongoose');

const breachAlertSchema = new mongoose.Schema({
    email: { type: String, required: true, unique: true },
    breaches: [
      {
        source: { type: String },
        date: { type: Date },
        type: { type: String },
        details: { type: String }
      }
    ],
    createdAt: { type: Date, default: Date.now }
  });


const breachAlertModel = mongoose.model('BreachAlert', breachAlertSchema);
module.exports = breachAlertModel;

```

### `backend\src\models\fakeData.model.js`

```javascript
const mongoose = require("mongoose");

const FakeDataSchema = new mongoose.Schema({
  userId: {
    type: mongoose.Schema.Types.ObjectId,
    ref: "User",
    required: true,
  },
  name: String,
  phone: String,
  address: String,
  city: String,
  state: String,
  aadhar: String,
  createdAt: {
    type: Date,
    default: Date.now,
  },
});

FakeDataSchema.index({ userId: 1 });


const fakeDataModel = mongoose.model("FakeData", FakeDataSchema);
module.exports = fakeDataModel;

```

### `backend\src\models\SharedApp.model.js`

```javascript
const mongoose = require("mongoose");

const sharedDataSchema = new mongoose.Schema(
  {
    email: {
      type: Boolean,
      default: false,
    },
    password: {
      type: Boolean,
      default: false,
    },
    phoneNumber: {
      type: Boolean,
      default: false,
    },
    location: {
      type: Boolean,
      default: false,
    },
    aadhaarNumber: {
      type: Boolean,
      default: false,
    },
  },
  { _id: false } // No separate _id for nested sharedData object
);

const sharedAppSchema = new mongoose.Schema(
  {
    userId: {
      type: mongoose.Schema.Types.ObjectId,
      ref: "User",
      required: true,
    },
    appName: {
      type: String,
      required: true,
    },
    sharedData: {
      type: sharedDataSchema,
      default: () => ({}),
    },
    accessDate: {
      type: Date,
      default: Date.now,
    },
    lastAccessed: {
      type: Date,
    },
  },
  { timestamps: true }
);

// 🔥 Indexes
sharedAppSchema.index({ userId: 1 });
sharedAppSchema.index({ appName: 1 });

module.exports = mongoose.model("SharedApp", sharedAppSchema);

```

### `backend\src\models\user.model.js`

```javascript
const mongoose = require('mongoose');
const config = require('../config/config');
const bcrypt = require('bcrypt');
const jwt = require('jsonwebtoken');
require("./BreachAlert.model");


const userSchema = new mongoose.Schema({
    username: {
        type: String,
        required: true,
        trim: true,
    },
    email: {
        type: String,
        required: true,
        unique: true,
        trim: true,
    },
    password: {
        type: String,
        required: true,
    },
    vaultPassword: {
        type: String,
        default: null,
    },
    phoneNumber: {
        type: String,
        required: true,
        unique: true,
    },
    isPremium: { type: Boolean, default: false },

    profilePicture: {
        type: String,
        default: "https://cdn.vectorstock.com/i/1000v/92/16/default-profile-picture-avatar-user-icon-vector-46389216.jpg",
    },

    isVerified: {
        type: Boolean,
        default: false,
    },
    resetPasswordToken: {
        type: String,
    },
    resetPasswordTokenExpiresAt: {
        type: Date,
    },
    verificationToken: {
        type: String,
    },
    verificationTokenExpiresAt: {
        type: Date,
    },
    sharedData: [{
        type: mongoose.Schema.Types.ObjectId,
        ref: 'SharedApp',
    }],
    savedFakeData: [{
        type: mongoose.Schema.Types.ObjectId,
        ref: 'FakeData',
    }],
    imageKitFileId: {
        type: String,
        default: null,
    },


}, { timestamps: true });

//indexes
userSchema.index({ email: 1 }, { unique: true }); // all  Fields with high update frequency  and  Low query usage
userSchema.index({ username: 1 });
userSchema.index({ isPremium: 1 });



userSchema.statics.generateHashedPassword = (password) => {
    return bcrypt.hashSync(password, 10);
};
userSchema.methods.comparePassword = function (password) {
    return bcrypt.compareSync(password, this.password);
};
userSchema.methods.compareVaultPassword = function (password) {
    return bcrypt.compareSync(password, this.vaultPassword);
};

userSchema.statics.generateToken = function (user) {
    return jwt.sign({ id: user._id, email: user.email }, config.JWT_SECRET);
};
userSchema.statics.validateToken = function (token) {
    return jwt.verify(token, config.JWT_SECRET, (err, decoded) => {
        if (err) {
            return false;
        }
        return decoded;
    });
};


const userModel = mongoose.model('User', userSchema);

module.exports = userModel;
```

### `backend\src\models\vaultitems.model.js`

```javascript
const mongoose = require('mongoose');

const VaultItemSchema = new mongoose.Schema({
    userId: {
      type: mongoose.Schema.Types.ObjectId,
      ref: 'User',
      required: true,
    },
    encryptedData: {
      title: {
        data: String,
        iv: String,
        tag: String,
      },
      username: {
        data: String,
        iv: String,
        tag: String,
      },
      password: {
        data: String,
        iv: String,
        tag: String,
      },
    },
    createdAt: { type: Date, default: Date.now },

  });

  VaultItemSchema.index({ userId: 1 });

const VaultItem = mongoose.model('VaultItem', VaultItemSchema);


module.exports = VaultItem;
```

### `backend\src\routes\auth.routes.js`

```javascript
const router = require("express").Router();
const authController = require("../controllers/auth.controller");
const { authUser } = require("../middleWare/userMiddleware");

//routes
router.post("/register" , authController.registerController);
router.post("/login" , authController.loginController);
router.get("/authme" , authUser ,  authController.authMe)



module.exports = router;
```

### `backend\src\routes\blog.routes.js`

```javascript
const express = require("express");
const blogController = require("../controllers/blog.controller.js");
const router = express.Router();

// Add blog post
router.post("/add",blogController.createBlog); 

// Get all posts
router.get("/",blogController.getAllBlogs);

module.exports = router;

```

### `backend\src\routes\breach.routes.js`

```javascript
// routes/breach.routes.js
const express = require("express");
const router = express.Router();
const breachController = require("../controllers/breach.controller");
const { authUser } = require("../middleWare/userMiddleware");

router.get("/:email", authUser, breachController.getBreachesByEmail);

module.exports = router;

```

### `backend\src\routes\fakeData.routes.js`

```javascript
// routes/fakeData.routes.js
const express = require("express");
const router = express.Router();
const fakeDataController = require("../controllers/fakeData.controller");
const { authUser } = require("../middleWare/userMiddleware");


// POST - Generate new fake data
router.post("/generate", authUser, fakeDataController.generateFakeData);

// GET - Get all fake data entries for logged-in user
router.get("/all", authUser, fakeDataController.getFakeData);

// DELETE - Delete a specific fake data entry by ID
router.post("/delete", authUser, fakeDataController.deleteFakeData);

module.exports = router;

```

### `backend\src\routes\otp.routes.js`

```javascript
const router = require("express").Router();
const otpControllers = require("../controllers/otp.controller");

//routes
router.post("/verifyotp" , otpControllers.verifyOTPController )
router.post("/resendotp" , otpControllers.resendOTPController )
// router.get("/forgotpassword" , otpControllers.forgotPasswordController )



module.exports = router;
```

### `backend\src\routes\sharedData.routes.js`

```javascript
const express = require("express");
const {
    getSharedApps,
    addSharedApp,
    updateSharedApp,
    deleteSharedApp,
} = require("../controllers/sharedApp.controller");
const { authUser } = require("../middleWare/userMiddleware");

const router = express.Router();

router.get("/", authUser, getSharedApps);
router.post("/", authUser, addSharedApp);
router.put("/:id", authUser, updateSharedApp);
router.delete("/:id", authUser, deleteSharedApp);

module.exports = router;

```

### `backend\src\routes\user.routes.js`

```javascript
const router = require("express").Router();
const userControllers = require("../controllers/user.controller");
const upload = require("../middleWare/Multer");
const { authUser } = require("../middleWare/userMiddleware");


router.get("/:id" ,authUser ,  userControllers.getUserById);
router.put("/update", authUser, upload.single("profilePicture"), userControllers.updateUserProfile);


module.exports = router;
```

### `backend\src\routes\vault.routes.js`

```javascript
const router = require('express').Router();
const { authUser } = require('../middleWare/userMiddleware');
const vaultController = require('../controllers/vault.controller');

// Route to get all vaults for a user
router.get('/getall', authUser, vaultController.getVault);
router.post('/add', authUser, vaultController.addVault);
router.put('/update/:id', authUser, vaultController.updateVault);
router.delete('/delete/:id', authUser, vaultController.deleteVault);
router.post('/createvaultPassword', authUser, vaultController.createVaultPassword);
router.post('/openvault', authUser, vaultController.openVault);
router.get("/isInitialized", authUser, vaultController.isVaultInitialized);

module.exports = router;
```

### `backend\src\services\auth.service.js`

```javascript
const userModel = require("../models/user.model")

module.exports.createUser = async ({ firstName, lastName, email, password, phoneNumber , OTP }) => {
    // Check if user already exists
    const userExists = await userModel.findOne({ email })
    if (userExists) {
        console.log(userExists)
        throw new Error('User already exists')
    }
    // Hash password
    const hashedPassword = userModel.generateHashedPassword(password)

    const username = firstName.trim() + ` ${lastName.trim()}`


    // Create new user
    const newUser = await userModel.create({
        username,
        email,
        password: hashedPassword,
        phoneNumber,
        verificationToken: OTP,
        verificationTokenExpiresAt: Date.now() + 2 * 60 * 1000, // 2 min expiration time
    })


    if(!newUser) {
        throw new Error('User creation failed')
    }

    // delete password from user object
    newUser.password = undefined

    return newUser


}
```

### `backend\src\services\email.service.js`

```javascript
const nodeMailer = require('nodemailer');
const config = require('../config/config');

const transporter = nodeMailer.createTransport({
    service: 'gmail',
    auth:{
        user : config.EMAIL_USER , 
        pass : config.EMAIL_PASS
    }

})
// Email send function for HTML content
const sendEmail = async (to, subject, htmlContent) => {
    try {
      const info = await transporter.sendMail({
        from: process.env.EMAIL_USER, // Sender address
        to, // Receiver address
        subject, // Subject line
        html: htmlContent, // HTML content
      });
  
      console.log("Email sent: " + info.response);
    } catch (error) {
      console.error("Error sending email: ", error);
    }
  };
  
  module.exports = { sendEmail };
```

### `backend\src\utils\cryptoUtil.js`

```javascript
const crypto = require('crypto');
const config = require('../config/config');
const VAULT_SECRET_KEY = config.VAULT_SECRET_KEY;

if (!VAULT_SECRET_KEY || VAULT_SECRET_KEY.length < 32) {
  throw new Error("VAULT_SECRET_KEY must be at least 32 characters long");
}

function generateEncryptionKey(userId) {
  return crypto.createHash("sha256").update(VAULT_SECRET_KEY + userId).digest(); // 32 bytes
}

function encryptField(userId, text) {
  const key = generateEncryptionKey(userId);
  const iv = crypto.randomBytes(12);
  const cipher = crypto.createCipheriv("aes-256-gcm", key, iv);
  const encrypted = Buffer.concat([cipher.update(text, "utf8"), cipher.final()]);
  const tag = cipher.getAuthTag();
  return {
    data: encrypted.toString("base64"),
    iv: iv.toString("base64"),
    tag: tag.toString("base64"),
  };
}

function decryptField(userId, encryptedField) {
  const key = generateEncryptionKey(userId);
  const { data, iv, tag } = encryptedField;
  const decipher = crypto.createDecipheriv("aes-256-gcm", key, Buffer.from(iv, "base64"));
  decipher.setAuthTag(Buffer.from(tag, "base64"));
  const decrypted = Buffer.concat([
    decipher.update(Buffer.from(data, "base64")),
    decipher.final(),
  ]);
  return decrypted.toString("utf8");
}

module.exports = {
  generateEncryptionKey,
  encryptField,
  decryptField,
};

```

### `backend\src\utils\fetchPrivacyNews.js`

```javascript
const cron = require("node-cron");
const axios = require("axios");
const blogModel = require("../models/blog.model");
const { NEWS_API_KEY } = require("../config/config");

const fetchAndSaveNews = async () => {
  try {
    const res = await axios.get(`https://newsapi.org/v2/everything?q=privacy&sortBy=publishedAt&pageSize=1&apiKey=${NEWS_API_KEY}`);
    const article = res.data.articles[0];

    const blog = new blogModel({
      title: article.title,
      content: article.description,
      source: article.url,
      image: article.urlToImage,
      datePublished: new Date(article.publishedAt),
      tags: ["privacy", "news"],
    });

    await blog.save();
    console.log("✅ blogModel post saved!");
  } catch (error) {
    console.error("❌ Error fetching/saving blog:", error.message);
  }
};

// Schedule: every day at 9 AM
cron.schedule("0 9 * * *", fetchAndSaveNews);


```

### `backend\src\utils\generateVerificationCode.js`

```javascript
const generateVerificationCode = () => {
    const code = Math.floor(100000 + Math.random() * 900000).toString(); // Generates a 5-digit random number
    return code;
}
module.exports = generateVerificationCode;
```

### `backend\src\utils\imageKit.js`

```javascript
const ImageKit = require("imagekit");
const { Readable } = require("stream");
const config = require("../config/config");
const mongoose = require("mongoose");

const imagekit = new ImageKit({
  publicKey: config.IMAGEKIT_PUBLIC_KEY,
  privateKey: config.IMAGEKIT_PRIVATE_KEY,
  urlEndpoint: config.IMAGEKIT_URL_ENDPOINT,
});

// Upload buffer stream
const uploadBufferStream = async (fileBuffer) => {
  const result = await imagekit.upload({
    file: Readable.from(fileBuffer),
    fileName: new mongoose.Types.ObjectId().toString(),
    isPublished: true,
    folder: "/PRIVGUARD",
  });
  return result;
};

// Delete file by fileId
const deleteImage = async (fileId) => {
  try {
    await imagekit.deleteFile(fileId);
    console.log("Deleted image from ImageKit:", fileId);
  } catch (err) {
    console.error("Error deleting file from ImageKit:", err.message);
  }
};

module.exports = {
  uploadBufferStream,
  deleteImage,
};

```

### `frontend\.gitignore`

```
# Logs
logs
*.log
npm-debug.log*
yarn-debug.log*
yarn-error.log*
pnpm-debug.log*
lerna-debug.log*

node_modules
dist
dist-ssr
*.local

# Editor directories and files
.vscode/*
!.vscode/extensions.json
.idea
.DS_Store
*.suo
*.ntvs*
*.njsproj
*.sln
*.sw?

```

### `frontend\eslint.config.js`

```javascript
import js from '@eslint/js'
import globals from 'globals'
import reactHooks from 'eslint-plugin-react-hooks'
import reactRefresh from 'eslint-plugin-react-refresh'

export default [
  { ignores: ['dist'] },
  {
    files: ['**/*.{js,jsx}'],
    languageOptions: {
      ecmaVersion: 2020,
      globals: globals.browser,
      parserOptions: {
        ecmaVersion: 'latest',
        ecmaFeatures: { jsx: true },
        sourceType: 'module',
      },
    },
    plugins: {
      'react-hooks': reactHooks,
      'react-refresh': reactRefresh,
    },
    rules: {
      ...js.configs.recommended.rules,
      ...reactHooks.configs.recommended.rules,
      'no-unused-vars': ['error', { varsIgnorePattern: '^[A-Z_]' }],
      'react-refresh/only-export-components': [
        'warn',
        { allowConstantExport: true },
      ],
    },
  },
]

```

### `frontend\index.html`

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <link rel="icon" type="image/svg+xml" href="./src/assets/PrevGuard.svg" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>PrivGuard</title>
  </head>
  <body>
    <div id="root"></div>
    <script type="module" src="/src/main.jsx"></script>
  </body>
</html>

```

### `frontend\package-lock.json`

```json
{
  "name": "frontend",
  "version": "0.0.0",
  "lockfileVersion": 3,
  "requires": true,
  "packages": {
    "": {
      "name": "frontend",
      "version": "0.0.0",
      "dependencies": {
        "@faker-js/faker": "^9.7.0",
        "@reduxjs/toolkit": "^2.6.1",
        "argon2-browser": "^1.18.0",
        "axios": "^1.8.4",
        "crypto-js": "^4.2.0",
        "dompurify": "^3.2.5",
        "framer-motion": "^12.6.5",
        "lodash": "^4.17.21",
        "lucide-react": "^0.486.0",
        "react": "^19.0.0",
        "react-circular-progressbar": "^2.2.0",
        "react-dom": "^19.0.0",
        "react-icons": "^5.5.0",
        "react-redux": "^9.2.0",
        "react-router-dom": "^7.4.1",
        "react-toastify": "^11.0.5"
      },
      "devDependencies": {
        "@eslint/js": "^9.21.0",
        "@types/react": "^19.0.10",
        "@types/react-dom": "^19.0.4",
        "@vitejs/plugin-react": "^4.3.4",
        "autoprefixer": "^10.4.21",
        "eslint": "^9.21.0",
        "eslint-plugin-react-hooks": "^5.1.0",
        "eslint-plugin-react-refresh": "^0.4.19",
        "globals": "^15.15.0",
        "postcss": "^8.5.3",
        "tailwindcss": "^3.4.17",
        "vite": "^6.2.0"
      }
    },
    "node_modules/@alloc/quick-lru": {
      "version": "5.2.0",
      "resolved": "https://registry.npmjs.org/@alloc/quick-lru/-/quick-lru-5.2.0.tgz",
      "integrity": "sha512-UrcABB+4bUrFABwbluTIBErXwvbsU/V7TZWfmbgJfbkwiBuziS9gxdODUyuiecfdGQ85jglMW6juS3+z5TsKLw==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=10"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/@ampproject/remapping": {
      "version": "2.3.0",
      "resolved": "https://registry.npmjs.org/@ampproject/remapping/-/remapping-2.3.0.tgz",
      "integrity": "sha512-30iZtAPgz+LTIYoeivqYo853f02jBYSd5uGnGpkFV0M3xOt9aN73erkgYAmZU43x4VfqcnLxW9Kpg3R5LC4YYw==",
      "dev": true,
      "license": "Apache-2.0",
      "dependencies": {
        "@jridgewell/gen-mapping": "^0.3.5",
        "@jridgewell/trace-mapping": "^0.3.24"
      },
      "engines": {
        "node": ">=6.0.0"
      }
    },
    "node_modules/@babel/code-frame": {
      "version": "7.26.2",
      "resolved": "https://registry.npmjs.org/@babel/code-frame/-/code-frame-7.26.2.tgz",
      "integrity": "sha512-RJlIHRueQgwWitWgF8OdFYGZX328Ax5BCemNGlqHfplnRT9ESi8JkFlvaVYbS+UubVY6dpv87Fs2u5M29iNFVQ==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@babel/helper-validator-identifier": "^7.25.9",
        "js-tokens": "^4.0.0",
        "picocolors": "^1.0.0"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/compat-data": {
      "version": "7.26.8",
      "resolved": "https://registry.npmjs.org/@babel/compat-data/-/compat-data-7.26.8.tgz",
      "integrity": "sha512-oH5UPLMWR3L2wEFLnFJ1TZXqHufiTKAiLfqw5zkhS4dKXLJ10yVztfil/twG8EDTA4F/tvVNw9nOl4ZMslB8rQ==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/core": {
      "version": "7.26.10",
      "resolved": "https://registry.npmjs.org/@babel/core/-/core-7.26.10.tgz",
      "integrity": "sha512-vMqyb7XCDMPvJFFOaT9kxtiRh42GwlZEg1/uIgtZshS5a/8OaduUfCi7kynKgc3Tw/6Uo2D+db9qBttghhmxwQ==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@ampproject/remapping": "^2.2.0",
        "@babel/code-frame": "^7.26.2",
        "@babel/generator": "^7.26.10",
        "@babel/helper-compilation-targets": "^7.26.5",
        "@babel/helper-module-transforms": "^7.26.0",
        "@babel/helpers": "^7.26.10",
        "@babel/parser": "^7.26.10",
        "@babel/template": "^7.26.9",
        "@babel/traverse": "^7.26.10",
        "@babel/types": "^7.26.10",
        "convert-source-map": "^2.0.0",
        "debug": "^4.1.0",
        "gensync": "^1.0.0-beta.2",
        "json5": "^2.2.3",
        "semver": "^6.3.1"
      },
      "engines": {
        "node": ">=6.9.0"
      },
      "funding": {
        "type": "opencollective",
        "url": "https://opencollective.com/babel"
      }
    },
    "node_modules/@babel/generator": {
      "version": "7.27.0",
      "resolved": "https://registry.npmjs.org/@babel/generator/-/generator-7.27.0.tgz",
      "integrity": "sha512-VybsKvpiN1gU1sdMZIp7FcqphVVKEwcuj02x73uvcHE0PTihx1nlBcowYWhDwjpoAXRv43+gDzyggGnn1XZhVw==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@babel/parser": "^7.27.0",
        "@babel/types": "^7.27.0",
        "@jridgewell/gen-mapping": "^0.3.5",
        "@jridgewell/trace-mapping": "^0.3.25",
        "jsesc": "^3.0.2"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/helper-compilation-targets": {
      "version": "7.27.0",
      "resolved": "https://registry.npmjs.org/@babel/helper-compilation-targets/-/helper-compilation-targets-7.27.0.tgz",
      "integrity": "sha512-LVk7fbXml0H2xH34dFzKQ7TDZ2G4/rVTOrq9V+icbbadjbVxxeFeDsNHv2SrZeWoA+6ZiTyWYWtScEIW07EAcA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@babel/compat-data": "^7.26.8",
        "@babel/helper-validator-option": "^7.25.9",
        "browserslist": "^4.24.0",
        "lru-cache": "^5.1.1",
        "semver": "^6.3.1"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/helper-module-imports": {
      "version": "7.25.9",
      "resolved": "https://registry.npmjs.org/@babel/helper-module-imports/-/helper-module-imports-7.25.9.tgz",
      "integrity": "sha512-tnUA4RsrmflIM6W6RFTLFSXITtl0wKjgpnLgXyowocVPrbYrLUXSBXDgTs8BlbmIzIdlBySRQjINYs2BAkiLtw==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@babel/traverse": "^7.25.9",
        "@babel/types": "^7.25.9"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/helper-module-transforms": {
      "version": "7.26.0",
      "resolved": "https://registry.npmjs.org/@babel/helper-module-transforms/-/helper-module-transforms-7.26.0.tgz",
      "integrity": "sha512-xO+xu6B5K2czEnQye6BHA7DolFFmS3LB7stHZFaOLb1pAwO1HWLS8fXA+eh0A2yIvltPVmx3eNNDBJA2SLHXFw==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@babel/helper-module-imports": "^7.25.9",
        "@babel/helper-validator-identifier": "^7.25.9",
        "@babel/traverse": "^7.25.9"
      },
      "engines": {
        "node": ">=6.9.0"
      },
      "peerDependencies": {
        "@babel/core": "^7.0.0"
      }
    },
    "node_modules/@babel/helper-plugin-utils": {
      "version": "7.26.5",
      "resolved": "https://registry.npmjs.org/@babel/helper-plugin-utils/-/helper-plugin-utils-7.26.5.tgz",
      "integrity": "sha512-RS+jZcRdZdRFzMyr+wcsaqOmld1/EqTghfaBGQQd/WnRdzdlvSZ//kF7U8VQTxf1ynZ4cjUcYgjVGx13ewNPMg==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/helper-string-parser": {
      "version": "7.25.9",
      "resolved": "https://registry.npmjs.org/@babel/helper-string-parser/-/helper-string-parser-7.25.9.tgz",
      "integrity": "sha512-4A/SCr/2KLd5jrtOMFzaKjVtAei3+2r/NChoBNoZ3EyP/+GlhoaEGoWOZUmFmoITP7zOJyHIMm+DYRd8o3PvHA==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/helper-validator-identifier": {
      "version": "7.25.9",
      "resolved": "https://registry.npmjs.org/@babel/helper-validator-identifier/-/helper-validator-identifier-7.25.9.tgz",
      "integrity": "sha512-Ed61U6XJc3CVRfkERJWDz4dJwKe7iLmmJsbOGu9wSloNSFttHV0I8g6UAgb7qnK5ly5bGLPd4oXZlxCdANBOWQ==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/helper-validator-option": {
      "version": "7.25.9",
      "resolved": "https://registry.npmjs.org/@babel/helper-validator-option/-/helper-validator-option-7.25.9.tgz",
      "integrity": "sha512-e/zv1co8pp55dNdEcCynfj9X7nyUKUXoUEwfXqaZt0omVOmDe9oOTdKStH4GmAw6zxMFs50ZayuMfHDKlO7Tfw==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/helpers": {
      "version": "7.27.0",
      "resolved": "https://registry.npmjs.org/@babel/helpers/-/helpers-7.27.0.tgz",
      "integrity": "sha512-U5eyP/CTFPuNE3qk+WZMxFkp/4zUzdceQlfzf7DdGdhp+Fezd7HD+i8Y24ZuTMKX3wQBld449jijbGq6OdGNQg==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@babel/template": "^7.27.0",
        "@babel/types": "^7.27.0"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/parser": {
      "version": "7.27.0",
      "resolved": "https://registry.npmjs.org/@babel/parser/-/parser-7.27.0.tgz",
      "integrity": "sha512-iaepho73/2Pz7w2eMS0Q5f83+0RKI7i4xmiYeBmDzfRVbQtTOG7Ts0S4HzJVsTMGI9keU8rNfuZr8DKfSt7Yyg==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@babel/types": "^7.27.0"
      },
      "bin": {
        "parser": "bin/babel-parser.js"
      },
      "engines": {
        "node": ">=6.0.0"
      }
    },
    "node_modules/@babel/plugin-transform-react-jsx-self": {
      "version": "7.25.9",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-react-jsx-self/-/plugin-transform-react-jsx-self-7.25.9.tgz",
      "integrity": "sha512-y8quW6p0WHkEhmErnfe58r7x0A70uKphQm8Sp8cV7tjNQwK56sNVK0M73LK3WuYmsuyrftut4xAkjjgU0twaMg==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@babel/helper-plugin-utils": "^7.25.9"
      },
      "engines": {
        "node": ">=6.9.0"
      },
      "peerDependencies": {
        "@babel/core": "^7.0.0-0"
      }
    },
    "node_modules/@babel/plugin-transform-react-jsx-source": {
      "version": "7.25.9",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-react-jsx-source/-/plugin-transform-react-jsx-source-7.25.9.tgz",
      "integrity": "sha512-+iqjT8xmXhhYv4/uiYd8FNQsraMFZIfxVSqxxVSZP0WbbSAWvBXAul0m/zu+7Vv4O/3WtApy9pmaTMiumEZgfg==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@babel/helper-plugin-utils": "^7.25.9"
      },
      "engines": {
        "node": ">=6.9.0"
      },
      "peerDependencies": {
        "@babel/core": "^7.0.0-0"
      }
    },
    "node_modules/@babel/template": {
      "version": "7.27.0",
      "resolved": "https://registry.npmjs.org/@babel/template/-/template-7.27.0.tgz",
      "integrity": "sha512-2ncevenBqXI6qRMukPlXwHKHchC7RyMuu4xv5JBXRfOGVcTy1mXCD12qrp7Jsoxll1EV3+9sE4GugBVRjT2jFA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@babel/code-frame": "^7.26.2",
        "@babel/parser": "^7.27.0",
        "@babel/types": "^7.27.0"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/traverse": {
      "version": "7.27.0",
      "resolved": "https://registry.npmjs.org/@babel/traverse/-/traverse-7.27.0.tgz",
      "integrity": "sha512-19lYZFzYVQkkHkl4Cy4WrAVcqBkgvV2YM2TU3xG6DIwO7O3ecbDPfW3yM3bjAGcqcQHi+CCtjMR3dIEHxsd6bA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@babel/code-frame": "^7.26.2",
        "@babel/generator": "^7.27.0",
        "@babel/parser": "^7.27.0",
        "@babel/template": "^7.27.0",
        "@babel/types": "^7.27.0",
        "debug": "^4.3.1",
        "globals": "^11.1.0"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/traverse/node_modules/globals": {
      "version": "11.12.0",
      "resolved": "https://registry.npmjs.org/globals/-/globals-11.12.0.tgz",
      "integrity": "sha512-WOBp/EEGUiIsJSp7wcv/y6MO+lV9UoncWqxuFfm8eBwzWNgyfBd6Gz+IeKQ9jCmyhoH99g15M3T+QaVHFjizVA==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/@babel/types": {
      "version": "7.27.0",
      "resolved": "https://registry.npmjs.org/@babel/types/-/types-7.27.0.tgz",
      "integrity": "sha512-H45s8fVLYjbhFH62dIJ3WtmJ6RSPt/3DRO0ZcT2SUiYiQyz3BLVb9ADEnLl91m74aQPS3AzzeajZHYOalWe3bg==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@babel/helper-string-parser": "^7.25.9",
        "@babel/helper-validator-identifier": "^7.25.9"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@esbuild/aix-ppc64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/aix-ppc64/-/aix-ppc64-0.25.2.tgz",
      "integrity": "sha512-wCIboOL2yXZym2cgm6mlA742s9QeJ8DjGVaL39dLN4rRwrOgOyYSnOaFPhKZGLb2ngj4EyfAFjsNJwPXZvseag==",
      "cpu": [
        "ppc64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "aix"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/android-arm": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/android-arm/-/android-arm-0.25.2.tgz",
      "integrity": "sha512-NQhH7jFstVY5x8CKbcfa166GoV0EFkaPkCKBQkdPJFvo5u+nGXLEH/ooniLb3QI8Fk58YAx7nsPLozUWfCBOJA==",
      "cpu": [
        "arm"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "android"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/android-arm64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/android-arm64/-/android-arm64-0.25.2.tgz",
      "integrity": "sha512-5ZAX5xOmTligeBaeNEPnPaeEuah53Id2tX4c2CVP3JaROTH+j4fnfHCkr1PjXMd78hMst+TlkfKcW/DlTq0i4w==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "android"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/android-x64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/android-x64/-/android-x64-0.25.2.tgz",
      "integrity": "sha512-Ffcx+nnma8Sge4jzddPHCZVRvIfQ0kMsUsCMcJRHkGJ1cDmhe4SsrYIjLUKn1xpHZybmOqCWwB0zQvsjdEHtkg==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "android"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/darwin-arm64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/darwin-arm64/-/darwin-arm64-0.25.2.tgz",
      "integrity": "sha512-MpM6LUVTXAzOvN4KbjzU/q5smzryuoNjlriAIx+06RpecwCkL9JpenNzpKd2YMzLJFOdPqBpuub6eVRP5IgiSA==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "darwin"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/darwin-x64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/darwin-x64/-/darwin-x64-0.25.2.tgz",
      "integrity": "sha512-5eRPrTX7wFyuWe8FqEFPG2cU0+butQQVNcT4sVipqjLYQjjh8a8+vUTfgBKM88ObB85ahsnTwF7PSIt6PG+QkA==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "darwin"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/freebsd-arm64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/freebsd-arm64/-/freebsd-arm64-0.25.2.tgz",
      "integrity": "sha512-mLwm4vXKiQ2UTSX4+ImyiPdiHjiZhIaE9QvC7sw0tZ6HoNMjYAqQpGyui5VRIi5sGd+uWq940gdCbY3VLvsO1w==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "freebsd"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/freebsd-x64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/freebsd-x64/-/freebsd-x64-0.25.2.tgz",
      "integrity": "sha512-6qyyn6TjayJSwGpm8J9QYYGQcRgc90nmfdUb0O7pp1s4lTY+9D0H9O02v5JqGApUyiHOtkz6+1hZNvNtEhbwRQ==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "freebsd"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/linux-arm": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-arm/-/linux-arm-0.25.2.tgz",
      "integrity": "sha512-UHBRgJcmjJv5oeQF8EpTRZs/1knq6loLxTsjc3nxO9eXAPDLcWW55flrMVc97qFPbmZP31ta1AZVUKQzKTzb0g==",
      "cpu": [
        "arm"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/linux-arm64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-arm64/-/linux-arm64-0.25.2.tgz",
      "integrity": "sha512-gq/sjLsOyMT19I8obBISvhoYiZIAaGF8JpeXu1u8yPv8BE5HlWYobmlsfijFIZ9hIVGYkbdFhEqC0NvM4kNO0g==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/linux-ia32": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-ia32/-/linux-ia32-0.25.2.tgz",
      "integrity": "sha512-bBYCv9obgW2cBP+2ZWfjYTU+f5cxRoGGQ5SeDbYdFCAZpYWrfjjfYwvUpP8MlKbP0nwZ5gyOU/0aUzZ5HWPuvQ==",
      "cpu": [
        "ia32"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/linux-loong64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-loong64/-/linux-loong64-0.25.2.tgz",
      "integrity": "sha512-SHNGiKtvnU2dBlM5D8CXRFdd+6etgZ9dXfaPCeJtz+37PIUlixvlIhI23L5khKXs3DIzAn9V8v+qb1TRKrgT5w==",
      "cpu": [
        "loong64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/linux-mips64el": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-mips64el/-/linux-mips64el-0.25.2.tgz",
      "integrity": "sha512-hDDRlzE6rPeoj+5fsADqdUZl1OzqDYow4TB4Y/3PlKBD0ph1e6uPHzIQcv2Z65u2K0kpeByIyAjCmjn1hJgG0Q==",
      "cpu": [
        "mips64el"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/linux-ppc64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-ppc64/-/linux-ppc64-0.25.2.tgz",
      "integrity": "sha512-tsHu2RRSWzipmUi9UBDEzc0nLc4HtpZEI5Ba+Omms5456x5WaNuiG3u7xh5AO6sipnJ9r4cRWQB2tUjPyIkc6g==",
      "cpu": [
        "ppc64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/linux-riscv64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-riscv64/-/linux-riscv64-0.25.2.tgz",
      "integrity": "sha512-k4LtpgV7NJQOml/10uPU0s4SAXGnowi5qBSjaLWMojNCUICNu7TshqHLAEbkBdAszL5TabfvQ48kK84hyFzjnw==",
      "cpu": [
        "riscv64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/linux-s390x": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-s390x/-/linux-s390x-0.25.2.tgz",
      "integrity": "sha512-GRa4IshOdvKY7M/rDpRR3gkiTNp34M0eLTaC1a08gNrh4u488aPhuZOCpkF6+2wl3zAN7L7XIpOFBhnaE3/Q8Q==",
      "cpu": [
        "s390x"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/linux-x64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-x64/-/linux-x64-0.25.2.tgz",
      "integrity": "sha512-QInHERlqpTTZ4FRB0fROQWXcYRD64lAoiegezDunLpalZMjcUcld3YzZmVJ2H/Cp0wJRZ8Xtjtj0cEHhYc/uUg==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/netbsd-arm64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/netbsd-arm64/-/netbsd-arm64-0.25.2.tgz",
      "integrity": "sha512-talAIBoY5M8vHc6EeI2WW9d/CkiO9MQJ0IOWX8hrLhxGbro/vBXJvaQXefW2cP0z0nQVTdQ/eNyGFV1GSKrxfw==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "netbsd"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/netbsd-x64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/netbsd-x64/-/netbsd-x64-0.25.2.tgz",
      "integrity": "sha512-voZT9Z+tpOxrvfKFyfDYPc4DO4rk06qamv1a/fkuzHpiVBMOhpjK+vBmWM8J1eiB3OLSMFYNaOaBNLXGChf5tg==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "netbsd"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/openbsd-arm64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/openbsd-arm64/-/openbsd-arm64-0.25.2.tgz",
      "integrity": "sha512-dcXYOC6NXOqcykeDlwId9kB6OkPUxOEqU+rkrYVqJbK2hagWOMrsTGsMr8+rW02M+d5Op5NNlgMmjzecaRf7Tg==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "openbsd"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/openbsd-x64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/openbsd-x64/-/openbsd-x64-0.25.2.tgz",
      "integrity": "sha512-t/TkWwahkH0Tsgoq1Ju7QfgGhArkGLkF1uYz8nQS/PPFlXbP5YgRpqQR3ARRiC2iXoLTWFxc6DJMSK10dVXluw==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "openbsd"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/sunos-x64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/sunos-x64/-/sunos-x64-0.25.2.tgz",
      "integrity": "sha512-cfZH1co2+imVdWCjd+D1gf9NjkchVhhdpgb1q5y6Hcv9TP6Zi9ZG/beI3ig8TvwT9lH9dlxLq5MQBBgwuj4xvA==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "sunos"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/win32-arm64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/win32-arm64/-/win32-arm64-0.25.2.tgz",
      "integrity": "sha512-7Loyjh+D/Nx/sOTzV8vfbB3GJuHdOQyrOryFdZvPHLf42Tk9ivBU5Aedi7iyX+x6rbn2Mh68T4qq1SDqJBQO5Q==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "win32"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/win32-ia32": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/win32-ia32/-/win32-ia32-0.25.2.tgz",
      "integrity": "sha512-WRJgsz9un0nqZJ4MfhabxaD9Ft8KioqU3JMinOTvobbX6MOSUigSBlogP8QB3uxpJDsFS6yN+3FDBdqE5lg9kg==",
      "cpu": [
        "ia32"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "win32"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/win32-x64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/win32-x64/-/win32-x64-0.25.2.tgz",
      "integrity": "sha512-kM3HKb16VIXZyIeVrM1ygYmZBKybX8N4p754bw390wGO3Tf2j4L2/WYL+4suWujpgf6GBYs3jv7TyUivdd05JA==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "win32"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@eslint-community/eslint-utils": {
      "version": "4.5.1",
      "resolved": "https://registry.npmjs.org/@eslint-community/eslint-utils/-/eslint-utils-4.5.1.tgz",
      "integrity": "sha512-soEIOALTfTK6EjmKMMoLugwaP0rzkad90iIWd1hMO9ARkSAyjfMfkRRhLvD5qH7vvM0Cg72pieUfR6yh6XxC4w==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "eslint-visitor-keys": "^3.4.3"
      },
      "engines": {
        "node": "^12.22.0 || ^14.17.0 || >=16.0.0"
      },
      "funding": {
        "url": "https://opencollective.com/eslint"
      },
      "peerDependencies": {
        "eslint": "^6.0.0 || ^7.0.0 || >=8.0.0"
      }
    },
    "node_modules/@eslint-community/eslint-utils/node_modules/eslint-visitor-keys": {
      "version": "3.4.3",
      "resolved": "https://registry.npmjs.org/eslint-visitor-keys/-/eslint-visitor-keys-3.4.3.tgz",
      "integrity": "sha512-wpc+LXeiyiisxPlEkUzU6svyS1frIO3Mgxj1fdy7Pm8Ygzguax2N3Fa/D/ag1WqbOprdI+uY6wMUl8/a2G+iag==",
      "dev": true,
      "license": "Apache-2.0",
      "engines": {
        "node": "^12.22.0 || ^14.17.0 || >=16.0.0"
      },
      "funding": {
        "url": "https://opencollective.com/eslint"
      }
    },
    "node_modules/@eslint-community/regexpp": {
      "version": "4.12.1",
      "resolved": "https://registry.npmjs.org/@eslint-community/regexpp/-/regexpp-4.12.1.tgz",
      "integrity": "sha512-CCZCDJuduB9OUkFkY2IgppNZMi2lBQgD2qzwXkEia16cge2pijY/aXi96CJMquDMn3nJdlPV1A5KrJEXwfLNzQ==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": "^12.0.0 || ^14.0.0 || >=16.0.0"
      }
    },
    "node_modules/@eslint/config-array": {
      "version": "0.19.2",
      "resolved": "https://registry.npmjs.org/@eslint/config-array/-/config-array-0.19.2.tgz",
      "integrity": "sha512-GNKqxfHG2ySmJOBSHg7LxeUx4xpuCoFjacmlCoYWEbaPXLwvfIjixRI12xCQZeULksQb23uiA8F40w5TojpV7w==",
      "dev": true,
      "license": "Apache-2.0",
      "dependencies": {
        "@eslint/object-schema": "^2.1.6",
        "debug": "^4.3.1",
        "minimatch": "^3.1.2"
      },
      "engines": {
        "node": "^18.18.0 || ^20.9.0 || >=21.1.0"
      }
    },
    "node_modules/@eslint/config-helpers": {
      "version": "0.2.0",
      "resolved": "https://registry.npmjs.org/@eslint/config-helpers/-/config-helpers-0.2.0.tgz",
      "integrity": "sha512-yJLLmLexii32mGrhW29qvU3QBVTu0GUmEf/J4XsBtVhp4JkIUFN/BjWqTF63yRvGApIDpZm5fa97LtYtINmfeQ==",
      "dev": true,
      "license": "Apache-2.0",
      "engines": {
        "node": "^18.18.0 || ^20.9.0 || >=21.1.0"
      }
    },
    "node_modules/@eslint/core": {
      "version": "0.12.0",
      "resolved": "https://registry.npmjs.org/@eslint/core/-/core-0.12.0.tgz",
      "integrity": "sha512-cmrR6pytBuSMTaBweKoGMwu3EiHiEC+DoyupPmlZ0HxBJBtIxwe+j/E4XPIKNx+Q74c8lXKPwYawBf5glsTkHg==",
      "dev": true,
      "license": "Apache-2.0",
      "dependencies": {
        "@types/json-schema": "^7.0.15"
      },
      "engines": {
        "node": "^18.18.0 || ^20.9.0 || >=21.1.0"
      }
    },
    "node_modules/@eslint/eslintrc": {
      "version": "3.3.1",
      "resolved": "https://registry.npmjs.org/@eslint/eslintrc/-/eslintrc-3.3.1.tgz",
      "integrity": "sha512-gtF186CXhIl1p4pJNGZw8Yc6RlshoePRvE0X91oPGb3vZ8pM3qOS9W9NGPat9LziaBV7XrJWGylNQXkGcnM3IQ==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "ajv": "^6.12.4",
        "debug": "^4.3.2",
        "espree": "^10.0.1",
        "globals": "^14.0.0",
        "ignore": "^5.2.0",
        "import-fresh": "^3.2.1",
        "js-yaml": "^4.1.0",
        "minimatch": "^3.1.2",
        "strip-json-comments": "^3.1.1"
      },
      "engines": {
        "node": "^18.18.0 || ^20.9.0 || >=21.1.0"
      },
      "funding": {
        "url": "https://opencollective.com/eslint"
      }
    },
    "node_modules/@eslint/eslintrc/node_modules/globals": {
      "version": "14.0.0",
      "resolved": "https://registry.npmjs.org/globals/-/globals-14.0.0.tgz",
      "integrity": "sha512-oahGvuMGQlPw/ivIYBjVSrWAfWLBeku5tpPE2fOPLi+WHffIWbuh2tCjhyQhTBPMf5E9jDEH4FOmTYgYwbKwtQ==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/@eslint/js": {
      "version": "9.23.0",
      "resolved": "https://registry.npmjs.org/@eslint/js/-/js-9.23.0.tgz",
      "integrity": "sha512-35MJ8vCPU0ZMxo7zfev2pypqTwWTofFZO6m4KAtdoFhRpLJUpHTZZ+KB3C7Hb1d7bULYwO4lJXGCi5Se+8OMbw==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": "^18.18.0 || ^20.9.0 || >=21.1.0"
      }
    },
    "node_modules/@eslint/object-schema": {
      "version": "2.1.6",
      "resolved": "https://registry.npmjs.org/@eslint/object-schema/-/object-schema-2.1.6.tgz",
      "integrity": "sha512-RBMg5FRL0I0gs51M/guSAj5/e14VQ4tpZnQNWwuDT66P14I43ItmPfIZRhO9fUVIPOAQXU47atlywZ/czoqFPA==",
      "dev": true,
      "license": "Apache-2.0",
      "engines": {
        "node": "^18.18.0 || ^20.9.0 || >=21.1.0"
      }
    },
    "node_modules/@eslint/plugin-kit": {
      "version": "0.2.7",
      "resolved": "https://registry.npmjs.org/@eslint/plugin-kit/-/plugin-kit-0.2.7.tgz",
      "integrity": "sha512-JubJ5B2pJ4k4yGxaNLdbjrnk9d/iDz6/q8wOilpIowd6PJPgaxCuHBnBszq7Ce2TyMrywm5r4PnKm6V3iiZF+g==",
      "dev": true,
      "license": "Apache-2.0",
      "dependencies": {
        "@eslint/core": "^0.12.0",
        "levn": "^0.4.1"
      },
      "engines": {
        "node": "^18.18.0 || ^20.9.0 || >=21.1.0"
      }
    },
    "node_modules/@faker-js/faker": {
      "version": "9.7.0",
      "resolved": "https://registry.npmjs.org/@faker-js/faker/-/faker-9.7.0.tgz",
      "integrity": "sha512-aozo5vqjCmDoXLNUJarFZx2IN/GgGaogY4TMJ6so/WLZOWpSV7fvj2dmrV6sEAnUm1O7aCrhTibjpzeDFgNqbg==",
      "funding": [
        {
          "type": "opencollective",
          "url": "https://opencollective.com/fakerjs"
        }
      ],
      "license": "MIT",
      "engines": {
        "node": ">=18.0.0",
        "npm": ">=9.0.0"
      }
    },
    "node_modules/@humanfs/core": {
      "version": "0.19.1",
      "resolved": "https://registry.npmjs.org/@humanfs/core/-/core-0.19.1.tgz",
      "integrity": "sha512-5DyQ4+1JEUzejeK1JGICcideyfUbGixgS9jNgex5nqkW+cY7WZhxBigmieN5Qnw9ZosSNVC9KQKyb+GUaGyKUA==",
      "dev": true,
      "license": "Apache-2.0",
      "engines": {
        "node": ">=18.18.0"
      }
    },
    "node_modules/@humanfs/node": {
      "version": "0.16.6",
      "resolved": "https://registry.npmjs.org/@humanfs/node/-/node-0.16.6.tgz",
      "integrity": "sha512-YuI2ZHQL78Q5HbhDiBA1X4LmYdXCKCMQIfw0pw7piHJwyREFebJUvrQN4cMssyES6x+vfUbx1CIpaQUKYdQZOw==",
      "dev": true,
      "license": "Apache-2.0",
      "dependencies": {
        "@humanfs/core": "^0.19.1",
        "@humanwhocodes/retry": "^0.3.0"
      },
      "engines": {
        "node": ">=18.18.0"
      }
    },
    "node_modules/@humanfs/node/node_modules/@humanwhocodes/retry": {
      "version": "0.3.1",
      "resolved": "https://registry.npmjs.org/@humanwhocodes/retry/-/retry-0.3.1.tgz",
      "integrity": "sha512-JBxkERygn7Bv/GbN5Rv8Ul6LVknS+5Bp6RgDC/O8gEBU/yeH5Ui5C/OlWrTb6qct7LjjfT6Re2NxB0ln0yYybA==",
      "dev": true,
      "license": "Apache-2.0",
      "engines": {
        "node": ">=18.18"
      },
      "funding": {
        "type": "github",
        "url": "https://github.com/sponsors/nzakas"
      }
    },
    "node_modules/@humanwhocodes/module-importer": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/@humanwhocodes/module-importer/-/module-importer-1.0.1.tgz",
      "integrity": "sha512-bxveV4V8v5Yb4ncFTT3rPSgZBOpCkjfK0y4oVVVJwIuDVBRMDXrPyXRL988i5ap9m9bnyEEjWfm5WkBmtffLfA==",
      "dev": true,
      "license": "Apache-2.0",
      "engines": {
        "node": ">=12.22"
      },
      "funding": {
        "type": "github",
        "url": "https://github.com/sponsors/nzakas"
      }
    },
    "node_modules/@humanwhocodes/retry": {
      "version": "0.4.2",
      "resolved": "https://registry.npmjs.org/@humanwhocodes/retry/-/retry-0.4.2.tgz",
      "integrity": "sha512-xeO57FpIu4p1Ri3Jq/EXq4ClRm86dVF2z/+kvFnyqVYRavTZmaFaUBbWCOuuTh0o/g7DSsk6kc2vrS4Vl5oPOQ==",
      "dev": true,
      "license": "Apache-2.0",
      "engines": {
        "node": ">=18.18"
      },
      "funding": {
        "type": "github",
        "url": "https://github.com/sponsors/nzakas"
      }
    },
    "node_modules/@isaacs/cliui": {
      "version": "8.0.2",
      "resolved": "https://registry.npmjs.org/@isaacs/cliui/-/cliui-8.0.2.tgz",
      "integrity": "sha512-O8jcjabXaleOG9DQ0+ARXWZBTfnP4WNAqzuiJK7ll44AmxGKv/J2M4TPjxjY3znBCfvBXFzucm1twdyFybFqEA==",
      "dev": true,
      "license": "ISC",
      "dependencies": {
        "string-width": "^5.1.2",
        "string-width-cjs": "npm:string-width@^4.2.0",
        "strip-ansi": "^7.0.1",
        "strip-ansi-cjs": "npm:strip-ansi@^6.0.1",
        "wrap-ansi": "^8.1.0",
        "wrap-ansi-cjs": "npm:wrap-ansi@^7.0.0"
      },
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@jridgewell/gen-mapping": {
      "version": "0.3.8",
      "resolved": "https://registry.npmjs.org/@jridgewell/gen-mapping/-/gen-mapping-0.3.8.tgz",
      "integrity": "sha512-imAbBGkb+ebQyxKgzv5Hu2nmROxoDOXHh80evxdoXNOrvAnVx7zimzc1Oo5h9RlfV4vPXaE2iM5pOFbvOCClWA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@jridgewell/set-array": "^1.2.1",
        "@jridgewell/sourcemap-codec": "^1.4.10",
        "@jridgewell/trace-mapping": "^0.3.24"
      },
      "engines": {
        "node": ">=6.0.0"
      }
    },
    "node_modules/@jridgewell/resolve-uri": {
      "version": "3.1.2",
      "resolved": "https://registry.npmjs.org/@jridgewell/resolve-uri/-/resolve-uri-3.1.2.tgz",
      "integrity": "sha512-bRISgCIjP20/tbWSPWMEi54QVPRZExkuD9lJL+UIxUKtwVJA8wW1Trb1jMs1RFXo1CBTNZ/5hpC9QvmKWdopKw==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=6.0.0"
      }
    },
    "node_modules/@jridgewell/set-array": {
      "version": "1.2.1",
      "resolved": "https://registry.npmjs.org/@jridgewell/set-array/-/set-array-1.2.1.tgz",
      "integrity": "sha512-R8gLRTZeyp03ymzP/6Lil/28tGeGEzhx1q2k703KGWRAI1VdvPIXdG70VJc2pAMw3NA6JKL5hhFu1sJX0Mnn/A==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=6.0.0"
      }
    },
    "node_modules/@jridgewell/sourcemap-codec": {
      "version": "1.5.0",
      "resolved": "https://registry.npmjs.org/@jridgewell/sourcemap-codec/-/sourcemap-codec-1.5.0.tgz",
      "integrity": "sha512-gv3ZRaISU3fjPAgNsriBRqGWQL6quFx04YMPW/zD8XMLsU32mhCCbfbO6KZFLjvYpCZ8zyDEgqsgf+PwPaM7GQ==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/@jridgewell/trace-mapping": {
      "version": "0.3.25",
      "resolved": "https://registry.npmjs.org/@jridgewell/trace-mapping/-/trace-mapping-0.3.25.tgz",
      "integrity": "sha512-vNk6aEwybGtawWmy/PzwnGDOjCkLWSD2wqvjGGAgOAwCGWySYXfYoxt00IJkTF+8Lb57DwOb3Aa0o9CApepiYQ==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@jridgewell/resolve-uri": "^3.1.0",
        "@jridgewell/sourcemap-codec": "^1.4.14"
      }
    },
    "node_modules/@nodelib/fs.scandir": {
      "version": "2.1.5",
      "resolved": "https://registry.npmjs.org/@nodelib/fs.scandir/-/fs.scandir-2.1.5.tgz",
      "integrity": "sha512-vq24Bq3ym5HEQm2NKCr3yXDwjc7vTsEThRDnkp2DK9p1uqLR+DHurm/NOTo0KG7HYHU7eppKZj3MyqYuMBf62g==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@nodelib/fs.stat": "2.0.5",
        "run-parallel": "^1.1.9"
      },
      "engines": {
        "node": ">= 8"
      }
    },
    "node_modules/@nodelib/fs.stat": {
      "version": "2.0.5",
      "resolved": "https://registry.npmjs.org/@nodelib/fs.stat/-/fs.stat-2.0.5.tgz",
      "integrity": "sha512-RkhPPp2zrqDAQA/2jNhnztcPAlv64XdhIp7a7454A5ovI7Bukxgt7MX7udwAu3zg1DcpPU0rz3VV1SeaqvY4+A==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">= 8"
      }
    },
    "node_modules/@nodelib/fs.walk": {
      "version": "1.2.8",
      "resolved": "https://registry.npmjs.org/@nodelib/fs.walk/-/fs.walk-1.2.8.tgz",
      "integrity": "sha512-oGB+UxlgWcgQkgwo8GcEGwemoTFt3FIO9ababBmaGwXIoBKZ+GTy0pP185beGg7Llih/NSHSV2XAs1lnznocSg==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@nodelib/fs.scandir": "2.1.5",
        "fastq": "^1.6.0"
      },
      "engines": {
        "node": ">= 8"
      }
    },
    "node_modules/@pkgjs/parseargs": {
      "version": "0.11.0",
      "resolved": "https://registry.npmjs.org/@pkgjs/parseargs/-/parseargs-0.11.0.tgz",
      "integrity": "sha512-+1VkjdD0QBLPodGrJUeqarH8VAIvQODIbwh9XpP5Syisf7YoQgsJKPNFoqqLQlu+VQ/tVSshMR6loPMn8U+dPg==",
      "dev": true,
      "license": "MIT",
      "optional": true,
      "engines": {
        "node": ">=14"
      }
    },
    "node_modules/@reduxjs/toolkit": {
      "version": "2.6.1",
      "resolved": "https://registry.npmjs.org/@reduxjs/toolkit/-/toolkit-2.6.1.tgz",
      "integrity": "sha512-SSlIqZNYhqm/oMkXbtofwZSt9lrncblzo6YcZ9zoX+zLngRBrCOjK4lNLdkNucJF58RHOWrD9txT3bT3piH7Zw==",
      "license": "MIT",
      "dependencies": {
        "immer": "^10.0.3",
        "redux": "^5.0.1",
        "redux-thunk": "^3.1.0",
        "reselect": "^5.1.0"
      },
      "peerDependencies": {
        "react": "^16.9.0 || ^17.0.0 || ^18 || ^19",
        "react-redux": "^7.2.1 || ^8.1.3 || ^9.0.0"
      },
      "peerDependenciesMeta": {
        "react": {
          "optional": true
        },
        "react-redux": {
          "optional": true
        }
      }
    },
    "node_modules/@rollup/rollup-android-arm-eabi": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-android-arm-eabi/-/rollup-android-arm-eabi-4.38.0.tgz",
      "integrity": "sha512-ldomqc4/jDZu/xpYU+aRxo3V4mGCV9HeTgUBANI3oIQMOL+SsxB+S2lxMpkFp5UamSS3XuTMQVbsS24R4J4Qjg==",
      "cpu": [
        "arm"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "android"
      ]
    },
    "node_modules/@rollup/rollup-android-arm64": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-android-arm64/-/rollup-android-arm64-4.38.0.tgz",
      "integrity": "sha512-VUsgcy4GhhT7rokwzYQP+aV9XnSLkkhlEJ0St8pbasuWO/vwphhZQxYEKUP3ayeCYLhk6gEtacRpYP/cj3GjyQ==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "android"
      ]
    },
    "node_modules/@rollup/rollup-darwin-arm64": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-darwin-arm64/-/rollup-darwin-arm64-4.38.0.tgz",
      "integrity": "sha512-buA17AYXlW9Rn091sWMq1xGUvWQFOH4N1rqUxGJtEQzhChxWjldGCCup7r/wUnaI6Au8sKXpoh0xg58a7cgcpg==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "darwin"
      ]
    },
    "node_modules/@rollup/rollup-darwin-x64": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-darwin-x64/-/rollup-darwin-x64-4.38.0.tgz",
      "integrity": "sha512-Mgcmc78AjunP1SKXl624vVBOF2bzwNWFPMP4fpOu05vS0amnLcX8gHIge7q/lDAHy3T2HeR0TqrriZDQS2Woeg==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "darwin"
      ]
    },
    "node_modules/@rollup/rollup-freebsd-arm64": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-freebsd-arm64/-/rollup-freebsd-arm64-4.38.0.tgz",
      "integrity": "sha512-zzJACgjLbQTsscxWqvrEQAEh28hqhebpRz5q/uUd1T7VTwUNZ4VIXQt5hE7ncs0GrF+s7d3S4on4TiXUY8KoQA==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "freebsd"
      ]
    },
    "node_modules/@rollup/rollup-freebsd-x64": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-freebsd-x64/-/rollup-freebsd-x64-4.38.0.tgz",
      "integrity": "sha512-hCY/KAeYMCyDpEE4pTETam0XZS4/5GXzlLgpi5f0IaPExw9kuB+PDTOTLuPtM10TlRG0U9OSmXJ+Wq9J39LvAg==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "freebsd"
      ]
    },
    "node_modules/@rollup/rollup-linux-arm-gnueabihf": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-arm-gnueabihf/-/rollup-linux-arm-gnueabihf-4.38.0.tgz",
      "integrity": "sha512-mimPH43mHl4JdOTD7bUMFhBdrg6f9HzMTOEnzRmXbOZqjijCw8LA5z8uL6LCjxSa67H2xiLFvvO67PT05PRKGg==",
      "cpu": [
        "arm"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-linux-arm-musleabihf": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-arm-musleabihf/-/rollup-linux-arm-musleabihf-4.38.0.tgz",
      "integrity": "sha512-tPiJtiOoNuIH8XGG8sWoMMkAMm98PUwlriOFCCbZGc9WCax+GLeVRhmaxjJtz6WxrPKACgrwoZ5ia/uapq3ZVg==",
      "cpu": [
        "arm"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-linux-arm64-gnu": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-arm64-gnu/-/rollup-linux-arm64-gnu-4.38.0.tgz",
      "integrity": "sha512-wZco59rIVuB0tjQS0CSHTTUcEde+pXQWugZVxWaQFdQQ1VYub/sTrNdY76D1MKdN2NB48JDuGABP6o6fqos8mA==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-linux-arm64-musl": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-arm64-musl/-/rollup-linux-arm64-musl-4.38.0.tgz",
      "integrity": "sha512-fQgqwKmW0REM4LomQ+87PP8w8xvU9LZfeLBKybeli+0yHT7VKILINzFEuggvnV9M3x1Ed4gUBmGUzCo/ikmFbQ==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-linux-loongarch64-gnu": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-loongarch64-gnu/-/rollup-linux-loongarch64-gnu-4.38.0.tgz",
      "integrity": "sha512-hz5oqQLXTB3SbXpfkKHKXLdIp02/w3M+ajp8p4yWOWwQRtHWiEOCKtc9U+YXahrwdk+3qHdFMDWR5k+4dIlddg==",
      "cpu": [
        "loong64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-linux-powerpc64le-gnu": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-powerpc64le-gnu/-/rollup-linux-powerpc64le-gnu-4.38.0.tgz",
      "integrity": "sha512-NXqygK/dTSibQ+0pzxsL3r4Xl8oPqVoWbZV9niqOnIHV/J92fe65pOir0xjkUZDRSPyFRvu+4YOpJF9BZHQImw==",
      "cpu": [
        "ppc64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-linux-riscv64-gnu": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-riscv64-gnu/-/rollup-linux-riscv64-gnu-4.38.0.tgz",
      "integrity": "sha512-GEAIabR1uFyvf/jW/5jfu8gjM06/4kZ1W+j1nWTSSB3w6moZEBm7iBtzwQ3a1Pxos2F7Gz+58aVEnZHU295QTg==",
      "cpu": [
        "riscv64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-linux-riscv64-musl": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-riscv64-musl/-/rollup-linux-riscv64-musl-4.38.0.tgz",
      "integrity": "sha512-9EYTX+Gus2EGPbfs+fh7l95wVADtSQyYw4DfSBcYdUEAmP2lqSZY0Y17yX/3m5VKGGJ4UmIH5LHLkMJft3bYoA==",
      "cpu": [
        "riscv64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-linux-s390x-gnu": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-s390x-gnu/-/rollup-linux-s390x-gnu-4.38.0.tgz",
      "integrity": "sha512-Mpp6+Z5VhB9VDk7RwZXoG2qMdERm3Jw07RNlXHE0bOnEeX+l7Fy4bg+NxfyN15ruuY3/7Vrbpm75J9QHFqj5+Q==",
      "cpu": [
        "s390x"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-linux-x64-gnu": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-x64-gnu/-/rollup-linux-x64-gnu-4.38.0.tgz",
      "integrity": "sha512-vPvNgFlZRAgO7rwncMeE0+8c4Hmc+qixnp00/Uv3ht2x7KYrJ6ERVd3/R0nUtlE6/hu7/HiiNHJ/rP6knRFt1w==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-linux-x64-musl": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-x64-musl/-/rollup-linux-x64-musl-4.38.0.tgz",
      "integrity": "sha512-q5Zv+goWvQUGCaL7fU8NuTw8aydIL/C9abAVGCzRReuj5h30TPx4LumBtAidrVOtXnlB+RZkBtExMsfqkMfb8g==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-win32-arm64-msvc": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-win32-arm64-msvc/-/rollup-win32-arm64-msvc-4.38.0.tgz",
      "integrity": "sha512-u/Jbm1BU89Vftqyqbmxdq14nBaQjQX1HhmsdBWqSdGClNaKwhjsg5TpW+5Ibs1mb8Es9wJiMdl86BcmtUVXNZg==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "win32"
      ]
    },
    "node_modules/@rollup/rollup-win32-ia32-msvc": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-win32-ia32-msvc/-/rollup-win32-ia32-msvc-4.38.0.tgz",
      "integrity": "sha512-mqu4PzTrlpNHHbu5qleGvXJoGgHpChBlrBx/mEhTPpnAL1ZAYFlvHD7rLK839LLKQzqEQMFJfGrrOHItN4ZQqA==",
      "cpu": [
        "ia32"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "win32"
      ]
    },
    "node_modules/@rollup/rollup-win32-x64-msvc": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-win32-x64-msvc/-/rollup-win32-x64-msvc-4.38.0.tgz",
      "integrity": "sha512-jjqy3uWlecfB98Psxb5cD6Fny9Fupv9LrDSPTQZUROqjvZmcCqNu4UMl7qqhlUUGpwiAkotj6GYu4SZdcr/nLw==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "win32"
      ]
    },
    "node_modules/@types/babel__core": {
      "version": "7.20.5",
      "resolved": "https://registry.npmjs.org/@types/babel__core/-/babel__core-7.20.5.tgz",
      "integrity": "sha512-qoQprZvz5wQFJwMDqeseRXWv3rqMvhgpbXFfVyWhbx9X47POIA6i/+dXefEmZKoAgOaTdaIgNSMqMIU61yRyzA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@babel/parser": "^7.20.7",
        "@babel/types": "^7.20.7",
        "@types/babel__generator": "*",
        "@types/babel__template": "*",
        "@types/babel__traverse": "*"
      }
    },
    "node_modules/@types/babel__generator": {
      "version": "7.6.8",
      "resolved": "https://registry.npmjs.org/@types/babel__generator/-/babel__generator-7.6.8.tgz",
      "integrity": "sha512-ASsj+tpEDsEiFr1arWrlN6V3mdfjRMZt6LtK/Vp/kreFLnr5QH5+DhvD5nINYZXzwJvXeGq+05iUXcAzVrqWtw==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@babel/types": "^7.0.0"
      }
    },
    "node_modules/@types/babel__template": {
      "version": "7.4.4",
      "resolved": "https://registry.npmjs.org/@types/babel__template/-/babel__template-7.4.4.tgz",
      "integrity": "sha512-h/NUaSyG5EyxBIp8YRxo4RMe2/qQgvyowRwVMzhYhBCONbW8PUsg4lkFMrhgZhUe5z3L3MiLDuvyJ/CaPa2A8A==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@babel/parser": "^7.1.0",
        "@babel/types": "^7.0.0"
      }
    },
    "node_modules/@types/babel__traverse": {
      "version": "7.20.7",
      "resolved": "https://registry.npmjs.org/@types/babel__traverse/-/babel__traverse-7.20.7.tgz",
      "integrity": "sha512-dkO5fhS7+/oos4ciWxyEyjWe48zmG6wbCheo/G2ZnHx4fs3EU6YC6UM8rk56gAjNJ9P3MTH2jo5jb92/K6wbng==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@babel/types": "^7.20.7"
      }
    },
    "node_modules/@types/cookie": {
      "version": "0.6.0",
      "resolved": "https://registry.npmjs.org/@types/cookie/-/cookie-0.6.0.tgz",
      "integrity": "sha512-4Kh9a6B2bQciAhf7FSuMRRkUWecJgJu9nPnx3yzpsfXX/c50REIqpHY4C82bXP90qrLtXtkDxTZosYO3UpOwlA==",
      "license": "MIT"
    },
    "node_modules/@types/estree": {
      "version": "1.0.7",
      "resolved": "https://registry.npmjs.org/@types/estree/-/estree-1.0.7.tgz",
      "integrity": "sha512-w28IoSUCJpidD/TGviZwwMJckNESJZXFu7NBZ5YJ4mEUnNraUn9Pm8HSZm/jDF1pDWYKspWE7oVphigUPRakIQ==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/@types/json-schema": {
      "version": "7.0.15",
      "resolved": "https://registry.npmjs.org/@types/json-schema/-/json-schema-7.0.15.tgz",
      "integrity": "sha512-5+fP8P8MFNC+AyZCDxrB2pkZFPGzqQWUzpSeuuVLvm8VMcorNYavBqoFcxK8bQz4Qsbn4oUEEem4wDLfcysGHA==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/@types/react": {
      "version": "19.0.12",
      "resolved": "https://registry.npmjs.org/@types/react/-/react-19.0.12.tgz",
      "integrity": "sha512-V6Ar115dBDrjbtXSrS+/Oruobc+qVbbUxDFC1RSbRqLt5SYvxxyIDrSC85RWml54g+jfNeEMZhEj7wW07ONQhA==",
      "devOptional": true,
      "license": "MIT",
      "dependencies": {
        "csstype": "^3.0.2"
      }
    },
    "node_modules/@types/react-dom": {
      "version": "19.0.4",
      "resolved": "https://registry.npmjs.org/@types/react-dom/-/react-dom-19.0.4.tgz",
      "integrity": "sha512-4fSQ8vWFkg+TGhePfUzVmat3eC14TXYSsiiDSLI0dVLsrm9gZFABjPy/Qu6TKgl1tq1Bu1yDsuQgY3A3DOjCcg==",
      "dev": true,
      "license": "MIT",
      "peerDependencies": {
        "@types/react": "^19.0.0"
      }
    },
    "node_modules/@types/trusted-types": {
      "version": "2.0.7",
      "resolved": "https://registry.npmjs.org/@types/trusted-types/-/trusted-types-2.0.7.tgz",
      "integrity": "sha512-ScaPdn1dQczgbl0QFTeTOmVHFULt394XJgOQNoyVhZ6r2vLnMLJfBPd53SB52T/3G36VI1/g2MZaX0cwDuXsfw==",
      "license": "MIT",
      "optional": true
    },
    "node_modules/@types/use-sync-external-store": {
      "version": "0.0.6",
      "resolved": "https://registry.npmjs.org/@types/use-sync-external-store/-/use-sync-external-store-0.0.6.tgz",
      "integrity": "sha512-zFDAD+tlpf2r4asuHEj0XH6pY6i0g5NeAHPn+15wk3BV6JA69eERFXC1gyGThDkVa1zCyKr5jox1+2LbV/AMLg==",
      "license": "MIT"
    },
    "node_modules/@vitejs/plugin-react": {
      "version": "4.3.4",
      "resolved": "https://registry.npmjs.org/@vitejs/plugin-react/-/plugin-react-4.3.4.tgz",
      "integrity": "sha512-SCCPBJtYLdE8PX/7ZQAs1QAZ8Jqwih+0VBLum1EGqmCCQal+MIUqLCzj3ZUy8ufbC0cAM4LRlSTm7IQJwWT4ug==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@babel/core": "^7.26.0",
        "@babel/plugin-transform-react-jsx-self": "^7.25.9",
        "@babel/plugin-transform-react-jsx-source": "^7.25.9",
        "@types/babel__core": "^7.20.5",
        "react-refresh": "^0.14.2"
      },
      "engines": {
        "node": "^14.18.0 || >=16.0.0"
      },
      "peerDependencies": {
        "vite": "^4.2.0 || ^5.0.0 || ^6.0.0"
      }
    },
    "node_modules/acorn": {
      "version": "8.14.1",
      "resolved": "https://registry.npmjs.org/acorn/-/acorn-8.14.1.tgz",
      "integrity": "sha512-OvQ/2pUDKmgfCg++xsTX1wGxfTaszcHVcTctW4UJB4hibJx2HXxxO5UmVgyjMa+ZDsiaf5wWLXYpRWMmBI0QHg==",
      "dev": true,
      "license": "MIT",
      "bin": {
        "acorn": "bin/acorn"
      },
      "engines": {
        "node": ">=0.4.0"
      }
    },
    "node_modules/acorn-jsx": {
      "version": "5.3.2",
      "resolved": "https://registry.npmjs.org/acorn-jsx/-/acorn-jsx-5.3.2.tgz",
      "integrity": "sha512-rq9s+JNhf0IChjtDXxllJ7g41oZk5SlXtp0LHwyA5cejwn7vKmKp4pPri6YEePv2PU65sAsegbXtIinmDFDXgQ==",
      "dev": true,
      "license": "MIT",
      "peerDependencies": {
        "acorn": "^6.0.0 || ^7.0.0 || ^8.0.0"
      }
    },
    "node_modules/ajv": {
      "version": "6.12.6",
      "resolved": "https://registry.npmjs.org/ajv/-/ajv-6.12.6.tgz",
      "integrity": "sha512-j3fVLgvTo527anyYyJOGTYJbG+vnnQYvE0m5mmkc1TK+nxAppkCLMIL0aZ4dblVCNoGShhm+kzE4ZUykBoMg4g==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "fast-deep-equal": "^3.1.1",
        "fast-json-stable-stringify": "^2.0.0",
        "json-schema-traverse": "^0.4.1",
        "uri-js": "^4.2.2"
      },
      "funding": {
        "type": "github",
        "url": "https://github.com/sponsors/epoberezkin"
      }
    },
    "node_modules/ansi-regex": {
      "version": "6.1.0",
      "resolved": "https://registry.npmjs.org/ansi-regex/-/ansi-regex-6.1.0.tgz",
      "integrity": "sha512-7HSX4QQb4CspciLpVFwyRe79O3xsIZDDLER21kERQ71oaPodF8jL725AgJMFAYbooIqolJoRLuM81SpeUkpkvA==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-regex?sponsor=1"
      }
    },
    "node_modules/ansi-styles": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
      "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "color-convert": "^2.0.1"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-styles?sponsor=1"
      }
    },
    "node_modules/any-promise": {
      "version": "1.3.0",
      "resolved": "https://registry.npmjs.org/any-promise/-/any-promise-1.3.0.tgz",
      "integrity": "sha512-7UvmKalWRt1wgjL1RrGxoSJW/0QZFIegpeGvZG9kjp8vrRu55XTHbwnqq2GpXm9uLbcuhxm3IqX9OB4MZR1b2A==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/anymatch": {
      "version": "3.1.3",
      "resolved": "https://registry.npmjs.org/anymatch/-/anymatch-3.1.3.tgz",
      "integrity": "sha512-KMReFUr0B4t+D+OBkjR3KYqvocp2XaSzO55UcB6mgQMd3KbcE+mWTyvVV7D/zsdEbNnV6acZUutkiHQXvTr1Rw==",
      "dev": true,
      "license": "ISC",
      "dependencies": {
        "normalize-path": "^3.0.0",
        "picomatch": "^2.0.4"
      },
      "engines": {
        "node": ">= 8"
      }
    },
    "node_modules/arg": {
      "version": "5.0.2",
      "resolved": "https://registry.npmjs.org/arg/-/arg-5.0.2.tgz",
      "integrity": "sha512-PYjyFOLKQ9y57JvQ6QLo8dAgNqswh8M1RMJYdQduT6xbWSgK36P/Z/v+p888pM69jMMfS8Xd8F6I1kQ/I9HUGg==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/argon2-browser": {
      "version": "1.18.0",
      "resolved": "https://registry.npmjs.org/argon2-browser/-/argon2-browser-1.18.0.tgz",
      "integrity": "sha512-ImVAGIItnFnvET1exhsQB7apRztcoC5TnlSqernMJDUjbc/DLq3UEYeXFrLPrlaIl8cVfwnXb6wX2KpFf2zxHw==",
      "license": "MIT"
    },
    "node_modules/argparse": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/argparse/-/argparse-2.0.1.tgz",
      "integrity": "sha512-8+9WqebbFzpX9OR+Wa6O29asIogeRMzcGtAINdpMHHyAg10f05aSFVBbcEqGf/PXw1EjAZ+q2/bEBg3DvurK3Q==",
      "dev": true,
      "license": "Python-2.0"
    },
    "node_modules/asynckit": {
      "version": "0.4.0",
      "resolved": "https://registry.npmjs.org/asynckit/-/asynckit-0.4.0.tgz",
      "integrity": "sha512-Oei9OH4tRh0YqU3GxhX79dM/mwVgvbZJaSNaRk+bshkj0S5cfHcgYakreBjrHwatXKbz+IoIdYLxrKim2MjW0Q==",
      "license": "MIT"
    },
    "node_modules/autoprefixer": {
      "version": "10.4.21",
      "resolved": "https://registry.npmjs.org/autoprefixer/-/autoprefixer-10.4.21.tgz",
      "integrity": "sha512-O+A6LWV5LDHSJD3LjHYoNi4VLsj/Whi7k6zG12xTYaU4cQ8oxQGckXNX8cRHK5yOZ/ppVHe0ZBXGzSV9jXdVbQ==",
      "dev": true,
      "funding": [
        {
          "type": "opencollective",
          "url": "https://opencollective.com/postcss/"
        },
        {
          "type": "tidelift",
          "url": "https://tidelift.com/funding/github/npm/autoprefixer"
        },
        {
          "type": "github",
          "url": "https://github.com/sponsors/ai"
        }
      ],
      "license": "MIT",
      "dependencies": {
        "browserslist": "^4.24.4",
        "caniuse-lite": "^1.0.30001702",
        "fraction.js": "^4.3.7",
        "normalize-range": "^0.1.2",
        "picocolors": "^1.1.1",
        "postcss-value-parser": "^4.2.0"
      },
      "bin": {
        "autoprefixer": "bin/autoprefixer"
      },
      "engines": {
        "node": "^10 || ^12 || >=14"
      },
      "peerDependencies": {
        "postcss": "^8.1.0"
      }
    },
    "node_modules/axios": {
      "version": "1.8.4",
      "resolved": "https://registry.npmjs.org/axios/-/axios-1.8.4.tgz",
      "integrity": "sha512-eBSYY4Y68NNlHbHBMdeDmKNtDgXWhQsJcGqzO3iLUM0GraQFSS9cVgPX5I9b3lbdFKyYoAEGAZF1DwhTaljNAw==",
      "license": "MIT",
      "dependencies": {
        "follow-redirects": "^1.15.6",
        "form-data": "^4.0.0",
        "proxy-from-env": "^1.1.0"
      }
    },
    "node_modules/balanced-match": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/balanced-match/-/balanced-match-1.0.2.tgz",
      "integrity": "sha512-3oSeUO0TMV67hN1AmbXsK4yaqU7tjiHlbxRDZOpH0KW9+CeX4bRAaX0Anxt0tx2MrpRpWwQaPwIlISEJhYU5Pw==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/binary-extensions": {
      "version": "2.3.0",
      "resolved": "https://registry.npmjs.org/binary-extensions/-/binary-extensions-2.3.0.tgz",
      "integrity": "sha512-Ceh+7ox5qe7LJuLHoY0feh3pHuUDHAcRUeyL2VYghZwfpkNIy/+8Ocg0a3UuSoYzavmylwuLWQOf3hl0jjMMIw==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/brace-expansion": {
      "version": "1.1.11",
      "resolved": "https://registry.npmjs.org/brace-expansion/-/brace-expansion-1.1.11.tgz",
      "integrity": "sha512-iCuPHDFgrHX7H2vEI/5xpz07zSHB00TpugqhmYtVmMO6518mCuRMoOYFldEBl0g187ufozdaHgWKcYFb61qGiA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "balanced-match": "^1.0.0",
        "concat-map": "0.0.1"
      }
    },
    "node_modules/braces": {
      "version": "3.0.3",
      "resolved": "https://registry.npmjs.org/braces/-/braces-3.0.3.tgz",
      "integrity": "sha512-yQbXgO/OSZVD2IsiLlro+7Hf6Q18EJrKSEsdoMzKePKXct3gvD8oLcOQdIzGupr5Fj+EDe8gO/lxc1BzfMpxvA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "fill-range": "^7.1.1"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/browserslist": {
      "version": "4.24.4",
      "resolved": "https://registry.npmjs.org/browserslist/-/browserslist-4.24.4.tgz",
      "integrity": "sha512-KDi1Ny1gSePi1vm0q4oxSF8b4DR44GF4BbmS2YdhPLOEqd8pDviZOGH/GsmRwoWJ2+5Lr085X7naowMwKHDG1A==",
      "dev": true,
      "funding": [
        {
          "type": "opencollective",
          "url": "https://opencollective.com/browserslist"
        },
        {
          "type": "tidelift",
          "url": "https://tidelift.com/funding/github/npm/browserslist"
        },
        {
          "type": "github",
          "url": "https://github.com/sponsors/ai"
        }
      ],
      "license": "MIT",
      "dependencies": {
        "caniuse-lite": "^1.0.30001688",
        "electron-to-chromium": "^1.5.73",
        "node-releases": "^2.0.19",
        "update-browserslist-db": "^1.1.1"
      },
      "bin": {
        "browserslist": "cli.js"
      },
      "engines": {
        "node": "^6 || ^7 || ^8 || ^9 || ^10 || ^11 || ^12 || >=13.7"
      }
    },
    "node_modules/call-bind-apply-helpers": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/call-bind-apply-helpers/-/call-bind-apply-helpers-1.0.2.tgz",
      "integrity": "sha512-Sp1ablJ0ivDkSzjcaJdxEunN5/XvksFJ2sMBFfq6x0ryhQV/2b/KwFe21cMpmHtPOSij8K99/wSfoEuTObmuMQ==",
      "license": "MIT",
      "dependencies": {
        "es-errors": "^1.3.0",
        "function-bind": "^1.1.2"
      },
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/callsites": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/callsites/-/callsites-3.1.0.tgz",
      "integrity": "sha512-P8BjAsXvZS+VIDUI11hHCQEv74YT67YUi5JJFNWIqL235sBmjX4+qx9Muvls5ivyNENctx46xQLQ3aTuE7ssaQ==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/camelcase-css": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/camelcase-css/-/camelcase-css-2.0.1.tgz",
      "integrity": "sha512-QOSvevhslijgYwRx6Rv7zKdMF8lbRmx+uQGx2+vDc+KI/eBnsy9kit5aj23AgGu3pa4t9AgwbnXWqS+iOY+2aA==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">= 6"
      }
    },
    "node_modules/caniuse-lite": {
      "version": "1.0.30001707",
      "resolved": "https://registry.npmjs.org/caniuse-lite/-/caniuse-lite-1.0.30001707.tgz",
      "integrity": "sha512-3qtRjw/HQSMlDWf+X79N206fepf4SOOU6SQLMaq/0KkZLmSjPxAkBOQQ+FxbHKfHmYLZFfdWsO3KA90ceHPSnw==",
      "dev": true,
      "funding": [
        {
          "type": "opencollective",
          "url": "https://opencollective.com/browserslist"
        },
        {
          "type": "tidelift",
          "url": "https://tidelift.com/funding/github/npm/caniuse-lite"
        },
        {
          "type": "github",
          "url": "https://github.com/sponsors/ai"
        }
      ],
      "license": "CC-BY-4.0"
    },
    "node_modules/chalk": {
      "version": "4.1.2",
      "resolved": "https://registry.npmjs.org/chalk/-/chalk-4.1.2.tgz",
      "integrity": "sha512-oKnbhFyRIXpUuez8iBMmyEa4nbj4IOQyuhc/wy9kY7/WVPcwIO9VA668Pu8RkO7+0G76SLROeyw9CpQ061i4mA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "ansi-styles": "^4.1.0",
        "supports-color": "^7.1.0"
      },
      "engines": {
        "node": ">=10"
      },
      "funding": {
        "url": "https://github.com/chalk/chalk?sponsor=1"
      }
    },
    "node_modules/chokidar": {
      "version": "3.6.0",
      "resolved": "https://registry.npmjs.org/chokidar/-/chokidar-3.6.0.tgz",
      "integrity": "sha512-7VT13fmjotKpGipCW9JEQAusEPE+Ei8nl6/g4FBAmIm0GOOLMua9NDDo/DWp0ZAxCr3cPq5ZpBqmPAQgDda2Pw==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "anymatch": "~3.1.2",
        "braces": "~3.0.2",
        "glob-parent": "~5.1.2",
        "is-binary-path": "~2.1.0",
        "is-glob": "~4.0.1",
        "normalize-path": "~3.0.0",
        "readdirp": "~3.6.0"
      },
      "engines": {
        "node": ">= 8.10.0"
      },
      "funding": {
        "url": "https://paulmillr.com/funding/"
      },
      "optionalDependencies": {
        "fsevents": "~2.3.2"
      }
    },
    "node_modules/chokidar/node_modules/glob-parent": {
      "version": "5.1.2",
      "resolved": "https://registry.npmjs.org/glob-parent/-/glob-parent-5.1.2.tgz",
      "integrity": "sha512-AOIgSQCepiJYwP3ARnGx+5VnTu2HBYdzbGP45eLw1vr3zB3vZLeyed1sC9hnbcOc9/SrMyM5RPQrkGz4aS9Zow==",
      "dev": true,
      "license": "ISC",
      "dependencies": {
        "is-glob": "^4.0.1"
      },
      "engines": {
        "node": ">= 6"
      }
    },
    "node_modules/clsx": {
      "version": "2.1.1",
      "resolved": "https://registry.npmjs.org/clsx/-/clsx-2.1.1.tgz",
      "integrity": "sha512-eYm0QWBtUrBWZWG0d386OGAw16Z995PiOVo2B7bjWSbHedGl5e0ZWaq65kOGgUSNesEIDkB9ISbTg/JK9dhCZA==",
      "license": "MIT",
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/color-convert": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
      "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "color-name": "~1.1.4"
      },
      "engines": {
        "node": ">=7.0.0"
      }
    },
    "node_modules/color-name": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
      "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/combined-stream": {
      "version": "1.0.8",
      "resolved": "https://registry.npmjs.org/combined-stream/-/combined-stream-1.0.8.tgz",
      "integrity": "sha512-FQN4MRfuJeHf7cBbBMJFXhKSDq+2kAArBlmRBvcvFE5BB1HZKXtSFASDhdlz9zOYwxh8lDdnvmMOe/+5cdoEdg==",
      "license": "MIT",
      "dependencies": {
        "delayed-stream": "~1.0.0"
      },
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/commander": {
      "version": "4.1.1",
      "resolved": "https://registry.npmjs.org/commander/-/commander-4.1.1.tgz",
      "integrity": "sha512-NOKm8xhkzAjzFx8B2v5OAHT+u5pRQc2UCa2Vq9jYL/31o2wi9mxBA7LIFs3sV5VSC49z6pEhfbMULvShKj26WA==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">= 6"
      }
    },
    "node_modules/concat-map": {
      "version": "0.0.1",
      "resolved": "https://registry.npmjs.org/concat-map/-/concat-map-0.0.1.tgz",
      "integrity": "sha512-/Srv4dswyQNBfohGpz9o6Yb3Gz3SrUDqBH5rTuhGR7ahtlbYKnVxw2bCFMRljaA7EXHaXZ8wsHdodFvbkhKmqg==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/convert-source-map": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/convert-source-map/-/convert-source-map-2.0.0.tgz",
      "integrity": "sha512-Kvp459HrV2FEJ1CAsi1Ku+MY3kasH19TFykTz2xWmMeq6bk2NU3XXvfJ+Q61m0xktWwt+1HSYf3JZsTms3aRJg==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/cookie": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/cookie/-/cookie-1.0.2.tgz",
      "integrity": "sha512-9Kr/j4O16ISv8zBBhJoi4bXOYNTkFLOqSL3UDB0njXxCXNezjeyVrJyGOWtgfs/q2km1gwBcfH8q1yEGoMYunA==",
      "license": "MIT",
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/cross-spawn": {
      "version": "7.0.6",
      "resolved": "https://registry.npmjs.org/cross-spawn/-/cross-spawn-7.0.6.tgz",
      "integrity": "sha512-uV2QOWP2nWzsy2aMp8aRibhi9dlzF5Hgh5SHaB9OiTGEyDTiJJyx0uy51QXdyWbtAHNua4XJzUKca3OzKUd3vA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "path-key": "^3.1.0",
        "shebang-command": "^2.0.0",
        "which": "^2.0.1"
      },
      "engines": {
        "node": ">= 8"
      }
    },
    "node_modules/crypto-js": {
      "version": "4.2.0",
      "resolved": "https://registry.npmjs.org/crypto-js/-/crypto-js-4.2.0.tgz",
      "integrity": "sha512-KALDyEYgpY+Rlob/iriUtjV6d5Eq+Y191A5g4UqLAi8CyGP9N1+FdVbkc1SxKc2r4YAYqG8JzO2KGL+AizD70Q==",
      "license": "MIT"
    },
    "node_modules/cssesc": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/cssesc/-/cssesc-3.0.0.tgz",
      "integrity": "sha512-/Tb/JcjK111nNScGob5MNtsntNM1aCNUDipB/TkwZFhyDrrE47SOx/18wF2bbjgc3ZzCSKW1T5nt5EbFoAz/Vg==",
      "dev": true,
      "license": "MIT",
      "bin": {
        "cssesc": "bin/cssesc"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/csstype": {
      "version": "3.1.3",
      "resolved": "https://registry.npmjs.org/csstype/-/csstype-3.1.3.tgz",
      "integrity": "sha512-M1uQkMl8rQK/szD0LNhtqxIPLpimGm8sOBwU7lLnCpSbTyY3yeU1Vc7l4KT5zT4s/yOxHH5O7tIuuLOCnLADRw==",
      "devOptional": true,
      "license": "MIT"
    },
    "node_modules/debug": {
      "version": "4.4.0",
      "resolved": "https://registry.npmjs.org/debug/-/debug-4.4.0.tgz",
      "integrity": "sha512-6WTZ/IxCY/T6BALoZHaE4ctp9xm+Z5kY/pzYaCHRFeyVhojxlrm+46y68HA6hr0TcwEssoxNiDEUJQjfPZ/RYA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "ms": "^2.1.3"
      },
      "engines": {
        "node": ">=6.0"
      },
      "peerDependenciesMeta": {
        "supports-color": {
          "optional": true
        }
      }
    },
    "node_modules/deep-is": {
      "version": "0.1.4",
      "resolved": "https://registry.npmjs.org/deep-is/-/deep-is-0.1.4.tgz",
      "integrity": "sha512-oIPzksmTg4/MriiaYGO+okXDT7ztn/w3Eptv/+gSIdMdKsJo0u4CfYNFJPy+4SKMuCqGw2wxnA+URMg3t8a/bQ==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/delayed-stream": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/delayed-stream/-/delayed-stream-1.0.0.tgz",
      "integrity": "sha512-ZySD7Nf91aLB0RxL4KGrKHBXl7Eds1DAmEdcoVawXnLD7SDhpNgtuII2aAkg7a7QS41jxPSZ17p4VdGnMHk3MQ==",
      "license": "MIT",
      "engines": {
        "node": ">=0.4.0"
      }
    },
    "node_modules/didyoumean": {
      "version": "1.2.2",
      "resolved": "https://registry.npmjs.org/didyoumean/-/didyoumean-1.2.2.tgz",
      "integrity": "sha512-gxtyfqMg7GKyhQmb056K7M3xszy/myH8w+B4RT+QXBQsvAOdc3XymqDDPHx1BgPgsdAA5SIifona89YtRATDzw==",
      "dev": true,
      "license": "Apache-2.0"
    },
    "node_modules/dlv": {
      "version": "1.1.3",
      "resolved": "https://registry.npmjs.org/dlv/-/dlv-1.1.3.tgz",
      "integrity": "sha512-+HlytyjlPKnIG8XuRG8WvmBP8xs8P71y+SKKS6ZXWoEgLuePxtDoUEiH7WkdePWrQ5JBpE6aoVqfZfJUQkjXwA==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/dompurify": {
      "version": "3.2.5",
      "resolved": "https://registry.npmjs.org/dompurify/-/dompurify-3.2.5.tgz",
      "integrity": "sha512-mLPd29uoRe9HpvwP2TxClGQBzGXeEC/we/q+bFlmPPmj2p2Ugl3r6ATu/UU1v77DXNcehiBg9zsr1dREyA/dJQ==",
      "license": "(MPL-2.0 OR Apache-2.0)",
      "optionalDependencies": {
        "@types/trusted-types": "^2.0.7"
      }
    },
    "node_modules/dunder-proto": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/dunder-proto/-/dunder-proto-1.0.1.tgz",
      "integrity": "sha512-KIN/nDJBQRcXw0MLVhZE9iQHmG68qAVIBg9CqmUYjmQIhgij9U5MFvrqkUL5FbtyyzZuOeOt0zdeRe4UY7ct+A==",
      "license": "MIT",
      "dependencies": {
        "call-bind-apply-helpers": "^1.0.1",
        "es-errors": "^1.3.0",
        "gopd": "^1.2.0"
      },
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/eastasianwidth": {
      "version": "0.2.0",
      "resolved": "https://registry.npmjs.org/eastasianwidth/-/eastasianwidth-0.2.0.tgz",
      "integrity": "sha512-I88TYZWc9XiYHRQ4/3c5rjjfgkjhLyW2luGIheGERbNQ6OY7yTybanSpDXZa8y7VUP9YmDcYa+eyq4ca7iLqWA==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/electron-to-chromium": {
      "version": "1.5.128",
      "resolved": "https://registry.npmjs.org/electron-to-chromium/-/electron-to-chromium-1.5.128.tgz",
      "integrity": "sha512-bo1A4HH/NS522Ws0QNFIzyPcyUUNV/yyy70Ho1xqfGYzPUme2F/xr4tlEOuM6/A538U1vDA7a4XfCd1CKRegKQ==",
      "dev": true,
      "license": "ISC"
    },
    "node_modules/emoji-regex": {
      "version": "9.2.2",
      "resolved": "https://registry.npmjs.org/emoji-regex/-/emoji-regex-9.2.2.tgz",
      "integrity": "sha512-L18DaJsXSUk2+42pv8mLs5jJT2hqFkFE4j21wOmgbUqsZ2hL72NsUU785g9RXgo3s0ZNgVl42TiHp3ZtOv/Vyg==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/es-define-property": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/es-define-property/-/es-define-property-1.0.1.tgz",
      "integrity": "sha512-e3nRfgfUZ4rNGL232gUgX06QNyyez04KdjFrF+LTRoOXmrOgFKDg4BCdsjW8EnT69eqdYGmRpJwiPVYNrCaW3g==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/es-errors": {
      "version": "1.3.0",
      "resolved": "https://registry.npmjs.org/es-errors/-/es-errors-1.3.0.tgz",
      "integrity": "sha512-Zf5H2Kxt2xjTvbJvP2ZWLEICxA6j+hAmMzIlypy4xcBg1vKVnx89Wy0GbS+kf5cwCVFFzdCFh2XSCFNULS6csw==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/es-object-atoms": {
      "version": "1.1.1",
      "resolved": "https://registry.npmjs.org/es-object-atoms/-/es-object-atoms-1.1.1.tgz",
      "integrity": "sha512-FGgH2h8zKNim9ljj7dankFPcICIK9Cp5bm+c2gQSYePhpaG5+esrLODihIorn+Pe6FGJzWhXQotPv73jTaldXA==",
      "license": "MIT",
      "dependencies": {
        "es-errors": "^1.3.0"
      },
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/es-set-tostringtag": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/es-set-tostringtag/-/es-set-tostringtag-2.1.0.tgz",
      "integrity": "sha512-j6vWzfrGVfyXxge+O0x5sh6cvxAog0a/4Rdd2K36zCMV5eJ+/+tOAngRO8cODMNWbVRdVlmGZQL2YS3yR8bIUA==",
      "license": "MIT",
      "dependencies": {
        "es-errors": "^1.3.0",
        "get-intrinsic": "^1.2.6",
        "has-tostringtag": "^1.0.2",
        "hasown": "^2.0.2"
      },
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/esbuild": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/esbuild/-/esbuild-0.25.2.tgz",
      "integrity": "sha512-16854zccKPnC+toMywC+uKNeYSv+/eXkevRAfwRD/G9Cleq66m8XFIrigkbvauLLlCfDL45Q2cWegSg53gGBnQ==",
      "dev": true,
      "hasInstallScript": true,
      "license": "MIT",
      "bin": {
        "esbuild": "bin/esbuild"
      },
      "engines": {
        "node": ">=18"
      },
      "optionalDependencies": {
        "@esbuild/aix-ppc64": "0.25.2",
        "@esbuild/android-arm": "0.25.2",
        "@esbuild/android-arm64": "0.25.2",
        "@esbuild/android-x64": "0.25.2",
        "@esbuild/darwin-arm64": "0.25.2",
        "@esbuild/darwin-x64": "0.25.2",
        "@esbuild/freebsd-arm64": "0.25.2",
        "@esbuild/freebsd-x64": "0.25.2",
        "@esbuild/linux-arm": "0.25.2",
        "@esbuild/linux-arm64": "0.25.2",
        "@esbuild/linux-ia32": "0.25.2",
        "@esbuild/linux-loong64": "0.25.2",
        "@esbuild/linux-mips64el": "0.25.2",
        "@esbuild/linux-ppc64": "0.25.2",
        "@esbuild/linux-riscv64": "0.25.2",
        "@esbuild/linux-s390x": "0.25.2",
        "@esbuild/linux-x64": "0.25.2",
        "@esbuild/netbsd-arm64": "0.25.2",
        "@esbuild/netbsd-x64": "0.25.2",
        "@esbuild/openbsd-arm64": "0.25.2",
        "@esbuild/openbsd-x64": "0.25.2",
        "@esbuild/sunos-x64": "0.25.2",
        "@esbuild/win32-arm64": "0.25.2",
        "@esbuild/win32-ia32": "0.25.2",
        "@esbuild/win32-x64": "0.25.2"
      }
    },
    "node_modules/escalade": {
      "version": "3.2.0",
      "resolved": "https://registry.npmjs.org/escalade/-/escalade-3.2.0.tgz",
      "integrity": "sha512-WUj2qlxaQtO4g6Pq5c29GTcWGDyd8itL8zTlipgECz3JesAiiOKotd8JU6otB3PACgG6xkJUyVhboMS+bje/jA==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/escape-string-regexp": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/escape-string-regexp/-/escape-string-regexp-4.0.0.tgz",
      "integrity": "sha512-TtpcNJ3XAzx3Gq8sWRzJaVajRs0uVxA2YAkdb1jm2YkPz4G6egUFAyA3n5vtEIZefPk5Wa4UXbKuS5fKkJWdgA==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=10"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/eslint": {
      "version": "9.23.0",
      "resolved": "https://registry.npmjs.org/eslint/-/eslint-9.23.0.tgz",
      "integrity": "sha512-jV7AbNoFPAY1EkFYpLq5bslU9NLNO8xnEeQXwErNibVryjk67wHVmddTBilc5srIttJDBrB0eMHKZBFbSIABCw==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@eslint-community/eslint-utils": "^4.2.0",
        "@eslint-community/regexpp": "^4.12.1",
        "@eslint/config-array": "^0.19.2",
        "@eslint/config-helpers": "^0.2.0",
        "@eslint/core": "^0.12.0",
        "@eslint/eslintrc": "^3.3.1",
        "@eslint/js": "9.23.0",
        "@eslint/plugin-kit": "^0.2.7",
        "@humanfs/node": "^0.16.6",
        "@humanwhocodes/module-importer": "^1.0.1",
        "@humanwhocodes/retry": "^0.4.2",
        "@types/estree": "^1.0.6",
        "@types/json-schema": "^7.0.15",
        "ajv": "^6.12.4",
        "chalk": "^4.0.0",
        "cross-spawn": "^7.0.6",
        "debug": "^4.3.2",
        "escape-string-regexp": "^4.0.0",
        "eslint-scope": "^8.3.0",
        "eslint-visitor-keys": "^4.2.0",
        "espree": "^10.3.0",
        "esquery": "^1.5.0",
        "esutils": "^2.0.2",
        "fast-deep-equal": "^3.1.3",
        "file-entry-cache": "^8.0.0",
        "find-up": "^5.0.0",
        "glob-parent": "^6.0.2",
        "ignore": "^5.2.0",
        "imurmurhash": "^0.1.4",
        "is-glob": "^4.0.0",
        "json-stable-stringify-without-jsonify": "^1.0.1",
        "lodash.merge": "^4.6.2",
        "minimatch": "^3.1.2",
        "natural-compare": "^1.4.0",
        "optionator": "^0.9.3"
      },
      "bin": {
        "eslint": "bin/eslint.js"
      },
      "engines": {
        "node": "^18.18.0 || ^20.9.0 || >=21.1.0"
      },
      "funding": {
        "url": "https://eslint.org/donate"
      },
      "peerDependencies": {
        "jiti": "*"
      },
      "peerDependenciesMeta": {
        "jiti": {
          "optional": true
        }
      }
    },
    "node_modules/eslint-plugin-react-hooks": {
      "version": "5.2.0",
      "resolved": "https://registry.npmjs.org/eslint-plugin-react-hooks/-/eslint-plugin-react-hooks-5.2.0.tgz",
      "integrity": "sha512-+f15FfK64YQwZdJNELETdn5ibXEUQmW1DZL6KXhNnc2heoy/sg9VJJeT7n8TlMWouzWqSWavFkIhHyIbIAEapg==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=10"
      },
      "peerDependencies": {
        "eslint": "^3.0.0 || ^4.0.0 || ^5.0.0 || ^6.0.0 || ^7.0.0 || ^8.0.0-0 || ^9.0.0"
      }
    },
    "node_modules/eslint-plugin-react-refresh": {
      "version": "0.4.19",
      "resolved": "https://registry.npmjs.org/eslint-plugin-react-refresh/-/eslint-plugin-react-refresh-0.4.19.tgz",
      "integrity": "sha512-eyy8pcr/YxSYjBoqIFSrlbn9i/xvxUFa8CjzAYo9cFjgGXqq1hyjihcpZvxRLalpaWmueWR81xn7vuKmAFijDQ==",
      "dev": true,
      "license": "MIT",
      "peerDependencies": {
        "eslint": ">=8.40"
      }
    },
    "node_modules/eslint-scope": {
      "version": "8.3.0",
      "resolved": "https://registry.npmjs.org/eslint-scope/-/eslint-scope-8.3.0.tgz",
      "integrity": "sha512-pUNxi75F8MJ/GdeKtVLSbYg4ZI34J6C0C7sbL4YOp2exGwen7ZsuBqKzUhXd0qMQ362yET3z+uPwKeg/0C2XCQ==",
      "dev": true,
      "license": "BSD-2-Clause",
      "dependencies": {
        "esrecurse": "^4.3.0",
        "estraverse": "^5.2.0"
      },
      "engines": {
        "node": "^18.18.0 || ^20.9.0 || >=21.1.0"
      },
      "funding": {
        "url": "https://opencollective.com/eslint"
      }
    },
    "node_modules/eslint-visitor-keys": {
      "version": "4.2.0",
      "resolved": "https://registry.npmjs.org/eslint-visitor-keys/-/eslint-visitor-keys-4.2.0.tgz",
      "integrity": "sha512-UyLnSehNt62FFhSwjZlHmeokpRK59rcz29j+F1/aDgbkbRTk7wIc9XzdoasMUbRNKDM0qQt/+BJ4BrpFeABemw==",
      "dev": true,
      "license": "Apache-2.0",
      "engines": {
        "node": "^18.18.0 || ^20.9.0 || >=21.1.0"
      },
      "funding": {
        "url": "https://opencollective.com/eslint"
      }
    },
    "node_modules/espree": {
      "version": "10.3.0",
      "resolved": "https://registry.npmjs.org/espree/-/espree-10.3.0.tgz",
      "integrity": "sha512-0QYC8b24HWY8zjRnDTL6RiHfDbAWn63qb4LMj1Z4b076A4une81+z03Kg7l7mn/48PUTqoLptSXez8oknU8Clg==",
      "dev": true,
      "license": "BSD-2-Clause",
      "dependencies": {
        "acorn": "^8.14.0",
        "acorn-jsx": "^5.3.2",
        "eslint-visitor-keys": "^4.2.0"
      },
      "engines": {
        "node": "^18.18.0 || ^20.9.0 || >=21.1.0"
      },
      "funding": {
        "url": "https://opencollective.com/eslint"
      }
    },
    "node_modules/esquery": {
      "version": "1.6.0",
      "resolved": "https://registry.npmjs.org/esquery/-/esquery-1.6.0.tgz",
      "integrity": "sha512-ca9pw9fomFcKPvFLXhBKUK90ZvGibiGOvRJNbjljY7s7uq/5YO4BOzcYtJqExdx99rF6aAcnRxHmcUHcz6sQsg==",
      "dev": true,
      "license": "BSD-3-Clause",
      "dependencies": {
        "estraverse": "^5.1.0"
      },
      "engines": {
        "node": ">=0.10"
      }
    },
    "node_modules/esrecurse": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/esrecurse/-/esrecurse-4.3.0.tgz",
      "integrity": "sha512-KmfKL3b6G+RXvP8N1vr3Tq1kL/oCFgn2NYXEtqP8/L3pKapUA4G8cFVaoF3SU323CD4XypR/ffioHmkti6/Tag==",
      "dev": true,
      "license": "BSD-2-Clause",
      "dependencies": {
        "estraverse": "^5.2.0"
      },
      "engines": {
        "node": ">=4.0"
      }
    },
    "node_modules/estraverse": {
      "version": "5.3.0",
      "resolved": "https://registry.npmjs.org/estraverse/-/estraverse-5.3.0.tgz",
      "integrity": "sha512-MMdARuVEQziNTeJD8DgMqmhwR11BRQ/cBP+pLtYdSTnf3MIO8fFeiINEbX36ZdNlfU/7A9f3gUw49B3oQsvwBA==",
      "dev": true,
      "license": "BSD-2-Clause",
      "engines": {
        "node": ">=4.0"
      }
    },
    "node_modules/esutils": {
      "version": "2.0.3",
      "resolved": "https://registry.npmjs.org/esutils/-/esutils-2.0.3.tgz",
      "integrity": "sha512-kVscqXk4OCp68SZ0dkgEKVi6/8ij300KBWTJq32P/dYeWTSwK41WyTxalN1eRmA5Z9UU/LX9D7FWSmV9SAYx6g==",
      "dev": true,
      "license": "BSD-2-Clause",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/fast-deep-equal": {
      "version": "3.1.3",
      "resolved": "https://registry.npmjs.org/fast-deep-equal/-/fast-deep-equal-3.1.3.tgz",
      "integrity": "sha512-f3qQ9oQy9j2AhBe/H9VC91wLmKBCCU/gDOnKNAYG5hswO7BLKj09Hc5HYNz9cGI++xlpDCIgDaitVs03ATR84Q==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/fast-glob": {
      "version": "3.3.3",
      "resolved": "https://registry.npmjs.org/fast-glob/-/fast-glob-3.3.3.tgz",
      "integrity": "sha512-7MptL8U0cqcFdzIzwOTHoilX9x5BrNqye7Z/LuC7kCMRio1EMSyqRK3BEAUD7sXRq4iT4AzTVuZdhgQ2TCvYLg==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@nodelib/fs.stat": "^2.0.2",
        "@nodelib/fs.walk": "^1.2.3",
        "glob-parent": "^5.1.2",
        "merge2": "^1.3.0",
        "micromatch": "^4.0.8"
      },
      "engines": {
        "node": ">=8.6.0"
      }
    },
    "node_modules/fast-glob/node_modules/glob-parent": {
      "version": "5.1.2",
      "resolved": "https://registry.npmjs.org/glob-parent/-/glob-parent-5.1.2.tgz",
      "integrity": "sha512-AOIgSQCepiJYwP3ARnGx+5VnTu2HBYdzbGP45eLw1vr3zB3vZLeyed1sC9hnbcOc9/SrMyM5RPQrkGz4aS9Zow==",
      "dev": true,
      "license": "ISC",
      "dependencies": {
        "is-glob": "^4.0.1"
      },
      "engines": {
        "node": ">= 6"
      }
    },
    "node_modules/fast-json-stable-stringify": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/fast-json-stable-stringify/-/fast-json-stable-stringify-2.1.0.tgz",
      "integrity": "sha512-lhd/wF+Lk98HZoTCtlVraHtfh5XYijIjalXck7saUtuanSDyLMxnHhSXEDJqHxD7msR8D0uCmqlkwjCV8xvwHw==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/fast-levenshtein": {
      "version": "2.0.6",
      "resolved": "https://registry.npmjs.org/fast-levenshtein/-/fast-levenshtein-2.0.6.tgz",
      "integrity": "sha512-DCXu6Ifhqcks7TZKY3Hxp3y6qphY5SJZmrWMDrKcERSOXWQdMhU9Ig/PYrzyw/ul9jOIyh0N4M0tbC5hodg8dw==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/fastq": {
      "version": "1.19.1",
      "resolved": "https://registry.npmjs.org/fastq/-/fastq-1.19.1.tgz",
      "integrity": "sha512-GwLTyxkCXjXbxqIhTsMI2Nui8huMPtnxg7krajPJAjnEG/iiOS7i+zCtWGZR9G0NBKbXKh6X9m9UIsYX/N6vvQ==",
      "dev": true,
      "license": "ISC",
      "dependencies": {
        "reusify": "^1.0.4"
      }
    },
    "node_modules/file-entry-cache": {
      "version": "8.0.0",
      "resolved": "https://registry.npmjs.org/file-entry-cache/-/file-entry-cache-8.0.0.tgz",
      "integrity": "sha512-XXTUwCvisa5oacNGRP9SfNtYBNAMi+RPwBFmblZEF7N7swHYQS6/Zfk7SRwx4D5j3CH211YNRco1DEMNVfZCnQ==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "flat-cache": "^4.0.0"
      },
      "engines": {
        "node": ">=16.0.0"
      }
    },
    "node_modules/fill-range": {
      "version": "7.1.1",
      "resolved": "https://registry.npmjs.org/fill-range/-/fill-range-7.1.1.tgz",
      "integrity": "sha512-YsGpe3WHLK8ZYi4tWDg2Jy3ebRz2rXowDxnld4bkQB00cc/1Zw9AWnC0i9ztDJitivtQvaI9KaLyKrc+hBW0yg==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "to-regex-range": "^5.0.1"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/find-up": {
      "version": "5.0.0",
      "resolved": "https://registry.npmjs.org/find-up/-/find-up-5.0.0.tgz",
      "integrity": "sha512-78/PXT1wlLLDgTzDs7sjq9hzz0vXD+zn+7wypEe4fXQxCmdmqfGsEPQxmiCSQI3ajFV91bVSsvNtrJRiW6nGng==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "locate-path": "^6.0.0",
        "path-exists": "^4.0.0"
      },
      "engines": {
        "node": ">=10"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/flat-cache": {
      "version": "4.0.1",
      "resolved": "https://registry.npmjs.org/flat-cache/-/flat-cache-4.0.1.tgz",
      "integrity": "sha512-f7ccFPK3SXFHpx15UIGyRJ/FJQctuKZ0zVuN3frBo4HnK3cay9VEW0R6yPYFHC0AgqhukPzKjq22t5DmAyqGyw==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "flatted": "^3.2.9",
        "keyv": "^4.5.4"
      },
      "engines": {
        "node": ">=16"
      }
    },
    "node_modules/flatted": {
      "version": "3.3.3",
      "resolved": "https://registry.npmjs.org/flatted/-/flatted-3.3.3.tgz",
      "integrity": "sha512-GX+ysw4PBCz0PzosHDepZGANEuFCMLrnRTiEy9McGjmkCQYwRq4A/X786G/fjM/+OjsWSU1ZrY5qyARZmO/uwg==",
      "dev": true,
      "license": "ISC"
    },
    "node_modules/follow-redirects": {
      "version": "1.15.9",
      "resolved": "https://registry.npmjs.org/follow-redirects/-/follow-redirects-1.15.9.tgz",
      "integrity": "sha512-gew4GsXizNgdoRyqmyfMHyAmXsZDk6mHkSxZFCzW9gwlbtOW44CDtYavM+y+72qD/Vq2l550kMF52DT8fOLJqQ==",
      "funding": [
        {
          "type": "individual",
          "url": "https://github.com/sponsors/RubenVerborgh"
        }
      ],
      "license": "MIT",
      "engines": {
        "node": ">=4.0"
      },
      "peerDependenciesMeta": {
        "debug": {
          "optional": true
        }
      }
    },
    "node_modules/foreground-child": {
      "version": "3.3.1",
      "resolved": "https://registry.npmjs.org/foreground-child/-/foreground-child-3.3.1.tgz",
      "integrity": "sha512-gIXjKqtFuWEgzFRJA9WCQeSJLZDjgJUOMCMzxtvFq/37KojM1BFGufqsCy0r4qSQmYLsZYMeyRqzIWOMup03sw==",
      "dev": true,
      "license": "ISC",
      "dependencies": {
        "cross-spawn": "^7.0.6",
        "signal-exit": "^4.0.1"
      },
      "engines": {
        "node": ">=14"
      },
      "funding": {
        "url": "https://github.com/sponsors/isaacs"
      }
    },
    "node_modules/form-data": {
      "version": "4.0.2",
      "resolved": "https://registry.npmjs.org/form-data/-/form-data-4.0.2.tgz",
      "integrity": "sha512-hGfm/slu0ZabnNt4oaRZ6uREyfCj6P4fT/n6A1rGV+Z0VdGXjfOhVUpkn6qVQONHGIFwmveGXyDs75+nr6FM8w==",
      "license": "MIT",
      "dependencies": {
        "asynckit": "^0.4.0",
        "combined-stream": "^1.0.8",
        "es-set-tostringtag": "^2.1.0",
        "mime-types": "^2.1.12"
      },
      "engines": {
        "node": ">= 6"
      }
    },
    "node_modules/fraction.js": {
      "version": "4.3.7",
      "resolved": "https://registry.npmjs.org/fraction.js/-/fraction.js-4.3.7.tgz",
      "integrity": "sha512-ZsDfxO51wGAXREY55a7la9LScWpwv9RxIrYABrlvOFBlH/ShPnrtsXeuUIfXKKOVicNxQ+o8JTbJvjS4M89yew==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": "*"
      },
      "funding": {
        "type": "patreon",
        "url": "https://github.com/sponsors/rawify"
      }
    },
    "node_modules/framer-motion": {
      "version": "12.6.5",
      "resolved": "https://registry.npmjs.org/framer-motion/-/framer-motion-12.6.5.tgz",
      "integrity": "sha512-MKvnWov0paNjvRJuIy6x418w23tFqRfS6CXHhZrCiSEpXVlo/F+usr8v4/3G6O0u7CpsaO1qop+v4Ip7PRCBqQ==",
      "license": "MIT",
      "dependencies": {
        "motion-dom": "^12.6.5",
        "motion-utils": "^12.6.5",
        "tslib": "^2.4.0"
      },
      "peerDependencies": {
        "@emotion/is-prop-valid": "*",
        "react": "^18.0.0 || ^19.0.0",
        "react-dom": "^18.0.0 || ^19.0.0"
      },
      "peerDependenciesMeta": {
        "@emotion/is-prop-valid": {
          "optional": true
        },
        "react": {
          "optional": true
        },
        "react-dom": {
          "optional": true
        }
      }
    },
    "node_modules/fsevents": {
      "version": "2.3.3",
      "resolved": "https://registry.npmjs.org/fsevents/-/fsevents-2.3.3.tgz",
      "integrity": "sha512-5xoDfX+fL7faATnagmWPpbFtwh/R77WmMMqqHGS65C3vvB0YHrgF+B1YmZ3441tMj5n63k0212XNoJwzlhffQw==",
      "dev": true,
      "hasInstallScript": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "darwin"
      ],
      "engines": {
        "node": "^8.16.0 || ^10.6.0 || >=11.0.0"
      }
    },
    "node_modules/function-bind": {
      "version": "1.1.2",
      "resolved": "https://registry.npmjs.org/function-bind/-/function-bind-1.1.2.tgz",
      "integrity": "sha512-7XHNxH7qX9xG5mIwxkhumTox/MIRNcOgDrxWsMt2pAr23WHp6MrRlN7FBSFpCpr+oVO0F744iUgR82nJMfG2SA==",
      "license": "MIT",
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/gensync": {
      "version": "1.0.0-beta.2",
      "resolved": "https://registry.npmjs.org/gensync/-/gensync-1.0.0-beta.2.tgz",
      "integrity": "sha512-3hN7NaskYvMDLQY55gnW3NQ+mesEAepTqlg+VEbj7zzqEMBVNhzcGYYeqFo/TlYz6eQiFcp1HcsCZO+nGgS8zg==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/get-intrinsic": {
      "version": "1.3.0",
      "resolved": "https://registry.npmjs.org/get-intrinsic/-/get-intrinsic-1.3.0.tgz",
      "integrity": "sha512-9fSjSaos/fRIVIp+xSJlE6lfwhES7LNtKaCBIamHsjr2na1BiABJPo0mOjjz8GJDURarmCPGqaiVg5mfjb98CQ==",
      "license": "MIT",
      "dependencies": {
        "call-bind-apply-helpers": "^1.0.2",
        "es-define-property": "^1.0.1",
        "es-errors": "^1.3.0",
        "es-object-atoms": "^1.1.1",
        "function-bind": "^1.1.2",
        "get-proto": "^1.0.1",
        "gopd": "^1.2.0",
        "has-symbols": "^1.1.0",
        "hasown": "^2.0.2",
        "math-intrinsics": "^1.1.0"
      },
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/get-proto": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/get-proto/-/get-proto-1.0.1.tgz",
      "integrity": "sha512-sTSfBjoXBp89JvIKIefqw7U2CCebsc74kiY6awiGogKtoSGbgjYE/G/+l9sF3MWFPNc9IcoOC4ODfKHfxFmp0g==",
      "license": "MIT",
      "dependencies": {
        "dunder-proto": "^1.0.1",
        "es-object-atoms": "^1.0.0"
      },
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/glob": {
      "version": "10.4.5",
      "resolved": "https://registry.npmjs.org/glob/-/glob-10.4.5.tgz",
      "integrity": "sha512-7Bv8RF0k6xjo7d4A/PxYLbUCfb6c+Vpd2/mB2yRDlew7Jb5hEXiCD9ibfO7wpk8i4sevK6DFny9h7EYbM3/sHg==",
      "dev": true,
      "license": "ISC",
      "dependencies": {
        "foreground-child": "^3.1.0",
        "jackspeak": "^3.1.2",
        "minimatch": "^9.0.4",
        "minipass": "^7.1.2",
        "package-json-from-dist": "^1.0.0",
        "path-scurry": "^1.11.1"
      },
      "bin": {
        "glob": "dist/esm/bin.mjs"
      },
      "funding": {
        "url": "https://github.com/sponsors/isaacs"
      }
    },
    "node_modules/glob-parent": {
      "version": "6.0.2",
      "resolved": "https://registry.npmjs.org/glob-parent/-/glob-parent-6.0.2.tgz",
      "integrity": "sha512-XxwI8EOhVQgWp6iDL+3b0r86f4d6AX6zSU55HfB4ydCEuXLXc5FcYeOu+nnGftS4TEju/11rt4KJPTMgbfmv4A==",
      "dev": true,
      "license": "ISC",
      "dependencies": {
        "is-glob": "^4.0.3"
      },
      "engines": {
        "node": ">=10.13.0"
      }
    },
    "node_modules/glob/node_modules/brace-expansion": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/brace-expansion/-/brace-expansion-2.0.1.tgz",
      "integrity": "sha512-XnAIvQ8eM+kC6aULx6wuQiwVsnzsi9d3WxzV3FpWTGA19F621kwdbsAcFKXgKUHZWsy+mY6iL1sHTxWEFCytDA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "balanced-match": "^1.0.0"
      }
    },
    "node_modules/glob/node_modules/minimatch": {
      "version": "9.0.5",
      "resolved": "https://registry.npmjs.org/minimatch/-/minimatch-9.0.5.tgz",
      "integrity": "sha512-G6T0ZX48xgozx7587koeX9Ys2NYy6Gmv//P89sEte9V9whIapMNF4idKxnW2QtCcLiTWlb/wfCabAtAFWhhBow==",
      "dev": true,
      "license": "ISC",
      "dependencies": {
        "brace-expansion": "^2.0.1"
      },
      "engines": {
        "node": ">=16 || 14 >=14.17"
      },
      "funding": {
        "url": "https://github.com/sponsors/isaacs"
      }
    },
    "node_modules/globals": {
      "version": "15.15.0",
      "resolved": "https://registry.npmjs.org/globals/-/globals-15.15.0.tgz",
      "integrity": "sha512-7ACyT3wmyp3I61S4fG682L0VA2RGD9otkqGJIwNUMF1SWUombIIk+af1unuDYgMm082aHYwD+mzJvv9Iu8dsgg==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/gopd": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/gopd/-/gopd-1.2.0.tgz",
      "integrity": "sha512-ZUKRh6/kUFoAiTAtTYPZJ3hw9wNxx+BIBOijnlG9PnrJsCcSjs1wyyD6vJpaYtgnzDrKYRSqf3OO6Rfa93xsRg==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/has-flag": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
      "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/has-symbols": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/has-symbols/-/has-symbols-1.1.0.tgz",
      "integrity": "sha512-1cDNdwJ2Jaohmb3sg4OmKaMBwuC48sYni5HUw2DvsC8LjGTLK9h+eb1X6RyuOHe4hT0ULCW68iomhjUoKUqlPQ==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/has-tostringtag": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/has-tostringtag/-/has-tostringtag-1.0.2.tgz",
      "integrity": "sha512-NqADB8VjPFLM2V0VvHUewwwsw0ZWBaIdgo+ieHtK3hasLz4qeCRjYcqfB6AQrBggRKppKF8L52/VqdVsO47Dlw==",
      "license": "MIT",
      "dependencies": {
        "has-symbols": "^1.0.3"
      },
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/hasown": {
      "version": "2.0.2",
      "resolved": "https://registry.npmjs.org/hasown/-/hasown-2.0.2.tgz",
      "integrity": "sha512-0hJU9SCPvmMzIBdZFqNPXWa6dqh7WdH0cII9y+CyS8rG3nL48Bclra9HmKhVVUHyPWNH5Y7xDwAB7bfgSjkUMQ==",
      "license": "MIT",
      "dependencies": {
        "function-bind": "^1.1.2"
      },
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/ignore": {
      "version": "5.3.2",
      "resolved": "https://registry.npmjs.org/ignore/-/ignore-5.3.2.tgz",
      "integrity": "sha512-hsBTNUqQTDwkWtcdYI2i06Y/nUBEsNEDJKjWdigLvegy8kDuJAS8uRlpkkcQpyEXL0Z/pjDy5HBmMjRCJ2gq+g==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">= 4"
      }
    },
    "node_modules/immer": {
      "version": "10.1.1",
      "resolved": "https://registry.npmjs.org/immer/-/immer-10.1.1.tgz",
      "integrity": "sha512-s2MPrmjovJcoMaHtx6K11Ra7oD05NT97w1IC5zpMkT6Atjr7H8LjaDd81iIxUYpMKSRRNMJE703M1Fhr/TctHw==",
      "license": "MIT",
      "funding": {
        "type": "opencollective",
        "url": "https://opencollective.com/immer"
      }
    },
    "node_modules/import-fresh": {
      "version": "3.3.1",
      "resolved": "https://registry.npmjs.org/import-fresh/-/import-fresh-3.3.1.tgz",
      "integrity": "sha512-TR3KfrTZTYLPB6jUjfx6MF9WcWrHL9su5TObK4ZkYgBdWKPOFoSoQIdEuTuR82pmtxH2spWG9h6etwfr1pLBqQ==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "parent-module": "^1.0.0",
        "resolve-from": "^4.0.0"
      },
      "engines": {
        "node": ">=6"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/imurmurhash": {
      "version": "0.1.4",
      "resolved": "https://registry.npmjs.org/imurmurhash/-/imurmurhash-0.1.4.tgz",
      "integrity": "sha512-JmXMZ6wuvDmLiHEml9ykzqO6lwFbof0GG4IkcGaENdCRDDmMVnny7s5HsIgHCbaq0w2MyPhDqkhTUgS2LU2PHA==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=0.8.19"
      }
    },
    "node_modules/is-binary-path": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/is-binary-path/-/is-binary-path-2.1.0.tgz",
      "integrity": "sha512-ZMERYes6pDydyuGidse7OsHxtbI7WVeUEozgR/g7rd0xUimYNlvZRE/K2MgZTjWy725IfelLeVcEM97mmtRGXw==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "binary-extensions": "^2.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/is-core-module": {
      "version": "2.16.1",
      "resolved": "https://registry.npmjs.org/is-core-module/-/is-core-module-2.16.1.tgz",
      "integrity": "sha512-UfoeMA6fIJ8wTYFEUjelnaGI67v6+N7qXJEvQuIGa99l4xsCruSYOVSQ0uPANn4dAzm8lkYPaKLrrijLq7x23w==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "hasown": "^2.0.2"
      },
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/is-extglob": {
      "version": "2.1.1",
      "resolved": "https://registry.npmjs.org/is-extglob/-/is-extglob-2.1.1.tgz",
      "integrity": "sha512-SbKbANkN603Vi4jEZv49LeVJMn4yGwsbzZworEoyEiutsN3nJYdbO36zfhGJ6QEDpOZIFkDtnq5JRxmvl3jsoQ==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/is-fullwidth-code-point": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/is-fullwidth-code-point/-/is-fullwidth-code-point-3.0.0.tgz",
      "integrity": "sha512-zymm5+u+sCsSWyD9qNaejV3DFvhCKclKdizYaJUuHA83RLjb7nSuGnddCHGv0hk+KY7BMAlsWeK4Ueg6EV6XQg==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/is-glob": {
      "version": "4.0.3",
      "resolved": "https://registry.npmjs.org/is-glob/-/is-glob-4.0.3.tgz",
      "integrity": "sha512-xelSayHH36ZgE7ZWhli7pW34hNbNl8Ojv5KVmkJD4hBdD3th8Tfk9vYasLM+mXWOZhFkgZfxhLSnrwRr4elSSg==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "is-extglob": "^2.1.1"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/is-number": {
      "version": "7.0.0",
      "resolved": "https://registry.npmjs.org/is-number/-/is-number-7.0.0.tgz",
      "integrity": "sha512-41Cifkg6e8TylSpdtTpeLVMqvSBEVzTttHvERD741+pnZ8ANv0004MRL43QKPDlK9cGvNp6NZWZUBlbGXYxxng==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=0.12.0"
      }
    },
    "node_modules/isexe": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/isexe/-/isexe-2.0.0.tgz",
      "integrity": "sha512-RHxMLp9lnKHGHRng9QFhRCMbYAcVpn69smSGcq3f36xjgVVWThj4qqLbTLlq7Ssj8B+fIQ1EuCEGI2lKsyQeIw==",
      "dev": true,
      "license": "ISC"
    },
    "node_modules/jackspeak": {
      "version": "3.4.3",
      "resolved": "https://registry.npmjs.org/jackspeak/-/jackspeak-3.4.3.tgz",
      "integrity": "sha512-OGlZQpz2yfahA/Rd1Y8Cd9SIEsqvXkLVoSw/cgwhnhFMDbsQFeZYoJJ7bIZBS9BcamUW96asq/npPWugM+RQBw==",
      "dev": true,
      "license": "BlueOak-1.0.0",
      "dependencies": {
        "@isaacs/cliui": "^8.0.2"
      },
      "funding": {
        "url": "https://github.com/sponsors/isaacs"
      },
      "optionalDependencies": {
        "@pkgjs/parseargs": "^0.11.0"
      }
    },
    "node_modules/jiti": {
      "version": "1.21.7",
      "resolved": "https://registry.npmjs.org/jiti/-/jiti-1.21.7.tgz",
      "integrity": "sha512-/imKNG4EbWNrVjoNC/1H5/9GFy+tqjGBHCaSsN+P2RnPqjsLmv6UD3Ej+Kj8nBWaRAwyk7kK5ZUc+OEatnTR3A==",
      "dev": true,
      "license": "MIT",
      "bin": {
        "jiti": "bin/jiti.js"
      }
    },
    "node_modules/js-tokens": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/js-tokens/-/js-tokens-4.0.0.tgz",
      "integrity": "sha512-RdJUflcE3cUzKiMqQgsCu06FPu9UdIJO0beYbPhHN4k6apgJtifcoCtT9bcxOpYBtpD2kCM6Sbzg4CausW/PKQ==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/js-yaml": {
      "version": "4.1.0",
      "resolved": "https://registry.npmjs.org/js-yaml/-/js-yaml-4.1.0.tgz",
      "integrity": "sha512-wpxZs9NoxZaJESJGIZTyDEaYpl0FKSA+FB9aJiyemKhMwkxQg63h4T1KJgUGHpTqPDNRcmmYLugrRjJlBtWvRA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "argparse": "^2.0.1"
      },
      "bin": {
        "js-yaml": "bin/js-yaml.js"
      }
    },
    "node_modules/jsesc": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/jsesc/-/jsesc-3.1.0.tgz",
      "integrity": "sha512-/sM3dO2FOzXjKQhJuo0Q173wf2KOo8t4I8vHy6lF9poUp7bKT0/NHE8fPX23PwfhnykfqnC2xRxOnVw5XuGIaA==",
      "dev": true,
      "license": "MIT",
      "bin": {
        "jsesc": "bin/jsesc"
      },
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/json-buffer": {
      "version": "3.0.1",
      "resolved": "https://registry.npmjs.org/json-buffer/-/json-buffer-3.0.1.tgz",
      "integrity": "sha512-4bV5BfR2mqfQTJm+V5tPPdf+ZpuhiIvTuAB5g8kcrXOZpTT/QwwVRWBywX1ozr6lEuPdbHxwaJlm9G6mI2sfSQ==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/json-schema-traverse": {
      "version": "0.4.1",
      "resolved": "https://registry.npmjs.org/json-schema-traverse/-/json-schema-traverse-0.4.1.tgz",
      "integrity": "sha512-xbbCH5dCYU5T8LcEhhuh7HJ88HXuW3qsI3Y0zOZFKfZEHcpWiHU/Jxzk629Brsab/mMiHQti9wMP+845RPe3Vg==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/json-stable-stringify-without-jsonify": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/json-stable-stringify-without-jsonify/-/json-stable-stringify-without-jsonify-1.0.1.tgz",
      "integrity": "sha512-Bdboy+l7tA3OGW6FjyFHWkP5LuByj1Tk33Ljyq0axyzdk9//JSi2u3fP1QSmd1KNwq6VOKYGlAu87CisVir6Pw==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/json5": {
      "version": "2.2.3",
      "resolved": "https://registry.npmjs.org/json5/-/json5-2.2.3.tgz",
      "integrity": "sha512-XmOWe7eyHYH14cLdVPoyg+GOH3rYX++KpzrylJwSW98t3Nk+U8XOl8FWKOgwtzdb8lXGf6zYwDUzeHMWfxasyg==",
      "dev": true,
      "license": "MIT",
      "bin": {
        "json5": "lib/cli.js"
      },
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/keyv": {
      "version": "4.5.4",
      "resolved": "https://registry.npmjs.org/keyv/-/keyv-4.5.4.tgz",
      "integrity": "sha512-oxVHkHR/EJf2CNXnWxRLW6mg7JyCCUcG0DtEGmL2ctUo1PNTin1PUil+r/+4r5MpVgC/fn1kjsx7mjSujKqIpw==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "json-buffer": "3.0.1"
      }
    },
    "node_modules/levn": {
      "version": "0.4.1",
      "resolved": "https://registry.npmjs.org/levn/-/levn-0.4.1.tgz",
      "integrity": "sha512-+bT2uH4E5LGE7h/n3evcS/sQlJXCpIp6ym8OWJ5eV6+67Dsql/LaaT7qJBAt2rzfoa/5QBGBhxDix1dMt2kQKQ==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "prelude-ls": "^1.2.1",
        "type-check": "~0.4.0"
      },
      "engines": {
        "node": ">= 0.8.0"
      }
    },
    "node_modules/lilconfig": {
      "version": "3.1.3",
      "resolved": "https://registry.npmjs.org/lilconfig/-/lilconfig-3.1.3.tgz",
      "integrity": "sha512-/vlFKAoH5Cgt3Ie+JLhRbwOsCQePABiU3tJ1egGvyQ+33R/vcwM2Zl2QR/LzjsBeItPt3oSVXapn+m4nQDvpzw==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=14"
      },
      "funding": {
        "url": "https://github.com/sponsors/antonk52"
      }
    },
    "node_modules/lines-and-columns": {
      "version": "1.2.4",
      "resolved": "https://registry.npmjs.org/lines-and-columns/-/lines-and-columns-1.2.4.tgz",
      "integrity": "sha512-7ylylesZQ/PV29jhEDl3Ufjo6ZX7gCqJr5F7PKrqc93v7fzSymt1BpwEU8nAUXs8qzzvqhbjhK5QZg6Mt/HkBg==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/locate-path": {
      "version": "6.0.0",
      "resolved": "https://registry.npmjs.org/locate-path/-/locate-path-6.0.0.tgz",
      "integrity": "sha512-iPZK6eYjbxRu3uB4/WZ3EsEIMJFMqAoopl3R+zuq0UjcAm/MO6KCweDgPfP3elTztoKP3KtnVHxTn2NHBSDVUw==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "p-locate": "^5.0.0"
      },
      "engines": {
        "node": ">=10"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/lodash": {
      "version": "4.17.21",
      "resolved": "https://registry.npmjs.org/lodash/-/lodash-4.17.21.tgz",
      "integrity": "sha512-v2kDEe57lecTulaDIuNTPy3Ry4gLGJ6Z1O3vE1krgXZNrsQ+LFTGHVxVjcXPs17LhbZVGedAJv8XZ1tvj5FvSg==",
      "license": "MIT"
    },
    "node_modules/lodash.merge": {
      "version": "4.6.2",
      "resolved": "https://registry.npmjs.org/lodash.merge/-/lodash.merge-4.6.2.tgz",
      "integrity": "sha512-0KpjqXRVvrYyCsX1swR/XTK0va6VQkQM6MNo7PqW77ByjAhoARA8EfrP1N4+KlKj8YS0ZUCtRT/YUuhyYDujIQ==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/lru-cache": {
      "version": "5.1.1",
      "resolved": "https://registry.npmjs.org/lru-cache/-/lru-cache-5.1.1.tgz",
      "integrity": "sha512-KpNARQA3Iwv+jTA0utUVVbrh+Jlrr1Fv0e56GGzAFOXN7dk/FviaDW8LHmK52DlcH4WP2n6gI8vN1aesBFgo9w==",
      "dev": true,
      "license": "ISC",
      "dependencies": {
        "yallist": "^3.0.2"
      }
    },
    "node_modules/lucide-react": {
      "version": "0.486.0",
      "resolved": "https://registry.npmjs.org/lucide-react/-/lucide-react-0.486.0.tgz",
      "integrity": "sha512-xWop/wMsC1ikiEVLZrxXjPKw4vU/eAip33G2mZHgbWnr4Nr5Rt4Vx4s/q1D3B/rQVbxjOuqASkEZcUxDEKzecw==",
      "license": "ISC",
      "peerDependencies": {
        "react": "^16.5.1 || ^17.0.0 || ^18.0.0 || ^19.0.0"
      }
    },
    "node_modules/math-intrinsics": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/math-intrinsics/-/math-intrinsics-1.1.0.tgz",
      "integrity": "sha512-/IXtbwEk5HTPyEwyKX6hGkYXxM9nbj64B+ilVJnC/R6B0pH5G4V3b0pVbL7DBj4tkhBAppbQUlf6F6Xl9LHu1g==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/merge2": {
      "version": "1.4.1",
      "resolved": "https://registry.npmjs.org/merge2/-/merge2-1.4.1.tgz",
      "integrity": "sha512-8q7VEgMJW4J8tcfVPy8g09NcQwZdbwFEqhe/WZkoIzjn/3TGDwtOCYtXGxA3O8tPzpczCCDgv+P2P5y00ZJOOg==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">= 8"
      }
    },
    "node_modules/micromatch": {
      "version": "4.0.8",
      "resolved": "https://registry.npmjs.org/micromatch/-/micromatch-4.0.8.tgz",
      "integrity": "sha512-PXwfBhYu0hBCPw8Dn0E+WDYb7af3dSLVWKi3HGv84IdF4TyFoC0ysxFd0Goxw7nSv4T/PzEJQxsYsEiFCKo2BA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "braces": "^3.0.3",
        "picomatch": "^2.3.1"
      },
      "engines": {
        "node": ">=8.6"
      }
    },
    "node_modules/mime-db": {
      "version": "1.52.0",
      "resolved": "https://registry.npmjs.org/mime-db/-/mime-db-1.52.0.tgz",
      "integrity": "sha512-sPU4uV7dYlvtWJxwwxHD0PuihVNiE7TyAbQ5SWxDCB9mUYvOgroQOwYQQOKPJ8CIbE+1ETVlOoK1UC2nU3gYvg==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/mime-types": {
      "version": "2.1.35",
      "resolved": "https://registry.npmjs.org/mime-types/-/mime-types-2.1.35.tgz",
      "integrity": "sha512-ZDY+bPm5zTTF+YpCrAU9nK0UgICYPT0QtT1NZWFv4s++TNkcgVaT0g6+4R2uI4MjQjzysHB1zxuWL50hzaeXiw==",
      "license": "MIT",
      "dependencies": {
        "mime-db": "1.52.0"
      },
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/minimatch": {
      "version": "3.1.2",
      "resolved": "https://registry.npmjs.org/minimatch/-/minimatch-3.1.2.tgz",
      "integrity": "sha512-J7p63hRiAjw1NDEww1W7i37+ByIrOWO5XQQAzZ3VOcL0PNybwpfmV/N05zFAzwQ9USyEcX6t3UO+K5aqBQOIHw==",
      "dev": true,
      "license": "ISC",
      "dependencies": {
        "brace-expansion": "^1.1.7"
      },
      "engines": {
        "node": "*"
      }
    },
    "node_modules/minipass": {
      "version": "7.1.2",
      "resolved": "https://registry.npmjs.org/minipass/-/minipass-7.1.2.tgz",
      "integrity": "sha512-qOOzS1cBTWYF4BH8fVePDBOO9iptMnGUEZwNc/cMWnTV2nVLZ7VoNWEPHkYczZA0pdoA7dl6e7FL659nX9S2aw==",
      "dev": true,
      "license": "ISC",
      "engines": {
        "node": ">=16 || 14 >=14.17"
      }
    },
    "node_modules/motion-dom": {
      "version": "12.6.5",
      "resolved": "https://registry.npmjs.org/motion-dom/-/motion-dom-12.6.5.tgz",
      "integrity": "sha512-jpM9TQLXzYMWMJ7Ec7sAj0iis8oIuu6WvjI3yNKJLdrZyrsI/b2cRInDVL8dCl683zQQq19DpL9cSMP+k8T1NA==",
      "license": "MIT",
      "dependencies": {
        "motion-utils": "^12.6.5"
      }
    },
    "node_modules/motion-utils": {
      "version": "12.6.5",
      "resolved": "https://registry.npmjs.org/motion-utils/-/motion-utils-12.6.5.tgz",
      "integrity": "sha512-IsOeKsOF+FWBhxQEDFBO6ZYC8/jlidmVbbLpe9/lXSA9j9kzGIMUuIBx2SZY+0reAS0DjZZ1i7dJp4NHrjocPw==",
      "license": "MIT"
    },
    "node_modules/ms": {
      "version": "2.1.3",
      "resolved": "https://registry.npmjs.org/ms/-/ms-2.1.3.tgz",
      "integrity": "sha512-6FlzubTLZG3J2a/NVCAleEhjzq5oxgHyaCU9yYXvcLsvoVaHJq/s5xXI6/XXP6tz7R9xAOtHnSO/tXtF3WRTlA==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/mz": {
      "version": "2.7.0",
      "resolved": "https://registry.npmjs.org/mz/-/mz-2.7.0.tgz",
      "integrity": "sha512-z81GNO7nnYMEhrGh9LeymoE4+Yr0Wn5McHIZMK5cfQCl+NDX08sCZgUc9/6MHni9IWuFLm1Z3HTCXu2z9fN62Q==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "any-promise": "^1.0.0",
        "object-assign": "^4.0.1",
        "thenify-all": "^1.0.0"
      }
    },
    "node_modules/nanoid": {
      "version": "3.3.11",
      "resolved": "https://registry.npmjs.org/nanoid/-/nanoid-3.3.11.tgz",
      "integrity": "sha512-N8SpfPUnUp1bK+PMYW8qSWdl9U+wwNWI4QKxOYDy9JAro3WMX7p2OeVRF9v+347pnakNevPmiHhNmZ2HbFA76w==",
      "dev": true,
      "funding": [
        {
          "type": "github",
          "url": "https://github.com/sponsors/ai"
        }
      ],
      "license": "MIT",
      "bin": {
        "nanoid": "bin/nanoid.cjs"
      },
      "engines": {
        "node": "^10 || ^12 || ^13.7 || ^14 || >=15.0.1"
      }
    },
    "node_modules/natural-compare": {
      "version": "1.4.0",
      "resolved": "https://registry.npmjs.org/natural-compare/-/natural-compare-1.4.0.tgz",
      "integrity": "sha512-OWND8ei3VtNC9h7V60qff3SVobHr996CTwgxubgyQYEpg290h9J0buyECNNJexkFm5sOajh5G116RYA1c8ZMSw==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/node-releases": {
      "version": "2.0.19",
      "resolved": "https://registry.npmjs.org/node-releases/-/node-releases-2.0.19.tgz",
      "integrity": "sha512-xxOWJsBKtzAq7DY0J+DTzuz58K8e7sJbdgwkbMWQe8UYB6ekmsQ45q0M/tJDsGaZmbC+l7n57UV8Hl5tHxO9uw==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/normalize-path": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/normalize-path/-/normalize-path-3.0.0.tgz",
      "integrity": "sha512-6eZs5Ls3WtCisHWp9S2GUy8dqkpGi4BVSz3GaqiE6ezub0512ESztXUwUB6C6IKbQkY2Pnb/mD4WYojCRwcwLA==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/normalize-range": {
      "version": "0.1.2",
      "resolved": "https://registry.npmjs.org/normalize-range/-/normalize-range-0.1.2.tgz",
      "integrity": "sha512-bdok/XvKII3nUpklnV6P2hxtMNrCboOjAcyBuQnWEhO665FwrSNRxU+AqpsyvO6LgGYPspN+lu5CLtw4jPRKNA==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/object-assign": {
      "version": "4.1.1",
      "resolved": "https://registry.npmjs.org/object-assign/-/object-assign-4.1.1.tgz",
      "integrity": "sha512-rJgTQnkUnH1sFw8yT6VSU3zD3sWmu6sZhIseY8VX+GRu3P6F7Fu+JNDoXfklElbLJSnc3FUQHVe4cU5hj+BcUg==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/object-hash": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/object-hash/-/object-hash-3.0.0.tgz",
      "integrity": "sha512-RSn9F68PjH9HqtltsSnqYC1XXoWe9Bju5+213R98cNGttag9q9yAOTzdbsqvIa7aNm5WffBZFpWYr2aWrklWAw==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">= 6"
      }
    },
    "node_modules/optionator": {
      "version": "0.9.4",
      "resolved": "https://registry.npmjs.org/optionator/-/optionator-0.9.4.tgz",
      "integrity": "sha512-6IpQ7mKUxRcZNLIObR0hz7lxsapSSIYNZJwXPGeF0mTVqGKFIXj1DQcMoT22S3ROcLyY/rz0PWaWZ9ayWmad9g==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "deep-is": "^0.1.3",
        "fast-levenshtein": "^2.0.6",
        "levn": "^0.4.1",
        "prelude-ls": "^1.2.1",
        "type-check": "^0.4.0",
        "word-wrap": "^1.2.5"
      },
      "engines": {
        "node": ">= 0.8.0"
      }
    },
    "node_modules/p-limit": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/p-limit/-/p-limit-3.1.0.tgz",
      "integrity": "sha512-TYOanM3wGwNGsZN2cVTYPArw454xnXj5qmWF1bEoAc4+cU/ol7GVh7odevjp1FNHduHc3KZMcFduxU5Xc6uJRQ==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "yocto-queue": "^0.1.0"
      },
      "engines": {
        "node": ">=10"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/p-locate": {
      "version": "5.0.0",
      "resolved": "https://registry.npmjs.org/p-locate/-/p-locate-5.0.0.tgz",
      "integrity": "sha512-LaNjtRWUBY++zB5nE/NwcaoMylSPk+S+ZHNB1TzdbMJMny6dynpAGt7X/tl/QYq3TIeE6nxHppbo2LGymrG5Pw==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "p-limit": "^3.0.2"
      },
      "engines": {
        "node": ">=10"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/package-json-from-dist": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/package-json-from-dist/-/package-json-from-dist-1.0.1.tgz",
      "integrity": "sha512-UEZIS3/by4OC8vL3P2dTXRETpebLI2NiI5vIrjaD/5UtrkFX/tNbwjTSRAGC/+7CAo2pIcBaRgWmcBBHcsaCIw==",
      "dev": true,
      "license": "BlueOak-1.0.0"
    },
    "node_modules/parent-module": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/parent-module/-/parent-module-1.0.1.tgz",
      "integrity": "sha512-GQ2EWRpQV8/o+Aw8YqtfZZPfNRWZYkbidE9k5rpl/hC3vtHHBfGm2Ifi6qWV+coDGkrUKZAxE3Lot5kcsRlh+g==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "callsites": "^3.0.0"
      },
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/path-exists": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/path-exists/-/path-exists-4.0.0.tgz",
      "integrity": "sha512-ak9Qy5Q7jYb2Wwcey5Fpvg2KoAc/ZIhLSLOSBmRmygPsGwkVVt0fZa0qrtMz+m6tJTAHfZQ8FnmB4MG4LWy7/w==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/path-key": {
      "version": "3.1.1",
      "resolved": "https://registry.npmjs.org/path-key/-/path-key-3.1.1.tgz",
      "integrity": "sha512-ojmeN0qd+y0jszEtoY48r0Peq5dwMEkIlCOu6Q5f41lfkswXuKtYrhgoTpLnyIcHm24Uhqx+5Tqm2InSwLhE6Q==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/path-parse": {
      "version": "1.0.7",
      "resolved": "https://registry.npmjs.org/path-parse/-/path-parse-1.0.7.tgz",
      "integrity": "sha512-LDJzPVEEEPR+y48z93A0Ed0yXb8pAByGWo/k5YYdYgpY2/2EsOsksJrq7lOHxryrVOn1ejG6oAp8ahvOIQD8sw==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/path-scurry": {
      "version": "1.11.1",
      "resolved": "https://registry.npmjs.org/path-scurry/-/path-scurry-1.11.1.tgz",
      "integrity": "sha512-Xa4Nw17FS9ApQFJ9umLiJS4orGjm7ZzwUrwamcGQuHSzDyth9boKDaycYdDcZDuqYATXw4HFXgaqWTctW/v1HA==",
      "dev": true,
      "license": "BlueOak-1.0.0",
      "dependencies": {
        "lru-cache": "^10.2.0",
        "minipass": "^5.0.0 || ^6.0.2 || ^7.0.0"
      },
      "engines": {
        "node": ">=16 || 14 >=14.18"
      },
      "funding": {
        "url": "https://github.com/sponsors/isaacs"
      }
    },
    "node_modules/path-scurry/node_modules/lru-cache": {
      "version": "10.4.3",
      "resolved": "https://registry.npmjs.org/lru-cache/-/lru-cache-10.4.3.tgz",
      "integrity": "sha512-JNAzZcXrCt42VGLuYz0zfAzDfAvJWW6AfYlDBQyDV5DClI2m5sAmK+OIO7s59XfsRsWHp02jAJrRadPRGTt6SQ==",
      "dev": true,
      "license": "ISC"
    },
    "node_modules/picocolors": {
      "version": "1.1.1",
      "resolved": "https://registry.npmjs.org/picocolors/-/picocolors-1.1.1.tgz",
      "integrity": "sha512-xceH2snhtb5M9liqDsmEw56le376mTZkEX/jEb/RxNFyegNul7eNslCXP9FDj/Lcu0X8KEyMceP2ntpaHrDEVA==",
      "dev": true,
      "license": "ISC"
    },
    "node_modules/picomatch": {
      "version": "2.3.1",
      "resolved": "https://registry.npmjs.org/picomatch/-/picomatch-2.3.1.tgz",
      "integrity": "sha512-JU3teHTNjmE2VCGFzuY8EXzCDVwEqB2a8fsIvwaStHhAWJEeVd1o1QD80CU6+ZdEXXSLbSsuLwJjkCBWqRQUVA==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=8.6"
      },
      "funding": {
        "url": "https://github.com/sponsors/jonschlinkert"
      }
    },
    "node_modules/pify": {
      "version": "2.3.0",
      "resolved": "https://registry.npmjs.org/pify/-/pify-2.3.0.tgz",
      "integrity": "sha512-udgsAY+fTnvv7kI7aaxbqwWNb0AHiB0qBO89PZKPkoTmGOgdbrHDKD+0B2X4uTfJ/FT1R09r9gTsjUjNJotuog==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/pirates": {
      "version": "4.0.7",
      "resolved": "https://registry.npmjs.org/pirates/-/pirates-4.0.7.tgz",
      "integrity": "sha512-TfySrs/5nm8fQJDcBDuUng3VOUKsd7S+zqvbOTiGXHfxX4wK31ard+hoNuvkicM/2YFzlpDgABOevKSsB4G/FA==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">= 6"
      }
    },
    "node_modules/postcss": {
      "version": "8.5.3",
      "resolved": "https://registry.npmjs.org/postcss/-/postcss-8.5.3.tgz",
      "integrity": "sha512-dle9A3yYxlBSrt8Fu+IpjGT8SY8hN0mlaA6GY8t0P5PjIOZemULz/E2Bnm/2dcUOena75OTNkHI76uZBNUUq3A==",
      "dev": true,
      "funding": [
        {
          "type": "opencollective",
          "url": "https://opencollective.com/postcss/"
        },
        {
          "type": "tidelift",
          "url": "https://tidelift.com/funding/github/npm/postcss"
        },
        {
          "type": "github",
          "url": "https://github.com/sponsors/ai"
        }
      ],
      "license": "MIT",
      "dependencies": {
        "nanoid": "^3.3.8",
        "picocolors": "^1.1.1",
        "source-map-js": "^1.2.1"
      },
      "engines": {
        "node": "^10 || ^12 || >=14"
      }
    },
    "node_modules/postcss-import": {
      "version": "15.1.0",
      "resolved": "https://registry.npmjs.org/postcss-import/-/postcss-import-15.1.0.tgz",
      "integrity": "sha512-hpr+J05B2FVYUAXHeK1YyI267J/dDDhMU6B6civm8hSY1jYJnBXxzKDKDswzJmtLHryrjhnDjqqp/49t8FALew==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "postcss-value-parser": "^4.0.0",
        "read-cache": "^1.0.0",
        "resolve": "^1.1.7"
      },
      "engines": {
        "node": ">=14.0.0"
      },
      "peerDependencies": {
        "postcss": "^8.0.0"
      }
    },
    "node_modules/postcss-js": {
      "version": "4.0.1",
      "resolved": "https://registry.npmjs.org/postcss-js/-/postcss-js-4.0.1.tgz",
      "integrity": "sha512-dDLF8pEO191hJMtlHFPRa8xsizHaM82MLfNkUHdUtVEV3tgTp5oj+8qbEqYM57SLfc74KSbw//4SeJma2LRVIw==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "camelcase-css": "^2.0.1"
      },
      "engines": {
        "node": "^12 || ^14 || >= 16"
      },
      "funding": {
        "type": "opencollective",
        "url": "https://opencollective.com/postcss/"
      },
      "peerDependencies": {
        "postcss": "^8.4.21"
      }
    },
    "node_modules/postcss-load-config": {
      "version": "4.0.2",
      "resolved": "https://registry.npmjs.org/postcss-load-config/-/postcss-load-config-4.0.2.tgz",
      "integrity": "sha512-bSVhyJGL00wMVoPUzAVAnbEoWyqRxkjv64tUl427SKnPrENtq6hJwUojroMz2VB+Q1edmi4IfrAPpami5VVgMQ==",
      "dev": true,
      "funding": [
        {
          "type": "opencollective",
          "url": "https://opencollective.com/postcss/"
        },
        {
          "type": "github",
          "url": "https://github.com/sponsors/ai"
        }
      ],
      "license": "MIT",
      "dependencies": {
        "lilconfig": "^3.0.0",
        "yaml": "^2.3.4"
      },
      "engines": {
        "node": ">= 14"
      },
      "peerDependencies": {
        "postcss": ">=8.0.9",
        "ts-node": ">=9.0.0"
      },
      "peerDependenciesMeta": {
        "postcss": {
          "optional": true
        },
        "ts-node": {
          "optional": true
        }
      }
    },
    "node_modules/postcss-nested": {
      "version": "6.2.0",
      "resolved": "https://registry.npmjs.org/postcss-nested/-/postcss-nested-6.2.0.tgz",
      "integrity": "sha512-HQbt28KulC5AJzG+cZtj9kvKB93CFCdLvog1WFLf1D+xmMvPGlBstkpTEZfK5+AN9hfJocyBFCNiqyS48bpgzQ==",
      "dev": true,
      "funding": [
        {
          "type": "opencollective",
          "url": "https://opencollective.com/postcss/"
        },
        {
          "type": "github",
          "url": "https://github.com/sponsors/ai"
        }
      ],
      "license": "MIT",
      "dependencies": {
        "postcss-selector-parser": "^6.1.1"
      },
      "engines": {
        "node": ">=12.0"
      },
      "peerDependencies": {
        "postcss": "^8.2.14"
      }
    },
    "node_modules/postcss-selector-parser": {
      "version": "6.1.2",
      "resolved": "https://registry.npmjs.org/postcss-selector-parser/-/postcss-selector-parser-6.1.2.tgz",
      "integrity": "sha512-Q8qQfPiZ+THO/3ZrOrO0cJJKfpYCagtMUkXbnEfmgUjwXg6z/WBeOyS9APBBPCTSiDV+s4SwQGu8yFsiMRIudg==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "cssesc": "^3.0.0",
        "util-deprecate": "^1.0.2"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/postcss-value-parser": {
      "version": "4.2.0",
      "resolved": "https://registry.npmjs.org/postcss-value-parser/-/postcss-value-parser-4.2.0.tgz",
      "integrity": "sha512-1NNCs6uurfkVbeXG4S8JFT9t19m45ICnif8zWLd5oPSZ50QnwMfK+H3jv408d4jw/7Bttv5axS5IiHoLaVNHeQ==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/prelude-ls": {
      "version": "1.2.1",
      "resolved": "https://registry.npmjs.org/prelude-ls/-/prelude-ls-1.2.1.tgz",
      "integrity": "sha512-vkcDPrRZo1QZLbn5RLGPpg/WmIQ65qoWWhcGKf/b5eplkkarX0m9z8ppCat4mlOqUsWpyNuYgO3VRyrYHSzX5g==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">= 0.8.0"
      }
    },
    "node_modules/proxy-from-env": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/proxy-from-env/-/proxy-from-env-1.1.0.tgz",
      "integrity": "sha512-D+zkORCbA9f1tdWRK0RaCR3GPv50cMxcrz4X8k5LTSUD1Dkw47mKJEZQNunItRTkWwgtaUSo1RVFRIG9ZXiFYg==",
      "license": "MIT"
    },
    "node_modules/punycode": {
      "version": "2.3.1",
      "resolved": "https://registry.npmjs.org/punycode/-/punycode-2.3.1.tgz",
      "integrity": "sha512-vYt7UD1U9Wg6138shLtLOvdAu+8DsC/ilFtEVHcH+wydcSpNE20AfSOduf6MkRFahL5FY7X1oU7nKVZFtfq8Fg==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/queue-microtask": {
      "version": "1.2.3",
      "resolved": "https://registry.npmjs.org/queue-microtask/-/queue-microtask-1.2.3.tgz",
      "integrity": "sha512-NuaNSa6flKT5JaSYQzJok04JzTL1CA6aGhv5rfLW3PgqA+M2ChpZQnAC8h8i4ZFkBS8X5RqkDBHA7r4hej3K9A==",
      "dev": true,
      "funding": [
        {
          "type": "github",
          "url": "https://github.com/sponsors/feross"
        },
        {
          "type": "patreon",
          "url": "https://www.patreon.com/feross"
        },
        {
          "type": "consulting",
          "url": "https://feross.org/support"
        }
      ],
      "license": "MIT"
    },
    "node_modules/react": {
      "version": "19.1.0",
      "resolved": "https://registry.npmjs.org/react/-/react-19.1.0.tgz",
      "integrity": "sha512-FS+XFBNvn3GTAWq26joslQgWNoFu08F4kl0J4CgdNKADkdSGXQyTCnKteIAJy96Br6YbpEU1LSzV5dYtjMkMDg==",
      "license": "MIT",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/react-circular-progressbar": {
      "version": "2.2.0",
      "resolved": "https://registry.npmjs.org/react-circular-progressbar/-/react-circular-progressbar-2.2.0.tgz",
      "integrity": "sha512-cgyqEHOzB0nWMZjKfWN3MfSa1LV3OatcDjPz68lchXQUEiBD5O1WsAtoVK4/DSL0B4USR//cTdok4zCBkq8X5g==",
      "license": "MIT",
      "peerDependencies": {
        "react": ">=0.14.0"
      }
    },
    "node_modules/react-dom": {
      "version": "19.1.0",
      "resolved": "https://registry.npmjs.org/react-dom/-/react-dom-19.1.0.tgz",
      "integrity": "sha512-Xs1hdnE+DyKgeHJeJznQmYMIBG3TKIHJJT95Q58nHLSrElKlGQqDTR2HQ9fx5CN/Gk6Vh/kupBTDLU11/nDk/g==",
      "license": "MIT",
      "dependencies": {
        "scheduler": "^0.26.0"
      },
      "peerDependencies": {
        "react": "^19.1.0"
      }
    },
    "node_modules/react-icons": {
      "version": "5.5.0",
      "resolved": "https://registry.npmjs.org/react-icons/-/react-icons-5.5.0.tgz",
      "integrity": "sha512-MEFcXdkP3dLo8uumGI5xN3lDFNsRtrjbOEKDLD7yv76v4wpnEq2Lt2qeHaQOr34I/wPN3s3+N08WkQ+CW37Xiw==",
      "license": "MIT",
      "peerDependencies": {
        "react": "*"
      }
    },
    "node_modules/react-redux": {
      "version": "9.2.0",
      "resolved": "https://registry.npmjs.org/react-redux/-/react-redux-9.2.0.tgz",
      "integrity": "sha512-ROY9fvHhwOD9ySfrF0wmvu//bKCQ6AeZZq1nJNtbDC+kk5DuSuNX/n6YWYF/SYy7bSba4D4FSz8DJeKY/S/r+g==",
      "license": "MIT",
      "dependencies": {
        "@types/use-sync-external-store": "^0.0.6",
        "use-sync-external-store": "^1.4.0"
      },
      "peerDependencies": {
        "@types/react": "^18.2.25 || ^19",
        "react": "^18.0 || ^19",
        "redux": "^5.0.0"
      },
      "peerDependenciesMeta": {
        "@types/react": {
          "optional": true
        },
        "redux": {
          "optional": true
        }
      }
    },
    "node_modules/react-refresh": {
      "version": "0.14.2",
      "resolved": "https://registry.npmjs.org/react-refresh/-/react-refresh-0.14.2.tgz",
      "integrity": "sha512-jCvmsr+1IUSMUyzOkRcvnVbX3ZYC6g9TDrDbFuFmRDq7PD4yaGbLKNQL6k2jnArV8hjYxh7hVhAZB6s9HDGpZA==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/react-router": {
      "version": "7.4.1",
      "resolved": "https://registry.npmjs.org/react-router/-/react-router-7.4.1.tgz",
      "integrity": "sha512-Vmizn9ZNzxfh3cumddqv3kLOKvc7AskUT0dC1prTabhiEi0U4A33LmkDOJ79tXaeSqCqMBXBU/ySX88W85+EUg==",
      "license": "MIT",
      "dependencies": {
        "@types/cookie": "^0.6.0",
        "cookie": "^1.0.1",
        "set-cookie-parser": "^2.6.0",
        "turbo-stream": "2.4.0"
      },
      "engines": {
        "node": ">=20.0.0"
      },
      "peerDependencies": {
        "react": ">=18",
        "react-dom": ">=18"
      },
      "peerDependenciesMeta": {
        "react-dom": {
          "optional": true
        }
      }
    },
    "node_modules/react-router-dom": {
      "version": "7.4.1",
      "resolved": "https://registry.npmjs.org/react-router-dom/-/react-router-dom-7.4.1.tgz",
      "integrity": "sha512-L3/4tig0Lvs6m6THK0HRV4eHUdpx0dlJasgCxXKnavwhh4tKYgpuZk75HRYNoRKDyDWi9QgzGXsQ1oQSBlWpAA==",
      "license": "MIT",
      "dependencies": {
        "react-router": "7.4.1"
      },
      "engines": {
        "node": ">=20.0.0"
      },
      "peerDependencies": {
        "react": ">=18",
        "react-dom": ">=18"
      }
    },
    "node_modules/react-toastify": {
      "version": "11.0.5",
      "resolved": "https://registry.npmjs.org/react-toastify/-/react-toastify-11.0.5.tgz",
      "integrity": "sha512-EpqHBGvnSTtHYhCPLxML05NLY2ZX0JURbAdNYa6BUkk+amz4wbKBQvoKQAB0ardvSarUBuY4Q4s1sluAzZwkmA==",
      "license": "MIT",
      "dependencies": {
        "clsx": "^2.1.1"
      },
      "peerDependencies": {
        "react": "^18 || ^19",
        "react-dom": "^18 || ^19"
      }
    },
    "node_modules/read-cache": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/read-cache/-/read-cache-1.0.0.tgz",
      "integrity": "sha512-Owdv/Ft7IjOgm/i0xvNDZ1LrRANRfew4b2prF3OWMQLxLfu3bS8FVhCsrSCMK4lR56Y9ya+AThoTpDCTxCmpRA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "pify": "^2.3.0"
      }
    },
    "node_modules/readdirp": {
      "version": "3.6.0",
      "resolved": "https://registry.npmjs.org/readdirp/-/readdirp-3.6.0.tgz",
      "integrity": "sha512-hOS089on8RduqdbhvQ5Z37A0ESjsqz6qnRcffsMU3495FuTdqSm+7bhJ29JvIOsBDEEnan5DPu9t3To9VRlMzA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "picomatch": "^2.2.1"
      },
      "engines": {
        "node": ">=8.10.0"
      }
    },
    "node_modules/redux": {
      "version": "5.0.1",
      "resolved": "https://registry.npmjs.org/redux/-/redux-5.0.1.tgz",
      "integrity": "sha512-M9/ELqF6fy8FwmkpnF0S3YKOqMyoWJ4+CS5Efg2ct3oY9daQvd/Pc71FpGZsVsbl3Cpb+IIcjBDUnnyBdQbq4w==",
      "license": "MIT"
    },
    "node_modules/redux-thunk": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/redux-thunk/-/redux-thunk-3.1.0.tgz",
      "integrity": "sha512-NW2r5T6ksUKXCabzhL9z+h206HQw/NJkcLm1GPImRQ8IzfXwRGqjVhKJGauHirT0DAuyy6hjdnMZaRoAcy0Klw==",
      "license": "MIT",
      "peerDependencies": {
        "redux": "^5.0.0"
      }
    },
    "node_modules/reselect": {
      "version": "5.1.1",
      "resolved": "https://registry.npmjs.org/reselect/-/reselect-5.1.1.tgz",
      "integrity": "sha512-K/BG6eIky/SBpzfHZv/dd+9JBFiS4SWV7FIujVyJRux6e45+73RaUHXLmIR1f7WOMaQ0U1km6qwklRQxpJJY0w==",
      "license": "MIT"
    },
    "node_modules/resolve": {
      "version": "1.22.10",
      "resolved": "https://registry.npmjs.org/resolve/-/resolve-1.22.10.tgz",
      "integrity": "sha512-NPRy+/ncIMeDlTAsuqwKIiferiawhefFJtkNSW0qZJEqMEb+qBt/77B/jGeeek+F0uOeN05CDa6HXbbIgtVX4w==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "is-core-module": "^2.16.0",
        "path-parse": "^1.0.7",
        "supports-preserve-symlinks-flag": "^1.0.0"
      },
      "bin": {
        "resolve": "bin/resolve"
      },
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/resolve-from": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/resolve-from/-/resolve-from-4.0.0.tgz",
      "integrity": "sha512-pb/MYmXstAkysRFx8piNI1tGFNQIFA3vkE3Gq4EuA1dF6gHp/+vgZqsCGJapvy8N3Q+4o7FwvquPJcnZ7RYy4g==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/reusify": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/reusify/-/reusify-1.1.0.tgz",
      "integrity": "sha512-g6QUff04oZpHs0eG5p83rFLhHeV00ug/Yf9nZM6fLeUrPguBTkTQOdpAWWspMh55TZfVQDPaN3NQJfbVRAxdIw==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "iojs": ">=1.0.0",
        "node": ">=0.10.0"
      }
    },
    "node_modules/rollup": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/rollup/-/rollup-4.38.0.tgz",
      "integrity": "sha512-5SsIRtJy9bf1ErAOiFMFzl64Ex9X5V7bnJ+WlFMb+zmP459OSWCEG7b0ERZ+PEU7xPt4OG3RHbrp1LJlXxYTrw==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@types/estree": "1.0.7"
      },
      "bin": {
        "rollup": "dist/bin/rollup"
      },
      "engines": {
        "node": ">=18.0.0",
        "npm": ">=8.0.0"
      },
      "optionalDependencies": {
        "@rollup/rollup-android-arm-eabi": "4.38.0",
        "@rollup/rollup-android-arm64": "4.38.0",
        "@rollup/rollup-darwin-arm64": "4.38.0",
        "@rollup/rollup-darwin-x64": "4.38.0",
        "@rollup/rollup-freebsd-arm64": "4.38.0",
        "@rollup/rollup-freebsd-x64": "4.38.0",
        "@rollup/rollup-linux-arm-gnueabihf": "4.38.0",
        "@rollup/rollup-linux-arm-musleabihf": "4.38.0",
        "@rollup/rollup-linux-arm64-gnu": "4.38.0",
        "@rollup/rollup-linux-arm64-musl": "4.38.0",
        "@rollup/rollup-linux-loongarch64-gnu": "4.38.0",
        "@rollup/rollup-linux-powerpc64le-gnu": "4.38.0",
        "@rollup/rollup-linux-riscv64-gnu": "4.38.0",
        "@rollup/rollup-linux-riscv64-musl": "4.38.0",
        "@rollup/rollup-linux-s390x-gnu": "4.38.0",
        "@rollup/rollup-linux-x64-gnu": "4.38.0",
        "@rollup/rollup-linux-x64-musl": "4.38.0",
        "@rollup/rollup-win32-arm64-msvc": "4.38.0",
        "@rollup/rollup-win32-ia32-msvc": "4.38.0",
        "@rollup/rollup-win32-x64-msvc": "4.38.0",
        "fsevents": "~2.3.2"
      }
    },
    "node_modules/run-parallel": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/run-parallel/-/run-parallel-1.2.0.tgz",
      "integrity": "sha512-5l4VyZR86LZ/lDxZTR6jqL8AFE2S0IFLMP26AbjsLVADxHdhB/c0GUsH+y39UfCi3dzz8OlQuPmnaJOMoDHQBA==",
      "dev": true,
      "funding": [
        {
          "type": "github",
          "url": "https://github.com/sponsors/feross"
        },
        {
          "type": "patreon",
          "url": "https://www.patreon.com/feross"
        },
        {
          "type": "consulting",
          "url": "https://feross.org/support"
        }
      ],
      "license": "MIT",
      "dependencies": {
        "queue-microtask": "^1.2.2"
      }
    },
    "node_modules/scheduler": {
      "version": "0.26.0",
      "resolved": "https://registry.npmjs.org/scheduler/-/scheduler-0.26.0.tgz",
      "integrity": "sha512-NlHwttCI/l5gCPR3D1nNXtWABUmBwvZpEQiD4IXSbIDq8BzLIK/7Ir5gTFSGZDUu37K5cMNp0hFtzO38sC7gWA==",
      "license": "MIT"
    },
    "node_modules/semver": {
      "version": "6.3.1",
      "resolved": "https://registry.npmjs.org/semver/-/semver-6.3.1.tgz",
      "integrity": "sha512-BR7VvDCVHO+q2xBEWskxS6DJE1qRnb7DxzUrogb71CWoSficBxYsiAGd+Kl0mmq/MprG9yArRkyrQxTO6XjMzA==",
      "dev": true,
      "license": "ISC",
      "bin": {
        "semver": "bin/semver.js"
      }
    },
    "node_modules/set-cookie-parser": {
      "version": "2.7.1",
      "resolved": "https://registry.npmjs.org/set-cookie-parser/-/set-cookie-parser-2.7.1.tgz",
      "integrity": "sha512-IOc8uWeOZgnb3ptbCURJWNjWUPcO3ZnTTdzsurqERrP6nPyv+paC55vJM0LpOlT2ne+Ix+9+CRG1MNLlyZ4GjQ==",
      "license": "MIT"
    },
    "node_modules/shebang-command": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/shebang-command/-/shebang-command-2.0.0.tgz",
      "integrity": "sha512-kHxr2zZpYtdmrN1qDjrrX/Z1rR1kG8Dx+gkpK1G4eXmvXswmcE1hTWBWYUzlraYw1/yZp6YuDY77YtvbN0dmDA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "shebang-regex": "^3.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/shebang-regex": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/shebang-regex/-/shebang-regex-3.0.0.tgz",
      "integrity": "sha512-7++dFhtcx3353uBaq8DDR4NuxBetBzC7ZQOhmTQInHEd6bSrXdiEyzCvG07Z44UYdLShWUyXt5M/yhz8ekcb1A==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/signal-exit": {
      "version": "4.1.0",
      "resolved": "https://registry.npmjs.org/signal-exit/-/signal-exit-4.1.0.tgz",
      "integrity": "sha512-bzyZ1e88w9O1iNJbKnOlvYTrWPDl46O1bG0D3XInv+9tkPrxrN8jUUTiFlDkkmKWgn1M6CfIA13SuGqOa9Korw==",
      "dev": true,
      "license": "ISC",
      "engines": {
        "node": ">=14"
      },
      "funding": {
        "url": "https://github.com/sponsors/isaacs"
      }
    },
    "node_modules/source-map-js": {
      "version": "1.2.1",
      "resolved": "https://registry.npmjs.org/source-map-js/-/source-map-js-1.2.1.tgz",
      "integrity": "sha512-UXWMKhLOwVKb728IUtQPXxfYU+usdybtUrK/8uGE8CQMvrhOpwvzDBwj0QhSL7MQc7vIsISBG8VQ8+IDQxpfQA==",
      "dev": true,
      "license": "BSD-3-Clause",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/string-width": {
      "version": "5.1.2",
      "resolved": "https://registry.npmjs.org/string-width/-/string-width-5.1.2.tgz",
      "integrity": "sha512-HnLOCR3vjcY8beoNLtcjZ5/nxn2afmME6lhrDrebokqMap+XbeW8n9TXpPDOqdGK5qcI3oT0GKTW6wC7EMiVqA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "eastasianwidth": "^0.2.0",
        "emoji-regex": "^9.2.2",
        "strip-ansi": "^7.0.1"
      },
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/string-width-cjs": {
      "name": "string-width",
      "version": "4.2.3",
      "resolved": "https://registry.npmjs.org/string-width/-/string-width-4.2.3.tgz",
      "integrity": "sha512-wKyQRQpjJ0sIp62ErSZdGsjMJWsap5oRNihHhu6G7JVO/9jIB6UyevL+tXuOqrng8j/cxKTWyWUwvSTriiZz/g==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "emoji-regex": "^8.0.0",
        "is-fullwidth-code-point": "^3.0.0",
        "strip-ansi": "^6.0.1"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/string-width-cjs/node_modules/ansi-regex": {
      "version": "5.0.1",
      "resolved": "https://registry.npmjs.org/ansi-regex/-/ansi-regex-5.0.1.tgz",
      "integrity": "sha512-quJQXlTSUGL2LH9SUXo8VwsY4soanhgo6LNSm84E1LBcE8s3O0wpdiRzyR9z/ZZJMlMWv37qOOb9pdJlMUEKFQ==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/string-width-cjs/node_modules/emoji-regex": {
      "version": "8.0.0",
      "resolved": "https://registry.npmjs.org/emoji-regex/-/emoji-regex-8.0.0.tgz",
      "integrity": "sha512-MSjYzcWNOA0ewAHpz0MxpYFvwg6yjy1NG3xteoqz644VCo/RPgnr1/GGt+ic3iJTzQ8Eu3TdM14SawnVUmGE6A==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/string-width-cjs/node_modules/strip-ansi": {
      "version": "6.0.1",
      "resolved": "https://registry.npmjs.org/strip-ansi/-/strip-ansi-6.0.1.tgz",
      "integrity": "sha512-Y38VPSHcqkFrCpFnQ9vuSXmquuv5oXOKpGeT6aGrr3o3Gc9AlVa6JBfUSOCnbxGGZF+/0ooI7KrPuUSztUdU5A==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "ansi-regex": "^5.0.1"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/strip-ansi": {
      "version": "7.1.0",
      "resolved": "https://registry.npmjs.org/strip-ansi/-/strip-ansi-7.1.0.tgz",
      "integrity": "sha512-iq6eVVI64nQQTRYq2KtEg2d2uU7LElhTJwsH4YzIHZshxlgZms/wIc4VoDQTlG/IvVIrBKG06CrZnp0qv7hkcQ==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "ansi-regex": "^6.0.1"
      },
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/chalk/strip-ansi?sponsor=1"
      }
    },
    "node_modules/strip-ansi-cjs": {
      "name": "strip-ansi",
      "version": "6.0.1",
      "resolved": "https://registry.npmjs.org/strip-ansi/-/strip-ansi-6.0.1.tgz",
      "integrity": "sha512-Y38VPSHcqkFrCpFnQ9vuSXmquuv5oXOKpGeT6aGrr3o3Gc9AlVa6JBfUSOCnbxGGZF+/0ooI7KrPuUSztUdU5A==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "ansi-regex": "^5.0.1"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/strip-ansi-cjs/node_modules/ansi-regex": {
      "version": "5.0.1",
      "resolved": "https://registry.npmjs.org/ansi-regex/-/ansi-regex-5.0.1.tgz",
      "integrity": "sha512-quJQXlTSUGL2LH9SUXo8VwsY4soanhgo6LNSm84E1LBcE8s3O0wpdiRzyR9z/ZZJMlMWv37qOOb9pdJlMUEKFQ==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/strip-json-comments": {
      "version": "3.1.1",
      "resolved": "https://registry.npmjs.org/strip-json-comments/-/strip-json-comments-3.1.1.tgz",
      "integrity": "sha512-6fPc+R4ihwqP6N/aIv2f1gMH8lOVtWQHoqC4yK6oSDVVocumAsfCqjkXnqiYMhmMwS/mEHLp7Vehlt3ql6lEig==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/sucrase": {
      "version": "3.35.0",
      "resolved": "https://registry.npmjs.org/sucrase/-/sucrase-3.35.0.tgz",
      "integrity": "sha512-8EbVDiu9iN/nESwxeSxDKe0dunta1GOlHufmSSXxMD2z2/tMZpDMpvXQGsc+ajGo8y2uYUmixaSRUc/QPoQ0GA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@jridgewell/gen-mapping": "^0.3.2",
        "commander": "^4.0.0",
        "glob": "^10.3.10",
        "lines-and-columns": "^1.1.6",
        "mz": "^2.7.0",
        "pirates": "^4.0.1",
        "ts-interface-checker": "^0.1.9"
      },
      "bin": {
        "sucrase": "bin/sucrase",
        "sucrase-node": "bin/sucrase-node"
      },
      "engines": {
        "node": ">=16 || 14 >=14.17"
      }
    },
    "node_modules/supports-color": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
      "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "has-flag": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/supports-preserve-symlinks-flag": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/supports-preserve-symlinks-flag/-/supports-preserve-symlinks-flag-1.0.0.tgz",
      "integrity": "sha512-ot0WnXS9fgdkgIcePe6RHNk1WA8+muPa6cSjeR3V8K27q9BB1rTE3R1p7Hv0z1ZyAc8s6Vvv8DIyWf681MAt0w==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/tailwindcss": {
      "version": "3.4.17",
      "resolved": "https://registry.npmjs.org/tailwindcss/-/tailwindcss-3.4.17.tgz",
      "integrity": "sha512-w33E2aCvSDP0tW9RZuNXadXlkHXqFzSkQew/aIa2i/Sj8fThxwovwlXHSPXTbAHwEIhBFXAedUhP2tueAKP8Og==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@alloc/quick-lru": "^5.2.0",
        "arg": "^5.0.2",
        "chokidar": "^3.6.0",
        "didyoumean": "^1.2.2",
        "dlv": "^1.1.3",
        "fast-glob": "^3.3.2",
        "glob-parent": "^6.0.2",
        "is-glob": "^4.0.3",
        "jiti": "^1.21.6",
        "lilconfig": "^3.1.3",
        "micromatch": "^4.0.8",
        "normalize-path": "^3.0.0",
        "object-hash": "^3.0.0",
        "picocolors": "^1.1.1",
        "postcss": "^8.4.47",
        "postcss-import": "^15.1.0",
        "postcss-js": "^4.0.1",
        "postcss-load-config": "^4.0.2",
        "postcss-nested": "^6.2.0",
        "postcss-selector-parser": "^6.1.2",
        "resolve": "^1.22.8",
        "sucrase": "^3.35.0"
      },
      "bin": {
        "tailwind": "lib/cli.js",
        "tailwindcss": "lib/cli.js"
      },
      "engines": {
        "node": ">=14.0.0"
      }
    },
    "node_modules/thenify": {
      "version": "3.3.1",
      "resolved": "https://registry.npmjs.org/thenify/-/thenify-3.3.1.tgz",
      "integrity": "sha512-RVZSIV5IG10Hk3enotrhvz0T9em6cyHBLkH/YAZuKqd8hRkKhSfCGIcP2KUY0EPxndzANBmNllzWPwak+bheSw==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "any-promise": "^1.0.0"
      }
    },
    "node_modules/thenify-all": {
      "version": "1.6.0",
      "resolved": "https://registry.npmjs.org/thenify-all/-/thenify-all-1.6.0.tgz",
      "integrity": "sha512-RNxQH/qI8/t3thXJDwcstUO4zeqo64+Uy/+sNVRBx4Xn2OX+OZ9oP+iJnNFqplFra2ZUVeKCSa2oVWi3T4uVmA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "thenify": ">= 3.1.0 < 4"
      },
      "engines": {
        "node": ">=0.8"
      }
    },
    "node_modules/to-regex-range": {
      "version": "5.0.1",
      "resolved": "https://registry.npmjs.org/to-regex-range/-/to-regex-range-5.0.1.tgz",
      "integrity": "sha512-65P7iz6X5yEr1cwcgvQxbbIw7Uk3gOy5dIdtZ4rDveLqhrdJP+Li/Hx6tyK0NEb+2GCyneCMJiGqrADCSNk8sQ==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "is-number": "^7.0.0"
      },
      "engines": {
        "node": ">=8.0"
      }
    },
    "node_modules/ts-interface-checker": {
      "version": "0.1.13",
      "resolved": "https://registry.npmjs.org/ts-interface-checker/-/ts-interface-checker-0.1.13.tgz",
      "integrity": "sha512-Y/arvbn+rrz3JCKl9C4kVNfTfSm2/mEp5FSz5EsZSANGPSlQrpRI5M4PKF+mJnE52jOO90PnPSc3Ur3bTQw0gA==",
      "dev": true,
      "license": "Apache-2.0"
    },
    "node_modules/tslib": {
      "version": "2.8.1",
      "resolved": "https://registry.npmjs.org/tslib/-/tslib-2.8.1.tgz",
      "integrity": "sha512-oJFu94HQb+KVduSUQL7wnpmqnfmLsOA/nAh6b6EH0wCEoK0/mPeXU6c3wKDV83MkOuHPRHtSXKKU99IBazS/2w==",
      "license": "0BSD"
    },
    "node_modules/turbo-stream": {
      "version": "2.4.0",
      "resolved": "https://registry.npmjs.org/turbo-stream/-/turbo-stream-2.4.0.tgz",
      "integrity": "sha512-FHncC10WpBd2eOmGwpmQsWLDoK4cqsA/UT/GqNoaKOQnT8uzhtCbg3EoUDMvqpOSAI0S26mr0rkjzbOO6S3v1g==",
      "license": "ISC"
    },
    "node_modules/type-check": {
      "version": "0.4.0",
      "resolved": "https://registry.npmjs.org/type-check/-/type-check-0.4.0.tgz",
      "integrity": "sha512-XleUoc9uwGXqjWwXaUTZAmzMcFZ5858QA2vvx1Ur5xIcixXIP+8LnFDgRplU30us6teqdlskFfu+ae4K79Ooew==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "prelude-ls": "^1.2.1"
      },
      "engines": {
        "node": ">= 0.8.0"
      }
    },
    "node_modules/update-browserslist-db": {
      "version": "1.1.3",
      "resolved": "https://registry.npmjs.org/update-browserslist-db/-/update-browserslist-db-1.1.3.tgz",
      "integrity": "sha512-UxhIZQ+QInVdunkDAaiazvvT/+fXL5Osr0JZlJulepYu6Jd7qJtDZjlur0emRlT71EN3ScPoE7gvsuIKKNavKw==",
      "dev": true,
      "funding": [
        {
          "type": "opencollective",
          "url": "https://opencollective.com/browserslist"
        },
        {
          "type": "tidelift",
          "url": "https://tidelift.com/funding/github/npm/browserslist"
        },
        {
          "type": "github",
          "url": "https://github.com/sponsors/ai"
        }
      ],
      "license": "MIT",
      "dependencies": {
        "escalade": "^3.2.0",
        "picocolors": "^1.1.1"
      },
      "bin": {
        "update-browserslist-db": "cli.js"
      },
      "peerDependencies": {
        "browserslist": ">= 4.21.0"
      }
    },
    "node_modules/uri-js": {
      "version": "4.4.1",
      "resolved": "https://registry.npmjs.org/uri-js/-/uri-js-4.4.1.tgz",
      "integrity": "sha512-7rKUyy33Q1yc98pQ1DAmLtwX109F7TIfWlW1Ydo8Wl1ii1SeHieeh0HHfPeL2fMXK6z0s8ecKs9frCuLJvndBg==",
      "dev": true,
      "license": "BSD-2-Clause",
      "dependencies": {
        "punycode": "^2.1.0"
      }
    },
    "node_modules/use-sync-external-store": {
      "version": "1.5.0",
      "resolved": "https://registry.npmjs.org/use-sync-external-store/-/use-sync-external-store-1.5.0.tgz",
      "integrity": "sha512-Rb46I4cGGVBmjamjphe8L/UnvJD+uPPtTkNvX5mZgqdbavhI4EbgIWJiIHXJ8bc/i9EQGPRh4DwEURJ552Do0A==",
      "license": "MIT",
      "peerDependencies": {
        "react": "^16.8.0 || ^17.0.0 || ^18.0.0 || ^19.0.0"
      }
    },
    "node_modules/util-deprecate": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/util-deprecate/-/util-deprecate-1.0.2.tgz",
      "integrity": "sha512-EPD5q1uXyFxJpCrLnCc1nHnq3gOa6DZBocAIiI2TaSCA7VCJ1UJDMagCzIkXNsUYfD1daK//LTEQ8xiIbrHtcw==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/vite": {
      "version": "6.2.4",
      "resolved": "https://registry.npmjs.org/vite/-/vite-6.2.4.tgz",
      "integrity": "sha512-veHMSew8CcRzhL5o8ONjy8gkfmFJAd5Ac16oxBUjlwgX3Gq2Wqr+qNC3TjPIpy7TPV/KporLga5GT9HqdrCizw==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "esbuild": "^0.25.0",
        "postcss": "^8.5.3",
        "rollup": "^4.30.1"
      },
      "bin": {
        "vite": "bin/vite.js"
      },
      "engines": {
        "node": "^18.0.0 || ^20.0.0 || >=22.0.0"
      },
      "funding": {
        "url": "https://github.com/vitejs/vite?sponsor=1"
      },
      "optionalDependencies": {
        "fsevents": "~2.3.3"
      },
      "peerDependencies": {
        "@types/node": "^18.0.0 || ^20.0.0 || >=22.0.0",
        "jiti": ">=1.21.0",
        "less": "*",
        "lightningcss": "^1.21.0",
        "sass": "*",
        "sass-embedded": "*",
        "stylus": "*",
        "sugarss": "*",
        "terser": "^5.16.0",
        "tsx": "^4.8.1",
        "yaml": "^2.4.2"
      },
      "peerDependenciesMeta": {
        "@types/node": {
          "optional": true
        },
        "jiti": {
          "optional": true
        },
        "less": {
          "optional": true
        },
        "lightningcss": {
          "optional": true
        },
        "sass": {
          "optional": true
        },
        "sass-embedded": {
          "optional": true
        },
        "stylus": {
          "optional": true
        },
        "sugarss": {
          "optional": true
        },
        "terser": {
          "optional": true
        },
        "tsx": {
          "optional": true
        },
        "yaml": {
          "optional": true
        }
      }
    },
    "node_modules/which": {
      "version": "2.0.2",
      "resolved": "https://registry.npmjs.org/which/-/which-2.0.2.tgz",
      "integrity": "sha512-BLI3Tl1TW3Pvl70l3yq3Y64i+awpwXqsGBYWkkqMtnbXgrMD+yj7rhW0kuEDxzJaYXGjEW5ogapKNMEKNMjibA==",
      "dev": true,
      "license": "ISC",
      "dependencies": {
        "isexe": "^2.0.0"
      },
      "bin": {
        "node-which": "bin/node-which"
      },
      "engines": {
        "node": ">= 8"
      }
    },
    "node_modules/word-wrap": {
      "version": "1.2.5",
      "resolved": "https://registry.npmjs.org/word-wrap/-/word-wrap-1.2.5.tgz",
      "integrity": "sha512-BN22B5eaMMI9UMtjrGd5g5eCYPpCPDUy0FJXbYsaT5zYxjFOckS53SQDE3pWkVoWpHXVb3BrYcEN4Twa55B5cA==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/wrap-ansi": {
      "version": "8.1.0",
      "resolved": "https://registry.npmjs.org/wrap-ansi/-/wrap-ansi-8.1.0.tgz",
      "integrity": "sha512-si7QWI6zUMq56bESFvagtmzMdGOtoxfR+Sez11Mobfc7tm+VkUckk9bW2UeffTGVUbOksxmSw0AA2gs8g71NCQ==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "ansi-styles": "^6.1.0",
        "string-width": "^5.0.1",
        "strip-ansi": "^7.0.1"
      },
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/chalk/wrap-ansi?sponsor=1"
      }
    },
    "node_modules/wrap-ansi-cjs": {
      "name": "wrap-ansi",
      "version": "7.0.0",
      "resolved": "https://registry.npmjs.org/wrap-ansi/-/wrap-ansi-7.0.0.tgz",
      "integrity": "sha512-YVGIj2kamLSTxw6NsZjoBxfSwsn0ycdesmc4p+Q21c5zPuZ1pl+NfxVdxPtdHvmNVOQ6XSYG4AUtyt/Fi7D16Q==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "ansi-styles": "^4.0.0",
        "string-width": "^4.1.0",
        "strip-ansi": "^6.0.0"
      },
      "engines": {
        "node": ">=10"
      },
      "funding": {
        "url": "https://github.com/chalk/wrap-ansi?sponsor=1"
      }
    },
    "node_modules/wrap-ansi-cjs/node_modules/ansi-regex": {
      "version": "5.0.1",
      "resolved": "https://registry.npmjs.org/ansi-regex/-/ansi-regex-5.0.1.tgz",
      "integrity": "sha512-quJQXlTSUGL2LH9SUXo8VwsY4soanhgo6LNSm84E1LBcE8s3O0wpdiRzyR9z/ZZJMlMWv37qOOb9pdJlMUEKFQ==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/wrap-ansi-cjs/node_modules/emoji-regex": {
      "version": "8.0.0",
      "resolved": "https://registry.npmjs.org/emoji-regex/-/emoji-regex-8.0.0.tgz",
      "integrity": "sha512-MSjYzcWNOA0ewAHpz0MxpYFvwg6yjy1NG3xteoqz644VCo/RPgnr1/GGt+ic3iJTzQ8Eu3TdM14SawnVUmGE6A==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/wrap-ansi-cjs/node_modules/string-width": {
      "version": "4.2.3",
      "resolved": "https://registry.npmjs.org/string-width/-/string-width-4.2.3.tgz",
      "integrity": "sha512-wKyQRQpjJ0sIp62ErSZdGsjMJWsap5oRNihHhu6G7JVO/9jIB6UyevL+tXuOqrng8j/cxKTWyWUwvSTriiZz/g==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "emoji-regex": "^8.0.0",
        "is-fullwidth-code-point": "^3.0.0",
        "strip-ansi": "^6.0.1"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/wrap-ansi-cjs/node_modules/strip-ansi": {
      "version": "6.0.1",
      "resolved": "https://registry.npmjs.org/strip-ansi/-/strip-ansi-6.0.1.tgz",
      "integrity": "sha512-Y38VPSHcqkFrCpFnQ9vuSXmquuv5oXOKpGeT6aGrr3o3Gc9AlVa6JBfUSOCnbxGGZF+/0ooI7KrPuUSztUdU5A==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "ansi-regex": "^5.0.1"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/wrap-ansi/node_modules/ansi-styles": {
      "version": "6.2.1",
      "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-6.2.1.tgz",
      "integrity": "sha512-bN798gFfQX+viw3R7yrGWRqnrN2oRkEkUjjl4JNn4E8GxxbjtG3FbrEIIY3l8/hrwUwIeCZvi4QuOTP4MErVug==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-styles?sponsor=1"
      }
    },
    "node_modules/yallist": {
      "version": "3.1.1",
      "resolved": "https://registry.npmjs.org/yallist/-/yallist-3.1.1.tgz",
      "integrity": "sha512-a4UGQaWPH59mOXUYnAG2ewncQS4i4F43Tv3JoAM+s2VDAmS9NsK8GpDMLrCHPksFT7h3K6TOoUNn2pb7RoXx4g==",
      "dev": true,
      "license": "ISC"
    },
    "node_modules/yaml": {
      "version": "2.7.1",
      "resolved": "https://registry.npmjs.org/yaml/-/yaml-2.7.1.tgz",
      "integrity": "sha512-10ULxpnOCQXxJvBgxsn9ptjq6uviG/htZKk9veJGhlqn3w/DxQ631zFF+nlQXLwmImeS5amR2dl2U8sg6U9jsQ==",
      "dev": true,
      "license": "ISC",
      "bin": {
        "yaml": "bin.mjs"
      },
      "engines": {
        "node": ">= 14"
      }
    },
    "node_modules/yocto-queue": {
      "version": "0.1.0",
      "resolved": "https://registry.npmjs.org/yocto-queue/-/yocto-queue-0.1.0.tgz",
      "integrity": "sha512-rVksvsnNCdJ/ohGc6xgPwyN8eheCxsiLM8mxuE/t/mOVqJewPuO1miLpTHQiRgTKCLexL4MeAFVagts7HmNZ2Q==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=10"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    }
  }
}

```

### `frontend\package.json`

```json
{
  "name": "frontend",
  "private": true,
  "version": "0.0.0",
  "type": "module",
  "scripts": {
    "dev": "vite",
    "build": "vite build",
    "lint": "eslint .",
    "preview": "vite preview"
  },
  "dependencies": {
    "@faker-js/faker": "^9.7.0",
    "@reduxjs/toolkit": "^2.6.1",
    "argon2-browser": "^1.18.0",
    "axios": "^1.8.4",
    "crypto-js": "^4.2.0",
    "dompurify": "^3.2.5",
    "framer-motion": "^12.6.5",
    "lodash": "^4.17.21",
    "lucide-react": "^0.486.0",
    "react": "^19.0.0",
    "react-circular-progressbar": "^2.2.0",
    "react-dom": "^19.0.0",
    "react-icons": "^5.5.0",
    "react-redux": "^9.2.0",
    "react-router-dom": "^7.4.1",
    "react-toastify": "^11.0.5"
  },
  "devDependencies": {
    "@eslint/js": "^9.21.0",
    "@types/react": "^19.0.10",
    "@types/react-dom": "^19.0.4",
    "@vitejs/plugin-react": "^4.3.4",
    "autoprefixer": "^10.4.21",
    "eslint": "^9.21.0",
    "eslint-plugin-react-hooks": "^5.1.0",
    "eslint-plugin-react-refresh": "^0.4.19",
    "globals": "^15.15.0",
    "postcss": "^8.5.3",
    "tailwindcss": "^3.4.17",
    "vite": "^6.2.0"
  }
}

```

### `frontend\postcss.config.js`

```javascript
export default {
  plugins: {
    tailwindcss: {},
    autoprefixer: {},
  },
}

```

### `frontend\public\vite.svg`

```
<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" role="img" class="iconify iconify--logos" width="31.88" height="32" preserveAspectRatio="xMidYMid meet" viewBox="0 0 256 257"><defs><linearGradient id="IconifyId1813088fe1fbc01fb466" x1="-.828%" x2="57.636%" y1="7.652%" y2="78.411%"><stop offset="0%" stop-color="#41D1FF"></stop><stop offset="100%" stop-color="#BD34FE"></stop></linearGradient><linearGradient id="IconifyId1813088fe1fbc01fb467" x1="43.376%" x2="50.316%" y1="2.242%" y2="89.03%"><stop offset="0%" stop-color="#FFEA83"></stop><stop offset="8.333%" stop-color="#FFDD35"></stop><stop offset="100%" stop-color="#FFA800"></stop></linearGradient></defs><path fill="url(#IconifyId1813088fe1fbc01fb466)" d="M255.153 37.938L134.897 252.976c-2.483 4.44-8.862 4.466-11.382.048L.875 37.958c-2.746-4.814 1.371-10.646 6.827-9.67l120.385 21.517a6.537 6.537 0 0 0 2.322-.004l117.867-21.483c5.438-.991 9.574 4.796 6.877 9.62Z"></path><path fill="url(#IconifyId1813088fe1fbc01fb467)" d="M185.432.063L96.44 17.501a3.268 3.268 0 0 0-2.634 3.014l-5.474 92.456a3.268 3.268 0 0 0 3.997 3.378l24.777-5.718c2.318-.535 4.413 1.507 3.936 3.838l-7.361 36.047c-.495 2.426 1.782 4.5 4.151 3.78l15.304-4.649c2.372-.72 4.652 1.36 4.15 3.788l-11.698 56.621c-.732 3.542 3.979 5.473 5.943 2.437l1.313-2.028l72.516-144.72c1.215-2.423-.88-5.186-3.54-4.672l-25.505 4.922c-2.396.462-4.435-1.77-3.759-4.114l16.646-57.705c.677-2.35-1.37-4.583-3.769-4.113Z"></path></svg>
```

### `frontend\README.md`

```markdown
# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript and enable type-aware lint rules. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

```

### `frontend\src\app\slices\sharedAppsSlice.js`

```javascript
import { createSlice } from "@reduxjs/toolkit";

const initialState = {
  sharedApps: [],
};

const sharedAppsSlice = createSlice({
  name: "sharedApps",
  initialState,
  reducers: {
    setSharedAppsData: (state, action) => {
      state.sharedApps = action.payload;
    },
    addSharedApp: (state, action) => {
      state.sharedApps.push(action.payload);
    },
    removeSharedApp: (state, action) => {
      state.sharedApps = state.sharedApps.filter(
        (app) => app._id !== action.payload
      );
    },
    updateSharedAppLocal: (state, action) => {
      const index = state.sharedApps.findIndex(app => app._id === action.payload._id);
      if (index !== -1) {
        state.sharedApps[index] = action.payload;
      }
    },
  },
});

export const {
  setSharedAppsData,
  addSharedApp,
  removeSharedApp,
  updateSharedAppLocal,
} = sharedAppsSlice.actions;

export default sharedAppsSlice.reducer;
```

### `frontend\src\app\slices\ThemeSlice.js`

```javascript
import { createSlice } from '@reduxjs/toolkit'

const initialState = {
    darkTheme: localStorage.getItem("darkTheme") === "true" ? true : false,  
  }

export const themeSlice = createSlice({
    name: 'theme',
    initialState,
    reducers: {
        toggleTheme: (state) => {
            //save to local storage
            localStorage.setItem('darkTheme', !state.darkTheme)
            state.darkTheme = !state.darkTheme
        },
    },
})


export default themeSlice.reducer

// Action creators are generated for each case reducer function
export const { toggleTheme } = themeSlice.actions
```

### `frontend\src\app\slices\userSlice.js`

```javascript
import { createSlice } from "@reduxjs/toolkit";

const initialState = {
    
} // initial state of the user slice

const userSlice = createSlice({
    name:"user", 
    initialState,
    reducers:{
        setUser: (state, action) => {
            state.user = action.payload; // set user in the state
        },
        removeUser: (state) => {
            state.user = null; // remove user from the state
        },
    }
})


export default userSlice.reducer // export the reducer


export const { setUser, removeUser } = userSlice.actions // export the actions
```

### `frontend\src\app\slices\vaultSlice.js`

```javascript
import { createSlice } from '@reduxjs/toolkit';

const vaultSlice = createSlice({
  name: 'vault',
  initialState: {
    unlocked: false,
  },
  reducers: {
    setVaultUnlocked: (state, action) => {
      state.unlocked = action.payload;
    },
    resetVault: (state) => {
      state.unlocked = false;
    },
  },
});

export const { setVaultUnlocked, resetVault } = vaultSlice.actions;
export default vaultSlice.reducer;

```

### `frontend\src\app\Store.js`

```javascript
import { configureStore } from '@reduxjs/toolkit'
import themeReducer from './slices/ThemeSlice'
import userReducer from './slices/userSlice'
import sharedAppsReducer from './slices/sharedAppsSlice';
import vaultReducer from './slices/vaultSlice';
const store = configureStore({
  reducer: {
    theme: themeReducer,
    user: userReducer,
    sharedApps: sharedAppsReducer,
    vault: vaultReducer, 

  }
})

export default store
```

### `frontend\src\App.jsx`

```javascript
import React from "react";
import AppRoutes from "./Routes/AppRoutes";
import { ToastContainer } from "react-toastify";
import NavBar from "./components/NavBar/NavBar";
import Protected from "./HOC/Protected";

const App = () => {
  return (
    <div>
      <NavBar />

      <AppRoutes />
      <ToastContainer />
    </div>
  );
};

export default App;

```

### `frontend\src\assets\loader.svg`

```
﻿<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 200 200'><path fill='#452A72' stroke='#452A72' stroke-width='15' transform-origin='center' d='m148 84.7 13.8-8-10-17.3-13.8 8a50 50 0 0 0-27.4-15.9v-16h-20v16A50 50 0 0 0 63 67.4l-13.8-8-10 17.3 13.8 8a50 50 0 0 0 0 31.7l-13.8 8 10 17.3 13.8-8a50 50 0 0 0 27.5 15.9v16h20v-16a50 50 0 0 0 27.4-15.9l13.8 8 10-17.3-13.8-8a50 50 0 0 0 0-31.7Zm-47.5 50.8a35 35 0 1 1 0-70 35 35 0 0 1 0 70Z'><animateTransform type='rotate' attributeName='transform' calcMode='spline' dur='2' values='0;120' keyTimes='0;1' keySplines='0 0 1 1' repeatCount='indefinite'></animateTransform></path></svg>
```

### `frontend\src\assets\PrevGuard.svg`

```
<!DOCTYPE svg PUBLIC "-//W3C//DTD SVG 1.1//EN" "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd">
<!-- Uploaded to: SVG Repo, www.svgrepo.com, Transformed by: SVG Repo Mixer Tools -->
<svg height="800px" width="800px" version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 512.001 512.001" xml:space="preserve" fill="##221736" stroke="##221736">
<g id="SVGRepo_bgCarrier" stroke-width="0"/>
<g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"/>
<g id="SVGRepo_iconCarrier"> <path style="fill:#A66CFF ;" d="M205.949,173.83c29.881,0,43.286,16.747,48.561,26.585c0.663,1.235,2.461,1.233,3.121-0.003 c5.257-9.838,18.589-26.582,48.466-26.582c34.035,0,63.975,23.233,63.975,65.659c0,17.168-3.498,31.876-13.208,48.289 c-19.789,33.45-84.977,76.812-98.368,85.357c-1.48,0.945-3.355,0.948-4.838,0.006c-13.401-8.504-78.602-51.651-98.546-85.363 c-9.71-16.414-13.185-31.121-13.185-48.289C141.925,197.063,171.912,173.83,205.949,173.83z"/> <g> <path style="fill:#A66CFF ;" d="M256.069,388.356c-3.61,0-7.133-1.024-10.188-2.961c-8.175-5.189-80.523-51.791-103.261-90.226 c-10.517-17.778-15.207-34.949-15.207-55.678c0-24.068,8.226-44.568,23.789-59.282c14.245-13.47,33.687-20.887,54.745-20.887 c24.555,0,40.392,9.59,50.108,19.242c9.7-9.654,25.509-19.242,50.041-19.242c21.057,0,40.492,7.419,54.725,20.892 c15.543,14.713,23.76,35.212,23.76,59.278c0,20.701-4.697,37.873-15.231,55.678c-22.578,38.164-94.881,84.987-103.052,90.2 C263.233,387.323,259.697,388.356,256.069,388.356z M205.949,188.34c-24.645,0-49.514,15.816-49.514,51.149 c0,15.649,3.234,27.499,11.164,40.901c14.668,24.796,61.498,59.353,88.456,77.029c26.952-17.76,73.756-52.415,88.318-77.029 c7.946-13.432,11.187-25.282,11.187-40.901c0-35.335-24.844-51.149-49.465-51.149c-21.13,0-31.059,10.283-35.67,18.911 c-2.832,5.302-8.335,8.599-14.359,8.599c-6.013,0-11.511-3.288-14.348-8.58C237.09,198.635,227.125,188.34,205.949,188.34z"/> <path style="fill:#A66CFF ;" d="M255.998,512.001c-2.251,0-4.501-0.522-6.563-1.57c-23.631-11.985-59.104-31.163-93.896-54.456 c-32.881-22.013-59.465-43.749-79.016-64.606c-18.873-20.134-29.267-46.439-29.267-74.068V109.147 c0-7.251,5.351-13.388,12.534-14.375c69.38-9.536,135.48-41.745,186.125-90.695c5.624-5.435,14.543-5.435,20.168,0 c27.092,26.185,58.341,47.513,92.874,63.391c7.281,3.347,10.469,11.964,7.123,19.245c-3.347,7.283-11.962,10.472-19.245,7.122 c-33.306-15.312-63.806-35.301-90.839-59.513c-50.425,45.102-113.384,75.67-179.719,87.245v195.735 c0,20.228,7.608,39.485,21.42,54.221c18.043,19.249,42.937,39.55,73.988,60.337c30.518,20.432,61.682,37.636,84.315,49.328 c22.633-11.694,53.797-28.897,84.315-49.328c31.052-20.789,55.945-41.088,73.988-60.337c13.814-14.736,21.42-33.993,21.42-54.221 V109.147c0-8.014,6.496-14.51,14.51-14.51s14.51,6.496,14.51,14.51v208.155c0,27.629-10.394,53.932-29.267,74.068 c-19.551,20.857-46.135,42.593-79.017,64.606c-34.792,23.293-70.263,42.471-93.895,54.456 C260.499,511.478,258.247,512.001,255.998,512.001z"/> </g> </g>
</svg>
```

### `frontend\src\assets\react.svg`

```
<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" role="img" class="iconify iconify--logos" width="35.93" height="32" preserveAspectRatio="xMidYMid meet" viewBox="0 0 256 228"><path fill="#00D8FF" d="M210.483 73.824a171.49 171.49 0 0 0-8.24-2.597c.465-1.9.893-3.777 1.273-5.621c6.238-30.281 2.16-54.676-11.769-62.708c-13.355-7.7-35.196.329-57.254 19.526a171.23 171.23 0 0 0-6.375 5.848a155.866 155.866 0 0 0-4.241-3.917C100.759 3.829 77.587-4.822 63.673 3.233C50.33 10.957 46.379 33.89 51.995 62.588a170.974 170.974 0 0 0 1.892 8.48c-3.28.932-6.445 1.924-9.474 2.98C17.309 83.498 0 98.307 0 113.668c0 15.865 18.582 31.778 46.812 41.427a145.52 145.52 0 0 0 6.921 2.165a167.467 167.467 0 0 0-2.01 9.138c-5.354 28.2-1.173 50.591 12.134 58.266c13.744 7.926 36.812-.22 59.273-19.855a145.567 145.567 0 0 0 5.342-4.923a168.064 168.064 0 0 0 6.92 6.314c21.758 18.722 43.246 26.282 56.54 18.586c13.731-7.949 18.194-32.003 12.4-61.268a145.016 145.016 0 0 0-1.535-6.842c1.62-.48 3.21-.974 4.76-1.488c29.348-9.723 48.443-25.443 48.443-41.52c0-15.417-17.868-30.326-45.517-39.844Zm-6.365 70.984c-1.4.463-2.836.91-4.3 1.345c-3.24-10.257-7.612-21.163-12.963-32.432c5.106-11 9.31-21.767 12.459-31.957c2.619.758 5.16 1.557 7.61 2.4c23.69 8.156 38.14 20.213 38.14 29.504c0 9.896-15.606 22.743-40.946 31.14Zm-10.514 20.834c2.562 12.94 2.927 24.64 1.23 33.787c-1.524 8.219-4.59 13.698-8.382 15.893c-8.067 4.67-25.32-1.4-43.927-17.412a156.726 156.726 0 0 1-6.437-5.87c7.214-7.889 14.423-17.06 21.459-27.246c12.376-1.098 24.068-2.894 34.671-5.345a134.17 134.17 0 0 1 1.386 6.193ZM87.276 214.515c-7.882 2.783-14.16 2.863-17.955.675c-8.075-4.657-11.432-22.636-6.853-46.752a156.923 156.923 0 0 1 1.869-8.499c10.486 2.32 22.093 3.988 34.498 4.994c7.084 9.967 14.501 19.128 21.976 27.15a134.668 134.668 0 0 1-4.877 4.492c-9.933 8.682-19.886 14.842-28.658 17.94ZM50.35 144.747c-12.483-4.267-22.792-9.812-29.858-15.863c-6.35-5.437-9.555-10.836-9.555-15.216c0-9.322 13.897-21.212 37.076-29.293c2.813-.98 5.757-1.905 8.812-2.773c3.204 10.42 7.406 21.315 12.477 32.332c-5.137 11.18-9.399 22.249-12.634 32.792a134.718 134.718 0 0 1-6.318-1.979Zm12.378-84.26c-4.811-24.587-1.616-43.134 6.425-47.789c8.564-4.958 27.502 2.111 47.463 19.835a144.318 144.318 0 0 1 3.841 3.545c-7.438 7.987-14.787 17.08-21.808 26.988c-12.04 1.116-23.565 2.908-34.161 5.309a160.342 160.342 0 0 1-1.76-7.887Zm110.427 27.268a347.8 347.8 0 0 0-7.785-12.803c8.168 1.033 15.994 2.404 23.343 4.08c-2.206 7.072-4.956 14.465-8.193 22.045a381.151 381.151 0 0 0-7.365-13.322Zm-45.032-43.861c5.044 5.465 10.096 11.566 15.065 18.186a322.04 322.04 0 0 0-30.257-.006c4.974-6.559 10.069-12.652 15.192-18.18ZM82.802 87.83a323.167 323.167 0 0 0-7.227 13.238c-3.184-7.553-5.909-14.98-8.134-22.152c7.304-1.634 15.093-2.97 23.209-3.984a321.524 321.524 0 0 0-7.848 12.897Zm8.081 65.352c-8.385-.936-16.291-2.203-23.593-3.793c2.26-7.3 5.045-14.885 8.298-22.6a321.187 321.187 0 0 0 7.257 13.246c2.594 4.48 5.28 8.868 8.038 13.147Zm37.542 31.03c-5.184-5.592-10.354-11.779-15.403-18.433c4.902.192 9.899.29 14.978.29c5.218 0 10.376-.117 15.453-.343c-4.985 6.774-10.018 12.97-15.028 18.486Zm52.198-57.817c3.422 7.8 6.306 15.345 8.596 22.52c-7.422 1.694-15.436 3.058-23.88 4.071a382.417 382.417 0 0 0 7.859-13.026a347.403 347.403 0 0 0 7.425-13.565Zm-16.898 8.101a358.557 358.557 0 0 1-12.281 19.815a329.4 329.4 0 0 1-23.444.823c-7.967 0-15.716-.248-23.178-.732a310.202 310.202 0 0 1-12.513-19.846h.001a307.41 307.41 0 0 1-10.923-20.627a310.278 310.278 0 0 1 10.89-20.637l-.001.001a307.318 307.318 0 0 1 12.413-19.761c7.613-.576 15.42-.876 23.31-.876H128c7.926 0 15.743.303 23.354.883a329.357 329.357 0 0 1 12.335 19.695a358.489 358.489 0 0 1 11.036 20.54a329.472 329.472 0 0 1-11 20.722Zm22.56-122.124c8.572 4.944 11.906 24.881 6.52 51.026c-.344 1.668-.73 3.367-1.15 5.09c-10.622-2.452-22.155-4.275-34.23-5.408c-7.034-10.017-14.323-19.124-21.64-27.008a160.789 160.789 0 0 1 5.888-5.4c18.9-16.447 36.564-22.941 44.612-18.3ZM128 90.808c12.625 0 22.86 10.235 22.86 22.86s-10.235 22.86-22.86 22.86s-22.86-10.235-22.86-22.86s10.235-22.86 22.86-22.86Z"></path></svg>
```

### `frontend\src\components\AddPasswordModal.jsx`

```javascript
import { useState } from "react";
import { X } from "lucide-react";
import { toast } from "react-toastify";
import axiosInstance from "../config/axios/axios";
import { useSelector } from "react-redux";

const AddPasswordModal = ({ isOpen, onClose, onSuccess }) => {
  const [title, setTitle] = useState("");
  const [username, setUsername] = useState("");
  const [password, setPassword] = useState("");
  const [loading, setLoading] = useState(false);
  const darkTheme = useSelector((state) => state.theme.darkTheme);

  const handleSubmit = async (e) => {
    e.preventDefault();
    if (!title || !password) {
      toast.error("App name and password are required");
      return;
    }

    setLoading(true);
    try {
      const res = await axiosInstance.post("/api/vault/add", {
        title,
        username,
        password,
      });

      onSuccess?.({
        title,
        username,
        password,
      });
      onClose?.();

      // Reset inputs
      setTitle("");
      setUsername("");
      setPassword("");
    } catch (err) {
      console.error(err);
      toast.error("Failed to save password");
    } finally {
      setLoading(false);
    }
  };

  if (!isOpen) return null;

  return (
    <div className="fixed inset-0 z-50 flex items-center justify-center bg-black/60 backdrop-blur-sm">
      <div
        className={`relative w-[90%] max-w-md p-6 rounded-2xl shadow-xl border ${
          darkTheme
            ? "bg-dark-background text-dark-primaryText border-dark-hover"
            : "bg-light-background text-light-primaryText border-light-hover"
        }`}
      >
        {/* Close Button */}
        <button
          onClick={onClose}
          className={`absolute top-3 right-3 transition-colors ${
            darkTheme
              ? "text-dark-secondaryText hover:text-dark-accent"
              : "text-light-secondaryText hover:text-light-accent"
          }`}
        >
          <X size={22} />
        </button>

        {/* Header */}
        <h2 className="text-xl font-bold mb-2">➕ Add New Password</h2>

        {/* Form */}
        <form onSubmit={handleSubmit} className="space-y-4">
          <input
            type="text"
            placeholder="App / Site Name"
            value={title}
            onChange={(e) => setTitle(e.target.value)}
            className={`w-full p-3 rounded-xl outline-none ${
              darkTheme
                ? "bg-dark-secondary text-dark-primaryText placeholder-dark-secondaryText"
                : "bg-light-secondary text-light-primaryText placeholder-light-secondaryText"
            }`}
          />
          <input
            type="text"
            placeholder="Username (optional)"
            value={username}
            onChange={(e) => setUsername(e.target.value)}
            className={`w-full p-3 rounded-xl outline-none ${
              darkTheme
                ? "bg-dark-secondary text-dark-primaryText placeholder-dark-secondaryText"
                : "bg-light-secondary text-light-primaryText placeholder-light-secondaryText"
            }`}
          />
          <input
            type="text"
            placeholder="Password"
            value={password}
            onChange={(e) => setPassword(e.target.value)}
            className={`w-full p-3 rounded-xl outline-none ${
              darkTheme
                ? "bg-dark-secondary text-dark-primaryText placeholder-dark-secondaryText"
                : "bg-light-secondary text-light-primaryText placeholder-light-secondaryText"
            }`}
          />

          <button
            type="submit"
            disabled={loading}
            className={`w-full py-2 rounded-xl font-semibold transition-all ${
              darkTheme
                ? "bg-dark-action hover:bg-dark-hover text-white"
                : "bg-light-action hover:bg-light-hover text-white"
            }`}
          >
            {loading ? "Saving..." : "Save Password"}
          </button>
        </form>
      </div>
    </div>
  );
};

export default AddPasswordModal;

```

### `frontend\src\components\DeleteConfirmModal.jsx`

```javascript
import { X } from "lucide-react";
import { useSelector } from "react-redux";

const DeleteConfirmModal = ({ isOpen, onConfirm, onCancel }) => {
  const darkTheme = useSelector((state) => state.theme.darkTheme);

  if (!isOpen) return null;

  return (
    <div className="fixed inset-0 z-50 flex items-center justify-center bg-black/60 backdrop-blur-sm">
      <div
        className={`relative w-[90%] max-w-md p-6 rounded-2xl shadow-xl border ${
          darkTheme
            ? "bg-dark-background text-dark-primaryText border-dark-hover"
            : "bg-light-background text-light-primaryText border-light-hover"
        }`}
      >
        {/* Close Button */}
        <button
          onClick={onCancel}
          className={`absolute top-3 right-3 transition-colors ${
            darkTheme
              ? "text-dark-secondaryText hover:text-dark-accent"
              : "text-light-secondaryText hover:text-light-accent"
          }`}
        >
          <X size={20} />
        </button>

        <h2 className="text-xl font-bold mb-2">⚠️ Confirm Deletion</h2>
        <p
          className={`text-sm ${
            darkTheme ? "text-dark-secondaryText" : "text-light-secondaryText"
          }`}
        >
          Are you sure you want to delete this password? This action cannot be
          undone.
        </p>

        <div className="mt-6 flex justify-end gap-4">
          <button
            onClick={onCancel}
            className={`px-4 py-2 rounded-lg font-semibold transition-all ${
              darkTheme
                ? "bg-dark-secondary text-white hover:bg-dark-hover"
                : "bg-light-secondary text-black hover:bg-light-hover"
            }`}
          >
            Cancel
          </button>
          <button
            onClick={onConfirm}
            className="px-4 py-2 bg-red-600 hover:bg-red-700 text-white font-semibold rounded-lg transition-all"
          >
            Yes, Delete
          </button>
        </div>
      </div>
    </div>
  );
};

export default DeleteConfirmModal;

```

### `frontend\src\components\Loading.jsx`

```javascript
import React from "react";

const Loading = () => {
  return (
    <div className="w-5 h-5 border-4 border-blue-500 border-dotted rounded-full animate-spin"></div>
  );
};

export default Loading;

```

### `frontend\src\components\LoadingScreen\LoadingScreen.jsx`

```javascript
import React from "react";
import { useSelector } from "react-redux";
import loader from "../../assets/loader.svg"; // Import the SVG properly

const LoadingScreen = () => {
  const { darkTheme } = useSelector((state) => state.theme);

  return (
    <div
      className={`min-h-screen flex flex-col items-center justify-center ${
        darkTheme
          ? "bg-dark-background text-dark-primaryText"
          : "bg-light-background text-light-primaryText"
      }`}
    >
      <div className="flex flex-col items-center">
        {/* Custom SVG Loader */}
        <img src={loader} alt="Loading..." className="w-32 h-32" />

        <p className="mt-4 text-lg font-semibold">Loading, please wait...</p>
      </div>
    </div>
  );
};

export default LoadingScreen;

```

### `frontend\src\components\LogoutPopup\hook\useOnConfirm.js`

```javascript
import { toast } from "react-toastify";
import { removeUser } from "../../../app/slices/userSlice";

  const useOnconfirm = (dispatch,navigate) => {
    // Handle logout confirmation logic here
    localStorage.removeItem("token"); // Clear user data from local storage
    dispatch(removeUser())
    toast.success("Logged out successfully", {
      position: "top-right",
      autoClose: 5000,
      hideProgressBar: false,
      closeOnClick: false,
      pauseOnHover: true,
      draggable: true,
      progress: undefined,
      theme: "light",
    });
    setTimeout(() => {
      navigate("/"); // Redirect to login page or home page
    }, 1000);    
  };

  export default useOnconfirm;
```

### `frontend\src\components\LogoutPopup\LogoutPopup.jsx`

```javascript
import React from "react";
import { IoIosLogOut } from "react-icons/io";
import { HiX } from "react-icons/hi";
import { useDispatch } from "react-redux";
import { useNavigate } from "react-router-dom";
import useOnconfirm from "./hook/useOnConfirm";

const LogoutPopup = ({ isOpen, onClose }) => {
  if (!isOpen) return null;
  const dispatch = useDispatch();
  const navigate = useNavigate();

  return (
    <div className="fixed inset-0 bg-black/40 backdrop-blur-sm flex items-center justify-center z-50">
      <div className="relative bg-light-secondary dark:bg-dark-secondary border border-light-border dark:border-dark-border shadow-lg rounded-lg p-6 w-80">
        {/* Close Button (X) */}
        <button
          onClick={onClose}
          className="absolute top-2 right-2 text-lg text-light-primaryText dark:text-dark-primaryText hover:text-light-accent dark:hover:text-dark-accent transition"
        >
          <HiX />
        </button>

        {/* Confirmation Text */}
        <h3 className="text-lg font-semibold text-center text-light-primaryText dark:text-dark-primaryText">
          Are you sure you want to logout?
        </h3>

        {/* Action Buttons */}
        <div className="flex justify-center gap-4 mt-4">
          <button
            onClick={() => {
              useOnconfirm(dispatch, navigate);
              onClose();
            }}
            className="flex items-center gap-2 px-4 py-2 text-lg bg-red-500 text-white rounded-md hover:bg-red-600 transition"
          >
            Yes, Logout <IoIosLogOut />
          </button>
          <button
            onClick={onClose}
            className="px-4 py-2 text-lg bg-gray-500 text-white rounded-md hover:bg-gray-600 transition"
          >
            Cancel
          </button>
        </div>
      </div>
    </div>
  );
};

export default LogoutPopup;

```

### `frontend\src\components\NavBar\NavBar.jsx`

```javascript
import React, { useEffect, useState } from "react";
import { Link } from "react-router-dom";
import { HiMenu } from "react-icons/hi";
import ThemeButton from "../../components/ThemeButton";
import Logo from "../../assets/PrevGuard.svg";
import SideBar from "../SideBar/SideBar";
import { PiSignInDuotone } from "react-icons/pi";
import { useDispatch, useSelector } from "react-redux";
import axiosInstance from "../../config/axios/axios";
import { setUser } from "../../app/slices/userSlice";
import { motion } from "framer-motion";

const NavBar = () => {
  const [isSidebarOpen, setIsSidebarOpen] = useState(false);
  const user = useSelector((state) => state.user.user);
  const { darkTheme } = useSelector((state) => state.theme);
  const dispatch = useDispatch();

  useEffect(() => {
    const isUserLoggedIn = async () => {
      axiosInstance
        .get("/api/auth/authme")
        .then((res) => {
          dispatch(setUser(res.data.user));
        })
        .catch((e) => {
          console.log(e);
          dispatch(setUser(null));
        });
    };
    isUserLoggedIn();
  }, []);

  // Animation variants
  const navbarVariants = {
    hidden: { y: -100, opacity: 0 },
    visible: {
      y: 0,
      opacity: 1,
      transition: {
        type: "spring",
        stiffness: 120,
        damping: 20,
        staggerChildren: 0.1,
        delayChildren: 0.2,
      },
    },
  };

  const itemVariants = {
    hidden: { y: -20, opacity: 0 },
    visible: {
      y: 0,
      opacity: 1,
      transition: {
        type: "spring",
        stiffness: 100,
      },
    },
  };

  const logoVariants = {
    hidden: { scale: 0.8, opacity: 0 },
    visible: {
      scale: 1,
      opacity: 1,
      transition: {
        type: "spring",
        stiffness: 150,
      },
    },
    hover: {
      scale: 1.05,
      transition: {
        duration: 0.2,
      },
    },
  };

  return (
    <>
      <motion.nav
        className="top-0 left-0 w-full bg-light-background/80 dark:bg-dark-background/80 backdrop-blur-lg shadow-md flex justify-between items-center px-3 py-2 md:px-4 md:py-3 lg:p-4 z-50"
        initial="hidden"
        animate="visible"
        variants={navbarVariants}
      >
        {/* Left Section */}
        <div className="flex items-center gap-2 md:gap-4">
          <motion.button
            onClick={() => setIsSidebarOpen(!isSidebarOpen)}
            className="text-light-primaryText dark:text-dark-primaryText text-lg md:text-xl lg:text-2xl hover:text-light-accent dark:hover:text-dark-accent transition"
            variants={itemVariants}
            whileHover={{ rotate: 180, scale: 1.1 }}
            whileTap={{ scale: 0.9 }}
          >
            <HiMenu />
          </motion.button>

          <motion.div variants={itemVariants}>
            <Link to={"/"}>
              <motion.img
                src={Logo}
                alt="PrevGuard Logo"
                className="h-7 md:h-8 lg:h-10"
                variants={logoVariants}
                whileHover="hover"
              />
            </Link>
          </motion.div>
        </div>

        {/* Center Title */}
        <motion.div variants={itemVariants} whileHover={{ scale: 1.05 }}>
          <Link
            to={"/"}
            className="hidden md:block text-lg lg:text-xl font-semibold text-light-primaryText dark:text-dark-primaryText bg-gradient-to-r from-light-accent to-light-action dark:from-dark-accent dark:to-dark-action bg-clip-text text-transparent"
          >
            PrivGuard
          </Link>
        </motion.div>

        {/* Right Section */}
        <motion.div className="flex items-center gap-2 md:gap-4" variants={itemVariants}>
          <motion.div variants={itemVariants} whileHover={{ scale: 1.1 }} whileTap={{ scale: 0.95 }}>
            <ThemeButton />
          </motion.div>

          {user ? (
            <motion.div
              variants={itemVariants}
              whileHover={{ scale: 1.1 }}
              whileTap={{ scale: 0.95 }}
            >
              <Link to="/profile">
                <motion.img
                  src={user.profilePicture}
                  alt="Profile"
                  className="h-7 w-7 md:h-8 md:w-8 lg:h-10 lg:w-10 rounded-full border border-light-accent dark:border-dark-accent cursor-pointer"
                  initial={{ opacity: 0 }}
                  animate={{ opacity: 1 }}
                  whileHover={{
                    boxShadow: `0 0 8px ${darkTheme ? '#A66CFF' : '#874CCC'}`
                  }}
                />
              </Link>
            </motion.div>
          ) : (
            <motion.div className="flex gap-2 items-center" variants={itemVariants}>
              <motion.div whileHover={{ scale: 1.05 }} whileTap={{ scale: 0.95 }}>
                <Link
                  to="/register"
                  className="text-xs md:text-sm text-light-primaryText dark:text-dark-primaryText hover:text-light-accent dark:hover:text-dark-accent mt-1 transition"
                >
                  New? here!
                </Link>
              </motion.div>
              <motion.div
                whileHover={{ scale: 1.1, rotate: 5, transition: { duration: 0.2 } }}
                whileTap={{ scale: 0.95 }}
              >
                <Link to="/login">
                  <PiSignInDuotone
                    className={`inline-block h-8 w-8 rounded-full ${
                      darkTheme ? "text-[#E3DFFD]" : "text-[#241847]"
                    }`}
                  />
                </Link>
              </motion.div>
            </motion.div>
          )}
        </motion.div>
      </motion.nav>

      <SideBar isOpen={isSidebarOpen} onClose={() => setIsSidebarOpen(false)} />
    </>
  );
};

export default NavBar;

```

### `frontend\src\components\ProfileEditModal\ProfileEditModal.jsx`

```javascript
import React, { useState } from "react";
import axiosInstance from "../../config/axios/axios";
import { X } from "lucide-react";
import { toast } from "react-toastify";
import { setUser } from "../../app/slices/userSlice";
import { useDispatch, useSelector } from "react-redux";


export default function ProfileEditModal({ user, onClose, onUpdate }) {
  const [username, setUsername] = useState(user.username);
  const [phoneNumber, setPhoneNumber] = useState(user.phoneNumber);
  const [image, setImage] = useState(null);
  const [loading, setLoading] = useState(false);
  const dispatch = useDispatch(); // Assuming you have a Redux store to manage user state
  const { darkTheme } = useSelector((state) => state.theme); // Assuming you have a Redux store with a theme slice

  const handleSubmit = async (e) => {
    e.preventDefault();
    const formData = new FormData();
    formData.append("username", username);
    formData.append("phoneNumber", phoneNumber);
    if (image) formData.append("profilePicture", image);
  
    try {
      setLoading(true);
      const res = await axiosInstance.put("/api/user/update", formData, {
        headers: { "Content-Type": "multipart/form-data" },
      });
      onUpdate(res.data);
      toast.success("Profile updated successfully!");
      dispatch(setUser(res.data.user));
      onClose();
    } catch (error) {
      console.error("Profile update failed", error);
      toast.error("Failed to update profile. Please try again.");
    } finally {
      setLoading(false);
    }
  };
  

  return (
    <div className="fixed inset-0 z-50 bg-black bg-opacity-50 flex justify-center items-center">
      <div className="bg-white dark:bg-dark-secondary text-black dark:text-white p-6 rounded-xl shadow-lg w-full max-w-md">
        <div className="flex justify-between items-center mb-4">
          <h2 className="text-xl font-semibold">Edit Profile</h2>
          <button onClick={onClose}><X className="w-6 h-6" /></button>
        </div>
        <form onSubmit={handleSubmit} className="flex flex-col gap-4">
          <input
            type="text"
            value={username}
            onChange={(e) => setUsername(e.target.value)}
            placeholder="Username"
            className="px-4 py-2 rounded-md border dark:bg-dark-background"
            required
          />
          <input
            type="tel"
            value={phoneNumber}
            onChange={(e) => setPhoneNumber(e.target.value)}
            placeholder="Phone Number"
            className="px-4 py-2 rounded-md border dark:bg-dark-background"
          />
          <input
            type="file"
            onChange={(e) => setImage(e.target.files[0])}
            accept="image/*"
            className="text-sm"
          />
          <input
            type="email"
            value={user.email}
            readOnly
            className="px-4 py-2 rounded-md border bg-gray-200 cursor-not-allowed"
          />
          <button
            type="submit"
            disabled={loading}
            className="bg-blue-600 hover:bg-blue-700 text-white py-2 rounded-md"
          >
            {loading ? "Updating..." : "Update Profile"}
          </button>
        </form>
      </div>
    </div>
  );
}

```

### `frontend\src\components\SideBar\SideBar.jsx`

```javascript
import React, { useState } from "react";
import { Link } from "react-router-dom";
import { HiX } from "react-icons/hi";
import { IoIosLogOut } from "react-icons/io";
import LogoutPopup from "../LogoutPopup/LogoutPopup"; // Import the modal
import { useSelector } from "react-redux";

const SideBar = ({ isOpen, onClose }) => {
  const [showLogoutPopup, setShowLogoutPopup] = useState(false);
  const user = useSelector((state) => state.user.user); // Replace with actual auth logic

  return (
    <>
      {/* Overlay */}
      <div
        className={`fixed inset-0 bg-black/30 backdrop-blur-md transition-opacity duration-300 ${
          isOpen ? "opacity-100 visible" : "opacity-0 invisible"
        } z-40`}
        onClick={onClose}
      ></div>

      {/* Sidebar */}
      <div
        className={`fixed top-0 right-0 h-full w-48 md:w-64 bg-light-secondary/40 dark:bg-dark-secondary/40 backdrop-blur-xl border-l border-light-border dark:border-dark-border shadow-2xl transform ${
          isOpen ? "translate-x-0" : "translate-x-full"
        } transition-transform duration-300 ease-in-out z-50`}
      >
        {/* Close Button */}
        <div className="flex justify-end p-4">
          <button
            onClick={onClose}
            className="text-2xl text-light-primaryText dark:text-dark-primaryText hover:text-light-accent dark:hover:text-dark-accent transition"
          >
            <HiX />
          </button>
        </div>

        {/* Navigation Links */}
        <nav className="flex flex-col gap-4 p-4 text-white dark:text-dark-primaryText">
          <Link
            onClick={onClose}
            to="/password-strength-checker"
            className="text-lg hover:text-light-accent dark:hover:text-dark-accent transition"
          >
            Password Strength Checker
          </Link>
          <Link
            onClick={onClose}
            to="/profile"
            className="text-lg hover:text-light-accent dark:hover:text-dark-accent transition"
          >
            Profile
          </Link>
          <Link
            onClick={onClose}
            to="/shared-data"
            className="text-lg hover:text-light-accent dark:hover:text-dark-accent transition"
          >
            Shared Data
          </Link>
          <Link
            onClick={onClose}
            to="/fake-data"
            className="text-lg hover:text-light-accent dark:hover:text-dark-accent transition"
          >
            Fake Data Generator
          </Link>
          <Link
            onClick={onClose}
            to="/breach-check"
            className="text-lg hover:text-light-accent dark:hover:text-dark-accent transition"
          >
            Breach Monitoring
          </Link>
          <Link
            onClick={onClose}
            to="/privacy-tips"
            className="text-lg hover:text-light-accent dark:hover:text-dark-accent transition"
          >
            Privacy Tips
          </Link>
          <Link
            onClick={onClose}
            to="/vault"
            className="text-lg hover:text-light-accent dark:hover:text-dark-accent transition"
          >
            Data Vault
          </Link>

          {/* Logout Button - Opens Popup */}
          {user ? (
            <button
              onClick={() => setShowLogoutPopup(true)}
              className="flex items-center gap-2 px-4 py-2 text-lg bg-red-500 text-white rounded-md hover:bg-red-600 transition"
            >
              Logout <IoIosLogOut />
            </button>
          ) : null}
        </nav>
      </div>

      {/* Logout Popup */}
      <LogoutPopup
        isOpen={showLogoutPopup}
        onClose={() => setShowLogoutPopup(false)}
        onConfirm={() => {
          console.log("User logged out!"); // Replace with actual logout logic
          setShowLogoutPopup(false);
        }}
      />
    </>
  );
};

export default SideBar;

```

### `frontend\src\components\ThemeButton.jsx`

```javascript
import React from "react";
import { useDispatch, useSelector } from "react-redux";
import { GiBoomerangSun } from "react-icons/gi";
import { RiMoonClearFill } from "react-icons/ri";
import { toggleTheme } from "../app/slices/ThemeSlice";

const ThemeButton = () => {
  const { darkTheme } = useSelector((state) => state.theme);
  const dispatch = useDispatch();

  return (
    <button
      onClick={() => dispatch(toggleTheme())}
      className={`rounded-full transition-all duration-500 transform ${
        darkTheme
          ? "bg-dark-secondary text-dark-primaryText scale-110 rotate-[360deg]"
          : "bg-light-secondary text-light-primaryText scale-100 rotate-0"
      } p-1 lg:p-3 shadow-md hover:scale-300 hover:shadow-lg`}
    >
      {darkTheme ? (
        <RiMoonClearFill className="text-xl text-light-accent transition-all duration-500" />
      ) : (
        <GiBoomerangSun className="text-xl text-dark-accent transition-all duration-500" />
      )}
    </button>
  );
};

export default ThemeButton;

```

### `frontend\src\components\Unauthorized.jsx`

```javascript
import React from "react";
import { Link } from "react-router-dom";
import { useSelector } from "react-redux";

const Unauthorized = () => {
  const { darkTheme } = useSelector((state) => state.theme);

  return (
    <div
      className={`min-h-screen flex flex-col items-center justify-center p-6 ${
        darkTheme
          ? "bg-dark-background text-dark-primaryText"
          : "bg-light-background text-light-primaryText"
      }`}
    >
      <div className="bg-secondary bg-opacity-40 backdrop-blur-md border border-white/20 p-8 rounded-2xl shadow-lg text-center">
        <h1 className="text-3xl font-bold mb-4">403 - Unauthorized</h1>
        <p className="mb-6">You do not have permission to access this page.</p>
        <Link
          to="/"
          className="px-6 py-2 rounded-md bg-blue-500 text-white text-lg hover:bg-blue-600 transition"
        >
          Go Home
        </Link>
      </div>
    </div>
  );
};

export default Unauthorized;

```

### `frontend\src\components\UpdatePasswordModal.jsx`

```javascript
import { useEffect, useState } from "react";
import { X } from "lucide-react";
import { toast } from "react-toastify";
import axiosInstance from "../config/axios/axios";
import { useSelector } from "react-redux";

const UpdatePasswordModal = ({ isOpen, onClose, onSuccess, vaultItem }) => {
  const [title, setTitle] = useState("");
  const [username, setUsername] = useState("");
  const [password, setPassword] = useState("");
  const [loading, setLoading] = useState(false);
  const darkTheme = useSelector((state) => state.theme.darkTheme);

  useEffect(() => {
    if (vaultItem) {
      setTitle(vaultItem.title || "");
      setUsername(vaultItem.username || "");
      setPassword(vaultItem.password || "");
    }
  }, [vaultItem]);

  const handleSubmit = async (e) => {
    e.preventDefault();

    if (!title || !password) {
      toast.error("App name and password are required");
      return;
    }

    setLoading(true);
    try {
      await axiosInstance.put(`/api/vault/update/${vaultItem._id}`, {
        title,
        username,
        password,
      });

      toast.success("Password updated 🔄");
      onSuccess?.();
      onClose?.();
    } catch (err) {
      console.error(err);
      toast.error("Failed to update password");
    } finally {
      setLoading(false);
    }
  };

  if (!isOpen) return null;

  return (
    <div className="fixed inset-0 z-50 flex items-center justify-center bg-black/60 backdrop-blur-sm">
      <div
        className={`relative w-[90%] max-w-md p-6 rounded-2xl shadow-xl border ${
          darkTheme
            ? "bg-dark-background text-dark-primaryText border-dark-hover"
            : "bg-light-background text-light-primaryText border-light-hover"
        }`}
      >
        <button
          onClick={onClose}
          className={`absolute top-3 right-3 transition-colors ${
            darkTheme
              ? "text-dark-secondaryText hover:text-dark-accent"
              : "text-light-secondaryText hover:text-light-accent"
          }`}
        >
          <X size={22} />
        </button>

        <h2 className="text-xl font-bold mb-2">✏️ Update Password</h2>

        <form onSubmit={handleSubmit} className="space-y-4">
          <input
            type="text"
            placeholder="App / Site Name"
            value={title}
            onChange={(e) => setTitle(e.target.value)}
            className={`w-full p-3 rounded-xl outline-none ${
              darkTheme
                ? "bg-dark-secondary text-dark-primaryText placeholder-dark-secondaryText"
                : "bg-light-secondary text-light-primaryText placeholder-light-secondaryText"
            }`}
          />
          <input
            type="text"
            placeholder="Username (optional)"
            value={username}
            onChange={(e) => setUsername(e.target.value)}
            className={`w-full p-3 rounded-xl outline-none ${
              darkTheme
                ? "bg-dark-secondary text-dark-primaryText placeholder-dark-secondaryText"
                : "bg-light-secondary text-light-primaryText placeholder-light-secondaryText"
            }`}
          />
          <input
            type="text"
            placeholder="Password"
            value={password}
            onChange={(e) => setPassword(e.target.value)}
            className={`w-full p-3 rounded-xl outline-none ${
              darkTheme
                ? "bg-dark-secondary text-dark-primaryText placeholder-dark-secondaryText"
                : "bg-light-secondary text-light-primaryText placeholder-light-secondaryText"
            }`}
          />

          <button
            type="submit"
            disabled={loading}
            className={`w-full py-2 rounded-xl font-semibold transition-all ${
              darkTheme
                ? "bg-dark-action hover:bg-dark-hover text-white"
                : "bg-light-action hover:bg-light-hover text-white"
            }`}
          >
            {loading ? "Updating..." : "Update Password"}
          </button>
        </form>
      </div>
    </div>
  );
};

export default UpdatePasswordModal;

```

### `frontend\src\components\VaultUnlock.jsx`

```javascript
// src/components/VaultUnlock.jsx
import { useState } from "react";
import { toast } from "react-toastify";
import * as argon2 from "argon2-browser";

const VaultUnlock = ({ salt, onUnlock }) => {
  const [password, setPassword] = useState("");
  const [loading, setLoading] = useState(false);

  const handleUnlock = async (e) => {
    e.preventDefault();

    if (!password) {
      toast.error("Vault password is required.");
      return;
    }

    try {
      setLoading(true);

      // Derive key using argon2id
      const { hash } = await argon2.hash({
        pass: password,
        salt,
        type: argon2.ArgonType.Argon2id,
        hashLen: 32,
        time: 3,
        mem: 65536,
        parallelism: 1,
      });

      onUnlock(hash, password); // Send key & password to parent
    } catch (err) {
      toast.error("Key derivation failed.");
    } finally {
      setLoading(false);
    }
  };

  return (
    <form
      onSubmit={handleUnlock}
      className="bg-card p-6 rounded-2xl shadow-lg space-y-4"
    >
      <h2 className="text-xl font-semibold text-foreground">Enter Vault Password</h2>
      <p className="text-sm text-muted-foreground">
        This password is used to encrypt/decrypt your Vault data. Don’t forget it.
      </p>
      <input
        type="password"
        placeholder="Vault Password"
        className="w-full p-2 rounded-xl bg-muted text-foreground placeholder:text-muted-foreground"
        value={password}
        onChange={(e) => setPassword(e.target.value)}
      />
      <button
        type="submit"
        disabled={loading}
        className="bg-primary text-primary-foreground px-4 py-2 rounded-xl w-full font-semibold hover:bg-primary/90 transition"
      >
        {loading ? "Unlocking..." : "Unlock Vault"}
      </button>
    </form>
  );
};

export default VaultUnlock;

```

### `frontend\src\config\axios\axios.js`

```javascript
import axios from 'axios';

const token = localStorage.getItem('token');

const axiosInstance = axios.create({
    baseURL: import.meta.env.VITE_API_URL,
    headers: {
        'Content-Type': 'application/json',
        Authorization: token ? `Bearer ${token}` : null,
    },
});

axiosInstance.interceptors.request.use((config) => {
    const token = localStorage.getItem("token"); // Get latest token
    if (token) {
        config.headers.Authorization = `Bearer ${token}`;
    }
    return config;
}, (error) => {
    return Promise.reject(error);
});


export default axiosInstance;
```

### `frontend\src\HOC\Protected.jsx`

```javascript
import React, { useEffect, useState } from "react";
import { toast } from "react-toastify";
import axiosInstance from "../config/axios/axios";
import { useDispatch } from "react-redux";
import { setUser } from "../app/slices/userSlice";
import Unauthorized from "../components/Unauthorized";
import { useNavigate } from "react-router-dom";
import LoadingScreen from "../components/LoadingScreen/LoadingScreen";

const Protected = ({ children }) => {
  const dispatch = useDispatch();
  const navigate = useNavigate();
  const [isAuthorized, setIsAuthorized] = useState(false);
  const [isLoading, setIsLoading] = useState(true);

  useEffect(() => {
    const token = localStorage.getItem("token"); // Get token inside useEffect

    if (!token) {
      toast.error("Unauthorized! Redirecting to login...");
      setTimeout(() => navigate("/"), 500);
      setIsAuthorized(false);
      setIsLoading(false);
      return;
    }

    let isMounted = true; // Prevent state updates after unmount

    axiosInstance
      .get("/api/auth/authme")
      .then((res) => {
        if (isMounted) {
          dispatch(setUser(res.data.user));
          setIsAuthorized(true);
        }
      })
      .catch((err) => {
        if (isMounted) {
          const errorMessage = err.response?.data?.message || "An error occurred. Try logging in again.";
          toast.error(errorMessage, { position: "top-right", autoClose: 3000 });
          setTimeout(() => navigate("/"), 500);
          setIsAuthorized(false);
        }
      })
      .finally(() => {
        if (isMounted) setIsLoading(false);
      });

    return () => {
      isMounted = false; // Cleanup function
    };
  }, [dispatch, navigate]);

  if (isLoading) return <LoadingScreen />; 
  if (!isAuthorized) return <Unauthorized />;

  return children;
};

export default Protected;

```

### `frontend\src\index.css`

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
/* Global Color Palette */
:root {
    --primary-color: #071952;
    --secondary-color: #088395;
    --light-background: #EBF4F6;
    --accent-color: #37B7C3;
  }
  
  /* Header (Primary Color) */
  .header {
    background-color: var(--primary-color);
    color: white;
    padding: 1rem 1.5rem;
  }
  
  .header h1 {
    font-size: 1.25rem;
    font-weight: 600;
  }
  
  /* Primary Button */
  .btn-primary {
    background-color: var(--primary-color);
    color: white;
    padding: 0.5rem 1rem;
    border-radius: 0.5rem;
    transition: all 0.3s ease;
  }
  
  .btn-primary:hover {
    background-color: var(--secondary-color);
  }
  
  /* Secondary Button */
  .btn-secondary {
    background-color: var(--secondary-color);
    color: white;
    padding: 0.5rem 1rem;
    border-radius: 0.5rem;
    transition: all 0.3s ease;
  }
  
  .btn-secondary:hover {
    background-color: var(--primary-color);
  }
  
  /* Light Background Section */
  .section-light {
    background-color: var(--light-background);
    color: var(--primary-color);
    padding: 1.5rem;
    border-radius: 0.5rem;
  }
  
  /* Input Field */
  .input-field {
    background-color: var(--light-background);
    border: 2px solid var(--primary-color);
    color: var(--primary-color);
    padding: 0.5rem 1rem;
    border-radius: 0.5rem;
    outline: none;
    transition: all 0.3s ease;
  }
  
  .input-field:focus {
    border-color: var(--secondary-color);
    box-shadow: 0 0 0 2px var(--secondary-color);
  }
  
  /* Card with Hover Effect */
  .card {
    background-color: var(--accent-color);
    color: var(--primary-color);
    padding: 1.5rem;
    border-radius: 0.5rem;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    transition: all 0.3s ease;
  }
  
  .card:hover {
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
  }
  
  /* Link with Hover Effect */
  .link {
    color: var(--primary-color);
    transition: all 0.3s ease;
  }
  
  .link:hover {
    color: var(--secondary-color);
  }
  
  /* Footer (Light Background) */
  .footer {
    background-color: var(--light-background);
    color: var(--primary-color);
    padding: 1rem 1.5rem;
  }
  
  .footer p {
    font-size: 0.875rem;
  }
  
```

### `frontend\src\main.jsx`

```javascript
import { createRoot } from "react-dom/client";
import "./index.css";
import App from "./App.jsx";
import { BrowserRouter } from "react-router-dom";
import  store  from "./app/Store.js";
import { Provider } from "react-redux";


createRoot(document.getElementById("root")).render(
  <Provider store={store}>
    <BrowserRouter>
      <App />
    </BrowserRouter>
  </Provider>
);

```

### `frontend\src\Routes\AppRoutes.jsx`

```javascript
import React from "react";
import { Route, Routes } from "react-router-dom";
import Home from "../screens/home,/Home";
import Register from "../screens/Register/Register";
import Login from "../screens/Login/Login";
import OTP from "../screens/OTP/OTP";
import Protected from "../HOC/Protected";
import Vault from "../screens/vault/Vault";
import BreachMonitor from "../screens/BreachMonitor/BreachMonitor";
import SharedApps from "../screens/SharedApps/SharedApps";
import ProfilePage from "../screens/profile/ProfilePage";
import VaultPasswordSetup from "../screens/vaultPasswordSetup/vaultPasswordSetup";
import UnlockVault from "../screens/unlockVault/UnlockVault";
import BlogPage from "../screens/BlogPage/BlogPage";
import PasswordBreachCheck from "../screens/PasswordBreachCheck/PasswordBreachCheck";
import Fakedata from "../screens/fakeData/FakeData";

const AppRoutes = () => {
  return (
    <Routes>
      <Route path="/" element={<Home />} />
      <Route path="/login" element={<Login />} />
      <Route path="/register" element={<Register />} />
      <Route path="/otp" element={<OTP />} />
      <Route
        path="/password-strength-checker"
        element={
          <Protected>
              <PasswordBreachCheck/>
          </Protected>
        }
      />
      <Route
        path="/vault"
        element={
          <Protected>
            <Vault />
          </Protected>
        }
      />

      <Route
        path="/fake-data"
        element={
          <Protected>
            <Fakedata />
          </Protected>
        }
      />

      <Route
        path="/breach-check"
        element={
          <Protected>
            <BreachMonitor />
          </Protected>
        }
      />

      <Route
        path="/shared-data"
        element={
          <Protected>
            <SharedApps />
          </Protected>
        }
      />

      <Route
        path="/profile"
        element={
          <Protected>
            <ProfilePage />
          </Protected>
        }
      />

      <Route
        path="/setupVaultPassword"
        element={
          <Protected>
            <VaultPasswordSetup />
          </Protected>
        }
      />

      <Route
        path="/vaultPassword"
        element={
          <Protected>
            <UnlockVault />
          </Protected>
        }
      />


        <Route
          path="/privacy-tips"
          element={
            <Protected>
              <BlogPage/>
            </Protected>
          }
        />

    </Routes>
  );
};

export default AppRoutes;

```

### `frontend\src\screens\BlogPage\BlogPage.jsx`

```javascript
import React, { useEffect, useState } from "react";
import { useSelector } from "react-redux";
import axiosInstance from "../../config/axios/axios";

const BlogPage = () => {
  const [blogs, setBlogs] = useState([]);
  const themeMode = useSelector((state) => state.theme.mode); // 'light' or 'dark'

  useEffect(() => {
    axiosInstance.get("/api/blogs").then((res) => setBlogs(res.data));
  }, []);

  const darkTheme = useSelector((state) => state.theme.darkTheme); // 'light' or 'dark'


  return (
    <div
      className={`p-4 md:p-6 space-y-4 md:space-y-6 min-h-screen transition-all duration-300 ${
        darkTheme ? "bg-dark-background text-dark-primaryText" : "bg-light-background text-light-primaryText"
      }`}
    >
      <h1
        className={`text-2xl md:text-3xl font-semibold mb-4 md:mb-6 ${
          darkTheme ? "text-dark-primaryText" : "text-light-primaryText"
        }`}
      >
        Latest Blogs
      </h1>
      <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4 md:gap-6">
        {blogs.map((blog, idx) => (
          <div
            key={idx}
            className={`shadow-md rounded-lg overflow-hidden transition-all duration-300 flex flex-col ${
              darkTheme
                ? "bg-dark-secondary text-dark-secondaryText"
                : "bg-light-secondary text-light-secondaryText"
            }`}
          >
            <img
              src={blog.image}
              alt={blog.title}
              className="w-full h-48 object-cover flex-shrink-0"
            />
            <div className="p-4 flex flex-col justify-between flex-grow">
              <div>
                <h2
                  className={`text-lg md:text-xl font-bold mb-2 ${
                    darkTheme ? "text-dark-primaryText" : "text-light-primaryText"
                  }`}
                >
                  {blog.title}
                </h2>
                <p className="mb-3 line-clamp-3 md:line-clamp-4 text-sm md:text-base">{blog.content}</p>
              </div>
              <a
                href={blog.source}
                target="_blank"
                rel="noreferrer"
                className={`inline-block text-sm md:text-base font-medium rounded px-3 py-1 transition w-fit ${
                  darkTheme
                    ? "bg-dark-accent text-dark-background hover:bg-dark-hover"
                    : "bg-light-accent text-white hover:bg-light-hover"
                }`}
              >
                Read More
              </a>
            </div>
          </div>
        ))}
      </div>
    </div>
  );
};

export default BlogPage;
```

### `frontend\src\screens\BreachMonitor\BreachMonitor.jsx`

```javascript
import React, { useState } from "react";
import axios from "axios";
import { useSelector } from "react-redux";
import { CheckCircle, AlertTriangle } from "lucide-react";
import Loading from "../../components/Loading";

const BreachMonitor = () => {
  const [email, setEmail] = useState("");
  const [breachData, setBreachData] = useState(null);
  const [loading, setLoading] = useState(false);
  const [error, setError] = useState("");
  const darkTheme = useSelector((state) => state.theme.darkTheme);

  const handleSearch = async () => {
    setLoading(true);
    setError("");
    try {
      const res = await axios.get(
        `https://api.xposedornot.com/v1/breach-analytics?email=${email}`
      );
      setBreachData(res.data);
    } catch (err) {
      setError("Could not fetch breach info");
    } finally {
      setLoading(false);
    }
  };

  const themeClass = darkTheme ? "dark" : "light";

  const renderExposedData = () => {
    return breachData?.BreachMetrics?.xposed_data[0]?.children.map((category, i) => (
      <div key={i} className="mb-3">
        <h4 className="font-semibold text-md">{category.name}</h4>
        <ul className="list-disc list-inside ml-4 text-sm">
          {category.children.map((item, j) => (
            <li key={j}>{item.name.replace("data_", "")}</li>
          ))}
        </ul>
      </div>
    ));
  };

  const renderBreaches = () => {
    const breaches = breachData?.ExposedBreaches?.breaches_details || [];
    return breaches.map((breach, index) => (
      <div
        key={index}
        className="bg-white/10 backdrop-blur-md p-4 sm:p-6 rounded-xl border border-red-500 shadow-lg transition hover:scale-[1.01]"
      >
        <div className="flex items-center gap-2 mb-2 text-red-400 font-semibold text-sm sm:text-base">
          <AlertTriangle className="w-5 h-5" />
          Breach Detected
        </div>
        <img src={breach.logo} alt={breach.breach} className="w-20 h-auto mb-3" />
        <p><strong>📛 Breach:</strong> {breach.breach}</p>
        <p><strong>🧠 Industry:</strong> {breach.industry}</p>
        <p><strong>📅 Year:</strong> {breach.xposed_date}</p>
        <p><strong>🧾 Records:</strong> {breach.xposed_records.toLocaleString()}</p>
        <p><strong>🔐 Exposed:</strong> {breach.xposed_data}</p>
        <p><strong>📖 Details:</strong> {breach.details}</p>
        <a
          href={breach.references}
          target="_blank"
          rel="noreferrer"
          className="text-blue-400 underline text-sm mt-2 inline-block"
        >
          Learn more
        </a>
      </div>
    ));
  };

  return (
    <div
      className={`min-h-screen px-4 sm:px-6 lg:px-16 py-10 bg-${themeClass}-background text-${themeClass}-primaryText transition-all flex flex-col items-center overflow-x-hidden`}
    >
      <h1 className="text-2xl sm:text-3xl lg:text-4xl font-bold mb-8 text-center">
        🔐 Email Breach Monitor
      </h1>
  
      <div className="w-full max-w-xl flex flex-col sm:flex-row gap-4 mb-10">
        <input
          type="email"
          className={`flex-1 px-4 py-2 rounded-lg bg-${themeClass}-secondary text-${themeClass}-primaryText placeholder-${themeClass}-secondaryText focus:outline-none`}
          placeholder="Enter email..."
          value={email}
          onChange={(e) => setEmail(e.target.value)}
        />
        <button
          onClick={handleSearch}
          className={`px-6 py-2 rounded-lg text-white bg-${themeClass}-action hover:bg-${themeClass}-hover transition-all`}
        >
          Search
        </button>
      </div>
  
      {loading && <p className="text-sm flex gap-4"><Loading /> Checking breaches...</p>}
      {error && <p className="text-red-500">{error}</p>}
  
      {breachData && (
        <div className="w-full max-w-4xl space-y-6 overflow-hidden">
          {/* Summary Section */}
          <div className="text-center">
            <h2 className="text-xl font-semibold mb-2">🔍 Summary</h2>
            <p>
              Breach Site:{" "}
              <span className="font-medium">{breachData.BreachesSummary?.site}</span>
            </p>
            <p>
              Overall Risk:{" "}
              <span className="font-medium">
                {breachData.BreachMetrics?.risk[0]?.risk_label} (
                {breachData.BreachMetrics?.risk[0]?.risk_score})
              </span>
            </p>
            <p>
              Weak Passwords:{" "}
              <span className="font-medium">
                {breachData.BreachMetrics?.passwords_strength[0]?.EasyToCrack}
              </span>
            </p>
          </div>
  
          {/* Exposed Data Section */}
          <div>
            <h2 className="text-xl font-semibold mb-2">📂 Exposed Data</h2>
            {renderExposedData()}
          </div>
  
          {/* Breaches Section */}
          <div>
            <h2 className="text-xl font-semibold mb-2">📛 Breaches</h2>
            {renderBreaches()}
          </div>
        </div>
      )}
    </div>
  );
  
};

export default BreachMonitor;

```

### `frontend\src\screens\checkVaultPassword\checkVaultPassword.jsx`

```javascript

```

### `frontend\src\screens\fakeData\FakeData.jsx`

```javascript
import { useEffect, useState } from "react";
import { toast } from "react-toastify";
import axiosInstance from "../../config/axios/axios";
import { X } from "lucide-react";
import { useSelector } from "react-redux";
import axios from "axios";
import debounce from "lodash/debounce";
import DOMPurify from "dompurify";



const Fakedata = () => {
  const [fakeDataList, setFakeDataList] = useState([]);
  const [loading, setLoading] = useState(false);
  const [mailEmail, setMailEmail] = useState(null);
  const [mailToken, setMailToken] = useState(null);
  const [messages, setMessages] = useState([]);
  const [syncing, setSyncing] = useState(false);
  const [activeMessage, setActiveMessage] = useState(null);
  const [isModalOpen, setIsModalOpen] = useState(false);
  

  const darkTheme = useSelector((state) => state.theme.darkTheme);
  const MAILTM_API = "https://api.mail.tm";

  // 📡 Fetch user's fake data
  const fetchFakeData = async () => {
    try {
      const res = await axiosInstance.get("/api/fake-data/all");
      setFakeDataList(res.data.fakedata);
    } catch (err) {
      toast.error("Failed to load fake data");
    }
  };

  // ➕ Generate new fake data
  const generateData = async () => {
    try {
      setLoading(true);
      const res = await axiosInstance.post("/api/fake-data/generate");
      toast.success("Fake data generated ✅");
      setFakeDataList((prev) => [...prev, res.data.data]);
    } catch (err) {
      toast.error(err.response?.data?.errors?.[0] || "Error generating data");
    } finally {
      setLoading(false);
    }
  };

  // 🗑️ Delete fake data
  const deleteData = async (id) => {
    try {
      await axiosInstance.post(`/api/fake-data/delete`, { fakeDataId: id });
      toast.success("Deleted 🗑️");
      setFakeDataList((prev) => prev.filter((item) => item._id !== id));
    } catch {
      toast.error("Failed to delete");
    }
  };

  // 🔐 Create mail.tm account and get token
  const generateMailAccount = async () => {
    setLoading(true);
    setMessages([]);
    setMailEmail(null);
    try {
      const domainRes = await axios.get(`${MAILTM_API}/domains`);
      const domain = domainRes.data["hydra:member"][0].domain;
      const randomUsername = Math.random().toString(36).substring(2, 10);
      const randomEmail = `${randomUsername}@${domain}`;
      const password = `PrivGuard@123`;

      await axios.post(`${MAILTM_API}/accounts`, {
        address: randomEmail,
        password,
      });

      const loginRes = await axios.post(`${MAILTM_API}/token`, {
        address: randomEmail,
        password,
      });

      setMailEmail(randomEmail);
      setMailToken(loginRes.data.token);
      toast.success("Disposable email created 📬");
    } catch (err) {
      console.error("Mail.tm Error:", err.response?.data || err.message);
      toast.error("Failed to create disposable email");
    } finally {
      setLoading(false);
    }
  };

  // 🔄 Debounced message fetcher (manual trigger)
  const fetchMessages = debounce(async () => {
    if (!mailToken) return;
    try {
      setSyncing(true);
      const res = await axios.get(`${MAILTM_API}/messages`, {
        headers: { Authorization: `Bearer ${mailToken}` },
      });
      setMessages(res.data["hydra:member"]);
      console.log(messages);
      toast.success("Inbox synced 📬");
    } catch (err) {
      console.error("Error fetching messages", err);
      toast.error("Failed to sync inbox");
    } finally {
      setSyncing(false);
    }
  }, 2000);

  useEffect(() => {
    fetchFakeData();
  }, []);

  const handleViewMessage = async (id) => {
    try {
      const res = await axios.get(`${MAILTM_API}/messages/${id}`, {
        headers: { Authorization: `Bearer ${mailToken}` },
      });

      setActiveMessage(res.data);
      setIsModalOpen(true);
    } catch (err) {
      console.error("Failed to load full message", err);
      toast.error("Failed to open email");
    }

  };
  

  return (
    <div
      className={`min-h-screen px-4 py-10 ${
        darkTheme
          ? "bg-dark-background text-dark-primaryText"
          : "bg-light-background text-light-primaryText"
      }`}
    >
      <div className="flex justify-between items-center mb-6">
        <h1 className="text-2xl font-bold">🧪 Fake Data Generator</h1>
        <button
          onClick={generateData}
          disabled={loading}
          className={`px-4 py-2 rounded-xl font-semibold transition ${
            darkTheme
              ? "bg-dark-accent hover:bg-dark-hover text-white"
              : "bg-light-accent hover:bg-light-hover text-white"
          }`}
        >
          {loading ? "Generating..." : "Generate Data"}
        </button>
      </div>

      {/* 📫 Disposable Mailbox */}
      <div className="my-10">
        <h2 className="text-xl font-semibold mb-3">📫 Disposable Mailbox</h2>
        {!mailEmail ? (
          <button
            onClick={generateMailAccount}
            className={`px-4 py-2 rounded-xl font-semibold transition ${
              darkTheme
                ? "bg-dark-accent hover:bg-dark-hover text-white"
                : "bg-light-accent hover:bg-light-hover text-white"
            }`}
          >
            Generate Disposable Email
          </button>
        ) : (
          <div className="space-y-2">
            <div className="flex items-center gap-4 mb-3">
              <p className="text-sm">
                Active Email: <strong>{mailEmail}</strong>
              </p>
              <button
                onClick={fetchMessages}
                disabled={syncing}
                className={`text-xs px-3 py-1 rounded-lg transition ${
                  darkTheme
                    ? "bg-dark-accent hover:bg-dark-hover text-white"
                    : "bg-light-accent hover:bg-light-hover text-white"
                }`}
              >
                {syncing ? "Syncing..." : "Sync Inbox 🔄"}
              </button>
            </div>
            <div className="bg-white/10 p-4 rounded-xl shadow-md border max-h-60 overflow-y-auto">
              {messages.length === 0 ? (
                <p className="text-sm text-gray-400">No messages yet...</p>
              ) : (
                messages.map((msg) => (
                  <button
                    onClick={() => handleViewMessage(msg.id)}
                    className="w-full text-left mb-3 border-b border-gray-500 pb-2 hover:bg-white/10 p-2 rounded transition"
                  >
                    <p className="font-bold text-sm text-blue-400 underline underline-offset-2">
                      {msg.subject || "(No Subject)"}
                    </p>
                    <p className="text-xs text-gray-300">
                      From:{" "}
                      <span className="font-medium">{msg.from?.address}</span>
                    </p>
                    <p className="text-xs text-secondaryText">{msg.intro}</p>
                  </button>
                ))
              )}
            </div>
          </div>
        )}
      </div>

      {/* 🔐 Fake Data Cards */}
      <div className="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-6">
        {fakeDataList.map((item) => (
          <div
            key={item._id}
            className={`relative backdrop-blur-lg p-4 rounded-2xl shadow-xl border ${
              darkTheme
                ? "bg-dark-secondary/30 border-dark-hover"
                : "bg-light-secondary/30 border-light-hover"
            }`}
          >
            <span className="absolute top-2 left-[5%] w-2 h-2 rounded-full bg-green-400 shadow-md shadow-green-500 animate-pulse" />
            <button
              onClick={() => deleteData(item._id)}
              className="absolute top-3 right-3 text-red-400 hover:text-red-600 transition"
            >
              <X size={20} />
            </button>
            <h3 className="text-lg font-semibold mb-1">Fake Name : {item.name}</h3>
            <p className="text-sm text-secondaryText">Fake PhoneNo. :{item.phone}</p>
            <p className="text-sm text-secondaryText">Fake Address : {item.address}</p>
            <p className="text-sm text-secondaryText">Fake AadharNo. :{item.aadhar}</p>
          </div>
        ))}
      </div>


      {isModalOpen && activeMessage && (
  <div className="fixed inset-0 bg-black/60 backdrop-blur-sm z-50 flex items-center justify-center">
    <div className={`relative max-w-3xl w-full max-h-[90vh] overflow-y-auto p-6 rounded-xl shadow-lg transition ${
      darkTheme ? "bg-dark-secondary text-dark-primaryText" : "bg-white text-black"
    }`}>
      <button
        onClick={() => setIsModalOpen(false)}
        className="absolute top-4 right-4 text-red-500 hover:text-red-700"
      >
        <X size={24} />
      </button>
      <h2 className="text-xl font-bold mb-2">{activeMessage.subject}</h2>
      <p className="text-sm text-gray-500 mb-4">From: {activeMessage.from?.address}</p>
      <div
        className="prose max-w-none text-sm"
        dangerouslySetInnerHTML={{ __html: DOMPurify.sanitize( activeMessage.html || activeMessage.text || "No content available.")  }}
      />
    </div>
  </div>
)}





    </div>
  );
};

export default Fakedata;

```

### `frontend\src\screens\home,\Home.jsx`

```javascript
import React, { useEffect, useState } from 'react';
import { Link } from 'react-router-dom';
import { useSelector } from 'react-redux';
import { Shield, Eye, Database, AlertTriangle, Lock, FileCheck } from 'lucide-react';
import { motion } from 'framer-motion';

const Home = () => {
  const { darkTheme } = useSelector((state) => state.theme);

  const [stats, setStats] = useState({
    protected: 0,
    fakesGenerated: 0,
    breachesPrevented: 0,
  });

  useEffect(() => {
    const interval = setInterval(() => {
      setStats((prev) => ({
        protected: prev.protected < 156 ? prev.protected + 3 : 156,
        fakesGenerated: prev.fakesGenerated < 1248 ? prev.fakesGenerated + 24 : 1248,
        breachesPrevented: prev.breachesPrevented < 37 ? prev.breachesPrevented + 1 : 37,
      }));
    }, 50);

    return () => clearInterval(interval);
  }, []);

  const featureVariants = {
    hidden: { x: -20, opacity: 0 },
    visible: (i) => ({
      x: 0,
      opacity: 1,
      transition: {
        delay: i * 0.1 + 0.5,
        duration: 0.4,
      },
    }),
  };

  const pulseAnimation = {
    pulse: {
      scale: [1, 1.03, 1],
      transition: {
        duration: 2,
        repeat: Infinity,
        repeatType: "loop",
      },
    },
  };

  return (
    <div className={`min-h-screen py-1 ${darkTheme ? "bg-dark-background text-dark-primaryText" : "bg-light-background text-light-primaryText"}`}>


      {/* Animated Stats & Features Section */}
      <motion.div className="flex flex-col items-center text-center px-4 py-16 md:py-24">
        <motion.div
          className={`p-6 rounded-full mb-6 ${darkTheme ? "bg-dark-secondary" : "bg-light-secondary"}`}
          animate="pulse"
          variants={pulseAnimation}
        >
          <Shield size={64} className={`${darkTheme ? "text-dark-action" : "text-light-action"}`} />
        </motion.div>

        <h1 className="text-4xl sm:text-5xl md:text-6xl font-bold mb-4">
          Data Shield <span className={`${darkTheme ? "text-dark-action" : "text-light-action"}`}>Visualizer</span>
        </h1>
        <p className={`text-lg md:text-xl max-w-2xl mb-8 ${darkTheme ? "text-dark-secondaryText" : "text-light-secondaryText"}`}>
          Take control of your digital privacy. Monitor your data, generate safe alternatives, and stay protected from breaches.
        </p>

        {/* Stats */}
        <div className="grid grid-cols-1 md:grid-cols-3 gap-8 w-full max-w-4xl mb-16">
          <div className={`p-6 rounded-xl ${darkTheme ? "bg-dark-secondary" : "bg-light-secondary"}`}>
            <h3 className="text-xl font-medium mb-2">Apps Protected</h3>
            <p className={`text-3xl font-bold ${darkTheme ? "text-dark-action" : "text-light-action"}`}>{stats.protected}</p>
          </div>
          <div className={`p-6 rounded-xl ${darkTheme ? "bg-dark-secondary" : "bg-light-secondary"}`}>
            <h3 className="text-xl font-medium mb-2">Fakes Generated</h3>
            <p className={`text-3xl font-bold ${darkTheme ? "text-dark-action" : "text-light-action"}`}>{stats.fakesGenerated}</p>
          </div>
          <div className={`p-6 rounded-xl ${darkTheme ? "bg-dark-secondary" : "bg-light-secondary"}`}>
            <h3 className="text-xl font-medium mb-2">Breaches Prevented</h3>
            <p className={`text-3xl font-bold ${darkTheme ? "text-dark-action" : "text-light-action"}`}>{stats.breachesPrevented}</p>
          </div>
        </div>

        {/* Features */}
        <div className="grid grid-cols-1 md:grid-cols-2 gap-8 max-w-6xl w-full">
          {[
            { icon: <Eye size={32} />, title: "Data Visibility", description: "See exactly what personal data is being shared with your apps and services." },
            { icon: <Database size={32} />, title: "Fake Data Generator", description: "Create fake identities and data for services you don't trust with your real information." },
            { icon: <AlertTriangle size={32} />, title: "Breach Monitoring", description: "Get instant alerts when your data appears in known breaches or leaks." },
            { icon: <Lock size={32} />, title: "Privacy Recommendations", description: "Receive personalized advice to enhance your digital privacy footprint." },
            { icon: <FileCheck size={32} />, title: "Compliance Checking", description: "Verify if services comply with privacy regulations like GDPR and CCPA." },
            { icon: <Shield size={32} />, title: "Risk Assessment", description: "Analyze and score the privacy risks of apps before you install them." },
          ].map((feature, i) => (
            <motion.div
              key={i}
              className={`p-6 rounded-xl ${darkTheme ? "bg-dark-background" : "bg-light-background"} hover:shadow-lg transition-all duration-300`}
              custom={i}
              initial="hidden"
              whileInView="visible"
              viewport={{ once: true }}
              variants={featureVariants}
            >
              <div className={`p-3 rounded-full inline-block mb-4 ${darkTheme ? "bg-dark-secondary" : "bg-light-secondary"}`}>
                <div className={`${darkTheme ? "text-dark-action" : "text-light-action"}`}>{feature.icon}</div>
              </div>
              <h3 className="text-xl font-bold mb-2">{feature.title}</h3>
              <p className={`${darkTheme ? "text-dark-secondaryText" : "text-light-secondaryText"}`}>{feature.description}</p>
            </motion.div>
          ))}
        </div>
      </motion.div>
    </div>
  );
};

export default Home;

```

### `frontend\src\screens\Login\Login.jsx`

```javascript
import React, { useState } from "react";
import { useNavigate } from "react-router-dom";
import { useDispatch, useSelector } from "react-redux";
import { toast } from "react-toastify";
import axiosInstance from "../../config/axios/axios";
import { removeUser } from "../../app/slices/userSlice";

const Login = () => {
  const dispatch = useDispatch(); 
  const [formData, setFormData] = useState({ email: "", password: "" });
  const [passwordVisible, setPasswordVisible] = useState(false);
  const { darkTheme } = useSelector((state) => state.theme);
  const [loading, setLoading] = useState(false);
  const navigate = useNavigate();

  const togglePasswordVisibility = () => setPasswordVisible(!passwordVisible);

  const handleChange = (e) => {
    const { name, value } = e.target;
    setFormData({ ...formData, [name]: value });
  };


  const handleLogin = async (e) => {
    e.preventDefault(); // FIX: Prevent default form submission
    setLoading(true);
    console.log(formData)
    try {
      const response = await axiosInstance.post("/api/auth/login", formData, {
        headers: {
          "Content-Type": "application/json", // Ensures proper JSON format
        },
      });
      
      console.log(response.data)
      localStorage.setItem("token", response.data.token); // Save token
      toast.success("Login Successful!");
      dispatch(removeUser(response.data.user));
      navigate("/password-strength-checker"); // Redirect after login
    } catch (error) {
      console.log(error)
      toast.error(error.response?.data?.message || "Login failed");
    } finally {
      setLoading(false);
    }
  };

  return (
    <div
      className={`flex items-center justify-center min-h-screen ${
        darkTheme ? "bg-dark-background text-dark-primaryText" : "bg-light-background text-light-primaryText"
      }`}
    >
      <div
        className={`w-96 p-6 rounded-lg shadow-lg ${
          darkTheme ? "bg-dark-secondary border border-dark-border" : "bg-light-secondary border border-light-border"
        }`}
      >
        <h2 className="text-xl font-bold text-center mb-6">Log In</h2>
        <form onSubmit={handleLogin}> {/* FIX: Use onSubmit */}
          <input
            type="email"
            name="email"
            value={formData.email}
            onChange={handleChange}
            placeholder="Email"
            className="w-full p-2 rounded-md border border-gray-500 focus:outline-none bg-transparent"
          />

          <div className="relative mt-4">
            <input
              type={passwordVisible ? "text" : "password"}
              name="password"
              value={formData.password}
              onChange={handleChange}
              placeholder="Password"
              className="w-full p-2 rounded-md border border-gray-500 focus:outline-none bg-transparent"
            />
            <span
              onClick={togglePasswordVisibility}
              className="absolute right-3 top-2 cursor-pointer text-sm hover:opacity-75 transition"
            >
              {passwordVisible ? "Hide" : "Show"}
            </span>
          </div>

          <button
            type="submit" // FIX: Ensure button submits the form
            className="w-full mt-6 p-2 rounded-md text-white font-semibold bg-blue-500 hover:bg-blue-600 transition"
            disabled={loading}
          >
            {loading ? "Logging in..." : "Sign In"}
          </button>
        </form>

        <p className="mt-4 text-center">
          Don't have an account?{" "}
          <a href="/register" className="underline hover:opacity-75">
            Sign up
          </a>
        </p>
      </div>
    </div>
  );
};

export default Login;

```

### `frontend\src\screens\OTP\OTP.jsx`

```javascript
import { useState, useRef } from "react";
import { FaArrowLeft } from "react-icons/fa";
import { useLocation, useNavigate } from "react-router-dom";
import { toast, ToastContainer } from "react-toastify";
import handelOTPverification from "./utility/handelOTPverification";
import handelResendOTP from "./utility/handelResendOTP";
import { useDispatch, useSelector } from "react-redux";

const OTP = () => {
  const length = 6;
  const [otp, setOtp] = useState(new Array(length).fill(""));
  const inputRefs = useRef([]);
  const navigate = useNavigate();
  const location = useLocation();
  const dispatch = useDispatch();
  const { darkTheme } = useSelector((state) => state.theme);

  const handleChange = (index, e) => {
    const value = e.target.value;
    if (isNaN(value)) return;
    const newOtp = [...otp];
    newOtp[index] = value.substring(value.length - 1);
    setOtp(newOtp);

    if (value && index < length - 1) {
      inputRefs.current[index + 1].focus();
    }
  };

  const handleKeyDown = (index, e) => {
    if (e.key === "Backspace" && !otp[index] && index > 0) {
      inputRefs.current[index - 1].focus();
    }
  };

  return (
    <div
      className={`flex flex-col items-center justify-center h-screen p-4 ${
        darkTheme ? "bg-[#1A102B]" : "bg-[#F2F0FC]"
      }`}
    >
      <h2
        className={`text-2xl font-semibold mb-4 ${
          darkTheme ? "text-[#E3DFFD]" : "text-[#241847]"
        }`}
      >
        Enter OTP
      </h2>
      <div className="flex space-x-2 md:space-x-4">
        {otp.map((data, index) => (
          <input
            key={index}
            type="text"
            value={data}
            maxLength="1"
            onChange={(e) => handleChange(index, e)}
            onKeyDown={(e) => handleKeyDown(index, e)}
            ref={(el) => (inputRefs.current[index] = el)}
            className={`w-12 h-12 md:w-14 md:h-14 text-center text-lg md:text-xl border-2 ${
              darkTheme ? "border-[#874CCC] bg-[#221736] text-[#E3DFFD]" : "border-[#874CCC] bg-[#DCD6F7] text-[#241847]"
            } rounded-lg focus:outline-none focus:border-green-600 focus:ring-2 focus:ring-green-500 transition`}
          />
        ))}
      </div>
      <div>
        <h1
          className={`text-xs font-light mt-4 text-center ${
            darkTheme ? "text-[#E3DFFD]" : "text-[#241847]"
          }`}
        >
          We Sent a OTP to Email and OTP will be valid for{" "}
          <span className="text-orange-400"> 2 min </span> only !!
        </h1>
      </div>
      <button
        onClick={() => {
          handelOTPverification(otp.join(""), location.state.email, navigate, dispatch);
        }}
        className={`mt-6 px-6 py-2 rounded-lg transition ${
          darkTheme ? "bg-[#A66CFF] text-[#E3DFFD]" : "bg-[#A66CFF] text-[#241847]"
        }`}
      >
        Verify OTP
      </button>
      <p className={`mt-4 ${darkTheme ? "text-[#E3DFFD]" : "text-[#241847]"}`}>
        Didn’t receive the OTP?{" "}
        <span
          onClick={() => handelResendOTP(location.state.email)}
          className={`cursor-pointer hover:underline ${
            darkTheme ? "text-[#874CCC] hover:text-[#A66CFF]" : "text-[#874CCC] hover:text-[#A66CFF]"
          }`}
        >
          Resend OTP
        </span>
      </p>
      <ToastContainer
        position="top-right"
        autoClose={5000}
        hideProgressBar={false}
        newestOnTop={false}
        closeOnClick
        rtl={false}
        pauseOnFocusLoss
        draggable
        pauseOnHover
        theme="light"
      />
    </div>
  );
};

export default OTP;
```

### `frontend\src\screens\OTP\utility\handelOTPverification.js`

```javascript
import { toast } from "react-toastify";
import axiosInstance from "../../../config/axios/axios";
import { setUser } from "../../../app/slices/userSlice";


const handelOTPverification = async (otp, email, navigate , dispatch) => {
    

    if(!email) {
        toast.error("Please enter a valid email address ", {
            position: "top-right",
            autoClose: 5000,    
            hideProgressBar: false,
            closeOnClick: false,
            pauseOnHover: true,
            draggable: true,
            progress: undefined,
            theme: "light",
        });
        return;
    }
   
   
    axiosInstance
        .post("/api/otp/verifyotp", { otp, email }) // send otp and email to backend via body
        .then((res) => {
            console.log(res.data);
            if (res.data) {
                localStorage.setItem("token", res.data.token); // store token in local storage
                toast.success(res.data.message, {
                    position: "top-right",
                    autoClose: 3000,
                    hideProgressBar: false,
                    closeOnClick: false,
                    pauseOnHover: true,
                    draggable: true,
                    progress: undefined,
                    theme: "dark",
                });

                console.log(res.data.user);

                dispatch(setUser(res.data.user)); 

                setTimeout(() => {
                    navigate("/password-strength-checker");
                }, 3000);
            }
        })
        .catch((err) => {
            console.log(err.response?.data?.errors?.[0] || "An error occurred");
            toast.error(err.response?.data?.errors?.[0] + " Try Resending OTP to your Email" || "An error occurred", {
                position: "top-right",
                autoClose: 5000,
                hideProgressBar: false,
                closeOnClick: false,
                pauseOnHover: true,
                draggable: true,
                progress: undefined,
                theme: "light",
            });

        });
};


export default handelOTPverification;








```

### `frontend\src\screens\OTP\utility\handelResendOTP.js`

```javascript
import axiosInstance from "../../../config/axios/axios";
import { toast } from "react-toastify";

const handelResendOTP = (email) => {

    axiosInstance
        .post("/api/otp/resendotp", { email: email }) // send email to backend via body
        .then((res) => {
            console.log(res.data);
            toast.success(res.data.message, {
                position: "top-right",
                autoClose: 5000,
                hideProgressBar: false,
                closeOnClick: false,
                pauseOnHover: true,
                draggable: true,
                progress: undefined,
                theme: "dark",
            });


        })
        .catch((err) => {
            console.log(err.response?.data?.errors?.[0] || "An error occurred");
            toast.error(
                err.response?.data?.errors?.[0] +
                " Try Resending OTP to your Email" || "An error occurred",
                {
                    position: "top-right",
                    autoClose: 5000,
                    hideProgressBar: false,
                    closeOnClick: false,
                    pauseOnHover: true,
                    draggable: true,
                    progress: undefined,
                    theme: "light",
                }
            );
        });
};

export default handelResendOTP;
```

### `frontend\src\screens\PasswordBreachCheck\PasswordBreachCheck.jsx`

```javascript
import React, { useState } from 'react';
import axios from 'axios';
import sha1 from 'crypto-js/sha1';
import { useSelector } from 'react-redux';

const PasswordBreachCheck = () => {
  const darkTheme = useSelector((state) => state.theme.darkTheme);
  const [password, setPassword] = useState('');
  const [breachCount, setBreachCount] = useState(null);
  const [loading, setLoading] = useState(false);

  const checkPassword = async () => {
    if (!password) return;

    setLoading(true);
    setBreachCount(null);

    try {
      const hashed = sha1(password).toString().toUpperCase();
      const prefix = hashed.slice(0, 5);
      const suffix = hashed.slice(5);

      const res = await axios.get(`https://api.pwnedpasswords.com/range/${prefix}`);
     

      const lines = res.data.split('\n');
      const match = lines.find(line => line.startsWith(suffix));

      if (match) {
        const count = parseInt(match.split(':')[1]);
        setBreachCount(count);
      } else {
        setBreachCount(0);
      }
    } catch (err) {
      console.error('Error checking password breach:', err);
      setBreachCount(-1);
    }

    setLoading(false);
  };

  return (
    <div className={`min-h-screen w-full flex items-center justify-center px-4 transition-colors duration-300 
      ${darkTheme ? 'bg-dark-background text-dark-primaryText' : 'bg-light-background text-light-primaryText'}
    `}>
      <div className={`w-full max-w-xl p-8 rounded-2xl shadow-2xl transition-all duration-300 
        ${darkTheme ? 'bg-dark-secondary' : 'bg-light-secondary'}
      `}>
        <h1 className="text-3xl font-bold mb-6 text-center">🔐 Password Breach Checker</h1>

        <input
          type="password"
          placeholder="Enter your password..."
          value={password}
          onChange={(e) => setPassword(e.target.value)}
          className={`w-full p-3 rounded-xl border-2 outline-none mb-4 transition 
            ${darkTheme 
              ? 'bg-dark-background text-dark-primaryText border-dark-hover placeholder-dark-secondaryText' 
              : 'bg-light-background text-light-primaryText border-light-hover placeholder-light-secondaryText'}
          `}
        />

        <button
          onClick={checkPassword}
          disabled={loading || !password}
          className={`w-full py-3 rounded-xl font-semibold transition-colors text-lg
            ${darkTheme 
              ? 'bg-dark-action text-dark-background hover:bg-dark-hover' 
              : 'bg-light-action text-white hover:bg-light-hover'}
          `}
        >
          {loading ? 'Checking...' : 'Check Breach'}
        </button>

        {breachCount !== null && (
          <div className={`mt-6 text-xl font-medium text-center
            ${breachCount === -1 
              ? 'text-yellow-500' 
              : breachCount > 0 
                ? 'text-red-500' 
                : 'text-green-600'}
          `}>
            {breachCount === -1
              ? '❌ Error checking breach.'
              : breachCount > 0
                ? `⚠️ This password was found in ${breachCount} breaches.   Try a different one! for better security.`
                : '✅ This password was not found in any known breach.'}
          </div>
        )}
      </div>
    </div>
  );
};

export default PasswordBreachCheck;

```

### `frontend\src\screens\profile\ProfilePage.jsx`

```javascript
import React, { useEffect, useState } from "react";
import { useSelector } from "react-redux";
import {
  BadgeCheck,
  Mail,
  Smartphone,
  MapPin,
  KeyRound,
  ShieldAlert,
} from "lucide-react";
import axiosInstance from "../../config/axios/axios"; // Adjust the import path as necessary
import LoadingScreen from "../../components/LoadingScreen/LoadingScreen";
import ProfileEditModal from "../../components/ProfileEditModal/ProfileEditModal";

export default function ProfilePage() {
  const [user, setUser] = useState(null);
  const [loading, setLoading] = useState(true);
  const [showModal, setShowModal] = useState(false);
  const u = useSelector((state) => state.user.user); // Assuming you have a Redux store with a user slice
  const darkTheme = useSelector((state) => state.theme.darkTheme); // Assuming you have a Redux store with a theme slice
  const handleUpdate = (updatedUser) => setUser(updatedUser);

  useEffect(() => {
    async function fetchuserData() {
      axiosInstance
        .get(`/api/user/${u._id}`)
        .then((res) => setUser(res.data.user))
        .catch((err) => console.log(err))
        .finally(() => setLoading(false));
    }
    fetchuserData();
  }, []);

  return loading ? (
    <LoadingScreen />
  ) : (
    <div
      className={`mx-auto min-h-screen p-4 sm:p-6 md:p-8 lg:p-10 xl:p-12 ${
        darkTheme ? "bg-dark-background text-dark-primaryText" : "bg-light-background text-light-primaryText"
      }`}
    >
      {/* Profile Header */}
      <div
        className={`rounded-xl sm:rounded-2xl shadow-md p-4 sm:p-6 flex flex-col sm:flex-row items-center gap-4 sm:gap-6 ${
          darkTheme ? "bg-dark-secondary" : "bg-light-secondary"
        }`}
      >
        <img
          src={user?.profilePicture}
          alt="Profile"
          className="w-16 h-16 sm:w-20 sm:h-20 rounded-full object-cover border"
        />
        <div className="text-center sm:text-left">
          <h2
            className={`text-xl sm:text-2xl font-bold flex items-center justify-center sm:justify-start gap-2 ${
              darkTheme ? "text-dark-primaryText" : "text-light-primaryText"
            }`}
          >
            {user.username}
            {user.isVerified && <BadgeCheck className="text-blue-500 w-4 h-4 sm:w-5 sm:h-5" />}
          </h2>
          <p
            className={`text-sm ${
              darkTheme ? "text-dark-secondaryText" : "text-light-secondaryText"
            }`}
          >
            {user.email}
          </p>
          <p
            className={`text-sm ${
              darkTheme ? "text-dark-secondaryText" : "text-light-secondaryText"
            }`}
          >
            {user.phoneNumber}
          </p>
        </div>
        <button
          onClick={() => setShowModal(true)}
          className="mt-4 px-4 py-2 bg-blue-500 text-white rounded-md hover:bg-blue-600"
        >
          Edit Profile
        </button>
      </div>

      {/* Shared Apps */}
      <section className="mt-6 sm:mt-8">
        <h3
          className={`text-lg sm:text-xl font-semibold mb-3 sm:mb-4 ${
            darkTheme ? "text-dark-primaryText" : "text-light-primaryText"
          }`}
        >
          Shared Apps
        </h3>
        <div className="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
          {user.sharedData?.map((app) => (
            <div
              key={app._id}
              className={`p-3 sm:p-4 rounded-md sm:rounded-xl shadow-md ${
                darkTheme ? "bg-dark-secondary hover:bg-dark-hover" : "bg-light-secondary hover:bg-light-hover"
              }`}
            >
              <h4
                className={`font-bold text-md sm:text-lg mb-1 sm:mb-2 truncate ${
                  darkTheme ? "text-dark-accent" : "text-light-accent"
                }`}
                title={app.appName}
              >
                {app.appName}
              </h4>
              <div className="flex flex-wrap gap-1 sm:gap-2 text-xs sm:text-sm">
                {Object.entries(app.sharedData).map(([field, shared]) =>
                  shared ? (
                    <span
                      key={field}
                      className={`${
                        darkTheme ? "bg-green-800 text-white" : "bg-green-100 text-green-800"
                      } px-1.5 py-0.5 sm:px-2 sm:py-1 rounded-full flex items-center gap-0.5 sm:gap-1`}
                    >
                      {field === "email" && <Mail className="w-3 h-3 sm:w-4 sm:h-4" />}
                      {field === "phoneNumber" && <Smartphone className="w-3 h-3 sm:w-4 sm:h-4" />}
                      {field === "location" && <MapPin className="w-3 h-3 sm:w-4 sm:h-4" />}
                      {field === "password" && <KeyRound className="w-3 h-3 sm:w-4 sm:h-4" />}
                      {field === "aadhaarNumber" && <ShieldAlert className="w-3 h-3 sm:w-4 sm:h-4" />}
                      {field}
                    </span>
                  ) : null
                )}
              </div>
              <p
                className={`mt-1 sm:mt-2 text-xs sm:text-sm ${
                  darkTheme ? "text-dark-secondaryText" : "text-light-secondaryText"
                }`}
              >
                Accessed on: {new Date(app.accessDate).toLocaleDateString()}
              </p>
            </div>
          ))}
        </div>
      </section>



      {/* Fake Data */}
      <section className="mt-6 sm:mt-8">
        <h3
          className={`text-lg sm:text-xl font-semibold mb-3 sm:mb-4 ${
            darkTheme ? "text-dark-primaryText" : "text-light-primaryText"
          }`}
        >
          Saved Fake Data
        </h3>
        <div className="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
          {user.savedFakeData?.map((fake) => (
            <div
              key={fake._id}
              className={`p-3 sm:p-4 rounded-md sm:rounded-xl shadow-sm ${
                darkTheme ? "bg-dark-secondary" : "bg-light-secondary"
              } ${darkTheme ? "text-dark-primaryText" : "text-light-primaryText"}`}
            >
              <p className="text-sm sm:text-base">
                <strong>Name:</strong> {fake.name}
              </p>
              <p className="text-sm sm:text-base">
                <strong>Phone:</strong> {fake.phone}
              </p>
              <p className="text-sm sm:text-base">
                <strong>Address:</strong> {fake.address}, {fake.city}, {fake.state}
              </p>
              <p className="text-sm sm:text-base">
                <strong>Aadhaar:</strong> {fake.aadhar}
              </p>
            </div>
          ))}
        </div>
      </section>


      {showModal && (
        <ProfileEditModal
          user={user}
          onClose={() => setShowModal(false)}
          onUpdate={handleUpdate}
        />
      )}



    </div>
  );
}
```

### `frontend\src\screens\Register\Register componets\PasswordStrength.jsx`

```javascript
import React from "react";
import { AiOutlineCheck } from "react-icons/ai";
import { AiOutlineClose } from "react-icons/ai";


const PasswordCriteria = ({ password }) => {
    const criteria = [
        { label: "At least 6 characters", met: password.length >= 6 },
        { label: "Contains uppercase letter", met: /[A-Z]/.test(password) },
        { label: "Contains lowercase letter", met: /[a-z]/.test(password) },
        { label: "Contains a number", met: /\d/.test(password) },
        { label: "Contains special character", met: /[^A-Za-z0-9]/.test(password) },
    ];

    return (
        <div className="mt-2 space-y-1">
            {criteria.map((item, index) => (
                <div key={index} className="flex items-center text-xs transition duration-200 ease-in-out">
                    {item.met ? (
                        <span className="text-green-500 mr-2"><AiOutlineCheck /></span> // Right icon
                    ) : (
                        <span className="text-red-500 mr-2"><AiOutlineClose/></span> // Wrong icon
                    )}
                    <span className={item.met ? "text-green-500 transition duration-200 ease-in-out" : "text-gray-400"}>
                        {item.label}
                    </span>
                </div>
            ))}
        </div>
    );
};

const PasswordStrength = ({ password }) => {
    const getStrength = (pass) => {
        let strength = 0;

        if (pass.length >= 6) strength++;
        if (/[A-Z]/.test(pass) && /[a-z]/.test(pass)) strength++;
        if (/\d/.test(pass)) strength++;
        if (/[^A-Za-z0-9]/.test(pass)) strength++;

        return strength;
    };

    const strength = getStrength(password);

    const getStrengthText = () => {
        switch (strength) {
            case 0:
                return "Very Weak";
            case 1:
                return "Weak";
            case 2:
                return "Moderate";
            case 3:
                return "Strong";
            default:
                return "Very Strong";
        }
    };

    return (
        <div className="mt-1">
            <div>
                <span className="text-xs text-gray-400">Password Strength: </span>
                <span className="text-xs text-gray-400">{getStrengthText()}</span>
            </div>

            <div className="h-1 w-full bg-gray-200 rounded-full mt-1 transition duration-200 ">
                <div
                    className={`h-full rounded-full ${
                        strength === 0
                            ? "bg-red-500"
                            : strength === 1
                            ? "bg-yellow-500"
                            : strength === 2
                            ? "bg-blue-500"
                            : "bg-green-500"
                    }`}
                    style={{ width: `${(strength / 4) * 100}%` }}
                ></div>
            </div>

            <PasswordCriteria password={password} />
        </div>
    );
};

export default PasswordStrength;

```

### `frontend\src\screens\Register\Register.jsx`

```javascript
import React, { useState } from "react";
import PasswordStrength from "./Register componets/PasswordStrength";
import { useNavigate } from "react-router-dom";
import { FaArrowLeft } from "react-icons/fa";
import axiosInstance from "../../config/axios/axios";
import { ToastContainer, toast } from "react-toastify";
import Loading from "../../components/Loading";
import { useSelector } from "react-redux";

const Register = () => {
  const [errors, setErrors] = useState([]);
  const [passwordVisible, setPasswordVisible] = useState(false);
  const [formData, setFormData] = useState({
    firstName: "",
    lastName: "",
    email: "",
    phoneNumber: "",
    password: "",
    agree: false,
  });
  const [isLoading, setIsLoading] = useState(false);
  const navigate = useNavigate();
  const { darkTheme } = useSelector((state) => state.theme);

  const togglePasswordVisibility = () => setPasswordVisible(!passwordVisible);

  const handleChange = (e) => {
    const { name, value, type, checked } = e.target;
    setFormData({
      ...formData,
      [name]: type === "checkbox" ? checked : value,
    });
  };

  const handelRegisterUser = async (e) => {
    setErrors([]);
    setIsLoading(true);
    try {
      e.preventDefault();
      const { firstName, lastName, email, password, phoneNumber } = formData;
      if (!firstName || !lastName || !email || !password || !phoneNumber) {
        setErrors(["All fields are required"]);
        toast.error("All fields are required", {
          position: "top-right",
          autoClose: 5000,
          hideProgressBar: false,
          closeOnClick: false,
          pauseOnHover: true,
          draggable: true,
          progress: undefined,
          theme: "light",
        });
        setIsLoading(false);
        return;
      }
      if (!formData.agree) {
        setErrors(["You must agree to the terms and conditions"]);
        toast.error(errors[0], {
          position: "top-right",
          autoClose: 5000,
          hideProgressBar: false,
          closeOnClick: false,
          pauseOnHover: true,
          draggable: true,
          progress: undefined,
          theme: "light",
        });
        setIsLoading(false);
        return;
      }

      const response = await axiosInstance.post("api/auth/register", formData);

      if (response.status === 201) {
        localStorage.setItem("token", response.data.token);
        toast.success("User registered successfully \n Now Verify the Email !!", {
          position: "top-right",
          autoClose: 5000,
          hideProgressBar: false,
          closeOnClick: false,
          pauseOnHover: true,
          draggable: true,
          progress: undefined,
          theme: "light",
        });
        setTimeout(() => {
          navigate("/otp", { state: { email: formData.email } });
        }, 1500);
      }
      setIsLoading(false);
    } catch (error) {
      const errorMessage =
        error.response?.data?.errors.join(", ") || "An error occurred";
      setErrors([errorMessage]);

      toast.error(errors[0], {
        position: "top-right",
        autoClose: 5000,
        hideProgressBar: false,
        closeOnClick: false,
        pauseOnHover: true,
        draggable: true,
        progress: undefined,
        theme: "light",
      });
      setIsLoading(false);
    }
  };

  return (
    <div
      className={`flex p-4 items-center justify-center min-h-screen relative ${
        darkTheme ? "bg-[#1A102B]" : "bg-[#F2F0FC]"
      }`}
    >


      <div
        className={`w-96 p-3 rounded-lg ${
          darkTheme ? "bg-[#221736]" : "bg-[#DCD6F7]"
        }`}
      >
        <h2 className={`text-xl font-bold mb-4 ${darkTheme ? "text-[#E3DFFD]" : "text-[#241847]"}`}>
          Sign Up
        </h2>
        <form className=""> 
          <div className="grid grid-cols-2 gap-2">
            <input
              type="text"
              name="firstName"
              value={formData.firstName}
              onChange={handleChange}
              placeholder="First Name"
              className={`w-full p-2 rounded-full border ${
                darkTheme ? "border-[#874CCC] text-[#E3DFFD]" : "border-[#874CCC] text-[#241847]"
              } bg-transparent`}
            />
            <input
              type="text"
              name="lastName"
              value={formData.lastName}
              onChange={handleChange}
              placeholder="Last Name"
              className={`w-full p-2 rounded-full border ${
                darkTheme ? "border-[#874CCC] text-[#E3DFFD]" : "border-[#874CCC] text-[#241847]"
              } bg-transparent`}
            />
          </div>
          <input
            type="email"
            name="email"
            value={formData.email}
            onChange={handleChange}
            placeholder="Email"
            className={`w-full mt-3 p-2 rounded-full border ${
              darkTheme ? "border-[#874CCC] text-[#E3DFFD]" : "border-[#874CCC] text-[#241847]"
            } bg-transparent`}
          />
          <input
            type="text"
            name="phoneNumber"
            value={formData.phoneNumber}
            onChange={handleChange}
            placeholder="Phone Number"
            className={`w-full mt-3 p-2 rounded-full border ${
              darkTheme ? "border-[#874CCC] text-[#E3DFFD]" : "border-[#874CCC] text-[#241847]"
            } bg-transparent`}
          />
          <div className="relative mt-3">
            <input
              type={passwordVisible ? "text" : "password"}
              name="password"
              value={formData.password}
              onChange={handleChange}
              placeholder="Password"
              className={`w-full p-2 rounded-full border ${
                darkTheme ? "border-[#874CCC] text-[#E3DFFD]" : "border-[#874CCC] text-[#241847]"
              } bg-transparent`}
            />
            <span
              onClick={togglePasswordVisibility}
              className={`absolute right-3 top-2 cursor-pointer ${darkTheme ? "text-[#874CCC]" : "text-[#874CCC]"}`}
            >
              {passwordVisible ? "Hide" : "Show"}
            </span>
          </div>

          <PasswordStrength password={formData.password} />

          <div className="flex items-center mt-3">
            <input
              type="checkbox"
              id="agree"
              name="agree"
              checked={formData.agree}
              onChange={handleChange}
              className="mr-2"
            />
            <label htmlFor="agree" className={darkTheme ? "text-[#E3DFFD]" : "text-[#241847]"}>
              I Agree with <span className={darkTheme ? "text-[#874CCC]" : "text-[#874CCC]"}>privacy</span> and{" "}
              <span className={darkTheme ? "text-[#874CCC]" : "text-[#874CCC]"}>policy</span>
            </label>
          </div>
          <button
            onClick={(e) => {
              handelRegisterUser(e);
            }}
            className={`w-full mt-4 p-2 rounded-full ${
              darkTheme ? "bg-[#A66CFF] text-[#E3DFFD]" : "bg-[#A66CFF] text-[#241847]"
            }`}
          >
            {isLoading ? <Loading /> : "Sign Up"}
          </button>
          <ToastContainer />
        </form>
        <p className={`mt-4 text-center ${darkTheme ? "text-[#E3DFFD]" : "text-[#241847]"}`}>
          Already have an account?{" "}
          <a href="/login" className={darkTheme ? "text-[#874CCC]" : "text-[#874CCC]"}>
            Sign in
          </a>
        </p>
      </div>
    </div>
  );
};

export default Register;
```

### `frontend\src\screens\SharedApps\SharedApps.jsx`

```javascript
import React, { useEffect, useState } from "react";
import axiosInstance from "../../config/axios/axios";
import { motion } from "framer-motion";
import { useSelector, useDispatch } from "react-redux";
import {
  setSharedAppsData,
  addSharedApp,
  removeSharedApp,
  updateSharedAppLocal,
} from "../../app/slices/sharedAppsSlice";

const SharedApps = () => {
  const { darkTheme } = useSelector((state) => state.theme);

  const sharedApps = useSelector((state) => state.sharedApps.sharedApps);
  const dispatch = useDispatch();
  const [loading, setLoading] = useState(true);
  const [error, setError] = useState(null);
  const [editingApp, setEditingApp] = useState(null);
  const [updatedData, setUpdatedData] = useState({});
  const [showModal, setShowModal] = useState(false);
  const [newAppData, setNewAppData] = useState({
    appName: "",
    accessDate: "",
    sharedData: {
      email: false,
      password: false,
      phoneNumber: false,
      location: false,
      aadhaarNumber: false,
    },
  });
  const [showCreateModal, setShowCreateModal] = useState(false);
  const DATA_WEIGHTS = {
    email: 10,
    password: 25,
    phoneNumber: 15,
    location: 20,
    aadhaarNumber: 30,
  };

  const calculateRiskScore = (sharedData) => {
    let score = 0;
    for (const [key, value] of Object.entries(sharedData)) {
      if (value && DATA_WEIGHTS[key]) {
        score += DATA_WEIGHTS[key];
      }
    }
    return score; // max is 100
  };

  

  const handleNewToggle = (field) => {
    setNewAppData((prev) => ({
      ...prev,
      sharedData: {
        ...prev.sharedData,
        [field]: !prev.sharedData[field],
      },
    }));
  };

  const createSharedApp = async () => {
    try {
      const res = await axiosInstance.post("/api/sharedApps", {
        appName: newAppData.appName,
        accessDate: newAppData.accessDate,
        sharedData: newAppData.sharedData,
      });
      dispatch(addSharedApp(res.data));
      setShowCreateModal(false);
      setNewAppData({
        appName: "",
        accessDate: "",
        sharedData: {
          email: false,
          password: false,
          phoneNumber: false,
          location: false,
          aadhaarNumber: false,
        },
      });
    } catch (err) {
      console.error("Create failed:", err);
    }
  };

  useEffect(() => {
    fetchSharedApps();
  }, []);

  const fetchSharedApps = async () => {
    try {
      const token = localStorage.getItem("token");
      const res = await axiosInstance.get("/api/sharedApps", {
        headers: {
          Authorization: `Bearer ${token}`,
        },
      });
      dispatch(setSharedAppsData(res.data));
    } catch (err) {
      setError("Failed to load shared apps");
    } finally {
      setLoading(false);
    }
  };

  const deleteApp = async (id) => {
    try {
      const token = localStorage.getItem("token");
      await axiosInstance.delete(`/api/sharedApps/${id}`);
      dispatch(removeSharedApp(id));
    } catch (err) {
      console.error("Delete failed:", err);
    }
  };

  const openEditModal = (app) => {
    setEditingApp(app);
    setUpdatedData(app.sharedData);
    setShowModal(true);
  };

  const handleToggle = (field) => {
    setUpdatedData((prev) => ({
      ...prev,
      [field]: !prev[field],
    }));
  };

  const updateSharedApp = async () => {
    try {
      const token = localStorage.getItem("token");
      const res = await axiosInstance.put(`/api/sharedApps/${editingApp._id}`, {
        sharedData: updatedData,
      });
      dispatch(
        updateSharedAppLocal({ ...editingApp, sharedData: updatedData })
      );
      setShowModal(false);
    } catch (err) {
      console.error("Update failed:", err);
    }
  };

  return (
    <div
      className={`min-h-screen px-4 py-10 ${
        darkTheme
          ? "bg-dark-background text-dark-primaryText"
          : "bg-light-background text-light-primaryText"
      }`}
    >
      <h1 className="text-3xl font-bold text-center mb-8">Shared Apps</h1>

      {loading && <p className="text-center">Loading...</p>}
      {error && <p className="text-center text-red-500">{error}</p>}

      <div className="flex justify-end mb-6">
        <button
          onClick={() => setShowCreateModal(true)}
          className="bg-green-600 text-white px-4 py-2 rounded hover:bg-green-700 transition"
        >
          + New App
        </button>
      </div>

      <div className="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-6">
        {sharedApps.map((app) => (
          <motion.div
            key={app._id}
            initial={{ opacity: 0, y: 20 }}
            animate={{ opacity: 1, y: 0 }}
            transition={{ duration: 0.5 }}
            className={`rounded-2xl p-4 shadow-lg hover:shadow-xl transition-all ${
              darkTheme
                ? "bg-dark-secondary text-dark-secondaryText hover:bg-dark-hover"
                : "bg-light-secondary text-light-secondaryText hover:bg-light-hover"
            }`}
          >
            <h2
              className={`text-xl font-semibold mb-2 ${
                darkTheme ? "text-dark-accent" : "text-light-accent"
              }`}
            >
              {app.appName}
            </h2>
            <p className="mt-3 font-medium">
              Data Risk Score:{"  "}
              <span
                className={
                  calculateRiskScore(app.sharedData) >= 70
                    ? "text-red-500"
                    : calculateRiskScore(app.sharedData) >= 40
                    ? "text-yellow-500"
                    : "text-green-500"
                }
              >
                {calculateRiskScore(app.sharedData)} / 100
              </span>
            </p>

            <div className="text-sm space-y-1">
              {Object.entries(app.sharedData).map(([key, value]) => (
                <p key={key}>
                  {key}:{" "}
                  {value ? (
                    <span className="text-green-500">✅ Shared</span>
                  ) : (
                    <span className="text-red-500">❌ Not Shared</span>
                  )}
                </p>
              ))}
              <p className="text-xs mt-2">
                Accessed: {new Date(app.accessDate).toLocaleDateString()}
              </p>
              {app.lastAccessed && (
                <p className="text-xs">
                  Last Accessed:{" "}
                  {new Date(app.lastAccessed).toLocaleDateString()}
                </p>
              )}
            </div>
            <div className="mt-4 flex gap-2">
              <button
                onClick={() => openEditModal(app)}
                className={`px-3 py-1 rounded transition ${
                  darkTheme
                    ? "bg-dark-action text-white hover:bg-dark-hover"
                    : "bg-light-action text-light-primaryText hover:bg-light-hover"
                }`}
              >
                Edit
              </button>
              <button
                onClick={() => deleteApp(app._id)}
                className="bg-red-600 text-white px-3 py-1 rounded hover:bg-red-800 transition"
              >
                Delete
              </button>
            </div>
          </motion.div>
        ))}
      </div>

      {/* Modal for Creating Shared App */}
      {showCreateModal && (
        <div
          className={`fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50 ${
            darkTheme ? "bg-dark-background" : "bg-light-background"
          }`}
        >
          <motion.div
            initial={{ scale: 0.8, opacity: 0 }}
            animate={{ scale: 1, opacity: 1 }}
            className={`rounded-xl p-6 w-full max-w-md shadow-lg ${
              darkTheme
                ? "bg-dark-secondary text-dark-primaryText"
                : "bg-light-secondary text-light-primaryText"
            }`}
          >
            <h2 className="text-xl font-bold mb-4">Create Shared App</h2>
            <input
              type="text"
              placeholder="App Name"
              value={newAppData.appName}
              onChange={(e) =>
                setNewAppData({ ...newAppData, appName: e.target.value })
              }
              className={`w-full mb-3 px-3 py-2 rounded ${
                darkTheme
                  ? "bg-dark-input border border-gray-700 text-black"
                  : "bg-light-input border border-gray-300 text-black"
              }`}
            />
            <input
              type="date"
              value={newAppData.accessDate}
              onChange={(e) =>
                setNewAppData({ ...newAppData, accessDate: e.target.value })
              }
              className={`w-full mb-4 px-3 py-2 rounded ${
                darkTheme
                  ? "bg-dark-input border border-gray-700 text-white"
                  : "bg-light-input border border-gray-300 text-black"
              }`}
            />
            <div className="space-y-2">
              {Object.entries(newAppData.sharedData).map(([key, value]) => (
                <div key={key} className="flex items-center justify-between">
                  <span>{key}</span>
                  <input
                    type="checkbox"
                    checked={value}
                    onChange={() => handleNewToggle(key)}
                    className="h-4 w-4"
                  />
                </div>
              ))}
            </div>
            <div className="mt-6 flex justify-end gap-2">
              <button
                onClick={() => setShowCreateModal(false)}
                className="px-4 py-1 rounded bg-gray-600 hover:bg-gray-800 text-white"
              >
                Cancel
              </button>
              <button
                onClick={createSharedApp}
                className="px-4 py-1 rounded bg-green-600 hover:bg-green-700 text-white"
              >
                Create
              </button>
            </div>
          </motion.div>
        </div>
      )}

      {/* Modal for Editing Shared App */}
      {showModal && editingApp && (
        <div
          className={`fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50 ${
            darkTheme ? "bg-dark-background" : "bg-light-background"
          }`}
        >
          <motion.div
            initial={{ scale: 0.8, opacity: 0 }}
            animate={{ scale: 1, opacity: 1 }}
            className={`rounded-xl p-6 w-full max-w-md shadow-lg ${
              darkTheme
                ? "bg-dark-secondary text-dark-primaryText"
                : "bg-light-secondary text-light-primaryText"
            }`}
          >
            <h2 className="text-xl font-bold mb-4">
              Edit Shared Data - {editingApp.appName}
            </h2>
            <div className="space-y-2">
              {Object.entries(updatedData).map(([key, value]) => (
                <div key={key} className="flex items-center justify-between">
                  <span>{key}</span>
                  <input
                    type="checkbox"
                    checked={value}
                    onChange={() => handleToggle(key)}
                    className="h-4 w-4"
                  />
                </div>
              ))}
            </div>
            <div className="mt-6 flex justify-end gap-2">
              <button
                onClick={() => setShowModal(false)}
                className="px-4 py-1 rounded bg-gray-600 hover:bg-gray-800 text-white"
              >
                Cancel
              </button>
              <button
                onClick={updateSharedApp}
                className={`px-4 py-1 rounded transition ${
                  darkTheme
                    ? "bg-dark-action hover:bg-dark-hover text-white"
                    : "bg-light-action hover:bg-light-hover text-light-primaryText"
                }`}
              >
                Save
              </button>
            </div>
          </motion.div>
        </div>
      )}
    </div>
  );
};

export default SharedApps;

```

### `frontend\src\screens\unlockVault\UnlockVault.jsx`

```javascript
import React, { useState } from 'react';
import { useSelector, useDispatch } from 'react-redux';
import { setVaultUnlocked } from '../../app/slices/vaultSlice'; // Import your action
import { toast } from 'react-toastify';
import { useNavigate } from 'react-router-dom';
import axiosInstance from '../../config/axios/axios';

const UnlockVault = () => {
  const darkTheme = useSelector((state) => state.theme.darkTheme);
  const dispatch = useDispatch();  // Initialize dispatch
  const [password, setPassword] = useState('');
  const [loading, setLoading] = useState(false);
  const navigate = useNavigate();

  const handleUnlock = async (e) => {
    e.preventDefault();
    setLoading(true);

    try {
      const res = await axiosInstance.post('http://localhost:3000/api/vault/openvault', { password });
      toast.success(res.data.message || 'Vault unlocked!');

      // Dispatch the action to update the vault status in Redux
      dispatch(setVaultUnlocked(true));

      navigate('/vault');  // Navigate to the vault after unlocking
    } catch (err) {
      toast.error(err.response?.data?.message || 'Incorrect password');
    } finally {
      setLoading(false);
    }
  };

  return (
    <div className={`min-h-screen flex items-center justify-center px-4 ${darkTheme ? 'bg-dark-background text-dark-primaryText' : 'bg-light-background text-light-primaryText'}`}>
      <div className={`max-w-md w-full p-6 rounded-xl shadow-md ${darkTheme ? 'bg-dark-secondary' : 'bg-light-secondary'}`}>
        <h2 className="text-2xl font-bold mb-4">Unlock Vault</h2>
        <p className={`text-sm mb-4 ${darkTheme ? 'text-dark-secondaryText' : 'text-light-secondaryText'}`}>
          Enter your vault password to unlock your stored data.
        </p>

        <form onSubmit={handleUnlock} className="space-y-4">
          <div>
            <label htmlFor="password" className="block text-sm font-medium mb-1">
              Vault Password
            </label>
            <input
              type="password"
              id="password"
              value={password}
              onChange={(e) => setPassword(e.target.value)}
              required
              className={`w-full px-3 py-2 rounded-lg border focus:outline-none ${
                darkTheme
                  ? 'bg-dark-background border-gray-700 text-white'
                  : 'bg-white border-gray-300 text-black'
              }`}
            />
          </div>

          <button
            type="submit"
            disabled={loading}
            className={`w-full py-2 rounded-lg font-semibold transition ${
              loading
                ? 'opacity-50 cursor-not-allowed'
                : `${darkTheme ? 'bg-dark-action hover:bg-dark-hover' : 'bg-light-action hover:bg-light-hover'}`
            }`}
          >
            {loading ? 'Unlocking...' : 'Unlock Vault'}
          </button>
        </form>
      </div>
    </div>
  );
};

export default UnlockVault;

```

### `frontend\src\screens\UserInfo\UserInfo.jsx`

```javascript
import React from "react";

const UserInfo = () => {
  return (
    <div className="flex flex-col items-center justify-center h-screen bg-[#071952] text-[#EBF4F6] p-4">
      <h2 className="text-3xl font-semibold mb-6">User Information</h2>
      <div className="bg-[#EBF4F6] text-[#071952] p-6 rounded-xl shadow-lg w-full max-w-md">
        <label className="block mb-2 font-medium">Name</label>
        <input
          type="text"
          className="w-full p-2 mb-4 border-2 border-[#088395] rounded-lg focus:outline-none focus:border-[#37B7C3]"
          value="John Doe"
          readOnly
        />
        <label className="block mb-2 font-medium">Email</label>
        <input
          type="email"
          className="w-full p-2 mb-4 border-2 border-[#088395] rounded-lg focus:outline-none focus:border-[#37B7C3]"
          value="johndoe@example.com"
          readOnly
        />
        <button className="w-full p-2 bg-[#071952] text-white rounded-lg hover:bg-[#088395] transition">
          Edit Profile
        </button>
      </div>
      <button className="mt-6 px-6 py-2 bg-red-600 text-white rounded-lg hover:bg-red-700 transition">
        Log Out
      </button>
    </div>
  );
};

export default UserInfo;

```

### `frontend\src\screens\vault\Vault.jsx`

```javascript
import { useEffect, useState } from "react";
import { useNavigate } from 'react-router-dom';
import { useSelector, useDispatch } from "react-redux";
import axiosInstance from "../../config/axios/axios";
import { resetVault, setVaultUnlocked } from "../../app/slices/vaultSlice"; 
import { toast } from "react-toastify";
import { IoMdAdd } from "react-icons/io";
import AddPasswordModal from "../../components/AddPasswordModal";
import DeleteConfirmModal from "../../components/DeleteConfirmModal";
import UpdatePasswordModal from "../../components/UpdatePasswordModal";
import { Copy, Eye, EyeIcon, EyeOff, EyeOffIcon, Trash2 } from "lucide-react";

const Vault = () => {
  const darkTheme = useSelector((state) => state.theme.darkTheme);
  const dispatch = useDispatch();
  const navigate = useNavigate();
  const [vaultItems, setVaultItems] = useState([]);
  const [visibleIndex, setVisibleIndex] = useState(null);
  const [showAddModal, setShowAddModal] = useState(false);
  const [showDeleteModal, setShowDeleteModal] = useState(false);
  const [itemToDelete, setItemToDelete] = useState(null);
  const [showEditModal, setShowEditModal] = useState(false);
  const [selectedItem, setSelectedItem] = useState(null);

  const vaultUnlocked = useSelector((state) => state.vault.unlocked);

  useEffect(() => {
    const checkVaultStatus = async () => {
      try {
        const res = await axiosInstance.get(
          "http://localhost:3000/api/vault/isInitialized"
        );
        const user = res.data;
        dispatch(setVaultUnlocked(user.isInitialized));

        if (!user.isInitialized) {
          navigate("/setupVaultPassword");  // Redirect to setup password page if vault is not initialized
        } else if (!vaultUnlocked) {
          navigate("/vaultPassword");  // Navigate to the password entry page if vault is unlocked
        }
      } catch (err) {
        console.log("Error checking vault status:", err);
        toast.error("Could not check vault status. Try again.");
      }
    };

    checkVaultStatus();

    // Reset vault state when the component unmounts
    return () => {
      dispatch(resetVault());
    };
  }, [dispatch, navigate, vaultUnlocked]);

  useEffect(() => {
    if (vaultUnlocked) {
      const fetchVaultItems = async () => {
        try {
          const res = await axiosInstance.get("/api/vault/getall");
          setVaultItems(res.data); 
        } catch (err) {
          console.error(err);
          toast.error("Failed to load vault items");
        }
      };

      fetchVaultItems();
    }
  }, [vaultUnlocked]);

  const handleDeleteClick = (itemId) => {
    setItemToDelete(itemId);
    setShowDeleteModal(true);
  };

  const confirmDelete = async () => {
    try {
      await axiosInstance.delete(`/api/vault/delete/${itemToDelete}`);
      setVaultItems((prev) => prev.filter((item) => item._id !== itemToDelete));
      toast.success("Deleted successfully");
    } catch (err) {
      toast.error("Failed to delete");
    } finally {
      setShowDeleteModal(false);
      setItemToDelete(null);
    }
  };

  const toggleVisibility = (index) => {
    setVisibleIndex(index === visibleIndex ? null : index);
  };

  const handleCopy = (password) => {
    navigator.clipboard.writeText(password);
    toast.success("Password copied to clipboard!");
  };

  return (
<div
  className={`min-h-screen px-4 py-10 ${
    darkTheme ? "bg-dark-background text-dark-primaryText" : "bg-light-background text-light-primaryText"
  }`}
>
  <div className="max-w-7xl mx-auto w-full space-y-6">
    <div className="text-center space-y-2">
      <h1 className="text-3xl font-bold">🔐 Vault Access Granted</h1>
      <p className={`text-sm ${darkTheme ? "text-dark-secondaryText" : "text-light-secondaryText"}`}>
        Welcome to your secured Vault. Manage your passwords safely.
      </p>

      <button
        onClick={() => setShowAddModal(true)}
        className={`mt-4 px-4 py-2 rounded-xl font-semibold transition-all duration-200 flex items-center gap-2 mx-auto ${
          darkTheme ? "bg-dark-accent text-white hover:bg-dark-hover" : "bg-light-accent text-white hover:bg-light-hover"
        }`}
      >
        <IoMdAdd size={20} /> Add Password
      </button>
    </div>

    {/* Vault Cards */}
    <div className="grid grid-cols-[repeat(auto-fit,minmax(280px,1fr))] gap-6">
      {vaultItems.map((item, index) => (
        <div
          key={index}
          className={`p-5 rounded-2xl shadow-lg transition-all duration-200 border ${
            darkTheme
              ? "bg-dark-secondary text-dark-primaryText border-dark-border hover:shadow-dark-hover"
              : "bg-light-secondary text-light-primaryText border-light-border hover:shadow-lg"
          }`}
        >
          <div className="mb-2">
            <h3 className="font-semibold text-lg truncate">{item.title}</h3>
            <p className="font-mono text-base break-all">
              {visibleIndex === index ? item.password : "••••••••••••"}
            </p>
          </div>

          <div className="flex justify-end items-center gap-2 mt-3">
            <button
              onClick={() => toggleVisibility(index)}
              className="p-2 rounded-md hover:bg-gray-200 dark:hover:bg-gray-700 transition"
              title="Toggle visibility"
            >
              {visibleIndex === index ? <EyeOffIcon size={18} /> : <EyeIcon size={18} />}
            </button>

            <button
              onClick={() => handleCopy(item.password)}
              className="p-2 rounded-md hover:bg-gray-200 dark:hover:bg-gray-700 transition"
              title="Copy password"
            >
              <Copy size={18} />
            </button>

            <button
              onClick={() => handleDeleteClick(item._id)}
              className="p-2 rounded-md hover:bg-red-100 dark:hover:bg-red-900 text-red-500 transition"
              title="Delete"
            >
              <Trash2 size={18} />
            </button>

            <button
              onClick={() => {
                setSelectedItem(item);
                setShowEditModal(true);
              }}
              className="p-2 rounded-md hover:bg-blue-100 dark:hover:bg-blue-900 text-blue-500 transition"
              title="Edit"
            >
              Edit
            </button>
          </div>
        </div>
      ))}
    </div>
  </div>

  {/* Modals */}
  {showAddModal && (
    <AddPasswordModal
      isOpen={showAddModal}
      onClose={() => setShowAddModal(false)}
      onSuccess={(newItem) => {
        setVaultItems((prev) => [...prev, newItem]);
        toast.success("Password added successfully!");
      }}
    />
  )}

  <DeleteConfirmModal
    isOpen={showDeleteModal}
    onConfirm={confirmDelete}
    onCancel={() => {
      setShowDeleteModal(false);
      setItemToDelete(null);
    }}
  />

  <UpdatePasswordModal
    isOpen={showEditModal}
    vaultItem={selectedItem}
    onClose={() => {
      setShowEditModal(false);
      setSelectedItem(null);
    }}
    onSuccess={async () => {
      const res = await axiosInstance.get("/api/vault/getall");
      setVaultItems(res.data);
    }}
  />
</div>

  );
};

export default Vault;

```

### `frontend\src\screens\vaultPasswordSetup\vaultPasswordSetup.jsx`

```javascript
import React, { useState } from 'react';
import { useSelector } from 'react-redux';
import { toast } from 'react-toastify';
import axiosInstance from '../../config/axios/axios';
import { useNavigate } from 'react-router-dom';

const VaultPasswordSetup = () => {
  const darkTheme = useSelector((state) => state.theme.darkTheme);
  const [password, setPassword] = useState('');
  const [created, setCreated] = useState(false);
  const navigate = useNavigate();

  const handleSubmit = async (e) => {
    e.preventDefault();

    try {
      await axiosInstance.post('http://localhost:3000/api/vault/createvaultPassword', { password });
      setCreated(true);
      toast.success('Vault password created successfully 🎉');
      navigate("/vault")
    } catch (err) {
      console.error(err);
      toast.error('Failed to create vault password. Try again.');
    }
  };

  return (
    <div className={`min-h-screen flex items-center justify-center px-4 ${darkTheme ? 'bg-dark-background text-dark-primaryText' : 'bg-light-background text-light-primaryText'}`}>
      <div className={`max-w-md w-full p-6 rounded-xl shadow-md ${darkTheme ? 'bg-dark-secondary' : 'bg-light-secondary'}`}>
        <h2 className="text-2xl font-bold mb-4">Vault Password Setup</h2>
        <p className={`text-sm mb-4 ${darkTheme ? 'text-dark-secondaryText' : 'text-light-secondaryText'}`}>
          You can only create your vault password once. Please remember it.
        </p>

        <form onSubmit={handleSubmit} className="space-y-4">
          <div>
            <label htmlFor="password" className="block text-sm font-medium mb-1">
              Create Vault Password
            </label>
            <input
              type="password"
              id="password"
              value={password}
              onChange={(e) => setPassword(e.target.value)}
              disabled={created}
              required
              className={`w-full px-3 py-2 rounded-lg border focus:outline-none ${
                darkTheme
                  ? 'bg-dark-background border-gray-700 text-white'
                  : 'bg-white border-gray-300 text-black'
              }`}
            />
          </div>

          <button
            type="submit"
            disabled={created}
            className={`w-full py-2 rounded-lg font-semibold transition ${
              created
                ? 'cursor-not-allowed opacity-50'
                : `${darkTheme ? 'bg-dark-action hover:bg-dark-hover' : 'bg-light-action hover:bg-light-hover'}`
            }`}
          >
            Create Vault Password
          </button>
        </form>
      </div>
    </div>
  );
};

export default VaultPasswordSetup;

```

### `frontend\tailwind.config.js`

```javascript
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {
      colors: {
        dark: {
          background: '#1A102B',
          secondary: '#221736',
          primaryText: '#E3DFFD',
          secondaryText: '#A08DCC',
          accent: '#874CCC',
          action: '#A66CFF',
          hover: '#603F8B',
        },
        light: {
          background: '#F2F0FC',
          secondary: '#DCD6F7',
          primaryText: '#241847',
          secondaryText: '#5A4B8A',
          accent: '#874CCC',
          action: '#A66CFF',
          hover: '#C8B6E2',
        },
      },
    },
  },
  plugins: [],
}
```

### `frontend\vite.config.js`

```javascript
import { defineConfig } from 'vite'
import react from '@vitejs/plugin-react'

// https://vite.dev/config/
export default defineConfig({
  plugins: [react()],
})

```

### `generateMdFromProject.js`

```javascript
const fs = require('fs');
const path = require('path');

// Excluded folders and files
const EXCLUDE = ['node_modules', '.git', '.env', '.DS_Store'];

function isExcluded(fileOrDirName) {
  return EXCLUDE.includes(fileOrDirName);
}

function getLanguageFromExtension(filename) {
  const ext = path.extname(filename).toLowerCase();
  const extMap = {
    '.js': 'javascript',
    '.ts': 'typescript',
    '.jsx': 'javascript',
    '.tsx': 'typescript',
    '.json': 'json',
    '.html': 'html',
    '.css': 'css',
    '.md': 'markdown',
    '.sh': 'bash',
    '.py': 'python',
  };
  return extMap[ext] || '';
}

function generateMarkdownFromDir(dir, mdLines = []) {
  const entries = fs.readdirSync(dir, { withFileTypes: true });

  for (const entry of entries) {
    if (isExcluded(entry.name)) continue;

    const fullPath = path.join(dir, entry.name);

    if (entry.isDirectory()) {
      generateMarkdownFromDir(fullPath, mdLines);
    } else {
      const content = fs.readFileSync(fullPath, 'utf8');
      const language = getLanguageFromExtension(entry.name);
      const relativePath = path.relative(process.cwd(), fullPath);
      mdLines.push(`### \`${relativePath}\`\n`);
      mdLines.push(`\`\`\`${language}\n${content}\n\`\`\`\n`);
    }
  }

  return mdLines;
}

// Entry point
const projectDir = process.cwd(); // Or provide a specific path
const markdownLines = generateMarkdownFromDir(projectDir);
fs.writeFileSync('project_code.md', markdownLines.join('\n'));

console.log('✅ Markdown file generated: project_code.md');

```

### `project_code.md`

```markdown
### `backend\.gitignore`

```
.env
node_modules

```

### `backend\package-lock.json`

```json
{
  "name": "backend",
  "version": "1.0.0",
  "lockfileVersion": 3,
  "requires": true,
  "packages": {
    "": {
      "name": "backend",
      "version": "1.0.0",
      "license": "ISC",
      "dependencies": {
        "@faker-js/faker": "^9.6.0",
        "@imagekit/javascript": "^5.0.0",
        "axios": "^1.8.4",
        "bcrypt": "^5.1.1",
        "cors": "^2.8.5",
        "dotenv": "^16.4.7",
        "express": "^5.1.0",
        "imagekit": "^6.0.0",
        "jsonwebtoken": "^9.0.2",
        "mongoose": "^8.13.2",
        "morgan": "^1.10.0",
        "multer": "^1.4.5-lts.2",
        "node-cron": "^3.0.3",
        "nodemailer": "^6.10.0"
      }
    },
    "node_modules/@faker-js/faker": {
      "version": "9.6.0",
      "resolved": "https://registry.npmjs.org/@faker-js/faker/-/faker-9.6.0.tgz",
      "integrity": "sha512-3vm4by+B5lvsFPSyep3ELWmZfE3kicDtmemVpuwl1yH7tqtnHdsA6hG8fbXedMVdkzgtvzWoRgjSB4Q+FHnZiw==",
      "funding": [
        {
          "type": "opencollective",
          "url": "https://opencollective.com/fakerjs"
        }
      ],
      "license": "MIT",
      "engines": {
        "node": ">=18.0.0",
        "npm": ">=9.0.0"
      }
    },
    "node_modules/@imagekit/javascript": {
      "version": "5.0.0",
      "resolved": "https://registry.npmjs.org/@imagekit/javascript/-/javascript-5.0.0.tgz",
      "integrity": "sha512-Q4qaVHBXrnNFJ6nw7dQTEeyIZzAbz68Z0Y27D4bkiaW3kjpPNoFJEl6XCIiOulBpkVDMteRzjGuKk5bQzgTRRg==",
      "license": "MIT"
    },
    "node_modules/@mapbox/node-pre-gyp": {
      "version": "1.0.11",
      "resolved": "https://registry.npmjs.org/@mapbox/node-pre-gyp/-/node-pre-gyp-1.0.11.tgz",
      "integrity": "sha512-Yhlar6v9WQgUp/He7BdgzOz8lqMQ8sU+jkCq7Wx8Myc5YFJLbEe7lgui/V7G1qB1DJykHSGwreceSaD60Y0PUQ==",
      "license": "BSD-3-Clause",
      "dependencies": {
        "detect-libc": "^2.0.0",
        "https-proxy-agent": "^5.0.0",
        "make-dir": "^3.1.0",
        "node-fetch": "^2.6.7",
        "nopt": "^5.0.0",
        "npmlog": "^5.0.1",
        "rimraf": "^3.0.2",
        "semver": "^7.3.5",
        "tar": "^6.1.11"
      },
      "bin": {
        "node-pre-gyp": "bin/node-pre-gyp"
      }
    },
    "node_modules/@mongodb-js/saslprep": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/@mongodb-js/saslprep/-/saslprep-1.2.0.tgz",
      "integrity": "sha512-+ywrb0AqkfaYuhHs6LxKWgqbh3I72EpEgESCw37o+9qPx9WTCkgDm2B+eMrwehGtHBWHFU4GXvnSCNiFhhausg==",
      "license": "MIT",
      "dependencies": {
        "sparse-bitfield": "^3.0.3"
      }
    },
    "node_modules/@types/webidl-conversions": {
      "version": "7.0.3",
      "resolved": "https://registry.npmjs.org/@types/webidl-conversions/-/webidl-conversions-7.0.3.tgz",
      "integrity": "sha512-CiJJvcRtIgzadHCYXw7dqEnMNRjhGZlYK05Mj9OyktqV8uVT8fD2BFOB7S1uwBE3Kj2Z+4UyPmFw/Ixgw/LAlA==",
      "license": "MIT"
    },
    "node_modules/@types/whatwg-url": {
      "version": "11.0.5",
      "resolved": "https://registry.npmjs.org/@types/whatwg-url/-/whatwg-url-11.0.5.tgz",
      "integrity": "sha512-coYR071JRaHa+xoEvvYqvnIHaVqaYrLPbsufM9BF63HkwI5Lgmy2QR8Q5K/lYDYo5AK82wOvSOS0UsLTpTG7uQ==",
      "license": "MIT",
      "dependencies": {
        "@types/webidl-conversions": "*"
      }
    },
    "node_modules/abbrev": {
      "version": "1.1.1",
      "resolved": "https://registry.npmjs.org/abbrev/-/abbrev-1.1.1.tgz",
      "integrity": "sha512-nne9/IiQ/hzIhY6pdDnbBtz7DjPTKrY00P/zvPSm5pOFkl6xuGrGnXn/VtTNNfNtAfZ9/1RtehkszU9qcTii0Q==",
      "license": "ISC"
    },
    "node_modules/accepts": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/accepts/-/accepts-2.0.0.tgz",
      "integrity": "sha512-5cvg6CtKwfgdmVqY1WIiXKc3Q1bkRqGLi+2W/6ao+6Y7gu/RCwRuAhGEzh5B4KlszSuTLgZYuqFqo5bImjNKng==",
      "license": "MIT",
      "dependencies": {
        "mime-types": "^3.0.0",
        "negotiator": "^1.0.0"
      },
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/agent-base": {
      "version": "6.0.2",
      "resolved": "https://registry.npmjs.org/agent-base/-/agent-base-6.0.2.tgz",
      "integrity": "sha512-RZNwNclF7+MS/8bDg70amg32dyeZGZxiDuQmZxKLAlQjr3jGyLx+4Kkk58UO7D2QdgFIQCovuSuZESne6RG6XQ==",
      "license": "MIT",
      "dependencies": {
        "debug": "4"
      },
      "engines": {
        "node": ">= 6.0.0"
      }
    },
    "node_modules/ansi-regex": {
      "version": "5.0.1",
      "resolved": "https://registry.npmjs.org/ansi-regex/-/ansi-regex-5.0.1.tgz",
      "integrity": "sha512-quJQXlTSUGL2LH9SUXo8VwsY4soanhgo6LNSm84E1LBcE8s3O0wpdiRzyR9z/ZZJMlMWv37qOOb9pdJlMUEKFQ==",
      "license": "MIT",
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/append-field": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/append-field/-/append-field-1.0.0.tgz",
      "integrity": "sha512-klpgFSWLW1ZEs8svjfb7g4qWY0YS5imI82dTg+QahUvJ8YqAY0P10Uk8tTyh9ZGuYEZEMaeJYCF5BFuX552hsw==",
      "license": "MIT"
    },
    "node_modules/aproba": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/aproba/-/aproba-2.0.0.tgz",
      "integrity": "sha512-lYe4Gx7QT+MKGbDsA+Z+he/Wtef0BiwDOlK/XkBrdfsh9J/jPPXbX0tE9x9cl27Tmu5gg3QUbUrQYa/y+KOHPQ==",
      "license": "ISC"
    },
    "node_modules/are-we-there-yet": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/are-we-there-yet/-/are-we-there-yet-2.0.0.tgz",
      "integrity": "sha512-Ci/qENmwHnsYo9xKIcUJN5LeDKdJ6R1Z1j9V/J5wyq8nh/mYPEpIKJbBZXtZjG04HiK7zV/p6Vs9952MrMeUIw==",
      "deprecated": "This package is no longer supported.",
      "license": "ISC",
      "dependencies": {
        "delegates": "^1.0.0",
        "readable-stream": "^3.6.0"
      },
      "engines": {
        "node": ">=10"
      }
    },
    "node_modules/asynckit": {
      "version": "0.4.0",
      "resolved": "https://registry.npmjs.org/asynckit/-/asynckit-0.4.0.tgz",
      "integrity": "sha512-Oei9OH4tRh0YqU3GxhX79dM/mwVgvbZJaSNaRk+bshkj0S5cfHcgYakreBjrHwatXKbz+IoIdYLxrKim2MjW0Q==",
      "license": "MIT"
    },
    "node_modules/axios": {
      "version": "1.8.4",
      "resolved": "https://registry.npmjs.org/axios/-/axios-1.8.4.tgz",
      "integrity": "sha512-eBSYY4Y68NNlHbHBMdeDmKNtDgXWhQsJcGqzO3iLUM0GraQFSS9cVgPX5I9b3lbdFKyYoAEGAZF1DwhTaljNAw==",
      "license": "MIT",
      "dependencies": {
        "follow-redirects": "^1.15.6",
        "form-data": "^4.0.0",
        "proxy-from-env": "^1.1.0"
      }
    },
    "node_modules/balanced-match": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/balanced-match/-/balanced-match-1.0.2.tgz",
      "integrity": "sha512-3oSeUO0TMV67hN1AmbXsK4yaqU7tjiHlbxRDZOpH0KW9+CeX4bRAaX0Anxt0tx2MrpRpWwQaPwIlISEJhYU5Pw==",
      "license": "MIT"
    },
    "node_modules/basic-auth": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/basic-auth/-/basic-auth-2.0.1.tgz",
      "integrity": "sha512-NF+epuEdnUYVlGuhaxbbq+dvJttwLnGY+YixlXlME5KpQ5W3CnXA5cVTneY3SPbPDRkcjMbifrwmFYcClgOZeg==",
      "license": "MIT",
      "dependencies": {
        "safe-buffer": "5.1.2"
      },
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/basic-auth/node_modules/safe-buffer": {
      "version": "5.1.2",
      "resolved": "https://registry.npmjs.org/safe-buffer/-/safe-buffer-5.1.2.tgz",
      "integrity": "sha512-Gd2UZBJDkXlY7GbJxfsE8/nvKkUEU1G38c1siN6QP6a9PT9MmHB8GnpscSmMJSoF8LOIrt8ud/wPtojys4G6+g==",
      "license": "MIT"
    },
    "node_modules/bcrypt": {
      "version": "5.1.1",
      "resolved": "https://registry.npmjs.org/bcrypt/-/bcrypt-5.1.1.tgz",
      "integrity": "sha512-AGBHOG5hPYZ5Xl9KXzU5iKq9516yEmvCKDg3ecP5kX2aB6UqTeXZxk2ELnDgDm6BQSMlLt9rDB4LoSMx0rYwww==",
      "hasInstallScript": true,
      "license": "MIT",
      "dependencies": {
        "@mapbox/node-pre-gyp": "^1.0.11",
        "node-addon-api": "^5.0.0"
      },
      "engines": {
        "node": ">= 10.0.0"
      }
    },
    "node_modules/body-parser": {
      "version": "2.2.0",
      "resolved": "https://registry.npmjs.org/body-parser/-/body-parser-2.2.0.tgz",
      "integrity": "sha512-02qvAaxv8tp7fBa/mw1ga98OGm+eCbqzJOKoRt70sLmfEEi+jyBYVTDGfCL/k06/4EMk/z01gCe7HoCH/f2LTg==",
      "license": "MIT",
      "dependencies": {
        "bytes": "^3.1.2",
        "content-type": "^1.0.5",
        "debug": "^4.4.0",
        "http-errors": "^2.0.0",
        "iconv-lite": "^0.6.3",
        "on-finished": "^2.4.1",
        "qs": "^6.14.0",
        "raw-body": "^3.0.0",
        "type-is": "^2.0.0"
      },
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/brace-expansion": {
      "version": "1.1.11",
      "resolved": "https://registry.npmjs.org/brace-expansion/-/brace-expansion-1.1.11.tgz",
      "integrity": "sha512-iCuPHDFgrHX7H2vEI/5xpz07zSHB00TpugqhmYtVmMO6518mCuRMoOYFldEBl0g187ufozdaHgWKcYFb61qGiA==",
      "license": "MIT",
      "dependencies": {
        "balanced-match": "^1.0.0",
        "concat-map": "0.0.1"
      }
    },
    "node_modules/bson": {
      "version": "6.10.3",
      "resolved": "https://registry.npmjs.org/bson/-/bson-6.10.3.tgz",
      "integrity": "sha512-MTxGsqgYTwfshYWTRdmZRC+M7FnG1b4y7RO7p2k3X24Wq0yv1m77Wsj0BzlPzd/IowgESfsruQCUToa7vbOpPQ==",
      "license": "Apache-2.0",
      "engines": {
        "node": ">=16.20.1"
      }
    },
    "node_modules/buffer-equal-constant-time": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/buffer-equal-constant-time/-/buffer-equal-constant-time-1.0.1.tgz",
      "integrity": "sha512-zRpUiDwd/xk6ADqPMATG8vc9VPrkck7T07OIx0gnjmJAnHnTVXNQG3vfvWNuiZIkwu9KrKdA1iJKfsfTVxE6NA==",
      "license": "BSD-3-Clause"
    },
    "node_modules/buffer-from": {
      "version": "1.1.2",
      "resolved": "https://registry.npmjs.org/buffer-from/-/buffer-from-1.1.2.tgz",
      "integrity": "sha512-E+XQCRwSbaaiChtv6k6Dwgc+bx+Bs6vuKJHHl5kox/BaKbhiXzqQOwK4cO22yElGp2OCmjwVhT3HmxgyPGnJfQ==",
      "license": "MIT"
    },
    "node_modules/busboy": {
      "version": "1.6.0",
      "resolved": "https://registry.npmjs.org/busboy/-/busboy-1.6.0.tgz",
      "integrity": "sha512-8SFQbg/0hQ9xy3UNTB0YEnsNBbWfhf7RtnzpL7TkBiTBRfrQ9Fxcnz7VJsleJpyp6rVLvXiuORqjlHi5q+PYuA==",
      "dependencies": {
        "streamsearch": "^1.1.0"
      },
      "engines": {
        "node": ">=10.16.0"
      }
    },
    "node_modules/bytes": {
      "version": "3.1.2",
      "resolved": "https://registry.npmjs.org/bytes/-/bytes-3.1.2.tgz",
      "integrity": "sha512-/Nf7TyzTx6S3yRJObOAV7956r8cr2+Oj8AC5dt8wSP3BQAoeX58NoHyCU8P8zGkNXStjTSi6fzO6F0pBdcYbEg==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/call-bind-apply-helpers": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/call-bind-apply-helpers/-/call-bind-apply-helpers-1.0.2.tgz",
      "integrity": "sha512-Sp1ablJ0ivDkSzjcaJdxEunN5/XvksFJ2sMBFfq6x0ryhQV/2b/KwFe21cMpmHtPOSij8K99/wSfoEuTObmuMQ==",
      "license": "MIT",
      "dependencies": {
        "es-errors": "^1.3.0",
        "function-bind": "^1.1.2"
      },
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/call-bound": {
      "version": "1.0.4",
      "resolved": "https://registry.npmjs.org/call-bound/-/call-bound-1.0.4.tgz",
      "integrity": "sha512-+ys997U96po4Kx/ABpBCqhA9EuxJaQWDQg7295H4hBphv3IZg0boBKuwYpt4YXp6MZ5AmZQnU/tyMTlRpaSejg==",
      "license": "MIT",
      "dependencies": {
        "call-bind-apply-helpers": "^1.0.2",
        "get-intrinsic": "^1.3.0"
      },
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/chownr": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/chownr/-/chownr-2.0.0.tgz",
      "integrity": "sha512-bIomtDF5KGpdogkLd9VspvFzk9KfpyyGlS8YFVZl7TGPBHL5snIOnxeshwVgPteQ9b4Eydl+pVbIyE1DcvCWgQ==",
      "license": "ISC",
      "engines": {
        "node": ">=10"
      }
    },
    "node_modules/color-support": {
      "version": "1.1.3",
      "resolved": "https://registry.npmjs.org/color-support/-/color-support-1.1.3.tgz",
      "integrity": "sha512-qiBjkpbMLO/HL68y+lh4q0/O1MZFj2RX6X/KmMa3+gJD3z+WwI1ZzDHysvqHGS3mP6mznPckpXmw1nI9cJjyRg==",
      "license": "ISC",
      "bin": {
        "color-support": "bin.js"
      }
    },
    "node_modules/combined-stream": {
      "version": "1.0.8",
      "resolved": "https://registry.npmjs.org/combined-stream/-/combined-stream-1.0.8.tgz",
      "integrity": "sha512-FQN4MRfuJeHf7cBbBMJFXhKSDq+2kAArBlmRBvcvFE5BB1HZKXtSFASDhdlz9zOYwxh8lDdnvmMOe/+5cdoEdg==",
      "license": "MIT",
      "dependencies": {
        "delayed-stream": "~1.0.0"
      },
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/concat-map": {
      "version": "0.0.1",
      "resolved": "https://registry.npmjs.org/concat-map/-/concat-map-0.0.1.tgz",
      "integrity": "sha512-/Srv4dswyQNBfohGpz9o6Yb3Gz3SrUDqBH5rTuhGR7ahtlbYKnVxw2bCFMRljaA7EXHaXZ8wsHdodFvbkhKmqg==",
      "license": "MIT"
    },
    "node_modules/concat-stream": {
      "version": "1.6.2",
      "resolved": "https://registry.npmjs.org/concat-stream/-/concat-stream-1.6.2.tgz",
      "integrity": "sha512-27HBghJxjiZtIk3Ycvn/4kbJk/1uZuJFfuPEns6LaEvpvG1f0hTea8lilrouyo9mVc2GWdcEZ8OLoGmSADlrCw==",
      "engines": [
        "node >= 0.8"
      ],
      "license": "MIT",
      "dependencies": {
        "buffer-from": "^1.0.0",
        "inherits": "^2.0.3",
        "readable-stream": "^2.2.2",
        "typedarray": "^0.0.6"
      }
    },
    "node_modules/concat-stream/node_modules/readable-stream": {
      "version": "2.3.8",
      "resolved": "https://registry.npmjs.org/readable-stream/-/readable-stream-2.3.8.tgz",
      "integrity": "sha512-8p0AUk4XODgIewSi0l8Epjs+EVnWiK7NoDIEGU0HhE7+ZyY8D1IMY7odu5lRrFXGg71L15KG8QrPmum45RTtdA==",
      "license": "MIT",
      "dependencies": {
        "core-util-is": "~1.0.0",
        "inherits": "~2.0.3",
        "isarray": "~1.0.0",
        "process-nextick-args": "~2.0.0",
        "safe-buffer": "~5.1.1",
        "string_decoder": "~1.1.1",
        "util-deprecate": "~1.0.1"
      }
    },
    "node_modules/concat-stream/node_modules/safe-buffer": {
      "version": "5.1.2",
      "resolved": "https://registry.npmjs.org/safe-buffer/-/safe-buffer-5.1.2.tgz",
      "integrity": "sha512-Gd2UZBJDkXlY7GbJxfsE8/nvKkUEU1G38c1siN6QP6a9PT9MmHB8GnpscSmMJSoF8LOIrt8ud/wPtojys4G6+g==",
      "license": "MIT"
    },
    "node_modules/concat-stream/node_modules/string_decoder": {
      "version": "1.1.1",
      "resolved": "https://registry.npmjs.org/string_decoder/-/string_decoder-1.1.1.tgz",
      "integrity": "sha512-n/ShnvDi6FHbbVfviro+WojiFzv+s8MPMHBczVePfUpDJLwoLT0ht1l4YwBCbi8pJAveEEdnkHyPyTP/mzRfwg==",
      "license": "MIT",
      "dependencies": {
        "safe-buffer": "~5.1.0"
      }
    },
    "node_modules/console-control-strings": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/console-control-strings/-/console-control-strings-1.1.0.tgz",
      "integrity": "sha512-ty/fTekppD2fIwRvnZAVdeOiGd1c7YXEixbgJTNzqcxJWKQnjJ/V1bNEEE6hygpM3WjwHFUVK6HTjWSzV4a8sQ==",
      "license": "ISC"
    },
    "node_modules/content-disposition": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/content-disposition/-/content-disposition-1.0.0.tgz",
      "integrity": "sha512-Au9nRL8VNUut/XSzbQA38+M78dzP4D+eqg3gfJHMIHHYa3bg067xj1KxMUWj+VULbiZMowKngFFbKczUrNJ1mg==",
      "license": "MIT",
      "dependencies": {
        "safe-buffer": "5.2.1"
      },
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/content-type": {
      "version": "1.0.5",
      "resolved": "https://registry.npmjs.org/content-type/-/content-type-1.0.5.tgz",
      "integrity": "sha512-nTjqfcBFEipKdXCv4YDQWCfmcLZKm81ldF0pAopTvyrFGVbcR6P/VAAd5G7N+0tTr8QqiU0tFadD6FK4NtJwOA==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/cookie": {
      "version": "0.7.2",
      "resolved": "https://registry.npmjs.org/cookie/-/cookie-0.7.2.tgz",
      "integrity": "sha512-yki5XnKuf750l50uGTllt6kKILY4nQ1eNIQatoXEByZ5dWgnKqbnqmTrBE5B4N7lrMJKQ2ytWMiTO2o0v6Ew/w==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/cookie-signature": {
      "version": "1.2.2",
      "resolved": "https://registry.npmjs.org/cookie-signature/-/cookie-signature-1.2.2.tgz",
      "integrity": "sha512-D76uU73ulSXrD1UXF4KE2TMxVVwhsnCgfAyTg9k8P6KGZjlXKrOLe4dJQKI3Bxi5wjesZoFXJWElNWBjPZMbhg==",
      "license": "MIT",
      "engines": {
        "node": ">=6.6.0"
      }
    },
    "node_modules/core-util-is": {
      "version": "1.0.3",
      "resolved": "https://registry.npmjs.org/core-util-is/-/core-util-is-1.0.3.tgz",
      "integrity": "sha512-ZQBvi1DcpJ4GDqanjucZ2Hj3wEO5pZDS89BWbkcrvdxksJorwUDDZamX9ldFkp9aw2lmBDLgkObEA4DWNJ9FYQ==",
      "license": "MIT"
    },
    "node_modules/cors": {
      "version": "2.8.5",
      "resolved": "https://registry.npmjs.org/cors/-/cors-2.8.5.tgz",
      "integrity": "sha512-KIHbLJqu73RGr/hnbrO9uBeixNGuvSQjul/jdFvS/KFSIH1hWVd1ng7zOHx+YrEfInLG7q4n6GHQ9cDtxv/P6g==",
      "license": "MIT",
      "dependencies": {
        "object-assign": "^4",
        "vary": "^1"
      },
      "engines": {
        "node": ">= 0.10"
      }
    },
    "node_modules/debug": {
      "version": "4.4.0",
      "resolved": "https://registry.npmjs.org/debug/-/debug-4.4.0.tgz",
      "integrity": "sha512-6WTZ/IxCY/T6BALoZHaE4ctp9xm+Z5kY/pzYaCHRFeyVhojxlrm+46y68HA6hr0TcwEssoxNiDEUJQjfPZ/RYA==",
      "license": "MIT",
      "dependencies": {
        "ms": "^2.1.3"
      },
      "engines": {
        "node": ">=6.0"
      },
      "peerDependenciesMeta": {
        "supports-color": {
          "optional": true
        }
      }
    },
    "node_modules/delayed-stream": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/delayed-stream/-/delayed-stream-1.0.0.tgz",
      "integrity": "sha512-ZySD7Nf91aLB0RxL4KGrKHBXl7Eds1DAmEdcoVawXnLD7SDhpNgtuII2aAkg7a7QS41jxPSZ17p4VdGnMHk3MQ==",
      "license": "MIT",
      "engines": {
        "node": ">=0.4.0"
      }
    },
    "node_modules/delegates": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/delegates/-/delegates-1.0.0.tgz",
      "integrity": "sha512-bd2L678uiWATM6m5Z1VzNCErI3jiGzt6HGY8OVICs40JQq/HALfbyNJmp0UDakEY4pMMaN0Ly5om/B1VI/+xfQ==",
      "license": "MIT"
    },
    "node_modules/depd": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/depd/-/depd-2.0.0.tgz",
      "integrity": "sha512-g7nH6P6dyDioJogAAGprGpCtVImJhpPk/roCzdb3fIh61/s/nPsfR6onyMwkCAR/OlC3yBC0lESvUoQEAssIrw==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/detect-libc": {
      "version": "2.0.3",
      "resolved": "https://registry.npmjs.org/detect-libc/-/detect-libc-2.0.3.tgz",
      "integrity": "sha512-bwy0MGW55bG41VqxxypOsdSdGqLwXPI/focwgTYCFMbdUiBAxLg9CFzG08sz2aqzknwiX7Hkl0bQENjg8iLByw==",
      "license": "Apache-2.0",
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/dotenv": {
      "version": "16.4.7",
      "resolved": "https://registry.npmjs.org/dotenv/-/dotenv-16.4.7.tgz",
      "integrity": "sha512-47qPchRCykZC03FhkYAhrvwU4xDBFIj1QPqaarj6mdM/hgUzfPHcpkHJOn3mJAufFeeAxAzeGsr5X0M4k6fLZQ==",
      "license": "BSD-2-Clause",
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://dotenvx.com"
      }
    },
    "node_modules/dunder-proto": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/dunder-proto/-/dunder-proto-1.0.1.tgz",
      "integrity": "sha512-KIN/nDJBQRcXw0MLVhZE9iQHmG68qAVIBg9CqmUYjmQIhgij9U5MFvrqkUL5FbtyyzZuOeOt0zdeRe4UY7ct+A==",
      "license": "MIT",
      "dependencies": {
        "call-bind-apply-helpers": "^1.0.1",
        "es-errors": "^1.3.0",
        "gopd": "^1.2.0"
      },
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/ecdsa-sig-formatter": {
      "version": "1.0.11",
      "resolved": "https://registry.npmjs.org/ecdsa-sig-formatter/-/ecdsa-sig-formatter-1.0.11.tgz",
      "integrity": "sha512-nagl3RYrbNv6kQkeJIpt6NJZy8twLB/2vtz6yN9Z4vRKHN4/QZJIEbqohALSgwKdnksuY3k5Addp5lg8sVoVcQ==",
      "license": "Apache-2.0",
      "dependencies": {
        "safe-buffer": "^5.0.1"
      }
    },
    "node_modules/ee-first": {
      "version": "1.1.1",
      "resolved": "https://registry.npmjs.org/ee-first/-/ee-first-1.1.1.tgz",
      "integrity": "sha512-WMwm9LhRUo+WUaRN+vRuETqG89IgZphVSNkdFgeb6sS/E4OrDIN7t48CAewSHXc6C8lefD8KKfr5vY61brQlow==",
      "license": "MIT"
    },
    "node_modules/emoji-regex": {
      "version": "8.0.0",
      "resolved": "https://registry.npmjs.org/emoji-regex/-/emoji-regex-8.0.0.tgz",
      "integrity": "sha512-MSjYzcWNOA0ewAHpz0MxpYFvwg6yjy1NG3xteoqz644VCo/RPgnr1/GGt+ic3iJTzQ8Eu3TdM14SawnVUmGE6A==",
      "license": "MIT"
    },
    "node_modules/encodeurl": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/encodeurl/-/encodeurl-2.0.0.tgz",
      "integrity": "sha512-Q0n9HRi4m6JuGIV1eFlmvJB7ZEVxu93IrMyiMsGC0lrMJMWzRgx6WGquyfQgZVb31vhGgXnfmPNNXmxnOkRBrg==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/es-define-property": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/es-define-property/-/es-define-property-1.0.1.tgz",
      "integrity": "sha512-e3nRfgfUZ4rNGL232gUgX06QNyyez04KdjFrF+LTRoOXmrOgFKDg4BCdsjW8EnT69eqdYGmRpJwiPVYNrCaW3g==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/es-errors": {
      "version": "1.3.0",
      "resolved": "https://registry.npmjs.org/es-errors/-/es-errors-1.3.0.tgz",
      "integrity": "sha512-Zf5H2Kxt2xjTvbJvP2ZWLEICxA6j+hAmMzIlypy4xcBg1vKVnx89Wy0GbS+kf5cwCVFFzdCFh2XSCFNULS6csw==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/es-object-atoms": {
      "version": "1.1.1",
      "resolved": "https://registry.npmjs.org/es-object-atoms/-/es-object-atoms-1.1.1.tgz",
      "integrity": "sha512-FGgH2h8zKNim9ljj7dankFPcICIK9Cp5bm+c2gQSYePhpaG5+esrLODihIorn+Pe6FGJzWhXQotPv73jTaldXA==",
      "license": "MIT",
      "dependencies": {
        "es-errors": "^1.3.0"
      },
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/es-set-tostringtag": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/es-set-tostringtag/-/es-set-tostringtag-2.1.0.tgz",
      "integrity": "sha512-j6vWzfrGVfyXxge+O0x5sh6cvxAog0a/4Rdd2K36zCMV5eJ+/+tOAngRO8cODMNWbVRdVlmGZQL2YS3yR8bIUA==",
      "license": "MIT",
      "dependencies": {
        "es-errors": "^1.3.0",
        "get-intrinsic": "^1.2.6",
        "has-tostringtag": "^1.0.2",
        "hasown": "^2.0.2"
      },
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/escape-html": {
      "version": "1.0.3",
      "resolved": "https://registry.npmjs.org/escape-html/-/escape-html-1.0.3.tgz",
      "integrity": "sha512-NiSupZ4OeuGwr68lGIeym/ksIZMJodUGOSCZ/FSnTxcrekbvqrgdUxlJOMpijaKZVjAJrWrGs/6Jy8OMuyj9ow==",
      "license": "MIT"
    },
    "node_modules/etag": {
      "version": "1.8.1",
      "resolved": "https://registry.npmjs.org/etag/-/etag-1.8.1.tgz",
      "integrity": "sha512-aIL5Fx7mawVa300al2BnEE4iNvo1qETxLrPI/o05L7z6go7fCw1J6EQmbK4FmJ2AS7kgVF/KEZWufBfdClMcPg==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/express": {
      "version": "5.1.0",
      "resolved": "https://registry.npmjs.org/express/-/express-5.1.0.tgz",
      "integrity": "sha512-DT9ck5YIRU+8GYzzU5kT3eHGA5iL+1Zd0EutOmTE9Dtk+Tvuzd23VBU+ec7HPNSTxXYO55gPV/hq4pSBJDjFpA==",
      "license": "MIT",
      "dependencies": {
        "accepts": "^2.0.0",
        "body-parser": "^2.2.0",
        "content-disposition": "^1.0.0",
        "content-type": "^1.0.5",
        "cookie": "^0.7.1",
        "cookie-signature": "^1.2.1",
        "debug": "^4.4.0",
        "encodeurl": "^2.0.0",
        "escape-html": "^1.0.3",
        "etag": "^1.8.1",
        "finalhandler": "^2.1.0",
        "fresh": "^2.0.0",
        "http-errors": "^2.0.0",
        "merge-descriptors": "^2.0.0",
        "mime-types": "^3.0.0",
        "on-finished": "^2.4.1",
        "once": "^1.4.0",
        "parseurl": "^1.3.3",
        "proxy-addr": "^2.0.7",
        "qs": "^6.14.0",
        "range-parser": "^1.2.1",
        "router": "^2.2.0",
        "send": "^1.1.0",
        "serve-static": "^2.2.0",
        "statuses": "^2.0.1",
        "type-is": "^2.0.1",
        "vary": "^1.1.2"
      },
      "engines": {
        "node": ">= 18"
      },
      "funding": {
        "type": "opencollective",
        "url": "https://opencollective.com/express"
      }
    },
    "node_modules/finalhandler": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/finalhandler/-/finalhandler-2.1.0.tgz",
      "integrity": "sha512-/t88Ty3d5JWQbWYgaOGCCYfXRwV1+be02WqYYlL6h0lEiUAMPM8o8qKGO01YIkOHzka2up08wvgYD0mDiI+q3Q==",
      "license": "MIT",
      "dependencies": {
        "debug": "^4.4.0",
        "encodeurl": "^2.0.0",
        "escape-html": "^1.0.3",
        "on-finished": "^2.4.1",
        "parseurl": "^1.3.3",
        "statuses": "^2.0.1"
      },
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/follow-redirects": {
      "version": "1.15.9",
      "resolved": "https://registry.npmjs.org/follow-redirects/-/follow-redirects-1.15.9.tgz",
      "integrity": "sha512-gew4GsXizNgdoRyqmyfMHyAmXsZDk6mHkSxZFCzW9gwlbtOW44CDtYavM+y+72qD/Vq2l550kMF52DT8fOLJqQ==",
      "funding": [
        {
          "type": "individual",
          "url": "https://github.com/sponsors/RubenVerborgh"
        }
      ],
      "license": "MIT",
      "engines": {
        "node": ">=4.0"
      },
      "peerDependenciesMeta": {
        "debug": {
          "optional": true
        }
      }
    },
    "node_modules/form-data": {
      "version": "4.0.2",
      "resolved": "https://registry.npmjs.org/form-data/-/form-data-4.0.2.tgz",
      "integrity": "sha512-hGfm/slu0ZabnNt4oaRZ6uREyfCj6P4fT/n6A1rGV+Z0VdGXjfOhVUpkn6qVQONHGIFwmveGXyDs75+nr6FM8w==",
      "license": "MIT",
      "dependencies": {
        "asynckit": "^0.4.0",
        "combined-stream": "^1.0.8",
        "es-set-tostringtag": "^2.1.0",
        "mime-types": "^2.1.12"
      },
      "engines": {
        "node": ">= 6"
      }
    },
    "node_modules/form-data/node_modules/mime-db": {
      "version": "1.52.0",
      "resolved": "https://registry.npmjs.org/mime-db/-/mime-db-1.52.0.tgz",
      "integrity": "sha512-sPU4uV7dYlvtWJxwwxHD0PuihVNiE7TyAbQ5SWxDCB9mUYvOgroQOwYQQOKPJ8CIbE+1ETVlOoK1UC2nU3gYvg==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/form-data/node_modules/mime-types": {
      "version": "2.1.35",
      "resolved": "https://registry.npmjs.org/mime-types/-/mime-types-2.1.35.tgz",
      "integrity": "sha512-ZDY+bPm5zTTF+YpCrAU9nK0UgICYPT0QtT1NZWFv4s++TNkcgVaT0g6+4R2uI4MjQjzysHB1zxuWL50hzaeXiw==",
      "license": "MIT",
      "dependencies": {
        "mime-db": "1.52.0"
      },
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/forwarded": {
      "version": "0.2.0",
      "resolved": "https://registry.npmjs.org/forwarded/-/forwarded-0.2.0.tgz",
      "integrity": "sha512-buRG0fpBtRHSTCOASe6hD258tEubFoRLb4ZNA6NxMVHNw2gOcwHo9wyablzMzOA5z9xA9L1KNjk/Nt6MT9aYow==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/fresh": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/fresh/-/fresh-2.0.0.tgz",
      "integrity": "sha512-Rx/WycZ60HOaqLKAi6cHRKKI7zxWbJ31MhntmtwMoaTeF7XFH9hhBp8vITaMidfljRQ6eYWCKkaTK+ykVJHP2A==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/fs-minipass": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/fs-minipass/-/fs-minipass-2.1.0.tgz",
      "integrity": "sha512-V/JgOLFCS+R6Vcq0slCuaeWEdNC3ouDlJMNIsacH2VtALiu9mV4LPrHc5cDl8k5aw6J8jwgWWpiTo5RYhmIzvg==",
      "license": "ISC",
      "dependencies": {
        "minipass": "^3.0.0"
      },
      "engines": {
        "node": ">= 8"
      }
    },
    "node_modules/fs-minipass/node_modules/minipass": {
      "version": "3.3.6",
      "resolved": "https://registry.npmjs.org/minipass/-/minipass-3.3.6.tgz",
      "integrity": "sha512-DxiNidxSEK+tHG6zOIklvNOwm3hvCrbUrdtzY74U6HKTJxvIDfOUL5W5P2Ghd3DTkhhKPYGqeNUIh5qcM4YBfw==",
      "license": "ISC",
      "dependencies": {
        "yallist": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/fs.realpath": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/fs.realpath/-/fs.realpath-1.0.0.tgz",
      "integrity": "sha512-OO0pH2lK6a0hZnAdau5ItzHPI6pUlvI7jMVnxUQRtw4owF2wk8lOSabtGDCTP4Ggrg2MbGnWO9X8K1t4+fGMDw==",
      "license": "ISC"
    },
    "node_modules/function-bind": {
      "version": "1.1.2",
      "resolved": "https://registry.npmjs.org/function-bind/-/function-bind-1.1.2.tgz",
      "integrity": "sha512-7XHNxH7qX9xG5mIwxkhumTox/MIRNcOgDrxWsMt2pAr23WHp6MrRlN7FBSFpCpr+oVO0F744iUgR82nJMfG2SA==",
      "license": "MIT",
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/gauge": {
      "version": "3.0.2",
      "resolved": "https://registry.npmjs.org/gauge/-/gauge-3.0.2.tgz",
      "integrity": "sha512-+5J6MS/5XksCuXq++uFRsnUd7Ovu1XenbeuIuNRJxYWjgQbPuFhT14lAvsWfqfAmnwluf1OwMjz39HjfLPci0Q==",
      "deprecated": "This package is no longer supported.",
      "license": "ISC",
      "dependencies": {
        "aproba": "^1.0.3 || ^2.0.0",
        "color-support": "^1.1.2",
        "console-control-strings": "^1.0.0",
        "has-unicode": "^2.0.1",
        "object-assign": "^4.1.1",
        "signal-exit": "^3.0.0",
        "string-width": "^4.2.3",
        "strip-ansi": "^6.0.1",
        "wide-align": "^1.1.2"
      },
      "engines": {
        "node": ">=10"
      }
    },
    "node_modules/get-intrinsic": {
      "version": "1.3.0",
      "resolved": "https://registry.npmjs.org/get-intrinsic/-/get-intrinsic-1.3.0.tgz",
      "integrity": "sha512-9fSjSaos/fRIVIp+xSJlE6lfwhES7LNtKaCBIamHsjr2na1BiABJPo0mOjjz8GJDURarmCPGqaiVg5mfjb98CQ==",
      "license": "MIT",
      "dependencies": {
        "call-bind-apply-helpers": "^1.0.2",
        "es-define-property": "^1.0.1",
        "es-errors": "^1.3.0",
        "es-object-atoms": "^1.1.1",
        "function-bind": "^1.1.2",
        "get-proto": "^1.0.1",
        "gopd": "^1.2.0",
        "has-symbols": "^1.1.0",
        "hasown": "^2.0.2",
        "math-intrinsics": "^1.1.0"
      },
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/get-proto": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/get-proto/-/get-proto-1.0.1.tgz",
      "integrity": "sha512-sTSfBjoXBp89JvIKIefqw7U2CCebsc74kiY6awiGogKtoSGbgjYE/G/+l9sF3MWFPNc9IcoOC4ODfKHfxFmp0g==",
      "license": "MIT",
      "dependencies": {
        "dunder-proto": "^1.0.1",
        "es-object-atoms": "^1.0.0"
      },
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/glob": {
      "version": "7.2.3",
      "resolved": "https://registry.npmjs.org/glob/-/glob-7.2.3.tgz",
      "integrity": "sha512-nFR0zLpU2YCaRxwoCJvL6UvCH2JFyFVIvwTLsIf21AuHlMskA1hhTdk+LlYJtOlYt9v6dvszD2BGRqBL+iQK9Q==",
      "deprecated": "Glob versions prior to v9 are no longer supported",
      "license": "ISC",
      "dependencies": {
        "fs.realpath": "^1.0.0",
        "inflight": "^1.0.4",
        "inherits": "2",
        "minimatch": "^3.1.1",
        "once": "^1.3.0",
        "path-is-absolute": "^1.0.0"
      },
      "engines": {
        "node": "*"
      },
      "funding": {
        "url": "https://github.com/sponsors/isaacs"
      }
    },
    "node_modules/gopd": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/gopd/-/gopd-1.2.0.tgz",
      "integrity": "sha512-ZUKRh6/kUFoAiTAtTYPZJ3hw9wNxx+BIBOijnlG9PnrJsCcSjs1wyyD6vJpaYtgnzDrKYRSqf3OO6Rfa93xsRg==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/hamming-distance": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/hamming-distance/-/hamming-distance-1.0.0.tgz",
      "integrity": "sha512-hYz2IIKtyuZGfOqCs7skNiFEATf+v9IUNSOaQSr6Ll4JOxxWhOvXvc3mIdCW82Z3xW+zUoto7N/ssD4bDxAWoA==",
      "license": "MIT"
    },
    "node_modules/has-symbols": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/has-symbols/-/has-symbols-1.1.0.tgz",
      "integrity": "sha512-1cDNdwJ2Jaohmb3sg4OmKaMBwuC48sYni5HUw2DvsC8LjGTLK9h+eb1X6RyuOHe4hT0ULCW68iomhjUoKUqlPQ==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/has-tostringtag": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/has-tostringtag/-/has-tostringtag-1.0.2.tgz",
      "integrity": "sha512-NqADB8VjPFLM2V0VvHUewwwsw0ZWBaIdgo+ieHtK3hasLz4qeCRjYcqfB6AQrBggRKppKF8L52/VqdVsO47Dlw==",
      "license": "MIT",
      "dependencies": {
        "has-symbols": "^1.0.3"
      },
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/has-unicode": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/has-unicode/-/has-unicode-2.0.1.tgz",
      "integrity": "sha512-8Rf9Y83NBReMnx0gFzA8JImQACstCYWUplepDa9xprwwtmgEZUF0h/i5xSA625zB/I37EtrswSST6OXxwaaIJQ==",
      "license": "ISC"
    },
    "node_modules/hasown": {
      "version": "2.0.2",
      "resolved": "https://registry.npmjs.org/hasown/-/hasown-2.0.2.tgz",
      "integrity": "sha512-0hJU9SCPvmMzIBdZFqNPXWa6dqh7WdH0cII9y+CyS8rG3nL48Bclra9HmKhVVUHyPWNH5Y7xDwAB7bfgSjkUMQ==",
      "license": "MIT",
      "dependencies": {
        "function-bind": "^1.1.2"
      },
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/http-errors": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/http-errors/-/http-errors-2.0.0.tgz",
      "integrity": "sha512-FtwrG/euBzaEjYeRqOgly7G0qviiXoJWnvEH2Z1plBdXgbyjv34pHTSb9zoeHMyDy33+DWy5Wt9Wo+TURtOYSQ==",
      "license": "MIT",
      "dependencies": {
        "depd": "2.0.0",
        "inherits": "2.0.4",
        "setprototypeof": "1.2.0",
        "statuses": "2.0.1",
        "toidentifier": "1.0.1"
      },
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/https-proxy-agent": {
      "version": "5.0.1",
      "resolved": "https://registry.npmjs.org/https-proxy-agent/-/https-proxy-agent-5.0.1.tgz",
      "integrity": "sha512-dFcAjpTQFgoLMzC2VwU+C/CbS7uRL0lWmxDITmqm7C+7F0Odmj6s9l6alZc6AELXhrnggM2CeWSXHGOdX2YtwA==",
      "license": "MIT",
      "dependencies": {
        "agent-base": "6",
        "debug": "4"
      },
      "engines": {
        "node": ">= 6"
      }
    },
    "node_modules/iconv-lite": {
      "version": "0.6.3",
      "resolved": "https://registry.npmjs.org/iconv-lite/-/iconv-lite-0.6.3.tgz",
      "integrity": "sha512-4fCk79wshMdzMp2rH06qWrJE4iolqLhCUH+OiuIgU++RB0+94NlDL81atO7GX55uUKueo0txHNtvEyI6D7WdMw==",
      "license": "MIT",
      "dependencies": {
        "safer-buffer": ">= 2.1.2 < 3.0.0"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/imagekit": {
      "version": "6.0.0",
      "resolved": "https://registry.npmjs.org/imagekit/-/imagekit-6.0.0.tgz",
      "integrity": "sha512-0MsxThZM2PYH6ngwN3zi9PDa8pCB5mEZG2FSySYiZk3Hfri8IMwUqVNzRlLQewBHQ3YtTN9M59O0Xe9HRewtOA==",
      "license": "MIT",
      "dependencies": {
        "axios": "^1.6.5",
        "form-data": "^4.0.0",
        "hamming-distance": "^1.0.0",
        "lodash": "^4.17.15",
        "tslib": "^2.4.0",
        "uuid": "^8.3.2"
      },
      "engines": {
        "node": ">=12.0.0"
      }
    },
    "node_modules/inflight": {
      "version": "1.0.6",
      "resolved": "https://registry.npmjs.org/inflight/-/inflight-1.0.6.tgz",
      "integrity": "sha512-k92I/b08q4wvFscXCLvqfsHCrjrF7yiXsQuIVvVE7N82W3+aqpzuUdBbfhWcy/FZR3/4IgflMgKLOsvPDrGCJA==",
      "deprecated": "This module is not supported, and leaks memory. Do not use it. Check out lru-cache if you want a good and tested way to coalesce async requests by a key value, which is much more comprehensive and powerful.",
      "license": "ISC",
      "dependencies": {
        "once": "^1.3.0",
        "wrappy": "1"
      }
    },
    "node_modules/inherits": {
      "version": "2.0.4",
      "resolved": "https://registry.npmjs.org/inherits/-/inherits-2.0.4.tgz",
      "integrity": "sha512-k/vGaX4/Yla3WzyMCvTQOXYeIHvqOKtnqBduzTHpzpQZzAskKMhZ2K+EnBiSM9zGSoIFeMpXKxa4dYeZIQqewQ==",
      "license": "ISC"
    },
    "node_modules/ipaddr.js": {
      "version": "1.9.1",
      "resolved": "https://registry.npmjs.org/ipaddr.js/-/ipaddr.js-1.9.1.tgz",
      "integrity": "sha512-0KI/607xoxSToH7GjN1FfSbLoU0+btTicjsQSWQlh/hZykN8KpmMf7uYwPW3R+akZ6R/w18ZlXSHBYXiYUPO3g==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.10"
      }
    },
    "node_modules/is-fullwidth-code-point": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/is-fullwidth-code-point/-/is-fullwidth-code-point-3.0.0.tgz",
      "integrity": "sha512-zymm5+u+sCsSWyD9qNaejV3DFvhCKclKdizYaJUuHA83RLjb7nSuGnddCHGv0hk+KY7BMAlsWeK4Ueg6EV6XQg==",
      "license": "MIT",
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/is-promise": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/is-promise/-/is-promise-4.0.0.tgz",
      "integrity": "sha512-hvpoI6korhJMnej285dSg6nu1+e6uxs7zG3BYAm5byqDsgJNWwxzM6z6iZiAgQR4TJ30JmBTOwqZUw3WlyH3AQ==",
      "license": "MIT"
    },
    "node_modules/isarray": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/isarray/-/isarray-1.0.0.tgz",
      "integrity": "sha512-VLghIWNM6ELQzo7zwmcg0NmTVyWKYjvIeM83yjp0wRDTmUnrM678fQbcKBo6n2CJEF0szoG//ytg+TKla89ALQ==",
      "license": "MIT"
    },
    "node_modules/jsonwebtoken": {
      "version": "9.0.2",
      "resolved": "https://registry.npmjs.org/jsonwebtoken/-/jsonwebtoken-9.0.2.tgz",
      "integrity": "sha512-PRp66vJ865SSqOlgqS8hujT5U4AOgMfhrwYIuIhfKaoSCZcirrmASQr8CX7cUg+RMih+hgznrjp99o+W4pJLHQ==",
      "license": "MIT",
      "dependencies": {
        "jws": "^3.2.2",
        "lodash.includes": "^4.3.0",
        "lodash.isboolean": "^3.0.3",
        "lodash.isinteger": "^4.0.4",
        "lodash.isnumber": "^3.0.3",
        "lodash.isplainobject": "^4.0.6",
        "lodash.isstring": "^4.0.1",
        "lodash.once": "^4.0.0",
        "ms": "^2.1.1",
        "semver": "^7.5.4"
      },
      "engines": {
        "node": ">=12",
        "npm": ">=6"
      }
    },
    "node_modules/jwa": {
      "version": "1.4.1",
      "resolved": "https://registry.npmjs.org/jwa/-/jwa-1.4.1.tgz",
      "integrity": "sha512-qiLX/xhEEFKUAJ6FiBMbes3w9ATzyk5W7Hvzpa/SLYdxNtng+gcurvrI7TbACjIXlsJyr05/S1oUhZrc63evQA==",
      "license": "MIT",
      "dependencies": {
        "buffer-equal-constant-time": "1.0.1",
        "ecdsa-sig-formatter": "1.0.11",
        "safe-buffer": "^5.0.1"
      }
    },
    "node_modules/jws": {
      "version": "3.2.2",
      "resolved": "https://registry.npmjs.org/jws/-/jws-3.2.2.tgz",
      "integrity": "sha512-YHlZCB6lMTllWDtSPHz/ZXTsi8S00usEV6v1tjq8tOUZzw7DpSDWVXjXDre6ed1w/pd495ODpHZYSdkRTsa0HA==",
      "license": "MIT",
      "dependencies": {
        "jwa": "^1.4.1",
        "safe-buffer": "^5.0.1"
      }
    },
    "node_modules/kareem": {
      "version": "2.6.3",
      "resolved": "https://registry.npmjs.org/kareem/-/kareem-2.6.3.tgz",
      "integrity": "sha512-C3iHfuGUXK2u8/ipq9LfjFfXFxAZMQJJq7vLS45r3D9Y2xQ/m4S8zaR4zMLFWh9AsNPXmcFfUDhTEO8UIC/V6Q==",
      "license": "Apache-2.0",
      "engines": {
        "node": ">=12.0.0"
      }
    },
    "node_modules/lodash": {
      "version": "4.17.21",
      "resolved": "https://registry.npmjs.org/lodash/-/lodash-4.17.21.tgz",
      "integrity": "sha512-v2kDEe57lecTulaDIuNTPy3Ry4gLGJ6Z1O3vE1krgXZNrsQ+LFTGHVxVjcXPs17LhbZVGedAJv8XZ1tvj5FvSg==",
      "license": "MIT"
    },
    "node_modules/lodash.includes": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/lodash.includes/-/lodash.includes-4.3.0.tgz",
      "integrity": "sha512-W3Bx6mdkRTGtlJISOvVD/lbqjTlPPUDTMnlXZFnVwi9NKJ6tiAk6LVdlhZMm17VZisqhKcgzpO5Wz91PCt5b0w==",
      "license": "MIT"
    },
    "node_modules/lodash.isboolean": {
      "version": "3.0.3",
      "resolved": "https://registry.npmjs.org/lodash.isboolean/-/lodash.isboolean-3.0.3.tgz",
      "integrity": "sha512-Bz5mupy2SVbPHURB98VAcw+aHh4vRV5IPNhILUCsOzRmsTmSQ17jIuqopAentWoehktxGd9e/hbIXq980/1QJg==",
      "license": "MIT"
    },
    "node_modules/lodash.isinteger": {
      "version": "4.0.4",
      "resolved": "https://registry.npmjs.org/lodash.isinteger/-/lodash.isinteger-4.0.4.tgz",
      "integrity": "sha512-DBwtEWN2caHQ9/imiNeEA5ys1JoRtRfY3d7V9wkqtbycnAmTvRRmbHKDV4a0EYc678/dia0jrte4tjYwVBaZUA==",
      "license": "MIT"
    },
    "node_modules/lodash.isnumber": {
      "version": "3.0.3",
      "resolved": "https://registry.npmjs.org/lodash.isnumber/-/lodash.isnumber-3.0.3.tgz",
      "integrity": "sha512-QYqzpfwO3/CWf3XP+Z+tkQsfaLL/EnUlXWVkIk5FUPc4sBdTehEqZONuyRt2P67PXAk+NXmTBcc97zw9t1FQrw==",
      "license": "MIT"
    },
    "node_modules/lodash.isplainobject": {
      "version": "4.0.6",
      "resolved": "https://registry.npmjs.org/lodash.isplainobject/-/lodash.isplainobject-4.0.6.tgz",
      "integrity": "sha512-oSXzaWypCMHkPC3NvBEaPHf0KsA5mvPrOPgQWDsbg8n7orZ290M0BmC/jgRZ4vcJ6DTAhjrsSYgdsW/F+MFOBA==",
      "license": "MIT"
    },
    "node_modules/lodash.isstring": {
      "version": "4.0.1",
      "resolved": "https://registry.npmjs.org/lodash.isstring/-/lodash.isstring-4.0.1.tgz",
      "integrity": "sha512-0wJxfxH1wgO3GrbuP+dTTk7op+6L41QCXbGINEmD+ny/G/eCqGzxyCsh7159S+mgDDcoarnBw6PC1PS5+wUGgw==",
      "license": "MIT"
    },
    "node_modules/lodash.once": {
      "version": "4.1.1",
      "resolved": "https://registry.npmjs.org/lodash.once/-/lodash.once-4.1.1.tgz",
      "integrity": "sha512-Sb487aTOCr9drQVL8pIxOzVhafOjZN9UU54hiN8PU3uAiSV7lx1yYNpbNmex2PK6dSJoNTSJUUswT651yww3Mg==",
      "license": "MIT"
    },
    "node_modules/make-dir": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/make-dir/-/make-dir-3.1.0.tgz",
      "integrity": "sha512-g3FeP20LNwhALb/6Cz6Dd4F2ngze0jz7tbzrD2wAV+o9FeNHe4rL+yK2md0J/fiSf1sa1ADhXqi5+oVwOM/eGw==",
      "license": "MIT",
      "dependencies": {
        "semver": "^6.0.0"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/make-dir/node_modules/semver": {
      "version": "6.3.1",
      "resolved": "https://registry.npmjs.org/semver/-/semver-6.3.1.tgz",
      "integrity": "sha512-BR7VvDCVHO+q2xBEWskxS6DJE1qRnb7DxzUrogb71CWoSficBxYsiAGd+Kl0mmq/MprG9yArRkyrQxTO6XjMzA==",
      "license": "ISC",
      "bin": {
        "semver": "bin/semver.js"
      }
    },
    "node_modules/math-intrinsics": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/math-intrinsics/-/math-intrinsics-1.1.0.tgz",
      "integrity": "sha512-/IXtbwEk5HTPyEwyKX6hGkYXxM9nbj64B+ilVJnC/R6B0pH5G4V3b0pVbL7DBj4tkhBAppbQUlf6F6Xl9LHu1g==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/media-typer": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/media-typer/-/media-typer-1.1.0.tgz",
      "integrity": "sha512-aisnrDP4GNe06UcKFnV5bfMNPBUw4jsLGaWwWfnH3v02GnBuXX2MCVn5RbrWo0j3pczUilYblq7fQ7Nw2t5XKw==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/memory-pager": {
      "version": "1.5.0",
      "resolved": "https://registry.npmjs.org/memory-pager/-/memory-pager-1.5.0.tgz",
      "integrity": "sha512-ZS4Bp4r/Zoeq6+NLJpP+0Zzm0pR8whtGPf1XExKLJBAczGMnSi3It14OiNCStjQjM6NU1okjQGSxgEZN8eBYKg==",
      "license": "MIT"
    },
    "node_modules/merge-descriptors": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/merge-descriptors/-/merge-descriptors-2.0.0.tgz",
      "integrity": "sha512-Snk314V5ayFLhp3fkUREub6WtjBfPdCPY1Ln8/8munuLuiYhsABgBVWsozAG+MWMbVEvcdcpbi9R7ww22l9Q3g==",
      "license": "MIT",
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/mime-db": {
      "version": "1.54.0",
      "resolved": "https://registry.npmjs.org/mime-db/-/mime-db-1.54.0.tgz",
      "integrity": "sha512-aU5EJuIN2WDemCcAp2vFBfp/m4EAhWJnUNSSw0ixs7/kXbd6Pg64EmwJkNdFhB8aWt1sH2CTXrLxo/iAGV3oPQ==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/mime-types": {
      "version": "3.0.1",
      "resolved": "https://registry.npmjs.org/mime-types/-/mime-types-3.0.1.tgz",
      "integrity": "sha512-xRc4oEhT6eaBpU1XF7AjpOFD+xQmXNB5OVKwp4tqCuBpHLS/ZbBDrc07mYTDqVMg6PfxUjjNp85O6Cd2Z/5HWA==",
      "license": "MIT",
      "dependencies": {
        "mime-db": "^1.54.0"
      },
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/minimatch": {
      "version": "3.1.2",
      "resolved": "https://registry.npmjs.org/minimatch/-/minimatch-3.1.2.tgz",
      "integrity": "sha512-J7p63hRiAjw1NDEww1W7i37+ByIrOWO5XQQAzZ3VOcL0PNybwpfmV/N05zFAzwQ9USyEcX6t3UO+K5aqBQOIHw==",
      "license": "ISC",
      "dependencies": {
        "brace-expansion": "^1.1.7"
      },
      "engines": {
        "node": "*"
      }
    },
    "node_modules/minimist": {
      "version": "1.2.8",
      "resolved": "https://registry.npmjs.org/minimist/-/minimist-1.2.8.tgz",
      "integrity": "sha512-2yyAR8qBkN3YuheJanUpWC5U3bb5osDywNB8RzDVlDwDHbocAJveqqj1u8+SVD7jkWT4yvsHCpWqqWqAxb0zCA==",
      "license": "MIT",
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/minipass": {
      "version": "5.0.0",
      "resolved": "https://registry.npmjs.org/minipass/-/minipass-5.0.0.tgz",
      "integrity": "sha512-3FnjYuehv9k6ovOEbyOswadCDPX1piCfhV8ncmYtHOjuPwylVWsghTLo7rabjC3Rx5xD4HDx8Wm1xnMF7S5qFQ==",
      "license": "ISC",
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/minizlib": {
      "version": "2.1.2",
      "resolved": "https://registry.npmjs.org/minizlib/-/minizlib-2.1.2.tgz",
      "integrity": "sha512-bAxsR8BVfj60DWXHE3u30oHzfl4G7khkSuPW+qvpd7jFRHm7dLxOjUk1EHACJ/hxLY8phGJ0YhYHZo7jil7Qdg==",
      "license": "MIT",
      "dependencies": {
        "minipass": "^3.0.0",
        "yallist": "^4.0.0"
      },
      "engines": {
        "node": ">= 8"
      }
    },
    "node_modules/minizlib/node_modules/minipass": {
      "version": "3.3.6",
      "resolved": "https://registry.npmjs.org/minipass/-/minipass-3.3.6.tgz",
      "integrity": "sha512-DxiNidxSEK+tHG6zOIklvNOwm3hvCrbUrdtzY74U6HKTJxvIDfOUL5W5P2Ghd3DTkhhKPYGqeNUIh5qcM4YBfw==",
      "license": "ISC",
      "dependencies": {
        "yallist": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/mkdirp": {
      "version": "1.0.4",
      "resolved": "https://registry.npmjs.org/mkdirp/-/mkdirp-1.0.4.tgz",
      "integrity": "sha512-vVqVZQyf3WLx2Shd0qJ9xuvqgAyKPLAiqITEtqW0oIUjzo3PePDd6fW9iFz30ef7Ysp/oiWqbhszeGWW2T6Gzw==",
      "license": "MIT",
      "bin": {
        "mkdirp": "bin/cmd.js"
      },
      "engines": {
        "node": ">=10"
      }
    },
    "node_modules/mongodb": {
      "version": "6.15.0",
      "resolved": "https://registry.npmjs.org/mongodb/-/mongodb-6.15.0.tgz",
      "integrity": "sha512-ifBhQ0rRzHDzqp9jAQP6OwHSH7dbYIQjD3SbJs9YYk9AikKEettW/9s/tbSFDTpXcRbF+u1aLrhHxDFaYtZpFQ==",
      "license": "Apache-2.0",
      "dependencies": {
        "@mongodb-js/saslprep": "^1.1.9",
        "bson": "^6.10.3",
        "mongodb-connection-string-url": "^3.0.0"
      },
      "engines": {
        "node": ">=16.20.1"
      },
      "peerDependencies": {
        "@aws-sdk/credential-providers": "^3.188.0",
        "@mongodb-js/zstd": "^1.1.0 || ^2.0.0",
        "gcp-metadata": "^5.2.0",
        "kerberos": "^2.0.1",
        "mongodb-client-encryption": ">=6.0.0 <7",
        "snappy": "^7.2.2",
        "socks": "^2.7.1"
      },
      "peerDependenciesMeta": {
        "@aws-sdk/credential-providers": {
          "optional": true
        },
        "@mongodb-js/zstd": {
          "optional": true
        },
        "gcp-metadata": {
          "optional": true
        },
        "kerberos": {
          "optional": true
        },
        "mongodb-client-encryption": {
          "optional": true
        },
        "snappy": {
          "optional": true
        },
        "socks": {
          "optional": true
        }
      }
    },
    "node_modules/mongodb-connection-string-url": {
      "version": "3.0.2",
      "resolved": "https://registry.npmjs.org/mongodb-connection-string-url/-/mongodb-connection-string-url-3.0.2.tgz",
      "integrity": "sha512-rMO7CGo/9BFwyZABcKAWL8UJwH/Kc2x0g72uhDWzG48URRax5TCIcJ7Rc3RZqffZzO/Gwff/jyKwCU9TN8gehA==",
      "license": "Apache-2.0",
      "dependencies": {
        "@types/whatwg-url": "^11.0.2",
        "whatwg-url": "^14.1.0 || ^13.0.0"
      }
    },
    "node_modules/mongoose": {
      "version": "8.13.2",
      "resolved": "https://registry.npmjs.org/mongoose/-/mongoose-8.13.2.tgz",
      "integrity": "sha512-riCBqZmNkYBWjXpM3qWLDQw7QmTKsVZDPhLXFJqC87+OjocEVpvS3dA2BPPUiLAu+m0/QmEj5pSXKhH+/DgerQ==",
      "license": "MIT",
      "dependencies": {
        "bson": "^6.10.3",
        "kareem": "2.6.3",
        "mongodb": "~6.15.0",
        "mpath": "0.9.0",
        "mquery": "5.0.0",
        "ms": "2.1.3",
        "sift": "17.1.3"
      },
      "engines": {
        "node": ">=16.20.1"
      },
      "funding": {
        "type": "opencollective",
        "url": "https://opencollective.com/mongoose"
      }
    },
    "node_modules/morgan": {
      "version": "1.10.0",
      "resolved": "https://registry.npmjs.org/morgan/-/morgan-1.10.0.tgz",
      "integrity": "sha512-AbegBVI4sh6El+1gNwvD5YIck7nSA36weD7xvIxG4in80j/UoK8AEGaWnnz8v1GxonMCltmlNs5ZKbGvl9b1XQ==",
      "license": "MIT",
      "dependencies": {
        "basic-auth": "~2.0.1",
        "debug": "2.6.9",
        "depd": "~2.0.0",
        "on-finished": "~2.3.0",
        "on-headers": "~1.0.2"
      },
      "engines": {
        "node": ">= 0.8.0"
      }
    },
    "node_modules/morgan/node_modules/debug": {
      "version": "2.6.9",
      "resolved": "https://registry.npmjs.org/debug/-/debug-2.6.9.tgz",
      "integrity": "sha512-bC7ElrdJaJnPbAP+1EotYvqZsb3ecl5wi6Bfi6BJTUcNowp6cvspg0jXznRTKDjm/E7AdgFBVeAPVMNcKGsHMA==",
      "license": "MIT",
      "dependencies": {
        "ms": "2.0.0"
      }
    },
    "node_modules/morgan/node_modules/ms": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/ms/-/ms-2.0.0.tgz",
      "integrity": "sha512-Tpp60P6IUJDTuOq/5Z8cdskzJujfwqfOTkrwIwj7IRISpnkJnT6SyJ4PCPnGMoFjC9ddhal5KVIYtAt97ix05A==",
      "license": "MIT"
    },
    "node_modules/morgan/node_modules/on-finished": {
      "version": "2.3.0",
      "resolved": "https://registry.npmjs.org/on-finished/-/on-finished-2.3.0.tgz",
      "integrity": "sha512-ikqdkGAAyf/X/gPhXGvfgAytDZtDbr+bkNUJ0N9h5MI/dmdgCs3l6hoHrcUv41sRKew3jIwrp4qQDXiK99Utww==",
      "license": "MIT",
      "dependencies": {
        "ee-first": "1.1.1"
      },
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/mpath": {
      "version": "0.9.0",
      "resolved": "https://registry.npmjs.org/mpath/-/mpath-0.9.0.tgz",
      "integrity": "sha512-ikJRQTk8hw5DEoFVxHG1Gn9T/xcjtdnOKIU1JTmGjZZlg9LST2mBLmcX3/ICIbgJydT2GOc15RnNy5mHmzfSew==",
      "license": "MIT",
      "engines": {
        "node": ">=4.0.0"
      }
    },
    "node_modules/mquery": {
      "version": "5.0.0",
      "resolved": "https://registry.npmjs.org/mquery/-/mquery-5.0.0.tgz",
      "integrity": "sha512-iQMncpmEK8R8ncT8HJGsGc9Dsp8xcgYMVSbs5jgnm1lFHTZqMJTUWTDx1LBO8+mK3tPNZWFLBghQEIOULSTHZg==",
      "license": "MIT",
      "dependencies": {
        "debug": "4.x"
      },
      "engines": {
        "node": ">=14.0.0"
      }
    },
    "node_modules/ms": {
      "version": "2.1.3",
      "resolved": "https://registry.npmjs.org/ms/-/ms-2.1.3.tgz",
      "integrity": "sha512-6FlzubTLZG3J2a/NVCAleEhjzq5oxgHyaCU9yYXvcLsvoVaHJq/s5xXI6/XXP6tz7R9xAOtHnSO/tXtF3WRTlA==",
      "license": "MIT"
    },
    "node_modules/multer": {
      "version": "1.4.5-lts.2",
      "resolved": "https://registry.npmjs.org/multer/-/multer-1.4.5-lts.2.tgz",
      "integrity": "sha512-VzGiVigcG9zUAoCNU+xShztrlr1auZOlurXynNvO9GiWD1/mTBbUljOKY+qMeazBqXgRnjzeEgJI/wyjJUHg9A==",
      "license": "MIT",
      "dependencies": {
        "append-field": "^1.0.0",
        "busboy": "^1.0.0",
        "concat-stream": "^1.5.2",
        "mkdirp": "^0.5.4",
        "object-assign": "^4.1.1",
        "type-is": "^1.6.4",
        "xtend": "^4.0.0"
      },
      "engines": {
        "node": ">= 6.0.0"
      }
    },
    "node_modules/multer/node_modules/media-typer": {
      "version": "0.3.0",
      "resolved": "https://registry.npmjs.org/media-typer/-/media-typer-0.3.0.tgz",
      "integrity": "sha512-dq+qelQ9akHpcOl/gUVRTxVIOkAJ1wR3QAvb4RsVjS8oVoFjDGTc679wJYmUmknUF5HwMLOgb5O+a3KxfWapPQ==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/multer/node_modules/mime-db": {
      "version": "1.52.0",
      "resolved": "https://registry.npmjs.org/mime-db/-/mime-db-1.52.0.tgz",
      "integrity": "sha512-sPU4uV7dYlvtWJxwwxHD0PuihVNiE7TyAbQ5SWxDCB9mUYvOgroQOwYQQOKPJ8CIbE+1ETVlOoK1UC2nU3gYvg==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/multer/node_modules/mime-types": {
      "version": "2.1.35",
      "resolved": "https://registry.npmjs.org/mime-types/-/mime-types-2.1.35.tgz",
      "integrity": "sha512-ZDY+bPm5zTTF+YpCrAU9nK0UgICYPT0QtT1NZWFv4s++TNkcgVaT0g6+4R2uI4MjQjzysHB1zxuWL50hzaeXiw==",
      "license": "MIT",
      "dependencies": {
        "mime-db": "1.52.0"
      },
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/multer/node_modules/mkdirp": {
      "version": "0.5.6",
      "resolved": "https://registry.npmjs.org/mkdirp/-/mkdirp-0.5.6.tgz",
      "integrity": "sha512-FP+p8RB8OWpF3YZBCrP5gtADmtXApB5AMLn+vdyA+PyxCjrCs00mjyUozssO33cwDeT3wNGdLxJ5M//YqtHAJw==",
      "license": "MIT",
      "dependencies": {
        "minimist": "^1.2.6"
      },
      "bin": {
        "mkdirp": "bin/cmd.js"
      }
    },
    "node_modules/multer/node_modules/type-is": {
      "version": "1.6.18",
      "resolved": "https://registry.npmjs.org/type-is/-/type-is-1.6.18.tgz",
      "integrity": "sha512-TkRKr9sUTxEH8MdfuCSP7VizJyzRNMjj2J2do2Jr3Kym598JVdEksuzPQCnlFPW4ky9Q+iA+ma9BGm06XQBy8g==",
      "license": "MIT",
      "dependencies": {
        "media-typer": "0.3.0",
        "mime-types": "~2.1.24"
      },
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/negotiator": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/negotiator/-/negotiator-1.0.0.tgz",
      "integrity": "sha512-8Ofs/AUQh8MaEcrlq5xOX0CQ9ypTF5dl78mjlMNfOK08fzpgTHQRQPBxcPlEtIw0yRpws+Zo/3r+5WRby7u3Gg==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/node-addon-api": {
      "version": "5.1.0",
      "resolved": "https://registry.npmjs.org/node-addon-api/-/node-addon-api-5.1.0.tgz",
      "integrity": "sha512-eh0GgfEkpnoWDq+VY8OyvYhFEzBk6jIYbRKdIlyTiAXIVJ8PyBaKb0rp7oDtoddbdoHWhq8wwr+XZ81F1rpNdA==",
      "license": "MIT"
    },
    "node_modules/node-cron": {
      "version": "3.0.3",
      "resolved": "https://registry.npmjs.org/node-cron/-/node-cron-3.0.3.tgz",
      "integrity": "sha512-dOal67//nohNgYWb+nWmg5dkFdIwDm8EpeGYMekPMrngV3637lqnX0lbUcCtgibHTz6SEz7DAIjKvKDFYCnO1A==",
      "license": "ISC",
      "dependencies": {
        "uuid": "8.3.2"
      },
      "engines": {
        "node": ">=6.0.0"
      }
    },
    "node_modules/node-fetch": {
      "version": "2.7.0",
      "resolved": "https://registry.npmjs.org/node-fetch/-/node-fetch-2.7.0.tgz",
      "integrity": "sha512-c4FRfUm/dbcWZ7U+1Wq0AwCyFL+3nt2bEw05wfxSz+DWpWsitgmSgYmy2dQdWyKC1694ELPqMs/YzUSNozLt8A==",
      "license": "MIT",
      "dependencies": {
        "whatwg-url": "^5.0.0"
      },
      "engines": {
        "node": "4.x || >=6.0.0"
      },
      "peerDependencies": {
        "encoding": "^0.1.0"
      },
      "peerDependenciesMeta": {
        "encoding": {
          "optional": true
        }
      }
    },
    "node_modules/node-fetch/node_modules/tr46": {
      "version": "0.0.3",
      "resolved": "https://registry.npmjs.org/tr46/-/tr46-0.0.3.tgz",
      "integrity": "sha512-N3WMsuqV66lT30CrXNbEjx4GEwlow3v6rr4mCcv6prnfwhS01rkgyFdjPNBYd9br7LpXV1+Emh01fHnq2Gdgrw==",
      "license": "MIT"
    },
    "node_modules/node-fetch/node_modules/webidl-conversions": {
      "version": "3.0.1",
      "resolved": "https://registry.npmjs.org/webidl-conversions/-/webidl-conversions-3.0.1.tgz",
      "integrity": "sha512-2JAn3z8AR6rjK8Sm8orRC0h/bcl/DqL7tRPdGZ4I1CjdF+EaMLmYxBHyXuKL849eucPFhvBoxMsflfOb8kxaeQ==",
      "license": "BSD-2-Clause"
    },
    "node_modules/node-fetch/node_modules/whatwg-url": {
      "version": "5.0.0",
      "resolved": "https://registry.npmjs.org/whatwg-url/-/whatwg-url-5.0.0.tgz",
      "integrity": "sha512-saE57nupxk6v3HY35+jzBwYa0rKSy0XR8JSxZPwgLr7ys0IBzhGviA1/TUGJLmSVqs8pb9AnvICXEuOHLprYTw==",
      "license": "MIT",
      "dependencies": {
        "tr46": "~0.0.3",
        "webidl-conversions": "^3.0.0"
      }
    },
    "node_modules/nodemailer": {
      "version": "6.10.0",
      "resolved": "https://registry.npmjs.org/nodemailer/-/nodemailer-6.10.0.tgz",
      "integrity": "sha512-SQ3wZCExjeSatLE/HBaXS5vqUOQk6GtBdIIKxiFdmm01mOQZX/POJkO3SUX1wDiYcwUOJwT23scFSC9fY2H8IA==",
      "license": "MIT-0",
      "engines": {
        "node": ">=6.0.0"
      }
    },
    "node_modules/nopt": {
      "version": "5.0.0",
      "resolved": "https://registry.npmjs.org/nopt/-/nopt-5.0.0.tgz",
      "integrity": "sha512-Tbj67rffqceeLpcRXrT7vKAN8CwfPeIBgM7E6iBkmKLV7bEMwpGgYLGv0jACUsECaa/vuxP0IjEont6umdMgtQ==",
      "license": "ISC",
      "dependencies": {
        "abbrev": "1"
      },
      "bin": {
        "nopt": "bin/nopt.js"
      },
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/npmlog": {
      "version": "5.0.1",
      "resolved": "https://registry.npmjs.org/npmlog/-/npmlog-5.0.1.tgz",
      "integrity": "sha512-AqZtDUWOMKs1G/8lwylVjrdYgqA4d9nu8hc+0gzRxlDb1I10+FHBGMXs6aiQHFdCUUlqH99MUMuLfzWDNDtfxw==",
      "deprecated": "This package is no longer supported.",
      "license": "ISC",
      "dependencies": {
        "are-we-there-yet": "^2.0.0",
        "console-control-strings": "^1.1.0",
        "gauge": "^3.0.0",
        "set-blocking": "^2.0.0"
      }
    },
    "node_modules/object-assign": {
      "version": "4.1.1",
      "resolved": "https://registry.npmjs.org/object-assign/-/object-assign-4.1.1.tgz",
      "integrity": "sha512-rJgTQnkUnH1sFw8yT6VSU3zD3sWmu6sZhIseY8VX+GRu3P6F7Fu+JNDoXfklElbLJSnc3FUQHVe4cU5hj+BcUg==",
      "license": "MIT",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/object-inspect": {
      "version": "1.13.4",
      "resolved": "https://registry.npmjs.org/object-inspect/-/object-inspect-1.13.4.tgz",
      "integrity": "sha512-W67iLl4J2EXEGTbfeHCffrjDfitvLANg0UlX3wFUUSTx92KXRFegMHUVgSqE+wvhAbi4WqjGg9czysTV2Epbew==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/on-finished": {
      "version": "2.4.1",
      "resolved": "https://registry.npmjs.org/on-finished/-/on-finished-2.4.1.tgz",
      "integrity": "sha512-oVlzkg3ENAhCk2zdv7IJwd/QUD4z2RxRwpkcGY8psCVcCYZNq4wYnVWALHM+brtuJjePWiYF/ClmuDr8Ch5+kg==",
      "license": "MIT",
      "dependencies": {
        "ee-first": "1.1.1"
      },
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/on-headers": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/on-headers/-/on-headers-1.0.2.tgz",
      "integrity": "sha512-pZAE+FJLoyITytdqK0U5s+FIpjN0JP3OzFi/u8Rx+EV5/W+JTWGXG8xFzevE7AjBfDqHv/8vL8qQsIhHnqRkrA==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/once": {
      "version": "1.4.0",
      "resolved": "https://registry.npmjs.org/once/-/once-1.4.0.tgz",
      "integrity": "sha512-lNaJgI+2Q5URQBkccEKHTQOPaXdUxnZZElQTZY0MFUAuaEqe1E+Nyvgdz/aIyNi6Z9MzO5dv1H8n58/GELp3+w==",
      "license": "ISC",
      "dependencies": {
        "wrappy": "1"
      }
    },
    "node_modules/parseurl": {
      "version": "1.3.3",
      "resolved": "https://registry.npmjs.org/parseurl/-/parseurl-1.3.3.tgz",
      "integrity": "sha512-CiyeOxFT/JZyN5m0z9PfXw4SCBJ6Sygz1Dpl0wqjlhDEGGBP1GnsUVEL0p63hoG1fcj3fHynXi9NYO4nWOL+qQ==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/path-is-absolute": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/path-is-absolute/-/path-is-absolute-1.0.1.tgz",
      "integrity": "sha512-AVbw3UJ2e9bq64vSaS9Am0fje1Pa8pbGqTTsmXfaIiMpnr5DlDhfJOuLj9Sf95ZPVDAUerDfEk88MPmPe7UCQg==",
      "license": "MIT",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/path-to-regexp": {
      "version": "8.2.0",
      "resolved": "https://registry.npmjs.org/path-to-regexp/-/path-to-regexp-8.2.0.tgz",
      "integrity": "sha512-TdrF7fW9Rphjq4RjrW0Kp2AW0Ahwu9sRGTkS6bvDi0SCwZlEZYmcfDbEsTz8RVk0EHIS/Vd1bv3JhG+1xZuAyQ==",
      "license": "MIT",
      "engines": {
        "node": ">=16"
      }
    },
    "node_modules/process-nextick-args": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/process-nextick-args/-/process-nextick-args-2.0.1.tgz",
      "integrity": "sha512-3ouUOpQhtgrbOa17J7+uxOTpITYWaGP7/AhoR3+A+/1e9skrzelGi/dXzEYyvbxubEF6Wn2ypscTKiKJFFn1ag==",
      "license": "MIT"
    },
    "node_modules/proxy-addr": {
      "version": "2.0.7",
      "resolved": "https://registry.npmjs.org/proxy-addr/-/proxy-addr-2.0.7.tgz",
      "integrity": "sha512-llQsMLSUDUPT44jdrU/O37qlnifitDP+ZwrmmZcoSKyLKvtZxpyV0n2/bD/N4tBAAZ/gJEdZU7KMraoK1+XYAg==",
      "license": "MIT",
      "dependencies": {
        "forwarded": "0.2.0",
        "ipaddr.js": "1.9.1"
      },
      "engines": {
        "node": ">= 0.10"
      }
    },
    "node_modules/proxy-from-env": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/proxy-from-env/-/proxy-from-env-1.1.0.tgz",
      "integrity": "sha512-D+zkORCbA9f1tdWRK0RaCR3GPv50cMxcrz4X8k5LTSUD1Dkw47mKJEZQNunItRTkWwgtaUSo1RVFRIG9ZXiFYg==",
      "license": "MIT"
    },
    "node_modules/punycode": {
      "version": "2.3.1",
      "resolved": "https://registry.npmjs.org/punycode/-/punycode-2.3.1.tgz",
      "integrity": "sha512-vYt7UD1U9Wg6138shLtLOvdAu+8DsC/ilFtEVHcH+wydcSpNE20AfSOduf6MkRFahL5FY7X1oU7nKVZFtfq8Fg==",
      "license": "MIT",
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/qs": {
      "version": "6.14.0",
      "resolved": "https://registry.npmjs.org/qs/-/qs-6.14.0.tgz",
      "integrity": "sha512-YWWTjgABSKcvs/nWBi9PycY/JiPJqOD4JA6o9Sej2AtvSGarXxKC3OQSk4pAarbdQlKAh5D4FCQkJNkW+GAn3w==",
      "license": "BSD-3-Clause",
      "dependencies": {
        "side-channel": "^1.1.0"
      },
      "engines": {
        "node": ">=0.6"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/range-parser": {
      "version": "1.2.1",
      "resolved": "https://registry.npmjs.org/range-parser/-/range-parser-1.2.1.tgz",
      "integrity": "sha512-Hrgsx+orqoygnmhFbKaHE6c296J+HTAQXoxEF6gNupROmmGJRoyzfG3ccAveqCBrwr/2yxQ5BVd/GTl5agOwSg==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/raw-body": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/raw-body/-/raw-body-3.0.0.tgz",
      "integrity": "sha512-RmkhL8CAyCRPXCE28MMH0z2PNWQBNk2Q09ZdxM9IOOXwxwZbN+qbWaatPkdkWIKL2ZVDImrN/pK5HTRz2PcS4g==",
      "license": "MIT",
      "dependencies": {
        "bytes": "3.1.2",
        "http-errors": "2.0.0",
        "iconv-lite": "0.6.3",
        "unpipe": "1.0.0"
      },
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/readable-stream": {
      "version": "3.6.2",
      "resolved": "https://registry.npmjs.org/readable-stream/-/readable-stream-3.6.2.tgz",
      "integrity": "sha512-9u/sniCrY3D5WdsERHzHE4G2YCXqoG5FTHUiCC4SIbr6XcLZBY05ya9EKjYek9O5xOAwjGq+1JdGBAS7Q9ScoA==",
      "license": "MIT",
      "dependencies": {
        "inherits": "^2.0.3",
        "string_decoder": "^1.1.1",
        "util-deprecate": "^1.0.1"
      },
      "engines": {
        "node": ">= 6"
      }
    },
    "node_modules/rimraf": {
      "version": "3.0.2",
      "resolved": "https://registry.npmjs.org/rimraf/-/rimraf-3.0.2.tgz",
      "integrity": "sha512-JZkJMZkAGFFPP2YqXZXPbMlMBgsxzE8ILs4lMIX/2o0L9UBw9O/Y3o6wFw/i9YLapcUJWwqbi3kdxIPdC62TIA==",
      "deprecated": "Rimraf versions prior to v4 are no longer supported",
      "license": "ISC",
      "dependencies": {
        "glob": "^7.1.3"
      },
      "bin": {
        "rimraf": "bin.js"
      },
      "funding": {
        "url": "https://github.com/sponsors/isaacs"
      }
    },
    "node_modules/router": {
      "version": "2.2.0",
      "resolved": "https://registry.npmjs.org/router/-/router-2.2.0.tgz",
      "integrity": "sha512-nLTrUKm2UyiL7rlhapu/Zl45FwNgkZGaCpZbIHajDYgwlJCOzLSk+cIPAnsEqV955GjILJnKbdQC1nVPz+gAYQ==",
      "license": "MIT",
      "dependencies": {
        "debug": "^4.4.0",
        "depd": "^2.0.0",
        "is-promise": "^4.0.0",
        "parseurl": "^1.3.3",
        "path-to-regexp": "^8.0.0"
      },
      "engines": {
        "node": ">= 18"
      }
    },
    "node_modules/safe-buffer": {
      "version": "5.2.1",
      "resolved": "https://registry.npmjs.org/safe-buffer/-/safe-buffer-5.2.1.tgz",
      "integrity": "sha512-rp3So07KcdmmKbGvgaNxQSJr7bGVSVk5S9Eq1F+ppbRo70+YeaDxkw5Dd8NPN+GD6bjnYm2VuPuCXmpuYvmCXQ==",
      "funding": [
        {
          "type": "github",
          "url": "https://github.com/sponsors/feross"
        },
        {
          "type": "patreon",
          "url": "https://www.patreon.com/feross"
        },
        {
          "type": "consulting",
          "url": "https://feross.org/support"
        }
      ],
      "license": "MIT"
    },
    "node_modules/safer-buffer": {
      "version": "2.1.2",
      "resolved": "https://registry.npmjs.org/safer-buffer/-/safer-buffer-2.1.2.tgz",
      "integrity": "sha512-YZo3K82SD7Riyi0E1EQPojLz7kpepnSQI9IyPbHHg1XXXevb5dJI7tpyN2ADxGcQbHG7vcyRHk0cbwqcQriUtg==",
      "license": "MIT"
    },
    "node_modules/semver": {
      "version": "7.7.1",
      "resolved": "https://registry.npmjs.org/semver/-/semver-7.7.1.tgz",
      "integrity": "sha512-hlq8tAfn0m/61p4BVRcPzIGr6LKiMwo4VM6dGi6pt4qcRkmNzTcWq6eCEjEh+qXjkMDvPlOFFSGwQjoEa6gyMA==",
      "license": "ISC",
      "bin": {
        "semver": "bin/semver.js"
      },
      "engines": {
        "node": ">=10"
      }
    },
    "node_modules/send": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/send/-/send-1.2.0.tgz",
      "integrity": "sha512-uaW0WwXKpL9blXE2o0bRhoL2EGXIrZxQ2ZQ4mgcfoBxdFmQold+qWsD2jLrfZ0trjKL6vOw0j//eAwcALFjKSw==",
      "license": "MIT",
      "dependencies": {
        "debug": "^4.3.5",
        "encodeurl": "^2.0.0",
        "escape-html": "^1.0.3",
        "etag": "^1.8.1",
        "fresh": "^2.0.0",
        "http-errors": "^2.0.0",
        "mime-types": "^3.0.1",
        "ms": "^2.1.3",
        "on-finished": "^2.4.1",
        "range-parser": "^1.2.1",
        "statuses": "^2.0.1"
      },
      "engines": {
        "node": ">= 18"
      }
    },
    "node_modules/serve-static": {
      "version": "2.2.0",
      "resolved": "https://registry.npmjs.org/serve-static/-/serve-static-2.2.0.tgz",
      "integrity": "sha512-61g9pCh0Vnh7IutZjtLGGpTA355+OPn2TyDv/6ivP2h/AdAVX9azsoxmg2/M6nZeQZNYBEwIcsne1mJd9oQItQ==",
      "license": "MIT",
      "dependencies": {
        "encodeurl": "^2.0.0",
        "escape-html": "^1.0.3",
        "parseurl": "^1.3.3",
        "send": "^1.2.0"
      },
      "engines": {
        "node": ">= 18"
      }
    },
    "node_modules/set-blocking": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/set-blocking/-/set-blocking-2.0.0.tgz",
      "integrity": "sha512-KiKBS8AnWGEyLzofFfmvKwpdPzqiy16LvQfK3yv/fVH7Bj13/wl3JSR1J+rfgRE9q7xUJK4qvgS8raSOeLUehw==",
      "license": "ISC"
    },
    "node_modules/setprototypeof": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/setprototypeof/-/setprototypeof-1.2.0.tgz",
      "integrity": "sha512-E5LDX7Wrp85Kil5bhZv46j8jOeboKq5JMmYM3gVGdGH8xFpPWXUMsNrlODCrkoxMEeNi/XZIwuRvY4XNwYMJpw==",
      "license": "ISC"
    },
    "node_modules/side-channel": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/side-channel/-/side-channel-1.1.0.tgz",
      "integrity": "sha512-ZX99e6tRweoUXqR+VBrslhda51Nh5MTQwou5tnUDgbtyM0dBgmhEDtWGP/xbKn6hqfPRHujUNwz5fy/wbbhnpw==",
      "license": "MIT",
      "dependencies": {
        "es-errors": "^1.3.0",
        "object-inspect": "^1.13.3",
        "side-channel-list": "^1.0.0",
        "side-channel-map": "^1.0.1",
        "side-channel-weakmap": "^1.0.2"
      },
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/side-channel-list": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/side-channel-list/-/side-channel-list-1.0.0.tgz",
      "integrity": "sha512-FCLHtRD/gnpCiCHEiJLOwdmFP+wzCmDEkc9y7NsYxeF4u7Btsn1ZuwgwJGxImImHicJArLP4R0yX4c2KCrMrTA==",
      "license": "MIT",
      "dependencies": {
        "es-errors": "^1.3.0",
        "object-inspect": "^1.13.3"
      },
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/side-channel-map": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/side-channel-map/-/side-channel-map-1.0.1.tgz",
      "integrity": "sha512-VCjCNfgMsby3tTdo02nbjtM/ewra6jPHmpThenkTYh8pG9ucZ/1P8So4u4FGBek/BjpOVsDCMoLA/iuBKIFXRA==",
      "license": "MIT",
      "dependencies": {
        "call-bound": "^1.0.2",
        "es-errors": "^1.3.0",
        "get-intrinsic": "^1.2.5",
        "object-inspect": "^1.13.3"
      },
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/side-channel-weakmap": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/side-channel-weakmap/-/side-channel-weakmap-1.0.2.tgz",
      "integrity": "sha512-WPS/HvHQTYnHisLo9McqBHOJk2FkHO/tlpvldyrnem4aeQp4hai3gythswg6p01oSoTl58rcpiFAjF2br2Ak2A==",
      "license": "MIT",
      "dependencies": {
        "call-bound": "^1.0.2",
        "es-errors": "^1.3.0",
        "get-intrinsic": "^1.2.5",
        "object-inspect": "^1.13.3",
        "side-channel-map": "^1.0.1"
      },
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/sift": {
      "version": "17.1.3",
      "resolved": "https://registry.npmjs.org/sift/-/sift-17.1.3.tgz",
      "integrity": "sha512-Rtlj66/b0ICeFzYTuNvX/EF1igRbbnGSvEyT79McoZa/DeGhMyC5pWKOEsZKnpkqtSeovd5FL/bjHWC3CIIvCQ==",
      "license": "MIT"
    },
    "node_modules/signal-exit": {
      "version": "3.0.7",
      "resolved": "https://registry.npmjs.org/signal-exit/-/signal-exit-3.0.7.tgz",
      "integrity": "sha512-wnD2ZE+l+SPC/uoS0vXeE9L1+0wuaMqKlfz9AMUo38JsyLSBWSFcHR1Rri62LZc12vLr1gb3jl7iwQhgwpAbGQ==",
      "license": "ISC"
    },
    "node_modules/sparse-bitfield": {
      "version": "3.0.3",
      "resolved": "https://registry.npmjs.org/sparse-bitfield/-/sparse-bitfield-3.0.3.tgz",
      "integrity": "sha512-kvzhi7vqKTfkh0PZU+2D2PIllw2ymqJKujUcyPMd9Y75Nv4nPbGJZXNhxsgdQab2BmlDct1YnfQCguEvHr7VsQ==",
      "license": "MIT",
      "dependencies": {
        "memory-pager": "^1.0.2"
      }
    },
    "node_modules/statuses": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/statuses/-/statuses-2.0.1.tgz",
      "integrity": "sha512-RwNA9Z/7PrK06rYLIzFMlaF+l73iwpzsqRIFgbMLbTcLD6cOao82TaWefPXQvB2fOC4AjuYSEndS7N/mTCbkdQ==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/streamsearch": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/streamsearch/-/streamsearch-1.1.0.tgz",
      "integrity": "sha512-Mcc5wHehp9aXz1ax6bZUyY5afg9u2rv5cqQI3mRrYkGC8rW2hM02jWuwjtL++LS5qinSyhj2QfLyNsuc+VsExg==",
      "engines": {
        "node": ">=10.0.0"
      }
    },
    "node_modules/string_decoder": {
      "version": "1.3.0",
      "resolved": "https://registry.npmjs.org/string_decoder/-/string_decoder-1.3.0.tgz",
      "integrity": "sha512-hkRX8U1WjJFd8LsDJ2yQ/wWWxaopEsABU1XfkM8A+j0+85JAGppt16cr1Whg6KIbb4okU6Mql6BOj+uup/wKeA==",
      "license": "MIT",
      "dependencies": {
        "safe-buffer": "~5.2.0"
      }
    },
    "node_modules/string-width": {
      "version": "4.2.3",
      "resolved": "https://registry.npmjs.org/string-width/-/string-width-4.2.3.tgz",
      "integrity": "sha512-wKyQRQpjJ0sIp62ErSZdGsjMJWsap5oRNihHhu6G7JVO/9jIB6UyevL+tXuOqrng8j/cxKTWyWUwvSTriiZz/g==",
      "license": "MIT",
      "dependencies": {
        "emoji-regex": "^8.0.0",
        "is-fullwidth-code-point": "^3.0.0",
        "strip-ansi": "^6.0.1"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/strip-ansi": {
      "version": "6.0.1",
      "resolved": "https://registry.npmjs.org/strip-ansi/-/strip-ansi-6.0.1.tgz",
      "integrity": "sha512-Y38VPSHcqkFrCpFnQ9vuSXmquuv5oXOKpGeT6aGrr3o3Gc9AlVa6JBfUSOCnbxGGZF+/0ooI7KrPuUSztUdU5A==",
      "license": "MIT",
      "dependencies": {
        "ansi-regex": "^5.0.1"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/tar": {
      "version": "6.2.1",
      "resolved": "https://registry.npmjs.org/tar/-/tar-6.2.1.tgz",
      "integrity": "sha512-DZ4yORTwrbTj/7MZYq2w+/ZFdI6OZ/f9SFHR+71gIVUZhOQPHzVCLpvRnPgyaMpfWxxk/4ONva3GQSyNIKRv6A==",
      "license": "ISC",
      "dependencies": {
        "chownr": "^2.0.0",
        "fs-minipass": "^2.0.0",
        "minipass": "^5.0.0",
        "minizlib": "^2.1.1",
        "mkdirp": "^1.0.3",
        "yallist": "^4.0.0"
      },
      "engines": {
        "node": ">=10"
      }
    },
    "node_modules/toidentifier": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/toidentifier/-/toidentifier-1.0.1.tgz",
      "integrity": "sha512-o5sSPKEkg/DIQNmH43V0/uerLrpzVedkUh8tGNvaeXpfpuwjKenlSox/2O/BTlZUtEe+JG7s5YhEz608PlAHRA==",
      "license": "MIT",
      "engines": {
        "node": ">=0.6"
      }
    },
    "node_modules/tr46": {
      "version": "5.1.0",
      "resolved": "https://registry.npmjs.org/tr46/-/tr46-5.1.0.tgz",
      "integrity": "sha512-IUWnUK7ADYR5Sl1fZlO1INDUhVhatWl7BtJWsIhwJ0UAK7ilzzIa8uIqOO/aYVWHZPJkKbEL+362wrzoeRF7bw==",
      "license": "MIT",
      "dependencies": {
        "punycode": "^2.3.1"
      },
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/tslib": {
      "version": "2.8.1",
      "resolved": "https://registry.npmjs.org/tslib/-/tslib-2.8.1.tgz",
      "integrity": "sha512-oJFu94HQb+KVduSUQL7wnpmqnfmLsOA/nAh6b6EH0wCEoK0/mPeXU6c3wKDV83MkOuHPRHtSXKKU99IBazS/2w==",
      "license": "0BSD"
    },
    "node_modules/type-is": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/type-is/-/type-is-2.0.1.tgz",
      "integrity": "sha512-OZs6gsjF4vMp32qrCbiVSkrFmXtG/AZhY3t0iAMrMBiAZyV9oALtXO8hsrHbMXF9x6L3grlFuwW2oAz7cav+Gw==",
      "license": "MIT",
      "dependencies": {
        "content-type": "^1.0.5",
        "media-typer": "^1.1.0",
        "mime-types": "^3.0.0"
      },
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/typedarray": {
      "version": "0.0.6",
      "resolved": "https://registry.npmjs.org/typedarray/-/typedarray-0.0.6.tgz",
      "integrity": "sha512-/aCDEGatGvZ2BIk+HmLf4ifCJFwvKFNb9/JeZPMulfgFracn9QFcAf5GO8B/mweUjSoblS5In0cWhqpfs/5PQA==",
      "license": "MIT"
    },
    "node_modules/unpipe": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/unpipe/-/unpipe-1.0.0.tgz",
      "integrity": "sha512-pjy2bYhSsufwWlKwPc+l3cN7+wuJlK6uz0YdJEOlQDbl6jo/YlPi4mb8agUkVC8BF7V8NuzeyPNqRksA3hztKQ==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/util-deprecate": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/util-deprecate/-/util-deprecate-1.0.2.tgz",
      "integrity": "sha512-EPD5q1uXyFxJpCrLnCc1nHnq3gOa6DZBocAIiI2TaSCA7VCJ1UJDMagCzIkXNsUYfD1daK//LTEQ8xiIbrHtcw==",
      "license": "MIT"
    },
    "node_modules/uuid": {
      "version": "8.3.2",
      "resolved": "https://registry.npmjs.org/uuid/-/uuid-8.3.2.tgz",
      "integrity": "sha512-+NYs2QeMWy+GWFOEm9xnn6HCDp0l7QBD7ml8zLUmJ+93Q5NF0NocErnwkTkXVFNiX3/fpC6afS8Dhb/gz7R7eg==",
      "license": "MIT",
      "bin": {
        "uuid": "dist/bin/uuid"
      }
    },
    "node_modules/vary": {
      "version": "1.1.2",
      "resolved": "https://registry.npmjs.org/vary/-/vary-1.1.2.tgz",
      "integrity": "sha512-BNGbWLfd0eUPabhkXUVm0j8uuvREyTh5ovRa/dyow/BqAbZJyC+5fU+IzQOzmAKzYqYRAISoRhdQr3eIZ/PXqg==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/webidl-conversions": {
      "version": "7.0.0",
      "resolved": "https://registry.npmjs.org/webidl-conversions/-/webidl-conversions-7.0.0.tgz",
      "integrity": "sha512-VwddBukDzu71offAQR975unBIGqfKZpM+8ZX6ySk8nYhVoo5CYaZyzt3YBvYtRtO+aoGlqxPg/B87NGVZ/fu6g==",
      "license": "BSD-2-Clause",
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/whatwg-url": {
      "version": "14.2.0",
      "resolved": "https://registry.npmjs.org/whatwg-url/-/whatwg-url-14.2.0.tgz",
      "integrity": "sha512-De72GdQZzNTUBBChsXueQUnPKDkg/5A5zp7pFDuQAj5UFoENpiACU0wlCvzpAGnTkj++ihpKwKyYewn/XNUbKw==",
      "license": "MIT",
      "dependencies": {
        "tr46": "^5.1.0",
        "webidl-conversions": "^7.0.0"
      },
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/wide-align": {
      "version": "1.1.5",
      "resolved": "https://registry.npmjs.org/wide-align/-/wide-align-1.1.5.tgz",
      "integrity": "sha512-eDMORYaPNZ4sQIuuYPDHdQvf4gyCF9rEEV/yPxGfwPkRodwEgiMUUXTx/dex+Me0wxx53S+NgUHaP7y3MGlDmg==",
      "license": "ISC",
      "dependencies": {
        "string-width": "^1.0.2 || 2 || 3 || 4"
      }
    },
    "node_modules/wrappy": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/wrappy/-/wrappy-1.0.2.tgz",
      "integrity": "sha512-l4Sp/DRseor9wL6EvV2+TuQn63dMkPjZ/sp9XkghTEbV9KlPS1xUsZ3u7/IQO4wxtcFB4bgpQPRcR3QCvezPcQ==",
      "license": "ISC"
    },
    "node_modules/xtend": {
      "version": "4.0.2",
      "resolved": "https://registry.npmjs.org/xtend/-/xtend-4.0.2.tgz",
      "integrity": "sha512-LKYU1iAXJXUgAXn9URjiu+MWhyUXHsvfp7mcuYm9dSUKK0/CjtrUwFAxD82/mCWbtLsGjFIad0wIsod4zrTAEQ==",
      "license": "MIT",
      "engines": {
        "node": ">=0.4"
      }
    },
    "node_modules/yallist": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/yallist/-/yallist-4.0.0.tgz",
      "integrity": "sha512-3wdGidZyq5PB084XLES5TpOSRA3wjXAlIWMhum2kRcv/41Sn2emQ0dycQW4uZXLejwKvg6EsvbdlVL+FYEct7A==",
      "license": "ISC"
    }
  }
}

```

### `backend\package.json`

```json
{
  "name": "backend",
  "version": "1.0.0",
  "description": "",
  "main": "server.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "node server.js"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "type": "commonjs",
  "dependencies": {
    "@faker-js/faker": "^9.6.0",
    "@imagekit/javascript": "^5.0.0",
    "axios": "^1.8.4",
    "bcrypt": "^5.1.1",
    "cors": "^2.8.5",
    "dotenv": "^16.4.7",
    "express": "^5.1.0",
    "imagekit": "^6.0.0",
    "jsonwebtoken": "^9.0.2",
    "mongoose": "^8.13.2",
    "morgan": "^1.10.0",
    "multer": "^1.4.5-lts.2",
    "node-cron": "^3.0.3",
    "nodemailer": "^6.10.0"
  }
}

```

### `backend\server.js`

```javascript
const env = require('dotenv').config()
const app = require('./src/app.js');
const config = require('./src/config/config');
require("./src/utils/fetchPrivacyNews.js");


app.listen(config.PORT, () => {
    console.log(`Server is running on port ${config.PORT}`);
})



const connectDB = require('./src/db/db.js')
connectDB()
```

### `backend\src\app.js`

```javascript
const express = require('express');
const morgan = require('morgan');
const cors = require('cors');
const app = express();
const authRoutes = require('./routes/auth.routes');
const OTPRoutes = require('./routes/otp.routes');
const userRoutes = require('./routes/user.routes');
const vaultRoutes = require('./routes/vault.routes');
const fakeDataRoutes = require("./routes/fakeData.routes");
const sharedDataRoutes = require("./routes/sharedData.routes");
const blogRoutes = require("./routes/blog.routes");


// Middleware
app.use(morgan('dev'));
app.use(express.json());
app.use(express.urlencoded({ extended: true }));
app.use(cors({
    origin: "http://localhost:5173",
}));


// Routes
app.get('/', (req, res) => {
    res.send('Welcome to the API!');
});

app.get('/health', (req, res) => {
    res.json({ status: 'OK' });
});

app.use('/api/auth', authRoutes);
app.use('/api/otp', OTPRoutes);
app.use('/api/user', userRoutes);
app.use('/api/vault', vaultRoutes);
app.use("/api/fake-data", fakeDataRoutes);
app.use("/api/sharedApps", sharedDataRoutes);
app.use("/api/blogs", blogRoutes);



// 404 Handler
app.use((req, res, next) => {
    res.status(404).json({ error: 'Not Found' });
});



// Export the app
module.exports = app;
```

### `backend\src\config\config.js`

```javascript
const _config = {
    PORT: process.env.PORT || 3000,
    MONGODB_URI: process.env.MONGODB_URI,
    JWT_SECRET: process.env.JWT_SECRET,
    EMAIL_USER: process.env.EMAIL_USER,
    EMAIL_PASS: process.env.EMAIL_PASS,
    VAULT_SECRET_KEY: process.env.VAULT_SECRET_KEY,
    NEWS_API_KEY: process.env.NEWS_API_KEY,
    IMAGEKIT_PUBLIC_KEY: process.env.IMAGEKIT_PUBLIC_KEY,
    IMAGEKIT_PRIVATE_KEY: process.env.IMAGEKIT_PRIVATE_KEY,
    IMAGEKIT_URL_ENDPOINT: process.env.IMAGEKIT_URL_ENDPOINT,
}

const config = Object.freeze(_config)

module.exports = config
```

### `backend\src\controllers\auth.controller.js`

```javascript
const userModel = require("../models/user.model")
const { createUser } = require("../services/auth.service")
const { sendEmail } = require("../services/email.service")
const generateVerificationCode = require("../utils/generateVerificationCode")

module.exports.registerController = async (req, res) => {
    try {
        const { firstName, lastName, email, password, phoneNumber } = req.body

        // Validate input
        if (!firstName || !lastName || !email || !password || !phoneNumber) {
            return res.status(400).json({
                errors: ['All fields are required'],
            })
        }


        //create user Service
        const OTP = generateVerificationCode()
        const newUser = await createUser({ firstName, lastName, email, password, phoneNumber, OTP })

        //send OTP by email
        const username = firstName.trim() + ` ${lastName.trim()}`
        const emailContent = `
        <html>
          <body style="font-family: Arial, sans-serif; color: #333;">
            <div style="background-color: #f0f0f0; padding: 20px; border-radius: 10px; max-width: 600px; margin: 0 auto;">
              <h2 style="color: #088395;">Welcome to Our Platform, ${username}!</h2>
              <h2 style="color: #088395;">Your OTP</h2>
              <p style="font-size: 18px; font-weight: bold;">Your OTP is: <span style="color: #37B7C3;">${OTP}</span></p>
              <p>Thank you for signing up with us. We’re excited to have you onboard!</p>
              <p>Here’s what you can do next:</p>
              <ul>
            <li>Explore our platform</li>
            <li>Set up your profile</li>
            <li>Start collaborating with others</li>
              </ul>
              <p style="color: #37B7C3;">Happy exploring!</p>
              <p>Best regards,<br/> The Team</p>
            </div>
          </body>
        </html>
          `;
       await sendEmail(email, 'Verify your account', emailContent)



        // Generate token
        const token = userModel.generateToken(newUser)


        // Send response
        res.status(201).json({
            message: 'User registered successfully',
            user: newUser,
            token,
        })


    } catch (error) {
        console.log(error.message)
        res.status(400).json({
            errors: [error.message],
        })
    }
}

module.exports.authMe = async (req, res) => {
  try {
      const user = req.user; // Assuming user is set in the request by authentication middleware

      if (!user) {
          return res.status(404).json({ errors: ["User not found"] });
      }

      // Exclude sensitive information
      user.password = undefined;
      user.verificationToken = undefined;
      user.verificationTokenExpiresAt = undefined;

      res.status(200).json({
          message: "User fetched successfully",
          user,
      });


  } catch (error) {
      
      console.error(error);
      res.status(500).json({ errors: ["Internal server error"] });
  }


}

module.exports.loginController = async (req, res) => {
    try {
        const { email, password } = req.body
        // Validate input
        if (!email || !password) {
            return res.status(400).json({
                errors: ['All fields are required'],
            })
        }

        // Find user by email
        const user = await userModel.findOne({ email })
        if (!user) {
            return res.status(404).json({
                errors: ['User not found'],
            })
        }

        // Check password
        if (!user.comparePassword(password)) {
            return res.status(401).json({
                errors: ['Invalid password'],
            })
        }
        // Generate token
        const token = userModel.generateToken(user)

        // Send response
        res.status(200).json({
            message: 'User logged in successfully',
            user,
            token,
        })

    } catch (error) {
        console.log(error.message)
        res.status(400).json({
            errors: [error.message],
        })
    }
}
```

### `backend\src\controllers\blog.controller.js`

```javascript
const blogModel = require("../models/blog.model");

module.exports.createBlog = async (req, res) => {
    try {
        const blog = new blogModel(req.body);
        await blog.save();
        res.status(201).json({ message: "Blog post added" });
    } catch (err) {
        res.status(500).json({ error: "Error saving blog" });
    }
}


module.exports.getAllBlogs = async (req, res) => {
    const blogs = await blogModel.find().sort({ datePublished: -1 });
    res.json(blogs);
}
```

### `backend\src\controllers\fakeData.controller.js`

```javascript
const fakeDataModel = require("../models/fakeData.model");
const userModel = require("../models/user.model");
const { faker } = require("@faker-js/faker");

exports.generateFakeData = async (req, res) => {
    try {
        const userId = req.user._id;
        console.log(req.headers)
        // Fetch the user to check savedFakeData array
        const user = await userModel.findById(userId);

        if (!user) {
            return res.status(404).json({ errors: ["User not found"] });
        }

        // Check if the user already has 8 fake data entries
        if (user.savedFakeData.length >= 8) {
            return res.status(400).json({ errors: ["Maximum limit of 8 fake data entries reached. Please delete one to create a new one."] });
        }

        // Create new fake data
        const fakeDataInstance = new fakeDataModel({
            userId,
            name: faker.person.fullName(),
            phone: faker.phone.number(),
            address: faker.location.streetAddress(),
            city: faker.location.city(),
            state: faker.location.state(),
            aadhar: faker.string.numeric(12),
        });


        await fakeDataInstance.save();

        // Push the new fake data ID into the user's savedFakeData array
        user.savedFakeData.push(fakeDataInstance._id);
        await user.save();

        res.status(201).json({ message: "Fake data generated", data: fakeDataInstance });
    } catch (error) {
        console.error("Generate Fake Data Error:", error);
        res.status(500).json({ errors: ["Failed to generate fake data"] });
    }
};

exports.getFakeData = async (req, res) => {
    try {
        const userId = req.user._id;
        const data = await fakeDataModel.find({ userId }).sort({ createdAt: -1 });

        res.status(200).json({ fakedata: data });
    } catch (error) {
        console.error("Fetch Fake Data Error:", error);
        res.status(500).json({ error: "Failed to fetch fake data" });
    }
};


exports.deleteFakeData = async (req, res) => {
    try {
        const userId = req.user._id;
        const fakeDataId = req.body.fakeDataId;

        // Find the fake data entry to delete
        const fakeDataEntry = await fakeDataModel.findOneAndDelete({ _id: fakeDataId, userId });

        if (!fakeDataEntry) {
            return res.status(404).json({ errors: ["Fake data not found"] });
        }

        // Remove the deleted fake data ID from the user's savedFakeData array
        await userModel.findByIdAndUpdate(userId, { $pull: { savedFakeData: fakeDataId } });

        res.status(200).json({ message: "Fake data deleted successfully" });

    } catch (error) {
        console.error("Delete Fake Data Error:", error);
        res.status(500).json({ errors: ["Failed to delete fake data"] });
    }
} 
```

### `backend\src\controllers\otp.controller.js`

```javascript
const userModel = require("../models/user.model");
const { sendEmail } = require("../services/email.service");
const generateVerificationCode = require("../utils/generateVerificationCode");

module.exports.verifyOTPController = async (req, res) => {
    try {

        const { email, otp } = req.body;

        // Find user by email
        const user = await userModel.findOne({ email });

        if (!user) {
            return res.status(400).json({ errors: ["User not found"] });
        }

        // Check if OTP matches and is not expired
        if (user.verificationToken !== otp || user.verificationTokenExpiresAt < Date.now()) {
            return res.status(400).json({ errors: ["Invalid or expired OTP"] });
        }

        // Update user as verified
        user.isVerified = true;
        user.verificationToken = undefined;
        user.verificationTokenExpiresAt = undefined;
        await user.save();

        // Generate Token
        const token = userModel.generateToken(user);

        user.password = undefined

        res.status(200).json({
            message: "OTP Verified. User logged in.",
            token,
            user
        });

    } catch (error) {
        res.status(500).json({ errors: [error.message] });
    }
};


module.exports.resendOTPController = async (req, res) => {
    try {
        const { email } = req.body;

        const user = await userModel.findOne({ email });

        if (!user) {
            return res.status(400).json({ errors: ["User not found"] });
        }
        
        
        // Generate new OTP
        const OTP = generateVerificationCode()
        user.isVerified = false; // Reset verification status
        user.verificationToken = OTP;
        user.verificationTokenExpiresAt = Date.now() + 2 * 60 * 1000; // 2 min expiration time
        await user.save();


        // Send OTP to user's email
        const emailContent = `
                <html>
                  <body style="font-family: Arial, sans-serif; color: #333;">
                    <div style="background-color: #f0f0f0; padding: 20px; border-radius: 10px; max-width: 600px; margin: 0 auto;">
                      <h2 style="color: #088395;">Welcome to Our Platform, ${user.userName}!</h2>
                      <h2 style="color: #088395;">Your OTP</h2>
                      <p style="font-size: 18px; font-weight: bold;">Your OTP is: <span style="color: #37B7C3;">${OTP}</span></p>
                      <p>Thank you for signing up with us. We’re excited to have you onboard!</p>
                      <p>Here’s what you can do next:</p>
                      <ul>
                    <li>Explore our platform</li>
                    <li>Set up your profile</li>
                    <li>Start collaborating with others</li>
                      </ul>
                      <p style="color: #37B7C3;">Happy exploring!</p>
                      <p>Best regards,<br/> The Team</p>
                    </div>
                  </body>
                </html>
                  `;
        await sendEmail(email, 'Verify your account', emailContent)


        res.status(200).json({
            message: "OTP resent successfully"
        });

    } catch (error) {
        res.status(500).json({ errors: [error.message] });
    }
}
```

### `backend\src\controllers\sharedApp.controller.js`

```javascript
const SharedApp = require("../models/SharedApp.model");
const userModel = require("../models/user.model");

// Get all shared apps for the logged-in user
const getSharedApps = async (req, res) => {
  try {
    const userId = req.user.id;

    // Find all apps created by the user
    const sharedApps = await SharedApp.find({ userId });

    res.json(sharedApps);
  } catch (err) {
    console.error(err);
    res.status(500).json({ error: "Server error" });
  }
};

// Add a new shared app
const addSharedApp = async (req, res) => {
  try {
    const userId = req.user.id;
    const { appName, sharedData, accessDate, lastAccessed } = req.body;

    // Validate sharedData to only contain booleans
    const validatedSharedData = {
      email: !!sharedData.email,
      password: !!sharedData.password,
      phoneNumber: !!sharedData.phoneNumber,
      location: !!sharedData.location,
      aadhaarNumber: !!sharedData.aadhaarNumber,
    };

    const newApp = new SharedApp({
      userId,
      appName,
      sharedData: validatedSharedData,
      accessDate,
      lastAccessed,
    });

    await newApp.save();

    // Add app reference to user's sharedData array
    await userModel.findByIdAndUpdate(userId, {
      $push: { sharedData: newApp._id },
    });

    res.status(201).json(newApp);
  } catch (err) {
    console.error(err);
    res.status(500).json({ error: "Server error" });
  }
};

// Update a shared app
const updateSharedApp = async (req, res) => {
  try {
    const appId = req.params.id;
    const { appName, sharedData } = req.body;

    const updatedSharedData = {
      email: !!sharedData.email,
      password: !!sharedData.password,
      phoneNumber: !!sharedData.phoneNumber,
      location: !!sharedData.location,
      aadhaarNumber: !!sharedData.aadhaarNumber,
    };

    const updatedApp = await SharedApp.findByIdAndUpdate(
      appId,
      {
        appName,
        sharedData: updatedSharedData,
        lastAccessed: new Date(),
      },
      { new: true }
    );

    if (!updatedApp) {
      return res.status(404).json({ message: "Shared app not found" });
    }

    res.json(updatedApp);
  } catch (err) {
    console.error(err);
    res.status(500).json({ error: "Server error" });
  }
};

// Delete a shared app
const deleteSharedApp = async (req, res) => {
  try {
    const userId = req.user.id;
    const appId = req.params.id;

    const deletedApp = await SharedApp.findByIdAndDelete(appId);

    if (!deletedApp) {
      return res.status(404).json({ message: "Shared app not found" });
    }

    await userModel.findByIdAndUpdate(userId, {
      $pull: { sharedData: appId },
    });

    res.json({ message: "App deleted successfully" });
  } catch (err) {
    console.error(err);
    res.status(500).json({ error: "Server error" });
  }
};

module.exports = {
  getSharedApps,
  addSharedApp,
  updateSharedApp,
  deleteSharedApp,
};

```

### `backend\src\controllers\user.controller.js`

```javascript
const { uploadBufferStream  , deleteImage  } = require("../utils/imageKit");
const userModel = require("../models/user.model");




module.exports.getUserById = async (req, res) => {
    
    try {
        const userId = req.params.id;
        const user = await userModel.findById(userId)
            .select("-password -vaultPassword -__v")
            .populate("savedFakeData")
            .populate("sharedData")
            
            

        if (!user) {
            return res.status(404).json({ errors: ["User not found"] });
        }

        return res.status(200).json({ user });


    } catch (error) {
        console.log(error)
        return res.status(500).json({ errors: [error.message] });
    }
}


module.exports.updateUserProfile = async (req, res) => {
    try {
      const user = await userModel.findById(req.user.id);
      if (!user) return res.status(404).json({ message: "User not found" });
  
      const updateFields = {
        username: req.body.username || user.username,
        phoneNumber: req.body.phoneNumber || user.phoneNumber,
      };
  
      // Handle profile picture
      if (req.file) {
        const DEFAULT_PROFILE_URL = "https://cdn.vectorstock.com/i/1000v/92/16/default-profile-picture-avatar-user-icon-vector-46389216.jpg";
  
        if (user.profilePicture !== DEFAULT_PROFILE_URL && user.imageKitFileId) { // for 2nd or more time update 
          await deleteImage(user.imageKitFileId);
          console.log("Previous image deleted");
        }
  
        const uploadResult = await uploadBufferStream(req.file.buffer);
        updateFields.profilePicture = uploadResult.url;
        updateFields.imageKitFileId = uploadResult.fileId;
      }

  
    const updatedUser = await userModel.findByIdAndUpdate(req.user.id, updateFields, { new: true })
      .select("-password -vaultPassword -__v")
      .populate("savedFakeData")
      .populate("sharedData");
      //AGGRIGATING ALL THE FIELDS 

      res.status(200).json(updatedUser);
    } catch (error) {
      console.error("Update failed:", error);
      res.status(500).json({ message: "Profile update failed" });
    }
  };

```

### `backend\src\controllers\vault.controller.js`

```javascript

const userModel = require("../models/user.model");
const VaultItem = require("../models/vaultitems.model");
const { encryptField, decryptField } = require("../utils/cryptoUtil");

module.exports.getVault = async (req, res) => {
    try {
        const userId = req.user._id;
        const items = await VaultItem.find({ userId });

        const decryptedItems = items.map(item => ({
            _id: item._id,
            title: decryptField(userId, item.encryptedData.title),
            username: decryptField(userId, item.encryptedData.username),
            password: decryptField(userId, item.encryptedData.password),
            createdAt: item.createdAt,
        }));

        return res.status(200).json(decryptedItems);
    } catch (err) {
        console.error("Vault Get Error:", err);
        return res.status(500).json({ errors: [err.message] });
    }
};

module.exports.addVault = async (req, res) => {
    try {
        const { title, username, password } = req.body;
        const userId = req.user._id;

        if (!title || !username || !password) {
            return res.status(400).json({ errors: ["All fields are required."] });
        }

        const newItem = new VaultItem({
            userId,
            encryptedData: {
                title: encryptField(userId, title),
                username: encryptField(userId, username),
                password: encryptField(userId, password),
            },
        });

        await newItem.save();
        return res.status(201).json({ message: "Vault item encrypted and saved!" });

    } catch (error) {
        return res.status(500).json({ errors: ["Internal server error"] });
    }
};

module.exports.updateVault = async (req, res) => {
    try {
        const userId = req.user._id;
        const vaultId = req.params.id;
        const { title, username, password } = req.body;

        const vaultItem = await VaultItem.findOne({ _id: vaultId, userId });
        if (!vaultItem) {
            return res.status(404).json({ errors: ["Vault item not found"] });
        }

        if (title) vaultItem.encryptedData.title = encryptField(userId, title);
        if (username) vaultItem.encryptedData.username = encryptField(userId, username);
        if (password) vaultItem.encryptedData.password = encryptField(userId, password);

        await vaultItem.save();
        return res.status(200).json({ message: "Vault item updated successfully" });

    } catch (err) {
        console.error(err);
        return res.status(500).json({ error: "Something went wrong!" });
    }
};

module.exports.deleteVault = async (req, res) => {
    try {
        const { id } = req.params;
        const userId = req.user._id;

        const vaultItem = await VaultItem.findOneAndDelete({ _id: id, userId });
        if (!vaultItem) {
            return res.status(404).json({ errors: ["Vault item not found"] });
        }

        return res.status(200).json({ message: "Vault item deleted successfully" });

    } catch (error) {
        return res.status(500).json({ errors: ["Internal server error"] });
    }
};

module.exports.createVaultPassword = async (req, res) => {
    try {
        const { password } = req.body;
        const user = await userModel.findById(req.user._id);

        if (user.vaultPassword) {
            return res.status(400).json({ errors: ["Vault password already set"] });
        }

        if (!password) {
            return res.status(400).json({ errors: ["Password is required"] });
        }


        const vaultPassword = userModel.generateHashedPassword(password);
        const updateduser = await userModel.findByIdAndUpdate(user, {
            vaultPassword: vaultPassword,
        }, { new: true });

        if (!updateduser) {
            return res.status(404).json({ errors: ["User not found"] });
        }


        return res.status(200).json({ message: "Vault password set successfully" });

    } catch (error) {

    }
}

module.exports.openVault = async (req, res) => {
    try {
        const password = req.body.password;
        const user = await userModel.findById(req.user._id);
        

        if (!password) {
            return res.status(400).json({ errors: ["Password is required"] })



        }
        const isMatch = await user.compareVaultPassword(password);

        if (!isMatch) {
            return res.status(400).json({ errors: ["Incorrect password"] });
        }

        res.status(200).json({ message: "Vault opened successfully" });

    } catch (error) {
        console.error("Error opening vault:", error);
        return res.status(500).json({ errors: ["Internal server error"] });
    }

}


module.exports.isVaultInitialized = async (req, res) => {
    try {
        const user = await userModel.findById(req.user._id).select("vaultPassword");

        if (!user) {
            return res.status(404).json({ errors: ["User not found"] });
        }

        const isInitialized = !!user.vaultPassword;
        return res.status(200).json({ isInitialized });

    } catch (error) {
        console.error("Error checking vault initialization:", error);
        return res.status(500).json({ errors: ["Internal server error"] });
    }
}
```

### `backend\src\db\db.js`

```javascript
const mongoose = require('mongoose');
const config = require('../config/config');


const connectDB = () => {
    mongoose.connect(config.MONGODB_URI)
    .then(() => {
        console.log('MongoDB connected')
    })
    .catch((err) => {
        console.log('MongoDB connection error:', err.message)
    })
}


module.exports = connectDB;
```

### `backend\src\middleWare\Multer.js`

```javascript
const multer = require("multer");
const storage = multer.memoryStorage();
const upload = multer({ storage });

module.exports = upload;

```

### `backend\src\middleWare\userMiddleware.js`

```javascript
const userModel = require("../models/user.model");
module.exports.authUser = async(req, res, next) => {
    try {
        const token = req.headers["authorization"]?.split(" ")[1];
        if (!token) {
            return res.status(401).json({ errors: ["Unauthorized"] });
        }

        // Verify token and extract user data
        const decoded = await userModel.validateToken(token);

        if (!decoded) {
            return res.status(401).json({ errors: ["Unauthorized"] });
        }

        // Find user by ID
        const user = await userModel.findById(decoded.id).select("-password -verificationToken -verificationTokenExpiresAt");

        if (!user) {
            return res.status(401).json({ errors: ["Unauthorized"] });
        }

        req.user = user; // Attach user to request object

        next(); // Proceed to the next middleware or route handler



        
    } catch (error) {
        
        console.error(error);
        res.status(500).json({ errors: ["Internal server error"] });

    }

}
```

### `backend\src\models\blog.model.js`

```javascript
const mongoose = require("mongoose");

const blogSchema = new mongoose.Schema({
    title: String,
    content: String,
    source: String,
    image: String,
    datePublished: Date,
    tags: [String],
});


const blogModel = mongoose.model("Blog", blogSchema);

module.exports = blogModel
```

### `backend\src\models\BreachAlert.model.js`

```javascript
// models/breaches.model.js
const mongoose = require('mongoose');

const breachAlertSchema = new mongoose.Schema({
    email: { type: String, required: true, unique: true },
    breaches: [
      {
        source: { type: String },
        date: { type: Date },
        type: { type: String },
        details: { type: String }
      }
    ],
    createdAt: { type: Date, default: Date.now }
  });


const breachAlertModel = mongoose.model('BreachAlert', breachAlertSchema);
module.exports = breachAlertModel;

```

### `backend\src\models\fakeData.model.js`

```javascript
const mongoose = require("mongoose");

const FakeDataSchema = new mongoose.Schema({
  userId: {
    type: mongoose.Schema.Types.ObjectId,
    ref: "User",
    required: true,
  },
  name: String,
  phone: String,
  address: String,
  city: String,
  state: String,
  aadhar: String,
  createdAt: {
    type: Date,
    default: Date.now,
  },
});

const fakeDataModel = mongoose.model("FakeData", FakeDataSchema);
module.exports = fakeDataModel;

```

### `backend\src\models\SharedApp.model.js`

```javascript
const mongoose = require("mongoose");

const sharedDataSchema = new mongoose.Schema(
  {
    email: {
      type: Boolean,
      default: false,
    },
    password: {
      type: Boolean,
      default: false,
    },
    phoneNumber: {
      type: Boolean,
      default: false,
    },
    location: {
      type: Boolean,
      default: false,
    },
    aadhaarNumber: {
      type: Boolean,
      default: false,
    },
  },
  { _id: false } // No separate _id for nested sharedData object
);

const sharedAppSchema = new mongoose.Schema(
  {
    userId: {
      type: mongoose.Schema.Types.ObjectId,
      ref: "User",
      required: true,
    },
    appName: {
      type: String,
      required: true,
    },
    sharedData: {
      type: sharedDataSchema,
      default: () => ({}),
    },
    accessDate: {
      type: Date,
      default: Date.now,
    },
    lastAccessed: {
      type: Date,
    },
  },
  { timestamps: true }
);

module.exports = mongoose.model("SharedApp", sharedAppSchema);

```

### `backend\src\models\user.model.js`

```javascript
const mongoose = require('mongoose');
const config = require('../config/config');
const bcrypt = require('bcrypt');
const jwt = require('jsonwebtoken');
require("./BreachAlert.model");


const userSchema = new mongoose.Schema({
    username: {
        type: String,
        required: true,
        trim: true,
    },
    email: {
        type: String,
        required: true,
        unique: true,
        trim: true,
    },
    password: {
        type: String,
        required: true,
    },
    vaultPassword: {
        type: String,
        default: null,
    },
    phoneNumber: {
        type: String,
        required: true,
        unique: true,
    },
    profilePicture: {
        type: String,
        default: "https://cdn.vectorstock.com/i/1000v/92/16/default-profile-picture-avatar-user-icon-vector-46389216.jpg",
    },

    isVerified: {
        type: Boolean,
        default: false,
    },
    resetPasswordToken: {
        type: String,
    },
    resetPasswordTokenExpiresAt: {
        type: Date,
    },
    verificationToken: {
        type: String,
    },
    verificationTokenExpiresAt: {
        type: Date,
    },
    sharedData: [{
        type: mongoose.Schema.Types.ObjectId,
        ref: 'SharedApp',
    }],
    savedFakeData: [{
        type: mongoose.Schema.Types.ObjectId,
        ref: 'FakeData',
    }],
    imageKitFileId: {
        type: String,
        default: null,
    },


}, { timestamps: true });

userSchema.statics.generateHashedPassword = (password) => {
    return bcrypt.hashSync(password, 10);
};
userSchema.methods.comparePassword = function (password) {
    return bcrypt.compareSync(password, this.password);
};
userSchema.methods.compareVaultPassword = function (password) {
    return bcrypt.compareSync(password, this.vaultPassword);
};

userSchema.statics.generateToken = function (user) {
    return jwt.sign({ id: user._id, email: user.email }, config.JWT_SECRET);
};
userSchema.statics.validateToken = function (token) {
    return jwt.verify(token, config.JWT_SECRET, (err, decoded) => {
        if (err) {
            return false;
        }
        return decoded;
    });
};


const userModel = mongoose.model('User', userSchema);

module.exports = userModel;
```

### `backend\src\models\vaultitems.model.js`

```javascript
const mongoose = require('mongoose');

const VaultItemSchema = new mongoose.Schema({
    userId: {
      type: mongoose.Schema.Types.ObjectId,
      ref: 'User',
      required: true,
    },
    encryptedData: {
      title: {
        data: String,
        iv: String,
        tag: String,
      },
      username: {
        data: String,
        iv: String,
        tag: String,
      },
      password: {
        data: String,
        iv: String,
        tag: String,
      },
    },
    createdAt: { type: Date, default: Date.now },

  });


const VaultItem = mongoose.model('VaultItem', VaultItemSchema);


module.exports = VaultItem;
```

### `backend\src\routes\auth.routes.js`

```javascript
const router = require("express").Router();
const authController = require("../controllers/auth.controller");
const { authUser } = require("../middleWare/userMiddleware");

//routes
router.post("/register" , authController.registerController);
router.post("/login" , authController.loginController);
router.get("/authme" , authUser ,  authController.authMe)



module.exports = router;
```

### `backend\src\routes\blog.routes.js`

```javascript
const express = require("express");
const blogController = require("../controllers/blog.controller.js");
const router = express.Router();

// Add blog post
router.post("/add",blogController.createBlog); 

// Get all posts
router.get("/",blogController.getAllBlogs);

module.exports = router;

```

### `backend\src\routes\breach.routes.js`

```javascript
// routes/breach.routes.js
const express = require("express");
const router = express.Router();
const breachController = require("../controllers/breach.controller");
const { authUser } = require("../middleWare/userMiddleware");

router.get("/:email", authUser, breachController.getBreachesByEmail);

module.exports = router;

```

### `backend\src\routes\fakeData.routes.js`

```javascript
// routes/fakeData.routes.js
const express = require("express");
const router = express.Router();
const fakeDataController = require("../controllers/fakeData.controller");
const { authUser } = require("../middleWare/userMiddleware");


// POST - Generate new fake data
router.post("/generate", authUser, fakeDataController.generateFakeData);

// GET - Get all fake data entries for logged-in user
router.get("/all", authUser, fakeDataController.getFakeData);

// DELETE - Delete a specific fake data entry by ID
router.post("/delete", authUser, fakeDataController.deleteFakeData);

module.exports = router;

```

### `backend\src\routes\otp.routes.js`

```javascript
const router = require("express").Router();
const otpControllers = require("../controllers/otp.controller");

//routes
router.post("/verifyotp" , otpControllers.verifyOTPController )
router.post("/resendotp" , otpControllers.resendOTPController )
// router.get("/forgotpassword" , otpControllers.forgotPasswordController )



module.exports = router;
```

### `backend\src\routes\sharedData.routes.js`

```javascript
const express = require("express");
const {
    getSharedApps,
    addSharedApp,
    updateSharedApp,
    deleteSharedApp,
} = require("../controllers/sharedApp.controller");
const { authUser } = require("../middleWare/userMiddleware");

const router = express.Router();

router.get("/", authUser, getSharedApps);
router.post("/", authUser, addSharedApp);
router.put("/:id", authUser, updateSharedApp);
router.delete("/:id", authUser, deleteSharedApp);

module.exports = router;

```

### `backend\src\routes\user.routes.js`

```javascript
const router = require("express").Router();
const userControllers = require("../controllers/user.controller");
const upload = require("../middleWare/Multer");
const { authUser } = require("../middleWare/userMiddleware");


router.get("/:id" ,authUser ,  userControllers.getUserById);
router.put("/update", authUser, upload.single("profilePicture"), userControllers.updateUserProfile);


module.exports = router;
```

### `backend\src\routes\vault.routes.js`

```javascript
const router = require('express').Router();
const { authUser } = require('../middleWare/userMiddleware');
const vaultController = require('../controllers/vault.controller');

// Route to get all vaults for a user
router.get('/getall', authUser, vaultController.getVault);
router.post('/add', authUser, vaultController.addVault);
router.put('/update/:id', authUser, vaultController.updateVault);
router.delete('/delete/:id', authUser, vaultController.deleteVault);
router.post('/createvaultPassword', authUser, vaultController.createVaultPassword);
router.post('/openvault', authUser, vaultController.openVault);
router.get("/isInitialized", authUser, vaultController.isVaultInitialized);

module.exports = router;
```

### `backend\src\services\auth.service.js`

```javascript
const userModel = require("../models/user.model")

module.exports.createUser = async ({ firstName, lastName, email, password, phoneNumber , OTP }) => {
    // Check if user already exists
    const userExists = await userModel.findOne({ email })
    if (userExists) {
        console.log(userExists)
        throw new Error('User already exists')
    }
    // Hash password
    const hashedPassword = userModel.generateHashedPassword(password)

    const username = firstName.trim() + ` ${lastName.trim()}`


    // Create new user
    const newUser = await userModel.create({
        username,
        email,
        password: hashedPassword,
        phoneNumber,
        verificationToken: OTP,
        verificationTokenExpiresAt: Date.now() + 2 * 60 * 1000, // 2 min expiration time
    })


    if(!newUser) {
        throw new Error('User creation failed')
    }

    // delete password from user object
    newUser.password = undefined

    return newUser


}
```

### `backend\src\services\email.service.js`

```javascript
const nodeMailer = require('nodemailer');
const config = require('../config/config');

const transporter = nodeMailer.createTransport({
    service: 'gmail',
    auth:{
        user : config.EMAIL_USER , 
        pass : config.EMAIL_PASS
    }

})
// Email send function for HTML content
const sendEmail = async (to, subject, htmlContent) => {
    try {
      const info = await transporter.sendMail({
        from: process.env.EMAIL_USER, // Sender address
        to, // Receiver address
        subject, // Subject line
        html: htmlContent, // HTML content
      });
  
      console.log("Email sent: " + info.response);
    } catch (error) {
      console.error("Error sending email: ", error);
    }
  };
  
  module.exports = { sendEmail };
```

### `backend\src\utils\cryptoUtil.js`

```javascript
const crypto = require('crypto');
const config = require('../config/config');
const VAULT_SECRET_KEY = config.VAULT_SECRET_KEY;

if (!VAULT_SECRET_KEY || VAULT_SECRET_KEY.length < 32) {
  throw new Error("VAULT_SECRET_KEY must be at least 32 characters long");
}

function generateEncryptionKey(userId) {
  return crypto.createHash("sha256").update(VAULT_SECRET_KEY + userId).digest(); // 32 bytes
}

function encryptField(userId, text) {
  const key = generateEncryptionKey(userId);
  const iv = crypto.randomBytes(12);
  const cipher = crypto.createCipheriv("aes-256-gcm", key, iv);
  const encrypted = Buffer.concat([cipher.update(text, "utf8"), cipher.final()]);
  const tag = cipher.getAuthTag();
  return {
    data: encrypted.toString("base64"),
    iv: iv.toString("base64"),
    tag: tag.toString("base64"),
  };
}

function decryptField(userId, encryptedField) {
  const key = generateEncryptionKey(userId);
  const { data, iv, tag } = encryptedField;
  const decipher = crypto.createDecipheriv("aes-256-gcm", key, Buffer.from(iv, "base64"));
  decipher.setAuthTag(Buffer.from(tag, "base64"));
  const decrypted = Buffer.concat([
    decipher.update(Buffer.from(data, "base64")),
    decipher.final(),
  ]);
  return decrypted.toString("utf8");
}

module.exports = {
  generateEncryptionKey,
  encryptField,
  decryptField,
};

```

### `backend\src\utils\fetchPrivacyNews.js`

```javascript
const cron = require("node-cron");
const axios = require("axios");
const blogModel = require("../models/blog.model");
const { NEWS_API_KEY } = require("../config/config");

const fetchAndSaveNews = async () => {
  try {
    const res = await axios.get(`https://newsapi.org/v2/everything?q=privacy&sortBy=publishedAt&pageSize=1&apiKey=${NEWS_API_KEY}`);
    const article = res.data.articles[0];

    const blog = new blogModel({
      title: article.title,
      content: article.description,
      source: article.url,
      image: article.urlToImage,
      datePublished: new Date(article.publishedAt),
      tags: ["privacy", "news"],
    });

    await blog.save();
    console.log("✅ blogModel post saved!");
  } catch (error) {
    console.error("❌ Error fetching/saving blog:", error.message);
  }
};

// Schedule: every day at 9 AM
cron.schedule("0 9 * * *", fetchAndSaveNews);


```

### `backend\src\utils\generateVerificationCode.js`

```javascript
const generateVerificationCode = () => {
    const code = Math.floor(100000 + Math.random() * 900000).toString(); // Generates a 5-digit random number
    return code;
}
module.exports = generateVerificationCode;
```

### `backend\src\utils\imageKit.js`

```javascript
const ImageKit = require("imagekit");
const { Readable } = require("stream");
const config = require("../config/config");
const mongoose = require("mongoose");

const imagekit = new ImageKit({
  publicKey: config.IMAGEKIT_PUBLIC_KEY,
  privateKey: config.IMAGEKIT_PRIVATE_KEY,
  urlEndpoint: config.IMAGEKIT_URL_ENDPOINT,
});

// Upload buffer stream
const uploadBufferStream = async (fileBuffer) => {
  const result = await imagekit.upload({
    file: Readable.from(fileBuffer),
    fileName: new mongoose.Types.ObjectId().toString(),
    isPublished: true,
    folder: "/PRIVGUARD",
  });
  return result;
};

// Delete file by fileId
const deleteImage = async (fileId) => {
  try {
    await imagekit.deleteFile(fileId);
    console.log("Deleted image from ImageKit:", fileId);
  } catch (err) {
    console.error("Error deleting file from ImageKit:", err.message);
  }
};

module.exports = {
  uploadBufferStream,
  deleteImage,
};

```

### `frontend\.gitignore`

```
# Logs
logs
*.log
npm-debug.log*
yarn-debug.log*
yarn-error.log*
pnpm-debug.log*
lerna-debug.log*

node_modules
dist
dist-ssr
*.local

# Editor directories and files
.vscode/*
!.vscode/extensions.json
.idea
.DS_Store
*.suo
*.ntvs*
*.njsproj
*.sln
*.sw?

```

### `frontend\eslint.config.js`

```javascript
import js from '@eslint/js'
import globals from 'globals'
import reactHooks from 'eslint-plugin-react-hooks'
import reactRefresh from 'eslint-plugin-react-refresh'

export default [
  { ignores: ['dist'] },
  {
    files: ['**/*.{js,jsx}'],
    languageOptions: {
      ecmaVersion: 2020,
      globals: globals.browser,
      parserOptions: {
        ecmaVersion: 'latest',
        ecmaFeatures: { jsx: true },
        sourceType: 'module',
      },
    },
    plugins: {
      'react-hooks': reactHooks,
      'react-refresh': reactRefresh,
    },
    rules: {
      ...js.configs.recommended.rules,
      ...reactHooks.configs.recommended.rules,
      'no-unused-vars': ['error', { varsIgnorePattern: '^[A-Z_]' }],
      'react-refresh/only-export-components': [
        'warn',
        { allowConstantExport: true },
      ],
    },
  },
]

```

### `frontend\index.html`

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <link rel="icon" type="image/svg+xml" href="./src/assets/PrevGuard.svg" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>PrivGuard</title>
  </head>
  <body>
    <div id="root"></div>
    <script type="module" src="/src/main.jsx"></script>
  </body>
</html>

```

### `frontend\package-lock.json`

```json
{
  "name": "frontend",
  "version": "0.0.0",
  "lockfileVersion": 3,
  "requires": true,
  "packages": {
    "": {
      "name": "frontend",
      "version": "0.0.0",
      "dependencies": {
        "@faker-js/faker": "^9.7.0",
        "@reduxjs/toolkit": "^2.6.1",
        "argon2-browser": "^1.18.0",
        "axios": "^1.8.4",
        "crypto-js": "^4.2.0",
        "dompurify": "^3.2.5",
        "framer-motion": "^12.6.5",
        "lodash": "^4.17.21",
        "lucide-react": "^0.486.0",
        "react": "^19.0.0",
        "react-circular-progressbar": "^2.2.0",
        "react-dom": "^19.0.0",
        "react-icons": "^5.5.0",
        "react-redux": "^9.2.0",
        "react-router-dom": "^7.4.1",
        "react-toastify": "^11.0.5"
      },
      "devDependencies": {
        "@eslint/js": "^9.21.0",
        "@types/react": "^19.0.10",
        "@types/react-dom": "^19.0.4",
        "@vitejs/plugin-react": "^4.3.4",
        "autoprefixer": "^10.4.21",
        "eslint": "^9.21.0",
        "eslint-plugin-react-hooks": "^5.1.0",
        "eslint-plugin-react-refresh": "^0.4.19",
        "globals": "^15.15.0",
        "postcss": "^8.5.3",
        "tailwindcss": "^3.4.17",
        "vite": "^6.2.0"
      }
    },
    "node_modules/@alloc/quick-lru": {
      "version": "5.2.0",
      "resolved": "https://registry.npmjs.org/@alloc/quick-lru/-/quick-lru-5.2.0.tgz",
      "integrity": "sha512-UrcABB+4bUrFABwbluTIBErXwvbsU/V7TZWfmbgJfbkwiBuziS9gxdODUyuiecfdGQ85jglMW6juS3+z5TsKLw==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=10"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/@ampproject/remapping": {
      "version": "2.3.0",
      "resolved": "https://registry.npmjs.org/@ampproject/remapping/-/remapping-2.3.0.tgz",
      "integrity": "sha512-30iZtAPgz+LTIYoeivqYo853f02jBYSd5uGnGpkFV0M3xOt9aN73erkgYAmZU43x4VfqcnLxW9Kpg3R5LC4YYw==",
      "dev": true,
      "license": "Apache-2.0",
      "dependencies": {
        "@jridgewell/gen-mapping": "^0.3.5",
        "@jridgewell/trace-mapping": "^0.3.24"
      },
      "engines": {
        "node": ">=6.0.0"
      }
    },
    "node_modules/@babel/code-frame": {
      "version": "7.26.2",
      "resolved": "https://registry.npmjs.org/@babel/code-frame/-/code-frame-7.26.2.tgz",
      "integrity": "sha512-RJlIHRueQgwWitWgF8OdFYGZX328Ax5BCemNGlqHfplnRT9ESi8JkFlvaVYbS+UubVY6dpv87Fs2u5M29iNFVQ==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@babel/helper-validator-identifier": "^7.25.9",
        "js-tokens": "^4.0.0",
        "picocolors": "^1.0.0"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/compat-data": {
      "version": "7.26.8",
      "resolved": "https://registry.npmjs.org/@babel/compat-data/-/compat-data-7.26.8.tgz",
      "integrity": "sha512-oH5UPLMWR3L2wEFLnFJ1TZXqHufiTKAiLfqw5zkhS4dKXLJ10yVztfil/twG8EDTA4F/tvVNw9nOl4ZMslB8rQ==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/core": {
      "version": "7.26.10",
      "resolved": "https://registry.npmjs.org/@babel/core/-/core-7.26.10.tgz",
      "integrity": "sha512-vMqyb7XCDMPvJFFOaT9kxtiRh42GwlZEg1/uIgtZshS5a/8OaduUfCi7kynKgc3Tw/6Uo2D+db9qBttghhmxwQ==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@ampproject/remapping": "^2.2.0",
        "@babel/code-frame": "^7.26.2",
        "@babel/generator": "^7.26.10",
        "@babel/helper-compilation-targets": "^7.26.5",
        "@babel/helper-module-transforms": "^7.26.0",
        "@babel/helpers": "^7.26.10",
        "@babel/parser": "^7.26.10",
        "@babel/template": "^7.26.9",
        "@babel/traverse": "^7.26.10",
        "@babel/types": "^7.26.10",
        "convert-source-map": "^2.0.0",
        "debug": "^4.1.0",
        "gensync": "^1.0.0-beta.2",
        "json5": "^2.2.3",
        "semver": "^6.3.1"
      },
      "engines": {
        "node": ">=6.9.0"
      },
      "funding": {
        "type": "opencollective",
        "url": "https://opencollective.com/babel"
      }
    },
    "node_modules/@babel/generator": {
      "version": "7.27.0",
      "resolved": "https://registry.npmjs.org/@babel/generator/-/generator-7.27.0.tgz",
      "integrity": "sha512-VybsKvpiN1gU1sdMZIp7FcqphVVKEwcuj02x73uvcHE0PTihx1nlBcowYWhDwjpoAXRv43+gDzyggGnn1XZhVw==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@babel/parser": "^7.27.0",
        "@babel/types": "^7.27.0",
        "@jridgewell/gen-mapping": "^0.3.5",
        "@jridgewell/trace-mapping": "^0.3.25",
        "jsesc": "^3.0.2"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/helper-compilation-targets": {
      "version": "7.27.0",
      "resolved": "https://registry.npmjs.org/@babel/helper-compilation-targets/-/helper-compilation-targets-7.27.0.tgz",
      "integrity": "sha512-LVk7fbXml0H2xH34dFzKQ7TDZ2G4/rVTOrq9V+icbbadjbVxxeFeDsNHv2SrZeWoA+6ZiTyWYWtScEIW07EAcA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@babel/compat-data": "^7.26.8",
        "@babel/helper-validator-option": "^7.25.9",
        "browserslist": "^4.24.0",
        "lru-cache": "^5.1.1",
        "semver": "^6.3.1"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/helper-module-imports": {
      "version": "7.25.9",
      "resolved": "https://registry.npmjs.org/@babel/helper-module-imports/-/helper-module-imports-7.25.9.tgz",
      "integrity": "sha512-tnUA4RsrmflIM6W6RFTLFSXITtl0wKjgpnLgXyowocVPrbYrLUXSBXDgTs8BlbmIzIdlBySRQjINYs2BAkiLtw==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@babel/traverse": "^7.25.9",
        "@babel/types": "^7.25.9"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/helper-module-transforms": {
      "version": "7.26.0",
      "resolved": "https://registry.npmjs.org/@babel/helper-module-transforms/-/helper-module-transforms-7.26.0.tgz",
      "integrity": "sha512-xO+xu6B5K2czEnQye6BHA7DolFFmS3LB7stHZFaOLb1pAwO1HWLS8fXA+eh0A2yIvltPVmx3eNNDBJA2SLHXFw==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@babel/helper-module-imports": "^7.25.9",
        "@babel/helper-validator-identifier": "^7.25.9",
        "@babel/traverse": "^7.25.9"
      },
      "engines": {
        "node": ">=6.9.0"
      },
      "peerDependencies": {
        "@babel/core": "^7.0.0"
      }
    },
    "node_modules/@babel/helper-plugin-utils": {
      "version": "7.26.5",
      "resolved": "https://registry.npmjs.org/@babel/helper-plugin-utils/-/helper-plugin-utils-7.26.5.tgz",
      "integrity": "sha512-RS+jZcRdZdRFzMyr+wcsaqOmld1/EqTghfaBGQQd/WnRdzdlvSZ//kF7U8VQTxf1ynZ4cjUcYgjVGx13ewNPMg==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/helper-string-parser": {
      "version": "7.25.9",
      "resolved": "https://registry.npmjs.org/@babel/helper-string-parser/-/helper-string-parser-7.25.9.tgz",
      "integrity": "sha512-4A/SCr/2KLd5jrtOMFzaKjVtAei3+2r/NChoBNoZ3EyP/+GlhoaEGoWOZUmFmoITP7zOJyHIMm+DYRd8o3PvHA==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/helper-validator-identifier": {
      "version": "7.25.9",
      "resolved": "https://registry.npmjs.org/@babel/helper-validator-identifier/-/helper-validator-identifier-7.25.9.tgz",
      "integrity": "sha512-Ed61U6XJc3CVRfkERJWDz4dJwKe7iLmmJsbOGu9wSloNSFttHV0I8g6UAgb7qnK5ly5bGLPd4oXZlxCdANBOWQ==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/helper-validator-option": {
      "version": "7.25.9",
      "resolved": "https://registry.npmjs.org/@babel/helper-validator-option/-/helper-validator-option-7.25.9.tgz",
      "integrity": "sha512-e/zv1co8pp55dNdEcCynfj9X7nyUKUXoUEwfXqaZt0omVOmDe9oOTdKStH4GmAw6zxMFs50ZayuMfHDKlO7Tfw==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/helpers": {
      "version": "7.27.0",
      "resolved": "https://registry.npmjs.org/@babel/helpers/-/helpers-7.27.0.tgz",
      "integrity": "sha512-U5eyP/CTFPuNE3qk+WZMxFkp/4zUzdceQlfzf7DdGdhp+Fezd7HD+i8Y24ZuTMKX3wQBld449jijbGq6OdGNQg==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@babel/template": "^7.27.0",
        "@babel/types": "^7.27.0"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/parser": {
      "version": "7.27.0",
      "resolved": "https://registry.npmjs.org/@babel/parser/-/parser-7.27.0.tgz",
      "integrity": "sha512-iaepho73/2Pz7w2eMS0Q5f83+0RKI7i4xmiYeBmDzfRVbQtTOG7Ts0S4HzJVsTMGI9keU8rNfuZr8DKfSt7Yyg==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@babel/types": "^7.27.0"
      },
      "bin": {
        "parser": "bin/babel-parser.js"
      },
      "engines": {
        "node": ">=6.0.0"
      }
    },
    "node_modules/@babel/plugin-transform-react-jsx-self": {
      "version": "7.25.9",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-react-jsx-self/-/plugin-transform-react-jsx-self-7.25.9.tgz",
      "integrity": "sha512-y8quW6p0WHkEhmErnfe58r7x0A70uKphQm8Sp8cV7tjNQwK56sNVK0M73LK3WuYmsuyrftut4xAkjjgU0twaMg==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@babel/helper-plugin-utils": "^7.25.9"
      },
      "engines": {
        "node": ">=6.9.0"
      },
      "peerDependencies": {
        "@babel/core": "^7.0.0-0"
      }
    },
    "node_modules/@babel/plugin-transform-react-jsx-source": {
      "version": "7.25.9",
      "resolved": "https://registry.npmjs.org/@babel/plugin-transform-react-jsx-source/-/plugin-transform-react-jsx-source-7.25.9.tgz",
      "integrity": "sha512-+iqjT8xmXhhYv4/uiYd8FNQsraMFZIfxVSqxxVSZP0WbbSAWvBXAul0m/zu+7Vv4O/3WtApy9pmaTMiumEZgfg==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@babel/helper-plugin-utils": "^7.25.9"
      },
      "engines": {
        "node": ">=6.9.0"
      },
      "peerDependencies": {
        "@babel/core": "^7.0.0-0"
      }
    },
    "node_modules/@babel/template": {
      "version": "7.27.0",
      "resolved": "https://registry.npmjs.org/@babel/template/-/template-7.27.0.tgz",
      "integrity": "sha512-2ncevenBqXI6qRMukPlXwHKHchC7RyMuu4xv5JBXRfOGVcTy1mXCD12qrp7Jsoxll1EV3+9sE4GugBVRjT2jFA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@babel/code-frame": "^7.26.2",
        "@babel/parser": "^7.27.0",
        "@babel/types": "^7.27.0"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/traverse": {
      "version": "7.27.0",
      "resolved": "https://registry.npmjs.org/@babel/traverse/-/traverse-7.27.0.tgz",
      "integrity": "sha512-19lYZFzYVQkkHkl4Cy4WrAVcqBkgvV2YM2TU3xG6DIwO7O3ecbDPfW3yM3bjAGcqcQHi+CCtjMR3dIEHxsd6bA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@babel/code-frame": "^7.26.2",
        "@babel/generator": "^7.27.0",
        "@babel/parser": "^7.27.0",
        "@babel/template": "^7.27.0",
        "@babel/types": "^7.27.0",
        "debug": "^4.3.1",
        "globals": "^11.1.0"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@babel/traverse/node_modules/globals": {
      "version": "11.12.0",
      "resolved": "https://registry.npmjs.org/globals/-/globals-11.12.0.tgz",
      "integrity": "sha512-WOBp/EEGUiIsJSp7wcv/y6MO+lV9UoncWqxuFfm8eBwzWNgyfBd6Gz+IeKQ9jCmyhoH99g15M3T+QaVHFjizVA==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/@babel/types": {
      "version": "7.27.0",
      "resolved": "https://registry.npmjs.org/@babel/types/-/types-7.27.0.tgz",
      "integrity": "sha512-H45s8fVLYjbhFH62dIJ3WtmJ6RSPt/3DRO0ZcT2SUiYiQyz3BLVb9ADEnLl91m74aQPS3AzzeajZHYOalWe3bg==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@babel/helper-string-parser": "^7.25.9",
        "@babel/helper-validator-identifier": "^7.25.9"
      },
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/@esbuild/aix-ppc64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/aix-ppc64/-/aix-ppc64-0.25.2.tgz",
      "integrity": "sha512-wCIboOL2yXZym2cgm6mlA742s9QeJ8DjGVaL39dLN4rRwrOgOyYSnOaFPhKZGLb2ngj4EyfAFjsNJwPXZvseag==",
      "cpu": [
        "ppc64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "aix"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/android-arm": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/android-arm/-/android-arm-0.25.2.tgz",
      "integrity": "sha512-NQhH7jFstVY5x8CKbcfa166GoV0EFkaPkCKBQkdPJFvo5u+nGXLEH/ooniLb3QI8Fk58YAx7nsPLozUWfCBOJA==",
      "cpu": [
        "arm"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "android"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/android-arm64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/android-arm64/-/android-arm64-0.25.2.tgz",
      "integrity": "sha512-5ZAX5xOmTligeBaeNEPnPaeEuah53Id2tX4c2CVP3JaROTH+j4fnfHCkr1PjXMd78hMst+TlkfKcW/DlTq0i4w==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "android"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/android-x64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/android-x64/-/android-x64-0.25.2.tgz",
      "integrity": "sha512-Ffcx+nnma8Sge4jzddPHCZVRvIfQ0kMsUsCMcJRHkGJ1cDmhe4SsrYIjLUKn1xpHZybmOqCWwB0zQvsjdEHtkg==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "android"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/darwin-arm64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/darwin-arm64/-/darwin-arm64-0.25.2.tgz",
      "integrity": "sha512-MpM6LUVTXAzOvN4KbjzU/q5smzryuoNjlriAIx+06RpecwCkL9JpenNzpKd2YMzLJFOdPqBpuub6eVRP5IgiSA==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "darwin"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/darwin-x64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/darwin-x64/-/darwin-x64-0.25.2.tgz",
      "integrity": "sha512-5eRPrTX7wFyuWe8FqEFPG2cU0+butQQVNcT4sVipqjLYQjjh8a8+vUTfgBKM88ObB85ahsnTwF7PSIt6PG+QkA==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "darwin"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/freebsd-arm64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/freebsd-arm64/-/freebsd-arm64-0.25.2.tgz",
      "integrity": "sha512-mLwm4vXKiQ2UTSX4+ImyiPdiHjiZhIaE9QvC7sw0tZ6HoNMjYAqQpGyui5VRIi5sGd+uWq940gdCbY3VLvsO1w==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "freebsd"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/freebsd-x64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/freebsd-x64/-/freebsd-x64-0.25.2.tgz",
      "integrity": "sha512-6qyyn6TjayJSwGpm8J9QYYGQcRgc90nmfdUb0O7pp1s4lTY+9D0H9O02v5JqGApUyiHOtkz6+1hZNvNtEhbwRQ==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "freebsd"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/linux-arm": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-arm/-/linux-arm-0.25.2.tgz",
      "integrity": "sha512-UHBRgJcmjJv5oeQF8EpTRZs/1knq6loLxTsjc3nxO9eXAPDLcWW55flrMVc97qFPbmZP31ta1AZVUKQzKTzb0g==",
      "cpu": [
        "arm"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/linux-arm64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-arm64/-/linux-arm64-0.25.2.tgz",
      "integrity": "sha512-gq/sjLsOyMT19I8obBISvhoYiZIAaGF8JpeXu1u8yPv8BE5HlWYobmlsfijFIZ9hIVGYkbdFhEqC0NvM4kNO0g==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/linux-ia32": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-ia32/-/linux-ia32-0.25.2.tgz",
      "integrity": "sha512-bBYCv9obgW2cBP+2ZWfjYTU+f5cxRoGGQ5SeDbYdFCAZpYWrfjjfYwvUpP8MlKbP0nwZ5gyOU/0aUzZ5HWPuvQ==",
      "cpu": [
        "ia32"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/linux-loong64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-loong64/-/linux-loong64-0.25.2.tgz",
      "integrity": "sha512-SHNGiKtvnU2dBlM5D8CXRFdd+6etgZ9dXfaPCeJtz+37PIUlixvlIhI23L5khKXs3DIzAn9V8v+qb1TRKrgT5w==",
      "cpu": [
        "loong64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/linux-mips64el": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-mips64el/-/linux-mips64el-0.25.2.tgz",
      "integrity": "sha512-hDDRlzE6rPeoj+5fsADqdUZl1OzqDYow4TB4Y/3PlKBD0ph1e6uPHzIQcv2Z65u2K0kpeByIyAjCmjn1hJgG0Q==",
      "cpu": [
        "mips64el"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/linux-ppc64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-ppc64/-/linux-ppc64-0.25.2.tgz",
      "integrity": "sha512-tsHu2RRSWzipmUi9UBDEzc0nLc4HtpZEI5Ba+Omms5456x5WaNuiG3u7xh5AO6sipnJ9r4cRWQB2tUjPyIkc6g==",
      "cpu": [
        "ppc64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/linux-riscv64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-riscv64/-/linux-riscv64-0.25.2.tgz",
      "integrity": "sha512-k4LtpgV7NJQOml/10uPU0s4SAXGnowi5qBSjaLWMojNCUICNu7TshqHLAEbkBdAszL5TabfvQ48kK84hyFzjnw==",
      "cpu": [
        "riscv64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/linux-s390x": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-s390x/-/linux-s390x-0.25.2.tgz",
      "integrity": "sha512-GRa4IshOdvKY7M/rDpRR3gkiTNp34M0eLTaC1a08gNrh4u488aPhuZOCpkF6+2wl3zAN7L7XIpOFBhnaE3/Q8Q==",
      "cpu": [
        "s390x"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/linux-x64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/linux-x64/-/linux-x64-0.25.2.tgz",
      "integrity": "sha512-QInHERlqpTTZ4FRB0fROQWXcYRD64lAoiegezDunLpalZMjcUcld3YzZmVJ2H/Cp0wJRZ8Xtjtj0cEHhYc/uUg==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/netbsd-arm64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/netbsd-arm64/-/netbsd-arm64-0.25.2.tgz",
      "integrity": "sha512-talAIBoY5M8vHc6EeI2WW9d/CkiO9MQJ0IOWX8hrLhxGbro/vBXJvaQXefW2cP0z0nQVTdQ/eNyGFV1GSKrxfw==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "netbsd"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/netbsd-x64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/netbsd-x64/-/netbsd-x64-0.25.2.tgz",
      "integrity": "sha512-voZT9Z+tpOxrvfKFyfDYPc4DO4rk06qamv1a/fkuzHpiVBMOhpjK+vBmWM8J1eiB3OLSMFYNaOaBNLXGChf5tg==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "netbsd"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/openbsd-arm64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/openbsd-arm64/-/openbsd-arm64-0.25.2.tgz",
      "integrity": "sha512-dcXYOC6NXOqcykeDlwId9kB6OkPUxOEqU+rkrYVqJbK2hagWOMrsTGsMr8+rW02M+d5Op5NNlgMmjzecaRf7Tg==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "openbsd"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/openbsd-x64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/openbsd-x64/-/openbsd-x64-0.25.2.tgz",
      "integrity": "sha512-t/TkWwahkH0Tsgoq1Ju7QfgGhArkGLkF1uYz8nQS/PPFlXbP5YgRpqQR3ARRiC2iXoLTWFxc6DJMSK10dVXluw==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "openbsd"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/sunos-x64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/sunos-x64/-/sunos-x64-0.25.2.tgz",
      "integrity": "sha512-cfZH1co2+imVdWCjd+D1gf9NjkchVhhdpgb1q5y6Hcv9TP6Zi9ZG/beI3ig8TvwT9lH9dlxLq5MQBBgwuj4xvA==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "sunos"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/win32-arm64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/win32-arm64/-/win32-arm64-0.25.2.tgz",
      "integrity": "sha512-7Loyjh+D/Nx/sOTzV8vfbB3GJuHdOQyrOryFdZvPHLf42Tk9ivBU5Aedi7iyX+x6rbn2Mh68T4qq1SDqJBQO5Q==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "win32"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/win32-ia32": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/win32-ia32/-/win32-ia32-0.25.2.tgz",
      "integrity": "sha512-WRJgsz9un0nqZJ4MfhabxaD9Ft8KioqU3JMinOTvobbX6MOSUigSBlogP8QB3uxpJDsFS6yN+3FDBdqE5lg9kg==",
      "cpu": [
        "ia32"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "win32"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@esbuild/win32-x64": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/@esbuild/win32-x64/-/win32-x64-0.25.2.tgz",
      "integrity": "sha512-kM3HKb16VIXZyIeVrM1ygYmZBKybX8N4p754bw390wGO3Tf2j4L2/WYL+4suWujpgf6GBYs3jv7TyUivdd05JA==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "win32"
      ],
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/@eslint-community/eslint-utils": {
      "version": "4.5.1",
      "resolved": "https://registry.npmjs.org/@eslint-community/eslint-utils/-/eslint-utils-4.5.1.tgz",
      "integrity": "sha512-soEIOALTfTK6EjmKMMoLugwaP0rzkad90iIWd1hMO9ARkSAyjfMfkRRhLvD5qH7vvM0Cg72pieUfR6yh6XxC4w==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "eslint-visitor-keys": "^3.4.3"
      },
      "engines": {
        "node": "^12.22.0 || ^14.17.0 || >=16.0.0"
      },
      "funding": {
        "url": "https://opencollective.com/eslint"
      },
      "peerDependencies": {
        "eslint": "^6.0.0 || ^7.0.0 || >=8.0.0"
      }
    },
    "node_modules/@eslint-community/eslint-utils/node_modules/eslint-visitor-keys": {
      "version": "3.4.3",
      "resolved": "https://registry.npmjs.org/eslint-visitor-keys/-/eslint-visitor-keys-3.4.3.tgz",
      "integrity": "sha512-wpc+LXeiyiisxPlEkUzU6svyS1frIO3Mgxj1fdy7Pm8Ygzguax2N3Fa/D/ag1WqbOprdI+uY6wMUl8/a2G+iag==",
      "dev": true,
      "license": "Apache-2.0",
      "engines": {
        "node": "^12.22.0 || ^14.17.0 || >=16.0.0"
      },
      "funding": {
        "url": "https://opencollective.com/eslint"
      }
    },
    "node_modules/@eslint-community/regexpp": {
      "version": "4.12.1",
      "resolved": "https://registry.npmjs.org/@eslint-community/regexpp/-/regexpp-4.12.1.tgz",
      "integrity": "sha512-CCZCDJuduB9OUkFkY2IgppNZMi2lBQgD2qzwXkEia16cge2pijY/aXi96CJMquDMn3nJdlPV1A5KrJEXwfLNzQ==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": "^12.0.0 || ^14.0.0 || >=16.0.0"
      }
    },
    "node_modules/@eslint/config-array": {
      "version": "0.19.2",
      "resolved": "https://registry.npmjs.org/@eslint/config-array/-/config-array-0.19.2.tgz",
      "integrity": "sha512-GNKqxfHG2ySmJOBSHg7LxeUx4xpuCoFjacmlCoYWEbaPXLwvfIjixRI12xCQZeULksQb23uiA8F40w5TojpV7w==",
      "dev": true,
      "license": "Apache-2.0",
      "dependencies": {
        "@eslint/object-schema": "^2.1.6",
        "debug": "^4.3.1",
        "minimatch": "^3.1.2"
      },
      "engines": {
        "node": "^18.18.0 || ^20.9.0 || >=21.1.0"
      }
    },
    "node_modules/@eslint/config-helpers": {
      "version": "0.2.0",
      "resolved": "https://registry.npmjs.org/@eslint/config-helpers/-/config-helpers-0.2.0.tgz",
      "integrity": "sha512-yJLLmLexii32mGrhW29qvU3QBVTu0GUmEf/J4XsBtVhp4JkIUFN/BjWqTF63yRvGApIDpZm5fa97LtYtINmfeQ==",
      "dev": true,
      "license": "Apache-2.0",
      "engines": {
        "node": "^18.18.0 || ^20.9.0 || >=21.1.0"
      }
    },
    "node_modules/@eslint/core": {
      "version": "0.12.0",
      "resolved": "https://registry.npmjs.org/@eslint/core/-/core-0.12.0.tgz",
      "integrity": "sha512-cmrR6pytBuSMTaBweKoGMwu3EiHiEC+DoyupPmlZ0HxBJBtIxwe+j/E4XPIKNx+Q74c8lXKPwYawBf5glsTkHg==",
      "dev": true,
      "license": "Apache-2.0",
      "dependencies": {
        "@types/json-schema": "^7.0.15"
      },
      "engines": {
        "node": "^18.18.0 || ^20.9.0 || >=21.1.0"
      }
    },
    "node_modules/@eslint/eslintrc": {
      "version": "3.3.1",
      "resolved": "https://registry.npmjs.org/@eslint/eslintrc/-/eslintrc-3.3.1.tgz",
      "integrity": "sha512-gtF186CXhIl1p4pJNGZw8Yc6RlshoePRvE0X91oPGb3vZ8pM3qOS9W9NGPat9LziaBV7XrJWGylNQXkGcnM3IQ==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "ajv": "^6.12.4",
        "debug": "^4.3.2",
        "espree": "^10.0.1",
        "globals": "^14.0.0",
        "ignore": "^5.2.0",
        "import-fresh": "^3.2.1",
        "js-yaml": "^4.1.0",
        "minimatch": "^3.1.2",
        "strip-json-comments": "^3.1.1"
      },
      "engines": {
        "node": "^18.18.0 || ^20.9.0 || >=21.1.0"
      },
      "funding": {
        "url": "https://opencollective.com/eslint"
      }
    },
    "node_modules/@eslint/eslintrc/node_modules/globals": {
      "version": "14.0.0",
      "resolved": "https://registry.npmjs.org/globals/-/globals-14.0.0.tgz",
      "integrity": "sha512-oahGvuMGQlPw/ivIYBjVSrWAfWLBeku5tpPE2fOPLi+WHffIWbuh2tCjhyQhTBPMf5E9jDEH4FOmTYgYwbKwtQ==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/@eslint/js": {
      "version": "9.23.0",
      "resolved": "https://registry.npmjs.org/@eslint/js/-/js-9.23.0.tgz",
      "integrity": "sha512-35MJ8vCPU0ZMxo7zfev2pypqTwWTofFZO6m4KAtdoFhRpLJUpHTZZ+KB3C7Hb1d7bULYwO4lJXGCi5Se+8OMbw==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": "^18.18.0 || ^20.9.0 || >=21.1.0"
      }
    },
    "node_modules/@eslint/object-schema": {
      "version": "2.1.6",
      "resolved": "https://registry.npmjs.org/@eslint/object-schema/-/object-schema-2.1.6.tgz",
      "integrity": "sha512-RBMg5FRL0I0gs51M/guSAj5/e14VQ4tpZnQNWwuDT66P14I43ItmPfIZRhO9fUVIPOAQXU47atlywZ/czoqFPA==",
      "dev": true,
      "license": "Apache-2.0",
      "engines": {
        "node": "^18.18.0 || ^20.9.0 || >=21.1.0"
      }
    },
    "node_modules/@eslint/plugin-kit": {
      "version": "0.2.7",
      "resolved": "https://registry.npmjs.org/@eslint/plugin-kit/-/plugin-kit-0.2.7.tgz",
      "integrity": "sha512-JubJ5B2pJ4k4yGxaNLdbjrnk9d/iDz6/q8wOilpIowd6PJPgaxCuHBnBszq7Ce2TyMrywm5r4PnKm6V3iiZF+g==",
      "dev": true,
      "license": "Apache-2.0",
      "dependencies": {
        "@eslint/core": "^0.12.0",
        "levn": "^0.4.1"
      },
      "engines": {
        "node": "^18.18.0 || ^20.9.0 || >=21.1.0"
      }
    },
    "node_modules/@faker-js/faker": {
      "version": "9.7.0",
      "resolved": "https://registry.npmjs.org/@faker-js/faker/-/faker-9.7.0.tgz",
      "integrity": "sha512-aozo5vqjCmDoXLNUJarFZx2IN/GgGaogY4TMJ6so/WLZOWpSV7fvj2dmrV6sEAnUm1O7aCrhTibjpzeDFgNqbg==",
      "funding": [
        {
          "type": "opencollective",
          "url": "https://opencollective.com/fakerjs"
        }
      ],
      "license": "MIT",
      "engines": {
        "node": ">=18.0.0",
        "npm": ">=9.0.0"
      }
    },
    "node_modules/@humanfs/core": {
      "version": "0.19.1",
      "resolved": "https://registry.npmjs.org/@humanfs/core/-/core-0.19.1.tgz",
      "integrity": "sha512-5DyQ4+1JEUzejeK1JGICcideyfUbGixgS9jNgex5nqkW+cY7WZhxBigmieN5Qnw9ZosSNVC9KQKyb+GUaGyKUA==",
      "dev": true,
      "license": "Apache-2.0",
      "engines": {
        "node": ">=18.18.0"
      }
    },
    "node_modules/@humanfs/node": {
      "version": "0.16.6",
      "resolved": "https://registry.npmjs.org/@humanfs/node/-/node-0.16.6.tgz",
      "integrity": "sha512-YuI2ZHQL78Q5HbhDiBA1X4LmYdXCKCMQIfw0pw7piHJwyREFebJUvrQN4cMssyES6x+vfUbx1CIpaQUKYdQZOw==",
      "dev": true,
      "license": "Apache-2.0",
      "dependencies": {
        "@humanfs/core": "^0.19.1",
        "@humanwhocodes/retry": "^0.3.0"
      },
      "engines": {
        "node": ">=18.18.0"
      }
    },
    "node_modules/@humanfs/node/node_modules/@humanwhocodes/retry": {
      "version": "0.3.1",
      "resolved": "https://registry.npmjs.org/@humanwhocodes/retry/-/retry-0.3.1.tgz",
      "integrity": "sha512-JBxkERygn7Bv/GbN5Rv8Ul6LVknS+5Bp6RgDC/O8gEBU/yeH5Ui5C/OlWrTb6qct7LjjfT6Re2NxB0ln0yYybA==",
      "dev": true,
      "license": "Apache-2.0",
      "engines": {
        "node": ">=18.18"
      },
      "funding": {
        "type": "github",
        "url": "https://github.com/sponsors/nzakas"
      }
    },
    "node_modules/@humanwhocodes/module-importer": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/@humanwhocodes/module-importer/-/module-importer-1.0.1.tgz",
      "integrity": "sha512-bxveV4V8v5Yb4ncFTT3rPSgZBOpCkjfK0y4oVVVJwIuDVBRMDXrPyXRL988i5ap9m9bnyEEjWfm5WkBmtffLfA==",
      "dev": true,
      "license": "Apache-2.0",
      "engines": {
        "node": ">=12.22"
      },
      "funding": {
        "type": "github",
        "url": "https://github.com/sponsors/nzakas"
      }
    },
    "node_modules/@humanwhocodes/retry": {
      "version": "0.4.2",
      "resolved": "https://registry.npmjs.org/@humanwhocodes/retry/-/retry-0.4.2.tgz",
      "integrity": "sha512-xeO57FpIu4p1Ri3Jq/EXq4ClRm86dVF2z/+kvFnyqVYRavTZmaFaUBbWCOuuTh0o/g7DSsk6kc2vrS4Vl5oPOQ==",
      "dev": true,
      "license": "Apache-2.0",
      "engines": {
        "node": ">=18.18"
      },
      "funding": {
        "type": "github",
        "url": "https://github.com/sponsors/nzakas"
      }
    },
    "node_modules/@isaacs/cliui": {
      "version": "8.0.2",
      "resolved": "https://registry.npmjs.org/@isaacs/cliui/-/cliui-8.0.2.tgz",
      "integrity": "sha512-O8jcjabXaleOG9DQ0+ARXWZBTfnP4WNAqzuiJK7ll44AmxGKv/J2M4TPjxjY3znBCfvBXFzucm1twdyFybFqEA==",
      "dev": true,
      "license": "ISC",
      "dependencies": {
        "string-width": "^5.1.2",
        "string-width-cjs": "npm:string-width@^4.2.0",
        "strip-ansi": "^7.0.1",
        "strip-ansi-cjs": "npm:strip-ansi@^6.0.1",
        "wrap-ansi": "^8.1.0",
        "wrap-ansi-cjs": "npm:wrap-ansi@^7.0.0"
      },
      "engines": {
        "node": ">=12"
      }
    },
    "node_modules/@jridgewell/gen-mapping": {
      "version": "0.3.8",
      "resolved": "https://registry.npmjs.org/@jridgewell/gen-mapping/-/gen-mapping-0.3.8.tgz",
      "integrity": "sha512-imAbBGkb+ebQyxKgzv5Hu2nmROxoDOXHh80evxdoXNOrvAnVx7zimzc1Oo5h9RlfV4vPXaE2iM5pOFbvOCClWA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@jridgewell/set-array": "^1.2.1",
        "@jridgewell/sourcemap-codec": "^1.4.10",
        "@jridgewell/trace-mapping": "^0.3.24"
      },
      "engines": {
        "node": ">=6.0.0"
      }
    },
    "node_modules/@jridgewell/resolve-uri": {
      "version": "3.1.2",
      "resolved": "https://registry.npmjs.org/@jridgewell/resolve-uri/-/resolve-uri-3.1.2.tgz",
      "integrity": "sha512-bRISgCIjP20/tbWSPWMEi54QVPRZExkuD9lJL+UIxUKtwVJA8wW1Trb1jMs1RFXo1CBTNZ/5hpC9QvmKWdopKw==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=6.0.0"
      }
    },
    "node_modules/@jridgewell/set-array": {
      "version": "1.2.1",
      "resolved": "https://registry.npmjs.org/@jridgewell/set-array/-/set-array-1.2.1.tgz",
      "integrity": "sha512-R8gLRTZeyp03ymzP/6Lil/28tGeGEzhx1q2k703KGWRAI1VdvPIXdG70VJc2pAMw3NA6JKL5hhFu1sJX0Mnn/A==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=6.0.0"
      }
    },
    "node_modules/@jridgewell/sourcemap-codec": {
      "version": "1.5.0",
      "resolved": "https://registry.npmjs.org/@jridgewell/sourcemap-codec/-/sourcemap-codec-1.5.0.tgz",
      "integrity": "sha512-gv3ZRaISU3fjPAgNsriBRqGWQL6quFx04YMPW/zD8XMLsU32mhCCbfbO6KZFLjvYpCZ8zyDEgqsgf+PwPaM7GQ==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/@jridgewell/trace-mapping": {
      "version": "0.3.25",
      "resolved": "https://registry.npmjs.org/@jridgewell/trace-mapping/-/trace-mapping-0.3.25.tgz",
      "integrity": "sha512-vNk6aEwybGtawWmy/PzwnGDOjCkLWSD2wqvjGGAgOAwCGWySYXfYoxt00IJkTF+8Lb57DwOb3Aa0o9CApepiYQ==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@jridgewell/resolve-uri": "^3.1.0",
        "@jridgewell/sourcemap-codec": "^1.4.14"
      }
    },
    "node_modules/@nodelib/fs.scandir": {
      "version": "2.1.5",
      "resolved": "https://registry.npmjs.org/@nodelib/fs.scandir/-/fs.scandir-2.1.5.tgz",
      "integrity": "sha512-vq24Bq3ym5HEQm2NKCr3yXDwjc7vTsEThRDnkp2DK9p1uqLR+DHurm/NOTo0KG7HYHU7eppKZj3MyqYuMBf62g==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@nodelib/fs.stat": "2.0.5",
        "run-parallel": "^1.1.9"
      },
      "engines": {
        "node": ">= 8"
      }
    },
    "node_modules/@nodelib/fs.stat": {
      "version": "2.0.5",
      "resolved": "https://registry.npmjs.org/@nodelib/fs.stat/-/fs.stat-2.0.5.tgz",
      "integrity": "sha512-RkhPPp2zrqDAQA/2jNhnztcPAlv64XdhIp7a7454A5ovI7Bukxgt7MX7udwAu3zg1DcpPU0rz3VV1SeaqvY4+A==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">= 8"
      }
    },
    "node_modules/@nodelib/fs.walk": {
      "version": "1.2.8",
      "resolved": "https://registry.npmjs.org/@nodelib/fs.walk/-/fs.walk-1.2.8.tgz",
      "integrity": "sha512-oGB+UxlgWcgQkgwo8GcEGwemoTFt3FIO9ababBmaGwXIoBKZ+GTy0pP185beGg7Llih/NSHSV2XAs1lnznocSg==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@nodelib/fs.scandir": "2.1.5",
        "fastq": "^1.6.0"
      },
      "engines": {
        "node": ">= 8"
      }
    },
    "node_modules/@pkgjs/parseargs": {
      "version": "0.11.0",
      "resolved": "https://registry.npmjs.org/@pkgjs/parseargs/-/parseargs-0.11.0.tgz",
      "integrity": "sha512-+1VkjdD0QBLPodGrJUeqarH8VAIvQODIbwh9XpP5Syisf7YoQgsJKPNFoqqLQlu+VQ/tVSshMR6loPMn8U+dPg==",
      "dev": true,
      "license": "MIT",
      "optional": true,
      "engines": {
        "node": ">=14"
      }
    },
    "node_modules/@reduxjs/toolkit": {
      "version": "2.6.1",
      "resolved": "https://registry.npmjs.org/@reduxjs/toolkit/-/toolkit-2.6.1.tgz",
      "integrity": "sha512-SSlIqZNYhqm/oMkXbtofwZSt9lrncblzo6YcZ9zoX+zLngRBrCOjK4lNLdkNucJF58RHOWrD9txT3bT3piH7Zw==",
      "license": "MIT",
      "dependencies": {
        "immer": "^10.0.3",
        "redux": "^5.0.1",
        "redux-thunk": "^3.1.0",
        "reselect": "^5.1.0"
      },
      "peerDependencies": {
        "react": "^16.9.0 || ^17.0.0 || ^18 || ^19",
        "react-redux": "^7.2.1 || ^8.1.3 || ^9.0.0"
      },
      "peerDependenciesMeta": {
        "react": {
          "optional": true
        },
        "react-redux": {
          "optional": true
        }
      }
    },
    "node_modules/@rollup/rollup-android-arm-eabi": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-android-arm-eabi/-/rollup-android-arm-eabi-4.38.0.tgz",
      "integrity": "sha512-ldomqc4/jDZu/xpYU+aRxo3V4mGCV9HeTgUBANI3oIQMOL+SsxB+S2lxMpkFp5UamSS3XuTMQVbsS24R4J4Qjg==",
      "cpu": [
        "arm"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "android"
      ]
    },
    "node_modules/@rollup/rollup-android-arm64": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-android-arm64/-/rollup-android-arm64-4.38.0.tgz",
      "integrity": "sha512-VUsgcy4GhhT7rokwzYQP+aV9XnSLkkhlEJ0St8pbasuWO/vwphhZQxYEKUP3ayeCYLhk6gEtacRpYP/cj3GjyQ==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "android"
      ]
    },
    "node_modules/@rollup/rollup-darwin-arm64": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-darwin-arm64/-/rollup-darwin-arm64-4.38.0.tgz",
      "integrity": "sha512-buA17AYXlW9Rn091sWMq1xGUvWQFOH4N1rqUxGJtEQzhChxWjldGCCup7r/wUnaI6Au8sKXpoh0xg58a7cgcpg==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "darwin"
      ]
    },
    "node_modules/@rollup/rollup-darwin-x64": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-darwin-x64/-/rollup-darwin-x64-4.38.0.tgz",
      "integrity": "sha512-Mgcmc78AjunP1SKXl624vVBOF2bzwNWFPMP4fpOu05vS0amnLcX8gHIge7q/lDAHy3T2HeR0TqrriZDQS2Woeg==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "darwin"
      ]
    },
    "node_modules/@rollup/rollup-freebsd-arm64": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-freebsd-arm64/-/rollup-freebsd-arm64-4.38.0.tgz",
      "integrity": "sha512-zzJACgjLbQTsscxWqvrEQAEh28hqhebpRz5q/uUd1T7VTwUNZ4VIXQt5hE7ncs0GrF+s7d3S4on4TiXUY8KoQA==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "freebsd"
      ]
    },
    "node_modules/@rollup/rollup-freebsd-x64": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-freebsd-x64/-/rollup-freebsd-x64-4.38.0.tgz",
      "integrity": "sha512-hCY/KAeYMCyDpEE4pTETam0XZS4/5GXzlLgpi5f0IaPExw9kuB+PDTOTLuPtM10TlRG0U9OSmXJ+Wq9J39LvAg==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "freebsd"
      ]
    },
    "node_modules/@rollup/rollup-linux-arm-gnueabihf": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-arm-gnueabihf/-/rollup-linux-arm-gnueabihf-4.38.0.tgz",
      "integrity": "sha512-mimPH43mHl4JdOTD7bUMFhBdrg6f9HzMTOEnzRmXbOZqjijCw8LA5z8uL6LCjxSa67H2xiLFvvO67PT05PRKGg==",
      "cpu": [
        "arm"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-linux-arm-musleabihf": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-arm-musleabihf/-/rollup-linux-arm-musleabihf-4.38.0.tgz",
      "integrity": "sha512-tPiJtiOoNuIH8XGG8sWoMMkAMm98PUwlriOFCCbZGc9WCax+GLeVRhmaxjJtz6WxrPKACgrwoZ5ia/uapq3ZVg==",
      "cpu": [
        "arm"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-linux-arm64-gnu": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-arm64-gnu/-/rollup-linux-arm64-gnu-4.38.0.tgz",
      "integrity": "sha512-wZco59rIVuB0tjQS0CSHTTUcEde+pXQWugZVxWaQFdQQ1VYub/sTrNdY76D1MKdN2NB48JDuGABP6o6fqos8mA==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-linux-arm64-musl": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-arm64-musl/-/rollup-linux-arm64-musl-4.38.0.tgz",
      "integrity": "sha512-fQgqwKmW0REM4LomQ+87PP8w8xvU9LZfeLBKybeli+0yHT7VKILINzFEuggvnV9M3x1Ed4gUBmGUzCo/ikmFbQ==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-linux-loongarch64-gnu": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-loongarch64-gnu/-/rollup-linux-loongarch64-gnu-4.38.0.tgz",
      "integrity": "sha512-hz5oqQLXTB3SbXpfkKHKXLdIp02/w3M+ajp8p4yWOWwQRtHWiEOCKtc9U+YXahrwdk+3qHdFMDWR5k+4dIlddg==",
      "cpu": [
        "loong64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-linux-powerpc64le-gnu": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-powerpc64le-gnu/-/rollup-linux-powerpc64le-gnu-4.38.0.tgz",
      "integrity": "sha512-NXqygK/dTSibQ+0pzxsL3r4Xl8oPqVoWbZV9niqOnIHV/J92fe65pOir0xjkUZDRSPyFRvu+4YOpJF9BZHQImw==",
      "cpu": [
        "ppc64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-linux-riscv64-gnu": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-riscv64-gnu/-/rollup-linux-riscv64-gnu-4.38.0.tgz",
      "integrity": "sha512-GEAIabR1uFyvf/jW/5jfu8gjM06/4kZ1W+j1nWTSSB3w6moZEBm7iBtzwQ3a1Pxos2F7Gz+58aVEnZHU295QTg==",
      "cpu": [
        "riscv64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-linux-riscv64-musl": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-riscv64-musl/-/rollup-linux-riscv64-musl-4.38.0.tgz",
      "integrity": "sha512-9EYTX+Gus2EGPbfs+fh7l95wVADtSQyYw4DfSBcYdUEAmP2lqSZY0Y17yX/3m5VKGGJ4UmIH5LHLkMJft3bYoA==",
      "cpu": [
        "riscv64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-linux-s390x-gnu": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-s390x-gnu/-/rollup-linux-s390x-gnu-4.38.0.tgz",
      "integrity": "sha512-Mpp6+Z5VhB9VDk7RwZXoG2qMdERm3Jw07RNlXHE0bOnEeX+l7Fy4bg+NxfyN15ruuY3/7Vrbpm75J9QHFqj5+Q==",
      "cpu": [
        "s390x"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-linux-x64-gnu": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-x64-gnu/-/rollup-linux-x64-gnu-4.38.0.tgz",
      "integrity": "sha512-vPvNgFlZRAgO7rwncMeE0+8c4Hmc+qixnp00/Uv3ht2x7KYrJ6ERVd3/R0nUtlE6/hu7/HiiNHJ/rP6knRFt1w==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-linux-x64-musl": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-linux-x64-musl/-/rollup-linux-x64-musl-4.38.0.tgz",
      "integrity": "sha512-q5Zv+goWvQUGCaL7fU8NuTw8aydIL/C9abAVGCzRReuj5h30TPx4LumBtAidrVOtXnlB+RZkBtExMsfqkMfb8g==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "linux"
      ]
    },
    "node_modules/@rollup/rollup-win32-arm64-msvc": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-win32-arm64-msvc/-/rollup-win32-arm64-msvc-4.38.0.tgz",
      "integrity": "sha512-u/Jbm1BU89Vftqyqbmxdq14nBaQjQX1HhmsdBWqSdGClNaKwhjsg5TpW+5Ibs1mb8Es9wJiMdl86BcmtUVXNZg==",
      "cpu": [
        "arm64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "win32"
      ]
    },
    "node_modules/@rollup/rollup-win32-ia32-msvc": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-win32-ia32-msvc/-/rollup-win32-ia32-msvc-4.38.0.tgz",
      "integrity": "sha512-mqu4PzTrlpNHHbu5qleGvXJoGgHpChBlrBx/mEhTPpnAL1ZAYFlvHD7rLK839LLKQzqEQMFJfGrrOHItN4ZQqA==",
      "cpu": [
        "ia32"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "win32"
      ]
    },
    "node_modules/@rollup/rollup-win32-x64-msvc": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/@rollup/rollup-win32-x64-msvc/-/rollup-win32-x64-msvc-4.38.0.tgz",
      "integrity": "sha512-jjqy3uWlecfB98Psxb5cD6Fny9Fupv9LrDSPTQZUROqjvZmcCqNu4UMl7qqhlUUGpwiAkotj6GYu4SZdcr/nLw==",
      "cpu": [
        "x64"
      ],
      "dev": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "win32"
      ]
    },
    "node_modules/@types/babel__core": {
      "version": "7.20.5",
      "resolved": "https://registry.npmjs.org/@types/babel__core/-/babel__core-7.20.5.tgz",
      "integrity": "sha512-qoQprZvz5wQFJwMDqeseRXWv3rqMvhgpbXFfVyWhbx9X47POIA6i/+dXefEmZKoAgOaTdaIgNSMqMIU61yRyzA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@babel/parser": "^7.20.7",
        "@babel/types": "^7.20.7",
        "@types/babel__generator": "*",
        "@types/babel__template": "*",
        "@types/babel__traverse": "*"
      }
    },
    "node_modules/@types/babel__generator": {
      "version": "7.6.8",
      "resolved": "https://registry.npmjs.org/@types/babel__generator/-/babel__generator-7.6.8.tgz",
      "integrity": "sha512-ASsj+tpEDsEiFr1arWrlN6V3mdfjRMZt6LtK/Vp/kreFLnr5QH5+DhvD5nINYZXzwJvXeGq+05iUXcAzVrqWtw==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@babel/types": "^7.0.0"
      }
    },
    "node_modules/@types/babel__template": {
      "version": "7.4.4",
      "resolved": "https://registry.npmjs.org/@types/babel__template/-/babel__template-7.4.4.tgz",
      "integrity": "sha512-h/NUaSyG5EyxBIp8YRxo4RMe2/qQgvyowRwVMzhYhBCONbW8PUsg4lkFMrhgZhUe5z3L3MiLDuvyJ/CaPa2A8A==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@babel/parser": "^7.1.0",
        "@babel/types": "^7.0.0"
      }
    },
    "node_modules/@types/babel__traverse": {
      "version": "7.20.7",
      "resolved": "https://registry.npmjs.org/@types/babel__traverse/-/babel__traverse-7.20.7.tgz",
      "integrity": "sha512-dkO5fhS7+/oos4ciWxyEyjWe48zmG6wbCheo/G2ZnHx4fs3EU6YC6UM8rk56gAjNJ9P3MTH2jo5jb92/K6wbng==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@babel/types": "^7.20.7"
      }
    },
    "node_modules/@types/cookie": {
      "version": "0.6.0",
      "resolved": "https://registry.npmjs.org/@types/cookie/-/cookie-0.6.0.tgz",
      "integrity": "sha512-4Kh9a6B2bQciAhf7FSuMRRkUWecJgJu9nPnx3yzpsfXX/c50REIqpHY4C82bXP90qrLtXtkDxTZosYO3UpOwlA==",
      "license": "MIT"
    },
    "node_modules/@types/estree": {
      "version": "1.0.7",
      "resolved": "https://registry.npmjs.org/@types/estree/-/estree-1.0.7.tgz",
      "integrity": "sha512-w28IoSUCJpidD/TGviZwwMJckNESJZXFu7NBZ5YJ4mEUnNraUn9Pm8HSZm/jDF1pDWYKspWE7oVphigUPRakIQ==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/@types/json-schema": {
      "version": "7.0.15",
      "resolved": "https://registry.npmjs.org/@types/json-schema/-/json-schema-7.0.15.tgz",
      "integrity": "sha512-5+fP8P8MFNC+AyZCDxrB2pkZFPGzqQWUzpSeuuVLvm8VMcorNYavBqoFcxK8bQz4Qsbn4oUEEem4wDLfcysGHA==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/@types/react": {
      "version": "19.0.12",
      "resolved": "https://registry.npmjs.org/@types/react/-/react-19.0.12.tgz",
      "integrity": "sha512-V6Ar115dBDrjbtXSrS+/Oruobc+qVbbUxDFC1RSbRqLt5SYvxxyIDrSC85RWml54g+jfNeEMZhEj7wW07ONQhA==",
      "devOptional": true,
      "license": "MIT",
      "dependencies": {
        "csstype": "^3.0.2"
      }
    },
    "node_modules/@types/react-dom": {
      "version": "19.0.4",
      "resolved": "https://registry.npmjs.org/@types/react-dom/-/react-dom-19.0.4.tgz",
      "integrity": "sha512-4fSQ8vWFkg+TGhePfUzVmat3eC14TXYSsiiDSLI0dVLsrm9gZFABjPy/Qu6TKgl1tq1Bu1yDsuQgY3A3DOjCcg==",
      "dev": true,
      "license": "MIT",
      "peerDependencies": {
        "@types/react": "^19.0.0"
      }
    },
    "node_modules/@types/trusted-types": {
      "version": "2.0.7",
      "resolved": "https://registry.npmjs.org/@types/trusted-types/-/trusted-types-2.0.7.tgz",
      "integrity": "sha512-ScaPdn1dQczgbl0QFTeTOmVHFULt394XJgOQNoyVhZ6r2vLnMLJfBPd53SB52T/3G36VI1/g2MZaX0cwDuXsfw==",
      "license": "MIT",
      "optional": true
    },
    "node_modules/@types/use-sync-external-store": {
      "version": "0.0.6",
      "resolved": "https://registry.npmjs.org/@types/use-sync-external-store/-/use-sync-external-store-0.0.6.tgz",
      "integrity": "sha512-zFDAD+tlpf2r4asuHEj0XH6pY6i0g5NeAHPn+15wk3BV6JA69eERFXC1gyGThDkVa1zCyKr5jox1+2LbV/AMLg==",
      "license": "MIT"
    },
    "node_modules/@vitejs/plugin-react": {
      "version": "4.3.4",
      "resolved": "https://registry.npmjs.org/@vitejs/plugin-react/-/plugin-react-4.3.4.tgz",
      "integrity": "sha512-SCCPBJtYLdE8PX/7ZQAs1QAZ8Jqwih+0VBLum1EGqmCCQal+MIUqLCzj3ZUy8ufbC0cAM4LRlSTm7IQJwWT4ug==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@babel/core": "^7.26.0",
        "@babel/plugin-transform-react-jsx-self": "^7.25.9",
        "@babel/plugin-transform-react-jsx-source": "^7.25.9",
        "@types/babel__core": "^7.20.5",
        "react-refresh": "^0.14.2"
      },
      "engines": {
        "node": "^14.18.0 || >=16.0.0"
      },
      "peerDependencies": {
        "vite": "^4.2.0 || ^5.0.0 || ^6.0.0"
      }
    },
    "node_modules/acorn": {
      "version": "8.14.1",
      "resolved": "https://registry.npmjs.org/acorn/-/acorn-8.14.1.tgz",
      "integrity": "sha512-OvQ/2pUDKmgfCg++xsTX1wGxfTaszcHVcTctW4UJB4hibJx2HXxxO5UmVgyjMa+ZDsiaf5wWLXYpRWMmBI0QHg==",
      "dev": true,
      "license": "MIT",
      "bin": {
        "acorn": "bin/acorn"
      },
      "engines": {
        "node": ">=0.4.0"
      }
    },
    "node_modules/acorn-jsx": {
      "version": "5.3.2",
      "resolved": "https://registry.npmjs.org/acorn-jsx/-/acorn-jsx-5.3.2.tgz",
      "integrity": "sha512-rq9s+JNhf0IChjtDXxllJ7g41oZk5SlXtp0LHwyA5cejwn7vKmKp4pPri6YEePv2PU65sAsegbXtIinmDFDXgQ==",
      "dev": true,
      "license": "MIT",
      "peerDependencies": {
        "acorn": "^6.0.0 || ^7.0.0 || ^8.0.0"
      }
    },
    "node_modules/ajv": {
      "version": "6.12.6",
      "resolved": "https://registry.npmjs.org/ajv/-/ajv-6.12.6.tgz",
      "integrity": "sha512-j3fVLgvTo527anyYyJOGTYJbG+vnnQYvE0m5mmkc1TK+nxAppkCLMIL0aZ4dblVCNoGShhm+kzE4ZUykBoMg4g==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "fast-deep-equal": "^3.1.1",
        "fast-json-stable-stringify": "^2.0.0",
        "json-schema-traverse": "^0.4.1",
        "uri-js": "^4.2.2"
      },
      "funding": {
        "type": "github",
        "url": "https://github.com/sponsors/epoberezkin"
      }
    },
    "node_modules/ansi-regex": {
      "version": "6.1.0",
      "resolved": "https://registry.npmjs.org/ansi-regex/-/ansi-regex-6.1.0.tgz",
      "integrity": "sha512-7HSX4QQb4CspciLpVFwyRe79O3xsIZDDLER21kERQ71oaPodF8jL725AgJMFAYbooIqolJoRLuM81SpeUkpkvA==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-regex?sponsor=1"
      }
    },
    "node_modules/ansi-styles": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-4.3.0.tgz",
      "integrity": "sha512-zbB9rCJAT1rbjiVDb2hqKFHNYLxgtk8NURxZ3IZwD3F6NtxbXZQCnnSi1Lkx+IDohdPlFp222wVALIheZJQSEg==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "color-convert": "^2.0.1"
      },
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-styles?sponsor=1"
      }
    },
    "node_modules/any-promise": {
      "version": "1.3.0",
      "resolved": "https://registry.npmjs.org/any-promise/-/any-promise-1.3.0.tgz",
      "integrity": "sha512-7UvmKalWRt1wgjL1RrGxoSJW/0QZFIegpeGvZG9kjp8vrRu55XTHbwnqq2GpXm9uLbcuhxm3IqX9OB4MZR1b2A==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/anymatch": {
      "version": "3.1.3",
      "resolved": "https://registry.npmjs.org/anymatch/-/anymatch-3.1.3.tgz",
      "integrity": "sha512-KMReFUr0B4t+D+OBkjR3KYqvocp2XaSzO55UcB6mgQMd3KbcE+mWTyvVV7D/zsdEbNnV6acZUutkiHQXvTr1Rw==",
      "dev": true,
      "license": "ISC",
      "dependencies": {
        "normalize-path": "^3.0.0",
        "picomatch": "^2.0.4"
      },
      "engines": {
        "node": ">= 8"
      }
    },
    "node_modules/arg": {
      "version": "5.0.2",
      "resolved": "https://registry.npmjs.org/arg/-/arg-5.0.2.tgz",
      "integrity": "sha512-PYjyFOLKQ9y57JvQ6QLo8dAgNqswh8M1RMJYdQduT6xbWSgK36P/Z/v+p888pM69jMMfS8Xd8F6I1kQ/I9HUGg==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/argon2-browser": {
      "version": "1.18.0",
      "resolved": "https://registry.npmjs.org/argon2-browser/-/argon2-browser-1.18.0.tgz",
      "integrity": "sha512-ImVAGIItnFnvET1exhsQB7apRztcoC5TnlSqernMJDUjbc/DLq3UEYeXFrLPrlaIl8cVfwnXb6wX2KpFf2zxHw==",
      "license": "MIT"
    },
    "node_modules/argparse": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/argparse/-/argparse-2.0.1.tgz",
      "integrity": "sha512-8+9WqebbFzpX9OR+Wa6O29asIogeRMzcGtAINdpMHHyAg10f05aSFVBbcEqGf/PXw1EjAZ+q2/bEBg3DvurK3Q==",
      "dev": true,
      "license": "Python-2.0"
    },
    "node_modules/asynckit": {
      "version": "0.4.0",
      "resolved": "https://registry.npmjs.org/asynckit/-/asynckit-0.4.0.tgz",
      "integrity": "sha512-Oei9OH4tRh0YqU3GxhX79dM/mwVgvbZJaSNaRk+bshkj0S5cfHcgYakreBjrHwatXKbz+IoIdYLxrKim2MjW0Q==",
      "license": "MIT"
    },
    "node_modules/autoprefixer": {
      "version": "10.4.21",
      "resolved": "https://registry.npmjs.org/autoprefixer/-/autoprefixer-10.4.21.tgz",
      "integrity": "sha512-O+A6LWV5LDHSJD3LjHYoNi4VLsj/Whi7k6zG12xTYaU4cQ8oxQGckXNX8cRHK5yOZ/ppVHe0ZBXGzSV9jXdVbQ==",
      "dev": true,
      "funding": [
        {
          "type": "opencollective",
          "url": "https://opencollective.com/postcss/"
        },
        {
          "type": "tidelift",
          "url": "https://tidelift.com/funding/github/npm/autoprefixer"
        },
        {
          "type": "github",
          "url": "https://github.com/sponsors/ai"
        }
      ],
      "license": "MIT",
      "dependencies": {
        "browserslist": "^4.24.4",
        "caniuse-lite": "^1.0.30001702",
        "fraction.js": "^4.3.7",
        "normalize-range": "^0.1.2",
        "picocolors": "^1.1.1",
        "postcss-value-parser": "^4.2.0"
      },
      "bin": {
        "autoprefixer": "bin/autoprefixer"
      },
      "engines": {
        "node": "^10 || ^12 || >=14"
      },
      "peerDependencies": {
        "postcss": "^8.1.0"
      }
    },
    "node_modules/axios": {
      "version": "1.8.4",
      "resolved": "https://registry.npmjs.org/axios/-/axios-1.8.4.tgz",
      "integrity": "sha512-eBSYY4Y68NNlHbHBMdeDmKNtDgXWhQsJcGqzO3iLUM0GraQFSS9cVgPX5I9b3lbdFKyYoAEGAZF1DwhTaljNAw==",
      "license": "MIT",
      "dependencies": {
        "follow-redirects": "^1.15.6",
        "form-data": "^4.0.0",
        "proxy-from-env": "^1.1.0"
      }
    },
    "node_modules/balanced-match": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/balanced-match/-/balanced-match-1.0.2.tgz",
      "integrity": "sha512-3oSeUO0TMV67hN1AmbXsK4yaqU7tjiHlbxRDZOpH0KW9+CeX4bRAaX0Anxt0tx2MrpRpWwQaPwIlISEJhYU5Pw==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/binary-extensions": {
      "version": "2.3.0",
      "resolved": "https://registry.npmjs.org/binary-extensions/-/binary-extensions-2.3.0.tgz",
      "integrity": "sha512-Ceh+7ox5qe7LJuLHoY0feh3pHuUDHAcRUeyL2VYghZwfpkNIy/+8Ocg0a3UuSoYzavmylwuLWQOf3hl0jjMMIw==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/brace-expansion": {
      "version": "1.1.11",
      "resolved": "https://registry.npmjs.org/brace-expansion/-/brace-expansion-1.1.11.tgz",
      "integrity": "sha512-iCuPHDFgrHX7H2vEI/5xpz07zSHB00TpugqhmYtVmMO6518mCuRMoOYFldEBl0g187ufozdaHgWKcYFb61qGiA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "balanced-match": "^1.0.0",
        "concat-map": "0.0.1"
      }
    },
    "node_modules/braces": {
      "version": "3.0.3",
      "resolved": "https://registry.npmjs.org/braces/-/braces-3.0.3.tgz",
      "integrity": "sha512-yQbXgO/OSZVD2IsiLlro+7Hf6Q18EJrKSEsdoMzKePKXct3gvD8oLcOQdIzGupr5Fj+EDe8gO/lxc1BzfMpxvA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "fill-range": "^7.1.1"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/browserslist": {
      "version": "4.24.4",
      "resolved": "https://registry.npmjs.org/browserslist/-/browserslist-4.24.4.tgz",
      "integrity": "sha512-KDi1Ny1gSePi1vm0q4oxSF8b4DR44GF4BbmS2YdhPLOEqd8pDviZOGH/GsmRwoWJ2+5Lr085X7naowMwKHDG1A==",
      "dev": true,
      "funding": [
        {
          "type": "opencollective",
          "url": "https://opencollective.com/browserslist"
        },
        {
          "type": "tidelift",
          "url": "https://tidelift.com/funding/github/npm/browserslist"
        },
        {
          "type": "github",
          "url": "https://github.com/sponsors/ai"
        }
      ],
      "license": "MIT",
      "dependencies": {
        "caniuse-lite": "^1.0.30001688",
        "electron-to-chromium": "^1.5.73",
        "node-releases": "^2.0.19",
        "update-browserslist-db": "^1.1.1"
      },
      "bin": {
        "browserslist": "cli.js"
      },
      "engines": {
        "node": "^6 || ^7 || ^8 || ^9 || ^10 || ^11 || ^12 || >=13.7"
      }
    },
    "node_modules/call-bind-apply-helpers": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/call-bind-apply-helpers/-/call-bind-apply-helpers-1.0.2.tgz",
      "integrity": "sha512-Sp1ablJ0ivDkSzjcaJdxEunN5/XvksFJ2sMBFfq6x0ryhQV/2b/KwFe21cMpmHtPOSij8K99/wSfoEuTObmuMQ==",
      "license": "MIT",
      "dependencies": {
        "es-errors": "^1.3.0",
        "function-bind": "^1.1.2"
      },
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/callsites": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/callsites/-/callsites-3.1.0.tgz",
      "integrity": "sha512-P8BjAsXvZS+VIDUI11hHCQEv74YT67YUi5JJFNWIqL235sBmjX4+qx9Muvls5ivyNENctx46xQLQ3aTuE7ssaQ==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/camelcase-css": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/camelcase-css/-/camelcase-css-2.0.1.tgz",
      "integrity": "sha512-QOSvevhslijgYwRx6Rv7zKdMF8lbRmx+uQGx2+vDc+KI/eBnsy9kit5aj23AgGu3pa4t9AgwbnXWqS+iOY+2aA==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">= 6"
      }
    },
    "node_modules/caniuse-lite": {
      "version": "1.0.30001707",
      "resolved": "https://registry.npmjs.org/caniuse-lite/-/caniuse-lite-1.0.30001707.tgz",
      "integrity": "sha512-3qtRjw/HQSMlDWf+X79N206fepf4SOOU6SQLMaq/0KkZLmSjPxAkBOQQ+FxbHKfHmYLZFfdWsO3KA90ceHPSnw==",
      "dev": true,
      "funding": [
        {
          "type": "opencollective",
          "url": "https://opencollective.com/browserslist"
        },
        {
          "type": "tidelift",
          "url": "https://tidelift.com/funding/github/npm/caniuse-lite"
        },
        {
          "type": "github",
          "url": "https://github.com/sponsors/ai"
        }
      ],
      "license": "CC-BY-4.0"
    },
    "node_modules/chalk": {
      "version": "4.1.2",
      "resolved": "https://registry.npmjs.org/chalk/-/chalk-4.1.2.tgz",
      "integrity": "sha512-oKnbhFyRIXpUuez8iBMmyEa4nbj4IOQyuhc/wy9kY7/WVPcwIO9VA668Pu8RkO7+0G76SLROeyw9CpQ061i4mA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "ansi-styles": "^4.1.0",
        "supports-color": "^7.1.0"
      },
      "engines": {
        "node": ">=10"
      },
      "funding": {
        "url": "https://github.com/chalk/chalk?sponsor=1"
      }
    },
    "node_modules/chokidar": {
      "version": "3.6.0",
      "resolved": "https://registry.npmjs.org/chokidar/-/chokidar-3.6.0.tgz",
      "integrity": "sha512-7VT13fmjotKpGipCW9JEQAusEPE+Ei8nl6/g4FBAmIm0GOOLMua9NDDo/DWp0ZAxCr3cPq5ZpBqmPAQgDda2Pw==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "anymatch": "~3.1.2",
        "braces": "~3.0.2",
        "glob-parent": "~5.1.2",
        "is-binary-path": "~2.1.0",
        "is-glob": "~4.0.1",
        "normalize-path": "~3.0.0",
        "readdirp": "~3.6.0"
      },
      "engines": {
        "node": ">= 8.10.0"
      },
      "funding": {
        "url": "https://paulmillr.com/funding/"
      },
      "optionalDependencies": {
        "fsevents": "~2.3.2"
      }
    },
    "node_modules/chokidar/node_modules/glob-parent": {
      "version": "5.1.2",
      "resolved": "https://registry.npmjs.org/glob-parent/-/glob-parent-5.1.2.tgz",
      "integrity": "sha512-AOIgSQCepiJYwP3ARnGx+5VnTu2HBYdzbGP45eLw1vr3zB3vZLeyed1sC9hnbcOc9/SrMyM5RPQrkGz4aS9Zow==",
      "dev": true,
      "license": "ISC",
      "dependencies": {
        "is-glob": "^4.0.1"
      },
      "engines": {
        "node": ">= 6"
      }
    },
    "node_modules/clsx": {
      "version": "2.1.1",
      "resolved": "https://registry.npmjs.org/clsx/-/clsx-2.1.1.tgz",
      "integrity": "sha512-eYm0QWBtUrBWZWG0d386OGAw16Z995PiOVo2B7bjWSbHedGl5e0ZWaq65kOGgUSNesEIDkB9ISbTg/JK9dhCZA==",
      "license": "MIT",
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/color-convert": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/color-convert/-/color-convert-2.0.1.tgz",
      "integrity": "sha512-RRECPsj7iu/xb5oKYcsFHSppFNnsj/52OVTRKb4zP5onXwVF3zVmmToNcOfGC+CRDpfK/U584fMg38ZHCaElKQ==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "color-name": "~1.1.4"
      },
      "engines": {
        "node": ">=7.0.0"
      }
    },
    "node_modules/color-name": {
      "version": "1.1.4",
      "resolved": "https://registry.npmjs.org/color-name/-/color-name-1.1.4.tgz",
      "integrity": "sha512-dOy+3AuW3a2wNbZHIuMZpTcgjGuLU/uBL/ubcZF9OXbDo8ff4O8yVp5Bf0efS8uEoYo5q4Fx7dY9OgQGXgAsQA==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/combined-stream": {
      "version": "1.0.8",
      "resolved": "https://registry.npmjs.org/combined-stream/-/combined-stream-1.0.8.tgz",
      "integrity": "sha512-FQN4MRfuJeHf7cBbBMJFXhKSDq+2kAArBlmRBvcvFE5BB1HZKXtSFASDhdlz9zOYwxh8lDdnvmMOe/+5cdoEdg==",
      "license": "MIT",
      "dependencies": {
        "delayed-stream": "~1.0.0"
      },
      "engines": {
        "node": ">= 0.8"
      }
    },
    "node_modules/commander": {
      "version": "4.1.1",
      "resolved": "https://registry.npmjs.org/commander/-/commander-4.1.1.tgz",
      "integrity": "sha512-NOKm8xhkzAjzFx8B2v5OAHT+u5pRQc2UCa2Vq9jYL/31o2wi9mxBA7LIFs3sV5VSC49z6pEhfbMULvShKj26WA==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">= 6"
      }
    },
    "node_modules/concat-map": {
      "version": "0.0.1",
      "resolved": "https://registry.npmjs.org/concat-map/-/concat-map-0.0.1.tgz",
      "integrity": "sha512-/Srv4dswyQNBfohGpz9o6Yb3Gz3SrUDqBH5rTuhGR7ahtlbYKnVxw2bCFMRljaA7EXHaXZ8wsHdodFvbkhKmqg==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/convert-source-map": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/convert-source-map/-/convert-source-map-2.0.0.tgz",
      "integrity": "sha512-Kvp459HrV2FEJ1CAsi1Ku+MY3kasH19TFykTz2xWmMeq6bk2NU3XXvfJ+Q61m0xktWwt+1HSYf3JZsTms3aRJg==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/cookie": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/cookie/-/cookie-1.0.2.tgz",
      "integrity": "sha512-9Kr/j4O16ISv8zBBhJoi4bXOYNTkFLOqSL3UDB0njXxCXNezjeyVrJyGOWtgfs/q2km1gwBcfH8q1yEGoMYunA==",
      "license": "MIT",
      "engines": {
        "node": ">=18"
      }
    },
    "node_modules/cross-spawn": {
      "version": "7.0.6",
      "resolved": "https://registry.npmjs.org/cross-spawn/-/cross-spawn-7.0.6.tgz",
      "integrity": "sha512-uV2QOWP2nWzsy2aMp8aRibhi9dlzF5Hgh5SHaB9OiTGEyDTiJJyx0uy51QXdyWbtAHNua4XJzUKca3OzKUd3vA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "path-key": "^3.1.0",
        "shebang-command": "^2.0.0",
        "which": "^2.0.1"
      },
      "engines": {
        "node": ">= 8"
      }
    },
    "node_modules/crypto-js": {
      "version": "4.2.0",
      "resolved": "https://registry.npmjs.org/crypto-js/-/crypto-js-4.2.0.tgz",
      "integrity": "sha512-KALDyEYgpY+Rlob/iriUtjV6d5Eq+Y191A5g4UqLAi8CyGP9N1+FdVbkc1SxKc2r4YAYqG8JzO2KGL+AizD70Q==",
      "license": "MIT"
    },
    "node_modules/cssesc": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/cssesc/-/cssesc-3.0.0.tgz",
      "integrity": "sha512-/Tb/JcjK111nNScGob5MNtsntNM1aCNUDipB/TkwZFhyDrrE47SOx/18wF2bbjgc3ZzCSKW1T5nt5EbFoAz/Vg==",
      "dev": true,
      "license": "MIT",
      "bin": {
        "cssesc": "bin/cssesc"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/csstype": {
      "version": "3.1.3",
      "resolved": "https://registry.npmjs.org/csstype/-/csstype-3.1.3.tgz",
      "integrity": "sha512-M1uQkMl8rQK/szD0LNhtqxIPLpimGm8sOBwU7lLnCpSbTyY3yeU1Vc7l4KT5zT4s/yOxHH5O7tIuuLOCnLADRw==",
      "devOptional": true,
      "license": "MIT"
    },
    "node_modules/debug": {
      "version": "4.4.0",
      "resolved": "https://registry.npmjs.org/debug/-/debug-4.4.0.tgz",
      "integrity": "sha512-6WTZ/IxCY/T6BALoZHaE4ctp9xm+Z5kY/pzYaCHRFeyVhojxlrm+46y68HA6hr0TcwEssoxNiDEUJQjfPZ/RYA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "ms": "^2.1.3"
      },
      "engines": {
        "node": ">=6.0"
      },
      "peerDependenciesMeta": {
        "supports-color": {
          "optional": true
        }
      }
    },
    "node_modules/deep-is": {
      "version": "0.1.4",
      "resolved": "https://registry.npmjs.org/deep-is/-/deep-is-0.1.4.tgz",
      "integrity": "sha512-oIPzksmTg4/MriiaYGO+okXDT7ztn/w3Eptv/+gSIdMdKsJo0u4CfYNFJPy+4SKMuCqGw2wxnA+URMg3t8a/bQ==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/delayed-stream": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/delayed-stream/-/delayed-stream-1.0.0.tgz",
      "integrity": "sha512-ZySD7Nf91aLB0RxL4KGrKHBXl7Eds1DAmEdcoVawXnLD7SDhpNgtuII2aAkg7a7QS41jxPSZ17p4VdGnMHk3MQ==",
      "license": "MIT",
      "engines": {
        "node": ">=0.4.0"
      }
    },
    "node_modules/didyoumean": {
      "version": "1.2.2",
      "resolved": "https://registry.npmjs.org/didyoumean/-/didyoumean-1.2.2.tgz",
      "integrity": "sha512-gxtyfqMg7GKyhQmb056K7M3xszy/myH8w+B4RT+QXBQsvAOdc3XymqDDPHx1BgPgsdAA5SIifona89YtRATDzw==",
      "dev": true,
      "license": "Apache-2.0"
    },
    "node_modules/dlv": {
      "version": "1.1.3",
      "resolved": "https://registry.npmjs.org/dlv/-/dlv-1.1.3.tgz",
      "integrity": "sha512-+HlytyjlPKnIG8XuRG8WvmBP8xs8P71y+SKKS6ZXWoEgLuePxtDoUEiH7WkdePWrQ5JBpE6aoVqfZfJUQkjXwA==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/dompurify": {
      "version": "3.2.5",
      "resolved": "https://registry.npmjs.org/dompurify/-/dompurify-3.2.5.tgz",
      "integrity": "sha512-mLPd29uoRe9HpvwP2TxClGQBzGXeEC/we/q+bFlmPPmj2p2Ugl3r6ATu/UU1v77DXNcehiBg9zsr1dREyA/dJQ==",
      "license": "(MPL-2.0 OR Apache-2.0)",
      "optionalDependencies": {
        "@types/trusted-types": "^2.0.7"
      }
    },
    "node_modules/dunder-proto": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/dunder-proto/-/dunder-proto-1.0.1.tgz",
      "integrity": "sha512-KIN/nDJBQRcXw0MLVhZE9iQHmG68qAVIBg9CqmUYjmQIhgij9U5MFvrqkUL5FbtyyzZuOeOt0zdeRe4UY7ct+A==",
      "license": "MIT",
      "dependencies": {
        "call-bind-apply-helpers": "^1.0.1",
        "es-errors": "^1.3.0",
        "gopd": "^1.2.0"
      },
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/eastasianwidth": {
      "version": "0.2.0",
      "resolved": "https://registry.npmjs.org/eastasianwidth/-/eastasianwidth-0.2.0.tgz",
      "integrity": "sha512-I88TYZWc9XiYHRQ4/3c5rjjfgkjhLyW2luGIheGERbNQ6OY7yTybanSpDXZa8y7VUP9YmDcYa+eyq4ca7iLqWA==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/electron-to-chromium": {
      "version": "1.5.128",
      "resolved": "https://registry.npmjs.org/electron-to-chromium/-/electron-to-chromium-1.5.128.tgz",
      "integrity": "sha512-bo1A4HH/NS522Ws0QNFIzyPcyUUNV/yyy70Ho1xqfGYzPUme2F/xr4tlEOuM6/A538U1vDA7a4XfCd1CKRegKQ==",
      "dev": true,
      "license": "ISC"
    },
    "node_modules/emoji-regex": {
      "version": "9.2.2",
      "resolved": "https://registry.npmjs.org/emoji-regex/-/emoji-regex-9.2.2.tgz",
      "integrity": "sha512-L18DaJsXSUk2+42pv8mLs5jJT2hqFkFE4j21wOmgbUqsZ2hL72NsUU785g9RXgo3s0ZNgVl42TiHp3ZtOv/Vyg==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/es-define-property": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/es-define-property/-/es-define-property-1.0.1.tgz",
      "integrity": "sha512-e3nRfgfUZ4rNGL232gUgX06QNyyez04KdjFrF+LTRoOXmrOgFKDg4BCdsjW8EnT69eqdYGmRpJwiPVYNrCaW3g==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/es-errors": {
      "version": "1.3.0",
      "resolved": "https://registry.npmjs.org/es-errors/-/es-errors-1.3.0.tgz",
      "integrity": "sha512-Zf5H2Kxt2xjTvbJvP2ZWLEICxA6j+hAmMzIlypy4xcBg1vKVnx89Wy0GbS+kf5cwCVFFzdCFh2XSCFNULS6csw==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/es-object-atoms": {
      "version": "1.1.1",
      "resolved": "https://registry.npmjs.org/es-object-atoms/-/es-object-atoms-1.1.1.tgz",
      "integrity": "sha512-FGgH2h8zKNim9ljj7dankFPcICIK9Cp5bm+c2gQSYePhpaG5+esrLODihIorn+Pe6FGJzWhXQotPv73jTaldXA==",
      "license": "MIT",
      "dependencies": {
        "es-errors": "^1.3.0"
      },
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/es-set-tostringtag": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/es-set-tostringtag/-/es-set-tostringtag-2.1.0.tgz",
      "integrity": "sha512-j6vWzfrGVfyXxge+O0x5sh6cvxAog0a/4Rdd2K36zCMV5eJ+/+tOAngRO8cODMNWbVRdVlmGZQL2YS3yR8bIUA==",
      "license": "MIT",
      "dependencies": {
        "es-errors": "^1.3.0",
        "get-intrinsic": "^1.2.6",
        "has-tostringtag": "^1.0.2",
        "hasown": "^2.0.2"
      },
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/esbuild": {
      "version": "0.25.2",
      "resolved": "https://registry.npmjs.org/esbuild/-/esbuild-0.25.2.tgz",
      "integrity": "sha512-16854zccKPnC+toMywC+uKNeYSv+/eXkevRAfwRD/G9Cleq66m8XFIrigkbvauLLlCfDL45Q2cWegSg53gGBnQ==",
      "dev": true,
      "hasInstallScript": true,
      "license": "MIT",
      "bin": {
        "esbuild": "bin/esbuild"
      },
      "engines": {
        "node": ">=18"
      },
      "optionalDependencies": {
        "@esbuild/aix-ppc64": "0.25.2",
        "@esbuild/android-arm": "0.25.2",
        "@esbuild/android-arm64": "0.25.2",
        "@esbuild/android-x64": "0.25.2",
        "@esbuild/darwin-arm64": "0.25.2",
        "@esbuild/darwin-x64": "0.25.2",
        "@esbuild/freebsd-arm64": "0.25.2",
        "@esbuild/freebsd-x64": "0.25.2",
        "@esbuild/linux-arm": "0.25.2",
        "@esbuild/linux-arm64": "0.25.2",
        "@esbuild/linux-ia32": "0.25.2",
        "@esbuild/linux-loong64": "0.25.2",
        "@esbuild/linux-mips64el": "0.25.2",
        "@esbuild/linux-ppc64": "0.25.2",
        "@esbuild/linux-riscv64": "0.25.2",
        "@esbuild/linux-s390x": "0.25.2",
        "@esbuild/linux-x64": "0.25.2",
        "@esbuild/netbsd-arm64": "0.25.2",
        "@esbuild/netbsd-x64": "0.25.2",
        "@esbuild/openbsd-arm64": "0.25.2",
        "@esbuild/openbsd-x64": "0.25.2",
        "@esbuild/sunos-x64": "0.25.2",
        "@esbuild/win32-arm64": "0.25.2",
        "@esbuild/win32-ia32": "0.25.2",
        "@esbuild/win32-x64": "0.25.2"
      }
    },
    "node_modules/escalade": {
      "version": "3.2.0",
      "resolved": "https://registry.npmjs.org/escalade/-/escalade-3.2.0.tgz",
      "integrity": "sha512-WUj2qlxaQtO4g6Pq5c29GTcWGDyd8itL8zTlipgECz3JesAiiOKotd8JU6otB3PACgG6xkJUyVhboMS+bje/jA==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/escape-string-regexp": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/escape-string-regexp/-/escape-string-regexp-4.0.0.tgz",
      "integrity": "sha512-TtpcNJ3XAzx3Gq8sWRzJaVajRs0uVxA2YAkdb1jm2YkPz4G6egUFAyA3n5vtEIZefPk5Wa4UXbKuS5fKkJWdgA==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=10"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/eslint": {
      "version": "9.23.0",
      "resolved": "https://registry.npmjs.org/eslint/-/eslint-9.23.0.tgz",
      "integrity": "sha512-jV7AbNoFPAY1EkFYpLq5bslU9NLNO8xnEeQXwErNibVryjk67wHVmddTBilc5srIttJDBrB0eMHKZBFbSIABCw==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@eslint-community/eslint-utils": "^4.2.0",
        "@eslint-community/regexpp": "^4.12.1",
        "@eslint/config-array": "^0.19.2",
        "@eslint/config-helpers": "^0.2.0",
        "@eslint/core": "^0.12.0",
        "@eslint/eslintrc": "^3.3.1",
        "@eslint/js": "9.23.0",
        "@eslint/plugin-kit": "^0.2.7",
        "@humanfs/node": "^0.16.6",
        "@humanwhocodes/module-importer": "^1.0.1",
        "@humanwhocodes/retry": "^0.4.2",
        "@types/estree": "^1.0.6",
        "@types/json-schema": "^7.0.15",
        "ajv": "^6.12.4",
        "chalk": "^4.0.0",
        "cross-spawn": "^7.0.6",
        "debug": "^4.3.2",
        "escape-string-regexp": "^4.0.0",
        "eslint-scope": "^8.3.0",
        "eslint-visitor-keys": "^4.2.0",
        "espree": "^10.3.0",
        "esquery": "^1.5.0",
        "esutils": "^2.0.2",
        "fast-deep-equal": "^3.1.3",
        "file-entry-cache": "^8.0.0",
        "find-up": "^5.0.0",
        "glob-parent": "^6.0.2",
        "ignore": "^5.2.0",
        "imurmurhash": "^0.1.4",
        "is-glob": "^4.0.0",
        "json-stable-stringify-without-jsonify": "^1.0.1",
        "lodash.merge": "^4.6.2",
        "minimatch": "^3.1.2",
        "natural-compare": "^1.4.0",
        "optionator": "^0.9.3"
      },
      "bin": {
        "eslint": "bin/eslint.js"
      },
      "engines": {
        "node": "^18.18.0 || ^20.9.0 || >=21.1.0"
      },
      "funding": {
        "url": "https://eslint.org/donate"
      },
      "peerDependencies": {
        "jiti": "*"
      },
      "peerDependenciesMeta": {
        "jiti": {
          "optional": true
        }
      }
    },
    "node_modules/eslint-plugin-react-hooks": {
      "version": "5.2.0",
      "resolved": "https://registry.npmjs.org/eslint-plugin-react-hooks/-/eslint-plugin-react-hooks-5.2.0.tgz",
      "integrity": "sha512-+f15FfK64YQwZdJNELETdn5ibXEUQmW1DZL6KXhNnc2heoy/sg9VJJeT7n8TlMWouzWqSWavFkIhHyIbIAEapg==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=10"
      },
      "peerDependencies": {
        "eslint": "^3.0.0 || ^4.0.0 || ^5.0.0 || ^6.0.0 || ^7.0.0 || ^8.0.0-0 || ^9.0.0"
      }
    },
    "node_modules/eslint-plugin-react-refresh": {
      "version": "0.4.19",
      "resolved": "https://registry.npmjs.org/eslint-plugin-react-refresh/-/eslint-plugin-react-refresh-0.4.19.tgz",
      "integrity": "sha512-eyy8pcr/YxSYjBoqIFSrlbn9i/xvxUFa8CjzAYo9cFjgGXqq1hyjihcpZvxRLalpaWmueWR81xn7vuKmAFijDQ==",
      "dev": true,
      "license": "MIT",
      "peerDependencies": {
        "eslint": ">=8.40"
      }
    },
    "node_modules/eslint-scope": {
      "version": "8.3.0",
      "resolved": "https://registry.npmjs.org/eslint-scope/-/eslint-scope-8.3.0.tgz",
      "integrity": "sha512-pUNxi75F8MJ/GdeKtVLSbYg4ZI34J6C0C7sbL4YOp2exGwen7ZsuBqKzUhXd0qMQ362yET3z+uPwKeg/0C2XCQ==",
      "dev": true,
      "license": "BSD-2-Clause",
      "dependencies": {
        "esrecurse": "^4.3.0",
        "estraverse": "^5.2.0"
      },
      "engines": {
        "node": "^18.18.0 || ^20.9.0 || >=21.1.0"
      },
      "funding": {
        "url": "https://opencollective.com/eslint"
      }
    },
    "node_modules/eslint-visitor-keys": {
      "version": "4.2.0",
      "resolved": "https://registry.npmjs.org/eslint-visitor-keys/-/eslint-visitor-keys-4.2.0.tgz",
      "integrity": "sha512-UyLnSehNt62FFhSwjZlHmeokpRK59rcz29j+F1/aDgbkbRTk7wIc9XzdoasMUbRNKDM0qQt/+BJ4BrpFeABemw==",
      "dev": true,
      "license": "Apache-2.0",
      "engines": {
        "node": "^18.18.0 || ^20.9.0 || >=21.1.0"
      },
      "funding": {
        "url": "https://opencollective.com/eslint"
      }
    },
    "node_modules/espree": {
      "version": "10.3.0",
      "resolved": "https://registry.npmjs.org/espree/-/espree-10.3.0.tgz",
      "integrity": "sha512-0QYC8b24HWY8zjRnDTL6RiHfDbAWn63qb4LMj1Z4b076A4une81+z03Kg7l7mn/48PUTqoLptSXez8oknU8Clg==",
      "dev": true,
      "license": "BSD-2-Clause",
      "dependencies": {
        "acorn": "^8.14.0",
        "acorn-jsx": "^5.3.2",
        "eslint-visitor-keys": "^4.2.0"
      },
      "engines": {
        "node": "^18.18.0 || ^20.9.0 || >=21.1.0"
      },
      "funding": {
        "url": "https://opencollective.com/eslint"
      }
    },
    "node_modules/esquery": {
      "version": "1.6.0",
      "resolved": "https://registry.npmjs.org/esquery/-/esquery-1.6.0.tgz",
      "integrity": "sha512-ca9pw9fomFcKPvFLXhBKUK90ZvGibiGOvRJNbjljY7s7uq/5YO4BOzcYtJqExdx99rF6aAcnRxHmcUHcz6sQsg==",
      "dev": true,
      "license": "BSD-3-Clause",
      "dependencies": {
        "estraverse": "^5.1.0"
      },
      "engines": {
        "node": ">=0.10"
      }
    },
    "node_modules/esrecurse": {
      "version": "4.3.0",
      "resolved": "https://registry.npmjs.org/esrecurse/-/esrecurse-4.3.0.tgz",
      "integrity": "sha512-KmfKL3b6G+RXvP8N1vr3Tq1kL/oCFgn2NYXEtqP8/L3pKapUA4G8cFVaoF3SU323CD4XypR/ffioHmkti6/Tag==",
      "dev": true,
      "license": "BSD-2-Clause",
      "dependencies": {
        "estraverse": "^5.2.0"
      },
      "engines": {
        "node": ">=4.0"
      }
    },
    "node_modules/estraverse": {
      "version": "5.3.0",
      "resolved": "https://registry.npmjs.org/estraverse/-/estraverse-5.3.0.tgz",
      "integrity": "sha512-MMdARuVEQziNTeJD8DgMqmhwR11BRQ/cBP+pLtYdSTnf3MIO8fFeiINEbX36ZdNlfU/7A9f3gUw49B3oQsvwBA==",
      "dev": true,
      "license": "BSD-2-Clause",
      "engines": {
        "node": ">=4.0"
      }
    },
    "node_modules/esutils": {
      "version": "2.0.3",
      "resolved": "https://registry.npmjs.org/esutils/-/esutils-2.0.3.tgz",
      "integrity": "sha512-kVscqXk4OCp68SZ0dkgEKVi6/8ij300KBWTJq32P/dYeWTSwK41WyTxalN1eRmA5Z9UU/LX9D7FWSmV9SAYx6g==",
      "dev": true,
      "license": "BSD-2-Clause",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/fast-deep-equal": {
      "version": "3.1.3",
      "resolved": "https://registry.npmjs.org/fast-deep-equal/-/fast-deep-equal-3.1.3.tgz",
      "integrity": "sha512-f3qQ9oQy9j2AhBe/H9VC91wLmKBCCU/gDOnKNAYG5hswO7BLKj09Hc5HYNz9cGI++xlpDCIgDaitVs03ATR84Q==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/fast-glob": {
      "version": "3.3.3",
      "resolved": "https://registry.npmjs.org/fast-glob/-/fast-glob-3.3.3.tgz",
      "integrity": "sha512-7MptL8U0cqcFdzIzwOTHoilX9x5BrNqye7Z/LuC7kCMRio1EMSyqRK3BEAUD7sXRq4iT4AzTVuZdhgQ2TCvYLg==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@nodelib/fs.stat": "^2.0.2",
        "@nodelib/fs.walk": "^1.2.3",
        "glob-parent": "^5.1.2",
        "merge2": "^1.3.0",
        "micromatch": "^4.0.8"
      },
      "engines": {
        "node": ">=8.6.0"
      }
    },
    "node_modules/fast-glob/node_modules/glob-parent": {
      "version": "5.1.2",
      "resolved": "https://registry.npmjs.org/glob-parent/-/glob-parent-5.1.2.tgz",
      "integrity": "sha512-AOIgSQCepiJYwP3ARnGx+5VnTu2HBYdzbGP45eLw1vr3zB3vZLeyed1sC9hnbcOc9/SrMyM5RPQrkGz4aS9Zow==",
      "dev": true,
      "license": "ISC",
      "dependencies": {
        "is-glob": "^4.0.1"
      },
      "engines": {
        "node": ">= 6"
      }
    },
    "node_modules/fast-json-stable-stringify": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/fast-json-stable-stringify/-/fast-json-stable-stringify-2.1.0.tgz",
      "integrity": "sha512-lhd/wF+Lk98HZoTCtlVraHtfh5XYijIjalXck7saUtuanSDyLMxnHhSXEDJqHxD7msR8D0uCmqlkwjCV8xvwHw==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/fast-levenshtein": {
      "version": "2.0.6",
      "resolved": "https://registry.npmjs.org/fast-levenshtein/-/fast-levenshtein-2.0.6.tgz",
      "integrity": "sha512-DCXu6Ifhqcks7TZKY3Hxp3y6qphY5SJZmrWMDrKcERSOXWQdMhU9Ig/PYrzyw/ul9jOIyh0N4M0tbC5hodg8dw==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/fastq": {
      "version": "1.19.1",
      "resolved": "https://registry.npmjs.org/fastq/-/fastq-1.19.1.tgz",
      "integrity": "sha512-GwLTyxkCXjXbxqIhTsMI2Nui8huMPtnxg7krajPJAjnEG/iiOS7i+zCtWGZR9G0NBKbXKh6X9m9UIsYX/N6vvQ==",
      "dev": true,
      "license": "ISC",
      "dependencies": {
        "reusify": "^1.0.4"
      }
    },
    "node_modules/file-entry-cache": {
      "version": "8.0.0",
      "resolved": "https://registry.npmjs.org/file-entry-cache/-/file-entry-cache-8.0.0.tgz",
      "integrity": "sha512-XXTUwCvisa5oacNGRP9SfNtYBNAMi+RPwBFmblZEF7N7swHYQS6/Zfk7SRwx4D5j3CH211YNRco1DEMNVfZCnQ==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "flat-cache": "^4.0.0"
      },
      "engines": {
        "node": ">=16.0.0"
      }
    },
    "node_modules/fill-range": {
      "version": "7.1.1",
      "resolved": "https://registry.npmjs.org/fill-range/-/fill-range-7.1.1.tgz",
      "integrity": "sha512-YsGpe3WHLK8ZYi4tWDg2Jy3ebRz2rXowDxnld4bkQB00cc/1Zw9AWnC0i9ztDJitivtQvaI9KaLyKrc+hBW0yg==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "to-regex-range": "^5.0.1"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/find-up": {
      "version": "5.0.0",
      "resolved": "https://registry.npmjs.org/find-up/-/find-up-5.0.0.tgz",
      "integrity": "sha512-78/PXT1wlLLDgTzDs7sjq9hzz0vXD+zn+7wypEe4fXQxCmdmqfGsEPQxmiCSQI3ajFV91bVSsvNtrJRiW6nGng==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "locate-path": "^6.0.0",
        "path-exists": "^4.0.0"
      },
      "engines": {
        "node": ">=10"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/flat-cache": {
      "version": "4.0.1",
      "resolved": "https://registry.npmjs.org/flat-cache/-/flat-cache-4.0.1.tgz",
      "integrity": "sha512-f7ccFPK3SXFHpx15UIGyRJ/FJQctuKZ0zVuN3frBo4HnK3cay9VEW0R6yPYFHC0AgqhukPzKjq22t5DmAyqGyw==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "flatted": "^3.2.9",
        "keyv": "^4.5.4"
      },
      "engines": {
        "node": ">=16"
      }
    },
    "node_modules/flatted": {
      "version": "3.3.3",
      "resolved": "https://registry.npmjs.org/flatted/-/flatted-3.3.3.tgz",
      "integrity": "sha512-GX+ysw4PBCz0PzosHDepZGANEuFCMLrnRTiEy9McGjmkCQYwRq4A/X786G/fjM/+OjsWSU1ZrY5qyARZmO/uwg==",
      "dev": true,
      "license": "ISC"
    },
    "node_modules/follow-redirects": {
      "version": "1.15.9",
      "resolved": "https://registry.npmjs.org/follow-redirects/-/follow-redirects-1.15.9.tgz",
      "integrity": "sha512-gew4GsXizNgdoRyqmyfMHyAmXsZDk6mHkSxZFCzW9gwlbtOW44CDtYavM+y+72qD/Vq2l550kMF52DT8fOLJqQ==",
      "funding": [
        {
          "type": "individual",
          "url": "https://github.com/sponsors/RubenVerborgh"
        }
      ],
      "license": "MIT",
      "engines": {
        "node": ">=4.0"
      },
      "peerDependenciesMeta": {
        "debug": {
          "optional": true
        }
      }
    },
    "node_modules/foreground-child": {
      "version": "3.3.1",
      "resolved": "https://registry.npmjs.org/foreground-child/-/foreground-child-3.3.1.tgz",
      "integrity": "sha512-gIXjKqtFuWEgzFRJA9WCQeSJLZDjgJUOMCMzxtvFq/37KojM1BFGufqsCy0r4qSQmYLsZYMeyRqzIWOMup03sw==",
      "dev": true,
      "license": "ISC",
      "dependencies": {
        "cross-spawn": "^7.0.6",
        "signal-exit": "^4.0.1"
      },
      "engines": {
        "node": ">=14"
      },
      "funding": {
        "url": "https://github.com/sponsors/isaacs"
      }
    },
    "node_modules/form-data": {
      "version": "4.0.2",
      "resolved": "https://registry.npmjs.org/form-data/-/form-data-4.0.2.tgz",
      "integrity": "sha512-hGfm/slu0ZabnNt4oaRZ6uREyfCj6P4fT/n6A1rGV+Z0VdGXjfOhVUpkn6qVQONHGIFwmveGXyDs75+nr6FM8w==",
      "license": "MIT",
      "dependencies": {
        "asynckit": "^0.4.0",
        "combined-stream": "^1.0.8",
        "es-set-tostringtag": "^2.1.0",
        "mime-types": "^2.1.12"
      },
      "engines": {
        "node": ">= 6"
      }
    },
    "node_modules/fraction.js": {
      "version": "4.3.7",
      "resolved": "https://registry.npmjs.org/fraction.js/-/fraction.js-4.3.7.tgz",
      "integrity": "sha512-ZsDfxO51wGAXREY55a7la9LScWpwv9RxIrYABrlvOFBlH/ShPnrtsXeuUIfXKKOVicNxQ+o8JTbJvjS4M89yew==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": "*"
      },
      "funding": {
        "type": "patreon",
        "url": "https://github.com/sponsors/rawify"
      }
    },
    "node_modules/framer-motion": {
      "version": "12.6.5",
      "resolved": "https://registry.npmjs.org/framer-motion/-/framer-motion-12.6.5.tgz",
      "integrity": "sha512-MKvnWov0paNjvRJuIy6x418w23tFqRfS6CXHhZrCiSEpXVlo/F+usr8v4/3G6O0u7CpsaO1qop+v4Ip7PRCBqQ==",
      "license": "MIT",
      "dependencies": {
        "motion-dom": "^12.6.5",
        "motion-utils": "^12.6.5",
        "tslib": "^2.4.0"
      },
      "peerDependencies": {
        "@emotion/is-prop-valid": "*",
        "react": "^18.0.0 || ^19.0.0",
        "react-dom": "^18.0.0 || ^19.0.0"
      },
      "peerDependenciesMeta": {
        "@emotion/is-prop-valid": {
          "optional": true
        },
        "react": {
          "optional": true
        },
        "react-dom": {
          "optional": true
        }
      }
    },
    "node_modules/fsevents": {
      "version": "2.3.3",
      "resolved": "https://registry.npmjs.org/fsevents/-/fsevents-2.3.3.tgz",
      "integrity": "sha512-5xoDfX+fL7faATnagmWPpbFtwh/R77WmMMqqHGS65C3vvB0YHrgF+B1YmZ3441tMj5n63k0212XNoJwzlhffQw==",
      "dev": true,
      "hasInstallScript": true,
      "license": "MIT",
      "optional": true,
      "os": [
        "darwin"
      ],
      "engines": {
        "node": "^8.16.0 || ^10.6.0 || >=11.0.0"
      }
    },
    "node_modules/function-bind": {
      "version": "1.1.2",
      "resolved": "https://registry.npmjs.org/function-bind/-/function-bind-1.1.2.tgz",
      "integrity": "sha512-7XHNxH7qX9xG5mIwxkhumTox/MIRNcOgDrxWsMt2pAr23WHp6MrRlN7FBSFpCpr+oVO0F744iUgR82nJMfG2SA==",
      "license": "MIT",
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/gensync": {
      "version": "1.0.0-beta.2",
      "resolved": "https://registry.npmjs.org/gensync/-/gensync-1.0.0-beta.2.tgz",
      "integrity": "sha512-3hN7NaskYvMDLQY55gnW3NQ+mesEAepTqlg+VEbj7zzqEMBVNhzcGYYeqFo/TlYz6eQiFcp1HcsCZO+nGgS8zg==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=6.9.0"
      }
    },
    "node_modules/get-intrinsic": {
      "version": "1.3.0",
      "resolved": "https://registry.npmjs.org/get-intrinsic/-/get-intrinsic-1.3.0.tgz",
      "integrity": "sha512-9fSjSaos/fRIVIp+xSJlE6lfwhES7LNtKaCBIamHsjr2na1BiABJPo0mOjjz8GJDURarmCPGqaiVg5mfjb98CQ==",
      "license": "MIT",
      "dependencies": {
        "call-bind-apply-helpers": "^1.0.2",
        "es-define-property": "^1.0.1",
        "es-errors": "^1.3.0",
        "es-object-atoms": "^1.1.1",
        "function-bind": "^1.1.2",
        "get-proto": "^1.0.1",
        "gopd": "^1.2.0",
        "has-symbols": "^1.1.0",
        "hasown": "^2.0.2",
        "math-intrinsics": "^1.1.0"
      },
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/get-proto": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/get-proto/-/get-proto-1.0.1.tgz",
      "integrity": "sha512-sTSfBjoXBp89JvIKIefqw7U2CCebsc74kiY6awiGogKtoSGbgjYE/G/+l9sF3MWFPNc9IcoOC4ODfKHfxFmp0g==",
      "license": "MIT",
      "dependencies": {
        "dunder-proto": "^1.0.1",
        "es-object-atoms": "^1.0.0"
      },
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/glob": {
      "version": "10.4.5",
      "resolved": "https://registry.npmjs.org/glob/-/glob-10.4.5.tgz",
      "integrity": "sha512-7Bv8RF0k6xjo7d4A/PxYLbUCfb6c+Vpd2/mB2yRDlew7Jb5hEXiCD9ibfO7wpk8i4sevK6DFny9h7EYbM3/sHg==",
      "dev": true,
      "license": "ISC",
      "dependencies": {
        "foreground-child": "^3.1.0",
        "jackspeak": "^3.1.2",
        "minimatch": "^9.0.4",
        "minipass": "^7.1.2",
        "package-json-from-dist": "^1.0.0",
        "path-scurry": "^1.11.1"
      },
      "bin": {
        "glob": "dist/esm/bin.mjs"
      },
      "funding": {
        "url": "https://github.com/sponsors/isaacs"
      }
    },
    "node_modules/glob-parent": {
      "version": "6.0.2",
      "resolved": "https://registry.npmjs.org/glob-parent/-/glob-parent-6.0.2.tgz",
      "integrity": "sha512-XxwI8EOhVQgWp6iDL+3b0r86f4d6AX6zSU55HfB4ydCEuXLXc5FcYeOu+nnGftS4TEju/11rt4KJPTMgbfmv4A==",
      "dev": true,
      "license": "ISC",
      "dependencies": {
        "is-glob": "^4.0.3"
      },
      "engines": {
        "node": ">=10.13.0"
      }
    },
    "node_modules/glob/node_modules/brace-expansion": {
      "version": "2.0.1",
      "resolved": "https://registry.npmjs.org/brace-expansion/-/brace-expansion-2.0.1.tgz",
      "integrity": "sha512-XnAIvQ8eM+kC6aULx6wuQiwVsnzsi9d3WxzV3FpWTGA19F621kwdbsAcFKXgKUHZWsy+mY6iL1sHTxWEFCytDA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "balanced-match": "^1.0.0"
      }
    },
    "node_modules/glob/node_modules/minimatch": {
      "version": "9.0.5",
      "resolved": "https://registry.npmjs.org/minimatch/-/minimatch-9.0.5.tgz",
      "integrity": "sha512-G6T0ZX48xgozx7587koeX9Ys2NYy6Gmv//P89sEte9V9whIapMNF4idKxnW2QtCcLiTWlb/wfCabAtAFWhhBow==",
      "dev": true,
      "license": "ISC",
      "dependencies": {
        "brace-expansion": "^2.0.1"
      },
      "engines": {
        "node": ">=16 || 14 >=14.17"
      },
      "funding": {
        "url": "https://github.com/sponsors/isaacs"
      }
    },
    "node_modules/globals": {
      "version": "15.15.0",
      "resolved": "https://registry.npmjs.org/globals/-/globals-15.15.0.tgz",
      "integrity": "sha512-7ACyT3wmyp3I61S4fG682L0VA2RGD9otkqGJIwNUMF1SWUombIIk+af1unuDYgMm082aHYwD+mzJvv9Iu8dsgg==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=18"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/gopd": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/gopd/-/gopd-1.2.0.tgz",
      "integrity": "sha512-ZUKRh6/kUFoAiTAtTYPZJ3hw9wNxx+BIBOijnlG9PnrJsCcSjs1wyyD6vJpaYtgnzDrKYRSqf3OO6Rfa93xsRg==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/has-flag": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/has-flag/-/has-flag-4.0.0.tgz",
      "integrity": "sha512-EykJT/Q1KjTWctppgIAgfSO0tKVuZUjhgMr17kqTumMl6Afv3EISleU7qZUzoXDFTAHTDC4NOoG/ZxU3EvlMPQ==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/has-symbols": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/has-symbols/-/has-symbols-1.1.0.tgz",
      "integrity": "sha512-1cDNdwJ2Jaohmb3sg4OmKaMBwuC48sYni5HUw2DvsC8LjGTLK9h+eb1X6RyuOHe4hT0ULCW68iomhjUoKUqlPQ==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/has-tostringtag": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/has-tostringtag/-/has-tostringtag-1.0.2.tgz",
      "integrity": "sha512-NqADB8VjPFLM2V0VvHUewwwsw0ZWBaIdgo+ieHtK3hasLz4qeCRjYcqfB6AQrBggRKppKF8L52/VqdVsO47Dlw==",
      "license": "MIT",
      "dependencies": {
        "has-symbols": "^1.0.3"
      },
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/hasown": {
      "version": "2.0.2",
      "resolved": "https://registry.npmjs.org/hasown/-/hasown-2.0.2.tgz",
      "integrity": "sha512-0hJU9SCPvmMzIBdZFqNPXWa6dqh7WdH0cII9y+CyS8rG3nL48Bclra9HmKhVVUHyPWNH5Y7xDwAB7bfgSjkUMQ==",
      "license": "MIT",
      "dependencies": {
        "function-bind": "^1.1.2"
      },
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/ignore": {
      "version": "5.3.2",
      "resolved": "https://registry.npmjs.org/ignore/-/ignore-5.3.2.tgz",
      "integrity": "sha512-hsBTNUqQTDwkWtcdYI2i06Y/nUBEsNEDJKjWdigLvegy8kDuJAS8uRlpkkcQpyEXL0Z/pjDy5HBmMjRCJ2gq+g==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">= 4"
      }
    },
    "node_modules/immer": {
      "version": "10.1.1",
      "resolved": "https://registry.npmjs.org/immer/-/immer-10.1.1.tgz",
      "integrity": "sha512-s2MPrmjovJcoMaHtx6K11Ra7oD05NT97w1IC5zpMkT6Atjr7H8LjaDd81iIxUYpMKSRRNMJE703M1Fhr/TctHw==",
      "license": "MIT",
      "funding": {
        "type": "opencollective",
        "url": "https://opencollective.com/immer"
      }
    },
    "node_modules/import-fresh": {
      "version": "3.3.1",
      "resolved": "https://registry.npmjs.org/import-fresh/-/import-fresh-3.3.1.tgz",
      "integrity": "sha512-TR3KfrTZTYLPB6jUjfx6MF9WcWrHL9su5TObK4ZkYgBdWKPOFoSoQIdEuTuR82pmtxH2spWG9h6etwfr1pLBqQ==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "parent-module": "^1.0.0",
        "resolve-from": "^4.0.0"
      },
      "engines": {
        "node": ">=6"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/imurmurhash": {
      "version": "0.1.4",
      "resolved": "https://registry.npmjs.org/imurmurhash/-/imurmurhash-0.1.4.tgz",
      "integrity": "sha512-JmXMZ6wuvDmLiHEml9ykzqO6lwFbof0GG4IkcGaENdCRDDmMVnny7s5HsIgHCbaq0w2MyPhDqkhTUgS2LU2PHA==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=0.8.19"
      }
    },
    "node_modules/is-binary-path": {
      "version": "2.1.0",
      "resolved": "https://registry.npmjs.org/is-binary-path/-/is-binary-path-2.1.0.tgz",
      "integrity": "sha512-ZMERYes6pDydyuGidse7OsHxtbI7WVeUEozgR/g7rd0xUimYNlvZRE/K2MgZTjWy725IfelLeVcEM97mmtRGXw==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "binary-extensions": "^2.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/is-core-module": {
      "version": "2.16.1",
      "resolved": "https://registry.npmjs.org/is-core-module/-/is-core-module-2.16.1.tgz",
      "integrity": "sha512-UfoeMA6fIJ8wTYFEUjelnaGI67v6+N7qXJEvQuIGa99l4xsCruSYOVSQ0uPANn4dAzm8lkYPaKLrrijLq7x23w==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "hasown": "^2.0.2"
      },
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/is-extglob": {
      "version": "2.1.1",
      "resolved": "https://registry.npmjs.org/is-extglob/-/is-extglob-2.1.1.tgz",
      "integrity": "sha512-SbKbANkN603Vi4jEZv49LeVJMn4yGwsbzZworEoyEiutsN3nJYdbO36zfhGJ6QEDpOZIFkDtnq5JRxmvl3jsoQ==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/is-fullwidth-code-point": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/is-fullwidth-code-point/-/is-fullwidth-code-point-3.0.0.tgz",
      "integrity": "sha512-zymm5+u+sCsSWyD9qNaejV3DFvhCKclKdizYaJUuHA83RLjb7nSuGnddCHGv0hk+KY7BMAlsWeK4Ueg6EV6XQg==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/is-glob": {
      "version": "4.0.3",
      "resolved": "https://registry.npmjs.org/is-glob/-/is-glob-4.0.3.tgz",
      "integrity": "sha512-xelSayHH36ZgE7ZWhli7pW34hNbNl8Ojv5KVmkJD4hBdD3th8Tfk9vYasLM+mXWOZhFkgZfxhLSnrwRr4elSSg==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "is-extglob": "^2.1.1"
      },
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/is-number": {
      "version": "7.0.0",
      "resolved": "https://registry.npmjs.org/is-number/-/is-number-7.0.0.tgz",
      "integrity": "sha512-41Cifkg6e8TylSpdtTpeLVMqvSBEVzTttHvERD741+pnZ8ANv0004MRL43QKPDlK9cGvNp6NZWZUBlbGXYxxng==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=0.12.0"
      }
    },
    "node_modules/isexe": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/isexe/-/isexe-2.0.0.tgz",
      "integrity": "sha512-RHxMLp9lnKHGHRng9QFhRCMbYAcVpn69smSGcq3f36xjgVVWThj4qqLbTLlq7Ssj8B+fIQ1EuCEGI2lKsyQeIw==",
      "dev": true,
      "license": "ISC"
    },
    "node_modules/jackspeak": {
      "version": "3.4.3",
      "resolved": "https://registry.npmjs.org/jackspeak/-/jackspeak-3.4.3.tgz",
      "integrity": "sha512-OGlZQpz2yfahA/Rd1Y8Cd9SIEsqvXkLVoSw/cgwhnhFMDbsQFeZYoJJ7bIZBS9BcamUW96asq/npPWugM+RQBw==",
      "dev": true,
      "license": "BlueOak-1.0.0",
      "dependencies": {
        "@isaacs/cliui": "^8.0.2"
      },
      "funding": {
        "url": "https://github.com/sponsors/isaacs"
      },
      "optionalDependencies": {
        "@pkgjs/parseargs": "^0.11.0"
      }
    },
    "node_modules/jiti": {
      "version": "1.21.7",
      "resolved": "https://registry.npmjs.org/jiti/-/jiti-1.21.7.tgz",
      "integrity": "sha512-/imKNG4EbWNrVjoNC/1H5/9GFy+tqjGBHCaSsN+P2RnPqjsLmv6UD3Ej+Kj8nBWaRAwyk7kK5ZUc+OEatnTR3A==",
      "dev": true,
      "license": "MIT",
      "bin": {
        "jiti": "bin/jiti.js"
      }
    },
    "node_modules/js-tokens": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/js-tokens/-/js-tokens-4.0.0.tgz",
      "integrity": "sha512-RdJUflcE3cUzKiMqQgsCu06FPu9UdIJO0beYbPhHN4k6apgJtifcoCtT9bcxOpYBtpD2kCM6Sbzg4CausW/PKQ==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/js-yaml": {
      "version": "4.1.0",
      "resolved": "https://registry.npmjs.org/js-yaml/-/js-yaml-4.1.0.tgz",
      "integrity": "sha512-wpxZs9NoxZaJESJGIZTyDEaYpl0FKSA+FB9aJiyemKhMwkxQg63h4T1KJgUGHpTqPDNRcmmYLugrRjJlBtWvRA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "argparse": "^2.0.1"
      },
      "bin": {
        "js-yaml": "bin/js-yaml.js"
      }
    },
    "node_modules/jsesc": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/jsesc/-/jsesc-3.1.0.tgz",
      "integrity": "sha512-/sM3dO2FOzXjKQhJuo0Q173wf2KOo8t4I8vHy6lF9poUp7bKT0/NHE8fPX23PwfhnykfqnC2xRxOnVw5XuGIaA==",
      "dev": true,
      "license": "MIT",
      "bin": {
        "jsesc": "bin/jsesc"
      },
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/json-buffer": {
      "version": "3.0.1",
      "resolved": "https://registry.npmjs.org/json-buffer/-/json-buffer-3.0.1.tgz",
      "integrity": "sha512-4bV5BfR2mqfQTJm+V5tPPdf+ZpuhiIvTuAB5g8kcrXOZpTT/QwwVRWBywX1ozr6lEuPdbHxwaJlm9G6mI2sfSQ==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/json-schema-traverse": {
      "version": "0.4.1",
      "resolved": "https://registry.npmjs.org/json-schema-traverse/-/json-schema-traverse-0.4.1.tgz",
      "integrity": "sha512-xbbCH5dCYU5T8LcEhhuh7HJ88HXuW3qsI3Y0zOZFKfZEHcpWiHU/Jxzk629Brsab/mMiHQti9wMP+845RPe3Vg==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/json-stable-stringify-without-jsonify": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/json-stable-stringify-without-jsonify/-/json-stable-stringify-without-jsonify-1.0.1.tgz",
      "integrity": "sha512-Bdboy+l7tA3OGW6FjyFHWkP5LuByj1Tk33Ljyq0axyzdk9//JSi2u3fP1QSmd1KNwq6VOKYGlAu87CisVir6Pw==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/json5": {
      "version": "2.2.3",
      "resolved": "https://registry.npmjs.org/json5/-/json5-2.2.3.tgz",
      "integrity": "sha512-XmOWe7eyHYH14cLdVPoyg+GOH3rYX++KpzrylJwSW98t3Nk+U8XOl8FWKOgwtzdb8lXGf6zYwDUzeHMWfxasyg==",
      "dev": true,
      "license": "MIT",
      "bin": {
        "json5": "lib/cli.js"
      },
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/keyv": {
      "version": "4.5.4",
      "resolved": "https://registry.npmjs.org/keyv/-/keyv-4.5.4.tgz",
      "integrity": "sha512-oxVHkHR/EJf2CNXnWxRLW6mg7JyCCUcG0DtEGmL2ctUo1PNTin1PUil+r/+4r5MpVgC/fn1kjsx7mjSujKqIpw==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "json-buffer": "3.0.1"
      }
    },
    "node_modules/levn": {
      "version": "0.4.1",
      "resolved": "https://registry.npmjs.org/levn/-/levn-0.4.1.tgz",
      "integrity": "sha512-+bT2uH4E5LGE7h/n3evcS/sQlJXCpIp6ym8OWJ5eV6+67Dsql/LaaT7qJBAt2rzfoa/5QBGBhxDix1dMt2kQKQ==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "prelude-ls": "^1.2.1",
        "type-check": "~0.4.0"
      },
      "engines": {
        "node": ">= 0.8.0"
      }
    },
    "node_modules/lilconfig": {
      "version": "3.1.3",
      "resolved": "https://registry.npmjs.org/lilconfig/-/lilconfig-3.1.3.tgz",
      "integrity": "sha512-/vlFKAoH5Cgt3Ie+JLhRbwOsCQePABiU3tJ1egGvyQ+33R/vcwM2Zl2QR/LzjsBeItPt3oSVXapn+m4nQDvpzw==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=14"
      },
      "funding": {
        "url": "https://github.com/sponsors/antonk52"
      }
    },
    "node_modules/lines-and-columns": {
      "version": "1.2.4",
      "resolved": "https://registry.npmjs.org/lines-and-columns/-/lines-and-columns-1.2.4.tgz",
      "integrity": "sha512-7ylylesZQ/PV29jhEDl3Ufjo6ZX7gCqJr5F7PKrqc93v7fzSymt1BpwEU8nAUXs8qzzvqhbjhK5QZg6Mt/HkBg==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/locate-path": {
      "version": "6.0.0",
      "resolved": "https://registry.npmjs.org/locate-path/-/locate-path-6.0.0.tgz",
      "integrity": "sha512-iPZK6eYjbxRu3uB4/WZ3EsEIMJFMqAoopl3R+zuq0UjcAm/MO6KCweDgPfP3elTztoKP3KtnVHxTn2NHBSDVUw==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "p-locate": "^5.0.0"
      },
      "engines": {
        "node": ">=10"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/lodash": {
      "version": "4.17.21",
      "resolved": "https://registry.npmjs.org/lodash/-/lodash-4.17.21.tgz",
      "integrity": "sha512-v2kDEe57lecTulaDIuNTPy3Ry4gLGJ6Z1O3vE1krgXZNrsQ+LFTGHVxVjcXPs17LhbZVGedAJv8XZ1tvj5FvSg==",
      "license": "MIT"
    },
    "node_modules/lodash.merge": {
      "version": "4.6.2",
      "resolved": "https://registry.npmjs.org/lodash.merge/-/lodash.merge-4.6.2.tgz",
      "integrity": "sha512-0KpjqXRVvrYyCsX1swR/XTK0va6VQkQM6MNo7PqW77ByjAhoARA8EfrP1N4+KlKj8YS0ZUCtRT/YUuhyYDujIQ==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/lru-cache": {
      "version": "5.1.1",
      "resolved": "https://registry.npmjs.org/lru-cache/-/lru-cache-5.1.1.tgz",
      "integrity": "sha512-KpNARQA3Iwv+jTA0utUVVbrh+Jlrr1Fv0e56GGzAFOXN7dk/FviaDW8LHmK52DlcH4WP2n6gI8vN1aesBFgo9w==",
      "dev": true,
      "license": "ISC",
      "dependencies": {
        "yallist": "^3.0.2"
      }
    },
    "node_modules/lucide-react": {
      "version": "0.486.0",
      "resolved": "https://registry.npmjs.org/lucide-react/-/lucide-react-0.486.0.tgz",
      "integrity": "sha512-xWop/wMsC1ikiEVLZrxXjPKw4vU/eAip33G2mZHgbWnr4Nr5Rt4Vx4s/q1D3B/rQVbxjOuqASkEZcUxDEKzecw==",
      "license": "ISC",
      "peerDependencies": {
        "react": "^16.5.1 || ^17.0.0 || ^18.0.0 || ^19.0.0"
      }
    },
    "node_modules/math-intrinsics": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/math-intrinsics/-/math-intrinsics-1.1.0.tgz",
      "integrity": "sha512-/IXtbwEk5HTPyEwyKX6hGkYXxM9nbj64B+ilVJnC/R6B0pH5G4V3b0pVbL7DBj4tkhBAppbQUlf6F6Xl9LHu1g==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.4"
      }
    },
    "node_modules/merge2": {
      "version": "1.4.1",
      "resolved": "https://registry.npmjs.org/merge2/-/merge2-1.4.1.tgz",
      "integrity": "sha512-8q7VEgMJW4J8tcfVPy8g09NcQwZdbwFEqhe/WZkoIzjn/3TGDwtOCYtXGxA3O8tPzpczCCDgv+P2P5y00ZJOOg==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">= 8"
      }
    },
    "node_modules/micromatch": {
      "version": "4.0.8",
      "resolved": "https://registry.npmjs.org/micromatch/-/micromatch-4.0.8.tgz",
      "integrity": "sha512-PXwfBhYu0hBCPw8Dn0E+WDYb7af3dSLVWKi3HGv84IdF4TyFoC0ysxFd0Goxw7nSv4T/PzEJQxsYsEiFCKo2BA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "braces": "^3.0.3",
        "picomatch": "^2.3.1"
      },
      "engines": {
        "node": ">=8.6"
      }
    },
    "node_modules/mime-db": {
      "version": "1.52.0",
      "resolved": "https://registry.npmjs.org/mime-db/-/mime-db-1.52.0.tgz",
      "integrity": "sha512-sPU4uV7dYlvtWJxwwxHD0PuihVNiE7TyAbQ5SWxDCB9mUYvOgroQOwYQQOKPJ8CIbE+1ETVlOoK1UC2nU3gYvg==",
      "license": "MIT",
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/mime-types": {
      "version": "2.1.35",
      "resolved": "https://registry.npmjs.org/mime-types/-/mime-types-2.1.35.tgz",
      "integrity": "sha512-ZDY+bPm5zTTF+YpCrAU9nK0UgICYPT0QtT1NZWFv4s++TNkcgVaT0g6+4R2uI4MjQjzysHB1zxuWL50hzaeXiw==",
      "license": "MIT",
      "dependencies": {
        "mime-db": "1.52.0"
      },
      "engines": {
        "node": ">= 0.6"
      }
    },
    "node_modules/minimatch": {
      "version": "3.1.2",
      "resolved": "https://registry.npmjs.org/minimatch/-/minimatch-3.1.2.tgz",
      "integrity": "sha512-J7p63hRiAjw1NDEww1W7i37+ByIrOWO5XQQAzZ3VOcL0PNybwpfmV/N05zFAzwQ9USyEcX6t3UO+K5aqBQOIHw==",
      "dev": true,
      "license": "ISC",
      "dependencies": {
        "brace-expansion": "^1.1.7"
      },
      "engines": {
        "node": "*"
      }
    },
    "node_modules/minipass": {
      "version": "7.1.2",
      "resolved": "https://registry.npmjs.org/minipass/-/minipass-7.1.2.tgz",
      "integrity": "sha512-qOOzS1cBTWYF4BH8fVePDBOO9iptMnGUEZwNc/cMWnTV2nVLZ7VoNWEPHkYczZA0pdoA7dl6e7FL659nX9S2aw==",
      "dev": true,
      "license": "ISC",
      "engines": {
        "node": ">=16 || 14 >=14.17"
      }
    },
    "node_modules/motion-dom": {
      "version": "12.6.5",
      "resolved": "https://registry.npmjs.org/motion-dom/-/motion-dom-12.6.5.tgz",
      "integrity": "sha512-jpM9TQLXzYMWMJ7Ec7sAj0iis8oIuu6WvjI3yNKJLdrZyrsI/b2cRInDVL8dCl683zQQq19DpL9cSMP+k8T1NA==",
      "license": "MIT",
      "dependencies": {
        "motion-utils": "^12.6.5"
      }
    },
    "node_modules/motion-utils": {
      "version": "12.6.5",
      "resolved": "https://registry.npmjs.org/motion-utils/-/motion-utils-12.6.5.tgz",
      "integrity": "sha512-IsOeKsOF+FWBhxQEDFBO6ZYC8/jlidmVbbLpe9/lXSA9j9kzGIMUuIBx2SZY+0reAS0DjZZ1i7dJp4NHrjocPw==",
      "license": "MIT"
    },
    "node_modules/ms": {
      "version": "2.1.3",
      "resolved": "https://registry.npmjs.org/ms/-/ms-2.1.3.tgz",
      "integrity": "sha512-6FlzubTLZG3J2a/NVCAleEhjzq5oxgHyaCU9yYXvcLsvoVaHJq/s5xXI6/XXP6tz7R9xAOtHnSO/tXtF3WRTlA==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/mz": {
      "version": "2.7.0",
      "resolved": "https://registry.npmjs.org/mz/-/mz-2.7.0.tgz",
      "integrity": "sha512-z81GNO7nnYMEhrGh9LeymoE4+Yr0Wn5McHIZMK5cfQCl+NDX08sCZgUc9/6MHni9IWuFLm1Z3HTCXu2z9fN62Q==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "any-promise": "^1.0.0",
        "object-assign": "^4.0.1",
        "thenify-all": "^1.0.0"
      }
    },
    "node_modules/nanoid": {
      "version": "3.3.11",
      "resolved": "https://registry.npmjs.org/nanoid/-/nanoid-3.3.11.tgz",
      "integrity": "sha512-N8SpfPUnUp1bK+PMYW8qSWdl9U+wwNWI4QKxOYDy9JAro3WMX7p2OeVRF9v+347pnakNevPmiHhNmZ2HbFA76w==",
      "dev": true,
      "funding": [
        {
          "type": "github",
          "url": "https://github.com/sponsors/ai"
        }
      ],
      "license": "MIT",
      "bin": {
        "nanoid": "bin/nanoid.cjs"
      },
      "engines": {
        "node": "^10 || ^12 || ^13.7 || ^14 || >=15.0.1"
      }
    },
    "node_modules/natural-compare": {
      "version": "1.4.0",
      "resolved": "https://registry.npmjs.org/natural-compare/-/natural-compare-1.4.0.tgz",
      "integrity": "sha512-OWND8ei3VtNC9h7V60qff3SVobHr996CTwgxubgyQYEpg290h9J0buyECNNJexkFm5sOajh5G116RYA1c8ZMSw==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/node-releases": {
      "version": "2.0.19",
      "resolved": "https://registry.npmjs.org/node-releases/-/node-releases-2.0.19.tgz",
      "integrity": "sha512-xxOWJsBKtzAq7DY0J+DTzuz58K8e7sJbdgwkbMWQe8UYB6ekmsQ45q0M/tJDsGaZmbC+l7n57UV8Hl5tHxO9uw==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/normalize-path": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/normalize-path/-/normalize-path-3.0.0.tgz",
      "integrity": "sha512-6eZs5Ls3WtCisHWp9S2GUy8dqkpGi4BVSz3GaqiE6ezub0512ESztXUwUB6C6IKbQkY2Pnb/mD4WYojCRwcwLA==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/normalize-range": {
      "version": "0.1.2",
      "resolved": "https://registry.npmjs.org/normalize-range/-/normalize-range-0.1.2.tgz",
      "integrity": "sha512-bdok/XvKII3nUpklnV6P2hxtMNrCboOjAcyBuQnWEhO665FwrSNRxU+AqpsyvO6LgGYPspN+lu5CLtw4jPRKNA==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/object-assign": {
      "version": "4.1.1",
      "resolved": "https://registry.npmjs.org/object-assign/-/object-assign-4.1.1.tgz",
      "integrity": "sha512-rJgTQnkUnH1sFw8yT6VSU3zD3sWmu6sZhIseY8VX+GRu3P6F7Fu+JNDoXfklElbLJSnc3FUQHVe4cU5hj+BcUg==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/object-hash": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/object-hash/-/object-hash-3.0.0.tgz",
      "integrity": "sha512-RSn9F68PjH9HqtltsSnqYC1XXoWe9Bju5+213R98cNGttag9q9yAOTzdbsqvIa7aNm5WffBZFpWYr2aWrklWAw==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">= 6"
      }
    },
    "node_modules/optionator": {
      "version": "0.9.4",
      "resolved": "https://registry.npmjs.org/optionator/-/optionator-0.9.4.tgz",
      "integrity": "sha512-6IpQ7mKUxRcZNLIObR0hz7lxsapSSIYNZJwXPGeF0mTVqGKFIXj1DQcMoT22S3ROcLyY/rz0PWaWZ9ayWmad9g==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "deep-is": "^0.1.3",
        "fast-levenshtein": "^2.0.6",
        "levn": "^0.4.1",
        "prelude-ls": "^1.2.1",
        "type-check": "^0.4.0",
        "word-wrap": "^1.2.5"
      },
      "engines": {
        "node": ">= 0.8.0"
      }
    },
    "node_modules/p-limit": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/p-limit/-/p-limit-3.1.0.tgz",
      "integrity": "sha512-TYOanM3wGwNGsZN2cVTYPArw454xnXj5qmWF1bEoAc4+cU/ol7GVh7odevjp1FNHduHc3KZMcFduxU5Xc6uJRQ==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "yocto-queue": "^0.1.0"
      },
      "engines": {
        "node": ">=10"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/p-locate": {
      "version": "5.0.0",
      "resolved": "https://registry.npmjs.org/p-locate/-/p-locate-5.0.0.tgz",
      "integrity": "sha512-LaNjtRWUBY++zB5nE/NwcaoMylSPk+S+ZHNB1TzdbMJMny6dynpAGt7X/tl/QYq3TIeE6nxHppbo2LGymrG5Pw==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "p-limit": "^3.0.2"
      },
      "engines": {
        "node": ">=10"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/package-json-from-dist": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/package-json-from-dist/-/package-json-from-dist-1.0.1.tgz",
      "integrity": "sha512-UEZIS3/by4OC8vL3P2dTXRETpebLI2NiI5vIrjaD/5UtrkFX/tNbwjTSRAGC/+7CAo2pIcBaRgWmcBBHcsaCIw==",
      "dev": true,
      "license": "BlueOak-1.0.0"
    },
    "node_modules/parent-module": {
      "version": "1.0.1",
      "resolved": "https://registry.npmjs.org/parent-module/-/parent-module-1.0.1.tgz",
      "integrity": "sha512-GQ2EWRpQV8/o+Aw8YqtfZZPfNRWZYkbidE9k5rpl/hC3vtHHBfGm2Ifi6qWV+coDGkrUKZAxE3Lot5kcsRlh+g==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "callsites": "^3.0.0"
      },
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/path-exists": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/path-exists/-/path-exists-4.0.0.tgz",
      "integrity": "sha512-ak9Qy5Q7jYb2Wwcey5Fpvg2KoAc/ZIhLSLOSBmRmygPsGwkVVt0fZa0qrtMz+m6tJTAHfZQ8FnmB4MG4LWy7/w==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/path-key": {
      "version": "3.1.1",
      "resolved": "https://registry.npmjs.org/path-key/-/path-key-3.1.1.tgz",
      "integrity": "sha512-ojmeN0qd+y0jszEtoY48r0Peq5dwMEkIlCOu6Q5f41lfkswXuKtYrhgoTpLnyIcHm24Uhqx+5Tqm2InSwLhE6Q==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/path-parse": {
      "version": "1.0.7",
      "resolved": "https://registry.npmjs.org/path-parse/-/path-parse-1.0.7.tgz",
      "integrity": "sha512-LDJzPVEEEPR+y48z93A0Ed0yXb8pAByGWo/k5YYdYgpY2/2EsOsksJrq7lOHxryrVOn1ejG6oAp8ahvOIQD8sw==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/path-scurry": {
      "version": "1.11.1",
      "resolved": "https://registry.npmjs.org/path-scurry/-/path-scurry-1.11.1.tgz",
      "integrity": "sha512-Xa4Nw17FS9ApQFJ9umLiJS4orGjm7ZzwUrwamcGQuHSzDyth9boKDaycYdDcZDuqYATXw4HFXgaqWTctW/v1HA==",
      "dev": true,
      "license": "BlueOak-1.0.0",
      "dependencies": {
        "lru-cache": "^10.2.0",
        "minipass": "^5.0.0 || ^6.0.2 || ^7.0.0"
      },
      "engines": {
        "node": ">=16 || 14 >=14.18"
      },
      "funding": {
        "url": "https://github.com/sponsors/isaacs"
      }
    },
    "node_modules/path-scurry/node_modules/lru-cache": {
      "version": "10.4.3",
      "resolved": "https://registry.npmjs.org/lru-cache/-/lru-cache-10.4.3.tgz",
      "integrity": "sha512-JNAzZcXrCt42VGLuYz0zfAzDfAvJWW6AfYlDBQyDV5DClI2m5sAmK+OIO7s59XfsRsWHp02jAJrRadPRGTt6SQ==",
      "dev": true,
      "license": "ISC"
    },
    "node_modules/picocolors": {
      "version": "1.1.1",
      "resolved": "https://registry.npmjs.org/picocolors/-/picocolors-1.1.1.tgz",
      "integrity": "sha512-xceH2snhtb5M9liqDsmEw56le376mTZkEX/jEb/RxNFyegNul7eNslCXP9FDj/Lcu0X8KEyMceP2ntpaHrDEVA==",
      "dev": true,
      "license": "ISC"
    },
    "node_modules/picomatch": {
      "version": "2.3.1",
      "resolved": "https://registry.npmjs.org/picomatch/-/picomatch-2.3.1.tgz",
      "integrity": "sha512-JU3teHTNjmE2VCGFzuY8EXzCDVwEqB2a8fsIvwaStHhAWJEeVd1o1QD80CU6+ZdEXXSLbSsuLwJjkCBWqRQUVA==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=8.6"
      },
      "funding": {
        "url": "https://github.com/sponsors/jonschlinkert"
      }
    },
    "node_modules/pify": {
      "version": "2.3.0",
      "resolved": "https://registry.npmjs.org/pify/-/pify-2.3.0.tgz",
      "integrity": "sha512-udgsAY+fTnvv7kI7aaxbqwWNb0AHiB0qBO89PZKPkoTmGOgdbrHDKD+0B2X4uTfJ/FT1R09r9gTsjUjNJotuog==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/pirates": {
      "version": "4.0.7",
      "resolved": "https://registry.npmjs.org/pirates/-/pirates-4.0.7.tgz",
      "integrity": "sha512-TfySrs/5nm8fQJDcBDuUng3VOUKsd7S+zqvbOTiGXHfxX4wK31ard+hoNuvkicM/2YFzlpDgABOevKSsB4G/FA==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">= 6"
      }
    },
    "node_modules/postcss": {
      "version": "8.5.3",
      "resolved": "https://registry.npmjs.org/postcss/-/postcss-8.5.3.tgz",
      "integrity": "sha512-dle9A3yYxlBSrt8Fu+IpjGT8SY8hN0mlaA6GY8t0P5PjIOZemULz/E2Bnm/2dcUOena75OTNkHI76uZBNUUq3A==",
      "dev": true,
      "funding": [
        {
          "type": "opencollective",
          "url": "https://opencollective.com/postcss/"
        },
        {
          "type": "tidelift",
          "url": "https://tidelift.com/funding/github/npm/postcss"
        },
        {
          "type": "github",
          "url": "https://github.com/sponsors/ai"
        }
      ],
      "license": "MIT",
      "dependencies": {
        "nanoid": "^3.3.8",
        "picocolors": "^1.1.1",
        "source-map-js": "^1.2.1"
      },
      "engines": {
        "node": "^10 || ^12 || >=14"
      }
    },
    "node_modules/postcss-import": {
      "version": "15.1.0",
      "resolved": "https://registry.npmjs.org/postcss-import/-/postcss-import-15.1.0.tgz",
      "integrity": "sha512-hpr+J05B2FVYUAXHeK1YyI267J/dDDhMU6B6civm8hSY1jYJnBXxzKDKDswzJmtLHryrjhnDjqqp/49t8FALew==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "postcss-value-parser": "^4.0.0",
        "read-cache": "^1.0.0",
        "resolve": "^1.1.7"
      },
      "engines": {
        "node": ">=14.0.0"
      },
      "peerDependencies": {
        "postcss": "^8.0.0"
      }
    },
    "node_modules/postcss-js": {
      "version": "4.0.1",
      "resolved": "https://registry.npmjs.org/postcss-js/-/postcss-js-4.0.1.tgz",
      "integrity": "sha512-dDLF8pEO191hJMtlHFPRa8xsizHaM82MLfNkUHdUtVEV3tgTp5oj+8qbEqYM57SLfc74KSbw//4SeJma2LRVIw==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "camelcase-css": "^2.0.1"
      },
      "engines": {
        "node": "^12 || ^14 || >= 16"
      },
      "funding": {
        "type": "opencollective",
        "url": "https://opencollective.com/postcss/"
      },
      "peerDependencies": {
        "postcss": "^8.4.21"
      }
    },
    "node_modules/postcss-load-config": {
      "version": "4.0.2",
      "resolved": "https://registry.npmjs.org/postcss-load-config/-/postcss-load-config-4.0.2.tgz",
      "integrity": "sha512-bSVhyJGL00wMVoPUzAVAnbEoWyqRxkjv64tUl427SKnPrENtq6hJwUojroMz2VB+Q1edmi4IfrAPpami5VVgMQ==",
      "dev": true,
      "funding": [
        {
          "type": "opencollective",
          "url": "https://opencollective.com/postcss/"
        },
        {
          "type": "github",
          "url": "https://github.com/sponsors/ai"
        }
      ],
      "license": "MIT",
      "dependencies": {
        "lilconfig": "^3.0.0",
        "yaml": "^2.3.4"
      },
      "engines": {
        "node": ">= 14"
      },
      "peerDependencies": {
        "postcss": ">=8.0.9",
        "ts-node": ">=9.0.0"
      },
      "peerDependenciesMeta": {
        "postcss": {
          "optional": true
        },
        "ts-node": {
          "optional": true
        }
      }
    },
    "node_modules/postcss-nested": {
      "version": "6.2.0",
      "resolved": "https://registry.npmjs.org/postcss-nested/-/postcss-nested-6.2.0.tgz",
      "integrity": "sha512-HQbt28KulC5AJzG+cZtj9kvKB93CFCdLvog1WFLf1D+xmMvPGlBstkpTEZfK5+AN9hfJocyBFCNiqyS48bpgzQ==",
      "dev": true,
      "funding": [
        {
          "type": "opencollective",
          "url": "https://opencollective.com/postcss/"
        },
        {
          "type": "github",
          "url": "https://github.com/sponsors/ai"
        }
      ],
      "license": "MIT",
      "dependencies": {
        "postcss-selector-parser": "^6.1.1"
      },
      "engines": {
        "node": ">=12.0"
      },
      "peerDependencies": {
        "postcss": "^8.2.14"
      }
    },
    "node_modules/postcss-selector-parser": {
      "version": "6.1.2",
      "resolved": "https://registry.npmjs.org/postcss-selector-parser/-/postcss-selector-parser-6.1.2.tgz",
      "integrity": "sha512-Q8qQfPiZ+THO/3ZrOrO0cJJKfpYCagtMUkXbnEfmgUjwXg6z/WBeOyS9APBBPCTSiDV+s4SwQGu8yFsiMRIudg==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "cssesc": "^3.0.0",
        "util-deprecate": "^1.0.2"
      },
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/postcss-value-parser": {
      "version": "4.2.0",
      "resolved": "https://registry.npmjs.org/postcss-value-parser/-/postcss-value-parser-4.2.0.tgz",
      "integrity": "sha512-1NNCs6uurfkVbeXG4S8JFT9t19m45ICnif8zWLd5oPSZ50QnwMfK+H3jv408d4jw/7Bttv5axS5IiHoLaVNHeQ==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/prelude-ls": {
      "version": "1.2.1",
      "resolved": "https://registry.npmjs.org/prelude-ls/-/prelude-ls-1.2.1.tgz",
      "integrity": "sha512-vkcDPrRZo1QZLbn5RLGPpg/WmIQ65qoWWhcGKf/b5eplkkarX0m9z8ppCat4mlOqUsWpyNuYgO3VRyrYHSzX5g==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">= 0.8.0"
      }
    },
    "node_modules/proxy-from-env": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/proxy-from-env/-/proxy-from-env-1.1.0.tgz",
      "integrity": "sha512-D+zkORCbA9f1tdWRK0RaCR3GPv50cMxcrz4X8k5LTSUD1Dkw47mKJEZQNunItRTkWwgtaUSo1RVFRIG9ZXiFYg==",
      "license": "MIT"
    },
    "node_modules/punycode": {
      "version": "2.3.1",
      "resolved": "https://registry.npmjs.org/punycode/-/punycode-2.3.1.tgz",
      "integrity": "sha512-vYt7UD1U9Wg6138shLtLOvdAu+8DsC/ilFtEVHcH+wydcSpNE20AfSOduf6MkRFahL5FY7X1oU7nKVZFtfq8Fg==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=6"
      }
    },
    "node_modules/queue-microtask": {
      "version": "1.2.3",
      "resolved": "https://registry.npmjs.org/queue-microtask/-/queue-microtask-1.2.3.tgz",
      "integrity": "sha512-NuaNSa6flKT5JaSYQzJok04JzTL1CA6aGhv5rfLW3PgqA+M2ChpZQnAC8h8i4ZFkBS8X5RqkDBHA7r4hej3K9A==",
      "dev": true,
      "funding": [
        {
          "type": "github",
          "url": "https://github.com/sponsors/feross"
        },
        {
          "type": "patreon",
          "url": "https://www.patreon.com/feross"
        },
        {
          "type": "consulting",
          "url": "https://feross.org/support"
        }
      ],
      "license": "MIT"
    },
    "node_modules/react": {
      "version": "19.1.0",
      "resolved": "https://registry.npmjs.org/react/-/react-19.1.0.tgz",
      "integrity": "sha512-FS+XFBNvn3GTAWq26joslQgWNoFu08F4kl0J4CgdNKADkdSGXQyTCnKteIAJy96Br6YbpEU1LSzV5dYtjMkMDg==",
      "license": "MIT",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/react-circular-progressbar": {
      "version": "2.2.0",
      "resolved": "https://registry.npmjs.org/react-circular-progressbar/-/react-circular-progressbar-2.2.0.tgz",
      "integrity": "sha512-cgyqEHOzB0nWMZjKfWN3MfSa1LV3OatcDjPz68lchXQUEiBD5O1WsAtoVK4/DSL0B4USR//cTdok4zCBkq8X5g==",
      "license": "MIT",
      "peerDependencies": {
        "react": ">=0.14.0"
      }
    },
    "node_modules/react-dom": {
      "version": "19.1.0",
      "resolved": "https://registry.npmjs.org/react-dom/-/react-dom-19.1.0.tgz",
      "integrity": "sha512-Xs1hdnE+DyKgeHJeJznQmYMIBG3TKIHJJT95Q58nHLSrElKlGQqDTR2HQ9fx5CN/Gk6Vh/kupBTDLU11/nDk/g==",
      "license": "MIT",
      "dependencies": {
        "scheduler": "^0.26.0"
      },
      "peerDependencies": {
        "react": "^19.1.0"
      }
    },
    "node_modules/react-icons": {
      "version": "5.5.0",
      "resolved": "https://registry.npmjs.org/react-icons/-/react-icons-5.5.0.tgz",
      "integrity": "sha512-MEFcXdkP3dLo8uumGI5xN3lDFNsRtrjbOEKDLD7yv76v4wpnEq2Lt2qeHaQOr34I/wPN3s3+N08WkQ+CW37Xiw==",
      "license": "MIT",
      "peerDependencies": {
        "react": "*"
      }
    },
    "node_modules/react-redux": {
      "version": "9.2.0",
      "resolved": "https://registry.npmjs.org/react-redux/-/react-redux-9.2.0.tgz",
      "integrity": "sha512-ROY9fvHhwOD9ySfrF0wmvu//bKCQ6AeZZq1nJNtbDC+kk5DuSuNX/n6YWYF/SYy7bSba4D4FSz8DJeKY/S/r+g==",
      "license": "MIT",
      "dependencies": {
        "@types/use-sync-external-store": "^0.0.6",
        "use-sync-external-store": "^1.4.0"
      },
      "peerDependencies": {
        "@types/react": "^18.2.25 || ^19",
        "react": "^18.0 || ^19",
        "redux": "^5.0.0"
      },
      "peerDependenciesMeta": {
        "@types/react": {
          "optional": true
        },
        "redux": {
          "optional": true
        }
      }
    },
    "node_modules/react-refresh": {
      "version": "0.14.2",
      "resolved": "https://registry.npmjs.org/react-refresh/-/react-refresh-0.14.2.tgz",
      "integrity": "sha512-jCvmsr+1IUSMUyzOkRcvnVbX3ZYC6g9TDrDbFuFmRDq7PD4yaGbLKNQL6k2jnArV8hjYxh7hVhAZB6s9HDGpZA==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/react-router": {
      "version": "7.4.1",
      "resolved": "https://registry.npmjs.org/react-router/-/react-router-7.4.1.tgz",
      "integrity": "sha512-Vmizn9ZNzxfh3cumddqv3kLOKvc7AskUT0dC1prTabhiEi0U4A33LmkDOJ79tXaeSqCqMBXBU/ySX88W85+EUg==",
      "license": "MIT",
      "dependencies": {
        "@types/cookie": "^0.6.0",
        "cookie": "^1.0.1",
        "set-cookie-parser": "^2.6.0",
        "turbo-stream": "2.4.0"
      },
      "engines": {
        "node": ">=20.0.0"
      },
      "peerDependencies": {
        "react": ">=18",
        "react-dom": ">=18"
      },
      "peerDependenciesMeta": {
        "react-dom": {
          "optional": true
        }
      }
    },
    "node_modules/react-router-dom": {
      "version": "7.4.1",
      "resolved": "https://registry.npmjs.org/react-router-dom/-/react-router-dom-7.4.1.tgz",
      "integrity": "sha512-L3/4tig0Lvs6m6THK0HRV4eHUdpx0dlJasgCxXKnavwhh4tKYgpuZk75HRYNoRKDyDWi9QgzGXsQ1oQSBlWpAA==",
      "license": "MIT",
      "dependencies": {
        "react-router": "7.4.1"
      },
      "engines": {
        "node": ">=20.0.0"
      },
      "peerDependencies": {
        "react": ">=18",
        "react-dom": ">=18"
      }
    },
    "node_modules/react-toastify": {
      "version": "11.0.5",
      "resolved": "https://registry.npmjs.org/react-toastify/-/react-toastify-11.0.5.tgz",
      "integrity": "sha512-EpqHBGvnSTtHYhCPLxML05NLY2ZX0JURbAdNYa6BUkk+amz4wbKBQvoKQAB0ardvSarUBuY4Q4s1sluAzZwkmA==",
      "license": "MIT",
      "dependencies": {
        "clsx": "^2.1.1"
      },
      "peerDependencies": {
        "react": "^18 || ^19",
        "react-dom": "^18 || ^19"
      }
    },
    "node_modules/read-cache": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/read-cache/-/read-cache-1.0.0.tgz",
      "integrity": "sha512-Owdv/Ft7IjOgm/i0xvNDZ1LrRANRfew4b2prF3OWMQLxLfu3bS8FVhCsrSCMK4lR56Y9ya+AThoTpDCTxCmpRA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "pify": "^2.3.0"
      }
    },
    "node_modules/readdirp": {
      "version": "3.6.0",
      "resolved": "https://registry.npmjs.org/readdirp/-/readdirp-3.6.0.tgz",
      "integrity": "sha512-hOS089on8RduqdbhvQ5Z37A0ESjsqz6qnRcffsMU3495FuTdqSm+7bhJ29JvIOsBDEEnan5DPu9t3To9VRlMzA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "picomatch": "^2.2.1"
      },
      "engines": {
        "node": ">=8.10.0"
      }
    },
    "node_modules/redux": {
      "version": "5.0.1",
      "resolved": "https://registry.npmjs.org/redux/-/redux-5.0.1.tgz",
      "integrity": "sha512-M9/ELqF6fy8FwmkpnF0S3YKOqMyoWJ4+CS5Efg2ct3oY9daQvd/Pc71FpGZsVsbl3Cpb+IIcjBDUnnyBdQbq4w==",
      "license": "MIT"
    },
    "node_modules/redux-thunk": {
      "version": "3.1.0",
      "resolved": "https://registry.npmjs.org/redux-thunk/-/redux-thunk-3.1.0.tgz",
      "integrity": "sha512-NW2r5T6ksUKXCabzhL9z+h206HQw/NJkcLm1GPImRQ8IzfXwRGqjVhKJGauHirT0DAuyy6hjdnMZaRoAcy0Klw==",
      "license": "MIT",
      "peerDependencies": {
        "redux": "^5.0.0"
      }
    },
    "node_modules/reselect": {
      "version": "5.1.1",
      "resolved": "https://registry.npmjs.org/reselect/-/reselect-5.1.1.tgz",
      "integrity": "sha512-K/BG6eIky/SBpzfHZv/dd+9JBFiS4SWV7FIujVyJRux6e45+73RaUHXLmIR1f7WOMaQ0U1km6qwklRQxpJJY0w==",
      "license": "MIT"
    },
    "node_modules/resolve": {
      "version": "1.22.10",
      "resolved": "https://registry.npmjs.org/resolve/-/resolve-1.22.10.tgz",
      "integrity": "sha512-NPRy+/ncIMeDlTAsuqwKIiferiawhefFJtkNSW0qZJEqMEb+qBt/77B/jGeeek+F0uOeN05CDa6HXbbIgtVX4w==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "is-core-module": "^2.16.0",
        "path-parse": "^1.0.7",
        "supports-preserve-symlinks-flag": "^1.0.0"
      },
      "bin": {
        "resolve": "bin/resolve"
      },
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/resolve-from": {
      "version": "4.0.0",
      "resolved": "https://registry.npmjs.org/resolve-from/-/resolve-from-4.0.0.tgz",
      "integrity": "sha512-pb/MYmXstAkysRFx8piNI1tGFNQIFA3vkE3Gq4EuA1dF6gHp/+vgZqsCGJapvy8N3Q+4o7FwvquPJcnZ7RYy4g==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=4"
      }
    },
    "node_modules/reusify": {
      "version": "1.1.0",
      "resolved": "https://registry.npmjs.org/reusify/-/reusify-1.1.0.tgz",
      "integrity": "sha512-g6QUff04oZpHs0eG5p83rFLhHeV00ug/Yf9nZM6fLeUrPguBTkTQOdpAWWspMh55TZfVQDPaN3NQJfbVRAxdIw==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "iojs": ">=1.0.0",
        "node": ">=0.10.0"
      }
    },
    "node_modules/rollup": {
      "version": "4.38.0",
      "resolved": "https://registry.npmjs.org/rollup/-/rollup-4.38.0.tgz",
      "integrity": "sha512-5SsIRtJy9bf1ErAOiFMFzl64Ex9X5V7bnJ+WlFMb+zmP459OSWCEG7b0ERZ+PEU7xPt4OG3RHbrp1LJlXxYTrw==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@types/estree": "1.0.7"
      },
      "bin": {
        "rollup": "dist/bin/rollup"
      },
      "engines": {
        "node": ">=18.0.0",
        "npm": ">=8.0.0"
      },
      "optionalDependencies": {
        "@rollup/rollup-android-arm-eabi": "4.38.0",
        "@rollup/rollup-android-arm64": "4.38.0",
        "@rollup/rollup-darwin-arm64": "4.38.0",
        "@rollup/rollup-darwin-x64": "4.38.0",
        "@rollup/rollup-freebsd-arm64": "4.38.0",
        "@rollup/rollup-freebsd-x64": "4.38.0",
        "@rollup/rollup-linux-arm-gnueabihf": "4.38.0",
        "@rollup/rollup-linux-arm-musleabihf": "4.38.0",
        "@rollup/rollup-linux-arm64-gnu": "4.38.0",
        "@rollup/rollup-linux-arm64-musl": "4.38.0",
        "@rollup/rollup-linux-loongarch64-gnu": "4.38.0",
        "@rollup/rollup-linux-powerpc64le-gnu": "4.38.0",
        "@rollup/rollup-linux-riscv64-gnu": "4.38.0",
        "@rollup/rollup-linux-riscv64-musl": "4.38.0",
        "@rollup/rollup-linux-s390x-gnu": "4.38.0",
        "@rollup/rollup-linux-x64-gnu": "4.38.0",
        "@rollup/rollup-linux-x64-musl": "4.38.0",
        "@rollup/rollup-win32-arm64-msvc": "4.38.0",
        "@rollup/rollup-win32-ia32-msvc": "4.38.0",
        "@rollup/rollup-win32-x64-msvc": "4.38.0",
        "fsevents": "~2.3.2"
      }
    },
    "node_modules/run-parallel": {
      "version": "1.2.0",
      "resolved": "https://registry.npmjs.org/run-parallel/-/run-parallel-1.2.0.tgz",
      "integrity": "sha512-5l4VyZR86LZ/lDxZTR6jqL8AFE2S0IFLMP26AbjsLVADxHdhB/c0GUsH+y39UfCi3dzz8OlQuPmnaJOMoDHQBA==",
      "dev": true,
      "funding": [
        {
          "type": "github",
          "url": "https://github.com/sponsors/feross"
        },
        {
          "type": "patreon",
          "url": "https://www.patreon.com/feross"
        },
        {
          "type": "consulting",
          "url": "https://feross.org/support"
        }
      ],
      "license": "MIT",
      "dependencies": {
        "queue-microtask": "^1.2.2"
      }
    },
    "node_modules/scheduler": {
      "version": "0.26.0",
      "resolved": "https://registry.npmjs.org/scheduler/-/scheduler-0.26.0.tgz",
      "integrity": "sha512-NlHwttCI/l5gCPR3D1nNXtWABUmBwvZpEQiD4IXSbIDq8BzLIK/7Ir5gTFSGZDUu37K5cMNp0hFtzO38sC7gWA==",
      "license": "MIT"
    },
    "node_modules/semver": {
      "version": "6.3.1",
      "resolved": "https://registry.npmjs.org/semver/-/semver-6.3.1.tgz",
      "integrity": "sha512-BR7VvDCVHO+q2xBEWskxS6DJE1qRnb7DxzUrogb71CWoSficBxYsiAGd+Kl0mmq/MprG9yArRkyrQxTO6XjMzA==",
      "dev": true,
      "license": "ISC",
      "bin": {
        "semver": "bin/semver.js"
      }
    },
    "node_modules/set-cookie-parser": {
      "version": "2.7.1",
      "resolved": "https://registry.npmjs.org/set-cookie-parser/-/set-cookie-parser-2.7.1.tgz",
      "integrity": "sha512-IOc8uWeOZgnb3ptbCURJWNjWUPcO3ZnTTdzsurqERrP6nPyv+paC55vJM0LpOlT2ne+Ix+9+CRG1MNLlyZ4GjQ==",
      "license": "MIT"
    },
    "node_modules/shebang-command": {
      "version": "2.0.0",
      "resolved": "https://registry.npmjs.org/shebang-command/-/shebang-command-2.0.0.tgz",
      "integrity": "sha512-kHxr2zZpYtdmrN1qDjrrX/Z1rR1kG8Dx+gkpK1G4eXmvXswmcE1hTWBWYUzlraYw1/yZp6YuDY77YtvbN0dmDA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "shebang-regex": "^3.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/shebang-regex": {
      "version": "3.0.0",
      "resolved": "https://registry.npmjs.org/shebang-regex/-/shebang-regex-3.0.0.tgz",
      "integrity": "sha512-7++dFhtcx3353uBaq8DDR4NuxBetBzC7ZQOhmTQInHEd6bSrXdiEyzCvG07Z44UYdLShWUyXt5M/yhz8ekcb1A==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/signal-exit": {
      "version": "4.1.0",
      "resolved": "https://registry.npmjs.org/signal-exit/-/signal-exit-4.1.0.tgz",
      "integrity": "sha512-bzyZ1e88w9O1iNJbKnOlvYTrWPDl46O1bG0D3XInv+9tkPrxrN8jUUTiFlDkkmKWgn1M6CfIA13SuGqOa9Korw==",
      "dev": true,
      "license": "ISC",
      "engines": {
        "node": ">=14"
      },
      "funding": {
        "url": "https://github.com/sponsors/isaacs"
      }
    },
    "node_modules/source-map-js": {
      "version": "1.2.1",
      "resolved": "https://registry.npmjs.org/source-map-js/-/source-map-js-1.2.1.tgz",
      "integrity": "sha512-UXWMKhLOwVKb728IUtQPXxfYU+usdybtUrK/8uGE8CQMvrhOpwvzDBwj0QhSL7MQc7vIsISBG8VQ8+IDQxpfQA==",
      "dev": true,
      "license": "BSD-3-Clause",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/string-width": {
      "version": "5.1.2",
      "resolved": "https://registry.npmjs.org/string-width/-/string-width-5.1.2.tgz",
      "integrity": "sha512-HnLOCR3vjcY8beoNLtcjZ5/nxn2afmME6lhrDrebokqMap+XbeW8n9TXpPDOqdGK5qcI3oT0GKTW6wC7EMiVqA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "eastasianwidth": "^0.2.0",
        "emoji-regex": "^9.2.2",
        "strip-ansi": "^7.0.1"
      },
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/string-width-cjs": {
      "name": "string-width",
      "version": "4.2.3",
      "resolved": "https://registry.npmjs.org/string-width/-/string-width-4.2.3.tgz",
      "integrity": "sha512-wKyQRQpjJ0sIp62ErSZdGsjMJWsap5oRNihHhu6G7JVO/9jIB6UyevL+tXuOqrng8j/cxKTWyWUwvSTriiZz/g==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "emoji-regex": "^8.0.0",
        "is-fullwidth-code-point": "^3.0.0",
        "strip-ansi": "^6.0.1"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/string-width-cjs/node_modules/ansi-regex": {
      "version": "5.0.1",
      "resolved": "https://registry.npmjs.org/ansi-regex/-/ansi-regex-5.0.1.tgz",
      "integrity": "sha512-quJQXlTSUGL2LH9SUXo8VwsY4soanhgo6LNSm84E1LBcE8s3O0wpdiRzyR9z/ZZJMlMWv37qOOb9pdJlMUEKFQ==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/string-width-cjs/node_modules/emoji-regex": {
      "version": "8.0.0",
      "resolved": "https://registry.npmjs.org/emoji-regex/-/emoji-regex-8.0.0.tgz",
      "integrity": "sha512-MSjYzcWNOA0ewAHpz0MxpYFvwg6yjy1NG3xteoqz644VCo/RPgnr1/GGt+ic3iJTzQ8Eu3TdM14SawnVUmGE6A==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/string-width-cjs/node_modules/strip-ansi": {
      "version": "6.0.1",
      "resolved": "https://registry.npmjs.org/strip-ansi/-/strip-ansi-6.0.1.tgz",
      "integrity": "sha512-Y38VPSHcqkFrCpFnQ9vuSXmquuv5oXOKpGeT6aGrr3o3Gc9AlVa6JBfUSOCnbxGGZF+/0ooI7KrPuUSztUdU5A==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "ansi-regex": "^5.0.1"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/strip-ansi": {
      "version": "7.1.0",
      "resolved": "https://registry.npmjs.org/strip-ansi/-/strip-ansi-7.1.0.tgz",
      "integrity": "sha512-iq6eVVI64nQQTRYq2KtEg2d2uU7LElhTJwsH4YzIHZshxlgZms/wIc4VoDQTlG/IvVIrBKG06CrZnp0qv7hkcQ==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "ansi-regex": "^6.0.1"
      },
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/chalk/strip-ansi?sponsor=1"
      }
    },
    "node_modules/strip-ansi-cjs": {
      "name": "strip-ansi",
      "version": "6.0.1",
      "resolved": "https://registry.npmjs.org/strip-ansi/-/strip-ansi-6.0.1.tgz",
      "integrity": "sha512-Y38VPSHcqkFrCpFnQ9vuSXmquuv5oXOKpGeT6aGrr3o3Gc9AlVa6JBfUSOCnbxGGZF+/0ooI7KrPuUSztUdU5A==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "ansi-regex": "^5.0.1"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/strip-ansi-cjs/node_modules/ansi-regex": {
      "version": "5.0.1",
      "resolved": "https://registry.npmjs.org/ansi-regex/-/ansi-regex-5.0.1.tgz",
      "integrity": "sha512-quJQXlTSUGL2LH9SUXo8VwsY4soanhgo6LNSm84E1LBcE8s3O0wpdiRzyR9z/ZZJMlMWv37qOOb9pdJlMUEKFQ==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/strip-json-comments": {
      "version": "3.1.1",
      "resolved": "https://registry.npmjs.org/strip-json-comments/-/strip-json-comments-3.1.1.tgz",
      "integrity": "sha512-6fPc+R4ihwqP6N/aIv2f1gMH8lOVtWQHoqC4yK6oSDVVocumAsfCqjkXnqiYMhmMwS/mEHLp7Vehlt3ql6lEig==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=8"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    },
    "node_modules/sucrase": {
      "version": "3.35.0",
      "resolved": "https://registry.npmjs.org/sucrase/-/sucrase-3.35.0.tgz",
      "integrity": "sha512-8EbVDiu9iN/nESwxeSxDKe0dunta1GOlHufmSSXxMD2z2/tMZpDMpvXQGsc+ajGo8y2uYUmixaSRUc/QPoQ0GA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@jridgewell/gen-mapping": "^0.3.2",
        "commander": "^4.0.0",
        "glob": "^10.3.10",
        "lines-and-columns": "^1.1.6",
        "mz": "^2.7.0",
        "pirates": "^4.0.1",
        "ts-interface-checker": "^0.1.9"
      },
      "bin": {
        "sucrase": "bin/sucrase",
        "sucrase-node": "bin/sucrase-node"
      },
      "engines": {
        "node": ">=16 || 14 >=14.17"
      }
    },
    "node_modules/supports-color": {
      "version": "7.2.0",
      "resolved": "https://registry.npmjs.org/supports-color/-/supports-color-7.2.0.tgz",
      "integrity": "sha512-qpCAvRl9stuOHveKsn7HncJRvv501qIacKzQlO/+Lwxc9+0q2wLyv4Dfvt80/DPn2pqOBsJdDiogXGR9+OvwRw==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "has-flag": "^4.0.0"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/supports-preserve-symlinks-flag": {
      "version": "1.0.0",
      "resolved": "https://registry.npmjs.org/supports-preserve-symlinks-flag/-/supports-preserve-symlinks-flag-1.0.0.tgz",
      "integrity": "sha512-ot0WnXS9fgdkgIcePe6RHNk1WA8+muPa6cSjeR3V8K27q9BB1rTE3R1p7Hv0z1ZyAc8s6Vvv8DIyWf681MAt0w==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">= 0.4"
      },
      "funding": {
        "url": "https://github.com/sponsors/ljharb"
      }
    },
    "node_modules/tailwindcss": {
      "version": "3.4.17",
      "resolved": "https://registry.npmjs.org/tailwindcss/-/tailwindcss-3.4.17.tgz",
      "integrity": "sha512-w33E2aCvSDP0tW9RZuNXadXlkHXqFzSkQew/aIa2i/Sj8fThxwovwlXHSPXTbAHwEIhBFXAedUhP2tueAKP8Og==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "@alloc/quick-lru": "^5.2.0",
        "arg": "^5.0.2",
        "chokidar": "^3.6.0",
        "didyoumean": "^1.2.2",
        "dlv": "^1.1.3",
        "fast-glob": "^3.3.2",
        "glob-parent": "^6.0.2",
        "is-glob": "^4.0.3",
        "jiti": "^1.21.6",
        "lilconfig": "^3.1.3",
        "micromatch": "^4.0.8",
        "normalize-path": "^3.0.0",
        "object-hash": "^3.0.0",
        "picocolors": "^1.1.1",
        "postcss": "^8.4.47",
        "postcss-import": "^15.1.0",
        "postcss-js": "^4.0.1",
        "postcss-load-config": "^4.0.2",
        "postcss-nested": "^6.2.0",
        "postcss-selector-parser": "^6.1.2",
        "resolve": "^1.22.8",
        "sucrase": "^3.35.0"
      },
      "bin": {
        "tailwind": "lib/cli.js",
        "tailwindcss": "lib/cli.js"
      },
      "engines": {
        "node": ">=14.0.0"
      }
    },
    "node_modules/thenify": {
      "version": "3.3.1",
      "resolved": "https://registry.npmjs.org/thenify/-/thenify-3.3.1.tgz",
      "integrity": "sha512-RVZSIV5IG10Hk3enotrhvz0T9em6cyHBLkH/YAZuKqd8hRkKhSfCGIcP2KUY0EPxndzANBmNllzWPwak+bheSw==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "any-promise": "^1.0.0"
      }
    },
    "node_modules/thenify-all": {
      "version": "1.6.0",
      "resolved": "https://registry.npmjs.org/thenify-all/-/thenify-all-1.6.0.tgz",
      "integrity": "sha512-RNxQH/qI8/t3thXJDwcstUO4zeqo64+Uy/+sNVRBx4Xn2OX+OZ9oP+iJnNFqplFra2ZUVeKCSa2oVWi3T4uVmA==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "thenify": ">= 3.1.0 < 4"
      },
      "engines": {
        "node": ">=0.8"
      }
    },
    "node_modules/to-regex-range": {
      "version": "5.0.1",
      "resolved": "https://registry.npmjs.org/to-regex-range/-/to-regex-range-5.0.1.tgz",
      "integrity": "sha512-65P7iz6X5yEr1cwcgvQxbbIw7Uk3gOy5dIdtZ4rDveLqhrdJP+Li/Hx6tyK0NEb+2GCyneCMJiGqrADCSNk8sQ==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "is-number": "^7.0.0"
      },
      "engines": {
        "node": ">=8.0"
      }
    },
    "node_modules/ts-interface-checker": {
      "version": "0.1.13",
      "resolved": "https://registry.npmjs.org/ts-interface-checker/-/ts-interface-checker-0.1.13.tgz",
      "integrity": "sha512-Y/arvbn+rrz3JCKl9C4kVNfTfSm2/mEp5FSz5EsZSANGPSlQrpRI5M4PKF+mJnE52jOO90PnPSc3Ur3bTQw0gA==",
      "dev": true,
      "license": "Apache-2.0"
    },
    "node_modules/tslib": {
      "version": "2.8.1",
      "resolved": "https://registry.npmjs.org/tslib/-/tslib-2.8.1.tgz",
      "integrity": "sha512-oJFu94HQb+KVduSUQL7wnpmqnfmLsOA/nAh6b6EH0wCEoK0/mPeXU6c3wKDV83MkOuHPRHtSXKKU99IBazS/2w==",
      "license": "0BSD"
    },
    "node_modules/turbo-stream": {
      "version": "2.4.0",
      "resolved": "https://registry.npmjs.org/turbo-stream/-/turbo-stream-2.4.0.tgz",
      "integrity": "sha512-FHncC10WpBd2eOmGwpmQsWLDoK4cqsA/UT/GqNoaKOQnT8uzhtCbg3EoUDMvqpOSAI0S26mr0rkjzbOO6S3v1g==",
      "license": "ISC"
    },
    "node_modules/type-check": {
      "version": "0.4.0",
      "resolved": "https://registry.npmjs.org/type-check/-/type-check-0.4.0.tgz",
      "integrity": "sha512-XleUoc9uwGXqjWwXaUTZAmzMcFZ5858QA2vvx1Ur5xIcixXIP+8LnFDgRplU30us6teqdlskFfu+ae4K79Ooew==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "prelude-ls": "^1.2.1"
      },
      "engines": {
        "node": ">= 0.8.0"
      }
    },
    "node_modules/update-browserslist-db": {
      "version": "1.1.3",
      "resolved": "https://registry.npmjs.org/update-browserslist-db/-/update-browserslist-db-1.1.3.tgz",
      "integrity": "sha512-UxhIZQ+QInVdunkDAaiazvvT/+fXL5Osr0JZlJulepYu6Jd7qJtDZjlur0emRlT71EN3ScPoE7gvsuIKKNavKw==",
      "dev": true,
      "funding": [
        {
          "type": "opencollective",
          "url": "https://opencollective.com/browserslist"
        },
        {
          "type": "tidelift",
          "url": "https://tidelift.com/funding/github/npm/browserslist"
        },
        {
          "type": "github",
          "url": "https://github.com/sponsors/ai"
        }
      ],
      "license": "MIT",
      "dependencies": {
        "escalade": "^3.2.0",
        "picocolors": "^1.1.1"
      },
      "bin": {
        "update-browserslist-db": "cli.js"
      },
      "peerDependencies": {
        "browserslist": ">= 4.21.0"
      }
    },
    "node_modules/uri-js": {
      "version": "4.4.1",
      "resolved": "https://registry.npmjs.org/uri-js/-/uri-js-4.4.1.tgz",
      "integrity": "sha512-7rKUyy33Q1yc98pQ1DAmLtwX109F7TIfWlW1Ydo8Wl1ii1SeHieeh0HHfPeL2fMXK6z0s8ecKs9frCuLJvndBg==",
      "dev": true,
      "license": "BSD-2-Clause",
      "dependencies": {
        "punycode": "^2.1.0"
      }
    },
    "node_modules/use-sync-external-store": {
      "version": "1.5.0",
      "resolved": "https://registry.npmjs.org/use-sync-external-store/-/use-sync-external-store-1.5.0.tgz",
      "integrity": "sha512-Rb46I4cGGVBmjamjphe8L/UnvJD+uPPtTkNvX5mZgqdbavhI4EbgIWJiIHXJ8bc/i9EQGPRh4DwEURJ552Do0A==",
      "license": "MIT",
      "peerDependencies": {
        "react": "^16.8.0 || ^17.0.0 || ^18.0.0 || ^19.0.0"
      }
    },
    "node_modules/util-deprecate": {
      "version": "1.0.2",
      "resolved": "https://registry.npmjs.org/util-deprecate/-/util-deprecate-1.0.2.tgz",
      "integrity": "sha512-EPD5q1uXyFxJpCrLnCc1nHnq3gOa6DZBocAIiI2TaSCA7VCJ1UJDMagCzIkXNsUYfD1daK//LTEQ8xiIbrHtcw==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/vite": {
      "version": "6.2.4",
      "resolved": "https://registry.npmjs.org/vite/-/vite-6.2.4.tgz",
      "integrity": "sha512-veHMSew8CcRzhL5o8ONjy8gkfmFJAd5Ac16oxBUjlwgX3Gq2Wqr+qNC3TjPIpy7TPV/KporLga5GT9HqdrCizw==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "esbuild": "^0.25.0",
        "postcss": "^8.5.3",
        "rollup": "^4.30.1"
      },
      "bin": {
        "vite": "bin/vite.js"
      },
      "engines": {
        "node": "^18.0.0 || ^20.0.0 || >=22.0.0"
      },
      "funding": {
        "url": "https://github.com/vitejs/vite?sponsor=1"
      },
      "optionalDependencies": {
        "fsevents": "~2.3.3"
      },
      "peerDependencies": {
        "@types/node": "^18.0.0 || ^20.0.0 || >=22.0.0",
        "jiti": ">=1.21.0",
        "less": "*",
        "lightningcss": "^1.21.0",
        "sass": "*",
        "sass-embedded": "*",
        "stylus": "*",
        "sugarss": "*",
        "terser": "^5.16.0",
        "tsx": "^4.8.1",
        "yaml": "^2.4.2"
      },
      "peerDependenciesMeta": {
        "@types/node": {
          "optional": true
        },
        "jiti": {
          "optional": true
        },
        "less": {
          "optional": true
        },
        "lightningcss": {
          "optional": true
        },
        "sass": {
          "optional": true
        },
        "sass-embedded": {
          "optional": true
        },
        "stylus": {
          "optional": true
        },
        "sugarss": {
          "optional": true
        },
        "terser": {
          "optional": true
        },
        "tsx": {
          "optional": true
        },
        "yaml": {
          "optional": true
        }
      }
    },
    "node_modules/which": {
      "version": "2.0.2",
      "resolved": "https://registry.npmjs.org/which/-/which-2.0.2.tgz",
      "integrity": "sha512-BLI3Tl1TW3Pvl70l3yq3Y64i+awpwXqsGBYWkkqMtnbXgrMD+yj7rhW0kuEDxzJaYXGjEW5ogapKNMEKNMjibA==",
      "dev": true,
      "license": "ISC",
      "dependencies": {
        "isexe": "^2.0.0"
      },
      "bin": {
        "node-which": "bin/node-which"
      },
      "engines": {
        "node": ">= 8"
      }
    },
    "node_modules/word-wrap": {
      "version": "1.2.5",
      "resolved": "https://registry.npmjs.org/word-wrap/-/word-wrap-1.2.5.tgz",
      "integrity": "sha512-BN22B5eaMMI9UMtjrGd5g5eCYPpCPDUy0FJXbYsaT5zYxjFOckS53SQDE3pWkVoWpHXVb3BrYcEN4Twa55B5cA==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=0.10.0"
      }
    },
    "node_modules/wrap-ansi": {
      "version": "8.1.0",
      "resolved": "https://registry.npmjs.org/wrap-ansi/-/wrap-ansi-8.1.0.tgz",
      "integrity": "sha512-si7QWI6zUMq56bESFvagtmzMdGOtoxfR+Sez11Mobfc7tm+VkUckk9bW2UeffTGVUbOksxmSw0AA2gs8g71NCQ==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "ansi-styles": "^6.1.0",
        "string-width": "^5.0.1",
        "strip-ansi": "^7.0.1"
      },
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/chalk/wrap-ansi?sponsor=1"
      }
    },
    "node_modules/wrap-ansi-cjs": {
      "name": "wrap-ansi",
      "version": "7.0.0",
      "resolved": "https://registry.npmjs.org/wrap-ansi/-/wrap-ansi-7.0.0.tgz",
      "integrity": "sha512-YVGIj2kamLSTxw6NsZjoBxfSwsn0ycdesmc4p+Q21c5zPuZ1pl+NfxVdxPtdHvmNVOQ6XSYG4AUtyt/Fi7D16Q==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "ansi-styles": "^4.0.0",
        "string-width": "^4.1.0",
        "strip-ansi": "^6.0.0"
      },
      "engines": {
        "node": ">=10"
      },
      "funding": {
        "url": "https://github.com/chalk/wrap-ansi?sponsor=1"
      }
    },
    "node_modules/wrap-ansi-cjs/node_modules/ansi-regex": {
      "version": "5.0.1",
      "resolved": "https://registry.npmjs.org/ansi-regex/-/ansi-regex-5.0.1.tgz",
      "integrity": "sha512-quJQXlTSUGL2LH9SUXo8VwsY4soanhgo6LNSm84E1LBcE8s3O0wpdiRzyR9z/ZZJMlMWv37qOOb9pdJlMUEKFQ==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/wrap-ansi-cjs/node_modules/emoji-regex": {
      "version": "8.0.0",
      "resolved": "https://registry.npmjs.org/emoji-regex/-/emoji-regex-8.0.0.tgz",
      "integrity": "sha512-MSjYzcWNOA0ewAHpz0MxpYFvwg6yjy1NG3xteoqz644VCo/RPgnr1/GGt+ic3iJTzQ8Eu3TdM14SawnVUmGE6A==",
      "dev": true,
      "license": "MIT"
    },
    "node_modules/wrap-ansi-cjs/node_modules/string-width": {
      "version": "4.2.3",
      "resolved": "https://registry.npmjs.org/string-width/-/string-width-4.2.3.tgz",
      "integrity": "sha512-wKyQRQpjJ0sIp62ErSZdGsjMJWsap5oRNihHhu6G7JVO/9jIB6UyevL+tXuOqrng8j/cxKTWyWUwvSTriiZz/g==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "emoji-regex": "^8.0.0",
        "is-fullwidth-code-point": "^3.0.0",
        "strip-ansi": "^6.0.1"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/wrap-ansi-cjs/node_modules/strip-ansi": {
      "version": "6.0.1",
      "resolved": "https://registry.npmjs.org/strip-ansi/-/strip-ansi-6.0.1.tgz",
      "integrity": "sha512-Y38VPSHcqkFrCpFnQ9vuSXmquuv5oXOKpGeT6aGrr3o3Gc9AlVa6JBfUSOCnbxGGZF+/0ooI7KrPuUSztUdU5A==",
      "dev": true,
      "license": "MIT",
      "dependencies": {
        "ansi-regex": "^5.0.1"
      },
      "engines": {
        "node": ">=8"
      }
    },
    "node_modules/wrap-ansi/node_modules/ansi-styles": {
      "version": "6.2.1",
      "resolved": "https://registry.npmjs.org/ansi-styles/-/ansi-styles-6.2.1.tgz",
      "integrity": "sha512-bN798gFfQX+viw3R7yrGWRqnrN2oRkEkUjjl4JNn4E8GxxbjtG3FbrEIIY3l8/hrwUwIeCZvi4QuOTP4MErVug==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=12"
      },
      "funding": {
        "url": "https://github.com/chalk/ansi-styles?sponsor=1"
      }
    },
    "node_modules/yallist": {
      "version": "3.1.1",
      "resolved": "https://registry.npmjs.org/yallist/-/yallist-3.1.1.tgz",
      "integrity": "sha512-a4UGQaWPH59mOXUYnAG2ewncQS4i4F43Tv3JoAM+s2VDAmS9NsK8GpDMLrCHPksFT7h3K6TOoUNn2pb7RoXx4g==",
      "dev": true,
      "license": "ISC"
    },
    "node_modules/yaml": {
      "version": "2.7.1",
      "resolved": "https://registry.npmjs.org/yaml/-/yaml-2.7.1.tgz",
      "integrity": "sha512-10ULxpnOCQXxJvBgxsn9ptjq6uviG/htZKk9veJGhlqn3w/DxQ631zFF+nlQXLwmImeS5amR2dl2U8sg6U9jsQ==",
      "dev": true,
      "license": "ISC",
      "bin": {
        "yaml": "bin.mjs"
      },
      "engines": {
        "node": ">= 14"
      }
    },
    "node_modules/yocto-queue": {
      "version": "0.1.0",
      "resolved": "https://registry.npmjs.org/yocto-queue/-/yocto-queue-0.1.0.tgz",
      "integrity": "sha512-rVksvsnNCdJ/ohGc6xgPwyN8eheCxsiLM8mxuE/t/mOVqJewPuO1miLpTHQiRgTKCLexL4MeAFVagts7HmNZ2Q==",
      "dev": true,
      "license": "MIT",
      "engines": {
        "node": ">=10"
      },
      "funding": {
        "url": "https://github.com/sponsors/sindresorhus"
      }
    }
  }
}

```

### `frontend\package.json`

```json
{
  "name": "frontend",
  "private": true,
  "version": "0.0.0",
  "type": "module",
  "scripts": {
    "dev": "vite",
    "build": "vite build",
    "lint": "eslint .",
    "preview": "vite preview"
  },
  "dependencies": {
    "@faker-js/faker": "^9.7.0",
    "@reduxjs/toolkit": "^2.6.1",
    "argon2-browser": "^1.18.0",
    "axios": "^1.8.4",
    "crypto-js": "^4.2.0",
    "dompurify": "^3.2.5",
    "framer-motion": "^12.6.5",
    "lodash": "^4.17.21",
    "lucide-react": "^0.486.0",
    "react": "^19.0.0",
    "react-circular-progressbar": "^2.2.0",
    "react-dom": "^19.0.0",
    "react-icons": "^5.5.0",
    "react-redux": "^9.2.0",
    "react-router-dom": "^7.4.1",
    "react-toastify": "^11.0.5"
  },
  "devDependencies": {
    "@eslint/js": "^9.21.0",
    "@types/react": "^19.0.10",
    "@types/react-dom": "^19.0.4",
    "@vitejs/plugin-react": "^4.3.4",
    "autoprefixer": "^10.4.21",
    "eslint": "^9.21.0",
    "eslint-plugin-react-hooks": "^5.1.0",
    "eslint-plugin-react-refresh": "^0.4.19",
    "globals": "^15.15.0",
    "postcss": "^8.5.3",
    "tailwindcss": "^3.4.17",
    "vite": "^6.2.0"
  }
}

```

### `frontend\postcss.config.js`

```javascript
export default {
  plugins: {
    tailwindcss: {},
    autoprefixer: {},
  },
}

```

### `frontend\public\vite.svg`

```
<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" role="img" class="iconify iconify--logos" width="31.88" height="32" preserveAspectRatio="xMidYMid meet" viewBox="0 0 256 257"><defs><linearGradient id="IconifyId1813088fe1fbc01fb466" x1="-.828%" x2="57.636%" y1="7.652%" y2="78.411%"><stop offset="0%" stop-color="#41D1FF"></stop><stop offset="100%" stop-color="#BD34FE"></stop></linearGradient><linearGradient id="IconifyId1813088fe1fbc01fb467" x1="43.376%" x2="50.316%" y1="2.242%" y2="89.03%"><stop offset="0%" stop-color="#FFEA83"></stop><stop offset="8.333%" stop-color="#FFDD35"></stop><stop offset="100%" stop-color="#FFA800"></stop></linearGradient></defs><path fill="url(#IconifyId1813088fe1fbc01fb466)" d="M255.153 37.938L134.897 252.976c-2.483 4.44-8.862 4.466-11.382.048L.875 37.958c-2.746-4.814 1.371-10.646 6.827-9.67l120.385 21.517a6.537 6.537 0 0 0 2.322-.004l117.867-21.483c5.438-.991 9.574 4.796 6.877 9.62Z"></path><path fill="url(#IconifyId1813088fe1fbc01fb467)" d="M185.432.063L96.44 17.501a3.268 3.268 0 0 0-2.634 3.014l-5.474 92.456a3.268 3.268 0 0 0 3.997 3.378l24.777-5.718c2.318-.535 4.413 1.507 3.936 3.838l-7.361 36.047c-.495 2.426 1.782 4.5 4.151 3.78l15.304-4.649c2.372-.72 4.652 1.36 4.15 3.788l-11.698 56.621c-.732 3.542 3.979 5.473 5.943 2.437l1.313-2.028l72.516-144.72c1.215-2.423-.88-5.186-3.54-4.672l-25.505 4.922c-2.396.462-4.435-1.77-3.759-4.114l16.646-57.705c.677-2.35-1.37-4.583-3.769-4.113Z"></path></svg>
```

### `frontend\README.md`

```markdown
# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript and enable type-aware lint rules. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

```

### `frontend\src\app\slices\sharedAppsSlice.js`

```javascript
import { createSlice } from "@reduxjs/toolkit";

const initialState = {
  sharedApps: [],
};

const sharedAppsSlice = createSlice({
  name: "sharedApps",
  initialState,
  reducers: {
    setSharedAppsData: (state, action) => {
      state.sharedApps = action.payload;
    },
    addSharedApp: (state, action) => {
      state.sharedApps.push(action.payload);
    },
    removeSharedApp: (state, action) => {
      state.sharedApps = state.sharedApps.filter(
        (app) => app._id !== action.payload
      );
    },
    updateSharedAppLocal: (state, action) => {
      const index = state.sharedApps.findIndex(app => app._id === action.payload._id);
      if (index !== -1) {
        state.sharedApps[index] = action.payload;
      }
    },
  },
});

export const {
  setSharedAppsData,
  addSharedApp,
  removeSharedApp,
  updateSharedAppLocal,
} = sharedAppsSlice.actions;

export default sharedAppsSlice.reducer;
```

### `frontend\src\app\slices\ThemeSlice.js`

```javascript
import { createSlice } from '@reduxjs/toolkit'

const initialState = {
    darkTheme: localStorage.getItem("darkTheme") === "true" ? true : false,  
  }

export const themeSlice = createSlice({
    name: 'theme',
    initialState,
    reducers: {
        toggleTheme: (state) => {
            //save to local storage
            localStorage.setItem('darkTheme', !state.darkTheme)
            state.darkTheme = !state.darkTheme
        },
    },
})


export default themeSlice.reducer

// Action creators are generated for each case reducer function
export const { toggleTheme } = themeSlice.actions
```

### `frontend\src\app\slices\userSlice.js`

```javascript
import { createSlice } from "@reduxjs/toolkit";

const initialState = {
    
} // initial state of the user slice

const userSlice = createSlice({
    name:"user", 
    initialState,
    reducers:{
        setUser: (state, action) => {
            state.user = action.payload; // set user in the state
        },
        removeUser: (state) => {
            state.user = null; // remove user from the state
        },
    }
})


export default userSlice.reducer // export the reducer


export const { setUser, removeUser } = userSlice.actions // export the actions
```

### `frontend\src\app\slices\vaultSlice.js`

```javascript
import { createSlice } from '@reduxjs/toolkit';

const vaultSlice = createSlice({
  name: 'vault',
  initialState: {
    unlocked: false,
  },
  reducers: {
    setVaultUnlocked: (state, action) => {
      state.unlocked = action.payload;
    },
    resetVault: (state) => {
      state.unlocked = false;
    },
  },
});

export const { setVaultUnlocked, resetVault } = vaultSlice.actions;
export default vaultSlice.reducer;

```

### `frontend\src\app\Store.js`

```javascript
import { configureStore } from '@reduxjs/toolkit'
import themeReducer from './slices/ThemeSlice'
import userReducer from './slices/userSlice'
import sharedAppsReducer from './slices/sharedAppsSlice';
import vaultReducer from './slices/vaultSlice';
const store = configureStore({
  reducer: {
    theme: themeReducer,
    user: userReducer,
    sharedApps: sharedAppsReducer,
    vault: vaultReducer, 

  }
})

export default store
```

### `frontend\src\App.jsx`

```javascript
import React from "react";
import AppRoutes from "./Routes/AppRoutes";
import { ToastContainer } from "react-toastify";
import NavBar from "./components/NavBar/NavBar";
import Protected from "./HOC/Protected";

const App = () => {
  return (
    <div>
      <NavBar />

      <AppRoutes />
      <ToastContainer />
    </div>
  );
};

export default App;

```

### `frontend\src\assets\loader.svg`

```
﻿<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 200 200'><path fill='#452A72' stroke='#452A72' stroke-width='15' transform-origin='center' d='m148 84.7 13.8-8-10-17.3-13.8 8a50 50 0 0 0-27.4-15.9v-16h-20v16A50 50 0 0 0 63 67.4l-13.8-8-10 17.3 13.8 8a50 50 0 0 0 0 31.7l-13.8 8 10 17.3 13.8-8a50 50 0 0 0 27.5 15.9v16h20v-16a50 50 0 0 0 27.4-15.9l13.8 8 10-17.3-13.8-8a50 50 0 0 0 0-31.7Zm-47.5 50.8a35 35 0 1 1 0-70 35 35 0 0 1 0 70Z'><animateTransform type='rotate' attributeName='transform' calcMode='spline' dur='2' values='0;120' keyTimes='0;1' keySplines='0 0 1 1' repeatCount='indefinite'></animateTransform></path></svg>
```

### `frontend\src\assets\PrevGuard.svg`

```
<!DOCTYPE svg PUBLIC "-//W3C//DTD SVG 1.1//EN" "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd">
<!-- Uploaded to: SVG Repo, www.svgrepo.com, Transformed by: SVG Repo Mixer Tools -->
<svg height="800px" width="800px" version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 512.001 512.001" xml:space="preserve" fill="##221736" stroke="##221736">
<g id="SVGRepo_bgCarrier" stroke-width="0"/>
<g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"/>
<g id="SVGRepo_iconCarrier"> <path style="fill:#A66CFF ;" d="M205.949,173.83c29.881,0,43.286,16.747,48.561,26.585c0.663,1.235,2.461,1.233,3.121-0.003 c5.257-9.838,18.589-26.582,48.466-26.582c34.035,0,63.975,23.233,63.975,65.659c0,17.168-3.498,31.876-13.208,48.289 c-19.789,33.45-84.977,76.812-98.368,85.357c-1.48,0.945-3.355,0.948-4.838,0.006c-13.401-8.504-78.602-51.651-98.546-85.363 c-9.71-16.414-13.185-31.121-13.185-48.289C141.925,197.063,171.912,173.83,205.949,173.83z"/> <g> <path style="fill:#A66CFF ;" d="M256.069,388.356c-3.61,0-7.133-1.024-10.188-2.961c-8.175-5.189-80.523-51.791-103.261-90.226 c-10.517-17.778-15.207-34.949-15.207-55.678c0-24.068,8.226-44.568,23.789-59.282c14.245-13.47,33.687-20.887,54.745-20.887 c24.555,0,40.392,9.59,50.108,19.242c9.7-9.654,25.509-19.242,50.041-19.242c21.057,0,40.492,7.419,54.725,20.892 c15.543,14.713,23.76,35.212,23.76,59.278c0,20.701-4.697,37.873-15.231,55.678c-22.578,38.164-94.881,84.987-103.052,90.2 C263.233,387.323,259.697,388.356,256.069,388.356z M205.949,188.34c-24.645,0-49.514,15.816-49.514,51.149 c0,15.649,3.234,27.499,11.164,40.901c14.668,24.796,61.498,59.353,88.456,77.029c26.952-17.76,73.756-52.415,88.318-77.029 c7.946-13.432,11.187-25.282,11.187-40.901c0-35.335-24.844-51.149-49.465-51.149c-21.13,0-31.059,10.283-35.67,18.911 c-2.832,5.302-8.335,8.599-14.359,8.599c-6.013,0-11.511-3.288-14.348-8.58C237.09,198.635,227.125,188.34,205.949,188.34z"/> <path style="fill:#A66CFF ;" d="M255.998,512.001c-2.251,0-4.501-0.522-6.563-1.57c-23.631-11.985-59.104-31.163-93.896-54.456 c-32.881-22.013-59.465-43.749-79.016-64.606c-18.873-20.134-29.267-46.439-29.267-74.068V109.147 c0-7.251,5.351-13.388,12.534-14.375c69.38-9.536,135.48-41.745,186.125-90.695c5.624-5.435,14.543-5.435,20.168,0 c27.092,26.185,58.341,47.513,92.874,63.391c7.281,3.347,10.469,11.964,7.123,19.245c-3.347,7.283-11.962,10.472-19.245,7.122 c-33.306-15.312-63.806-35.301-90.839-59.513c-50.425,45.102-113.384,75.67-179.719,87.245v195.735 c0,20.228,7.608,39.485,21.42,54.221c18.043,19.249,42.937,39.55,73.988,60.337c30.518,20.432,61.682,37.636,84.315,49.328 c22.633-11.694,53.797-28.897,84.315-49.328c31.052-20.789,55.945-41.088,73.988-60.337c13.814-14.736,21.42-33.993,21.42-54.221 V109.147c0-8.014,6.496-14.51,14.51-14.51s14.51,6.496,14.51,14.51v208.155c0,27.629-10.394,53.932-29.267,74.068 c-19.551,20.857-46.135,42.593-79.017,64.606c-34.792,23.293-70.263,42.471-93.895,54.456 C260.499,511.478,258.247,512.001,255.998,512.001z"/> </g> </g>
</svg>
```

### `frontend\src\assets\react.svg`

```
<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" role="img" class="iconify iconify--logos" width="35.93" height="32" preserveAspectRatio="xMidYMid meet" viewBox="0 0 256 228"><path fill="#00D8FF" d="M210.483 73.824a171.49 171.49 0 0 0-8.24-2.597c.465-1.9.893-3.777 1.273-5.621c6.238-30.281 2.16-54.676-11.769-62.708c-13.355-7.7-35.196.329-57.254 19.526a171.23 171.23 0 0 0-6.375 5.848a155.866 155.866 0 0 0-4.241-3.917C100.759 3.829 77.587-4.822 63.673 3.233C50.33 10.957 46.379 33.89 51.995 62.588a170.974 170.974 0 0 0 1.892 8.48c-3.28.932-6.445 1.924-9.474 2.98C17.309 83.498 0 98.307 0 113.668c0 15.865 18.582 31.778 46.812 41.427a145.52 145.52 0 0 0 6.921 2.165a167.467 167.467 0 0 0-2.01 9.138c-5.354 28.2-1.173 50.591 12.134 58.266c13.744 7.926 36.812-.22 59.273-19.855a145.567 145.567 0 0 0 5.342-4.923a168.064 168.064 0 0 0 6.92 6.314c21.758 18.722 43.246 26.282 56.54 18.586c13.731-7.949 18.194-32.003 12.4-61.268a145.016 145.016 0 0 0-1.535-6.842c1.62-.48 3.21-.974 4.76-1.488c29.348-9.723 48.443-25.443 48.443-41.52c0-15.417-17.868-30.326-45.517-39.844Zm-6.365 70.984c-1.4.463-2.836.91-4.3 1.345c-3.24-10.257-7.612-21.163-12.963-32.432c5.106-11 9.31-21.767 12.459-31.957c2.619.758 5.16 1.557 7.61 2.4c23.69 8.156 38.14 20.213 38.14 29.504c0 9.896-15.606 22.743-40.946 31.14Zm-10.514 20.834c2.562 12.94 2.927 24.64 1.23 33.787c-1.524 8.219-4.59 13.698-8.382 15.893c-8.067 4.67-25.32-1.4-43.927-17.412a156.726 156.726 0 0 1-6.437-5.87c7.214-7.889 14.423-17.06 21.459-27.246c12.376-1.098 24.068-2.894 34.671-5.345a134.17 134.17 0 0 1 1.386 6.193ZM87.276 214.515c-7.882 2.783-14.16 2.863-17.955.675c-8.075-4.657-11.432-22.636-6.853-46.752a156.923 156.923 0 0 1 1.869-8.499c10.486 2.32 22.093 3.988 34.498 4.994c7.084 9.967 14.501 19.128 21.976 27.15a134.668 134.668 0 0 1-4.877 4.492c-9.933 8.682-19.886 14.842-28.658 17.94ZM50.35 144.747c-12.483-4.267-22.792-9.812-29.858-15.863c-6.35-5.437-9.555-10.836-9.555-15.216c0-9.322 13.897-21.212 37.076-29.293c2.813-.98 5.757-1.905 8.812-2.773c3.204 10.42 7.406 21.315 12.477 32.332c-5.137 11.18-9.399 22.249-12.634 32.792a134.718 134.718 0 0 1-6.318-1.979Zm12.378-84.26c-4.811-24.587-1.616-43.134 6.425-47.789c8.564-4.958 27.502 2.111 47.463 19.835a144.318 144.318 0 0 1 3.841 3.545c-7.438 7.987-14.787 17.08-21.808 26.988c-12.04 1.116-23.565 2.908-34.161 5.309a160.342 160.342 0 0 1-1.76-7.887Zm110.427 27.268a347.8 347.8 0 0 0-7.785-12.803c8.168 1.033 15.994 2.404 23.343 4.08c-2.206 7.072-4.956 14.465-8.193 22.045a381.151 381.151 0 0 0-7.365-13.322Zm-45.032-43.861c5.044 5.465 10.096 11.566 15.065 18.186a322.04 322.04 0 0 0-30.257-.006c4.974-6.559 10.069-12.652 15.192-18.18ZM82.802 87.83a323.167 323.167 0 0 0-7.227 13.238c-3.184-7.553-5.909-14.98-8.134-22.152c7.304-1.634 15.093-2.97 23.209-3.984a321.524 321.524 0 0 0-7.848 12.897Zm8.081 65.352c-8.385-.936-16.291-2.203-23.593-3.793c2.26-7.3 5.045-14.885 8.298-22.6a321.187 321.187 0 0 0 7.257 13.246c2.594 4.48 5.28 8.868 8.038 13.147Zm37.542 31.03c-5.184-5.592-10.354-11.779-15.403-18.433c4.902.192 9.899.29 14.978.29c5.218 0 10.376-.117 15.453-.343c-4.985 6.774-10.018 12.97-15.028 18.486Zm52.198-57.817c3.422 7.8 6.306 15.345 8.596 22.52c-7.422 1.694-15.436 3.058-23.88 4.071a382.417 382.417 0 0 0 7.859-13.026a347.403 347.403 0 0 0 7.425-13.565Zm-16.898 8.101a358.557 358.557 0 0 1-12.281 19.815a329.4 329.4 0 0 1-23.444.823c-7.967 0-15.716-.248-23.178-.732a310.202 310.202 0 0 1-12.513-19.846h.001a307.41 307.41 0 0 1-10.923-20.627a310.278 310.278 0 0 1 10.89-20.637l-.001.001a307.318 307.318 0 0 1 12.413-19.761c7.613-.576 15.42-.876 23.31-.876H128c7.926 0 15.743.303 23.354.883a329.357 329.357 0 0 1 12.335 19.695a358.489 358.489 0 0 1 11.036 20.54a329.472 329.472 0 0 1-11 20.722Zm22.56-122.124c8.572 4.944 11.906 24.881 6.52 51.026c-.344 1.668-.73 3.367-1.15 5.09c-10.622-2.452-22.155-4.275-34.23-5.408c-7.034-10.017-14.323-19.124-21.64-27.008a160.789 160.789 0 0 1 5.888-5.4c18.9-16.447 36.564-22.941 44.612-18.3ZM128 90.808c12.625 0 22.86 10.235 22.86 22.86s-10.235 22.86-22.86 22.86s-22.86-10.235-22.86-22.86s10.235-22.86 22.86-22.86Z"></path></svg>
```

### `frontend\src\components\AddPasswordModal.jsx`

```javascript
import { useState } from "react";
import { X } from "lucide-react";
import { toast } from "react-toastify";
import axiosInstance from "../config/axios/axios";
import { useSelector } from "react-redux";

const AddPasswordModal = ({ isOpen, onClose, onSuccess }) => {
  const [title, setTitle] = useState("");
  const [username, setUsername] = useState("");
  const [password, setPassword] = useState("");
  const [loading, setLoading] = useState(false);
  const darkTheme = useSelector((state) => state.theme.darkTheme);

  const handleSubmit = async (e) => {
    e.preventDefault();
    if (!title || !password) {
      toast.error("App name and password are required");
      return;
    }

    setLoading(true);
    try {
      const res = await axiosInstance.post("/api/vault/add", {
        title,
        username,
        password,
      });

      onSuccess?.({
        title,
        username,
        password,
      });
      onClose?.();

      // Reset inputs
      setTitle("");
      setUsername("");
      setPassword("");
    } catch (err) {
      console.error(err);
      toast.error("Failed to save password");
    } finally {
      setLoading(false);
    }
  };

  if (!isOpen) return null;

  return (
    <div className="fixed inset-0 z-50 flex items-center justify-center bg-black/60 backdrop-blur-sm">
      <div
        className={`relative w-[90%] max-w-md p-6 rounded-2xl shadow-xl border ${
          darkTheme
            ? "bg-dark-background text-dark-primaryText border-dark-hover"
            : "bg-light-background text-light-primaryText border-light-hover"
        }`}
      >
        {/* Close Button */}
        <button
          onClick={onClose}
          className={`absolute top-3 right-3 transition-colors ${
            darkTheme
              ? "text-dark-secondaryText hover:text-dark-accent"
              : "text-light-secondaryText hover:text-light-accent"
          }`}
        >
          <X size={22} />
        </button>

        {/* Header */}
        <h2 className="text-xl font-bold mb-2">➕ Add New Password</h2>

        {/* Form */}
        <form onSubmit={handleSubmit} className="space-y-4">
          <input
            type="text"
            placeholder="App / Site Name"
            value={title}
            onChange={(e) => setTitle(e.target.value)}
            className={`w-full p-3 rounded-xl outline-none ${
              darkTheme
                ? "bg-dark-secondary text-dark-primaryText placeholder-dark-secondaryText"
                : "bg-light-secondary text-light-primaryText placeholder-light-secondaryText"
            }`}
          />
          <input
            type="text"
            placeholder="Username (optional)"
            value={username}
            onChange={(e) => setUsername(e.target.value)}
            className={`w-full p-3 rounded-xl outline-none ${
              darkTheme
                ? "bg-dark-secondary text-dark-primaryText placeholder-dark-secondaryText"
                : "bg-light-secondary text-light-primaryText placeholder-light-secondaryText"
            }`}
          />
          <input
            type="text"
            placeholder="Password"
            value={password}
            onChange={(e) => setPassword(e.target.value)}
            className={`w-full p-3 rounded-xl outline-none ${
              darkTheme
                ? "bg-dark-secondary text-dark-primaryText placeholder-dark-secondaryText"
                : "bg-light-secondary text-light-primaryText placeholder-light-secondaryText"
            }`}
          />

          <button
            type="submit"
            disabled={loading}
            className={`w-full py-2 rounded-xl font-semibold transition-all ${
              darkTheme
                ? "bg-dark-action hover:bg-dark-hover text-white"
                : "bg-light-action hover:bg-light-hover text-white"
            }`}
          >
            {loading ? "Saving..." : "Save Password"}
          </button>
        </form>
      </div>
    </div>
  );
};

export default AddPasswordModal;

```

### `frontend\src\components\DeleteConfirmModal.jsx`

```javascript
import { X } from "lucide-react";
import { useSelector } from "react-redux";

const DeleteConfirmModal = ({ isOpen, onConfirm, onCancel }) => {
  const darkTheme = useSelector((state) => state.theme.darkTheme);

  if (!isOpen) return null;

  return (
    <div className="fixed inset-0 z-50 flex items-center justify-center bg-black/60 backdrop-blur-sm">
      <div
        className={`relative w-[90%] max-w-md p-6 rounded-2xl shadow-xl border ${
          darkTheme
            ? "bg-dark-background text-dark-primaryText border-dark-hover"
            : "bg-light-background text-light-primaryText border-light-hover"
        }`}
      >
        {/* Close Button */}
        <button
          onClick={onCancel}
          className={`absolute top-3 right-3 transition-colors ${
            darkTheme
              ? "text-dark-secondaryText hover:text-dark-accent"
              : "text-light-secondaryText hover:text-light-accent"
          }`}
        >
          <X size={20} />
        </button>

        <h2 className="text-xl font-bold mb-2">⚠️ Confirm Deletion</h2>
        <p
          className={`text-sm ${
            darkTheme ? "text-dark-secondaryText" : "text-light-secondaryText"
          }`}
        >
          Are you sure you want to delete this password? This action cannot be
          undone.
        </p>

        <div className="mt-6 flex justify-end gap-4">
          <button
            onClick={onCancel}
            className={`px-4 py-2 rounded-lg font-semibold transition-all ${
              darkTheme
                ? "bg-dark-secondary text-white hover:bg-dark-hover"
                : "bg-light-secondary text-black hover:bg-light-hover"
            }`}
          >
            Cancel
          </button>
          <button
            onClick={onConfirm}
            className="px-4 py-2 bg-red-600 hover:bg-red-700 text-white font-semibold rounded-lg transition-all"
          >
            Yes, Delete
          </button>
        </div>
      </div>
    </div>
  );
};

export default DeleteConfirmModal;

```

### `frontend\src\components\Loading.jsx`

```javascript
import React from "react";

const Loading = () => {
  return (
    <div className="w-5 h-5 border-4 border-blue-500 border-dotted rounded-full animate-spin"></div>
  );
};

export default Loading;

```

### `frontend\src\components\LoadingScreen\LoadingScreen.jsx`

```javascript
import React from "react";
import { useSelector } from "react-redux";
import loader from "../../assets/loader.svg"; // Import the SVG properly

const LoadingScreen = () => {
  const { darkTheme } = useSelector((state) => state.theme);

  return (
    <div
      className={`min-h-screen flex flex-col items-center justify-center ${
        darkTheme
          ? "bg-dark-background text-dark-primaryText"
          : "bg-light-background text-light-primaryText"
      }`}
    >
      <div className="flex flex-col items-center">
        {/* Custom SVG Loader */}
        <img src={loader} alt="Loading..." className="w-32 h-32" />

        <p className="mt-4 text-lg font-semibold">Loading, please wait...</p>
      </div>
    </div>
  );
};

export default LoadingScreen;

```

### `frontend\src\components\LogoutPopup\hook\useOnConfirm.js`

```javascript
import { toast } from "react-toastify";
import { removeUser } from "../../../app/slices/userSlice";

  const useOnconfirm = (dispatch,navigate) => {
    // Handle logout confirmation logic here
    localStorage.removeItem("token"); // Clear user data from local storage
    dispatch(removeUser())
    toast.success("Logged out successfully", {
      position: "top-right",
      autoClose: 5000,
      hideProgressBar: false,
      closeOnClick: false,
      pauseOnHover: true,
      draggable: true,
      progress: undefined,
      theme: "light",
    });
    setTimeout(() => {
      navigate("/"); // Redirect to login page or home page
    }, 1000);    
  };

  export default useOnconfirm;
```

### `frontend\src\components\LogoutPopup\LogoutPopup.jsx`

```javascript
import React from "react";
import { IoIosLogOut } from "react-icons/io";
import { HiX } from "react-icons/hi";
import { useDispatch } from "react-redux";
import { useNavigate } from "react-router-dom";
import useOnconfirm from "./hook/useOnConfirm";

const LogoutPopup = ({ isOpen, onClose }) => {
  if (!isOpen) return null;
  const dispatch = useDispatch();
  const navigate = useNavigate();

  return (
    <div className="fixed inset-0 bg-black/40 backdrop-blur-sm flex items-center justify-center z-50">
      <div className="relative bg-light-secondary dark:bg-dark-secondary border border-light-border dark:border-dark-border shadow-lg rounded-lg p-6 w-80">
        {/* Close Button (X) */}
        <button
          onClick={onClose}
          className="absolute top-2 right-2 text-lg text-light-primaryText dark:text-dark-primaryText hover:text-light-accent dark:hover:text-dark-accent transition"
        >
          <HiX />
        </button>

        {/* Confirmation Text */}
        <h3 className="text-lg font-semibold text-center text-light-primaryText dark:text-dark-primaryText">
          Are you sure you want to logout?
        </h3>

        {/* Action Buttons */}
        <div className="flex justify-center gap-4 mt-4">
          <button
            onClick={() => {
              useOnconfirm(dispatch, navigate);
              onClose();
            }}
            className="flex items-center gap-2 px-4 py-2 text-lg bg-red-500 text-white rounded-md hover:bg-red-600 transition"
          >
            Yes, Logout <IoIosLogOut />
          </button>
          <button
            onClick={onClose}
            className="px-4 py-2 text-lg bg-gray-500 text-white rounded-md hover:bg-gray-600 transition"
          >
            Cancel
          </button>
        </div>
      </div>
    </div>
  );
};

export default LogoutPopup;

```

### `frontend\src\components\NavBar\NavBar.jsx`

```javascript
import React, { useEffect, useState } from "react";
import { Link } from "react-router-dom";
import { HiMenu } from "react-icons/hi";
import ThemeButton from "../../components/ThemeButton";
import Logo from "../../assets/PrevGuard.svg";
import SideBar from "../SideBar/SideBar";
import { PiSignInDuotone } from "react-icons/pi";
import { useDispatch, useSelector } from "react-redux";
import axiosInstance from "../../config/axios/axios";
import { setUser } from "../../app/slices/userSlice";
import { motion } from "framer-motion";

const NavBar = () => {
  const [isSidebarOpen, setIsSidebarOpen] = useState(false);
  const user = useSelector((state) => state.user.user);
  const { darkTheme } = useSelector((state) => state.theme);
  const dispatch = useDispatch();

  useEffect(() => {
    const isUserLoggedIn = async () => {
      axiosInstance
        .get("/api/auth/authme")
        .then((res) => {
          dispatch(setUser(res.data.user));
        })
        .catch((e) => {
          console.log(e);
          dispatch(setUser(null));
        });
    };
    isUserLoggedIn();
  }, []);

  // Animation variants
  const navbarVariants = {
    hidden: { y: -100, opacity: 0 },
    visible: {
      y: 0,
      opacity: 1,
      transition: {
        type: "spring",
        stiffness: 120,
        damping: 20,
        staggerChildren: 0.1,
        delayChildren: 0.2,
      },
    },
  };

  const itemVariants = {
    hidden: { y: -20, opacity: 0 },
    visible: {
      y: 0,
      opacity: 1,
      transition: {
        type: "spring",
        stiffness: 100,
      },
    },
  };

  const logoVariants = {
    hidden: { scale: 0.8, opacity: 0 },
    visible: {
      scale: 1,
      opacity: 1,
      transition: {
        type: "spring",
        stiffness: 150,
      },
    },
    hover: {
      scale: 1.05,
      transition: {
        duration: 0.2,
      },
    },
  };

  return (
    <>
      <motion.nav
        className="top-0 left-0 w-full bg-light-background/80 dark:bg-dark-background/80 backdrop-blur-lg shadow-md flex justify-between items-center px-3 py-2 md:px-4 md:py-3 lg:p-4 z-50"
        initial="hidden"
        animate="visible"
        variants={navbarVariants}
      >
        {/* Left Section */}
        <div className="flex items-center gap-2 md:gap-4">
          <motion.button
            onClick={() => setIsSidebarOpen(!isSidebarOpen)}
            className="text-light-primaryText dark:text-dark-primaryText text-lg md:text-xl lg:text-2xl hover:text-light-accent dark:hover:text-dark-accent transition"
            variants={itemVariants}
            whileHover={{ rotate: 180, scale: 1.1 }}
            whileTap={{ scale: 0.9 }}
          >
            <HiMenu />
          </motion.button>

          <motion.div variants={itemVariants}>
            <Link to={"/"}>
              <motion.img
                src={Logo}
                alt="PrevGuard Logo"
                className="h-7 md:h-8 lg:h-10"
                variants={logoVariants}
                whileHover="hover"
              />
            </Link>
          </motion.div>
        </div>

        {/* Center Title */}
        <motion.div variants={itemVariants} whileHover={{ scale: 1.05 }}>
          <Link
            to={"/"}
            className="hidden md:block text-lg lg:text-xl font-semibold text-light-primaryText dark:text-dark-primaryText bg-gradient-to-r from-light-accent to-light-action dark:from-dark-accent dark:to-dark-action bg-clip-text text-transparent"
          >
            PrivGuard
          </Link>
        </motion.div>

        {/* Right Section */}
        <motion.div className="flex items-center gap-2 md:gap-4" variants={itemVariants}>
          <motion.div variants={itemVariants} whileHover={{ scale: 1.1 }} whileTap={{ scale: 0.95 }}>
            <ThemeButton />
          </motion.div>

          {user ? (
            <motion.div
              variants={itemVariants}
              whileHover={{ scale: 1.1 }}
              whileTap={{ scale: 0.95 }}
            >
              <Link to="/profile">
                <motion.img
                  src={user.profilePicture}
                  alt="Profile"
                  className="h-7 w-7 md:h-8 md:w-8 lg:h-10 lg:w-10 rounded-full border border-light-accent dark:border-dark-accent cursor-pointer"
                  initial={{ opacity: 0 }}
                  animate={{ opacity: 1 }}
                  whileHover={{
                    boxShadow: `0 0 8px ${darkTheme ? '#A66CFF' : '#874CCC'}`
                  }}
                />
              </Link>
            </motion.div>
          ) : (
            <motion.div className="flex gap-2 items-center" variants={itemVariants}>
              <motion.div whileHover={{ scale: 1.05 }} whileTap={{ scale: 0.95 }}>
                <Link
                  to="/register"
                  className="text-xs md:text-sm text-light-primaryText dark:text-dark-primaryText hover:text-light-accent dark:hover:text-dark-accent mt-1 transition"
                >
                  New? here!
                </Link>
              </motion.div>
              <motion.div
                whileHover={{ scale: 1.1, rotate: 5, transition: { duration: 0.2 } }}
                whileTap={{ scale: 0.95 }}
              >
                <Link to="/login">
                  <PiSignInDuotone
                    className={`inline-block h-8 w-8 rounded-full ${
                      darkTheme ? "text-[#E3DFFD]" : "text-[#241847]"
                    }`}
                  />
                </Link>
              </motion.div>
            </motion.div>
          )}
        </motion.div>
      </motion.nav>

      <SideBar isOpen={isSidebarOpen} onClose={() => setIsSidebarOpen(false)} />
    </>
  );
};

export default NavBar;

```

### `frontend\src\components\ProfileEditModal\ProfileEditModal.jsx`

```javascript
import React, { useState } from "react";
import axiosInstance from "../../config/axios/axios";
import { X } from "lucide-react";
import { toast } from "react-toastify";
import { setUser } from "../../app/slices/userSlice";
import { useDispatch, useSelector } from "react-redux";


export default function ProfileEditModal({ user, onClose, onUpdate }) {
  const [username, setUsername] = useState(user.username);
  const [phoneNumber, setPhoneNumber] = useState(user.phoneNumber);
  const [image, setImage] = useState(null);
  const [loading, setLoading] = useState(false);
  const dispatch = useDispatch(); // Assuming you have a Redux store to manage user state
  const { darkTheme } = useSelector((state) => state.theme); // Assuming you have a Redux store with a theme slice

  const handleSubmit = async (e) => {
    e.preventDefault();
    const formData = new FormData();
    formData.append("username", username);
    formData.append("phoneNumber", phoneNumber);
    if (image) formData.append("profilePicture", image);
  
    try {
      setLoading(true);
      const res = await axiosInstance.put("/api/user/update", formData, {
        headers: { "Content-Type": "multipart/form-data" },
      });
      onUpdate(res.data);
      toast.success("Profile updated successfully!");
      dispatch(setUser(res.data.user));
      onClose();
    } catch (error) {
      console.error("Profile update failed", error);
      toast.error("Failed to update profile. Please try again.");
    } finally {
      setLoading(false);
    }
  };
  

  return (
    <div className="fixed inset-0 z-50 bg-black bg-opacity-50 flex justify-center items-center">
      <div className="bg-white dark:bg-dark-secondary text-black dark:text-white p-6 rounded-xl shadow-lg w-full max-w-md">
        <div className="flex justify-between items-center mb-4">
          <h2 className="text-xl font-semibold">Edit Profile</h2>
          <button onClick={onClose}><X className="w-6 h-6" /></button>
        </div>
        <form onSubmit={handleSubmit} className="flex flex-col gap-4">
          <input
            type="text"
            value={username}
            onChange={(e) => setUsername(e.target.value)}
            placeholder="Username"
            className="px-4 py-2 rounded-md border dark:bg-dark-background"
            required
          />
          <input
            type="tel"
            value={phoneNumber}
            onChange={(e) => setPhoneNumber(e.target.value)}
            placeholder="Phone Number"
            className="px-4 py-2 rounded-md border dark:bg-dark-background"
          />
          <input
            type="file"
            onChange={(e) => setImage(e.target.files[0])}
            accept="image/*"
            className="text-sm"
          />
          <input
            type="email"
            value={user.email}
            readOnly
            className="px-4 py-2 rounded-md border bg-gray-200 cursor-not-allowed"
          />
          <button
            type="submit"
            disabled={loading}
            className="bg-blue-600 hover:bg-blue-700 text-white py-2 rounded-md"
          >
            {loading ? "Updating..." : "Update Profile"}
          </button>
        </form>
      </div>
    </div>
  );
}

```

### `frontend\src\components\SideBar\SideBar.jsx`

```javascript
import React, { useState } from "react";
import { Link } from "react-router-dom";
import { HiX } from "react-icons/hi";
import { IoIosLogOut } from "react-icons/io";
import LogoutPopup from "../LogoutPopup/LogoutPopup"; // Import the modal
import { useSelector } from "react-redux";

const SideBar = ({ isOpen, onClose }) => {
  const [showLogoutPopup, setShowLogoutPopup] = useState(false);
  const user = useSelector((state) => state.user.user); // Replace with actual auth logic

  return (
    <>
      {/* Overlay */}
      <div
        className={`fixed inset-0 bg-black/30 backdrop-blur-md transition-opacity duration-300 ${
          isOpen ? "opacity-100 visible" : "opacity-0 invisible"
        } z-40`}
        onClick={onClose}
      ></div>

      {/* Sidebar */}
      <div
        className={`fixed top-0 right-0 h-full w-48 md:w-64 bg-light-secondary/40 dark:bg-dark-secondary/40 backdrop-blur-xl border-l border-light-border dark:border-dark-border shadow-2xl transform ${
          isOpen ? "translate-x-0" : "translate-x-full"
        } transition-transform duration-300 ease-in-out z-50`}
      >
        {/* Close Button */}
        <div className="flex justify-end p-4">
          <button
            onClick={onClose}
            className="text-2xl text-light-primaryText dark:text-dark-primaryText hover:text-light-accent dark:hover:text-dark-accent transition"
          >
            <HiX />
          </button>
        </div>

        {/* Navigation Links */}
        <nav className="flex flex-col gap-4 p-4 text-white dark:text-dark-primaryText">
          <Link
            onClick={onClose}
            to="/password-strength-checker"
            className="text-lg hover:text-light-accent dark:hover:text-dark-accent transition"
          >
            Password Strength Checker
          </Link>
          <Link
            onClick={onClose}
            to="/profile"
            className="text-lg hover:text-light-accent dark:hover:text-dark-accent transition"
          >
            Profile
          </Link>
          <Link
            onClick={onClose}
            to="/shared-data"
            className="text-lg hover:text-light-accent dark:hover:text-dark-accent transition"
          >
            Shared Data
          </Link>
          <Link
            onClick={onClose}
            to="/fake-data"
            className="text-lg hover:text-light-accent dark:hover:text-dark-accent transition"
          >
            Fake Data Generator
          </Link>
          <Link
            onClick={onClose}
            to="/breach-check"
            className="text-lg hover:text-light-accent dark:hover:text-dark-accent transition"
          >
            Breach Monitoring
          </Link>
          <Link
            onClick={onClose}
            to="/privacy-tips"
            className="text-lg hover:text-light-accent dark:hover:text-dark-accent transition"
          >
            Privacy Tips
          </Link>
          <Link
            onClick={onClose}
            to="/vault"
            className="text-lg hover:text-light-accent dark:hover:text-dark-accent transition"
          >
            Data Vault
          </Link>

          {/* Logout Button - Opens Popup */}
          {user ? (
            <button
              onClick={() => setShowLogoutPopup(true)}
              className="flex items-center gap-2 px-4 py-2 text-lg bg-red-500 text-white rounded-md hover:bg-red-600 transition"
            >
              Logout <IoIosLogOut />
            </button>
          ) : null}
        </nav>
      </div>

      {/* Logout Popup */}
      <LogoutPopup
        isOpen={showLogoutPopup}
        onClose={() => setShowLogoutPopup(false)}
        onConfirm={() => {
          console.log("User logged out!"); // Replace with actual logout logic
          setShowLogoutPopup(false);
        }}
      />
    </>
  );
};

export default SideBar;

```

### `frontend\src\components\ThemeButton.jsx`

```javascript
import React from "react";
import { useDispatch, useSelector } from "react-redux";
import { GiBoomerangSun } from "react-icons/gi";
import { RiMoonClearFill } from "react-icons/ri";
import { toggleTheme } from "../app/slices/ThemeSlice";

const ThemeButton = () => {
  const { darkTheme } = useSelector((state) => state.theme);
  const dispatch = useDispatch();

  return (
    <button
      onClick={() => dispatch(toggleTheme())}
      className={`rounded-full transition-all duration-500 transform ${
        darkTheme
          ? "bg-dark-secondary text-dark-primaryText scale-110 rotate-[360deg]"
          : "bg-light-secondary text-light-primaryText scale-100 rotate-0"
      } p-1 lg:p-3 shadow-md hover:scale-300 hover:shadow-lg`}
    >
      {darkTheme ? (
        <RiMoonClearFill className="text-xl text-light-accent transition-all duration-500" />
      ) : (
        <GiBoomerangSun className="text-xl text-dark-accent transition-all duration-500" />
      )}
    </button>
  );
};

export default ThemeButton;

```

### `frontend\src\components\Unauthorized.jsx`

```javascript
import React from "react";
import { Link } from "react-router-dom";
import { useSelector } from "react-redux";

const Unauthorized = () => {
  const { darkTheme } = useSelector((state) => state.theme);

  return (
    <div
      className={`min-h-screen flex flex-col items-center justify-center p-6 ${
        darkTheme
          ? "bg-dark-background text-dark-primaryText"
          : "bg-light-background text-light-primaryText"
      }`}
    >
      <div className="bg-secondary bg-opacity-40 backdrop-blur-md border border-white/20 p-8 rounded-2xl shadow-lg text-center">
        <h1 className="text-3xl font-bold mb-4">403 - Unauthorized</h1>
        <p className="mb-6">You do not have permission to access this page.</p>
        <Link
          to="/"
          className="px-6 py-2 rounded-md bg-blue-500 text-white text-lg hover:bg-blue-600 transition"
        >
          Go Home
        </Link>
      </div>
    </div>
  );
};

export default Unauthorized;

```

### `frontend\src\components\UpdatePasswordModal.jsx`

```javascript
import { useEffect, useState } from "react";
import { X } from "lucide-react";
import { toast } from "react-toastify";
import axiosInstance from "../config/axios/axios";
import { useSelector } from "react-redux";

const UpdatePasswordModal = ({ isOpen, onClose, onSuccess, vaultItem }) => {
  const [title, setTitle] = useState("");
  const [username, setUsername] = useState("");
  const [password, setPassword] = useState("");
  const [loading, setLoading] = useState(false);
  const darkTheme = useSelector((state) => state.theme.darkTheme);

  useEffect(() => {
    if (vaultItem) {
      setTitle(vaultItem.title || "");
      setUsername(vaultItem.username || "");
      setPassword(vaultItem.password || "");
    }
  }, [vaultItem]);

  const handleSubmit = async (e) => {
    e.preventDefault();

    if (!title || !password) {
      toast.error("App name and password are required");
      return;
    }

    setLoading(true);
    try {
      await axiosInstance.put(`/api/vault/update/${vaultItem._id}`, {
        title,
        username,
        password,
      });

      toast.success("Password updated 🔄");
      onSuccess?.();
      onClose?.();
    } catch (err) {
      console.error(err);
      toast.error("Failed to update password");
    } finally {
      setLoading(false);
    }
  };

  if (!isOpen) return null;

  return (
    <div className="fixed inset-0 z-50 flex items-center justify-center bg-black/60 backdrop-blur-sm">
      <div
        className={`relative w-[90%] max-w-md p-6 rounded-2xl shadow-xl border ${
          darkTheme
            ? "bg-dark-background text-dark-primaryText border-dark-hover"
            : "bg-light-background text-light-primaryText border-light-hover"
        }`}
      >
        <button
          onClick={onClose}
          className={`absolute top-3 right-3 transition-colors ${
            darkTheme
              ? "text-dark-secondaryText hover:text-dark-accent"
              : "text-light-secondaryText hover:text-light-accent"
          }`}
        >
          <X size={22} />
        </button>

        <h2 className="text-xl font-bold mb-2">✏️ Update Password</h2>

        <form onSubmit={handleSubmit} className="space-y-4">
          <input
            type="text"
            placeholder="App / Site Name"
            value={title}
            onChange={(e) => setTitle(e.target.value)}
            className={`w-full p-3 rounded-xl outline-none ${
              darkTheme
                ? "bg-dark-secondary text-dark-primaryText placeholder-dark-secondaryText"
                : "bg-light-secondary text-light-primaryText placeholder-light-secondaryText"
            }`}
          />
          <input
            type="text"
            placeholder="Username (optional)"
            value={username}
            onChange={(e) => setUsername(e.target.value)}
            className={`w-full p-3 rounded-xl outline-none ${
              darkTheme
                ? "bg-dark-secondary text-dark-primaryText placeholder-dark-secondaryText"
                : "bg-light-secondary text-light-primaryText placeholder-light-secondaryText"
            }`}
          />
          <input
            type="text"
            placeholder="Password"
            value={password}
            onChange={(e) => setPassword(e.target.value)}
            className={`w-full p-3 rounded-xl outline-none ${
              darkTheme
                ? "bg-dark-secondary text-dark-primaryText placeholder-dark-secondaryText"
                : "bg-light-secondary text-light-primaryText placeholder-light-secondaryText"
            }`}
          />

          <button
            type="submit"
            disabled={loading}
            className={`w-full py-2 rounded-xl font-semibold transition-all ${
              darkTheme
                ? "bg-dark-action hover:bg-dark-hover text-white"
                : "bg-light-action hover:bg-light-hover text-white"
            }`}
          >
            {loading ? "Updating..." : "Update Password"}
          </button>
        </form>
      </div>
    </div>
  );
};

export default UpdatePasswordModal;

```

### `frontend\src\components\VaultUnlock.jsx`

```javascript
// src/components/VaultUnlock.jsx
import { useState } from "react";
import { toast } from "react-toastify";
import * as argon2 from "argon2-browser";

const VaultUnlock = ({ salt, onUnlock }) => {
  const [password, setPassword] = useState("");
  const [loading, setLoading] = useState(false);

  const handleUnlock = async (e) => {
    e.preventDefault();

    if (!password) {
      toast.error("Vault password is required.");
      return;
    }

    try {
      setLoading(true);

      // Derive key using argon2id
      const { hash } = await argon2.hash({
        pass: password,
        salt,
        type: argon2.ArgonType.Argon2id,
        hashLen: 32,
        time: 3,
        mem: 65536,
        parallelism: 1,
      });

      onUnlock(hash, password); // Send key & password to parent
    } catch (err) {
      toast.error("Key derivation failed.");
    } finally {
      setLoading(false);
    }
  };

  return (
    <form
      onSubmit={handleUnlock}
      className="bg-card p-6 rounded-2xl shadow-lg space-y-4"
    >
      <h2 className="text-xl font-semibold text-foreground">Enter Vault Password</h2>
      <p className="text-sm text-muted-foreground">
        This password is used to encrypt/decrypt your Vault data. Don’t forget it.
      </p>
      <input
        type="password"
        placeholder="Vault Password"
        className="w-full p-2 rounded-xl bg-muted text-foreground placeholder:text-muted-foreground"
        value={password}
        onChange={(e) => setPassword(e.target.value)}
      />
      <button
        type="submit"
        disabled={loading}
        className="bg-primary text-primary-foreground px-4 py-2 rounded-xl w-full font-semibold hover:bg-primary/90 transition"
      >
        {loading ? "Unlocking..." : "Unlock Vault"}
      </button>
    </form>
  );
};

export default VaultUnlock;

```

### `frontend\src\config\axios\axios.js`

```javascript
import axios from 'axios';

const token = localStorage.getItem('token');

const axiosInstance = axios.create({
    baseURL: import.meta.env.VITE_API_URL,
    headers: {
        'Content-Type': 'application/json',
        Authorization: token ? `Bearer ${token}` : null,
    },
});

axiosInstance.interceptors.request.use((config) => {
    const token = localStorage.getItem("token"); // Get latest token
    if (token) {
        config.headers.Authorization = `Bearer ${token}`;
    }
    return config;
}, (error) => {
    return Promise.reject(error);
});


export default axiosInstance;
```

### `frontend\src\HOC\Protected.jsx`

```javascript
import React, { useEffect, useState } from "react";
import { toast } from "react-toastify";
import axiosInstance from "../config/axios/axios";
import { useDispatch } from "react-redux";
import { setUser } from "../app/slices/userSlice";
import Unauthorized from "../components/Unauthorized";
import { useNavigate } from "react-router-dom";
import LoadingScreen from "../components/LoadingScreen/LoadingScreen";

const Protected = ({ children }) => {
  const dispatch = useDispatch();
  const navigate = useNavigate();
  const [isAuthorized, setIsAuthorized] = useState(false);
  const [isLoading, setIsLoading] = useState(true);

  useEffect(() => {
    const token = localStorage.getItem("token"); // Get token inside useEffect

    if (!token) {
      toast.error("Unauthorized! Redirecting to login...");
      setTimeout(() => navigate("/"), 500);
      setIsAuthorized(false);
      setIsLoading(false);
      return;
    }

    let isMounted = true; // Prevent state updates after unmount

    axiosInstance
      .get("/api/auth/authme")
      .then((res) => {
        if (isMounted) {
          dispatch(setUser(res.data.user));
          setIsAuthorized(true);
        }
      })
      .catch((err) => {
        if (isMounted) {
          const errorMessage = err.response?.data?.message || "An error occurred. Try logging in again.";
          toast.error(errorMessage, { position: "top-right", autoClose: 3000 });
          setTimeout(() => navigate("/"), 500);
          setIsAuthorized(false);
        }
      })
      .finally(() => {
        if (isMounted) setIsLoading(false);
      });

    return () => {
      isMounted = false; // Cleanup function
    };
  }, [dispatch, navigate]);

  if (isLoading) return <LoadingScreen />; 
  if (!isAuthorized) return <Unauthorized />;

  return children;
};

export default Protected;

```

### `frontend\src\index.css`

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
/* Global Color Palette */
:root {
    --primary-color: #071952;
    --secondary-color: #088395;
    --light-background: #EBF4F6;
    --accent-color: #37B7C3;
  }
  
  /* Header (Primary Color) */
  .header {
    background-color: var(--primary-color);
    color: white;
    padding: 1rem 1.5rem;
  }
  
  .header h1 {
    font-size: 1.25rem;
    font-weight: 600;
  }
  
  /* Primary Button */
  .btn-primary {
    background-color: var(--primary-color);
    color: white;
    padding: 0.5rem 1rem;
    border-radius: 0.5rem;
    transition: all 0.3s ease;
  }
  
  .btn-primary:hover {
    background-color: var(--secondary-color);
  }
  
  /* Secondary Button */
  .btn-secondary {
    background-color: var(--secondary-color);
    color: white;
    padding: 0.5rem 1rem;
    border-radius: 0.5rem;
    transition: all 0.3s ease;
  }
  
  .btn-secondary:hover {
    background-color: var(--primary-color);
  }
  
  /* Light Background Section */
  .section-light {
    background-color: var(--light-background);
    color: var(--primary-color);
    padding: 1.5rem;
    border-radius: 0.5rem;
  }
  
  /* Input Field */
  .input-field {
    background-color: var(--light-background);
    border: 2px solid var(--primary-color);
    color: var(--primary-color);
    padding: 0.5rem 1rem;
    border-radius: 0.5rem;
    outline: none;
    transition: all 0.3s ease;
  }
  
  .input-field:focus {
    border-color: var(--secondary-color);
    box-shadow: 0 0 0 2px var(--secondary-color);
  }
  
  /* Card with Hover Effect */
  .card {
    background-color: var(--accent-color);
    color: var(--primary-color);
    padding: 1.5rem;
    border-radius: 0.5rem;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    transition: all 0.3s ease;
  }
  
  .card:hover {
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
  }
  
  /* Link with Hover Effect */
  .link {
    color: var(--primary-color);
    transition: all 0.3s ease;
  }
  
  .link:hover {
    color: var(--secondary-color);
  }
  
  /* Footer (Light Background) */
  .footer {
    background-color: var(--light-background);
    color: var(--primary-color);
    padding: 1rem 1.5rem;
  }
  
  .footer p {
    font-size: 0.875rem;
  }
  
```

### `frontend\src\main.jsx`

```javascript
import { createRoot } from "react-dom/client";
import "./index.css";
import App from "./App.jsx";
import { BrowserRouter } from "react-router-dom";
import  store  from "./app/Store.js";
import { Provider } from "react-redux";


createRoot(document.getElementById("root")).render(
  <Provider store={store}>
    <BrowserRouter>
      <App />
    </BrowserRouter>
  </Provider>
);

```

### `frontend\src\Routes\AppRoutes.jsx`

```javascript
import React from "react";
import { Route, Routes } from "react-router-dom";
import Home from "../screens/home,/Home";
import Register from "../screens/Register/Register";
import Login from "../screens/Login/Login";
import OTP from "../screens/OTP/OTP";
import Protected from "../HOC/Protected";
import Vault from "../screens/vault/Vault";
import BreachMonitor from "../screens/BreachMonitor/BreachMonitor";
import SharedApps from "../screens/SharedApps/SharedApps";
import ProfilePage from "../screens/profile/ProfilePage";
import VaultPasswordSetup from "../screens/vaultPasswordSetup/vaultPasswordSetup";
import UnlockVault from "../screens/unlockVault/UnlockVault";
import BlogPage from "../screens/BlogPage/BlogPage";
import PasswordBreachCheck from "../screens/PasswordBreachCheck/PasswordBreachCheck";
import Fakedata from "../screens/fakeData/FakeData";

const AppRoutes = () => {
  return (
    <Routes>
      <Route path="/" element={<Home />} />
      <Route path="/login" element={<Login />} />
      <Route path="/register" element={<Register />} />
      <Route path="/otp" element={<OTP />} />
      <Route
        path="/password-strength-checker"
        element={
          <Protected>
              <PasswordBreachCheck/>
          </Protected>
        }
      />
      <Route
        path="/vault"
        element={
          <Protected>
            <Vault />
          </Protected>
        }
      />

      <Route
        path="/fake-data"
        element={
          <Protected>
            <Fakedata />
          </Protected>
        }
      />

      <Route
        path="/breach-check"
        element={
          <Protected>
            <BreachMonitor />
          </Protected>
        }
      />

      <Route
        path="/shared-data"
        element={
          <Protected>
            <SharedApps />
          </Protected>
        }
      />

      <Route
        path="/profile"
        element={
          <Protected>
            <ProfilePage />
          </Protected>
        }
      />

      <Route
        path="/setupVaultPassword"
        element={
          <Protected>
            <VaultPasswordSetup />
          </Protected>
        }
      />

      <Route
        path="/vaultPassword"
        element={
          <Protected>
            <UnlockVault />
          </Protected>
        }
      />


        <Route
          path="/privacy-tips"
          element={
            <Protected>
              <BlogPage/>
            </Protected>
          }
        />

    </Routes>
  );
};

export default AppRoutes;

```

### `frontend\src\screens\BlogPage\BlogPage.jsx`

```javascript
import React, { useEffect, useState } from "react";
import { useSelector } from "react-redux";
import axiosInstance from "../../config/axios/axios";

const BlogPage = () => {
  const [blogs, setBlogs] = useState([]);
  const themeMode = useSelector((state) => state.theme.mode); // 'light' or 'dark'

  useEffect(() => {
    axiosInstance.get("/api/blogs").then((res) => setBlogs(res.data));
  }, []);

  const darkTheme = useSelector((state) => state.theme.darkTheme); // 'light' or 'dark'


  return (
    <div
      className={`p-4 md:p-6 space-y-4 md:space-y-6 min-h-screen transition-all duration-300 ${
        darkTheme ? "bg-dark-background text-dark-primaryText" : "bg-light-background text-light-primaryText"
      }`}
    >
      <h1
        className={`text-2xl md:text-3xl font-semibold mb-4 md:mb-6 ${
          darkTheme ? "text-dark-primaryText" : "text-light-primaryText"
        }`}
      >
        Latest Blogs
      </h1>
      <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4 md:gap-6">
        {blogs.map((blog, idx) => (
          <div
            key={idx}
            className={`shadow-md rounded-lg overflow-hidden transition-all duration-300 flex flex-col ${
              darkTheme
                ? "bg-dark-secondary text-dark-secondaryText"
                : "bg-light-secondary text-light-secondaryText"
            }`}
          >
            <img
              src={blog.image}
              alt={blog.title}
              className="w-full h-48 object-cover flex-shrink-0"
            />
            <div className="p-4 flex flex-col justify-between flex-grow">
              <div>
                <h2
                  className={`text-lg md:text-xl font-bold mb-2 ${
                    darkTheme ? "text-dark-primaryText" : "text-light-primaryText"
                  }`}
                >
                  {blog.title}
                </h2>
                <p className="mb-3 line-clamp-3 md:line-clamp-4 text-sm md:text-base">{blog.content}</p>
              </div>
              <a
                href={blog.source}
                target="_blank"
                rel="noreferrer"
                className={`inline-block text-sm md:text-base font-medium rounded px-3 py-1 transition w-fit ${
                  darkTheme
                    ? "bg-dark-accent text-dark-background hover:bg-dark-hover"
                    : "bg-light-accent text-white hover:bg-light-hover"
                }`}
              >
                Read More
              </a>
            </div>
          </div>
        ))}
      </div>
    </div>
  );
};

export default BlogPage;
```

### `frontend\src\screens\BreachMonitor\BreachMonitor.jsx`

```javascript
import React, { useState } from "react";
import axios from "axios";
import { useSelector } from "react-redux";
import { CheckCircle, AlertTriangle } from "lucide-react";
import Loading from "../../components/Loading";

const BreachMonitor = () => {
  const [email, setEmail] = useState("");
  const [breachData, setBreachData] = useState(null);
  const [loading, setLoading] = useState(false);
  const [error, setError] = useState("");
  const darkTheme = useSelector((state) => state.theme.darkTheme);

  const handleSearch = async () => {
    setLoading(true);
    setError("");
    try {
      const res = await axios.get(
        `https://api.xposedornot.com/v1/breach-analytics?email=${email}`
      );
      setBreachData(res.data);
    } catch (err) {
      setError("Could not fetch breach info");
    } finally {
      setLoading(false);
    }
  };

  const themeClass = darkTheme ? "dark" : "light";

  const renderExposedData = () => {
    return breachData?.BreachMetrics?.xposed_data[0]?.children.map((category, i) => (
      <div key={i} className="mb-3">
        <h4 className="font-semibold text-md">{category.name}</h4>
        <ul className="list-disc list-inside ml-4 text-sm">
          {category.children.map((item, j) => (
            <li key={j}>{item.name.replace("data_", "")}</li>
          ))}
        </ul>
      </div>
    ));
  };

  const renderBreaches = () => {
    const breaches = breachData?.ExposedBreaches?.breaches_details || [];
    return breaches.map((breach, index) => (
      <div
        key={index}
        className="bg-white/10 backdrop-blur-md p-4 sm:p-6 rounded-xl border border-red-500 shadow-lg transition hover:scale-[1.01]"
      >
        <div className="flex items-center gap-2 mb-2 text-red-400 font-semibold text-sm sm:text-base">
          <AlertTriangle className="w-5 h-5" />
          Breach Detected
        </div>
        <img src={breach.logo} alt={breach.breach} className="w-20 h-auto mb-3" />
        <p><strong>📛 Breach:</strong> {breach.breach}</p>
        <p><strong>🧠 Industry:</strong> {breach.industry}</p>
        <p><strong>📅 Year:</strong> {breach.xposed_date}</p>
        <p><strong>🧾 Records:</strong> {breach.xposed_records.toLocaleString()}</p>
        <p><strong>🔐 Exposed:</strong> {breach.xposed_data}</p>
        <p><strong>📖 Details:</strong> {breach.details}</p>
        <a
          href={breach.references}
          target="_blank"
          rel="noreferrer"
          className="text-blue-400 underline text-sm mt-2 inline-block"
        >
          Learn more
        </a>
      </div>
    ));
  };

  return (
    <div
      className={`min-h-screen px-4 sm:px-6 lg:px-16 py-10 bg-${themeClass}-background text-${themeClass}-primaryText transition-all flex flex-col items-center overflow-x-hidden`}
    >
      <h1 className="text-2xl sm:text-3xl lg:text-4xl font-bold mb-8 text-center">
        🔐 Email Breach Monitor
      </h1>
  
      <div className="w-full max-w-xl flex flex-col sm:flex-row gap-4 mb-10">
        <input
          type="email"
          className={`flex-1 px-4 py-2 rounded-lg bg-${themeClass}-secondary text-${themeClass}-primaryText placeholder-${themeClass}-secondaryText focus:outline-none`}
          placeholder="Enter email..."
          value={email}
          onChange={(e) => setEmail(e.target.value)}
        />
        <button
          onClick={handleSearch}
          className={`px-6 py-2 rounded-lg text-white bg-${themeClass}-action hover:bg-${themeClass}-hover transition-all`}
        >
          Search
        </button>
      </div>
  
      {loading && <p className="text-sm flex gap-4"><Loading /> Checking breaches...</p>}
      {error && <p className="text-red-500">{error}</p>}
  
      {breachData && (
        <div className="w-full max-w-4xl space-y-6 overflow-hidden">
          {/* Summary Section */}
          <div className="text-center">
            <h2 className="text-xl font-semibold mb-2">🔍 Summary</h2>
            <p>
              Breach Site:{" "}
              <span className="font-medium">{breachData.BreachesSummary?.site}</span>
            </p>
            <p>
              Overall Risk:{" "}
              <span className="font-medium">
                {breachData.BreachMetrics?.risk[0]?.risk_label} (
                {breachData.BreachMetrics?.risk[0]?.risk_score})
              </span>
            </p>
            <p>
              Weak Passwords:{" "}
              <span className="font-medium">
                {breachData.BreachMetrics?.passwords_strength[0]?.EasyToCrack}
              </span>
            </p>
          </div>
  
          {/* Exposed Data Section */}
          <div>
            <h2 className="text-xl font-semibold mb-2">📂 Exposed Data</h2>
            {renderExposedData()}
          </div>
  
          {/* Breaches Section */}
          <div>
            <h2 className="text-xl font-semibold mb-2">📛 Breaches</h2>
            {renderBreaches()}
          </div>
        </div>
      )}
    </div>
  );
  
};

export default BreachMonitor;

```

### `frontend\src\screens\checkVaultPassword\checkVaultPassword.jsx`

```javascript

```

### `frontend\src\screens\fakeData\FakeData.jsx`

```javascript
import { useEffect, useState } from "react";
import { toast } from "react-toastify";
import axiosInstance from "../../config/axios/axios";
import { X } from "lucide-react";
import { useSelector } from "react-redux";
import axios from "axios";
import debounce from "lodash/debounce";
import DOMPurify from "dompurify";



const Fakedata = () => {
  const [fakeDataList, setFakeDataList] = useState([]);
  const [loading, setLoading] = useState(false);
  const [mailEmail, setMailEmail] = useState(null);
  const [mailToken, setMailToken] = useState(null);
  const [messages, setMessages] = useState([]);
  const [syncing, setSyncing] = useState(false);
  const [activeMessage, setActiveMessage] = useState(null);
  const [isModalOpen, setIsModalOpen] = useState(false);
  

  const darkTheme = useSelector((state) => state.theme.darkTheme);
  const MAILTM_API = "https://api.mail.tm";

  // 📡 Fetch user's fake data
  const fetchFakeData = async () => {
    try {
      const res = await axiosInstance.get("/api/fake-data/all");
      setFakeDataList(res.data.fakedata);
    } catch (err) {
      toast.error("Failed to load fake data");
    }
  };

  // ➕ Generate new fake data
  const generateData = async () => {
    try {
      setLoading(true);
      const res = await axiosInstance.post("/api/fake-data/generate");
      toast.success("Fake data generated ✅");
      setFakeDataList((prev) => [...prev, res.data.data]);
    } catch (err) {
      toast.error(err.response?.data?.errors?.[0] || "Error generating data");
    } finally {
      setLoading(false);
    }
  };

  // 🗑️ Delete fake data
  const deleteData = async (id) => {
    try {
      await axiosInstance.post(`/api/fake-data/delete`, { fakeDataId: id });
      toast.success("Deleted 🗑️");
      setFakeDataList((prev) => prev.filter((item) => item._id !== id));
    } catch {
      toast.error("Failed to delete");
    }
  };

  // 🔐 Create mail.tm account and get token
  const generateMailAccount = async () => {
    setLoading(true);
    setMessages([]);
    setMailEmail(null);
    try {
      const domainRes = await axios.get(`${MAILTM_API}/domains`);
      const domain = domainRes.data["hydra:member"][0].domain;
      const randomUsername = Math.random().toString(36).substring(2, 10);
      const randomEmail = `${randomUsername}@${domain}`;
      const password = `PrivGuard@123`;

      await axios.post(`${MAILTM_API}/accounts`, {
        address: randomEmail,
        password,
      });

      const loginRes = await axios.post(`${MAILTM_API}/token`, {
        address: randomEmail,
        password,
      });

      setMailEmail(randomEmail);
      setMailToken(loginRes.data.token);
      toast.success("Disposable email created 📬");
    } catch (err) {
      console.error("Mail.tm Error:", err.response?.data || err.message);
      toast.error("Failed to create disposable email");
    } finally {
      setLoading(false);
    }
  };

  // 🔄 Debounced message fetcher (manual trigger)
  const fetchMessages = debounce(async () => {
    if (!mailToken) return;
    try {
      setSyncing(true);
      const res = await axios.get(`${MAILTM_API}/messages`, {
        headers: { Authorization: `Bearer ${mailToken}` },
      });
      setMessages(res.data["hydra:member"]);
      console.log(messages);
      toast.success("Inbox synced 📬");
    } catch (err) {
      console.error("Error fetching messages", err);
      toast.error("Failed to sync inbox");
    } finally {
      setSyncing(false);
    }
  }, 2000);

  useEffect(() => {
    fetchFakeData();
  }, []);

  const handleViewMessage = async (id) => {
    try {
      const res = await axios.get(`${MAILTM_API}/messages/${id}`, {
        headers: { Authorization: `Bearer ${mailToken}` },
      });

      setActiveMessage(res.data);
      setIsModalOpen(true);
    } catch (err) {
      console.error("Failed to load full message", err);
      toast.error("Failed to open email");
    }

  };
  

  return (
    <div
      className={`min-h-screen px-4 py-10 ${
        darkTheme
          ? "bg-dark-background text-dark-primaryText"
          : "bg-light-background text-light-primaryText"
      }`}
    >
      <div className="flex justify-between items-center mb-6">
        <h1 className="text-2xl font-bold">🧪 Fake Data Generator</h1>
        <button
          onClick={generateData}
          disabled={loading}
          className={`px-4 py-2 rounded-xl font-semibold transition ${
            darkTheme
              ? "bg-dark-accent hover:bg-dark-hover text-white"
              : "bg-light-accent hover:bg-light-hover text-white"
          }`}
        >
          {loading ? "Generating..." : "Generate Data"}
        </button>
      </div>

      {/* 📫 Disposable Mailbox */}
      <div className="my-10">
        <h2 className="text-xl font-semibold mb-3">📫 Disposable Mailbox</h2>
        {!mailEmail ? (
          <button
            onClick={generateMailAccount}
            className={`px-4 py-2 rounded-xl font-semibold transition ${
              darkTheme
                ? "bg-dark-accent hover:bg-dark-hover text-white"
                : "bg-light-accent hover:bg-light-hover text-white"
            }`}
          >
            Generate Disposable Email
          </button>
        ) : (
          <div className="space-y-2">
            <div className="flex items-center gap-4 mb-3">
              <p className="text-sm">
                Active Email: <strong>{mailEmail}</strong>
              </p>
              <button
                onClick={fetchMessages}
                disabled={syncing}
                className={`text-xs px-3 py-1 rounded-lg transition ${
                  darkTheme
                    ? "bg-dark-accent hover:bg-dark-hover text-white"
                    : "bg-light-accent hover:bg-light-hover text-white"
                }`}
              >
                {syncing ? "Syncing..." : "Sync Inbox 🔄"}
              </button>
            </div>
            <div className="bg-white/10 p-4 rounded-xl shadow-md border max-h-60 overflow-y-auto">
              {messages.length === 0 ? (
                <p className="text-sm text-gray-400">No messages yet...</p>
              ) : (
                messages.map((msg) => (
                  <button
                    onClick={() => handleViewMessage(msg.id)}
                    className="w-full text-left mb-3 border-b border-gray-500 pb-2 hover:bg-white/10 p-2 rounded transition"
                  >
                    <p className="font-bold text-sm text-blue-400 underline underline-offset-2">
                      {msg.subject || "(No Subject)"}
                    </p>
                    <p className="text-xs text-gray-300">
                      From:{" "}
                      <span className="font-medium">{msg.from?.address}</span>
                    </p>
                    <p className="text-xs text-secondaryText">{msg.intro}</p>
                  </button>
                ))
              )}
            </div>
          </div>
        )}
      </div>

      {/* 🔐 Fake Data Cards */}
      <div className="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-6">
        {fakeDataList.map((item) => (
          <div
            key={item._id}
            className={`relative backdrop-blur-lg p-4 rounded-2xl shadow-xl border ${
              darkTheme
                ? "bg-dark-secondary/30 border-dark-hover"
                : "bg-light-secondary/30 border-light-hover"
            }`}
          >
            <span className="absolute top-2 left-[5%] w-2 h-2 rounded-full bg-green-400 shadow-md shadow-green-500 animate-pulse" />
            <button
              onClick={() => deleteData(item._id)}
              className="absolute top-3 right-3 text-red-400 hover:text-red-600 transition"
            >
              <X size={20} />
            </button>
            <h3 className="text-lg font-semibold mb-1">Fake Name : {item.name}</h3>
            <p className="text-sm text-secondaryText">Fake PhoneNo. :{item.phone}</p>
            <p className="text-sm text-secondaryText">Fake Address : {item.address}</p>
            <p className="text-sm text-secondaryText">Fake AadharNo. :{item.aadhar}</p>
          </div>
        ))}
      </div>


      {isModalOpen && activeMessage && (
  <div className="fixed inset-0 bg-black/60 backdrop-blur-sm z-50 flex items-center justify-center">
    <div className={`relative max-w-3xl w-full max-h-[90vh] overflow-y-auto p-6 rounded-xl shadow-lg transition ${
      darkTheme ? "bg-dark-secondary text-dark-primaryText" : "bg-white text-black"
    }`}>
      <button
        onClick={() => setIsModalOpen(false)}
        className="absolute top-4 right-4 text-red-500 hover:text-red-700"
      >
        <X size={24} />
      </button>
      <h2 className="text-xl font-bold mb-2">{activeMessage.subject}</h2>
      <p className="text-sm text-gray-500 mb-4">From: {activeMessage.from?.address}</p>
      <div
        className="prose max-w-none text-sm"
        dangerouslySetInnerHTML={{ __html: DOMPurify.sanitize( activeMessage.html || activeMessage.text || "No content available.")  }}
      />
    </div>
  </div>
)}





    </div>
  );
};

export default Fakedata;

```

### `frontend\src\screens\home,\Home.jsx`

```javascript
import React, { useEffect, useState } from 'react';
import { Link } from 'react-router-dom';
import { useSelector } from 'react-redux';
import { Shield, Eye, Database, AlertTriangle, Lock, FileCheck } from 'lucide-react';
import { motion } from 'framer-motion';

const Home = () => {
  const { darkTheme } = useSelector((state) => state.theme);

  const [stats, setStats] = useState({
    protected: 0,
    fakesGenerated: 0,
    breachesPrevented: 0,
  });

  useEffect(() => {
    const interval = setInterval(() => {
      setStats((prev) => ({
        protected: prev.protected < 156 ? prev.protected + 3 : 156,
        fakesGenerated: prev.fakesGenerated < 1248 ? prev.fakesGenerated + 24 : 1248,
        breachesPrevented: prev.breachesPrevented < 37 ? prev.breachesPrevented + 1 : 37,
      }));
    }, 50);

    return () => clearInterval(interval);
  }, []);

  const featureVariants = {
    hidden: { x: -20, opacity: 0 },
    visible: (i) => ({
      x: 0,
      opacity: 1,
      transition: {
        delay: i * 0.1 + 0.5,
        duration: 0.4,
      },
    }),
  };

  const pulseAnimation = {
    pulse: {
      scale: [1, 1.03, 1],
      transition: {
        duration: 2,
        repeat: Infinity,
        repeatType: "loop",
      },
    },
  };

  return (
    <div className={`min-h-screen py-1 ${darkTheme ? "bg-dark-background text-dark-primaryText" : "bg-light-background text-light-primaryText"}`}>


      {/* Animated Stats & Features Section */}
      <motion.div className="flex flex-col items-center text-center px-4 py-16 md:py-24">
        <motion.div
          className={`p-6 rounded-full mb-6 ${darkTheme ? "bg-dark-secondary" : "bg-light-secondary"}`}
          animate="pulse"
          variants={pulseAnimation}
        >
          <Shield size={64} className={`${darkTheme ? "text-dark-action" : "text-light-action"}`} />
        </motion.div>

        <h1 className="text-4xl sm:text-5xl md:text-6xl font-bold mb-4">
          Data Shield <span className={`${darkTheme ? "text-dark-action" : "text-light-action"}`}>Visualizer</span>
        </h1>
        <p className={`text-lg md:text-xl max-w-2xl mb-8 ${darkTheme ? "text-dark-secondaryText" : "text-light-secondaryText"}`}>
          Take control of your digital privacy. Monitor your data, generate safe alternatives, and stay protected from breaches.
        </p>

        {/* Stats */}
        <div className="grid grid-cols-1 md:grid-cols-3 gap-8 w-full max-w-4xl mb-16">
          <div className={`p-6 rounded-xl ${darkTheme ? "bg-dark-secondary" : "bg-light-secondary"}`}>
            <h3 className="text-xl font-medium mb-2">Apps Protected</h3>
            <p className={`text-3xl font-bold ${darkTheme ? "text-dark-action" : "text-light-action"}`}>{stats.protected}</p>
          </div>
          <div className={`p-6 rounded-xl ${darkTheme ? "bg-dark-secondary" : "bg-light-secondary"}`}>
            <h3 className="text-xl font-medium mb-2">Fakes Generated</h3>
            <p className={`text-3xl font-bold ${darkTheme ? "text-dark-action" : "text-light-action"}`}>{stats.fakesGenerated}</p>
          </div>
          <div className={`p-6 rounded-xl ${darkTheme ? "bg-dark-secondary" : "bg-light-secondary"}`}>
            <h3 className="text-xl font-medium mb-2">Breaches Prevented</h3>
            <p className={`text-3xl font-bold ${darkTheme ? "text-dark-action" : "text-light-action"}`}>{stats.breachesPrevented}</p>
          </div>
        </div>

        {/* Features */}
        <div className="grid grid-cols-1 md:grid-cols-2 gap-8 max-w-6xl w-full">
          {[
            { icon: <Eye size={32} />, title: "Data Visibility", description: "See exactly what personal data is being shared with your apps and services." },
            { icon: <Database size={32} />, title: "Fake Data Generator", description: "Create fake identities and data for services you don't trust with your real information." },
            { icon: <AlertTriangle size={32} />, title: "Breach Monitoring", description: "Get instant alerts when your data appears in known breaches or leaks." },
            { icon: <Lock size={32} />, title: "Privacy Recommendations", description: "Receive personalized advice to enhance your digital privacy footprint." },
            { icon: <FileCheck size={32} />, title: "Compliance Checking", description: "Verify if services comply with privacy regulations like GDPR and CCPA." },
            { icon: <Shield size={32} />, title: "Risk Assessment", description: "Analyze and score the privacy risks of apps before you install them." },
          ].map((feature, i) => (
            <motion.div
              key={i}
              className={`p-6 rounded-xl ${darkTheme ? "bg-dark-background" : "bg-light-background"} hover:shadow-lg transition-all duration-300`}
              custom={i}
              initial="hidden"
              whileInView="visible"
              viewport={{ once: true }}
              variants={featureVariants}
            >
              <div className={`p-3 rounded-full inline-block mb-4 ${darkTheme ? "bg-dark-secondary" : "bg-light-secondary"}`}>
                <div className={`${darkTheme ? "text-dark-action" : "text-light-action"}`}>{feature.icon}</div>
              </div>
              <h3 className="text-xl font-bold mb-2">{feature.title}</h3>
              <p className={`${darkTheme ? "text-dark-secondaryText" : "text-light-secondaryText"}`}>{feature.description}</p>
            </motion.div>
          ))}
        </div>
      </motion.div>
    </div>
  );
};

export default Home;

```

### `frontend\src\screens\Login\Login.jsx`

```javascript
import React, { useState } from "react";
import { useNavigate } from "react-router-dom";
import { useDispatch, useSelector } from "react-redux";
import { toast } from "react-toastify";
import axiosInstance from "../../config/axios/axios";
import { removeUser } from "../../app/slices/userSlice";

const Login = () => {
  const dispatch = useDispatch(); 
  const [formData, setFormData] = useState({ email: "", password: "" });
  const [passwordVisible, setPasswordVisible] = useState(false);
  const { darkTheme } = useSelector((state) => state.theme);
  const [loading, setLoading] = useState(false);
  const navigate = useNavigate();

  const togglePasswordVisibility = () => setPasswordVisible(!passwordVisible);

  const handleChange = (e) => {
    const { name, value } = e.target;
    setFormData({ ...formData, [name]: value });
  };


  const handleLogin = async (e) => {
    e.preventDefault(); // FIX: Prevent default form submission
    setLoading(true);
    console.log(formData)
    try {
      const response = await axiosInstance.post("/api/auth/login", formData, {
        headers: {
          "Content-Type": "application/json", // Ensures proper JSON format
        },
      });
      
      console.log(response.data)
      localStorage.setItem("token", response.data.token); // Save token
      toast.success("Login Successful!");
      dispatch(removeUser(response.data.user));
      navigate("/password-strength-checker"); // Redirect after login
    } catch (error) {
      console.log(error)
      toast.error(error.response?.data?.message || "Login failed");
    } finally {
      setLoading(false);
    }
  };

  return (
    <div
      className={`flex items-center justify-center min-h-screen ${
        darkTheme ? "bg-dark-background text-dark-primaryText" : "bg-light-background text-light-primaryText"
      }`}
    >
      <div
        className={`w-96 p-6 rounded-lg shadow-lg ${
          darkTheme ? "bg-dark-secondary border border-dark-border" : "bg-light-secondary border border-light-border"
        }`}
      >
        <h2 className="text-xl font-bold text-center mb-6">Log In</h2>
        <form onSubmit={handleLogin}> {/* FIX: Use onSubmit */}
          <input
            type="email"
            name="email"
            value={formData.email}
            onChange={handleChange}
            placeholder="Email"
            className="w-full p-2 rounded-md border border-gray-500 focus:outline-none bg-transparent"
          />

          <div className="relative mt-4">
            <input
              type={passwordVisible ? "text" : "password"}
              name="password"
              value={formData.password}
              onChange={handleChange}
              placeholder="Password"
              className="w-full p-2 rounded-md border border-gray-500 focus:outline-none bg-transparent"
            />
            <span
              onClick={togglePasswordVisibility}
              className="absolute right-3 top-2 cursor-pointer text-sm hover:opacity-75 transition"
            >
              {passwordVisible ? "Hide" : "Show"}
            </span>
          </div>

          <button
            type="submit" // FIX: Ensure button submits the form
            className="w-full mt-6 p-2 rounded-md text-white font-semibold bg-blue-500 hover:bg-blue-600 transition"
            disabled={loading}
          >
            {loading ? "Logging in..." : "Sign In"}
          </button>
        </form>

        <p className="mt-4 text-center">
          Don't have an account?{" "}
          <a href="/register" className="underline hover:opacity-75">
            Sign up
          </a>
        </p>
      </div>
    </div>
  );
};

export default Login;

```

### `frontend\src\screens\OTP\OTP.jsx`

```javascript
import { useState, useRef } from "react";
import { FaArrowLeft } from "react-icons/fa";
import { useLocation, useNavigate } from "react-router-dom";
import { toast, ToastContainer } from "react-toastify";
import handelOTPverification from "./utility/handelOTPverification";
import handelResendOTP from "./utility/handelResendOTP";
import { useDispatch, useSelector } from "react-redux";

const OTP = () => {
  const length = 6;
  const [otp, setOtp] = useState(new Array(length).fill(""));
  const inputRefs = useRef([]);
  const navigate = useNavigate();
  const location = useLocation();
  const dispatch = useDispatch();
  const { darkTheme } = useSelector((state) => state.theme);

  const handleChange = (index, e) => {
    const value = e.target.value;
    if (isNaN(value)) return;
    const newOtp = [...otp];
    newOtp[index] = value.substring(value.length - 1);
    setOtp(newOtp);

    if (value && index < length - 1) {
      inputRefs.current[index + 1].focus();
    }
  };

  const handleKeyDown = (index, e) => {
    if (e.key === "Backspace" && !otp[index] && index > 0) {
      inputRefs.current[index - 1].focus();
    }
  };

  return (
    <div
      className={`flex flex-col items-center justify-center h-screen p-4 ${
        darkTheme ? "bg-[#1A102B]" : "bg-[#F2F0FC]"
      }`}
    >
      <h2
        className={`text-2xl font-semibold mb-4 ${
          darkTheme ? "text-[#E3DFFD]" : "text-[#241847]"
        }`}
      >
        Enter OTP
      </h2>
      <div className="flex space-x-2 md:space-x-4">
        {otp.map((data, index) => (
          <input
            key={index}
            type="text"
            value={data}
            maxLength="1"
            onChange={(e) => handleChange(index, e)}
            onKeyDown={(e) => handleKeyDown(index, e)}
            ref={(el) => (inputRefs.current[index] = el)}
            className={`w-12 h-12 md:w-14 md:h-14 text-center text-lg md:text-xl border-2 ${
              darkTheme ? "border-[#874CCC] bg-[#221736] text-[#E3DFFD]" : "border-[#874CCC] bg-[#DCD6F7] text-[#241847]"
            } rounded-lg focus:outline-none focus:border-green-600 focus:ring-2 focus:ring-green-500 transition`}
          />
        ))}
      </div>
      <div>
        <h1
          className={`text-xs font-light mt-4 text-center ${
            darkTheme ? "text-[#E3DFFD]" : "text-[#241847]"
          }`}
        >
          We Sent a OTP to Email and OTP will be valid for{" "}
          <span className="text-orange-400"> 2 min </span> only !!
        </h1>
      </div>
      <button
        onClick={() => {
          handelOTPverification(otp.join(""), location.state.email, navigate, dispatch);
        }}
        className={`mt-6 px-6 py-2 rounded-lg transition ${
          darkTheme ? "bg-[#A66CFF] text-[#E3DFFD]" : "bg-[#A66CFF] text-[#241847]"
        }`}
      >
        Verify OTP
      </button>
      <p className={`mt-4 ${darkTheme ? "text-[#E3DFFD]" : "text-[#241847]"}`}>
        Didn’t receive the OTP?{" "}
        <span
          onClick={() => handelResendOTP(location.state.email)}
          className={`cursor-pointer hover:underline ${
            darkTheme ? "text-[#874CCC] hover:text-[#A66CFF]" : "text-[#874CCC] hover:text-[#A66CFF]"
          }`}
        >
          Resend OTP
        </span>
      </p>
      <ToastContainer
        position="top-right"
        autoClose={5000}
        hideProgressBar={false}
        newestOnTop={false}
        closeOnClick
        rtl={false}
        pauseOnFocusLoss
        draggable
        pauseOnHover
        theme="light"
      />
    </div>
  );
};

export default OTP;
```

### `frontend\src\screens\OTP\utility\handelOTPverification.js`

```javascript
import { toast } from "react-toastify";
import axiosInstance from "../../../config/axios/axios";
import { setUser } from "../../../app/slices/userSlice";


const handelOTPverification = async (otp, email, navigate , dispatch) => {
    

    if(!email) {
        toast.error("Please enter a valid email address ", {
            position: "top-right",
            autoClose: 5000,    
            hideProgressBar: false,
            closeOnClick: false,
            pauseOnHover: true,
            draggable: true,
            progress: undefined,
            theme: "light",
        });
        return;
    }
   
   
    axiosInstance
        .post("/api/otp/verifyotp", { otp, email }) // send otp and email to backend via body
        .then((res) => {
            console.log(res.data);
            if (res.data) {
                localStorage.setItem("token", res.data.token); // store token in local storage
                toast.success(res.data.message, {
                    position: "top-right",
                    autoClose: 3000,
                    hideProgressBar: false,
                    closeOnClick: false,
                    pauseOnHover: true,
                    draggable: true,
                    progress: undefined,
                    theme: "dark",
                });

                console.log(res.data.user);

                dispatch(setUser(res.data.user)); 

                setTimeout(() => {
                    navigate("/password-strength-checker");
                }, 3000);
            }
        })
        .catch((err) => {
            console.log(err.response?.data?.errors?.[0] || "An error occurred");
            toast.error(err.response?.data?.errors?.[0] + " Try Resending OTP to your Email" || "An error occurred", {
                position: "top-right",
                autoClose: 5000,
                hideProgressBar: false,
                closeOnClick: false,
                pauseOnHover: true,
                draggable: true,
                progress: undefined,
                theme: "light",
            });

        });
};


export default handelOTPverification;








```

### `frontend\src\screens\OTP\utility\handelResendOTP.js`

```javascript
import axiosInstance from "../../../config/axios/axios";
import { toast } from "react-toastify";

const handelResendOTP = (email) => {

    axiosInstance
        .post("/api/otp/resendotp", { email: email }) // send email to backend via body
        .then((res) => {
            console.log(res.data);
            toast.success(res.data.message, {
                position: "top-right",
                autoClose: 5000,
                hideProgressBar: false,
                closeOnClick: false,
                pauseOnHover: true,
                draggable: true,
                progress: undefined,
                theme: "dark",
            });


        })
        .catch((err) => {
            console.log(err.response?.data?.errors?.[0] || "An error occurred");
            toast.error(
                err.response?.data?.errors?.[0] +
                " Try Resending OTP to your Email" || "An error occurred",
                {
                    position: "top-right",
                    autoClose: 5000,
                    hideProgressBar: false,
                    closeOnClick: false,
                    pauseOnHover: true,
                    draggable: true,
                    progress: undefined,
                    theme: "light",
                }
            );
        });
};

export default handelResendOTP;
```

### `frontend\src\screens\PasswordBreachCheck\PasswordBreachCheck.jsx`

```javascript
import React, { useState } from 'react';
import axios from 'axios';
import sha1 from 'crypto-js/sha1';
import { useSelector } from 'react-redux';

const PasswordBreachCheck = () => {
  const darkTheme = useSelector((state) => state.theme.darkTheme);
  const [password, setPassword] = useState('');
  const [breachCount, setBreachCount] = useState(null);
  const [loading, setLoading] = useState(false);

  const checkPassword = async () => {
    if (!password) return;

    setLoading(true);
    setBreachCount(null);

    try {
      const hashed = sha1(password).toString().toUpperCase();
      const prefix = hashed.slice(0, 5);
      const suffix = hashed.slice(5);

      const res = await axios.get(`https://api.pwnedpasswords.com/range/${prefix}`);
     

      const lines = res.data.split('\n');
      const match = lines.find(line => line.startsWith(suffix));

      if (match) {
        const count = parseInt(match.split(':')[1]);
        setBreachCount(count);
      } else {
        setBreachCount(0);
      }
    } catch (err) {
      console.error('Error checking password breach:', err);
      setBreachCount(-1);
    }

    setLoading(false);
  };

  return (
    <div className={`min-h-screen w-full flex items-center justify-center px-4 transition-colors duration-300 
      ${darkTheme ? 'bg-dark-background text-dark-primaryText' : 'bg-light-background text-light-primaryText'}
    `}>
      <div className={`w-full max-w-xl p-8 rounded-2xl shadow-2xl transition-all duration-300 
        ${darkTheme ? 'bg-dark-secondary' : 'bg-light-secondary'}
      `}>
        <h1 className="text-3xl font-bold mb-6 text-center">🔐 Password Breach Checker</h1>

        <input
          type="password"
          placeholder="Enter your password..."
          value={password}
          onChange={(e) => setPassword(e.target.value)}
          className={`w-full p-3 rounded-xl border-2 outline-none mb-4 transition 
            ${darkTheme 
              ? 'bg-dark-background text-dark-primaryText border-dark-hover placeholder-dark-secondaryText' 
              : 'bg-light-background text-light-primaryText border-light-hover placeholder-light-secondaryText'}
          `}
        />

        <button
          onClick={checkPassword}
          disabled={loading || !password}
          className={`w-full py-3 rounded-xl font-semibold transition-colors text-lg
            ${darkTheme 
              ? 'bg-dark-action text-dark-background hover:bg-dark-hover' 
              : 'bg-light-action text-white hover:bg-light-hover'}
          `}
        >
          {loading ? 'Checking...' : 'Check Breach'}
        </button>

        {breachCount !== null && (
          <div className={`mt-6 text-xl font-medium text-center
            ${breachCount === -1 
              ? 'text-yellow-500' 
              : breachCount > 0 
                ? 'text-red-500' 
                : 'text-green-600'}
          `}>
            {breachCount === -1
              ? '❌ Error checking breach.'
              : breachCount > 0
                ? `⚠️ This password was found in ${breachCount} breaches.   Try a different one! for better security.`
                : '✅ This password was not found in any known breach.'}
          </div>
        )}
      </div>
    </div>
  );
};

export default PasswordBreachCheck;

```

### `frontend\src\screens\profile\ProfilePage.jsx`

```javascript
import React, { useEffect, useState } from "react";
import { useSelector } from "react-redux";
import {
  BadgeCheck,
  Mail,
  Smartphone,
  MapPin,
  KeyRound,
  ShieldAlert,
} from "lucide-react";
import axiosInstance from "../../config/axios/axios"; // Adjust the import path as necessary
import LoadingScreen from "../../components/LoadingScreen/LoadingScreen";
import ProfileEditModal from "../../components/ProfileEditModal/ProfileEditModal";

export default function ProfilePage() {
  const [user, setUser] = useState(null);
  const [loading, setLoading] = useState(true);
  const [showModal, setShowModal] = useState(false);
  const u = useSelector((state) => state.user.user); // Assuming you have a Redux store with a user slice
  const darkTheme = useSelector((state) => state.theme.darkTheme); // Assuming you have a Redux store with a theme slice
  const handleUpdate = (updatedUser) => setUser(updatedUser);

  useEffect(() => {
    async function fetchuserData() {
      axiosInstance
        .get(`/api/user/${u._id}`)
        .then((res) => setUser(res.data.user))
        .catch((err) => console.log(err))
        .finally(() => setLoading(false));
    }
    fetchuserData();
  }, []);

  return loading ? (
    <LoadingScreen />
  ) : (
    <div
      className={`mx-auto min-h-screen p-4 sm:p-6 md:p-8 lg:p-10 xl:p-12 ${
        darkTheme ? "bg-dark-background text-dark-primaryText" : "bg-light-background text-light-primaryText"
      }`}
    >
      {/* Profile Header */}
      <div
        className={`rounded-xl sm:rounded-2xl shadow-md p-4 sm:p-6 flex flex-col sm:flex-row items-center gap-4 sm:gap-6 ${
          darkTheme ? "bg-dark-secondary" : "bg-light-secondary"
        }`}
      >
        <img
          src={user?.profilePicture}
          alt="Profile"
          className="w-16 h-16 sm:w-20 sm:h-20 rounded-full object-cover border"
        />
        <div className="text-center sm:text-left">
          <h2
            className={`text-xl sm:text-2xl font-bold flex items-center justify-center sm:justify-start gap-2 ${
              darkTheme ? "text-dark-primaryText" : "text-light-primaryText"
            }`}
          >
            {user.username}
            {user.isVerified && <BadgeCheck className="text-blue-500 w-4 h-4 sm:w-5 sm:h-5" />}
          </h2>
          <p
            className={`text-sm ${
              darkTheme ? "text-dark-secondaryText" : "text-light-secondaryText"
            }`}
          >
            {user.email}
          </p>
          <p
            className={`text-sm ${
              darkTheme ? "text-dark-secondaryText" : "text-light-secondaryText"
            }`}
          >
            {user.phoneNumber}
          </p>
        </div>
        <button
          onClick={() => setShowModal(true)}
          className="mt-4 px-4 py-2 bg-blue-500 text-white rounded-md hover:bg-blue-600"
        >
          Edit Profile
        </button>
      </div>

      {/* Shared Apps */}
      <section className="mt-6 sm:mt-8">
        <h3
          className={`text-lg sm:text-xl font-semibold mb-3 sm:mb-4 ${
            darkTheme ? "text-dark-primaryText" : "text-light-primaryText"
          }`}
        >
          Shared Apps
        </h3>
        <div className="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
          {user.sharedData?.map((app) => (
            <div
              key={app._id}
              className={`p-3 sm:p-4 rounded-md sm:rounded-xl shadow-md ${
                darkTheme ? "bg-dark-secondary hover:bg-dark-hover" : "bg-light-secondary hover:bg-light-hover"
              }`}
            >
              <h4
                className={`font-bold text-md sm:text-lg mb-1 sm:mb-2 truncate ${
                  darkTheme ? "text-dark-accent" : "text-light-accent"
                }`}
                title={app.appName}
              >
                {app.appName}
              </h4>
              <div className="flex flex-wrap gap-1 sm:gap-2 text-xs sm:text-sm">
                {Object.entries(app.sharedData).map(([field, shared]) =>
                  shared ? (
                    <span
                      key={field}
                      className={`${
                        darkTheme ? "bg-green-800 text-white" : "bg-green-100 text-green-800"
                      } px-1.5 py-0.5 sm:px-2 sm:py-1 rounded-full flex items-center gap-0.5 sm:gap-1`}
                    >
                      {field === "email" && <Mail className="w-3 h-3 sm:w-4 sm:h-4" />}
                      {field === "phoneNumber" && <Smartphone className="w-3 h-3 sm:w-4 sm:h-4" />}
                      {field === "location" && <MapPin className="w-3 h-3 sm:w-4 sm:h-4" />}
                      {field === "password" && <KeyRound className="w-3 h-3 sm:w-4 sm:h-4" />}
                      {field === "aadhaarNumber" && <ShieldAlert className="w-3 h-3 sm:w-4 sm:h-4" />}
                      {field}
                    </span>
                  ) : null
                )}
              </div>
              <p
                className={`mt-1 sm:mt-2 text-xs sm:text-sm ${
                  darkTheme ? "text-dark-secondaryText" : "text-light-secondaryText"
                }`}
              >
                Accessed on: {new Date(app.accessDate).toLocaleDateString()}
              </p>
            </div>
          ))}
        </div>
      </section>



      {/* Fake Data */}
      <section className="mt-6 sm:mt-8">
        <h3
          className={`text-lg sm:text-xl font-semibold mb-3 sm:mb-4 ${
            darkTheme ? "text-dark-primaryText" : "text-light-primaryText"
          }`}
        >
          Saved Fake Data
        </h3>
        <div className="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
          {user.savedFakeData?.map((fake) => (
            <div
              key={fake._id}
              className={`p-3 sm:p-4 rounded-md sm:rounded-xl shadow-sm ${
                darkTheme ? "bg-dark-secondary" : "bg-light-secondary"
              } ${darkTheme ? "text-dark-primaryText" : "text-light-primaryText"}`}
            >
              <p className="text-sm sm:text-base">
                <strong>Name:</strong> {fake.name}
              </p>
              <p className="text-sm sm:text-base">
                <strong>Email:</strong> {fake.email}
              </p>
              <p className="text-sm sm:text-base">
                <strong>Phone:</strong> {fake.phone}
              </p>
              <p className="text-sm sm:text-base">
                <strong>Address:</strong> {fake.address}, {fake.city}, {fake.state}
              </p>
              <p className="text-sm sm:text-base">
                <strong>Aadhaar:</strong> {fake.aadhar}
              </p>
            </div>
          ))}
        </div>
      </section>


      {showModal && (
        <ProfileEditModal
          user={user}
          onClose={() => setShowModal(false)}
          onUpdate={handleUpdate}
        />
      )}



    </div>
  );
}
```

### `frontend\src\screens\Register\Register componets\PasswordStrength.jsx`

```javascript
import React from "react";
import { AiOutlineCheck } from "react-icons/ai";
import { AiOutlineClose } from "react-icons/ai";


const PasswordCriteria = ({ password }) => {
    const criteria = [
        { label: "At least 6 characters", met: password.length >= 6 },
        { label: "Contains uppercase letter", met: /[A-Z]/.test(password) },
        { label: "Contains lowercase letter", met: /[a-z]/.test(password) },
        { label: "Contains a number", met: /\d/.test(password) },
        { label: "Contains special character", met: /[^A-Za-z0-9]/.test(password) },
    ];

    return (
        <div className="mt-2 space-y-1">
            {criteria.map((item, index) => (
                <div key={index} className="flex items-center text-xs transition duration-200 ease-in-out">
                    {item.met ? (
                        <span className="text-green-500 mr-2"><AiOutlineCheck /></span> // Right icon
                    ) : (
                        <span className="text-red-500 mr-2"><AiOutlineClose/></span> // Wrong icon
                    )}
                    <span className={item.met ? "text-green-500 transition duration-200 ease-in-out" : "text-gray-400"}>
                        {item.label}
                    </span>
                </div>
            ))}
        </div>
    );
};

const PasswordStrength = ({ password }) => {
    const getStrength = (pass) => {
        let strength = 0;

        if (pass.length >= 6) strength++;
        if (/[A-Z]/.test(pass) && /[a-z]/.test(pass)) strength++;
        if (/\d/.test(pass)) strength++;
        if (/[^A-Za-z0-9]/.test(pass)) strength++;

        return strength;
    };

    const strength = getStrength(password);

    const getStrengthText = () => {
        switch (strength) {
            case 0:
                return "Very Weak";
            case 1:
                return "Weak";
            case 2:
                return "Moderate";
            case 3:
                return "Strong";
            default:
                return "Very Strong";
        }
    };

    return (
        <div className="mt-1">
            <div>
                <span className="text-xs text-gray-400">Password Strength: </span>
                <span className="text-xs text-gray-400">{getStrengthText()}</span>
            </div>

            <div className="h-1 w-full bg-gray-200 rounded-full mt-1 transition duration-200 ">
                <div
                    className={`h-full rounded-full ${
                        strength === 0
                            ? "bg-red-500"
                            : strength === 1
                            ? "bg-yellow-500"
                            : strength === 2
                            ? "bg-blue-500"
                            : "bg-green-500"
                    }`}
                    style={{ width: `${(strength / 4) * 100}%` }}
                ></div>
            </div>

            <PasswordCriteria password={password} />
        </div>
    );
};

export default PasswordStrength;

```

### `frontend\src\screens\Register\Register.jsx`

```javascript
import React, { useState } from "react";
import PasswordStrength from "./Register componets/PasswordStrength";
import { useNavigate } from "react-router-dom";
import { FaArrowLeft } from "react-icons/fa";
import axiosInstance from "../../config/axios/axios";
import { ToastContainer, toast } from "react-toastify";
import Loading from "../../components/Loading";
import { useSelector } from "react-redux";

const Register = () => {
  const [errors, setErrors] = useState([]);
  const [passwordVisible, setPasswordVisible] = useState(false);
  const [formData, setFormData] = useState({
    firstName: "",
    lastName: "",
    email: "",
    phoneNumber: "",
    password: "",
    agree: false,
  });
  const [isLoading, setIsLoading] = useState(false);
  const navigate = useNavigate();
  const { darkTheme } = useSelector((state) => state.theme);

  const togglePasswordVisibility = () => setPasswordVisible(!passwordVisible);

  const handleChange = (e) => {
    const { name, value, type, checked } = e.target;
    setFormData({
      ...formData,
      [name]: type === "checkbox" ? checked : value,
    });
  };

  const handelRegisterUser = async (e) => {
    setErrors([]);
    setIsLoading(true);
    try {
      e.preventDefault();
      const { firstName, lastName, email, password, phoneNumber } = formData;
      if (!firstName || !lastName || !email || !password || !phoneNumber) {
        setErrors(["All fields are required"]);
        toast.error("All fields are required", {
          position: "top-right",
          autoClose: 5000,
          hideProgressBar: false,
          closeOnClick: false,
          pauseOnHover: true,
          draggable: true,
          progress: undefined,
          theme: "light",
        });
        setIsLoading(false);
        return;
      }
      if (!formData.agree) {
        setErrors(["You must agree to the terms and conditions"]);
        toast.error(errors[0], {
          position: "top-right",
          autoClose: 5000,
          hideProgressBar: false,
          closeOnClick: false,
          pauseOnHover: true,
          draggable: true,
          progress: undefined,
          theme: "light",
        });
        setIsLoading(false);
        return;
      }

      const response = await axiosInstance.post("api/auth/register", formData);

      if (response.status === 201) {
        localStorage.setItem("token", response.data.token);
        toast.success("User registered successfully \n Now Verify the Email !!", {
          position: "top-right",
          autoClose: 5000,
          hideProgressBar: false,
          closeOnClick: false,
          pauseOnHover: true,
          draggable: true,
          progress: undefined,
          theme: "light",
        });
        setTimeout(() => {
          navigate("/otp", { state: { email: formData.email } });
        }, 1500);
      }
      setIsLoading(false);
    } catch (error) {
      const errorMessage =
        error.response?.data?.errors.join(", ") || "An error occurred";
      setErrors([errorMessage]);

      toast.error(errors[0], {
        position: "top-right",
        autoClose: 5000,
        hideProgressBar: false,
        closeOnClick: false,
        pauseOnHover: true,
        draggable: true,
        progress: undefined,
        theme: "light",
      });
      setIsLoading(false);
    }
  };

  return (
    <div
      className={`flex p-4 items-center justify-center min-h-screen relative ${
        darkTheme ? "bg-[#1A102B]" : "bg-[#F2F0FC]"
      }`}
    >


      <div
        className={`w-96 p-3 rounded-lg ${
          darkTheme ? "bg-[#221736]" : "bg-[#DCD6F7]"
        }`}
      >
        <h2 className={`text-xl font-bold mb-4 ${darkTheme ? "text-[#E3DFFD]" : "text-[#241847]"}`}>
          Sign Up
        </h2>
        <form className=""> 
          <div className="grid grid-cols-2 gap-2">
            <input
              type="text"
              name="firstName"
              value={formData.firstName}
              onChange={handleChange}
              placeholder="First Name"
              className={`w-full p-2 rounded-full border ${
                darkTheme ? "border-[#874CCC] text-[#E3DFFD]" : "border-[#874CCC] text-[#241847]"
              } bg-transparent`}
            />
            <input
              type="text"
              name="lastName"
              value={formData.lastName}
              onChange={handleChange}
              placeholder="Last Name"
              className={`w-full p-2 rounded-full border ${
                darkTheme ? "border-[#874CCC] text-[#E3DFFD]" : "border-[#874CCC] text-[#241847]"
              } bg-transparent`}
            />
          </div>
          <input
            type="email"
            name="email"
            value={formData.email}
            onChange={handleChange}
            placeholder="Email"
            className={`w-full mt-3 p-2 rounded-full border ${
              darkTheme ? "border-[#874CCC] text-[#E3DFFD]" : "border-[#874CCC] text-[#241847]"
            } bg-transparent`}
          />
          <input
            type="text"
            name="phoneNumber"
            value={formData.phoneNumber}
            onChange={handleChange}
            placeholder="Phone Number"
            className={`w-full mt-3 p-2 rounded-full border ${
              darkTheme ? "border-[#874CCC] text-[#E3DFFD]" : "border-[#874CCC] text-[#241847]"
            } bg-transparent`}
          />
          <div className="relative mt-3">
            <input
              type={passwordVisible ? "text" : "password"}
              name="password"
              value={formData.password}
              onChange={handleChange}
              placeholder="Password"
              className={`w-full p-2 rounded-full border ${
                darkTheme ? "border-[#874CCC] text-[#E3DFFD]" : "border-[#874CCC] text-[#241847]"
              } bg-transparent`}
            />
            <span
              onClick={togglePasswordVisibility}
              className={`absolute right-3 top-2 cursor-pointer ${darkTheme ? "text-[#874CCC]" : "text-[#874CCC]"}`}
            >
              {passwordVisible ? "Hide" : "Show"}
            </span>
          </div>

          <PasswordStrength password={formData.password} />

          <div className="flex items-center mt-3">
            <input
              type="checkbox"
              id="agree"
              name="agree"
              checked={formData.agree}
              onChange={handleChange}
              className="mr-2"
            />
            <label htmlFor="agree" className={darkTheme ? "text-[#E3DFFD]" : "text-[#241847]"}>
              I Agree with <span className={darkTheme ? "text-[#874CCC]" : "text-[#874CCC]"}>privacy</span> and{" "}
              <span className={darkTheme ? "text-[#874CCC]" : "text-[#874CCC]"}>policy</span>
            </label>
          </div>
          <button
            onClick={(e) => {
              handelRegisterUser(e);
            }}
            className={`w-full mt-4 p-2 rounded-full ${
              darkTheme ? "bg-[#A66CFF] text-[#E3DFFD]" : "bg-[#A66CFF] text-[#241847]"
            }`}
          >
            {isLoading ? <Loading /> : "Sign Up"}
          </button>
          <ToastContainer />
        </form>
        <p className={`mt-4 text-center ${darkTheme ? "text-[#E3DFFD]" : "text-[#241847]"}`}>
          Already have an account?{" "}
          <a href="/login" className={darkTheme ? "text-[#874CCC]" : "text-[#874CCC]"}>
            Sign in
          </a>
        </p>
      </div>
    </div>
  );
};

export default Register;
```

### `frontend\src\screens\SharedApps\SharedApps.jsx`

```javascript
import React, { useEffect, useState } from "react";
import axiosInstance from "../../config/axios/axios";
import { motion } from "framer-motion";
import { useSelector, useDispatch } from "react-redux";
import {
  setSharedAppsData,
  addSharedApp,
  removeSharedApp,
  updateSharedAppLocal,
} from "../../app/slices/sharedAppsSlice";

const SharedApps = () => {
  const { darkTheme } = useSelector((state) => state.theme);

  const sharedApps = useSelector((state) => state.sharedApps.sharedApps);
  const dispatch = useDispatch();
  const [loading, setLoading] = useState(true);
  const [error, setError] = useState(null);
  const [editingApp, setEditingApp] = useState(null);
  const [updatedData, setUpdatedData] = useState({});
  const [showModal, setShowModal] = useState(false);
  const [newAppData, setNewAppData] = useState({
    appName: "",
    accessDate: "",
    sharedData: {
      email: false,
      password: false,
      phoneNumber: false,
      location: false,
      aadhaarNumber: false,
    },
  });
  const [showCreateModal, setShowCreateModal] = useState(false);
  const DATA_WEIGHTS = {
    email: 10,
    password: 25,
    phoneNumber: 15,
    location: 20,
    aadhaarNumber: 30,
  };

  const calculateRiskScore = (sharedData) => {
    let score = 0;
    for (const [key, value] of Object.entries(sharedData)) {
      if (value && DATA_WEIGHTS[key]) {
        score += DATA_WEIGHTS[key];
      }
    }
    return score; // max is 100
  };

  

  const handleNewToggle = (field) => {
    setNewAppData((prev) => ({
      ...prev,
      sharedData: {
        ...prev.sharedData,
        [field]: !prev.sharedData[field],
      },
    }));
  };

  const createSharedApp = async () => {
    try {
      const res = await axiosInstance.post("/api/sharedApps", {
        appName: newAppData.appName,
        accessDate: newAppData.accessDate,
        sharedData: newAppData.sharedData,
      });
      dispatch(addSharedApp(res.data));
      setShowCreateModal(false);
      setNewAppData({
        appName: "",
        accessDate: "",
        sharedData: {
          email: false,
          password: false,
          phoneNumber: false,
          location: false,
          aadhaarNumber: false,
        },
      });
    } catch (err) {
      console.error("Create failed:", err);
    }
  };

  useEffect(() => {
    fetchSharedApps();
  }, []);

  const fetchSharedApps = async () => {
    try {
      const token = localStorage.getItem("token");
      const res = await axiosInstance.get("/api/sharedApps", {
        headers: {
          Authorization: `Bearer ${token}`,
        },
      });
      dispatch(setSharedAppsData(res.data));
    } catch (err) {
      setError("Failed to load shared apps");
    } finally {
      setLoading(false);
    }
  };

  const deleteApp = async (id) => {
    try {
      const token = localStorage.getItem("token");
      await axiosInstance.delete(`/api/sharedApps/${id}`);
      dispatch(removeSharedApp(id));
    } catch (err) {
      console.error("Delete failed:", err);
    }
  };

  const openEditModal = (app) => {
    setEditingApp(app);
    setUpdatedData(app.sharedData);
    setShowModal(true);
  };

  const handleToggle = (field) => {
    setUpdatedData((prev) => ({
      ...prev,
      [field]: !prev[field],
    }));
  };

  const updateSharedApp = async () => {
    try {
      const token = localStorage.getItem("token");
      const res = await axiosInstance.put(`/api/sharedApps/${editingApp._id}`, {
        sharedData: updatedData,
      });
      dispatch(
        updateSharedAppLocal({ ...editingApp, sharedData: updatedData })
      );
      setShowModal(false);
    } catch (err) {
      console.error("Update failed:", err);
    }
  };

  return (
    <div
      className={`min-h-screen px-4 py-10 ${
        darkTheme
          ? "bg-dark-background text-dark-primaryText"
          : "bg-light-background text-light-primaryText"
      }`}
    >
      <h1 className="text-3xl font-bold text-center mb-8">Shared Apps</h1>

      {loading && <p className="text-center">Loading...</p>}
      {error && <p className="text-center text-red-500">{error}</p>}

      <div className="flex justify-end mb-6">
        <button
          onClick={() => setShowCreateModal(true)}
          className="bg-green-600 text-white px-4 py-2 rounded hover:bg-green-700 transition"
        >
          + New App
        </button>
      </div>

      <div className="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-6">
        {sharedApps.map((app) => (
          <motion.div
            key={app._id}
            initial={{ opacity: 0, y: 20 }}
            animate={{ opacity: 1, y: 0 }}
            transition={{ duration: 0.5 }}
            className={`rounded-2xl p-4 shadow-lg hover:shadow-xl transition-all ${
              darkTheme
                ? "bg-dark-secondary text-dark-secondaryText hover:bg-dark-hover"
                : "bg-light-secondary text-light-secondaryText hover:bg-light-hover"
            }`}
          >
            <h2
              className={`text-xl font-semibold mb-2 ${
                darkTheme ? "text-dark-accent" : "text-light-accent"
              }`}
            >
              {app.appName}
            </h2>
            <p className="mt-3 font-medium">
              Data Risk Score:{"  "}
              <span
                className={
                  calculateRiskScore(app.sharedData) >= 70
                    ? "text-red-500"
                    : calculateRiskScore(app.sharedData) >= 40
                    ? "text-yellow-500"
                    : "text-green-500"
                }
              >
                {calculateRiskScore(app.sharedData)} / 100
              </span>
            </p>

            <div className="text-sm space-y-1">
              {Object.entries(app.sharedData).map(([key, value]) => (
                <p key={key}>
                  {key}:{" "}
                  {value ? (
                    <span className="text-green-500">✅ Shared</span>
                  ) : (
                    <span className="text-red-500">❌ Not Shared</span>
                  )}
                </p>
              ))}
              <p className="text-xs mt-2">
                Accessed: {new Date(app.accessDate).toLocaleDateString()}
              </p>
              {app.lastAccessed && (
                <p className="text-xs">
                  Last Accessed:{" "}
                  {new Date(app.lastAccessed).toLocaleDateString()}
                </p>
              )}
            </div>
            <div className="mt-4 flex gap-2">
              <button
                onClick={() => openEditModal(app)}
                className={`px-3 py-1 rounded transition ${
                  darkTheme
                    ? "bg-dark-action text-white hover:bg-dark-hover"
                    : "bg-light-action text-light-primaryText hover:bg-light-hover"
                }`}
              >
                Edit
              </button>
              <button
                onClick={() => deleteApp(app._id)}
                className="bg-red-600 text-white px-3 py-1 rounded hover:bg-red-800 transition"
              >
                Delete
              </button>
            </div>
          </motion.div>
        ))}
      </div>

      {/* Modal for Creating Shared App */}
      {showCreateModal && (
        <div
          className={`fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50 ${
            darkTheme ? "bg-dark-background" : "bg-light-background"
          }`}
        >
          <motion.div
            initial={{ scale: 0.8, opacity: 0 }}
            animate={{ scale: 1, opacity: 1 }}
            className={`rounded-xl p-6 w-full max-w-md shadow-lg ${
              darkTheme
                ? "bg-dark-secondary text-dark-primaryText"
                : "bg-light-secondary text-light-primaryText"
            }`}
          >
            <h2 className="text-xl font-bold mb-4">Create Shared App</h2>
            <input
              type="text"
              placeholder="App Name"
              value={newAppData.appName}
              onChange={(e) =>
                setNewAppData({ ...newAppData, appName: e.target.value })
              }
              className={`w-full mb-3 px-3 py-2 rounded ${
                darkTheme
                  ? "bg-dark-input border border-gray-700 text-black"
                  : "bg-light-input border border-gray-300 text-black"
              }`}
            />
            <input
              type="date"
              value={newAppData.accessDate}
              onChange={(e) =>
                setNewAppData({ ...newAppData, accessDate: e.target.value })
              }
              className={`w-full mb-4 px-3 py-2 rounded ${
                darkTheme
                  ? "bg-dark-input border border-gray-700 text-white"
                  : "bg-light-input border border-gray-300 text-black"
              }`}
            />
            <div className="space-y-2">
              {Object.entries(newAppData.sharedData).map(([key, value]) => (
                <div key={key} className="flex items-center justify-between">
                  <span>{key}</span>
                  <input
                    type="checkbox"
                    checked={value}
                    onChange={() => handleNewToggle(key)}
                    className="h-4 w-4"
                  />
                </div>
              ))}
            </div>
            <div className="mt-6 flex justify-end gap-2">
              <button
                onClick={() => setShowCreateModal(false)}
                className="px-4 py-1 rounded bg-gray-600 hover:bg-gray-800 text-white"
              >
                Cancel
              </button>
              <button
                onClick={createSharedApp}
                className="px-4 py-1 rounded bg-green-600 hover:bg-green-700 text-white"
              >
                Create
              </button>
            </div>
          </motion.div>
        </div>
      )}

      {/* Modal for Editing Shared App */}
      {showModal && editingApp && (
        <div
          className={`fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50 ${
            darkTheme ? "bg-dark-background" : "bg-light-background"
          }`}
        >
          <motion.div
            initial={{ scale: 0.8, opacity: 0 }}
            animate={{ scale: 1, opacity: 1 }}
            className={`rounded-xl p-6 w-full max-w-md shadow-lg ${
              darkTheme
                ? "bg-dark-secondary text-dark-primaryText"
                : "bg-light-secondary text-light-primaryText"
            }`}
          >
            <h2 className="text-xl font-bold mb-4">
              Edit Shared Data - {editingApp.appName}
            </h2>
            <div className="space-y-2">
              {Object.entries(updatedData).map(([key, value]) => (
                <div key={key} className="flex items-center justify-between">
                  <span>{key}</span>
                  <input
                    type="checkbox"
                    checked={value}
                    onChange={() => handleToggle(key)}
                    className="h-4 w-4"
                  />
                </div>
              ))}
            </div>
            <div className="mt-6 flex justify-end gap-2">
              <button
                onClick={() => setShowModal(false)}
                className="px-4 py-1 rounded bg-gray-600 hover:bg-gray-800 text-white"
              >
                Cancel
              </button>
              <button
                onClick={updateSharedApp}
                className={`px-4 py-1 rounded transition ${
                  darkTheme
                    ? "bg-dark-action hover:bg-dark-hover text-white"
                    : "bg-light-action hover:bg-light-hover text-light-primaryText"
                }`}
              >
                Save
              </button>
            </div>
          </motion.div>
        </div>
      )}
    </div>
  );
};

export default SharedApps;

```

### `frontend\src\screens\unlockVault\UnlockVault.jsx`

```javascript
import React, { useState } from 'react';
import { useSelector, useDispatch } from 'react-redux';
import { setVaultUnlocked } from '../../app/slices/vaultSlice'; // Import your action
import { toast } from 'react-toastify';
import { useNavigate } from 'react-router-dom';
import axiosInstance from '../../config/axios/axios';

const UnlockVault = () => {
  const darkTheme = useSelector((state) => state.theme.darkTheme);
  const dispatch = useDispatch();  // Initialize dispatch
  const [password, setPassword] = useState('');
  const [loading, setLoading] = useState(false);
  const navigate = useNavigate();

  const handleUnlock = async (e) => {
    e.preventDefault();
    setLoading(true);

    try {
      const res = await axiosInstance.post('http://localhost:3000/api/vault/openvault', { password });
      toast.success(res.data.message || 'Vault unlocked!');

      // Dispatch the action to update the vault status in Redux
      dispatch(setVaultUnlocked(true));

      navigate('/vault');  // Navigate to the vault after unlocking
    } catch (err) {
      toast.error(err.response?.data?.message || 'Incorrect password');
    } finally {
      setLoading(false);
    }
  };

  return (
    <div className={`min-h-screen flex items-center justify-center px-4 ${darkTheme ? 'bg-dark-background text-dark-primaryText' : 'bg-light-background text-light-primaryText'}`}>
      <div className={`max-w-md w-full p-6 rounded-xl shadow-md ${darkTheme ? 'bg-dark-secondary' : 'bg-light-secondary'}`}>
        <h2 className="text-2xl font-bold mb-4">Unlock Vault</h2>
        <p className={`text-sm mb-4 ${darkTheme ? 'text-dark-secondaryText' : 'text-light-secondaryText'}`}>
          Enter your vault password to unlock your stored data.
        </p>

        <form onSubmit={handleUnlock} className="space-y-4">
          <div>
            <label htmlFor="password" className="block text-sm font-medium mb-1">
              Vault Password
            </label>
            <input
              type="password"
              id="password"
              value={password}
              onChange={(e) => setPassword(e.target.value)}
              required
              className={`w-full px-3 py-2 rounded-lg border focus:outline-none ${
                darkTheme
                  ? 'bg-dark-background border-gray-700 text-white'
                  : 'bg-white border-gray-300 text-black'
              }`}
            />
          </div>

          <button
            type="submit"
            disabled={loading}
            className={`w-full py-2 rounded-lg font-semibold transition ${
              loading
                ? 'opacity-50 cursor-not-allowed'
                : `${darkTheme ? 'bg-dark-action hover:bg-dark-hover' : 'bg-light-action hover:bg-light-hover'}`
            }`}
          >
            {loading ? 'Unlocking...' : 'Unlock Vault'}
          </button>
        </form>
      </div>
    </div>
  );
};

export default UnlockVault;

```

### `frontend\src\screens\UserInfo\UserInfo.jsx`

```javascript
import React from "react";

const UserInfo = () => {
  return (
    <div className="flex flex-col items-center justify-center h-screen bg-[#071952] text-[#EBF4F6] p-4">
      <h2 className="text-3xl font-semibold mb-6">User Information</h2>
      <div className="bg-[#EBF4F6] text-[#071952] p-6 rounded-xl shadow-lg w-full max-w-md">
        <label className="block mb-2 font-medium">Name</label>
        <input
          type="text"
          className="w-full p-2 mb-4 border-2 border-[#088395] rounded-lg focus:outline-none focus:border-[#37B7C3]"
          value="John Doe"
          readOnly
        />
        <label className="block mb-2 font-medium">Email</label>
        <input
          type="email"
          className="w-full p-2 mb-4 border-2 border-[#088395] rounded-lg focus:outline-none focus:border-[#37B7C3]"
          value="johndoe@example.com"
          readOnly
        />
        <button className="w-full p-2 bg-[#071952] text-white rounded-lg hover:bg-[#088395] transition">
          Edit Profile
        </button>
      </div>
      <button className="mt-6 px-6 py-2 bg-red-600 text-white rounded-lg hover:bg-red-700 transition">
        Log Out
      </button>
    </div>
  );
};

export default UserInfo;

```

### `frontend\src\screens\vault\Vault.jsx`

```javascript
import { useEffect, useState } from "react";
import { useNavigate } from 'react-router-dom';
import { useSelector, useDispatch } from "react-redux";
import axiosInstance from "../../config/axios/axios";
import { resetVault, setVaultUnlocked } from "../../app/slices/vaultSlice"; 
import { toast } from "react-toastify";
import { IoMdAdd } from "react-icons/io";
import AddPasswordModal from "../../components/AddPasswordModal";
import DeleteConfirmModal from "../../components/DeleteConfirmModal";
import UpdatePasswordModal from "../../components/UpdatePasswordModal";
import { Copy, Eye, EyeIcon, EyeOff, EyeOffIcon, Trash2 } from "lucide-react";

const Vault = () => {
  const darkTheme = useSelector((state) => state.theme.darkTheme);
  const dispatch = useDispatch();
  const navigate = useNavigate();
  const [vaultItems, setVaultItems] = useState([]);
  const [visibleIndex, setVisibleIndex] = useState(null);
  const [showAddModal, setShowAddModal] = useState(false);
  const [showDeleteModal, setShowDeleteModal] = useState(false);
  const [itemToDelete, setItemToDelete] = useState(null);
  const [showEditModal, setShowEditModal] = useState(false);
  const [selectedItem, setSelectedItem] = useState(null);

  const vaultUnlocked = useSelector((state) => state.vault.unlocked);

  useEffect(() => {
    const checkVaultStatus = async () => {
      try {
        const res = await axiosInstance.get(
          "http://localhost:3000/api/vault/isInitialized"
        );
        const user = res.data;
        dispatch(setVaultUnlocked(user.isInitialized));

        if (!user.isInitialized) {
          navigate("/setupVaultPassword");  // Redirect to setup password page if vault is not initialized
        } else if (!vaultUnlocked) {
          navigate("/vaultPassword");  // Navigate to the password entry page if vault is unlocked
        }
      } catch (err) {
        console.log("Error checking vault status:", err);
        toast.error("Could not check vault status. Try again.");
      }
    };

    checkVaultStatus();

    // Reset vault state when the component unmounts
    return () => {
      dispatch(resetVault());
    };
  }, [dispatch, navigate, vaultUnlocked]);

  useEffect(() => {
    if (vaultUnlocked) {
      const fetchVaultItems = async () => {
        try {
          const res = await axiosInstance.get("/api/vault/getall");
          setVaultItems(res.data); 
        } catch (err) {
          console.error(err);
          toast.error("Failed to load vault items");
        }
      };

      fetchVaultItems();
    }
  }, [vaultUnlocked]);

  const handleDeleteClick = (itemId) => {
    setItemToDelete(itemId);
    setShowDeleteModal(true);
  };

  const confirmDelete = async () => {
    try {
      await axiosInstance.delete(`/api/vault/delete/${itemToDelete}`);
      setVaultItems((prev) => prev.filter((item) => item._id !== itemToDelete));
      toast.success("Deleted successfully");
    } catch (err) {
      toast.error("Failed to delete");
    } finally {
      setShowDeleteModal(false);
      setItemToDelete(null);
    }
  };

  const toggleVisibility = (index) => {
    setVisibleIndex(index === visibleIndex ? null : index);
  };

  const handleCopy = (password) => {
    navigator.clipboard.writeText(password);
    toast.success("Password copied to clipboard!");
  };

  return (
<div
  className={`min-h-screen px-4 py-10 ${
    darkTheme ? "bg-dark-background text-dark-primaryText" : "bg-light-background text-light-primaryText"
  }`}
>
  <div className="max-w-7xl mx-auto w-full space-y-6">
    <div className="text-center space-y-2">
      <h1 className="text-3xl font-bold">🔐 Vault Access Granted</h1>
      <p className={`text-sm ${darkTheme ? "text-dark-secondaryText" : "text-light-secondaryText"}`}>
        Welcome to your secured Vault. Manage your passwords safely.
      </p>

      <button
        onClick={() => setShowAddModal(true)}
        className={`mt-4 px-4 py-2 rounded-xl font-semibold transition-all duration-200 flex items-center gap-2 mx-auto ${
          darkTheme ? "bg-dark-accent text-white hover:bg-dark-hover" : "bg-light-accent text-white hover:bg-light-hover"
        }`}
      >
        <IoMdAdd size={20} /> Add Password
      </button>
    </div>

    {/* Vault Cards */}
    <div className="grid grid-cols-[repeat(auto-fit,minmax(280px,1fr))] gap-6">
      {vaultItems.map((item, index) => (
        <div
          key={index}
          className={`p-5 rounded-2xl shadow-lg transition-all duration-200 border ${
            darkTheme
              ? "bg-dark-secondary text-dark-primaryText border-dark-border hover:shadow-dark-hover"
              : "bg-light-secondary text-light-primaryText border-light-border hover:shadow-lg"
          }`}
        >
          <div className="mb-2">
            <h3 className="font-semibold text-lg truncate">{item.title}</h3>
            <p className="font-mono text-base break-all">
              {visibleIndex === index ? item.password : "••••••••••••"}
            </p>
          </div>

          <div className="flex justify-end items-center gap-2 mt-3">
            <button
              onClick={() => toggleVisibility(index)}
              className="p-2 rounded-md hover:bg-gray-200 dark:hover:bg-gray-700 transition"
              title="Toggle visibility"
            >
              {visibleIndex === index ? <EyeOffIcon size={18} /> : <EyeIcon size={18} />}
            </button>

            <button
              onClick={() => handleCopy(item.password)}
              className="p-2 rounded-md hover:bg-gray-200 dark:hover:bg-gray-700 transition"
              title="Copy password"
            >
              <Copy size={18} />
            </button>

            <button
              onClick={() => handleDeleteClick(item._id)}
              className="p-2 rounded-md hover:bg-red-100 dark:hover:bg-red-900 text-red-500 transition"
              title="Delete"
            >
              <Trash2 size={18} />
            </button>

            <button
              onClick={() => {
                setSelectedItem(item);
                setShowEditModal(true);
              }}
              className="p-2 rounded-md hover:bg-blue-100 dark:hover:bg-blue-900 text-blue-500 transition"
              title="Edit"
            >
              Edit
            </button>
          </div>
        </div>
      ))}
    </div>
  </div>

  {/* Modals */}
  {showAddModal && (
    <AddPasswordModal
      isOpen={showAddModal}
      onClose={() => setShowAddModal(false)}
      onSuccess={(newItem) => {
        setVaultItems((prev) => [...prev, newItem]);
        toast.success("Password added successfully!");
      }}
    />
  )}

  <DeleteConfirmModal
    isOpen={showDeleteModal}
    onConfirm={confirmDelete}
    onCancel={() => {
      setShowDeleteModal(false);
      setItemToDelete(null);
    }}
  />

  <UpdatePasswordModal
    isOpen={showEditModal}
    vaultItem={selectedItem}
    onClose={() => {
      setShowEditModal(false);
      setSelectedItem(null);
    }}
    onSuccess={async () => {
      const res = await axiosInstance.get("/api/vault/getall");
      setVaultItems(res.data);
    }}
  />
</div>

  );
};

export default Vault;

```

### `frontend\src\screens\vaultPasswordSetup\vaultPasswordSetup.jsx`

```javascript
import React, { useState } from 'react';
import { useSelector } from 'react-redux';
import { toast } from 'react-toastify';
import axiosInstance from '../../config/axios/axios';
import { useNavigate } from 'react-router-dom';

const VaultPasswordSetup = () => {
  const darkTheme = useSelector((state) => state.theme.darkTheme);
  const [password, setPassword] = useState('');
  const [created, setCreated] = useState(false);
  const navigate = useNavigate();

  const handleSubmit = async (e) => {
    e.preventDefault();

    try {
      await axiosInstance.post('http://localhost:3000/api/vault/createvaultPassword', { password });
      setCreated(true);
      toast.success('Vault password created successfully 🎉');
      navigate("/vault")
    } catch (err) {
      console.error(err);
      toast.error('Failed to create vault password. Try again.');
    }
  };

  return (
    <div className={`min-h-screen flex items-center justify-center px-4 ${darkTheme ? 'bg-dark-background text-dark-primaryText' : 'bg-light-background text-light-primaryText'}`}>
      <div className={`max-w-md w-full p-6 rounded-xl shadow-md ${darkTheme ? 'bg-dark-secondary' : 'bg-light-secondary'}`}>
        <h2 className="text-2xl font-bold mb-4">Vault Password Setup</h2>
        <p className={`text-sm mb-4 ${darkTheme ? 'text-dark-secondaryText' : 'text-light-secondaryText'}`}>
          You can only create your vault password once. Please remember it.
        </p>

        <form onSubmit={handleSubmit} className="space-y-4">
          <div>
            <label htmlFor="password" className="block text-sm font-medium mb-1">
              Create Vault Password
            </label>
            <input
              type="password"
              id="password"
              value={password}
              onChange={(e) => setPassword(e.target.value)}
              disabled={created}
              required
              className={`w-full px-3 py-2 rounded-lg border focus:outline-none ${
                darkTheme
                  ? 'bg-dark-background border-gray-700 text-white'
                  : 'bg-white border-gray-300 text-black'
              }`}
            />
          </div>

          <button
            type="submit"
            disabled={created}
            className={`w-full py-2 rounded-lg font-semibold transition ${
              created
                ? 'cursor-not-allowed opacity-50'
                : `${darkTheme ? 'bg-dark-action hover:bg-dark-hover' : 'bg-light-action hover:bg-light-hover'}`
            }`}
          >
            Create Vault Password
          </button>
        </form>
      </div>
    </div>
  );
};

export default VaultPasswordSetup;

```

### `frontend\tailwind.config.js`

```javascript
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {
      colors: {
        dark: {
          background: '#1A102B',
          secondary: '#221736',
          primaryText: '#E3DFFD',
          secondaryText: '#A08DCC',
          accent: '#874CCC',
          action: '#A66CFF',
          hover: '#603F8B',
        },
        light: {
          background: '#F2F0FC',
          secondary: '#DCD6F7',
          primaryText: '#241847',
          secondaryText: '#5A4B8A',
          accent: '#874CCC',
          action: '#A66CFF',
          hover: '#C8B6E2',
        },
      },
    },
  },
  plugins: [],
}
```

### `frontend\vite.config.js`

```javascript
import { defineConfig } from 'vite'
import react from '@vitejs/plugin-react'

// https://vite.dev/config/
export default defineConfig({
  plugins: [react()],
})

```

### `generateMdFromProject.js`

```javascript
const fs = require('fs');
const path = require('path');

// Excluded folders and files
const EXCLUDE = ['node_modules', '.git', '.env', '.DS_Store'];

function isExcluded(fileOrDirName) {
  return EXCLUDE.includes(fileOrDirName);
}

function getLanguageFromExtension(filename) {
  const ext = path.extname(filename).toLowerCase();
  const extMap = {
    '.js': 'javascript',
    '.ts': 'typescript',
    '.jsx': 'javascript',
    '.tsx': 'typescript',
    '.json': 'json',
    '.html': 'html',
    '.css': 'css',
    '.md': 'markdown',
    '.sh': 'bash',
    '.py': 'python',
  };
  return extMap[ext] || '';
}

function generateMarkdownFromDir(dir, mdLines = []) {
  const entries = fs.readdirSync(dir, { withFileTypes: true });

  for (const entry of entries) {
    if (isExcluded(entry.name)) continue;

    const fullPath = path.join(dir, entry.name);

    if (entry.isDirectory()) {
      generateMarkdownFromDir(fullPath, mdLines);
    } else {
      const content = fs.readFileSync(fullPath, 'utf8');
      const language = getLanguageFromExtension(entry.name);
      const relativePath = path.relative(process.cwd(), fullPath);
      mdLines.push(`### \`${relativePath}\`\n`);
      mdLines.push(`\`\`\`${language}\n${content}\n\`\`\`\n`);
    }
  }

  return mdLines;
}

// Entry point
const projectDir = process.cwd(); // Or provide a specific path
const markdownLines = generateMarkdownFromDir(projectDir);
fs.writeFileSync('project_code.md', markdownLines.join('\n'));

console.log('✅ Markdown file generated: project_code.md');

```

```
