# raupjc-hw0

#Pitanje 1: U bin/Debug folderu sada se nalazi i .dll class library kojeg smo referencirali. Njegovo uklanjanje uzrokuje neobrađenu iznimku System.IO.FileNotFoundException pri pokretanju glavnog programa, jer ne nalazi referenciranu klasu koja se koristi u njemu. Uz .exe za rad aplikacije treba poslati i sve referencirane datoteke koje smo izradili.

#Pitanje 2: Unutar Visual Studija, pri izgradnji i pokretanju aplikacije 'po defaultu' automatski se izgrađuju i referencirane biblioteke, i tada će naravno aplikacija ispisati izmijenjeni string. Međutim, ako se ta opcija isključi, bit će ispisan neizmijenjeni string, jer aplikacija koristi aktualni build biblioteke za reference.

#Pitanje 3: Prilikom build procesa (točnije, prije samog procesa) obnovljen je NodaTime package i vraćen u packages direktorij.