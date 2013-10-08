# statsd + graphite to go

Provision a virtual machine with vagrant and puppet to play around with statsd and graphite

## Details:

 * debian package for statsd (github.com/etsy) included 
 * port forwardings enabled
 * graphite: http://localhost:8080/
 * statsd: 8125:udp

## Instructions

```bash
git clone https://github.com/Jimdo/vagrant-statsd-graphite-puppet
cd vagrant-statsd-graphite-puppet
vagrant up
open http://localhost:8080
```