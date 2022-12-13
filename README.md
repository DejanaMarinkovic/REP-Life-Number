# Life Number
# : -----------------------------------------------------------------------------------------------------------------------------------------------------------
# : Dejana Marinkovic - PHP Developer 
# : -----------------------------------------------------------------------------------------------------------------------------------------------------------

day = input("Unesite dan vaseg rodjenja:")
month = input("Unesite mesec vaseg rodjenja:")
year = input("Unesite godinu vaseg rodjenja:")

lista_datuma_rodjenja  = [int(x) if x.isdigit() else x
          for z in day + month + year for x in str(z)]

racunanje1 = [sum(lista_datuma_rodjenja)]

racunanje2 = [int(x) if x.isdigit() else x
          for z in racunanje1 for x in str(z)]

lifenumber = sum(racunanje2)

print("\nVas zivotni broj je", lifenumber , ".\n")


if lifenumber == 1:
    print("Sve u prirodi, svetu i životu počinje brojem jedan."
          " Zato on predstavlja univerzalni broj svega, a time i samog sistema brojeva. Simbolizuje osobine \nizrazite "
          "individualnosti, stvaralačkih stremljenja i pozitivnih opredeljenja prema svetu i ljudima.Osobe sa ovim brojem"
          " poseduju osećaj samosvojnosti, \nzbog čega su nekad sklone dominantnoj poziciji u odnosu sa drugim ljudima. "
          "Teže da složene životne situacije rešavaju na svoj originalni način. Prema \nsvetu i ljudima odnose se hrabro, "
          "čak i odvažno, zbog čega se rado odazivaju izazovima nepoznatog. Spremne su da preuzmu ulogu vođe, "
          "koji zna tačno šta \nhoće i bez obzira na prepreke streme ka odabranom cilju.Stalo im je do ugleda i "
          "poštovanja u porodičnom i poslovnom okruženju. Jedinica je bogati arsenal \ninvencija. Preterana ambicija "
          "nije im na korist, jer u slučaju neuspeha na nekom od životnih planova mogu postati razdražljivi i neurotični."
          " Ipak, \n0"
          "eventualni neuspesi remete psihološku ravnotežu za kraće vreme.Za osobe koje uspevaju, veoma je važno da "
          "kontrolišu svoje težnje za dominacijom, kako bi \nobuzdale eventualnu agresivnost i aroganciju prema okolini."
          " Treba da racionalno procene domet svojih potencijala u odnosu na brojne izazove njihovog \nživotnog puta. "
          "Kada dosegnu željene ciljeve njihov egocentrizam biva obojen notom šarma, zbog čega postaju simpatični."
          "Muževan, inventivan, hrabar, \nambiciozan, organizovan, lider, preteča, samopouzdan, usredsređen, originalan,"
          " istraživač, takmičar, snažne volje, snalažljiv, samosvojan.\n\nVladajuća planeta – Sunce.")

elif lifenumber == 2:
    print("Broj dva simbolizuje dualizam, životni princip dvojnosti ili udvojenosti. Prijemčiva, osećajna, prilagodljiva"
          " i osetljiva dvojka, lako se integriše sa \nindividualno snažnom i dominantnom jedinicom."
          "Osobe broja dva su maštovite, umetnički obdarene i pomalo romantične prirode, koje teže skladnim odnosima sa "
          "\nljudima u okruženju i svetom uopšte. Poseduju naglašen smisao za partnerstvo i zato su neka vrsta “spiritus "
          "movensa”, kada nastupaju u ekipnom i timskom \nradu i delovanju. Mogu biti odlični saradnici i drugovi od "
          "poverenja u međuljudskim i poslovnim odnosima. Nedostaje im višak energije za aktiviranje \nidejne inventivnosti"
          " i njene realizacije u spoljnom okruženju. Ovaj nedostatak dvojka kompenzuje svojim mentalno-emotivnim "
          "kvalitetima i ima sposobnost \nda se na suptilno pozitivan način upliće u brojne ljudske interakcije."
          "Preterana osetljivost, prijemčivost i razumevanje osoba u okruženju može izazvati \npovišen altruizam, "
          "ponekad do samoporicanja. Zato je neophodno da dvojka ove pozitivne i korisne osobine po svet i ljude u "
          "okruženju ograniči. Mora biti \nsvesna svoje prenaglašenosti u realizaciji združenih ideja sa svojim partnerima, "
          "kao i povremene pritajene kolebljivosti u preduzimanju konkretnih \nakcija.Uravnotežena, diplomata, ženstvena,"
          " prilagodljiva, ritmična, plemenita, skladna, prijemčiva, obzirna, druželjubiva, miroljubiva, ljubazna, "
          "\nmisaona, fleksibilna, sklona saradnji…\n\nVladajuća planeta – Mesec.")

