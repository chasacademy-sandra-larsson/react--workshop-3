
# React workshop #3: Forms + React Router 


👋 Denna workshop utforskar vidare i Reacts ekossytem och handlar om routing med React Router och formulär samt validering med React Hook Form (samt Yup, Zod). Men också hur useContext kan användas för att dela data mellan komponenter utan props. Med dessa tekniker tillsammans blir övningen ett multi-step formulär med validering. För att göra snabb prototyping av UI kan man även använda komponentbibliotek som Chakra, Material UI

* [React Hook Form](https://react-hook-form.com/) tillsammans med [Yup](https://www.npmjs.com/package/yup) eller [Zod](https://github.com/colinhacks/zod)
* [React Router](https://reactrouter.com/en/main)
* [React Hook useContext](https://beta.reactjs.org/reference/react/useContext)
* [Chakra](https://chakra-ui.com/), [Material UI](https://mui.com/)


# 👩🏽‍💻 Övning: Multi-step formulär


Formuläret ska innehålla följande fält och ska fördelar på två steg:

* Namn
* Förnamn
* E-post
* Adress
* Postnummer 
* Ort
* Telefon
* Jag godkänner integritetspolicy  (checkbox)
* Fortsätt (submit-knapp)

Steg 3 är resultatsida som visar samtliga uppgifter som insamlats från formulär. 
Hur formuläret är struktuerat samt lämplig validering väljs efter preferenser. 

### Bra att veta
Det finns fler strategier för multi-step formulär. Exempelvis kan man använda som conditional rendering istället för routing. Det finns även andra biblitek som Redux Form och Formik. Den bästa strategin avgörs av situationen. Strategin i denna workshopövning är React Hook Form, React Router och useContext - just för det står skrivit i era kursplaner - men också en lämplig lösning 🥸

## ➡️ Tillvägagångsätt

### 1. Installation med npm

Installera react-hook-form, yup eller zup samt react-router-dom samt övriga alternativ (Chakra, Material UI). Gå till respektive dokumentation för rätt installation. 


### 2. Skapa formulär + formulärvalidering

Skapa först formuläret som helhet för rätt utförande av react-hook-form samt validering med Yup eller Zod

### 3. Använda komponentbibliotek

Använd sig av Chakra, Material UI eller liknande för att få tillgängliga och snygga komponenter snabbt och effektivt. 

### 4. Sätta upp routes

Använd React Router (v 6) och skapa routes för steg1, steg2 och resultatsida. När ett formulär submittas på steg1 eller steg2 ska användaren redirectas till nästa steg. För detta kan du använda hooken useNavigate.

### 5. Använda useContext 

När ett formulär på steg1 eller steg2 submittas ska data insamlas genom att använda useContext. Datat som samlas in i formuläret ska presenteras på resultatstidan.

# 🤩 Redovisning

### Redovisning:
* Du/gruppen redovisar svaren på instuderingsfrågorna muntligt under workshop. 
* Du redovisar slutresultat av övningen Multi-step formuläret) 

***Om du inte kan delta på workshopen, redovisar du ovanstående nästkommande workshop***

### 💬 Diskussionsfrågor

Diskutera följande frågor i studiegruppen medan ni jobbar, redovisa sedan för lärare. Gör egna anteckningar i syfte för kommande teorihandbok om React.

* Vad är routing? Hur görs routing med React Router?
* Hur kan man omdirigiera (redirect) till en annan sida med React Router?
* Vad tillför React Hook Form? Vad gör Yup eller Zod?
* Vad är useContext och vad kan det användas till?
