# Web Platform Incubator Community Group

This repository is being used for work in the W3C Web Platform Incubator Community Group, governed by the [W3C Community License
Agreement (CLA)](http://www.w3.org/community/about/process/cla/). To make substantive contributions,
you must join the CG.

If you are not the sole contributor to a contribution (pull request), please identify all
contributors in the pull request comment.

To add a contributor (other than yourself, that's automatic), mark them one per line as follows:

```
+@github_username
```

If you added a contributor by mistake, you can remove them in a comment with:

```
-@github_username
```

If you are making a pull request on behalf of someone else but you had no part in designing the
feature, you can remove yourself with the above syntax.

# Style guide to contributors

- the spec uses [ReSpec](https://www.w3.org/respec/)
- the spec is tidied using [HTML5 Tidy](https://github.com/w3c/tidy-html5). For
  instructions on running HTML5 tidy, see below.
- put comments in front of sections, for better readability with
  syntax coloring editors.

# Running HTML5 Tidy

Please make sure you have HTML5 tidy installed, instead of
the the one that ships with \*nix systems. You can comfirm this by running:

```bash
tidy --version  #HTML Tidy for HTML5 (experimental) for ...
```

Once you have confirmed (make sure you have committed your changes before
running tidy, as the changes are destructive ... in a good way:)):

```bash
tidy -config tidyconfig.txt -o index.html index.html
```
