---
permalink: /compact-ids/
title: "Compact Identifiers"
layout: default
classes: wide
---


# Compact Identifiers (CURIEs)

```
Examples                         PDB:2gc4
                               Taxon:9606
                                 DOI:10.5281/ZENODO.1289856
                                 ark:/47881/m6g15z54
                                IGSN:SSH000SUA

General format                Prefix:LocalId

Registry links      -> full set of N2T prefix records
                    -> joint N2T/Identifiers.org prefix list
                    -> request to add a prefix to the list
Early adoption      -> Nature Scientic Data: On the road to robust data citation
Formal support      -> Memorandum of Understanding Between CDL and EMBL-EBI
```

## How they work

N2T.net is a kind of URL shortener for persistent identifiers. The above compact identifiers, also known as CURIEs (Compact URIs). They become actionable when appended to a URL based at N2T.net:

```
https://n2t.net/PDB:2gc4
https://n2t.net/Taxon:9606
https://n2t.net/DOI:10.5281/ZENODO.1289856
https://n2t.net/ark:/47881/m6g15z54
https://n2t.net/IGSN:SSH000SUA
```

Besides storing and resolving individual identifiers, N2T.net also stores resolution rules for entire classes, based on the prefixes. Failing to find a match after looking up an individual identifier, N2T looks for a rule associated with the identifier's prefix. Rules for the above identifiers result in the following redirects, respectively:

```
> http://www.rcsb.org/pdb/explore/explore.do?structureId=2gc4
> http://www.ncbi.nlm.nih.gov/Taxonomy/Browser/wwwtax.cgi?mode=Info&id=9606
> https://zenodo.org/record/1289856
> http://bibnum.univ-lyon1.fr/nuxeo/nxfile/default/49e1576c-0cae-4b4b-a63b-73370f476681/blobholder:0/THm_2014_NGUYEN_Marie_France.pdf
> https://app.geosamples.org/sample/igsn/SSH000SUA
```

There is a formal agreement between Identifiers.org and N2T.net to serve a common set of prefixes. You can read more about this effort and our plans to reach out to publishers to encourage adoption of inline citation of compact identifiers in [Uniform Resolution of Compact Identifiers for Biomedical Data](https://doi.org/10.1038/sdata.2018.95).
