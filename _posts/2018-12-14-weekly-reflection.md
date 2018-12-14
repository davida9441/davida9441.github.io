---
layout: post
title: "Flag Project - In process "
date: 2018-12-14
---

This week we have started our flag project V2. no one is finished yet and we are all currently in progress of coding the flag. Here is the code for my in progress flag (Greece):

include image

size = 97.32
width = size * 3
height = size * 2

stripe-height = height / 9

base = rectangle(width, height, "solid", "blue")
stripe = rectangle(width, stripe-height, "solid", "white")

base1 = place-image(stripe, width / 2, 1.5 * stripe-height, base)

base2 = place-image(stripe, width / 2, 3.5 * stripe-height, base1)




