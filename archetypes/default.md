+++
date = '{{ .Date }}'
draft = true
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
description = "{{ .Description }}"
categories:
  - "{{ .Categories | default "默认分类" }}"
tags:
  - "{{ .Tags | default "默认标签" }}"
+++
