# robotsDisallowed 🤖

A lightweight security reconnaissance tool that extracts and analyzes disallowed paths from robots.txt files, helping security researchers and penetration testers discover potentially sensitive endpoints.

# Overview

robotsDisallowed automatically scans and extracts paths from robots.txt files, creating a comprehensive wordlist of potentially hidden or sensitive directories and files. While robots.txt files are intended to guide search engine crawlers, they often inadvertently reveal valuable information about a website's structure and sensitive areas that organizations want to keep hidden from search engines.

The tool leverages data from CommonCrawl and top million websites rankings to perform large-scale analysis of robots.txt files across the internet. This broad scanning capability allows for:

1. Creation of comprehensive wordlists based on real-world data
2. Identification of common patterns in restricted paths across different industries
3. Discovery of industry-specific sensitive endpoints and naming conventions

# Why Use robotsDisallowed?

### For Security Researchers

- Quick Reconnaissance: Rapidly identify potential sensitive endpoints without manual inspection
- Automated Wordlist Generation: Create custom wordlists for further security testing and directory bruteforcing
- Pattern Recognition: Identify common patterns in restricted paths that might indicate vulnerable areas
- Time Efficiency: Automate the initial phase of security assessment by quickly gathering potential target endpoints

### For Organizations

- Security Auditing: Verify that sensitive paths are properly protected, not just hidden from search engines
- Exposure Assessment: Understand what sensitive information might be exposed through robots.txt
- Configuration Review: Identify potentially misconfigured access controls
- Compliance Checking: Ensure sensitive paths are properly documented and protected according to security policies

# Disclaimer

This tool is intended for legal security testing and research purposes only. Users must obtain proper authorization before scanning any systems they don't own. The authors are not responsible for any misuse or damage caused by this tool.
