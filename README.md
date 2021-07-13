# Zombie-apocalypse-game-
```markdown
#Zombie Apocalypse
#by Alan Tran 

print('''
Zombies are everywhere!!
They are trying to invade your house. 
And you are alone.
''')
  
print('''
What are you going to do?
1. Fight the zombies with a baseball bat.
2. Play dead
3. Run to the nearesr hiding place
4. Call 000
 ''')
choice=input('You Choose:')
 
if choice.strip()[0]=='1':
   print('You fight vigourously. You managed to knock down 3 zombies, but then another zombie came from behind... and you are dead.')
elif choice.strip()[0]=='2':
  print('You play dead. The zombies do not notice you at all. But then you have a strong urge to sneeze, and as soon as you smeeze... you are dead')
elif choice.strip()[0]=='3':
  print('You ran to the backyard where your friends are also hiding. You are safe. But the... there is no water or food where you guys are hiding, so you starve to death.')
elif choice.strip()[0]=='4':
  print('You call 000. The operator answers, but the operator is only screaming. He is dead. You are also dead.')
else:
  print('Please choose 1-4')
  ```
