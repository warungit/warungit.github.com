---
layout: page
title: "Cara Posting"
description: "Cara posting di warunGIT"
---
{% include JB/setup %}

Cara posting di warunGIT :

- rake post title="Judul Posting Kamu" (Contoh: Jual Ayam Kampungs)
- Liat di folder '/_posts', terus buka file : '2015-07-15-Jual-Ayam-Kampungs.md' (YYYY-MM-DD -> Format Waktu)
- Pasti ada kode gini :

<code>
layout: post <br />
title: "Jual Ayam Kampungs" <br />
description: "" <br />
category: "" <br />
tags: []
</code>

Ubah jadi gini : <br />
<code>
layout: post <br />
title: "Dijual Stiker Ubuntu!" <br />
description: "Deskripsi (Untuk di Meta Description)" <br />
category: hewan, kamu (Format : jenis barang yang kamu jual, nama kamu) <br />
tags: [toko] (Harus toko ya :)) <br />

(Deskripsi Konten Kamu. format :)<br />
<img src="url_gambar_kamu" alt='deskripsi foto' /><br />
Judul Yang kamu jual, ex: Dijual Stiker Ubuntu!<br />
Harga yang kamu jual, ex: Rp. 5000 (Bisa Nego)<br />
Kontak yang bisa dihubungi, ex: Contact info : +6287 808 355 629 (Whatsapp)<br />
Nama Penjual, ex: Penjual : FarizMedia
</code>

Dimohon untuk mengikuti Ini ya :) Terima Kasih. <br />
Happy Commit!