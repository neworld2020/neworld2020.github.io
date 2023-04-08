---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am Mengxuan Song, an undergraduate student learning in School of Control Science and Engineering, Zhejiang University (ZJU), looking for a **summer research opportunity** concerning with network or network application.

In past three years in ZJU, I got a GPA(for all major courses) of **4.585/5(or 3.99/4)**, which is is the 7th among all students in this major. As for English, I got 557 in College English Test(CET) and I'm preparing for a TOEFL test on 4/26.

I'm familiar with **C,C++** for embedding development, **C#** for app development, and **python**, **matlab** for scientific calculation&simulation.

# Personal Characteristics

I think of myself as a person who enjoys describing the world with **programming**, and is interested in how computers form a huge, complex system, in other words, a **network**. 

## Obsessed in Programming

I believe programming is a a way to solve problems in our real world. While preparing for my TOEFL test, I was not satisfied with current English words memorizing apps, so I wrote one myself.  The github repo for this app can be found at [neworld2020/MemoApp](https://github.com/neworld2020/MemoApp) , and the code for app server can be found at [neworld2020/WebFlask](https://github.com/neworld2020/WebFlask). This app is written in C# and the server is written in Flask. This app uses a longer and more interesting context (which is collected from my favorite game, movie, etc) to help me memorize unfamiliar words. I'm now trying to train an AI model to help the user(me) concerntrate on words that are less familiar with and save time.

I am also interested in **IOT** programming. I learn http/mqtt protocols in my freshman's year, based on which I developed a small app collecting carbon data from sensor and we can choose our strategy properly to decrease carbon emission in school. With that I won the third prize in the Energy conservation and emission reduction competition. In my second year, I went to a lab for further learning, where I wrote a small script to convert various types of industrial communication protocols, like modbus, ethercat, etc, into one single protocol OPCUA. I also tried to write an IOT platform resemble to the aliyun or huaweicloud, but with much less functions.

There are some other small projects as well. For example, I try to do the experiments of **map-reduce** with *golang* when I learn distributed system course of MIT. I also wrote a small program to automatically fetch my homework from my school website and send to my calendar, which helps to improve my efficiency greatly.

## Interested in Network

When I first learnt Computer Network, I was attracted by its idea that we can build a really huge and complex system only with small rules(protocols) running on every participant. From that on, I start my learning and researching on network. I have learnt some Web programming skills as base, and currently I pay my attention on distributed system. I studied *distributed system* lesson from MIT open course and tried to do several experiments of the course. Last year, I followed one professor in my school to do researches on distributed learning. Now I am doing research on **relationship between network topology and learning performance**. I have read several related papers and I'm preparing for experiments about this topic.

Beyond computer network, I'm curious whether we can apply the principles of computer network to other fields to build a huge system as well, I think the basic is to create proper rules and make participants to obey them.

# Projects

Here are some typical examples of projects I've done. It contains projects related to network, wireless signal, network application(http), etc.

## Research on Relationship between Network Topology and Deep Learning Performance

> **Introduction**
> With the development of big-model AI, how to train AI on a huge dataset become a problem, using a distributed training system is one of our solutions. However, when the number of machines increase, the communication cost gradually gets larger and become the bottleneck. From the aspect of network topology, what topology can reach a satisfying balance between communication cost and convergence speed.
>
> **Type**
> Long term research project
>
> **Current Progress**
> Reading and Learning period. In this period, I'll learn how to evaluate the performance of a distributed learning system, what factors may influence the performance, what's the relationship between them, how to get these factors if a network topology is given. After learning these theories, I'll begin to do experiments to verify these theories and try to find new problems.
>
> To be specific, in my first stage, I have learnt that communication cost can be evaluated through the max degree of all nodes, and convergence speed can be evaluated with the 'spectral gap' of a network. To get the idea, I started to learn some basic about Graph Spectrum Theory, laying a mathematical fundation for further research.

## Active Person Detection with WIFI CSI Signal

> **Introduction**
> Channel State Information(CSI), according to OSI Model, is a kind of physical layer information. It contains information about the propagation process of WIFI signal, and is often used to indoor location. In this project, I plan to use CSI to detect whether there are active persons in a space, like a classroom.
>
> Its principle is really simple: we set an AP and Station connected to each other, when there are someone walk between them, the WIFI signal will be disturbed. We can detect such disturbance as a signal meaning there are active things moving between them. You can find my experiment video at [Active People Detection](https://youtu.be/IXZZNA0fULc).
>
> **Type**
> Temporary Project
>
> **Result**
> It can detect persons' movements in a 'quiet' environment, where there are small number of wireless devices and only a few people are active. But gets a bad result in an environment where there are lots of people and wireless devices. 
>
> After learning big-data analysis methods, I realized maybe I can continue improving this project using big-data analsys methods. We can first pre-collect environment information, and analyse current information with big-data method. This is one direction I'm interested in.

## Playen: An Interest-based Words Memorizing App

> **Introduction**
> For non-native English speakers, to help them memorize words more easily, I developed a small app. This app uses dialogues from a famous game. When you see the word, you can remember where it appears, and you know the meaning of the word. Also, by learning how character express their thoughts, we can know how to express like a native English speaker. These are my principles to develop such an app.
>
> These project can be divided into two parts: app that runs on your mobile, written with C#; and server that supports the app, written in python
>
> **Type**
> Short term project
>
> **Current Progress**
> Almost all basic functions are completed. Now I'm working on its review algorithm, which decides what words to appear when reviewing. I'm trying to use an AI model that uses word length, time span, mistake rate as its input, and estimated word familiarity as its output. With that, I can decide words to show just simply according to familiarity.

# Awards

Academic Excellency Award of ZJU
Zhejiang University Scholarship - Third Prize

National Undergraduate Mathematics Competition - First Prize
Energy Conservation and Emission Reduction Competition - Third Prize