# CUDPP HAS MOVED TO GITHUB #

**9 October 2013**

This project has been moved to [http://cudpp.github.io/](http://cudpp.github.io/).  All src code, issues, and wiki pages have been migrated.  In addition, we are happy to announce the release of CUDPP 2.1 which adds new primitives and bug fixes.  Please do use the version of CUDPP from Github and do not file issues here at Google Code.

# Overview #

CUDPP is the CUDA Data Parallel Primitives Library. CUDPP is a library of data-parallel algorithm primitives such as parallel prefix-sum (”scan”), parallel sort and parallel reduction. Primitives such as these are important building blocks for a wide variety of data-parallel algorithms, including sorting, stream compaction, and building data structures such as trees and summed-area tables. CUDPP runs on processors that support [CUDA](http://www.nvidia.com/cuda).

For detailed information, see the [CUDPP Documentation](http://cudpp.googlecode.com/svn/tags/2.0/doc/html/index.html).  A good place to start is the [simpleCUDPP Example](http://cudpp.googlecode.com/svn/tags/2.0/doc/html/example_simplecudpp.html).

[Download CUDPP Now!](https://github.com/cudpp/cudpp/releases)

# News #

## Moved to github, CUDPP 2.1 Released. ##
**9 October 2013**

This project has been moved to [GitHub](http://cudpp.github.io/).  All src code, issues, and wiki pages have been migrated.  In addition, we are happy to announce the release of CUDPP 2.1 which added a slew of new primitives.

## CUDPP 2.0 Released! ##
**9 August 2011**

CUDPP release 2.0 is a major new release of the CUDPP library, with exciting new features.  The public interface has undergone a minor redesign to provide thread safety.  Parallel reductions ([cudppReduce](http://cudpp.googlecode.com/svn/tags/2.0/doc/html/group__public_interface.html#ga21d9b2b3c74daffbec52ef628f835313)) and a tridiagonal system solver ([cudppTridiagonal](http://cudpp.googlecode.com/svn/tags/2.0/doc/html/group__public_interface.html#gabd3c1f97e1d22839756fd2594aaefb56)) have been added, and a new component library, [cudpp\_hash](http://cudpp.googlecode.com/svn/tags/2.0/doc/html/hash_overview.html), provides fast data-parallel hash table functionality. In addition, support for 64-bit data types (double as well as long long and unsigned long long) has been added to all CUDPP algorithms, and a variety of bugs have been fixed.

For a complete list of changes, see the [change log](http://cudpp.googlecode.com/svn/tags/2.0/doc/html/changelog.html).

[Download CUDPP 2.0 Now!](http://code.google.com/p/cudpp/downloads/list)

## CUDPP 1.1.1 Released! ##
**29 April 2010**

CUDPP release 1.1.1 is a bugfix release with fixes for scan, segmented scan, stream compaction, and radix sort on the NVIDIA Fermi (sm\_20) architecture, including GeForce 400 series and Tesla 20 series GPUs.  It also includes improvements and bugfixes for radix sorts on 64-bit OSes, and fixes for 64-bit builds on MS Windows OSes and Apple OS X 10.6 (Snow Leopard). [Change Log](http://cudpp.googlecode.com/svn/tags/1.1.1/cudpp/doc/html/changelog.html).

&lt;wiki:gadget url="http://www.ohloh.net/p/379621/widgets/project\_basic\_stats.xml" height="220" border="1"/&gt;