---
layout : post
type   : 
title  : LiteGapps Best Custom Gapps Android
date   : 2023-12-23
slug   : litegapps
categories: [Gapps]
tags      : [magisk, gapps, ksu]
keywords  : [magisk module, litegapps, lite gapps, Kernelsu]
author : wahyu6070
opengraph:
toc    :
excerpt:
---

Google Apps adalah kumpulan aplikasi google yang cukup penting dalam kehidupan sehari-hari, misalnya setiap hari kita menggunakan aplikasi seperti youtube untuk memutar video, google translate untuk menerjemahkan bahasa, google chrome untuk peramban web browsing. jadi google apps ini penting untuk terinstall di dalam smartphone kita khususnya bagi pengguna android.

Pada dasarnya Google Apps sudah terpasang di dalam stock rom (rom bawaan vendor) namun ada juga beberapa yang belum terpasang google apps karena alasan kebijakan atau lainya misalnya **MIUI CHINA** dan beberapa custom rom seperti lineage os atau lainya.

jadi kali ini saya akan bahas cusrom gapps (google apps) yang cukup populer dikalangan komunitas android yaitu litegapps, mari kita ulas tentang proyek yang menarik ini.

litegapps adalah custom gapps proyek sumber terbuka yang di kembangkan oleh anggota sernior xda-developer @wahyu6070,proyek ini befokus pada minimal, efesiensi dan lengkap dalam berbagai penanganan kasus pengguna google apps. litegapps memiliki mode installasi yang unik yaitu ``systemless`` dan ``non systemless``, mari kita bahas lebih lanjut tentang kedua mode ini :

### systemless

yaitu mode installasi yang melakukan penginstallan di partisi android secara palsu (file tidak terpasang secara asli ke dalam partisi) itu menggunakan sistem installasi **magisk module** atau **KSU module** yang bahkan bisa melakukan modifikasi secara palsu kedalam partisi read only.

### non systemless

yaitu mode installasi normal/lama yang melakukan installasi file secara langsung kedalam partisi android (file terpasang secara asli), jadi untuk menggunakan mode ini partisi android harus bisa melakukan read/write ke dalam partisi agar bisa melakukan modifikasi atau menginstall file google apps.

