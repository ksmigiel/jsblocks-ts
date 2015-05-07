# jsblocks-ts
TypeScript definitions for [jsblocks](http://jsblocks.com/) framework.

If you want to use dynamic properties, instead of:

```
blocks.observable.formatter = () => {
  // ...
};
```
use different syntax:

```
blocks.observable['formatter'] = () => {
  // ...
};
```