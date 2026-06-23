def detective_game():
    print("Welcome to the Detective Game!")
    print("You are investigating a robbery at the museum.")
    
    choice1 = input("Do you want to (1) inspect the crime scene or (2) question witnesses? Enter 1 or 2: ")
    
    if choice1 == "1":
        print("You find a torn glove near the broken window.")
        choice2 = input("Do you (1) send it for lab tests or (2) ignore it? Enter 1 or 2: ")
        if choice2 == "1":
            print("The lab reveals fingerprints! You catch the thief. Case solved!")
        else:
            print("You miss the clue. The thief escapes. Case unsolved.")
    
    elif choice1 == "2":
        print("A witness says they saw someone running away in a red jacket.")
        choice2 = input("Do you (1) search the nearby park or (2) check CCTV footage? Enter 1 or 2: ")
        if choice2 == "1":
            print("You find the suspect hiding in the park. Case solved!")
        else:
            print("The CCTV shows nothing useful. The trail goes cold. Case unsolved.")
    
    else:
        print("Invalid choice. Game over.")

# Run the game
detective_game()
