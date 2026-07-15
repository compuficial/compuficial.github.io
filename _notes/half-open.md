---
layout: note
title: half open
date: 2025-08-21
---

if you stare at enough packet captures you start seeing handshakes in conversations. people SYN you. people ACK. people leave FIN hanging and call it a soft goodbye. RST is honesty. nobody wants RST. everybody wants the half-open forever connection where neither side admits the socket is dead

i have relationships like that. they show up in `ss -tp` as established and in real life as nothing
