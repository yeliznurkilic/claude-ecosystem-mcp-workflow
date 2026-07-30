# 🤖 Claude Ekosistemi: Skill'ler, MCP & Workflow Tasarımları

Bu proje, **Anthropic Claude Ekosistemi**'nin (Skill'ler, Model Context Protocol - MCP, Advanced Prompting ve Workflow'lar) kurumsal süreçlere entegrasyonunu ve canlı test sonuçlarını içerir.

---

## 🎯 Öne Çıkanlar

* **Prompt Testleri:** Zero-Shot, Few-Shot ve CoT + XML teknikleri aynı kriz senaryosu üzerinde karşılaştırılmıştır.
* **MCP Entegrasyonları:** PostgreSQL, GitHub ve File System MCP mimarileri tasarlanmıştır.
* **Uçtan Uca Workflows:**
  1. **Yazılım Hata Analizi & PR İnceleme Akışı** (GitHub MCP + Python Skill)
  2. **Müşteri Kriz Yönetimi Akışı** (PostgreSQL MCP + CoT Risk Analitiği)

---

## 📊 İş Akışı Şeması

![Workflow Diyagramı](./workflows/mermaid-diagram.png)

---

## 🧪 Canlı Test Çıktıları

* **Düz İstem (Zero-Shot):** ![Zero-Shot](./prompts/Düz%20İstem%20(Zero-Shot%20Direct%20Prompting)%20.png)
* **Örnekli İstem (Few-Shot):** ![Few-Shot](./prompts/Örnekli%20İstem%20(Few-Shot%20Prompting)%20.png)
* **XML + CoT (Adım Adım Düşünme):**  
  ![XML-CoT 1](./prompts/1Structured%20XML%20Etiketleme%20ve%20Chain-of-Thought%20(CoT)%20.png)  
  ![XML-CoT 2](./prompts/2Structured%20XML%20Etiketleme%20ve%20Chain-of-Thought%20(CoT)%20.png)

---

## 📄 Belgeler

* 📑 [Teknik Rapor (PDF)](./docs/Claude_Ekosistemi_Teknik_Raporu.pdf)
* 📊 [Sunum Slaytları (PPTX)](./docs/Claude%20Ekosistemi.pptx)

---
**Hazırlayan:** Yeliz Nur Kılıç | **Görev:** DDYO Staj Araştırma Görevi (Görev 07)
