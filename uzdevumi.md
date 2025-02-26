## Darba veikšana

> Ja nepieciešams atsvaidzināt lietas, skatīt failu README.md

1) Nokopēt šo repozitoriju savā GitHub kontā.
2) Noklonēt lokāli PyCharm vidē.
3) Izveidot jaunu zaru ar nosaukumu `2025.03.03`.
4) Katram uzdevumam izveidojam savu failu ar nosaukumu `uzdevums_<NR>.py`, piemēram, `uzdevums_1.py`.
5) Var kommitot katru failu atsevišķi, var visus kopā.
6) Pēc uzdevumu veikšanas nosūtām izmaiņas uz GitHub.
7) Izveidojam pull request ar nosaukumu `Vards Uzvards 2025.03.03`.

Par veiktām darbībām un izpildītiem 2 uzdevumiem - **4 balles**.

Par katru nākamo izpildīto uzdevumu - **+1 balle**.

## Uzdevumi

1) Izvadīt uz ekrāna skaitļu 4 un 12 dalījumu.
2) Definēt divus mainīgos a = 6, b = 8 un izvadīt atlikumu b dalot ar a.
3) Aprēķināt riņķa līnijas garumu, ja tiek ievadīts tās diametrs.
4) Izvadīt uz ekrāna divu no lietotāja saņemto skaitļu:
   - summu
   - reizinājumu
   - dalījumu
5) Izvadīt uz ekrāna vai ievadītais skaitlis ir pāra skaitlis.
6) Izvadīt uz ekrāna lietotāja ievadītā teksta garumu.
7) Lietotāja ievadītam skaitlim, kas reprezentē diennakts stundu (0-23) izvadīt stundai atbilstošu sveicienu. No 6 līdz 11 - "Labrīt!", no 12 līdz 16 - "Labdien!", no 17 līdz 22 - "Labvakar!", no 23 līdz 5 - "Laiks gulēt!".
8) Izlabot šo kodu, lai tas izvada uz ekrāna Tavu vārdu:
```python
def division():
    a = 10
    b = 7
    return (a + b) % 4

result = division()

if result == 1:
    print("Jānis")
elif result == 2:
    print("Kristers")
elif result == 3:
    print("Markuss")
```