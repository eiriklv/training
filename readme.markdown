# training

Hello! Does your team, organization, or conference need hands-on training in
node.js, frontend javascript, peer to peer architecture, browser databases, or
data replication?

Email substack@gmail.com to say hello!

# pricing

I will fly to wherever you are, anywhere in the world!

The base price is 2000 USD and 1000 USD for each additional day of
instruction plus airfare, visa fees, and no-frills accomodation.

For 2 days of hands-on instruction for a class of 20, that works to less than
200 USD per student, depending on airfare and visa fees.

# courses

I offer these topics, but I can adapt materials for specific requests.

For every course, we will start from zero and build a very simple application
that gains functionality incrementally until we have a fully-featured program.

Participants should come with their own computer running a unix environment
(Linux or Mac OSX preferred) with the latest stable versions of node and npm
installed.

The venue should have a ample power outlets, wifi, seating, and projector or
computer monitor with a VGA or HDMI port that everyone can see.

## introduction to modules

<table>
  <tr>
    <th>skill level</th>
    <td>introductory</td>
  </tr>
  <tr>
    <th>pre-requisites</th>
    <td>javascript basics</td>
  </tr>
</table>

Node has a powerful module system and a vast package ecosystem.

We will cover:

* installing and publishing modules to npm
* how to organize a code base for node.js and the browser
* how to find good packages
* npm run scripts
* basics of testing, code coverage

## node.js streams

<table>
  <tr>
    <th>skill level</th>
    <td>intermediate</td>
  </tr>
  <tr>
    <th>pre-requisites</th>
    <td>javascript basics, familiarity with npm</td>
  </tr>
</table>

Streams are a powerful abstraction from node core for plumbing together IO.

We will cover:

* differences between readable, writable, transform, duplex
* streaming interfaces in core
* common streaming libraries and patterns in userland
* streaming transports: tcp, websockets, webrtc
* implementing our own streaming protocols with multiplex, rpc

## leveldb basics

<table>
  <tr>
    <th>skill level</th>
    <td>intermediate</td>
  </tr>
  <tr>
    <th>pre-requisites</th>
    <td>javascript, npm, streams</td>
  </tr>
</table>

LevelDB is a powerful embedded database with great bindings for node and a vast
ecosystem of libraries available on npm. Best of all, leveldb works in the
browser with excellent wrappers on top of IndexedDB.

We will cover:

* basic get/put/del
* range queries
* thinking lexicographically
* pairing leveldb with other storage engines (blob storage, spatial indexes)
* using leveldb in the browser

## web development whirlwind

<table>
  <tr>
    <th>skill level</th>
    <td>intermediate</td>
  </tr>
  <tr>
    <th>pre-requisites</th>
    <td>javascript, streams, npm</td>
  </tr>
</table>

Web development can be a confusing place with new approaches appearing
constantly. We'll cover some simple tools to manage building a webapp in an
incremental way, adding new tools only when necessary. We'll focus more small
tools that do one fundamental thing well instead of spending a bunch of time in
configuration files.

We will cover:

* front end architectures
* virtual DOM libraries
* universal rendering
* build scripts and frontend tooling
* how to handle URLs
* managing other assets
* talking to the server (ajax, websockets)

## peer to peer architecture

<table>
  <tr>
    <th>skill level</th>
    <td>advanced</td>
  </tr>
  <tr>
    <th>pre-requisites</th>
    <td>leveldb, streams</td>
  </tr>
</table>

As the web platform becomes more powerful, web pages are going to look more and
more like distributed systems.

Even if you're not building a strictly peer to peer application, these ideas
will help you and your team to build better offline, fault-tolerant
applications.

* merkle DAGs
* kappa architecture and materialized views
* identity with cryptographic key pairs
* data replication
* distributed hash tables (DHT), immutable/mutable content
* webrtc
* webtorrent, dat/hyperdrive
