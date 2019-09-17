---
layout: post
title:  "Servis Başlatma Hatası(Failed to start LSB)"
author: İrem Çelik
---

**Aşağıdaki resimde görüldüğü üzere snort kurulum sırasında servis oluşturmadan kaynaklanan bir hata verdi. **	
![Octocat](https://user-images.githubusercontent.com/15799224/65027886-6b6b4200-d93b-11e9-8822-798c2d66a943.png)
Bunun için çözümde önerilen yeni servis oluşturma metodunu uyguladım ve başarılı bir şekilde snort servisleri çalışmaya başladı. Çözümde önerilen komutlar:
•	Systemctl enable snort.service
•	Systemctl start snort.service
