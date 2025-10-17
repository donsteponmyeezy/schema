# schema

GEO validated schema for web pages. Rich metadata for objects on the page to help machines understand their purpose and relationships through graphs.

## Implementation

Put the JSON-LD formatted schema within a script tag as follows:
`<script type="application/ld+json" class="optimized-schema-graph">
  {schema goes here}
  </script>`

## Overview

This repository contains a comprehensive schema for embedding GEO (Geospatial) metadata into web pages. The schema is designed to enhance the understanding of web content by machines, enabling better indexing, searchability, and interoperability of geospatial data.

Each folder represents a website that has had been optimized for machine learning, with each JSON file representing a page within that website. Subfolders represent pages that have enough children to justify their own rich schema.

## TODO

- Add folders with example data for each commonly used type, for future reference
- Make basic schema validation tool, find incorrect typing and link to the schema.org page for that type
