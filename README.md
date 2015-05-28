
####Black box test of Bundler's Gemfile.lock..####

..for the scenario:
```
         b''
        /
  a'   b' -> bb
 /    /
a -> b -> c
```

*Horizonal arrow:* dependency expressed in gemspec.
*Vertical arrow:* dependency not expressed in gemspec, but expressed in Gemfile.

**a's Gemfile.lock**

```b'``` does not appear there (and thus neither do b'' nor bb)

**b's Gemfile.lock**

```b''``` does not appear there
