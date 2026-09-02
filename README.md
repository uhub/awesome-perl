# awesome-perl

A curated list of awesome Perl frameworks, libraries and software.

* Learning and Reference
	* [Tutorials and Books](#tutorials-and-books)
	* [Examples and Exercises](#examples-and-exercises)
	* [Awesome Lists and Collections](#awesome-lists-and-collections)
* Language and Tooling
	* [Compilers and Interpreters](#compilers-and-interpreters)
	* [Build Systems](#build-systems)
	* [Package Management](#package-management)
	* [Linters and Formatters](#linters-and-formatters)
	* [Debugging and Profiling](#debugging-and-profiling)
	* [Editor and IDE Support](#editor-and-ide-support)
	* [Version Control](#version-control)
* Web
	* [Web Frameworks](#web-frameworks)
	* [HTTP and Networking Clients](#http-and-networking-clients)
	* [API and GraphQL](#api-and-graphql)
	* [Web Servers and Proxies](#web-servers-and-proxies)
	* [Scraping and Crawling](#scraping-and-crawling)
* Data and Storage
	* [Database Clients and ORMs](#database-clients-and-orms)
	* [Serialization and Formats](#serialization-and-formats)
	* [Caching and Queues](#caching-and-queues)
* Machine Learning and AI
	* [Natural Language Processing](#natural-language-processing)
	* [Data Science and Analytics](#data-science-and-analytics)
* Networking and Distributed
	* [Networking](#networking)
	* [RPC and Messaging](#rpc-and-messaging)
	* [Distributed Systems](#distributed-systems)
	* [Cloud and Infrastructure](#cloud-and-infrastructure)
	* [Monitoring and Observability](#monitoring-and-observability)
* User Interface
	* [Terminal and Console UI](#terminal-and-console-ui)
	* [Applications and End User Tools](#applications-and-end-user-tools)
* Graphics and Media
	* [Graphics and Rendering](#graphics-and-rendering)
	* [Game Development](#game-development)
	* [Audio](#audio)
	* [Image and Video](#image-and-video)
* Security
	* [Cryptography](#cryptography)
	* [Security Tools](#security-tools)
	* [Authentication and Authorization](#authentication-and-authorization)
	* [Reverse Engineering](#reverse-engineering)
* Concurrency and Performance
	* [Concurrency and Parallelism](#concurrency-and-parallelism)
* Testing and Quality
	* [Testing](#testing)
* Utilities
	* [Command Line Tools](#command-line-tools)
	* [Logging and Configuration](#logging-and-configuration)
	* [Text Processing](#text-processing)
	* [Files and Operating System](#files-and-operating-system)
	* [Automation and Scripting](#automation-and-scripting)
	* [General Purpose Libraries](#general-purpose-libraries)
* Systems and Hardware
	* [Embedded and Firmware](#embedded-and-firmware)
* Business and Domain
	* [Finance and Trading](#finance-and-trading)
	* [Business and Productivity](#business-and-productivity)
* Science and Math
	* [Scientific Computing](#scientific-computing)
* [Other](#other)

## Learning and Reference

### Tutorials and Books

* [astrid-runtime/book](https://github.com/astrid-runtime/book) - The canonical reference for Astrid: kernel, capsules, host ABI, IPC, and the security model.
* [jlord/git-it-electron](https://github.com/jlord/git-it-electron) - :computer: :mortar_board: Git-it is a (Mac, Win, Linux) Desktop App for Learning Git and GitHub
* [sarabander/sicp-pdf](https://github.com/sarabander/sicp-pdf) - SICP PDF with Texinfo and LaTeX source
* [openresty/nginx-tutorials](https://github.com/openresty/nginx-tutorials) - Nginx Tutorials
* [curl/everything-curl](https://github.com/curl/everything-curl) - The book documenting the curl project, the curl tool, libcurl and more. Simply put: everything curl.
* [hadley/ggplot2-book](https://github.com/hadley/ggplot2-book) - ggplot2: elegant graphics for data analysis
* [StefanSchroeder/Golang-Regex-Tutorial](https://github.com/StefanSchroeder/Golang-Regex-Tutorial) - Golang - Regular Expression Tutorial
* [mrnugget/opencv-haar-classifier-training](https://github.com/mrnugget/opencv-haar-classifier-training) - Learn how to train your own OpenCV Haar classifier *(archived)*
* [chromatic/modern_perl_book](https://github.com/chromatic/modern_perl_book) - Modern Perl: the book
* [neubig/nlptutorial](https://github.com/neubig/nlptutorial) - A Tutorial about Programming for Natural Language Processing
* [neubig/nmt-tips](https://github.com/neubig/nmt-tips) - A tutorial about neural machine translation including tips on building practical systems
* [awsdocs/aws-cdk-guide](https://github.com/awsdocs/aws-cdk-guide) - User guide for the AWS Cloud Development Kit (CDK).
* [openresty/programming-openresty](https://github.com/openresty/programming-openresty) - Programming OpenResty Book
* [swcarpentry/DEPRECATED-bc](https://github.com/swcarpentry/DEPRECATED-bc) - DEPRECATED: This repository is now frozen - please see individual lesson repositories. *(archived)*
* [gch1p/thinkpad-bios-software-flashing-guide](https://github.com/gch1p/thinkpad-bios-software-flashing-guide) - flashing coreboot on thinkpads without external programmer
* [mit-pdos/xv6-book](https://github.com/mit-pdos/xv6-book) - Commentary for xv6-public
* [spencertipping/js-in-ten-minutes](https://github.com/spencertipping/js-in-ten-minutes) - JavaScript in Ten (arbitrarily long) Minutes
* [petdance/bobby-tables](https://github.com/petdance/bobby-tables) - bobby-tables.com, the site for preventing SQL injections
* [ubccpsc/310](https://github.com/ubccpsc/310) - Main course webpage for CPSC 310.
* [GreyZhang/hack_autosar](https://github.com/GreyZhang/hack_autosar) - learning autosar documents, aha, very hard!
* [awakecoding/FreeRDP-Manuals](https://github.com/awakecoding/FreeRDP-Manuals) - FreeRDP Manuals
* [hackman/linux-sysadmin-course](https://github.com/hackman/linux-sysadmin-course) - Linux System Administration 101
* [powerman/asciidoc-cheatsheet](https://github.com/powerman/asciidoc-cheatsheet) - Asciidoc cheatsheet for GitHub
* [davetang/learning_vcf_file](https://github.com/davetang/learning_vcf_file) - Learning the Variant Call Format
* [theiostream/theos-ref](https://github.com/theiostream/theos-ref) - Theos Docs! (because there never was a chapter 2)
* [shabble/irssi-docs](https://github.com/shabble/irssi-docs) - In-depth documentation of the Irssi IRC Client
* [davetang/learning_bam_file](https://github.com/davetang/learning_bam_file) - Learning the Sequence Alignment/Map format
* [gjreda/pydata2014nyc](https://github.com/gjreda/pydata2014nyc) - Materials for my pandas tutorial at PyData 2014, NYC
* [chromatic/little_plack_book](https://github.com/chromatic/little_plack_book) - Using Plack and PSGI in Modern Perl Web Applications
* [WardCunningham/ddd](https://github.com/WardCunningham/ddd) - Domain Driven Design (Eric Evans's Patterns)
* [oalders/go-for-perl-hackers](https://github.com/oalders/go-for-perl-hackers) - Go Cheat Sheet for Perl Hackers
* [d3m0n4l3x/eJPT](https://github.com/d3m0n4l3x/eJPT) - Some knowledge learnt during the eJPT studying.
* [perladvent/perldotcom](https://github.com/perladvent/perldotcom) - The source code for Perl.com website
* [book/perlsecret](https://github.com/book/perlsecret) - The perl secret operators
* [djanowski/ack-tutorial](https://github.com/djanowski/ack-tutorial)
* [JJ/curso-tdd](https://github.com/JJ/curso-tdd) - Curso de desarrollo para asegurar la calidad del software
* [castaway/dbix-class-book](https://github.com/castaway/dbix-class-book) - DBIx::Class book
* [szabgab/perlmaven.com](https://github.com/szabgab/perlmaven.com) - The source files of the Perl Maven articles
* [manwar/Design-Patterns](https://github.com/manwar/Design-Patterns) - Design Patterns in Modern Perl.
* [davorg/perlwebbook](https://github.com/davorg/perlwebbook) - A book. About Perl. And the Web.
* [learnbyexample/Perl_intro](https://github.com/learnbyexample/Perl_intro) - :dromedary_camel: Introductory course for Perl 5 through examples, geared towards VLSI engineers
* [manwar/perl-cool-snippets](https://github.com/manwar/perl-cool-snippets) - A Perl cookbook of version-specific syntax snippets.
* [barbie/perl-jam](https://github.com/barbie/perl-jam) - Perl Jam - a book about organising conferences
* [kevinphilp/Perl-gtk3-Tutorial](https://github.com/kevinphilp/Perl-gtk3-Tutorial) - Some notes on using Gtk3 with Perl
* [thibaultduponchelle/tryperl](https://github.com/thibaultduponchelle/tryperl) - 🍫 Try Perl: learn the basics of the Perl language in your browser
* [jpa/Moose-Doc-JA](https://github.com/jpa/Moose-Doc-JA) - Perl Moose Documentation In Japanese
* [MaxPerl/perl-Gtk3-Tutorial](https://github.com/MaxPerl/perl-Gtk3-Tutorial) - a Tutorial about perl-Gtk3 based on the python tutorial found at https://developer.gnome.org/gnome-devel-demos/stable/tutorial.py.html.en
* [tokuhirom/optimize-perl-doc](https://github.com/tokuhirom/optimize-perl-doc) - how to optimize your perl code?
* [fayland/chinese-perl-book](https://github.com/fayland/chinese-perl-book) - free book in Chinese "Master Perl Today"

### Examples and Exercises

* [manwar/perlweeklychallenge-club](https://github.com/manwar/perlweeklychallenge-club) - Knowledge base for The Weekly Challenge club members using Perl, Raku, Ada, APL, Awk, Bash, BASIC, Bc, Befunge-93, Bourne Shell, BQN, Brainfuck, C3, C, CESIL, C++, C#, Clojure, COBOL, Coconut, Crystal, D, Dart, Dc, Elm, Emacs Lisp, Erlang, Excel VBA, Fennel, Fish, Forth, Fortran, Gembase, GNAT, Go, Haskell, Haxe, HTML, Idris, IO, J, Janet, Java, JavaScript, Julia, Kotlin, Lisp, Lua, M4, Miranda, Modula 3, MMIX, Mumps, Myrddin, Nim, Nix, Node.js, Nuweb, OCaml, Odin, Ook, Pascal, PHP, Python, Postscript, Prolog, R, Ring, Ruby, Rust, Scala, Scheme, Sed, Smalltalk, SQL, Swift, Tcl, TypeScript, Visual BASIC, WebAssembly, Wolfram, XSLT and Zig.
* [michaeljamesfitzgerald/Introducing-Regular-Expressions](https://github.com/michaeljamesfitzgerald/Introducing-Regular-Expressions) - Example code and target text files for the O'Reilly book Introducing Regular Expressions
* [HariSekhon/Templates](https://github.com/HariSekhon/Templates) - 100+ DevOps Code & Config templates for AWS, GCP, Docker, CI/CD, Kubernetes, Terraform, Packer, Jenkins, CircleCI, GitHub Actions, Vagrant, Puppet, Lambda, Python, Perl, Bash, Ruby, Golang, Java, Scala, Groovy, Maven, SBT, Gradle, Make, Jenkinsfile, Makefile, Dockerfile, docker-compose.yml, Vagrantfile, M4, AWS CodeBuild, GCP Cloud Build etc...
* [tempire/MojoExample](https://github.com/tempire/MojoExample) - Mojolicious example with DBIx::Class schema load, deploy, fixtures, and tests.
* [otherjoel/try-pollen](https://github.com/otherjoel/try-pollen) - 📔🌼 An example website/book created with Pollen.
* [oxnz/design-patterns](https://github.com/oxnz/design-patterns) - design patterns impelemented in serveral programming languages
* [CalculatedContent/tsvm](https://github.com/CalculatedContent/tsvm) - experiments testing transductive svm for my blog posts
* [briandfoy/Learning-Perl-Sample-Files](https://github.com/briandfoy/Learning-Perl-Sample-Files) - Extra files for use with Learning Perl
* [maebert/prolog_puzzles](https://github.com/maebert/prolog_puzzles) - Prolog puzzles for fun and profit (mostly fun)
* [mojombo/gollum-demo](https://github.com/mojombo/gollum-demo) - Gollum test repo
* [agordon/dancer_bootstrap_fontawesome_template](https://github.com/agordon/dancer_bootstrap_fontawesome_template) - A template for quick-starting applications using Perl's Dancer, Twitter's Bootstrap and Font-Awesome.
* [xsawyerx/perl-android-scripts](https://github.com/xsawyerx/perl-android-scripts) - Collection of Perl scripts (examples, programs) that run on Android using ASE
* [dave-theunsub/gtk3-perl-demos](https://github.com/dave-theunsub/gtk3-perl-demos) - This repository is intended to give perl-Gtk3 users some example programs. It's not rocket surgery, you know.
* [typester/perldojo](https://github.com/typester/perldojo) - online perl testing!
* [patrickleboutillier/jcscpu](https://github.com/patrickleboutillier/jcscpu) - Logical implementation, in Perl and Go, of the computer described in J. Clark Scott's book "But How Do It Know?".
* [exercism/perl5](https://github.com/exercism/perl5) - Exercism exercises in Perl 5.
* [kokonior/Perl-Projects](https://github.com/kokonior/Perl-Projects) - Feel free to create new file, don't hesitate to pull your code, the most important thing is that the file name here must match your nickname so that file does not conflict with other people.
* [skaji/perl-github-actions-sample](https://github.com/skaji/perl-github-actions-sample) - Perl meets GitHub Actions
* [sclorg/dancer-ex](https://github.com/sclorg/dancer-ex) - Perl Dancer Example
* [pkrumins/perl-tcp-proxy2](https://github.com/pkrumins/perl-tcp-proxy2) - Program for my "A TCP Proxy in Perl" article
* [ReneNyffenegger/PerlModules](https://github.com/ReneNyffenegger/PerlModules) - (Very) simple scripts for some Perl modules, intended as copy paste templates.
* [jmlynesjr/wxPerl-wxBook-Examples](https://github.com/jmlynesjr/wxPerl-wxBook-Examples) - wxPerl examples ported from "Cross-Platform GUI Programming with wxWidgets" - "The wxBook"

### Awesome Lists and Collections

* [hachiojipm/awesome-perl](https://github.com/hachiojipm/awesome-perl) - A curated list of awesome Perl frameworks and libraries. Come on Pull Requests!
* [szabgab/awesome-lists](https://github.com/szabgab/awesome-lists) - The awesome list of all the awesome lists
* [CDCgov/SARS-CoV-2_Sequencing](https://github.com/CDCgov/SARS-CoV-2_Sequencing) - A collection of sequencing protocols and bioinformatic resources for SARS-CoV-2 sequencing.
* [cindustries/unreal-directory](https://github.com/cindustries/unreal-directory) - Directory of useful Unreal Engine 4 resources
* [c9s/github-taiwan](https://github.com/c9s/github-taiwan) - Taiwan Developers on Github
* [dse/monospace-font-list](https://github.com/dse/monospace-font-list) - Work to build a list of monospace/typewriter/coding/fixed-width fonts, with completeness as the goal.
* [EnlightenedPerlOrganisation/task-kensho](https://github.com/EnlightenedPerlOrganisation/task-kensho) - A Glimpse at an Enlightned Perl Distribution
* [vmbrasseur/Perl_Companies](https://github.com/vmbrasseur/Perl_Companies) - A list of companies which use Perl. Initially generated from postings to jobs.perl.org. *(archived)*
* [szabgab/perlweekly](https://github.com/szabgab/perlweekly) - A free, once a week e-mail round-up of hand-picked news and articles about Perl

## Language and Tooling

### Compilers and Interpreters

* [Perl/perl5](https://github.com/Perl/perl5) - 🐪 The Perl programming language
* [fglock/Perlito](https://github.com/fglock/Perlito) - "Perlito" Perl programming language compiler
* [fxcoudert/gfortran-for-macOS](https://github.com/fxcoudert/gfortran-for-macOS) - GNU Fortran (and GCC) compilers for macOS
* [audreyt/lingua-sinica-perlyuyan](https://github.com/audreyt/lingua-sinica-perlyuyan) - Perl in Classical Chinese in Perl
* [wbraswell/rperl](https://github.com/wbraswell/rperl) - RPerl Compiler
* [theos/logos](https://github.com/theos/logos) - Preprocessor that simplifies Objective-C hooking.
* [yuvi/gas-preprocessor](https://github.com/yuvi/gas-preprocessor) - Perl script that implements a subset of the GNU as preprocessor that Apple's as doesn't
* [Drahflow/Elymas](https://github.com/Drahflow/Elymas) - A programming language I can like. Unholy and full of magic.
* [spencertipping/caterwaul](https://github.com/spencertipping/caterwaul) - A Javascript-to-Javascript compiler
* [jeffreykegler/Marpa--R2](https://github.com/jeffreykegler/Marpa--R2) - Parse any language you can describe in BNF
* [Perl-Apollo/Corinna](https://github.com/Perl-Apollo/Corinna) - Corinna - Bring Modern OO to the Core of Perl
* [perl11/cperl](https://github.com/perl11/cperl) - A perl5 with classes, types, compilable, company friendly, security *(archived)*
* [combinatorylogic/clike](https://github.com/combinatorylogic/clike) - A simple C-like language compiler with an extensible syntax and typed macros support
* [trizen/sidef](https://github.com/trizen/sidef) - Sidef is a modern, expressive programming language that combines the elegance of Ruby, the versatility of Raku, and the mathematical power of a built-in computer algebra system.
* [topaz/aoc2019-intcode](https://github.com/topaz/aoc2019-intcode) - Intcode compiler and samples from Advent of Code 2019
* [Qucs/ADMS](https://github.com/Qucs/ADMS) - ADMS is a code generator for some of Verilog-A
* [combinatorylogic/mbase](https://github.com/combinatorylogic/mbase) - Metaprogramming framework for .net
* [Perl/PPCs](https://github.com/Perl/PPCs) - This repository is for Proposed Perl Changes - proposals to change the Perl language.
* [yosshin4004/xdev68k](https://github.com/yosshin4004/xdev68k) - Cross development environment for the SHARP X68K.
* [rurban/perl-compiler](https://github.com/rurban/perl-compiler) - B::C - Moved over from googlecode
* [fglock/PerlOnJava](https://github.com/fglock/PerlOnJava) - An implementation of the Perl programming language designed to run on the Java platform
* [pegex-parser/pegex-pm](https://github.com/pegex-parser/pegex-pm) - Pegex Parser for Perl
* [hzhou/MyDef](https://github.com/hzhou/MyDef) - Programming in the next paradigm -- your way
* [mklement0/perli](https://github.com/mklement0/perli) - Multi-platform Perl REPL
* [softpano/pythonizer](https://github.com/softpano/pythonizer) - Translator (or more correctly transcriber) from Perl to Python
* [G4Vi/Perl-Dist-APPerl](https://github.com/G4Vi/Perl-Dist-APPerl) - Actually Portable Perl
* [passerinea/Perl2Python](https://github.com/passerinea/Perl2Python) - A tool to (try to) convert Perl scripts to Python
* [jnthn/blizkost](https://github.com/jnthn/blizkost) - Makes Perl 5 available as if it were just another Parrot language by embedding the Perl 5 interpreter. *(archived)*
* [run4flat/C-Blocks](https://github.com/run4flat/C-Blocks) - Embeding a fast C compiler directly into your Perl parser
* [timbunce/java2perl6](https://github.com/timbunce/java2perl6) - Parse Java class files and generate corresponding Perl6 Class and Role files
* [PeterMartini/go-perl](https://github.com/PeterMartini/go-perl) - Linking in Go code via XS
* [rafl/devel-declare](https://github.com/rafl/devel-declare) - Adding keywords to perl, in perl
* [hotwolf/HSW12](https://github.com/hotwolf/HSW12) - Assembler and IDE for NXP/Freescale/Motorola's HC11, HC12, S12, S12X, and XGATE CPUs
* [Util/Blue_Tiger](https://github.com/Util/Blue_Tiger) - Perl 5 to Perl 6 Translator
* [audreyt/pugs](https://github.com/audreyt/pugs) - A Perl 6 Implementation
* [drforr/Perl-Mogrify](https://github.com/drforr/Perl-Mogrify) - Transmogrify Perl5 code to Perl6 with a plugin system
* [xsawyerx/guacamole](https://github.com/xsawyerx/guacamole) - Guacamole is a parser toolkit for Standard Perl. It provides fully static BNF-based parsing capability to a reasonable subset of Perl.
* [wehu/CljPerl](https://github.com/wehu/CljPerl) - CljPerl is a lisp on Perl.

### Build Systems

* [webfrogs/xcode_shell](https://github.com/webfrogs/xcode_shell) - shell script that used to auto-build xcode project
* [plerup/makeEspArduino](https://github.com/plerup/makeEspArduino) - A makefile for ESP8266 and ESP32 Arduino projects
* [openresty/openresty-devel-utils](https://github.com/openresty/openresty-devel-utils) - Utilities for nginx module development
* [Zimbra/zm-build](https://github.com/Zimbra/zm-build) - zm-build for Zimbra Collaboration Suite, FOSS Edition
* [rjbs/Dist-Zilla](https://github.com/rjbs/Dist-Zilla) - scary tools for building CPAN distributions
* [pagekite/Colormake](https://github.com/pagekite/Colormake) - A simple wrapper around make to colorize the output.
* [openSUSE/obs-build](https://github.com/openSUSE/obs-build) - OBS build script, can be used with OBS or stand alone
* [johnno1962/xcodemake](https://github.com/johnno1962/xcodemake) - Faster xcodebuilds using "make"
* [ainvyu/vcxproj2cmake](https://github.com/ainvyu/vcxproj2cmake) - Convert Visual studio 2010 project(vcxproj) to CMakeFile.txt
* [DOCGroup/MPC](https://github.com/DOCGroup/MPC) - MPC (The Makefile, Project, and Workspace Creator)
* [Perl-Toolchain-Gang/ExtUtils-MakeMaker](https://github.com/Perl-Toolchain-Gang/ExtUtils-MakeMaker) - Perl module to make Makefiles and build modules (what backs Makefile.PL)
* [rschupp/PAR-Packer](https://github.com/rschupp/PAR-Packer) - (perl) Generate stand-alone executables, perl scripts and PAR files https://metacpan.org/pod/PAR::Packer
* [metomi/fcm](https://github.com/metomi/fcm) - :hammer: FCM: a modern Fortran build system + wrappers to Subversion for scientific software development
* [Perl-Toolchain-Gang/Module-Build](https://github.com/Perl-Toolchain-Gang/Module-Build) - Perl module to configure and build modules (what backs most Build.PLs)
* [bingos/devel-patchperl](https://github.com/bingos/devel-patchperl) - (perl) Patch perl source a la Devel::PPort's buildperl.pl
* [Perl-Toolchain-Gang/ExtUtils-CBuilder](https://github.com/Perl-Toolchain-Gang/ExtUtils-CBuilder) - Compile and link C code for Perl modules
* [liyanage/build-entropy-php](https://github.com/liyanage/build-entropy-php) - The Perl-based build system used to build the Entropy PHP distribution

### Package Management

* [hokaccha/nodebrew](https://github.com/hokaccha/nodebrew) - Node.js version manager
* [trizen/trizen](https://github.com/trizen/trizen) - Lightweight AUR Package Manager
* [miyagawa/cpanminus](https://github.com/miyagawa/cpanminus) - cpanminus - get, unpack, build and install modules from CPAN
* [gugod/App-perlbrew](https://github.com/gugod/App-perlbrew) - Manage perl installations in your $HOME
* [perl-carton/carton](https://github.com/perl-carton/carton) - Bundler or pip freeze for Perl
* [metacpan/metacpan-web](https://github.com/metacpan/metacpan-web) - Web interface for MetaCPAN
* [apt-mirror/apt-mirror](https://github.com/apt-mirror/apt-mirror) - Official apt-mirror source.
* [StrawberryPerl/Perl-Dist-Strawberry](https://github.com/StrawberryPerl/Perl-Dist-Strawberry) - Tooling to build and package releases for Perl on Windows.
* [metacpan/metacpan-api](https://github.com/metacpan/metacpan-api) - A free, open API for everything you want to know about CPAN
* [openSUSE/opi](https://github.com/openSUSE/opi) - OBS Package Installer (CLI)
* [fink/fink](https://github.com/fink/fink) - The fink package manager
* [lvc/pkgdiff](https://github.com/lvc/pkgdiff) - A tool for visualizing changes in Linux software packages
* [edolstra/nix-serve](https://github.com/edolstra/nix-serve) - A standalone Nix binary cache server
* [VividCortex/johnny-deps](https://github.com/VividCortex/johnny-deps) - Barebones dependency manager for Go. *(archived)*
* [tadzik/rakudobrew](https://github.com/tadzik/rakudobrew) - Perl 6 installation manager
* [c9s/Vimana](https://github.com/c9s/Vimana) - Vimana is an easy to use system for searching , installing, and downloading vim script. Vimana provides a command-line interface such like aptitude programe on Debian linux, for you to search , download , install , upgrade scripts from http://www.vim.org (vimonline site).
* [skaji/cpm](https://github.com/skaji/cpm) - fast CPAN client
* [whohas/whohas](https://github.com/whohas/whohas) - Cross-platform software search
* [andk/pause](https://github.com/andk/pause) - Perl authors upload server
* [Raku/ecosystem](https://github.com/Raku/ecosystem) - Raku ecosystem – modules and more
* [miyagawa/Carmel](https://github.com/miyagawa/Carmel) - CPAN Artifact Repository Manager
* [avh4/elm-upgrade](https://github.com/avh4/elm-upgrade) - Upgrade Elm projects
* [tokuhirom/Minilla](https://github.com/tokuhirom/Minilla) - Authorizing tool for CPAN modules
* [andk/cpanpm](https://github.com/andk/cpanpm) - CPAN.pm
* [tokuhirom/Perl-Build](https://github.com/tokuhirom/Perl-Build)
* [miyagawa/cpanfile](https://github.com/miyagawa/cpanfile) - Yet another way to declare CPAN dependencies
* [skaji/relocatable-perl](https://github.com/skaji/relocatable-perl) - self-contained, portable perl binaries
* [thaljef/Pinto](https://github.com/thaljef/Pinto) - Curate your own repository of Perl modules
* [jizhang/perl-virtualenv](https://github.com/jizhang/perl-virtualenv) - Virtual Environment for Perl
* [xsawyerx/module-starter](https://github.com/xsawyerx/module-starter) - Module::Starter, a tool to help create solid Perl modules from scratch
* [dann/p5-cpan-packager](https://github.com/dann/p5-cpan-packager) - CPAN::Packager is a tool to help you make packages from perl modules on CPAN.
* [Perl-Toolchain-Gang/local-lib](https://github.com/Perl-Toolchain-Gang/local-lib) - local::lib - create and use a local lib/ for perl modules with PERL5LIB
* [briandfoy/cpan-script](https://github.com/briandfoy/cpan-script) - (Perl) Interact with CPAN from the command line *(archived)*
* [mklement0/whichpm](https://github.com/mklement0/whichpm) - Locates installed Perl modules.
* [rurban/App-perlall](https://github.com/rurban/App-perlall) - create and work with /usr/local/bin/perl5.*

### Linters and Formatters

* [AlDanial/cloc](https://github.com/AlDanial/cloc) - cloc counts blank lines, comment lines, and physical lines of source code in many programming languages.
* [alx-tools/Betty](https://github.com/alx-tools/Betty) - Holberton-style C code checker written in Perl
* [lvc/abi-compliance-checker](https://github.com/lvc/abi-compliance-checker) - A tool for checking backward API/ABI compatibility of a C/C++ library
* [lvc/japi-compliance-checker](https://github.com/lvc/japi-compliance-checker) - A tool for checking backward API/ABI compatibility of a Java library
* [koknat/callGraph](https://github.com/koknat/callGraph) - A multi-language tool which parses source code for function definitions and calls
* [check-spelling/check-spelling](https://github.com/check-spelling/check-spelling) - Spelling checker action to check spelling in repositories / pull requests / commits
* [petersenna/codeviz](https://github.com/petersenna/codeviz) - CodeViz: A CallGraph Visualiser
* [lvc/abi-dumper](https://github.com/lvc/abi-dumper) - Dump ABI of an ELF object containing DWARF debug info
* [lvc/abi-tracker](https://github.com/lvc/abi-tracker) - A tool to visualize ABI changes timeline of a C/C++ software library
* [Perl-Critic/Perl-Critic](https://github.com/Perl-Critic/Perl-Critic) - The leading static analyzer for Perl. Configurable, extensible, powerful.
* [perltidy/perltidy](https://github.com/perltidy/perltidy) - Perl::Tidy, a source code formatter for Perl
* [moznion/Perl-Lint](https://github.com/moznion/Perl-Lint) - Yet Another Perl Source Code Linter
* [sonar-perl/sonar-perl](https://github.com/sonar-perl/sonar-perl) - Community Perl Plugin for SonarQube
* [hrbrmstr/cloc](https://github.com/hrbrmstr/cloc) - 🔢 R package to the perl cloc script (which counts blank lines, comment lines, and physical lines of source code in source files/trees/archives)
* [hitode909/App-PRT](https://github.com/hitode909/App-PRT) - Command line tool for Perl code refactoring
* [perl-ide/App-perlimports](https://github.com/perl-ide/App-perlimports) - Make implicit Perl imports explicit
* [worldmind/perlqual](https://github.com/worldmind/perlqual) - Wrapper for some tests for Perl code quality

### Debugging and Profiling

* [brendangregg/FlameGraph](https://github.com/brendangregg/FlameGraph) - Stack trace visualizer
* [openresty/openresty-systemtap-toolkit](https://github.com/openresty/openresty-systemtap-toolkit) - Real-time analysis and diagnostics tools for OpenResty (including NGINX, LuaJIT, ngx_lua, and more) based on SystemTap
* [openresty/stapxx](https://github.com/openresty/stapxx) - Simple macro language extentions to systemtap
* [proger/eflame](https://github.com/proger/eflame) - Flame Graph profiler for Erlang
* [brendangregg/HeatMap](https://github.com/brendangregg/HeatMap) - Heat map generation tools
* [bearstech/phptop](https://github.com/bearstech/phptop) - PHP basic ressource profiler (CPU/memory), safe and useful for production sites
* [blopker/djdt-flamegraph](https://github.com/blopker/djdt-flamegraph) - Flamegraphs for Django Debug Toolbar *(archived)*
* [mrhooray/torch](https://github.com/mrhooray/torch) - Generate CPU FlameGraphs based on DWARF Debug Info
* [esrrhs/pLua](https://github.com/esrrhs/pLua) - Lua 性能分析工具 Lua profiler tool like gperftools
* [intel/ioprof](https://github.com/intel/ioprof) - The Linux I/O profiler (ioprof) is a tool that provides significant insight into I/O workloads while remaining easy to use. *(archived)*
* [garu/Data-Printer](https://github.com/garu/Data-Printer) - colored pretty-print of Perl data structures and objects
* [agentzh/perl-systemtap-toolkit](https://github.com/agentzh/perl-systemtap-toolkit) - Real-time analyzing and diagnosing tools for perl 5 based on SystemTap
* [timbunce/devel-nytprof](https://github.com/timbunce/devel-nytprof) - Devel::NYTProf is a powerful feature-rich source code profiler for Perl. (Mostly in maintenance mode, so PRs are much more likely to be acted upon than Issues.)
* [onishi/perl5-devel-kytprof](https://github.com/onishi/perl5-devel-kytprof) - Devel::KYTProf - Simple Perl code profiler
* [Trepan-Debuggers/Perl-Devel-Trepan](https://github.com/Trepan-Debuggers/Perl-Devel-Trepan) - Perl port of trepanning debugger
* [Ovid/DB--Color](https://github.com/Ovid/DB--Color) - Syntax highlighting the Perl debugger
* [Camelcade/Devel-Camelcadedb](https://github.com/Camelcade/Devel-Camelcadedb) - Perl module for debugging with Perl5 plugin for IntelliJ
* [mbarbon/devel-statprofiler](https://github.com/mbarbon/devel-statprofiler) - Low-overhead statistical Perl profiler for production use

### Editor and IDE Support

* [YabataDesign/afterglow-theme](https://github.com/YabataDesign/afterglow-theme) - [DEPRECATED] A minimal dark Theme for Sublime Text 2 and 3
* [Camelcade/Perl5-IDEA](https://github.com/Camelcade/Perl5-IDEA) - Perl5 plugins for IntelliJ IDEA
* [file-icons/icons](https://github.com/file-icons/icons) - Source files for the custom icon-font used by the File-Icons package.
* [bscan/PerlNavigator](https://github.com/bscan/PerlNavigator) - Perl Language Server that includes syntax checking, perl critic, and code navigation
* [richterger/Perl-LanguageServer](https://github.com/richterger/Perl-LanguageServer) - Language Server for Perl
* [jjrscott/ColoredConsole](https://github.com/jjrscott/ColoredConsole) - Reenabling colors in Xcode's console
* [rcarmo/textwrangler-bbedit-solarized](https://github.com/rcarmo/textwrangler-bbedit-solarized) - solarized color scheme for BBEdit and TextWrangler
* [jtaby/Waldo](https://github.com/jtaby/Waldo) - A generic port of TextMate's Find-In-Project, with associated MacVim plugin
* [FractalBoy/perl-language-server](https://github.com/FractalBoy/perl-language-server)
* [PadreIDE/Padre](https://github.com/PadreIDE/Padre) - Offical repository of the core Padre code
* [Ibmurai/Markdown.codaplugin](https://github.com/Ibmurai/Markdown.codaplugin) - A Markdown plugin for Coda.
* [ice1000/NppExtension](https://github.com/ice1000/NppExtension) - :smiley: Language extension for notepad++
* [liyanage/xcode-text-macros](https://github.com/liyanage/xcode-text-macros) - Some XCode text macros plus a macro overview HTML page generator
* [jploski/epic-ide](https://github.com/jploski/epic-ide) - EPIC - Eclipse Perl Integration (new official repository!)
* [aki2o/plsense](https://github.com/aki2o/plsense) - Omni completion tool for Perl
* [Blaizer/ModernPerl-sublime](https://github.com/Blaizer/ModernPerl-sublime) - Perl syntax highlighting for Sublime Text that isn't outdated
* [textmate/perl.tmbundle](https://github.com/textmate/perl.tmbundle) - TextMate support for Perl
* [yanick/Vim-X](https://github.com/yanick/Vim-X) - Write Perl functions within Vim

### Version Control

* [so-fancy/diff-so-fancy](https://github.com/so-fancy/diff-so-fancy) - Make your diffs human readable for improved code quality and faster defect detection. :tada:
* [sitaramc/gitolite](https://github.com/sitaramc/gitolite) - Hosting git repositories -- Gitolite allows you to setup git hosting on a central server, with very fine-grained access control and many (many!) more powerful features.
* [k4rthik/git-cal](https://github.com/k4rthik/git-cal) - github like contributions calendar on terminal
* [yuki-kimoto/gitprep](https://github.com/yuki-kimoto/gitprep) - Portable GitHub system into your own server
* [dolmen/github-keygen](https://github.com/dolmen/github-keygen) - Easy creation and upgrade of secure SSH configuration for your GitHub account(s)
* [takaaki-kasai/git-foresta](https://github.com/takaaki-kasai/git-foresta) - git-foresta: Text-based git log graph viewer
* [torbiak/git-autofixup](https://github.com/torbiak/git-autofixup) - create fixup commits for topic branches
* [Git-Mediawiki/Git-Mediawiki](https://github.com/Git-Mediawiki/Git-Mediawiki) - Gate between Git and Mediawiki
* [broquaint/Gitalist](https://github.com/broquaint/Gitalist) - A modern git web viewer
* [mjdominus/git-util](https://github.com/mjdominus/git-util) - Miscellaneous git scripts and utilities
* [danny0838/git-store-meta](https://github.com/danny0838/git-store-meta) - Simple file metadata storing and applying for git.
* [dmnd/git-diff-blame](https://github.com/dmnd/git-diff-blame) - 🕵 Display a diff alongside blame info like author and commit
* [mndrix/merge-this](https://github.com/mndrix/merge-this) - Revision control stress tests *(archived)*
* [SethRobertson/git-what-branch](https://github.com/SethRobertson/git-what-branch) - Discover what branch a commit is on, or how it got to a named branch
* [RichiH/myrepos](https://github.com/RichiH/myrepos)
* [brunopostle/ifcmerge](https://github.com/brunopostle/ifcmerge) - A three-way-merge tool for IFC files
* [jacquesg/p5-Git-Raw](https://github.com/jacquesg/p5-Git-Raw) - Perl bindings to the Git linkable library (libgit2)
* [acme/git-pureperl](https://github.com/acme/git-pureperl) - A Pure Perl interface to Git repositories
* [book/Git-Repository](https://github.com/book/Git-Repository) - Perl interface to Git repositories

## Web

### Web Frameworks

* [mojolicious/mojo](https://github.com/mojolicious/mojo) - :sparkles: Mojolicious - Perl real-time web framework
* [idevz/vanilla](https://github.com/idevz/vanilla) - An OpenResty Lua MVC Web Framework
* [PerlDancer/Dancer](https://github.com/PerlDancer/Dancer) - The easiest way to write web applications with Perl (Perl web micro-framework)
* [PerlDancer/Dancer2](https://github.com/PerlDancer/Dancer2) - Perl Dancer Next Generation (rewrite of Perl Dancer)
* [plack/Plack](https://github.com/plack/Plack) - PSGI toolkit and server adapters
* [perl-catalyst/catalyst-runtime](https://github.com/perl-catalyst/catalyst-runtime) - The Elegant MVC Web Application Framework
* [tokuhirom/Amon](https://github.com/tokuhirom/Amon) - yet another web application framework
* [tudorconstantin/Mojolicious-Boilerplate](https://github.com/tudorconstantin/Mojolicious-Boilerplate) - The Web in an **Awesome** Box
* [gshank/html-formhandler](https://github.com/gshank/html-formhandler) - a Perl Moose HTML form handler
* [typester/ark-perl](https://github.com/typester/ark-perl)
* [Kelp-framework/Kelp](https://github.com/Kelp-framework/Kelp) - Main repository of the Kelp web framework
* [preaction/Yancy](https://github.com/preaction/Yancy) - The Best Web Framework Deserves the Best Content Management System
* [masak/web](https://github.com/masak/web) - A Perl 6 web framework
* [sartak/webmachine-perl](https://github.com/sartak/webmachine-perl) - A Perl port of Webmachine
* [iinteractive/OX](https://github.com/iinteractive/OX) - the hardest working two letters in Perl
* [jjn1056/pagi](https://github.com/jjn1056/pagi) - Perl port of Python's ASGI
* [beppu/squatting](https://github.com/beppu/squatting) - A Camping-inspired Web Microframework for Perl
* [leejo/CGI.pm](https://github.com/leejo/CGI.pm) - The CGI.pm perl module
* [jamadam/mojo-legacy](https://github.com/jamadam/mojo-legacy) - mojo for Perl-5.8.7
* [jonswar/perl-poet](https://github.com/jonswar/perl-poet) - Perl Poet distribution
* [livedoor/Sledge](https://github.com/livedoor/Sledge) - ancient Perl Web Application Framework.
* [vti/plack-middleware-socketio](https://github.com/vti/plack-middleware-socketio) - Socket.IO Perl/Plack implementation DEPRECATED USE PocketIO INSTEAD
* [markstos/CGI--Application](https://github.com/markstos/CGI--Application) - A Perl framework for building reusable web-applications

### HTTP and Networking Clients

* [cloudflare/lua-resty-cookie](https://github.com/cloudflare/lua-resty-cookie) - Lua library for HTTP cookie manipulations for OpenResty/ngx_lua *(archived)*
* [curl/h2c](https://github.com/curl/h2c) - headers 2 curl. Provided a set of HTTP request headers, output the curl command line for generating that set. Try the converter online at
* [libwww-perl/libwww-perl](https://github.com/libwww-perl/libwww-perl) - The libwww-perl collection is a set of Perl modules that provides a simple, consistent application programming interface to the World-Wide Web. The main focus of the library is providing classes and functions allowing to write WWW clients. It also contains modules that are of more general use and even classes to help implement simple HTTP servers.
* [fayland/perl-net-github](https://github.com/fayland/perl-net-github) - Perl interface to GitHub
* [tokuhirom/Furl](https://github.com/tokuhirom/Furl) - pretty fast http client library for perl5
* [semifor/Net-Twitter](https://github.com/semifor/Net-Twitter) - A Perl interface to the Twitter APIs *(archived)*
* [line/line-bot-sdk-perl](https://github.com/line/line-bot-sdk-perl) - LINE Messaging API SDK for Perl *(archived)*
* [plu/Pithub](https://github.com/plu/Pithub) - Perl Github v3 API
* [rizen/Facebook-Graph](https://github.com/rizen/Facebook-Graph) - A perl module to help navigate the intricacies of the Facebook Graph API.
* [Robertof/perl-www-telegram-botapi](https://github.com/Robertof/perl-www-telegram-botapi) - Perl implementation of the Telegram Bot API
* [sanko/Finance-Robinhood](https://github.com/sanko/Finance-Robinhood) - Trade stocks and ETFs with free brokerage Robinhood and Perl
* [ericblue/Perl-FitBit-API](https://github.com/ericblue/Perl-FitBit-API) - Provides an OO API for fetching fitness data from fitbit.com. Currently there is no official API, however data is retrieved using XML feeds that populate the flash-based charts.
* [norbu09/Net--Dropbox](https://github.com/norbu09/Net--Dropbox) - perl interface to the Dropbox API
* [comewalk/google-api-perl-client](https://github.com/comewalk/google-api-perl-client) - Google APIs Client Library for Perl
* [cotto/www-workflowy](https://github.com/cotto/www-workflowy) - unofficial reverse-engineered Perl 5 interface to Workflowy
* [ericblue/Perl-Belkin-WeMo-API](https://github.com/ericblue/Perl-Belkin-WeMo-API) - Perl-Belkin-WeMo-API
* [tempire/perl-google-voice](https://github.com/tempire/perl-google-voice) - Perl module to interact with Google::Voice
* [hexsum/pfqq](https://github.com/hexsum/pfqq) - 【该项目已停止维护，请关注重构项目: Mojo-Webqq】使用Perl语言编写的webqq客户端框架（非GUI），支持旧版webqq的多重md5带盐登录密码算法以及新版smartqq的md5+rsa+tea+base64组合登录密码算法
* [lukec/stripe-perl](https://github.com/lukec/stripe-perl) - Perl library to connect to the Stripe API
* [vsTerminus/Mojo-Discord](https://github.com/vsTerminus/Mojo-Discord) - Perl Modules that implement parts of the Discord API. Intended for Text Chat Bots.
* [hexsum/Mojo-SinaWeibo](https://github.com/hexsum/Mojo-SinaWeibo) - 使用Perl语言编写的新浪微博客户端SDK，通过微博私信和微软小冰进行问答，提供小冰API接口，其他微博功能敬请期待
* [dk/Net-Eboks](https://github.com/dk/Net-Eboks) - perl API for eboks.dk
* [metacpan/MetaCPAN-Client](https://github.com/metacpan/MetaCPAN-Client) - Home of the official MetaCPAN Perl API client.
* [CpanelInc/cPanel-PublicAPI](https://github.com/CpanelInc/cPanel-PublicAPI) - A perl module for interfacing with cPanel's various APIs
* [ipinfo/perl](https://github.com/ipinfo/perl) - Official Perl client library for IPinfo API (IP geolocation and other types of IP data)
* [szbalint/WWW--Curl](https://github.com/szbalint/WWW--Curl) - Perl binding for libcurl
* [semifor/net-twitter-lite](https://github.com/semifor/net-twitter-lite) - A lighter weight (non-Moose) Perl interface to the Twitter API *(archived)*
* [aquaron/Business-Stripe](https://github.com/aquaron/Business-Stripe) - Perl bindings for Stripe payment system
* [sysread/Reddit-API](https://github.com/sysread/Reddit-API) - Reddit API for perl
* [gray/webservice-google-reader](https://github.com/gray/webservice-google-reader) - Perl interface to the Google Reader API
* [Evernote/evernote-sdk-perl](https://github.com/Evernote/evernote-sdk-perl) - Evernote SDK for Perl *(archived)*
* [googleads/google-ads-perl](https://github.com/googleads/google-ads-perl) - Google Ads API Client Library for Perl

### API and GraphQL

* [ocpi/ocpi](https://github.com/ocpi/ocpi) - The Open Charge Point Interface (OCPI) allows for a scalable, automated roaming setup between Charge Point Operators and e-Mobility Service Providers. It supports authorisation, charge point information exchange (incl transaction events), charge detail record exchange and finally, the exchange of smart-charging commands between parties.
* [leedo/noembed](https://github.com/leedo/noembed) - oEmbed gateway service with additional non-oEmbed sources
* [Ensembl/ensembl-rest](https://github.com/Ensembl/ensembl-rest) - Language agnostic RESTful data access to Ensembl data over HTTP
* [jloh/geojs](https://github.com/jloh/geojs) - Geo-location lookup API
* [SPORE/specifications](https://github.com/SPORE/specifications) - SPORE specifications
* [graphql-perl/graphql-perl](https://github.com/graphql-perl/graphql-perl) - GraphQL in Perl 5
* [agentzh/old-openresty](https://github.com/agentzh/old-openresty) - Obsolete 1st generation of OpenResty written mostly in Perl. Please check out the new OpenResty based on Nginx and Lua instead.
* [khrt/Raisin](https://github.com/khrt/Raisin) - Raisin - a REST API micro framework for Perl 🐫 🐪
* [SPORE/net-http-spore](https://github.com/SPORE/net-http-spore) - Perl implementation for SPORE *(archived)*
* [skx/dns-api.org](https://github.com/skx/dns-api.org) - The code which was previously used at https://dns-api.org/ *(archived)*

### Web Servers and Proxies

* [CNSRE/ABTestingGateway](https://github.com/CNSRE/ABTestingGateway)
* [engintron/engintron](https://github.com/engintron/engintron) - Engintron for cPanel/WHM is the easiest way to integrate Nginx on your cPanel/WHM server. Engintron will improve the performance & web serving capacity of your server, while reducing CPU/RAM load at the same time, by installing & configuring the popular Nginx webserver to act as a reverse caching proxy in front of Apache.
* [yaoweibin/ngx_http_substitutions_filter_module](https://github.com/yaoweibin/ngx_http_substitutions_filter_module) - a filter module which can do both regular expression and fixed string substitutions for nginx
* [richardforth/apache2buddy](https://github.com/richardforth/apache2buddy) - apache2buddy
* [miyagawa/Starman](https://github.com/miyagawa/Starman) - Starman is a high-performance preforking Perl PSGI web server
* [yaoweibin/nginx_ajp_module](https://github.com/yaoweibin/nginx_ajp_module) - support AJP protocol proxy with Nginx
* [multiplay/lancache](https://github.com/multiplay/lancache) - Dynamically Cache Game Installs at LAN’s using Nginx *(archived)*
* [timebug/lua-resty-redis-ratelimit](https://github.com/timebug/lua-resty-redis-ratelimit) - Limit the request processing rate between multiple NGINX instances backed by Redis
* [zevenet/zlb](https://github.com/zevenet/zlb) - ZEVENET is now RELIANOID
* [apache/incubator-pagespeed-cpanel](https://github.com/apache/incubator-pagespeed-cpanel) - mod_pagespeed module for CPanel WHM *(archived)*
* [calio/form-input-nginx-module](https://github.com/calio/form-input-nginx-module) - This is a nginx module that reads HTTP POST and PUT request body encoded in "application/x-www-form-urlencoded", and parse the arguments in request body into nginx variables.
* [hamishforbes/lua-resty-upstream](https://github.com/hamishforbes/lua-resty-upstream) - Upstream connection load balancing and failover module for Openresty
* [nicholaschiasson/ngx_upstream_jdomain](https://github.com/nicholaschiasson/ngx_upstream_jdomain) - An asynchronous domain name resolution module for nginx upstream. *(archived)*
* [TooTallNate/node-cgi](https://github.com/TooTallNate/node-cgi) - An http/stack/connect layer to invoke and serve CGI executables.
* [gustavmaskowitz/apachebuddy.pl](https://github.com/gustavmaskowitz/apachebuddy.pl) - Not written by me, no longer maintained by me : Apachebuddy.pl
* [rgeissert/http-redirector](https://github.com/rgeissert/http-redirector) - Debian mirrors HTTP redirector
* [mindreframer/nginx-lua-stuff](https://github.com/mindreframer/nginx-lua-stuff) - some libs for NginX-Lua integration
* [kazeburo/Gazelle](https://github.com/kazeburo/Gazelle) - Preforked Plack Handler for performance freaks
* [stash/Feersum](https://github.com/stash/Feersum) - A PSGI engine for Perl based on EV/libev
* [openSUSE/MirrorCache](https://github.com/openSUSE/MirrorCache) - Download Redirector
* [davidcarlisle/latexcgi](https://github.com/davidcarlisle/latexcgi) - LaTeX server via perl cgi script, developed for learnlatex.org
* [apache/mod_perl](https://github.com/apache/mod_perl) - Mirror of Apache mod_perl
* [mpaperno/spampd](https://github.com/mpaperno/spampd) - SpamPD - Spam Proxy Daemon. A spam-filtering SMTP/LMTP proxy server using SpamAssassin in Perl. Since 2002.
* [hachi/Perlbal](https://github.com/hachi/Perlbal) - Perl HTTP Load Balancer

### Scraping and Crawling

* [XMLTV/xmltv](https://github.com/XMLTV/xmltv) - Utilities to obtain, generate, and post-process TV listings data in XMLTV format
* [ciderpunx/twitrssme](https://github.com/ciderpunx/twitrssme) - TwitRSS.me: Tool to make Twittter timelines and searches into RSS feeds
* [duckduckgo/smarter-encryption](https://github.com/duckduckgo/smarter-encryption)
* [teodesian/Selenium-Remote-Driver](https://github.com/teodesian/Selenium-Remote-Driver) - Perl Bindings to the Selenium Webdriver server
* [finance-quote/finance-quote](https://github.com/finance-quote/finance-quote) - Finance::Quote module for Perl
* [w3c/link-checker](https://github.com/w3c/link-checker) - Check links and anchors in Web pages or full Web sites.
* [miyagawa/web-scraper](https://github.com/miyagawa/web-scraper) - Perl web scraping toolkit
* [shuaiscott/zap2xml](https://github.com/shuaiscott/zap2xml) - Docker container for zap2xml
* [libwww-perl/WWW-Mechanize](https://github.com/libwww-perl/WWW-Mechanize) - Handy web browsing in a Perl object
* [ati/ljsm](https://github.com/ati/ljsm) - perl script for LiveJournal blog backup
* [aesuli/Amazon-downloader](https://github.com/aesuli/Amazon-downloader) - Two perl scripts to download and parse Amazon's reviews
* [spezifanta/SteamCalculator-Scripts](https://github.com/spezifanta/SteamCalculator-Scripts) - Perl scripts, which parses the Valve's Steam store.
* [motemen/Wight](https://github.com/motemen/Wight) - Communicate with PhantomJS in Perl (Capybara+Poltergeist to Perl)
* [Corion/www-mechanize-firefox](https://github.com/Corion/www-mechanize-firefox) - The API of WWW::Mechanize, combined with the Javascript-power of Firefox
* [Corion/WWW-Mechanize-Chrome](https://github.com/Corion/WWW-Mechanize-Chrome) - automate the Chrome browser
* [pkrumins/social-scraper](https://github.com/pkrumins/social-scraper) - Social scraper is a Perl program that scrapes reddit, digg, stumbleupon, delicious, furl, flickr, simpy, boingboing, wired for content that matches the given patterns.
* [teodesian/playwright-perl](https://github.com/teodesian/playwright-perl) - Perl bindings for playwright
* [david-dick/firefox-marionette](https://github.com/david-dick/firefox-marionette) - This is a client module to automate the Mozilla Firefox browser via the Marionette protocol
* [fayland/perl-www-contact](https://github.com/fayland/perl-www-contact) - WWW::Contact - Get contacts/addressbook from Web

## Data and Storage

### Database Clients and ORMs

* [sqitchers/sqitch](https://github.com/sqitchers/sqitch) - Sensible database change management
* [percona/percona-toolkit](https://github.com/percona/percona-toolkit) - Percona Toolkit: a collection of advanced open source command-line tools.
* [darold/ora2pg](https://github.com/darold/ora2pg) - Ora2Pg is a free tool used to migrate an Oracle database to a PostgreSQL compatible schema. It connects your Oracle database, scan it automatically and extracts its structure or data, it then generates SQL scripts that you can load into PostgreSQL.
* [dalibo/sqlserver2pgsql](https://github.com/dalibo/sqlserver2pgsql) - Migration tool to convert a Microsoft SQL Server Database into a PostgreSQL database, as automatically as possible
* [steve0511/resty-redis-cluster](https://github.com/steve0511/resty-redis-cluster) - Openresty lua client for redis cluster.
* [dataegret/pgcompacttable](https://github.com/dataegret/pgcompacttable)
* [mla/pg_sample](https://github.com/mla/pg_sample) - PostgreSQL utility for creating a small, sample database from a larger one
* [hackmysql/archive](https://github.com/hackmysql/archive) - Deprecated tools from HackMySQL.com
* [mongodb-labs/mongo-perl-driver](https://github.com/mongodb-labs/mongo-perl-driver) - Perl driver for the MongoDB *(archived)*
* [cbbrowne/autodoc](https://github.com/cbbrowne/autodoc) - PostgreSQL Autodoc - dumps a Postgres schema in several useful documentary forms
* [Perl5/DBIx-Class](https://github.com/Perl5/DBIx-Class) - GitHub side of the DBIx::Class ( DBIC ) repository
* [vision5/ngx_mongo](https://github.com/vision5/ngx_mongo) - Non-blocking upstream module for Nginx to connect to MongoDB
* [aspiers/mysqldiff](https://github.com/aspiers/mysqldiff) - tool and CPAN suite backend for comparing MySQL database schemas
* [ewaters/altsql-shell](https://github.com/ewaters/altsql-shell) - An easily extensible DBI shell, perfect for a drop-in replacement to mysql-client
* [PerlRedis/perl-redis](https://github.com/PerlRedis/perl-redis) - Perl binding for Redis database
* [cuiweixie/lua-resty-redis-cluster](https://github.com/cuiweixie/lua-resty-redis-cluster) - a openresty redis cluster client
* [mojolicious/mojo-pg](https://github.com/mojolicious/mojo-pg) - Mojolicious :heart: PostgreSQL
* [perl5-dbi/dbi](https://github.com/perl5-dbi/dbi) - DBI - The Perl 5 Database Interface
* [elastic/elasticsearch-perl](https://github.com/elastic/elasticsearch-perl) - Official Perl low-level client for Elasticsearch.
* [nekokak/p5-Teng](https://github.com/nekokak/p5-Teng) - simple DBI wrapper/ORMapper
* [elliotchance/mbzdb](https://github.com/elliotchance/mbzdb) - 🎵 Port of the MusicBrainz database to run on other RDBMSs with replication (previously named MB_MySQL.) *(archived)*
* [dbsrgits/sql-translator](https://github.com/dbsrgits/sql-translator) - SQL::Translator (SQLFairy)
* [kraih/mango](https://github.com/kraih/mango) - :see_no_evil: Pure-Perl non-blocking I/O MongoDB driver *(archived)*
* [perl5-dbi/DBD-mysql](https://github.com/perl5-dbi/DBD-mysql) - MySQL driver for the Perl5 Database Interface (DBI)
* [bucardo/dbdpg](https://github.com/bucardo/dbdpg) - Perl Postgres driver DBD::Pg aka dbdpg
* [libwww-perl/URI-db](https://github.com/libwww-perl/URI-db) - Perl module representing database URIs
* [OpensourceICTSolutions/zabbix-mysql-partitioning-perl](https://github.com/OpensourceICTSolutions/zabbix-mysql-partitioning-perl) - This script is a script written in Perl to partition the Zabbix database tables in time based chunks. We can use this script to replace the Zabbix housekeeper process which tends to get too slow once you hit a certain database size.
* [ap/DBIx-Connector](https://github.com/ap/DBIx-Connector) - Fast, safe DBI connection and transaction management
* [perl5-dbi/DBD-MariaDB](https://github.com/perl5-dbi/DBD-MariaDB) - Perl MariaDB driver
* [bigpresh/Dancer-Plugin-Database](https://github.com/bigpresh/Dancer-Plugin-Database) - Dancer::Plugin::Database - easy database support for Dancer applications
* [karupanerura/Aniki](https://github.com/karupanerura/Aniki) - The ORM as our great brother.
* [bigpresh/Dancer-Plugin-SimpleCRUD](https://github.com/bigpresh/Dancer-Plugin-SimpleCRUD) - Quick and effortless CRUD (create/read/update/delete) operations based on database tables
* [dpavlin/perl-Redis-obsolete](https://github.com/dpavlin/perl-Redis-obsolete) - perl binding for Redis database - latest development is in melo's repository
* [societe-generale/code2pg](https://github.com/societe-generale/code2pg) - Tool to help migrate application code from Oracle to PostgreSQL
* [perl5-dbi/DBD-Oracle](https://github.com/perl5-dbi/DBD-Oracle) - Oracle database driver for the DBI module
* [nnthnn/perl-rethinkdb](https://github.com/nnthnn/perl-rethinkdb) - A Pure Perl RethinkDB Driver *(archived)*
* [p5-RedisDB/RedisDB](https://github.com/p5-RedisDB/RedisDB) - Perl extension to access Redis
* [mkjellman/perlcassa](https://github.com/mkjellman/perlcassa) - a Perl client for Apache Cassandra

### Serialization and Formats

* [mvz/email-outlook-message-perl](https://github.com/mvz/email-outlook-message-perl) - Email::Outlook::Message Perl module for reading Outlook .msg files
* [dkogan/vnlog](https://github.com/dkogan/vnlog) - Process labelled tabular ASCII data using normal UNIX tools
* [leolovenet/qqwry2mmdb](https://github.com/leolovenet/qqwry2mmdb) - 为 Wireshark 能使用纯真网络 IP 数据库(QQwry)而提供的格式转换工具
* [jmcnamara/excel-writer-xlsx](https://github.com/jmcnamara/excel-writer-xlsx) - Perl module to create Excel XLSX files.
* [yaml/yaml-grammar](https://github.com/yaml/yaml-grammar)
* [sisimai/p5-sisimai](https://github.com/sisimai/p5-sisimai) - Mail Analyzing Interface for email bounce: A Perl module to parse RFC5322 bounce mails and generating structured data as JSON from parsed results. Formerly known as bounceHammer 4: an error mail analyzer.
* [maxmind/MaxMind-DB-Writer-perl](https://github.com/maxmind/MaxMind-DB-Writer-perl) - Create MaxMind DB database files *(archived)*
* [mrihtar/Garmin-FIT](https://github.com/mrihtar/Garmin-FIT) - Perl code for reading and conversion of Garmin FIT binary files
* [msgpack/msgpack-perl](https://github.com/msgpack/msgpack-perl) - MessagePack serializer implementation for Perl / msgpack.org[Perl]
* [makamaka/JSON](https://github.com/makamaka/JSON) - perl implementation of JSON encoder/decoder
* [rurban/Cpanel-JSON-XS](https://github.com/rurban/Cpanel-JSON-XS) - Improved fork of JSON-XS
* [jmcnamara/spreadsheet-writeexcel](https://github.com/jmcnamara/spreadsheet-writeexcel) - Perl module to write Excel binary files
* [mirod/xmltwig](https://github.com/mirod/xmltwig) - XML, the Perl way
* [miyagawa/xml-atom](https://github.com/miyagawa/xml-atom) - XML::Atom perl module
* [pjcj/Gedcom.pm](https://github.com/pjcj/Gedcom.pm) - Gedcom - a Perl module to manipulate Gedcom genealogy files
* [perlpunk/YAML-PP-p5](https://github.com/perlpunk/YAML-PP-p5) - A YAML 1.2 processor in perl
* [kasei/perlrdf](https://github.com/kasei/perlrdf) - Deprecated in favor of the Attean package
* [zigorou/perl-JSV](https://github.com/zigorou/perl-JSV) - JSON Schema implementation for Perl
* [makamaka/JSON-PP](https://github.com/makamaka/JSON-PP) - JSON::PP for perl core module
* [masukomi/jsonpath-perl](https://github.com/masukomi/jsonpath-perl) - Perl port of JSONPath *(archived)*
* [ingydotnet/yaml-pm](https://github.com/ingydotnet/yaml-pm) - YAML Perl Module
* [ranguard/text-vcard](https://github.com/ranguard/text-vcard) - Perl package to edit and create vCard(s) (RFC 2426)
* [naoya/perl-Text-LTSV](https://github.com/naoya/perl-Text-LTSV) - Text::LTSV - Labeled Tab Separated Value manipulator
* [sid5432/pubOTDR](https://github.com/sid5432/pubOTDR) - Simple OTDR SOR file parser (Perl)
* [marcschwartz/WriteXLS](https://github.com/marcschwartz/WriteXLS) - CRAN Package WriteXLS: Cross-platform Perl based R function to create Excel 2003 (XLS) and Excel 2007 (XLSX) files from one or more data frames. Each data frame will be written to a separate named worksheet in the Excel spreadsheet. The worksheet name will be the name of the data frame it contains or can be specified by the user.

### Caching and Queues

* [thibaultcha/lua-resty-mlcache](https://github.com/thibaultcha/lua-resty-mlcache) - Layered caching library for OpenResty
* [mojolicious/minion](https://github.com/mojolicious/minion) - :octopus: Perl high performance job queue
* [kni/redis-sharding](https://github.com/kni/redis-sharding) - Redis Sharding is a multiplexed proxy-server, designed to work with the database divided to several servers. It's a temporary substitution of Redis Cluster that is under development.
* [TrackingSoft/Kafka](https://github.com/TrackingSoft/Kafka) - Perl implementation of Kafka API (official CPAN module)
* [diegok/resque-perl](https://github.com/diegok/resque-perl) - Perl port of the original Ruby library. It's intended to work using the same backend to share tasks and be able to manage the system using ruby's resque-server webapp. Resque is a Redis-backed library for creating background jobs, placing them on multiple queues, and processing them later.
* [jonswar/perl-chi](https://github.com/jonswar/perl-chi) - Perl CHI distribution
* [cooldaemon/RabbitFoot](https://github.com/cooldaemon/RabbitFoot) - An asynchronous and multi channel Perl AMQP client. It uses Coro and AnyEvent::RabbitMQ.
* [ewaters/net-amqp](https://github.com/ewaters/net-amqp) - Implementation of the AMQ Protocol in Perl
* [memcached/perl-Cache-Memcached](https://github.com/memcached/perl-Cache-Memcached) - Cache::Memcached
* [net-amqp-rabbitmq/net-amqp-rabbitmq](https://github.com/net-amqp-rabbitmq/net-amqp-rabbitmq) - Perl bindings to the librabbitmq-c AMQP library.
* [shogo82148/Redis-Fast](https://github.com/shogo82148/Redis-Fast) - fast perl binding for Redis database
* [cooldaemon/AnyEvent-RabbitMQ](https://github.com/cooldaemon/AnyEvent-RabbitMQ) - An asynchronous and multi channel Perl AMQP client.

## Machine Learning and AI

### Natural Language Processing

* [ciprian-chelba/1-billion-word-language-modeling-benchmark](https://github.com/ciprian-chelba/1-billion-word-language-modeling-benchmark) - Formerly known as code.google.com/p/1-billion-word-language-modeling-benchmark
* [ko-ichi-h/khcoder](https://github.com/ko-ichi-h/khcoder) - KH Coder: for Quantitative Content Analysis or Text Mining
* [zaf/asterisk-speech-recog](https://github.com/zaf/asterisk-speech-recog) - Speech recognition script for Asterisk that uses google's speech engine.
* [isi-nlp/uroman](https://github.com/isi-nlp/uroman) - Universal Romanizer that can convert any unicode script to roman (latin) script
* [zaf/asterisk-googletts](https://github.com/zaf/asterisk-googletts) - Asterisk AGI script that uses Google's translate text to speech service.
* [UniversalDependencies/tools](https://github.com/UniversalDependencies/tools) - Various utilities for processing the data.
* [strubell/LISA](https://github.com/strubell/LISA) - Linguistically-Informed Self-Attention implemented in TensorFlow
* [pltrdy/files2rouge](https://github.com/pltrdy/files2rouge) - Calculating ROUGE score between two files (line-by-line)
* [shayneobrien/coreference-resolution](https://github.com/shayneobrien/coreference-resolution) - Efficient and clean PyTorch reimplementation of "End-to-end Neural Coreference Resolution" (Lee et al., EMNLP 2017).
* [tagucci/pythonrouge](https://github.com/tagucci/pythonrouge) - Python wrapper for evaluating summarization quality by ROUGE package
* [knmnyn/ParsCit](https://github.com/knmnyn/ParsCit) - An open-source CRF Reference String Parsing Package
* [diegoantognini/py-rouge](https://github.com/diegoantognini/py-rouge) - Full Python implementation of the ROUGE metric, producing same results as in the official perl implementation.
* [lil-lab/newsroom](https://github.com/lil-lab/newsroom) - Tools for downloading and analyzing summaries and evaluating summarization systems. https://summari.es/
* [jefflai108/pytorch-kaldi-neural-speaker-embeddings](https://github.com/jefflai108/pytorch-kaldi-neural-speaker-embeddings) - A light weight neural speaker embeddings extraction based on Kaldi and PyTorch.
* [ShomyLiu/pytorch-pcnn](https://github.com/ShomyLiu/pytorch-pcnn) - supervised relation extraction for PCNN (Zeng 2014) in pytorch 关系抽取
* [bckim92/language-evaluation](https://github.com/bckim92/language-evaluation) - :clipboard: Collection of evaluation code for natural language generation.
* [g0v/moedict-data-csld](https://github.com/g0v/moedict-data-csld) - 中華大辭典
* [nassosoassos/sail_align](https://github.com/nassosoassos/sail_align) - SailAlign is an open-source software toolkit for robust long speech-text alignment implementing an adaptive, iterative speech recognition and text alignment scheme that allows for the processing of very long (and possibly noisy) audio and is robust to transcription errors. It is mainly written as a perl library but its functionality also depends on freely available software, namely HTK, srilm and sclite.
* [julius-speech/segmentation-kit](https://github.com/julius-speech/segmentation-kit) - Speech Segmentation Toolkit using Julius
* [zamiron/ru4sphinx](https://github.com/zamiron/ru4sphinx) - Creating Russian voice model for cmu-sphinx
* [g0v/moedict-data-twblg](https://github.com/g0v/moedict-data-twblg) - 臺灣閩南語常用詞辭典 資料檔
* [UniversalDependencies/UD_Russian-SynTagRus](https://github.com/UniversalDependencies/UD_Russian-SynTagRus) - Russian data from the SynTagRus corpus.
* [conll/reference-coreference-scorers](https://github.com/conll/reference-coreference-scorers) - This is the reference implementation of commonly used coreference metrics.
* [laurieburchell/open-lid-dataset](https://github.com/laurieburchell/open-lid-dataset) - Repository accompanying "An Open Dataset and Model for Language Identification" (Burchell et al., 2023)
* [Sundy1219/eesen-for-thchs30](https://github.com/Sundy1219/eesen-for-thchs30) - ASR for Chinese Mandarin
* [elsevierlabs/OA-STM-Corpus](https://github.com/elsevierlabs/OA-STM-Corpus) - Corpus of Open Access articles from multiple fields in Science, Technology, and Medicine.

### Data Science and Analytics

* [dkogan/feedgnuplot](https://github.com/dkogan/feedgnuplot) - Tool to plot realtime and stored data from the commandline, using gnuplot.
* [LibreCat/Catmandu](https://github.com/LibreCat/Catmandu) - Catmandu - a data processing toolkit
* [synacor/dtk](https://github.com/synacor/dtk) - DTK (data toolkit) is a suite of tools for parsing, analyzing, and graphing logs and other datasets.
* [spencertipping/nfu](https://github.com/spencertipping/nfu) - Numeric Fu for the command line
* [EntropyOrg/p5-Devel-IPerl](https://github.com/EntropyOrg/p5-Devel-IPerl) - :microscope::books: Perl5 language kernel for Jupyter <http://jupyter.org/>
* [raphael-susewind/india-religion-politics](https://github.com/raphael-susewind/india-religion-politics) - Data on religion and politics in India
* [vigsterkr/circos](https://github.com/vigsterkr/circos) - Circos is a software package for visualizing data and information. It visualizes data in a circular layout — this makes Circos ideal for exploring relationships between objects or positions.
* [spencertipping/ni](https://github.com/spencertipping/ni) - Say "ni" to data of any size
* [zrlram/afterglow](https://github.com/zrlram/afterglow) - graph visualization tool
* [gphat/chart-clicker](https://github.com/gphat/chart-clicker) - Extensible, Beautiful Charts for Perl *(archived)*
* [kruser/atbat-mongodb](https://github.com/kruser/atbat-mongodb) - A Perl project that pulls data from MLB's AtBat servers and shoves them into a local MongoDB

## Networking and Distributed

### Networking

* [ddclient/ddclient](https://github.com/ddclient/ddclient) - ddclient updates dynamic DNS entries for accounts on a wide range of dynamic DNS services.
* [adrienverge/openfortivpn](https://github.com/adrienverge/openfortivpn) - Client for PPP+TLS VPN tunnel services
* [htrgouvea/nipe](https://github.com/htrgouvea/nipe) - An engine to make Tor network your default gateway
* [jetmore/swaks](https://github.com/jetmore/swaks) - Swaks - Swiss Army Knife for SMTP
* [arboliva/AirChat](https://github.com/arboliva/AirChat) - Free Communications For Everyone.
* [Lochnair/vyatta-wireguard](https://github.com/Lochnair/vyatta-wireguard) - *(archived)*
* [kjokjo/ipcalc](https://github.com/kjokjo/ipcalc)
* [jbittel/httpry](https://github.com/jbittel/httpry) - HTTP logging and information retrieval tool
* [zonemaster/zonemaster](https://github.com/zonemaster/zonemaster) - The Zonemaster Project
* [jpoliv/wakeonlan](https://github.com/jpoliv/wakeonlan) - Perl script for waking up computers via Wake-On-LAN magic packets
* [wisdomfusion/qqwry.dat](https://github.com/wisdomfusion/qqwry.dat) - 纯真IP地址数据库镜像，mirror of qqwry.dat
* [atomia/atomiadns](https://github.com/atomia/atomiadns) - Atomia DNS
* [toreanderson/clatd](https://github.com/toreanderson/clatd) - A 464XLAT CLAT implementation for Linux
* [abh/ntppool](https://github.com/abh/ntppool) - NTP Pool Project
* [hamishforbes/lua-resty-iputils](https://github.com/hamishforbes/lua-resty-iputils) - Utility functions for working with IP addresses in Openresty
* [mogaal/sendemail](https://github.com/mogaal/sendemail) - lightweight, command line SMTP email client
* [jimsalterjrs/network-testing](https://github.com/jimsalterjrs/network-testing) - This is a small collection of GPLv3-licensed tools to assist an intrepid researcher in testing the performance of networks, wired or wireless.
* [mludvig/smtp-cli](https://github.com/mludvig/smtp-cli) - The ultimate command line SMTP client
* [NicTool/NicTool](https://github.com/NicTool/NicTool) - NicTool: a DNS management solution
* [jmapio/jmap-perl](https://github.com/jmapio/jmap-perl) - JMAP Proxy implemented in Perl
* [rghose/kill-close-wait-connections](https://github.com/rghose/kill-close-wait-connections) - Kills all TCP CLOSE_WAIT connections
* [smtpd/qpsmtpd](https://github.com/smtpd/qpsmtpd) - qpsmtpd is a flexible smtpd daemon written in Perl
* [sourceperl/mbtget](https://github.com/sourceperl/mbtget) - A simple Modbus/TCP client write in pure Perl.
* [andygrundman/tailscale-wakeonlan](https://github.com/andygrundman/tailscale-wakeonlan) - Wake your LAN devices from any device on your tailnet
* [gbxyz/unbound-block-hosts](https://github.com/gbxyz/unbound-block-hosts) - a script to convert Dan Pollock's ad blocking hosts file into Unbound local-data. *(archived)*
* [dyne/gitzone](https://github.com/dyne/gitzone) - git-based zone management tool for static and dynamic domains
* [ryancdotorg/ssh-chain](https://github.com/ryancdotorg/ssh-chain) - *(archived)*
* [kirei/fpdns](https://github.com/kirei/fpdns) - Net::DNS::Fingerprint *(archived)*
* [aprsorg/aprs-deviceid](https://github.com/aprsorg/aprs-deviceid) - APRS device identification data: tocalls.txt + mic-e-types.txt current primary allocations (YAML, JSON, XML)
* [staskobzar/cisco_prov](https://github.com/staskobzar/cisco_prov) - Cisco SCCP and SIP provisioning configuration examples and firmare
* [pkolano/ballast](https://github.com/pkolano/ballast) - Lightweight SSH load balancer supporting user-specific selection policies
* [britannic/ubnt-bcast-relay](https://github.com/britannic/ubnt-bcast-relay) - UDP Packet Broadcast Relay, integrated with EdgeOS CLI
* [vti/pocketio](https://github.com/vti/pocketio) - SocketIO PSGI App
* [philpennock/sieve-connect](https://github.com/philpennock/sieve-connect) - A client for the MANAGESIEVE Protocol
* [stickster/irssi-libnotify](https://github.com/stickster/irssi-libnotify) - Automatically exported from code.google.com/p/irssi-libnotify
* [djabberd/DJabberd](https://github.com/djabberd/DJabberd) - The main DJabberd source
* [samm-git/jvpn](https://github.com/samm-git/jvpn) - Perl script to connect to the Juniper VPN with Host Checker enabled
* [skx/dhcp.io](https://github.com/skx/dhcp.io) - Dynamic DNS - Via Redis, Perl, and Amazon Route53. *(archived)*
* [pkrumins/perl-tcp-proxy](https://github.com/pkrumins/perl-tcp-proxy) - A simple TCP proxy written in Perl. Uses IO::Socket::INET and IO::Select for multiplexing.
* [dpavlin/perl-cwmp](https://github.com/dpavlin/perl-cwmp) - Perl ACS server implementing CWMP protocol to manage CPE clients
* [rjbs/Email-Sender](https://github.com/rjbs/Email-Sender) - a perl library for sending email
* [rfc1036/rpsltool](https://github.com/rfc1036/rpsltool) - A multi-target BGP configurations generator
* [KD8EYF/TRBO-NET](https://github.com/KD8EYF/TRBO-NET) - mototrbo perl modules for ARS TMS and LRRP
* [vladak/ipv6gen](https://github.com/vladak/ipv6gen) - IPv6 prefix generator
* [rfc1036/kit-censura](https://github.com/rfc1036/kit-censura) - Software used to censor the Internet in Italy
* [abh/pgeodns](https://github.com/abh/pgeodns) - Geographic Perl Nameserver
* [AMS-IX/arpsponge](https://github.com/AMS-IX/arpsponge) - AMS-IX ARPsponge Project
* [zhou0/shadowsocks-perl](https://github.com/zhou0/shadowsocks-perl) - An asynchronous, non-blocking shadowsocks client and server written in Perl.
* [netdisco/snmp-info](https://github.com/netdisco/snmp-info) - SNMP::Info - Perl Interface to Network devices and MIBs through SNMP
* [noxxi/p5-io-socket-ssl](https://github.com/noxxi/p5-io-socket-ssl) - IO::Socket::SSL Perl Module
* [ImKKingshuk/USBoverSSH](https://github.com/ImKKingshuk/USBoverSSH) - USBoverSSH - Seamlessly Connect USB Devices Over SSH! 🚀✨ Leverage the power of USBoverSSH to establish secure connections between USB devices and remote hosts. Effortlessly bridge the gap between local and remote USB devices, ensuring smooth communication over SSH. 🌐🔒 Embark on a journey of secure USB connectivity with USBoverSSH.
* [robinbowes/net-udap](https://github.com/robinbowes/net-udap) - Net::UDAP is a Perl module to configure the Logitech SqueezeBox Receiver (SBR) from a PC, i.e. without requiring a SqueezeBox Controller (SBC) *(archived)*
* [njh/perl-net-sdp](https://github.com/njh/perl-net-sdp) - Perl Module : Session Description Protocol (rfc2327)
* [semifor/twirc](https://github.com/semifor/twirc) - Twitter / IRC gateway in perl *(archived)*
* [salva/p5-Net-OpenSSH](https://github.com/salva/p5-Net-OpenSSH) - Perl SSH client built on top of OpenSSH
* [KKBOX/mpdnsd-perl](https://github.com/KKBOX/mpdnsd-perl) - Marco Polo DNS Daemon
* [proxmox/pve-firewall](https://github.com/proxmox/pve-firewall) - Firewall test scripts
* [perl-ldap/perl-ldap](https://github.com/perl-ldap/perl-ldap) - Perl LDAP client library
* [gbarr/perl-libnet](https://github.com/gbarr/perl-libnet) - perl libnet library *(archived)*
* [rkitover/net-ssh2](https://github.com/rkitover/net-ssh2) - Net::SSH2 perl module using libssh2
* [Juniper/netconf-perl](https://github.com/Juniper/netconf-perl) - Perl library for Netconf
* [abh/colobus](https://github.com/abh/colobus) - Perl NNTP server
* [vti/sockjs-perl](https://github.com/vti/sockjs-perl) - SockJS Perl Plack/PSGI implementation *(archived)*
* [beanz/xpl-perl](https://github.com/beanz/xpl-perl) - Perl modules for the xPL Home Automation Protocol

### RPC and Messaging

* [mogui/MDWamp](https://github.com/mogui/MDWamp) - MDWamp is a client side objective-C implementation of the WebSocket subprotocol WAMP.
* [lestrrat-p5/ZMQ](https://github.com/lestrrat-p5/ZMQ) - libzmq Perl binding
* [tsee/ZeroMQ-Perl](https://github.com/tsee/ZeroMQ-Perl) - Perl interface to 0MQ2
* [joyrex2001/grpc-perl](https://github.com/joyrex2001/grpc-perl) - Perl 5 implementation of gRPC using the official gRPC shared library.
* [rjray/rpc-xml](https://github.com/rjray/rpc-xml) - A Perl implementation of the XML-RPC specification
* [zeromq/perlzmq](https://github.com/zeromq/perlzmq) - version agnostic Perl bindings for zeromq

### Distributed Systems

* [yoshinorim/mha4mysql-manager](https://github.com/yoshinorim/mha4mysql-manager) - Development tree of Master High Availability Manager and tools for MySQL (MHA), Manager part
* [bucardo/bucardo](https://github.com/bucardo/bucardo) - Bucardo multimaster and master/slave Postgres replication
* [yoshinorim/mha4mysql-node](https://github.com/yoshinorim/mha4mysql-node) - Development tree of Master High Availability Manager and tools for MySQL (MHA), Node (MySQL Server) part
* [ClusterLabs/PAF](https://github.com/ClusterLabs/PAF) - PostgreSQL Automatic Failover: High-Availibility for Postgres, based on Pacemaker and Corosync.
* [stf-storage/stf](https://github.com/stf-storage/stf) - STF - Distributed Object Storage (Perl/MySQL/(Q4M|TheSchwartz|Resque|Redis)/Memcached)
* [kentaro/serf-hosts](https://github.com/kentaro/serf-hosts)
* [mtve/yazecminer](https://github.com/mtve/yazecminer) - yet another ZEC miner
* [cosimo/TicketServer](https://github.com/cosimo/TicketServer) - Flickr-like Ticket Server implemented with Perl + DBI + MySQL
* [proxmox/pve-ha-manager](https://github.com/proxmox/pve-ha-manager) - Proxmox VE High Availabillity Manager - read-only source mirror

### Cloud and Infrastructure

* [lamw/vmware-scripts](https://github.com/lamw/vmware-scripts) - Various scripts for VMware based solutions
* [git-deploy/git-deploy](https://github.com/git-deploy/git-deploy) - Tool to manage using git as a deployment management tool
* [RexOps/Rex](https://github.com/RexOps/Rex) - Rex, the friendly automation framework
* [UPC/ravada](https://github.com/UPC/ravada) - Remote Virtual Desktops Manager
* [docker-library/repo-info](https://github.com/docker-library/repo-info) - Extended information (especially license and layer details) about the published Official Images
* [linode/cli](https://github.com/linode/cli) - This is the DEPRECATED Linode CLI. Use https://github.com/linode/linode-cli *(archived)*
* [timkay/aws](https://github.com/timkay/aws) - Easy command line access to Amazon EC2, S3, SQS, ELB, and SDB
* [alestic/ec2-consistent-snapshot](https://github.com/alestic/ec2-consistent-snapshot) - [SUNSET] Initiate consistent EBS snapshots in Amazon EC2
* [Cyclenerd/google-cloud-compute-machine-types](https://github.com/Cyclenerd/google-cloud-compute-machine-types) - ☁️ Choose the optimal Google Compute Engine machine type or instance in the many Google Cloud Platform regions
* [xcat2/xcat-core](https://github.com/xcat2/xcat-core) - Code repo for xCAT core packages
* [dlandon/zoneminder.machine.learning](https://github.com/dlandon/zoneminder.machine.learning) - Zoneminder Docker *(archived)*
* [proxmox/qemu-server](https://github.com/proxmox/qemu-server) - Proxmox VE's Virtual Machine Manager
* [Cyclenerd/google-cloud-pricing-cost-calculator](https://github.com/Cyclenerd/google-cloud-pricing-cost-calculator) - 💸 Calculate estimated monthly costs of Google Cloud Platform products and resources via YAML files and CLI program (Linux, macOS, Windows)
* [Flipkart/HostDB](https://github.com/Flipkart/HostDB) - HostDB: a new tool to help manage data center inventory and write applications around it.
* [pplu/aws-sdk-perl](https://github.com/pplu/aws-sdk-perl) - A community AWS SDK for Perl Programmers
* [xbgmsharp/ipxe-buildweb](https://github.com/xbgmsharp/ipxe-buildweb) - iPXE Prebuilt binary web interface
* [dreamcat4/docker-images](https://github.com/dreamcat4/docker-images) - Dreamcat4's Docker Images (Trusted Builds)
* [boomshankerx/proxmox-truenas](https://github.com/boomshankerx/proxmox-truenas) - TrueNAS over iSCSI for Proxmox VE
* [OSInside/kiwi-legacy](https://github.com/OSInside/kiwi-legacy) - KIWI - Appliance Builder (legacy please read deprecation notice) *(archived)*
* [apenwarr/gitbuilder](https://github.com/apenwarr/gitbuilder) - Auto-builds and tests all the branches of your git projects, showing pass/fail results on a web page/RSS feed. Isolates failures to the first commit that caused the problem.
* [jsierles/chef_cookbooks_deprecated](https://github.com/jsierles/chef_cookbooks_deprecated) - Opinionated chef recipes for Ubuntu/Debian. Manage nginx, unicorn, UNIX user accounts, postgresql, and more!
* [hamishforbes/lua-resty-consul](https://github.com/hamishforbes/lua-resty-consul) - Library to interface with the consul HTTP API from ngx_lua
* [cloudflarearchive/Cloudflare-Tools](https://github.com/cloudflarearchive/Cloudflare-Tools) - Tools which enable you to get the full benefit of using the Cloudflare service.
* [iosifpeterfi/schnellnode-pve-ha-manager](https://github.com/iosifpeterfi/schnellnode-pve-ha-manager)
* [warewulf/warewulf3](https://github.com/warewulf/warewulf3) - Warewulf is a scalable systems management suite originally developed to manage large high-performance Linux clusters.
* [alestic/ec2-expire-snapshots](https://github.com/alestic/ec2-expire-snapshots) - Delete expired EBS snapshots in Amazon EC2. Install on Ubuntu with: sudo add-apt-repository -y ppa:alestic && sudo apt-get update && sudo apt-get install -y ec2-expire-snapshots
* [dave-lang/webmin-docker](https://github.com/dave-lang/webmin-docker) - Docker module for Webmin
* [shogo82148/actions-setup-perl](https://github.com/shogo82148/actions-setup-perl) - Setup Perl environment Action
* [vaskozl/home-infra](https://github.com/vaskozl/home-infra) - My home Kubernetes cluster
* [CircleCI-Archived/dockerfile-wizard](https://github.com/CircleCI-Archived/dockerfile-wizard) - Use CircleCI to build custom Docker images with combinations of common languages/dependencies *(archived)*
* [ibm-cloud-architecture/refarch-privatecloud](https://github.com/ibm-cloud-architecture/refarch-privatecloud) - This project provides guidance on how to deploy IBM Private Cloud
* [thoughtpolice/eris](https://github.com/thoughtpolice/eris) - Serve your /nix/store directory over the internet :sparkles:
* [Netflix-Skunkworks/jenkins-cli](https://github.com/Netflix-Skunkworks/jenkins-cli) - Simple Jenkins Command Line Interface
* [plone/ansible-playbook](https://github.com/plone/ansible-playbook) - An Ansible playbook for automated deployment of full-stack Plone servers.
* [proxmox/pve-common](https://github.com/proxmox/pve-common) - Proxmox Project's Common Perl Code
* [pplu/aws-map](https://github.com/pplu/aws-map) - Make a network graph of an AWS region
* [openresty/opsboy](https://github.com/openresty/opsboy) - A rule-based sysadmin tool that helps setting up complex environment for blank machines
* [wtsi-hgi/docker-proxify](https://github.com/wtsi-hgi/docker-proxify) - Allows building and running docker container images from behind a corporate proxy
* [kentaro/cinnamon](https://github.com/kentaro/cinnamon) - a simple deploy tool
* [cfengine/design-center](https://github.com/cfengine/design-center) - CFEngine community-contributed content *(archived)*
* [proxmox/pve-container](https://github.com/proxmox/pve-container) - Proxmox VE container manager & runtime - read-only mirror
* [xen-tools/xen-tools](https://github.com/xen-tools/xen-tools) - xen-tools is a collection of simple perl scripts which allow you to easily create new Xen guest domains upon your Xen host server.
* [Perl/docker-perl-tester](https://github.com/Perl/docker-perl-tester) - Docker images with pre-installed test modules and test dependencies for CPAN modules
* [moznion/aws-lambda-perl5-layer](https://github.com/moznion/aws-lambda-perl5-layer) - Perl5 layer for AWS Lambda with runtime API
* [adriaandens/fagrant](https://github.com/adriaandens/fagrant) - Vagrant in 100 lines of (Perl) code
* [kubernetes-client/perl](https://github.com/kubernetes-client/perl) - Perl(5) client library for Kubernetes. Work In Progress.
* [shogo82148/p5-aws-lambda](https://github.com/shogo82148/p5-aws-lambda) - AWS Lambda Layer for Perl5
* [vmware-archive/vsphere-automation-sdk-perl](https://github.com/vmware-archive/vsphere-automation-sdk-perl) - [DEPRECATED] Please see README. Perl samples, language bindings, and API reference documentation for vSphere using the VMware REST API *(archived)*
* [acme/net-amazon-s3](https://github.com/acme/net-amazon-s3) - Use the Amazon S3 - Simple Storage Service from Perl
* [fujiwara/aswrap](https://github.com/fujiwara/aswrap) - AWS assume role credential wrapper
* [proxmox/dab](https://github.com/proxmox/dab) - Read-only mirror of the Proxmox Debian Appliance Builder (DAB)
* [wertarbyte/hetzner-robot-perl](https://github.com/wertarbyte/hetzner-robot-perl) - Perl module and command line tool for control over the Hetzner robot

### Monitoring and Observability

* [darold/pgbadger](https://github.com/darold/pgbadger) - A fast PostgreSQL Log Analyzer
* [munin-monitoring/munin](https://github.com/munin-monitoring/munin) - Main repository for munin master / node / plugins
* [oetiker/SmokePing](https://github.com/oetiker/SmokePing) - The Active Monitoring System
* [mikaku/Monitorix](https://github.com/mikaku/Monitorix) - Monitorix is a free, open source, lightweight system monitoring tool.
* [munin-monitoring/contrib](https://github.com/munin-monitoring/contrib) - Contributed stuff for munin (plugins, tools, etc...)
* [netdisco/netdisco](https://github.com/netdisco/netdisco) - A web-based network management tool.
* [innotop/innotop](https://github.com/innotop/innotop) - A realtime terminal-based top-like monitor for MySQL
* [bucardo/check_postgres](https://github.com/bucardo/check_postgres) - Nagios check_postgres plugin for checking status of PostgreSQL databases
* [percona/pg_stat_monitor](https://github.com/percona/pg_stat_monitor) - Query Performance Monitoring Tool for PostgreSQL
* [glpi-project/glpi-agent](https://github.com/glpi-project/glpi-agent) - GLPI Agent
* [sni/thruk](https://github.com/sni/thruk) - Thruk is a multibackend monitoring webinterface for Naemon, Nagios, Icinga and Shinken using the Livestatus API.
* [eldy/AWStats](https://github.com/eldy/AWStats) - AWStats Log Analyzer project (official sources)
* [darold/pgcluu](https://github.com/darold/pgcluu) - PostgreSQL Cluster performances monitoring and auditing tool
* [centreon/centreon-plugins](https://github.com/centreon/centreon-plugins) - Collection of standard plugins to discover and gather cloud-to-edge metrics and status across your whole IT infrastructure.
* [linode/longview](https://github.com/linode/longview) - Linode Longview Agent *(archived)*
* [oetiker/mrtg](https://github.com/oetiker/mrtg) - MRTG - Multi Router Traffic Grapher
* [fusioninventory/fusioninventory-agent](https://github.com/fusioninventory/fusioninventory-agent) - FusionInventory Agent
* [httpdss/collectd-web](https://github.com/httpdss/collectd-web) - Modern, customizable web frontend for Collectd. Visualize system metrics through a responsive dashboard, deploy in minutes with the standalone Python server, or plug into Apache/Nginx. A drop-in replacement for Collectd's bundled UI.
* [v-zhuravlev/zbx-smartctl](https://github.com/v-zhuravlev/zbx-smartctl) - Templates and scripts for monitoring disks health with Zabbix and smartmontools
* [zabbix-tools/mib2zabbix](https://github.com/zabbix-tools/mib2zabbix) - SNMP Template generator for Zabbix
* [cvicente/Netdot](https://github.com/cvicente/Netdot) - Network Documentation Tool
* [kazeburo/GrowthForecast](https://github.com/kazeburo/GrowthForecast) - Lightning Fast Graphing/Visualization
* [fastmail/towncrier](https://github.com/fastmail/towncrier) - A status dashboard *(archived)*
* [mcholste/elsa](https://github.com/mcholste/elsa) - Enterprise Log Search and Archive
* [dockerana/dockerana](https://github.com/dockerana/dockerana) - Docker Monitoring with support for Grafana and Graphite
* [manuelkasper/AS-Stats](https://github.com/manuelkasper/AS-Stats) - A simple tool to generate per-AS traffic graphs from NetFlow/sFlow records
* [nagios-plugins-rabbitmq/nagios-plugins-rabbitmq](https://github.com/nagios-plugins-rabbitmq/nagios-plugins-rabbitmq) - A set of nagios checks for RabbitMQ using the management interface
* [OPMDG/check_pgactivity](https://github.com/OPMDG/check_pgactivity) - Nagios remote agent
* [simple-evcorr/sec](https://github.com/simple-evcorr/sec) - Simple Event Correlator releases
* [Octopussy-Project/Octopussy](https://github.com/Octopussy-Project/Octopussy) - Octopussy - Open Source Log Management Solution
* [hirose31/redis-traffic-stats](https://github.com/hirose31/redis-traffic-stats) - Redis query analyzer for counting, traffic stats by command
* [kjellm/munin-mysql](https://github.com/kjellm/munin-mysql) - Improved MySQL Graphs for Munin
* [lausser/check_nwc_health](https://github.com/lausser/check_nwc_health) - nwc = network component. This plugin checks lots of aspects of routers, switches, wlan controllers, firewalls,.....
* [jzawodn/mytop](https://github.com/jzawodn/mytop) - a "top" clone for MySQL
* [ganglia/gmetric](https://github.com/ganglia/gmetric) - Repository of user-contributed gmetric scripts
* [kazeburo/cloudforecast](https://github.com/kazeburo/cloudforecast) - the server metrics gathering
* [oetiker/smokeping-3.x](https://github.com/oetiker/smokeping-3.x) - reengineered SmokePing, using Extopus as its frontend
* [glensc/nagios-plugin-check_raid](https://github.com/glensc/nagios-plugin-check_raid) - Nagios/Icinga/Sensu plugin to check current server's RAID status ⛺
* [librenms/librenms-agent](https://github.com/librenms/librenms-agent) - LibreNMS Agent & Scripts
* [joemiller/collectd-graphite](https://github.com/joemiller/collectd-graphite) - collectd plugin for sending data to graphite
* [darold/squidanalyzer](https://github.com/darold/squidanalyzer) - Squid Analyzer parses Squid proxy access log and reports general statistics about hits, bytes, users, networks, top URLs, and top second level domains. Statistic reports are oriented toward user and bandwidth control.
* [v-zhuravlev/zabbix-notify](https://github.com/v-zhuravlev/zabbix-notify) - Notify alarms from Zabbix to Slack Hipchat and PagerDuty *(archived)*
* [ClickHouse/pg_stat_ch](https://github.com/ClickHouse/pg_stat_ch)
* [BaldMansMojo/check_vmware_esx](https://github.com/BaldMansMojo/check_vmware_esx) - chech_vmware_esx Fork of check_vmware_api.pl
* [iamcal/Flickr-StatsD](https://github.com/iamcal/Flickr-StatsD) - Mirror of code.flickr.com: Flickr-StatsD
* [willixix/WL-NagiosPlugins](https://github.com/willixix/WL-NagiosPlugins) - Clone of naglio-plugins repository for those using old name
* [netdisco/netdisco-mibs](https://github.com/netdisco/netdisco-mibs) - Collection of SNMP MIB files included in Netdisco
* [perusio/nginx-munin](https://github.com/perusio/nginx-munin) - A set of plugins for monitoring nginx with Munin
* [jayjanssen/myq_gadgets](https://github.com/jayjanssen/myq_gadgets) - myq_gadgets is deprecated by myq-tools! *(archived)*
* [tjstein/php5-fpm-munin-plugins](https://github.com/tjstein/php5-fpm-munin-plugins) - A set of Munin plugins for PHP5-FPM
* [OCSInventory-NG/UnixAgent](https://github.com/OCSInventory-NG/UnixAgent) - This is the OCS unified agent for Unix operating systems
* [justintime/nagios-plugins](https://github.com/justintime/nagios-plugins) - Collection of some handy Nagios plugins
* [netrusov/ZabbixDBA](https://github.com/netrusov/ZabbixDBA) - Zabbix Database Monitoring Service (Oracle, Pg, MySQL, MS SQL, DB2, etc.)
* [netoptimizer/IPTV-Analyzer](https://github.com/netoptimizer/IPTV-Analyzer) - Fast MPEG2 Transport Stream Analyzer, based on Netfilter kernel module
* [dalibo/pgshark](https://github.com/dalibo/pgshark) - Messing with PostgreSQL network traffic to make some usefull things
* [aleksandr-oliferuk/pcap2squid](https://github.com/aleksandr-oliferuk/pcap2squid) - Recieve raw network trafic dump in pcap-format and parse it to squid-proxy log. Then generate report for lightsquid and shows it in Web UI
* [JeremyJones/Apachetop](https://github.com/JeremyJones/Apachetop) - Apachetop is a console-based tool for monitoring the threads and overall performance of a set of Apache web servers, using the server-status information pages in Apache.
* [noodba/myawr](https://github.com/noodba/myawr) - awr of MySQL
* [dheiland-r7/snmp](https://github.com/dheiland-r7/snmp) - SNMP data gather scripts
* [eculver/memcache-top](https://github.com/eculver/memcache-top) - "top" for memcache - watch the traffic and other stats in real-time. Yoikes. Forked from Nicholas Tang's Google Code project.
* [SteScho/manubulon-snmp](https://github.com/SteScho/manubulon-snmp) - Set of Icinga/Nagios plugins to check hosts and hardware with the SNMP protocol.
* [darold/sendmailanalyzer](https://github.com/darold/sendmailanalyzer) - Sendmail log Analyzer is a tool to monitor sendmail usage and generate HTML and graph reports. It reports all you ever wanted to know about email trafic on your network. You can also use it in ISP environment with per domain and per mailbox report.
* [Napsty/check_smart](https://github.com/Napsty/check_smart) - Monitoring Plugin to check hard drives, solid state drives and NVMe drives using SMART
* [kcsinclair/mibs](https://github.com/kcsinclair/mibs) - A collection of MIBS used for SNMP I have accumulated over the last 20+ years, works with NET-SNMP tools.
* [willixix/naglio-plugins](https://github.com/willixix/naglio-plugins) - Monitoring Plugins by William Leibzon
* [masterzen/mysql-snmp](https://github.com/masterzen/mysql-snmp) - Net-SNMP perl agent for monitoring MySQL servers
* [mharsch/arcstat](https://github.com/mharsch/arcstat) - uses Perl to extract, format, and display kstats from the ZFS ARC
* [jirutka/apcupsd-snmp](https://github.com/jirutka/apcupsd-snmp) - Apcupsd module for Net-SNMP
* [aleex42/netapp-cdot-nagios](https://github.com/aleex42/netapp-cdot-nagios) - Nagios-Checks for monitoring NetApp cDOT-Systems via NetApp Perl API
* [rhuss/jmx4perl](https://github.com/rhuss/jmx4perl) - JMX access tools and modules
* [monitoring-plugins/monitoring-plugin-perl](https://github.com/monitoring-plugins/monitoring-plugin-perl) - Perl module Monitoring::Plugin - Nagios::Plugin
* [jjatria/perl-opentelemetry](https://github.com/jjatria/perl-opentelemetry) - A Perl implementation of the OpenTelemetry standard
* [slauger/check_netscaler](https://github.com/slauger/check_netscaler) - A Nagios Plugin written in Python for the Citrix ADC (formerly Citrix NetScaler). It uses the NetScaler NITRO API.
* [pawal/dnssec-monitor](https://github.com/pawal/dnssec-monitor) - DNSSEC-monitoring tools used many TLDs
* [mojolicious/mojo-status](https://github.com/mojolicious/mojo-status) - :whale: Mojolicious server status
* [jensenja/graphite-snmp-collector](https://github.com/jensenja/graphite-snmp-collector) - Asynchronous Perl to collect SNMP data to feed into Graphite
* [alvar-freude/Posemo](https://github.com/alvar-freude/Posemo) - PostgreSQL Secure Monitoring
* [getsentry/perl-raven](https://github.com/getsentry/perl-raven) - A perl sentry client *(archived)*
* [sni/Monitoring-Livestatus](https://github.com/sni/Monitoring-Livestatus) - Livestatus Perl API to access runtime data from Nagios, Naemon, Icinga and Shinken.
* [omniti-labs/resmon](https://github.com/omniti-labs/resmon) - Resmon is a lightweight utility for local host monitoring that can be queried by tools such as nagios over http. One of the main design goals is portability: that resmon should require nothing more than a default install of Perl. Built with the philosophy that "we are smart because we are dumb," that is, local requirements should be minimal to ease deployment on multiple platforms.
* [reyjrar/DreamCatcher](https://github.com/reyjrar/DreamCatcher) - DNS Monitoring Suite
* [nagios-plugins/nagios-plugin-perl](https://github.com/nagios-plugins/nagios-plugin-perl) - Perl module Nagios::Monitoring::Plugin
* [duncs/perl-nagios-object](https://github.com/duncs/perl-nagios-object) - A group of modules for parsing a Nagios configuration and representing it as objects in perl.
* [fm4dd/nagios4dd](https://github.com/fm4dd/nagios4dd) - Collection of scripts and plugins for the open source monitoring system Nagios.
* [PerlToolsTeam/dashboard](https://github.com/PerlToolsTeam/dashboard) - Simple code build dashboard
* [mollusc-labs/slapbird](https://github.com/mollusc-labs/slapbird) - SlapbirdAPM 🐦: An open-source observability, and performance monitoring platform for Perl web-applications *(archived)*

## User Interface

### Terminal and Console UI

* [xyb3rt/urxvt-perls](https://github.com/xyb3rt/urxvt-perls) - Perl extensions for the rxvt-unicode terminal emulator *(archived)*
* [janlarres/urxvt-font-size](https://github.com/janlarres/urxvt-font-size) - Change the urxvt font size on the fly
* [rollecode/weed](https://github.com/rollecode/weed) - Heavily Xchat inspired beautiful irssi theme.
* [simmel/urxvt-resize-font](https://github.com/simmel/urxvt-resize-font) - URxvt Perl extension for resizing the font
* [cmatsuoka/figlet-fonts](https://github.com/cmatsuoka/figlet-fonts) - A collection of fonts for FIGlet
* [bkendzior/cowfiles](https://github.com/bkendzior/cowfiles) - ASCII cowfiles for cowsay
* [stepb/urxvt-tabbedex](https://github.com/stepb/urxvt-tabbedex) - Tabbed plugin for rxvt-unicode with many enhancements
* [dequis/tmux-url-select](https://github.com/dequis/tmux-url-select) - Keyboard based URL selector that integrates with tmux
* [gryf/tabbedalt](https://github.com/gryf/tabbedalt) - Extended tabbed plugin for rxvt-unicode (urxvt)
* [pkkolos/urxvt-scripts](https://github.com/pkkolos/urxvt-scripts) - A small collection of perl extensions for the rxvt-unicode terminal emulator *(archived)*
* [dams/curses-toolkit](https://github.com/dams/curses-toolkit) - Curses::Toolkit perl module

### Applications and End User Tools

* [Jack000/Expose](https://github.com/Jack000/Expose) - A simple static site generator for photoessays
* [imapsync/imapsync](https://github.com/imapsync/imapsync) - Imapsync is an IMAP transfers tool. The purpose of imapsync is to migrate IMAP accounts or to backup IMAP accounts. IMAP is one of the three current standard protocols to access mailboxes, the two others are POP3 and HTTP with webmails, webmails are often tied to an IMAP server. Upstream website is
* [holzschu/a-shell](https://github.com/holzschu/a-shell) - A terminal for iOS, with multiple windows
* [rsnapshot/rsnapshot](https://github.com/rsnapshot/rsnapshot) - a tool for backing up your data using rsync (if you want to get help, use https://lists.sourceforge.net/lists/listinfo/rsnapshot-discuss)
* [Difegue/LANraragi](https://github.com/Difegue/LANraragi) - Web application for archival and reading of manga/doujinshi. Lightweight and Docker-ready for NAS/servers.
* [szTheory/exifcleaner](https://github.com/szTheory/exifcleaner) - Cross-platform desktop GUI app to clean image metadata
* [get-iplayer/get_iplayer](https://github.com/get-iplayer/get_iplayer) - A utility for downloading TV and radio programmes from BBC iPlayer and BBC Sounds
* [shanleiguang/vRain](https://github.com/shanleiguang/vRain) - 中文古籍刻本風格直排電子書製作工具 Chinese Ancient eBooks Generator
* [backuppc/backuppc](https://github.com/backuppc/backuppc) - BackupPC is a high-performance, enterprise-grade system for backing up to a server's disk.
* [OpenKore/openkore](https://github.com/OpenKore/openkore) - A free/open source client and automation tool for Ragnarok Online
* [trizen/youtube-viewer](https://github.com/trizen/youtube-viewer) - Lightweight YouTube client for Linux
* [asbru-cm/asbru-cm](https://github.com/asbru-cm/asbru-cm) - Ásbrú Connection Manager is a user interface that helps organizing remote terminal sessions and automating repetitive tasks.
* [cmatsuoka/asciiquarium](https://github.com/cmatsuoka/asciiquarium) - Enjoy the mysteries of the sea from the safety of your own terminal!
* [pasky/speedread](https://github.com/pasky/speedread) - A simple terminal-based open source Spritz-alike (per-word RSVP aligned on optimal reading points)
* [convos-chat/convos](https://github.com/convos-chat/convos) - Convos :busts_in_silhouette: is the simplest way to use IRC in your browser
* [bestpractical/rt](https://github.com/bestpractical/rt) - Request Tracker, an enterprise-grade issue tracking system
* [openfoodfacts/openfoodfacts-server](https://github.com/openfoodfacts/openfoodfacts-server) - Open Food Facts database, API server and web interface - 🐪🦋 Perl, CSS and JS coders welcome 😊 For helping in Python, see Robotoff or taxonomy-editor
* [andrewning/sortphotos](https://github.com/andrewning/sortphotos) - SortPhotos is a Python script that organizes photos and videos into folders using date/time information
* [metabrainz/musicbrainz-server](https://github.com/metabrainz/musicbrainz-server) - Server for the MusicBrainz project (website, API, database tools)
* [duncs/clusterssh](https://github.com/duncs/clusterssh) - Cluster SSH - Cluster Admin Via SSH
* [webmin/authentic-theme](https://github.com/webmin/authentic-theme) - Official theme for the best server management panel of the 21st Century
* [bugzilla/bugzilla](https://github.com/bugzilla/bugzilla) - Official repository for the Bugzilla bug tracking system. Report bugs to https://bugzilla.mozilla.org/enter_bug.cgi?product=Bugzilla&format=__default__ . Main website:
* [shanleiguang/vYinn](https://github.com/shanleiguang/vYinn) - 中文古籍印章製作工具 Chinese Ancient Seals Design Tool
* [shutter-project/shutter](https://github.com/shutter-project/shutter) - Screenshot tool for Linux
* [zentyal/zentyal](https://github.com/zentyal/zentyal) - Linux Small Business Server
* [mysociety/fixmystreet](https://github.com/mysociety/fixmystreet) - This is mySociety's popular map-based reporting platform: easy to install in new countries and regions
* [znuny/Znuny](https://github.com/znuny/Znuny) - Znuny is a free, open-source, and versatile web-based ticketing system for Customer Service, Help Desk, IT Service Management, and more. It is built for transparency and long-term sustainability and is highly tailorable to your organization's needs.
* [trizen/pipe-viewer](https://github.com/trizen/pipe-viewer) - A lightweight YouTube client for Linux, without requiring an API key.
* [iberianpig/xSwipe](https://github.com/iberianpig/xSwipe) - Multitouch gestures with synaptics driver on X11, Linux *(archived)*
* [ljunkie/plexWatch](https://github.com/ljunkie/plexWatch) - Notify and Log watched content on a Plex Media Server *(archived)*
* [movabletype/movabletype](https://github.com/movabletype/movabletype) - Movable Type
* [ZoneMinder/zmeventnotification](https://github.com/ZoneMinder/zmeventnotification) - Machine Learning powered Secure Websocket & MQTT based ZoneMinder event notification server *(archived)*
* [OCSInventory-NG/OCSInventory-Server](https://github.com/OCSInventory-NG/OCSInventory-Server) - Communication server of OCS Inventory
* [apache/spamassassin](https://github.com/apache/spamassassin) - Read-only mirror of Apache SpamAssassin.
* [oysttyer/oysttyer](https://github.com/oysttyer/oysttyer) - An interactive console text-based command-line Twitter client written in Perl *(archived)*
* [xypiie/spread0r](https://github.com/xypiie/spread0r) - spread0r is a txt reader, which makes your reading twice as fast as usual
* [sympa-community/sympa](https://github.com/sympa-community/sympa) - Sympa, Mailing List Management Software
* [uparrows/LANraragi_cn](https://github.com/uparrows/LANraragi_cn) - This repo is a fork of Difegue / LANraragi , those things i've done was to translate this repo into chinese ,and fix chrome browser js problem.
* [kaimi-io/yandex-music-download](https://github.com/kaimi-io/yandex-music-download) - Yandex Music Downloader
* [hollie/misterhouse](https://github.com/hollie/misterhouse) - Perl open source home automation program. It's fun, it's free, and it's entirely geeky.
* [monsieurvideo/get-flash-videos](https://github.com/monsieurvideo/get-flash-videos) - Download or play videos from various Flash-based video hosting sites, without having to use the Flash player.
* [carnager/clerk](https://github.com/carnager/clerk) - clerk - mpd client, based on rofi/fzf *(archived)*
* [melmothx/amusewiki](https://github.com/melmothx/amusewiki) - Text::Amuse-based publishing platform
* [ldidry/lstu](https://github.com/ldidry/lstu) - Lightweight URL shortener. Read-only mirror of https://framagit.org/fiat-tux/hat-softwares/lstu
* [perseo22/pacmanager](https://github.com/perseo22/pacmanager) - Perl/GTK Gnome SSH GUI on steroids. Configure SSH/Telnet connections: users, passwords, EXPECT regular expressions, macros, ...
* [dreamwidth/dreamwidth](https://github.com/dreamwidth/dreamwidth) - Dreamwidth's open source repository
* [miyagawa/github-growler](https://github.com/miyagawa/github-growler) - Growl github updates
* [MarkWheadon/velocity-painting](https://github.com/MarkWheadon/velocity-painting) - #VelocityPainting: patterning 3D prints by modulating the print speed
* [squentin/gmusicbrowser](https://github.com/squentin/gmusicbrowser) - jukebox for large collections of music
* [bandiaozimu/dj_voice_organize](https://github.com/bandiaozimu/dj_voice_organize) - 同人音声资料库系统
* [somenonymous/OshiUpload](https://github.com/somenonymous/OshiUpload) - Ephemeral file sharing engine
* [trizen/obmenu-generator](https://github.com/trizen/obmenu-generator) - A fast menu generator for the Openbox Window Manager.
* [miyagawa/plagger](https://github.com/miyagawa/plagger) - Pluggable RSS/Atom aggregator
* [derf/travelynx](https://github.com/derf/travelynx) - Traewelling-inspired journey logger with realtime data
* [justingit/dada-mail](https://github.com/justingit/dada-mail) - Self-Hosted, Full Featured, Email Mailing List Manager. Announcement + Discussion Lists, Web-based Installer, Installs with minimal dependencies, sendmail/SMTP/Amazon SES supported
* [mozilla/bmo](https://github.com/mozilla/bmo) - bugzilla.mozilla.org source - report issues here: https://bugzilla.mozilla.org/enter_bug.cgi?product=bugzilla.mozilla.org
* [chelseybadau/iOSMessageExport](https://github.com/chelseybadau/iOSMessageExport) - *(archived)*
* [xchataqua/xchataqua](https://github.com/xchataqua/xchataqua) - An IRC client, OS X native front-end for XChat ( http://itunes.apple.com/app/id447521961 )
* [marchyman/GeoTag](https://github.com/marchyman/GeoTag) - Image geo location editing for macOS. Instructions and a .dmg of the current version are on the application home page.
* [nriley/Pester](https://github.com/nriley/Pester) - Simple, disposable alarms and timers for macOS.
* [BitMOE/PortableHexo](https://github.com/BitMOE/PortableHexo) - A Portable version of Hexo
* [jamesphotography/SuperPicky](https://github.com/jamesphotography/SuperPicky) - Ai Powered Bird Photography Culling Tools
* [webmin/usermin](https://github.com/webmin/usermin) - Usermin source code
* [cschneid/irclogger](https://github.com/cschneid/irclogger) - Sinatra based irclogger.com
* [john-bokma/tumblelog](https://github.com/john-bokma/tumblelog) - A static tumblelog generator available as both a Perl and Python version
* [mojomojo/mojomojo](https://github.com/mojomojo/mojomojo) - A Catalyst & DBIx::Class powered Wiki.
* [ingydotnet/vroom-pm](https://github.com/ingydotnet/vroom-pm) - Vim Based Slideshow Presentations
* [NicolasGuilloux/blade-shadow-beta](https://github.com/NicolasGuilloux/blade-shadow-beta) - Various documentation and tools for Shadow on Linux maintained by community *(archived)*
* [miyagawa/remedie](https://github.com/miyagawa/remedie) - perl based pluggable media center application *(archived)*
* [foswiki/distro](https://github.com/foswiki/distro) - START HERE! This is the Foswiki project "Distribution". It is a monolith repository with the core + default extensions.
* [jmacdotorg/plerd](https://github.com/jmacdotorg/plerd) - Ultralight Dropbox-friendly Markdown-based blogging.
* [joz-k/ios_backup_extractor](https://github.com/joz-k/ios_backup_extractor) - iOS backup media extraction tool (photos, videos)
* [Gilwyad/mailnesia.com](https://github.com/Gilwyad/mailnesia.com) - Anonymous Email in Seconds
* [davidbauer/Instacurate](https://github.com/davidbauer/Instacurate) - Turn your Twitter timeline into a personalised news site, in an instant. Fetches links from your timeline and displays them in a discovery friendly design.
* [zhy201810576/ETagCN](https://github.com/zhy201810576/ETagCN) - 基于Difegue编写的E-Hentai插件进行改良，结合EhTagTranslation项目提供的数据库转换来自E-Hentai上的英文标签为中文标签。
* [bricoleurs/bricolage](https://github.com/bricoleurs/bricolage) - Content management and publishing system
* [trizen/straw-viewer](https://github.com/trizen/straw-viewer) - **DEPRECATED** Use https://github.com/trizen/pipe-viewer instead. *(archived)*
* [nonnymoose/xsr](https://github.com/nonnymoose/xsr) - X Steps Recorder
* [ology/Chess-Inspector](https://github.com/ology/Chess-Inspector) - Visualize move, protection and threat status
* [derf/db-fakedisplay](https://github.com/derf/db-fakedisplay) - App/Infoscreen for Railway Departures in Germany
* [fletcher/MultiMarkdown-CMS](https://github.com/fletcher/MultiMarkdown-CMS) - Package to assist with publishing a web site using MMD and a few perl scripts
* [andrewcmyers/civs](https://github.com/andrewcmyers/civs) - Condorcet Internet Voting System
* [andre-st/goodreads-toolbox](https://github.com/andre-st/goodreads-toolbox) - 9 tools for Goodreads.com, for finding people based on the books they’ve read, finding books popular among the people you follow, following new book reviews, etc *(archived)*
* [apparentlymart/livejournal](https://github.com/apparentlymart/livejournal) - LiveJournal Server Source Code (stale history from before it went closed-source) *(archived)*
* [kensanata/oddmuse](https://github.com/kensanata/oddmuse) - A simple wiki engine written in Perl. No database required.
* [demanuel/NewsUP](https://github.com/demanuel/NewsUP) - Fully feature high performance binary usenet uploader/poster
* [nkh/P5-App-Asciio](https://github.com/nkh/P5-App-Asciio) - Plain ASCII diagram
* [preaction/Statocles](https://github.com/preaction/Statocles) - Static website CMS
* [vti/bootylicious](https://github.com/vti/bootylicious) - LIghtweight blog engine on Mojo steroids!
* [hashier/MacFolket](https://github.com/hashier/MacFolket) - A Swedish <-> English Dictionary || svensk <-> engelsk ordbok for Mac OS X
* [perlorg/perlweb](https://github.com/perlorg/perlweb) - Various perl.org websites
* [WindyCloudCute/LANraragi_Chinese](https://github.com/WindyCloudCute/LANraragi_Chinese) - 全新稳定更新的LANraragi中文汉化翻译项目 *(archived)*
* [dgl/cgiirc](https://github.com/dgl/cgiirc) - CGI:IRC web based IRC client
* [eserte/bbbike](https://github.com/eserte/bbbike) - BBBike
* [memowe/contenticious](https://github.com/memowe/contenticious) - A simple file based "CMS" on Mojo steroids! *(archived)*
* [Grinnz/perldoc-browser](https://github.com/Grinnz/perldoc-browser) - Perldoc Browser
* [Real-Gecko/Filemin](https://github.com/Real-Gecko/Filemin) - File manager for Webmin written completely in perl
* [trizen/menutray](https://github.com/trizen/menutray) - An application menu through a GTK+ tray status icon.
* [yoe/SReview](https://github.com/yoe/SReview) - sreview review system
* [SoylentNews/rehash](https://github.com/SoylentNews/rehash) - Forked from Slashcode, rehash is the codebase that powers SoylentNews.org, powered by mod_perl 2
* [skx/templer](https://github.com/skx/templer) - A modular extensible static-site-generator written in perl. *(archived)*
* [plainblack/webgui](https://github.com/plainblack/webgui) - A free open source content management system and web application framework. The most widely deployed mod_perl application on the planet.
* [PrefKarafuto/ex0ch](https://github.com/PrefKarafuto/ex0ch) - EXぜろちゃんねる
* [denny/ShinyCMS](https://github.com/denny/ShinyCMS) - ShinyCMS is an open source CMS. This is the Perl version, built with Catalyst and DBIC. (There is also a Ruby on Rails version: www.github.com/denny/ShinyCMS-ruby)
* [guruperl/mlm](https://github.com/guruperl/mlm) - Comprehensive open-source Multi-Level Marketing (MLM) Software
* [duckduckgo/duckduckgo-publisher](https://github.com/duckduckgo/duckduckgo-publisher) - Generation of the static files of DuckDuckGo and its microsites. *(archived)*
* [statico/cadubi](https://github.com/statico/cadubi) - :art: Creative ASCII Drawing Utility By Ian (1997)
* [dasdom/CreateAppStoreBill](https://github.com/dasdom/CreateAppStoreBill) - A perl script and tex files to create bills for the German tax office from Apple's financial reports.
* [mahlonsmith/shelldap](https://github.com/mahlonsmith/shelldap) - A handy shell-like interface for browsing LDAP servers and editing their content. It keeps command history, has sane autocompletes, credential caching, site-wide and individual configs, and it's fun to say. Shelldap! Shelldap! Shelldap!
* [jberger/Zoidberg](https://github.com/jberger/Zoidberg) - A modular perl shell
* [Tekki/sql-ledger](https://github.com/Tekki/sql-ledger) - SQL-Ledger ERP, the most advanced version.
* [klenin/cats-main](https://github.com/klenin/cats-main) - Programming contest control system
* [vti/showmethedesktop](https://github.com/vti/showmethedesktop) - Perl + VNC + WebSockets + HTML5 Canvas
* [LibreCat/LibreCat](https://github.com/LibreCat/LibreCat) - A publication management system *(archived)*
* [CiderWebmail/CiderWebmail](https://github.com/CiderWebmail/CiderWebmail) - Perl/Catalyst/AJAX based Webmail
* [nigelhorne/ged2site](https://github.com/nigelhorne/ged2site) - Create a family tree website from a Gedcom file
* [mclenburg/plutoTV-tvheadend](https://github.com/mclenburg/plutoTV-tvheadend) - Perl-Script to generate m3u and xmltv-epg from PlutoTV-API
* [yusukebe/App-revealup](https://github.com/yusukebe/App-revealup) - HTTP Server app for viewing Markdown formatted text as slides
* [perigrin/blawd](https://github.com/perigrin/blawd) - Simple Blogging Software in Perl, similar to blosxome or Jekyll
* [trapd00r/pimpd2](https://github.com/trapd00r/pimpd2) - Perl Interface for the Music Player Daemon 2 | http://search.cpan.org/dist/App-Pimpd/
* [gflohr/qgoda](https://github.com/gflohr/qgoda) - Qgoda (pronounce: yagoda!) is an extensible static site generator with arbitrary taxonomies and cross-links and a strong focus on multilanguage facilities.
* [xtaran/wApua](https://github.com/xtaran/wApua) - web browser for WAP WML pages
* [Flameborn/Kiramoji](https://github.com/Flameborn/Kiramoji) - Kiramoji is a modified version of the popular anonymous message board: Kareha.
* [isgphys/BaNG](https://github.com/isgphys/BaNG) - Backup Next Generation for Linux & Mac using rsync (support hardlinks and btrfs snapshots), Web-Frontend, Statistics, History-Merger)
* [eserte/cpan-testers-matrix](https://github.com/eserte/cpan-testers-matrix) - the code behind matrix.cpantesters.org
* [skx/markdownshare.com](https://github.com/skx/markdownshare.com) - The code which was previously used at http://markdownshare.com/ *(archived)*
* [prepan-developers/prepan](https://github.com/prepan-developers/prepan) - Social Reviewing for Perl Modules
* [davorg-cpan/perlanet](https://github.com/davorg-cpan/perlanet) - Simple Planet Clone in Perl
* [mdom/termpub](https://github.com/mdom/termpub) - Epubreader for the terminal *(archived)*
* [bgoglin/llgal](https://github.com/bgoglin/llgal) - Command-line online gallery generator
* [hakobe/Guita](https://github.com/hakobe/Guita) - Gist clone for private use written in Perl
* [nigelhorne/gedcom](https://github.com/nigelhorne/gedcom) - Gedcom utility program
* [pssc/squeezy](https://github.com/pssc/squeezy) - A command-line utility for controlling squeezebox network audio players via their squeezeserver.
* [cho45/Niro](https://github.com/cho45/Niro) - Blogging System for personal use written in Perl.
* [rickumali/RickUmaliVanityWebsite](https://github.com/rickumali/RickUmaliVanityWebsite) - This is the Perl source code that generates my vanity webpage (hosted at rickumali.com).
* [cryptostorm/cstorm_widget](https://github.com/cryptostorm/cstorm_widget) - The Perl source code to the Cryptostorm widget
* [skx/chronicle2](https://github.com/skx/chronicle2) - Chronicle is a simple blog compiler, written in Perl with minimal dependencies. *(archived)*
* [USGCRP/gcis](https://github.com/USGCRP/gcis) - Global Change Information System
* [yuki-kimoto/gitweblite](https://github.com/yuki-kimoto/gitweblite) - Git repository browser. This is gtiweb.cgi clone to modern perl.
* [algorithmic-alcove/gmail-imap-label](https://github.com/algorithmic-alcove/gmail-imap-label) - :mailbox_with_mail::open_file_folder::bookmark: adds Gmail labels to IMAP stream as the X-Label header
* [neevek/minerl](https://github.com/neevek/minerl) - A blog-aware static site generator written in perl.
* [vitaly-s/robocopy](https://github.com/vitaly-s/robocopy) - Synology package for organize photo/video files by rules

## Graphics and Media

### Graphics and Rendering

* [ironcamel/Graph-Easy](https://github.com/ironcamel/Graph-Easy) - Convert or render graphs (as ASCII, HTML, SVG or via Graphviz)
* [dse/dse-typewriter-font](https://github.com/dse/dse-typewriter-font) - A monospace coding font inspired by pre-war typewriters.
* [shoorick/russian-road-sign-font](https://github.com/shoorick/russian-road-sign-font) - Font which used for road signs in USSR and Russia
* [silnrsi/font-charis](https://github.com/silnrsi/font-charis) - Fonts for languages and writing systems that use the Latin and Cyrillic scripts
* [kristov/ldraw2stl](https://github.com/kristov/ldraw2stl) - Convert LEGO LDraw files into STL
* [kbh3rd/shptosvg](https://github.com/kbh3rd/shptosvg) - Shapefile to SVG renderer in Perl
* [alx77/render_list_geo.pl](https://github.com/alx77/render_list_geo.pl) - Perl script for automatic rendering tiles for renderd+mod_tile
* [topaz/perl-mandelbrot](https://github.com/topaz/perl-mandelbrot) - Interactive Mandelbrot set renderer/explorer for your terminal.
* [silnrsi/font-ttf](https://github.com/silnrsi/font-ttf) - Font::TTF Perl Module

### Game Development

* [kthakore/frozen-bubble](https://github.com/kthakore/frozen-bubble) - Making frozen bubble cross platform
* [rsu-client/rsu-client](https://github.com/rsu-client/rsu-client) - A git repository for the RuneScape Linux/Unix Client Project *(archived)*
* [cocos2d/cocos2d-x-3rd-party-libs-src](https://github.com/cocos2d/cocos2d-x-3rd-party-libs-src) - Dependencies of cocos2d-x.
* [jsnell/terra-mystica](https://github.com/jsnell/terra-mystica) - Online Terra Mystica
* [DFHack/df-structures](https://github.com/DFHack/df-structures) - Dwarf Fortress data structure descriptions
* [CityGenerator/CityGenerator](https://github.com/CityGenerator/CityGenerator) - CityGenerator is a tool for generating a setting for Fantasy Roleplaying games.
* [PerlGameDev/SDL](https://github.com/PerlGameDev/SDL) - Rehashing the old perl SDL binding on cpan.org
* [DerekPascarella/Capcomvs.SNK2-EnglishPatchDreamcast](https://github.com/DerekPascarella/Capcomvs.SNK2-EnglishPatchDreamcast) - English translation patch for the Sega Dreamcast game "Capcom vs. SNK 2".
* [Lallassu/DungeonGenerator](https://github.com/Lallassu/DungeonGenerator) - Dungeon generator for games.
* [existentialcomics/kungFuChess](https://github.com/existentialcomics/kungFuChess) - Real time chess game using websockets, perl, and c++ for the AI.
* [saiftynet/Wordle](https://github.com/saiftynet/Wordle) - A command Line wordle clone
* [OliverBoy/Luna](https://github.com/OliverBoy/Luna) - Club Penguin Server Emulator - AS2 Protocol
* [lynxlynxlynx/gemrb-mods](https://github.com/lynxlynxlynx/gemrb-mods) - Repository of my GemRB mods and tools not included with GemRB itself
* [Yaribz/SPADS](https://github.com/Yaribz/SPADS) - SpringRTS Perl Autohost for Dedicated Server
* [elmex/Construder](https://github.com/elmex/Construder) - A 3D Game written in Perl - inspired by Minecraft

### Audio

* [LMS-Community/slimserver](https://github.com/LMS-Community/slimserver) - Server for Squeezebox and compatible players. This server is also called Lyrion Music Server.
* [ChordPro/chordpro](https://github.com/ChordPro/chordpro) - Reference implementation of the ChordPro standard for musical lead sheets.
* [raboof/realtimeconfigquickscan](https://github.com/raboof/realtimeconfigquickscan) - Linux configuration checker for systems to be used for real-time audio *(archived)*
* [michaelherger/Spotty-Plugin](https://github.com/michaelherger/Spotty-Plugin) - A Spotify plugin for the Lyrion Music Server (fka. Logitech Media Server) and Squeezebox compatible players
* [robinbowes/flac2mp3](https://github.com/robinbowes/flac2mp3) - flac2mp3 is a tool to convert audio files from flac to mp3 format including the copying of tags.
* [philippe44/libraop](https://github.com/philippe44/libraop) - RAOP player and library (AirPlay)
* [divVerent/ecantorix](https://github.com/divVerent/ecantorix) - Singing synthesis frontend for espeak
* [glutanimate/simple-google-tts](https://github.com/glutanimate/simple-google-tts) - Use Google text-to-speech on your Linux desktop *(archived)*
* [hechtus/squeezebox-googlemusic](https://github.com/hechtus/squeezebox-googlemusic) - Squeezebox (Logitech Media Server) Plugin for Google Play Music
* [trizen/clyrics](https://github.com/trizen/clyrics) - An extensible lyrics fetcher, with daemon support for cmus and mocp.
* [stiefenm/spoton](https://github.com/stiefenm/spoton) - SpotOn — A fresh Spotify plugin for Lyrion Music Server (LMS)

### Image and Video

* [exiftool/exiftool](https://github.com/exiftool/exiftool) - ExifTool meta information reader/writer
* [quran/quran.com-images](https://github.com/quran/quran.com-images) - images using fonts from King Fahed Complex / qurancomplex.org
* [revmischa/rtsp-server](https://github.com/revmischa/rtsp-server) - Lightweight RTSP/RTP streaming media server
* [bookkojot/mp4fixer](https://github.com/bookkojot/mp4fixer) - Recover damaged/unfinished mp4 files with h264 video
* [osklil/hls-fetch](https://github.com/osklil/hls-fetch) - Download and decrypt videos served by the HTTP Live Streaming (HLS) protocol.
* [kud/jpegrescan](https://github.com/kud/jpegrescan) - JPEGrescan: losslessly shrink any JPEG file - YOU PROBABLY SHOULD USE MozJPEG https://github.com/mozilla/mozjpeg *(archived)*
* [joielechong/iso-country-flags-svg-collection](https://github.com/joielechong/iso-country-flags-svg-collection)
* [gnoling/UnlinkMKV](https://github.com/gnoling/UnlinkMKV) - Merges ordered chapters / segmented MKVs back into a single file.
* [jhnc/findimagedupes](https://github.com/jhnc/findimagedupes) - Finds visually similar or duplicate images
* [dennispaagman/font-awesome-balsamiq](https://github.com/dennispaagman/font-awesome-balsamiq) - Font Awesome icons as .png, ready for use with Balsamiq *(archived)*
* [jjl/get_iplayer](https://github.com/jjl/get_iplayer) - A utility for grabbing tv and radio from BBC iPlayer. Phil Lewis has stopped developed it so I've forked it.
* [cyberang3l/timelapse-deflicker](https://github.com/cyberang3l/timelapse-deflicker) - Simple script to deflicker images taken for timelapses
* [NapoleonWils0n/kodi-playercorefactory](https://github.com/NapoleonWils0n/kodi-playercorefactory) - kodi playercorefactory.xml players to play and record videos and bash scripts
* [grampajoe/Autodatamosh](https://github.com/grampajoe/Autodatamosh) - Perl script that automatically datamoshes MPEG4-encoded AVI videos.
* [kensanata/sitelen-mute](https://github.com/kensanata/sitelen-mute) - a static image gallery creator
* [dnsforge-repo/xteve](https://github.com/dnsforge-repo/xteve) - Latest Dockerized xTeVe v2.2.x IPTV proxy with Guide2go, zap2XML, Crond & Perl Support.
* [typester/kamaitachi](https://github.com/typester/kamaitachi) - perl flash media server
* [lstein/Perl-GD](https://github.com/lstein/Perl-GD) - Perl GD module for bitmap graphics
* [shanleiguang/vQi](https://github.com/shanleiguang/vQi) - 圍棋SGF棋譜文件轉中式古棋譜圖 - Go SGF to images of Chinese ancient style
* [tonycoz/imager](https://github.com/tonycoz/imager) - Imager - image manipulation from perl.
* [LaTeX-Package-Repositories/pdfcrop](https://github.com/LaTeX-Package-Repositories/pdfcrop) - pdfcrop perl utility
* [geuma/pDLNA](https://github.com/geuma/pDLNA) - perl DLNA MediaServer
* [silnrsi/font-ttf-scripts](https://github.com/silnrsi/font-ttf-scripts) - Font::TTF::Scripts perl module
* [exiftool-rb/exiftool_vendored.rb](https://github.com/exiftool-rb/exiftool_vendored.rb) - The exiftool gem requires the exiftool perl package, which this includes.

## Security

### Cryptography

* [openxpki/openxpki](https://github.com/openxpki/openxpki) - OpenXPKI Code
* [do-know/Crypt-LE](https://github.com/do-know/Crypt-LE) - Crypt::LE - Let's Encrypt / Buypass / ZeroSSL and other ACME-servers client and library in Perl for obtaining free SSL certificates (inc. generating RSA/ECC keys and CSRs). HTTP/DNS verification is supported out of the box, EAB (External Account Binding) supported, easily extended with plugins, easily dockerized.
* [microsoft/PQCrypto-VPN](https://github.com/microsoft/PQCrypto-VPN) - Post-quantum Cryptography VPN
* [bbusschots/hsxkpasswd](https://github.com/bbusschots/hsxkpasswd) - A Perl module and terminal command for generating secure memorable passwords inspired by the fabulous XKCD web comic and Steve Gibson's Password Hay Stacks. This is the library that powers www.xkpasswd.net
* [linenoise/asemica](https://github.com/linenoise/asemica) - An asemic Markov-chained cipher
* [Prajithp/letsencrypt-cpanel](https://github.com/Prajithp/letsencrypt-cpanel) - cPanel/WHM plugin for Let's Encrypt client
* [jkeys089/lua-resty-hmac](https://github.com/jkeys089/lua-resty-hmac) - HMAC functions for ngx_lua and LuaJIT
* [lixmal/keepass4web](https://github.com/lixmal/keepass4web) - [deprecated] KeePass databases served on the web *(archived)*
* [kirei/catt](https://github.com/kirei/catt) - Certification Authority Trust Tracker
* [SSLMate/sslmate](https://github.com/SSLMate/sslmate) - The SSLMate Client - Buy and Manage SSL Certs from the Command Line
* [Open-TEE/project](https://github.com/Open-TEE/project) - Overall project configuration and documentation
* [radiator-software/p5-net-ssleay](https://github.com/radiator-software/p5-net-ssleay) - Net-SSLeay: Perl bindings for OpenSSL and LibreSSL
* [dsully/perl-crypt-openssl-x509](https://github.com/dsully/perl-crypt-openssl-x509) - Perl interface to OpenSSL's X509 module.
* [wllm-rbnt/asn1template](https://github.com/wllm-rbnt/asn1template) - A CLI tool that converts DER or PEM encoded ASN.1 structures into an equivalent textual description compatible with OpenSSL's ASN1_generate_nconf(3) function
* [gisle/mozilla-ca](https://github.com/gisle/mozilla-ca) - Perl module that provides Mozilla's CA cert bundle in PEM format
* [sludin/Protocol-ACME](https://github.com/sludin/Protocol-ACME) - A perl library that provides a simple interface to writing scripts for cert provisioning with Let's Encrypt.

### Security Tools

* [sullo/nikto](https://github.com/sullo/nikto) - Nikto web server scanner
* [x0rz/EQGRP](https://github.com/x0rz/EQGRP) - Decrypted content of eqgrp-auction-file.tar.xz
* [GuidoBartoli/sherloq](https://github.com/GuidoBartoli/sherloq) - An open-source digital image forensic toolset
* [Moham3dRiahi/Th3inspector](https://github.com/Moham3dRiahi/Th3inspector) - Th3Inspector 🕵️ Best Tool For Information Gathering 🔎
* [SpiderLabs/owasp-modsecurity-crs](https://github.com/SpiderLabs/owasp-modsecurity-crs) - OWASP ModSecurity Core Rule Set (CRS) Project (Official Repository) *(archived)*
* [samyk/slipstream](https://github.com/samyk/slipstream) - NAT Slipstreaming allows an attacker to remotely access any TCP/UDP services bound to a victim machine, bypassing the victim’s NAT/firewall, just by anyone on the victim's network visiting a website
* [jondonas/linux-exploit-suggester-2](https://github.com/jondonas/linux-exploit-suggester-2) - Next-Generation Linux Kernel Exploit Suggester
* [owasp-modsecurity/ModSecurity-nginx](https://github.com/owasp-modsecurity/ModSecurity-nginx) - ModSecurity v3 Nginx Connector
* [InteliSecureLabs/Linux_Exploit_Suggester](https://github.com/InteliSecureLabs/Linux_Exploit_Suggester) - Linux Exploit Suggester; based on operating system release number
* [kost/dvcs-ripper](https://github.com/kost/dvcs-ripper) - Rip web accessible (distributed) version control systems: SVN/GIT/HG...
* [Moham3dRiahi/XAttacker](https://github.com/Moham3dRiahi/XAttacker) - X Attacker Tool ☣ Website Vulnerability Scanner & Auto Exploiter
* [inverse-inc/packetfence](https://github.com/inverse-inc/packetfence) - PacketFence is a fully supported, trusted, Free and Open Source network access control (NAC) solution. Boasting an impressive feature set including a captive-portal for registration and remediation, centralized wired and wireless management, powerful BYOD management options, 802.1X support, layer-2 isolation of problematic devices; PacketFence can be used to effectively secure networks small to very large heterogeneous networks.
* [AlisamTechnology/ATSCAN](https://github.com/AlisamTechnology/ATSCAN) - Advanced dork Search & Mass Exploit Scanner
* [CiscoCXSecurity/enum4linux](https://github.com/CiscoCXSecurity/enum4linux) - enum4Linux is a Linux alternative to enum.exe for enumerating data from Windows and Samba hosts
* [infobyte/evilgrade](https://github.com/infobyte/evilgrade) - Evilgrade is a modular framework that allows the user to take advantage of poor upgrade implementations by injecting fake updates.
* [p0pr0ck5/lua-resty-waf](https://github.com/p0pr0ck5/lua-resty-waf) - High-performance WAF built on the OpenResty stack
* [sighook/pixload](https://github.com/sighook/pixload) - Image Payload Creating/Injecting tools
* [sbwml/halflife-list](https://github.com/sbwml/halflife-list) - ABP/ublock 广告过滤规则（每周一早上 8 点更新）
* [wireghoul/dotdotpwn](https://github.com/wireghoul/dotdotpwn) - DotDotPwn - The Directory Traversal Fuzzer
* [strozfriedberg/PadBuster](https://github.com/strozfriedberg/PadBuster) - Automated script for performing Padding Oracle attacks
* [rapid7/IoTSeeker](https://github.com/rapid7/IoTSeeker) - Created by Jin Qian via the GitHub Connector
* [truongkma/ctf-tools](https://github.com/truongkma/ctf-tools) - tổng hợp tool ctf
* [fwaeytens/dnsenum](https://github.com/fwaeytens/dnsenum) - dnsenum is a perl script that enumerates DNS information
* [modzero/mod0BurpUploadScanner](https://github.com/modzero/mod0BurpUploadScanner) - HTTP file upload scanner for Burp Proxy *(archived)*
* [philsmd/7z2hashcat](https://github.com/philsmd/7z2hashcat) - extract information from password-protected .7z archives (and .sfx files) such that you can crack these "hashes" with hashcat
* [shirkdog/pulledpork](https://github.com/shirkdog/pulledpork) - Pulled Pork for Snort and Suricata rule management (from Google code)
* [rapid7/metasploit-vulnerability-emulator](https://github.com/rapid7/metasploit-vulnerability-emulator) - Created by Jin Qian via the GitHub Connector *(archived)*
* [dave-theunsub/clamtk](https://github.com/dave-theunsub/clamtk) - An easy to use, light-weight, on-demand virus scanner for Linux systems
* [mrash/psad](https://github.com/mrash/psad) - psad: Intrusion Detection and Log Analysis with iptables
* [OWASP/O-Saft](https://github.com/OWASP/O-Saft) - O-Saft - OWASP SSL advanced forensic tool
* [Aetherinox/csf-firewall](https://github.com/Aetherinox/csf-firewall) - ConfigServer Security & Firewall (CSF) - Robust linux iptables/nftables firewall & free ipset blocklist service.
* [MaxKellermann/ferm](https://github.com/MaxKellermann/ferm) - ferm is a frontend for iptables
* [davisjam/vuln-regex-detector](https://github.com/davisjam/vuln-regex-detector) - Detect vulnerable regexes in your project. REDOS, catastrophic backtracking.
* [julienbedard/browsersploit](https://github.com/julienbedard/browsersploit) - BrowserExploit is an advanced browser exploit pack for doing internal and external pentesting, helping gaining access to internal computers.
* [OWASP/vbscan](https://github.com/OWASP/vbscan) - OWASP VBScan is a Black Box vBulletin Vulnerability Scanner *(archived)*
* [davidpepper/fierce-domain-scanner](https://github.com/davidpepper/fierce-domain-scanner) - Fierce.pl Domain Scanner
* [HexaCluster/pgdsat](https://github.com/HexaCluster/pgdsat) - PostgreSQL Database Security Assessment Tool
* [fuzyll/defcon-vm](https://github.com/fuzyll/defcon-vm) - Files from my DEFCON CTF VM.
* [CiscoCXSecurity/rdp-sec-check](https://github.com/CiscoCXSecurity/rdp-sec-check) - rdp-sec-check is a Perl script to enumerate security settings of an RDP Service (AKA Terminal Services)
* [sandialabs/scot](https://github.com/sandialabs/scot) - Sandia Cyber Omni Tracker (SCOT)
* [techsneeze/dmarcts-report-parser](https://github.com/techsneeze/dmarcts-report-parser) - A Perl based tool to parse DMARC reports from an IMAP mailbox or from the filesystem, and insert the information into a database. ( Formerly known as imap-dmarcts )
* [LudovicRousseau/pcsc-tools](https://github.com/LudovicRousseau/pcsc-tools) - Some tools to be used with smart cards and PC/SC
* [csirtgadgets/massive-octo-spice](https://github.com/csirtgadgets/massive-octo-spice) - DEPRECATED - USE v3 (bearded-avenger) *(archived)*
* [henshin/filebuster](https://github.com/henshin/filebuster) - An extremely fast and flexible web fuzzer
* [aziz0x48/vMass](https://github.com/aziz0x48/vMass) - vMass Bot :hook: Vulnerability Scanner & Auto Exploiter Tool Written in Perl.
* [MailScanner/v5](https://github.com/MailScanner/v5) - MailScanner v5
* [noxxi/p5-ssl-tools](https://github.com/noxxi/p5-ssl-tools) - various standalone perl scripts
* [gottburgm/Exploits](https://github.com/gottburgm/Exploits) - Containing Self Made Perl Reproducers / PoC Codes
* [xme/pastemon](https://github.com/xme/pastemon) - pastebin.com Content Monitoring Tool
* [percx/Praeda](https://github.com/percx/Praeda)
* [xme/hoover](https://github.com/xme/hoover) - Wireless Probe Requests Sniffer
* [anestisb/WeBaCoo](https://github.com/anestisb/WeBaCoo) - Web Backdoor Cookie Script-Kit
* [yuri-gushin/Roboo](https://github.com/yuri-gushin/Roboo) - Roboo - HTTP Robot Mitigator
* [deepakdaswani/whatsapp_discover](https://github.com/deepakdaswani/whatsapp_discover) - "Whatsapp Discover" is a tool for getting phone numbers of devices using Whatsapp by real time sniffing from an interface (disabled in this first version) or from a list of pcap files, which can be processed in batch
* [schweikert/postgrey](https://github.com/schweikert/postgrey) - Postfix Greylisting Policy-Daemon
* [Raikia/SMBCrunch](https://github.com/Raikia/SMBCrunch) - 3 tools that work together to simplify reconaissance of Windows File Shares
* [pentestmonkey/smtp-user-enum](https://github.com/pentestmonkey/smtp-user-enum) - Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.
* [nerodtm/ReconCobra---Complete-Automated-Pentest-Framework-For-Information-Gathering](https://github.com/nerodtm/ReconCobra---Complete-Automated-Pentest-Framework-For-Information-Gathering) - ReconCobra Reconcobra is Foot printing software for Ultimate Information Gathering Kali, Parrot OS, Black Arch, Termux, Android Led TV Interface Software have 82 Options with full automation with powerful information gathering capability Brief Introduction ReconCobra is useful in Banks, Private Organisations and Ethical hacker personnel for legal auditing. It serves as a defense method to find as much as information possible for gaining unauthorised access and intrusion. With the emergence of more advanced technology, cybercriminals have also found more ways to get into the system of many organizations. ReconCobra software can audit, firewall behaviour, if it is leaking backend machines/server and replying pings, it can find internal and external networks where many software’s like erp, mail firewalls are installed, exposing servers so it do Footprinting, Scanning & Enumeration as much as possible of target, to discover and collect most possible informations like username, web technologies, files, endpoint, api and much more.
* [Aron-Tn/Mega-Bot](https://github.com/Aron-Tn/Mega-Bot) - [NEW] : Mega Bot ☣ Scanner & Auto Exploiter
* [infoslack/sec-tools](https://github.com/infoslack/sec-tools) - Docker images for infosec tools
* [bestpractical/rtir](https://github.com/bestpractical/rtir)
* [reider-roque/pentest-tools](https://github.com/reider-roque/pentest-tools) - Penetration testing scripts
* [poerschke/Uniscan](https://github.com/poerschke/Uniscan) - Uniscan web vulnerability scanner
* [irsl/dfwfw](https://github.com/irsl/dfwfw) - Docker Firewall Framework
* [ezarko/opendlp](https://github.com/ezarko/opendlp)
* [0x90/vpn-arsenal](https://github.com/0x90/vpn-arsenal) - VPN pentest tools and scripts
* [MustLive/DAVOSET](https://github.com/MustLive/DAVOSET) - DDoS attacks via other sites execution tool (DAVOSET) - it is command line tool for conducting DDoS attacks on the sites via Abuse of Functionality and XML External Entities vulnerabilities at other sites.
* [philsmd/itunes_backup2hashcat](https://github.com/philsmd/itunes_backup2hashcat) - Extract the information needed from the Manifest.plist files to convert it to hashes compatible with hashcat
* [cldrn/davtest](https://github.com/cldrn/davtest) - davtest (improved)- Exploits WebDAV folders
* [htrgouvea/spellbook](https://github.com/htrgouvea/spellbook) - Framework for rapid development of offensive security tools
* [Qualys/community](https://github.com/Qualys/community) - Qualys community open source scripts. Please note these are provided as-is and are not supported.
* [FastVPSEestiOu/Antidoto](https://github.com/FastVPSEestiOu/Antidoto) - Linux antimalware and antirootkit tool
* [tanjiti/FingerPrint](https://github.com/tanjiti/FingerPrint) - web应用指纹识别
* [CiscoCXSecurity/udp-proto-scanner](https://github.com/CiscoCXSecurity/udp-proto-scanner) - udp-proto-scanner is a Perl script which discovers UDP services by sending triggers to a list of hosts
* [owasp-modsecurity/ModSecurity-apache](https://github.com/owasp-modsecurity/ModSecurity-apache) - ModSecurity v3 Apache Connector
* [convisolabs/CVE-2021-22204-exiftool](https://github.com/convisolabs/CVE-2021-22204-exiftool) - Python exploit for the CVE-2021-22204 vulnerability in Exiftool
* [interference-security/kali-windows-binaries](https://github.com/interference-security/kali-windows-binaries) - Windows binaries from Kali Linux : http://git.kali.org/gitweb/?p=packages/windows-binaries.git;a=summary
* [noxxi/p5-app-dubioushttp](https://github.com/noxxi/p5-app-dubioushttp) - use ambiguous HTTP to circumvent security systems
* [0x646e78/bluesniff](https://github.com/0x646e78/bluesniff) - Bluesniff
* [rwx-777/WPA2-FritzBox-Pswd-Wordlist-Generator](https://github.com/rwx-777/WPA2-FritzBox-Pswd-Wordlist-Generator) - This Script will produce all of the WPA2 Passwords used by various Router companies aswell as Fritzbox. All of these Passwords will be 16 Numbers in length. So it could get a bit large.
* [mfazrinizar/FazScan](https://github.com/mfazrinizar/FazScan) - | FazScan is a Perl program to do some vulnerability scanning and pentesting |
* [spamhaus/spamassassin-dqs](https://github.com/spamhaus/spamassassin-dqs) - Spamhaus code for the Spamassassin plugin. See https://docs.spamhaustech.com/40-real-world-usage/SpamAssassin/000-intro.html
* [d4t4king/lynis-report-converter](https://github.com/d4t4king/lynis-report-converter) - Manageable report from lynis text output, in various formats.
* [postfwd/postfwd](https://github.com/postfwd/postfwd) - Postfwd - http://www.postfwd.org
* [cmlh/Maltego-Facebook](https://github.com/cmlh/Maltego-Facebook) - Maltego Local Transforms for Facebook
* [TheBeastofwar/linuxhacker](https://github.com/TheBeastofwar/linuxhacker) - 一款linux 内网渗透辅助工具
* [codewatchorg/cpscam](https://github.com/codewatchorg/cpscam) - Bypass captive portals by impersonating inactive users
* [hknutzen/Netspoc](https://github.com/hknutzen/Netspoc) - A network security policy compiler. Netspoc is targeted at environments with a large number of firewalls and admins. Firewall rules are derived from a single rule set. Supported are Cisco IOS, ASA, Palo-Alto, VMware NSX gateway firewalls and IPTables.
* [mrash/fwsnort](https://github.com/mrash/fwsnort) - Application Layer IDS/IPS with iptables
* [xxgrunge/sqlninja](https://github.com/xxgrunge/sqlninja) - SQL Injection Tool
* [wireghoul/doona](https://github.com/wireghoul/doona) - Network based protocol fuzzer
* [corazawaf/coraza-nginx](https://github.com/corazawaf/coraza-nginx) - Coraza NGINX Experimental Connector
* [Moham3dRiahi/WPGrabInfo](https://github.com/Moham3dRiahi/WPGrabInfo) - WP Grab Info v2
* [htrgouvea/nozaki](https://github.com/htrgouvea/nozaki) - HTTP fuzzer engine security oriented
* [htrgouvea/zarn](https://github.com/htrgouvea/zarn) - A lightweight static security analysis tool for modern Perl Apps
* [batchmcnulty/uberscan](https://github.com/batchmcnulty/uberscan) - Security program for recovering passwords and pen-testing servers, routers and IoT devices using brute-force password attacks.
* [userjack6880/Open-Report-Parser](https://github.com/userjack6880/Open-Report-Parser) - A Perl based tool to parse DMARC reports from an IMAP mailbox or from the filesystem, and insert the information into a database. Derived from Techsneeze's dmarcts-report-parser
* [cqHack/DDoS-Script](https://github.com/cqHack/DDoS-Script) - A script written in perl for ddos ​​with automatic detection of open and vulnerable port that gives up to 1.5 gb packages / s
* [dr-iman/Drupal-Hunter](https://github.com/dr-iman/Drupal-Hunter) - Drupal Exploiter Tool (Drupal Hunter)
* [modernistik/Nmap-Parser](https://github.com/modernistik/Nmap-Parser) - Parse nmap scan data with Perl (official repo)
* [msimerson/mail-dmarc](https://github.com/msimerson/mail-dmarc) - Mail::DMARC, a complete DMARC implementation in Perl
* [unspecific/nmap-tools](https://github.com/unspecific/nmap-tools) - Set of tools written in Perl circa 2002
* [pentestmonkey/ident-user-enum](https://github.com/pentestmonkey/ident-user-enum) - ident-user-enum is a simple PERL script to query the ident service (113/TCP) in order to determine the owner of the process listening on each TCP port of a target system.
* [htrgouvea/harpoon](https://github.com/htrgouvea/harpoon) - [W.I.P] An ecosystem of crawlers for detecting: leaks, sensitive data exposure and attempts exfiltration of data
* [BishopFox/ProxyListReliabilityCheck](https://github.com/BishopFox/ProxyListReliabilityCheck) - Perl script to test the reliability of a list of open web proxies.
* [The-McGrail-Foundation/MIMEDefang](https://github.com/The-McGrail-Foundation/MIMEDefang) - MIMEDefang is an e-mail filtering tool that works with the Sendmail “Milter” library. MIMEDefang lets you express your filtering policies in Perl rather than C, making it quick and easy to filter or manipulate your mail.
* [CiscoCXSecurity/ssl-cipher-suite-enum](https://github.com/CiscoCXSecurity/ssl-cipher-suite-enum) - ssl-cipher-suite enum is a Perl script to enumerate supported SSL cipher suites supported by network services (principally HTTPS)
* [briandfoy/cpan-security-advisory](https://github.com/briandfoy/cpan-security-advisory) - CPAN Security Advisory Database
* [vti/cpan-audit-deprecated](https://github.com/vti/cpan-audit-deprecated) - Check CPAN modules for known security vulnerabilities *(archived)*
* [htrgouvea/fuzzpm](https://github.com/htrgouvea/fuzzpm) - Differential Fuzzer to hunt for logic bugs on Perl Modules
* [KylerCondran/WarCappin](https://github.com/KylerCondran/WarCappin) - WiFi Hacking: Autonomously man in the middle deauthenticate WPA2 wireless networks and packet capture the three way handshake for offline cracking using Kali Linux and a WiFi antenna.
* [LetUsFsck/protokill](https://github.com/LetUsFsck/protokill) - Here's a Perl script that can either be used as a protocol fuzzer, or a DoS tool
* [xme/known_hosts_bruteforcer](https://github.com/xme/known_hosts_bruteforcer) - Perl script to bruteforce SSH known_hosts files.
* [riusksk/StrutScan](https://github.com/riusksk/StrutScan) - Struts2 Vuls Scanner base perl script
* [hndko/revsliderautoexploiter](https://github.com/hndko/revsliderautoexploiter) - Tools Auto Exploiter Plugin Revslider
* [dgerzo/bruteforceblocker](https://github.com/dgerzo/bruteforceblocker) - BruteForceBlocker is a perl script, that works along with pf firewall. Its main purpose is to block SSH bruteforce attacks via firewall.
* [annmuor/freeaudit](https://github.com/annmuor/freeaudit) - Packaging audit toolkit using vulners.com vulnerability database
* [briandfoy/cpan-audit](https://github.com/briandfoy/cpan-audit) - Check CPAN modules for known security vulnerabilities
* [cyberisltd/ProxyDetect](https://github.com/cyberisltd/ProxyDetect) - Perl script to detect the existence of transparent proxies
* [GHubgenius/slowloris.pl](https://github.com/GHubgenius/slowloris.pl) - A new DOS Perl Programm
* [brianwrf/myPadBuster](https://github.com/brianwrf/myPadBuster) - It is a Python+Perl script to exploit ASP.net Padding Oracle vulnerability.
* [vti/cpan-audit](https://github.com/vti/cpan-audit) - Check CPAN modules for known security vulnerabilities
* [Moham3dRiahi/XBruteForcer](https://github.com/Moham3dRiahi/XBruteForcer) - X Brute Forcer Tool 🔓 WordPress , Joomla , DruPal , OpenCart , Magento

### Authentication and Authorization

* [ovh/the-bastion](https://github.com/ovh/the-bastion) - Authentication, authorization, traceability and auditability for SSH accesses.
* [mrash/fwknop](https://github.com/mrash/fwknop) - Single Packet Authorization > Port Knocking
* [SkyLothar/lua-resty-jwt](https://github.com/SkyLothar/lua-resty-jwt) - JWT For The Great Openresty
* [nginxinc/nginx-openid-connect](https://github.com/nginxinc/nginx-openid-connect) - Reference implementation of OpenID Connect integration for NGINX Plus
* [AndriiGrytsenko/openssh-ldap-publickey](https://github.com/AndriiGrytsenko/openssh-ldap-publickey) - Wrapper for OpenSSH to store public keys inside the OpenLDAP entry.
* [fastmail/authentication_milter](https://github.com/fastmail/authentication_milter) - Email Authentication by SPF/DKIM/DMARC etc.
* [jimdigriz/freeradius-oauth2-perl](https://github.com/jimdigriz/freeradius-oauth2-perl) - FreeRADIUS OAuth2 (OpenID Connect) using rlm_perl
* [trentm/node-ldapauth](https://github.com/trentm/node-ldapauth) - **UNMAINTAINED.** Simple node.js module to authenticate against an LDAP server
* [exflickr/GodAuth](https://github.com/exflickr/GodAuth) - Authentication layer for web app tools
* [proxmox/pve-access-control](https://github.com/proxmox/pve-access-control) - Access control framework
* [lyokato/p5-oauth-lite2](https://github.com/lyokato/p5-oauth-lite2) - Perl Library for OAuth 2.0
* [bigpresh/Dancer-Plugin-Auth-Extensible](https://github.com/bigpresh/Dancer-Plugin-Auth-Extensible) - Authentication framework for Dancer-based web applications

### Reverse Engineering

* [keydet89/RegRipper3.0](https://github.com/keydet89/RegRipper3.0) - RegRipper3.0
* [samyk/samytools](https://github.com/samyk/samytools) - Simple tools to make reverse engineering and console cowboying easier, primarily by data translation and manipulation + file handle piping. Mostly *nix tools with an emphasis on macOS.
* [iafan/Hacksby](https://github.com/iafan/Hacksby) - Description and unofficial implementation of Furby's audio protocol
* [hn/reolink-camera](https://github.com/hn/reolink-camera) - Reolink RLC-410-5MP IP camera reverse engineered technical details
* [librespot-org/spotify-connect-resources](https://github.com/librespot-org/spotify-connect-resources) - A repository to hold any data/stuff related to reversing the Spotify Connect protocol. Mostly just data dumps at the moment, but if you have something to add to it, be it an implementation, information or just another data dump, make a PR and I will add it asap.
* [keydet89/Tools](https://github.com/keydet89/Tools) - Tools from WFA 4/e, timeline tools, etc.
* [XlogicX/m2elf](https://github.com/XlogicX/m2elf) - Converts Machine Code to x86 (32-bit) Linux executable (auto-wrapping with ELF headers)
* [keydet89/RegRipper4.0](https://github.com/keydet89/RegRipper4.0) - RegRipper4.0
* [RealityNet/hotoloti](https://github.com/RealityNet/hotoloti) - documentation, scripts, tools related to Zena Forensics (http://blog.digital-forensics.it)
* [jindroush/albituzka](https://github.com/jindroush/albituzka) - Reverzní inženýrství Albi Kouzelného čtení
* [openvehicles/CAN-RE-Tool](https://github.com/openvehicles/CAN-RE-Tool) - A reverse engineering tool for systems based on CAN bus communications
* [brimorlabs/rdpieces](https://github.com/brimorlabs/rdpieces) - The home of the BriMor Labs rdpieces Perl script that tries to rebuild parsed RDP Bitmap Cache images
* [keydet89/Events-Ripper](https://github.com/keydet89/Events-Ripper) - Project based on RegRipper, to extract add'l value/pivot points from TLN events file
* [MahdiSafsafi/opcodesDB](https://github.com/MahdiSafsafi/opcodesDB) - x86-64 | ARM (AArch32/AArch64/THUMB) full instruction set.
* [Falseclock/UEFI-dumper](https://github.com/Falseclock/UEFI-dumper) - simple perl script to get access to your Insyde Bios hidden menus
* [dpavlin/perl-Mifare-MAD](https://github.com/dpavlin/perl-Mifare-MAD) - pretty print Mifare Classic MAD - Mifare Application Directory from dump files

## Concurrency and Performance

### Concurrency and Parallelism

* [rcaputo/poe](https://github.com/rcaputo/poe) - POE is a portable perl multitasking and networking framework for any event loop.
* [rcaputo/reflex](https://github.com/rcaputo/reflex) - Reflex is a class library for writing reactive Perl programs. It provides base classes for reactive objects, and specific subclasses for various tasks.
* [marioroy/mce-perl](https://github.com/marioroy/mce-perl) - Many-Core Engine for Perl
* [stevan/promises-perl](https://github.com/stevan/promises-perl) - An implementation of Promises in Perl
* [eilara/Rx.pl](https://github.com/eilara/Rx.pl) - Microsoft Reactive Extensions clone for Perl
* [dluxhu/perl-parallel-forkmanager](https://github.com/dluxhu/perl-parallel-forkmanager) - Parallel::ForkManager
* [hakobe/p5-Fiber](https://github.com/hakobe/p5-Fiber) - Ruby like Fiber on Perl
* [sanko/Acme-Parataxis.pm](https://github.com/sanko/Acme-Parataxis.pm) - A Perl concurrency model

## Testing and Quality

### Testing

* [linux-test-project/lcov](https://github.com/linux-test-project/lcov) - LCOV
* [rjust/defects4j](https://github.com/rjust/defects4j) - A Database of Real Faults and an Experimental Infrastructure to Enable Controlled Experiments in Software Engineering Research
* [jonreid/XcodeCoverage](https://github.com/jonreid/XcodeCoverage) - Code coverage for Xcode projects (Objective-C only)
* [openresty/test-nginx](https://github.com/openresty/test-nginx) - Data-driven test scaffold for Nginx C module and OpenResty Lua library development
* [os-autoinst/openQA](https://github.com/os-autoinst/openQA) - openQA web-frontend, scheduler and tools.
* [liuhuigmail/GrowingBugRepository](https://github.com/liuhuigmail/GrowingBugRepository) - A bug repository that keeps growing
* [yaml/yaml-test-suite](https://github.com/yaml/yaml-test-suite) - Comprehensive, language independent Test Suite for YAML
* [os-autoinst/os-autoinst](https://github.com/os-autoinst/os-autoinst) - OS-level test automation
* [Test-More/test-more](https://github.com/Test-More/test-more) - Test2, Test::More, Test::Simple and Test::Builder Perl modules for writing tests
* [nginx/nginx-tests](https://github.com/nginx/nginx-tests) - Test suite for nginx.
* [FFmpeg/fateserver](https://github.com/FFmpeg/fateserver) - Mirror of git://git.ffmpeg.org/fateserver
* [pjcj/Devel--Cover](https://github.com/pjcj/Devel--Cover) - Code coverage metrics for Perl
* [os-autoinst/os-autoinst-distri-opensuse](https://github.com/os-autoinst/os-autoinst-distri-opensuse) - os-autoinst test cases for openSUSE
* [lvc/api-sanity-checker](https://github.com/lvc/api-sanity-checker) - An automatic generator of basic unit tests for a C/C++ library
* [matrix-org/sytest](https://github.com/matrix-org/sytest) - Black-box integration testing for Matrix homeservers
* [agentzh/cheater](https://github.com/agentzh/cheater) - A tool and a language that help generating random complex database instance based on predefined rules
* [pherkin/test-bdd-cucumber-perl](https://github.com/pherkin/test-bdd-cucumber-perl) - Test::BDD::Cucumber - Cucumber in Perl
* [tokuhirom/Test-TCP](https://github.com/tokuhirom/Test-TCP) - Test::TCP for perl
* [Perl-Toolchain-Gang/Test-Harness](https://github.com/Perl-Toolchain-Gang/Test-Harness) - Run Perl standard test scripts with statistics
* [kingpong/perl-Test-Spec](https://github.com/kingpong/perl-Test-Spec) - rSpec-like test system for Perl
* [lukec/cpan-selenium-rc-perl](https://github.com/lukec/cpan-selenium-rc-perl) - Test-WWW-Selenium Perl Selenium RC Driver
* [kesor/p5-cucumber](https://github.com/kesor/p5-cucumber) - Cucumber for Perl 5
* [gugod/Test-Continuous](https://github.com/gugod/Test-Continuous) - (Perl) Run your tests suite continusouly when developing.
* [AndyA/Test-Harness](https://github.com/AndyA/Test-Harness) - Run Perl standard test scripts with statistics
* [mjgardner/test-class](https://github.com/mjgardner/test-class) - Test::Class - an xUnit testing framework for Perl 5.x
* [cpan-testers/CPAN-Reporter](https://github.com/cpan-testers/CPAN-Reporter) - (Perl) Adds CPAN Testers reporting to CPAN.pm

## Utilities

### Command Line Tools

* [major/MySQLTuner-perl](https://github.com/major/MySQLTuner-perl) - MySQLTuner is a script written in Perl that will assist you with your MySQL configuration and make recommendations for increased performance and stability.
* [curl/trurl](https://github.com/curl/trurl) - a command line tool for URL parsing and manipulation.
* [jfcoz/postgresqltuner](https://github.com/jfcoz/postgresqltuner) - Simple script to analyse your PostgreSQL database configuration, and give tuning advice
* [beyondgrep/ack2](https://github.com/beyondgrep/ack2) - **ack 2 is no longer being maintained. ack 3 is the latest version.**
* [smxi/inxi](https://github.com/smxi/inxi) - inxi is a full featured CLI system information tool. It is available in most Linux distribution repositories, and does its best to support the BSDs. *(archived)*
* [creaktive/rainbarf](https://github.com/creaktive/rainbarf) - it's like Rainmeter, but for CLI!
* [skx/sysadmin-util](https://github.com/skx/sysadmin-util) - Tools for Linux/Unix sysadmins. *(archived)*
* [circulosmeos/gdown.pl](https://github.com/circulosmeos/gdown.pl) - Google Drive direct download of big files
* [nferraz/st](https://github.com/nferraz/st) - simple statistics from the command line
* [beyondgrep/ack3](https://github.com/beyondgrep/ack3) - ack is a grep-like search tool optimized for source code.
* [beyondgrep/ack1](https://github.com/beyondgrep/ack1) - This repository is for ack 1.x, which is **no longer being maintained**. DO NOT SUBMIT ISSUES HERE. ack 2.0 has a new GitHub project at
* [vsespb/mt-aws-glacier](https://github.com/vsespb/mt-aws-glacier) - Perl Multithreaded Multipart sync to Amazon Glacier
* [trapd00r/ls--](https://github.com/trapd00r/ls--) - ls on steroids
* [tnalpgge/rank-amateur-cowsay](https://github.com/tnalpgge/rank-amateur-cowsay) - Fork me if you want to maintain cowsay. *(archived)*
* [anhsirk0/fetch-master-6000](https://github.com/anhsirk0/fetch-master-6000) - Simple Dilbert themed system info-fetching tool
* [benbernard/RecordStream](https://github.com/benbernard/RecordStream) - commandline tools for slicing and dicing JSON records.
* [openresty/resty-cli](https://github.com/openresty/resty-cli) - Fancy command-line utilities for OpenResty
* [cowsay-org/cowsay](https://github.com/cowsay-org/cowsay) - apjanke's fork of the classic cowsay project
* [briandfoy/PerlPowerTools](https://github.com/briandfoy/PerlPowerTools) - Perl Power Tools
* [datacharmer/mysql-sandbox](https://github.com/datacharmer/mysql-sandbox) - Quick and painless install of one or more MySQL servers in the same host. *(archived)*
* [colorgcc/colorgcc](https://github.com/colorgcc/colorgcc) - colorgcc is a perl script to colorize gcc output. I'm collecting random patches and changes
* [gregkh/bti](https://github.com/gregkh/bti) - bash twitter ididocy
* [jimeh/manservant](https://github.com/jimeh/manservant) - Browse man pages in style with your personal manservant.
* [s-aska/dropbox-api-command](https://github.com/s-aska/dropbox-api-command) - command line interface to access Dropbox API *(archived)*
* [kiamazi/kateb](https://github.com/kiamazi/kateb) - Install and update free Farsi fonts
* [ungive/media-control](https://github.com/ungive/media-control) - Control and observe media playback from the command line
* [Wadauk/scihub_ck](https://github.com/Wadauk/scihub_ck) - A tiny tool for checking the working domain of sci-hub
* [coryarcangel/Pizza-Party-0.1.b](https://github.com/coryarcangel/Pizza-Party-0.1.b) - Order pizza over the commandline (circa 2004)
* [HariSekhon/DevOps-Perl-tools](https://github.com/HariSekhon/DevOps-Perl-tools) - 25+ DevOps CLI Tools - Anonymizer, SQL ReCaser (MySQL, PostgreSQL, AWS Redshift, Snowflake, Apache Drill, Hive, Impala, Cassandra CQL, Microsoft SQL Server, Oracle, Couchbase N1QL, Dockerfiles), Hadoop HDFS & Hive tools, Solr/SolrCloud CLI, Nginx stats & HTTP(S) URL watchers for load-balanced web farms, Linux tools etc.
* [kazuho/kaztools](https://github.com/kazuho/kaztools) - shellscripts and utilities for myself
* [HariSekhon/Spotify-tools](https://github.com/HariSekhon/Spotify-tools) - Spotify Tools - Playlists Backups, Spotify CLI, URI translator, duplication detection / removal, API search queries, API automation etc.
* [jeremija/unipicker](https://github.com/jeremija/unipicker) - Search unicode characters in console and copy to clipboard
* [raszi/colorize](https://github.com/raszi/colorize) - Log colorizer perl script
* [trapd00r/utils](https://github.com/trapd00r/utils) - Small useful utilities for everyday work
* [peterkeen/calorific](https://github.com/peterkeen/calorific) - Command-line nutrient tracking tool *(archived)*
* [andrewnimmo/rick-sanders-imap-tools](https://github.com/andrewnimmo/rick-sanders-imap-tools) - What is the IMAP Tools Set? It is a set of Perl programs for use with IMAP servers.
* [lhost/sendxmpp](https://github.com/lhost/sendxmpp) - perl-script to send xmpp (jabber), similar to what mail(1) does for mail.
* [gnp/psh](https://github.com/gnp/psh) - Perl Shell (psh) — Aspiring to be your primary login shell
* [grantm/bcvi](https://github.com/grantm/bcvi) - Back-channel vi
* [tobert/perl-ssh-tools](https://github.com/tobert/perl-ssh-tools) - A more capable DSH / cluster ssh suite
* [kraih/kefctl](https://github.com/kraih/kefctl) - Command line application for controlling KEF speakers
* [duckduckgo/p5-app-duckpan](https://github.com/duckduckgo/p5-app-duckpan) - DuckDuckHack OpenSource Development Application *(archived)*
* [zehm/sendEmail](https://github.com/zehm/sendEmail) - SendEmail is a lightweight, command line SMTP email client. If you have the need to send email from a command line, this free program is perfect: simple to use and feature rich. It was designed to be used in bash scripts, batch files, Perl programs and web sites, but is quite adaptable and will likely meet your requirements. SendEmail is written in Perl and is unique in that it requires NO MODULES. It has an intuitive and flexible set of command-line options, making it very easy to learn and use. SendEmail is licensed under the GNU GPL, either version 2 of the License or (at your option) any later version. [Supported Platforms: Linux, BSD, OS X, Windows 98, Windows NT, Windows 2000, & Windows XP]
* [kablamo/git-spark](https://github.com/kablamo/git-spark) - Plot your commit history on the command line with sparklines. A mash up of git and spark and Perl.
* [ap/perldoc-complete](https://github.com/ap/perldoc-complete) - A bash completion helper for perldoc
* [swannman/pdf2gerb](https://github.com/swannman/pdf2gerb) - Perl script converts PDF files to Gerber format
* [rjbs/App-Cmd](https://github.com/rjbs/App-Cmd) - perl framework for testable, extensible command line apps
* [cpan-authors/speedtest](https://github.com/cpan-authors/speedtest) - Perl CLI for speedtest.net
* [Easy-Forex/Verify-emails](https://github.com/Easy-Forex/Verify-emails) - Quick perl script to check a list of email addresses for valid and bogus.
* [kngenie/ias3upload](https://github.com/kngenie/ias3upload) - simple Perl script for uploading files to Internet Archive through its S3-like interface
* [adobe-type-tools/perl-scripts](https://github.com/adobe-type-tools/perl-scripts) - Command-line Perl Scripts
* [aartoni/schema2ldif](https://github.com/aartoni/schema2ldif) - schema2ldif : tool to convert .schema to .ldif files and mange them live into an openldap server
* [gbxyz/rdapper](https://github.com/gbxyz/rdapper) - A command-line RDAP client.
* [micans/bash-utils](https://github.com/micans/bash-utils) - Unix terminal histograms, sequencing depth and bar charts (hissyfit). Small data/file munge, morph, find and count scripts/functions in various languages, mostly bash and perl. For apparix see the apparix repository that is a sibling to this one.
* [sushdm/git_svn_externals](https://github.com/sushdm/git_svn_externals) - A perl script to clone an SVN repository with externals, using git-svn
* [licheng/gccfilter](https://github.com/licheng/gccfilter) - gccfilter is a perl filter to colorize and simplify (or expand) gcc diagnostic messages. gccfilter is particularly aimed at g++ (i.e. dealinging with C++) messages which can contain lot of template-related errors or warnings difficult to sort out.
* [Fourmilab/unum](https://github.com/Fourmilab/unum) - Utility for looking up Unicode characters and HTML entities by code, name, block, or description. Written in Perl, compatible with almost any system that runs Perl.
* [ironcamel/App-p](https://github.com/ironcamel/App-p) - Steroids for your perl one-liners. Does that mean steroids for your steroids? Is that even possible?
* [xsawyerx/gitflux](https://github.com/xsawyerx/gitflux) - A Perl port of gitflow. Really? Yes, really!

### Logging and Configuration

* [magenx/Magento-mysql](https://github.com/magenx/Magento-mysql) - Magento default mysql settings
* [yaoweibin/nginx_syslog_patch](https://github.com/yaoweibin/nginx_syslog_patch) - add the full syslog feature to Nginx
* [mschilli/log4perl](https://github.com/mschilli/log4perl) - Log4j Implementation For Perl
* [katzgrau/chip](https://github.com/katzgrau/chip) - A log file multiplexer and monitor. Tail multiple remote or local log files, set actions, and more. A friend to every developer and system admin. Alpha.
* [tagomoris/fluent-agent-lite](https://github.com/tagomoris/fluent-agent-lite) - Lightweight log delivery agent works w/ fluentd
* [PaulWay/lnav-formats](https://github.com/PaulWay/lnav-formats) - Log format description files for lnav
* [dod38fr/config-model](https://github.com/dod38fr/config-model) - Perl module to create configuration editor with semantic validation
* [sarahkadar/pflogsumm](https://github.com/sarahkadar/pflogsumm) - NOT MAINTAINED *(archived)*
* [fluent/fluent-logger-perl](https://github.com/fluent/fluent-logger-perl) - A structured logger for Fluentd (Perl)
* [auduny/statpipe](https://github.com/auduny/statpipe) - Poor mans Splunk. Command line real time statistics while tailing logs

### Text Processing

* [tobie/ua-parser](https://github.com/tobie/ua-parser) - A multi-language port of Browserscope's user agent parser. *(archived)*
* [brucemiller/LaTeXML](https://github.com/brucemiller/LaTeXML) - LaTeXML: a TeX and LaTeX to XML/HTML/ePub/MathML translator.
* [fletcher/MultiMarkdown](https://github.com/fletcher/MultiMarkdown) - This project is now deprecated. Please use MultiMarkdown-7 instead!
* [neldredge/mathgen](https://github.com/neldredge/mathgen) - Generate random nonsense math papers
* [devd/Academic-Writing-Check](https://github.com/devd/Academic-Writing-Check) - check for passive words, weasel words, duplicate words, typographical errors and words strunk & white don't like
* [en-wl/wordlist](https://github.com/en-wl/wordlist) - English Speller Database (ESDB)
* [OpenCageData/address-formatting](https://github.com/OpenCageData/address-formatting) - templates to format geographic addresses
* [norbusan/kobo-ja-dict-enhance](https://github.com/norbusan/kobo-ja-dict-enhance) - Enhance built-in Japanese dictionaries from Kobo with English definitions
* [norbusan/texlive-rewrite](https://github.com/norbusan/texlive-rewrite) - Rewrite of some core scripts in TeX Live from shell to perl
* [latex2html/latex2html](https://github.com/latex2html/latex2html) - Converts LaTeX documents to HTML
* [sbosio/rla-es](https://github.com/sbosio/rla-es) - Recursos lingüísticos abiertos del español
* [acl-org/ACLPUB](https://github.com/acl-org/ACLPUB) - The official tool for creating proceedings for conferences of the Association for Computational Linguistics (ACL).
* [serge-community/serge](https://github.com/serge-community/serge) - Continuous localization platform
* [naoya/md2inao](https://github.com/naoya/md2inao) - Convert markdown to inao-format for WEB+DB PRESS
* [meso-cacase/difff](https://github.com/meso-cacase/difff) - Webベースのテキスト比較ツール difff《ﾃﾞｭﾌﾌ》
* [rtomayko/shocco](https://github.com/rtomayko/shocco) - shocco is a quick-and-dirty, literate-programming-style documentation generator for / in POSIX shell *(archived)*
* [cpan-authors/Template2](https://github.com/cpan-authors/Template2) - Perl Template Toolkit v2
* [mquinson/po4a](https://github.com/mquinson/po4a) - Maintain the translations of your documentation with ease (PO for anything)
* [xslate/p5-Text-Xslate](https://github.com/xslate/p5-Text-Xslate) - Scalable template engine for Perl5
* [bagder/roffit](https://github.com/bagder/roffit) - converts nroff man pages to HTML
* [duckduckgo/duckduckgo-locales](https://github.com/duckduckgo/duckduckgo-locales) - Translation files for duckduckgo.com
* [SebastianSzturo/Dictionary-Development-Kit](https://github.com/SebastianSzturo/Dictionary-Development-Kit) - Mirror of Apple's Dictionary Development Kit
* [yanick/Template-Mustache](https://github.com/yanick/Template-Mustache) - Drawing Mustaches on Perl, for fun and profit
* [guo-yu/docor](https://github.com/guo-yu/docor) - a smart and tiny README maker using default manifest package.json
* [yoshiki/markdown2impress](https://github.com/yoshiki/markdown2impress) - markdown2impress is script to convert markdown into presentation using impress.js.
* [punchdrunker/iOSEmoji](https://github.com/punchdrunker/iOSEmoji) - information about unicode6 emoji used in iOS5 *(archived)*
* [alecchen/doxygen-lua](https://github.com/alecchen/doxygen-lua) - Make Doxygen support Lua *(archived)*
* [ap/titlecase](https://github.com/ap/titlecase) - John Gruber’s Title Case
* [fnord0/hURL](https://github.com/fnord0/hURL) - hexadecimal & URL encoder + decoder
* [jim-kirisame/jpgramma-cn-pdf-converter](https://github.com/jim-kirisame/jpgramma-cn-pdf-converter) - 一个将日语语法指南网页版转成pdf的小工具
* [libwww-perl/URI](https://github.com/libwww-perl/URI) - The Perl URI module
* [jonswar/perl-mason](https://github.com/jonswar/perl-mason) - Mason 2
* [Aralhach/bashobfus](https://github.com/Aralhach/bashobfus) - A small bash minifier/obfuscator written in Perl.
* [matteoacrossi/texprlcount](https://github.com/matteoacrossi/texprlcount) - Perl script that evaluates the word count of a tex document according to the PRL length guidelines
* [openresty/lemplate](https://github.com/openresty/lemplate) - OpenResty/Lua template framework implementing Perl's TT2 templating language
* [vti/text-haml](https://github.com/vti/text-haml) - Haml parser in Perl
* [dankogai/p5-encode](https://github.com/dankogai/p5-encode) - Encode - character encodings (for Perl 5.8 or better)
* [jjazzboss/colorbindiff](https://github.com/jjazzboss/colorbindiff) - A visual and colorized diff for binary files.
* [grantm/Algorithm-CouponCode](https://github.com/grantm/Algorithm-CouponCode) - Perl library to generate and validate 'CouponCode' strings
* [gonzoua/EBook-EPUB](https://github.com/gonzoua/EBook-EPUB) - EBook::EPUB perl module for generating EPUB document
* [fayland/perl-lingua-han](https://github.com/fayland/perl-lingua-han) - all Lingua::Han:: CPAN modules
* [libraryhackers/library-callnumber-lc](https://github.com/libraryhackers/library-callnumber-lc) - Perl and Python modules for normalizing Library of Congress call numbers
* [jric/epubtohtml](https://github.com/jric/epubtohtml) - A simple perl script to convert epub documents to documents that browsers can natively browse.
* [ajensenwaud/dbs-tools](https://github.com/ajensenwaud/dbs-tools) - Perl tools to transform account / transaction data from DBS Bank into proper CSV
* [koknat/dif](https://github.com/koknat/dif) - 'dif' is a Linux preprocessing front end to gvimdiff/meld/kompare
* [DrHyde/perl-modules-Number-Phone](https://github.com/DrHyde/perl-modules-Number-Phone) - Number::Phone and friends
* [rjbs/Mail-DeliveryStatus-BounceParser](https://github.com/rjbs/Mail-DeliveryStatus-BounceParser) - perl library to parse email bounce messages
* [fasheng/vimwiki2org](https://github.com/fasheng/vimwiki2org) - Convert VimWiki files to Emacs Org-Mode *(archived)*
* [mpeters/html-template](https://github.com/mpeters/html-template) - Perl HTML::Template module
* [bradchoate/text-textile](https://github.com/bradchoate/text-textile) - Text::Textile -- Perl module for handling Textile format
* [briandfoy/unicode-tussle](https://github.com/briandfoy/unicode-tussle) - Tom( Christiansen)'s Unicode Scripts So Life is Easier
* [rjbs/Email-MIME](https://github.com/rjbs/Email-MIME) - perl library for parsing MIME messages
* [jordan2175/doxygen-filter-perl](https://github.com/jordan2175/doxygen-filter-perl) - Doxygen::Filter::Perl - A perl code pre-filter for Doxygen

### Files and Operating System

* [jimsalterjrs/sanoid](https://github.com/jimsalterjrs/sanoid) - These are policy-driven snapshot management and replication tools which use OpenZFS for underlying next-gen storage. (Btrfs support plans are shelved unless and until btrfs becomes reliable.)
* [digint/btrbk](https://github.com/digint/btrbk) - Tool for creating snapshots and remote backups of btrfs subvolumes
* [linuxhw/hw-probe](https://github.com/linuxhw/hw-probe) - Probe for hardware, check operability and find drivers
* [oetiker/znapzend](https://github.com/oetiker/znapzend) - zfs backup with remote capabilities and mbuffer integration.
* [liske/needrestart](https://github.com/liske/needrestart) - Restart daemons after library updates.
* [pshved/timeout](https://github.com/pshved/timeout) - A script to measure and limit CPU time and memory consumption of black-box processes in Linux
* [pmqs/Fix-OneDrive-Zip](https://github.com/pmqs/Fix-OneDrive-Zip) - Fix OneDrive Zip files >4Gig
* [trapd00r/vidir](https://github.com/trapd00r/vidir) - edit directory in $EDITOR (better than vim . with netrw)
* [dimikot/dklab_realsync](https://github.com/dimikot/dklab_realsync) - dkLab RealSync: replicate developer's files over SSH in realtime
* [jollyjinx/ZFS-TimeMachine](https://github.com/jollyjinx/ZFS-TimeMachine) - TimeMachine style backup for ZFS
* [hjmangalam/parsyncfp](https://github.com/hjmangalam/parsyncfp) - follow-on to parsync (parallel rsync) with better startup perf
* [ap/rename](https://github.com/ap/rename) - Rename multiple files
* [jonmatifa/zfsmanager](https://github.com/jonmatifa/zfsmanager) - ZFS administration tool for Webmin
* [speed47/btrfs-list](https://github.com/speed47/btrfs-list) - Get a nice tree-style view of your btrfs subvolumes/snapshots, including their size, a la 'zfs list'
* [berekuk/Ubic](https://github.com/berekuk/Ubic) - Polymorphic service manager.
* [crucially/riakfuse](https://github.com/crucially/riakfuse) - Filesystem backed by riak
* [hjmangalam/parsyncfp2](https://github.com/hjmangalam/parsyncfp2) - MultiHost parallel rsync wrapper
* [anhsirk0/file-arranger](https://github.com/anhsirk0/file-arranger) - Simple & capable Directory arranger/cleaner
* [ido50/Svsh](https://github.com/ido50/Svsh) - Process supervision shell for daemontools, perp, s6 and runit
* [xtaran/unburden-home-dir](https://github.com/xtaran/unburden-home-dir) - Automatically unburden $HOME from caches, etc. Useful for $HOME on SSDs, small disks or slow NFS homes. Can be triggered via an hook in /etc/X11/Xsession.d/.
* [DE-IBH/imvirt](https://github.com/DE-IBH/imvirt) - detects several virtualizations
* [nephri/FreeNas-DiskList](https://github.com/nephri/FreeNas-DiskList) - FreeNas "Disklist" script for report informations about installed hard drives, volumes and partitions
* [subogero/rename](https://github.com/subogero/rename) - Perl rename as a separate package
* [symkat/Daemon-Control](https://github.com/symkat/Daemon-Control) - Daemon::Control - Create init scripts in Perl
* [bgoglin/lltag](https://github.com/bgoglin/lltag) - Automatic command-line mp3/ogg/flac file tagger and renamer
* [clip9/adbren](https://github.com/clip9/adbren) - adbren - Rename and organize anime using this AniDB API client written in perl
* [ingydotnet/io-all-pm](https://github.com/ingydotnet/io-all-pm) - All in One Perl IO
* [chicks-net/megamap](https://github.com/chicks-net/megamap) - MegaRAID® Linux drive map
* [takehaya/Sys-Ebpf](https://github.com/takehaya/Sys-Ebpf) - Sys::Ebpf is a pure-perl library to read, modify and load eBPF programs and attach them to various hooks in the Linux kernel.In other words eBPF Loader for written in Perl.
* [noordawod/gigasync](https://github.com/noordawod/gigasync) - Rsync-based Perl script to incrementally mirror enormous directory trees.
* [RalXYZ/moyu.sh](https://github.com/RalXYZ/moyu.sh) - Junk file generator script
* [Hopper262/classic-mac-utils](https://github.com/Hopper262/classic-mac-utils) - Perl scripts to handle resource forks and other old Mac formats.
* [mdom/squaretag](https://github.com/mdom/squaretag) - Tag files using just the file name *(archived)*
* [peterkeen/proclaunch](https://github.com/peterkeen/proclaunch) - A pure-perl process management system *(archived)*
* [sweharris/MMB_Utils](https://github.com/sweharris/MMB_Utils) - Perl library and utilities for manipulating BBC MMB and SSD files
* [petdance/file-next](https://github.com/petdance/file-next) - File::Next, a file finding module for Perl 5
* [pjf/ipc-system-simple](https://github.com/pjf/ipc-system-simple) - Perl module to make running system commands and capturing errors as simple as possible.
* [zfsonlinux/linux-kstat](https://github.com/zfsonlinux/linux-kstat) - Sun::Solaris::Kstat perl module for linux-zfs
* [yannk/ControlFreak](https://github.com/yannk/ControlFreak) - a process supervisor in Perl

### Automation and Scripting

* [ThePrimeagen/.dotfiles](https://github.com/ThePrimeagen/.dotfiles)
* [thoughtbot/rcm](https://github.com/thoughtbot/rcm) - rc file (dotfile) management
* [hexsum/Mojo-Webqq](https://github.com/hexsum/Mojo-Webqq) - 【重要通知：WebQQ将在2019年1月1日停止服务，此项目目前已停止维护，感谢大家四年来的一路陪伴】使用Perl语言（不会没关系）编写的smartqq/webqq客户端框架（非GUI），可通过插件提供基于HTTP协议的api接口供其他语言或系统调用
* [OreosLab/checkinpanel](https://github.com/OreosLab/checkinpanel) - 一个主要运行在 𝐞𝐥𝐞𝐜𝐕𝟐𝐏 或 𝐪𝐢𝐧𝐠𝐥𝐨𝐧𝐠 等定时面板，同时支持系统运行环境的签到项目（环境：𝑷𝒚𝒕𝒉𝒐𝒏 3.8+ / 𝑵𝒐𝒅𝒆.𝒋𝒔 10+ / 𝑩𝒂𝒔𝒉 4+ / 𝑶𝒑𝒆𝒏𝑱𝑫𝑲8 / 𝑷𝒆𝒓𝒍5）
* [hexsum/Mojo-Weixin](https://github.com/hexsum/Mojo-Weixin) - 使用Perl语言（不会没关系）编写的个人账号微信/weixin/wechat客户端框架（非GUI），可通过插件提供基于HTTP协议的api接口供其他语言或系统调用
* [aspiers/stow](https://github.com/aspiers/stow) - GNU Stow - mirror of savannah git repository occasionally with more bleeding-edge branches
* [dotphiles/dotphiles](https://github.com/dotphiles/dotphiles) - A community driven framework of dotfiles.
* [Tarrasch/zsh-autoenv](https://github.com/Tarrasch/zsh-autoenv) - Autoenv for zsh
* [statico/dotfiles](https://github.com/statico/dotfiles) - :floppy_disk: Ian's dotfiles, utils, and Zsh/Vim/tmux configs
* [tildeclub/tilde.club](https://github.com/tildeclub/tilde.club) - Code and documentation for setting up and managing a tilde.club server
* [jaagr/dots](https://github.com/jaagr/dots) - dotfiles for my local setup
* [irssi/scripts.irssi.org](https://github.com/irssi/scripts.irssi.org) - Script Repository for Irssi
* [electro7/dot_debian](https://github.com/electro7/dot_debian) - Config files for linux (debian based)
* [faiproject/fai](https://github.com/faiproject/fai) - non-interactive system to install, customize and manage Linux systems
* [autodl-community/autodl-irssi](https://github.com/autodl-community/autodl-irssi) - A community-driven fork of autodl-irssi
* [randileeharper/ggautoblocker](https://github.com/randileeharper/ggautoblocker) - Good Game Auto Blocker
* [theophile/SuperSlicer_to_Orca_scripts](https://github.com/theophile/SuperSlicer_to_Orca_scripts) - Script(s) to convert SuperSlicer data for use in Orca Slicer
* [hexchat/hexchat-addons](https://github.com/hexchat/hexchat-addons) - Plugins and scripts made for HexChat *(archived)*
* [tangledhelix/dotfiles](https://github.com/tangledhelix/dotfiles) - My dotfiles. My Precious.
* [pjf/exobrain](https://github.com/pjf/exobrain) - Automate your life with Exobrain
* [addy-dclxvi/void-bspwm-dotfiles](https://github.com/addy-dclxvi/void-bspwm-dotfiles) - My personal backup of my dotfiles (Void Linux).
* [justone/dotfiles](https://github.com/justone/dotfiles) - Dotfiles
* [untoldwind/alfred2-layout](https://github.com/untoldwind/alfred2-layout) - Alfred 2 Layout workflow
* [laravel-dojo/wagon](https://github.com/laravel-dojo/wagon) - 免安裝可攜的 Laravel 開發環境
* [WolverineFan/YNABLinuxInstall](https://github.com/WolverineFan/YNABLinuxInstall) - Install script for YNAB 4 on Linux
* [bluehost/wp-tools](https://github.com/bluehost/wp-tools) - Tools to backup and upgrade WordPress installations *(archived)*
* [shabble/irssi-scripts](https://github.com/shabble/irssi-scripts) - Repo to store some personal irssi scripts
* [lifeforms/irssi-smartfilter](https://github.com/lifeforms/irssi-smartfilter) - Irssi smart filter to selectively hide JOIN/QUIT in busy channels
* [trizen/perl-scripts](https://github.com/trizen/perl-scripts) - A nice collection of day-to-day Perl scripts.
* [zigdon/twirssi](https://github.com/zigdon/twirssi) - An irssi script allowing the use of Twitter from within the IRC client.
* [sorin-ionescu/dotfiles](https://github.com/sorin-ionescu/dotfiles) - My command line life.
* [justone/dfm](https://github.com/justone/dfm) - dotfiles manager
* [zigdon/xkcd-Bucket](https://github.com/zigdon/xkcd-Bucket) - Bucket is the channel bot for #xkcd
* [agentzh/sshbatch](https://github.com/agentzh/sshbatch) - SSH::Batch for cluster operations
* [mhop/fhem-mirror](https://github.com/mhop/fhem-mirror) - Branch 'master' is an unofficial read-only-mirror of https://svn.fhem.de/fhem/trunk which is updated once a day. (branch sf_old a mirror of the old repo: svn://svn.code.sf.net/p/fhem/code/trunk)
* [stuartcryan/advanced-google-maps-alfred-workflow](https://github.com/stuartcryan/advanced-google-maps-alfred-workflow) - Advanced Google Maps and Apple Maps Workflow for Alfred
* [ytoolshed/pogo](https://github.com/ytoolshed/pogo) - Pogo is an agent-based system for running interruptive commands safely on thousands of machines in parallel
* [jdavis/dotfiles](https://github.com/jdavis/dotfiles) - 🛠👾 Config files for various things
* [dabockster/Smackbook-Yosemite](https://github.com/dabockster/Smackbook-Yosemite) - Updated Smackbook script for OS X Yosemite *(archived)*
* [globau/logbot](https://github.com/globau/logbot) - IRC logging bot *(archived)*
* [moritz/ilbot](https://github.com/moritz/ilbot) - IRC logging bot and web frontend
* [matschaffer/profile](https://github.com/matschaffer/profile) - My Bash profile
* [melezhik/sparrow](https://github.com/melezhik/sparrow) - Sparrow - script distribution platform for Linux OS
* [ecnerwala/dotfiles](https://github.com/ecnerwala/dotfiles) - My dotfiles, managed by stow
* [metakirby5/.dots](https://github.com/metakirby5/.dots) - :computer: All of my dotfiles.
* [pragma-/pbot](https://github.com/pragma-/pbot) - A pragmatic Perl IRCv3 bot
* [soarpenguin/perl-scripts](https://github.com/soarpenguin/perl-scripts) - useful perl script and snippets of code.
* [fletcher/SimplenoteSync](https://github.com/fletcher/SimplenoteSync) - perl routine to sync folder of text files with your notes on Simplenote
* [ahloiscreamo/Illit](https://github.com/ahloiscreamo/Illit) - Dotfile for Dec 2022 | I3WM | Rosé Pine colorscheme
* [gnustavo/Git-Hooks](https://github.com/gnustavo/Git-Hooks) - Framework for implementing Git (and Gerrit) hooks
* [mlawren/githook-perltidy](https://github.com/mlawren/githook-perltidy) - Run perltidy as a Git pre-commit hook
* [Debian/devscripts](https://github.com/Debian/devscripts) - Mirror of https://salsa.debian.org/debian/devscripts.git
* [Izder456/dotfiles](https://github.com/Izder456/dotfiles) - My OpenBSD Dotfiles *(archived)*
* [greg-kennedy/dot_scr](https://github.com/greg-kennedy/dot_scr) - Perl process that records DOSBox movies of Windows 3.1 screensavers, and posts to Twitter.
* [johnkerl/scripts](https://github.com/johnkerl/scripts) - Productivity tools for Linux/Unix.
* [woodpeck/osm-revert-scripts](https://github.com/woodpeck/osm-revert-scripts) - A collection of Perl scripts to handle reverts on OpenStreetMap
* [Farow/hexchat-scripts](https://github.com/Farow/hexchat-scripts) - Perl scripts for HexChat
* [grickit/Gambot](https://github.com/grickit/Gambot) - Gambot is a modular IRC bot written in Perl.
* [MadsAlbertsen/miscperlscripts](https://github.com/MadsAlbertsen/miscperlscripts) - Small collection of random useful perl scripts
* [tobeychris/hipchat-room-message-APIv2](https://github.com/tobeychris/hipchat-room-message-APIv2) - This is a simple perl script that will use Hipchat's API v2 to message a room after passing in the room name, authentication token and a message. Also includes features for selecting the colour, notifying the room, passing in an html message, using a proxy and using API v1 should you so choose.

### General Purpose Libraries

* [thibaultcha/lua-resty-jit-uuid](https://github.com/thibaultcha/lua-resty-jit-uuid) - Fast and dependency-free UUID library for LuaJIT/ngx_lua
* [moose/Moose](https://github.com/moose/Moose) - Official repository for Moose
* [evalEmpire/perl5i](https://github.com/evalEmpire/perl5i) - A single module to fix as much of Perl 5 as possible in one go
* [stevan/p5-mop-redux](https://github.com/stevan/p5-mop-redux) - A(nother) MOP for Perl 5
* [stevan/p5-mop-original](https://github.com/stevan/p5-mop-original) - A MOP for Perl 5
* [PerlFFI/FFI-Platypus](https://github.com/PerlFFI/FFI-Platypus) - Write Perl bindings to non-Perl libraries with FFI. No XS required.
* [tobyink/p5-type-tiny](https://github.com/tobyink/p5-type-tiny) - Perl 5 distribution Type-Tiny; see homepage for downloads and documentation.
* [xslate/p5-Mouse](https://github.com/xslate/p5-Mouse) - Lightweight class builder for Perl, as a subset of Moose
* [dagolden/Capture-Tiny](https://github.com/dagolden/Capture-Tiny) - (Perl) Capture STDOUT and STDERR from Perl, XS or external programs
* [ingydotnet/mo-pm](https://github.com/ingydotnet/mo-pm) - Perl Micro Objects
* [awncorp/venus](https://github.com/awncorp/venus) - OO Standard Library for Perl 5
* [perl-workflow/perl-workflow](https://github.com/perl-workflow/perl-workflow) - Workflow - simple, flexible system to implement workflows/state machines
* [Dual-Life/autodie](https://github.com/Dual-Life/autodie) - Make functions succeed or die in Perl, with lexical scope.
* [vti/underscore-perl](https://github.com/vti/underscore-perl) - Underscore-perl is a Perl clone of Underscore.js
* [Dual-Life/Scalar-List-Utils](https://github.com/Dual-Life/Scalar-List-Utils) - Scalar::Util, List::Util and Sub::Util perl modules
* [Perl-Apollo/oshun](https://github.com/Perl-Apollo/oshun) - Declarative data validation for variables and subroutines
* [ashb/trycatch](https://github.com/ashb/trycatch) - 'Native' try {} catch {} semantics for perl using Devel::Declare
* [chromatic/Modern-Perl](https://github.com/chromatic/Modern-Perl) - The Modern::Perl CPAN Distribution
* [stevan/BreadBoard](https://github.com/stevan/BreadBoard) - Inversion of Control and Dependency Injection for Perl
* [Ovid/hop](https://github.com/Ovid/hop) - Higher Order Perl modules on the CPAN
* [Ovid/Role-Basic](https://github.com/Ovid/Role-Basic) - Roles in Perl. Nothing else.
* [graphviz-perl/Graph](https://github.com/graphviz-perl/Graph) - Perl class for direct graph data structures and algorithms
* [stevan/p5-MOP](https://github.com/stevan/p5-MOP) - A Meta Object Protocol for Perl 5
* [pflanze/functional-perl](https://github.com/pflanze/functional-perl) - Functional programming on Perl 5
* [tokuhirom/FormValidator-Lite](https://github.com/tokuhirom/FormValidator-Lite) - very lite and fast validation library for perl
* [typester/object-container-perl](https://github.com/typester/object-container-perl) - simple object container
* [sanko/Acme-Bitfield.pm](https://github.com/sanko/Acme-Bitfield.pm) - Bitmask for Tracking Boolean Sets

## Systems and Hardware

### Embedded and Firmware

* [hamishcoleman/thinkpad-ec](https://github.com/hamishcoleman/thinkpad-ec) - Infrastructure for examining and patching Thinkpad embedded controller firmware
* [lm-sensors/lm-sensors](https://github.com/lm-sensors/lm-sensors) - lm-sensors repository
* [winterheart/broadcom-bt-firmware](https://github.com/winterheart/broadcom-bt-firmware) - Repository for various Broadcom Bluetooth firmware
* [teleshoes/tpacpi-bat](https://github.com/teleshoes/tpacpi-bat) - ThinkPad ACPI Battery Util
* [bwachter/supermicro-ipmi-key](https://github.com/bwachter/supermicro-ipmi-key) - Generate keys for supermicro IPMI
* [Gator96100/ProxSpace](https://github.com/Gator96100/ProxSpace) - Proxmark III develoment environment for Windows
* [jcs/payphone](https://github.com/jcs/payphone) - notes and code for my payphone project
* [nebulous/infinitude](https://github.com/nebulous/infinitude) - Open control of Carrier/Bryant thermostats
* [bgcngm/mtk-tools](https://github.com/bgcngm/mtk-tools) - Unpack / repack MT65xx/MT83xx boot.img, recovery.img or logo.bin
* [pali/hsphfpd-prototype](https://github.com/pali/hsphfpd-prototype) - Prototype of Bluetooth HSP/HFP daemon
* [DoctorWkt/CSCvon8](https://github.com/DoctorWkt/CSCvon8) - A crazy small 8-bit CPU built with only seventeen 7400-series chips.
* [Digital-Naturalism-Laboratories/Mothbox](https://github.com/Digital-Naturalism-Laboratories/Mothbox) - Developing an open source,low cost automated system for Moth-Lighting photography
* [SynAckFin/TuyOTA](https://github.com/SynAckFin/TuyOTA) - Flashing Tuya devices with Tasmota firmware.
* [jareddantis/unbrick_8960](https://github.com/jareddantis/unbrick_8960) - [DEPRECATED] A tool for unbricking MSM8960 devices in QDLOAD/SDBOOT mode *(archived)*
* [khorton/nas_fan_control](https://github.com/khorton/nas_fan_control) - collection of scripts to control fan speed on NAS boxes
* [robelix/hard-dj](https://github.com/robelix/hard-dj) - arduino based DJ MIDI cotroller using Harddisks as jog wheels
* [DoctorWkt/CSCv2](https://github.com/DoctorWkt/CSCv2) - Version 2 of my Crazy Small CPU
* [NasdaqGodzilla/UNISOC_SPRD_PAC_UNPAC](https://github.com/NasdaqGodzilla/UNISOC_SPRD_PAC_UNPAC) - 紫光展锐展讯SPRD刷机包pac文件解包提取img文件。Extract Images from .pac file from Spreadtrum Unisoc SPRD.
* [RFD-FHEM/RFFHEM](https://github.com/RFD-FHEM/RFFHEM) - Counterpart of SIGNALDuino, it's the code for FHEM to work with the data received from the uC
* [klein0r/fhem-tasmota](https://github.com/klein0r/fhem-tasmota) - DEPRECATED - PLEASE USE MQTT2_DEVICE INSTEAD *(archived)*

## Business and Domain

### Finance and Trading

* [ledgersmb/LedgerSMB](https://github.com/ledgersmb/LedgerSMB) - Double-entry accounting & ERP for the web
* [xFFFFF/Gekko-BacktestTool](https://github.com/xFFFFF/Gekko-BacktestTool) - Batch backtest, import and strategy params optimalization for Gekko Trading Bot. With one command you will run any number of backtests.
* [xFFFFF/Gekko-Datasets](https://github.com/xFFFFF/Gekko-Datasets) - Gekko Trading Bot dataset dumps. Ready to use and download history files in SQLite format.
* [kivitendo/kivitendo-erp](https://github.com/kivitendo/kivitendo-erp) - Web-based ERP system for the German market
* [danuk/shm](https://github.com/danuk/shm) - Universal Billing with external actions
* [beancount/ledger2beancount](https://github.com/beancount/ledger2beancount) - Ledger to Beancount text-based converter
* [microsoft/cal-open-library](https://github.com/microsoft/cal-open-library) - C/AL Open Library is a repository for .NET Interop wrappers that will be included into Dynamics 365 for Financials and usable from Extensions V2 *(archived)*

### Business and Productivity

* [Koha-Community/Koha](https://github.com/Koha-Community/Koha) - Koha is a free software integrated library system (ILS). Koha is distributed under the GNU GPL version 3 or later. ***Note: this is a synced mirror of the official Koha repo. Note: This project uses its own bug tracker, see https://bugs.koha-community.org/ to report a bug or submit a patch.
* [RotherOSS/otobo](https://github.com/RotherOSS/otobo) - OTOBO is one of the most flexible web-based ticketing systems used for Customer Service, Help Desk, IT Service Management. https://otobo.io/
* [openwebwork/webwork2](https://github.com/openwebwork/webwork2) - Course management front end for WeBWorK
* [liblime/LibLime-Koha](https://github.com/liblime/LibLime-Koha) - LibLime Koha is the most mature of the open source ILS applications. Based on the ground-breaking 3.0 platform (derived from the original Koha offering of 1999), LibLime Koha is a completely web-based open source ILS, with library staff, systems librarians, and library users all accessing LibLime Koha through a web browser. Relying on the MySQL relational database, all LibLime Koha data is readily accessible.
* [bugzilla/harmony](https://github.com/bugzilla/harmony) - next generation bugzilla
* [book/Act](https://github.com/book/Act) - A Conference Toolkit (Git conversion of the Subversion repository)
* [domm/App-TimeTracker](https://github.com/domm/App-TimeTracker) - distributed timetracking from the commandline
* [bestpractical/sd](https://github.com/bestpractical/sd) - A distributed issue tracker; upstream is now http://gitorious.org/prophet

## Science and Math

### Scientific Computing

* [tseemann/prokka](https://github.com/tseemann/prokka) - :zap: :aquarius: Rapid prokaryotic genome annotation
* [thesourcerer8/altium2kicad](https://github.com/thesourcerer8/altium2kicad) - Altium to KiCad converter for PCB and schematics *(archived)*
* [trinityrnaseq/trinityrnaseq](https://github.com/trinityrnaseq/trinityrnaseq) - Trinity RNA-Seq de novo transcriptome assembly
* [weizhongli/cdhit](https://github.com/weizhongli/cdhit) - Automatically exported from code.google.com/p/cdhit
* [tseemann/snippy](https://github.com/tseemann/snippy) - :scissors: :zap: Rapid haploid variant calling and core genome alignment
* [Ensembl/ensembl-vep](https://github.com/Ensembl/ensembl-vep) - The Ensembl Variant Effect Predictor predicts the functional effects of genomic variants
* [tseemann/abricate](https://github.com/tseemann/abricate) - :mag_right: :pill: Mass screening of contigs for antimicrobial and virulence genes
* [oushujun/EDTA](https://github.com/oushujun/EDTA) - Extensive de-novo TE Annotator
* [Gaius-Augustus/BRAKER](https://github.com/Gaius-Augustus/BRAKER) - BRAKER is a pipeline for fully automated prediction of protein coding gene structures with GeneMark-ES/ET/EP/ETP and AUGUSTUS in novel eukaryotic genomes
* [mskcc/vcf2maf](https://github.com/mskcc/vcf2maf) - Convert a VCF into a MAF, where each variant is annotated to only one of all possible gene isoforms
* [sanger-pathogens/Roary](https://github.com/sanger-pathogens/Roary) - Rapid large-scale prokaryote pan genome analysis
* [bioperl/bioperl-live](https://github.com/bioperl/bioperl-live) - Core BioPerl 1.x code
* [Dfam-consortium/RepeatMasker](https://github.com/Dfam-consortium/RepeatMasker) - RepeatMasker is a program that screens DNA sequences for interspersed repeats and low complexity DNA sequences.
* [TransDecoder/TransDecoder](https://github.com/TransDecoder/TransDecoder) - TransDecoder source
* [tseemann/barrnap](https://github.com/tseemann/barrnap) - :microscope: :leo: Microbial RNA annotation
* [tseemann/mlst](https://github.com/tseemann/mlst) - :id: Scan contig files against PubMLST typing schemes
* [tseemann/shovill](https://github.com/tseemann/shovill) - ⚡♠️ Assemble bacterial isolate genomes from Illumina paired-end reads
* [STAR-Fusion/STAR-Fusion](https://github.com/STAR-Fusion/STAR-Fusion) - STAR-Fusion codebase
* [Dfam-consortium/RepeatModeler](https://github.com/Dfam-consortium/RepeatModeler) - De-Novo Repeat Discovery Tool
* [AnantharamanLab/METABOLIC](https://github.com/AnantharamanLab/METABOLIC) - A scalable high-throughput metabolic and biogeochemical functional trait profiler
* [hewm2008/NGenomeSyn](https://github.com/hewm2008/NGenomeSyn) - Any Way to Show Multi genomic Synteny
* [BGI-shenzhen/LDBlockShow](https://github.com/BGI-shenzhen/LDBlockShow) - LDBlockShow: a fast and convenient tool for visualizing linkage disequilibrium and haplotype blocks based on VCF files
* [NBISweden/GAAS](https://github.com/NBISweden/GAAS) - Genome Assembly and Annotation Service code
* [oushujun/LTR_retriever](https://github.com/oushujun/LTR_retriever) - LTR_retriever is a highly accurate and sensitive program for identification of LTR retrotransposons; The LTR Assembly Index (LAI) is also included in this package.
* [AstraZeneca-NGS/VarDict](https://github.com/AstraZeneca-NGS/VarDict) - VarDict *(archived)*
* [PASApipeline/PASApipeline](https://github.com/PASApipeline/PASApipeline) - PASA software
* [ndierckx/NOVOPlasty](https://github.com/ndierckx/NOVOPlasty) - NOVOPlasty - The organelle assembler and heteroplasmy caller
* [konradjk/loftee](https://github.com/konradjk/loftee)
* [lskatz/mashtree](https://github.com/lskatz/mashtree) - :deciduous_tree: Create a tree using Mash distances
* [tangerzhang/ALLHiC](https://github.com/tangerzhang/ALLHiC) - ALLHiC: phasing and scaffolding polyploid genomes based on Hi-C data
* [Ensembl/VEP_plugins](https://github.com/Ensembl/VEP_plugins) - Plugins for the Ensembl Variant Effect Predictor (VEP)
* [rajewsky-lab/mirdeep2](https://github.com/rajewsky-lab/mirdeep2) - Discovering known and novel miRNAs from small RNA sequencing data
* [veripool/verilog-perl](https://github.com/veripool/verilog-perl) - Verilog parser, preprocessor, and related tools for the Verilog-Perl package
* [Gaius-Augustus/GALBA](https://github.com/Gaius-Augustus/GALBA) - GALBA is a pipeline for fully automated prediction of protein coding gene structures with AUGUSTUS in novel eukaryotic genomes for the scenario where high quality proteins from one or several closely related species are available.
* [mskcc/RNAseqDB](https://github.com/mskcc/RNAseqDB)
* [tseemann/any2fasta](https://github.com/tseemann/any2fasta) - Convert various sequence formats to FASTA
* [tseemann/nullarbor](https://github.com/tseemann/nullarbor) - :floppy_disk: :page_with_curl: "Reads to report" for public health and clinical microbiology
* [maasha/biopieces](https://github.com/maasha/biopieces) - Biopieces is a bioinformatic framework of tools easily used and easily created.
* [rpetit3/dragonflye](https://github.com/rpetit3/dragonflye) - :dragon: :fly: Assemble bacterial isolate genomes from Nanopore reads
* [MabinogiX/VASP-script](https://github.com/MabinogiX/VASP-script)
* [eead-csic-compbio/get_homologues](https://github.com/eead-csic-compbio/get_homologues) - GET_HOMOLOGUES: a versatile software package for pan-genome analysis
* [EVidenceModeler/EVidenceModeler](https://github.com/EVidenceModeler/EVidenceModeler) - source code for EVM
* [shangshanzhizhe/Work_flow_of_population_genetics](https://github.com/shangshanzhizhe/Work_flow_of_population_genetics) - 整理常用的群体遗传学分析流程和脚本
* [tallulandrews/scRNASeqPipeline](https://github.com/tallulandrews/scRNASeqPipeline)
* [NLM-DIR/vadr](https://github.com/NLM-DIR/vadr) - Viral Annotation DefineR: classification and annotation of viral sequences based on RefSeq annotation
* [starskyzheng/panpop](https://github.com/starskyzheng/panpop) - Application of pan-genome for population
* [chasewnelson/SNPGenie](https://github.com/chasewnelson/SNPGenie) - Program for estimating πN/πS, dN/dS, and other diversity measures from next-generation sequencing data
* [chrishah/MITObim](https://github.com/chrishah/MITObim) - MITObim - mitochondrial baiting and iterative mapping
* [BGI-shenzhen/RectChr](https://github.com/BGI-shenzhen/RectChr) - Multi-level visualization of genomic statistical variables on rectangular chromosomes
* [DiltheyLab/MetaMaps](https://github.com/DiltheyLab/MetaMaps) - Long-read metagenomic analysis
* [Dfam-consortium/TETools](https://github.com/Dfam-consortium/TETools) - Dfam Transposable Element Tools Docker container.
* [jaswindersingh2/SPOT-RNA](https://github.com/jaswindersingh2/SPOT-RNA) - RNA Secondary Structure Prediction using an Ensemble of Two-dimensional Deep Neural Networks and Transfer Learning.
* [yjx1217/simuG](https://github.com/yjx1217/simuG) - simuG: a general-purpose genome simulator
* [dcouvin/CRISPRCasFinder](https://github.com/dcouvin/CRISPRCasFinder) - A Perl script allowing to identify CRISPR arrays and associated Cas proteins from DNA sequences
* [rlabduke/MolProbity](https://github.com/rlabduke/MolProbity) - Protein and nucleic acid validation service
* [shenwei356/bio_scripts](https://github.com/shenwei356/bio_scripts) - Practical, reusable scripts for bioinformatics
* [simroux/VirSorter](https://github.com/simroux/VirSorter) - Source code of the VirSorter tool, also available as an App on CyVerse/iVirus (https://de.iplantcollaborative.org/de/)
* [SionBayliss/PIRATE](https://github.com/SionBayliss/PIRATE) - A toolbox for pangenome analysis and threshold evaluation.
* [arrogantrobot/23andme2vcf](https://github.com/arrogantrobot/23andme2vcf) - convert your 23andme raw file to VCF | DEPRECATED, please see https://github.com/plantimals/2vcf
* [ewels/clusterflow](https://github.com/ewels/clusterflow) - A pipelining tool to automate and standardise bioinformatics analyses on cluster environments. *(archived)*
* [JustinChu/JupiterPlot](https://github.com/JustinChu/JupiterPlot) - A Circos-based tool to visualize genome assembly consistency or synteny between assemblies.
* [tderrien/FEELnc](https://github.com/tderrien/FEELnc) - FEELnc : FlExible Extraction of LncRNA
* [JiaoLaboratory/CRAQ](https://github.com/JiaoLaboratory/CRAQ) - Identification of errors in draft genome assemblies with single-base pair resolution for quality assessment and improvement
* [sujaikumar/assemblage](https://github.com/sujaikumar/assemblage) - Tools for working with second gen assemblies, fasta sequences, etc
* [vastgroup/vast-tools](https://github.com/vastgroup/vast-tools) - A toolset for profiling alternative splicing events in RNA-Seq data.
* [biosql/biosql](https://github.com/biosql/biosql)
* [HRGV/phyloFlash](https://github.com/HRGV/phyloFlash) - phyloFlash - A pipeline to rapidly reconstruct the SSU rRNAs and explore phylogenetic composition of an illumina (meta)genomic dataset.
* [xie186/ViewBS](https://github.com/xie186/ViewBS) - ViewBS - a powerful toolkit for visualization of high-throughput bisulfite sequencing data
* [4ureliek/Parsing-RepeatMasker-Outputs](https://github.com/4ureliek/Parsing-RepeatMasker-Outputs) - Few scripts facilitating the extraction of info from Repeat Masker .out files
* [adigenova/wengan](https://github.com/adigenova/wengan) - An accurate and ultra-fast hybrid genome assembler
* [chenlianfu/geta](https://github.com/chenlianfu/geta)
* [bruceravel/demeter](https://github.com/bruceravel/demeter) - Process and analyze X-ray Absorption Spectroscopy data using Feff and either Larch or Ifeffit.
* [Ensembl/ensembl](https://github.com/Ensembl/ensembl) - The Ensembl Core Perl API and SQL schema
* [ArimaGenomics/mapping_pipeline](https://github.com/ArimaGenomics/mapping_pipeline) - Mapping pipeline for data generated using Arima-HiC
* [bcgsc/mirna](https://github.com/bcgsc/mirna) - microRNA profiling pipeline
* [RyanCook94/inphared](https://github.com/RyanCook94/inphared) - Providing up-to-date phage genome databases, metrics and useful input files for a number of bioinformatic pipelines.
* [gjospin/PhyloSift](https://github.com/gjospin/PhyloSift) - Phylogenetic and taxonomic analysis for genomes and metagenomes
* [nhansen/SVanalyzer](https://github.com/nhansen/SVanalyzer) - Tools for the analysis of structural variation in genomes
* [shawnlaffan/biodiverse](https://github.com/shawnlaffan/biodiverse) - A tool for the spatial analysis of diversity
* [MadsAlbertsen/multi-metagenome](https://github.com/MadsAlbertsen/multi-metagenome) - Scripts and tutorials on how to assemble individual microbial genomes from metagenomes
* [apetkau/orthomcl-pipeline](https://github.com/apetkau/orthomcl-pipeline) - Automates running of OrthoMCL software from http://orthomcl.org/common/downloads/software/v2.0/
* [nylander/catfasta2phyml](https://github.com/nylander/catfasta2phyml) - Concatenates FASTA formatted files to one "phyml" (PHYLIP) formatted file
* [genome/gms](https://github.com/genome/gms) - The Genome Modeling System installer *(archived)*
* [LANL-Bioinformatics/EDGE](https://github.com/LANL-Bioinformatics/EDGE) - EDGE is a highly adaptable bioinformatics platform that allows laboratories to quickly analyze and interpret genomic sequence data.
* [piercelab/antibody_benchmark](https://github.com/piercelab/antibody_benchmark) - Antibody-Antigen Docking and Affinity Benchmark
* [Spiritdude/Slicer4RTN](https://github.com/Spiritdude/Slicer4RTN) - Conic slicer utilizing planar slicers for 4-axis Rotating Tilted Nozzle (RTN) 3D printers
* [matutani/nocgen](https://github.com/matutani/nocgen) - NoC (Network-on-Chip) generator that generates Verilog HDL model of NoC consisting of on-chip routers
* [kjolley/BIGSdb](https://github.com/kjolley/BIGSdb) - Bacterial Isolate Genome Sequence Database (BIGSdb): A platform for gene-by-gene bacterial population annotation and analysis.
* [UUPharmacometrics/PsN](https://github.com/UUPharmacometrics/PsN) - Perl-Speaks-NONMEM
* [dekkerlab/cworld-dekker](https://github.com/dekkerlab/cworld-dekker) - perl cworld module and collection of utility/analysis scripts for C data (3C, 4C, 5C, Hi-C)
* [vinuesa/get_phylomarkers](https://github.com/vinuesa/get_phylomarkers) - A pipeline to select optimal markers for microbial phylogenomics and species tree estimation using the multispecies coalescent and concatenation approaches
* [Ensembl/ensembl-compara](https://github.com/Ensembl/ensembl-compara) - The Ensembl Compara Perl API and SQL schema
* [Sunhh/NGS_data_processing](https://github.com/Sunhh/NGS_data_processing) - Tool set for processing fasta/fastq/table formated data. Usually they are perl scripts.
* [Ensembl/ensembl-hive](https://github.com/Ensembl/ensembl-hive) - EnsEMBL Hive - a system for creating and running pipelines on a distributed compute resource
* [ding-lab/hotspot3d](https://github.com/ding-lab/hotspot3d) - 3D hotspot mutation proximity analysis tool
* [egonozer/in_silico_pcr](https://github.com/egonozer/in_silico_pcr) - Perl script for simulating PCR reactions. Extract sequences from a query based on primer sequences.
* [tao-bioinfo/gff3sort](https://github.com/tao-bioinfo/gff3sort) - GFF3sort: A Perl Script to sort gff3 files and produce suitable results for tabix tools
* [aleimba/bac-genomics-scripts](https://github.com/aleimba/bac-genomics-scripts) - Collection of scripts for bacterial genomics
* [LyonsLab/coge](https://github.com/LyonsLab/coge) - CoGe (Comparative Genomics) Platform
* [olarerin/metaPlotR](https://github.com/olarerin/metaPlotR) - A Perl/R pipeline for plotting metagenes
* [Geo-omics/scripts](https://github.com/Geo-omics/scripts) - Metagenomic pipeline and other general scripts used in the lab.
* [WRao96/Materials-Studio-script](https://github.com/WRao96/Materials-Studio-script) - perl script of Materials Studio
* [Ensembl/ensembl-variation](https://github.com/Ensembl/ensembl-variation) - The Ensembl Variation Perl API and SQL schema
* [josephhughes/Sequence-manipulation](https://github.com/josephhughes/Sequence-manipulation) - A range of different perl scripts for manipulating sequences, conducting alignments, consensus sequences, changing formats
* [Ensembl/Bio-DB-HTS](https://github.com/Ensembl/Bio-DB-HTS) - Git repo for Bio::DB::HTS module on CPAN, providing Perl links into HTSlib
* [mtw/Bio-ViennaNGS](https://github.com/mtw/Bio-ViennaNGS) - A Perl extension and collection of utilities for Next-Generation Sequencing (NGS) data analysis
* [ntruchsess/perl-firmata](https://github.com/ntruchsess/perl-firmata) - Perl implementation of the firmata client. Originally authored by Aki Mimoto (amimoto) this repository was transfered to Norbert Truchsess (ntruchsess) in 02/2013. Anybody willing to contribute is very wellcome! Please submitt pull-requests against branch 'dev'
* [GTseq/GTseq-Pipeline](https://github.com/GTseq/GTseq-Pipeline) - A series of perl and python scripts for generating genotypes from NGS fastq files from GTseq library sequencing.
* [sandialabs/TIGER](https://github.com/sandialabs/TIGER) - Target / Integrative Genetic Element Retriever: precisely maps IGEs (a defined type of genomic island) in bacterial and archaeal genomes; package also includes orthogonal program Islander

## Other

* [duckduckgo/duckduckgo](https://github.com/duckduckgo/duckduckgo) - DuckDuckGo Instant Answer Infrastructure *(archived)*
* [duckduckgo/zeroclickinfo-goodies](https://github.com/duckduckgo/zeroclickinfo-goodies) - DuckDuckGo Instant Answers based on Perl & JavaScript *(archived)*
* [dejavu-fonts/dejavu-fonts](https://github.com/dejavu-fonts/dejavu-fonts)
* [huichen/mlf](https://github.com/huichen/mlf) - 大数据机器学习框架
* [qwerty-fr/qwerty-fr](https://github.com/qwerty-fr/qwerty-fr) - Qwerty keyboard layout with French accents
* [rovo89/XposedTools](https://github.com/rovo89/XposedTools) - These tools can be used to compile and package the Xposed framework. *(archived)*
* [SSNikolaevich/DejaVuSansCode](https://github.com/SSNikolaevich/DejaVuSansCode) - Monospaced font with programming ligatures based on DejaVu Sans Mono
* [jfhovinne/jFeed](https://github.com/jfhovinne/jFeed) - jQuery RSS/ATOM feed parser plugin *(archived)*
* [norbusan/debian-graph](https://github.com/norbusan/debian-graph) - Representing Debian UDD in a graph database
* [norbusan/jfontmaps](https://github.com/norbusan/jfontmaps) - dvipdfmx map files and support programs for Japanese font setup
* [norbusan/tlptexlive-root](https://github.com/norbusan/tlptexlive-root) - packaging stuff for tlptexlive
* [erlang/eep](https://github.com/erlang/eep) - Erlang Enhancement Proposals
* [bagder/emails](https://github.com/bagder/emails) - emails I received
* [XueshiQiao/FLEXLoader](https://github.com/XueshiQiao/FLEXLoader) - A jailbreak iOS device tweak which can load FLEX dynamiclly
* [SyntheticAutonomicMind/CLIO](https://github.com/SyntheticAutonomicMind/CLIO) - An AI-assisted coding agent that runs in your terminal and supports many providers and models.
* [jwilk-archive/perl-friday](https://github.com/jwilk-archive/perl-friday) - Perl code that is syntactically correct only on Fridays *(archived)*
* [raviriley/donna](https://github.com/raviriley/donna) - OpenAI x PearVC hackathon (built in 6 hours)
* [makertum/non-planar-layer-fdm](https://github.com/makertum/non-planar-layer-fdm)
* [its-pointless/its-pointless.github.io](https://github.com/its-pointless/its-pointless.github.io) - For info see https://github.com/its-pointless/gcc_termux
* [grayhemp/pgtoolkit](https://github.com/grayhemp/pgtoolkit) - Tools for PostgreSQL maintenance
* [mdom/dategrep](https://github.com/mdom/dategrep) - print lines matching a time range
* [omniti-labs/omnipitr](https://github.com/omniti-labs/omnipitr) - Advanced WAL File Management Tools for PostgreSQL
* [kazuho/jailing](https://github.com/kazuho/jailing) - super-easy chroot jail builder/runner for Linux
* [reyjrar/es-utils](https://github.com/reyjrar/es-utils) - ElasticSearch Utilities
* [famzah/langs-performance](https://github.com/famzah/langs-performance) - C++ vs. Python vs. Perl vs. PHP vs. Java vs. NodeJS vs. Go vs. Ruby vs. Rust vs. Swift vs. D performance benchmark
* [menavaur/Autobench](https://github.com/menavaur/Autobench)
* [ingydotnet/...](https://github.com/ingydotnet/...) - Dot Dot Dot
* [omniti-labs/pgtreats](https://github.com/omniti-labs/pgtreats) - Tasty treats for PostgreSQL
* [barzan/dbseer](https://github.com/barzan/dbseer) - DBSeer
* [satoru-takeuchi/elkdat](https://github.com/satoru-takeuchi/elkdat) - ELKDAT: easy linux kernel development and test tool
* [cgutteridge/geocraft](https://github.com/cgutteridge/geocraft)
* [sp1ritCS/gtk-android-builder](https://github.com/sp1ritCS/gtk-android-builder) - Pixiewood - Build GTK applications for Android
* [PDLPorters/pdl](https://github.com/PDLPorters/pdl) - Scientific computing with Perl
* [xdata-skylark/libskylark](https://github.com/xdata-skylark/libskylark) - Sketching-based Distributed Matrix Computations for Machine Learning
* [embermap/ember-cli-tailwind](https://github.com/embermap/ember-cli-tailwind) - Adds Tailwind CSS to your app or addon
* [gknops/adHocGenerate](https://github.com/gknops/adHocGenerate) - Wireless ad hoc distribution of iOS applications
* [itouhiro/PixelMplus](https://github.com/itouhiro/PixelMplus) - TrueType outline fonts like 8-bit bitmap fonts
* [ZANSIN-sec/ZANSIN](https://github.com/ZANSIN-sec/ZANSIN)
* [saiftynet/GUIDeFATE](https://github.com/saiftynet/GUIDeFATE) - GUI Design From A Text Editor
* [otherjoel/thenotepad](https://github.com/otherjoel/thenotepad) - 📓🍎An experimental blog written in Pollen / Racket
* [shmilee/T450-Hackintosh](https://github.com/shmilee/T450-Hackintosh) - T450-Hackintosh *(archived)*
* [liangclab/HERA](https://github.com/liangclab/HERA)
* [OpenDDRdotORG/OpenDDR-Resources](https://github.com/OpenDDRdotORG/OpenDDR-Resources) - OpenDDR resources
* [vernnobile/NunitoFont](https://github.com/vernnobile/NunitoFont) - repo for the Nunito Font family
* [Webconverger/webc](https://github.com/Webconverger/webc) - Webconverger's curated chroot from which updates originate
* [gbxyz/webidx](https://github.com/gbxyz/webidx) - webidx is a client-side search engine for static websites.
* [blogs-perl-org/blogs.perl.org](https://github.com/blogs-perl-org/blogs.perl.org) - Templates and stuff for the blogs.perl.org web site
* [sophiehuiberts/Bootimg-scripts](https://github.com/sophiehuiberts/Bootimg-scripts) - Perl scripts for unpacking and repackaging Android boot.img's. I did not write these, just sharing.
* [danaj/Math-Prime-Util](https://github.com/danaj/Math-Prime-Util) - Perl (XS) module implementing prime number utilities, including sieves
* [houseabsolute/DateTime.pm](https://github.com/houseabsolute/DateTime.pm) - A date and time object for Perl
* [FormFu/HTML-FormFu](https://github.com/FormFu/HTML-FormFu) - HTML Form Creation, Rendering and Validation Framework. Just define the form, and let FormFu do the all heavy lifting.
* [leto/math--gsl](https://github.com/leto/math--gsl) - Perl interface to the GNU Scientific Library
* [mojolicious/mojo-assetpack](https://github.com/mojolicious/mojo-assetpack) - :tractor: Compress and convert CSS, Less, Sass and JavaScript files
* [sass/perl-libsass](https://github.com/sass/perl-libsass) - Perl bindings for libsass (CSS::Sass) *(archived)*
* [schwern/Sex](https://github.com/schwern/Sex) - Perl teaches the birds and the bees
* [tanjiti/perl_tools](https://github.com/tanjiti/perl_tools) - perl小工具
* [raku-community-modules/raku-bench](https://github.com/raku-community-modules/raku-bench) - Benchmark and compare Raku implementations against Perl
* [rudism/NetAuthority](https://github.com/rudism/NetAuthority) - Historical perl code that ran the original NetAuthority.org site *(archived)*
* [mojolicious/mojo-mcp](https://github.com/mojolicious/mojo-mcp) - Perl SDK for Model Context Protocol servers and clients
* [tangerzhang/my_script](https://github.com/tangerzhang/my_script) - my commonly used perl script
* [Taryck/idrive](https://github.com/Taryck/idrive) - idrive scripts (perl)
* [sanko/Acme-MCP.pm](https://github.com/sanko/Acme-MCP.pm) - Cheap Model Context Protocol (MCP) Server