elif lifenumber == 3:
    print("Broj nedokučive tajne moći. Utrojeno božanstvo, vladar vidljivih materijalnih i nevidljivih duhovnih svetova."
          " Demijurg neiscrpne životne energije. \nPočetak, sredina i svršetak svega. Prošlost, sadašnjost i budućnost u "
          "tački spajanja. Osobe broja tri su obdarene stvaralačkim intelektom, snagom volje i \nizrazitom ambicijom "
          "ustremljenom na visoke i počasne pozicije u političkom zivotu, armijskoj hijerarhiji i drugim društvenim "
          "delatnostima i profesijama. \nZa ove sobe su u društvu rezervisana mesta “od poverenja i odgovornosti”, "
          "sa kojih realizuju svoje upravljačke i komandne sposobnosti da bi sebi pribavili \nblistavi oreol “autoriteta bez premca”."
          "Pronicljiv, samoizražajan i stvaralački intelekt, usmerana snaga volje, savesnost i odgovornost su neosporno"
          "osobine \nbroja tri. Zrače životnim optimizmom, pozitivno su orjentisane prema svetu i ljudima. "
          "Društvena, stvaralačka, samoizražajna, telentovana za umetnost, \nšarmantna, duhovita-dosetljiva, srećna,"
          " vesela, spontana, rečita, optimista, entuzijasta, prilagodljiva, osetljiva.\n\nVladajuća planeta – Jupiter.")

elif lifenumber == 4:
    print("Ovo je broj koji simboliše “temelj-fondaciju”, skver, radnik, stvaraoc materijalnih vrednosti."
          "On je stub porodice, uže i šire društvene zajednice. Nosi \natribute temeljnosti, naporan i istrajan "
          "neimarski rad kao faktor integriteta, odnosno živo vezivno tkivo u oblastima materijalnog stvaralaštva i "
          "\ndiscipline. Revnostan i uporan umni i graditeljski rad na konstruisanju neutemeljenih fizičkih objekata poput"
          " supersoničnih aviona, svemirskih raketa i \nnuklearnih podmornica – tehničko – elektronskih čuda koje su "
          "obeležile dvadeseti vek. Osobe ovog broja pored karakterne čvrstine, napornog materijalnog \nstvaranja i "
          "izgaranja u radu imaju jak osećaj ljudske časti i dostojanstva, kao i razumevanje za potrebe drugih ljudi."
          " Nisu vizionari, nego su graditelji.\nNjihovi kvaliteti da istraju i uspeju pretvaraju vizije drugih ljudi u "
          "stvari. Struktuiran, praktičan, izdržljiv, radnik, organizovan, koncentrisan, \nprivržen, istinoljubiv, "
          "prijatelj, neimar, čuvaran, pragmatičan, od poverenja, žilav, nepopustljiv… \n\nVladajuća planeta – Saturn.")


