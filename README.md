# game-py
print ("you are walking in a medieval town which is nestled in the lush folds of the mountain ")
print ("it is not too far away from the frontline but you still can hear troubadour is singing the song from age of legends")
print ("you see a team of soldiers running through your face they looks very serious")
print ("at the same time another team of soldiers are driving people in to the indoor ")
print("you see a pub is infront of you ")
ans = input("DO you want to enter?(Y or N)")

if ans == 'N':
    print('there is a team of soliders come to you')
    print('"what are you doing young man!"')
    print('"get into the room!"')
    cs = input("Go to the pub(G) Ignore the soldiers(I)")

    if cs == 'G':
        print ('you turn around walk to the pub suddenly you hear the soldiers behind you they are screeching')
        print ('you dont want to make trouble so you walk more fast')
        print ('but it is too late there is a claw in your chest and it is even stirring')
        print ('you turn around your head the last things you can see is the a bloody face and your can sure that is not belong to human')
    elif cs == 'I':
        print('"damned paro you have to pay for this"')
        print('than you dead (is it too hasty? of course because i am lasy!!! can you just push Y you nasty!!!')


elif ans =='Y':
    print('you push the door you can hear the old wooden door creaked')
    print('There is a old man walke to you,he dress in ornate but old clothes the beard nearly covered his half face')
    print('"Wellcome to my pub adventurer!! you must be tired but before you take rest can you tell me your name?"')
    person = input("Enter your name")

    print('hi', person, 'it is a good name and how many years you live in this chaotic world')
    age = eval (input("Enter your age"))
    if age < 20:
        print('hi',)
