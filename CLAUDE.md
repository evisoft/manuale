# Manuale - Reguli de proiect

## Regula principală: Scanare înainte de commit

**Înainte de fiecare commit**, trebuie să:

1. **Scanezi tot conținutul** directorului pentru fișiere `.pdf` și `.epub` noi sau modificate
2. **Actualizezi `README.md`** cu orice manual nou descoperit:
   - Adaugă o intrare în tabelul clasei corespunzătoare (creează secțiunea dacă nu există)
   - Include linkuri relative spre PDF și EPUB (cu URL encoding pentru spații: `%20`)
   - Adaugă o scurtă descriere a manualului
3. **Verifică linkurile** existente — dacă un fișier a fost mutat sau șters, actualizează sau elimină intrarea

## Structura directorului

```
/
├── README.md           # Index cu linkuri și descrieri
├── CLAUDE.md           # Reguli de proiect (acest fișier)
├── 6/                  # Clasa a VI-a
│   └── Istoria Românilor/
│       ├── *.pdf
│       └── *.epub
├── 7/                  # Clasa a VII-a (viitor)
├── 8/                  # Clasa a VIII-a (viitor)
└── ...
```

## Convenții

- Directoarele sunt organizate pe clase (6, 7, 8, etc.)
- Fiecare manual are propriul subdirector cu numele materiei
- Fișierele sunt în format PDF și EPUB
- README.md conține un tabel per clasă cu coloane: Manual (nume + descriere), PDF, EPUB
