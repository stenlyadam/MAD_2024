# Chapter 1. Setup Environment React Native

## Mobile Application Development, Semester 2, Tahun Akademik 2023/2024

## #Exercise 01

Pada Chapter ini kita akan melakukan instalasi [react native]. Pada latihan ini anda diminta untuk menginstall React Native CLI (Bukan Expo) dilaptop/PC masing-masing, dimana langkah-langkahnya adalah sebagai berikut:

- Install Node, JDK
- Install Android Studio & SDK
- Konfigurasi tambahan (khusus yang menggunakan processor [AMD])
- Configure the ANDROID_HOME environment variable & Add platform-tools to Path
- Install Android Emulator (optional - bisa dilewati jika anda ingin menjalankan aplikasi langsung dari hp. Baca dokumentasi [running on device])
- Create project React Native menggunakan npx
- Run project

## Status Instalasi

| Langkah-langkah                           | Status | Versi         |
| ----------------------------------------- | ------ | ------------- |
| Instalasi Node                            |  done  |   20.11.0     |
| Instalasi JDK                             |  done  |openjdk 17.0.8 2023-07-18|
| Android Studio                            |  done  |  2023.1.1     | 
| SDK                                       |  done  |     34        |
| ANDROID_HOME & Add platform-tools to Path |  done  | -             |
| Android Emulator (opt)                    |  done  |pixel 3a API 33|
| Create Project RN using npx               |  done  | -             |
| Run Project on Emulator / Device          |  done  | -             |

Silahkan update status instalasi anda, apabila sudah terinstall silahkan isi versinya:
untuk mengetahui versi node ketik dari cmd (node -v) untuk mengetahui versi JDK ketik dari cmd (java --version).
Sebagai contoh :

| Langkah-langkah                           | Status | Versi                       |
| ----------------------------------------- | ------ | --------------------------- |
| Node                                      | Done   | 12.13.1                     |
| JDK                                       | Done   | [openjdk 11.0.5 2019-10-15] |
| Android Studio                            | Done   | 4.0                         |
| SDK                                       | Done   | 29                          |
| ANDROID_HOME & Add platform-tools to Path | Done   | -                           |
| Android Emulator (opt)                    | Done   | pixel 2 xl api 29           |
| Create Project RN using npx               | Done   | -                           |
| Run Project on Emulator / Device          | Done   | -                           |

## Langkah-langkah Pengumpulan Latihan

- Fork project github ini. Ada terdapat 3 branch yaitu: master, parallel-a, parallel-b, parallel-c
- Dari local laptop/PC anda buat branch baru dengan nama sesuai dengan nama diikuti oleh nim. contoh: johndoe_105022110001
- Buat file baru sama seperti nama anda dengan format .md. contoh: johndoe_105022110001.md
- Edit file tersebut dengan mengisi status instalasi pada tabel yang sudah disediakan.
- git add dan commit dengan commit message "adding johndoe_105022110001.md"
- lakukan pull request ke dalam branch sesuai dengan parallel kelas anda. (Bukan Branch Master)

  [react native]: https://reactnative.dev/docs/environment-setup
  [running on device]: https://reactnative.dev/docs/running-on-device
  [amd]: https://android-developers.googleblog.com/2018/07/android-emulator-amd-processor-hyper-v.html
  [openjdk 11.0.5 2019-10-15]: https://docs.aws.amazon.com/corretto/latest/corretto-11-ug/downloads-list.html
