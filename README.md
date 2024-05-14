# Reflection
## Reflection on Hello Minikube
1. Ketika saya membuka aplikasi beberapa kali, terlihat pada log request GET terjadi. Di bawah ini terdapat screenshot tampilan logs.
![Logs](img/Logs.png)
2. Saat mengeksekusi perintah `kubectl get`, option `-n` bertujuan untuk menentukan namespace yang ingin ditampilkan informasinya. Namespace pada Kubernetes bertujuan untuk mempartisi resources menjadi beberapa cluster. Tanpa option `-n`, akan muncul informasi dari namespace default. Output tidak memberikan list pods/services yang dibuat karena hal-hal tersebut berada pada namespace `default`.
