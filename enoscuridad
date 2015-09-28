from sys import exit

def dead(why):
    print why, 
    print "Some things remain forever unfinished."
    print  "/     \\"
    print "| () () |"
    print "\\  ^  /"
    print "  |||||"
    print "  |||||"
    exit(0)

def end_credits():
    print "  "
    print "  "
    print "Congratulations! You have ascended."
    print "Rule this higher plain well and one day another path may become known."
    print "POTROS EN OSCURIDAD by Robert Norman and Eve Ahearn - September 2015"
    exit(0)

def all_alone():
    print "The new power still courses through you, but there is no one left to share it with."
    print "You have searched, but the disappearance or your new kin remains a mystery."
    print "You bathe in the sunlight and it feels glorious, but there is a sense that this is not the end for you."
    print "There is nothing left but to wait and to run."
    print "Until a greater power comes along, you are the only deity on this island."
    print "Until the next nightmare, you are young and wild and free."
    if 0==0:
        end_credits()

def running():
    print "You run to all corners of the island, but see no other signs of life."
    print "Keep running?"

    choice = raw_input("> ")

    if "run" in choice or "keep" in choice:
        running()
    else:
        all_alone()

def restless():
    print "Staying put does not feel right. Despite your wishes, you begin to run."
    if 0==0:
        all_alone()

def no_sleep():
    print "You shut your eyes, but sleep no longer comes. The soothing voice is gone from your mind."
    print "Wait for your kin to return or search for them?"

    choice = raw_input("> ")

    if "search" in choice or "centaur" in choice or "run" in choice:
        running()
    elif "wait" in choice:
        restless()
    else:
        restless()

def frolic_end():
    print "You take your fellow godling's hand and run with him."
    print "Power flows through every bit of you."
    print "The aching body that awoke on the dungeon floor is a distant memory that feels like a pitiful joke."
    print "Hours melt away in your new life, galloping."
    print "When you and your new kin lay down in a clearing to sleep, you feel only satisfation."
    print " "
    print "Your dreams are filled by a deep and throaty voice, it chants and whispers soft things to you,"
    print "YOUR WILL IS FOREVER MY WILL."
    print "You awake, still feeling elated, until you realize you are all alone."
    print "Search for your kin, or go back to sleep?"

    choice = raw_input("> ")

    if "search" in choice or "centaur" in choice or "run" in choice:
        running()
    elif "sleep" in choice:
        no_sleep()
    else:
        running()

def sapo_cave_end():
    print "Sapo's true form is revealed to in hideous glory."
    print "IF YOU HAD TRUSTED ME YOUR PATH TO GREATNESS WAS ENSURED."
    print "TO FALTER AT THE FINISH LINE IS STILL TO FAIL."
    print "Sapo's green light fills the cave."
    print "No action can stand in the way of his will."
    if 0==0:
        dead("Take solace in the knowledge that your mind has been destroyed. There is no memory of the horrible things done to you in this dark and lonely place.")

def uneasy_end():
    print "All of your instincts drove you here, but something about the Island of the Centaurs feels too good to be true."
    print "You turn down his hand and flee."
    print "You run all day, and your new body thrives in the sunlight, but your heart feels uneasy."
    print "As the sun goes down, you take shelter in a cave."
    print "You lay down, exhausted, and are about to close your eyes when you hear the throaty croak of a giant toad."
    print "Sapo, the giant glowing toad, illuminates the room. He appears to be angry."
    print "YOU HAVE IGNORED MY GIFT. ASCENSION IS GLORIOUS AND YOU HAVE SPIT UPON IT."
    print "A greater being's fury is about to be unleashed, what do you do?"

    choice = raw_input("> ")

    if "talk" in choice:
        sapo_cave_end()
    else:
        sapo_cave_end()

def centaur_talk():
    print "YOUR PAST LIFE WAS ONE STEP. TO TRY TO REMEMBER IS FUTILE AND AN AFFRONT TO YOUR ASCENSION."
    print "YOU HAVE FOLLOWED THE CORRECT PATH AND LEFT THE HUMAN COWARDS BEHIND."
    print "ONE DAY, MAYBE SOON, SAPO WILL CALL ON US, BUT UNTIL THAT DAY IT IS OUR DUTY TO BE YOUNG AND WILD AND FREE."
    print "THIS IS THE FIRST OF THE HIGHER PLAINS."
    print "RUN WITH ME IN THE SUNLIGHT?"
    print "He holds out his hand, do you join him?"

    choice = raw_input("> ")

    if "join" in choice or "run" in choice or "sunlight" in choice:
        frolic_end()
    else:
        uneasy_end()

