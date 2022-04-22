#Sofia Cordero
#Final Project: Mad Libs Story Game

#All of the stories are blantantly borrowed from Mad Libs Books.
#The imported images are my own original drawings.

#Story One-Basketball Playoffs

from PIL import Image

def story_one():

        print("Basketball Playoffs")
        print(" ")

        #User inputs series of nouns, verbs, and adjectives to fill in the story.
        
        person_in_room=(input("Enter a person in the room: "))
        noun=(input("Enter a noun: "))
        adjective=(input("Enter an adjective: "))
        verb_past_tense=(input("Enter a past tense verb: "))
        plural_noun=(input("Enter a plural noun: "))
        plural_noun_2=(input("Enter a plural noun: "))
        number=(input("Enter a number: "))
        adjective_2=(input("Enter an adjective: "))
        adjective_3=(input("Enter an adjective: "))
        noun_2=(input("Enter a noun: "))
        exclamation=(input("Enter an exclamation: "))
        noun_3=(input("Enter a noun: "))
        person_in_room_2=(input("Enter another person in the room: "))
        noun_4=(input("Enter a noun: "))
        noun_5=(input("Enter a noun: "))
        number_2=(input("Enter a number: "))
        noun_6=(input("Enter a noun: "))
        noun_7=(input("Enter a noun: "))
        noun_8=(input("Enter a noun: "))
        print(" ")

        #Print story.

        part_one="Hi! This is {}, speaking to you from the broadcasting {} at the {} forum. In case you {} in late,".format(person_in_room, noun, adjective, verb_past_tense)
        part_two="the score between Los Angeles {} and the Boston {} is a squeaker, 141 to {}. This has been the".format(plural_noun, plural_noun_2, number)
        part_three="most {} game these {} eyes have seen in years. First, one team scores a {}, then {}!-the other".format(adjective_2, adjective_3, noun_2, exclamation)
        part_four="team comes right back. Okay. Time-out is over. Los Angeles brings in the ball mid-{}. {} dribbles".format(noun_3, person_in_room_2)
        part_five="down the {}, fakes the defedner out of his {} and shoots a {}-handed shot. It goes right through the".format(noun_4, noun_5, number_2)
        part_six="{}. He beat the {}! The game is over just as the {} goes off.".format(noun_6, noun_7, noun_8)
        print(part_one)
        print(part_two)
        print(part_three)
        print(part_four)
        print(part_five)
        print(part_six)
              
        print(" ")

        im1 = Image.open(r"basketball.jpg")

        im1.show()     

#Story Two-Amusement Parks
              
def story_two():
        
        print("Amusement Parks")
        print(" ")

        #User inputs series of nouns, verbs, and adjectives to fill in the story.
        
        noun=(input("Enter a noun: "))
        article_of_clothing=(input("Enter an article of clothing: "))
        adjective=(input("Enter an adjective: "))
        adjective_2=(input("Enter an adjective: "))
        noun_2=(input("Enter a noun: "))
        type_of_food=(input("Enter a type of food: "))
        noun_3=(input("Enter a noun: "))
        adjective_3=(input("Enter an adjective: "))
        type_of_food_2=(input("Enter a type of food: "))
        type_of_drink=(input("Enter a type of drink: "))
        body_part=(input("Enter a body part: "))
        plural_noun=(input("Enter a plural noun: "))
        plural_noun_2=(input("Enter a plural noun: "))
        animal=(input("Enter an animal: "))
        noun_4=(input("Enter a noun: "))
        print(" ")

        #Print story.
        
        part_one="An amusement park is always fun to visit on a hot summer {}. When you get there, you can wear your {} and go for a swim.".format(noun, article_of_clothing)
        part_two="There are lots of {} things to eat. You can start off with a/an {}-dog on a/an {} with mustard, relish, and {} on it".format(adjective, adjective_2, noun_2, type_of_food)
        part_three="Then you can have a buttered ear of {} with a nice {} slice of {} and a big bottle of cold {}. When you are full,".format(noun_3, adjective_3, type_of_food_2, type_of_drink)
        part_four="it's time to go on the roller coaster, which should settle your {}. Other amusementpark rides are the bumper cars,".format(body_part)
        part_five="which have little {} that you drive and run into other {}, and the merry-go-round, where you can sit on a big {} and".format(plural_noun, plural_noun_2, animal)
        part_six="try to grab the gold {} as you ride past it.".format(noun_4)
        print(part_one)
        print(part_two)
        print(part_three)
        print(part_four)
        print(part_five)
        print(part_six)

        print(" ")

        im2 = Image.open(r"amusementpark.jpg")

        im2.show()   

#Story Three-History of the Jelly Bean
        
