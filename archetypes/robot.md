---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
description: ""
categories: [Robots]
tags: [FRC,robot,'{{ now.Format "2006" }}_season']disableComments: false
draft: true
menu:
  main:
    parent: "robots"
    weight: 1
    # Set weight according to where you want it placed. lower number = higher on list.
---
