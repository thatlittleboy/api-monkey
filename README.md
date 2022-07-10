# API Monkey
Host a web application that allows users to upload query data (csv, etc.), perform bulk queries to third-party data API, and automatically store the results in specified database.

WIP...

## Components
* front-end: streamlit; with data upload functionality
* async
* support for custom headers, GET/POST only.
* stream logging to screen, graceful handling of mid-cancellation
* auto-batching capabilities: to batch up large files into smaller batches
* connecting to db for data storage
* security: user auth (ignore for now)
