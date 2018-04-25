[![Build Status](https://travis-ci.org/jkramer/home.svg?branch=master)](https://travis-ci.org/jkramer/home)

NAME
====

Proc::Editor - Start a text editor

SYNOPSIS
========

    use Proc::Editor;

    my $text = edit('original text');
    say "Edited text: {$text.trim}";

DESCRIPTION
===========

Proc::Editor runs a text editor and returns the edited text.

AUTHOR
======

Jonas Kramer <jkramer@mark17.net>

COPYRIGHT AND LICENSE
=====================

Copyright 2018 Jonas Kramer

This library is free software; you can redistribute it and/or modify it under the Artistic License 2.0.

