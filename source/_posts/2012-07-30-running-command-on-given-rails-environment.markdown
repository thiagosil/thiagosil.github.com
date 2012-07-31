---
layout: post
title: "Running command on given rails environment"
date: 2012-07-30 22:01
comments: true
categories: [rails, rake]
---

To run a command on a given rails environment you just need to do:

```
$ RAILS_ENV=test rake db:migrate
```

For example, would run the command, for the test environment only.