elif lifenumber == 5:
    print("Osobe ovog broja imaju privilegiju suficita lične samostalnosti i nezavisnosti od drugih ljudi. "
          "Zato se njihov životni put rasprostire na sve četiri \nstrane sveta, slobodno kretanje i prolaz preko granica "
          "mnogih zemalja. Životni put ispunjen interesantnim doživljajima, kretanjem i promenama koje donose \nuzbuđenje."
          "“Rođeni putnik” sa izoštrenim čulima za prijem i upijanje svih lepota sveta. Neumoran istraživač nepoznatih "
          "predela, ljudi i nacija zaokupljen \nspoznajom njihovih kultura, običaja i predela. Svestrana ličnost, mobilna "
          "i dinamična u svom nastojanju da dosegne i isproba čari slobode, u pozitivnom \nsmislu te reči. "
          "Brzo donosi odluke jer svaku promenu smatra korisnom za širenje svojih potencijala u areni slobode. "
          "Često svoje akcije započinje \nimpulsivno, nastojeći da postigne njihov efektan svršetak. Skloni izbegavanju "
          "poslova koji zahtevaju dug, istrajan rad i disciplinu.Vlasnici su samo \nnjima svojstvenog psihofizičkog "
          "imuniteta, pa zato iz kratkotrajnih kriza izlaze brzo oporavljeni i vraćaju se u životnu arenu tražeći nove "
          "uzbudljive \nizazove. Preteran lov na uzbuđenja i neumorno sakupljanje utisaka i iskustava mogu izazvati "
          "kratkotrajne depresije.Višestrani, prilagodljivi, uzbudljivi, \nneobični, slobodni, energični, harizmatični, "
          "aktivni, skloni promenama, brzi, iskusni, osetljivi, avanturisti…\n\nVladajuća planeta – Merkur.")
elif lifenumber == 6:
    print("Broj ljubavi, braka, porodice i istine. Osobe ovog broja, u okviru njihove uže porodice, deluju ne samo kao "
          "brižni roditelji, već i kao \nučitelji-vaspitači, koji svoja znanja i iskustva prenose potomstvu. Spremne su da"
          " svoje dobre i korisne usluge pružaju, ne samo svojoj porodici, već i \nširem krugu rodbine.One su tvorci "
          "porodičnih ugodnosti i sofisticirani pedagozi dečije nege i razvoja. U međuljudskim odnosima nastupaju i "
          "deluju sa \npažnjom i razumevanjem, nastojeći da ostvare sklad i moguće prijateljstvo.Poseduju istančan ukus "
          "za estetske doživljaje i smisao za umetničko izražavanje \nkroz muziku, ples i slikarstvo. Ako imaju veću "
          "imovinu ili finansijske potencijale mogu postati velike mecene umetnosti i kolekcionarstva. Mogu u sebi "
          "\nimati viziju boljeg i finijeg sveta te stremiti izgradnji društva u kome će kulturne i umetničke vrednosti "
          "biti korisne mnogim članovima zajednice.\nPrijatelj, ljubazan, stvaralački, samoizražajan, širokogrud, "
          "kulturan, pouzdan, Samarićanin, moralan, sklon umetnosti, harizmatičan, skladan, srdačan… \n\nVladajuća planeta – Venera.")
elif lifenumber == 7:
    print("Intelekt, prosvetljena promisao i intuicija udruženi u nameri da proniknu kroz površinu pojavnih oblika "
          "života do njegovih tajnovitih i skrivenih \ndubinskih nivoa te da odgonetnu i razjasne suštinska pitanja "
          "ljudske egzistencije. Savez radoznalog i prosvećenog uma i intuicije, spoj naučne zamisli sa \nnagoveštajima "
          "i slutnjama za pomak granica saznanja ka skrivenim dimenzijama života i sveta. Osobe broja sedam kao da su "
          "predodređene za naučna \nistraživanja, filozofske rasprave, darovane čulima za “onostrano-metafizičko” i "
          "analitično istraživanje svetskih religija. Njihova najveća inspiracija \nbila bi osvajanje tajni svemira i "
          "rado bi uskočili u astronautske skafandere. Urođeni smisao za originalne ideje, svesni materijalnih "
          "vrednosti prema \nkojima se odnose bezbrižno, ponekad nonšalantno. Izraziti individualisti, obdareni "
          "smislom za umetnost i lepo, estete. Slavni kompozitori, književnici, \npoete,vajari i slikari… Poneki "
          "mogu razviti darove intuitivnosti do vidovitosti – prozorljivog viđenja života i sveta. Želja za "
          "fundamentalnim znanjima i \nperfekcionizam mogu prouzrokovati melanholije. Istinoljubivi, analitični, "
          "skloni naučnom istraživanju, specijalisti, željni dokazivanja i fundamentalnih \nznanja, misoani, intuitivni,"
          " perfekcionisti, verni, mudri, učitelji, osetljivi… \n\nVladajuća planeta Uran.")
