## Clearbit Demo

Let’s play with the enrichment feature of the [Clearbit API](https://clearbit.com/docs#enrichment-api)!

Clone the app and run it with:

```sh
yarn
webpack-dev-server
```

### Hints:

- [Sign up on Clearbit](https://dashboard.clearbit.com/signup) to get an API key (you can use a [temporary email](https://temp-mail.org) for that)
- Check how authenticathion works for this specific API, and remember you can pass HTTP Headers to `fetch`:

```js
fetch(url, {
  headers: {
    'User-Agent': 'Mozilla/5.0 (Windows NT 5.1; rv:15.0) Gecko/20100101 Firefox/15.0.1',
  },
  // ...
})
```

- Once you are done with your version, you can check another possible solution [here](https://github.com/gabrielecanepa/clearbit/blob/solution/lib/clearbit.js)
