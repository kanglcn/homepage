---
title: "{{ .Name | replaceRE "^.{11}" "" | humanize | title }}"
date: {{ .Date }}
lastmod: {{ .Date }}
author: 梁康
categories:
  - 
tags: 
  - 
slug: {{ .Name | replaceRE "^.{11}" "" }} 
draft: true
---

