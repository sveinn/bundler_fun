
**Black box test of Bundler's Gemfile.lock for the following scenario**

```
         b''
        /
  a'   b' -> bb
 /    /
a -> b
```

Horizonal arrow: dependency expressed in gemspec.

Vertical arrow: dependency not expressed in gemspec, but expressed in Gemfile.

a's Gemfile.lock
----------------
```b'``` does not appear there

b's Gemfile.lock
----------------
```b''``` does not appear there
