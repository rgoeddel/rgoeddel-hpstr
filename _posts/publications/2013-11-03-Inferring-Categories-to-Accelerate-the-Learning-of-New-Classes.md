---
layout: post
title: "Inferring Categories to Accelerate the Learning of New Classes"
categories: [publications]
comments: false
hidden: true
---

**Proceedings of the IEEE/RSJ International Conference on Intelligent Robots
and Systems (IROS), 2013**<br>
*Robert Goeddel and Edwin Olson*

<img src="/images/bolt-fig.png" align="right" hspace="10px" width="50%">
**Abstract -**
On-the-fly learning systems are necessary for the deployment of general purpose
robots. New training examples for such systems are often supplied by mentor
interactions. Due to the cost of acquiring such examples, it is desirable to
reduce the number of necessary interactions. Transfer learning has been shown
to improve classification results for classes with small numbers of training
examples by pooling knowledge from related classes. Standard practice in these
works is to assume that the relationship between the transfer target and
related classes is already known.
{: align="justify"}

In this work, we explore how previously learned categories, or related
groupings of classes, can be used to transfer knowledge to novel classes
without explicitly known relationships to them. We demonstrate an algorithm
for determining the category membership of a novel class, focusing on the
difficult case when few training examples are available. We show that
classifiers trained via this method outperform classifiers optimized to learn
the novel class individually when evaluated on both synthetic and real-world
datasets.
{: align="justify"}

[PDF](https://april.eecs.umich.edu/pdfs/goeddel2013iros.pdf)