elif lifenumber == 8:
    print("Znak broja osam sastavljen je od dva tangentna kruga koja manifestuju čovekovo prisustvo u dva sasvim "
          "različita sveta – fizičkom svetu materije i \nnevidljivom duhovnom svetu. Numerolozi ovaj broj tumače kao "
          "simbol neizbežne sudbine pojedinaca i naroda, ali i gospodarenje i vladanje spoljnim i \nunutrašnjim svetovima."
          "Osoba broja osam poseduje razvijenu i ciljno usmerenu intiligenciju koja podstaknuta snažnom duhovnom "
          "energijom i ambicijom može na \njavnoj društvenoj sceni odigrati važnu ulogu, značajnu za živote raznih "
          "društvenih grupa, nekad i čitavih naroda. Poseduju osećaj samosvojnosti i \nposebnosti njihovih života u "
          "odnosu na druge ljude. Njiihov životni put liči na eksluzivnu misiju koja se realizuje punim aktiviranjem "
          "i upotrebom \nkarakternih potencijala u funkciji postizanja raznih ciljeva.Osmica poseduje dve moći – striktnost"
          " u donošenju odluka i egzekutivnost u njihovom \nsprovođenju, izvršenju. Ostavlja utisak neospornog autoriteta,"
          " podobnog za uticajne političke funkcije, upravnika velike kompanije, direktora banke ili \nsopstvenog preduzeća."
          " To su samopouzdane osobe sa dobrim organizatorskim sposobnostima.Ponekad svoje ciljeve i dobre namere postižu "
          "i ostvaruju uz velike \nsopstvene žrtve. Duboka i snažna priroda kao i individualna snaga, omogućuju ovim osobama"
          " iskrenu pobožnost i veru.Različit, upravnik, zna vrednosti, \norganizovan, uravnotežen, odlučan, ambiciozan, "
          "inteligentan, praktičan, egzekutivan, samopouzdan, realist, finansijer, progresivan, pravilno rasuđuje…\n\nVladajuća planeta – Mars.")
elif lifenumber == 9:
    print("Broj devet je jedini broj koji ima sposobnost samoreprodukcije, jer pomnožen sa bilo kojim brojem, "
          "on ponovo reprodukuje sebe. \n\n9 x 2 = 18 = 1 + 8 = 9\n\nOsobe ovog broja imaju spiritualne sposobnosti i "
          "altruističke sklonosti i nadahnutosti. One se mogu posvetiti humanitarnim delatnostima na dobrobit "
          "\nmnogih siromaha, bolesnika, uopšte ljudi sa hendikepom.Osobe broja devet mogu se integrisati u duhovnim "
          "zajednicama poput manastira i u molitvi i postu \nrazvijati svoju duhovnu dimenziju. Treba da se čuvaju "
          "preterane osećajnosti, kao i da negativna iskustva svog života relativizuju, da bi se sačuvali od \nozleda "
          "svoje ranjive duše. Ne treba previše da prinose sebe na žrtvenik radi koristi i dobrobiti drugim ljudima. "
          "To je pravi način da se održi psihička \ncelina i ravnoteža, a izbegnu bolne duševne rane.Altruisti, "
          "milosrdni, univerzalni, nedvosmisleni, skloni opraštanju, inspirisani, umetnički nadareni, \ndramatični, "
          "skoro savršeni, svesni pripadnosti svetu, sinergetični…\n\nVladajuće planete – Neptun i Pluton.")
          
