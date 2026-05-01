
## Big platforms, clouds, and data clean rooms

| Company / product                             | What they claim to enable                                                                                                                                           |
| --------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **AWS Clean Rooms**                           | Multi-party analytics without sharing/revealing underlying raw data. ([Amazon Web Services, Inc.][1])                                                               |
| **AWS Nitro Enclaves**                        | Isolated compute environments for securely processing highly sensitive data; AWS also mentions multi-party computation use cases. ([Amazon Web Services, Inc.][2])  |
| **Google Ads Data Hub**                       | Privacy-centric advertising/measurement analytics while respecting user privacy. ([Google for Developers][3])                                                       |
| **Google Cloud Confidential Computing**       | Confidential computing for secure data collaboration, AI model training, analytics, and federated learning. ([Google Cloud Documentation][4])                       |
| **Google BigQuery Differential Privacy**      | Differential privacy support in BigQuery, built on Google’s open-source DP library. ([Google Cloud Documentation][5])                                               |
| **Microsoft Azure Confidential Computing**    | Hardware-based trusted execution environments to protect data while processed in the cloud. ([Microsoft Azure][6])                                                  |
| **IBM Confidential Computing Platform**       | Attested hardware-based TEEs to protect mission-critical workloads and sensitive data during processing. ([IBM][7])                                                 |
| **NVIDIA Confidential Computing**             | Confidential AI / GPU confidential computing for protecting AI models and sensitive data in shared or cloud environments. ([NVIDIA][8])                             |
| **Apple Private Cloud Compute**               | Cloud AI compute where personal user data sent to PCC is claimed not to be accessible to anyone other than the user, not even Apple. ([Apple Security Research][9]) |
| **Apple Differential Privacy**                | Opt-in device analytics using differential privacy to learn aggregate trends while protecting individual-level data. ([Apple Machine Learning Research][10])        |
| **Meta privacy-enhancing technologies / MPC** | Describes MPC and other PETs for ad measurement and private computation; Meta AI has also published on MPC-based ML. ([About Facebook][11])                         |
| **Snowflake Data Clean Rooms**                | Privacy-safe collaboration and multi-party analytics without moving data. ([Snowflake][12])                                                                         |
| **Databricks Clean Rooms**                    | Privacy-centric collaboration for data, analytics, and AI without direct access to raw data. ([Databricks][13])                                                     |
| **LiveRamp Clean Room**                       | Secure data collaboration with privacy and governance controls; LiveRamp acquired Habu, a clean-room software provider, in 2024. ([LiveRamp][14])                   |
| **InfoSum Secure Data Clean Room**            | Matching and analyzing datasets without sharing or moving data; claims patented PETs. ([InfoSum][15])                                                               |
| **AppsFlyer Data Clean Room**                 | Privacy-first / secure data collaboration for marketing and retail media use cases. ([AppsFlyer][16])                                                               |

## Cryptographic / PET specialist companies

| Company                         | Main PET angle                                                                                                                                                            |
| ------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Duality Technologies**        | Secure data collaboration using PETs including fully homomorphic encryption, federated learning, differential privacy, and TEEs. ([Duality Technologies][17])             |
| **Zama**                        | Open-source FHE company; focuses on FHE for blockchain and AI. ([Zama][18])                                                                                               |
| **Enveil**                      | Homomorphic-encryption-based encrypted search, analytics, and ML under its ZeroReveal product line. ([Enveil][19])                                       |
| **Decentriq**                   | Data clean rooms using confidential computing and homomorphic encryption; strong focus on media, healthcare, finance, and regulated data collaboration. ([Decentriq][20]) |
| **Roseman Labs**                | Secure multi-party computation for encrypted linking and analysis of sensitive datasets. ([Roseman Labs][21])                                                             |
| **Partisia**                    | Enterprise data collaboration based on multi-party computation; markets “zero trust data collaboration.” ([Partisia][22])                                                 |
| **Cybernetica / Sharemind MPC** | Secure data processing platform for collaborative analysis without revealing underlying data. ([Cybernetica][23])                                                         |
| **Tune Insight**                | Healthcare-focused secure collaboration using homomorphic encryption, secure multiparty computation, differential privacy, and federated learning. ([Tune Insight][24])   |
| **TripleBlind**                 | Privacy-preserving healthcare data collaboration; claims PETs including secure multi-party computation and federated learning. ([privacysuite.tripleblind.com][25])       |
| **Oasis Labs**                  | PrivateSQL and privacy-preserving partner analytics; also known for secure-enclave / privacy infrastructure. ([Oasis Labs][26])                                           |
| **Nillion**                     | “Blind computer” / decentralized private computation over encrypted sensitive data. ([Nillion Docs][27])                                                                  |
| **Cosmian**                     | Next-generation cryptography and confidential computing for “data in use”; offers verifiable confidential computing. ([Cosmian][28])                                      |
| **Secretarium**                 | Confidential computing platform that processes data while keeping it encrypted in memory, with no privileged runtime access. ([Secretarium][29])                          |
| **Sarus**                       | Differential-privacy-based privacy layer for analytics and AI; synthetic data and query rewriting. ([Sarus][30])                                                          |

