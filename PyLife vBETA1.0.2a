import time
import random
print "Welcome to PyLife vBETA1.0.2a"

body = ('arm', 'leg', 'knee', 'anus', 'mouth', 'tounge',
        'ear', 'brain', 'rectum', 'heart', 'toes', 'larynx', 'armpit', 'wenis'
        , 'skull', 'kneecaps')
drug = ('weed', 'cocaine', 'ecstasy', 'marijuana', 'speed', 'morphine')
liquor = ('beer', 'wine', 'whiskey', 'rum', 'gin and juice', 'whiskey sour', 'Red Bull Vodka',
          'Alize')
firstname_male = ('Mike', 'James', 'John', 'Robert', 'Bob', 'Jack', 'William', 'Charlie',
                   'Joe', 'Dave')
firstname_female = ('Mary', 'Christina', 'Jessica', 'Patricia', 'Linda',
                     'Elizabeth', 'Sue', 'Rachel', 'Barbara', 'Ashley')
surname = ('Smith', 'Johnson', 'Jones', 'Brown', 'Lopez', 'Miller', 'Anderson',
            'Lee', 'Taylor', 'Perez', 'Paul')
item = ('table', 'bed', 'television', 'computer', 'NES', 'DVD player', 'Sony Walkman',
        'couch', 'mirror')
assault = ('hit', 'punched', 'stabbed', 'poked', 'smacked', 'sliced', 'squeezed', 'snap, crackle, and popped')

def update():
    print """vBETA1.0.2a:  bug fixes.  Removed the option to be gay or bi due to 
bugs in the way it worked"""
    print """vBETA1.0.2: added the option to be gay or bi and changed
how you start the game."""
    print "vBETA1.0.1: added dating"
    print "vBETA1.0: launched game"
           
