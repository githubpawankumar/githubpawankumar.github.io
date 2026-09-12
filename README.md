# Pawan Kumar Singh — Final Current Research Website

This package is the continuously updated public-facing research and publications site.

## What it shows
- Current research manuscripts and professional publications
- Contract Intelligence identified as submitted to Information Systems Frontiers
- LinkedIn business article hub
- ORCID, LinkedIn, and GitHub profile links

## What it intentionally does NOT do
- It does not upload journal-under-review manuscript PDFs publicly.
- It does not claim unpublished manuscripts are published.
- It does not guess Zenodo URLs or DOIs.
- It does not create duplicate website cards for older versions.

## Updating later
Edit only `publications.json` when:
- a manuscript is revised
- a paper is submitted
- a paper is accepted
- a Zenodo record/DOI is created
- a LinkedIn article is published

Then commit the updated `publications.json` to GitHub.

## GitHub files to replace
Upload/replace:
- index.html
- styles.css
- publications.json

You may also upload this README.md, but it is not required by the live site.


## Clickable research cards

Each research card opens an on-site detail modal containing:
- research summary
- research question
- methodology
- key findings
- research contribution
- keywords
- publication status

No manuscript PDF or download link is exposed. When an official publication or DOI becomes public, add `canonical_url` and/or `doi` to the matching record in `publications.json`.
