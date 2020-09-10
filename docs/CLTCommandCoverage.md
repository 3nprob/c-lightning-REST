### C-Lightning Commands Covered with the APIs

=== bitcoin ===
- [x] feerates
- [ ] fundpsbt
- [x] newaddr
- [ ] reserveinputs
- [ ] sendpsbt
- [ ] signpsbt
- [ ] txdiscard
- [ ] txprepare
- [ ] txsend
- [ ] unreserveinputs
- [x] withdraw

=== channels ===
- [x] close
- [ ] fundchannel_cancel
- [ ] fundchannel_complete
- [ ] fundchannel_start
- [x] getroute
- [x] listchannels
- [x] listforwards
- [x] setchannelfee

=== network ===
- [x] connect
- [x] disconnect
- [x] listnodes
- [x] listpeers
- [ ] ping

=== payment ===
- [ ] createonion
- [x] decodepay
- [x] delexpiredinvoice
- [x] delinvoice
- [x] invoice
- [x] listinvoices
- [x] listsendpays
- [ ] listtransactions
- [ ] sendonion
- [ ] sendpay
- [ ] waitanyinvoice
- [ ] waitinvoice
- [ ] waitsendpay

=== plugin ===
- [ ] autocleaninvoice
- [x] estimatefees
- [x] fundchannel
- [ ] getchaininfo
- [ ] getrawblockbyheight
- [ ] getutxout
- [x] keysend
- [ ] legacypay
- [x] listpays
- [x] pay
- [ ] paystatus
- [ ] plugin
- [ ] sendrawtransaction

=== utility ===
- [ ] check
- [x] checkmessage
- [x] getinfo
- [ ] getlog
- [ ] getsharedsecret
- [ ] help
- [ ] listconfigs
- [x] listfunds
- [x] signmessage
- [ ] stop
- [ ] waitblockheight

=== developer ===   
- [ ] dev-listaddrs
- [ ] dev-rescan-outputs