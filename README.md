# robotsDisallowed 🤖

<img src="https://github.com/ph0enix-protocol/robotsDisallowed/blob/main/robotsDisallowed.svg" />

> Transform robots.txt files into security reconnaissance goldmines - automated harvesting and analysis at scale.

## Overview
robotsDisallowed is an automated, all-in-one solution for harvesting and analyzing `robots.txt` files across the internet. It crawls public archives, processes robots.txt files, and extracts disallowed paths to aid in web assessments and security research.

## Why robots.txt?
The `robots.txt` file is used by websites to instruct web crawlers about which directories and files should not be crawled. However, these disallowed paths often reveal:
- 🔒 Sensitive administrative panels
- 🚪 Hidden directories
- 📁 Backup files
- 🛠️ Development environments
- 📌 Internal applications
- 🔑 Authentication endpoints

This information is invaluable for penetration testing, vulnerability research, and bug bounties.

## Key Features

### Data Collection
- **Multiple Dataset Integration:**
  - Common Crawl dataset processing
  - Top million websites scanning
  - Custom URL scanning capabilities

### Analysis & Processing
- **Intelligent Path Extraction:**
  - Automated disallowed path extraction
  - Pattern recognition and categorization
  - Duplicate removal and path normalization

### Wordlist Generation
- **Smart Wordlist Creation:**
  - Context-aware path filtering
  - Sensitivity-based categorization
  - Format-specific sorting (directories vs files)
  - Export in multiple formats (TXT, JSON, CSV)

## Why This Project Matters

  ### For Security Professionals
  - **Efficient Reconnaissance:** Quickly discover hidden endpoints, development environments, and sensitive paths that traditional scanners miss
  - **Time-Saving Automation:** Focus on testing rather than discovery by automating robots.txt analysis and wordlist generation
  - **Bug Bounty Advantage:** Find unique attack surfaces often overlooked by others and quickly identify potential vulnerabilities

  ### For Organizations
  - **Security Auditing:** Identify exposed sensitive paths, forgotten assets, and potential security gaps before attackers do
  - **Compliance Support:** Maintain an inventory of sensitive endpoints and ensure proper access controls for regulatory requirements
  - **Continuous Monitoring:** Track changes in exposed endpoints and integrate security checks into your development pipeline

robotsDisallowed turns overlooked robots.txt files into valuable security insights, making it essential for both offensive and defensive security teams.

## Future Roadmap 🚀

### Planned Features
- AI-powered wordlist generation combining:
  - robots.txt analysis
  - Web application content analysis
  - Pattern learning from successful findings
- Technology stack-specific filters
- Enhanced sensitivity detection

## Security Considerations ⚠️

This tool is designed for legitimate security research and authorized testing only. Users must:
- Obtain proper authorization before scanning any target
- Follow responsible disclosure practices
- Comply with all applicable laws and regulations
- Respect rate limits and scanning policies

## Contributing

Contributions are welcome! Please feel free to submit pull requests, report bugs, or suggest features.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

