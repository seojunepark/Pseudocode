#Riley Park- text based adventure game pseudocode. This code will calculate the total cost of the inventories needed for the text-based adventure game 
#8 April, 2022
#Listing the inventories 
print("This part of the program will print the inventories including weapons, consumables, and protections as well as their specific items.")
weapons = ['pencil', 'knife', 'bat', 'human arm', 'torch']
print("\n""Weapons:")
amessagezero = f"1. {weapons[0]}"
amessageone = f"2. {weapons[1]}"
amessagetwo = f"3. {weapons[2]}"
amessagethree = f"4. {weapons[3]}"
amessagefour = f"5. {weapons[4]}"
print(amessagezero)
print(amessageone)
print(amessagetwo)
print(amessagethree)
print(amessagefour)
consumables = ['water', 'cell phone', 'oxygen tank', 'flashlight']
print("\n""Consumables:")
bmessagezero = f"1. {consumables[0]}"
bmessageone = f"2. {consumables[1]}"
bmessagetwo = f"3. {consumables[2]}"
bmessagethree = f"4. {consumables[3]}"
print(bmessagezero)
print(bmessageone)
print(bmessagetwo)
print(bmessagethree)
protections = ['shield', 'fire proof suit', 'freeze proof suit', 'tent']
print("\n""Protections:")
cmessagezero = f"1. {protections[0]}"
cmessageone = f"2. {protections[1]}"
cmessagetwo = f"3. {protections[2]}"
cmessagethree = f"4. {protections[3]}"
print(cmessagezero)
print(cmessageone)
print(cmessagetwo)
print(cmessagethree)
#Assigning variables for the program
pencil = 10 #Price of the pencil in dollars 
knife = 20 #Price of the knife in dollars 
bat = 20 #Price of the bat in dollars 
human_arm = 5000 #Price of the human arm in dollars  
torch =  30 #Price of the torch in dollars 
water = 0 #Price of the water in dollars 
cell_phone = 500 #Price of the cell phone in dollars 
oxygen_tank = 150 #Price of the oxygen tank in dollars
flashlight = 20 #Price of the flashlight in dollars 
shield = 300 #Price of the shield in dollars
fire_proof_suit = 400 #Price of the fire proof suit in dollars  
freeze_proof_suit = 400 #Price of the freeze proof suit in dollars 
tent = 20 #Price of the tent in dollars 
#Program calculation using variables 
total_cost = (pencil+knife+bat+human_arm+torch+water+cell_phone+oxygen_tank+flashlight+shield+fire_proof_suit+freeze_proof_suit+tent)
print("The total cost of the inventory items required is: $",format(total_cost,",.2f"))