def reach_island():
    print "As you swim, something changes. Your body feels stronger. All uncertainty melts away."
    print "It must have taken hours to reach the shore, but you are not tired when you first feel sand and rocks beneath your feet."
    print "Feet? Feet no longer. Your hooves knock against the ground."
    print "WELCOME, KIN, CONGRATULATIONS."
    print "The source of this voice is a lean, muscular man, whose torso ends in the body of a horse."
    print "As he extends his arms to you, you realize that you are not the human you set out as,"
    print "but have evolved to look just like this creature."
    print "Question the being, or run away?"

    choice = raw_input("> ")

    if "talk" in choice or "question" in choice:
        centaur_talk()
    else:
        uneasy_end()

def lost_in_ocean():
    print "Your natural navigational sense leaves you almost immediately after you refuse it."
    print "You swim for hours, and you begin to tire."
    print "The water no longer feels like a friendly place, and night is coming."
    if 0==0:
        dead("There is an even deeper darkness known only beneath the ocean. You have stumbled into an even more complete misery.") 

def enter_ocean():
    print "The water welcomes you."
    print "Swimming comes easily, and somewhere inside you feel the direction that you need to go."
    print "Respect your instincts, or head into the unknown?"

    choice = raw_input("> ")

    if "respect" in choice or "swim" in choice or "instinct" in choice:
        reach_island()
    else:
        lost_in_ocean()

def stampede_end2():
    print "Your hesitation does not sit well with the horses."
    print "As you look up at them, the kindness leaves their open eyes and is replaced with fire."
    print "One by one and then all together, they break free from the stone."
    print "Hooves clatter along the throne room floor."
    print "Before you are consumed by this stampede, you think to yourself,"
    if 0==0:
        dead("THIS WAS NOT THE GREATNESS RESERVED FOR ME.")

def by_trap_door():
    print "The horses urge you on. They plead with their eyes for you to escape."
    print "Make the jump? Or risk offending the ones you saved."

    choice = raw_input("> ")
    if "jump" in choice or "ocean" in choice or "swim" in choice:
        enter_ocean()
    else:
        stampede_end2()

def trap_door():
    print "The throne slides easily away."
    print "When the knob is pulled, the wooden door flings open, revealing a drop straight into a dark, whorling ocean."
    print "Do you make the jump, or remain?"

    choice = raw_input("> ")

    if "jump" in choice or "ocean" in choice or "swim" in choice:
        enter_ocean()
    else:
        by_trap_door()

def stampede_end():
    print "As soon as you touch the items of the ancient human king. A cold and traitorous feeling surges through you."
    print "You don his crown and pick up his scepter, then take a seat in his throne."
    print "As you look up at the horses, the kindness leaves their open eyes and is replaced with fire."
    print "One by one and then all together, they break free from the stone."
    print "Hooves clatter along the throne room floor."
    print "Before you are consumed by this stampede, you think to yourself,"
    if 0==0:
        dead("THIS WAS NOT THE GREATNESS RESERVED FOR ME.")

def throne_stay():
    print "The hundres of horses urge you on. To stay any longer is a waste of your potential."
    print "Act now."

    choice = raw_input("> ")   

    if "knob" in choice or "door" in choice:
        trap_door()
    elif "crown" in choice or "scepter" in choice or "leave" in choice or "hall" in choice:
        stampede_end()
    else:
        dead("Triumphant action requires a follow up. Wasting an opportunity is wasting a life. The horses kind eyes turn to fire. You are not what they hoped for. They descend.")

def end_of_reign():
    print "The bones crack beneath your feet."
    print "As you pulverize, the stone floor beneath you shudders and a wailing is emitted from these ancient bones."
    print "As you step upon the skull, you look up and see that all of the horses lining the walls have opened their eyes."
    print "They look on gratefully and smile."
    print "When you turn back to the throne you see that the the golden crown and scepter have fallen to the floor."
    print "You also see that the throne rests upon a wooden door with a knob."
    print "What do you do?"

    choice = raw_input("> ")

    if "open" in choice or "knob" in choice or "door" in choice:
        trap_door()
    elif "crown" in choice or "scepter" in choice or "leave" in choice or "hall" in choice:
        stampede_end()
    else:
        throne_stay()

