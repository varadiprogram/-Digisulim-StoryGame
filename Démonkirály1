import random
import time


def jatek():
    def koszonom_a_reszvetelt_meghaltal():
        print(nev, "Köszönöm hogy kipróbálta a játékomat.")
        velemeny = input("Zárd be a programot vagy nyomj egy entert:")

        while velemeny == "":
            print("Fogd Fel hogy veszettél, zárd már be a programot!!!!")

    def sikeresen_vegigjatszodtad_a_jatekot():
        print(nev, "Sikeresen végigjátszodtad a játékot!\nBy: Váradi Zsolt")

    print("Ez a kis játék arról szól, hogy fel kell magad küzdeni a csúcsra S-rangra, mert gyerekkorod óta az volt az álmod, és nem tudhatod, kivel találkozol az útad során.\nAz útad során folyamatosan erősödni fogsz.\n")
    time.sleep(5)
    erod = 100
    aranytaller = 4850

    print("Egy szegény kis faluban kezdesz, ahol kis korodtól kezdve.\nKalandor akarsz lenni és betöltödted a 18.életévedet.\nSzóval Elmehetsz Regisztrálni a Kalandor Céhben.\nAhol csak a neved kellett megadni.\n")
    time.sleep(3)
    nev = input("Név: ")

    while nev == "":
        nev = input("Név: ")

    print("Sikeresen Regisztráltál a Kalandorok céhébe, ahol F rangtól kezded az útad. A rang rendszer egyszerű: F, E, D, C, B, A, S\n")
    time.sleep(3)
    kuldetesed = input(
        "És egyből elakarsz vállalni egy küldetést, válaszd ki a küldetésed szintjét (F, E, D, C, B, A, S): ")

    while kuldetesed != "F" and kuldetesed != "E":
        print(
            "\nNem tudsz a rangodtól 2-vel nagyobb küldetést vállalni, vagy valamit elírtál.")
        time.sleep(1.5)
        kuldetesed = input(
            "Válaszd ki a küldetésed szintjét (F, E, D, C, B, A, S): ")

    if kuldetesed == "F":
        time.sleep(2)
        print("\nA feladat az, hogy el kell menni egy gógynövényért a Red Line erdőbe, ahol eltévedsz és egy olyan helyre keveredel, amit senki sem tudott, hogy létezik.\nMinden Sötét, de felcsillan egy könyv. Odamész és hozzá érsz. Fel akarod venni és hozzáérinted a mutató újjad, erre a könyv, mintha a testedbe ivódott volna.\nMegrémülsz, de nem történt semmi változás.\nVisszataláltál az eredeti célhoz.\n")
        time.sleep(3)
        print("\nÖsszeszeded és hazaérsz, ahol a céhben kapsz a küldetért 150 pénzt")
        aranytaller += 150

    elif kuldetesed == "E":
        time.sleep(2)
        print("A feladat az, hogy el kell menni 5 Silmot (Szörnyeket) ölni.\nTe azt hiszed, hogy gyengék hozzád képest, ezért súlyosan megsebeznek. Sikerült legyőzni őket, de belehalsz a sérülésekbe.")
        koszonom_a_reszvetelt_meghaltal()

    print("El akarsz menni a céhbe küldetést felvenni, de belebotlottál egy ELF kis lányba, aki azt kérte, hogy segítsd meg a társait a fogságtól.")
    segitesz = input("Segítesz Neki? (igen/nem): ")

    while segitesz != "nem" and segitesz != "igen":
        segitesz = input("Segítesz Neki? (igen/nem): ")

    if segitesz == "igen":
        time.sleep(2)
        elso_ORK_eroszintje = 750
        masodik_ORK_eroszintje = 525
        print("\nElmész a fogvatartóikhoz, akik 2 ORK, és tudod, esélyed sincs ellenük, de megpróbálsz ellenük harcolni.\nMegpróbálsz ellenük harcolni, de majdnem megölnek téged.\nSzerencsére volt nálad egy kis kard, amit a céhtől kaptál a regisztrációd során.\nÉs szerencsédre az egyik bele fut és belehal.")
        print("\nHirtelen megjelent egy ablak előtted, ami azt írja, hogy hozzáadott +750-az erődhöz.\nA másik ORK megtámad, de te látod, hogy az erő szintje: 525, de könnyedén megölöd.\nRájössz, hogy a könyv az első küldetésen azt a képességet adta neked, hogy:\nFELTUDOD MÉRNI AZ ELLENSÉGEID ERŐ SZINTJÉT, ÉS HA MEGÖLÖD AZT A SZEMÉLYT, AKKOR HOZZÁADJA AZ ERŐ SZINTJÉT A TIEDHEZ")
        erod = erod + elso_ORK_eroszintje + masodik_ORK_eroszintje

    elif segitesz == "nem":
        time.sleep(2)
        print("A kis rabszolga lány leszúr és meghalsz")
        koszonom_a_reszvetelt_meghaltal()

    beakarsz_ujjitani = input("Akarsz új tárgyakat venni?(igen/nem): ")
    while beakarsz_ujjitani != "igen" and beakarsz_ujjitani != "nem":
        beakarsz_ujjitani = input("Akarsz új tárgyakat venni?(igen/nem): ")

    if beakarsz_ujjitani == "igen":
        print("\nJelenlegi vagyonod(aranytallér): ", aranytaller)
        time.sleep(2)

        kardok = ["Kis bicska(999 aranytallér, 200+erő)",
                  "Vér Aprító(2499 aranytallér,850+erő )",
                  "Isten ülő(4999 aranytallér,1500+erő)"]

    osszes_kard = len(kardok)

    print("Összes kard: ", osszes_kard)

    for i in kardok:
        print("Kardok: ", i)
    print("")

    vasarolsz_kardot = input("Vásárolsz Kardot?(igen/nem): ")
    while vasarolsz_kardot != "igen" and vasarolsz_kardot != "nem":
        vasarolsz_kardot = input("Vásárolsz Kardot?(igen/nem): ")

    if vasarolsz_kardot == "igen":
        melyiket_akarod = str(input(
            "írd be azt hogy mennyi aranytállérba került: "))

        while melyiket_akarod != "999" and melyiket_akarod != "2499" and melyiket_akarod != "4999":
            melyiket_akarod = str(input(
                "írd be azt hogy mennyi aranytállérba került: "))

        if melyiket_akarod == "999" and aranytaller > 999:
            aranytaller = aranytaller - 999
            erod = erod + 200
            print(
                "Megvetted a kardot és az erőd nagyobb lett 200-al, jelenlegi erő szinted: ", erod)

        elif melyiket_akarod == "2499" and aranytaller > 2499:
            aranytaller = aranytaller - 2499
            erod = erod + 850
            print(
                "Megvetted a kardot és az erőd nagyobb lett 850-el, jelenlegi erő szinted: ", erod)

        elif melyiket_akarod == "4999" and aranytaller > 4999:
            aranytaller = aranytaller - 4999
            erod = erod + 1500
            print(
                "Megvetted a kardot és az erőd nagyobb lett 1500-al, jelenlegi erő szinted: ", erod)

        else:
            print("Nincs elegendő aranytallérod")

        if vasarolsz_kardot == "nem":
            time.sleep(3)
            print(
                "\nTalálkozol egy nagyon erős ellenfélel és megöl mert nem volt fegyvered.")
            koszonom_a_reszvetelt_meghaltal()

    time.sleep(2)
    print("Olyan erős lettél hogy nem találod a helyed az életbe ezért elkezded mászni a ranglisát a céhbe ezért megakarsz ölni 5 DÉMONT")
    print("JELENLEGI ERŐD: ", erod)

    # 1

    elso_demon_ereje = random.randint(1500, 3000)

    time.sleep(2)
    print("\nTalálkozol az első démonnal akinek az ereje:", elso_demon_ereje)

    input("A támadáshoz nyomj egy entert:")

    if elso_demon_ereje <= erod:
        erod = elso_demon_ereje + erod
        time.sleep(2)
        print("Sikeresen legyőzted a démont, az ereje hozzá adodott a tiedhez, jelenlegi erőd: ", erod, "\n")

    elif elso_demon_ereje > erod:
        time.sleep(2)
        print("megölt a Démon\n")
        koszonom_a_reszvetelt_meghaltal()

    # 2

    masodik_demon_ereje = random.randint(3000, 5000)

    time.sleep(2)
    print("\nTalálkozol a második démonnal akinek az ereje:", masodik_demon_ereje)

    input("A támadáshoz nyomj egy entert:")

    if masodik_demon_ereje <= erod:
        erod = masodik_demon_ereje + erod
        time.sleep(2)
        print("Sikeresen legyőzted a démont, az ereje hozzá adodott a tiedhez, jelenlegi erőd: ", erod, "\n")

    elif masodik_demon_ereje > erod:
        time.sleep(2)
        print("megölt a Démon\n")
        koszonom_a_reszvetelt_meghaltal()

    # 3

    harmadik_demon_ereje = random.randint(5000, 9100)

    time.sleep(2)
    print("\nTalálkozol a harmadik démonnal akinek az ereje:", harmadik_demon_ereje)

    input("A támadáshoz nyomj egy entert:")

    if harmadik_demon_ereje <= erod:
        erod = harmadik_demon_ereje + erod
        time.sleep(2)
        print("Sikeresen legyőzted a démont, az ereje hozzá adodott a tiedhez, jelenlegi erőd: ", erod, "\n")

    elif harmadik_demon_ereje > erod:
        time.sleep(2)
        print("megölt a Démon\n")
        koszonom_a_reszvetelt_meghaltal()

    # 4

    negyedik_demon_ereje = random.randint(9100, 14500)

    time.sleep(2)
    print("\nTalálkozol a negyedik démonnal akinek az ereje:", negyedik_demon_ereje)

    input("A támadáshoz nyomj egy entert:")

    if negyedik_demon_ereje <= erod:
        erod = negyedik_demon_ereje + erod
        time.sleep(2)
        print("Sikeresen legyőzted a démont, az ereje hozzá adodott a tiedhez, jelenlegi erőd: ", erod, "\n")

    elif negyedik_demon_ereje > erod:
        time.sleep(2)
        print("megölt a Démon\n")
        koszonom_a_reszvetelt_meghaltal()

    time.sleep(3)
    print("\nAz utolsó démon a, DÉMONKIRÁLY néven ismert\nés a céhbe az a hír járja aki megöli az felkerül a legnagyobb rangba a játkba vagyis S-ragú lesz.")
    print("\nA démon király ereje: 35000")
    demon_kiraly_ereje = 35000

    input("A támadáshoz nyomj egy entert:")

    print(".")
    time.sleep(3)
    print("..")
    time.sleep(3)
    print("...")
    time.sleep(3)

    if erod < demon_kiraly_ereje and erod < 30000:
        print("Megölt a DÉMONKIRÁLY")
        koszonom_a_reszvetelt_meghaltal()

    elif erod >= demon_kiraly_ereje:
        print("Sikeresen Megölted a démon Királyt és a beleírtad megad a világ vagyis a DigiSulim történetébe.\nBetelesült az álmod hogy S-rangú kalandor legyél.")
        sikeresen_vegigjatszodtad_a_jatekot()

    elif erod < demon_kiraly_ereje and erod > 30000:
        print("A démon király majdnem megölt de hagyott magán egy kis rést")

        oldal = ["jobb", "bal"]

        dontes = random.choice(oldal)
        honnan_tamadsz = input("Honnan Támadsz?(jobb,bal): ")
        while honnan_tamadsz != "jobb" and honnan_tamadsz != "bal":
            honnan_tamadsz = input("Honnan Támadsz?(jobb,bal): ")

        if honnan_tamadsz == dontes:
            print("Sikeresen Megölted a démon Királyt és a beleírtad megad a világ vagyis a DigiSulim történetébe.\nBetelesült az álmod hogy S-rangú kalandor legyél.")
            sikeresen_vegigjatszodtad_a_jatekot()
        else:
            print("Megölt a DÉMONKIRÁLY")
            koszonom_a_reszvetelt_meghaltal()


jatek()
# by: Váradi Zsolt | Ezzel a programmal töltött idő: 4óra 35perc
