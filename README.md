# libev

### libev is a high-performance event loop/event model with lots of features.

    Libev is modelled (very losely) after libevent and the Event perl
    module, but is faster, scales better and is more correct, and also more
    featureful. And also smaller. Yay.
    
-----
                         **UNOFFICAL VERSION**

#### Warning: This is an un-official version of libev maintained by Brig Young for his use on github.
See the Homepage for details on how to obtain an official release. You
are of course encouraged to fork this repo and use it in accordance with
the LICENSE provided by the authors.

#### 30-NOV-2016: This system builds with some non-problem warnings and installs correctly on Linux Mint 18.

-----

##### Benchmark: http://libev.schmorp.de/bench.html
##### Homepage: http://software.schmorp.de/pkg/libev
##### Listserv: libev@lists.schmorp.de
##### ListArchive: http://lists.schmorp.de/cgi-bin/mailman/listinfo/libev
##### Documentation: http://pod.tst.eu/http://cvs.schmorp.de/libev/ev.pod

------

### Some of the specialties of libev not commonly found elsewhere are:
   
* extensive and detailed, readable documentation.

* fully supports fork, can detect fork in various ways and automatically
  re-arms kernel mechanisms that do not support fork.

* highly optimised select, poll, epoll, kqueue and event ports backends.

* filesystem object (path) watching (with optional linux inotify support).

* wallclock-based times (using absolute time, cron-like).

* relative timers/timeouts (handle time jumps).

* fast intra-thread communication between multiple
  event loops (with optional fast linux eventfd backend).

* extremely easy to embed (fully documented, no dependencies,
  autoconf supported but optional).

* very small codebase, no bloated library, simple code.

* fully extensible by being able to plug into the event loop,
  integrate other event loops, integrate other event loop users.

* very little memory use (small watchers, small event loop data).

* optional C++ interface allowing method and function callbacks
  at no extra memory or runtime overhead.

* optional Perl interface with similar characteristics (capable
  of running Glib/Gtk2 on libev).

* support for other languages (multiple C++ interfaces, D, Ruby,
  Python) available from third-parties.

* Examples of programs that embed libev:

the EV perl module, node.js, auditd, rxvt-unicode, gvpe (GNU Virtual Private Ethernet),
the Deliantra MMORPG server (http://www.deliantra.net/), Rubinius 
(a next-generation Ruby VM), the Ebb web server, the Rev event toolkit.

-----

### Contributors:

##### libev was written and designed by Marc Lehmann and Emanuele Giaquinta.

The following people sent in patches or made other noteworthy
contributions to the design (for minor patches, see the Changes
file. If I forgot to include you, please shout at me, it was an
accident):

##### W.C.A. Wijngaards
##### Christopher Layne
##### Chris Brody

