# Minimal DNS-over-HTTPS Blocklist

This repository provides a **minimal, safe regex list** to prevent
DNS-over-HTTPS (DoH) bypass in browsers and applications.

## Intended use
- Pi-hole (regex denylist)
- Networks with enforced DNS (pfSense, Unbound, etc.)

## What this list blocks
- Cloudflare DoH
- Firefox bootstrap DoH
- Google DoH
- Quad9 DoH
- NextDNS DoH

## What this list does NOT block
- Cloudflare CDN
- Google services
- SaaS platforms
- HTTP/3 globally

## Philosophy
> Block DoH by **protocol** at the firewall  
> Block **only DNS endpoints** at the DNS layer

Overblocking breaks networks. This list avoids that.
