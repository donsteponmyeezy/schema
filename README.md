# schema

GEO validated schema for web pages. Rich metadata for objects on the page to help machines understand their purpose and relationships through graphs.

## Overview

This repository contains a comprehensive schema for embedding GEO (Generative Engine Optimization) metadata into web pages. The schema is designed to enhance the understanding of web content by machines, enabling better indexing, searchability, and interoperability of geospatial data.

Each folder represents a website that has had been optimized for machine learning, with each JSON file representing a page within that website. Subfolders represent pages that have enough children to justify their own rich schema.

## Usage

Each folder is named after a public website, and contains valid JSON-LD schema files named after the individual web pages. If you want to see how the schema works in real time:

1. Visit https://foldername/filename
2. Press f12 on windows or cmd + option + I on mac to open Chrome Dev Tools (or Firefox)
3. Clck in the source window and use ctrl + f to start searching
4. Search "Schema" and navigate down until you see the large block of JSON that corresponds with the file name you chose

## Implementation

1. Put the JSON-LD formatted schema within a script tag as follows:
`<script type="application/ld+json" class="optimized-schema-graph">
  {schema goes here}  </script>`

2. Upload this script tag to the <Head> of your website

## Future Releases

- Add folders with example data for each commonly used type, for future reference
- Integrate schema validation tool into a package command (npm run validate)
