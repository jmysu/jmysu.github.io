---
title: '吉米匠作 Project documentation template'
disqus: jimmyCraft
---

Project Title
===
 [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)        [![Build Status](https://travis-ci.com/jmysu/R3Esp32Grbl.svg?branch=master)](https://travis-ci.com/jmysu/R3Esp32Grbl)

![issues](https://img.shields.io/github/issues/:user/:repo.svg) ![cmmit](https://img.shields.io/github/last-commit/:user/:repo.svg) ![ver](https://img.shields.io/github/manifest-json/v/:user/:repo.svg)
 
### Table of Contents

[TOC]

### About

JimmyCraft Open Sources project!



### History
---
```gherkin=
Feature: Shopping Cart
  As a Shopper
  I want to put items in my shopping cart
  Because I want to manage items before I check out

  Scenario: User adds item to cart
    Given I'm a logged-in User
    When I go to the Item page
    And I click "Add item to cart"
    Then the quantity of items in my cart should go up
    And my subtotal should increment
    And the warehouse inventory should decrement
```


### Project Timeline
---
```mermaid
gantt
    title  吉米匠作 時程規劃

    section Hardware
    PCB Design/Layout:a1, 19-06-01, 45d
    PCB Debug:a2, after a1, 30d
    PCB 2'nd RUN      :after a2  , 15d
    
    section Firmware
    ESP32/PlatformIO:19-07-01  , 45d
    ESP32/WebUI      :19-07-01, 60d
```
```Read more about mermaid here: http://knsv.github.io/mermaid/
```
> I choose a lazy person to do a hard job. Because a lazy person will find an easy way to do it. [name=Bill Gates]


