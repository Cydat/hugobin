---
title: {{ replace .TranslationBaseName "-" " " | title }}
subtitle:
date: {{ date:%Y-%m-%d %H:%M:%S.%6N %Z }}
slug: {{ substr .File.UniqueID 0 7 }}
description:
keywords:
draft: true
comment: false
---
