# BMI Calculator — React frontend

BMI Calculator ni urubuga rw'imbere (frontend gusa) rufasha kubara BMI, kureba ibisubizo no kubika amateka kuri mudasobwa ukoresha.

## Ikoresha
- React.js + Vite
- CSS
- Recharts (igishushanyo cy'impinduka)
- localStorage (kubika amakuru muri browser)

> Iyi ni frontend gusa. Nta backend cyangwa MySQL birimo. Konti n'amateka bibikwa kuri browser ukoresha, bityo ntibihuzwa hagati y'ibikoresho bitandukanye.

## Gutangiza
1. Shyiramo Node.js.
2. Fungura terminal muri iyi folder.
3. Koresha:
   ```bash
   npm install
   npm run dev
   ```
4. Fungura URL Vite iguha (akenshi `http://localhost:5173`).

## Kubaka no kugerageza
```bash
npm run build
npm run preview
```

## Ibirimo
- Kubara BMI ukoresheje ibiro (kg) n'uburebure (cm).
- Ibisubizo n'ibyiciro by'abantu bakuru.
- Amateka abikwa muri localStorage.
- Dashboard n'igishushanyo cy'impinduka.
- Guhindura ururimi hagati y'Ikinyarwanda n'Icyongereza.
- Gukuramo raporo ya BMI mu nyandiko ya CSV.
- Guhanagura amateka.

## Icyitonderwa ku buzima
BMI ni igipimo rusange, si isuzuma ry'indwara. Ibyiciro biri muri iyi porogaramu bigenewe abantu bakuru bafite imyaka 20 kuzamura. Ku bana n'ingimbi, hakenerwa uburyo bwihariye bushingiye ku myaka n'igitsina.

## Responsive design (phones, tablets and computers)

CSS yateguwe kugira ngo page, menu, profile sidebar, forms, BMI result, dashboard, history table, guide cards na footer bihindure imiterere bitewe n'ubugari bwa screen. Ku bikoresho bito, menu iba mobile menu; calculator ihinduka column imwe; history table ishobora kuzengurutswa iburyo n'ibumoso aho gucika.

### Uburyo bworoshye bwo kuyitestinga muri Chrome

1. Tangiza project ukoresheje `npm install` na `npm run dev`.
2. Fungura `http://localhost:5173` muri Google Chrome.
3. Kanda `F12` (cyangwa `Ctrl + Shift + I`), hanyuma ukande `Ctrl + Shift + M` kugira ngo ufungure Device Toolbar.
4. Hitamo ibikoresho bitandukanye (urugero: iPhone, Pixel, iPad) cyangwa uhindure ubugari bwa screen ukoresheje custom size.
5. Gerageza ubu bugari bukurikira:

| Igikoresho cyo kugerageza | Ubugari bwa screen | Ibyo ugomba kureba |
|---|---:|---|
| Terefone nto | 320–360 px | Nta horizontal page scroll; amagambo na buttons ntibicike |
| Smartphone isanzwe | 375–430 px | Menu ya mobile irafunguka; calculator iba column imwe |
| Tablet | 600–850 px | Sidebar na cards birahinduka neza; nta bintu bisunikana |
| Laptop | 1024–1366 px | Navigation na calculator bigaragara neza |
| Desktop nini | 1440–1920 px | Page iba hagati kandi ikoresha umwanya neza |

### Checklist yo kugerageza features zose

- [ ] Kanda buri link yo muri navigation; urebe ko Home, Kubara BMI, Imbonerahamwe, Amateka na Umwirondoro bifunguka.
- [ ] Kuri terefone, kanda menu icon urebe ko navigation ifunguka kandi buri link ikora.
- [ ] Hindura ururimi hagati ya Kinyarwanda n'Icyongereza.
- [ ] Kuri Umwirondoro, gerageza kubika utujuje ibisabwa; urebe ko ubutumwa bwo kuzuza umwirondoro bugaragara. Hanyuma wuzuze amazina na email yemewe ubike.
- [ ] Jya kuri Kubara BMI, andika ibiro, uburebure n'imyaka, ukande Bara BMI; reba ko igisubizo kigaragara neza kuri screen nto n'inini.
- [ ] Kanda Bika kugira ngo ubike igisubizo; reba Amateka na Dashboard.
- [ ] Kuri Amateka, gerageza kureba table kuri terefone uyinyereza iburyo n'ibumoso; gerageza CSV na delete.
- [ ] Reba Developer Profile, footer, social links n'ahashyirwa ifoto.
- [ ] Hindura screen kuva portrait ujya landscape; reba ko nta bice bipfukirana.

**Inama:** Device Toolbar ni simulation nziza yo kugerageza responsive layout, ariko mbere yo gushyira system ku mugaragaro, gerageza no kuri telefone na tablet nyazo niba bishoboka.