def throne_end():
    print "As you turn to leave, you hear a clatter, then a creaking sound behind you."
    print "You turn to meet the noise, but it is too late."
    print "The king is no longer a skeleton, but a young and beautiful boy."
    print "He smiles at you from the other end of his extended scepter, which has been thrust through your torso."
    if 0==0:
        dead("A deep and throaty voice fills your mind, FOOL, it wails, THEY REIGN FOR ANOTHER GENERATION.")

def throne_end2():    
    print "While you remain worthless in the face of an important choice, the skeleton king stands."
    print "As he walks toward you, his flesh returns."
    print "A beautiful, handsomely clothed boy king stands before you. He pets your head with a firm, calm hand."
    print "SHHH, he says, reassuringly, before thrusting his scepter through your torso."
    if 0==0:
        dead("A deep and throaty voice fills your mind, FOOL, it wails, THEY REIGN FOR ANOTHER GENERATION.")

def throne_illuminated():
    print "You approach the throne."
    print "A terrible sight presents itself when you adjust your eyes to the shadows."
    print "The mounted heads of hundreds of horses line the walls."
    print "Their eyes have been sewn shut, their manes shorn."
    print "Humiliation is the point."
    print "Tears spring from your eyes and you become fixated on the dead and rotten king, still smiling in his throne."
    print "Fury builds with every step you take towards the throne."
    print "Do you symbolically crush the bones of this long dead monarch? Or turn back and leave this atrocity unaddressed?"

    choice = raw_input("> ")

    if "crush" in choice or "hit" in choice or "attack" in choice:
        end_of_reign()
    elif "back" in choice or "leave" in choice:
        throne_end()
    else:
        throne_end2()

def throne_indecision():
    print "Something is not right here."
    print "Leave or look for the source of your unrest."

    choice = raw_input("> ")

    if "investigate" in choice or "look" in choice or "throne" in choice:
        throne_illuminated()
    elif "leave" in choice or "back" in choice:
        past_giant()
    else:
        throne_indecision()

def throne_room():
    print "One enormous gilded throne sits across the door from you."
    print "A human skeleton rests in it, wearing crown and holding scepter."
    print "He is lit, but the rest of the room is covered in darkness."
    print "Investigate the room, or turn back?"

    choice = raw_input("> ")

    if "investigate" in choice or "look" in choice or "throne" in choice:
        throne_illuminated()
    elif "leave" in choice or "back" in choice:
        past_giant()
    else:
        throne_indecision()

def horrible_witnessing():
    print "Sapo spoke truthfully, this is more than your mind can take."
    print "This is not a predator and prey or even a massacre of human proportions."
    print "You watch as the lesser beings are enveloped into the Toad, fuel for a greater purpose."
    print "WHY?"
    print "You cry out,"
    print "LET ME HELP. LET ME KNOW YOUR POWER."
    print "Sapo licks his lips and sighs,"
    print "YOU WERE MEANT TO REACH, BUT THIS IS TOO FAR. I GRIEVE FOR YOUR POTENTIAL."
    print "You realize that you have offended order with your request, but feel no fear as the Great One approaches,"
    print "removes from you what he deems necessary."
    if 0==0:
        dead("This elation is a taste of what will never come.")

def ritual_room():
    print "A horrible slurping sound fills this room."
    print "Huddled around the room, paralyzed by fear, are a group of dirty, bruised humans."
    print "They have the same primitive and dangerous look of the band in that disgusting photograph."
    print "You had been hoping to run into anyone helpful, but this group immediately repulses you."
    print "You can tell immediately that they have nothing to offer you, hatred bubbles up from some well deep within you."
    print "You are so disgusted that it takes you a moment to recognize the source of their fear."
    print "A giant, glowing toad sits in the center of the room. His lips are bloody."
    print "I AM SAPO, LEAVE NOW OR LEARN MORE THAN YOU ARE CAPABLE OF UNDERSTANDING."

    choice = raw_input("> ")

    if "leave" in choice or "back" in choice:
        past_giant()
    else:
        horrible_witnessing()

