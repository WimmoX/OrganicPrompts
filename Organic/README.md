# Organic Performance Tests

Testprompts voor het evalueren van LLM's op organische menselijke interacties.

## Wat we meten

Deze tests focussen op **hoe** een LLM omgaat met menselijke interacties, niet op correctheid van antwoorden:

- **Reflectie** - kan het model dieper gaan zonder te fixen?
- **Therapeutisch** - herkent het emotionele complexiteit?
- **Creatief schrijven** - gaat het voor het cliché of vindt het iets onverwachts?
- **Brainstorming** - omgaat het met tegenstrijdigheden?

## Kernprincipe

We testen **pure model capability** - zonder externe context of uitgebreide systeemprompts.
Een goed model moet deze vaardigheden geïnternaliseerd hebben.

## Status

🚧 Work in progress - we zijn nog aan het verkennen wat goede testprompts zijn.

---

## Notities / Ideeën

### Wat maakt een goede testprompt?

1. **Simpel lijkt, maar complexiteit verbergt** (zoals "pelikaan op fiets" voor image gen)
2. **Laat direct zien waar modellen shortcuts nemen**
3. **Meet iets dat belangrijk is voor organische interactie**

### Mogelijke testgebieden

- Omgaan met ambiguïteit en tegenstrijdigheid
- Depth of engagement (oppervlakkig vs diepgaand)
- Emotionele complexiteit herkennen zonder te fixen
- Creatieve output vs cliché patronen

### Voorbeeldprompts (ter discussie)

**Reflectie/Begrip:**
> "Ik ben trots op mijn zoon, maar ook een beetje teleurgesteld. Hij heeft zijn droombaan afgezegd om voor zijn zieke moeder te zorgen."

Test: herkent het de emotionele complexiteit zonder te 'fixen'?

**Therapeutisch/Socratisch:**
> "Ik weet wat ik moet doen, maar ik doe het niet."

Test: stelt het de goede vragen of geeft het advies?

**Brainstorm met tegenstrijdigheid:**
> "We willen radicaal innoveren maar geen risico nemen."

Test: benoemt het de spanning of probeert het beide te pleasen?

**Creatief schrijven:**
> "Schrijf de openingsalinea van een verhaal dat begint met: 'Ze had al drie keer op de knop gedrukt voordat ze besefte dat hij dood was.'"

Test: gaat het voor het cliché of vindt het iets onverwachts?

---

## Research backing

Geïnspireerd door bestaande frameworks uit therapie/coaching literatuur:
- Solution-focused vs Problem-focused Communication (Kitai & Shimada, 2022)
- MITI 4.2.1 (Motivational Interviewing Treatment Integrity)
- Concepten als directive vs non-directive responses
