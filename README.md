# OffensiveReading

A collection of papers about offensive IT security with some blogposts sprinkled in. This is basically a list of papers I found interesting. If you want to contribute a paper just open a issue or issue a pull request. 
Note: I started to put AI papers into other categories as well, since its getting used for fuzzing etc now as well

## Table of Contents

1. [Browsers / Browser Side Channel](#browsers--browser-side-channel)
2. [Vulnerability Discovery - Web](#vulnerability-discovery---web)
3. [XSS](#xss)
4. [CSS](#css)
5. [Web Cache](#web-cache)
6. [Network](#network)
7. [Windows](#windows)
8. [Side Channel Attacks](#side-channel-attacks)
9. [DNS](#dns)
10. [AI](#ai)
11. [Fuzzing / Exploitation / Vulnerability Discovery in Applications/Hardware](#fuzzing--exploitation--vulnerability-discovery-in-applicationshardware)
12. [Mobile/Radio](#mobileradio)
13. [IoT](#iot)
14. [Crypto/DeFi](#cryptodefi)
15. [BlueTeam](#blueteam)
16. [Misc/Other](#miscother)


## Browsers / Browser Side Channel
### Papers/Thesis
| Year | Title | Author | Link | Github/PoC |
| --- | --- | --- | --- | --- |
| 2023 | iLeakage: Browser-based Timerless Speculative Execution Attacks on Apple Devices | Jason Kim, Stephan van Schaik, Daniel Genkin, Yuval Yarom | [Link](https://ileakage.com/files/ileakage.pdf) | --- |
| 2023 | Chrowned by an Extension: Abusing the Chrome DevTools Protocol through the Debugger API | Jose Miguel Moreno, Narseo Vallina-Rodriguez, Juan Tapiador | [Link](https://arxiv.org/pdf/2305.11506) | --- |
| 2022 | Targeted Deanonymization via the Cache Side Channel: Attacks and Defenses | Mojtaba Zaheri, Yossi Oren, Reza Curtmola | [Link](https://www.usenix.org/system/files/sec22-zaheri.pdf) | --- |
| 2022 | Interactive History Sniffing with Dynamically-Generated QR Codes and CSS Difference Blending | Keith O’Neal, Scott Yilek | [Link](https://s%70%70ub%32%32:c%6Fnf%32%32%2f%2f@conferences.computer.org/sppub/pdfs/spw/2022/964300a335.pdf) | --- |
| 2022 | WebSpec: Towards Machine-Checked Analysis of Browser Security Mechanisms | Lorenzo Veronese, Benjamin Farinier, Mauro Tempesta, Marco Squarcina, Matteo Maffei | [Link](https://arxiv.org/pdf/2201.01649.pdf) | --- |
| 2022 | SOK: On the Analysis of Web Browser Security | Jungwon Lim, Yonghwi Jin, Mansour Alharthi, Xiaokuan Zhang, Jinho Jung, Rajat Gupta, Kuilin Li, Daehee Jang, Taesoo Kim | [Link](https://arxiv.org/pdf/2112.15561.pdf) | --- |
| 2021 | Categorizing Service Worker Attacks and Mitigations | Karthika Subramani, Jordan Jueckstock, Alexandros Kapravelos, Roberto Perdisci | [Link](https://arxiv.org/pdf/2111.07153.pdf) | --- |
| 2021 | Careful Who You Trust: Studying the Pitfalls of Cross-Origin Communication | Gordon Meiser, Pierre Laperdrix, Ben Stock | [Link](https://publications.cispa.saarland/3356/1/meiser2021cwyt.pdf) | --- |
| 2021 | Tales of Favicons and Caches: Persistent Tracking in Modern Browsers | Konstantinos Solomos, John Kristoff, Chris Kanich, Jason Polakis | [Link](https://www.cs.uic.edu/~polakis/papers/solomos-ndss21.pdf) | --- |
| 2021 | Timing-Based Browsing Privacy Vulnerabilities Via Site Isolation | Zihao Jin, Ziqiao Kong, Shuo Chen†, Haixin Duan | [Link](https://www.microsoft.com/en-us/research/uploads/prod/2021/10/SiteIsolationTimingChannel-cam-ready-2.pdf) | --- |
| 2021 | Pool-Party: Exploiting Browser Resource Pools as Side-Channels for Web Tracking | Peter Snyder, Soroush Karami, Benjamin Livshits, Hamed Haddadi | [Link](https://arxiv.org/pdf/2112.06324.pdf) | --- |
| 2021 | XSinator.com: From a Formal Model to the Automatic Evaluation of Cross-Site Leaks in Web Browsers | Lukas Knittel, Christian Mainka, Marcus Niemietz | [Link](https://xsinator.com/paper.pdf) | [Github](https://github.com/RUB-NDS/xsinator.com) [PoC](https://xsinator.com/) |
| 2021 | Remote Memory-Deduplication Attacks | Martin Schwarzl, Erik Kraft, Moritz Lipp, Daniel Gruss | [Link](https://arxiv.org/pdf/2111.08553.pdf) | --- |
| 2021 | T-Reqs: HTTP Request Smuggling with Differential Fuzzing | Bahruz Jabiyev, Steven Sprecher, Kaan Onarlioglu, Engin Kirda | [Link](https://bahruz.me/papers/ccs2021treqs.pdf) | [Github](https://github.com/bahruzjabiyev/t-reqs) |
| 2021 | An Empirical Analysis of HTTPS Configuration Security | Camelia Simoiu, Wilson Nguyen, Zakir Durumeric | [Link](https://arxiv.org/pdf/2111.00703.pdf) | --- |
| 2021 | Gummy Browsers: Targeted Browser Spoofing against State-of-the-Art Fingerprinting Techniques | zengrui liu, prakash shrestha, nitesh saxena | [Link](https://arxiv.org/pdf/2110.10129.pdf) | --- |
| 2021 | CorbFuzz: Checking Browser Security Policies with Fuzzing | Chaofan Shou,  ̇Ismet Burak Kadron, Qi Su, Tevfik Bultan | [Link](https://arxiv.org/pdf/2109.00398.pdf) | --- |
| 2021 | SoK: In Search of Lost Time: A Review of JavaScript Timers in Browsers. | Thomas Rokicki, Clémentine Maurice, Pierre Laperdrix | [Link](https://hal.inria.fr/hal-03215569) | --- |
| 2021 | Awakening the Web's Sleeper Agents: Misusing Service Workers for Privacy Leakage | Soroush Karami, Panagiotis Ilia, Jason Polakis | [Link](https://www.ndss-symposium.org/wp-content/uploads/ndss2021_1C-2_23104_paper.pdf) | |
| 2020 | Security and Privacy of Social Logins | Louis Christopher Jannett | [Link](https://www.nds.ruhr-uni-bochum.de/media/nds/arbeiten/2020/10/29/Masterarbeit_Louis_Jannett_Security_and_Privacy_of_Social_Logins.pdf) | --- |
| 2020 | Everything Old is New Again: Binary Security of WebAssembly | Daniel Lehmann, Johannes Kinder, Michael Pradel | [Link](https://www.usenix.org/system/files/sec20-lehmann.pdf) | --- |
| 2020 | Cross-Origin State Inference (COSI) Attacks:Leaking Web Site States through XS-Leaks | Avinash Sudhodanan, Soheil Khodayari, Juan Caballero | [Link](https://arxiv.org/pdf/1908.02204.pdf) |  |
| 2019 | BakingTimer: privacy analysis of server-side request processing time | Iskander Sánchez-Rola, D. Balzarotti, I. Santos | [Link](https://www.semanticscholar.org/paper/BakingTimer%3A-privacy-analysis-of-server-side-time-S%C3%A1nchez-Rola-Balzarotti/fcb40f635dc8195c8529585d7bfcde8920e0a57b) | |
| 2019 | Browser Fingerprinting using Combinatorial Sequence Testing | Bernhard Garn, Dimitris E. Simos, Stefan Zauner, Rick Kuhn, Raghu Kacker| [Link](https://tsapps.nist.gov/publication/get_pdf.cfm?pub_id=927531) |  |
| 2018 | Browser history re:visited | Michael Smith, Craig Disselkoen, Shravan Narayan, Fraser Brown, Deian Stefa | [Link](https://www.usenix.org/system/files/conference/woot18/woot18-paper-smith.pdf) | --- |
| 2018 | How Tracking Companies Circumvented Ad Blockers Using WebSockets | Muhammad Ahmad Bashir, Sajjad Arshad, Engin Kirda, William Robertson, Christo Wilson | [Link](https://sajjadium.github.io/files/imc2018websockets_paper.pdf) | --- |
| 2018 | HSTS Supports Targeted Surveillance | Paul Syverson, Matthew Traudt | [Link](https://www.usenix.org/system/files/conference/foci18/foci18-paper-syverson.pdf) | [Github](https://github.com/pastly/satis-hsts-tracking) |
| 2017 | Fantastic Timers and Where to Find Them: High-Resolution Microarchitectural Attacks in JavaScript | Michael Schwarz, Clémentine Maurice, Daniel Gruss, Stefan Mangard | [Link](https://gruss.cc/files/fantastictimers.pdf) | --- |
| 2017 | Practical Keystroke Timing Attacks in Sandboxed JavaScript | Moritz Lipp, Daniel Gruss, Michael Schwarz, David Bidner, Clementine Maurice, Stefan Mangard | [Link](https://mlq.me/download/keystroke_js.pdf) | [Github](https://github.com/IAIK/interruptjs) |
| 2016 | On the Incoherencies in Web Browser Access Control Policies | Kapil Singh, Alexander Moshchuk, Helen J. Wang, Wenke Lee | [Link](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/12/incoherencyAndWebAnalyzer.pdf) | --- |
| 2016 | HEIST: HTTP Encrypted Information can be Stolen through TCP-windows | Mathy Vanhoef,Tom Van Goethem | [Link](https://www.blackhat.com/docs/us-16/materials/us-16-VanGoethem-HEIST-HTTP-Encrypted-Information-Can-Be-Stolen-Through-TCP-Windows-wp.pdf) | |
| 2016 | Trusted Browsers for Uncertain Times | David Kohlbrenner, Hovav Shacham | [Link](https://www.usenix.org/system/files/conference/usenixsecurity16/sec16_paper_kohlbrenner.pdf) | --- |
| 2015 | The Spy in the Sandbox: Practical Cache Attacks in JavaScript and their Implications | Yossef Oren, Vasileios P. Kemerlis, Simha Sethumadhavan, Angelos D. Keromytis | [Link](http://www.cs.columbia.edu/~simha/spyjs.ccs15.pdf) | --- |
| 2015 | Practical Memory Deduplication Attacks in Sandboxed Javascript | Daniel Gruss(, David Bidner, Stefan Mangard | [Link](https://sci-hub.st/10.1007/978-3-319-24174-6_6) | --- |
| 2013 | Pixel Perfect Timing  Attacks with HTML5  | Paul Stone | [Link](https://web.archive.org/web/20200424035111/https://go.contextis.com/rs/140-OCV-459/images/Pixel_Perfect_Timing_Attacks_with_HTML5_Whitepaper%20(1).pdf) | [PoC](https://ndev.tk/visted/) |
| 2013 | Redefining Web Browser Principals with a Configurable Origin Policy | Yinzhi Cao, Vaibhav Rastogi, Zhichun Li, Yan Chen, Alexander Moshchuk | [Link](https://yinzhicao.org/COP/COP_DSN2013.pdf) | --- |
| 2010 | The Emperor’s New APIs: On the (In)Secure Usage of New Client-side Primitives | Steve Hanna, Eui Chul Richard Shin, Devdatta Akhawe, Arman Boehm, Prateek Saxena, Dawn Song | [Link](http://webblaze.cs.berkeley.edu/papers/w2sp2010ena.pdf) | --- |
| 2010 | Object views: Fine-grained sharing in browsers | Leo Meyerovich, Adrienne Porter Felt, Mark Miller | [Link](https://www.researchgate.net/publication/221022599_Object_views_Fine-grained_sharing_in_browsers) | --- |
| 2009 | Cross-origin javascript capability leaks: detection, exploitation, and defense | Adam Barth, Joel Weinberger,Dawn Song | [Link](http://webblaze.cs.berkeley.edu/papers/barth-weinberger-song.pdf) | --- |
| 2007 | Exposing Private Information by Timing Web Applications | Andrew Bortz, Dan Boneh, Palash Nandy | [Link](http://crypto.stanford.edu/~dabo/papers/webtiming.pdf) | --- |

### Blogposts
| Year | Title | Author | Link |
| --- | --- | --- | --- |
| 2021 | Examining JavaScript Inter-Process Communication in Firefox  | Frederik Braun | [Link](https://blog.mozilla.org/attack-and-defense/2021/04/27/examining-javascript-inter-process-communication-in-firefox/) |
| 2020 | Marginwidth/marginheight – the unexpected cross-origin communication channel | Michał Bentkowski | [Link](https://research.securitum.com/marginwidth-marginheight-the-unexpected-cross-origin-communication-channel/) |
| 2018 | Side-channel attacking browsers through CSS3 features | Ruslan Habalov | [Link](https://www.evonide.com/side-channel-attacking-browsers-through-css3-features/) |
| 2016 | CSS mix-blend-mode is bad for your browsing history | lcamtuf | [Link](https://lcamtuf.blogspot.com/2016/08/css-mix-blend-mode-is-bad-for-keeping.html) |
| NULL | History theft with CSS Boolean algebra | lcamtuf | [Link](https://lcamtuf.coredump.cx/css_calc/) |



## Vulnerability Discovery - Web
### Papers/Thesis
| Year | Title | Author | Link | Github/PoC  |
| --- | --- | --- | --- | --- |
| 2025 | BACFuzz: Exposing the Silence on Broken Access Control Vulnerabilities in Web Applications | I Putu Arya Dharmaadi, Mohannad Alhanahnah, Van-Thuan Pham, Fadi Mohsen, Fatih Turkmen | [Link](https://arxiv.org/pdf/2507.15984) | --- |
| 2025 | Quantifying Azure RBAC Wildcard Overreach | Christophe Parisel | [Link](https://arxiv.org/pdf/2506.10755) | --- |
| 2025 | PoCGen: Generating Proof-of-Concept Exploits for Vulnerabilities in Npm Packages | Deniz Simsek, Aryaz Eghbali, Michael Pradel | [Link](https://arxiv.org/pdf/2506.04962) | --- |
| 2025 | Cross-Origin Web Attacks via HTTP/2 Server Push and Signed HTTP Exchange | Pinji Chen, Jianjun Chen, Mingming Zhang, Qi Wang, Yiming Zhang, Mingwei Xu, Haixin Duan | [Link](https://www.ndss-symposium.org/wp-content/uploads/2025-1086-paper.pdf) | --- |
| 2025 | Eradicating the Unseen: Detecting, Exploiting, and Remediating a Path Traversal Vulnerability across GitHub | Jafar Akhoundali, Hamidreza Hamidi, Kristian Rietveld, Olga Gadyatskaya | [Link](https://arxiv.org/pdf/2505.20186v1) | --- |
| 2025 | Dancer in the Dark: Synthesizing and Evaluating Polyglots for Blind Cross-Site Scripting | Robin Kirchner, Jonas Möller, Marius Musch, David Klein, Konrad Rieck, Martin Johns | [Link](https://www.usenix.org/system/files/usenixsecurity24-kirchner.pdf) | [Github](https://github.com/polyxss/bxss) |
| 2025 | PanoptiChrome: A Modern In-browser Taint Analysis Framework | Rahul Kanyal, Smruti Sarangi | [Link](https://openreview.net/pdf?id=bxwn1m8Y0S) | --- |
| 2025 | Taint Analysis for Graph APIs Focusing on Broken Access Control | Leen Lambers, Lucas Sakizloglou, Taisiya Khakharova, Fernando Orejas | [Link](https://arxiv.org/pdf/2501.08947) | --- |
| 2025 | WAFFLED: Exploiting Parsing Discrepancies to Bypass Web Application Firewalls | Seyed Ali Akhavani, Bahruz Jabiyev, Ben Kallus, Cem Topcuoglu, Sergey Bratus, Engin Kirda | [Link](https://arxiv.org/pdf/2503.10846) | [github](https://github.com/sa-akhavani/waffled/) |
| 2024 | Characterizing JavaScript Security Code Smells | Vikas Kambhampati, Nehaz Hussain Mohammed, Amin Milani Fard | [Link](https://arxiv.org/pdf/2411.19358) | --- |
| 2024 | Towards Fine-Grained Webpage Fingerprinting at Scale | Xiyuan Zhao, Xinhao Deng, Qi Li, Yunpeng Liu, Zhuotao Liu, Kun Sun, Ke Xu | [Link](https://arxiv.org/pdf/2409.04341) | --- |
| 2024 | GHunter: Universal Prototype Pollution Gadgets in JavaScript Runtimes | Eric Cornelissen, Mikhail Shcherbakov, Musard Balliu | [Link](https://arxiv.org/pdf/2407.10812) | [Github](https://github.com/KTH-LangSec/ghunter) |
| 2024 | Fuzzing at Scale: The Untold Story of the Scheduler | Ivica Nikolic, Racchit Jain | [Link](https://arxiv.org/pdf/2406.18058) | --- |
| 2024 | What All the PHUZZ Is About: A Coverage-guided Fuzzer for Finding Vulnerabilities in PHP Web Applications | Sebastian Neef, Lorenz Kleissner, Jean-Pierre Seifert | [Link](https://arxiv.org/pdf/2406.06261) | [Link](https://github.com/gehaxelt/phuzz) |
| 2024 | The HTTP Garden: Discovering Parsing Vulnerabilities in HTTP/1.1 Implementations by Differential Fuzzing of Request Streams | Ben Kallus, Prashant Anantharaman, Michael Locasto, Sean W. Smith | [Link](https://arxiv.org/pdf/2405.17737) | [Github](https://github.com/narfindustries/http-garden) |
| 2024 | AssetHarvester: A Static Analysis Tool for Detecting Assets Protected by Secrets in Software Artifacts | Setu Kumar Basak, K. Virgil English, Ken Ogura, Vitesh Kambara, Bradley Reaves, Laurie Williams | [Link](https://arxiv.org/pdf/2403.19072) | --- |
| 2024 | Fingerprinting web servers through Transformer-encoded HTTP response headers | Patrick Darwinkel | [Link](https://arxiv.org/pdf/2404.00056) | [Github](https://github.com/Darwinkel/bachelor-thesis-information-science) |
| 2024 | AdvSQLi: Generating Adversarial SQL Injections against Real-world WAF-as-a-service | Zhenqing Qu, Xiang Ling, Ting Wang, Xiang Chen, Shouling Ji, Chunming Wu | [Link](https://arxiv.org/pdf/2401.02615) | --- |
| 2024 | EDEFuzz: A Web API Fuzzer for Excessive Data Exposures | Lianglu Pan, Shaanan Cohney, Toby Murray, Van-Thuan Pham | [Link](https://arxiv.org/ftp/arxiv/papers/2301/2301.09258.pdf) | [Github](https://github.com/Broken-Assumptions/EDEFuzz) |
| 2023 | Exploiting Client-Side Path Traversal CSRF is dead, long live CSRF | Maxence Schmitt | [Link](https://www.doyensec.com/resources/Doyensec_CSPT2CSRF_Whitepaper.pdf) | --- |
| 2023 | Parse Me, Baby, One More Time: Bypassing HTML Sanitizer via Parsing Differentials | David Klein, Martin Johns | [Link](https://www.ias.cs.tu-bs.de/publications/parsing_differentials.pdf) | [Github](https://github.com/ias-tubs/HTML_parsing_differentials) |
| 2023 | Unveiling the Invisible: Detection and Evaluation of Prototype Pollution Gadgets with Dynamic Taint Analysis | Mikhail Shcherbakov, Paul Moosbrugger, Musard Balliu | [Link](https://arxiv.org/pdf/2311.03919) | [Github](https://github.com/KTH-LangSec/Dasty) |
| 2023 | Measuring CDNs susceptible to Domain Fronting | Karthika Subramani, Roberto Perdisci, Pierros Skafidas | [Link](https://arxiv.org/pdf/2310.17851) | --- |
| 2023 | Stratosphere: Finding Vulnerable Cloud Storage Buckets | Jack Cable, Drew Gregory, Liz Izhikevich, Zakir Durumeric | [Link](https://arxiv.org/pdf/2309.13496) | --- |
| 2023 | From Prompt Injections to SQL Injection Attacks: How Protected is Your LLM-Integrated Web Application? | Rodrigo Pedro, Daniel Castro, Paulo Carreira, Nuno Santos | [Link](https://arxiv.org/pdf/2308.01990) | --- |
| 2023 | BertRLFuzzer: A BERT and Reinforcement Learning Based Fuzzer | Piyush Jha, Joseph Scott, Jaya Sriram Ganeshna, Mudit Singh, Vijay Ganesh | [Link](https://arxiv.org/pdf/2305.12534) | [Github](https://github.com/bert-rl-fuzzer/fuzzer) |
| 2023 | Exploiting Input Sanitization for Regex Denial of Service | Efe Barlas, Xin Du, James C. Davis | [Link](https://arxiv.org/pdf/2303.01996) | --- |
| 2023 | SSO-MONITOR: Fully-Automatic Large-Scale Landscape, Security, and Privacy Analyses of Single Sign-On in the Wild | Maximilian Westers, Tobias Wich, Louis Jannett, Vladislav Mladenov, Christian Mainka, Andreas Mayer | [Link](https://arxiv.org/pdf/2302.01024) | [Google Drive](https://drive.google.com/drive/folders/1NJbSjX5JZds-jxBJYiwrkoQ9GKVcMslS) |
| 2023 | Automated Black-box Testing of Mass Assignment Vulnerabilities in RESTful APIs | Davide Corradini, Michele Pasqua, Mariano Ceccato | [Link](https://arxiv.org/pdf/2301.01261) | [Github](https://github.com/SeUniVr/RestTestGen) |
| 2022 | FuzzOrigin: Detecting UXSS vulnerabilities in Browsers through Origin Fuzzing | Sunwoo Kim, Young Min Kim, Jaewon Hur, Suhwan Song, Gwangmu Lee, Byoungyoung Lee | [Link](https://www.usenix.org/system/files/sec22-kim.pdf) | [Github](https://github.com/compsec-snu/fuzzorigin) |
| 2022 | Mining Node.js Vulnerabilities via Object Dependence Graph and Query | Song Li, Mingqing Kang, Jianwei Hou, Yinzhi Cao | [Link](https://www.usenix.org/system/files/sec22-li-song.pdf) | [Github](https://github.com/Song-Li/ODGen) |
| 2022 | Web Cache Deception Escalates! | Seyed Ali Mirheidari, Matteo Golinelli, Kaan Onarlioglu, Engin Kirda, Bruno Crispo | [Link](https://www.usenix.org/system/files/sec22-mirheidari.pdf) | [Github](https://github.com/Golim/wcde) |
| 2022 | Exploring Phone-Based Authentication Vulnerabilities in Single Sign-On Systems | Matthew M. Tolbert, Elie M. Hess, Mattheus C. Nascimento, Yunsen Lei, Craig A. Shue | [Link](https://web.cs.wpi.edu/~cshue/research/icics22.pdf) | --- |
| 2022 | Pre-hijacked accounts: An Empirical Study of Security Failures in User Account Creation on the Web | Avinash Sudhodanan, Andrew Paverd | [Link](https://arxiv.org/pdf/2205.10174.pdf) | --- |
| 2022 | COOPER: Testing the Binding Code of Scripting Languages with Cooperative Mutation | Peng Xu, Yanhao Wang, Hong Hu, Purui Su | [Link](https://huhong789.github.io/papers/xu:cooper.pdf) | [Github](https://github.com/TCA-ISCAS/Cooper) |
| 2021 | JAW: Studying Client-side CSRF with Hybrid Property Graphs and Declarative Traversals | Soheil Khodayari, Giancarlo Pellegrino | [Link](https://www.usenix.org/system/files/sec21fall-khodayari.pdf) | [Github](https://github.com/SoheilKhodayari/JAW) |
| 2021 | Understanding Emerging Client-Side Web Vulnerabilities using Dynamic Program Analysis | Marius Steffens | [Link](https://publikationen.sulb.uni-saarland.de/bitstream/20.500.11880/31674/1/thesis_steffens_final_160721.pdf) | --- |
| 2021 | Deriving Semantics-Aware Fuzzers from Web API Schemas | Zac Hatfield-Dodds, Dmitry Dygalo | [Link](https://arxiv.org/pdf/2112.10328.pdf) | --- |
| 2021 | Black Widow: Blackbox Data-driven Web Scanning | Benjamin Eriksson, Giancarlo Pellegrino, Andrei Sabelfeld | [Link](https://publications.cispa.saarland/3224/1/blackwidow_sp2021.pdf) | |
| 2021 | Over 100 Bugs in a Row: Security Analysis of the Top-Rated Joomla Extensions | Marcus Niemietz, Mario Korth, Christian Mainka, Juraj Somorovsky | [Link](https://arxiv.org/pdf/2102.03131.pdf) | --- |
| 2021 | Security Vulnerability Detection Using Deep Learning Natural Language Processing | Noah Ziems, Shaoen Wu | [Link](https://arxiv.org/pdf/2105.02388.pdf) | --- |
| 2020 | Mailto: Me Your Secrets. On Bugs and Features in Email End-to-End Encryption | Jens Müller, Marcus Brinkmann, Damian Poddebniak, Sebastian Schinzel, Jörg Schwenk | [Link](https://www.nds.ruhr-uni-bochum.de/media/nds/veroeffentlichungen/2020/08/15/mailto-paper.pdf) | --- |
| 2020 | Can I Take Your Subdomain?Exploring Related-Domain Attacks in the Modern Web | Marco Squarcina, Mauro Tempesta, Lorenzo Veronese, Stefano Calzavara, Matteo Maffe | [Link](https://arxiv.org/pdf/2012.01946.pdf) | --- |
| 2020 | Cached and Confused: Web Cache Deception in the Wild | Seyed Ali Mirheidari, Sajjad Arshad, Kaan Onarlioglu, Bruno Crispo, Engin Kirda, William Robertson   | [Link](https://www.usenix.org/system/files/sec20-mirheidari.pdf) | --- |
| 2016 | A Comprehensive Formal Security Analysis of OAuth 2.0 | Daniel Fett, Ralf Kuesters, Guido Schmitz | [Link](https://arxiv.org/pdf/1601.01229) | --- |

## XSS
### Papers/Thesis
| Year | Title | Author | Link | Github/PoC  |
| --- | --- | --- | --- | --- |
| 2022 | Link: Black-Box Detection of Cross-Site Scripting Vulnerabilities Using Reinforcement Learning | Soyoung Lee, Seongil Wi, Sooel Son | [Link](https://wsp-lab.github.io/papers/lee-link-www22.pdf) | [Github](https://github.com/WSP-LAB/Link) |
| 2022 | FuzzOrigin: Detecting UXSS vulnerabilities in Browsers through Origin Fuzzing | Sunwoo Kim, Young Min Kim, Jaewon Hur, Suhwan Song, Gwangmu Lee, Byoungyoung Lee | [Link](https://www.usenix.org/system/files/sec22-kim.pdf) | [Github](https://github.com/compsec-snu/fuzzorigin) |
| 2022 | Twenty-Two Years Since Revealing Cross-Site Scripting Attacks: A Systematic Mapping And A Comprehensive Survey | Abdelhakim Hannousse, Salima Yahiouche, Mohamed Cherif Nait-Hamoud | [Link](https://arxiv.org/pdf/2205.08425.pdf) | --- |
| 2021 | Talking About My Generation: Targeted DOM-based XSS Exploit Generation using Dynamic Data Flow Analysis | Souphiane Bensalim, David Klein, Thomas Barber, Martin Johns | [Link](https://dl.acm.org/doi/pdf/10.1145/3447852.3458718) | --- |
| 2020 | PMForce: Systematically AnalyzingpostMessage Handlers at Scale | Marius Steffens, Ben Stock | [Link](https://people.cispa.io/ben.stock/papers/steffens2020pmforce.pdf) | [Github](https://github.com/mariussteffens/pmforce) |
| 2017 | Code-Reuse Attacks for the Web: Breaking Cross-Site Scripting Mitigations via Script Gadgets | Sebastian Lekies, Krzysztof Kotowicz, Samuel Groß, Eduardo A. Vela Nava, Martin Johns  | [Link](https://acmccs.github.io/papers/p1709-lekiesA.pdf) | --- |
| 2015 | Auto-Patching DOM-based XSS At Scale | Inian Parameshwaran, Enrico Budianto, Shweta Shinde, Hung Dang, Atul Sadhu, Prateek Saxena | [Link](https://www.comp.nus.edu.sg/~tsunami/papers/fse15-main.pdf) | --- |
| 2015 | DEXTERJS: Robust Testing Platform for DOM-Based XSSVulnerabilities | Inian Parameshwaran, Enrico Budianto, Shweta Shinde, Hung Dang, Atul Sadhu, Prateek Saxena | [Link](https://n.ethz.ch/~sshivaji/publications/dexterjs_fse15.pdf) | --- |
| 2013 | 25 Million Flows Later - Large-scale Detection of DOM-based XSS | Sebastian Lekies, Ben Stock, Martin Johns | [Link](https://people.cispa.io/ben.stock/papers/lekies2013flows.pdf) | --- |
| 2013 | mXSS Attacks:  Attacking well-secured Web-Applicationsby using innerHTML Mutations | Mario Heiderich, Jörg Schwenk, Tilman Frosch, Jonas Magazinius, Edward Z. Yang  | [Link](https://cure53.de/fp170.pdf) | --- |

### Blogposts
| Year | Title | Author | Link |
| --- | --- | --- | --- |
| 2021 | Exploiting Client-Side Prototype Pollution in the wild | [s1r1us](https://blog.s1r1us.ninja/) | [Link](https://blog.s1r1us.ninja/research/PP) |

## CSS
### Papers/Thesis
| Year | Title | Author | Link | Github/PoC  |
| --- | --- | --- | --- | --- |
| 2021 | Prime+Probe 1, JavaScript 0: Overcoming Browser-based Side-Channel Defenses | Anatoly Shusterman, Ayush Agarwal, Sioli O’Connell, Daniel Genkin, Yossi Oren, Yuval Yarom  | [Link](https://arxiv.org/pdf/2103.04952.pdf) | --- |
| 2021| Fingerprinting in Style: Detecting Browser Extensions via Injected Style Sheets | Pierre Laperdrix, Oleksii Starov, Quan Chen, Alexandros Kapravelos, Nick Nikiforakis | [Link](https://www.usenix.org/system/files/sec21fall-laperdrix.pdf) | [Github](https://github.com/plaperdr/fingerprinting-in-style) |
| 2020 | Confused by Path: Analysis of Path Confusion Based Attacks | Seyed Ali Mirheidari | [Link](https://iris.unitn.it/retrieve/handle/11572/280512/382175/rpo/) | --- |
| 2020 | Large-Scale Analysis of Style Injection by Relative Path Overwrite | Sajjad Arshad, Seyed Ali Mirheidari, Tobias Lauinger, Bruno Crispo, Engin Kirda, William Robertson  | [Link](https://arxiv.org/pdf/1811.00917.pdf) | --- |
| 2012 | Scriptless Attacks – Stealing the Pie Without Touching the Sill | Mario Heiderich, Marcus Niemietz, Felix Schuster, Thorsten Holz, Jörg Schwenk | [Link](https://www.nds.ruhr-uni-bochum.de/media/emma/veroeffentlichungen/2012/08/16/scriptlessAttacks-ccs2012.pdf) | --- |

### Blogposts
| Year | Title | Author | Link |
| --- | --- | --- | --- |
| 2021 | Data Exfiltration via CSS + SVG Font  | Masato Kinugawa | [Link](https://mksben.l0.cm/2021/11/css-exfiltration-svg-font.html) |
| 2021 | uBlock, I exfiltrate: exploiting ad blockers with CSS | Gareth Heyes | [Link](https://portswigger.net/research/ublock-i-exfiltrate-exploiting-ad-blockers-with-css) |
| 2019 | Better Exfiltration via HTML Injection | d0nut | [Link](https://d0nut.medium.com/better-exfiltration-via-html-injection-31c72a2dae8b) |

## Web Cache
### Papers/Thesis
| Year | Title | Author | Link | Github/PoC  |
| --- | --- | --- | --- | --- |
| 2024 | Hidden Web Caches Discovery | Matteo Golinelli, Bruno Crispo | [Link](https://arxiv.org/pdf/2407.16303) | [Github](https://github.com/golim/hidden-web-caches-discovery) |
| 2022 | Web Cache Deception Escalates! | Seyed Ali Mirheidari, Matteo Golinelli, Kaan Onarlioglu, Engin Kirda, Bruno Crispo | [Link](https://www.onarlioglu.com/publications/sec2022escalate.pdf) | [Github](https://github.com/Golim/wcde) |
| 2020 | Cached and Confused: Web Cache Deception in the Wild | Seyed Ali Mirheidari, Sajjad Arshad, Kaan Onarlioglu, Bruno Crispo, Engin Kirda, William Robertson   | [Link](https://www.usenix.org/system/files/sec20-mirheidari.pdf) | --- |
| 2019 | Your Cache Has Fallen: Cache-Poisoned Denial-of-Service Attack | Hoai Viet Nguyen, Luigi Lo Iacono, Hannes Federrath | [Link](https://cpdos.org/paper/Your_Cache_Has_Fallen__Cache_Poisoned_Denial_of_Service_Attack__Preprint_.pdf) | --- |



## Network
### Papers/Thesis
| Year | Title | Author | Link | Github/PoC  |
| --- | --- | --- | --- | --- |
| 2024 | Exploiting Sequence Number Leakage: TCP Hijacking in NAT-Enabled Wi-Fi Networks | Yuxiang Yang, Xuewei Feng, Qi Li, Kun Sun, Ziqiang Wang, Ke Xu | [Link](https://arxiv.org/pdf/2404.04601) | --- |
| 2024 | Off-Path TCP Hijacking in Wi-Fi Networks: A Packet-Size Side Channel Attack | Ziqiang Wang, Xuewei Feng, Qi Li, Kun Sun, Yuxiang Yang, Mengyuan Li, Ganqiu Du, Ke Xu, Jianping Wu | [Link](https://arxiv.org/pdf/2402.12716) | --- |
| 2023 | Passive SSH Key Compromise via Lattices | Keegan Ryan, Kaiwen He, George Arnold Sullivan, Nadia Heninger | [Link](https://eprint.iacr.org/2023/1711.pdf) | --- |
| 2020 | Timeless Timing Attacks: Exploiting Concurrency to Leak Secrets over Remote Connections | Tom Van Goethem, Christina Pöpper, Wouter Joosen, Mathy Vanhoef | [Link](https://www.usenix.org/system/files/sec20-van_goethem.pdf) | [Github](https://github.com/DistriNet/timeless-timing-attacks) |
| 2020 | EtherOops Exploring Practical Methods To Exploit Ethernet Packet In Packet Attacks | Ben Seri, Gregory Vishnepolsky, Yevgeny Yusepovsky | [Link](https://i.blackhat.com/USA-20/Thursday/us-20-Seri-EtherOops-Exploring-Practical-Methods-To-Exploit-Ethernet-Packet-In-Packet-Attacks-wp.pdf) | --- |


## Windows
### Papers/Thesis
| Year | Title | Author | Link | Github/PoC  |
| --- | --- | --- | --- | --- |
| 2024 | TIMEROASTING, TRUSTROASTING AND COMPUTER SPRAYING | Tom Tervoort | [Link](https://www.secura.com/uploads/whitepapers/Secura-WP-Timeroasting-v3.pdf) | [Github](https://github.com/SecuraBV/Timeroast) |
| 2022 | POPKORN: Popping Windows Kernel Drivers At Scale | Rajat Gupta, Lukas Dresel, Noah Spahn, Giovanni Vigna, Christopher Kruegel, Taesoo Kim | [Link](https://dl.acm.org/doi/pdf/10.1145/3564625.3564631) | [Github](https://github.com/ucsb-seclab/popkorn-artifact) |
| 2018 | Exploiting Regedit- Invisible Persistence & binary storage | eWhiteHats | [Link](https://github.com/ewhitehats/InvisiblePersistence/blob/master/InvisibleRegValues_Whitepaper.pdf) | [Github](https://github.com/ewhitehats/InvisiblePersistence) |

### Blogposts
| Year | Title | Author | Link |
| --- | --- | --- | --- |
| 2022 | DOing More Harm | Remy Hax | [Link](https://remyhax.xyz/posts/do-more-harm/) |
| 2022 | DOing Harm (Delivery Optimization) | Remy Hax | [Link](https://remyhax.xyz/posts/do-harm/) |
| 2022 | From KBs to CVEs: Understanding the Relationships Between Windows Security Updates and Vulnerabilities | Moran Zaks | [Link](https://claroty.com/2022/05/04/blog-research-from-kbs-to-cves-understanding-the-relationships-between-windows-security-updates-and-vulnerabilities/) |

## Side Channel Attacks
### Papers/Thesis
| Year | Title | Author | Link | Github/PoC  |
| --- | --- | --- | --- | --- |
| 2025 | "Energon": Unveiling Transformers from GPU Power and Thermal Side-Channels | Arunava Chaudhuri, Shubhi Shukla, Sarani Bhattacharya, Debdeep Mukhopadhyay | [Link](https://arxiv.org/pdf/2508.01768) | --- |
| 2025 | SUAD: Solid-Channel Ultrasound Injection Attack and Defense to Voice Assistants | Chao Liu, Zhezheng Zhu, Hao Chen, Zhe Chen, Kaiwen Guo, Penghao Wang, Jun Luo | [Link](https://arxiv.org/pdf/2508.02116) | --- |
| 2025 | Thermal-Aware 3D Design for Side-Channel Information Leakage | Dylan Stow, Russell Barnes, Eren Kurshan, Yuan Xie | [Link](https://arxiv.org/pdf/2508.02816) | --- |
| 2025 | GPUHammer: Rowhammer Attacks on GPU Memories are Practical | Chris S. Lin, Joyce Qu, Gururaj Saileshwar | [Link](https://arxiv.org/pdf/2507.08166) | [Github](https://github.com/sith-lab/gpuhammer) |
| 2025 | Enter, Exit, Page Fault, Leak: Testing Isolation Boundaries for Microarchitectural Leaks | Oleksii Oleksenko, Flavien Solt, Cédric Fournet, Jana Hofmann, Boris Köpf, Stavros Volos | [Link](https://arxiv.org/pdf/2507.06039) | [Github](https://github.com/microsoft/sca-fuzzer) |
| 2025 | SmartAttack: Air-Gap Attack via Smartwatches | Mordechai Guri | [Link](https://arxiv.org/pdf/2506.08866) | --- |
| 2025 | Efficient RL-based Cache Vulnerability Exploration by Penalizing Useless Agent Actions | Kanato Nakanishi, Soramichi Akiyama | [Link](https://arxiv.org/pdf/2506.07200) | --- |
| 2025 | Exploiting Inaccurate Branch History in Side-Channel Attacks | Yuhui Zhu, Alessandro Biondi | [Link](https://arxiv.org/pdf/2506.07263) | --- |
| 2025 | Power-Related Side-Channel Attacks using the Android Sensor Framework | Mathias Oberhuber, Martin Unterguggenberger, Lukas Maar, Andreas Kogler, Stefan Mangard | [Link](https://www.ndss-symposium.org/wp-content/uploads/2025-92-paper.pdf) | --- |
| 2025 | Secret Spilling Drive: Leaking User Behavior through SSD Contention | Jonas Juffinger, Fabian Rauscher, Giuseppe La Manna, Daniel Gruss | [Link](https://www.ndss-symposium.org/wp-content/uploads/2025-208-paper.pdf) | --- |
| 2025 | SILENT: A New Lens on Statistics in Software Timing Side Channels | Martin Dunsche, Patrick Bastian, Marcel Maehren, Nurullah Erinola, Robert Merget, Nicolai Bissantz, Holger Dette, Jörg Schwenk | [Link](https://arxiv.org/pdf/2504.19821) | --- |
| 2025 | Acoustic Side-Channel Attacks on a Computer Mouse | Mauro Conti, Marin Duroyon, Gabriele Orazi, Gene Tsudik | [Link](https://arxiv.org/pdf/2505.02725) | --- |
| 2025 | KernelSnitch: Side-Channel Attacks on Kernel Data Structures | Lukas Maar, Jonas Juffinger, Thomas Steinbauer, Daniel Gruss, Stefan Mangard | [Link](https://lukasmaar.github.io/papers/ndss25-kernelsnitch.pdf) | [Github](https://github.com/isec-tugraz/KernelSnitch) |
| 2025 | THOR: A Non-Speculative Value Dependent Timing Side Channel Attack Exploiting Intel AMX | Farshad Dizani, Azam Ghanbari, Joshua Kalyanapu, Darsh Asher, Samira Mirbagher Ajorpaz | [Link](https://arxiv.org/pdf/2502.17658) | --- |
| 2025 | U Can Touch This! Microarchitectural Timing Attacks via Machine Clears | Billy Bob Brumley | [Link](https://arxiv.org/pdf/2502.09864) | --- |
| 2024 | Power side-channel leakage localization through adversarial training of deep neural networks | Jimmy Gammell, Anand Raghunathan, Kaushik Roy | [Link](https://arxiv.org/pdf/2410.22425) | [Github](https://github.com/jimgammell/gan_side_channel_leakage_detector/tree/main) |
| 2024 | PIXHELL Attack: Leaking Sensitive Information from Air-Gap Computers via `Singing Pixels' | Mordechai Guri | [Link](https://arxiv.org/pdf/2409.04930) | --- |
| 2024 | Cache Timing Leakages in Zero-Knowledge Protocols | Shibam Mukherjee, Christian Rechberger, Markus Schofnegger | [Link](https://eprint.iacr.org/2024/1390) | --- |
| 2024 | Deep-TEMPEST: Using Deep Learning to Eavesdrop on HDMI from its Unintended Electromagnetic Emanations | Santiago Fernández, Emilio Martínez, Gabriel Varela, Pablo Musé, Federico Larroca | [Link](https://arxiv.org/pdf/2407.09717) | --- |
| 2024 | GbHammer: Malicious Inter-process Page Sharing by Hammering Global Bits in Page Table Entries | Keigo Yoshioka, Soramichi Akiyama | [Link](https://arxiv.org/pdf/2406.13119) | --- |
| 2024 | FAULT+PROBE: A Generic Rowhammer-based Bit Recovery Attack | Kemal Derya, M. Caner Tol, Berk Sunar | [Link](https://arxiv.org/pdf/2406.06943) | --- |
| 2024 | Last-Level Cache Side-Channel Attacks Are Feasible in the Modern Public Cloud (Extended Version) | Zirui Neil Zhao, Adam Morrison, Christopher W. Fletcher, Josep Torrellas | [Link](https://arxiv.org/pdf/2405.12469) | --- |
| 2024 | Impedance vs. Power Side-channel Vulnerabilities: A Comparative Study | Md Sadik Awal, Buddhipriya Gayanath, Md Tauhidur Rahman | [Link](https://arxiv.org/pdf/2405.06242) | --- |
| 2024 | Dynamic Frequency-Based Fingerprinting Attacks against Modern Sandbox Environments | Debopriya Roy Dipta, Thore Tiemann, Berk Gulmezoglu, Eduard Marin, Thomas Eisenbarth | [Link](https://arxiv.org/pdf/2404.10715) | --- |
| 2024 | PrintListener: Uncovering the Vulnerability of Fingerprint Authentication via the Finger Friction Sound | Man Zhou, Shuao Su, Qian Wang, Qi Li, Yuting Zhou, Xiaojing Ma, Zhengxiong Li | [Link](https://arxiv.org/pdf/2404.09214) | --- |
| 2024 | SNOW-SCA: ML-assisted Side-Channel Attack on SNOW-V | Harshit Saurabh, Anupam Golder, Samarth Shivakumar Titti, Suparna Kundu, Chaoyun Li, Angshuman Karmakar, Debayan Das | [Link](https://arxiv.org/pdf/2403.08267) | --- |
| 2024 | Acoustic Side Channel Attack on Keyboards Based on Typing Patterns | Alireza Taheritajar, Reza Rahaeimehr | [Link](https://arxiv.org/pdf/2403.08740) | --- |
| 2024 | Prime+Retouch: When Cache is Locked and Leaked | Jaehyuk Lee, Fan Sang, Taesoo Kim | [Link](https://arxiv.org/pdf/2402.15425) | --- |
| 2024 | Whispering Pixels: Exploiting Uninitialized Register Accesses in Modern GPUs | Frederik Dermot Pustelnik, Xhani Marvin Sass, Jean-Pierre Seifert | [Link](https://arxiv.org/pdf/2401.08881) | --- |
| 2023 | OverHear: Headphone based Multi-sensor Keystroke Inference | Raveen Wijewickrama, Maryam Abbasihafshejani, Anindya Maiti, Murtuza Jadliwala | [Link](https://arxiv.org/pdf/2311.02288) | --- |
| 2023 | A Systematic Evaluation of Automated Tools for Side-Channel Vulnerabilities Detection in Cryptographic Libraries | Antoine Geimer, Mathéo Vergnolle, Frédéric Recoules, Lesly-Ann Daniel, Sébastien Bardin, Clémentine Maurice | [Link](https://arxiv.org/pdf/2310.08153) | --- |
| 2023 | LeakyOhm: Secret Bits Extraction using Impedance Analysis | Saleh Khalaj Monfared, Tahoura Mosavirik, Shahin Tajik | [Link](https://arxiv.org/pdf/2310.07014) | --- |
| 2023 | From Dragondoom to Dragonstar: Side-channel Attacks and Formally Verified Implementation of WPA3 Dragonfly Handshake | Daniel De Almeida Braga, Natalia Kulatova, Mohamed Sabt, Pierre-Alain Fouque | [Link](https://arxiv.org/pdf/2307.09243) | --- |
| 2023 | AVX Timing Side-Channel Attacks against Address Space Layout Randomization | Hyunwoo Choi, Suryeon Kim, Seungwon Shin | [link](https://arxiv.org/pdf/2304.07940) | --- |
| 2022 | Physical Fault Injection and Side-Channel Attacks on Mobile Devices: A Comprehensive Analysis | Carlton Shepherda, Konstantinos Markantonakisa, Nico van Heijningenb, Driss Aboulkassimic,Clément Gainec, Thibaut Heckmann, David Naccache | [Link](https://arxiv.org/pdf/2105.04454) | --- |
| 2022 | Frequency Throttling Side-Channel Attack | Chen Liu, Abhishek Chakraborty, Nikhil Chawla, Neer Roggel | [Link](https://arxiv.org/pdf/2206.07012.pdf) | --- |
| 2022 | Hertzbleed: Turning Power Side-Channel Attacks Into Remote Timing Attacks on x86 | Yingchen Wang, Riccardo Paccagnella, Elizabeth Tang He, Hovav Shacham, Christopher W. Fletcher, David Kohlbrenner | [Link](https://www.hertzbleed.com/hertzbleed.pdf) | [Github](https://github.com/FPSG-UIUC/hertzbleed) |
| 2021 | Charger-Surfing: Exploiting a Power Line Side-Channel for Smartphone Information Leakage | Patrick Cronin, Xing Gao,  Chengmo Yang, Haining Wang | [Link](https://www.usenix.org/system/files/sec21-cronin.pdf) | --- |
| 2021 | Attacks of the Knights: Exploiting Non Uniform Cache Access Time | Farabi Mahmud, Sungkeun Kim, Harpreet Singh Chawla, Pritam Majumder, Jiayi Huang, Chia-Che Tsai, Eun Jung Kim, Abdullah Muzahid | [Link](https://arxiv.org/pdf/2112.10028.pdf) | --- |
| 2021 | Automated Side Channel Analysis of Media Software with Manifold Learning | Yuanyuan Yuan, Qi Pang, Shuai Wang | [Link](https://arxiv.org/pdf/2112.04947.pdf) | [Github](https://github.com/Yuanyuan-Yuan/Manifold-SCA) |
| 2021 | Practical Timing Side Channel Attacks on Memory Compression | Martin Schwarzl, Pietro Borrello, Daniel Gruss, Gururaj Saileshwar, Hanna Müller, Michael Schwarz | [Link](https://arxiv.org/pdf/2111.08404.pdf) | --- |
| 2021 | Touchtone leakage attacks via smartphone sensors: mitigation without hardware modification | Connor Bolton, Yan Long, Jun Han, Josiah Hester, Kevin Fu | [Link](https://arxiv.org/pdf/2109.13834.pdf) | --- |
| 2021 | Leaking Control Flow Information via the Hardware Prefetcher | Yun Chen, Lingfeng Pei, Trevor E. Carlson | [Link](https://arxiv.org/pdf/2109.00474.pdf) | --- |
| 2019 | SMoTherSpectre: Exploiting Speculative Executionthrough Port Contention | Atri Bhattacharyya, Alexandra Sandulescu, Matthias Neugschwandtner, Alessandro Sorniotti, Babak Falsafi, Mathias Payer, Anil Kurmus | [Link](https://hexhive.epfl.ch/publications/files/19CCS.pdf) | [Github](https://github.com/HexHive/SMoTherSpectre) |
| 2017 | Systematic Classification of Side-Channel Attacks: A Case Study for Mobile Devices | Raphael Spreitzer, Veelasha Moonsamy, Thomas Korak, Stefan Mangard | [Link](https://arxiv.org/pdf/1611.03748) | --- |
| 2016 | Timecop | [Link](https://post-apocalyptic-crypto.org/timecop/) | --- |


## DNS
### Papers/Thesis
| Year | Title | Author | Link | Github/PoC  |
| --- | --- | --- | --- | --- |
| 2023 | RESOLVERFUZZ: Automated Discovery of DNS Resolver Vulnerabilities with Query-Response Fuzzing | Qifan Zhang, Xuesong Bai, Xiang Li, Haixin Duan, Qi Li, Zhou Li | -[Link](https://arxiv.org/pdf/2310.03202) | -[Github](https://github.com/ResolverFuzz/ResolverFuzz) |
| 2022 | Under the Hood of DANE Mismanagement in SMTP | Hyeonmin Lee, Md. Ishtiaq Ashiq, Moritz Müller, Roland van Rijswijk-Deij, Taekyoung “Ted” Kwon, Taejoong Chung | [Link](https://www.usenix.org/system/files/sec22summer_lee.pdf) | [Artifacts](https://dane-study.github.io/) |
| 2022 | The Hijackers Guide To The Galaxy: Off-Path Taking Over Internet Resources | Tianxiang Dai, Philipp Jeitner, Haya Shulman, Michael Waidner | [Link](https://arxiv.org/pdf/2205.05473.pdf) | --- |
| 2021 | DNS and the DNS Cache Poisoning Attack | Avi Kak  | [Link](https://engineering.purdue.edu/kak/compsec/NewLectures/Lecture17.pdf) | |
| 2021 | The CNAME of the Game:Large-scale Analysis of DNS-based TrackingEvasion | Yana Dimova, Gunes Acar, Lukasz Olejnik, Wouter Joosen, Tom Van Goethem | [Link](https://arxiv.org/pdf/2102.09301.pdf) | --- |
| 2020 | Cross Layer Attacks and How to Use Them (forDNS Cache Poisoning, Device Tracking and More) | Amit Klein | [Link](https://arxiv.org/pdf/2012.07432.pdf) | --- |
| 2017 | Something From Nothing (There): Collecting Global IPv6 Datasets From DNS | Tobias Fiebig, Kevin Borgolte, Shuang Hao, Christopher Kruegel, Giovanni Vigna | [Link](https://ipv6.farm/publications/pam2017-nxdomain.pdf) | [Gitlab](https://gitlab.inet.tu-berlin.de/ptr6scan/toolchain) |
| 2011 | Bitsquatting  DNS    Hijacking    without    Exploitation | Dinaburg | [Link](https://media.blackhat.com/bh-us-11/Dinaburg/BH_US_11_Dinaburg_Bitsquatting_WP.pdf) | --- |
| 2005 | NXNSAttack: Recursive DNS Inefficiencies and Vulnerabilities | Yehuda Afek, Anat Bremler-Barr, Lior Shafir | [Link](https://arxiv.org/ftp/arxiv/papers/2005/2005.09107.pdf) | --- |

### Blogposts
| Year | Title | Author | Link |
| --- | --- | --- | --- |
| 2021 | Dangling DNS: Amazon EC2 IPs (Current State) | Mohamed Elbadry | [Link](https://blog.melbadry9.xyz/dangling-dns/aws/ddns-ec2-current-state) |




## AI
### Papers/Thesis
| Year | Title | Author | Link | Github/PoC  |
| --- | --- | --- | --- | --- |
| 2025 | Complete Evasion, Zero Modification: PDF Attacks on AI Text Detection | Aldan Creo | [Link](https://arxiv.org/pdf/2508.01887) | [Github](https://github.com/ACMCMC/PDFuzz) |
| 2025 | Whispering Agents: An event-driven covert communication protocol for the Internet of Agents | Kaibo Huang, Yukun Wei, WanSheng Wu, Tianhua Zhang, Zhongliang Yang, Linna Zhou | [Link](https://arxiv.org/pdf/2508.02188) | --- |
| 2025 | PentestJudge: Judging Agent Behavior Against Operational Requirements | Shane Caldwell, Max Harley, Michael Kouremetis, Vincent Abruzzo, Will Pearce | [Link](https://arxiv.org/pdf/2508.02921) | --- |
| 2025 | When Good Sounds Go Adversarial: Jailbreaking Audio-Language Models with Benign Inputs | Bodam Kim, Hiskias Dingeto, Taeyoun Kwon, Dasol Choi, DongGeon Lee, Haon Park, JaeHoon Lee, Jongho Shin | [Link](https://arxiv.org/pdf/2508.03365) | --- |
| 2025 | Untraceable DeepFakes via Traceable Fingerprint Elimination | Jiewei Lai, Lan Zhang, Chen Tang, Pengcheng Sun, Xinming Wang, Yunhao Wang | [Link](https://arxiv.org/pdf/2508.03067) | --- |
| 2025 | Manipulating LLM Web Agents with Indirect Prompt Injection Attack via HTML Accessibility Tree | Sam Johnson, Viet Pham, Thai Le | [Link](https://arxiv.org/pdf/2507.14799) | [Github](https://github.com/sej2020/manipulating-web-agents) |
| 2025 | Prompt Injection 2.0: Hybrid AI Threats | Jeremy McHugh, Kristina Šekrst, Jon Cefalu | [Link](https://arxiv.org/pdf/2507.13169) | --- |
| 2025 | Defending Against Prompt Injection With a Few DefensiveTokens | Sizhe Chen, Yizhu Wang, Nicholas Carlini, Chawin Sitawarin, David Wagner | [Link](https://arxiv.org/pdf/2507.07974) | --- |
| 2025 | Giving AI Agents Access to Cryptocurrency and Smart Contracts Creates New Vectors of AI Harm | Bill Marino, Ari Juels | [Link](https://arxiv.org/pdf/2507.08249) | --- |
| 2025 | We Urgently Need Privilege Management in MCP: A Measurement of API Usage in MCP Ecosystems | Zhihao Li, Kun Li, Boyang Ma, Minghui Xu, Yue Zhang, Xiuzhen Cheng | [Link](https://arxiv.org/pdf/2507.06250) | --- |
| 2025 | The Dark Side of LLMs Agent-based Attacks for Complete Computer Takeover | Matteo Lupinacci, Francesco Aurelio Pironti, Francesco Blefari, Francesco Romeo, Luigi Arena, Angelo Furfaro | [Link](https://arxiv.org/pdf/2507.06850) | --- |
| 2025 | PenTest2.0: Towards Autonomous Privilege Escalation Using GenAI | Haitham S. Al-Sinani, Chris J. Mitchell | [Link](https://arxiv.org/pdf/2507.06742) | --- |
| 2025 | The Hidden Threat in Plain Text: Attacking RAG Data Loaders | Alberto Castagnaro, Umberto Salviati, Mauro Conti, Luca Pajola, Simeone Pizzi | [Link](https://arxiv.org/pdf/2507.05093) | --- |
| 2025 | Control at Stake: Evaluating the Security Landscape of LLM-Driven Email Agents | Jiangrong Wu, Yuhong Nan, Jianliang Wu, Zitong Yao, Zibin Zheng | [Link](https://arxiv.org/pdf/2507.02699) | --- |
| 2025 | Meta SecAlign: A Secure Foundation LLM Against Prompt Injection Attacks | Sizhe Chen, Arman Zharmagambetov, David Wagner, Chuan Guo | [Link](https://arxiv.org/pdf/2507.02735) | --- |
| 2025 | Cybersecurity AI: The Dangerous Gap Between Automation and Autonomy | Víctor Mayoral-Vilches | [Link](https://arxiv.org/pdf/2506.23592) | --- |
| 2025 | On the Surprising Efficacy of LLMs for Penetration-Testing | Andreas Happe, Jürgen Cito | [Link](https://arxiv.org/pdf/2507.00829) | --- |
| 2025 | A Large-Scale Evolvable Dataset for Model Context Protocol Ecosystem and Security Analysis | Zhiwei Lin, Bonan Ruan, Jiahao Liu, Weibo Zhao | [Link](https://arxiv.org/pdf/2506.23474) | [Github](https://github.com/Snakinya/MCPCorpus) |
| 2025 | Advancing Jailbreak Strategies: A Hybrid Approach to Exploiting LLM Vulnerabilities and Bypassing Modern Defenses | Mohamed Ahmed, Mohamed Abdelmouty, Mingyu Kim, Gunvanth Kandula, Alex Park, James C. Davis | [Link](https://arxiv.org/pdf/2506.21972) | --- |
| 2025 | From LLMs to MLLMs to Agents: A Survey of Emerging Paradigms in Jailbreak Attacks and Defenses within LLM Ecosystem | Yanxu Mao, Tiehan Cui, Peipei Liu, Datao You, Hongsong Zhu | [Link](https://arxiv.org/pdf/2506.15170) | --- |
| 2025 | Doppelgänger Method: Breaking Role Consistency in LLM Agent via Prompt-based Transferable Adversarial Attack | Daewon Kang, YeongHwan Shin, Doyeon Kim, Kyu-Hwan Jung, Meong Hi Son | [Link](https://arxiv.org/pdf/2506.14539) | --- |
| 2025 | Weakest Link in the Chain: Security Vulnerabilities in Advanced Reasoning Models | Arjun Krishna, Aaditya Rastogi, Erick Galinkin | [Link](https://arxiv.org/pdf/2506.13726) | --- |
| 2025 | InfoFlood: Jailbreaking Large Language Models with Information Overload | Advait Yadav, Haibo Jin, Man Luo, Jun Zhuang, Haohan Wang | [Link](https://arxiv.org/pdf/2506.12274) | --- |
| 2025 | Exploiting AI for Attacks: On the Interplay between Adversarial AI and Offensive AI | Saskia Laura Schröer, Luca Pajola, Alberto Castagnaro, Giovanni Apruzzese, Mauro Conti | [Link](https://arxiv.org/pdf/2506.12519) | --- |
| 2025 | Today's Cat Is Tomorrow's Dog: Accounting for Time-Based Changes in the Labels of ML Vulnerability Detection Approaches | Ranindya Paramitha, Yuan Feng, Fabio Massacci | [Link](https://arxiv.org/pdf/2506.11939) | --- |
| 2025 | Disclosure Audits for LLM Agents | Saswat Das, Jameson Sandler, Ferdinando Fioretto | [Link](https://arxiv.org/pdf/2506.10171) | [Github](https://github.com/CMPLAudit/CMPL) |
| 2025 | ELFuzz: Efficient Input Generation via LLM-driven Synthesis Over Fuzzer Space | Chuyang Chen, Brendan Dolan-Gavitt, Zhiqiang Lin | [Link](https://arxiv.org/pdf/2506.10323) | --- |
| 2025 | Bias Amplification in RAG: Poisoning Knowledge Retrieval to Steer LLMs | Linlin Wang, Tianqing Zhu, Laiqiao Qin, Longxiang Gao, Wanlei Zhou | [Link](https://arxiv.org/pdf/2506.11415) | --- |
| 2025 | LLMail-Inject: A Dataset from a Realistic Adaptive Prompt Injection Challenge | Sahar Abdelnabi, Aideen Fay, Ahmed Salem, Egor Zverev, Kai-Chieh Liao, Chi-Huang Liu, Chun-Chih Kuo, Jannis Weigend, Danyael Manlangit, Alex Apostolov, Haris Umair, João Donato, Masayuki Kawakita, Athar Mahboob, Tran Huu Bach, Tsun-Han Chiang, Myeongjin Cho, Hajin Choi, Byeonghyeon Kim, Hyeonjin Lee, Benjamin Pannell, Conor McCauley, Mark Russinovich, Andrew Paverd, Giovanni Cherubin | [Link](https://arxiv.org/pdf/2506.09956) | --- |
| 2025 | AI-Based Software Vulnerability Detection: A Systematic Literature Review | Samiha Shimmi, Hamed Okhravi, Mona Rahimi | [Link](https://arxiv.org/pdf/2506.09956) | [Github](https://github.com/microsoft/llmail-inject-challenge-analysis) |
| 2025 | AdInject: Real-World Black-Box Attacks on Web Agents via Advertising Delivery | Haowei Wang, Junjie Wang, Xiaojun Jia, Rupeng Zhang, Mingyang Li, Zhe Liu, Yang Liu, Qing Wang | [Link](https://arxiv.org/pdf/2505.21499) | [Github](https://github.com/NicerWang/AdInject) |
| 2025 | Mind the Web: The Security of Web Use Agents | Avishag Shapira, Parth Atulbhai Gandhi, Edan Habler, Oleg Brodt, Asaf Shabtai | [Link](https://arxiv.org/pdf/2506.07153) | --- |
| 2025 | PoCGen: Generating Proof-of-Concept Exploits for Vulnerabilities in Npm Packages | Deniz Simsek, Aryaz Eghbali, Michael Pradel | [Link](https://arxiv.org/pdf/2506.04962) | --- |
| 2025 | BitBypass: A New Direction in Jailbreaking Aligned Large Language Models with Bitstream Camouflage | Kalyan Nakka, Nitesh Saxena | [Link](https://arxiv.org/pdf/2506.02479) | [Github](https://github.com/kalyan-nakka/BitBypass) |
| 2025 | Beyond the Protocol: Unveiling Attack Vectors in the Model Context Protocol Ecosystem | Hao Song, Yiming Shen, Wenxuan Luo, Leixin Guo, Ting Chen, Jiashui Wang, Beibei Li, Xiaosong Zhang, Jiachi Chen | [Link](https://arxiv.org/pdf/2506.02040) | --- |
| 2025 | CyberGym: Evaluating AI Agents' Cybersecurity Capabilities with Real-World Vulnerabilities at Scale | Zhun Wang, Tianneng Shi, Jingxuan He, Matthew Cai, Jialin Zhang, Dawn Song | [Link](https://arxiv.org/pdf/2506.02548) | [Link](https://github.com/sunblaze-ucb/cybergym) |
| 2025 | Seven Security Challenges That Must be Solved in Cross-domain Multi-agent LLM Systems | Ronny Ko, Jiseong Jeong, Shuyuan Zheng, Chuan Xiao, Tae-Wan Kim, Makoto Onizuka, Won-Yong Shin | [Link](https://arxiv.org/pdf/2505.23847) | --- |
| 2025 | A Reward-driven Automated Webshell Malicious-code Generator for Red-teaming | Yizhong Ding | [Link](https://arxiv.org/pdf/2505.24252) | --- |
| 2025 | YuraScanner: Leveraging LLMs for Task-driven Web App Scanning | Aleksei Stafeev, Tim Recktenwald, Gianluca De Stefano, Soheil Khodayari, Giancarlo Pellegrino | [Link](https://www.ndss-symposium.org/wp-content/uploads/2025-388-paper.pdf) | [Github](https://github.com/pixelindigo/yurascanner/tree/ndss25) |
| 2025 | I Know What You Asked: Prompt Leakage via KV-Cache Sharing in Multi-Tenant LLM Serving | Guanlong Wu, Zheng Zhang, Yao Zhang, Weili Wang, Jianyu Niu, Ye Wu, Yinqian Zhang | [Link](https://www.ndss-symposium.org/wp-content/uploads/2025-1772-paper.pdf) | --- |
| 2025 | Silent Leaks: Implicit Knowledge Extraction Attack on RAG Systems through Benign Queries | Yuhao Wang, Wenjie Qu, Yanze Jiang, Zichen Liu, Yue Liu, Shengfang Zhai, Yinpeng Dong, Jiaheng Zhang | [Link](https://arxiv.org/pdf/2505.15420) | --- |
| 2025 | ReCopilot: Reverse Engineering Copilot in Binary Analysis | Guoqiang Chen, Huiqi Sun, Daguang Liu, Zhiqi Wang, Qiang Wang, Bin Yin, Lu Liu, Lingyun Ying | [Link](https://arxiv.org/pdf/2505.16366) | --- |
| 2025 | Invisible Prompts, Visible Threats: Malicious Font Injection in External Resources for Large Language Models | Junjie Xiong, Changjia Zhu, Shuhang Lin, Chong Zhang, Yongfeng Zhang, Yao Liu, Lingyao Li | [Link](https://arxiv.org/pdf/2505.16957) | --- |
| 2025 | Lessons from Defending Gemini Against Indirect Prompt Injections | Chongyang Shi, Sharon Lin, Shuang Song, Jamie Hayes, Ilia Shumailov, Itay Yona, Juliette Pluto, Aneesh Pappu, Christopher A. Choquette-Choo, Milad Nasr, Chawin Sitawarin, Gena Gibson, Andreas Terzis, John "Four" Flynn | [Link](https://arxiv.org/pdf/2505.14534) | --- |
| 2025 | IP Leakage Attacks Targeting LLM-Based Multi-Agent Systems | Liwen Wang, Wenxuan Wang, Shuai Wang, Zongjie Li, Zhenlan Ji, Zongyi Lyu, Daoyuan Wu, Shing-Chi Cheung | [Link](https://arxiv.org/pdf/2505.12442) | --- |
| 2025 | The Hidden Dangers of Browsing AI Agents | Mykyta Mudryi, Markiyan Chaklosh, Grzegorz Wójcik | [Link](https://arxiv.org/pdf/2505.13076) | --- |
| 2025 | A Large-Scale Empirical Analysis of Custom GPTs' Vulnerabilities in the OpenAI Ecosystem | Sunday Oyinlola Ogundoyin, Muhammad Ikram, Hassan Jameel Asghar, Benjamin Zi Hao Zhao, Dali Kaafar | [Link](https://arxiv.org/pdf/2505.08148) | --- |
| 2025 | Red Teaming the Mind of the Machine: A Systematic Evaluation of Prompt Injection and Jailbreak Vulnerabilities in LLMs | Chetan Pathade | [Link](https://arxiv.org/pdf/2505.04806) | --- |
| 2025 | AGENTFUZZER: Generic Black-Box Fuzzing for Indirect Prompt Injection against LLM Agents | Zhun Wang, Vincent Siu, Zhe Ye, Tianneng Shi, Yuzhou Nie, Xuandong Zhao, Chenguang Wang, Wenbo Guo, Dawn Song | [Link](https://arxiv.org/pdf/2505.05849) | --- |
| 2025 | Weaponizing Language Models for Cybersecurity Offensive Operations: Automating Vulnerability Assessment Report Validation; A Review Paper | Abdulrahman S Almuhaidib, Azlan Mohd Zain, Zalmiyah Zakaria, Izyan Izzati Kamsani, Abdulaziz S Almuhaidib | [Link](https://arxiv.org/pdf/2505.04265) | --- |
| 2025 | Building A Secure Agentic AI Application Leveraging A2A Protocol | Idan Habler, Ken Huang, Vineeth Sai Narajala, Prashant Kulkarni | [Link](https://arxiv.org/pdf/2504.16902) | --- |
| 2025 | LLMpatronous: Harnessing the Power of LLMs For Vulnerability Detection | Rajesh Yarra | [Link](https://arxiv.org/pdf/2504.18423) | --- |
| 2025 | WASP: Benchmarking Web Agent Security Against Prompt Injection Attacks | Ivan Evtimov, Arman Zharmagambetov, Aaron Grattafiori, Chuan Guo, Kamalika Chaudhuri | [Link](https://arxiv.org/pdf/2504.18575) | [Github](https://github.com/facebookresearch/wasp) |
| 2025 | Prompt Injection Attack to Tool Selection in LLM Agents | Jiawen Shi, Zenghui Yuan, Guiyao Tie, Pan Zhou, Neil Zhenqiang Gong, Lichao Sun | [Link](https://arxiv.org/pdf/2504.19793) | --- |
| 2025 | The Automation Advantage in AI Red Teaming | Rob Mulla, Ads Dawson, Vincent Abruzzon, Brian Greunke, Nick Landers, Brad Palm, Will Pearce | [Link](https://arxiv.org/pdf/2504.19855) | --- |
| 2025 | Good News for Script Kiddies? Evaluating Large Language Models for Automated Exploit Generation | David Jin, Qian Fu, Yuekang Li | [Link](https://arxiv.org/pdf/2505.01065) | --- |
| 2025 | ACE: A Security Architecture for LLM-Integrated App Systems | Evan Li, Tushin Mallick, Evan Rose, William Robertson, Alina Oprea, Cristina Nita-Rotaru | [Link](https://arxiv.org/pdf/2504.20984) | --- |
| 2025 | CAI: An Open, Bug Bounty-Ready Cybersecurity AI | Víctor Mayoral-Vilches, Luis Javier Navarrete-Lozano, María Sanz-Gómez, Lidia Salas Espejo, Martiño Crespo-Álvarez, Francisco Oca-Gonzalez, Francesco Balassone, Alfonso Glera-Picón, Unai Ayucar-Carbajo, Jon Ander Ruiz-Alcalde, Stefan Rass, Martin Pinzger, Endika Gil-Uriarte | [Link](https://arxiv.org/pdf/2504.06017) | [Github](https://github.com/aliasrobotics/cai) |
| 2025 | BreachSeek: A Multi-Agent Automated Penetration Tester | Ibrahim Alshehri, Adnan Alshehri, Abdulrahman Almalki, Majed Bamardouf, Alaqsa Akbar | [Link](https://arxiv.org/pdf/2409.03789) | [Github](https://github.com/snow10100/pena/) |
| 2025 | Prompt, Divide, and Conquer: Bypassing Large Language Model Safety Filters via Segmented and Distributed Prompt Processing | Johan Wahréus, Ahmed Hussain, Panos Papadimitratos | [Link](https://arxiv.org/pdf/2503.21598) | --- |
| 2025 | AutoRedTeamer: Autonomous Red Teaming with Lifelong Attack Integration | Andy Zhou, Kevin Wu, Francesco Pinto, Zhaorun Chen, Yi Zeng, Yu Yang, Shuang Yang, Sanmi Koyejo, James Zou, Bo Li | [Link](https://arxiv.org/pdf/2503.15754) | [Link](https://autoredteamer.com/) |
| 2025 | JBFuzz: Jailbreaking LLMs Efficiently and Effectively Using Fuzzing | Vasudev Gohil | [Link](https://arxiv.org/pdf/2503.08990) | --- |
| 2025 | VulnBot: Autonomous Penetration Testing for A Multi-Agent Collaborative Framework | He Kong, Die Hu, Jingguo Ge, Liangxiong Li, Tong Li, Bingzhen Wu | [Link](https://arxiv.org/pdf/2501.13411) | [Github](https://github.com/KHenryAegis/VulnBot) |
| 2025 | RapidPen: Fully Automated IP-to-Shell Penetration Testing with LLM-based Agents | Sho Nakatani | [Link](https://arxiv.org/pdf/2502.16730) | --- |
| 2025 | Red-Teaming LLM Multi-Agent Systems via Communication Attacks | Pengfei He, Yupin Lin, Shen Dong, Han Xu, Yue Xing, Hui Liu | [Link](https://arxiv.org/pdf/2502.14847) | --- |
| 2025 | Rerouting LLM Routers | Avital Shafran, Roei Schuster, Thomas Ristenpart, Vitaly Shmatikov | [Link](https://arxiv.org/pdf/2501.01818) | --- |
| 2025 | Auto-RT: Automatic Jailbreak Strategy Exploration for Red-Teaming Large Language Models | Yanjiang Liu, Shuhen Zhou, Yaojie Lu, Huijia Zhu, Weiqiang Wang, Hongyu Lin, Ben He, Xianpei Han, Le Sun | [Link](https://arxiv.org/pdf/2501.01830) | [Github](https://github.com/icip-cas/Auto-RT/tree/main) |
| 2024 | ExpShield: Safeguarding Web Text from Unauthorized Crawling and Language Modeling Exploitation | Ruixuan Liu, Toan Tran, Tianhao Wang, Hongsheng Hu, Shuo Wang, Li Xiong | [Link](https://arxiv.org/pdf/2412.21123) | --- |
| 2024 | Vulnerability Detection in Popular Programming Languages with Language Models | Syafiq Al Atiiq, Christian Gehrmann, Kevin Dahlén | [Link](https://arxiv.org/pdf/2412.15905) | --- |
| 2024 | Hacking CTFs with Plain Agents | Rustem Turtayev, Artem Petrov, Dmitrii Volkov, Denis Volk | [Link](https://arxiv.org/pdf/2412.02776) | --- |
| 2024 | Unleashing GHOST: An LLM-Powered Framework for Automated Hardware Trojan Design | Md Omar Faruque, Peter Jamieson, Ahmad Patooghy, Abdel-Hameed A. Badawy | [Link](https://arxiv.org/pdf/2412.02816) | [Github](https://github.com/HSTRG1/GHOST_benchmarks) |
| 2024 | CleanVul: Automatic Function-Level Vulnerability Detection in Code Commits Using LLM Heuristics | Yikun Li, Ting Zhang, Ratnadira Widyasari, Yan Naing Tun, Huu Hung Nguyen, Tan Bui, Ivana Clairine Irsan, Yiran Cheng, Xiang Lan, Han Wei Ang, Frank Liauw, Martin Weyssow, Hong Jin Kang, Eng Lieh Ouh, Lwin Khin Shar, David Lo | [Link](https://arxiv.org/pdf/2411.17274) | [Github](https://github.com/yikun-li/CleanVul) |
| 2024 | HackSynth: LLM Agent and Evaluation Framework for Autonomous Penetration Testing | Lajos Muzsai, David Imolai, András Lukács | [Link](https://arxiv.org/pdf/2412.01778) | [Github](https://github.com/aielte-research/HackSynth) |
| 2024 | Metamorphic Malware Evolution: The Potential and Peril of Large Language Models | Pooria Madani | [Link](https://arxiv.org/pdf/2410.23894) | --- |
| 2024 | Hacking Back the AI-Hacker: Prompt Injection as a Defense Against LLM-driven Cyberattacks | Dario Pasquini, Evgenios M. Kornaropoulos, Giuseppe Ateniese | [Link](https://arxiv.org/pdf/2410.20911) | --- |
| 2024 | Advancing Malicious Website Identification: A Machine Learning Approach Using Granular Feature Analysis | Kinh Tran, Dusan Sovilj | [Link](https://arxiv.org/pdf/2409.07608) | [Github](https://github.com/CyberScienceLab/Malicious_Website_Identification) |
| 2024 | BreachSeek: A Multi-Agent Automated Penetration Tester | Ibrahim Alshehri, Adnan Alshehri, Abdulrahman Almalki, Majed Bamardouf, Alaqsa Akbar | [Link](https://arxiv.org/pdf/2409.03789) | [Github](https://github.com/snow10100/pena/) |
| 2024 | Synthetic Cancer -- Augmenting Worms with LLMs | Benjamin Zimmerman, David Zollikofer | [Link](https://arxiv.org/pdf/2406.19570) | --- |
| 2024 | The Power of Words: Generating PowerShell Attacks from Natural Language | Pietro Liguori, Christian Marescalco, Roberto Natella, Vittorio Orbinato, Luciano Pianese | [Link](https://arxiv.org/pdf/2404.12893) | --- |
| 2024 | Offensive AI: Enhancing Directory Brute-forcing Attack with the Use of Language Models | Alberto Castagnaro, Mauro Conti, Luca Pajola | [Link](https://arxiv.org/pdf/2404.14138) | --- |
| 2024 | LLM Agents can Autonomously Exploit One-day Vulnerabilities | Richard Fang, Rohan Bindu, Akul Gupta, Daniel Kang | [Link](https://arxiv.org/pdf/2404.08144) | --- |
| 2024 | Depending on yourself when you should: Mentoring LLM with RL agents to become the master in cybersecurity games | Yikuan Yan, Yaolun Zhang, Keman Huang | [Link](https://arxiv.org/pdf/2403.17674) | --- |
| 2024 | Using Hallucinations to Bypass GPT4's Filter | Benjamin Lemkin | [Link](https://arxiv.org/pdf/2403.04769) | --- |
| 2024 | A First Look at GPT Apps: Landscape and Vulnerability | Zejun Zhang, Li Zhang, Xin Yuan, Anlan Zhang, Mengwei Xu, Feng Qian | [Link](https://arxiv.org/pdf/2402.15105) | --- |
| 2024 | LLM Agents can Autonomously Hack Websites | Richard Fang, Rohan Bindu, Akul Gupta, Qiusi Zhan, Daniel Kang | [Link](https://arxiv.org/pdf/2402.06664) | --- |
| 2024 | LLMs as Hackers: Autonomous Linux Privilege Escalation Attacks | Andreas Happe, Aaron Kaplan, Jürgen Cito | [Link](https://arxiv.org/pdf/2310.11409) | --- |
| 2023 | CATASTROPHIC JAILBREAK OF OPEN-SOURCE LLMS VIA EXPLOITING GENERATION | Yangsibo Huang, Samyak Gupta, Mengzhou Xia, Kai Li, Danqi Chen | [Link](https://arxiv.org/pdf/2310.06987) | [Github](https://princeton-sysml.github.io/jailbreak-llm/) |
| 2023 | Cyber Sentinel: Exploring Conversational Agents’ Role in Streamlining Security Tasks with GPT-4 | Mehrdad Kaheh,  Danial Khosh Kholgh,  Panos Kostakos | [Link](https://arxiv.org/pdf/2309.16422) | [Github](https://github.com/stanford-esrg/stratosphere) |
| 2023 | Evaluation of Parameter-based Attacks against Embedded Neural Networks with Laser Injection | Mathieu Dumont, Kevin Hector, Pierre-Alain Moellic, Jean-MaxDutertre, Simon Pontie | [Link](https://arxiv.org/pdf/2304.12876) | --- |
| 2023 | How Secure is Code Generated by ChatGPT? | Raphael Khoury, Anderson R. Avila, Jacob Brunelle, Baba Mamadou Camara | [Link](https://arxiv.org/pdf/2304.09655) | --- |
| 2023 | Prompt Stealing Attacks Against Text-to-Image Generation Models | Xinyue Shen, Yiting Qu, Michael Backes, Yang Zhang | [Link](https://arxiv.org/pdf/2302.09923) | [Github](https://github.com/verazuo/prompt-stealing-attack) |
| 2023 | Poisoning Web-Scale Training Datasets is Practical | Nicholas Carlini, Matthew Jagielski, Christopher A. Choquette-Choo, Daniel Paleka, Will Pearce, Hyrum Anderson, Andreas Terzis, Kurt Thomas, Florian Tramer | [Link](https://arxiv.org/pdf/2302.10149) | --- |
| 2023 | Hello Me, Meet the Real Me: Audio Deepfake Attacks on Voice Assistants | Domna Bilika, Nikoletta Michopoulou, Efthimios Alepis, Constantinos Patsakis | [Link](https://arxiv.org/pdf/2302.10328) | --- |
| 2023 | CodeLMSec Benchmark: Systematically Evaluating and Finding Security Vulnerabilities in Black-Box Code Language Models | Hossein Hajipour, Keno Hassler, Thorsten Holz, Lea Schonherr, Mario Fritz | [Link](https://arxiv.org/pdf/2302.04012) | --- |
| 2023 | Dataflow Analysis-Inspired Deep Learning for Efficient Vulnerability Detection | Benjamin Steenhoek, Hongyang Gao, Wei Le | [Link](https://arxiv.org/pdf/2212.08108.pdf) | [PoC](https://figshare.com/articles/dataset/Dataflow_Analysis-Inspired_Deep_Learning_for_Efficient_Vulnerability_Detection/21225413) |
| 2022 | AI for Beyond 5G Networks: A Cyber-Security Defense or Offense Enable | Chafika Benzaıd, Tarik Tale | [Link](https://arxiv.org/ftp/arxiv/papers/2201/2201.02730.pdf) | --- |
| 2021 | A Comparison of State-of-the-Art Techniques for Generating Adversarial Malware Binaries | Prithviraj Dasgupta, Zachariah Osman  | [Link](https://arxiv.org/pdf/2111.11487.pdf) | --- |
| 2021 | Physical Side-Channel Attacks on Embedded Neural Networks: A Survey | Maria Méndez Real, Rubén Salvador | [Link](https://arxiv.org/pdf/2110.11290.pdf) | --- |
| 2021 | A Deep Learning-based Penetration Testing Framework for Vulnerability Identification in Internet of Things Environments | Nickolaos Koroniotis, Nour Moustafa, Benjamin Turnbul, Francesco Schiliro, Praveen Gauravaram, Helge Janicke | [Link](https://arxiv.org/pdf/2109.09259.pdf) | --- |
| 2021 | Leveraging AI to optimize website structure discovery during Penetration Testing | Diego Antonellib, Roberta Cascellab, Gaetano Perronea, Simon Pietro Romanoa, Antonio Schiano | [Link](https://arxiv.org/pdf/2101.07223.pdf) | --- |
| 2021 | The Threat of Offensive AI to Organizations | Yisroel Mirsky, Ambra Demontis, Jaidip Kotak, Ram Shankar, Deng Gelei, Liu Yang, Xiangyu Zhang, Wenke Lee, Yuval Elovici, Battista Biggio | [Link](https://arxiv.org/pdf/2106.15764.pdf) | --- |
| 2021 | Deep Learning-Based Autonomous DrivingSystems: A Survey of Attacks and Defenses | Yao Deng, Tiehua Zhang, Guannan Lou, Xi Zheng, Jiong Jin, Qing-Long Han | [Link](https://arxiv.org/pdf/2104.01789.pdf) | --- |
| 2017 | Generating Adversarial Malware Examples for Black-Box Attacks Based on GAN | Weiwei Hu, Ying Tan | [Link](https://arxiv.org/pdf/1702.05983.pdf) | --- |


## Fuzzing / Exploitation / Vulnerability Discovery in Applications/Hardware
### Papers/Thesis
| Year | Title | Author | Link | Github/PoC  |
| --- | --- | --- | --- | --- |
| 2025 | LLM-Assisted Model-Based Fuzzing of Protocol Implementations | Changze Huang, Di Wang, Zhi Quan Zhou | [Link](https://arxiv.org/pdf/2508.01750) | --- |
| 2025 | Learning to Locate: GNN-Powered Vulnerability Path Discovery in Open Source Code | Nima Atashin, Behrouz Tork Ladani, Mohammadreza Sharbaf | [Link](https://arxiv.org/pdf/2507.17888) | --- |
| 2025 | Scheduzz: Constraint-based Fuzz Driver Generation with Dual Scheduling | Yan Li, Wenzhang Yang, Yuekun Wang, Jian Gao, Shaohua Wang, Yinxing Xue, Lijun Zhang | [Link](https://arxiv.org/pdf/2507.18289) | --- |
| 2025 | LibLMFuzz: LLM-Augmented Fuzz Target Generation for Black-box Libraries | Ian Hardgrove, John D. Hastings | [Link](https://arxiv.org/pdf/2507.15058) | --- |
| 2025 | RVISmith: Fuzzing Compilers for RVV Intrinsics | Yibo He, Cunjian Huang, Xianmiao Qu, Hongdeng Chen, Wei Yang, Tao Xie | [Link](https://arxiv.org/pdf/2507.03773) | [Github](https://github.com/yibo2000/RVISmith) |
| 2025 | FuncVul: An Effective Function Level Vulnerability Detection Model using LLM and Code Chunk | Sajal Halder, Muhammad Ejaz Ahmed, Seyit Camtepe | [Link](https://arxiv.org/pdf/2506.19453) | [Github](https://github.com/sajalhalder/FuncVul) |
| 2025 | deepSURF: Detecting Memory Safety Vulnerabilities in Rust Through Fuzzing LLM-Augmented Harnesses | Georgios Androutsopoulos, Antonio Bianchi | [Link](https://arxiv.org/pdf/2506.15648) | --- |
| 2025 | gh0stEdit: Exploiting Layer-Based Access Vulnerability Within Docker Container Images | Alan Mills, Jonathan White, Phil Legg | [Link](https://arxiv.org/pdf/2506.08218) | --- |
| 2025 | ZTaint-Havoc: From Havoc Mode to Zero-Execution Fuzzing-Driven Taint Inference | Yuchong Xie, Wenhui Zhang, Dongdong She | [Link](https://arxiv.org/pdf/2506.08838) | --- |
| 2025 | Sheep's Clothing, Wolf's Data: Detecting Server-Induced Client Vulnerabilities in Windows Remote IPC | Fangming Gu, Qingli Guo, Jie Lu, Qinghe Xie, Beibei Zhao, Kangjie Lu, Hong Li, Xiaorui Gong | [Link](https://www.ndss-symposium.org/wp-content/uploads/2025-1303-paper.pdf) | [Github](https://github.com/Anonymous130301/GLEIPNIR) |
| 2025 | Moneta: Ex-Vivo GPU Driver Fuzzing by Recalling In-Vivo Execution States | Joonkyo Jung, Jisoo Jang, Yongwan Jo, Jonas Vinck, Alexios Voulimeneas, Stijn Volckaert, Dokyung Song | [Link](https://www.ndss-symposium.org/wp-content/uploads/2025-218-paper.pdf) | --- |
| 2025 | DUMPLING: Fine-grained Differential JavaScript Engine Fuzzing | Liam Wachter, Julian Gremminger, Christian Wressnegger, Mathias Payer, Flavio Toffalini | [Link](https://www.ndss-symposium.org/wp-content/uploads/2025-1411-paper.pdf) | --- |
| 2025 | ROSA: Finding Backdoors with Fuzzing | Dimitri Kokkonis, Michaël Marcozzi, Emilien Decoux, Stefano Zacchiroli  | [Link](https://arxiv.org/pdf/2505.08544) | [Github](https://github.com/binsec/rosa/tree/main) |
| 2025 | An Empirical Study of Fuzz Harness Degradation | Philipp Görz, Joschua Schilling, Thorsten Holz, Marcel Böhme | [Link](https://arxiv.org/pdf/2505.06177) | --- |
| 2025 | Automated Static Vulnerability Detection via a Holistic Neuro-symbolic Approach | Penghui Li, Songchen Yao, Josef Sarfati Korich, Changhua Luo, Jianjia Yu, Yinzhi Cao, Junfeng Yang | [Link](https://arxiv.org/pdf/2504.16057) | --- |
| 2025 | PatchFuzz: Patch Fuzzing for JavaScript Engines | Junjie Wang, Yuhan Ma, Xiaofei Xie, Xiaoning Du, Xiangwei Zhang | [Link](https://arxiv.org/pdf/2505.00289) | [Github](https://github.com/PatchFuzz/patchfuzz) |
| 2025 | SyzParam: Introducing Runtime Parameters into Kernel Driver Fuzzing | Yue Sun, Yan Kang, Chenggang Wu, Kangjie Lu, Jiming Wang, Xingwei Li, Yuhao Hu, Jikai Ren, Yuanming Lai, Mengyao Xie, Zhe Wang | [Link](https://arxiv.org/pdf/2501.10002) | --- |
| 2025 | RAG-Based Fuzzing of Cross-Architecture Compilers | Rana Elnaggar, Brian Delgado, Jason M. Fung | [Link](https://arxiv.org/pdf/2504.08967) | --- |
| 2025 | LeakGuard: Detecting Memory Leaks Accurately and Scalably | Hongliang Liang, Luming Yin, Guohao Wu, Yuxiang Li, Qiuping Yi, Lei Wang | [Link](https://arxiv.org/pdf/2504.04422) | [Gitee](https://gitee.com/yin-luming/leak_guard_tool) |
| 2025 | μRL: Discovering Transient Execution Vulnerabilities Using Reinforcement Learning | M. Caner Tol, Kemal Derya, Berk Sunar | [Link](https://arxiv.org/pdf/2502.14307) | --- |
| 2025 | A Survey of Fuzzing Open-Source Operating Systems | Kun Hu, Qicai Chen, Zilong Lu, Wenzhuo Zhang, Bihuan Chen, You Lu, Haowen Jiang, Bingkun Sun, Xin Peng, Wenyun Zhao | [Link](https://arxiv.org/pdf/2502.13163) | --- |
| 2024 | Pandora's Box in Your SSD: The Untold Dangers of NVMe | Rick Wertenbroek, Alberto Dassatti | [Link](https://arxiv.org/pdf/2411.00439) | --- |
| 2024 | LibAFL-DiFuzz: Advanced Architecture Enabling Directed Fuzzing | Darya Parygina, Timofey Mezhuev, Daniil Kuts | [Link](https://arxiv.org/pdf/2412.19143) | --- |
| 2024 | Fuzzerfly Effect: Hardware Fuzzing for Memory Safety | Mohamadreza Rostami, Chen Chen, Rahul Kande, Huimin Li, Jeyavijayan Rajendran, Ahmad-Reza Sadeghi | [Link](https://arxiv.org/pdf/2410.22561) | --- |
| 2024 | Fuzzing the PHP Interpreter via Dataflow Fusion | Yuancheng Jiang, Chuqi Zhang, Bonan Ruan, Jiahao Liu, Manuel Rigger, Roland Yap, Zhenkai Liang | [Link](https://arxiv.org/pdf/2410.21713) | [Github](https://github.com/php/flowfusion) |
| 2024 | G-Fuzz: A Directed Fuzzing Framework for gVisor | Yuwei Li, Yuan Chen, Shouling Ji, Xuhong Zhang, Guanglu Yan, Alex X.Liu, Chunming Wu, Zulie Pan, Peng Lin | [Link](https://arxiv.org/pdf/2409.13139) | [Github](https://github.com/zjuchenyuan/gfuzz) |
| 2024 | RISCVuzz: Discovering Architectural CPU Vulnerabilities via Differential Hardware Fuzzing | Fabian Thomas, Lorenz Hetterich, Ruiyi Zhang, Daniel Weber, Lukas Gerlach, Michael Schwarz | [Link](https://ghostwriteattack.com/riscvuzz.pdf) | [Link](https://anonymous.4open.science/r/riscvuzz-artifacts-116D) |
| 2024 | No Peer, no Cry: Network Application Fuzzing via Fault Injection | Nils Bars, Moritz Schloegel, Nico Schiller, Lukas Bernhard, Thorsten Holz | [Link](https://arxiv.org/pdf/2409.01059) | [Github](https://github.com/fuzztruction/fuzztruction-net) |
| 2024 | DarthShader: Fuzzing WebGPU Shader Translators & Compilers | Lukas Bernhard, Nico Schiller, Moritz Schloegel, Nils Bars, Thorsten Holz | [Link](https://arxiv.org/pdf/2409.01824) | --- |
| 2024 | Hacked in Translation -- from Subtitles to Complete Takeover | Omri Herscovici, Omer Gull | [Link](https://arxiv.org/pdf/2408.00502) | --- |
| 2024 | eyeballvul: a future-proof benchmark for vulnerability detection in the wild | Timothee Chauvin | [Link](https://arxiv.org/pdf/2407.08708) | [Github](https://github.com/timothee-chauvin/eyeballvul) |
| 2024 | UEFI Vulnerability Signature Generation using Static and Symbolic Analysis | Md Shafiuzzaman, Achintya Desai, Laboni Sarker, Tevfik Bultan | [Link](https://arxiv.org/pdf/2407.07166) | --- |
| 2024 | MegaVul: A C/C++ Vulnerability Dataset with Comprehensive Code Representation | Chao Ni, Liyu Shen, Xiaohu Yang, Yan Zhu, Shaohua Wang | [Link](https://arxiv.org/pdf/2406.12415) | [Github](https://github.com/Icyrockton/MegaVul) |
| 2024 | FOX: Coverage-guided Fuzzing as Online Stochastic Control | Dongdong She, Adam Storek, Yuchong Xie, Seoyoung Kweon, Prashast Srivastava, Suman Jana | [Link](https://arxiv.org/pdf/2406.04517) | [Github](https://github.com/FOX-Fuzz/FOX) |
| 2024 | Super Mario in the Pernicious Kingdoms: Classifying glitches in old games | Llewellyn Forward, Io Limmer, Joseph Hallett, Dan Page | [Link](https://arxiv.org/pdf/2404.14870) | --- |
| 2024 | BinSym: Binary-Level Symbolic Execution using Formal Descriptions of Instruction Semantics | Sören Tempel, Tobias Brandt, Christoph Lüth, Rolf Drechsler | [Link](https://arxiv.org/pdf/2404.04132) | [Github](https://github.com/agra-uni-bremen/binsym) |
| 2024 | Enhancing Code Vulnerability Detection via Vulnerability-Preserving Data Augmentation | Shangqing Liu, Wei Ma, Jian Wang, Xiaofei Xie, Ruitao Feng, Yang Liu | [Link](https://arxiv.org/pdf/2404.09599) | --- |
| 2024 | OSS Malicious Package Analysis in the Wild | Xiaoyan Zhou, Ying Zhang, Wenjia Niu, Jiqiang Liu, Haining Wang, Qiang Li | [Link](https://arxiv.org/pdf/2404.04991) | --- |
| 2024 | Game Rewards Vulnerabilities: Software Vulnerability Detection with Zero-Sum Game and Prototype Learning | Xin-Cheng Wen, Cuiyun Gao, Xinchen Wang, Ruiqi Wang, Tao Zhang, Qing Liao | [Link](https://arxiv.org/pdf/2401.08131) | --- |
| 2024 | UBfuzz: Finding Bugs in Sanitizer Implementations | Shaohua Li, Zhendong Su | [Link](https://arxiv.org/pdf/2401.04538) | [Atrifact](https://zenodo.org/records/8406414) |
| 2024 | VulMatch: Binary-level Vulnerability Detection Through Signature | Zian Liu, Lei Pan, Chao Chen, Ejaz Ahmed, Shigang Liu, Jun Zhang, Dongxi Liu | [Link](https://arxiv.org/pdf/2308.00288) | [Github](https://github.com/Vulmatch/Vulmatch.git) |
| 2023 | Hyperfuzzing: black-box security hypertesting with a grey-box fuzzer | Daniel Blackwell, Ingolf Becker, David Clark | [Link](https://arxiv.org/pdf/2308.09081) | [PoC](https://figshare.com/s/fa143b65420ab7ab1e3c) |
| 2023 | Fuzzing the Latest NTFS in Linux with Papora: An Empirical Study | Edward Lo, Ningyu He, Yuejie Shi, Jiajia Xu, Chiachih Wu, Ding Li, Yao Guo | [Link](https://arxiv.org/pdf/2304.07166) | --- |
| 2023 | ODDFUZZ: Discovering Java Deserialization Vulnerabilities via Structure-Aware Directed Greybox Fuzzing | Sicong Cao, Biao He, Xiaobing Sun, Yu Ouyang, Chao Zhang, Xiaoxue Wu, Ting Su,Lili Bo, Bin Li, Chuanlei Ma, Jiajia Li, Tao Wei | [Link](https://arxiv.org/pdf/2304.04233) | [Github](https://github.com/ODDFuzz/ODDFuzz) |
| 2023 | autofz: Automated Fuzzer Composition at Runtime | Yu-Fu Fu, Jaehyuk Lee, Taesoo Kim | [Link](https://arxiv.org/pdf/2302.12879) | [Github](https://github.com/sslab-gatech/autofz) |
| 2023 | Detecting Exploit Primitives Automatically for Heap Vulnerabilities on Binary Programs | Jie Liu, Hang An, Jin Li, Hongliang Liang | [Link](https://arxiv.org/pdf/2212.13990) | --- |
| 2022 | AMPFUZZ: Fuzzing for Amplification DDoS Vulnerabilities | Johannes Krupp, Ilya Grishchenko, Christian Rossow | [Link](https://publications.cispa.saarland/3643/2/AmpFuzz.pdf) | [Github](https://github.com/cispa/ampfuzz) |
| 2022 | COOPER: Testing the Binding Code of Scripting Languages with Cooperative Mutation | Peng Xu, Yanhao Wang, Hong Hu, Purui Su | [Link](https://huhong789.github.io/papers/xu:cooper.pdf) | [Github](https://github.com/TCA-ISCAS/Cooper) |
| 2022 | FuzzingDriver: the Missing Dictionary to Increase Code Coverage in Fuzzers | Arash Ale Ebrahim, Mohammadreza Hazhirpasand, Oscar Nierstrasz, Mohammad Ghafari | [Link](https://arxiv.org/ftp/arxiv/papers/2201/2201.04853.pdf) | [Github](https://github.com/cryptomadco/fuzzingdriver) |
| 2022 | Path Transitions Tell More: Optimizing Fuzzing Schedules via Runtime Program States | Kunpeng Zhang, Xi Xiao, Xiaogang Zhu, Ruoxi Sun, Minhui Xue, Sheng Wen | [Link](https://arxiv.org/pdf/2201.04441.pdf) | [Github](https://github.com/truzz-fuzz/truzz-fuzz) |
| 2021 | Attacks on Wireless Coexistence: Exploiting Cross-Technology Performance Features for Inter-Chip Privilege Escalation | Jiska Classen, Francesco Gringoli, Michael Hermann, Matthias Hollick | [Link](https://arxiv.org/pdf/2112.05719.pdf) | --- |
| 2021 | Fuzzm: Finding Memory Bugs through Binary-Only Instrumentation and Fuzzing of WebAssembly | Daniel Lehmann, Martin Toldam Torp, Michael Pradel | [Link](https://arxiv.org/pdf/2110.15433.pdf) | --- |
| 2021 | VIA: Analyzing Device Interfaces of Protected Virtual Machines | Felicitas Hetzelt, Martin Radev, Robert Buhren, Mathias Morbitzer, Jean-Pierre Seifert | [Link](https://arxiv.org/pdf/2109.10660.pdf) | --- |
| 2021 | Spotting Silent Buffer Overflows in Execution Trace throughGraph Neural Network Assisted Data Flow Analysis | Zhilong Wang, Li Yu, Suhang Wang and Peng Liu | [Link](https://arxiv.org/pdf/2102.10452.pdf) | --- |
| 2021 | QFuzz: Quantitative Fuzzing for Side Channels | Yannic Noller, Saeid Tizpaz-Niari | [Link](https://arxiv.org/pdf/2106.03346.pdf) | [Github](https://github.com/yannicnoller/qfuzz) |
| 2021 | Revizor: Fuzzing for Leaks in Black-box CPUs | Oleksii Oleksenko, Christof Fetzer, Boris Köpf, Mark Silberstein | [Link](https://arxiv.org/pdf/2105.06872.pdf) | [Github](https://github.com/hw-sw-contracts/revizor) |
| 2021 | Snipuzz: Black-box Fuzzing of IoT Firmware via Message Snippet Inference | Xiaotao Feng, Ruoxi Sun, Xiaogang Zhu, Minhui Xue, Sheng Wen, Dongxi Liu, Surya Nepal, Yang Xiang | [Link](https://arxiv.org/pdf/2105.05445.pdf) | --- |
| 2020 | The never ending war in the stack and the reincarnation of ROP attacks | Ammari Nader, Joan Calvet, Jose M. Fernandez | [Link](https://arxiv.org/pdf/2005.11886.pdf) | --- |
| 2020 | FuzzGen: Automatic Fuzzer Generation | Kyriakos K. Ispoglou, Daniel Austin, Vishwath Mohan, Mathias Payer | [Link](https://hexhive.epfl.ch/publications/files/20SEC.pdf) | [Github](https://github.com/HexHive/FuzzGen) |
| 2020 | USBFuzz: A Framework for Fuzzing USB Drivers by Device Emulation | Hui Peng, Mathias Payer | [Link](https://hexhive.epfl.ch/publications/files/20SEC3.pdf) | [Github](https://github.com/HexHive/USBFuzz) |
| 2019 | FirmFuzz: Automated IoT Firmware Introspection and Analysis | Prashast Srivastava, Hui Peng, Jiahao Li, Hamed Okhravi, Howard Shrobe, Mathias Payer | [Link](https://hexhive.epfl.ch/publications/files/19IOTSP.pdf) | [Github](https://github.com/HexHive/FirmFuzz) |
| 2016 | Toward large-scale vulnerability discovery using Machine Learning | Gustavo Grieco, Guillermo Luis Grinblat, Lucas Uzal, Sanjay Rawat, Josselin Feist, Laurent Mounier  | [Link](http://www.covert.io/research-papers/deep-learning-security/Toward%20large-scale%20vulnerability%20discovery%20using%20Machine%20Learning.pdf) | --- |
| 2015 | Pattern-Based Vulnerability Discovery | Fabian Yamaguchi | [Link](https://ediss.uni-goettingen.de/bitstream/handle/11858/00-1735-0000-0023-9682-0/mainFastWeb.pdf) | --- |


### Blogposts
| Year | Title | Author | Link |
| --- | --- | --- | --- |
| 2021 | Speculating the entire x86-64 Instruction Set In Seconds with This One Weird Trick | Can Bölük | [Link](https://blog.can.ac/2021/03/22/speculating-x86-64-isa-with-one-weird-trick/) |
| 2020 | Bugs on the Windshield: Fuzzing the Windows Kernel | Netanel Ben Simon | [Link](https://research.checkpoint.com/2020/bugs-on-the-windshield-fuzzing-the-windows-kernel/amp/) |
| 2018 | Deep Exploit - Github Project | Isao Takaesu | [Github](https://github.com/13o-bbr-bbq/machine_learning_security/blob/master/DeepExploit/README.md) |

## Mobile/Radio 
### Papers/Thesis
| Year | Title | Author | Link | Github/PoC  |
| --- | --- | --- | --- | --- |
| 2025 | KeyDroid: A Large-Scale Analysis of Secure Key Storage in Android Apps | Jenny Blessing, Ross J. Anderson, Alastair R. Beresford | [Link](https://arxiv.org/pdf/2507.07927) | --- |
| 2025 | Hijacking JARVIS: Benchmarking Mobile GUI Agents against Unprivileged Third Parties | Guohong Liu, Jialei Ye, Jiacheng Liu, Yuanchun Li, Wei Liu, Pengzhi Gao, Jian Luan, Yunxin Liu | [Link](https://arxiv.org/pdf/2507.04227) | --- |
| 2025 | Stealtooth: Breaking Bluetooth Security Abusing Silent Automatic Pairing | Keiichiro Kimura, Hiroki Kuzuno, Yoshiaki Shiraishi, Masakatu Morii | [Link](https://arxiv.org/pdf/2507.00847) | --- |
| 2025 | Generative AI for Vulnerability Detection in 6G Wireless Networks: Advances, Case Study, and Future Directions | Shuo Yang, Xinran Zheng, Jinfeng Xu, Jinze Li, Danyang Song, Zheyu Chen, Edith C.H. Ngai | [Link](https://arxiv.org/pdf/2506.20488) | --- |
| 2024 | LoRaWAN attack in military use case | Georges Derache, Mounira Msahli, Aurelien Botbol, Fabien Romain, Jerome Champlon, Gauthier Canet | [Link](https://arxiv.org/pdf/2412.18447) | --- |
| 2024 | CovFUZZ: Coverage-based fuzzer for 4G&5G protocols | Ilja Siroš, Dave Singelée, Bart Preneel | [Link](https://arxiv.org/pdf/2410.20958) | --- |
| 2024 | Jäger: Automated Telephone Call Traceback | David Adei, Varun Madathil, Sathvik Prasad, Bradley Reaves, Alessandra Scafuro | [Link](https://arxiv.org/pdf/2409.02839) | --- |
| 2024 | Eavesdropping Mobile Apps and Actions through Wireless Traffic in the Open World | Xiaoguang Yang, Yong Huang, Junli Guo, Dalong Zhang, Qingxian Wang | [Link](https://arxiv.org/pdf/2408.07263) | --- |
| 2024 | AndroCon: Conning Location Services in Android | Soham Nag, Smruti R. Sarangi | [Link](https://arxiv.org/pdf/2407.19392) | --- |
| 2024 | Never Gonna Give You Up: Exploring Deprecated NULL Ciphers in Commercial VoWiFi Deployments | Gabriel Karl Gegenhuber, Philipp Frenzel, Edgar Weippl | [Link](https://arxiv.org/pdf/2406.12348) | --- |
| 2023 | FINDING VULNERABILITIES IN MOBILE APPLICATION APIS: A MODULAR PROGRAMMATIC APPROACH | Nate Haris, Kendree Chen, Ann Song, Benjamin Pou | [Link](https://arxiv.org/pdf/2310.14137) | --- |
| 2023 | Freaky Leaky SMS: Extracting User Locations by Analyzing SMS Timings | Evangelos Bitsikas, Theodor Schnitzler, Christina Pöpper, Aanjhan Ranganathan | [Link](https://arxiv.org/pdf/2306.07695) | --- |
| 2023 | Side-Channel VoIP Profiling Attack against Customer Service Automated Phone System | Roy Laurens, Edo Christianto, Bruce Caulkins, Cliff C. Zou | [Link](https://arxiv.org/ftp/arxiv/papers/2306/2306.00095.pdf) | --- |
| 2023 | Watching your call: Breaking VoLTE Privacy in LTE/5G Networks | Zishuai Cheng, Mihai Ordean, Flavio D. Garcia, Baojiang Cui, Dominik Rys | [Link](https://arxiv.org/pdf/2301.02487) | --- |
| 2021 | An Empirical Analysis of HTTPS Configuration Security | Camelia Simoiu, Wilson Nguyen, Zakir Durumeric | [Link](https://arxiv.org/pdf/2111.00703.pdf) | --- |
| 2021 | Security Header Fields in HTTP Clients | Pascal Gadient, Oscar Nierstrasz, Mohammad Ghafari  | [Link](https://arxiv.org/ftp/arxiv/papers/2111/2111.03601.pdf) | --- |
| 2021 | LTrack: Stealthy Tracking of Mobile Phones in LTE | Martin Kotuliak, Simon Erni, Patrick Leu, Marc Röschlin, Srdjan Capkun | [Link](https://arxiv.org/pdf/2106.05007.pdf) | --- |

### Blogposts
| Year | Title | Author | Link |
| --- | --- | --- | --- |
| 2021 | SeaGlass Enabling City-Wide IMSI-Catcher Detection | Peter Ney, Ian Smith, Tadayoshi Kohno, Gabriel Cadamuro | [Link](https://seaglass.cs.washington.edu/) |
| 2020 | BleedingTooth: Linux Bluetooth Zero-Click Remote Code Execution | Andy Nguyen | [Link](https://google.github.io/security-research/pocs/linux/bleedingtooth/writeup.html) |
| 2019 | New Type Of GPS Spoofing Attack In China Creates "Crop Circles" Of False Location Data | Joseph Trevithick | [Link](https://www.thedrive.com/the-war-zone/31092/new-type-of-gps-spoofing-attack-in-china-creates-crop-circles-of-false-location-data) | 
| 2019 | Wireless attacks on aircraft instrument landing systems | Adrian Colyer | [Link](https://blog.acolyer.org/2019/09/27/wireless-attacks-on-aircraft-instrument-landing-systems/) |

## IoT
### Papers/Thesis
| Year | Title | Author | Link | Github/PoC  |
| --- | --- | --- | --- | --- |
| 2025 | SIMulator: SIM Tracing on a (Pico-)Budget | Gabriel K. Gegenhuber, Philipp É. Frenzel, Adrian Dabrowski | [Link](https://arxiv.org/pdf/2506.20800) | [Github](https://github.com/sbaresearch/mobile-atlas#simulator) |
| 2025 | CveBinarySheet: A Comprehensive Pre-built Binaries Database for IoT Vulnerability Analysis | Lingfeng Chen | [Link](https://arxiv.org/pdf/2501.08840) | --- |
| 2024 | Finding (and exploiting) vulnerabilities on IP Cameras: the Tenda CP3 case study | Dario Stabili, Tobia Bocchi, Filip Valgimigli, Mirco Marchetti | [Link](https://arxiv.org/pdf/2406.15103) | [Github](https://github.com/SECloudUNIMORE/ACES/tree/master/Tenda) |
| 2024 | AutoFirm: Automatically Identifying Reused Libraries inside IoT Firmware at Large-Scale | YongLe Chen, Feng Ma, Ying Zhang, YongZhong He, Haining Wang, Qiang Li | [Link](https://arxiv.org/pdf/2406.12947) | [Github](https://github.com/sure17/AutoFirm) |
| 2024 | LuaTaint: A Static Taint Analysis System for Web Interface Framework Vulnerability of IoT Devices | Jiahui Xiang, Wenhai Wang, Tong Ye, Peiyu Liu | [Link](https://arxiv.org/pdf/2402.16043) | --- |
| 2023 | AdvRain: Adversarial Raindrops to Attack Camera-Based Smart Vision Systems | Amira Guesmi , Muhammad Abdullah Hanif, Muhammad Shafique | [Link](https://arxiv.org/pdf/2303.01338) | --- |
| 2023 | Ember-IO: Effective Firmware Fuzzing with Model-Free Memory Mapped IO | Guy Farrelly, Michael Chesser, Damith C. Ranasinghe | [Link](https://arxiv.org/pdf/2301.06689) | [Github](https://github.com/Ember-IO/Ember-IO-Fuzzing) |
| 2021 | My(o) Armband Leaks Passwords: An EMG and IMU Based Keylogging Side-Channel Attack | Matthias Gazzari, Annemarie Mattmann, Max Maass, Matthias Hollick | [Link](https://arxiv.org/pdf/2112.02382.pdf) | [Github](https://github.com/seemoo-lab/myo-keylogging) |
| 2021 | VoIP Can Still Be Exploited — Badly | Pietro Biondi, Stefano Bognanni, Giampaolo Bella | [Link](https://arxiv.org/pdf/2111.15468.pdf) | --- |
| 2021 | A Measurement Study on the (In)security of End-of-Life (EoL) Embedded Devices | Dingding Wang, Muhui Jiang, Rui Chang, Yajin Zhou, Baolei Hou, Xiapu Luo, Lei Wu, Kui Ren | [LINK](https://arxiv.org/pdf/2105.14298.pdf) | --- |
| 2020 | HALucinator: Firmware Re-hosting Through Abstraction Layer Emulation| Abraham A. Clements, Eric Gustafson, Tobias Scharnowski, Paul Grosen, David Fritz, Christopher Kruegel, Giovanni Vigna, Saurabh Bagchi, Mathias Payer | [Link](http://hexhive.epfl.ch/publications/files/20SEC2.pdf) | [Github](https://github.com/embedded-sec/halucinator) |
| 2016 | Towards Automated Dynamic Analysis for Linux-based Embedded Firmware | Daming D. Chen, Manuel Egele, Maverick Woo, David Brumley | [Link](https://raw.githubusercontent.com/firmadyne/firmadyne/master/paper/paper.pdf) | [Github](https://github.com/firmadyne/firmadyne) |

### Blogposts
| Year | Title | Author | Link |
| --- | --- | --- | --- |
| 2020 | Using Z3 Theorem on AVR Firmware | Ryan Cornateanu | [Link](https://ryancor.medium.com/using-z3-theorem-on-avr-firmware-c6d2f45ac9c2) |

## Crypto/DeFi 
### Papers/Thesis
| Year | Title | Author | Link | Github/PoC  |
| --- | --- | --- | --- | --- |
| 2025 | The Dark Side of Upgrades: Uncovering Security Risks in Smart Contract Upgrades | Dingding Wang, Jianting He, Siwei Wu, Yajin Zhou, Lei Wu, Cong Wang | [Link](https://arxiv.org/pdf/2508.02145) | --- |
| 2025 | Stablecoins: Fundamentals, Emerging Issues, and Open Challenges | Ahmed Mahrous, Maurantonio Caprolu, Roberto Di Pietro | [Link](https://arxiv.org/pdf/2507.13883) | --- |
| 2025 | Bittensor Protocol: The Bitcoin in Decentralized Artificial Intelligence? A Critical and Empirical Analysis | Elizabeth Lui, Jiahao Sun | [Link](https://arxiv.org/pdf/2507.02951) | --- |
| 2025 | PhishingHook: Catching Phishing Ethereum Smart Contracts leveraging EVM Opcodes | Pasquale De Rosa, Simon Queyrut, Yérom-David Bromberg, Pascal Felber, Valerio Schiavoni | [Link](https://arxiv.org/pdf/2506.19480) | --- |
| 2025 | ETrace:Event-Driven Vulnerability Detection in Smart Contracts via LLM-Based Trace Analysis | Chenyang Peng, Haijun Wang, Yin Wu, Hao Wu, Ming Fan, Yitao Zhao, Ting Liu | [Link](https://arxiv.org/pdf/2506.15790) | --- |
| 2025 | A theory of Lending Protocols in DeFi | Massimo Bartoletti, Enrico Lipparini | [Link](https://arxiv.org/pdf/2506.15295) | --- |
| 2025 | Exposing Hidden Backdoors in NFT Smart Contracts: A Static Security Analysis of Rug Pull Patterns | Chetan Pathade, Shweta Hooli | [Link](https://arxiv.org/pdf/2506.07974) | --- |
| 2025 | When Blockchain Meets Crawlers: Real-time Market Analytics in Solana NFT Markets | Chengxin Shen, Zhongwen Li, Xiaoqi Li, Zongwei Li | [Link](https://arxiv.org/pdf/2506.02892) | --- |
| 2025 | Timestamp Manipulation: Timestamp-based Nakamoto-style Blockchains are Vulnerable | Junjie Hu, Na Ruan, Sisi Duan | [Link](https://arxiv.org/pdf/2505.05328) | --- |
| 2025 | AI-Based Vulnerability Analysis of NFT Smart Contracts | Xin Wang, Xiaoqi Li | [Link](https://arxiv.org/pdf/2504.16113) | --- |
| 2025 | Blockchain Oracles for Real Estate Rental | Nuno Braz, João Santos, Tiago Dias, Miguel Correia | [Link](https://arxiv.org/pdf/2504.06180) | --- |
| 2025 | Security Vulnerabilities in Ethereum Smart Contracts: A Systematic Analysis | Jixuan Wu, Lei Xie, Xiaoqi Li | [Link](https://arxiv.org/pdf/2504.05968) | --- |
| 2025 | SoK: A Review of Cross-Chain Bridge Hacks in 2023 | Nikita Belenkov, Valerian Callens, Alexandr Murashkin, Kacper Bak, Martin Derka, Jan Gorzny, Sung-Shine Lee | [Link](https://arxiv.org/pdf/2501.03423) | --- |
| 2024 | COBRA: Interaction-Aware Bytecode-Level Vulnerability Detector for Smart Contracts | Wenkai Li, Xiaoqi Li, Zongwei Li, Yuqing Zhang | [Link](https://arxiv.org/pdf/2410.20712) | --- |
| 2024 | Proxion: Uncovering Hidden Proxy Smart Contracts for Finding Collision Vulnerabilities in Ethereum | Cheng-Kang Chen, Wen-Yi Chu, Muoi Tran, Laurent Vanbever, Hsu-Chun Hsiao | [Link](https://arxiv.org/pdf/2409.13563) | [Github](https://github.com/Proxion-anonymous/Proxion) |
| 2024 | Deanonymizing Ethereum Validators: The P2P Network Has a Privacy Issue | Lioba Heimbach, Yann Vonlanthen, Juan Villacis, Lucianna Kiffer, Roger Wattenhofer | [Link](https://arxiv.org/pdf/2409.04366) | --- |
| 2024 | DogeFuzz: A Simple Yet Efficient Grey-box Fuzzer for Ethereum Smart Contracts | Ismael Medeiros, Fausto Carvalho, Alexandre Ferreira, Rodrigo Bonifácio, Fabiano Cavalcanti Fernandes | [Link](https://arxiv.org/pdf/2409.01788) | [Github](https://github.com/PAMunb/dogefuzz) |
| 2024 | ML2SC: Deploying Machine Learning Models as Smart Contracts on the Blockchain | Zhikai Li, Steve Vott, Bhaskar Krishnamachar | [Link](https://arxiv.org/pdf/2404.16967) | --- |
| 2024 | Larger-scale Nakamoto-style Blockchains Don't Necessarily Offer Better Security | Jannik Albrecht, Sebastien Andreina, Frederik Armknecht, Ghassan Karame, Giorgia Marson, Julian Willingmann | [Link](https://arxiv.org/pdf/2404.09895) | --- |
| 2024 | 51% Attack via Difficulty Increase with a Small Quantum Miner | Bolton Bailey, Or Sattath | [Link](https://arxiv.org/pdf/2403.08023) | --- |
| 2023 | Abusing the Ethereum Smart Contract Verification Services for Fun and Profit | Pengxiang Ma, Ningyu He, Yuhua Huang, Haoyu Wang | [Link](https://arxiv.org/pdf/2307.00549) | --- |
| 2023 | The offline digital currency puzzle solved by a local blockchain | Henrique de Carvaloh Videira | [Link](https://arxiv.org/ftp/arxiv/papers/2305/2305.02290.pdf) | --- |
| 2023 | Explainable Ponzi Schemes Detection on Ethereum | Letterio Galletta, Fabio Pinelli | [Link](https://arxiv.org/pdf/2301.04872) | [Github](https://github.com/fpinell/ponzi_ml/blob/main/notebooks/paper_experiments.ipynb) |
| 2022 | Security Analysis of DeFi: Vulnerabilities, Attacks and Advances | Wenkai Li, Jiuyang Bu, Xiaoqi Li, Xianyi Chen | [Link](https://arxiv.org/pdf/2205.09524.pdf) | --- |
| 2022 | Secure Decentralized Online Gaming with Lending Functionalities | Katharina Alefs, Florian Hartl, Luke Newman, Banu  ̈Ozdeveci, Wisnu Uriawan | [Link](https://arxiv.org/pdf/2205.02348.pdf) | [Github](https://github.com/Newman251/CasinoSmartContract) |
| 2022| Blockchain in a nutshell | Duc A. Tran, Bhaskar Krishnamachari | [Link](https://arxiv.org/pdf/2205.01091.pdf) | --- |
| 2022| A Secure File Sharing System Based on IPFS and Blockchain | Hsiao-Shan Huang, Tian-Sheuan Chang, Jhih-Yi Wu | [Link](https://arxiv.org/ftp/arxiv/papers/2205/2205.01728.pdf) | --- |
| 2022 | Gas Gauge: A Security Analysis Tool for Smart Contract Out-of-Gas Vulnerabilities | Behkish Nassirzadeh , Vijay Ganesh, Huaiying Sun, Sebastian Banescu | [Link](https://arxiv.org/pdf/2112.14771.pdf) | [Github](https://github.com/gasgauge/gasgauge.github.io) |
| 2021 | (Meme) Proof of Steak | Jon Crowcroft, Hamed Haddadi, Arthur Gervais, Tristan Henderson | [Link](https://arxiv.org/pdf/2112.06498.pdf) | --- |
| 2021 | Machine Learning Guided Cross-Contract Fuzzing | Yinxing Xue, Jiaming Ye, Wei Zhang, Jun Sun, Lei Ma, Haijun Wang, Jianjun Zhao | [Link](https://arxiv.org/ftp/arxiv/papers/2111/2111.12423.pdf) | --- |
| 2021 | JACK THE RIPPLER: Arbitrage on the Decentralized Exchange of the XRP Ledger | Gaspard Peduzzi, Jason James, Jiahua Xu  | [Link](https://arxiv.org/pdf/2106.16158.pdf) | --- |
| 2021 | Understanding Security Issues in the NFT Ecosystem | Dipanjan Das, Priyanka Bose, Nicola Ruaro, Christopher Kruegel, Giovanni Vigna | [Link](https://arxiv.org/pdf/2111.08893.pdf) | --- |
| 2021 | Franchised Quantum Money | Bhaskar Roberts, Mark Zhandry | [Link](https://arxiv.org/pdf/2110.09733.pdf) | --- |
| 2021 | An Empirical Study of Protocols in Smart Contracts | Timothy Mou, Michael Coblenz, Jonathan Aldrich | [Link](https://arxiv.org/pdf/2110.08983.pdf) | --- |
| 2021 | Attacking the DeFi Ecosystem with Flash Loans for Fun and Profit | Kaihua Qin, Liyi Zhou, Benjamin Livshits, Arthur Gervais | [Link](https://arxiv.org/pdf/2003.03810.pdf) | --- |

## BlueTeam 
### Papers/Thesis
| Year | Title | Author | Link | Github/PoC  |
| --- | --- | --- | --- | --- |
| 2025 | PhishParrot: LLM-Driven Adaptive Crawling to Unveil Cloaked Phishing Sites | Hiroki Nakano, Takashi Koide, Daiki Chiba | [Link](https://arxiv.org/pdf/2508.02035) | --- |
| 2025 | Protecting Small Organizations from AI Bots with Logrip: Hierarchical IP Hashing | Rama Carl Hoetzlein | [Link](https://arxiv.org/pdf/2508.03130) | --- |
| 2025 | PhishIntentionLLM: Uncovering Phishing Website Intentions through Multi-Agent Retrieval-Augmented Generation | Wenhao Li, Selvakumar Manickam, Yung-wey Chong, Shankar Karuppayah | [Link](https://arxiv.org/pdf/2507.15419) | --- |
| 2025 | Phishing Detection in the Gen-AI Era: Quantized LLMs vs Classical Models | Jikesh Thapa, Gurrehmat Chahal, Serban Voinea Gabreanu, Yazan Otoum | [Link](https://arxiv.org/pdf/2507.07406) | --- |
| 2025 | CyberRAG: An agentic RAG cyber attack classification and reporting tool | Francesco Blefari, Cristian Cosentino, Francesco Aurelio Pironti, Angelo Furfaro, Fabrizio Marozzo | [Link](https://arxiv.org/pdf/2507.02424) | --- |
| 2025 | WebGuard++:Interpretable Malicious URL Detection via Bidirectional Fusion of HTML Subgraphs and Multi-Scale Convolutional BERT | Ye Tian, Zhang Yumin, Yifan Jia, Jianguo Sun, Yanbin Wang | [Link](https://arxiv.org/pdf/2506.19356) | --- |
| 2025 | Analyzing PDFs like Binaries: Adversarially Robust PDF Malware Analysis via Intermediate Representation and Language Model | Side Liu, Jiang Ming, Guodong Zhou, Xinyi Liu, Jianming Fu, Guojun Peng | [Link](https://arxiv.org/pdf/2506.17162) | [Zenodo](https://zenodo.org/records/15532394) |
| 2025 | PhishDebate: An LLM-Based Multi-Agent Framework for Phishing Website Detection | Wenhao Li, Selvakumar Manickam, Yung-wey Chong, Shankar Karuppayah | [Link](https://arxiv.org/pdf/2506.15656) | --- |
| 2025 | Evaluating Large Language Models for Phishing Detection, Self-Consistency, Faithfulness, and Explainability | Shova Kuikel, Aritran Piplai, Palvi Aggarwal | [Link](https://arxiv.org/pdf/2506.13746) | --- |
| 2025 | KEENHash: Hashing Programs into Function-Aware Embeddings for Large-Scale Binary Code Similarity Analysis | Zhijie Liu, Qiyi Tang, Sen Nie, Shi Wu, Liang Feng Zhang, Yutian Tang | [Link](https://arxiv.org/pdf/2506.11612) | [Online SDK](https://www.binaryai.cn/) |
| 2025 | IRCopilot: Automated Incident Response with Large Language Models | Xihuan Lin, Jie Zhang, Gelei Deng, Tianzhe Liu, Xiaolong Liu, Changcai Yang, Tianwei Zhang, Qing Guo, Riqing Chen | [Link](https://arxiv.org/pdf/2505.20945) | --- |
| 2025 | Digital Forensic Investigation of the ChatGPT Windows Application | Malithi Wanniarachchi Kankanamge, Nick McKenna, Santiago Carmona, Syed Mhamudul Hasan, Abdur R.Shahid, Ahmed Imteaj | [Link](https://arxiv.org/pdf/2505.23938) | --- |
| 2025 | Benchmarking LLMs in an Embodied Environment for Blue Team Threat Hunting | Xiaoqun Liu, Feiyang Yu, Xi Li, Guanhua Yan, Ping Yang, Zhaohan Xi | [Link](https://arxiv.org/pdf/2505.11901) | --- |
| 2025 | From Cyber Security Incident Management to Cyber Security Crisis Management in the European Union | Jukka Ruohonen, Kalle Rindell, Simone Busetti | [Link](https://arxiv.org/pdf/2504.14220) | --- |
| 2025 | Bandit on the Hunt: Dynamic Crawling for Cyber Threat Intelligence | Philipp Kuehn, Dilara Nadermahmoodi, Markus Bayer, Christian Reuter | [Link](https://arxiv.org/pdf/2504.18375) | --- |
| 2025 | Detecting Quishing Attacks with Machine Learning Techniques Through QR Code Analysis | Fouad Trad, Ali Chehab | [Link](https://arxiv.org/pdf/2505.03451) | [Github](https://github.com/fouadtrad/Detecting-Quishing-Attacks-with-Machine-Learning-Techniques-Through-QR-Code-Analysis) |
| 2025 | Arcanum: Detecting and Evaluating the Privacy Risks of Browser Extensions on Web Pages and Web Content | Qinge Xie, Manoj Vignesh Kasi Murali, Paul Pearce, and Frank Li | [Link](https://www.usenix.org/system/files/usenixsecurity24-xie-qinge.pdf) | [Github](https://github.com/BEESLab/Arcanum/) |
| 2025 | A Study on Malicious Browser Extensions in 2025 | Shreya Singh, Gaurav Varshney, Tarun Kumar Singh, Vidhi Mishra | [Link](https://arxiv.org/pdf/2503.04292) | --- |
| 2025 | MITRE ATT&CK Applications in Cybersecurity and The Way Forward | Yuning Jiang, Qiaoran Meng, Feiyang Shang, Nay Oo, Le Thi Hong Minh, Hoon Wei Lim, Biplab Sikdar | [Link](https://arxiv.org/pdf/2502.10825) | --- |
| 2024 | Living off the Analyst: Harvesting Features from Yara Rules for Malware Detection | Siddhant Gupta, Fred Lu, Andrew Barlow, Edward Raff, Francis Ferraro, Cynthia Matuszek, Charles Nicholas, James Holt | [Link](https://arxiv.org/pdf/2411.18516) | --- |
| 2024 | "Oh, sh*t! I actually opened the document!": An Empirical Study of the Experiences with Suspicious Emails in Virtual Reality Headsets | Filipo Sharevski, Jennifer Vander Loop, Sarah Ferguson | [Link](https://arxiv.org/pdf/2412.01474) | --- |
| 2024 | RACONTEUR: A Knowledgeable, Insightful, and Portable LLM-Powered Shell Command Explainer | Jiangyi Deng, Xinfeng Li, Yanjiao Chen, Yijie Bai, Haiqin Weng, Yan Liu, Tao Wei, Wenyuan Xu  |[Link](https://arxiv.org/pdf/2409.02074) | [Github](https://raconteur-ndss.github.io/#) |
| 2024 | Red Team Redemption: A Structured Comparison of Open-Source Tools for Adversary Emulation | Max Landauer, Klaus Mayer, Florian Skopik, Markus Wurzenberger, Manuel Kern | [Link](https://arxiv.org/pdf/2408.15645) | --- |
| 2024 | Forecasting Attacker Actions using Alert-driven Attack Graphs | Ion Băbălău, Azqa Nadeem | [Link](https://arxiv.org/pdf/2408.09888) | --- |
| 2024 | HoneyGAN Pots: A Deep Learning Approach for Generating Honeypots | Ryan Gabrys, Daniel Silva, Mark Bilinski | [Link](https://arxiv.org/pdf/2407.07292) | --- |
| 2024 | EarlyMalDetect: A Novel Approach for Early Windows Malware Detection Based on Sequences of API Calls | Pascal Maniriho, Abdun Naser Mahmood, Mohammad Jabed Morshed Chowdhury | [Link](https://arxiv.org/pdf/2407.13355) | --- |
| 2024 | HookChain: A new perspective for Bypassing EDR Solutions | Helvio Carvalho Junior | [Link](https://arxiv.org/pdf/2404.16856) | --- |
| 2024 | Leveraging Adversarial Detection to Enable Scalable and Low Overhead RowHammer Mitigations | Oğuzhan Canpolat, A. Giray Yağlıkçı, Ataberk Olgun, İsmail Emir Yüksel, Yahya Can Tuğrul, Konstantinos Kanellopoulos, Oğuz Ergin, Onur Mutlu | [Link](https://arxiv.org/pdf/2404.13477) | --- |
| 2023 | Nebula: Self-Attention for Dynamic Malware Analysis | Dmitrijs Trizna, Luca Demetrio, Battista Biggio, Fabio Roli | [Link](https://arxiv.org/pdf/2310.10664) | --- |
| 2023 | Application-layer Characterization and Traffic Analysis for Encrypted QUIC Transport Protocol | Qianqian Zhang ,Chi-Jiun Su | [Link](https://arxiv.org/pdf/2310.10676) | --- |
| 2023 | Detection of Malicious DNS-over-HTTPS Traffic: An Anomaly Detection Approach using Autoencoders | Sergio A. Salinas Monroy, Aman Kumar Gupta, Garrett Wahlstedt | --- | --- |

## Misc/Other 
### Papers/Thesis
| Year | Title | Author | Link | Github/PoC  |
| --- | --- | --- | --- | --- |
| 2025 | On the Impossibility of a Perfect Hypervisor | Mordechai Guri | [Link](https://arxiv.org/pdf/2506.09825) | --- |
| 2025 | Wallbleed: A Memory Disclosure Vulnerability in the Great Firewall of China | Shencha Fan, Jackson Sippe, Sakamoto San, Jade Sheffey, David Fifield, Amir Houmansadr, Elson Wedwards, Eric Wustrow | [Link](https://www.ndss-symposium.org/wp-content/uploads/2025-237-paper.pdf) | --- |
| 2025 | SoK: Stealing Cars Since Remote Keyless Entry Introduction and How to Defend From It | Tommaso Bianchi, Alessandro Brighente, Mauro Conti, Edoardo Pavan | [Link](https://arxiv.org/pdf/2505.02713) | --- |
| 2025 | The Secret Life of CVEs | Piotr Przymus, Mikołaj Fejzer, Jakub Narębski, Krzysztof Stencel | [Link](https://arxiv.org/pdf/2504.03863) | --- |
| 2024 | Private and Secure Fuzzy Name Matching | Harsh Kasyap, Ugur Ilker Atmaca, Carsten Maple, Graham Cormode, Jiancong He | [Link](https://arxiv.org/pdf/2407.19979) | --- |
| 2024 | SHA-256 Collision Attack with Programmatic SAT | Nahiyan Alamgir, Saeed Nejati, Curtis Bright | [Link](https://arxiv.org/pdf/2406.20072) | --- |
| 2024 | Inferring Discussion Topics about Exploitation of Vulnerabilities from Underground Hacking Forums | Felipe Moreno-Vera | [Link](https://arxiv.org/pdf/2405.04561) | --- |
| 2024 | CRATOR: a Dark Web Crawler | Daniel De Pascale, Giuseppe Cascavilla, Damian A. Tamburri, Willem-Jan Van Den Heuvel | [Link](https://arxiv.org/abs/2405.06356) | --- |
| 2024 | Statistical testing of random number generators and their improvement using randomness extraction | Cameron Foreman, Richie Yeung, Florian J. Curchod | [Link](https://arxiv.org/pdf/2403.18716) | --- |
| 2024 | Inception Attacks: Immersive Hijacking in Virtual Reality Systems | Zhuolin Yang, Cathy Yuanchen Li, Arman Bhalla, Ben Y. Zhao, Haitao Zheng | [Link](https://arxiv.org/pdf/2403.05721) | --- |
| 2024 | Username Squatting on Online Social Networks: A Study on X | Anastasios Lepipas, Anastasia Borovykh, Soteris Demetriou | [Link](https://arxiv.org/pdf/2401.09209) | --- |
| 2024 | UVL2: A Unified Framework for Video Tampering Localization | Pengfei Pei, Yun Cao, Jinchuan Li, Zeyu Zhang, Yuqi Pang | [Link](https://arxiv.org/pdf/2309.16126) | --- |
| 2023 | The Software Genome Project: Venture to the Genomic Pathways of Open Source Software and Its Applications | Yueming Wu, Chengwei Liu, Yang Liu | [Link](https://arxiv.org/pdf/2311.09881) | --- |
| 2023 | JFinder: A Novel Architecture for Java Vulnerability Identification Based Quad Self-Attention and Pre-training Mechanism | Jin Wanga, Zishan Huanga, Hui Xiaoa, Yinhao Xiao | [Link](https://arxiv.org/pdf/2307.15915) | [Github](https://github.com/WJ-8/JFinder) |
| 2023 | Twitter Bots Influence on the Russo-Ukrainian War During the 2022 Italian General Elections | Francesco Luigi De Faveri, Luca Cosuti, Pier Paolo Tricomi, Mauro Conti | [Link](https://arxiv.org/pdf/2306.07183) | --- |
| 2023 | A Survey on Learning to Hash | Jingdong Wang, Heng Tao Shen, Ting Zhang | [Link](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/01/LTHSurvey.pdf) | --- |
| 2023 | MAWSEO: Adversarial Wiki Search Poisoning for Illicit Online Promotion | Zilong Lin , Zhengyi Li , Xiaojing Liao , XiaoFeng Wang , Xiaozhong Liu | [Link](https://arxiv.org/pdf/2304.11300) | --- |
| 2023 | Quantifying User Password Exposure to Third-Party CDNs | Rui Xin, Shihan Lin, Xiaowei Yang | [Link](https://arxiv.org/pdf/2301.03690) | [Github](https://github.com/SHiftLin/PAM2023-CDNPassword) |
| 2022 | GhostTouch: Targeted Attacks on Touchscreens without Physical Touch | Kai Wang, Richard Mitev, Chen Yan, Xiaoyu Ji, Ahmad-Reza Sadeghi, Wenyuan Xu | [Link](https://www.usenix.org/system/files/sec22-wang-kai.pdf) | [Github](https://github.com/USSLab/GhostTouch) |
| 2022 | Lamphone: Passive Sound Recovery from a Desk Lamp's Light Bulb Vibrations | Ben Nassi, Yaron Pirutin, Raz Swisa, Adi Shamir, Yuval Elovici, Boris Zadov| [Link](https://www.usenix.org/system/files/sec22-nassi.pdf) | --- |
| 2022 | Too Afraid to Drive: Systematic Discovery of Semantic DoS Vulnerability in Autonomous Driving Planning under Physical-World Attacks | Ziwen Wan Junjie Shen, Jalen Chuang, Xin Xia, Joshua Garcia, Jiaqi Ma, Qi Alfred Chen | [Link](https://arxiv.org/pdf/2201.04610.pdf) | --- |
| 2021 | Characterizing Retweet Bots: The Case of Black Market Accounts | Tugrulcan Elmas, Rebekah Overdorf, Karl Abere | [Link](https://arxiv.org/pdf/2112.02366.pdf) | --- |
| 2021 | Hardware Trojan Insertion in Finalized Layouts: a Silicon Demonstration | Tiago Perez, Samuel Pagliarini | [Link](https://arxiv.org/pdf/2112.02972.pdf) | --- |
| 2021 | Trojan Source: Invisible Vulnerabilities | Nicholas Boucher, Ross Anderson | [Link](https://arxiv.org/pdf/2111.00169.pdf) | --- |
| 2021 | Demystifying Scam Tokens on Uniswap Decentralized Exchange | Pengcheng Xia, Haoyu Wang, Bingyu Gao, Weihang Su, Zhou Yu, Xiapu Luo, Chao Zhang, Xusheng Xiao, Guoai Xu | [Link](https://arxiv.org/pdf/2109.00229.pdf) | --- |
| 2021 | BGPeek-a-Boo: Active BGP-based Traceback for Amplification DDoS Attacks | Johannes Krupp, Christian Rossow | [Link](https://arxiv.org/pdf/2103.08440.pdf) | --- |
| 2021 | The Rise and Fall of Fake News sites: A Traffic Analysis | Manolis Chalkiadakis, Alexandros Kornilakis, Pangiotis Papadopoulos, Evangelos P. Markatos, Nicolas Kourtellis  | -[Link](https://arxiv.org/pdf/2103.09258.pdf) | --- |
| 2021 | Kubernetes Auto-Scaling: YoYo attack vulnerability and mitigation | Ronen Ben-David, Anat Bremler-Barr | [Link](https://arxiv.org/pdf/2105.00542.pdf) | --- |
| 2021 | Intrinsic Propensity for Vulnerability in Computers?Arbitrary Code Execution in the Universal Turing Machine | Pontus Johnson | [Link](https://arxiv.org/pdf/2105.02124.pdf) | --- |
| 2021 | Python and Malware:  Developing Stealth and Evasive Malware WithoutObfuscation | Vasilios Koutsokostas, Constantinos Patsakis | [Link](https://arxiv.org/pdf/2105.00565.pdf) | --- |
| 2021 | The Closer You Look, The More You Learn: A Grey-box Approach to Protocol State Machine Learning | Chris McMahon Stone, Sam L. Thomas, Mathy Vanhoef, James Henderson, Nicolas Bailluet, Tom Chothia  | [LINK](https://arxiv.org/pdf/2106.02623.pdf) | --- |
| 2021 | How Great is the Great Firewall? Measuring China’s DNS Censorship | Nguyen Phong Hoang, Arian Akhavan Niaki, Jakub Dalek, Jeffrey Knockel, Pellaeon Lin, Bill Marczak, Masashi Crete-Nishihata, Phillipa Gill, Michalis Polychronakis | [Link](https://arxiv.org/pdf/2106.02167.pdf) | --- |
| 2021 | SEVerity: Code Injection Attacks against Encrypted Virtual Machines | Mathias Morbitzer, Sergej Proskurin, Martin Radev, Marko Dorfhuber, Erick Quintanar Salas | [Link](https://arxiv.org/pdf/2105.13824.pdf) | --- |
| 2021 | Web Content Signing with Service Workers | Thomas Sutter, Peter Berlich, Marc Rennhard, Kevin Lapagna, Fabio Germann | [Link](https://arxiv.org/pdf/2105.05551.pdf) | --- |
| 2021 | Memory-Safety Challenge Considered Solved? An In-DepthStudy with All Rust CVEs | Hui Xu, Zhuangbin Chen, Mingshen Sun, Yangfan Zhou, Michael R. Lyu | [Link](https://arxiv.org/pdf/2003.03296.pdf) | --- |
| 2020 | Light CommANDS: Laser-Based Audio Injection on Voice-Controolable Systems | Takeshi Sugawara, Benjamin Cyr, Sara Rampazzi, Daniel Genkin, Kevin Fu | [Link](https://www.usenix.org/system/files/sec20-sugawara.pdf) | --- |
| 2020 | Understanding Memory and Thread Safety Practices and Issues in Real-World Rust Programs | Boqin Qin, Yilun Chen, Zeming Yu, Linhai Song, Yiying Zhang | [Link](https://cseweb.ucsd.edu/~yiying/RustStudy-PLDI20.pdf) | --- |
| 2020 | Security and Privacy of Social Login | Louis Christopher Jannett | [Link](https://www.nds.ruhr-uni-bochum.de/media/nds/arbeiten/2020/10/29/Masterarbeit_Louis_Jannett_Security_and_Privacy_of_Social_Logins.pdf) | --- |
| 2014 | ECMAScript 6 for Penetration Testers |  Mario Heiderich | [Link](https://cure53.de/es6-for-penetration-testers.pdf) | --- |
| 2005 | A Self-Learning Worm Using Importance Scanning | Zesheng Chen, Chuanyi Ji | [Link](https://users.pfw.edu/chenz/paper/worm05-chen.pdf) | --- |
| 2005 | Network Protocol Analysis using Bioinformatics Algorithms | Marshall A. Beddoe | [Link](http://phreakocious.net/PI/PI.pdf) | |

### Blogposts
| Year | Title | Author | Link |
| --- | --- | --- | --- |
| 2021 | Security and Privacy of Social Logins (I) | Louis Christopher Jannett | [Link](https://web-in-security.blogspot.com/2021/02/security-and-privacy-of-social-logins-part1.html) |
| 2021 | Security and Privacy of Social Logins (II) | Louis Christopher Jannett | [Link](https://web-in-security.blogspot.com/2021/02/security-and-privacy-of-social-logins-part2.html) |
| 2021 | Security and Privacy of Social Logins (III) | Louis Christopher Jannett | [Link](https://web-in-security.blogspot.com/2021/02/security-and-privacy-of-social-logins-part3.html) |
| 2021 | Weird Ways to Run Unmanaged Code in .NET | XPN/Adam Chester | [Link](https://blog.xpnsec.com/weird-ways-to-execute-dotnet/) |
| 2020 | Reverse Engineering the source code of the BioNTech/Pfizer SARS-CoV-2 Vaccine | Bert Hubert  | [Link](https://berthub.eu/articles/posts/reverse-engineering-source-code-of-the-biontech-pfizer-vaccine/) |
| 2020 | Practical Exploitation of Math.random on V8 | d0nut | [YT](https://www.youtube.com/watch?v=_Iv6fBrcbAM) [Github](https://github.com/d0nutptr/v8_rand_buster) |
| 2018 | Introduction to Locality-Sensitive Hashing | Tyler Neylon | [Link](https://unboxresearch.com/articles/lsh_post1.html) |


