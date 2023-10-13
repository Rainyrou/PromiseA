# Handwrite Promises/A+

Refer to this link:

https://github.com/promises-aplus/promises-tests

Configure `package.json`  

```json
{
    "devDependencies": {
        "promises-aplus-tests": "^2.1.2"
    },
    "scripts": {
        "test": "promises-aplus-tests myPromise"
    }
}
```

and Run:

```bash
npm run test
```

You can test whether your handwritten promise conforms to the standard.
