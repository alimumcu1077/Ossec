# Ossec
#Ossec Otamatik Agent Yükleme Scripti 
Ossec Kurulumunu Çok fazla Client'in olduğu sistemlerde  otamatik gerçekleştirebilmek için bu scripti kullanabilirsiniz.
Scrpiti çalıştıran kullanıcısının hem ossec sunucuda hem de client'larda sudo yetkisi olmalıdır.(Scritpi root ile çalıştırmayınız)
Güvenlik prosedüerlernde root genelde ssh erişimine kapalı olduğu için scritpi sudo yetkisinde bir kullanıcının çalıştıracağı varsayılmıştır.

#Script Çalıştırıldığında interaktif olarak kuurlum işlemlerinde kullanıılacak kullanıcı adını ve parola bilgilerini sorar ve daha sonra #clients dosyasından satır satır client'ların ip(internet protokol) adreslerini çekerek for döngüsü ile ossec sunucusunda ve agent #
#kurulacak olan client sunucularda gerekli işlemleri gerçekleştirir.



