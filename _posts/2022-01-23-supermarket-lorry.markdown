---
layout: post
title:  "Don't take a lorry to the supermarket when a motorcycle will do"
date: 2022-01-22
category: Productivity
published: false
---

## A Real Example

Let's take an example - suppose you have a dataset of 100 thousand records. You and your team want to be able to search, filter, pivot and graph all the data flexibly and very quickly.

The tendency for technologists - especially ones who are very capable and have a lot of tools in their toolbox - is to think about building a *future-proof* solution. The logic goes something like - "What if the dataset grows to 100 million records? If we build for that now, then we don't have to do it again later. So let's do it from the start."

The conversation will then go into using "Big Data" and other buzzword technologies. Then about deploying it on the Cloud, with an over-priced managed data warehouse with all the bells and whistles. This can go on and on.

Good engineers do indeed need to predict the myriad ways something can go wrong and build accordingly, ideally such that problems never occur. However, this can be taken way too far.

In the 100 thousand records case, guess what - you don't have to code anything. Excel can handle up to 1 million rows and can do everything you want. Even Google Sheets can handle a few hundred thousand if you don't want to pay the license fee. If the dataset grows, stick it into simple SQL database like Postgres or even SQLite!

But thsoe are incredibly boring and unsexy solutions, so people don't really like to discuss it. Much more fun to discuss a giant datawarehouse that no one really needs.