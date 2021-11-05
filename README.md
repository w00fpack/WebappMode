# Overview
[![screenshot](https://github.com/w00fpack/WebappMode/blob/main/screenshots/main.jpg)](https://raw.github.com/wiki/w00fpack/WebappMode/blob/main/screenshots/main.jpg)

Released files are compressed Mozilla browser profiles that have tabs, menu bar and other UI interfaces hidden. In this way, you can run your specific browser with your HTML content and have it look like a native application.

Mozilla based browsers do not support the -app argument as Chrome browsers do.  hence this hack is necessary.  In the past, the term "app" referred to using Mozilla browsers to run in XUL app mode.  This is different than Chrome's app mode.

## Requirements

A Mozilla based browser

# Installation

Assuming you have Palemoon installed

* download the Palemoon profile in compressed form
* uncompress the release.  The folder /usr/share/appmode/Palemoon will be created.


# Quickstart

To run your HTML content in "app" mode, use a line similar to the following

/opt/palemoon/palemoon --profile /usr/share/appmode/Palemoon file:///webpage.html

# Limitations

This release is focused on running on Linux, hence the path under /usr/share.  This is done to make the app be installed in a universal location easily referenced by any of your webapps.

# License

This add-on is CC0 [licensed](https://github.com/w00fpack/WebappMode/LICENSE).  When applicable, this license is superceded by the originating author's licensing.

# Contributing

To submit code changes, please open pull requests against the [GitHub repository](https://github.com/w00fpack/WebappMode/). Patches submitted in issues, email, or elsewhere will likely be ignored. Here's some general guidelines when submitting PRs:

 * In your pull request, please:
   * Describe the changes, why they were necessary, etc
   * Describe how the changes affect existing behaviour
   * Describe how you tested and validated your changes
   * Include any relevant screenshots/evidence demonstrating that the changes work and have been tested