def telescope_end():
    print "How long have you been looking, not searching?"
    print "The Earth sighs beneath you, a voice calls from somewhere behind you, but you cannot remove your eyes from the sight."
    print "YOU ARE NOT WHAT WE NEED."
    if 0==0:
        dead("Glimpsing greatness and realizing it are not one in the same.")

def telescope_vision():
    print "No adjustments are necessary."
    print "Your field of vision is full of wild horses running freely."
    print "Something about this sight is more than pleasant. Your skin tingles, burns, with desire."
    print "These horses, you need to run with them."
    print "They are close, reachable, you can tell."
    print "Gaze on, or leave this place and seek the real thing?"

    choice = raw_input("> ")

    if "gaze" in choice or "look" in choice or "telescope" in choice:
        telescope_end()
    else:
        past_giant()

def telescope_room():
    print "A stone room bathed in golden light,"
    print "empty except for a long golden telescope pointed down at a small circular window."
    print "Look through the telescope, or leave?"

    choice = raw_input("> ")

    if "gaze" in choice or "look" in choice or "telescope" in choice:
        telescope_vision()
    else:
        past_giant()

def past_giant():
    print "The corridor that had seemed to last forever ends suddenly."
    print "Three doors stand before you, helpfully labeled."
    print "Room 1 - Reserved for Ritual"
    print "Room 2 - For Looking Beyond"
    print "Room 3 - Throne Room"
    print "Which door do you open?"

    choice = raw_input("> ")

    if "1" in choice or "one" in choice or "ritual" in choice:
        ritual_room()
    elif "2" in choice or "two" in choice or "look" in choice or "beyond" in choice:
        telescope_room()
    elif "3" in choice or "three" in choice or "throne" in choice:
        throne_room()
    else:
        dead("There are moments for action and moments for pause. A chosen one knows the difference. Your path was begun but now it has ended.")    

def left_corridor():
    if 0==0:
        past_giant()

def sapo_appeal():
    print "The toad sighs at your apology."
    print "I AM SAPO, he says. YOU WILL KNOW OF ME SOON ENOUGH."
    print "OR PERHAPS YOU WON'T, BUT I HOLD OUT HOPE FOR YOU."
    print "DO NOT MISSTEP. IT IS A RULE THAT I DO NOT FORGIVE TWICE."
    print " "
    print "The toad belches like its earthly kin, but in this context it is frightful."
    print "Sapo leaps through the wall and you are left alone in the corridor."
    print "The trudging continues, but you watch your step."
    if 0==0:
        left_corridor()

def sapo_disgrace():    
    print "You plunge your heel into the toad's lumpen flesh."
    print "It sinks easily into the creature's abdomen."
    print "At first you are a satisfied exterminator, but you cannot stop the plunge."
    print "Cold amphibian skin rises up around your ankle and you sink even further."
    print "All attempts to dislodge your leg leave you feeling even more trapped."
    print "You feel the vibration run through your entire body as a deep and impossibly loud voice fills the corridor."
    print "MY NAME IS SAPO. WE WERE KIN IF YOU FOLLOWED THE PATH."
    print "ONCE YOU HAVE LOST YOUR WAY THE PATH IS CLOSED FOREVER."
    print "TODAY DOES NOT COME AGAIN."
    if 0==0:
        dead("A greater being has found you unworthy.")

def giant_end ():
    print "Idleness has no place on this path and one who watches another weep must be run through with cruelty."
    print "A deep and throaty voice rings through the corridor,"
    print "WE WERE WRONG, THIS IS NOT THE PATH FOR YOU,"
    print "before you feel something essential ripped from deep within you and watch the world go black."
    if 0==0:
        dead("Today was wasted.")

def giant_forever():
    print "You are nothing to this weeping giant. Everything you do will be ignored."
    print "Engaging again will be proof that you have nothing useful or original to add to this world."
    print "Turn back?"

    choice = raw_input("> ")

    if "back" in choice or "way" in choice:
        toad_room()
    else:
        giant_end()

def giant_weeps_again():
    print "It is as if you disappear. This giant is overwhelmed with grief."
    print "He sits again and your path remains blocked."
    print "The tears return."
    print "Turn back?"

    choice = raw_input("> ")

    if "back" in choice or "way" in choice:
        toad_room()
    else:
        giant_forever()

