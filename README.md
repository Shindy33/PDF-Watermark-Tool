# 📄 PDF Watermark Tool

Jednoduchá webová aplikace vytvořená ve Flasku pro přidávání textových vodoznaků do PDF dokumentů.

Projekt vznikl jako školní úkol zaměřený na práci s PDF dokumenty a vytvoření webové aplikace s grafickým rozhraním.

---

## Funkce

- Přidání vlastního textového vodoznaku do PDF
- Nastavení velikosti textu
- Výběr barvy vodoznaku
- Nastavení průhlednosti
- Výběr umístění vodoznaku (9 pozic)
- Automatické vytvoření nového PDF souboru
- Stažení upraveného dokumentu přímo z webové aplikace
- Kontrola, že uživatel nahrál PDF soubor

---

## Použité technologie

- Python 3
- Flask
- PyPDF2
- ReportLab
- HTML
- CSS

---

## Instalace

### 1. Naklonování repozitáře

```bash
git clone https://github.com/Shindy33/PDF-Watermark-Tool
cd PDF-Watermark-Tool
```

### 2. Instalace knihoven

```bash
pip install -r requirements.txt
```

Případně:

```bash
pip install flask PyPDF2 reportlab
```

### 3. Spuštění aplikace

```bash
python app.py
```

Poté otevřete prohlížeč a přejděte na adresu:

```
http://127.0.0.1:5000
```

---

## Použití

1. Vyberte PDF soubor.
2. Zadejte text vodoznaku.
3. Nastavte velikost textu.
4. Vyberte barvu.
5. Nastavte průhlednost.
6. Vyberte umístění vodoznaku.
7. Klikněte na tlačítko **Přidat vodoznak**.
8. Upravený PDF dokument se automaticky stáhne.

---

## Struktura projektu

```
PDF-Watermark-Tool/
│
├── app.py
├── requirements.txt
│
├── static/
│   └── style.css
│
├── templates/
│   └── index.html
│
├── uploads/
└── outputs/
```

## Autor

Michal Šindelář

Projekt vytvořen jako školní práce.
