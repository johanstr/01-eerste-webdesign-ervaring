# Module 01 - Mijn eerste WebDesign ervaring

## Inleiding
Om kennis te maken met je opleiding volg je nu module 1. In deze module gaan we ook voor het eerst kennis maken met de basics van WebDesign, oftewel het maken van webpagina's gestyleerd met CSS.  
  
## Wat vind ik hier?
Dit is een zogenaamde repo _(afkorting van repository)_. Een repo is een online opslag van je code bedoeld om de verschillende versies, die gedurende de development fase kunnen ontstaan, te beheren. Maar ook om met meerdere developers samen aan dezelfde codebase te kunnen werken.  

## Hoe haal ik deze code binnen op mijn laptop?
Om aan de code te kunnen werken moet je wel de code vanuit de repo binnenhalen op je eigen computer. Hier doen we dat met de basic cloning actie van Git. Cloning wil zeggen dat je een eigen versie binnenhaalt waaraan jij dan kunt werken.  
Dit kun je doen door de onderstaande stappen te volgen:  
  
1. **STAP 1**  
   Open een terminal venster (b.v. CMD, Windows Terminal of Git Bash)  

2. **STAP 2**  
   Geef het commando (cd) om naar de map te gaan waar je de code van deze repo wil gaan plaatsen. In dit voorbeeld ga ik naar de rootmap van mijn lokale webserver:

    Om er voor te zorgen dat ik zeker weten op de schijf sta waar de rootmap zich bevindt, tik ik eerst onderstaande opdracht in de terminal in:

    ```bash
        C:
    ```  

    Pas daarna tik ik de opdracht in om naar de rootmap te gaan:
    ```bash
        cd \xampp\htdocs
    ```  

3. **STAP 3**  
   Nu halen we met de git opdracht de code binnen:  
   ```bash
        git clone https://github.com/johanstr/01-eerste-webdesign-ervaring.git
   ```  
   ***LET OP!!!!***  
   Door de bovenstaande opdracht in te tikken krijg je een submap met de naam:  
   ***01-eerste-webdesign-ervaring***  
   Dit is uiteraard een lange naam en waarschijnlijk niet wenselijk of handig. Je kunt de naam van map aanpassen door achteraan de opdracht nog een zelfgekozen naam voor de submap te tikken (vergeet niet de spatie vooraf aan de zelfgekozen naam)