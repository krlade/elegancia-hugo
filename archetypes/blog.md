---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
author: "{{ .Site.Params.author }}"
layout: blog
---
This is a template blog post
