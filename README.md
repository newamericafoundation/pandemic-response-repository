# New America Pandemic Response Repository
[![CC BY 4.0][cc-by-shield]][cc-by]

[New America](https://www.newamerica.org/) is maintaining a running list of all government open source projects responding to the novel Coronavirus.

The open source projects catalogued in the Pandemic Response Repository are powering more efficient and effective public sector responses to the coronavirus pandemic. Many governments are struggling to find the right solutions and to share technology and content they’ve developed with others in need. The solutions listed here are reusable, easily shared among agencies, municipalities and countries, and can be adapted to local needs. The repository will be updated daily based on research by our team and submissions from around the world. We have not undertaken an independent code review of each solution.

The Pandemic Response Repository is the first phase of a more comprehensive Open Source Framework researched and developed by New America to strengthen and modernize government institutions. Across the public sector, private sector, and civil society, there is growing momentum to create open source, digital public goods that can deliver broad benefits for society and be easily modified to meet the needs of different communities. This work is intended to help build that movement. The Pandemic Response Repository is a joint project of the Digital Impact and Governance Initiative (DIGI) and Public Interest Technology (PIT) teams at New America.

### Reading the Projects online

You’re presently looking at the Pandemic Response Repository GitHub (code) repository. Please [visit the main page](https://newamericafoundation.github.io/pandemic-response-repository/) to view the project list online.

### Contributing to Pandemic Response Repository
If you would like to suggest a new project be added to the collection, [please use this Google form](https://docs.google.com/forms/d/e/1FAIpQLSfQNld7gWcEc8D8tLwyVqUKePMUmZUUKeH41Fx8RXyjQtjWOQ/viewform?usp=sf_link). If you have general questions about the project, send us an email at [DIGI@newamerica.org](mailto:DIGI@newamerica.org). For more information on the contributing to the source code to the Pandemic Response Repository, see [our source code repository for this website](https://github.com/newamericafoundation/pandemic-response-repository/).

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
