---
templateKey: index-page
title: World's First Strong Relativistic Linearizable Database
image: /img/golden-gate-bridge-1596161_1920.jpg
heading: Non-blocking reads in the past
subheading: In-Memory Append-Log Post-Quantum Immutable Cache Storage
mainpitch:
  title: Why EinsteinDB
  description: >-
    EinsteinDB is an opinionated scalable, multi-version, globally-distributed,
    and synchronously-replicated in-memory database. 
description: >-
  EinsteinDB supports non-blocking reads in the past, lock-free read-only
  transactions, and atomic schema changes. In order to support
  externally-consistent distributed transactions at global scale, it uses a
  novel CausetNet API that exposes and exploits clock uncertainty.
intro:
  blurbs:
    - image: /img/coffee.png
      text: >
        We sell green and roasted coffee beans that are sourced directly from
        independent farmers and farm cooperatives. We’re proud to offer a
        variety of coffee beans grown with great care for the environment and
        local communities. Check our post or contact us directly for current
        availability.
    - image: /img/coffee-gear.png
      text: >
        We offer a small, but carefully curated selection of brewing gear and
        tools for every taste and experience level. No matter if you roast your
        own beans or just bought your first french press, you’ll find a gadget
        to fall in love with in our shop.
    - image: /img/tutorials.png
      text: >
        Love a great cup of coffee, but never knew how to make one? Bought a
        fancy new Chemex but have no clue how to use it? Don't worry, we’re here
        to help. You can schedule a custom 1-on-1 consultation with our baristas
        to learn anything you want to know about coffee roasting and brewing.
        Email us or call the store for details.
    - image: /img/meeting-space.png
      text: >
        We believe that good coffee has the power to bring people together.
        That’s why we decided to turn a corner of our shop into a cozy meeting
        space where you can hang out with fellow coffee lovers and learn about
        coffee making techniques. All of the artwork on display there is for
        sale. The full price you pay goes to the artist.
  heading: What we offer
  description: >-
    EinsteinDB solves the problem of geo-replication, append-only, and strong
    causal consistency by ditching wall-clock calculations.  EinsteinDB achieves
    convergent causal consistency by applying a partial order consensus to an
    eventually-consistent data store.
main:
  heading: A solution to the problem of overwritten histories
  description: >-
    We have integrated production-ready eventually consistent data stores
    through metadata-transaction bartering and polling via Postgres, RocksDB,
    and Cassandra with explicit causal consistency traces embedded as optimized
    write tables through MariaDB/MySQL/SQLite.
  image1:
    alt: A close-up of a paper filter filled with ground coffee
    image: /img/products-grid3.jpg
  image2:
    alt: A green cup of a coffee on a wooden table
    image: /img/products-grid2.jpg
  image3:
    alt: Coffee beans
    image: /img/products-grid1.jpg
---

