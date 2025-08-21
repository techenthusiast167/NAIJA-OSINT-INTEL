 # NAIJA OSINT INTEL - Nigeria's Premier Cybersecurity Suite

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![OSINT](https://img.shields.io/badge/OSINT-Tool-green)
![Cybersecurity](https://img.shields.io/badge/Cybersecurity-Suite-red)


**NAIJA OSINT INTEL** is a comprehensive open-source intelligence gathering tool specifically designed for Nigerian cybersecurity professionals, law enforcement, and digital investigators. This tool specializes in Nigerian cyber threat intelligence, scam detection, and judicial evidence collection.


# Why This Tool Matters

- **Nigeria-Focused**: Specifically designed for Nigerian cybercrime patterns
- **Legal Evidence**: Court-admissible evidence packaging capabilities
- **Comprehensive**: 11 specialized modules covering all OSINT & security aspects
- **Accessible**: Easy-to-use menu system for all skill levels


# Installation Requirements

## Install Python dependencies:

    pip install requests beautifulsoup4 colorama cryptography fpdf tldextract python-whois dnspython phonenumbers pillow exifread

## For advanced features:

    pip install selenium webdriver-manager spacy python-whois

## Download spaCy language model:

    python -m spacy download en_core_web_sm

## Browser Drivers (For Module 1)

- Install ChromeDriver automatically via webdriver-manager
- The tool will handle this automatically when needed


## Create your virtual environment:   

    virtualenv my_temp_venv
    source my_temp_venv/bin/activate

## Optional - make the tool executable:

    chmod +x naija_osint.py


## Run the Tool:


    python naija_osint.py 

---

# Modules Overview

**1. Nigeria Threat Intelligence Collector**

**Purpose**: Extract and analyze Nigerian-focused cyber threats with NLP labeling

**Usage**:

- Enter scam-related URLs (news sites, forums)

- Automatically labels content as SCAM/CYBER/FINANCIAL

- Output: JSON with highlighted keywords and categories

---

**2. Phishing & Scam Reporting**

**Purpose**: Detect 419 scams in emails/SMS with VirusTotal integration

**Usage**:

- Paste suspicious email content

- Get risk assessment score

- Manual VirusTotal URL checking guidance

---

**3. Mobile OSINT**

**Purpose**: Phone number analysis with carrier and geo-location data

**Usage**:

- Enter full number with country code (+234...)

- Get carrier, region, and Google dork queries

- Direct browser integration for quick searches

---

**4. Digital Property Intelligence**

**Purpose**: Domain investigation with WHOIS, DNS, and subdomain enumeration

**Usage**:

- Enter target domain (.ng domains supported)

- Get WHOIS data, DNS records, subdomains

- Special focus on Nigerian domains

---

**5. Image & Document Forensics**

**Purpose**: Metadata extraction and image authenticity verification

**Usage**:

- Provide image file path

- Extract EXIF data, GPS coordinates, hashes

- Reverse image search integration

- Error Level Analysis for tampering detection

---

**6. Malware & Botnet Tracker**

**Purpose**: Threat intelligence with AbuseIPDB integration

**Usage**:

- Enter IP addresses or domains

- Check abuse confidence scores

- Get detailed threat reports

---

**7. Automated Judicial Evidence Packager**

**Purpose**: Court-admissible evidence collection with chain of custody

**Usage**:

- Enter case ID and evidence file paths

- Automatic encryption and hashing

- PDF report generation with timestamps

- Chain of custody documentation


---

**8. IP Grabber Automation**

**Purpose**: Comprehensive IP address investigation

**Usage**:

- Single or multiple IP analysis

- Geolocation, WHOIS, port scanning

- Integration with Grabify and IP Logger

---

**9. Digital Footprint Investigation**

**Purpose**: Google dorking with pre-built templates

**Usage**:

- Enter target name/domain

- Choose from pre-built dork queries

- Direct browser integration

---

**10. N-G Business Registry Lookup**

**Purpose**: Nigerian business investigation via CAC portal

**Usage**:

- Direct access to CAC public search

- Business registration verification

- Corporate intelligence gathering

---

**11. Website Metadata Scraper**

**Purpose**: Comprehensive website intelligence gathering

**Usage:**

- Enter target URLs

- Extract emails, social links, security headers

- Entity extraction (persons, organizations, locations)

---
---

## Privacy & Legal Considerations

- **Data Handling**: All processing happens locally on your machine

- **No Data Storage**: The tool doesn't send data to external servers

- **Legal Compliance**: Designed for security resaerchers and legitimate OSINT investigators

- **Encryption**: Judicial evidence module includes AES encryption

---
---

## Responsible Usage

**This tool is intended for**:

- Cybersecurity professionals

- Law enforcement agencies

- Digital forensic investigators

- Ethical hackers with proper authorization

- **Warning**: Always obtain proper authorization before investigating any target.


  ---
  ---


## Contributing

**I welcome contributions! Areas for improvement**:

- Additional Nigerian-specific threat intelligence sources

- Improved NLP models for Nigerian English/Pidgin

- More local business database integrations

- Enhanced mobile network analysis



---
---

⭐ If you find this tool useful, please star the gist and share with colleagues!
