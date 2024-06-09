+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = {{ .Date }}
author = '{{ site.Params.Author.Name}}'
description = ''
slug = '{{ .File.ContentBaseName }}'
+++
