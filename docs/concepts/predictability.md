---
title: Predictability
layout: default
project: GridOS
parent: Important Concepts
permalink: /concepts/predictability
---

## {{ page.title }}

We value this as N. Historically items valued N have ranged in delivery time from X - Z weeks of total effort. Therefore, we can theoretically place this change to take between X and Z weeks to deliver

Given our current progress on Inventory Item A is at 4 weeks out of 20, we estimate the delivery of this item in J weeks of effort

Therefore we estimate this will take between X - Z weeks of effort to get done once we get started. Our current WIP has Approximately A - B time left, so we should get started on Improving Medication Search Times in 3-4week time given what we know currently.

(10 + 10 +(10 - 3)) / 3
(7 + 10 + 7) / 3
24 / 3
8
<!-- 
```mermaid
timeline
    title Team Accomplishments
    2023.Q1.S1  : CLOWNS
                : MOTIVATORS
                : DELIVER
                : GROWTH
                : CRAZY
                : PROTRACTOR
    2023.Q1.S2 : Facebook
         : Google
    2023.Q1.S3 : Youtube
    2023.Q1.S4 : Twitter
```

```mermaid
    C4Context
      title System Context diagram for Internet Banking System
      Enterprise_Boundary(b0, "BankBoundary0") {
        Person(customerA, "Banking Customer A", "A customer of the bank, with personal bank accounts.")
        Person(customerB, "Banking Customer B")
        Person_Ext(customerC, "Banking Customer C", "desc")

        Person(customerD, "Banking Customer D", "A customer of the bank, <br/> with personal bank accounts.")

        System(SystemAA, "Internet Banking System", "Allows customers to view information about their bank accounts, and make payments.")

        Enterprise_Boundary(b1, "BankBoundary") {

          SystemDb_Ext(SystemE, "Mainframe Banking System", "Stores all of the core banking information about customers, accounts, transactions, etc.")

          System_Boundary(b2, "BankBoundary2") {
            System(SystemA, "Banking System A")
            System(SystemB, "Banking System B", "A system of the bank, with personal bank accounts. next line.")
          }

          System_Ext(SystemC, "E-mail system", "The internal Microsoft Exchange e-mail system.")
          SystemDb(SystemD, "Banking System D Database", "A system of the bank, with personal bank accounts.")

          Boundary(b3, "BankBoundary3", "boundary") {
            SystemQueue(SystemF, "Banking System F Queue", "A system of the bank.")
            SystemQueue_Ext(SystemG, "Banking System G Queue", "A system of the bank, with personal bank accounts.")
          }
        }
      }

      BiRel(customerA, SystemAA, "Uses")
      BiRel(SystemAA, SystemE, "Uses")
      Rel(SystemAA, SystemC, "Sends e-mails", "SMTP")
      Rel(SystemC, customerA, "Sends e-mails to")

      UpdateElementStyle(customerA, $fontColor="red", $bgColor="grey", $borderColor="red")
      UpdateRelStyle(customerA, SystemAA, $textColor="blue", $lineColor="blue", $offsetX="5")
      UpdateRelStyle(SystemAA, SystemE, $textColor="blue", $lineColor="blue", $offsetY="-10")
      UpdateRelStyle(SystemAA, SystemC, $textColor="blue", $lineColor="blue", $offsetY="-40", $offsetX="-50")
      UpdateRelStyle(SystemC, customerA, $textColor="red", $lineColor="red", $offsetX="-50", $offsetY="20")

      UpdateLayoutConfig($c4ShapeInRow="3", $c4BoundaryInRow="1")
``` -->
