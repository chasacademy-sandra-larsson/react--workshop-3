
# React workshop #3: Forms + React Router 


👋 Denna workshop har inte så mycket utrymme i Robins bok "The road to React" eftersom vi ska utforska vidare i Reacts ekossytem. Det som kommer användas är React Router för routing och react-hook-form (samt Yup, Zod) för formulärhantering och validering. För att samla in data från alla delsteg kommer useContext att användas. Det är valfritt att använda komponentbibliotek som Chakra, Material UI, eller liknande för att lättare prototypa UI för formulär.

* [React-hook-form](https://react-hook-form.com/) tillsammans med [Yup](https://www.npmjs.com/package/yup) eller [Zod](https://github.com/colinhacks/zod)
* [React Router](https://reactrouter.com/en/main)
* [React Hook useContext](https://beta.reactjs.org/reference/react/useContext)
* [Chakra](https://chakra-ui.com/), [Material UI](https://mui.com/)


# 👩🏽‍💻 Övning: Multi-step formulär


Formuläret ska innehålla följande fält:

* Namn
* Förnamn
* E-post
* Adress
* Postnummer 
* Ort
* Telefon
* Jag godkänner integritetspolicy  (checkbox)
* Fortsätt (submit-knapp)

Du har två steg (exempelvis Step1.js och Step.js) samt en resultatsida som visar samtliga uppgifter som insamplats. Hur formuläret är struktuerat samt lämplig validering väljs efter preferenser. Du använder Yup eller Zod för valideringsschema.

Testa Chakra eller Material UI eller liknande, för att exempelvis använda till kommande Reactprojekt.

### Bra att veta
Det finns fler strategier för multi-step formulär som att använda som conditional rendering istället för routing. Det finns även andra biblitek som Redux Form och Formik. Den bästa strategin avgörs ju av situationen. Strategin i denna workshopövning är Routing och useContext - just för det står skrivit i era kursplaner 🥸

## ➡️ Tillvägagångsätt

### 1. Installation med npm

Installera react-hook-form, react-router samt övriga alternativ. Gå till respektive dokumentation för rätt installation. 


### 2. Skapa formulär + formulärvalidering

Skapa först formuläret som helhet för rätt utförande av react-hook-form samt validering med Yup eller Zod

### 3. Använda komponentbibliotek

Använd sig av Chakra, Material UI eller liknande för att få tillgängliga och snygga komponenter snabbt och effektivt. 

### 4. Sätta upp routes

Använd React router och skapa routes för steg1, steg2 och resultatsida. När ett formulär submittas på steg1 eller steg2 ska användaren redirectas till nästa steg. För detta kan du använda hooken useNavigate.

### 5. Använda useContext 

När ett formulär på steg1 eller steg2 submittas ska data insamlas genom att använda useContext. Datat som samlas in i formuläret ska presenteras på resultatstidan.

# 🤩 Redovisning

### Redovisning:
* Du/gruppen redovisar svaren på instuderingsfrågorna muntligt under workshop. 
* Du redovisar slutresultat av övningen Pokedex (se nedan) 

***Om du inte kan delta på workshopen, redovisar du ovanstående nästkommande workshop***

### 💬 Diskussionsfrågor

Diskutera följande frågor i studiegruppen medan ni jobbar, redovisa sedan för lärare. Gör egna anteckningar i syfte för kommande teorihandbok om React.

* Vad är routing? 
* Vad tillför react-hook-form? Vad gör Yup eller Zod?
* Vad används useContext till?
