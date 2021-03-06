# Islandora Web ARChive Solution Pack

## Build Status

[![Build Status](https://travis-ci.org/Islandora/islandora_solution_pack_web_archive.png?branch=7.x)](https://travis-ci.org/Islandora/islandora_solution_pack_web_archive)

## Introduction

Web Archive Solution Pack for Islandora.

Adds all required Fedora objects to allow users to ingest and retrieve web archives through the Islandora interface.

## Requirements

This module requires the following modules/libraries:

* [Islandora](https://github.com/islandora/islandora)
* [Tuque](https://github.com/islandora/tuque)
* [warctools](https://github.com/internetarchive/warctools)

## Installation

Install as usual, see [this](https://drupal.org/documentation/install/modules-themes/modules-7) for further information.

## Configuration

Set the paths for `warcindex` and `warcfilter` in Administration » Islandora » Web ARChive Collection (admin/islandora/web_archive).

[![Configuration](http://i.imgur.com/tP7djFl.png)](http://i.imgur.com/tP7djFl.png)

## Troubleshooting

Having problems or solved a problem? Check out the Islandora google groups for a solution.

* [Islandora Group](https://groups.google.com/forum/?hl=en&fromgroups#!forum/islandora)
* [Islandora Dev Group](https://groups.google.com/forum/?hl=en&fromgroups#!forum/islandora-dev)

## FAQ

Solr indexing:

If you are using Solr 4+, the WARC_FILTERED datastream will automatically be indexed via Apache Tika. You will need to add `ds.WARC_FILTERED^1` to the Query fields form in Adminstration » Islandora » Solr Index » Solr Settings (admin/islandora/search/islandora_solr/settings).

## Maintainers

[Nick Ruest](https://github.com/ruebot)

## License

[GPLv3](http://www.gnu.org/licenses/gpl-3.0.txt)
