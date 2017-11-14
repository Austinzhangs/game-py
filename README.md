############################################################################################################
#  AUSTIN ZHANG                                                                                            #
#  THIS IS A RPG GAME PROGRAM                                                                              #
#                                                                                                          #
#                                                                                                          #
#                                                                                                          #
#                                                                                                          #
#                                                                                                          #
#                                                                                                          #
#                                                                                                          #
#                                                                                                          #
#                                                                                                          #
#############################################################################################################

print("Hi welcome to my game  hope you will enjoy it")
print("Here is the suggestion")
print("Please play this game with some music of middle age that can make you more get involve in this game")
print("like <God Rest ye Merry Gentleman>  <Tempus Est locundum> <Away>")

while True:
    输入=input ("Are you ready to play (．m．)? (Y or N)")
    if 输入 == 'Y':    # This if is ask player is ready or not
     print("You are walking in a medieval town which is nestled in the lush folds of the mountain ")
     print("It is not too far away from the frontline but you still can hear troubadour is singing the song from age of legends")
     print("You see a team of soldiers running through your face they looks very serious")
     print("At the same time another team of soldiers are driving people in to the indoor ")
     print('There is a poor child come to you')
     print('"Sir can you give me some coin? "')
     break

    else:
        continue

while True:
    要钱 = input('Do you want give this poor child money?(Y or N)')
    if 要钱 == 'Y':     # This if is for the player to choice to give money or not
        print('"Thanks you! sir now i can buy the medicine for my sister!"')
        print('The boy run to the house on the right of pub that must be the pharmacy')
        break

    elif 要钱 == 'N':
        print('"Sorry sir i just want to buy the medicine for my sister"')
        break
    else:
        print("Invalid")
        continue


