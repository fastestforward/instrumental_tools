# Instrumental Tools

A collection of tools for use with Instrumental ([www.instrumental.com](http://www.instrumentalapp.com/))

## instrument_server

Use to collect various monitoring statistics of a server. Execute with:

```sh
instrument_server -k <INSTRUMENTAL_API_KEY>
```

Mac OS note: Due to a bug in Ruby, instrument_server can occasionally deadlock ([bug report](http://bugs.ruby-lang.org/issues/5811)).

## instrumental

Output text graphs of the different metrics in your project.

See all options with: `instrumental --help`

## gitstrumental

Collect statistics on commit counts in a given git repo.  Execute in the repo directory with:

```sh
gitstrumental [INSTRUMENTAL_API_KEY]
```
