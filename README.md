# DevOps_02_GitOps
Repozitoř k 2. lekci

# DevOps Úkol 02: GitHub Actions & Git Flow

Tento repozitář obsahuje řešení domácího úkolu zaměřeného na GitOps, správu verzí pomocí Git Flow a automatizaci pomocí GitHub Actions v prostředí RHEL 10 (spravovaném přes MobaXTerm).

## 🎯 Cíle projektu

* **Úvodní Workflow Pipeline:** Vytvoření základní automatizované pipeline přímo v UI rozhraní GitHubu.
* **Git Flow a Pull Request:** Vytvoření samostatné feature větve v prostředí RHEL 10, lokální úprava YAML konfigurace a její bezpečné sloučení přes Pull Request po úspěšném doběhu kontrol.
* **GitHub Marketplace:** Integrace hotové akce z Marketplace pro nahrávání výsledných balíčků (Artifacts) do repozitáře.

## 📂 Struktura projektu

* **`.github/workflows/blank.yml`** – Konfigurační soubor GitHub Actions definující kroky pipeline a integraci z Marketplace.
* **`README.md`** – Dokumentace projektu s retrospektivním záznamem.

---

## ⚠️ Retrospektiva (Vazba na Úkol 5)

Při implementaci tohoto úkolu došlo k odchylce od původního zadání lektora:
* **Stav v Úkolu 2:** Byla úspěšně vybudována a otestována GitOps infrastruktura (vytvoření větve, push, Pull Request, merge a upload artifactu). Samotná pipeline však obsahovala pouze demonstrativní textové příkazy `echo` a jako balíček z Marketplace nahrávala statický soubor `README.md`. Chyběla implementace lektorem sdíleného Python skriptu pro matematické operace a jeho testování.
* **Náprava v Úkolu 5:** Úkol 5 plně navazuje na tuto připravenou GitOps kostru, odchylku napravuje a doplňuje do pipeline konfiguraci Python prostředí, spouštění reálné matematické logiky, automatické testy a nahrávání skutečných aplikačních výstupů.