# NotificationAction Object

* `type</ 0>  String - Tipe tindakan, bisa dengan <code>button</ 0> .</li>
<li><code>text` String (opsional) - Label yang diberikan untuk aksi.

## Platform / Action Support

Penggunaan ` teks </ 0></th>
  <th>Default <code> teks </ 0></th>
  <th>Keterbatasan</th>
</tr>
</thead>
<tbody>
<tr>
  <td><code>tombol`</td> 

</tr> </tbody> </table> 



### Dukungan tombol pada macos

Agar tombol notifikasi tambahan dapat berfungsi di macOS, aplikasi Anda harus memenuhi kriteria berikut.

* Aplikasi telah ditandatangani
* Aplikasi mempunyai `NSUserNotificationAlertStyle` set ke `alert` di bagian `info.plist`.

Jika salah satu dari persyaratan tidak terpenuhi maka tombol tidak akan muncul.
