---
layout: post
title:  "Three-Way Coin Toss"
date:   2020-09-16
desc: "Designing a coin with equal probability of landing on any three faces"
keywords: "Probability, Physics"
categories: [Probability]
tags: [Probability, Physics]
icon: icon-coin
---
A [wikipedia page on coin flipping](https://en.wikipedia.org/wiki/Coin_flipping#:~:text=However%2C%20even%20on%20a%20flat,their%20edges%20unsupported%20if%20flipped.) proposes mutliple methods for three-way coin flips. However, these all involve either multiple coins, or flipping a singular coin multiple times - both solutions are begging to be optimized. 

Now, the obvious solution is to use a dice-like object, where each face has equal probabilities, and those faces can be distributed among three players evenly. A  more biased approach would involve assigning the edge of the coin (i.e. the height of the cylinder) to the third player - Wikipedia outlines this probability to be about 1 in 6000 (for an American nickel). However, as the height of the cylinder grows, the likelihood of the "edge" being landed on also increases. For example, you could imagine a hockey puck landing on any of its faces, and ironically, flipping a packaged bank roll of coins would probably result in all coins landing on their "edge". Taking this to the extreme gives a bottle-like shape, where getting the object to land on one of its circular faces has literally become a [sport](https://bleacherreport.com/articles/2695150-water-bottle-flipping-is-now-a-real-sport-no-seriously).

This begs the question of optimality. What is the ideal height of a cylinder with a given diameter, such that the probabilities of the cylinder landing on each of its three faces are equivalent?

Surprisingly enough, there may be no right answer. [Fair Dice](http://statweb.stanford.edu/~cgates/PERSI/papers/fairdice.pdf), by Persi Diaconis and Joseph B. Keller, describes how dice can be fair by symmetry (i.e. a 6-sided die), or by continuity, such as the three-sided coin that we are describing, but that fair dice dependent on continuity have probabilities impacted by their environment, i.e. air pressure and the surface upon which the object lands.

Mathematician Matt Parker has a cool [video](https://www.youtube.com/watch?v=-qqPKKOU-yY) on the topic that I'd highly recommend. Additionally, check out [this simulation](https://jsfiddle.net/x4fab/vf3q0210/) to experiment with varying coin widths.