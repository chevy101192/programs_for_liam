def main():
###pulls the choice operator from the "random" library
  from random inport choice
  cave_numbers = range(1, 10)
  dragon_location = choice(cave_numbers)
  player_location = choice(cave_numbers)
  while player_location ==dragon_location:
    player_location == choice(cave_numbers)
    
    ###Dialogue to induce Game play###
    print("Welcome to your Kingdom!")
    print("Might i ask... What is your name?")
    player_name = input("> ")
    print("""Well fair {} it's an honor to meet you!
    though i am sad that you have come here now.""".format(player_name))
    input("Press Enter to continue")
    print(" ")
    
    print("""We are having some trouble with a Dragon,
    it's been attacking our kingdom and no one has been able to stop it!""")
    input("Press Enter to continue")
    print(" ")
    
    print("""The Dragon is up in a cave in the mountains...
    do you believe you could defeat it?""")
    input("Press Enter to continue")
    print(" ")
    
    print(""" With that the brave {} and his new friend
    traveled into the mountains to face the Dragon""".format(player_name))
    
    ###A while loop that will ask for the player to guess which cave the dragon is in###
    while true:
      print("You are in cave", player_location)
      if(player_location == dragon_location -1 or player_location = dragon_location + 1):
          print("What's that? I think i heard the dragon")
      
      else:
          print("I don't think he's here we must look in another cave")
          player_input = input("Which cave should we go to next?")
          if(not player_input.isdigit() or int(player_input) not in cave_numbers):
              print("Thats not one of the caves silly!"
          
          else:
              player_location = int(player_input)
              if player_location == dragon_location):
                  print("We've found it!. Now you must defeat it!")
                  math()
                  print("amazing! you've defeated the beast!!!")
                  break
                  
def math():
    from random import choice
    math_num = range(1, 20)
    iterator = 0
    
    ###a while loop to create new math problems
    while(iterator != 4):
        first_num = choice(math_num)
        second_num = choice(math_num)
        answer = first_num + second_num
        
        player_answer = int(input("{} + {} = ".format(first_num, second_num)))
        
        ###compare player input to the correct answer###
        if player_answer == answer):
            ###increase the iterator variable###
            iterator = iterator +1
            til_done = (iterator - 4) * -1)
            keep_score = 4 - iterator
            
            if(til_done !+ 0):
                print("Great job! That's {} hit {} more to go and you will slay this beast".format(iterator, til_done))
                
            else:
                print("""Sadly that is the incorrect answer, your sword did not hit the dragon!
                but you can still slay the beast!!""")
                
main()
