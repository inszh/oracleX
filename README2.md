port: 7890
socks-port: 7891
allow-lan: true
mode: Rule
log-level: info
external-controller: 127.0.0.1:9090
proxies:
  - {name: Oracle_WS, server: oraclex.arkfrp.life, port: 443, type: vmess, uuid: 3384c6c8-f37a-453c-a105-841bb6cfe3c8, alterId: 0, cipher: auto, tls: true, skip-cert-verify: true, network: ws, ws-opts: {path: /3384c6c8-f37a-453c-a105-841bb6cfe3c8, headers: {Host: oraclex.arkfrp.life}}, udp: true}
  - {name: Oracle_X811, server: oraclex811.arkfrp.life, port: 443, type: vmess, uuid: 6a7fbd6e-09b2-47d9-aede-7f8cd0e3f977, alterId: 0, cipher: auto, tls: true, skip-cert-verify: true, network: ws, ws-opts: {path: /6a7fbd6e-09b2-47d9-aede-7f8cd0e3f977, headers: {Host: oraclex811.arkfrp.life}}, udp: true}
proxy-groups:
