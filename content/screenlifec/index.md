---
title: "ScreenLife Capture"
summary: ScreenLife Capture is an open-source software tool for researchers to collect screenome data.
date: ""

featured: true
reading_time: true  # Show estimated reading time?
share: true  # Show social sharing links?
profile: false  # Show author profile?
comments: true  # Show comments?

# Optional header image (relative to `static/img/` folder).
header:
  caption: ""
  image: " "

---
Developed by students and researchers at the Singapore University of Technology and Design, the ScreenLife Capture application is an open-source software suite which allows researchers to collect screenome data from Android smartphones. Screenomes are sequenced high-frequency screenshots of participants’ device use, and a technique to study digital media use pioneered by Reeves and colleagues (2021). For example, the ScreenLife Capture Android application captures a screenshot of a participant’s smartphone use every five seconds. This allows for highly granular data on smartphone use which may be useful for researchers interested in the study of digital media. 

An example of screenome data can be represented in the following analysis:

{{< figure src="ScreenomeYeeAnalysis.jpeg" title="" lightbox="true" >}}

ScreenLife Capture is the first freely available and open-source screenome collection tool for researchers. The application is free to download, edit, and use for academic research purposes. The full details of the application can be found in the following paper. Please use the following citation if you are using ScreenLife Capture for your research project:

_Yee, A. Z. H., Yu, R., Lim, S. S., Lim, K. H., Dinh, T. T. A., Loh, L., Hadianto, A., and Quizon, M. (2022, August 31). ScreenLife Capture: An open-source and user-friendly framework for collecting screenome data from Android smartphones. Retrieved from https://psyarxiv.com/sphq4_

The code to the different components of ScreenLife Capture can be found here: https://github.com/ScreenLife-Capture-Team

Meanwhile, researchers can refer to this easy-to-understand guide in order to build their own data collection module:

{{% staticref "/screenlifec/SLCGuide.pdf" "newtab" %}}ScreenLife Capture Guide for Researchers{{% /staticref %}}


All the components of the ScreenLife Capture Framework is licensed under the
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
