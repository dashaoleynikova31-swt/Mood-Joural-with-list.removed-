# Mood-Joural-with-list.removed-
This is my attempt to add a new deletion element

tasks = []

while True:
    print("\nMood Journal")
    print("1 - Addition a new mood: ")
    print("2 - Show all moods: ")
    print("3 - Delate the mood: ")
    print("4 - Exit: ")
    
    choice = input("Enter one: ")
    
    if choice == "1":
        task = input("Enter your mood:")
        tasks.append(task)
        print(f"I added! {tasks}")
        
    elif choice == "2":
        print(f"All your moods: {tasks}")
        
    elif choice == "3":
        do = input("Enter the mood to remove: ")
        if do not in tasks:
            print("Please, write the correct answer!")
        else:
            tasks.remove(do)
            print(f"Your mood successfully removed! {tasks}")
            
    elif choice == "4":
        print("Bye! Have a lovely day!")
        break
    
    else:
       print("Enter the correсt answer!")
