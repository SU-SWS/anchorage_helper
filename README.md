#[Anchorage Helper](https://github.com/SU-SWS/anchorage_helper)
##### Version: 7.x-1.0-alpha3

Maintainer: [jbickar](https://github.com/jbickar)

[Changelog.txt](CHANGELOG.txt)

Installation
---

Install this module like any other module. [See Drupal Documentation](https://drupal.org/documentation/install/modules-themes/modules-7)

Configuration
---

There are several "hidden features":

1. The default "from" address is "anchorage-support@lists.stanford.edu". Use `drush vset anchorage_helper_ses_from email@example.com` to use a different "from" address.
2. To debug, use `drush vset anchorage_helper_debug TRUE`. That will give you two array variables whenever an email is sent, `anchorage_helper_pre` and `anchorage_helper_post`. Those represent the `$message` variable before and after the implementation of `hook_mail_alter()`.



Contribution / Collaboration
---

You are welcome to contribute functionality, bug fixes, or documentation to this module. If you would like to suggest a fix or new functionality you may add a new issue to the GitHub issue queue or you may fork this repository and submit a pull request. For more help please see [GitHub's article on fork, branch, and pull requests](https://help.github.com/articles/using-pull-requests)
