semver (Sematic Versioning)

x.y.z

x = MAJOR (API publik)

y = MINOR (Fitur)

z = PATCH (perbaikan bug)

jika versi minor dinaikan versi patch dijadikan 0;
jika versi major dinaikkan versi minor dan patch dijadikan 0;
Versi prarilis BISA ditulis dengan menambahkan tanda hubung dan rangkaian pengenal dengan pemisah titik tepat setelah versi patch. Pengenal ini HARUS terdiri dari hanya alfanumerik ASCII dan tanda hubung [0-9A-Za-z]. Pengenal TIDAK BOLEH kosong. Pengenal numerik TIDAK BOLEH didahului angka 0. Versi prarilis memiliki presendens yang lebih rendah dibandingkan dengan versi normal yang terkait. Versi prarilis dianggap tidak stabil dan mungkin tidak memuaskan persyaratan kompatibilitas yang dimaksudkan seperti yang ditunjukkan oleh versi normal yang terkait. Contoh: 1.0.0-alpha, 1.0.0-alpha.1, 1.0.0-0.3.7, 1.0.0-x.7.z.92, 1.0.0-x-y-z.--.

Build metadata BISA ditulis didahului dengan tanda tambah dan rangkaian pengenal dengan pemisah titik setelah versi patch atau prarilis. Build metadata HARUS ditulis dengan huruf ASCII alfanumerik dan tanda hubung [0-9A-Za-z]. Pengenal ini HARUS terdiri dari hanya alfanumerik ASCII dan tanda hubung [0-9A-Za-z]. Pengenal TIDAK BOLEH kosong. Build metadata HARUS diabaikan saat menentukan presedens versi. Dengan begitu, dua versi yang berbeda hanya di build metadata-nya memiliki preseden yang sama. Contoh: 1.0.0-alpha+001, 1.0.0+20130313144700, 1.0.0-beta+exp.sha.5114f85, 1.0.0+21AF26D3----117B344092BD.

Source : [semver](https://semver.org/lang/id/)
