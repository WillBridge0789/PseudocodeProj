# Brewing a cup of coffee

## INIT: Variables<br>
* Coffee Pot **->** (coffeePot): Can brew up to (5) cups<br>
* Cup of Water **->** (cupOfWater): max (5)<br>
* Cup of Coffee **->** (cupOfCoffee): (1) Cup per brew
* Coffee Filter Basket **->** (coffeeFiltBask): Holds coffee filter. Max (1) per brew<br>
* Coffee Filter **->** (coffeeFilter)<br>
* Bag of Coffee **->** (bagOfCoffee)<br>
* Coffee grounds **->**(coffeeGrounds)<br>
* Water <br>
* Spoon

## Objects:
### Bag of Coffee = {
    coffeeGrounds: 5; (measured in scoops)
}

## Functions: <br>

### Function for Get Materials -> getMaterials();
    * Cup Of Water (1)
    * Coffee Filter (1)
    * Bag of Coffee (1)
    * Spoon (1) 

### Function for Brew Coffee -> brewCoffee();
    WHILE (water IN Coffee Pot, Coffee grounds IN Coffee Filter, AND Coffee Filter Basket in place) 
        FOR Water IN CoffeePot
            IF (Water value === Coffee Grounds value AND Coffee Filter value)
                Say "Coffee is brewing!"
            ELSE
                Say "Please fill to start brew"
            END


## START
Coffee Pot = 0<br>
Cup of Water = 0<br>
Cup of Coffee = 0<br>
Coffee Filter Basket = 0 (*no filter in it*)<br>
Coffee Filter = 0 (*empty*)<br>
Bag of Coffee = Coffee grounds(*5 scoops*)

1. **getMaterials();**
    >*Cup of Water, Coffee Filter, Bag of Coffee and Spoon should have a value of 1.*


2. **FOR** Water **IN** Cup Of Water
    * **IF** Cup Of Water += 1
        * pour Cup Of Water into Coffee Pot<br> (Coffee Pot += 1 Cup)
    * END

3.  **IF** Coffee Filter Basket is empty<br>
    put Coffee Filter in it<br>
    >*Coffee Filter Basket has 1 filter.*<br>
        END

4. Grab Spoon 
5. **DO** 1 Spoon of Coffee Grounds FROM Bag of Coffee<br>
    **WHILE** Coffee Filter is in Coffee Filter Basket<br>
         **FOR** each Cup of Water *IN* Coffee Pot (*Coffee Pot currently equals 1*)<br>
            **SCOOP** 1 Spoon of Coffee Grounds<br>
             *Coffee Filter now equals 1 and Bag of Coffee's value should be 4*

8. **WHILE** Coffee Pot has Water, Coffee Filter Basket has Filter *WITH* Coffee
    * **brewCoffee();**
    >*Cup of Coffee value is now 1*

9. **SERVE** Cup of Coffee

END program