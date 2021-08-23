# OffensiveReading

A collection of papers about offensive IT security with some blogposts sprinkled in. If you want to contribute a paper just open a issue or issue a pull request. 

## Browsers / Browser Side Channel
### Papers/Thesis
| Year | Title | Author | Link | Github/PoC |
| --- | --- | --- | --- | --- |
| 2021 | SoK: In Search of Lost Time: A Review of JavaScript Timers in Browsers. | Thomas Rokicki, Clémentine Maurice, Pierre Laperdrix | [Link](https://hal.inria.fr/hal-03215569) | --- |
| 2021 | Awakening the Web's Sleeper Agents: Misusing Service Workers for Privacy Leakage | Soroush Karami, Panagiotis Ilia, Jason Polakis | [Link](https://www.ndss-symposium.org/wp-content/uploads/ndss2021_1C-2_23104_paper.pdf) | |
| 2020 | Cross-Origin State Inference (COSI) Attacks:Leaking Web Site States through XS-Leaks | Avinash Sudhodanan, Soheil Khodayari, Juan Caballero | [Link](https://arxiv.org/pdf/1908.02204.pdf) |  |
| 2019 | BakingTimer: privacy analysis of server-side request processing time | Iskander Sánchez-Rola, D. Balzarotti, I. Santos | [Link](https://www.semanticscholar.org/paper/BakingTimer%3A-privacy-analysis-of-server-side-time-S%C3%A1nchez-Rola-Balzarotti/fcb40f635dc8195c8529585d7bfcde8920e0a57b) | |
| 2019 | Browser Fingerprinting using Combinatorial Sequence Testing | Bernhard Garn, Dimitris E. Simos, Stefan Zauner, Rick Kuhn, Raghu Kacker| [Link](https://tsapps.nist.gov/publication/get_pdf.cfm?pub_id=927531) |  |
| 2018 | How Tracking Companies Circumvented Ad Blockers Using WebSockets | Muhammad Ahmad Bashir, Sajjad Arshad, Engin Kirda, William Robertson, Christo Wilson | [Link](https://sajjadium.github.io/files/imc2018websockets_paper.pdf) | --- |
| 2017 | Fantastic Timers and Where to Find Them: High-Resolution Microarchitectural Attacks in JavaScript | Michael Schwarz, Clémentine Maurice, Daniel Gruss, Stefan Mangard | [Link](https://gruss.cc/files/fantastictimers.pdf) | --- |
| 2017 | Practical Keystroke Timing Attacks in Sandboxed JavaScript | Moritz Lipp, Daniel Gruss, Michael Schwarz, David Bidner, Clementine Maurice, Stefan Mangard | [Link](https://mlq.me/download/keystroke_js.pdf) | [Github](https://github.com/IAIK/interruptjs) |
| 2016 | HEIST: HTTP Encrypted Information can be Stolen through TCP-windows | Mathy Vanhoef,Tom Van Goethem | [Link](https://www.blackhat.com/docs/us-16/materials/us-16-VanGoethem-HEIST-HTTP-Encrypted-Information-Can-Be-Stolen-Through-TCP-Windows-wp.pdf) | |
| 2016 | Trusted Browsers for Uncertain Times | David Kohlbrenner, Hovav Shacham | [Link](https://www.usenix.org/system/files/conference/usenixsecurity16/sec16_paper_kohlbrenner.pdf) | --- |
| 2013 | Pixel Perfect Timing  Attacks with HTML5  | Paul Stone | [Link](https://web.archive.org/web/20200424035111/https://go.contextis.com/rs/140-OCV-459/images/Pixel_Perfect_Timing_Attacks_with_HTML5_Whitepaper%20(1).pdf) | [PoC](https://ndev.tk/visted/) |
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


## XSS
### Papers/Thesis
| Year | Title | Author | Link | Github/PoC  |
| --- | --- | --- | --- | --- |
| 2017 | Code-Reuse Attacks for the Web: Breaking Cross-Site Scripting Mitigations via Script Gadgets | Sebastian Lekies, Krzysztof Kotowicz, Samuel Groß, Eduardo A. Vela Nava, Martin Johns  | [Link](https://acmccs.github.io/papers/p1709-lekiesA.pdf) | --- |
| 2020 | PMForce: Systematically AnalyzingpostMessage Handlers at Scale | Marius Steffens, Ben Stock | [Link](https://people.cispa.io/ben.stock/papers/steffens2020pmforce.pdf) | [Github](https://github.com/mariussteffens/pmforce) |
| 2015 | Auto-Patching DOM-based XSS At Scale | Inian Parameshwaran, Enrico Budianto, Shweta Shinde, Hung Dang, Atul Sadhu, Prateek Saxena | [Link](https://www.comp.nus.edu.sg/~tsunami/papers/fse15-main.pdf) | --- |
| 2015 | DEXTERJS: Robust Testing Platform for DOM-Based XSSVulnerabilities | Inian Parameshwaran, Enrico Budianto, Shweta Shinde, Hung Dang, Atul Sadhu, Prateek Saxena | [Link](https://n.ethz.ch/~sshivaji/publications/dexterjs_fse15.pdf) | --- |
| 2013 | 25 Million Flows Later - Large-scale Detection of DOM-based XSS | Sebastian Lekies, Ben Stock, Martin Johns | [Link](https://people.cispa.io/ben.stock/papers/lekies2013flows.pdf) | --- |
| 2013 | mXSS Attacks:  Attacking well-secured Web-Applicationsby using innerHTML Mutations | Mario Heiderich, Jörg Schwenk, Tilman Frosch, Jonas Magazinius, Edward Z. Yang  | [Link](https://cure53.de/fp170.pdf) | --- |


## CSS
### Papers/Thesis
| Year | Title | Author | Link | Github/PoC  |
| --- | --- | --- | --- | --- |
| 2021 | Prime+Probe 1, JavaScript 0: Overcoming Browser-based Side-Channel Defenses | Anatoly Shusterman, Ayush Agarwal, Sioli O’Connell, Daniel Genkin, Yossi Oren, Yuval Yarom  | [Link](https://arxiv.org/pdf/2103.04952.pdf) | --- |
| 2021| Fingerprinting in Style: Detecting Browser Extensions via Injected Style Sheets | Pierre Laperdrix, Oleksii Starov, Quan Chen, Alexandros Kapravelos, Nick Nikiforakis | [Link](https://www.usenix.org/system/files/sec21fall-laperdrix.pdf) | [Github](https://github.com/plaperdr/fingerprinting-in-style) |
| 2020 | Confused by Path: Analysis of Path Confusion Based Attacks | Seyed Ali Mirheidari | [Link](https://iris.unitn.it/retrieve/handle/11572/280512/382175/rpo/) | --- |
| 2020 | Large-Scale Analysis of Style Injection by Relative Path Overwrite | Sajjad Arshad, Seyed Ali Mirheidari, Tobias Lauinger, Bruno Crispo, Engin Kirda, William Robertson  | [Link](https://arxiv.org/pdf/1811.00917.pdf) | --- |

### Blogposts
| Year | Title | Author | Link |
| --- | --- | --- | --- |
| 2019 | Better Exfiltration via HTML Injection | d0nut | [Link](https://d0nut.medium.com/better-exfiltration-via-html-injection-31c72a2dae8b) |


## Side Channels
### Papers/Thesis
| Year | Title | Author | Link | Github/PoC  |
| --- | --- | --- | --- | --- |
| 2019 | SMoTherSpectre: Exploiting Speculative Executionthrough Port Contention | Atri Bhattacharyya, Alexandra Sandulescu, Matthias Neugschwandtner, Alessandro Sorniotti, Babak Falsafi, Mathias Payer, Anil Kurmus | [Link](https://hexhive.epfl.ch/publications/files/19CCS.pdf) | [Github](https://github.com/HexHive/SMoTherSpectre) |


## DNS
### Papers/Thesis
| Year | Title | Author | Link | Github/PoC  |
| --- | --- | --- | --- | --- |
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


## Vulnerability Discovery - Web
### Papers/Thesis
| Year | Title | Author | Link | Github/PoC  |
| --- | --- | --- | --- | --- |
| 2021 | Black Widow: Blackbox Data-driven Web Scanning | Benjamin Eriksson, Giancarlo Pellegrino, Andrei Sabelfeld | [Link](https://publications.cispa.saarland/3224/1/blackwidow_sp2021.pdf) | |
| 2021 | Over 100 Bugs in a Row: Security Analysis of the Top-Rated Joomla Extensions | Marcus Niemietz, Mario Korth, Christian Mainka, Juraj Somorovsky | [Link](https://arxiv.org/pdf/2102.03131.pdf) | --- |
| 2021 | Security Vulnerability Detection Using Deep Learning Natural Language Processing | Noah Ziems, Shaoen Wu | [Link](https://arxiv.org/pdf/2105.02388.pdf) | --- |
| 2020 | Can I Take Your Subdomain?Exploring Related-Domain Attacks in the Modern Web | Marco Squarcina, Mauro Tempesta, Lorenzo Veronese, Stefano Calzavara, Matteo Maffe | [Link](https://arxiv.org/pdf/2012.01946.pdf) | --- |
| 2020 | Cached and Confused: Web Cache Deception in the Wild | Seyed Ali Mirheidari, Sajjad Arshad, Kaan Onarlioglu, Bruno Crispo, Engin Kirda, William Robertson   | --- | --- |

## AI
### Papers/Thesis
| Year | Title | Author | Link | Github/PoC  |
| --- | --- | --- | --- | --- |
| 2021 | Leveraging AI to optimize website structure discovery during Penetration Testing | Diego Antonellib, Roberta Cascellab, Gaetano Perronea, Simon Pietro Romanoa, Antonio Schiano | [Link](https://arxiv.org/pdf/2101.07223.pdf) | --- |
| 2021 | The Threat of Offensive AI to Organizations | YISROEL MIRSKY, AMBRA DEMONTIS, JAIDIP KOTAK, RAM SHANKAR, DENG GELEI, LIU YANG, XIANGYU ZHANG, WENKE LEE, YUVAL ELOVICI, BATTISTA BIGGIO | [Link](https://arxiv.org/pdf/2106.15764.pdf) | --- |
| 2021 | Deep Learning-Based Autonomous DrivingSystems: A Survey of Attacks and Defenses | Yao Deng, Tiehua Zhang, Guannan Lou, Xi Zheng, Jiong Jin, Qing-Long Han | [Link](https://arxiv.org/pdf/2104.01789.pdf) | --- |
| 2017 | Generating Adversarial Malware Examples for Black-Box Attacks Based on GAN | Weiwei Hu, Ying Tan | [Link](https://arxiv.org/pdf/1702.05983.pdf) | --- |


## Fuzzing / Exploitation / Vulnerability Discovery in Binaries
### Papers/Thesis
| Year | Title | Author | Link | Github/PoC  |
| --- | --- | --- | --- | --- |
| 2021 | Spotting Silent Buffer Overflows in Execution Trace throughGraph Neural Network Assisted Data Flow Analysis | Zhilong Wang, Li Yu, Suhang Wang and Peng Liu | [Link](https://arxiv.org/pdf/2102.10452.pdf) | --- |
| 2021 | QFuzz: Quantitative Fuzzing for Side Channels | Yannic Noller, Saeid Tizpaz-Niari | [Link](https://arxiv.org/pdf/2106.03346.pdf) | [Github](https://github.com/yannicnoller/qfuzz) |
| 2021 | Revizor: Fuzzing for Leaks in Black-box CPUs | Oleksii Oleksenko, Christof Fetzer, Boris Köpf, Mark Silberstein | [Link](https://arxiv.org/pdf/2105.06872.pdf) | [Github](https://github.com/hw-sw-contracts/revizor) |
| 2021 | Snipuzz: Black-box Fuzzing of IoT Firmware via Message Snippet Inference | Xiaotao Feng, Ruoxi Sun, Xiaogang Zhu, Minhui Xue, Sheng Wen, Dongxi Liu, Surya Nepal, Yang Xiang | [Link](https://arxiv.org/pdf/2105.05445.pdf) | --- |
| 2020 | The never ending war in the stack and the reincarnation of ROP attacks | Ammari Nader, Joan Calvet, Jose M. Fernandez | [Link](https://arxiv.org/pdf/2005.11886.pdf) | --- |
| 2015 | Pattern-Based Vulnerability Discovery | Fabian Yamaguchi | [Link](https://ediss.uni-goettingen.de/bitstream/handle/11858/00-1735-0000-0023-9682-0/mainFastWeb.pdf) | --- |
| 2016 | Toward large-scale vulnerability discovery using Machine Learning | Gustavo Grieco, Guillermo Luis Grinblat, Lucas Uzal, Sanjay Rawat, Josselin Feist, Laurent Mounier  | [Link](http://www.covert.io/research-papers/deep-learning-security/Toward%20large-scale%20vulnerability%20discovery%20using%20Machine%20Learning.pdf) | --- |

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
| 2021 | A Measurement Study on the (In)security of End-of-Life (EoL) Embedded Devices | Dingding Wang, Muhui Jiang, Rui Chang, Yajin Zhou, Baolei Hou, Xiapu Luo, Lei Wu, Kui Ren | [LINK](https://arxiv.org/pdf/2105.14298.pdf) | --- |
| 2020 | HALucinator: Firmware Re-hosting Through Abstraction Layer Emulation| Abraham A. Clements, Eric Gustafson, Tobias Scharnowski, Paul Grosen, David Fritz, Christopher Kruegel, Giovanni Vigna, Saurabh Bagchi, Mathias Payer | [Link](http://hexhive.epfl.ch/publications/files/20SEC2.pdf) | [Github](https://github.com/embedded-sec/halucinator) |
| 2016 | Towards Automated Dynamic Analysis for Linux-based Embedded Firmware | Daming D. Chen, Manuel Egele, Maverick Woo, David Brumley | [Link](https://raw.githubusercontent.com/firmadyne/firmadyne/master/paper/paper.pdf) | [Github](https://github.com/firmadyne/firmadyne) |

### Blogposts
| Year | Title | Author | Link |
| --- | --- | --- | --- |
| 2020 | Using Z3 Theorem on AVR Firmware | Ryan Cornateanu | [Link](https://ryancor.medium.com/using-z3-theorem-on-avr-firmware-c6d2f45ac9c2) |


## Misc/Other 
### Papers/Thesis
| Year | Title | Author | Link | Github/PoC  |
| --- | --- | --- | --- | --- |
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