def story_three():
        
        print("History of the Jelly Bean")
        print(" ")

        #User inputs series of nouns, verbs, and adjectives to fill in the story.
        
        adjective=(input("Enter an adjective: "))
        plural_noun=(input("Enter a plural noun: "))
        body_part=(input("Enter a plural part of the body: "))
        noun=(input("Enter a noun: "))
        plural_noun_2=(input("Enter a plural noun: "))
        number=(input("Enter a number: "))
        body_part_2=(input("Enter a plural part of the body: "))
        body_part_3=(input("Enter a plural part of the body: "))
        adjective_2=(input("Enter an adjective: "))
        noun_2=(input("Enter a noun: "))
        plural_noun_3=(input("Enter a plural noun: "))
        noun_3=(input("Enter a noun: "))
        adjective_3=(input("Enter an adjective: "))
        adjective_4=(input("Enter an adjective: "))
        print(" ")
        
        #Print story.

        part_one="Jelly beans aren't just Easter candy-they have a very long and {} history in the United {} of America, dating all the way".format(adjective, plural_noun)
        part_two="back to the 1800s. During the Civil War, Americans sent jelly beans to soilders to put smiles on their {}. In the early".format(body_part)
        part_three="1900s, 'penny candy'-sweets you could buy for just one {}-became all the rage, and jelly {} became more popular than".format(noun, plural_noun_2)
        part_four="ever. In the 1940s, during World War {}, a chocolate shortage led people to turn to jelly beans to satisfy their sweet".format(number)
        part_five="{}. By the 1960s, even rock stars were falling head over {} for the {} jelly beans. When fans of the famous musical {},".format(body_part_2, body_part_3, adjective_2, noun_2)
        part_six="the Beatles, heard the band liked the candy, they tossed {} onto the stage at their concerts. In the 1980s, President".format(plural_noun_3)
        part_seven="Reagan said he needed a/an {} full of jelly beans just to get through {} meetings. Some might say the United States".format(noun_3, adjective_3)
        part_eight="itself runs on delicious {} jelly beans!".format(adjective_4)
        print(part_one)
        print(part_two)
        print(part_three)
        print(part_four)
        print(part_five)
        print(part_six)
        print(part_seven)
        print(part_eight)
        
        print(" ")
        
        im3 = Image.open(r"jellybeans.jpg")

        im3.show()     

#Story Four-A Card from Camp
              
def story_four():
        
        print("A Card From Camp")
        print(" ")

        #User inputs series of nouns,x verbs, and adjectives to fill in the story.

        plural_noun=(input("Enter a plural noun: "))
        plural_noun_2=(input("Enter a plural noun: "))
        person_in_room=(input("Enter a person in the room: "))
        adjective=(input("Enter an adjective: "))
        noun=(input("Enter a noun: "))
        adjective_2=(input("Enter an adjective: "))
        verb=(input("Enter a verb: "))
        noun_2=(input("Enter a noun: "))
        article_of_clothing=(input("Enter a plural article of clothing: "))
        noun_3=(input("Enter a noun: "))
        plural_noun_3=(input("Enter a plural noun: "))
        noun_4=(input("Enter a noun: "))
        plural_noun_4=(input("Enter a plural noun: "))
        noun_5=(input("Enter a noun: "))
        adjective_3=(input("Enter an adjective: "))
        plural_noun_5=(input("Enter a plural noun: "))
        body_part=(input("Enter a part of the body: "))
        noun_6=(input("Enter a noun: "))
        person_in_room_2=(input("Enter a person in the room: "))
        print(" ")

        #Print story.
        part_one="Dear Folks,"
        part_two="Camp is great! I like all the {} in my tent. I have become as close as two {} in a pod with {}, who has a/an".format(plural_noun, plural_noun_2, person_in_room)
        part_three="{} personality and is never without a {}. He/she tells really {} stories which make all of us {} out loud.".format(adjective, noun, adjective_2, verb)
        part_four="I have to stop writing now. I know I promised a long {}, but this morning I washed my shirts and {}".format(noun_2, article_of_clothing)
        part_five="and put them out to dry on the clothes {}, and it looks like it's getting ready to rain cats and {}.".format(noun_3, plural_noun_3)
        part_six="I better get off my {} and get my {} off the {} line before I run out of {} underwear. I promise to".format(noun_4, plural_noun_4, noun_5, adjective_3)
        part_seven="write a letter full of {} before my {} hits the pillow tonight...or tomorrow...or maybe I'll".format(plural_noun_5, body_part)
        part_eight="write Tuesday."
        part_nine="Your loving {},".format(noun_6)
        part_ten=person_in_room_2

        print(part_two)
        print(part_three)
        print(part_four)
        print(part_five)
        print(part_six)
        print(part_seven)
        print(part_eight)
        print(part_nine)
        print(part_ten)
              
        print(" ")

        im4 = Image.open(r"summercamp.jpg")

        im4.show()   

#Table of Contents
              
done="";
while ((done!="no")or(done!="no")):
    print("Mad Libs Story Game:")
    print(" ")
    print("\"1\": Basketball Playoffs");
    print("\"2\": Amusement Parks");
    print("\"3\": History of the Jelly Bean");
    print("\"4\": A Card From Camp");
    print(" ")
    input_string=input("Please enter the number of the story you would like to chose: ");
    print(" ")

    if(input_string=="1"):
        story_one();
    elif(input_string=="2"):
        story_two();
    elif(input_string=="3"):
        story_three();
    elif(input_string=="4"):
        story_four();

    done=input("Would you like to chose another story? ")

                 
