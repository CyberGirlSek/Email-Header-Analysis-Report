# Email-Header-Analysis-Report
Analysis of a suspicious phishing email header."

## Project Overview
This project analyses a suspicious email received on **15th August 2024** with the subject line "Your balance: 1.3426 BTC". The email is identified as a phishing attempt, and this report provides a detailed analysis of the email header, IP address, domain name, and geolocation.

## Key Findings
- **Sender Email**: `franklin.polhaupessy@murni.co.id`
- **Reply-To Email**: `Support Inoutbqbcnge@parkcityaccomodation.com`
- **IP Address**: `202.137.25.204` (Flagged as malicious by 1/94 security vendors)
- **Domain**: `murni.co.id` (DMARC policy not enabled, blacklisted)
- **Geolocation**: Jakarta, Indonesia

## Tools Used
- **AbuseIPDB**: For IP address analysis.
- **VirusTotal**: For IP and domain reputation checks.
- **MX Toolbox**: For domain and email server analysis.
- **IP2Location**: For geolocation data.

## Repository Structure
- **report/**: Contains the full analysis report in PDF and a summary in Markdown.
- **data/**: Contains raw data such as email headers, IP details, and domain details.
- **tools/**: Lists the tools used for the analysis.
- **screenshots/**: Contains screenshots of analysis results from tools like AbuseIPDB, VirusTotal, and MX Toolbox.


## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
