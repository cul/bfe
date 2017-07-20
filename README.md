# Bibframe Editor
This repo contains a local installation of `bfe.` The version of `bfe` that is used in this repository can be found at https://github.com/lcnetdev/bfe/tree/e15091bab4c30f075a032111795a7d515d4ed527

## Repository Setup
This the site content is at `/public.` Most of the files at the root of the directory are related to our Capistrano deploy of this site.

`/public` - contains all the js/css/html files necessary for the site
`/source` - contains the original source code of the codebase
`/lib` - set up to eventually include capistrano tasks, if necessary
`/config/*` - Capistrano configuration
`/Capfile` - list all the Capistrano requirements
`/Gemfile*` - Gemfile and Gemfile.lock for use with Bundler

## Description of `bfe` from README
`bfe` is a standalone Editor for the Library of Congress's [Bibliographic Framework
(BIBFRAME) Initiative][bfi].  It can be used more generically as an editor for RDF data.
`bfe` uses [BIBFRAME Profiles][profilespec] to render an HTML/UI input form; it is
capable of integrating 'lookup' services, which query data from external Web APIs;
and implementers can define the input and extract the output.
