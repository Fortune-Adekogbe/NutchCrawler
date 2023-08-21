# Apache Nutch Web Crawler

This project utilizes Apache Nutch to crawl websites and indexes the extracted data into Apache Solr, enabling powerful search capabilities.

## Prerequisites

- Java Development Kit (JDK)
- Windows Subsystem for Linux (WSL) for Windows users
- A Code Editor like Visual Studio Code

## Setup & Configuration

1. **Install and Configure Apache Nutch**:
   - Download and extract the latest version of Nutch.
   - Modify `nutch-site.xml` for specific configurations like Solr integration, crawl delay, etc.

2. **Install and Start Solr**:
   - Download, extract, and start Solr.
   - Create a new core for Nutch.

3. **Crawl Configuration**:
   - Set up seed URLs.
   - Configure `regex-urlfilter.txt` to specify allowed or disallowed URLs.

4. **Start the Crawl Process** using Nutch commands.

5. **View & Search Indexed Data** in Solr's Admin UI.

## Usage

- Initiate web crawls using Nutch's command line tools.
- View indexed data on Solr's Admin UI: `http://localhost:8983/solr/#/nutch/core-overview`.
- Use Solr's powerful search capabilities to search through the indexed content.