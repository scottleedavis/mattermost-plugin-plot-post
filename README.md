# Mattermost Plugin Ascii Plot
![CircleCI branch](https://img.shields.io/circleci/project/github/scottleedavis/mattermost-plugin-ascii-plot/master.svg)   [![codecov](https://codecov.io/gh/scottleedavis/mattermost-plugin-ascii-plot/branch/master/graph/badge.svg)](https://codecov.io/gh/scottleedavis/mattermost-plugin-ascii-plot)  [![Releases](https://img.shields.io/github/release/scottleedavis/mattermost-plugin-ascii-plot.svg)](https://github.com/scottleedavis/mattermost-plugin-ascii-plot/releases/latest)

![img](asciiplot-example.gif)

Usage (start a message in mattermost with `asciiplot `, following by a comma seperated list of numbers (floats))
```bash
asciiplot 3, 4, 9, 6, 2, 4, 5, 8, 5, 10, 2, 7, 2, 5, 6
```
Build
```
make
```

This will produce a single plugin file (with support for multiple architectures) for upload to your Mattermost server:

```
dist/com.github.scottleedavis.mattermost-plugin-ascii-post.tar.gz
```
