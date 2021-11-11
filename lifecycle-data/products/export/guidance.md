---
title: Panduan ekspor data siklus hidup
description: Panduan informasi siklus hidup produk ekspor
ms.date: 12/16/2020
layout: ContentPage
ms.openlocfilehash: 5e9dddbff5fac32e6d3cf8ef0943151d2dfe5e35
ms.sourcegitcommit: 6ea3221fd5475440480515f04f33988656d71748
ms.translationtype: HT
ms.contentlocale: id-ID
ms.lasthandoff: 11/02/2021
ms.locfileid: "3546859"
---
# <a name="lifecycle-data-export-guidance"></a>Panduan ekspor data siklus hidup
Dokumen ini menjelaskan cara menggunakan file ekspor produk.

## <a name="query-information"></a>Informasi Kueri
Dalam dokumen Excel, terdapat bidang untuk membantu mengidentifikasi data yang terisi dalam tabel produk.

### <a name="end-of-support"></a>Akhir Dukungan
Nilai akhir dukungan akan memfilter produk dengan tanggal akhir dukungan produk atau tanggal akhir rilisnya.

Nilai yang mungkin: Semua (tidak ada filter yang diterapkan), Tahun, dan Rentang.

### <a name="family"></a>Family
Nilai keluarga memfilter produk menurut tingkat induknya dalam hierarki yang dikenal sebagai keluarga.

Nilai yang mungkin: Semua (tidak ada filter yang diterapkan), Nama Keluarga

### <a name="group"></a>Group
Nilai grup memfilter produk di dalam tingkat induknya (keluarga) ke grup tertentu.

Nilai yang mungkin: Semua (tidak ada filter yang diterapkan), Nama Grup

## <a name="table-columns"></a>Kolom Tabel
Tabel produk terdiri dari kolom yang menetapkan tanggal produk, edisi, rilis, dan dukungan yang terkait.

> [!NOTE]
> Akan ada baris untuk setiap kombinasi produk, edisi, dan rilis.

### <a name="product"></a>Produk
Nama produk.

### <a name="edition"></a>Edisi
Kolom edisi akan terisi ketika produk berisi edisi. Jika tidak ada edisi produk, bidang ini akan kosong.

### <a name="release"></a>Rilis
Kolom rilis akan terisi ketika produk berisi beberapa rilis.
Ketika produk hanya memiliki satu rilis, bidang ini akan kosong.

### <a name="support-policy"></a>Kebijakan Dukungan
Bidang ini menentukan kebijakan dukungan yang dipatuhi oleh produk.

Nilai yang mungkin: [Tetap](/lifecycle/policies/fixed), [Modern](/lifecycle/policies/modern), Komponen

### <a name="start-date"></a>Tanggal Mulai
Tanggal dukungan dimulai untuk produk.

### <a name="mainstream-date"></a>Tanggal Mainstream
Ketika Kebijakan Dukungan **Tetap** atau **Komponen**, ini adalah tanggal berakhir mainstream produk.
  
Ketika Kebijakan Dukungan **Modern**, ini akan kosong.

### <a name="extended-end-date"></a>Tanggal Akhir Diperpanjang
Ketika Kebijakan Dukungan **Tetap** atau **Komponen**, ini adalah tanggal akhir yang diperpanjang untuk produk.

Ketika Kebijakan Dukungan **Modern**, ini akan kosong.

### <a name="retirement-date"></a>Tanggal Pensiun
Ketika Kebijakan Dukungan **Tetap** atau **Komponen**, ini akan kosong.

Ketika Kebijakan Dukungan **Modern**, ini akan menjadi tanggal pensiun produk.

### <a name="release-start-date"></a>Tanggal Mulai Rilis
Tanggal dukungan dimulai untuk rilis. Ketika produk hanya memiliki satu rilis, bidang ini akan kosong.
 
### <a name="release-end-date"></a>Tanggal Berakhir Rilis
Tanggal dukungan berakhir untuk rilis.
Ketika produk hanya memiliki satu rilis, bidang ini akan kosong.

### <a name="docs-url"></a>Docs Url
Url ke dokumentasi yang diperluas.
