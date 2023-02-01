# Brewing a cup of coffee

## INIT: Variables<br>
* Coffee Pot: Can brew up to (5) cups<br>
* Cup of Water: max (5)<br>
* Cup of Coffee: (1) Cup per brew
* Coffee Filter Basket<br>
* Coffee Filter<br>
* Bag of Coffee<br>
* Water <br>
* Spoon



## Functions: <br>

### Function brewCoffee()
    WHILE (water IN Coffee Pot) 
        FOR cupOfWater IN CoffeePot
            IF (cupOfWater > 0) AND ( <= 5)
                Say "Coffee is brewing!"
            ELSE
                Say "Please fill to start brew"
            END


## START
Coffee Pot = 
Cup of Water = 0 <br>
Cup of Coffee = 0<br>
Coffee Filter Basket = 0 (*no filter in it*)<br>
Coffee Filter = 0 (*empty*)<br>

1. **IF** Cup is empty
    * fill cup with water
    * Cup += 1
        * END

2. **IF** Water **IN** Cup
    * pour Cup into Coffee Pot (Coffee Pot = 1 Cup)

3. Grab a Coffee Filter

    * **IF** Coffee Filter Basket is empty <br>put Coffee Filter in it

4. Grab Spoon 
5. Grab Bag of Coffee
6. Open Bag of Coffee

7. **WHILE** Spoon is empty *AND* Bag of Coffee is open
    * **FOR** each Cup of Water *IN* Coffee Pot (Currently 1 Cup)
        * Do 1 Spoon of Coffee

8. **WHILE** Coffee Pot has Water, Coffee Filter Basket has Filter *WITH* Coffee
    * **START** brewing Cup of Coffee

9. Serve Cup of Coffee

END program