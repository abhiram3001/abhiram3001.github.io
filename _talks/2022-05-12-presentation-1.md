---
title: "Lempel-Ziv Compression, guided by prof. Andrew Thangaraj"
collection: presentation
type: "Presentation"
permalink: /talks/2022-05-12-presentation-1
venue: "CRC 301, NPTEL Studio"
date: 2023-05-12
location: "Chennai, India"
---
In many practical scenarios in communications and data processing, we work with large volumes of data. A single minute of an uncompressed HD video can be over 1 GB. How do we then fit a two-hour film on a 25 GB Blu-ray disc? So, there is a need for robust, lossless data compression techniques.
Most compression techniques (like Huffman encoding) although optimal, need prior knowledge of the source distribution.

But when no prior information of the source is the available, and the statistical tests are unreliable, the problem of data compression becomes a lot more complex. So, the goal is to have a universal coding scheme that works for any discrete source and also has a performance comparable to optimal source codes. Most data files have patterns in them, where certain letters are more likely to occur. Data compression algorithms exploit these characteristics to compress data. Lempel Ziv does something similar, and uses an ’adaptive’ dictionary where the algorithm adds syllables/words that occur more often to that dictionary.

Here you can find my final presentation: [presentation](https://drive.google.com/file/d/1HHI_gLGgX3aA0C-7PXI-1EIQ1OKIpXyu/view?usp=sharing)

and if the presentation interests you, link to the project report: [report](https://drive.google.com/file/d/1Ji24ldE-HpeLsSbeabawEJTxD4tSRJZj/view?usp=sharing)

(Sidenote: This project was the culmination of all my learnings about Information Theory (EE5143) under the guidance of Prof. Andrew Thangaraj. EE5143 was easily one of the best courses I have done in the seven semesters of my UG so far. The project topic is a really beautiful one, with an opportunity to delve very deep into the intricacies of Information Theory. 

I also got a chance to present my work to a class of ~30 students along with Prof. Andrew, and while my presentation went on for almost thrice as long as the prescribed time limit, I am extremely glad that the feedback I got from my peers and Prof. Andrew was really encouraging.)
