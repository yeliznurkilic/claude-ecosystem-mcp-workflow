# 🤖 Claude Ekosistemi: Skill'ler, MCP & Kurumsal Workflow Tasarımları

Bu proje, **Anthropic Claude LLM Ekosistemi**'nin sunduğu temel mimari bileşenlerin (Skill'ler, Model Context Protocol - MCP, Advanced Prompt Engineering ve Pipeline Tasarımları) kurumsal süreçlere entegrasyonunu inceleyen ve uygulamalı prototipler sunan bir Ar-Ge çalışmasıdır.

---

## 📂 Depo Dosya Yapısı

* **`docs/`**: Teknik araştırma raporu (`.pdf`) ve sunum slaytları (`.pptx`).
* **`prompts/`**: Canlı olarak test edilen istem tekniklerine ait ekran çıktıları (`.png`).
* **`workflows/`**: Müşteri Kriz Yönetimi İş Akışı'na ait Mermaid akış diyagramı (`.png`).

---

## 🎯 Araştırma Kapsamı ve Öne Çıkanlar

* **Prompt Teknikleri Karşılaştırmalı Analizi:** Zero-Shot, Few-Shot ve CoT + XML teknikleri aynı kriz senaryosu (SLA ihlali, 50.000$ ciro riski ve dava tehdidi) üzerinde canlı olarak test edilmiş ve analitik skorlama sunulmuştur.
* **Kurumsal MCP Entegrasyonları:** PostgreSQL (Read-Only), GitHub ve File System MCP sunucu mimarileri kurgulanmıştır.
* **Uçtan Uca Workflows (İş Akışları):**
  1. **Yazılım Hata Analizi ve PR İnceleme Akışı:** GitHub MCP + Python Execution Skill entegrasyonu.
  2. **Müşteri Şikayeti ve Kriz Yönetimi Akışı:** PostgreSQL MCP + Structured XML (CoT) + Otomatik PDF Raporlama Pipeline'ı.

---

## 📊 İş Akışı Şeması (Workflow 2)

![Müşteri Kriz Yönetimi Akış Şeması](./workflows/mermaid-diagram.png)

---

## 🧪 Canlı Test İstemleri ve Çıktı Görselleri

### 1. Düz İstem (Zero-Shot Direct Prompting)
![Düz İstem Çıktısı](./prompts/Düz%20İstem%20(Zero-Shot%20Direct%20Prompting)%20.png)

### 2. Örnekli İstem (Few-Shot Prompting)
![Örnekli İstem Çıktısı](./prompts/Örnekli%20İstem%20(Few-Shot%20Prompting)%20.png)

### 3. Structured XML Etiketleme ve Chain-of-Thought (CoT)
![XML ve CoT Çıktısı 1](./prompts/1Structured%20XML%20Etiketleme%20ve%20Chain-of-Thought%20(CoT)%20.png)
![XML ve CoT Çıktısı 2](./prompts/2Structured%20XML%20Etiketleme%20ve%20Chain-of-Thought%20(CoT)%20.png)

---

## 📄 Proje Belgeleri

* 📑 [Teknik Rapor (PDF)](./docs/Claude_Ekosistemi_Teknik_Raporu.pdf)
* 📊 [Sunum Slaytları (PPTX)](./docs/Claude%20Ekosistemi.pptx)

---
**Hazırlayan:** Yeliz Nur Kılıç  
**Görev:** DDYO Staj Teknik Araştırma Görevi (Görev 07)  
**Tarih:** 30.07.2026
