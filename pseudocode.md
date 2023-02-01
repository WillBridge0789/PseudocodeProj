Brewing a cup of coffee

INIT: variables<br>
* Coffee Pot<br>
* Cup<br>
* Coffee Filter Basket<br>
* Coffee Filter<br>
* Water<br>
* Bag of Coffee<br>
* Spoon

START: <br>
Cup is empty
1. **IF** Cup is empty
    * fill cup with water

2. **IF** Water **IN** Cup
    * pour cup into Coffee Pot (Coffee Pot = 1 Cup)

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