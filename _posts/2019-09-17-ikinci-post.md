---
layout: post
title:  ".NET error"
author: İrem Çelik
---

**1.	'/' Uygulamasında Sunucu Hatası. Kaynak bulunamadı. Açıklama: HTTP 404. Aradığınız kaynak (veya bağımlı olduklarından biri) kaldırılmış, adı değiştirilmiş veya geçici olarak kullanılamaz durumda olabilir. Lütfen aşağıdaki URL'yi gözden geçirin ve doğru yazıldığından emin olun.   İstenen URL: /  Sürüm Bilgisi: Microsoft .NET Framework Sürümü:4.0.30319; ASP.NET Sürümü:4.7.3429.0**

Çözüm :
           routes.MapRoute(
                name: "Sayfa",
                url: "Sayfa/Index/{id}",
                defaults: new { id = UrlParameter.Optional },
                namespaces: new[] { "Emlak_MVC4.Controllers" }            
            );
