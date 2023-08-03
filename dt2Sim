import random

ingots = False
vestige1 = False
vestigeCount1 = 0
vardKC = 0
vestige2 = False
vestigeCount2 = 0
dukeKC = 0
vestige3 = False
vestigeCount3 = 0
leviKC = 0
vestige4 = False
vestigeCount4 = 0
wispKC = 0
axe1 = False
axe2 = False
axe3 = False
axe4 = False
# virtus1 = True
# virtus2 = True
# virtus3 = True

vardKCavg = 0
dukeKCavg = 0
wispKCavg = 0
leviKCavg = 0
rollTable = 0
rollUnique = 0
totalKC = 0
trialCount = 0
avgTally = 0
avgCompletion = 0

while trialCount < 10000:

    # Vard
    while not(vestige1 and axe1):
        rollTable = random.randint(1, 136)
        if rollTable == 1:
            rollUnique = random.randint(1, 8)
            if 1 <= rollUnique <= 3:
                vestigeCount1 = vestigeCount1 + 1
                if vestigeCount1 == 3:
                    vestige1 = True
            if 4 <= rollUnique <= 6:
                ingots = ingots + 1
            if rollUnique == 7:
                axe1 = True
        vardKC = vardKC + 1

    # Duke
    while not (vestige2 and axe2):
        rollTable = random.randint(1, 90)
        if rollTable == 1:
            rollUnique = random.randint(1, 8)
            if 1 <= rollUnique <= 3:
                vestigeCount2 = vestigeCount2 + 1
                if vestigeCount2 == 3:
                    vestige2 = True
            if 4 <= rollUnique <= 6:
                ingots = ingots + 1
            if rollUnique == 7:
                axe2 = True
        dukeKC = dukeKC + 1

    # Wisp
    while not (vestige3 and axe3):
        rollTable = random.randint(1, 64)
        if rollTable == 1:
            rollUnique = random.randint(1, 8)
            if 1 <= rollUnique <= 3:
                vestigeCount3 = vestigeCount3 + 1
                if vestigeCount3 == 3:
                    vestige3 = True
            if 4 <= rollUnique <= 6:
                ingots = ingots + 1
            if rollUnique == 7:
                axe3 = True
        wispKC = wispKC + 1

    # Levi
    while not (vestige4 and axe4):
        rollTable = random.randint(1, 96)
        if rollTable == 1:
            rollUnique = random.randint(1, 8)
            if 1 <= rollUnique <= 3:
                vestigeCount4 = vestigeCount4 + 1
                if vestigeCount4 == 3:
                    vestige4 = True
            if 4 <= rollUnique <= 6:
                ingots = ingots + 1
            if rollUnique == 7:
                axe4 = True
        leviKC = leviKC + 1

    # ingot check
    while ingots < 12:
        rollTable = random.randint(1, 64)
        if rollTable == 1:
            rollUnique = random.randint(1,8)
            if 1 <= rollUnique <= 3:
                ingots = ingots + 1
        wispKC = wispKC + 1

    vardKCavg = vardKCavg + vardKC
    dukeKCavg = dukeKCavg + dukeKC
    wispKCavg = wispKCavg + wispKC
    leviKCavg = leviKCavg + leviKC
    ingots = False
    vestige1 = False
    vestigeCount1 = 0
    vardKC = 0
    vestige2 = False
    vestigeCount2 = 0
    dukeKC = 0
    vestige3 = False
    vestigeCount3 = 0
    leviKC = 0
    vestige4 = False
    vestigeCount4 = 0
    wispKC = 0
    axe1 = False
    axe2 = False
    axe3 = False
    axe4 = False
    trialCount = trialCount + 1
    totalKC = 0
    print(trialCount)

print()
vardAvgCompletion = (vardKCavg / trialCount)
dukeAvgCompletion = (dukeKCavg / trialCount)
wispAvgCompletion = (wispKCavg / trialCount)
leviAvgCompletion = (leviKCavg / trialCount)
print("Average Completion Vard KC: " + str(vardAvgCompletion))
print("Average Completion Duke KC: " + str(dukeAvgCompletion))
print("Average Completion Wisp KC: " + str(wispAvgCompletion))
print("Average Completion Levi KC: " + str(leviAvgCompletion))
