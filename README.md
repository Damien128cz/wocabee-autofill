# wocabee-autofill
Automatický skript pro WocaBee funkční 
Tento JavaScriptový skript automaticky zobrazuje správnou odpověď při procvičování ve WocaBee. Využívá slovník a kontroluje otázky každé 2 sekundy. Funguje z češtiny do němčiny i naopak.

---

## ✨ Jak to použít

### ✅ 1. Otevři procvičování ve WocaBee

Například:procvičování,test a balíčky

### ✅ 2. Otevři konzoli

- Na Windows: `F12` nebo `Ctrl + Shift + I`
- Vpravo nahoře klikni na záložku **Console**

### ✅ 3. Vlož skript

Zkopíruj celý obsah souboru `script.js` a vlož ho do konzole.

### ✅ 4. Hotovo!

Správná odpověď se zobrazí v rohu obrazovky jako nápověda. ✅

---

## 🛠️ Co skript dělá?

- Vyhledá otázku na stránce (např. „sto“)
- Najde správný překlad ve slovníku
- Zobrazí odpověď ve vyskakovacím boxu
- Každé 2 sekundy kontroluje novou otázku

---

## 📚 Slovní zásoba

Slovník je obousměrný (němčina,ajina,francouština a prostě jaký koliv jazyk <-> čeština). Pokud chceš přidat další slovíčka, otevři `script.js` a uprav objekt `slovicka`:

```js
const slovicka = {
  "hundert": "sto",
  "sto": "hundert",
  ...
};