## Confidential computing / secure enclave infrastructure vendors

| Company                                      | Main PET angle                                                                                                                       |
| -------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| **Fortanix**                                 | Confidential computing manager / Runtime Encryption for secure enclaves and privacy-preserving analytics. ([Fortanix][31])           |
| **Opaque Systems**                           | Confidential AI platform for running cloud-scale AI workloads on encrypted data using confidential computing. ([Opaque][32])         |
| **Anjuna**                                   | Secure enclave / confidential computing layer for running existing applications inside TEEs without major rewrites. ([Anjuna][33])   |
| **Edgeless Systems**                         | Confidential computing and privacy-preserving AI; open-source confidential computing tooling. ([Edgeless Systems][34])               |
| **Evervault**                                | Confidential computing / secure enclave product for running Docker containers in constrained compute environments. ([Evervault][35]) |
| **Intel Confidential Computing / SGX / TDX** | Hardware-level TEEs for protecting data in use; major enabling vendor rather than a data-analysis app provider. ([Intel][36])        |

## Differential privacy, anonymization, and synthetic-data companies

| Company                                   | Main PET angle                                                                                                                                                                    |
| ----------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Tumult Labs / Tumult Analytics**        | Differential privacy for safe data sharing and analytics; members of the Tumult team joined LinkedIn in 2025, and Tumult Analytics remains an OpenDP project. ([Tumult Labs][37]) |
| **Informatica / Privitar**                | Data privacy, access controls, anonymization, and privacy policy management; Informatica acquired Privitar in 2023. ([Informatica][38])                                           |
| **Tonic.ai**                              | De-identified and synthetic data for testing, development, and AI while preserving privacy/compliance. ([Tonic][39])                                                              |
| **Gretel / NVIDIA NeMo Safe Synthesizer** | Privacy-preserving synthetic data; Gretel materials discuss de-identification, differential privacy, similarity filters, and privacy monitoring. ([Gretel][40])                   |
| **MOSTLY AI**                             | Privacy-safe synthetic data platform with anonymization and differential-privacy-related controls. ([MOSTLY AI][41])                                                              |
| **YData**                                 | Synthetic data / data-for-AI platform; discusses synthetic data as privacy engineering and differential privacy controls. ([YData][42])                                           |

