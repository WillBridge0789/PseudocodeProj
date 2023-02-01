Brewing a cup of coffee

Variables<br>
* Coffee Pot: has a liquid volume max of 5 cups<br>
* Cup: When filled with Water OR Coffee, becomes **fullCup**<br>
* Coffee Filter Basket<br>
* Coffee Filter<br>
* Water<br>
* Bag of Coffee<br>
* Spoon

START: <br>
Cup is empty (Cup = 0)
1. **IF** Cup is empty
    * fill cup with water
    * Cup = fullCup++
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