# Mad-libs

"""

"""

# The template for the story

STORY = "This morning %s woke up feeling %s. 'It is going to be a %s day!' Outside, a bunch of %s were protesting to keep %s in stores. They began to %s to the rhythm of the %s, which made all the %s very %s. Concerned, %s texted %s, who flew %s to %s and dropped %s in a puddle of frozen %s. %s woke up in the year %s, in a world where %s ruled the world."

print "Mad Libs has started!"
name = raw_input("Enter a name:")
adj1 = raw_input("Name first adjective:")
adj2 = raw_input("Name second adjective:")
adj3 = raw_input("Name third adjective:")
verb = raw_input('State one verb:')
noun1 = raw_input("Input first noun:")
noun2 = raw_input("Input second noun:")
animal = raw_input("Name an animal:")
food = raw_input("Name an food:")
fruit = raw_input("Name an fruit:")
superhero = raw_input("Name an superhero:")
country = raw_input("Name an country:")
dessert = raw_input("Name an dessert:")
year = raw_input("Name an year:")
print STORY % (name, adj1, adj2, animal, food, verb, noun1, fruit, adj3, name, superhero, name, country, name, dessert, name, year, noun2)