def giant_boredom_end():
    print "The weeping giant lights up immediately as soon as you agree to hear him out."
    print "He begins at Appendix i, and almost immediately you realize your mistake."
    print "The list of rules and regulations for this hallway has been in constant compilation for millenia and fills countless volumes."
    print "One who lights his one way has no need for the guidelines of others, you think to yourself as you realize your fate."
    print "Your mind drifts into a soft smooth gray area at the start of Volume VI, and never returns."
    if 0==0:
        dead("For you, this conversation will literally never end.")

def giant_explain():        
    print "IT'S MY JOB, MY DUTY, IT ALWAYS HAS BEEN, TO MONITOR THE HALL AND KEEP OUT INTRUDERS, BUT NOBODY HAS EVER COME UNTIL TODAY."
    print "TODAY THE HALL IS ALL FULL OF THE TINY CREATURES AND NOT ONE HAS LISTENED TO ME."
    print "THERE ARE A NUMBER OF RULES AND REGULATIONS TO FOLLOW ONCE YOU GET PAST ME."
    print "THEY'LL ALL BE LOST FOREVER WITHOUT HEARING MY PRESENTATION."
    print "THE THOUGHT OF ETERNAL DARKNESS FOR ANYONE MAKES ME SO SAD."
    print "YOU'LL LISTEN TO ME, WON'T YOU?"
    print "The enormous creature leans in even closer to you. He pleads with his glistening eyes."
    print "Do you agree to listen, or say no and push past?"

    choice = raw_input("> ")

    if "yes" in choice or "agree" in choice or "listen" in choice:
        giant_boredom_end()
    elif "no" in choice or "push" in choice or "run" in choice:
        past_giant()
    else:
        dead("The giant senses your condescension. In a fit of self pity, he flings himself down. Your life is snuffed between him and the floor.")    

def giant_murder():
    print "Your second strike ends this large and pitiful life."
    print "Your hands burn hot. It is not entirely pleasant."
    print "You step over the corpse of the murdered giant"
    if 0==0:
        past_giant()

def run_past():
    print "You clamber over his shivering frame."
    print "The creature is too large to turn around and give chase, you continue to flee."
    if 0==0:
        past_giant()

def giant_blow():
    print "At your strike, the weeping giant howls in pain."
    print "As you reach for strength, so it comes to you."
    print "Imposing your will on another gives your hands a warm glow. Perhaps this was something you did before the dungeon."
    print "Perhaps this sensation is memory."
    print "Do you hit him again or run past while he nurses his wound?"

    choice = raw_input("> ")

    if "hit" in choice or "attack" in choice or "again" in choice:
        giant_murder()
    elif "run" in choice or "push" in choice or "past" in choice:
        run_past()
    else:
        dead("There are moments for action and moments for pause. A chosen one knows the difference. Your path was begun but now it has ended.")

def giant_announce():
    print "You do not know your own name, so instead you call out IT IS I, I AM HERE."
    print "The weeping giant springs to his feet. He is too tall to stand up straight, so he presses his back up against the ceiling."
    print "The giant bellows NOBODY IS SUPPOSED TO COME THROUGH HERE! LEAVE ME ALONE!"
    print "The giant is manic. Action is necessary."
    print "Do you ask him why he is crying or attack?"

    choice = raw_input("> ")

    if "ask" in choice or "talk" in choice:
        giant_explain()
    elif "attack" in choice or "hit" in choice:
        giant_blow()
    else:
        giant_weeps_again()

def giant_tear():
    print "One of the giant's tears is flung from his face to yours."
    print "You are knocked back, humbled further, and left with the same choice."
    print "Announce yourself or act physically."

    choice = raw_input("> ")

    if "announce" in choice or "talk" in choice:
        giant_announce()
    elif "poke" in choice or "touch" in choice or "attack" in choice or "act" in choice:
        giant_blow()
    else:
        giant_tear()             

def weeping_giant():
    print "You head down the hall that lies to the left."
    print "Measurement is impossible but it feels like this carpet must stretch for miles."
    print "Your eyes droop closed as you trudge along."
    print "You are startled from your slumber when you bounce off of a thick and hairy shin."
    print "A weeping giant sits before you, blocking your path."
    print "Do you announce yourself or touch him?"

    choice = raw_input("> ")

    if "touch" in choice or "poke" in choice or "attack" in choice:
        giant_blow() 
    elif "announce" in choice or "talk" in choice:
        giant_announce()
    else:
        giant_tear()        

