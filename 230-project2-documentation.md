# Project 2 Documentation

## Process:
  My process for making this application was using the framework PureCSS and the PokemonTCG API to create
  a useful web service application which allows a user to search for Pokemon cards based on many different 
  criteria.
  
  ### PureCSS:
    I used the PureCSS framework to make my buttons and textboxes look nice with minimal extra css.
    
  ### PokemonTCG API:
    For this project I used the PokemonTCG API to create a web page which allowed for the user to search for 
    Pokemon cards based on inputs from the user. The user can search for Pokemon cards by name, move name, 
    ability name, their hp, and their retreat cost. As well the user can hover (or click on if on mobile) over
    the energy types box for a list of energy types to appear. The user choose as many types as they want
    and cards matching those types will be displayed. This functionality is also applicable on the weaknesses
    and resistances boxes but those will determine what type the pokemon cards weaknesses and or resistances 
    will be. Below the special drop down menus, there are traditional drop downs for ability type, card type,
    rarity, and what set the cards originate from. Additionally, I stored the users last input for every input
    except for the checkboxes within the custom drop downs.
    
  ### Above & Beyond:
    For the above and beyond, I made custom drop down boxes which when hovered over, will display checkbox options.
    As well, the custom drop down boxes will shrink back once the user hovers off of it. Additionally, I used flex
    box to display the cards on screen. Another thing I did to go above and beyond is I looked into how to make
    custom checkboxes online and used what I found to create custom checkboxes for my custom drop down menus. Finally,
    when the user scrolls down more than 40px, a button will appear in the bottom left of the screen which will
    bring you back to the top of the page when clicked.
    
  ### Grade:
    As for a grade that I feel fairly represents what my project is worth, I would say a 95%. I put a lot of work 
    into this project to make it functional and look nice. However, I didn't get enough time to do everything I
    wanted to do. If I had more time for this project, I would have messed around with the controls I have and
    work out a better menu system to allow for many controls but also allow everything to fit on one page
    without the need for scrolling. I wanted it so as you scrolled down the page, the menu followed with you. I
    did get this to work but I ran into issues with the cards appearing behind the menu and how I did the follow
    effect made it so my custom drop downs didn't function correctly. Because of this I decided it would be better
    to scrap the idea and just go with a button which returns the user back to the top of the page. Additionally,
    a feature that I would have liked to add is the ability to click on a card image and have it enlarged and 
    overlayed on the screen. This would have been useful because the api gives a image url and a high resolution
    image url and some cards are hard to read using only the normal image url. I would have used the high res image 
    as the overlain image and the normal ones for everything else. But sadly because I didn't have enough time to 
    tinker with it and figure it out I decided it would be best to leave it with just displaying the regular 
    sized images which conserves image download time anyway.
    
## Sources:
  PureCSS: https://purecss.io/
  PokemonTCG API: https://docs.pokemontcg.io/
