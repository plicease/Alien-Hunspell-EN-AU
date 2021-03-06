# Alien::Hunspell::EN::AU [![Build Status](https://secure.travis-ci.org/plicease/Alien-Hunspell-EN-AU.png)](http://travis-ci.org/plicease/Alien-Hunspell-EN-AU)

Australian English wordlist for Hunspell

# SYNOPSIS

    use Alien::Hunspell::EN::AU;
    use Text::Hunspell; # or Text::Hunspell::FFI
    
    my $class = 'Alien::Hunspell::EN::AU';
    my $speller = Text::Hunspell->new($class->aff_file, $class->dic_file);

# DESCRIPTION

This Alien distribution provides Australian English language word list 
and affix files for use with Hunspell (from Perl with either 
[Text::Hunspell](https://metacpan.org/pod/Text::Hunspell) or [Text::Hunspell::FFI](https://metacpan.org/pod/Text::Hunspell::FFI).  It may also be useful for 
other applications.

# FUNCTIONS

## aff\_file

    my $aff_file = Alien::Hunspell::EN::AU->aff_file;

Returns the full path to the affix file.

## dic\_file

    my $dic_file = Alien::Hunspell::EN::AU->dic_file;

Returns the full path to the "dictionary" word list file.

## dir

    my $dir = Alien::Hunspell::EN::AU->dir;

Return the directory that contains the world list files.

# BUNDLED FILES

This distribution comes with files which are licensed under the GPL 
version 2.

    Copyright (C) 1989, 1991 Free Software Foundation, Inc.,

See the license.txt file in the share directory which came with this 
software.

# AUTHOR

Graham Ollis <plicease@cpan.org>

# COPYRIGHT AND LICENSE

This software is Copyright (c) 2016 by Graham Ollis.

This is free software, licensed under:

    The GNU General Public License, Version 2, June 1991