def toad_room():
    print "You head down the hall that lies to the left."
    print "Measurement is impossible but it feels like this carpet must stretch for miles."
    print "Your eyes droop closed as you trudge along."
    print "The moment is coming when you may trudge no longer when your feet lands on something soft."
    print "With a squelch."
    print "The largest toad you have ever seen looks up with intelligent eyes."
    print "Do you apologize to this strange and exceptional animal?"
    print "Or attack and extinguish the vile and slimy creature?"

    choice = raw_input("> ")

    if "apologize" in choice or "talk" in choice:
        sapo_appeal()
    elif "attack" in choice or "extinguish" in choice:
        sapo_disgrace()
    else:
        dead("The toad blinks and you feel something essential sucked out from deep within you. Your lack of action has offended a higher power. You could continue, but why bother? Appeals to greater authority would be moot and are impossible.")

def attic_return():
    print "In the room there is another window and tall stone walls."
    print "Investigate or descend?"

    choice = raw_input("> ")

    if "investigate" in choice or "look" in choice or "wall" in choice:
        inscription()
    elif "descend" in choice or "ladder" in choice:
        hallway_fork()
    elif "jump" in choice:
        dead("This is not your intended path, but something within you stirs anyway. You are winged now. The ocean is forever and you are above it.")    

def inscription():
    print "You run your hands along the stone wall and find a description"
    print "NIHIL LIBEROS CORDE NOBILIOR NIHIL HOMINIS."
    print "But HOMINIS is crossed out and replaced underneath by EQUO"
    print "And again, EQUO is slashed through and replaced by RUBETA."
    print "You don't read Latin, but understand significance when it is placed before you."
    print "You ponder while looking out the other window. There is no island here."
    print "The ocean stretches beyond imagination."
    print "Descend?"

    choice = raw_input("> ")

    if "descend" in choice or "ladder" in choice:
        hallway_fork()
    else:
        attic_return()

def attic(): 
    print "The ladder's rungs are gold and warm."
    print "Your climb is comfortable, natural, and you ascend toward a small and terribly bright circle of light."
    print "The landing you reach is at the top of a spire and bathed in golden light."
    print "You look out from one of the windows available and discover that this structure borders a body of water."
    print "Nearby is an island with nothing built upon it, inhabited by what appear to be horses from here."
    print "The island is a swimmable distance is your first though."
    print "Perhaps you were an athlete? Perhaps this is a competition?"
    print "In the room there is another window and tall stone walls."
    print "Investigate or descend?"

    choice = raw_input("> ")

    if "investigate" in choice or "look" in choice or "wall" in choice:
        inscription()
    elif "descend" in choice or "ladder" in choice:
        hallway_fork()
    elif "jump" in choice:
        dead("This is not your intended path, but something within you stirs anyway. You are winged. The ocean is forever and you are above it.")    

def ladder_descends():
    print "Rarely does indecision lead to reward. Who knows if this is an exception."
    print "Climb, head left, or head right."

    choice = raw_input("> ")

    if "right" in choice:
        weeping_giant()
    elif "left" in choice:
        toad_room()
    elif "climb" in choice or "ladder" in choice:
        attic()
    else:
        dead("Choices are required for adventure. Nothing is guaranteed. You take no chances and so you suffer in uncertainty.")

def hallway_fork():
    print "The hallway splits."
    print "A bright glimmer of light shines from up above," 
    print "but both paths lead off into burgundy darkness beyond the limits of your sight."
    print "Head left or head right."

    choice = raw_input("> ")

    if "right" in choice:
        weeping_giant()
    elif "left" in choice:
        toad_room()
    else:
        print "A gilded ladder descends from the ceiling."
        ladder_descends()

def screaming_urge():
    print "Howls in a language you don't remember understanding carom down the hall and call you toward them."
    print "There is no choice but to move forward."
    if 0==0:
        hallway_fork()

