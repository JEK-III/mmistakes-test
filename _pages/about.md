---
permalink: /about/
title: "About"
classes: wide
---

N2T.net (Name-to-Thing) is a "resolver," a kind of server that specializes in indirection. Resolvers serve content indirectly by forwarding most incoming requests to other servers rather than serving content directly (this page being an exception). Resolvers are good at redirecting requests to content servers, similar to URL shorteners like bit.ly and t.co.

## Origins of N2T

The name "n2t" was chosen for several reasons. First, it is unique enough to be easy to search for. Second, "n2t" is relatively opaque, which helps URLs based at n2t.net to age and travel well, the presumption being that brand- and language-neutrality can shield URLs from future embarrassment and forced retirement due to long term evolving political, legal, and usability pressures. The name is also short, which saves time and space – both in storage and in "visual real estate" – across often-repeated acts of transcription and citation. Finally, N2T's name was patterned after a set of IETF (the main Internet standards body) mapping operations for the URN (Uniform Resource Name) dating back to 1997 (RFC 2168): N2R (Name to Resource), N2L (Name to URL), and N2C (Name to URC, 'C' = Characteristics/Citation).

N2T's technical infrastructure arose from the demand for a global ARK (Archival Resource Key) resolver. All that a basic resolver needs is software to look up a given incoming string in a table and to issue a "server redirect", as found in every web server since 1992. The approach taken by many systems (Handle, DOI, etc.), is to create a "silo" that only works for one type of identifier. Because making lookups fail except for certain parts of the alphabet is exclusionary and artificial, the ARK resolver design took a more open and general approach. The result was N2T, a scheme-agnostic resolver that currently works for over 900 types of identifier, including ARKs, DOIs, Handles, PURLs, URNs, ORCIDs, ISSNs, etc.

The main use of N2T is for "persistent identifiers". An archive or publisher that gives out content links (URLs) starting with n2t.net doesn't need to worry about their breaking when content eventually moves to different servers. Provided forwarding rules at N2T are updated, links starting with n2t.net remain stable. (All persistent identifier systems rely on this same basic principle.)

## Features Unique to the N2T Resolver

Unlike URL shorteners, N2T can store more than one "target" (forwarding link) for an identifier, as well as any kind or amount of metadata (descriptive information) and links to metadata in different formats. When forwarding doesn't work for some reason, such as a temporary outage or insufficient permission at the target server, N2T can nonetheless return any persistent information it has about the identified object.

## Audience

The primary audience for N2T services is the global community of people engaged in research, academic, and cultural heritage endeavors. We work with national, university, and public libraries, academic and society publishers, natural history and art museums, as well as companies and funders that support education and research.

## Organizational Backing

N2T is maintained at the California Digital Library (CDL) within the University of California (UC) Office of the President (UCOP). CDL supports electronic library services for ten UC campuses and affiliated law schools, medical centers, and national laboratories, as well as hundreds of museums, herbaria, botanical gardens, etc. You may provide feedback on N2T via the CDL contact form.
N2T runs in the AWS (Amazon Web Services) cloud. On top of the foundational physical, network, and procedural security maintained by AWS datacenters located in the United States of America, N2T security and privacy is enhanced by additional CDL and UCOP privacy safeguards, patching policies, access restrictions, and firewall controls,
Maintenance Window
The N2T service may occasionally be suspended or interrupted for up to one hour during the routine maintenance window. If maintenance is to take place, it happens on Sundays beginning at 08:00 in California, UTC-08:00 (standard time), UTC-07:00 (daylight savings).
