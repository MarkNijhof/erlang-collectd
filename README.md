# Erlang collectd application

[Collectd](http://www.collectd.org) is a system statistics collection daemon.

Erlang-collectd is a simple client wich talk to collectd daemon (in UDP).

# Test it

## Compilation

	./rebar compile
	./rebar test

## Collectd

Install (with brew, apt-get, rpm ...) **collectd**, configure it as a 
[network server](http://collectd.org/wiki/index.php/Networking_introduction)
and start it.

## Exemple use

Launch example.erl .

## Graphing

You can use _rrdtool_,
[kcollectd](http://www.forwiss.uni-passau.de/~berberic/Linux/kcollectd.html), 
[visage](http://auxesis.github.com/visage/) or any rrd graphing frontend.

# Use it in different erlang project

## Ejabberd

A module and a patch to log ejabberd activity is in _ejabberd_ folder.