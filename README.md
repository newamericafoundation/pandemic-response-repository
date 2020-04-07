# New America Pandemic Response Repository
[![CC BY 4.0][cc-by-shield]][cc-by]

[New America](https://www.newamerica.org/) is maintaining a running list of all government open source projects responding to the novel Coronavirus.

Governments across the globe are responding to the COVID-19 pandemic by creating critical resources for their people. Many of these governments are providing their work as open source repositories, and other governments have used that work as a starting point for their response efforts. However, the discovery of these projects is difficult – open source repositories are being shared via closed channels like Slack groups or email lists, or through social networks like Twitter. Our research into open source software for government use has shown that discovery of existing OSS tools is one of the larger barriers to using more OSS in the government context.

To facilitate in the response to the COVID-19 pandemic, we are managing this centralized resource hub where all of these projects will be catalogued for governments in need to discover. This is a joint project between the Digital Impact and Governance Initiative (DIGI) and Public Interest Technology (PIT) teams at New America.

### Reading the Projects online

You’re presently looking at the Pandemic Response Repository GitHub (code) repository. Please [visit the main page](https://newamericafoundation.github.io/pandemic-response-repository/) to view the project list online.

### Contributing to Pandemic Response Repository
For more information on contributing to Pandemic Response Repository, see [CONTRIBUTING.md](https://github.com/newamericafoundation/pandemic-response-repository/blob/master/CONTRIBUTING.md). If you would like to suggest a new project be added to the collection, [please use this Google form](). If you have general questions about the project, send us an email at [DIGI@newamerica.org](mailto:DIGI@newamerica.org).

### Running the Pandemic Response Repository website on your local machine

You will need [Ruby](https://www.ruby-lang.org) ( > version 2.1.5 ). You may consider using a Ruby version manager such as [rbenv](https://github.com/sstephenson/rbenv) or [rvm](https://rvm.io/) to help ensure that Ruby version upgrades don’t mean all your [gems](https://rubygems.org/) will need to be rebuilt.

On OS X, you can use [Homebrew](http://brew.sh/) to install Ruby in `/usr/local/bin`, which may require you to update your `$PATH` environment variable:

```shell
$ brew update
$ brew install ruby
```

To serve the site locally, using `projects` as the name of your new repository:
Run each of the following steps to get the site up and running.

```shell
$ git clone git@github.com:newamericafoundation/pandemic-response-repository
$ cd projects
$ bundle install
$ bundle exec jekyll serve
```

You should be able to see the site at: `http://localhost:4000/`

### License

This work is licensed under a [Creative Commons Attribution 4.0 International
License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
