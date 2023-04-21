# SMTP-Generator
Generator finds vulnerable SMTP servers all over internet using c# and provides you with login details

[![CI](https://github.com/rubysec/bundler-audit/actions/workflows/ruby.yml/badge.svg)](https://github.com/rubysec/bundler-audit/actions/workflows/ruby.yml)
[![Code Climate](https://codeclimate.com/github/rubysec/bundler-audit.svg)](https://codeclimate.com/github/rubysec/bundler-audit)
[![Gem Version](https://badge.fury.io/rb/bundler-audit.svg)](https://badge.fury.io/rb/bundler-audit)

* [Homepage](https://github.com/rubysec/bundler-audit#readme)
* [Issues](https://github.com/rubysec/bundler-audit/issues)
* [Documentation](http://rubydoc.info/gems/bundler-audit/frames)

## Description

Patch-level verification for [bundler].

## Features

* Checks for vulnerable versions 
* Try to exploit
* Provide plain text login details
* Removes WhiteList,BlackList on server.
* Noob friendly

## Synopsis

Audit a project's `Gemfile.lock`:

    $ bundle-audit
    Name: actionpack
    Version: 3.2.10
    Advisory: OSVDB-91452
    Criticality: Medium
    URL: http://www.osvdb.org/show/osvdb/91452
    Title: XSS vulnerability in sanitize_css in Action Pack
    Solution: upgrade to ~> 2.3.18, ~> 3.1.12, >= 3.2.13

    Name: actionpack
    Version: 3.2.10
    Advisory: OSVDB-91454
    Criticality: Medium
    URL: http://osvdb.org/show/osvdb/91454
    Title: XSS Vulnerability in the `sanitize` helper of Ruby on Rails
    Solution: upgrade to ~> 2.3.18, ~> 3.1.12, >= 3.2.13

    Name: actionpack
    Version: 3.2.10
    Advisory: OSVDB-89026
    Criticality: High
    URL: http://osvdb.org/show/osvdb/89026
    Title: Ruby on Rails params_parser.rb Action Pack Type Casting Parameter Parsing Remote Code Execution
    Solution: upgrade to ~> 2.3.15, ~> 3.0.19, ~> 3.1.10, >= 3.2.11

    Name: activerecord
    Version: 3.2.10
    Advisory: OSVDB-91453
    Criticality: High
    URL: http://osvdb.org/show/osvdb/91453
    Title: Symbol DoS vulnerability in Active Record
    Solution: upgrade to ~> 2.3.18, ~> 3.1.12, >= 3.2.13

    Name: activerecord
    Version: 3.2.10
    Advisory: OSVDB-90072
    Criticality: Medium
    URL: http://direct.osvdb.org/show/osvdb/90072
    Title: Ruby on Rails Active Record attr_protected Method Bypass
    Solution: upgrade to ~> 2.3.17, ~> 3.1.11, >= 3.2.12

    Name: activerecord
    Version: 3.2.10
    Advisory: OSVDB-89025
    Criticality: High
    URL: http://osvdb.org/show/osvdb/89025
    Title: Ruby on Rails Active Record JSON Parameter Parsing Query Bypass
    Solution: upgrade to ~> 2.3.16, ~> 3.0.19, ~> 3.1.10, >= 3.2.11

    Name: activesupport
    Version: 3.2.10
    Advisory: OSVDB-91451
    Criticality: High
    URL: http://www.osvdb.org/show/osvdb/91451
    Title: XML Parsing Vulnerability affecting JRuby users
    Solution: upgrade to ~> 3.1.12, >= 3.2.13

    Unpatched versions found!
