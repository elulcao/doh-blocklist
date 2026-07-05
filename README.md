# Telemetry Safe Blocklist

This repository also provides a curated DNS blocklist for Pi-hole, AdGuard Home, NextDNS, Technitium DNS, and other
DNS-based blockers.

The list focuses on blocking telemetry, analytics, and marketing infrastructure while minimizing website and application
breakage.

## Purpose

The goal of this blocklist is to improve privacy by blocking services used for:

- Telemetry
- Analytics
- Marketing automation
- Attribution
- Customer engagement
- Feature flags
- Event collection

Unlike aggressive blocklists, this list intentionally excludes domains that commonly break functionality.

## Design Principles

- Block telemetry whenever possible.
- Minimize false positives.
- Preserve website and application functionality.
- Avoid breaking authentication, media playback, push notifications, embedded widgets, and consent management platforms.
- Prioritize usability over maximum blocking.

## Intended Use

This list is designed to complement general-purpose DNS blocklists, not replace them.

It works well alongside:

- Ad & tracker blocklists
- Malware blocklists
- Phishing protection
- Threat intelligence feeds

## Compatibility

Compatible with:

- Pi-hole
- AdGuard Home
- NextDNS
- Technitium DNS Server
- dnsmasq
- Any DNS sinkhole supporting hosts or domain-based blocklists

## Maintenance

Domains are periodically reviewed to ensure they still meet the project's criteria.

Domains that are cause widespread service breakage or are required for essential functionality are removed from the
list.

## Scope

This project intentionally targets only telemetry and related tracking infrastructure.

It does **not** attempt to block:

- All advertising domains
- CDN infrastructure
- Essential APIs
- Login providers
- Media delivery services
- Consent management platforms

The objective is simple:

> **Maximize privacy without sacrificing usability.**
