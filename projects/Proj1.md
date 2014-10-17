---
title: Video Tampering Detection using Digital Image Watermarking
layout: default
members: Rajat Vikram Singh, Charvi Puri, Saurav Maitra
description: Internship Project @ Image Analysis and Biometrics Lab, IIITD
category: project
---

The problem of Video Authentication has been explored widely by researchers across the globe hence there are many algorithms presently available on this topic. The two main approaches generally seen are – digital signature and digital watermarking. Digital watermarking uses visual feature extraction and embeds them into the underlying frame of the video, whereas digital signature schemes often add some information in the frame which is visible to the user. 
In this project, we proposed a robust digital watermarking algorithm which counters all the global attacks that are used to alter the content of the video: frame addition, removal, shuffle and object addition and removal. 
As part of the project, two existing algorithms were implemented as baseline. Among the algorithms implemented, one was entropy based algorithm and the other was based on the measures of decay in wavelet transform of the frames.
The solution we proposed used both inter-frame and intra-frame image properties. We used properties like edges within frame and the hamming distance between consecutive frames, to form a vector which is watermarked in the image in the form of pre-defined pixel-value manipulations. This vector is recovered from the watermark and matched with the vector recovered from the video to check for tampering.