def pylife():
    '''Starts PyLife'''
    name = raw_input("What do you want your name to be:   ")
    gender = int(raw_input("Do you want your character to be a boy(1) or a girl(2):  "))
    print "PyLife", u"\u00a9", " is loading..."
    print "THIS GAME IS A SCHOOL PROJECT USED FOR EDUCATIONAL USE.  ALL RIGHTS GO TO THE ORIGINAL OWNER."
    time.sleep(5)

    #Bools
    age = 0
    life = True
    dropout = False
    school = True
    single = True
    gay = False

    #Start
    print "Welcome ", name, "!"
    print "Press 0 at any time to end your life."
    while life == True:
        print "You are ", age, " year(s) old."

        #Variables
        cancer = random.randint(1,100)
        cow = random.randint(1,250)
        bully = random.randint(1,10)
        drugs = random.randint(1,50)
        booze = random.randint(1,30)
        date = random.randint(1,12)
        oldDeath = random.randint(1,30) #50+
        OldDeath = random.randint(1,25) #60+
        OlderDeath = random.randint(1,18) #75+
        


        if age == 4:
            print "Your mom is accusing you of breaking her ", random.choice(item),"!"
            print "1. It wasn't me!"
            print "2. I plead the 5th!"
            integrety = int(raw_input("...   "))
            if integrety == 1:
                print "I lied about breaking my mom's stuff."
            elif integrety == 2:
                print "I told my mom the truth."
            else:
                print "I told my mom the truth."

        
        if age == 5:
            print "You started elementary school."

        
        if age == 14 and school == True:
            print "You started high school."
        '''
        #GAY?
        if age == 15:
            print "You have to confront your sexuallity.  Are you gay(1), bisexual(2), or straight(3)"
            gay_choice = int(raw_input("..."))
            if gay_choice == 1:
                gay = True
                print "I am homosexual"
            elif gay_choice == 2:
                gay = True
                print "I am bisexual"
            elif gay_choice == 3:
                gay = False
                print "I am heterosexual"
            else:
                gay = False
                print "I am heterosexual"  
        '''            

        #dropout
        if dropout == False and age >= 16 and age < 18 and school == True:
            out = int(raw_input("To age up, press 1.  To dropout of school, press 2:  "))
            if out == 2:
                print "You dropped out of school."
                dropout = True
                
        if age >=6 and age <= 14 and bully == 3:
            print"You are being bullied at school.  Do you:"
            print"1. Assault him."
            print"2. Tell on him."
            print"3. Let it be."
            bullychoice = int(raw_input("Pick 1, 2, or 3:   "))
            if bullychoice == 1:
                print "You assaulted him!"
                print "You", random.choice(assault), "his ",random.choice(body), "and", random.choice(assault), "his ", random.choice(body), "!!"
                manslaughter = random.randint(1,50)
                if manslaughter == 42:
                    print "He died from his injuries."
                    print "You were forced to drop out of school."
                    school = False
            elif bullychoice == 2:
                print "You told on the bully."
            elif bullychoice == 3:
                print "You let the bully continue to bully you."
                
        #Drugs        
        if drugs == 17 and age >= 18:
            drugtype = random.choice(drug)
            print "Someone just offered you ", drugtype, ".  Do you take it?"
            drug_choice = int(raw_input("Press 1 for yes or 2 for no:  "))
            if drug_choice == 1:
                print "You took the drugs."
            elif drug_choice == 2:
                print "You said no to drugs."
            else:
                print "You said no to drugs."
                
        #random event for alcohol
        if booze == 2 and age >= 21:
            print "Someone has offered you ", random.choice(liquor), ".  Do you drink it?"
            booze_choice = int(raw_input("Press 1 for yes or 2 for no:  "))
            if booze_choice == 1:
                print "You took the alcohol."
            elif booze_choice == 2:
                print "You said no to alcohol."
            else:
                print "You said no to alcohol." 
                
        #Dating
        if age >= 18 and single == True and date == 7:
            if gender == 1 and gay == False:
                print random.choice(firstname_female), random.choice(surname), "wants to go out with you!"
                date_choice = int(raw_input("Press 1 for yes and 2 for no"))
                if date_choice == 1:
                    print "You are now dating."
                    single = False
                elif date_choice == 2:
                    print "You rejected her."
                else:
                    print "You rejected her."
            elif gender == 2 and gay == False:
                print random.choice(firstname_male), random.choice(surname), "wants to go out with you!"
                date_choice = int(raw_input("Press 1 for yes and 2 for no"))
                if date_choice == 1:
                    print "You are now dating."
                    single = False
                elif date_choice == 2:
                    print "You rejected him."
                else:
                    print "You rejected him."
            elif gender == 1 and gay == True:
                print random.choice(firstname_female), random.choice(surname), "wants to go out with you!"
                date_choice = int(raw_input("Press 1 for yes and 2 for no"))
                if date_choice == 1:
                    print "You are now dating."
                    single = False
                elif date_choice == 2:
                    print "You rejected her."
                else:
                    print "You rejected her."
            elif gender == 2 and gay == True:
                print random.choice(firstname_male), random.choice(surname), "wants to go out with you!"
                date_choice = int(raw_input("Press 1 for yes and 2 for no"))
                if date_choice == 1:
                    print "You are now dating."
                    single = False
                elif date_choice == 2:
                    print "You rejected him."
                else:
                    print "You rejected him."
            else:
                print "ERROR WITH DATING"

        #death from old age (50+)
        if age >= 50 and age < 60 and oldDeath == 4:
            life = False
            print "You died at the age of ", age, " from complications of old age."
            break
            
        #death from old age (60+)    
        if age >= 60 and age < 75 and OldDeath == 4:
            life = False
            print "You died at the age of ", age, " from complications of old age."
            break
            
        #death from old age (75+)
        if age >= 75 and age < 90 and OlderDeath == 4:
            life = False
            print "You died at the age of ", age, " from complications of old age."
            break
        
        #cancer
        if age > 4 and cancer == 97:
            life = False
            print"You have cancer of the ",random.choice(body),"!"
        
        #cow
        if age > 1 and cow == 107:
            life = False
            print "You have mad cow disease."
        
        #To age up
        choice = int(raw_input("To age up, press 1.  For more options, press 5:   "))
        if choice == 1:
            age = age + 1
        elif choice == 5:
            print "Beta"
        #To end life
        elif choice == 0:
            life = False
            print "You ended your own life."
            break
        else:
            return "Error.  Try again."
            
    if life == False:
        print "You died at ", age, "years old."
