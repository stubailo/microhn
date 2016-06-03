# microhn

A microscopic Hacker News client built on top of [GraphQLHub](https://www.graphqlhub.com/).

You don't need any frameworks to build an app with GraphQL. Just a `script` tag and some browser APIs!

Note: not all browsers are currently supported due to use of `fetch` and template literals. Those were just the fastest way for me to get this done, so I welcome PRs to make this even simpler!

[Read Hacker News now!](http://stubailo.github.io/microhn/)

### Browser support

Because this doesn't use any frameworks or transpilers, we don't get any browser compatibility for free.

- [x] Chrome
- [x] Firefox
- [ ] Safari (doesn't support arrow functions)

Unknown (please submit a PR with status update):

- [ ] Edge
- [ ] IE
- [ ] Opera
