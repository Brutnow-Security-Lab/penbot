# PenBot

PenBot is a simple penetration testing tool that performs subdomain enumeration, vulnerability scanning, port scanning, DNS enumeration, SSL certificate analysis, and generates reports.

// ...existing code...

## Features

- Subdomain enumeration
- Vulnerability scanning
- Port scanning
- Report generation
- DNS enumeration
- SSL certificate analysis
- AI-based vulnerability prioritization

## Installation

To install PenBot, clone the repository and install the dependencies:

```sh
git clone https://github.com/pentestool/penbot.git
cd penbot
pip install -r requirements.txt
```

## Configuration

Before running the tool, you can configure it by editing the `config.yaml` file located in the root directory. 

## Usage

To run the tool, use the following command:

```sh
penbot
```

For example, to perform a subdomain enumeration, use:

```sh
penbot --subdomain example.com
```

To perform a vulnerability scan, use:

```sh
penbot --scan example.com
```

To generate a report, use:

```sh
penbot --report example.com
```

To perform a port scan, use:

```sh
penbot --portscan example.com
```

To perform a DNS enumeration, use:

```sh
penbot --dns example.com
```

To perform an SSL certificate analysis, use:

```sh
penbot --ssl example.com
```

To prioritize vulnerabilities using AI, use:

```sh
penbot --ai-prioritize example.com
```

// ...existing code...
