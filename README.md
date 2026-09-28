```dart
void main() {
  String namaHewan = 'Cahyo';
  String makanan = 'Omnivora';
  int umur = 20;
  double berat = 65.5;
  bool hidup = true;

  umur = 21;

  print(namaHewan);
  print(makanan);
  print(umur);
  print(berat);
  print(hidup);

  String? keterangan;
  keterangan = null;

  print(keterangan ?? 'Belum ada keterangan');

  final String kode = 'CHY20';
  final DateTime tanggal = DateTime.now();

  print(kode);
  print(tanggal);

  const double tinggiMaksimal = 100.0;
  const String satuan = 'cm';

  print(tinggiMaksimal);
  print(satuan);

  List<String> makananFavorit = [
    'Ikan',
    'Ayam',
    'Telur',
    'Nasi',
    'Sayur'
  ];

  print(makananFavorit);
  print(makananFavorit[0]);
  print(makananFavorit[1]);
  print(makananFavorit[2]);
  print(makananFavorit[3]);
  print(makananFavorit[4]);

  print('Cahyo suka makan ' + makananFavorit[0]);
}
```