while True:
    print("Than you  walk to the pub which is in front of you ")
    问题1 = input("DO you want to enter?(Y or N)")    # This input is let player to put name

    if 问题1 == 'N':                                  # This if is for the player choice enter pub or nat
            print ('There is a team of solders come to you')
            print('"What are you doing young man!"')
            print('"Get into the room!"')
            不进酒吧 = input("Go to the pub(G) Ignore the soldiers(I)")

            if 不进酒吧 == 'G':
                print('You turn around walk to the pub suddenly you hear the soldiers behind you they are screeching')
                print('You dont want to make trouble so you walk more fast')
                print('But it is too late there is a claw in your chest and it is even stirring')
                print('You turn around your head the last things you can see is the a bloody face and your can sure that is not belong to human')
            elif 不进酒吧 == 'I':
                print('"Shit you have to pay for this!!"')
                print('Than you dead ')
            else:
                print('"Shit are you kidding me do you thin i am a fool ?!!"')
                print('Than you dead (is it too hasty? of course because i am lazy!!! can you just push Y !!!')
    elif 问题1 == 'Y':

            print('You push the door you can hear the old wooden door creaked')
            print('The warm air come to your face ,there is a burning fire in the middle of the hall')
            print('The bard is playing the organist and people are singing a strange ballad around the fire')
            print('There is a old man walk to you,he dress in ornate but old clothes the beard nearly covered his half face')
            print('"Welcome to my pub adventurer!! you must be tired but before you take rest can you tell me your name?"')
            person = input("Enter your name")

            print('Hi!!', person, 'it is a good name and how many years you live in this chaotic world')
            age = eval (input("Enter your age"))
            if age < 30:                             # This if is for player to enter age
                print('"Oh what a young man! Gentlemen lets toast for this brave young man and emperor!"')
            else:
                print('"Really? you looks not that old whatever Gentlemen lets toast for this  brave man and emperor!"')
                print('Old man drink all the beer form the glass and some of the beer foam touched his beard')
                print('Than he laughed so loud that the whole pub seem to shake ')

            讲故事 =input('"My friend you must from a distance do you want listen the story of this wonderful place?"(Y or N)')

            if 讲故事 == 'Y':                   # This if is for player to listen story or not
                print('"Finally a person would like to listen to a old guy tell a story"')
                print('"The name of this town is Firewood my family has settled down here since the great forntier" ')
                print('"One of my ancestor his name is Mad Fred he led his family and his man to build this town"')
                print('"That was a dark age at that time dragon was still raging in this world"')
                print('"Not like the dragon in the far east which help people to survive and work our dragon would only kill and keep its treasure" ')
                print('"One of my ancestor son dead in the battle with the ghoul,my ancestor he took his hunge ax kill a whole tribe of ghoul"')
                print('"After that time he get the name Mad Fred but he was so sad of his son dead after one month his died of grief" ')
                print('When the old man want to keep telling his story the door of the pub break open there is a riot outside ')
                print('"What the hell happend! my friend can you fight take the axe off the shelf to protect yourself!"')
                拿斧子 = input("Do you want to take the axe? (Y or N)") # This if is for player to take weapon
                if 拿斧子 == 'N':
                    print ('You didnt take the axe')
                    print ('suddenly there are two humanoid creature come you dont know what is that but you can sure that is not human')
                    print ('They come to you but you dont have any weapon!')
                    print ('YOU DEAD')
                    break
                if 拿斧子 == 'Y':
                    print("You pick up the axe it is a little heavy it looks like it is made of fine iron ")
                    print('There are two humanoid creature come you dont know what is that but you can sure that is not human')
                    干架=input('Do you want fight with them ?(Y or N)')
                    if 干架 == 'N':    # This is for fight 
                        print('You try to hide at first they can not find you but more and more monster come ')
                        print('You kill some of them but you still dead because they are too many')

                    elif 干架 == 'Y':
                        print('You fight with them they looks nasty you see them wear the cloth of citizen and one of them is the kid ask you for money before')
                        print('You get hurt you must find some medicine so you walk out of the pub')
                        药店 = input ('Do you want walk left or right(R or L)')
                        if 药店== 'L':          # This is for enter place
                            print('You get out of the pub you can can see the old man and his man are fighting with monster ')
                            print('You can not join them because your are too weak so you walk left')
                            print('you walk to another street  but you can not find anything to treat and you hear the howls of old man')
                            print('"For the Firewood and emperor!!!!!"')
                            print('Then there is only the noise of thr monster and the whining of the people')
                            print('There are two monster in front of you')
                            药店干架 = input('DO you want to fight with them?(Y or N)')
                            if 药店干架 == 'Y':
                                print('You rush up want to kill them as soon sa possible but more of monster come out')
                                print('YOU DEAD')

                            elif 药店干架 == 'N':
                                print('You try to not touch with them but it is too late more of monster come out you try to fight')
                                print('YOU DEAD')
                        elif 药店 == 'R':
                            print('You get out of the pub you can can see the old man and his man are fighting with monster ')
                            print('You need to get the medicine as soon as possible so you run to the house on the right of the pub')
                            print('You get into the house luckily it is a pharmacy')
                            print('No one is here you find the medicine on the table but you dont know what kind of medicine it is')
                            用药 = input('Do you want to use this medicine? (Y or N) ')
                            if 用药 == 'Y':  # This is for use medicine
                                print('You ise the medicine form the table')
                                print('........................................................')
                                print('...........................................')
                                print('....................................')
                                print('...............................')
                                print('.......................')
                                print('...............')
                                print('........')
                                print('....')
                                print('.')
                                print('Some thing is ..........wron..g')
                                print('YOU DEAD OF THE RAT POISON')

                            elif 用药 == 'N':
                                print('You did not take that medicine now you are bloodying you think you are going to dead')
                                离开 = input('Do you want to keep search or go to another place? (k or G)')
                                if 离开 == 'G':           # This is for leave
                                    print('You go out and try to find another place')
                                    print(' You hear the howls of old man')
                                    print('"For the Firewood and emperor!!!!!"')
                                    print('Then there is only the noise of thr monster and the whining of the people')
                                    print('And you feel sleepy than everything is become dark')
                                    print('YOU DEAD')
                                elif 离开 == 'K':
                                    print('You keep searching finally you find the drug')
                                    print('Drug +1')
                                    药 = input('Do you want to use it now?(Y or N)')
                                    if 药 == 'N':
                                        print ('You still dont want to use it')
                                        找东西 = input('Do you want to keep searching or go out (K or G)')
                                        if 找东西 == 'K':      # This is for search
                                            print('You keep search the house and you see there are a lot of medicine and money on another table')
                                            药和钱 = input('Do you want to take them?(Y or N)')
                                            if 药和钱 == 'Y':
                                                print('You walk to the table')
                                                print('And you feel sleepy than everything is become dark')
                                                print('YOU DEAD')
                                            else:
                                                print('suddenly you feel sleepy than everything is become dark')
                                                print('YOU DEAD')
                                        elif 找东西 == 'G': 
                                            print('You go out and try to find another place')
                                            print('You see the is only old man fight by himself his man all dead')
                                            print('"For the Firewood and emperor!!!!!"')
                                            print('Then there is only the noise of thr monster and the whining of the people')
                                            print('And you feel sleepy than everything is become dark')
                                            print('YOU DEAD')

                                    if 药 == 'Y':        # This is for use medicine 
                                        print('You use the drug')
                                        print('You feel batter and full of energy')
                                        print('You hear the old man are asking for help')
                                        救人 = input('Do you go out to help the old man (Y or N)')
                                        if 救人 == 'Y':  # This is for help people 
                                            print('You rush out and join the battle')
                                            print('You cna see almost all man of old are dead ')
                                            print('You find out that until now you didnt see any soldiers where are they?')
                                            print('But you dont have the time to think about this ')
                                            print('"Finally!! My friend you come to help me!!!!')
                                            print('There are more and more monster come to you')
                                            print('"Shit!! they are too many!!! we need to leave this town!!!')
                                            离开 = input('Do you want to leave with the old man?(Y or N)')
                                            if 离开 == 'N':            # This is for leave
                                                print('You didnt leave you fight with those monster until you dead')

                                            elif 离开 == 'Y':
                                                print('"Lets go my friend!!')
                                                print('You run to the gate of the town')
                                                print('There are a lot of soldiers in the square')
                                                print('And the are many corpse in front of them')
                                                print("Their eyes are full of killing")
                                                print('You find something is wrong...')
                                                print('THE END MORE STORY PLEASE WAITE FOR NEXT GAME')
