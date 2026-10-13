# Számlázási kérdések

Ebben a cikkben összefoglaltuk a VIPY rendszerben elérhető fizetési módokat, a számlázás működését, valamint a szolgáltatások életciklusát.

## Hogyan lehet fizetni?

Többféle fizetési módszer is elérhető felületünkön automatizáltan, melyek szinte azonnali fizetést biztosítanak:

- **SimplePay (Bankkártya, Google Pay, Apple Pay)**: azonnali feldolgozás
- **Stripe (Bankkártya)**: azonnali feldolgozás
- **PayPal (Bankkártya, PayPal egyenleg)**: azonnali feldolgozás
- **paysafecard**: azonnali feldolgozás

Illetve szükség szerint akár **banki átutalással** is megoldható, ezzel kapcsolatban kérjük vegye fel velünk a kapcsolatot. Számlát / nyugtát a befizetés után maximum pár perccel készíti el a rendszer melyet email-ben is kiküldünk az értesítési cím(ekre), illetve a felületről is letölthető bármikor a későbbiekben.

Számlázási profilokat dinamikusan lehet módosítani bármikor a projekten belül, ám a fiók kezelője köteles ezen adatok helyességéről gondoskodni, utólagos módosítást csak kezelési költség ellenében van lehetőség. 

## Mi történik ha elmarad a hosszabbítás?

### 1. Véletlen elmulasztás

Lejárat előtt **7 és 3 nappal** értesítést küldünk emailben, illetve igény alapján discord webhook-on keresztül is, a lejárati dátum után **3 napig** még futni hagyjuk a szolgáltatást és utána még **2 napig** tároljuk.

Amennyiben el szeretné kerülni a véletlen lejáratot, ajánlott bekapcsolni az előfizetést (SimplePay rendszeren keresztül) a szolgáltatás számlázási oldalán. Ilyenkor a lejárat előtt 3 nappal terheljük a hozzárendelt bankkártyát, sikertelen terhelés esetén értesítést küldünk.

### 2. Nincs szükség a szolgáltatásra a továbbiakban

Lemondás esetén nincs extra teendő, nem szükséges jelezni a lemondást.

Lejárati dátum utáni **5. napon** töröljük a rendszerünkből a szolgáltatást és minden mentését.

## Szolgáltatás lejárata és törlődése

Lejárat utáni **5. napon** törlődik a szolgáltatás és minden hozzá kapcsolódó mentés.

Ezek után **nincsen semmilyen lehetőség visszaállítani**.
