# brownm09.github.io

This is my Github-hosted personal site--powered by Jekyll--which you can find at [The Perfect Compromise](https://theperfectcompromise.com). It is based on [Anjuan Simmons](https://github.com/anjuan/anjuan.github.io)'s website, which is a detached fork of [Steven V. Miller's site](http://svmiller.com/), based on his [Github template](https://github.com/svmiller/steve-ngvb-jekyll-template).

<!-- Potential search engine optimization hack text:  -->

## Run and Test Locally

To run and test this website locally:

1. Powershell: `winget install RubyInstallerTeam.RubyWithDevKit.3.2`
1. Git-Bash: `PATH=$PATH:/c/Ruby32-x64/bin`
1. Verify Ruby installation: `ruby -v`
1. Install Jekyll: `gem install jekyll bundler`
1. Verify Jeykll installation: `jekyll -v`
1. Install dependencies: `bundle install`
1. (If necessary; update/delete `Gemfile.lock` and repeat.)
1. Serve Jekyll site locally: `bundle exec jekyll serve --watch --config _config-dev.yml --trace --livereload`

If the `serve` command fails to discover `_includes` that are _right there_, it's probably a symlink issue (hard links/junctions may not work, either).
