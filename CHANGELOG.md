# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [1.0.1]
### Added
- Missing domains from Burning Umbrella Report for Area #1
  (20180503_Burning_Umbrella_Area_1_indicators.csv), thanks for the
  catch guys!

### Removed
- IOC files no longer include quotes around csv fields

## [1.0.0]
### Added
- Changelog to track post and changes to unified format
- Unifed format for machine readable IOCs in all IOC files
- Blacklist for cert and file type indicators
- README description of detections repo
- README description of unified IOC format
- Previous post added to Reports section of README that have no IOC, IDS, or other github docs
- Apache LICENSE descriptor
- ingest.py to read in all IOC/IDS/Blacklist as a python list()
- 20180503_Burning_Umbrella_Area_1_indicators.csv
- 20180503_Burning_Umbrella_Area_2_indicators.csv
- 20180503_Burning_Umbrella_Area_3_indicators.csv
- 20180503_Burning_Umbrella_Area_5_indicators.csv
- 20180503_Burning_Umbrella_Area_6_indicators.csv
- 20180503_Burning_Umbrella_Area_7_indicators.csv
- 20180503_Burning_Umbrella_Area_8_indicators.csv
- 20180503_Burning_Umbrella.pdf

### Changed
- ioc_urls.txt
- cert_bl.csv
- file_bl.csv
- Formating of IOCs to unified format addressed in README.md
- README.md : [Burning Umbrella: An Intelligence Report on the Winnti Umbrella and Associated State-Sponsored Attackers](https://401trg.pw/burning-umbrella/)

### Removed
- Defang Domains, IPs, and URLs in IOC files

## [0.6.0] - 2018-02-22
### Added
- 20180222_Analysis_of_Active_Satori_Botnet_Infections_indicators
- 20180222_Analysis_of_Active_Satori_Botnet_Infections__ids
- 20171220_Introduction_to_SMB_pcaps
- 20171220_Introduction_to_SMB_pdf
- 20171101_ExposingPhishing_indicators
- 20171101_ExposingPhishing_ids
- 20171026_LargeScaleIRC_indicators
- 20171026_LargeScaleIRC_ids
- 20171016_UpdateWinnti_indicators
- 20171016_UpdateWinnti_ids
- 20171010_TurlaWateringHole_indicators
- 20171010_TurlaWateringHole_ids
- 20170711_WinntiEvolution_indicators

### Changed
- README.md : [Analysis of Active Satori Botnet Infections](https://401trg.pw/analysis-of-active-satori-botnet-infections)
- README.md : [An Introduction to SMB for Network Security Analysts](https://401trg.pw/an-introduction-to-smb-for-network-security-analysts)
- README.md : [Exposing a Phishing Kit](https://401trg.pw/exposing-a-phishing-kit)
- README.md : [Large Scale IRCbot Infection Attempts](https://401trg.pw/large_scale_ircbot_infection_attempts)
- README.md : [An Update on Winnti](https://401trg.pw/an-update-on-winnti)
- README.md : [Turla Watering Hole Campaigns 2016/2017](https://401trg.pw/turla-watering-hole-campaigns-2016-2017)
- README.md : [Winnti (LEAD/APT17) Evolution - Going Open Source](https://401trg.pw/winnti-evolution-going-open-source)
