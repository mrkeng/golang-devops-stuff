## Golang Lib for DevOps
  - metrics
  - monitoring
  - servers
  - global locking / paxos / raft
  - Cloud API clients





## Distributed Computing with Golang
  - https://code.google.com/p/go-wiki/wiki/Courses
    - [15-440: Distributed Systems Syllabus](http://www.cs.cmu.edu/~dga/15-440/F12/syllabus.html) - very-very-very good course!
    - [6.824 Lab 1: Lock Server](http://pdos.csail.mit.edu/6.824/labs/lab-1.html)

    - [Chinese Courses](http://billlangjun.github.io/golang.html)

## Locking Server/PubSub/Service Discovery
  - GNats/Nats:
    - http://www.reddit.com/r/golang/comments/1oqqx7/gnatsd_from_apcera_a_high_performance_nats_server/
    - NATS does not have persistence, or transactions. It is more like a nervous system, and it will protect itself at all costs and does not have SPOFs. It does publish/subscribe, and distributed queues.
    - http://www.quora.com/Cloud-Foundry/Why-does-CloudFoundry-use-NATS-a-specially-written-messaging-system-whereas-OpenStack-uses-AMQP
    AMQP, and implementations like RabbitMQ, are enterprise messaging systems built with things like durability, transactions, and formal queues. NATS was designed and built to be like a dial-tone publish-subscribe service, something that is always on and available. However, NATS does not provide durability or transactions, and its queuing model is interest-based only. It also protects itself, the NATS service, at all costs, so that it can always be available. This forms a great base platform for building scalable and reliable distributed systems, but is probably not a good fit for the typical enterprise application.

  - Serf:
    - http://www.serfdom.io/
    - https://news.ycombinator.com/item?id=6600063


## Distributed Execution
  - [Исполнение SSH-команд на сотнях серверов с помощью Golang - 2014.02](http://habrahabr.ru/post/215111/)


## Why Golang for DevOps?
  - [Go Language for Ops and Site Reliability Engineering](http://talks.golang.org/2013/go-sreops.slide)



This repository is supposed to work with [DirEnv](https://github.com/zimbatm/direnv). It will set the GOPATH to current directory and append the ./bin folder to your PATH variable.


<!-- PROJECTS_LIST_START -->
    *** GENERATED BY https://github.com/mindreframer/techwatcher (ruby _sh/pull golang-devops-stuff) *** 

    abh/geodns:
      DNS server with per-client targeted responses
       241 commits, last change: , 305 stars, 26 forks

    abhishekkr/goshare:
      Go Share your TimeSeries/NameSpace/KeyVal DataStore (using leveldb) over HTTP /or ZeroMQ
       61 commits, last change: , 21 stars, 3 forks

    adnaan/hamster:
      A back end as a service based on MongoDB
       45 commits, last change: , 52 stars, 3 forks

    apcera/gnatsd:
      High Performance NATS Server
       301 commits, last change: , 390 stars, 46 forks

    apcera/nats:
      NATS client for Go
       220 commits, last change: , 94 stars, 13 forks

    ARolek/lilpinger:
      A small site pinging application with email and SMS notifications written in Golang
       5 commits, last change: , 17 stars, 3 forks

    benbjohnson/go-raft:
      A Go implementation of the Raft distributed consensus protocol.
       537 commits, last change: , 856 stars, 98 forks

    bitly/google_auth_proxy:
      A reverse proxy that provides authentication using Google OAuth2
       19 commits, last change: , 206 stars, 29 forks

    bitly/nsq:
      A realtime distributed messaging platform
       1,097 commits, last change: , 2,456 stars, 211 forks

    bradfitz/runsit:
      It runs it.
       69 commits, last change: , 171 stars, 11 forks

    buger/cloud-ssh:
      Wrapper for ssh which enchance work with cloud providers
       11 commits, last change: , 21 stars, 1 forks

    buger/gor:
      HTTP traffic replay in real-time. Replay traffic from production to staging and dev environments.
       324 commits, last change: , 1,436 stars, 71 forks

    BurntSushi/cmail:
      cmail runs a command and sends the output to your email address at certain intervals.
       11 commits, last change: , 3 stars, 0 forks

    calmh/syncthing:
      Open Source Continuous Replication / Cluster Synchronization Thing
       398 commits, last change: 2014-05-13 14:59:17, 2,123 stars, 68 forks

    ccding/go-stun:
      a go implementation of the STUN client (RFC 3489 and RFC 5389)
       4 commits, last change: , 15 stars, 2 forks

    cloudflare/redoctober:
      Go server for two-man rule style file encryption and decryption.
       72 commits, last change: , 557 stars, 39 forks

    cloudfoundry/gorouter:

       433 commits, last change: , 136 stars, 53 forks

    cloudfoundry/gosigar:

       15 commits, last change: , 64 stars, 21 forks

    cloudfoundry/hm9000:

       321 commits, last change: , 21 stars, 9 forks

    cloudfoundry/yagnats:
      Yet Another Go NATS client
       64 commits, last change: , 6 stars, 0 forks

    coreos/etcd:
      A highly-available key value store for shared configuration and service discovery
       1,747 commits, last change: , 3,069 stars, 281 forks

    crosbymichael/skydock:
      Service discovery via DNS for docker
       86 commits, last change: , 384 stars, 27 forks

    crowdmob/goamz:
      Fork of the GOAMZ version developed within Canonical with additional functionality with DynamoDB
       630 commits, last change: , 144 stars, 85 forks

    dotcloud/docker:
      Docker - the open-source application container engine
       7,984 commits, last change: , 11,670 stars, 1,889 forks

    efficient/epaxos:

       26 commits, last change: , 164 stars, 9 forks

    erikh/gollector:
      json-based metrics collector
       175 commits, last change: , 100 stars, 6 forks

    errplane/errplane-go:
      Go library for metrics for Errplane
       52 commits, last change: , 14 stars, 2 forks

    flynn/go-crypto-ssh:
      Forked from go.crypto as Flynn working copy until changes merged upstream
       7 commits, last change: , 2 stars, 1 forks

    flynn/go-discover:
      Service discovery system written in Go
       130 commits, last change: , 187 stars, 18 forks

    flynn/rpcplus:
      Go RPC plus streaming responses (forked from vitess)
       23 commits, last change: , 15 stars, 1 forks

    globocom/gandalf:
      Gandalf is an API to manage git repositories.
       504 commits, last change: , 123 stars, 16 forks

    globocom/tsuru:
      Open source Platform as a Service.
       6,986 commits, last change: , 962 stars, 95 forks

    gogits/gogs:
      Gogs(Go Git Service) is a Self Hosted Git Service in the Go Programming Language.
       971 commits, last change: , 1,774 stars, 107 forks

    golang/groupcache:
      groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases.
       21 commits, last change: , 2,742 stars, 237 forks

    happypancake/fsd:

        commits, last change: ,  stars,  forks

    hashicorp/serf:
      Service orchestration and management tool.
       1,141 commits, last change: , 2,007 stars, 121 forks

    inconshreveable/muxado:
      Stream multiplexing for Go
       15 commits, last change: , 147 stars, 6 forks

    inconshreveable/ngrok:
      Introspected tunnels to localhost
       277 commits, last change: , 2,143 stars, 141 forks

    inconshreveable/slt:
      A TLS reverse proxy with SNI multiplexing in Go
       9 commits, last change: , 93 stars, 1 forks

    influxdb/influxdb:
      Scalable datastore for metrics, events, and real-time analytics
       1,353 commits, last change: , 1,937 stars, 107 forks

    jingweno/gotask:
      Idiomatic build tool in Go
       123 commits, last change: , 116 stars, 5 forks

    joewalnes/websocketd:
      Like inetd, but for WebSockets. Turn any application that uses STDIN/STDOUT into a WebSocket server.
       134 commits, last change: , 3,075 stars, 139 forks

    jondot/groundcontrol:
      Manage and monitor your Raspberry Pi with ease
       50 commits, last change: , 653 stars, 42 forks

    jordansissel/lumberjack:
      An experiment to cut logs in preparation for processing elsewhere.
       541 commits, last change: , 520 stars, 133 forks

    jyap808/jaeger:
      Jaeger is a JSON encoded GPG encrypted key value store. It is useful for generating and keeping configuration files secure. Jaeger is written in Go.
       38 commits, last change: , 8 stars, 2 forks

    kelseyhightower/confd:
      Manage local application configuration files using templates and data from etcd or consul
       224 commits, last change: , 436 stars, 31 forks

    mailgun/vulcan:
      Golang HTTP reverse proxy library
       290 commits, last change: , 193 stars, 7 forks

    mindreframer/emtail:
      extract whitebox monitoring data from logs and insert into a timeseries database - mirror for https://code.google.com/p/emtail/
       273 commits, last change: , 1 stars, 0 forks

    mitchellh/go-ps:
      Find, list, and inspect processes from Go (golang).
       19 commits, last change: , 161 stars, 7 forks

    mitchellh/packer:
      Packer is a tool for creating identical machine images for multiple platforms from a single source configuration.
       2,925 commits, last change: , 2,408 stars, 392 forks

    mozilla-services/heka:
      Data collection and processing made easy.
       2,347 commits, last change: , 1,220 stars, 112 forks

    mrwilson/helixdns:
      A simple dns server that reads records from etcd.
       45 commits, last change: , 27 stars, 4 forks

    necrogami/watchdog:
      Watchdog
       7 commits, last change: , 2 stars, 1 forks

    nf/gohttptun:
      A tool to tunnel TCP over HTTP, written in Go
       22 commits, last change: , 88 stars, 15 forks

    nuxeo/gogeta:
      Reverse proxy based on etcd hierarchy
       17 commits, last change: , 60 stars, 5 forks

    oleiade/trousseau:
      Networked and encrypted key-value database
       271 commits, last change: , 557 stars, 22 forks

    petar/GoTeleport:
      Teleport Transport: End-to-end resilience to network outages
       6 commits, last change: , 108 stars, 2 forks

    pubsubsql/pubsubsql:
      An open-source distributed in-memory database integrated with Publish-Subscribe
       450 commits, last change: , 35 stars, 5 forks

    PuerkitoBio/throttled:
      throttling strategies for HTTP handlers
       39 commits, last change: , 155 stars, 4 forks

    rackspace/gophercloud:
      The Go SDK for Openstack.
       197 commits, last change: , 194 stars, 25 forks

    rcrowley/go-metrics:
      Go port of Coda Hale's Metrics library
       207 commits, last change: , 381 stars, 50 forks

    ReshNesh/pixlserv:
      Go server for processing and serving of images
       142 commits, last change: , 203 stars, 6 forks

    rzab/ostent:
      A drop-in system metrics inspector
       33 commits, last change: , 14 stars, 2 forks

    Sendhub/shipbuilder:
      The Open-source self-hosted Platform-as-a-Service written in Go
       139 commits, last change: , 5 stars, 39 forks

    shirkey/go-guerrilla:
      Mini SMTP server written in golang
       28 commits, last change: , 0 stars, 18 forks

    skydb/sky:
      Sky is an open source, behavioral analytics database.
       557 commits, last change: , 571 stars, 53 forks

    skynetservices/skydns:
      DNS for skynet or any other service discovery
       357 commits, last change: , 460 stars, 32 forks

    smira/aptly:
      aptly - Debian repository management tool
       592 commits, last change: , 240 stars, 15 forks

    spf13/nitro:
      Quick and easy performance analyzer library for golang
       7 commits, last change: , 92 stars, 5 forks

    stripe-ctf/octopus:
      Many-armed network simulator
       17 commits, last change: , 52 stars, 3 forks

    tsenart/tb:
      A generic lock-free implementation of the "Token-Bucket" algorithm
       51 commits, last change: , 40 stars, 0 forks

    tsenart/vegeta:
      HTTP load testing tool and library. It's over 9000!
       171 commits, last change: , 1,599 stars, 75 forks

    uniqush/uniqush-push:
      Uniqush is a free and open source software which provides a unified push service for server-side notification to apps on mobile devices.
       406 commits, last change: , 426 stars, 55 forks

    vektra/tachyon:
      An experimental configuration management system inspired by ansible
       121 commits, last change: , 27 stars, 6 forks

    vito/garden:
      Go Warden
       287 commits, last change: , 0 stars, 5 forks

    VividCortex/robustly:
      Run functions resiliently
       33 commits, last change: , 52 stars, 2 forks

    xtaci/gonet:
      a game server skeleton in golang
       974 commits, last change: , 198 stars, 83 forks

    YuriyNasretdinov/GoSSHa:
      Ssh client that supports multiple servers
       17 commits, last change: , 16 stars, 1 forks

    zimbatm/socketmaster:
      Zero downtime restarts for your apps
       51 commits, last change: , 408 stars, 20 forks
<!-- PROJECTS_LIST_END -->
