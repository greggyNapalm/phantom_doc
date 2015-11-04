===============
What is Phantom
===============

Phantom is an open source Web server, proxy server and load generator, with a strong focus on high concurrency, performance and low memory usage. It is licensed under a LGPL-like license and it runs on Linux.


**Features**
============

Very accurate and predictable measurement
-----------------------------------------
  
 Test scenario is defined up to every millisecond and every byte send to test host

Low level data collected in simple format
-----------------------------------------
 Test plan and result both are plain-text files, which could be parsed with ever You want

 Result consist of: 

 * send/receive data size
 * rtt, connection, send, server-side processing and receive times for each request
 * networks error codes(errno) and application layer protocol specific codes, like HTTP status codes.

Distributed & Scalable - supports tens of thousands of concurrent requests
--------------------------------------------------------------------------

 You can get ``~40K HTTP rps`` from one Phantom instance(POSIX process) on one Linux box

 Process are independent from each other     

Extendable/Hackable
-------------------
 
 You can write Your own Phantom modules for custom protocols like SSL or put anything in plain-text protocols body.

**Background**
==============

**Analogs**
===========

Free tools
----------
 * `jMeter <http://jmeter.apache.org/>`_
 * `Tsung <http://tsung.erlang-projects.org/>`_
 * `Siege <http://www.joedog.org/siege-home/>`_
 * `ab <http://httpd.apache.org/docs/2.0/programs/ab.html>`_
 * `Locust <https://github.com/esnme/locust>`_
 * `iago <http://twitter.github.com/iago/>`_
 * `Httperf <http://code.google.com/p/httperf/>`_
 * `Pylot <http://pylot.org/>`_
 * `http_load <http://www.acme.com/software/http_load/>`_
 * `Grinder <http://grinder.sourceforge.net/>`_
 * `Gatling <http://gatling-tool.org/>`_
 * `wrk <https://github.com/wg/wrk/>`_
 * `funkload <http://funkload.nuxeo.org/>`_
 * `sniper <https://github.com/lubia/sniper>`_
 * `vegeta <https://github.com/tsenart/vegeta>`_


Nonefree tools
--------------
 * `HP LoadRunner <http://www8.hp.com/us/en/software-solutions/software.html?compURI=1175451>`_
 * `IBM - IBM Rational Performance Tester <http://www.ibm.com/software/awdtools/tester/performance/>`_
 * `Borland SilkPerformer <http://www.borland.com/us/products/silk/silkperformer/>`_
 * `Visual Studio Load Test <http://www.microsoft.com/visualstudio/en-us/products/2010-editions/load-test-virtual-user-pack/overview>`_
 * `WebLoad <http://www.webload.org/>`_


online Services
---------------
 * `loadstorm <http://loadstorm.com/>`_
 * `loadimpact <http://loadimpact.com/>`_
 * `neustar <https://browsermob.com/performance-testing>`_
 * `loader.io <http://loader.io/>`_
 * `blazemeter <http://blazemeter.com/>`_
 * `apica <https://www.apicasystem.com/>`_

**Authors**
===========
 * Evgeniy Mamchits

**License**
===========

Open source licensed under the `LGPL <http://www.gnu.org/licenses/lgpl-2.1.html>`_ license.