def shy_portraits():
    print "Paintings of royalty that wear a crest you are unfamiliar with line the walls."
    print "It's true that now you remember nothing, but this symbol is beyond even what you have forgotten."
    print "As you walk by, the likenesses of these kings and queens of the realm turn their painted heads to avoid your gaze."
    print "At first, you think it must be an optical illusion, but when you look closer, it is true, they break the agreed upon rules of art and observer to avert their eyes."
    print " "
    print "All but the orgiastic subjects of a final scene. Nude peasants slip on wine and bloodied marble, gorging themselves on earth or excrement."
    print "They dance around a disemboweled horse. This was once a mighty steed. His eyes shine with a lonely intelligence."
    print "These people appear to be mocking the animal, to look up and mock you as well."
    print "It is a filthy sight that fills you with rage for reasons you do not yet understand."
    print "Before you know it, you are gouging out pieces of canvas with your thumb. Poking out the heads and mutilating the bodies of these lesser beings."
    print "VIOLENCE COMES EASILY TO ME, is a thought that crosses your mind."
    print "You have reached the end of the hallway."
    if 0==0:
        hallway_fork()  

def opulent_hallway():
    print "The door grinds and falls away as if it were old and ruined, but you see no signs of rust."
    print "Things continue senselessly."
    print "This is the hall of a king carpeted thick and red, adorned with golden sconces."
    print "It should not be leading from or towards a dungeon,"
    print "but as you turn to look where you have come from, you see that it no longer does."
    print "There is nothing to do but head down the hall or search its walls for clues."

    choice = raw_input("> ")

    if "look" in choice or "clue" in choice:
        shy_portraits()
    elif "hall" in choice or "walk" in choice:
        hallway_fork()
    else:
        screaming_urge()

def door_approach():
    print "Voices. Human ones, you think."
    print "You step closer."
    print "What seemed like whispers become distant moans, wails."
    print "You were certain you recognized something there, in that sound, but now?"
    print "HELP."
    print "You would like to, but this door stands in the way. You are frail, tired, there is no way it could possibly budge."
    print "Do you try anyway?"

    choice = raw_input("> ")

    if "push" in choice or "try" in choice or "pull" in choice:
        opulent_hallway()
    else:
        dead("Choices are required for adventure. Nothing is guaranteed. You take no chances and so you suffer in uncertainty.")

def rat_nudge():
    print "Teeth touch your ankle."
    print "Pain is your only memory."

    choice = raw_input("> ")

    if "door" in choice:
        door_approach()
    else:
        dead("To test danger once in this world can be more than enough. One creature lacked patience and you are no more.")    

def first_dungeon():
    print "This world is barely brighter than the one beneath your eyelids."
    print "Bit by bit you make out your prison."
    print "Dank and hopeless, light is unknown here. Memory evades you. Nothing makes sense."
    print "The only sign of an outside world is one iron door, padlocked, impossibly thick, across the room."
    print "If you do not move this room may be your forever."
    print "Approach the door or push to remember?"

    choice = raw_input("> ")   

    if "door" in choice or "approach" in choice:
        door_approach()
    elif "remember" in choice:
        print "Your thoughts get nowhere before you hear a scraping beneath you."
        rat_nudge()
    else:
        print "It seemed as though nothing could live down here, but something slides along your feet."
        print "There is still only one exit."
        rat_nudge()

def first_end():
    print "You shut your eyes even tighter."
    print "Sleep comes, but slowly." 
    print "It will be forever fitful. You dream of unrealized power."
    print "Potential burns, wasted, hot, deep inside your heart."
    if 0==0:
        dead("Today will never come again.")


def start():
    print "Welcome to the world of Los Potros en Oscuridad."
    print "Survive. Ascend. You Must."
    print " "
    print " "
    print "Enter AWAKEN to proceed."

    choice = raw_input("> ")

    if "awaken" in choice:
        dungeon()
    else:
        dungeon()

def dungeon():
    print "Consciousness comes suddenly, you are awake before your eyes can open."
    print "Your body aches. Uneven stone pushes painfully against your back."
    print "Drops of some foul-smelling liquid drip from above and land around you, on your face."
    print "Do you open your eyes or push your body back into sleep?"

    choice = raw_input("> ")

    if "open" in choice:
        first_dungeon()
    elif "sleep" in choice:
        first_end()
    else:
        print "A scream, from down the corridor or somewhere within your own mind, forces your eyes open"
        first_dungeon()


start()