[1]: https://aws.amazon.com/clean-rooms/ "Data Collaboration Service – AWS Clean Rooms"
[2]: https://aws.amazon.com/ec2/nitro/nitro-enclaves/ "AWS Nitro Enclaves"
[3]: https://developers.google.com/ads-data-hub "Ads Data Hub"
[4]: https://docs.cloud.google.com/architecture/security/confidential-computing-analytics-ai "Confidential computing for data analytics, AI, and federated ..."
[5]: https://docs.cloud.google.com/bigquery/docs/differential-privacy "Use differential privacy | BigQuery"
[6]: https://azure.microsoft.com/en-us/solutions/confidential-compute "Azure Confidential Computing – Protect Data In Use"
[7]: https://www.ibm.com/products/confidential-computing-platform "IBM Confidential Computing Platform"
[8]: https://www.nvidia.com/en-us/data-center/solutions/confidential-computing/ "AI Security with Confidential Computing"
[9]: https://security.apple.com/blog/private-cloud-compute/ "Private Cloud Compute: A new frontier for AI privacy in the ..."
[10]: https://machinelearning.apple.com/research/differential-privacy-aggregate-trends "Understanding Aggregate Trends for Apple Intelligence ..."
[11]: https://about.fb.com/news/2021/08/privacy-enhancing-technologies-and-ads/ "What Are Privacy-Enhancing Technologies (PETs) and ..."
[12]: https://www.snowflake.com/en/product/features/data-clean-rooms/ "Snowflake Data Clean Rooms"
[13]: https://www.databricks.com/product/collaboration/clean-rooms "Databricks Clean Rooms: Privacy and Collaboration"
[14]: https://liveramp.com/our-platform/clean-rooms "LiveRamp Clean Room"
[15]: https://www.infosum.com/products/secure-data-clean-room "The Secure Data Clean Room"
[16]: https://www.appsflyer.com/products/data-collaboration/data-clean-room/ "AppsFlyer Data Clean Room | Privacy-First Collaboration"
[17]: https://dualitytech.com/ "Duality Tech | Secure, Privacy Protected Data Collaboration"
[18]: https://www.zama.org/ "Zama - Open Source Cryptography"
[19]: https://www.enveil.com/ "Enveil Is A Privacy Enhancing Technology Company | Enveil"
[20]: https://www.decentriq.com/ "Decentriq | Data collaboration and audience platform"
[21]: https://rosemanlabs.com/en/ "Roseman Labs: Encrypt, link & analyze sensitive data"
[22]: https://www.partisia.com/ "Partisia - Secure data sharing without compromise"
[23]: https://cyber.ee/products/sharemind-mpc/ "Sharemind MPC"
[24]: https://tuneinsight.com/en/about-us/ "Tune Insight - About us"
[25]: https://privacysuite.tripleblind.com/home/ "Privacy Suite – TripleBlind"
[26]: https://www.oasislabs.com/ "Oasis Labs"
[27]: https://docs.nillion.com/blind-computer/learn/overview "Blind Computer"
[28]: https://cosmian.com/ "Cosmian | We bring security to the public cloud"
[29]: https://www.secretarium.com/ "Secretarium | Private Cloud Compute"
[30]: https://www.sarus.tech/ "Sarus - The Privacy Layer for Analytics & AI"
[31]: https://www.fortanix.com/platform/confidential-computing-manager "Confidential Computing Manager Platform"
[32]: https://www.opaque.co/ "Confidential AI Platform for Trusted AI | Opaque"
[33]: https://www.anjuna.io/ "Anjuna Security: Autonomous Agents Need a Supervisor"
[34]: https://www.edgeless.systems/ "Edgeless Systems – Confidential Computing & Runtime ..."
[35]: https://evervault.com/solutions/confidential-computing "Confidential Computing"
[36]: https://www.intel.com/content/www/us/en/security/confidential-computing.html "Intel® Confidential Computing Solutions"
[37]: https://www.tmlt.io/ "Tumult Labs | Differential Privacy Made Easy"
[38]: https://www.informatica.com/about-us/news/news-releases/2023/06/20230614-informatica-announces-intent-to-acquire-privitar-to-bolster-cloud-data-access-management-and-governance-capabilities.html "Informatica Announces Intent to Acquire Privitar to Bolster ..."
[39]: https://www.tonic.ai/ "Tonic.ai: Synthetic Test Data Generation for Software and AI ..."
[40]: https://info.gretel.ai/guide-gdpr-ccpa "The Definitive Guide to Navigating the GDPR and CCPA"
[41]: https://mostly.ai/ "MOSTLY AI: Data Access and Data Insights for Everyone"
[42]: https://ydata.ai/ "YData data quality for Data Science | Synthetic data Data ..."
