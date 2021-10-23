---
title: "Contact"
permalink: "/contact.html"
---

<form action="https://formspree.io/{{site.email}}" method="POST">    
<p class="mb-4">Anda dapat mengirimkan pesan kepada redaksi {{site.name}} melalui kotak pesan berikut. Kami akan membalas sesegera mungkin!</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="Nama*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="Alamat E-mail*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="Pesan*" required></textarea>    
<input class="btn btn-success" type="submit" value="Kirim">
</form>
